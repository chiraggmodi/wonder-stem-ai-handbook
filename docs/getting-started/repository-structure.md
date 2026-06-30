# Repository Structure

The repository is organized around the Wonder STEM Factory.

```
wonder-stem-ai-handbook/

├── docs/
│   ├── getting-started/
│   ├── factory/
│   ├── gems/
│   ├── workflows/
│   ├── prompts/
│   ├── artifacts/
│   ├── automation/
│   ├── troubleshooting/
│   └── resources/
│
├── mkdocs.yml
├── README.md
├── LICENSE
└── ROADMAP.md
```

---

## docs/

Contains all handbook documentation.

---

## getting-started/

Introduction and setup.

---

## factory/

Explains the overall production factory.

---

## gems/

Documentation for every Gemini Gem.

Each Gem includes:

- Purpose
- Inputs
- Outputs
- Prompt
- Best practices

---

## workflows/

Documents complete production workflows.

Examples:

- Topic Assessment
- Research
- Script Writing
- Verification
- Publishing

---

## prompts/

Reusable prompts.

These are prompt templates rather than finished workflows.

---

## artifacts/

Explains every artifact produced during production.

Examples:

- Research Brief
- Script
- Thumbnail Plan
- Production Manifest

---

## automation/

Automation examples using:

- Gemini
- Airtable
- n8n
- Make
- GitHub Actions

---

## troubleshooting/

Common AI issues.

Examples:

- Empty responses
- Token limits
- Hallucinations
- Broken Markdown
- JSON formatting errors

---

## resources/

External references and useful links.

---

## Version Control

Every documentation update should be committed separately.

Example:

```
docs(factory): update workflow documentation
```

This makes changes easy to review.