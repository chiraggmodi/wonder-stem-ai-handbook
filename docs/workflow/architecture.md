# Workflow Architecture

The Wonder STEM architecture follows a layered approach that separates responsibilities across independent stages.

---

## High-Level Architecture

```text
                 User
                  │
                  ▼
           Topic Selection
                  │
                  ▼
            Research Gem
                  │
                  ▼
       Topic Evaluation Gem
                  │
                  ▼
         Outline Generator
                  │
                  ▼
          Script Generator
                  │
                  ▼
          Fact Verification
                  │
                  ▼
          Visual Planning
                  │
                  ▼
       Publishing Assistant
                  │
                  ▼
          Final Assets
```

---

## Architectural Layers

### Input Layer

Receives user ideas, topics, or requirements.

Examples:

* "How do rockets work?"
* "Can plants hear?"
* "Why is the sky blue?"

---

### Intelligence Layer

Responsible for reasoning and content generation.

Components include:

* Research
* Evaluation
* Outline generation
* Script writing
* Fact checking

---

### Production Layer

Transforms educational content into publishable assets.

Examples include:

* YouTube titles
* Descriptions
* Thumbnail ideas
* Visual prompts
* Social media posts

---

### Review Layer

Ensures generated content meets quality standards.

Checks include:

* Accuracy
* Readability
* Educational value
* Formatting
* Completeness

---

## Design Goals

The architecture is designed to be:

* Reliable
* Maintainable
* Extensible
* Model-agnostic
* Easy to debug
* Suitable for production use
