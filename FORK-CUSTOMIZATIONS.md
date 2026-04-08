# Fork Customizations

> Upstream: [stanfordnlp/dspy](https://github.com/stanfordnlp/dspy)
> Fork maintained by: @ashsolei
> Last reviewed: 2026-04-08
> Fork type: **active-dev**
> Sync cadence: **monthly**

## Purpose of Fork

DSPy prompt-program framework; iAiFy fork adds enterprise CI and tracks upstream releases.

## Upstream Source

| Property | Value |
|---|---|
| Upstream | [stanfordnlp/dspy](https://github.com/stanfordnlp/dspy) |
| Fork org | AiFeatures |
| Fork type | active-dev |
| Sync cadence | monthly |
| Owner | @ashsolei |

## Carried Patches

Local commits ahead of `upstream/main` at last review:

- `dcb51f87 chore(deps): bump urllib3 from 1.26.6 to 2.6.3 (#21)`
- `abed46c1 chore(deps): bump protobuf from 6.31.1 to 6.33.5 (#22)`
- `aac7abf7 chore(deps): bump pynacl from 1.5.0 to 1.6.2 (#23)`
- `5d66ffc4 chore(deps): bump virtualenv from 20.31.2 to 20.36.1 (#24)`
- `0a205b32 chore(deps): bump black from 25.1.0 to 26.3.1 (#2)`
- `39007156 chore(deps): bump pillow from 12.0.0 to 12.1.1 (#3)`
- `3489871d chore(deps): bump authlib from 1.6.0 to 1.6.9 (#5)`
- `cfa6c9f2 chore(deps): bump pyjwt from 2.10.1 to 2.12.0 (#6)`
- `6285cb5d chore(deps): bump orjson from 3.11.2 to 3.11.6 (#7)`
- `eb349bee chore(deps): bump langsmith from 0.4.42 to 0.6.3 (#8)`
- `9fe8e939 chore(deps): bump requests from 2.32.3 to 2.33.0 in /docs (#10)`
- `cb553ad9 chore(deps): bump requests from 2.32.4 to 2.33.0 (#11)`
- `6a720893 chore(deps): bump langchain-core from 1.0.4 to 1.2.22 (#12)`
- `3e2248e7 chore(deps): bump cryptography from 43.0.3 to 46.0.6 (#13)`
- `24948ee2 chore(deps): bump pygments from 2.19.1 to 2.20.0 (#14)`
- `8cdf5d05 chore(deps): bump pygments from 2.19.1 to 2.20.0 in /docs (#15)`
- `995efa81 chore(deps): bump aiohttp from 3.11.14 to 3.13.4 in /docs (#16)`
- `0e0f7880 chore(deps): bump aiohttp from 3.13.2 to 3.13.4 (#17)`
- `31219267 chore(deps): bump tornado from 6.4.2 to 6.5.5 in /docs (#18)`
- `6e5dd2a6 chore: sync CLAUDE.md and copilot-instructions docs`
- `b7f8d344 chore(deps): bump ujson from 5.10.0 to 5.12.0 in /docs (#1)`
- `7cc8b453 docs: update FORK-CUSTOMIZATIONS.md with upstream source`
- `2f547c37 docs: add FORK-CUSTOMIZATIONS.md per enterprise fork governance`
- `ff647613 ci: add copilot-setup-steps.yml for Copilot Workspace`
- `ec2dfad0 chore: add AGENTS.md`
- ... (13 more commits ahead of `upstream/main`)

## Supported Components

- Root governance files (`.github/`, `CLAUDE.md`, `AGENTS.md`, `FORK-CUSTOMIZATIONS.md`)
- Enterprise CI/CD workflows imported from `Ai-road-4-You/enterprise-ci-cd`

## Out of Support

- All upstream source directories are tracked as upstream-of-record; local edits to core source are discouraged.

## Breaking-Change Policy

1. On upstream sync, classify per `governance/docs/fork-governance.md`.
2. Breaking API/license/security changes auto-classify as `manual-review-required`.
3. Owner triages within 5 business days; conflicts are logged to the `fork-sync-failure` issue label.
4. Revert local customizations only after stakeholder sign-off.

## Sync Strategy

This fork follows the [Fork Governance Policy](https://github.com/Ai-road-4-You/governance/blob/main/docs/fork-governance.md)
and the [Fork Upstream Merge Runbook](https://github.com/Ai-road-4-You/governance/blob/main/docs/runbooks/fork-upstream-merge.md).

- **Sync frequency**: monthly
- **Conflict resolution**: Prefer upstream; reapply iAiFy customizations on a sync branch
- **Automation**: [`Ai-road-4-You/fork-sync`](https://github.com/Ai-road-4-You/fork-sync) workflows
- **Failure handling**: Sync failures create issues tagged `fork-sync-failure`

## Decision: Continue, Rebase, Refresh, or Replace

| Option | Current Assessment |
|---|---|
| Continue maintaining fork | yes - active iAiFy product scope |
| Full rebase onto upstream | feasible on request |
| Fresh fork (discard local changes) | not acceptable without owner review |
| Replace with upstream directly | not possible (local product value) |

## Maintenance

- **Owner**: @ashsolei
- **Last reviewed**: 2026-04-08
- **Reference runbook**: `ai-road-4-you/governance/docs/runbooks/fork-upstream-merge.md`
