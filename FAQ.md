# FAQ

## For Agencies

### Can my agency use AgentFlow for multiple clients?

AgentFlow Enterprise is positioned as a foundation that agencies can evaluate for multi-client delivery. Actual multi-client use should be reviewed privately for tenant boundaries, deployment model, service responsibilities, and commercial licensing.

### Can AgentFlow be white-labeled?

White-labeling may be possible as a commercial arrangement, but it is not granted by this public repository. Branding, resale rights, client deployment rights, and support obligations should be agreed in writing.

### How fast can an agency deploy it for a client?

The realistic timeline depends on client requirements, provider configuration, data handling expectations, payment setup, and workflow complexity. A focused pilot can usually be scoped faster than a full client rollout, but commercial deployment should follow live provider verification.

### Can it support client-specific workflows?

Yes at the product direction level. AgentFlow is intended for configurable RevOps workflows such as lead intake, qualification, review, billing readiness, and handoff. Client-specific behavior should be reviewed in a private technical walkthrough.

### What does an agency still need to configure?

An agency should expect to configure branding, provider accounts, deployment settings, billing settings, client workflow assumptions, notification paths, and any CRM or operations handoff. The public repository does not include private configuration values.

## For Senior Developers

### What is the actual tech stack?

At a high level, AgentFlow Enterprise is described as a modern SaaS foundation using Supabase for authentication/storage foundations, Stripe/PayPal checkout readiness, OpenAI-powered qualification flow, Vercel deployment posture, and a protected dashboard experience. Exact implementation details remain private for controlled diligence.

### Is this a starter kit or a production-conscious SaaS foundation?

It should be evaluated as a production-conscious SaaS foundation. That means the product has been shaped around real SaaS concerns such as authentication, dashboard protection, AI workflow boundaries, checkout readiness, deployment, and buyer documentation. It is not represented here as revenue validated or fully enterprise certified.

### How are authentication and protected dashboards handled at a high level?

The product is designed around authenticated access and protected operator-facing areas. Public documentation does not disclose access-control internals, route names, or detailed security logic.

### How are webhooks handled at a high level?

Webhook handling is treated as a server-side trust boundary with signature verification principles and careful event processing expectations. This public repository does not disclose endpoint details, handler code, or provider-specific internals.

### Does the platform include tenant-aware architecture?

The product is positioned with tenant-aware SaaS expectations, but a buyer should verify the exact isolation model, access boundaries, and operational assumptions during private technical review.

### What remains to be verified before commercial operation?

Live provider behavior, payment flows, webhook processing, deployment settings, observability, data handling, customer onboarding, and support processes should be verified before commercial claims or client rollout.

### Can the AI provider be changed?

The current product truth references an OpenAI-powered qualification flow. Provider flexibility may be possible depending on architecture, but any provider change should be reviewed privately for model behavior, cost, latency, safety, and data handling.

### What should remain private during technical review?

Private review should protect source code, database structure, access-control details, provider configuration, event-handling internals, deployment settings, security logic, and operational procedures. These should not be posted in public issues or public documentation.

## For SaaS Buyers / Founders

### Does AgentFlow have paying customers?

No paying-customer claim is made in this repository. AgentFlow Enterprise should be treated as pre-revenue unless verified otherwise through private evidence.

### What does pre-revenue but post-build mean?

It means the product has moved beyond an idea or pitch deck into a built SaaS foundation, but it has not yet proven recurring revenue, customer retention, or market adoption.

### What is already implemented?

At a public level, AgentFlow presents a working product direction, public demo flow, buyer documentation, AI qualification workflow, protected dashboard concept, checkout readiness, deployment posture, and acquisition-oriented materials. Exact implementation evidence should be reviewed privately.

### What still needs validation?

The key validation areas are customer demand, willingness to pay, live checkout behavior, integration reliability, operational support, onboarding experience, and repeatable agency or founder-led sales motion.

### Can this be turned into a live SaaS business?

Potentially, yes. The value depends on execution after acquisition or licensing: customer development, live provider verification, sales process, onboarding, support, security review, and product focus.

### What would increase the value of the platform?

Evidence of pilot usage, first customer revenue, verified checkout operation, clearer onboarding, stronger demo assets, security review artifacts, and documented implementation options would increase buyer confidence.

### What is the difference between codebase value and revenue-validated SaaS value?

Codebase value reflects product build quality, architecture, documentation, and speed-to-market potential. Revenue-validated SaaS value requires proof that customers pay, retain, and receive measurable business value.

