# SocialLens CFG — Project Scope

## Title
Fake News Detection on Social Media Platforms Using Context-Free Grammar Analysis

## Implemented software prototype
SocialLens CFG is an educational web application that examines sentence structure and configured language signals. It offers a text input workspace, transparent signal breakdown, a simplified CFG-inspired parse view, a production-rule playground, local browser history, and JSON export.

## Theoretical mapping
- Grammar tuple: G = (V, Σ, P, S)
- Sentence symbol S
- Noun phrase (NP) and verb phrase (VP) labels
- Production rules and illustrative derivation
- Parse-tree visualization

## Scope boundary
This prototype is not a factual fact-checking system. It has no live social-media ingestion, external verification, or trained model. Signal scoring is heuristic and explainable. CFGs model syntactic structure; factual truth cannot be determined from syntax alone.

## Deployment
Vite builds the React application into a static dist directory. GitHub Actions builds and deploys it to GitHub Pages on pushes to main.
