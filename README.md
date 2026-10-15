# Stationary Strings Theorem II: Relativity, Phase Transition and the Cosmological Cycle of Information

> **Türkçe:** [README_TR.md](./README_TR.md)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.YYYYYYY.svg)](https://doi.org/10.5281/zenodo.YYYYYYY)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

> **Status:** Unpublished preprint (v1, 2025; extended v5 text). Not peer-reviewed.

Second link of the series: a bridge between gravitational time dilation and string frequency
($t' = k_t f_0 \sqrt{1-2GM/rc^2}$), definition of the Perfection Potential ($\Phi = 1/S(f)$),
black holes as phase transducers converting energy into information.
Paper available in Turkish and English.

## Repository layout

```
.
├── paper/
│   ├── duran_sicimler_teoremi_II.tex      # Paper source (Turkish, v5)
│   ├── duran_sicimler_teoremi_II.pdf     # Compiled paper, TR
│   ├── duran_sicimler_teoremi_II_EN.tex  # Paper source (English)
│   └── duran_sicimler_teoremi_II_EN.pdf  # Compiled paper, EN
├── CITATION.cff
└── LICENSE
```

## Compiling

```bash
cd paper
pdflatex -interaction=nonstopmode duran_sicimler_teoremi_II.tex
pdflatex -interaction=nonstopmode duran_sicimler_teoremi_II_EN.tex
```

## Citation

```bibtex
@misc{meral2025duranII,
  author = {Fahri Meral},
  title  = {Stationary Strings Theorem: Relativity, Phase Transition and the Cosmological Cycle of Information},
  year   = {2025},
  doi    = {10.5281/zenodo.YYYYYYY},
  url    = {https://github.com/fahrim/stationary-strings-ii}
}
```

## License

Paper text (TR + EN): [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — Fahri Meral (2025).
