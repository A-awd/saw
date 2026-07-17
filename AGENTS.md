# Agent instructions

These instructions apply to Claude, Codex, ChatGPT, Hermes, and future agents working on `saw-production`.

## Authority

GitHub is the only permanent source of truth. Platform-local memory, chat history, caches, and uncommitted files are non-authoritative. Resolve conflicts using the latest approved GitHub branch and commit, or record the conflict in `STATE.md`.

## Session start

1. Open this target repository.
2. Inspect the latest authorized GitHub branch and commit.
3. Read `README.md`, `AGENTS.md`, `STATE.md`, and `HANDOFF.md`.
4. Read relevant `DECISIONS.md` records.
5. Confirm repository visibility and restrict work to public-safe, high-level material while it remains public.

## Working rules

- Keep project operational memory in this project repository, but do not add it while the repository is public.
- Store only reusable public-safe documentation on the current migration branch.
- Never include employee, applicant, customer, booking, legal, financial, production, credential, or raw conversational material.
- Do not change live booking, workforce, customer, production, or repository settings from these documents.
- Refer to `ai-operating-system` only for reusable global rules.

## Session end

Update `STATE.md` and `HANDOFF.md`; record durable public-safe choices in `DECISIONS.md`; validate; and commit and push only when authorized. Do not merge this foundation while the visibility blocker remains.

## Canonical authority and entry contract

GitHub is the only permanent source of truth for approved, sanitized project state. Platform-local memory, chat history, launcher text, caches, and unpushed work are non-authoritative.

At session start, read `README.md`, `AGENTS.md`, `STATE.md`, `HANDOFF.md`, `DECISIONS.md`, and `LAUNCHER.md`, plus relevant linked decisions and workflows. Continue only from the latest verified GitHub branch and commit.

## Required One Brain synchronization contract

Before work, every supported agent must verify the canonical remote `A-awd/saw-production`, inspect the working tree, current branch, latest local commit, latest GitHub commit, and synchronization state, then continue only from the latest verified GitHub state. Read `README.md`, `AGENTS.md`, `STATE.md`, `HANDOFF.md`, `DECISIONS.md`, and `LAUNCHER.md`, plus relevant linked decisions, workflows, and security guidance.

After meaningful work, validate the exact change; update `STATE.md` and `HANDOFF.md`; update `DECISIONS.md` when a durable decision is made; record blockers, risks, and unfinished or unpushed work; commit and push when authorized; and verify that GitHub contains the reported revision. If push is unavailable or unauthorized, record the exact unpushed state and do not claim durable completion.

GitHub is the only permanent authority. Platform memory, chat history, launcher text, caches, local scratch files, and unpushed work are non-authoritative. Never leave GitHub behind the conversation.
