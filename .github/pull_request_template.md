<!--
Title: conventional commit format, e.g. `fix(agent): say "Zephyr unreachable" when the API cannot be reached`
Write in plain technical English: short, active sentences, facts first.
Keep these headings in this order. Delete comments and any section that does not apply.
AI agents: fill this template exactly. Never list a check as done if you did not run it.
-->

## 🎫 Ticket

<!-- One PR closes one issue: "Closes #123" closes it on merge. If the work needs several PRs, the issue should be an epic or split. -->

Closes #

## 🧠 Why

<!-- The problem, in one to three sentences. Link the RFC if there is one. -->

## 📝 What changed

<!-- The behavior before and after. Call out anything risky or not obvious. Skip a file-by-file list; the diff shows that. -->

## 🧪 Testing

<!--
Ran: the checks you ran and their results. Name the checks you did not run.
Verify: steps a reviewer can follow, with the expected result for each step.
Staging: the result on staging, or "Not needed: <reason>".
-->

- Ran:
- Verify:
- Staging:

## ⚠️ Risk and rollout

<!--
Breaking changes, migrations, feature flags, deploy order, and how to roll back.
State "Not deployed" if nothing was released. Write "Low risk: <reason>" if nothing applies.
-->

## 📸 Screenshots

<!-- Before and after, for UI changes only. -->

## ✅ Checklist

- [ ] The ticket is linked
- [ ] `main` and every deployed app work before and after this PR; it does not depend on an unmerged PR
- [ ] Tests are added or updated, or the reason they are not is under Testing
- [ ] Docs are updated, or not needed (public behavior changes need a zephyr-documentation PR)
- [ ] No secrets, tokens or customer data in the code, logs or this description
- [ ] AI assistance is disclosed below

**AI assistance:** <!-- None / Partly / Mostly agent-written — name the tool and model, e.g. "Mostly agent-written (Claude Code, Opus 5.5)" -->
