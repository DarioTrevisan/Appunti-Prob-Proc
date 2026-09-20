# Probabilità e Processi Stocastici (455AA)

Lecture notes for the course *Probabilità e Processi Stocastici* (455AA), in the
Degree Programme in Robotics and Automation Engineering at the University of
Pisa.

The notes are written in Italian and are authored by Dario Trevisan. They are
published as a Quarto book and include executable R examples.

## Build the book

Install:

- [Quarto](https://quarto.org/)
- [R](https://cran.r-project.org/)
- the R packages used by the examples, as required by the source files

From the repository root, render the complete book with:

~~~sh
quarto render
~~~

To preview it locally while editing:

~~~sh
quarto preview
~~~

The rendered book is written to the _book/ directory, which is intentionally
excluded from version control.

## Structure

- index.qmd — introduction
- eventi.qmd — elementary probability
- VA_generali.qmd — general random variables
- 04-VA_indicatori.qmd — characteristic indicators
- 05-VA_gaussiane.qmd — Gaussian random variables
- 06-processi_discreti.qmd — discrete-state stochastic processes
- 07-processi_continui.qmd — continuous-state stochastic processes
- 08-teoremi_limite.qmd — limit theorems
- 10-R-intro.qmd — introduction to R
- 11-fourier.qmd — Fourier transform

## Contributing corrections

Corrections and suggestions are welcome. Please open an issue or pull request
with the relevant chapter and a short description of the change.

## License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/). See [LICENSE](LICENSE) for details.
