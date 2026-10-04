# CLAUDE.md

Instructions for coding agents working in this repo. Keep this short and accurate. If it's wrong, fix it in the same PR.

## Project

<!-- One or two lines: what this repo is and who uses it. -->

## Commands

<!-- The exact commands to install, test, lint and build. Agents will run these, so they must work. -->

```sh
# install
# test
# lint
```

## Layout

<!-- Where the important code lives, and anything non-obvious about the structure. -->

## Conventions

- Follow the existing style. Don't introduce a new pattern where one already exists.
- Write or update tests for any behaviour you change, and run them before finishing.
- Keep changes focused on the task. Don't refactor unrelated code.
- Don't add dependencies without saying why.
- Never commit secrets, local tool state or agent transcripts.

## Don't touch

<!-- Generated files, vendored code, anything that must only change through a specific process. -->

## Before you finish

- Tests and lint pass.
- Docs, specs and this file are updated if behaviour changed.
- The PR description says what changed, why, and how AI was used.
