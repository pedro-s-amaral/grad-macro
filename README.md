# Graduate Macroeconomics

Materials for ECON 503, Advanced Macroeconomics, at Cal State Fullerton.

The repository is organized around two main uses:

- `tutorials/`: short R Markdown tutorials used for math refreshers, optimization, data work, and macroeconomic applications.
- `textbook-exercises/solutions/`: Quarto source files with selected public solutions to textbook exercises.

## Tutorials

Math refresher materials live in `tutorials/math-refresher/`.

- `univariate_derivatives.Rmd`
- `multivariate_derivatives.Rmd`
- `unconstrained_optimization.Rmd`
- `constrained_optimization.Rmd`

Data and filtering tutorials live in `tutorials/data/`.

- `bea_data_tutorial.Rmd`
- `fred_data_tutorial.Rmd`
- `hp_tutorial.Rmd`
- `pwt_data_tutorial.Rmd`

Macroeconomic application tutorials live in `tutorials/macro-topics/`.

- `dispersion.Rmd`
- `kaldor_facts.Rmd`
- `solow_model.Rmd`

The shared stylesheet for these R Markdown files is `tutorials/style.css`.

## Textbook Exercise Solutions

Selected public solution source files live in `textbook-exercises/solutions/` and are named by chapter, for example `chapter-05.qmd`.

Only files intentionally chosen for the public repository should be copied into this folder.

Rendered HTML files are intentionally not tracked. To rebuild a solution locally, render the relevant Quarto file from `textbook-exercises/solutions/`.
