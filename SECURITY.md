# Security Policy

This is an early-stage, unofficial community project. **It is not ready for production use.**

## Reporting security concerns

Please **do not post vulnerability details, proofs of exploitation, API keys, tokens, or real customer information in public GitHub Issues or pull requests**.

If the repository's **Security → Report a vulnerability** feature is enabled, use GitHub's private vulnerability reporting. Otherwise, contact a repository maintainer through an available private channel to coordinate a confidential report. If no private contact route is available, do not share sensitive details publicly.

For Housecall Pro service or account security issues that do not originate in this project, follow Housecall Pro's own security/support channels.

## Scope

We welcome reports concerning original code, examples, dependency security, documentation instructions that may cause unsafe behavior, and any future SDK or MCP components in this repository. Report only vulnerabilities you have permission to investigate. Do not test against other people's or companies' HCP accounts.

## Safe-development commitments

- Least privilege; read-only examples before write-capable integrations.
- No credentials in code, fixtures, tests, logs, commits, CI artifacts, or bug reports.
- No sensitive provider response bodies or attachment URLs in public evidence.
- Tenant/account access boundaries must not rely solely on query filters.
- Explicit approval and independent review for authentication, authorization, outbound API calls, and any future write operations.
- Synthetic data for public test fixtures; bounded requests, retries, and pagination.

There is no announced response-time guarantee while the project is being established. Maintainers will prioritize serious reports as resources permit.
