# Verification Report

> Version: 1.0.0

---

# Purpose

The Verification Report GEM performs scientific quality assurance on the completed Draft Script.

Its responsibility is to identify factual inaccuracies, unsupported claims, oversimplifications, missing context, and scientific risks before the content proceeds to the editorial review stage.

It protects the educational integrity of Wonder STEM by ensuring that published content remains scientifically accurate and evidence-driven.

---

# Position in Workflow

```text
Draft Script
      ↓
Verification Report
      ↓
Script Audit
```

---

# Input

| Variable | Required | Description |
|----------|----------|-------------|
| Draft Script | Yes | Completed narration-ready script |
| Research Brief | Optional | Original scientific research reference |
| Blueprint Handoff | Optional | Story structure reference |

---

# Output

Produces a structured Verification Report containing:

- Executive Summary
- Master Verification Table
- Scientific Accuracy Audit
- Narrative Exaggeration Audit
- Context Audit
- Simplification Risk Audit
- Uncertainty Audit
- Statistics & Numbers Audit
- Metaphor & Scale Verification
- Hook Fact Audit
- Hallucination Detection
- Source Requirements
- High Priority Verification List
- Final Correction Table
- Publication Decision

---

# Responsibilities

This GEM is responsible for:

- Verifying scientific claims
- Detecting unsupported information
- Reviewing numerical claims
- Evaluating scientific nuance
- Assessing educational simplifications
- Identifying hallucinations
- Recommending corrections
- Assessing publication readiness

---

# Non-Responsibilities

This GEM does **not**:

- Rewrite the script
- Improve storytelling
- Increase engagement
- Change pacing
- Optimize retention
- Generate new scientific content

Its role is verification only.

---

# Variables

| Variable | Required |
|----------|----------|
| Draft Script | Yes |
| Research Brief | Optional |
| Blueprint Handoff | Optional |

---

# Production Prompt

See:

`/prompts/verification-report.md`

---

# Design Principles

- Assume every significant claim requires scrutiny.
- Verify before trusting.
- Prioritize scientific integrity over narrative impact.
- Explain every verification recommendation.
- Distinguish between errors, uncertainty, and acceptable simplifications.
- Preserve educational clarity while protecting factual accuracy.

---

# Verification Priorities

Highest priority should always be given to:

- Hook claims
- Title claims
- Thumbnail claims
- Major reveals
- Statistics
- Historical dates
- Numerical comparisons
- Counterintuitive facts
- Scientific explanations

---

# Known Limitations

- Cannot independently confirm every scientific claim without authoritative sources.
- Verification quality improves when the Research Brief is available.
- Human expert review is recommended for highly specialized scientific topics.

---

# Future Improvements

Potential enhancements:

- DOI verification support
- Automatic citation matching
- Cross-reference against peer-reviewed literature
- Government and university source validation
- Confidence scoring based on evidence quality

---

# Changelog

## v1.0.0

Initial production prompt.