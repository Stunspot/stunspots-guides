---
layout: default
title: How to Use These Guides
---

# How to Use These Guides

The **Stunspot’s Guide to…** repositories are Advanced Knowledge Bases: human-readable, but primarily designed as model-facing knowledge substrates.

Use them as:

- AI project knowledge
- RAG corpus material
- long-context reference material
- agent memory substrate
- domain doctrine for assistants
- human field manuals
- citation-bearing public artifacts

## Recommended Workflow

### 1. Pick the right canon

Start from the [Catalog](./catalog.html). Choose the guide whose domain matches the task.

For cross-domain problems, combine guides deliberately. For example:

- AI product strategy: **AI Systems** + **Business Venture Formulation** + **Game Theory**
- RAG meaning and citation discipline: **AI Systems** + **Semantics, Semiotics, and Symbols**
- Investigative market analysis: **Investigative News Intelligence** + **Macroeconomics** + **Sales Prospecting Strategy**
- Human-centered product or organizational reasoning: **Human Behavioral Neurobiology** + **Business Venture Formulation** + **Game Theory**

### 2. Prefer compiled packs first

Most guide repositories include:

```text
knowledge-packs/
├── by-report/
├── compiled-packs/
└── omnibus/
```

For most AI systems, start with `compiled-packs/`.

Compiled packs usually give the best balance between:

- retrieval precision
- manageable file count
- preserved conceptual structure
- easier upload into AI Projects, RAG systems, NotebookLM-style tools, and long-context workspaces

### 3. Use by-report packs for precision

Use `knowledge-packs/by-report/` when you need source-level separation, better citation discipline, or fine-grained retrieval.

This is usually best for:

- serious RAG systems
- search/index pipelines
- citation-sensitive workflows
- selective domain loading
- debugging which source introduced a claim

### 4. Use omnibus packs for continuity

Use `knowledge-packs/omnibus/` when the target system handles large single files well.

This is usually best for:

- archival simplicity
- long-context synthesis
- single-file AI project upload
- local search
- systems where global continuity matters more than retrieval granularity

### 5. Cite the specific guide, not this gateway

This repository is the library index. Each guide owns its own citation metadata.

When citing a guide, use that guide’s own:

- `CITATION.cff`
- `LICENSE.md`
- `STATUS.md`
- `CHANGELOG.md`
- `manifest.json`

Use this gateway only when citing the catalog itself.

## Common Pattern

A typical guide repository works like this:

| Area | Purpose |
|---|---|
| `README.md` | Public orientation and quick-start explanation. |
| `MANIFEST.md` | Human-readable structural inventory. |
| `manifest.json` | Machine-readable structural inventory. |
| `STATUS.md` | Release and completion status. |
| `CITATION.cff` | Citation metadata. |
| `LICENSE.md` | License terms for that guide. |
| `docs/` | Navigation, Pages support, and usage guidance. |
| `knowledge-packs/by-report/` | Individual source-report corpus. |
| `knowledge-packs/compiled-packs/` | Grouped upload packs. |
| `knowledge-packs/omnibus/` | Whole-corpus bundle. |

## Practical Loading Advice

When uploading guides into an AI workspace, avoid throwing everything into the same bucket without a reason. Choose a small set of relevant guides and tell the model what each one is for.

Example setup language:

```text
Use Stunspot’s Guide to AI Systems as the primary doctrine for AI architecture, RAG design, agent boundaries, evals, and model operations.

Use Stunspot’s Guide to Semantics, Semiotics, and Symbols as the semantic hygiene layer for meaning, reference, ambiguity, symbols, interpretation, and citation discipline.

When the two guides overlap, treat AI Systems as the engineering layer and Semantics/Semiotics as the meaning-governance layer.
```

## Placeholder

A public website landing page may later live at:

**TODO: https://stunspot.com/guides**
