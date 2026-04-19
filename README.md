# Portfolio

End-to-end R analyses using packages I've published to CRAN:
biostatistics, genomic surveillance, and clinical AI fairness.

**Live site:** https://cuiweig.github.io/portfolio

## Case studies

| # | Title | Package |
|---|---|---|
| 1 | Forecasting SARS-CoV-2 Variant Dominance | [lineagefreq](https://CRAN.R-project.org/package=lineagefreq) |
| 2 | Post-hoc Fairness Audit of a Deployed Risk Score (COMPAS) | [clinicalfair](https://CRAN.R-project.org/package=clinicalfair) |
| 3 | Optimising Sequencing Budgets for Pathogen Surveillance | [survinger](https://CRAN.R-project.org/package=survinger) |
| 4 | Releasing Synthetic Clinical Data | [syntheticdata](https://CRAN.R-project.org/package=syntheticdata) |

Each case study is a complete Quarto document (`{N}-*/index.qmd`)
rendered to HTML under `docs/`. GitHub Pages serves from `main:/docs`.

## How to reproduce

Requires R 4.1+ and Quarto 1.3+.

```r
install.packages(c("lineagefreq", "survinger", "clinicalfair", "syntheticdata"))
install.packages(c("ggplot2", "dplyr", "tibble", "scales"))
```

```sh
# From the repo root:
quarto render
```

Rendered output lands in `docs/`. Open `docs/index.html` in a browser
or rely on the GitHub Pages deployment at the live-site URL above.

Tested with R 4.5.3 and Quarto 1.8.25 on Windows 11.

## License

MIT — see [LICENSE](LICENSE).

## Links

- Main GitHub profile: https://github.com/CuiweiG
- Blog: https://cuiweig.github.io
