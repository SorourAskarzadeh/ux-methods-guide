# UX Methods Guide

A small documentation website with three short, practical guides to common UX research methods: heuristic evaluation, closed card sorting, and usability testing with the System Usability Scale (SUS). Each guide uses one of my own design projects as an example.

The site is built with [Quarto](https://quarto.org) from Markdown source files and published with GitHub Pages.

Live site: [UX Methods Guide](https://sorouraskarzadeh.github.io/ux-methods-guide/)

## Project structure

- `index.qmd`: home page with a short description of each guide
- `page1.qmd`, `page2.qmd`, `page3.qmd`: the three guides
- `_quarto.yml`: site settings (title, navigation, theme, footer)
- `styles.css`: custom styling for the home page header
- `images/`: screenshots and the header image
- `docs/`: the generated website (do not edit by hand)

## How to update the site

1. Edit the `.qmd` files.
2. Run `quarto render` to rebuild the site into `docs/`.
3. Commit and push the changes to GitHub. The live site updates in a few minutes.