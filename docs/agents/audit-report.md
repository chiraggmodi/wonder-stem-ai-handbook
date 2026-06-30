# Audit Report

> Version: 1.0.0

---

# Purpose

The Audit Report GEM performs the final editorial quality review of the Draft Script before revision.

Unlike the Verification Report, which focuses exclusively on scientific correctness, the Audit Report evaluates the complete viewer experience by combining scientific integrity, storytelling quality, audience retention, educational effectiveness, and production readiness.

Its objective is to identify every issue that could reduce the quality of the final Wonder STEM video and provide actionable recommendations for improvement.

---

# Position in Workflow

```text
Blueprint
      │
      ├──────────────┐
      ▼              ▼
Draft Script   Verification Report
      │              │
      └──────┬───────┘
             ▼
       Audit Report
             ▼
       Revised Script
```

---

# Input

| Variable | Required | Description |
|----------|----------|-------------|
| Blueprint Handoff | Yes | Original educational design |
| Draft Script | Yes | Narration-ready script |
| Verification Report | Yes | Scientific verification findings |

---

# Output

Produces a comprehensive Audit Report containing:

- Executive Summary
- Scientific Accuracy Audit
- Hallucination Detection
- Hook Analysis
- Hook Efficiency Audit
- Retention Analysis
- Emotional Journey Audit
- Curiosity Audit
- Storytelling Audit
- Narrative Voice Audit
- Visualization Audit
- Cognitive Load Audit
- Educational Flow Audit
- Virality Audit
- Platform Optimization
- Ending & CTA Audit
- Final Publication Decision

---

# Responsibilities

This GEM is responsible for:

- Reviewing the complete viewer experience
- Evaluating educational effectiveness
- Measuring audience retention
- Assessing storytelling quality
- Reviewing emotional progression
- Validating script structure against the Blueprint
- Applying findings from the Verification Report
- Producing prioritized improvement recommendations

---

# Non-Responsibilities

This GEM does **not**:

- Rewrite the script
- Research new facts
- Verify scientific claims independently
- Introduce new educational content
- Generate production assets

Its role is evaluation only.

---

# Variables

| Variable | Required |
|----------|----------|
| Blueprint Handoff | Yes |
| Draft Script | Yes |
| Verification Report | Yes |

---

# Production Prompt

See:

`/prompts/audit-report.md`

---

# Design Principles

- Evaluate the complete viewing experience.
- Preserve scientific integrity.
- Prioritize audience retention.
- Provide actionable recommendations.
- Rank issues by impact.
- Focus on measurable improvements rather than subjective preferences.

---

# Quality Dimensions

The Audit Report evaluates:

- Scientific Quality
- Educational Quality
- Storytelling Quality
- Viewer Retention
- Curiosity
- Emotional Journey
- Visual Potential
- Platform Suitability
- Wonder STEM Brand Fit

---

# Issue Prioritization

Issues are classified using four priority levels:

| Priority | Meaning |
|----------|---------|
| P0 | Critical — factual errors or misinformation |
| P1 | Major — significant retention or storytelling issues |
| P2 | Moderate — clarity or optimization opportunities |
| P3 | Minor — stylistic improvements |

P0 and P1 issues should always be addressed before publication.

---

# Known Limitations

- Audit quality depends on the completeness of the Draft Script and Verification Report.
- Some recommendations involve editorial judgment and may require human review.
- Final publishing decisions should consider audience and production constraints.

---

# Future Improvements

Potential enhancements:

- Automated pacing analysis
- Audience retention prediction
- Readability scoring
- AI narration quality analysis
- Thumbnail and title consistency checks
- Cross-platform optimization scoring

---

# Changelog

## v1.0.0

Initial production prompt.