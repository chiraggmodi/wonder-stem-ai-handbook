# Research Brief

> Version: 1.0.0

---

# Purpose

The Research Brief GEM is the scientific foundation of the Wonder STEM workflow.

It transforms the Topic Assessment into a comprehensive, evidence-based research document that is used by every downstream GEM.

Its primary objective is to maximize factual accuracy while producing research that is easy to convert into educational content.

---

# Position in Workflow

```text
Topic Assessment
        ↓
Research Brief
        ↓
Blueprint Handoff
```

---

# Input

| Variable | Description |
|----------|-------------|
| Topic Assessment | Structured topic analysis from the previous GEM |

---

# Output

Produces a structured Research Brief containing:

- Topic Definition
- Executive Summary
- Key Facts
- Scientific Explanation
- Misconceptions
- History & Discovery
- Current Research
- Applications
- Content Opportunities
- Visual Planning
- Verification Priorities
- Source Guidance
- Script Risk Alerts
- Research Summary

---

# Responsibilities

This GEM is responsible for:

- Scientific research
- Educational simplification
- Fact organization
- Visual planning
- Identifying misconceptions
- Highlighting verification priorities
- Preparing content for downstream script generation

---

# Non-Responsibilities

This GEM does **not**:

- Write narration
- Generate dialogue
- Create video scenes
- Optimize titles
- Produce thumbnails
- Publish content

Those tasks belong to later GEMs.

---

# Variables

| Variable | Required |
|----------|----------|
| Topic Assessment | Yes |

---

# Production Prompt

See:

`/prompts/research-brief.md`

---

# Design Principles

- Scientific accuracy above engagement
- Never invent facts
- Separate established science from speculation
- Explain uncertainty clearly
- Produce reusable research for downstream GEMs

---

# Known Limitations

- Research quality depends on the Topic Assessment.
- Emerging scientific fields may contain uncertainty.
- Verification is still recommended for surprising claims.

---

# Future Improvements

Potential enhancements:

- Automatic citation support
- DOI lookup
- Google Scholar integration
- arXiv integration
- PubMed integration

---

# Changelog

## v1.0.0

Initial production prompt.