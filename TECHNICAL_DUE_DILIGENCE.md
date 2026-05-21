# Technical Due Diligence

This document gives buyers a high-level diligence framework without exposing private implementation details. It is suitable for public review and should be paired with a controlled private review for serious acquisition, licensing, or agency deployment discussions.

## What Technical Due Diligence Should Verify

Qualified reviewers should verify:

- Product workflow completeness from lead intake through handoff
- Authentication and protected dashboard behavior
- Tenant-aware assumptions and access boundaries
- Payment and checkout readiness
- Webhook safety behavior
- AI qualification behavior, cost profile, and data handling
- Deployment posture and rollback expectations
- Logging, monitoring, and alerting readiness
- Error handling and operational support model
- Dependency and provider risk
- Test coverage and known gaps
- Commercial readiness for pilot or customer deployment

## Implementation Status Categories

| Category | Meaning |
| --- | --- |
| Implemented | Built or represented in the private product foundation and suitable for private evidence review. |
| Verification needed | Requires live provider evidence, end-to-end testing, or buyer-side confirmation before commercial claims. |
| Planned | Product direction or reasonable next work, not complete unless separately verified. |
| Not claimed | Areas where this public repository makes no certification, customer, revenue, or audit claim. |

## Safe Architecture Overview

At a public level, AgentFlow Enterprise can be understood as:

- A public marketing and demo surface
- A lead intake and qualification flow
- A server-side AI qualification boundary
- A protected operator dashboard concept
- A payment readiness layer
- A Supabase authentication/storage foundation
- A Vercel deployment posture
- Webhook safety principles for provider events
- Documentation designed for buyer diligence

This overview is intentionally non-operational. It does not provide instructions for recreating, attacking, or bypassing the private system.

## Evidence a Buyer Should Request

During private diligence, buyers should request:

- Product walkthrough with realistic lead scenarios
- Demo evidence across the primary workflow
- Source review under NDA
- Authentication and access-control explanation
- Payment provider test evidence
- Webhook validation evidence
- AI provider behavior and prompt-governance review at a safe level
- Deployment and hosting evidence
- Monitoring or staging evidence where available
- Known-risk register
- Post-acquisition or post-license transition plan

## Private Technical Review Requires NDA

Private technical review should require confidentiality terms before sharing sensitive material. The public repository is intentionally limited so that buyers can evaluate fit without exposing private system knowledge.

Materials that may be shared only in a controlled process include:

- Source code
- Private architecture notes
- Provider configuration approach
- Access-control design details
- Payment and webhook implementation evidence
- Deployment and operations materials
- Known issues and remediation plans

## What Remains Private Until NDA

The following should remain private until an appropriate diligence process is in place:

- Application source code
- Database structure
- Provider configuration
- Security-control details
- Event-processing internals
- Payment implementation details
- Dashboard access design
- Deployment settings
- Operational procedures

## What Should Never Be Shared Publicly

Never share:

- Credentials or tokens
- Raw private configuration
- Production access details
- Internal event endpoints
- Database design details
- Sensitive logs
- Customer or prospect data
- Security bypass details
- Operational recovery procedures

## Public Safety Boundary

This document does not include exact API routes, database table names, SQL, access-policy details, environment-variable lists, webhook URLs, admin route names, or implementation-specific secret values.

