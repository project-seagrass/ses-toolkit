# Seagrass Social-Ecological Monitoring Toolkit

A Quarto website for the **Seagrass Social-Ecological Monitoring Toolkit**.

Subtitle: **A practical learning guide for monitoring seagrass conservation across people, nature and place.**

## What is included

- `_quarto.yml` website configuration
- `.qmd` pages for the learning platform
- custom CSS in `assets/css/styles.css`
- Project Seagrass logo placeholder in `assets/img/project-seagrass-logo.svg`
- Figure 1 from the manuscript in `assets/img/figure-1.png`
- themed references and a full reference list

## How to preview locally

Install Quarto, then run:

```bash
quarto preview
```

## How to render

```bash
quarto render
```

The rendered site will be created in `_site/`.

## GitHub Pages

1. Upload this folder to a GitHub repository.
2. Render the site locally or set up a GitHub Action for Quarto.
3. Publish the `_site/` folder using GitHub Pages.

## Replacing the logo

Replace:

```text
assets/img/project-seagrass-logo.svg
```

with the official Project Seagrass logo file. Keep the same file name or update `_quarto.yml`.

## Figure 1

Figure 1 is included here:

```text
assets/img/figure-1.png
```

It appears on the homepage and framework page with a plain-language caption.

## Notes

This first version intentionally does not include templates or downloads. It is structured as a learning platform with worked examples and scientific interpretation callouts.
