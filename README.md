# Computational Techniques for Sustainable Energy Materials

Notes accompanying the Computational Tools lectures for the 2025 Neutrons for Sustainable Energy training school at KTH Stockholm.

**[Read the notes](https://bjmorgan.github.io/neutrons_for_sustainable_energy/)**

## Overview

These notes cover computational methods relevant to neutron scattering studies of energy materials. The goal is to help neutron scientists become literate consumers of computational work and effective collaborators with modellers.

The material is organised in three parts:

| Part | Topic |
|------|-------|
| I | Calculating E(r) — classical potentials, DFT, machine-learned potentials |
| II | Structure and Dynamics — geometry optimisation, phonons, molecular dynamics |
| III | Configurational Disorder — Monte Carlo, cluster expansion, short-range order |

## Building locally

The notes are written using [bookdown](https://bookdown.org/). To build locally:
```r
install.packages("bookdown")
bookdown::render_book("index.Rmd")
```

Output appears in `_book/`.

## Author

Benjamin J. Morgan, University of Bath

## Licence

This work is licensed under a [Creative Commons Attribution 4.0 International Licence](https://creativecommons.org/licenses/by/4.0/).
