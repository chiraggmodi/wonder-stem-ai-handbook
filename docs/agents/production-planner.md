# Production Planner

> Version: 1.0.0

---

# Purpose

The Production Planner converts the approved Wonder STEM content package into a complete production blueprint that can be executed by AI generation tools and video editors.

It bridges creative planning and asset production by defining scenes, storyboards, production assets, AI generation prompts, editing instructions, and production order.

This GEM ensures every narration segment has a corresponding visual strategy while optimizing production efficiency and educational impact.

---

# Position in Workflow

```text
Revised Script
        │
Thumbnail & Title Package
        │
        ▼
Production Planner
        ▼
Scene Breakdown
```

---

# Input

| Variable | Required | Description |
|----------|----------|-------------|
| Revised Script | Yes | Final approved production script |
| Thumbnail & Title Package | Yes | Winning title and thumbnail package |
| Blueprint Handoff | Optional | Story structure reference |
| Research Brief | Optional | Scientific clarification reference |

---

# Output

Produces a complete Production Planning Package containing:

- Production Overview
- Scene Breakdown
- Visual Storyboard
- Asset Production Plan
- Line-by-Line Shot List
- Flow Readiness Check
- Image Generation Prompts
- Video Generation Prompts
- Motion Graphics Plan
- Shot Generator Handoff
- Sound Design Plan
- Editing Instructions
- Production Complexity Estimate
- Asset Priority Matrix
- Render Order

---

# Responsibilities

This GEM is responsible for:

- Planning production workflow
- Designing visual storyboards
- Mapping narration to visuals
- Defining production assets
- Creating AI generation prompts
- Preparing Google Flow Shot Generator assets
- Estimating production complexity
- Optimizing production efficiency

---

# Non-Responsibilities

This GEM does **not**:

- Rewrite narration
- Change educational content
- Modify scientific explanations
- Optimize titles
- Design thumbnails
- Perform research
- Verify scientific claims

It operates exclusively on approved workflow artifacts.

---

# Variables

| Variable | Required |
|----------|----------|
| Revised Script | Yes |
| Thumbnail & Title Package | Yes |
| Blueprint Handoff | No |
| Research Brief | No |

---

# Production Prompt

See:

`/prompts/production-planner.md`

---

# Design Principles

- Visual-first storytelling
- One visual purpose for every narration segment
- No visual gaps
- AI-first production workflow
- Production efficiency over unnecessary complexity
- Educational clarity before visual spectacle

---

# Production Modes

The planner supports three production modes:

| Mode | Primary Assets |
|------|----------------|
| Solo Creator | AI Images, AI Video, Motion Graphics |
| Small Team | Custom Graphics, Light Animation |
| Professional Studio | Custom Animation, Filming, Advanced Compositing |

The default mode is **Solo Creator AI-First Workflow**.

---

# Asset Classification

Every asset must be assigned one of the following types:

- FLOW
- MOTION_GRAPHICS
- STATIC_IMAGE

Every asset must also receive a priority level:

| Priority | Purpose |
|----------|---------|
| P0 | Essential production asset |
| P1 | Major retention asset |
| P2 | Supporting educational asset |
| P3 | Optional enhancement |

---

# Quality Gates

Before production begins:

- Every narration line has a visual.
- Every asset has a type.
- Every asset has a priority.
- Every FLOW asset includes a production-ready prompt.
- Every Motion Graphics asset includes animation instructions.
- No visual section exceeds the retention rule.

---

# Known Limitations

- Production complexity estimates are approximate.
- AI generation quality varies by platform.
- Human review is recommended before large-scale asset generation.

---

# Future Improvements

Potential enhancements:

- Automatic shot duration estimation
- Asset dependency graph
- Budget estimation
- AI render cost estimation
- Timeline generation
- Direct integration with Google Flow

---

# Changelog

## v1.0.0

Initial production prompt.