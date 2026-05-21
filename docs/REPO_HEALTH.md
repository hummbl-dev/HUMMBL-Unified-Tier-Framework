# Repository Health Contract

## Identity

- **Repository**: `HUMMBL/HUMMBL-Unified-Tier-Framework`
- **Canonical host**: `https://anvil.tail0ff7b3.ts.net/HUMMBL/HUMMBL-Unified-Tier-Framework`
- **Public mirror**: `https://github.com/hummbl-dev/HUMMBL-Unified-Tier-Framework`
- **Default branch**: `main`
- **Visibility**: Public
- **Owner**: HUMMBL Team

## Lifecycle

- **Status**: Active framework and public documentation artifact
- **Purpose**: Define the unified tier model for problem complexity, learning progression, and base architecture.

## Canonical Relationship

- **Source of truth**: `github.com/hummbl-dev/HUMMBL-Unified-Tier-Framework`.
- **Gitea lane**: `HUMMBL/HUMMBL-Unified-Tier-Framework` mirrors docs and issue flow.

## Validation Contract

No dedicated runtime test suite is required for this repository.
Use these mechanical checks for repository content changes:

```bash
npx markdownlint-cli2 "**/*.md" --config .markdownlint.json
```

and validate documentation-related workflows in CI.

## Branch Protection Expectation

- Keep `main` PR-driven.
- Preserve documentation integrity; require required-checks matching the repository’s markdown and link-check workflows.
