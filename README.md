# Production SaaS Engineering

A public-safe engineering showcase of a privately developed full-stack SaaS application built with production-oriented architecture, structured validation, controlled deployment practices, and bounded AI-assisted workflows.

> **Current status:** active private product engineering project with a verified production runtime. Broader rollout, higher-impact permissions, and public marketplace release remain separate gated decisions.

## At a glance

| Area | Current evidence |
| --- | --- |
| Application | Embedded full-stack SaaS product with authenticated server-side workflows |
| Stack | TypeScript, Node.js, Remix, Prisma, PostgreSQL-ready persistence |
| Platform | Embedded commerce-platform integration |
| Validation | Automated tests, type checks, source-boundary checks, build validation |
| Operations | Production deployment, health checks, recovery checkpoints, manual release controls |
| AI | Narrow, explicit, review-oriented server-side AI assistance with deterministic fallback |
| Governance | Fail-closed feature controls and explicit separation between permission, preview, and mutation |

## What I am building

The private application is a production-oriented SaaS product for merchants operating inside a larger commerce ecosystem. The public version intentionally abstracts the commercial use case and focuses on the engineering work required to make the application reliable, auditable, and safe to evolve.

The project has included:

- full-stack product development;
- embedded-platform authentication and navigation;
- database-backed domain modelling;
- billing and compliance workflows;
- deterministic auditing and review flows;
- controlled AI-assisted functionality;
- staged deployment and recovery discipline;
- feature gating for higher-impact operations.

## What this demonstrates

- full-stack TypeScript / Node.js application engineering
- Remix server/client boundary design
- Prisma-backed persistence and domain modelling
- embedded-platform integration
- API and authenticated workflow development
- production deployment and health-check practices
- Git/GitHub branch and pull-request discipline
- regression testing and checkpoint-based validation
- controlled AI integration rather than unrestricted automation
- safe handling of higher-impact permissions and write operations

## Technical areas

`TypeScript` · `Node.js` · `Remix` · `Prisma` · `PostgreSQL` · `Shopify App Architecture` · `APIs` · `Git/GitHub` · `Render` · `Testing & Validation` · `AI-assisted Workflows`

## Engineering principles

1. **Read and write authority are separate.** A working feature foundation does not imply permission to perform a consequential mutation.
2. **Production controls fail closed.** Missing or invalid configuration should not silently broaden capability.
3. **Deployment is intentional.** Source changes and production deployment are treated as separate actions.
4. **AI remains bounded.** AI-assisted flows are explicit, narrow, review-oriented, and backed by deterministic fallback behaviour.
5. **Validation is checkpoint-specific.** Evidence is tied to reviewed states rather than assumed from intent.
6. **Recovery matters.** Stable checkpoints and controlled rollback/recovery references are part of normal engineering discipline.

## Public-safe workflow example

See [`examples/sanitized-workflow.md`](examples/sanitized-workflow.md) for a generic workflow showing how an authenticated request can pass through validation, business logic, persistence, review, and a gated higher-impact action without exposing the underlying commercial product logic.

## Repository scope

This is **not** the private commercial product repository. It is a sanitized engineering portfolio intended for professional review.

Intentionally excluded:

- the private product name, branding, pricing, and differentiated business proposition;
- customer/merchant data and private operational records;
- exact production URLs, deployment identifiers, and environment values;
- internal roadmap stage names and authorization records;
- sensitive permission/mutation implementation details;
- secrets, credentials, tokens, and live account configuration.

## Private Development Repository

This public repository is a selectively disclosed portfolio representation of a broader private development project. The private repository contains the complete product-development history, source implementation, commits, validation evidence, production-engineering records, and project documentation that are intentionally excluded here for IP, privacy, security, commercial, or operational reasons.

**Additional private implementation evidence may be shared selectively during a relevant technical interview or professional review, subject to appropriate confidentiality and disclosure considerations.**

## Current limitations

The existence of a production runtime is not presented as evidence that every planned high-impact capability is active. Broader writes, beta release, and public marketplace submission remain controlled decisions rather than implied features.

## Additional notes

- [`docs/architecture-and-delivery.md`](docs/architecture-and-delivery.md) — application and delivery structure
- [`docs/testing-and-governance.md`](docs/testing-and-governance.md) — validation and governance approach
- [`docs/project-maturity.md`](docs/project-maturity.md) — what the private application currently demonstrates

---

**Why this repository exists:** to show real-world software-engineering and production discipline without exposing the private product's commercial differentiation or sensitive operational details.