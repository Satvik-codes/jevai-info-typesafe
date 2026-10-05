# jevai-info-typesafe

Internal reference page documenting **`typesafe/jev-1.13`**, a System One decision model from TypeSafe AI, served via DefAPI.

A single static page — no build step, no dependencies.

## Contents

- Model specification and commercial terms
- The three decision primitives: `noul`, `choice`, `score`
- Request lifecycle
- Comparative analysis against a standard language model
- Operational notes on cost and confidence handling

## Local development

Open `index.html` directly, or serve the folder:

```bash
npx serve .
```

## Deployment

Push to GitHub, then import the repository in Vercel. No framework preset and no build command are required — the repository is served as static files, with `index.html` as the entry point.

## Note

This page contains documentation only. No API credentials are stored in this repository.
