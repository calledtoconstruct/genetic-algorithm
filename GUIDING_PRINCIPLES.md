# Guiding principles: calledtoconstruct/genetic-algorithm

## Purpose and scope
An implementation of a genetic algorithm (README only so far).

## Stack and layout
Only `README.md`, `LICENSE` and `.gitignore`. No source, language or build files yet.

## Commands
| Check | Command | Evidence |
|---|---|---|
| Build / type-check / tests | None yet: there is no code | repository tree |
| CI | None | repository tree |

Commands marked as not written down come from the build files, not from project docs; confirm them before relying on them.

## Before every push
Before every push: run the build and type-check/lint that exist here, plus only the tests for the files or feature you changed (team rule, ideas #14 note 6797). Do not run the full suite locally as a routine gate; this repository has no CI that runs the full suite, so run the full suite only when the change is broad, and say in the PR that CI coverage is missing. Merge needs a positive review. Explain any new failure your change caused. Never weaken a valid test to make it pass, and never invent a command this file does not list.

## Project rules
- The first code change must also choose and document the language, build command and test command here.
- Do not invent tooling in this file before code exists.

## What to avoid
- Committing to the default branch; work on a branch and open a pull request.
- Deleting files, branches or history, or changing repository settings.
- Adding tooling, CI or dependencies that the change does not need.
- Rules copied from other projects (file-size limits, clocks, quotas) that this repository never adopted.

## Delivery and safety
- Nothing is deployed.

## Open questions
- Language and direction are not established.

## Sources
Read from the `master` branch on 2026-11-08 ET: `README.md`, repository tree.

## Instruction updates
Check `guiding-principles.version` at the start of each turn and when you enter this project; reload this file when the version changes. Change this file, its version and date, and `PRINCIPLES_HISTORY.md` in the same commit. Team-wide role instructions are versioned separately in the team-process repository.
