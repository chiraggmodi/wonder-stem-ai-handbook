# Scene Breakdown Generator

> Version: 1.0.0

---

# Purpose

The Scene Breakdown Generator transforms the approved Production Plan into a structured, platform-agnostic scene specification.

Rather than creating new creative assets, this GEM organizes approved narration, production assets, timing, and continuity into executable scenes that downstream AI video generators can consume.

Its output serves as the canonical scene specification for all supported video generation platforms.

---

# Position in Workflow

```text
Production Planner
        │
        ▼
Scene Breakdown Generator
        ▼
Google Flow Prompt Generator
```

---

# Input

| Variable | Required | Description |
|----------|----------|-------------|
| Production Plan | Yes | Approved production blueprint |
| Revised Script | Yes | Final narration |
| Thumbnail Package | No | Opening visual direction |
| Blueprint Handoff | No | Storytelling reference |

---

# Output

Produces a Scene Breakdown Package containing:

- Scene Specifications
- Shot Assignments
- Asset References
- Timing
- Continuity IDs
- Camera Intent
- Visual Goals
- Motion Requirements
- Validation Report

---

# Responsibilities

This GEM is responsible for:

- Breaking the production into executable scenes
- Mapping narration to scenes
- Preserving approved timing
- Maintaining visual continuity
- Assigning approved Asset IDs
- Defining camera intent
- Defining visual goals
- Preparing platform-agnostic scene specifications

---

# Non-Responsibilities

This GEM does **not**:

- Rewrite narration
- Modify scene order
- Create new assets
- Generate AI prompts
- Perform editing
- Perform research
- Modify production strategy

Its role is structural decomposition only.

---

# Variables

| Variable | Required |
|----------|----------|
| Production Plan | Yes |
| Revised Script | Yes |
| Thumbnail Package | No |
| Blueprint Handoff | No |

---

# Production Prompt

See:

`/prompts/scene-breakdown.md`

---

# Design Principles

- One narration line belongs to exactly one scene.
- Every scene references approved assets.
- Every scene preserves approved timing.
- Scenes remain platform-agnostic.
- Continuity is explicit rather than implied.
- Downstream generators should not infer missing information.

---

# Continuity Management

Every recurring subject receives a Continuity ID.

Examples:

- EARTH_001
- MOON_001
- SUN_001
- DNA_001
- SATELLITE_001

Continuity IDs ensure visual consistency across scenes regardless of the downstream rendering platform.

---

# Validation Rules

Before publishing the Scene Breakdown Package:

- Every narration line appears exactly once.
- Every Asset ID exists in the Production Plan.
- Every scene has exactly one Asset Type.
- Every scene has one Camera Intent.
- Every scene has one Continuity ID.
- Every scene has one Visual Goal.
- No scene exceeds approved duration.

Validation failures must be reported rather than silently corrected.

---

# Known Limitations

- Scene quality depends on the completeness of the Production Plan.
- Continuity assumes upstream asset consistency.
- Does not optimize for platform-specific rendering constraints.

---

# Future Improvements

Potential enhancements:

- Automatic continuity graph generation
- Shot dependency visualization
- Scene complexity scoring
- Asset reuse optimization
- Multi-platform scene variants
- Timeline export support

---

# Changelog

## v1.0.0

Initial production prompt.