# Project Roadmap

This is a **community proposal**, not a product commitment or a claim that the listed Housecall Pro operations are available to every account.

## v0.1 — Foundations and learning

- [x] Create a public repository with an explicit license.
- [ ] Publish clear getting-started, contribution, and security documentation.
- [ ] Create a small, sourced API field guide beginning with `GET /jobs`.
- [ ] Add an original, synthetic-only example response and basic read-only pagination tests.
- [ ] Record unresolved API questions with exact links and evidence tiers.

**Exit criterion:** A beginner can understand how documented Jobs reads work, how they can fail, and how to test example code without any real credentials.

## v0.2 — Carefully scoped read-only tooling

- [ ] Decide a supported implementation language and API shape through a public design issue.
- [ ] Implement only the verified, approved read operations needed for one demonstrable community use case.
- [ ] Test request validation, array parameter encoding, pagination termination, backoff, and error handling with synthetic responses.
- [ ] Make any optional live verification strictly opt-in, local, and authorized.
- [ ] Document known limits and the security model.

## Later, only if useful

- Community-requested connectors, optional SDK packaging, and AI/MCP tool interfaces.
- More data types such as customers, employees, estimates, invoices, and scheduling.
- Contributor-led maintenance of documentation discrepancies and regression cases.

## Explicit non-goals for now

- No commercial BAGDigital application code or customer-specific business logic.
- No real-company credentials, customer data, or operational records.
- No unofficial access to Housecall Pro's private/internal endpoints.
- No write actions, automatically triggered workflows, webhook subscriptions, or hosted API proxy in v0.1.
- No bulk reproduction of proprietary or third-party API specifications.

## How to propose changes

Open an issue explaining who would benefit, what official or community evidence exists, security/privacy risks, and the smallest useful change. Maintainers will prioritize clarity, safety, and reliability over the number of features.
