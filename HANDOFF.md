# Handoff

## Read first

Read `AGENTS.md`, `STATE.md`, relevant `DECISIONS.md` records, and the latest GitHub branch and commit state. Verify repository visibility before any work.

## Foundation completed

A public-safe canonical identity, global authority model, high-level project boundary, and privacy exclusions are documented. Existing useful history is preserved, and no private operational memory was migrated.

## Blocking handoff

The repository is public. Keep the migration branch unmerged. A separately authorized visibility decision must be completed and verified before a private operational documentation pass can be considered.

## Exact next action

Obtain an authorized repository-visibility decision, implement it outside this migration only if authorized, verify the resulting privacy boundary, and then rerun a sanitized merge review of this branch.

## Stop conditions

Stop if work would expose any employee, applicant, customer, booking, legal, commercial, production, or internal operating information, or would modify live systems or repository settings.

## Repository synchronization evidence

- Verified: 2026-07-18
- Canonical repository: `A-awd/saw`
- Approved default branch: `main`
- Verified effective ref: `migration/one-brain-foundation`
- Verified baseline revision: `0463bb4e72b1b71ed5a2c14b758a13d9bf5e6b6c`
- Evidence: the One Brain documents were refreshed from that exact GitHub revision; no business code or production system was changed.
- Runtime requirement: each agent must fetch or inspect the branch tip and remote synchronization state again before work. Local working-tree state was not inferred through the connector.
