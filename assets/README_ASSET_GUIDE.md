# Asset Guide

The `assets` folder is reserved for public-safe presentation assets only. Every asset should help buyers understand the product without exposing private implementation details.

## Required / Recommended Assets

| Asset | What It Should Show | What It Must Avoid | Recommended Size | Why It Helps Buyers |
| --- | --- | --- | --- | --- |
| `hero-dashboard.png` | Polished high-level dashboard impression with placeholder data. | Real customer data, private routes, internal controls, provider settings. | 1600 x 900 | Gives buyers an immediate sense of product quality. |
| `dashboard-preview.png` | Operator review surface with sanitized lead and workflow states. | Real leads, sensitive notes, admin-only details, database identifiers. | 1600 x 1000 | Shows how a user would review qualified leads. |
| `demo-flow.gif` | Short walkthrough from intake to review using fake data. | Private URLs, debugging panels, credentials, provider dashboards. | 1280 x 720 | Makes the workflow tangible for non-technical buyers. |
| `architecture-overview.png` | Conceptual diagram: intake, AI qualification, review, billing readiness, handoff. | Database schema, exact endpoints, security-control internals, deployment secrets. | 1600 x 900 | Helps technical buyers understand the system shape safely. |
| `implementation-status-preview.png` | Visual status matrix showing current, verification needed, and planned areas. | Internal issue lists, private backlog details, sensitive readiness notes. | 1400 x 900 | Builds trust by showing maturity boundaries honestly. |
| `workflow-automation.png` | RevOps workflow map with safe placeholder process labels. | Client-specific processes, private automations, hidden provider details. | 1600 x 900 | Helps agencies and consultants see use cases quickly. |
| `agency-use-case.png` | Agency deployment concept for client lead qualification. | Real client brands, contracts, pricing, private client data. | 1600 x 900 | Speaks directly to agency buyers and implementation partners. |
| `developer-stack.png` | High-level stack categories and provider roles. | Secret names, exact configuration, internal routes, private architecture. | 1600 x 900 | Gives developers enough orientation without unsafe detail. |

## General Rules

Acceptable assets:

- Public product screenshots with placeholder data
- Demo visuals with fictional content
- Logo files approved for public use
- Conceptual diagrams that do not reveal private architecture
- Buyer presentation images

Do not add:

- Screenshots containing customer data
- Credentials, tokens, keys, or private configuration
- Internal architecture diagrams
- Database schema images
- Payment provider configuration
- Webhook or integration internals
- Private deployment screenshots
- Admin-only product screens unless fully sanitized

Before adding assets, confirm that they are safe for a public repository and do not reveal private implementation details.

