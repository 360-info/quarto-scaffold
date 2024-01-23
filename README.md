# 360info Quarto scaffold

Use this repo as a template to quickly start a 360info project in [Quarto](https://quarto.org).

This template is designed to be used as a [dev container](https://containers.dev). You can work inside the container [locally using Docker and VScode](https://code.visualstudio.com/docs/devcontainers/containers), or you can open the project in GitHub Codespaces:

![Screenshot of the code menu on a GitHub repository, showing the Codespaces tab](https://github.com/360-info/quarto-scaffold/assets/6520659/dc1afe15-2c1a-4a5a-8861-e3e131dacc02)

Add dependencies, such as R package or other tools, using the `.devcontainer/devcontainer.json` file.

The project's `README.md` will be generated from `README.qmd`, not this file. Fill the frontmatter in there to customise the README. When the project is ready for publication, overwrite this file with the rendered `out/README.md`.

## Adding analyses or embeds

This template just includes the project scaffolding to et started. To create an analysis or embed document, use [`360-info/quarto-templates`](https://github.com/360-info/quarto-templates):

```bash
quarto use templaye 360-info/quarto-templates/360-embed
```
