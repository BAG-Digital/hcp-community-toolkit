# Contributing to HCP Community Toolkit

Thank you for helping make integration knowledge easier to understand and use safely.

## Ways to help

You can improve plain-language guides; report documentation ambiguities; supply links to official sources; write small synthetic-only examples or tests; suggest accessible developer tooling; and review pull requests.

Before starting a larger change, open an issue describing the user problem, intended scope, and how the change could be checked. Avoid proposing unrelated features in one PR.

## Evidence and honesty

Every API claim should identify its evidence level:

- **Official documentation:** Link the exact vendor operation/reference.
- **Community observation:** Link the source and clearly attribute the claim.
- **Verified test:** State the authorized testing environment, test date, sanitized steps, and outcome. Do not include credentials, customer information, provider bodies, or sensitive logs.
- **Unknown:** Say so clearly. Do not silently replace unknown values with guesses.

If sources disagree, document the disagreement and a safe verification plan instead of choosing one arbitrarily.

## Pull request workflow

1. Open or reference an issue for nontrivial changes.
2. Create a branch; do not commit directly to `main`.
3. Keep changes small, understandable, and original. Use descriptive names and explain *why* the change exists.
4. Add or update tests and docs appropriate to the change. Examples must use synthetic fixtures by default.
5. Open a pull request with a summary, evidence links, checks performed, risks, and anything still unknown.
6. Maintainers review the change before merging. Security-sensitive or credential-handling changes require additional independent review.

No direct deployment or live Housecall Pro account testing is authorized by submitting a PR.

## Privacy and security

- **Never commit** API keys, access tokens, passwords, webhook secrets, production URLs containing secrets, real customer/employee information, or identifiable job data.
- Do not paste real API responses into issues or tests. Build clearly marked synthetic fixtures.
- Do not add dependencies, automated network calls, background jobs, or new write-capable actions without a focused review.
- Report suspected vulnerabilities using the private guidance in [SECURITY.md](SECURITY.md).

## Licensing and attribution

By submitting contributions you agree that your original contributions may be distributed under this repository's MIT License. You must have the rights to submit what you contribute. Link to third-party resources rather than copying proprietary API reference text or other repositories' code wholesale. Maintain accurate source attribution.

## Community expectations

Be respectful, welcome learners, explain technical terms when they matter, and focus critiques on the work rather than the person. Maintainers may close abusive or off-topic threads and request revisions for unsafe submissions.
