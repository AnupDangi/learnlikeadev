# AI & System Design Learning Platform

Guided roadmaps built from 4 source PDFs in this repo. Site renders with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) and hosts on GitHub Pages.

## Local preview

```bash
pip install -r requirements.txt
mkdocs serve
```

Open http://127.0.0.1:8000

## Deploy

Push to `main` triggers `.github/workflows/deploy-pages.yml` (build → upload artifact → deploy).
Then enable: repo Settings → Pages → Source: **GitHub Actions**. Live URL:

`https://anupdangi.github.io/learnlikeadev/`

## Source PDFs (single source of truth)

- `Senior_Cloud_Production_Engineering_Field_Manual.pdf` → `docs/cloud/`
- `Practical_System_Design_Anup_Dangi.pdf` → `docs/system-design/`
- `Practical_AI_Engineering_Anup_Dangi.pdf` → `docs/applied-ai/`
- `60_Days_AI_Engineering_System_Design_Roadmap_Anup_Dangi.pdf` → `docs/60-day/`

Lesson pages expand PDF-by-PDF in later phases. Roadmap indexes are live in Phase 0.
