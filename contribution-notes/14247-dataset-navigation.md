# Phoenix #14247 — Navigate to a dataset after creating it

- Issue: https://github.com/Arize-ai/phoenix/issues/14247
- Size: XS
- Status: Parked pending explicit maintainer approval
- Product code changed: No

## Summary

After a user creates a dataset, Phoenix should navigate directly to the newly created dataset instead of leaving the user on the current page. The affected creation flow and canonical destination route will be confirmed after a maintainer approves the contribution.

## Proposed implementation

1. Reproduce the dataset creation behavior.
2. Locate the successful create mutation and canonical dataset route.
3. Navigate at the mutation success boundary.
4. Add a focused frontend regression test.
5. Run the focused test, formatter check, lint, and typecheck.
6. Capture before/after UI evidence for the PR.

## Contribution status

- 2026-10-20: Confirmed the issue was open, unassigned, and had no linked PR.
- 2026-10-20: Read `AGENTS.md`, `CONTRIBUTING.md`, and `CLA.md`.
- 2026-10-20: Asked the maintainer whether a small PR would be welcome.
- Waiting for explicit approval, as required by Phoenix's contribution policy.

## Before opening a PR

- Remove this tracking note from the upstream PR diff.
- Use a Conventional Commit-style PR title.
- Start the description with `fixes #14247`.
- Include tests and before/after UI evidence.
- Review and sign the Arize CLA personally if proceeding.
- Do not include employer code, data, credentials, or confidential information.
