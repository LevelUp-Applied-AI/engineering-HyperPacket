# PR Checklist

Use this checklist before opening a pull request. A reviewer should be able to understand, run, and verify the change without guessing.

## Pre-PR Checks

* [ ] The code does what the PR title and description claim (feature works or bug is fixed)
* [ ] Tests exist for the change and all tests pass locally
* [ ] README or relevant docs are updated if behavior or usage changed
* [ ] The PR contains only one logical change (no unrelated edits)
* [ ] No debug artifacts remain (print statements, breakpoints, temp files)
* [ ] The changes can be reproduced using the provided test/run steps
* [ ] Dependencies added or removed are justified and documented
* [ ] Code is readable and follows project conventions
