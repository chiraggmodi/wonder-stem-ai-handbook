# Revised Script

> Version: 1.0.0

---

# Purpose

The Revised Script GEM is the final editorial integration stage of the Wonder STEM content pipeline.

Its responsibility is to apply approved corrections from the Verification Report and Audit Report while preserving the original Draft Script as much as possible.

Unlike previous GEMs, this stage does **not** generate new ideas, perform research, or redesign the story. It acts as a precision editor, ensuring that only justified changes are incorporated into the final production-ready script.

---

# Position in Workflow

```text
Draft Script
      │
      ├──────────────┐
      ▼              ▼
Verification Report  Audit Report
      │              │
      └──────┬───────┘
             ▼
       Revised Script
             ▼
     Production Planner
```

---

# Input

| Variable | Required | Description |
|----------|----------|-------------|
| Draft Script | Yes | Original narration-ready script |
| Verification Report | Yes | Scientific corrections and verification findings |
| Audit Report | Yes | Editorial, retention, and storytelling improvements |
| Explicit Replacement Dictionary | Optional | Pre-approved wording replacements |

---

# Output

Produces a complete Revision Package containing:

- Revision Summary
- Change Log
- Final Approved Script

The output is intended to become the canonical production script for downstream production assets.

---

# Responsibilities

This GEM is responsible for:

- Applying approved scientific corrections
- Integrating editorial improvements
- Preserving unaffected script content
- Maintaining narrative continuity
- Producing a complete production-ready script
- Tracking every applied and rejected change
- Ensuring alignment between the change log and the final script

---

# Non-Responsibilities

This GEM does **not**:

- Perform new research
- Invent scientific facts
- Redesign the story
- Add new narrative sections
- Improve creativity beyond approved recommendations
- Rewrite unaffected portions of the script

Its role is precision revision only.

---

# Variables

| Variable | Required |
|----------|----------|
| Draft Script | Yes |
| Verification Report | Yes |
| Audit Report | Yes |
| Explicit Replacement Dictionary | No |

---

# Production Prompt

See:

`/prompts/revised-script.md`

---

# Design Principles

- The Draft Script is the primary source of truth.
- Scientific corrections always take precedence.
- Preserve as much original wording as possible.
- Every applied finding must appear in the final script.
- Every finding must be tracked.
- Prefer local edits over complete rewrites.
- Produce a publication-ready script.

---

# Revision Priority

When conflicts occur:

1. Verification Report
2. Audit Report
3. Draft Script

Scientific integrity always overrides stylistic preferences.

---

# Quality Gates

Before a script is considered complete, it must satisfy:

- Scientific Integrity
- Clarity
- Retention
- Storytelling
- Change Log ↔ Final Script consistency

A failed quality gate requires another revision cycle.

---

# Known Limitations

- Cannot resolve conflicting audit recommendations without predefined priority rules.
- Revision quality depends on the quality of the Verification Report and Audit Report.
- Human editorial review is recommended before publication.

---

# Future Improvements

Potential enhancements:

- Automated diff generation
- Side-by-side revision comparison
- Readability regression analysis
- Change impact scoring
- Approval workflow integration

---

# Changelog

## v1.0.0

Initial production prompt.