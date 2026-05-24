# kennyholm.github.io

Personal website built with [Quarto](https://quarto.org).

## Structure

- `index.qmd` — About page
- `code.qmd` — Code & Papers (MATLAB, Julia)
- `links.qmd` — External links
- `disclaimer.qmd` — Disclaimer
- `assets/` — Downloads (MATLAB/Julia code, papers)
- `textbook/` — Rendered textbook (generated from [nyholm-textbook](https://github.com/KenNyholm/nyholm-textbook))

## Deploying

Render the textbook first, then publish the site:

```bash
cd ../nyholm-textbook
quarto render --to html

cd ../KenNyholm.github.io
quarto publish gh-pages --no-prompt
```
