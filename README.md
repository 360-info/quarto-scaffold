# quarto-scaffold

Base a new repo off this public template to get started with a reproducible analysis or graphic quickly. The template comes with a [dev container](https://code.visualstudio.com/docs/remote/containers) in order to get working with 360's data science stack quickly.

## ➕ Adding stories

This repo just keeps the dev environment scaffolding; templates for individual analyses and graphics are kept in the [`quarto-examples`] repo. To bring one of them into your project with [Quarto](https://quarto.org), run (for example):

```shell
quarto use extension 360-info/quarto-examples/360analysis
```

## ✅ Publication checklist

- [ ] Replace this README with [`README-template.md`](README-template.md), adding:
  * `[report title]`
  * `[report summary]`
  * `[report data sources and links]`
  * Any exceptions to [CC BY 4.0](https://creativecommons.org/licenses/by/4.0) licensing
  * `[report repo name]`
  * Any changes that need to be made to reproduction instructions
- [ ] Fill in [`data/README.md`](data/README.md) with the data dictionary, links or other notes needed to understand and re-use the dataset