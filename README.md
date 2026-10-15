# Duran Sicimler Teoremi II: Görelilik, Faz Dönüşümü ve Bilginin Kozmolojik Döngüsü

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.YYYYYYY.svg)](https://doi.org/10.5281/zenodo.YYYYYYY)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

> **Durum:** Yayımlanmamış ön-baskı (preprint, v1, 2025; genişletilmiş v5 metni). Hakem denetiminden geçmemiştir.

Serinin ikinci halkası: kütleçekimsel zaman genişlemesi ile sicim frekansı arasında köprü
($t' = k_t f_0 \sqrt{1-2GM/rc^2}$), Mükemmellik Potansiyeli ($\Phi = 1/S(f)$) tanımı,
kara deliklerin enerjiyi bilgiye çeviren faz dönüştürücüler olduğu önermesi.
Makale Türkçe + İngilizce mevcuttur.

## Repo yapısı

```
.
├── paper/
│   ├── duran_sicimler_teoremi_II.tex      # Makale kaynağı (Türkçe, v5)
│   ├── duran_sicimler_teoremi_II.pdf     # Derlenmiş makale, TR
│   ├── duran_sicimler_teoremi_II_EN.tex  # Makale kaynağı (İngilizce)
│   └── duran_sicimler_teoremi_II_EN.pdf  # Derlenmiş makale, EN
├── CITATION.cff
└── LICENSE
```

## Derleme

```bash
cd paper
pdflatex -interaction=nonstopmode duran_sicimler_teoremi_II.tex
pdflatex -interaction=nonstopmode duran_sicimler_teoremi_II_EN.tex
```

## Atıf

```bibtex
@misc{meral2025duranII,
  author = {Fahri Meral},
  title  = {Duran Sicimler Teoremi: Görelilik, Faz Dönüşümü ve Bilginin Kozmolojik Döngüsü},
  year   = {2025},
  doi    = {10.5281/zenodo.YYYYYYY},
  url    = {https://github.com/KULLANICI/duran-sicimler-II}
}
```

## Lisans

Makale metni (TR + EN): [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — Fahri Meral (2025).
