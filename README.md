# SocialLens CFG — Fake News Structural Analysis

**TOC project:** Fake News Detection on Social Media Platforms Using Context-Free Grammar Analysis

SocialLens is a premium-style educational web prototype that examines social-media claims using CFG-inspired sentence structure and transparent linguistic pattern signals.

> **Important scope:** This is not a fact-checking or truth-classification tool. Grammar and linguistic signals cannot establish whether a claim is true. It is an explainable educational demonstration of Theory of Computation concepts.

## Demo / deployment

GitHub Pages deployment is configured with GitHub Actions. After the first successful workflow deployment, the project site is expected at:

https://nageswar-bellamkonda.github.io/CSA1308---TOC/

## Features

- Interactive social claim text workspace
- Four built-in example inputs
- CFG-inspired sentence segmentation and simplified NP / VP structure visualization
- Transparent language signal breakdown
- Explainable indicator score (heuristic, not truth probability)
- Editable production-rule Grammar Lab
- Illustrative derivation steps
- Browser-local analysis history
- JSON export of an analysis
- Responsive interface for desktop and mobile
- Automated Vite build and GitHub Pages deploy workflow

## Technology

React 18 · Vite · CSS · GitHub Actions · GitHub Pages

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

## Deployment

Workflow: `.github/workflows/deploy.yml`

Every push to `main` runs the build and deploy jobs. The repository's Pages publishing source must be set to **GitHub Actions** under **Settings → Pages** if it is not already configured.

## Academic connection

The application visualizes and discusses grammar components such as the grammar tuple `G = (V, Σ, P, S)`, terminals, non-terminals, production rules, sentence segmentation, phrase structure, and illustrative derivation.

## Student details

- **Student:** Nageswar Bellamkonda
- **Register No.:** 192372005
- **Course:** Theory of Computation
- **Course code:** CSA1308
- **Slot:** D
- **Faculty:** Thiyagarajan A.
- **Institution:** SIMATS

