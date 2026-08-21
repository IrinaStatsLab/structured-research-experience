# Teaching Materials: Scientific Communication, Simulation Studies, and Reproducibility

Materials developed for teaching scientific communication (oral and written), the design of simulation studies, and reproducible research practices that has been used for structured research experiences (SRE) with undergraduate students and beyond. Unless noted otherwise, everything here is licensed under [CC BY 4.0](LICENSE.md) — you are welcome to use and adapt it with attribution.

## Contents

| Folder | Materials |
|---|---|
| [`oral-communication/`](oral-communication/) | Oral Presentation Assessment Rubric ([source](oral-communication/presentation-rubric.qmd), [PDF](oral-communication/presentation-rubric.pdf)) |
| [`written-communication/`](written-communication/) | *Coming soon* |
| [`simulation-studies/`](simulation-studies/) | *Coming soon* |
| [`reproducibility/`](reproducibility/) | *Coming soon* |

## Building the PDFs

Each document is a single [Quarto](https://quarto.org) source file (`.qmd`) rendered to PDF via Quarto's built-in Typst engine (no LaTeX installation needed):

```bash
quarto render oral-communication/presentation-rubric.qmd
```

Edit the `.qmd`, re-render, and commit both the source and the updated PDF.

## License

© Irina Gaynanova. Licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) — see [LICENSE.md](LICENSE.md). Suggested attribution: "Adapted from teaching materials by Irina Gaynanova, CC BY 4.0."
