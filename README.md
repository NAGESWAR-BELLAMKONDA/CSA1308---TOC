# SocialLens CFG
A professional, explainable web prototype for structural analysis of social-media news claims using Context-Free Grammar (CFG) concepts.

> Academic scope: CFG analysis can identify structural patterns and linguistic signals. It does **not** verify factual truth. Results are structural-risk indicators, not truth verdicts.

## Live deployment
GitHub Actions deploys the static site to GitHub Pages after pushes to `main`.

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
npm run preview
```

## Features
- Interactive claim analyzer
- CFG-inspired sentence segmentation and phrase classification
- Explainable structural signals with score breakdown
- Grammar explorer / playground
- Demonstration dataset and analysis history (local browser storage)
- Export analysis report as JSON or text
- Responsive dashboard and GitHub Pages deployment

## Academic integrity
The classifier is a transparent heuristic demonstration of TOC/CFG concepts. It is not a trained model, does not access live social networks, and cannot independently confirm news claims.
