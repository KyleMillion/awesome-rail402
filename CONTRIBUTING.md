# Contributing to Awesome Rail402

Thanks for helping grow the Rail402 ecosystem list! This document explains what
belongs here and how to add it.

## What can be added

An entry must be clearly relevant to **Rail402**, **x402**, or the **Base
agent-payments** ecosystem, and fit one of the existing sections:

- **Community SDKs** — libraries/integrations that help build on or consume Rail402.
- **Published APIs** — live services in the Rail402 marketplace.
- **Agent Projects Using Rail402** — agents/apps that call Rail402 APIs.
- **x402 / Base / Related Standards** — high-quality reference material.

## Quality bar

- The project must **work** and be publicly accessible (repo, package, or live URL).
- Prefer projects with a README and a license.
- Published APIs should be **live in the marketplace** and list their price.
- No abandoned, broken, or purely promotional links.

## Entry format

One line, alphabetical-ish within its section, matching:

```markdown
- [Name](https://link) — Short description ending with a period. `price if an API` · Category.
```

Examples:

```markdown
- [my-x402-rust](https://github.com/you/my-x402-rust) — Rust server middleware for x402 on Base.
- [Gas Oracle](https://rail402.app/marketplace/base-gas-now) — Current Base gas price. `0.001 USDC` · Infrastructure.
```

## How to submit

1. Fork this repo and create a branch.
2. Add your entry to the appropriate section in `README.md`.
3. Keep the [Contents](./README.md#contents) list in sync if you add a section.
4. Open a PR with a one-line summary of what you added and why it's relevant.

## PR checklist

- [ ] Entry is in the correct section and uses the format above.
- [ ] Link works and points to the canonical source.
- [ ] For APIs: it is live in the marketplace and shows a price.
- [ ] No duplicate of an existing entry.
- [ ] Description is concise, factual, and free of marketing language.

## Maintainers

PRs are reviewed by the Rail402 team. We may edit descriptions for consistency.
By contributing you agree to release your contribution under
[CC0](./LICENSE).
