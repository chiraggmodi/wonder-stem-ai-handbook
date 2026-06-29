# Workflow Overview

The Wonder STEM workflow is designed as a modular pipeline where each stage performs a single well-defined task.

Rather than relying on one large prompt, every phase of content generation is isolated, making the system more reliable and easier to maintain.

---

## Workflow

```text
Idea
 │
 ▼
Research
 │
 ▼
Topic Evaluation
 │
 ▼
Outline
 │
 ▼
Script
 │
 ▼
Fact Check
 │
 ▼
Visual Planning
 │
 ▼
Publishing Assets
```

---

## Why Modular?

Large prompts often suffer from:

* Empty responses
* Context overflow
* Token limits
* Formatting inconsistencies
* Difficult debugging

A modular workflow reduces these risks by allowing each stage to be executed independently.

---

## Workflow Principles

### Single Responsibility

Each stage performs one task only.

### Clear Interfaces

Every stage receives structured input and produces structured output.

### Recoverability

If a stage fails, only that stage needs to be rerun.

### Reusability

Outputs can be reused by other workflows or AI models.

---

## Benefits

* Better output quality
* Lower token consumption
* Easier maintenance
* Faster iterations
* Consistent formatting
* Simplified testing
