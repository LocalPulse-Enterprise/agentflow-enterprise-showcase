# Security Posture

AgentFlow Enterprise is presented as a production-conscious SaaS foundation with a buyer-safe public documentation layer. This page describes principles and review expectations, not private implementation details.

## Public Repository Boundary

This public repository contains no private source code, secrets, credentials, deployment configuration, database schema, checkout internals, webhook handlers, or operational procedures.

Its purpose is to support buyer review while protecting the private system from unnecessary exposure.

## Security Principles

AgentFlow Enterprise should be evaluated against these principles:

- Keep sensitive configuration out of public repositories
- Manage secrets through secure deployment environment variables in real deployments
- Protect operator dashboards with authenticated access
- Treat webhook processing as a server-side trust boundary
- Use provider signature verification principles for webhook events
- Keep AI provider calls server-side
- Avoid exposing internal implementation details in public documentation
- Require controlled access for private technical diligence
- Review data handling before commercial or client deployment

## Authenticated Dashboard Principle

Dashboard access should be limited to authorized users and reviewed during private diligence. Public documentation does not disclose access-control internals or private dashboard logic.

## Webhook Signature Verification Principle

Webhook safety should be based on provider signature verification, server-side processing, event validation, and careful handling of failures. Exact verification logic and event handling remain private.

## Server-Side AI Calls Principle

AI qualification should be handled through server-side boundaries so provider credentials and sensitive workflow logic are not exposed to public clients.

## Certification Status

This repository makes no claim of:

- SOC 2 certification
- ISO certification
- Formal penetration testing
- Enterprise security audit completion
- Regulated-industry compliance approval

Any future certification, audit, or assessment should be supported by evidence from the relevant reviewer or provider.

## Responsible Disclosure

Security concerns should be reported to [contact@agentflow-enterprise.com](mailto:contact@agentflow-enterprise.com).

Please do not submit sensitive vulnerabilities through public GitHub issues. There is no public bug bounty program currently.

## What This Public Repository Intentionally Does Not Reveal

This repository intentionally does not reveal:

- Backend logic
- Database schema
- API route internals
- Webhook implementation
- Checkout internals
- Operational runbooks
- Security control internals
- Provider configuration
- Production access details

## Buyer Security Review

Before production or client use, buyers should review:

- Authentication and access boundaries
- Data collection and retention assumptions
- Provider configuration and permission model
- Payment and webhook safety evidence
- Logging and monitoring behavior
- Incident response expectations
- Dependency posture
- Support and maintenance responsibilities

