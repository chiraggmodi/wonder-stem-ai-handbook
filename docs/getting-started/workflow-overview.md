# Workflow Overview

Wonder STEM Factory is a sequential AI production pipeline.

Each workflow produces an artifact.

The artifact becomes the input for the next workflow.

```text
Topic Assessment
        │
        ▼
Research Brief
        │
        ▼
Blueprint
        │
        ▼
Draft Script
        │
        ▼
Verification
        │
        ▼
Audit
        │
        ▼
Revision
        │
        ▼
Thumbnail
        │
        ▼
Production Manifest
        │
        ▼
Publishing
```

---

## Why multiple workflows?

Instead of asking AI to do everything at once:

```
Write me a YouTube video.
```

Wonder STEM divides work into specialized stages.

Benefits:

- Better quality
- Easier debugging
- Reusable outputs
- Consistent formatting
- Easier verification

---

## Inputs and Outputs

Every workflow follows the same pattern.

Input

↓

Processing

↓

Artifact

↓

Next Workflow

---

## Workflow Categories

### Research

Collects information.

---

### Planning

Structures content.

---

### Writing

Creates educational scripts.

---

### Verification

Checks scientific accuracy.

---

### Production

Creates publishing assets.

---

### Publishing

Generates metadata and upload packages.

---

## Human Review

The workflow intentionally pauses after important milestones.

Typical approval gates include:

- Research approval
- Script approval
- Verification approval
- Production approval

This prevents incorrect information from reaching the final publication.