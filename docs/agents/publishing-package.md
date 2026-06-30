# Publishing Package Generator

> Version: 1.0.0

---

# Purpose

The Publishing Package Generator is the final content preparation stage of the Wonder STEM Factory.

Its responsibility is to transform the approved production assets into a complete YouTube publishing package optimized for discoverability, audience trust, viewer satisfaction, and long-term search performance.

Unlike previous agents, it performs no creative development or production planning. Instead, it prepares every metadata asset required for publication.

---

# Position in Workflow

```text
Production Manifest Generator
            │
            ▼
Publishing Package Generator
            ▼
HTML Dashboard
```

---

# Input

| Variable | Required | Description |
|----------|----------|-------------|
| Production Manifest | Yes | Final production dataset |
| Revised Script | Yes | Approved script |
| Thumbnail Package | Yes | Winning title and thumbnail |
| Google Flow Prompt Package | No | Production reference |
| Scene Breakdown Package | No | Story structure reference |
| Production Plan | No | Runtime and chapter guidance |
| Blueprint Handoff | No | Story intent reference |

---

# Output

Produces a complete Publishing Package including:

- Search Intent Analysis
- SEO Package
- Primary Keyword
- Secondary Keywords
- Long-Tail Keywords
- Search Queries
- Video Description
- Mobile Description
- YouTube Chapters
- Tags
- Hashtags
- Pinned Comments
- Community Posts
- Shorts Package
- Viewer Engagement Package
- Social Sharing Package
- Publishing Validation
- Publishing Checklist
- Packaging Score
- Canonical Publishing Package (YAML)

---

# Responsibilities

This GEM is responsible for:

- Optimizing YouTube discoverability
- Generating metadata
- Producing descriptions
- Creating chapters
- Building SEO assets
- Producing social media copy
- Creating engagement assets
- Validating publishing readiness
- Packaging all publishing assets into one canonical artifact

---

# Non-Responsibilities

This GEM does **not**:

- Rewrite the script
- Modify narration
- Change scientific explanations
- Redesign thumbnails
- Produce AI prompts
- Perform research
- Modify production planning

Its responsibility is publishing only.

---

# Variables

| Variable | Required |
|----------|----------|
| Production Manifest | Yes |
| Revised Script | Yes |
| Thumbnail Package | Yes |
| Production Plan | No |
| Research Brief | No |
| Blueprint Handoff | No |

---

# Production Prompt

See:

`/prompts/publishing-package.md`

---

# Design Principles

- Humans before algorithms
- Search supports education
- Metadata reflects the approved script
- Curiosity without clickbait
- Educational integrity above SEO
- Every asset strengthens audience trust

---

# Deliverables

The Publishing Package contains:

- SEO metadata
- Descriptions
- Chapters
- Search keywords
- Tags
- Hashtags
- Shorts strategy
- Community posts
- Pinned comments
- Social media posts
- Publishing checklist
- Packaging score

This package becomes the canonical publishing artifact consumed by downstream systems.

---

# Validation Rules

Before publishing:

- Description matches the script.
- Metadata supports the winning title.
- Chapters follow the story.
- SEO remains natural.
- Tags are relevant.
- Hashtags are appropriate.
- No unsupported claims exist.
- Publishing checklist passes.

Validation failures are reported rather than automatically corrected.

---

# Known Limitations

- Search trends evolve over time.
- Keyword opportunities vary by audience and region.
- Human review is recommended before publication.

---

# Future Improvements

Potential enhancements:

- YouTube API integration
- TubeBuddy compatibility
- vidIQ recommendations
- Trending keyword analysis
- Competitor metadata comparison
- Multi-language publishing packages
- A/B metadata generation

---

# Changelog

## v1.0.0

Initial production prompt.