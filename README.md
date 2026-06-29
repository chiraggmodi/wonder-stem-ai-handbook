# Wonder STEM AI Handbook

> A production-ready AI content generation framework for building reliable, multi-stage educational content pipelines using Gemini Gems.

---

## Overview

Wonder STEM AI Handbook is a collection of prompts, workflows, templates, and best practices for creating high-quality STEM educational content with Gemini.

The project focuses on solving one of the biggest challenges when working with Large Language Models:

> **Long prompts eventually fail.**

Instead of relying on a single massive prompt, this project breaks complex work into independent stages that can recover gracefully when failures occur.

---

# Why This Exists

During development we encountered several issues with Gemini Gems:

- Empty responses
- Context overflow
- Token exhaustion
- Inconsistent formatting
- Random stopping
- Lost outputs after long generations

Rather than making prompts even larger, this repository introduces a modular pipeline architecture.

---

# Core Principles

- Modular prompts
- Small context windows
- Stage isolation
- Recoverable workflows
- Reusable prompt libraries
- Human review checkpoints
- Version controlled prompts

---

# Architecture

```
Research
      │
      ▼
Topic Evaluation
      │
      ▼
Outline Generation
      │
      ▼
Script Writing
      │
      ▼
Fact Checking
      │
      ▼
Visual Planning
      │
      ▼
Thumbnail Ideas
      │
      ▼
Publishing Assets
```

Every stage is independent.

If Gemini fails, only that stage needs to be rerun.

---

# Repository Structure

```
wonder-stem-ai-handbook/

README.md
CHANGELOG.md

docs/
    architecture.md
    workflow.md
    best-practices.md

gems/
    research/
    evaluation/
    outline/
    script/
    visual/
    publishing/

prompts/
    reusable/
    system/
    templates/

examples/
    sample-topics/
    generated-content/

templates/
    markdown/
    airtable/
    youtube/

assets/
```

---

# Features

- Gemini Gems prompt collection
- Modular workflow
- Recovery-friendly architecture
- Prompt versioning
- Standardized output formats
- Markdown-first documentation
- Educational content pipeline

---

# Workflow

1. Select topic
2. Evaluate virality
3. Generate research
4. Build outline
5. Expand into script
6. Fact check
7. Generate visuals
8. Produce publishing assets

---

# Design Philosophy

Instead of asking Gemini to create everything in one prompt:

❌

```
Topic
→ Research
→ Script
→ Visuals
→ Thumbnail
→ Metadata
→ Shorts
```

Use:

✅

```
Research
↓

Outline
↓

Script
↓

Review
↓

Visuals
↓

Publishing
```

Small prompts are:

- Faster
- More reliable
- Easier to debug
- Easier to improve

---

# Handling Gemini Empty Responses

When Gemini returns an empty response:

- Do not restart the entire workflow.
- Restart only the failed stage.
- Preserve outputs from previous stages.
- Keep prompts under manageable size.
- Avoid unnecessary context accumulation.

---

# Best Practices

- Keep prompts focused.
- Avoid chaining too many tasks together.
- Save outputs after every stage.
- Use structured Markdown.
- Version prompts.
- Separate reusable instructions from task-specific prompts.

---

# Future Roadmap

- Prompt testing framework
- Automated regression testing
- Multi-model support
- NotebookLM integration
- Flow integration
- Airtable integration
- Prompt analytics
- Quality scoring

---

# Contributing

Contributions are welcome.

Please submit:

- new prompts
- workflow improvements
- bug fixes
- documentation enhancements

---

# License

MIT