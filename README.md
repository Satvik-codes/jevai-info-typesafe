# jevai-info-typesafe

Internal reference page documenting **Jev 1.13**, the first System One decision model from [TypeSafe AI](https://typesafe.ai).

A single static page — no build step, no dependencies.

## Contents

- Model identity, owner, and naming
- The three decision primitives: `noul`, `choice`, `score`
- Access routes: TypeSafe's first-party endpoint, official SDKs, and third-party gateways
- Comparative analysis against a standard language model
- Operational notes on cost, confidence, and known limits

## Attribution

Jev is built and owned by **TypeSafe AI**. Services such as DefAPI and OpenRouter resell access to
the same upstream model under their own pricing; they are gateways, not the model owner.

## Local development

Open `index.html` directly, or serve the folder:

```bash
npx serve .
```

## Deployment

Push to GitHub, then import the repository in Vercel. No framework preset and no build command are required — the repository is served as static files, with `index.html` as the entry point.

## Note

This page contains documentation only. No API credentials are stored in this repository.
