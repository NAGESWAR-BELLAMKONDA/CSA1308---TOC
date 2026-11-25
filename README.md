# SocialLens CFG

**Academic title:** Fake News Detection on Social Media Platforms Using Context-Free Grammar Analysis  
**Course:** CSA1308 — Theory of Computation · Slot D

SocialLens is an explainable, grammar-inspired analysis workspace for studying linguistic patterns in social-media claims. It is a ToC demonstration and human verification aid—not an automated truth detector.

## Deployment

Expected GitHub Pages URL (deployment not yet confirmed): https://nageswar-bellamkonda.github.io/CSA1308---TOC/

Actions: https://github.com/NAGESWAR-BELLAMKONDA/CSA1308---TOC/actions
Pages settings: https://github.com/NAGESWAR-BELLAMKONDA/CSA1308---TOC/settings/pages

If needed, set repository Pages **Source** to **GitHub Actions**.

## Current interactive modules

- Overview: animated product dashboard, scenarios and feature overview
- Analyze: text input, TXT import, heuristic signal groups, indicator score, word/sentence statistics, grammar membership samples, JSON export
- Batch Lab: multiple claims separated by `---`; CSV export
- Compare: compare two claims' language patterns and statistics
- Grammar Studio: editable CFG production rules and simplified CYK membership tester with chart
- Insights: summaries from browser-local history
- History: recent analyses, reopen and clear
- Project: purpose, academic mapping, limitations and roadmap

## UX

- Responsive desktop/mobile layout
- Glassmorphism cards and animated ambient background
- Animated orbital hero visualization
- Micro-interactions and toast feedback
- Dark/light theme switch
- Reduced-motion preference support
- Local-first prototype storage

## Stack

React, Vite, CSS, browser localStorage, GitHub Actions and GitHub Pages.

## Local run

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Theory of Computation

- CFG tuple: G = (V, Sigma, P, S)
- Terminals and non-terminals
- Production rules and start symbol
- Simplified CYK membership demonstration

The CYK demo supports terminal unary rules and binary non-terminal rules. It is not a complete natural-language parser.

## Responsible-use boundary

Language cues and grammar membership cannot establish factual truth. Scores are heuristic review indicators—not truth, credibility or probability scores. This prototype does not scrape social platforms, access external sources, perform source verification or use a trained AI model.

## Production-readiness status

This is a frontend prototype with static hosting. It does not yet contain a production backend, user accounts, multi-user database, live social-platform integrations, evidence retrieval, authentication, server-side audit records, rate limiting, security monitoring, formal evaluation or automated tests. These are future phases, not current features.

## Roadmap

1. Unit/component/end-to-end tests and CI quality gates
2. Curated multilingual dataset and evaluation metrics
3. Backend/API, authentication, database, rate limits, logs and monitoring
4. Evidence retrieval and source provenance with human review
5. Multilingual UX and accessibility evaluation
6. Security, privacy and abuse testing; responsible AI governance

## Student

Nageswar Bellamkonda · Register No. 192372005  
Faculty: Thiyagarajan A. · SIMATS
