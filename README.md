# 360info report template

What's this report all about? What kind of charts or analysis have we done?

## Use + Remix rights

![[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0)](https://mirrors.creativecommons.org/presskit/buttons/80x15/png/by.png)

These charts, as well as the analyses that underpin them, are available under a Creative Commons Attribution 4.0 licence. This includes commercial reuse and derivates.

<!-- Do any of the data sources fall under a different licence? If so, describe the licence and which parts of the data fall under it here! if most of it does, change the above and replace LICENCE.md too -->

Data in these charts comes from:

* Data sources here (with links!)

**Please attribute 360info and the data sources when you use and remix these visualisations.**

## Reproduce the analysis

We typically publish graphics using [Quarto](https://quarto.org) notebooks, which can be found in the`*.qmd` files. Quarto allows reproducible analysis and visualisation to be done in a mix of languages, but we typically use [R](https://r-project,.org) and [Observable JS](https://observablehq.com/@observablehq/observables-not-javascript).

You'll need to:
- [Download and install Quarto](https://quarto.org/docs/get-started)
- [Download the install R](https://www.r-project.org)
- Satisfy the R package dependencies. In R:
  * Install the [`renv`](https://rstudio.github.io/renv) package with `install.packages("renv")`,
  * Then run `renv::restore()` to install the R package dependencies.
  * (For problems satisfying R package dependencies, refer to [Quarto's documentation on virtual environments](https://quarto.org/docs/projects/virtual-environments.html).)

Now, render the `.qmd` files to the `/out` directory with:

```sh
quarto render
```

## Help

<!-- replace `report-template` with the name of this repo in the link below  -->

If you find any problems with our analysis or charts, please feel free to [create an issue](https://github.com/360-info/report-template/issues/new)!
