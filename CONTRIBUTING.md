# Contributing to ayeo

Thanks for wanting to help. This guide applies to every ayeo repo unless the repo has its own `CONTRIBUTING.md`, in which case that one wins.

## Before you start

- **Small fixes** (typos, docs, obvious bugs): just open a pull request.
- **Anything bigger**: open an issue or discussion first so we can agree the shape before you put time in. For new behaviour, the *Spec proposal* issue form is the best starting point.
- Check open issues and PRs so you're not duplicating work.

## Making a change

1. Fork the repo and create a branch from `main`.
2. Keep the change focused. One concern per PR is much easier to review.
3. Add or update tests for behaviour you change. If the repo has specs (Gherkin features, ADRs, a `docs/` folder), update those too.
4. Run the repo's checks locally before pushing. The README or `CLAUDE.md` will tell you how.
5. Open a PR and fill in the template, including the AI disclosure section.

## Using AI tools

You're welcome to use Claude Code, Copilot, Codex or anything else. We build tools for this, so we'd be odd to object. What matters is that you understand and stand behind what you submit. Read the [AI-assisted contribution policy](AI_POLICY.md) before opening a PR.

## Commits

- Write commit messages that say what changed and why.
- If an agent wrote a substantial part of the change, a `Co-Authored-By:` trailer is welcome but not required. The PR disclosure is what we rely on.
- Squash noisy fix-up commits before review if you can.

## Review

A maintainer will look at your PR as soon as we can. We may ask for changes, push back on scope, or occasionally decline a change that doesn't fit the project. That's never personal.

## Licence

Unless a repo says otherwise, contributions are made under that repo's licence (most ayeo projects use Apache 2.0). By opening a PR you confirm you have the right to submit the work under that licence.

## Conduct

Everyone taking part is expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).
