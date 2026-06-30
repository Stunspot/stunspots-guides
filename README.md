# Stunspot’s Guides

**The Advanced Knowledge Base Library**  
*A central gateway for the public **Stunspot’s Guide to…** model-facing knowledge canons.*

![Status](https://img.shields.io/badge/status-first_pass_catalog-darkgreen)
![Guides](https://img.shields.io/badge/guides-11-blue)
![Audience](https://img.shields.io/badge/audience-AI%2FRAG_systems-blueviolet)
![License](https://img.shields.io/badge/license-see_individual_repos-darkgrey)

This repository is the canonical GitHub index for the public **Stunspot’s Guide to…** Advanced Knowledge Base series.

Each guide is a Markdown-native, model-facing knowledge repository designed for AI/RAG ingestion, long-context workspaces, project knowledge bases, retrieval corpora, agent memory layers, and serious human reference. Human readers can browse them like field manuals, but their deeper purpose is practical augmentation: they give models dense domain doctrine, stable terminology, reasoning frames, failure maps, and operational heuristics.

Use this gateway to find the right canon, jump into its GitHub repository, open its GitHub Pages site, or locate the knowledge packs intended for upload into AI systems.

---

## Start Here

- [Catalog](./docs/catalog.md)
- [How to Use These Guides](./docs/how-to-use.md)
- [Machine-readable manifest](./manifest.json)
- Gateway Pages site, once enabled: **https://stunspot.github.io/stunspots-guides/**
- Public website landing page placeholder: **TODO: https://stunspot.com/guides**

---

## The Library

| Guide | What It Covers | GitHub | Pages |
|---|---|---:|---:|
| **Stunspot’s Guide to AI Systems** | Practical AI systems design, model steering, context architecture, RAG, agents, evals, governance, and operations. | [Repo](https://github.com/Stunspot/stunspots-guide-to-ai-systems) | [Pages](https://stunspot.github.io/stunspots-guide-to-ai-systems/) |
| **Stunspot’s Guide to Semantics, Semiotics, and Symbols** | Representation, reference, signs, meaning, symbols, interpretation, grounding, semantic pathology, and assistant governance. | [Repo](https://github.com/Stunspot/stunspots-guide-to-semantics-semiotics-and-symbols) | [Pages](https://stunspot.github.io/stunspots-guide-to-semantics-semiotics-and-symbols/) |
| **Stunspot’s Guide to Macroeconomics** | Money, liquidity, credit, macro regimes, financial instability, central banks, fiscal systems, and institutional strategy. | [Repo](https://github.com/Stunspot/stunspots-guide-to-macroeconomics) | [Pages](https://stunspot.github.io/stunspots-guide-to-macroeconomics/) |
| **Stunspot’s Guide to Human Behavioral Neurobiology** | Human behavior as embodied, predictive, metabolically constrained, socially regulated, culturally patterned, and ecologically situated. | [Repo](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology) | [Pages](https://stunspot.github.io/stunspots-guide-to-human-behavioral-neurobiology/) |
| **Stunspot’s Guide to Automotive Systems** | Vehicle reality modeling, machine physics, platform architecture, propulsion, chassis dynamics, diagnostics, lifecycle economics, safety, and repair judgment. | [Repo](https://github.com/Stunspot/stunspots-guide-to-automotive-systems) | [Pages](https://stunspot.github.io/stunspots-guide-to-automotive-systems/) |
| **Stunspot’s Guide to Business Venture Formulation** | Venture ideas as inspectable enterprise systems: markets, offers, operations, risks, business models, and strategic viability. | [Repo](https://github.com/Stunspot/stunspots-guide-to-business-venture-formulation) | [Pages](https://stunspot.github.io/stunspots-guide-to-business-venture-formulation/) |
| **Stunspot’s Guide to Game Theory** | Incentives, interdependence, equilibrium, institutional design, strategic failure, conflict, cooperation, and long-run governance. | [Repo](https://github.com/Stunspot/stunspots-guide-to-game-theory) | [Pages](https://stunspot.github.io/stunspots-guide-to-game-theory/) |
| **Stunspot’s Guide to Gastronomic Engineering** | Deterministic food physics, culinary formulation, experimental protocols, dietary constraint engineering, and AI/RAG culinary reasoning. | [Repo](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering) | [Pages](https://stunspot.github.io/stunspots-guide-to-gastronomic-engineering/) |
| **Stunspot’s Guide to Legal Mastery** | Legal systems reasoning, authority, interpretation, proof, procedure, strategy, private ordering, legal ethics, and legal execution. | [Repo](https://github.com/Stunspot/stunspots-guide-to-legal-mastery) | [Pages](https://stunspot.github.io/stunspots-guide-to-legal-mastery/) |
| **Stunspot’s Guide to Sales Prospecting Strategy** | Demand-signal architecture, buyer-system mapping, evidence discipline, outbound operations, CRM/RAG continuity, and GTM failure diagnosis. | [Repo](https://github.com/Stunspot/stunspots-guide-to-sales-prospecting-strategy) | [Pages](https://stunspot.github.io/stunspots-guide-to-sales-prospecting-strategy/) |
| **Stunspot’s Guide to Investigative News Intelligence** | Evidence reasoning, public-reality mapping, source topology, narrative-operation analysis, and bounded inference under partial observability. | [Repo](https://github.com/Stunspot/stunspots-guide-to-investigative-news-intelligence) | [Pages](https://stunspot.github.io/stunspots-guide-to-investigative-news-intelligence/) |

---

## Browse by Use Case

### AI builders, prompt engineers, and RAG architects
Start with **AI Systems** and **Semantics, Semiotics, and Symbols**. These are the spine for model steering, context architecture, corpus hygiene, meaning, reference, and assistant governance.

### Strategy, markets, and institutional reasoning
Use **Macroeconomics**, **Game Theory**, **Business Venture Formulation**, **Sales Prospecting Strategy**, and **Legal Mastery** when the task involves incentives, markets, governance, decision systems, commercial pressure, or strategic execution.

### Human, physical, and applied-domain reasoning
Use **Human Behavioral Neurobiology**, **Automotive Systems**, and **Gastronomic Engineering** when the task needs embodied reality, physical constraints, diagnostics, formulation, or practical field judgment.

### Public reality, evidence, and narrative analysis
Use **Investigative News Intelligence** for source reasoning, evidence discipline, claim evaluation, narrative mapping, and public-reality reconstruction.

---

## Common Repository Anatomy

Most guide repositories follow this directory policy:

```text
.
├── README.md
├── MANIFEST.md
├── manifest.json
├── STATUS.md
├── CHANGELOG.md
├── CITATION.cff
├── LICENSE.md
├── docs/
│   ├── index.md
│   ├── canon-map.md
│   ├── how-to-use-this-canon.md
│   └── knowledge-packs.md
└── knowledge-packs/
    ├── by-report/
    ├── compiled-packs/
    └── omnibus/
```

The rule of thumb:

- **`docs/`** is for navigation, GitHub Pages, and usage guidance.
- **`knowledge-packs/by-report/`** contains the individual canonical source reports.
- **`knowledge-packs/compiled-packs/`** contains grouped upload packs for AI/RAG workflows.
- **`knowledge-packs/omnibus/`** contains a whole-corpus bundle for single-file import, archive, or long-context systems.

---

## How to Use the Knowledge Packs

For most AI/RAG workflows, start with each guide’s **compiled packs**. They preserve useful structure while avoiding both extremes: dozens of separate files or one massive omnibus file.

Use **by-report** when you need fine-grained retrieval, source isolation, or citation discipline.

Use **omnibus** when your target system handles large single-file sources well, when you want archival simplicity, or when you are working in a long-context environment that benefits from global continuity. NotebookLM excels at such and can crosslink multiple domains at once with ease given the knowledge bases' regularities in construction. With its advanced knowledge graphing, they snap together like Lego. 

---

## Citation and Licensing

Each guide owns its own license, citation metadata, release status, and version history. Check the individual repository’s:

- `CITATION.cff`
- `LICENSE.md`
- `STATUS.md`
- `CHANGELOG.md`
- `manifest.json`

Do not treat this gateway repo as the citation target for a specific guide unless you are citing the library index itself. Cite the individual guide when referencing a specific canon.

---

## Authorship

Created by **Sam “stunspot” Walker** and **Collaborative Dynamics**.

Maintained as the public GitHub gateway for the Stunspot Advanced Knowledge Base library.

--stunspot | ⟨🤩⨯📍⟩ and 💠‍🌐Nova
