# Alisson Ramos · Selected Product Work

**Applied AI, operational software and multilingual web applications.**

I build products that connect a user-facing experience to the work behind it: generation jobs and credits, customer relationships and sales workflows, content publishing and service delivery.

This collection brings together independently operated products, a partner-built platform and client deliveries. Each case explains the problem, my role, the implemented scope and the decisions behind the application.

## Products

| Project | What it does | My role | Current stage |
| --- | --- | --- | --- |
| [TTSELEVEN](https://github.com/alissonramosz/ttseleven-case-study) | Speech generation, asynchronous jobs, customer credits and audio history | Owner, developer and operator | Live; marketplace sales |
| [Flowork](https://github.com/alissonramosz/flowork-case-study) | Real-estate CRM, properties, appointments, negotiations, contracts and AI-assisted service | Product-development partner and full-stack builder | Pilot at Imobgreen (partner's agency); pre-commercial |

## Client applications

| Project | Delivery | Open the project |
| --- | --- | --- |
| [Temple of Earth and Star](https://github.com/alissonramosz/temple-earth-and-star-case-study) | Service platform, CMS, blog, customer area, booking workflows and birth-chart calculation | [Live website](https://www.templeearthstar.com) |
| [Travessia do Sol](https://github.com/alissonramosz/travessia-do-sol-case-study) | Retreat-house website in EN/FR/PT, interactive stay planner and a CMS for retreats, testimonials and photos | [Delivered site preview](https://preview.travessiadosol.com) |
| [Déborah Pirata](https://github.com/alissonramosz/deborah-pirata-case-study) | Artist portfolio in EN/PT/FR with responsive design and motion | [Live portfolio](https://deborah-pirata.vercel.app) |

TTSELEVEN and Flowork link to their real application entry points from their cases; operational features require an account. Travessia's link is the delivered preview, not the previous website still on its main domain.

## Recurring product decisions

- **Applied AI:** connect model outputs to usable workflows, account state and human follow-up.
- **Reliable state transitions:** separate a request from its completion, a draft from publication, and an enquiry from a confirmed booking.
- **Operator autonomy:** give the person running the business practical content and management tools.
- **International UX:** handle language, date and time meaning explicitly rather than treating them as presentation details.

Not every project needs AI. The client applications also document frontend, CMS and domain-specific engineering in their own right.

## Technology across the projects

| Project | Interface | Backend and data | Domain-specific work |
| --- | --- | --- | --- |
| TTSELEVEN | React, JavaScript, Vite | Node.js, Express, PostgreSQL, Sequelize, object storage | Speech-service integration, generation jobs and customer credits |
| Flowork | TypeScript, React, Vite | Node.js, Express, PostgreSQL, external APIs | Connected agency workflows and AI-assisted service |
| Temple of Earth and Star | TypeScript, Next.js, React | Supabase, PostgreSQL, SQL, Stripe | CMS, bookings, customer area and chart calculation |
| Travessia do Sol | TypeScript, Next.js, React | Supabase, PostgreSQL, SQL, object storage | Multilingual CMS, media processing and stay planning |
| Déborah Pirata | TypeScript, Next.js, React | No custom database required for this scope | Localized content, GSAP / Lenis motion and responsive interaction |

Each case explains what those technologies do in the application. The public diagrams are conceptual; they do not publish private schemas, infrastructure addresses or business rules.

## Development workflow

I use **Claude Code**, **Codex** and **OpenClaw** as development and orchestration tools. The workflow combines repository context, scoped tasks, implementation, checks and release decisions.

The application stack and the tools used to build it are different layers. Listing an AI coding tool is not evidence that an application runs that tool, or that an LLM should replace deterministic domain logic.

## Development backlog

The [issue tracker](https://github.com/alissonramosz/ai-product-portfolio/issues) contains follow-up work and component proposals. Open issues are planned work, not completed product features.

| Work item | State |
| --- | --- |
| [Voice-generation lifecycle and credit handling](https://github.com/alissonramosz/ai-product-portfolio/issues/1) | Open — detailed technical follow-up |
| [Multilingual enquiry routing and human handoff checks](https://github.com/alissonramosz/ai-product-portfolio/issues/2) | Done — released as [handoff-evals v0.1.0](https://github.com/alissonramosz/handoff-evals) |
| [Isolated credit settlement for asynchronous jobs](https://github.com/alissonramosz/ai-product-portfolio/issues/3) | Done — released as [credit-ledger v0.1.0](https://github.com/alissonramosz/credit-ledger) |

## Open-source projects

Small, complete projects written from scratch, with no client or partner code. They are separate from the case studies above.

| Project | What it is | State |
| --- | --- | --- |
| [credit-ledger](https://github.com/alissonramosz/credit-ledger) | Reserve, settle and release credits for async and AI jobs. Idempotent, with an in-memory store and a PostgreSQL store. | v0.1.0; 68 tests, including against a real PostgreSQL server |
| [handoff-evals](https://github.com/alissonramosz/handoff-evals) | Multilingual test cases and a scorer for AI enquiry routing and human handoff (EN, PT, ES, RU), with a runner for any OpenAI-compatible model. | v0.1.0; 51 tests; no language model evaluated yet |

## Source availability

These repositories are public case studies of real work, not open-source releases of the full applications. Client and partner source, data, media assets and operational configurations remain private. The standalone projects listed above state their own scope.

[About me](https://github.com/alissonramosz)
