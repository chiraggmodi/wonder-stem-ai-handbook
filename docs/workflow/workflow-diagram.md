# Workflow Diagram

The following diagram illustrates how content flows through the Wonder STEM pipeline.

## Complete Pipeline

```text
                    ┌───────────────┐
                    │ Topic / Idea  │
                    └───────┬───────┘
                            │
                            ▼
                  ┌──────────────────┐
                  │ Research Gem     │
                  └────────┬─────────┘
                           │
                           ▼
               ┌────────────────────────┐
               │ Topic Evaluation Gem   │
               └────────┬───────────────┘
                        │
                        ▼
                ┌──────────────────┐
                │ Outline Generator│
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Script Generator │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Fact Checker     │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Visual Planner   │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Publishing Gem   │
                └────────┬─────────┘
                         │
                         ▼
                 Final Educational Assets
```

---

## Error Recovery

If any stage fails:

```text
Research ✓
Evaluation ✓
Outline ✓
Script ✗

Retry Script Only
```

There is no need to restart the entire workflow.

---

## Advantages

* Independent execution
* Smaller prompts
* Easier debugging
* Better scalability
* Reduced token usage
* Faster retries
* Higher reliability

This modular architecture is the foundation of the Wonder STEM AI Handbook and is applicable to educational content generation as well as many other AI-driven workflows.
