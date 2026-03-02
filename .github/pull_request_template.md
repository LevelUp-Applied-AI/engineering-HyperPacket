# Pull Request Template

## Title

Use an imperative, specific title (prefer Conventional Commits):

Example:

* feat
* fix
* chore
* docs
* style
* refactor
* test


Keep under 72 characters. One PR = one logical change.

---

## What Changed

Summarize the behavior or structural changes so the reviewer does
not need to read the full diff first.

Include:

* Major code changes
* Files or modules affected
* Behavior before vs after (if relevant)

---

## Why

Explain the problem being solved and the motivation.

Answer:

* What problem existed?
* Why did it matter?
* Why this solution instead of alternatives?

This section provides the context reviewers cannot get from the diff.

---

## How to Test

Provide reproducible verification steps.

On a clean environment a reviewer should be able to verify
in under 5 minutes.

Include:

Entry point:

* Command(s) to run

Setup:

* Dependencies or installation steps

Verification:

* Exact commands
* Expected output or behavior


---

## Scope

Confirm this PR contains exactly one logical change.

If this PR could be described using "and", it should be split.

---

## Checklist

Self-review before requesting review:

* [ ] Title is specific and imperative
* [ ] PR does one logical change only
* [ ] Description explains what and why
* [ ] Reproducible test steps included
* [ ] Tests added or updated if needed
* [ ] README updated if behavior changed
* [ ] No debug prints or temporary code
