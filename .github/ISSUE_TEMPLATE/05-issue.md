---
name: ✅ Issue (Zephyr team)
about: One concern, closed by one PR. Written so a person or an AI agent can deliver it without questions.
title: 'feat(scope): what changes'
type: Task
labels: []
---

<!--
Same template as zephyr-cloud-io's "Issue" (rules in docs/process/issues.md there).
Rules: one concern per issue | one PR closes it | main and every deployed app work before and after the PR | staging first.
Delete a surface section when it has no change, or merge them into one line: "🔐 Permissions · 🗄️ Data · 🧾 Audit — No change."
AI agents: copy this body, keep the headings in this order, and never invent APIs, tables or flags.
-->

## 🎯 What

<!-- One or two sentences: the outcome, not the implementation. -->

## 🧠 Why

<!-- The problem today, with evidence (file paths at a commit, behaviour, decision and date). Link the parent epic, bug or RFC. -->

## ✅ Acceptance criteria

- **Given** …, **when** …, **then** …
- **Given** the change is unused (flag off, no new input), **then** behaviour is exactly as before
- **Given** staging, **then** every check above passes there before production

## 🔐 Permissions

<!-- Resource, action, who is allowed; denial shape. -->

## 🔌 API contract

<!-- Paths or public package API, request and response shapes, errors, CLI output. -->

## 🗄️ Data

<!-- Tables, columns, constraints, migrations (expand first, contract later). -->

## 🧾 Audit

<!-- Events written, including denied results. -->

## 🎨 UI

<!-- Screens and states. -->

## 🚫 Out of scope

- <!-- Neighbouring work, with its issue number. -->

## 🛠️ How (one PR closes this issue)

**Code**

- [ ] …

**Tests**

- [ ] Unit: …
- [ ] Contract or integration: …
- [ ] E2E: …
- [ ] Staging: … (record the result in this issue)

**Docs**

- [ ] … (behaviour or API change → docs in the same PR)

**Staging first** (where the repo has staging)

- [ ] Merged to staging; staging checks passed and recorded here
- [ ] Only then production; on a failed staging check, revert instead of fixing forward

## ⚠️ Caveats and rollback

- <!-- Risks, limits, how to undo without data loss. -->

## 🔗 Dependencies

**Depends on:** #… · **Blocks:** #… · **Writer:** <!-- the single writer of the data this changes -->

## 📝 Links

Epic #… · <!-- plan, discussion, design doc, RFC, client -->
