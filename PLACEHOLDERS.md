# Placeholders and Follow-Up Notes

This repo has been filled out as a first-pass central gateway for the public **Stunspot’s Guide to…** Advanced Knowledge Base library.

## Confirm / Decide

### Public website URL

Current placeholder:

```text
https://stunspot.com/guides
```

Decision needed: confirm whether this is the final public-facing landing page path, or choose another path such as:

```text
https://stunspot.com/knowledge-bases
https://stunspot.com/library
https://stunspot.com/guides-and-canons
```

Recommendation: use **/guides** unless there is already a site architecture reason not to. It is short, memorable, and broad enough for the whole series.

### Gateway GitHub Pages

Expected Pages URL:

```text
https://stunspot.github.io/stunspots-guides/
```

Action needed: enable GitHub Pages for this repo from `/docs` on the `main` branch.

### Gateway brand assets

No gateway-specific images are included yet.

Potential future assets:

```text
docs/assets/brand/stunspots-guides-readme-hero.png
docs/assets/brand/stunspots-guides-pages-hero.png
docs/assets/brand/stunspots-guides-social-preview.png
```

Recommendation: only create these if this repo becomes a prominent public front door. If the main public front door lives on stunspot.com, this repo can stay clean and utility-first.

### DOI / citation policy

Decision needed: should this gateway get its own DOI?

Recommendation: probably **no**, unless the library index itself becomes a stable cited artifact. Individual guide repos should remain the primary citation targets because they contain the actual corpora.

### New guide additions

When a new public guide repo is added, update:

1. `README.md`
2. `docs/index.md`
3. `docs/catalog.md`
4. `manifest.json`
5. this file, if the new guide has unresolved Pages, DOI, license, or asset questions

## Current Public Guide Repos in Catalog

- `Stunspot/stunspots-guide-to-ai-systems`
- `Stunspot/stunspots-guide-to-semantics-semiotics-and-symbols`
- `Stunspot/stunspots-guide-to-macroeconomics`
- `Stunspot/stunspots-guide-to-human-behavioral-neurobiology`
- `Stunspot/stunspots-guide-to-automotive-systems`
- `Stunspot/stunspots-guide-to-business-venture-formulation`
- `Stunspot/stunspots-guide-to-game-theory`
- `Stunspot/stunspots-guide-to-gastronomic-engineering`
- `Stunspot/stunspots-guide-to-legal-mastery`
- `Stunspot/stunspots-guide-to-sales-prospecting-strategy`
- `Stunspot/stunspots-guide-to-investigative-news-intelligence`

## Notes

The guide descriptions and Pages URLs were derived from existing repository metadata and each repo’s own manifest/README where available.

The gateway deliberately avoids duplicating full corpus content. Its job is discovery, routing, positioning, and catalog maintenance.
