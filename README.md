# HCP Community Toolkit

**Unofficial, community-driven tools and learning resources for building integrations with Housecall Pro.**

[Housecall Pro official API documentation](https://docs.housecallpro.com/) · [Roadmap](docs/ROADMAP.md) · [Contributing](CONTRIBUTING.md) · [Security](SECURITY.md)

> **Status: early project setup (pre-alpha).** This repository does not yet provide an installable SDK, an MCP server, or a production-ready integration. Nothing here is a guarantee of access to a Housecall Pro feature.

## Why this exists

Business owners should be able to benefit from automation without having to become software engineers. Developers should be able to find understandable examples, documented limitations, and repeatable tests rather than guess about how an API behaves.

Our goal is to make **safe, approachable, transparent, and reusable** integration resources for the community. We start with Housecall Pro because it is a concrete, useful API to study.

## Who it's for

- **Business owners:** Learn what automation may be able to do, what it cannot prove, and what requires approval.
- **Developers:** Discover documented operations, examples, limitations, and safe testing patterns.
- **AI builders:** Explore permission-aware integration patterns without granting an assistant uncontrolled access to business records.
- **Contributors:** Improve explanations, report API-documentation discrepancies, submit tests, and propose small tools.

## What we're building

| Area | Plan |
| --- | --- |
| Plain-language guides | Explain API keys, authentication, jobs, customers, schedules, and integration fundamentals |
| API field guide | Point to official operations and distinguish documentation from third-party reports and tested behavior |
| Read-only examples | Demonstrate input validation, pagination, error handling, and minimal data access |
| Synthetic fixtures and tests | Verify behavior without exposing real customers or connecting a live account |
| Optional future SDK / MCP tools | Consider only after the documentation and security foundations are dependable |

See [the roadmap](docs/ROADMAP.md) for proposed, *not promised*, milestones.

## Evidence matters

This project will distinguish:

1. **Officially documented:** Supported by a linked Housecall Pro source.
2. **Community-reported:** Reported by an independent developer, not independently verified here.
3. **Tested:** Reproduced with an approved setup and recorded in a sanitized test report.
4. **Unknown or unsupported:** Not verified for the stated operation, credential type, account, or situation.

A `200 OK` response does not prove that a supplied filter was honored. A documented endpoint does not prove that any particular customer's account can use it.

## Safe by default

- No real customer data, API keys, passwords, access tokens, webhook secrets, or private screenshots in public issues or commits.
- Start with **read-only, least-privilege** examples. Write actions require explicit, separately reviewed authorization.
- Do not run API samples against a real account unless the account owner authorized the activity and the example clearly describes the risks.
- Prefer synthetic test data, bounded pagination, careful logging, and independently reviewed changes.
- Never copy third-party code or entire vendor specifications into this repository without checking attribution and redistribution rights.

Read [SECURITY.md](SECURITY.md) before submitting sensitive findings.

## Get involved

Found a confusing field, an inconsistency in the docs, or a use case that would help small businesses? Open a [GitHub Issue](https://github.com/BAG-Digital/hcp-community-toolkit/issues) **without any private information**. Small, focused pull requests are welcome; please read [CONTRIBUTING.md](CONTRIBUTING.md).

## Relationship to BAGDigital and Housecall Pro

This is a **public community project founded by BAGDigital**, maintained separately from BAGDigital's private/commercial product work. It is **not affiliated with, sponsored, endorsed, or supported by Housecall Pro**. Housecall Pro is a trademark of its respective owner. Use the [official vendor documentation](https://docs.housecallpro.com/) for current vendor statements.

## License

Original content and code created in this repository are available under the [MIT License](LICENSE), except where otherwise identified. This license does **not** grant rights to third-party proprietary documentation, SDKs, trademarks, or other materials.
