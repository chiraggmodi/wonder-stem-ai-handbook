# Production Manifest Generator

> Version: 1.0.0

---

# Purpose

The Production Manifest Generator is the final data transformation stage of the Wonder STEM production pipeline.

Its responsibility is to convert the approved Google Flow Prompt Package into a structured production manifest that can be imported into production tracking systems, project management tools, and dashboard applications.

Unlike previous GEMs, this stage performs no creative work. It simply organizes approved production data into a standardized, machine-readable format.

---

# Position in Workflow

```text
Google Flow Prompt Generator
            │
            ▼
Production Manifest Generator
            ▼
HTML Dashboard
```

---

# Input

| Variable | Required | Description |
|----------|----------|-------------|
| Google Flow Prompt Package | Yes | Final Google Flow prompts |
| Production Plan | No | Validation reference |
| Scene Breakdown Package | No | Additional metadata |

---

# Output

Produces a Production Manifest containing:

- Production Summary
- Airtable Import Table
- Asset Manifest
- Production Statistics
- Validation Report

The manifest serves as the canonical production dataset for downstream systems.

---

# Responsibilities

This GEM is responsible for:

- Creating production records
- Preserving approved asset metadata
- Organizing assets by type
- Generating import-ready tables
- Producing production statistics
- Validating production completeness
- Preparing structured data for dashboards and tracking systems

---

# Non-Responsibilities

This GEM does **not**:

- Rewrite prompts
- Modify production assets
- Change Scene IDs
- Change Asset IDs
- Modify durations
- Generate new prompts
- Create new scenes
- Perform production planning

It only organizes approved production data.

---

# Variables

| Variable | Required |
|----------|----------|
| Google Flow Prompt Package | Yes |
| Production Plan | No |
| Scene Breakdown Package | No |

---

# Production Prompt

See:

`/prompts/production-manifest.md`

---

# Design Principles

- Preserve all approved production data.
- Every scene becomes exactly one production record.
- No information is modified.
- Produce both human-readable and machine-readable output.
- Ensure compatibility with multiple production tracking systems.

---

# Manifest Structure

Every production record preserves:

- Scene ID
- Shot ID
- Asset ID
- Continuity ID
- Asset Type
- Duration
- Prompt
- Negative Prompt
- Production Status

The default production status is **Pending**.

---

# Validation Rules

Before export:

- Every Scene has one record.
- Every Shot has one Asset.
- Every Asset ID is unique.
- Every Prompt exists.
- Every Duration exists.
- Continuity IDs are preserved.

Validation failures are reported without automatic correction.

---

# Supported Integrations

The Production Manifest is designed to support:

- Airtable
- Google Sheets
- Notion
- Excel
- CSV exports
- Internal production databases
- HTML Dashboard

---

# Known Limitations

- Assumes upstream workflow artifacts are complete and approved.
- Does not resolve missing production data.
- Import compatibility depends on downstream schema requirements.

---

# Future Improvements

Potential enhancements:

- JSON export
- CSV export
- Airtable API integration
- Notion API integration
- Asset dependency graph
- Production progress tracking
- Render queue generation

---

# Changelog

## v1.0.0

Initial production prompt.