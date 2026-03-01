# Hugo Migration Workspace

This folder contains the Hugo version of the site.

## Domain and GitHub Pages compatibility

- Canonical base URL: `https://federicomorando.net/`
- GitHub Pages custom domain file: `static/CNAME`
- Jekyll bypass file: `static/.nojekyll`

## Build locally

```bash
hugo --source hugo
```

Output is generated in `hugo/public`.

## Deploy via GitHub Actions

Workflow: `.github/workflows/hugo-pages.yml`

It builds from `hugo/` and deploys `hugo/public` to GitHub Pages.

## Notes

- Legacy Pelican output in repository root has been left untouched for now.
- Converted content is under `hugo/content/`.
