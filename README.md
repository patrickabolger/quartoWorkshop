# Quarto workshop revealjs deck

A GitHub Pages-ready Quarto project for a one-hour undergraduate workshop.

## Local preview

Open `index.qmd` in RStudio and select **Render**, or run:

```bash
quarto preview index.qmd
```

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Add `index.qmd`, `_quarto.yml`, `styles.css`, and the prompt template.
3. Render the project. The website output is written to `docs/`.
4. Commit and push the source files and the `docs/` folder.
5. In the repository, open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Choose the main branch and the `/docs` folder, then save.

The published `docs/index.html` is the revealjs slide deck.
