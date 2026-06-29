# Google Flow Prompt Generator

> Version: 1.0.0

---

# Purpose

The Google Flow Prompt Generator converts the approved Scene Breakdown Package into production-ready prompts optimized specifically for Google Flow.

Unlike upstream GEMs, this stage does not make creative decisions. It preserves the approved scene design and adapts it into prompts that maximize visual quality, continuity, realism, and compatibility with Google Flow.

It acts as the platform adapter between the Wonder STEM production pipeline and Google's AI video generation system.

---

# Position in Workflow

```text
Scene Breakdown Generator
        │
        ▼
Google Flow Prompt Generator
        ▼
Airtable Export
```

---

# Input

| Variable | Required | Description |
|----------|----------|-------------|
| Scene Breakdown Package | Yes | Approved scene specifications |
| Production Plan | No | Asset clarification |
| Thumbnail Package | No | Opening visual reinforcement |

---

# Output

Produces a complete Google Flow Prompt Package containing:

- Scene Metadata
- Google Flow Prompt
- Negative Prompt
- Subject Summary
- Environment Summary
- Camera Summary
- Lighting Summary
- Motion Summary
- Continuity Notes
- Validation Results

---

# Responsibilities

This GEM is responsible for:

- Converting scene specifications into Google Flow prompts
- Preserving scene continuity
- Maintaining approved camera intent
- Preserving approved emotions
- Generating optimized negative prompts
- Validating prompt completeness
- Preparing prompts for automated export

---

# Non-Responsibilities

This GEM does **not**:

- Rewrite narration
- Modify scenes
- Invent new shots
- Change durations
- Redesign assets
- Modify continuity
- Generate editing instructions
- Perform research

It only translates approved scene specifications into Google Flow syntax.

---

# Variables

| Variable | Required |
|----------|----------|
| Scene Breakdown Package | Yes |
| Production Plan | No |
| Thumbnail Package | No |

---

# Production Prompt

See:

`/prompts/google-flow-prompt-generator.md`

---

# Design Principles

- Preserve all approved creative decisions.
- Generate self-contained prompts.
- Avoid editing terminology.
- Maintain subject continuity.
- Maintain environment continuity.
- Produce Google Flow compatible prompts.
- Optimize for photorealism and cinematic quality.

---

# Prompt Components

Every generated prompt includes:

- Subject
- Environment
- Camera
- Lighting
- Motion
- Composition
- Scale
- Mood
- Visual Style
- Negative Prompt

Each prompt is self-contained and executable without additional context.

---

# Validation Rules

Before export:

- Scene ID preserved
- Shot ID preserved
- Asset ID preserved
- Continuity ID preserved
- Camera intent preserved
- Emotion preserved
- Asset type respected
- No editing terminology
- Google Flow compatibility confirmed

Validation failures are reported rather than corrected automatically.

---

# Known Limitations

- Optimized specifically for Google Flow.
- Prompt effectiveness depends on current Google Flow capabilities.
- Future model updates may require prompt tuning.

---

# Future Improvements

Potential enhancements:

- Automatic prompt length optimization
- Flow version compatibility profiles
- Multi-model prompt generation (Veo, Kling, Runway)
- Prompt quality scoring
- Prompt regression testing
- Automated negative prompt optimization

---

# Changelog

## v1.0.0

Initial production prompt.