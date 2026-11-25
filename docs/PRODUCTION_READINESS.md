# SocialLens CFG — Full-stack / production roadmap

## Current delivered prototype
- React + Vite single-page UI, responsive design
- Animated glassmorphism theme with dark/light mode
- Single-claim linguistic signal analysis
- Transparent pattern explanation
- Batch claim review and CSV export
- Side-by-side claim comparison
- Editable CFG rules and simplified CYK membership chart
- Browser-local history and JSON export
- Verification checklist download
- GitHub Actions static build and Pages deployment configuration

## Honest current boundaries
This is a static frontend prototype. It has no server-side database, identity/authentication, backend API, real-time social feeds, source retrieval, evidence provenance service, trained classifier/LLM, user collaboration, moderation workflow, server-side logging, automated test suite, or formal accuracy/quality evaluation. Do not represent roadmap items as already implemented.

## Full real-product requirement checklist

### Product and UX
- [ ] User research and accessibility review
- [ ] Product personas and user journeys
- [ ] Design system / tokens / component library
- [ ] Keyboard navigation, screen-reader labels, focus management
- [ ] Responsive tablet, mobile, desktop
- [x] Responsive current UI
- [x] Dark/light mode
- [x] Reduced-motion CSS support

### Frontend
- [x] SPA route-like module navigation
- [x] Analysis input and TXT import
- [x] Transparent findings
- [x] Batch review
- [x] Comparison
- [x] Grammar playground
- [x] Browser-local history
- [x] JSON / CSV export
- [ ] Browser error handling and analytics (privacy-preserving opt-in)
- [ ] Accessibility audit and UX test

### Backend and platform
- [ ] REST API or GraphQL with versioning
- [ ] Server-side validation and input limits
- [ ] Authentication / authorization and role-based access
- [ ] User and workspace model
- [ ] Database with migrations and backup/restore
- [ ] Queue for long-running research jobs
- [ ] Rate limiting, quotas, abuse prevention
- [ ] API documentation / OpenAPI
- [ ] Secret management and environment configuration
- [ ] Structured logs, metrics, tracing and health checks
- [ ] Data retention, deletion and export controls

### Evidence / future AI capabilities
- [ ] Optional source search with source allowlist/quality rubric
- [ ] Retrieval with URLs, timestamps, source provenance and snippets
- [ ] Claim decomposition into checkable subclaims
- [ ] Evidence table: supports / contradicts / context / unknown
- [ ] Citation-backed summaries
- [ ] Retrieval freshness and duplicate-source detection
- [ ] Image/video provenance tools (separate feature and evaluated limits)
- [ ] Multilingual support with language-specific evaluation
- [ ] AI output guardrails and prompt-injection defenses
- [ ] Human review and correction feedback loop
- [ ] Model/data version records
- [ ] Clear distinction among grammar acceptance, linguistic cues, evidence and factual conclusion

### Security and privacy
- [ ] Threat model
- [ ] Dependency scanning and update policy
- [ ] Static analysis and secrets scanning
- [ ] OWASP web security review
- [ ] XSS/CSRF/CORS policy appropriate to backend architecture
- [ ] Secure authentication and session management
- [ ] Encryption in transit and at rest where sensitive data is stored
- [ ] User data deletion and retention policy
- [ ] Consent and transparency for any external API
- [ ] Abuse / safety / incident-response process

### Quality engineering
- [ ] Unit tests for text normalization, signal rules, grammar parsing and CYK
- [ ] Component tests
- [ ] End-to-end tests for main user journeys
- [ ] Regression dataset with labeled expectations (not used to claim truth without evaluation)
- [ ] CI gates: lint, type-check, tests, production build
- [ ] Performance and accessibility checks
- [ ] Test environment and production environment separation
- [ ] Deployment smoke test and rollback procedure

### Operations / deployment
- [x] GitHub Actions build/deploy workflow configured
- [ ] Confirm GitHub Pages Source = GitHub Actions
- [ ] Confirm successful workflow and live URL
- [ ] Domain, TLS, CDN and production environment (if expanding)
- [ ] Backend deployment and database provisioning
- [ ] Monitoring, alerting and uptime checks
- [ ] Backups and disaster recovery
- [ ] Release tags and changelog
- [ ] Rollback / incident procedure

## Suggested staged implementation

### Phase 1 — Academic prototype (current)
Frontend, grammar demonstration, explainability, demo examples, exports and Pages deployment.

### Phase 2 — Engineering quality
Add tests, input normalization, parser correctness cases, lint/type checking, accessibility checks and CI build gates.

### Phase 3 — Full-stack platform
Backend service, API, user identity, database, workspaces, secure storage, audit events, rate limits and deployment.

### Phase 4 — Evidence research assistant
Source discovery, provenance, claim decomposition, evidence comparison and citation-backed summaries. The app must show evidence and uncertainty instead of claiming a universal truth score.

### Phase 5 — International readiness
Multilingual pipelines, locale-aware UX, accessibility, privacy/legal review, evaluation datasets and regional source-quality guidance.

## Academic-safe demonstration
Demonstrate the CFG/CYK module as a formal-language membership example. Demonstrate signal analysis as transparent heuristics. Demonstrate verification as a separate human process. Never state that CFG or heuristic cues prove misinformation.
