# ajairup.github.io

Personal academic website of Ajai Ruparelia, live at <https://ajairup.github.io>.

Built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme. Pushes to `main` are built and deployed to the `gh-pages` branch by `.github/workflows/deploy.yml`.

## Editing

- Bio and profile: `_pages/about.md`
- Publications: `_bibliography/papers.bib`
- CV: `assets/json/resume.json` (PDF at `assets/pdf/ARuparelia_CV.pdf`)
- News: `_news/`
- Social links: `_data/socials.yml`

## Local preview

```bash
docker compose pull && docker compose up
```

Then open <http://localhost:8080>.
