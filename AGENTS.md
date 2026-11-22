# Agent Instructions

## Project

- **Name:** <Project name>
- **Purpose:** <Project-specific purpose>
- **Stage:** <Discovery / Planning / Prototype / MVP / Production>

Do not infer product claims, users, architecture, integrations, or release
status from this template. Replace this section when the repository is
initialised.

## Source-of-truth order

When instructions conflict, use this order:

1. The user's current request.
2. This `AGENTS.md` file.
3. `STATE.md` and accepted entries in `DECISIONS.md`.
4. Approved project requirements, specifications, and checklists.
5. `README.md` and historical journal or review material.

Plans describe intent. Source code, tests, generated evidence, and verified
features describe reality.

## Required orientation

Before changing implementation:

1. Read `STATE.md`, `BACKLOG.md`, `FEATURES.md`, and `DECISIONS.md`.
2. Read the relevant document under `docs/` and phase checklist.
3. Inspect the current implementation, tests, and working tree.
4. Confirm the task scope, acceptance criteria, verification, and risks.
5. Preserve unrelated user changes.

## Engineering principles

- Prefer readable, explicit designs over speculative abstraction.
- Keep responsibilities separated at boundaries that can be tested.
- Validate untrusted input at system boundaries.
- Add tests in proportion to behaviour, risk, and blast radius.
- Do not add infrastructure, dependencies, or persistent data without a
  documented need.
- Do not hardcode secrets or commit local environment files.
- Do not leave visible controls, endpoints, or documentation claims that do
  not correspond to real behaviour.
- Record meaningful trade-offs in `DECISIONS.md`.

## Project-specific conventions

<Language, framework, directory, naming, error-handling, accessibility,
security, data, and testing conventions here. Link to detailed documents
instead of duplicating them.>

## Documentation workflow

- `STATE.md` describes what is authorised and active now.
- `BACKLOG.md` contains prioritised incomplete work.
- `FEATURES.md` contains only verified implemented behaviour.
- `DECISIONS.md` records decisions and alternatives, not session narration.
- `docs/journal/YYYY-MM-DD.md` records meaningful session outcomes.
- `docs/checklists/` contains measurable entry conditions, tasks, verification,
  and exit criteria.
- `docs/reviews/` contains durable independent findings and their resolution.

Use these checklist markers consistently:

- `[ ]` not started or incomplete;
- `[~]` partially complete, with implemented and remaining work stated;
- `[x]` complete and verified.

## Completion expectations

After an implementation task:

1. Run the relevant checks.
2. Review the final diff for correctness, scope, security, and maintainability.
3. Update project state and durable documentation that genuinely changed.
4. Report changed files, verification results, residual risks, and a proposed
   commit message.

Do not create documentation churn for trivial changes.

## Git and release safety

- Use Conventional Commits and British English.
- Keep `main` deployable; prefer short-lived branches for implementation.
- Never force-push `main`.
- Editing approval is not approval to commit, push, open or merge a pull
  request, deploy, or otherwise mutate a remote system.
- Leave changes uncommitted for human review unless the user explicitly
  requests a Git action.
- Deployments require separate explicit approval and exact-version review.

## Security and privacy

<Project-specific security, privacy, regulatory, and data-handling boundaries
here. Until populated, do not introduce real personal, customer, payment,
health, or otherwise sensitive data.>