## For RevOps Consultants

### Does AgentFlow replace a CRM?

No. AgentFlow is best understood as a workflow and qualification layer that can support revenue operations. It is not positioned as a full CRM replacement.

### Where does AgentFlow sit in the revenue workflow?

It sits between lead capture and operational follow-through: intake, AI-assisted qualification, operator review, billing readiness, and handoff into the next system or process.

### Can it connect to existing sales processes?

That is the intended direction. Existing sales process fit should be evaluated by mapping client intake, qualification criteria, review steps, and handoff requirements.

### Can it help prioritize demo requests?

Yes at the workflow level. AgentFlow is designed around AI-assisted qualification that can help operators decide which requests need attention first, subject to private verification and business-rule configuration.

### What client use cases are most realistic?

Realistic use cases include agency lead intake, SaaS demo qualification, consultant inquiry triage, paid discovery routing, and structured follow-up for service businesses.

## For Potential Acquirers

### Is AgentFlow acquisition-ready?

It is prepared for acquisition discussion and buyer diligence, but it should not be treated as a fully de-risked operating business. A buyer should verify code quality, live services, customer status, and commercial assumptions.

### What is included in a private acquisition discussion?

A private discussion may include a technical walkthrough, implementation evidence, deployment review, provider configuration review, roadmap discussion, ownership terms, licensing options, and transition support scope.

### What is not included publicly?

Source code, private architecture, database structure, provider configuration, security internals, event-processing details, payment internals, and operational procedures are not included publicly.

### Is there recurring revenue?

No recurring-revenue claim is made here. Buyers should request evidence if revenue status changes.

### What would a buyer need to complete after acquisition?

A buyer would likely need to complete live provider verification, customer discovery, first pilot or customer proof, support model design, operational monitoring, security review, and go-to-market execution.

### Is technical due diligence available?

Yes, for qualified buyers through a private process. Sensitive materials should be shared only under appropriate confidentiality terms.

### What evidence should a buyer request?

Buyers should request a product walkthrough, code review session, deployment evidence, provider-side screenshots where appropriate, payment test evidence, security posture notes, known-risk list, and a transition plan.

## For Security-Conscious Buyers

### Are secrets included in this public repo?

No. This repository is documentation only and does not include credentials, private configuration, or sensitive source material.

### Where should secrets be stored in a real deployment?

Secrets should be managed through secure deployment environment configuration and provider-managed secret storage. They should not be committed to public repositories.

### Is AgentFlow SOC 2 or ISO certified?

No certification claim is made. AgentFlow does not claim SOC 2, ISO, formal penetration testing, or enterprise audit completion in this public repository.

### What is the security posture?

The posture is production-conscious and buyer-safe: protect private code, keep sensitive configuration out of public repositories, use authenticated dashboard principles, treat webhooks as trust boundaries, and keep AI calls server-side.

### How are webhooks secured at a high level?

Webhook security should rely on provider signature verification, server-side processing, event validation, and careful logging practices. Exact implementation details remain private.

### Is there a responsible disclosure process?

Yes. Security concerns should be sent to [contact@agentflow-enterprise.com](mailto:contact@agentflow-enterprise.com). Sensitive findings should not be posted publicly.

### What should not be disclosed publicly?

Do not disclose private source code, provider configuration, database design, event-handling internals, dashboard access details, security logic, or operational procedures in public channels.

## For Non-Technical Business Buyers

### What does AgentFlow actually do?

AgentFlow helps structure the path from a new lead to a qualified next step. It is designed to capture interest, assist with qualification, support operator review, prepare for billing, and hand work off into the next business process.

### Do I need a developer to use it?

For evaluation, you can review the public website and demo. For real deployment, a developer or technical operator is recommended to configure providers, data handling, branding, and workflow details.

### What happens to my data?

Data handling depends on the deployment and provider configuration. Before using AgentFlow commercially, buyers should review what data is collected, where it is stored, who can access it, and how long it is retained.

### Can this help me follow up with leads faster?

That is the intended business value. AgentFlow is designed to reduce manual qualification delay and give operators clearer context for follow-up.

### Is this ready to use out of the box?

It should be treated as a SaaS foundation that still requires configuration, verification, and business-specific setup before commercial use.

### What is the simplest way to evaluate it?

Start with the public website, try the demo, read the FAQ and roadmap, then request a private walkthrough if the product fits your use case.

