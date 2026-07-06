# TDCA — Transport Data Collection and Analysis

Slides and materials for the **Transport Data Collection and Analysis (TDCA)** module at the Institute for Transport Studies, University of Leeds.

**Live slides:** https://itsleeds.github.io/tdca/slides.html

![Deploy status](https://img.shields.io/github/actions/workflow/status/itsleeds/tdca/publish.yml?branch=main&label=deploy)

## Contents

- `slides.qmd` — Data Science and AI for Data-Driven Transport Planning (revealjs slides)
- `index.qmd` — Landing page / website index
- `references.bib` — Bibliography
- `_extensions/clean/` — clean-revealjs theme
- `images/` — Figures and slide images
- `.github/workflows/publish.yml` — Auto-deploy to GitHub Pages on push to main

## Links

- **TDS (Transport Data Science):** [itsleeds.github.io/tds](https://itsleeds.github.io/tds/)
- Module website: [itsleeds.github.io/tdca](https://itsleeds.github.io/tdca/)
- Reproducible project template: [github.com/Robinlovelace/reproducible-project-template](https://github.com/Robinlovelace/reproducible-project-template)

## Local development

```sh
quarto render    # Build site into docs/
open docs/slides.html  # View slides
```

Built with [Quarto](https://quarto.org/) and deployed via [GitHub Actions](https://github.com/features/actions).
