# Structured Research Experience

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23022270.svg)](https://doi.org/10.5281/zenodo.23022270)

Materials developed for teaching scientific communication (oral and written), the
design of simulation studies, and reproducible research practices, used for
structured research experiences (SRE) with undergraduate students and beyond.

| Folder | Materials |
|---|---|
| [`oral-communication/`](oral-communication/) | Oral Presentation Assessment Rubric |
| [`written-communication/`](written-communication/) | Academic Writing |
| [`simulation-studies/`](simulation-studies/) | Designing and Reporting Simulation Studies |
| [`reproducibility/`](reproducibility/) | Reproducible Project Workflows |

## Building

Each document is a single [Quarto](https://quarto.org) source file rendered to
PDF via Quarto's Typst engine (no LaTeX needed):

```bash
quarto render <folder>/<file>.qmd
```

## License

© Irina Gaynanova, licensed [CC BY 4.0](LICENSE.md). Suggested attribution:
"Adapted from teaching materials by Irina Gaynanova, CC BY 4.0."
