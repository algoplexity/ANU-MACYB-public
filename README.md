# ANU-MACYB-public

Curated, sanitised public subset of coursework and project artefacts for the
**Master of Applied Cybernetics (MACYB)** at the Australian National University.

This repository follows the shared operating protocol in `master-rdmp.md`.

- `ANU-MACYB-private`: private working knowledge engine and implementation layer
- `ANU-MACYB-public`: curated public mirror and communication layer

## CIO / MACYB governance and source alignment

This repository is the curated public mirror and communication layer for the CIO/MACYB ecosystem.

The system-wide operating protocol is [`master-rdmp.md`](../master-rdmp.md). It defines the shared operating model, provenance rules, and folder grammar across theory, private implementation, and public publication.

The broader Cybernetic Intelligence programme is anchored by the canonical synthesis in [`docs/CI-unified.md`](https://github.com/algoplexity/cybernetic-intelligence/blob/main/docs/CI-unified.md).

This repository should remain a sanitized, public-safe subset of the upstream theory and private working material.

## What lives where

| Location | Contents |
|---|---|
| This repo (`main`) | Sanitised code, docs, small data samples, and site source |
| Private repo | Drafts, working notes, and in-progress material |
| Google Drive | Final PDFs/Docs, binary assets, and large files |

GitHub Pages is served from the `/docs` directory on the `main` branch.
Visit the site at: `https://algoplexity.github.io/ANU-MACYB-public/`

## Repository layout

```
docs/               # GitHub Pages source (Jekyll/Markdown)
  blog/             # Blog posts
  pages/            # Static pages (About, etc.)
  assets/images/    # Images used by the site
projects/
  cps1-individual/  # CPS1 individual project artefacts
  cps2-group/       # CPS2 group project artefacts
```

## Intentionally excluded

The following will **never** appear in this public repository:

- Assessment submissions (reports, essays, exams)
- Raw personal reflections or journal entries
- Sensitive or private data of any kind
- Large or raw datasets
- Any information that could identify peers or staff

## Licence

MIT — see [LICENSE](LICENSE).
