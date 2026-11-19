# Statistics for Machine Learning

Quarto book for the course *Statistics for Machine Learning* (second-year Bioinformatics).

- The rendered website is in `docs/`. It is served by GitHub Pages.
- The chapter sources are the `.qmd` files in this folder.
- `_freeze/` stores the results of the R code, so the book can be re-rendered without re-running every chapter. Keep it in the repository.

## Rebuild

Open this folder as a project in RStudio, install the packages listed in the preface, and run in the Terminal:

```
quarto render
```

The website in `docs/` is then updated. Commit and push `docs/` together with the changed `.qmd` files.

## Publish with GitHub Pages

In the repository on GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/docs`.

Figures in `Figs/` that show "Figure to be added" are placeholders. Replace each with the real image under the same file name.
