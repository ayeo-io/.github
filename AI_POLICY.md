# AI-assisted contributions

ayeo builds tools for AI-assisted development, and we use them every day. AI-assisted contributions are welcome here. This policy is about keeping quality and trust high when they arrive.

## The short version

1. **You own it.** You're responsible for every line in your PR, whoever or whatever typed it.
2. **Understand it.** Be ready to explain any part of the change in review. "The agent did it" isn't an answer.
3. **Say so.** Tick the AI disclosure box in the PR template and give a line on how you used it.
4. **Verify it.** Run the tests. Read the diff. Check that generated tests actually test something.
5. **Keep it tight.** Agents happily produce a lot of code. Cut what isn't needed before you ask anyone to review it.

## Disclosure

The PR template asks whether AI tools were used and how. Something like "Claude Code wrote the first pass, I rewrote the error handling and added the edge-case tests" is plenty. Disclosure doesn't count against a PR. It helps reviewers know where to look harder.

## What we look for in review

- Code that fits the existing style and structure, not a parallel version of something that already exists.
- No invented APIs, flags, config keys or dependencies.
- Tests that would fail if the behaviour broke, not just tests that pass.
- Docs and comments that are accurate and don't pad.
- A scope that matches what was asked for.

## Things we'll close

- Large unsolicited PRs that are clearly unreviewed agent output.
- Drive-by "improvements" across many files with no linked issue.
- Issues or PRs generated in bulk, or text that reads as pasted from a chat session without being checked.

If you're unsure whether something is too big, open an issue first.

## Data and secrets

- Don't paste secrets, tokens, or private data into AI tools while working on ayeo code.
- Don't commit agent transcripts, local tool state or caches. Check `.gitignore` before you push.
- Only submit work you have the right to submit. If a tool reproduced a chunk of someone else's code, don't include it.

## Agent configuration in our repos

Many ayeo repos include a `CLAUDE.md` or similar file that tells coding agents how to work in that repo. Use it, and if you find it wrong or missing something, a PR to fix it is a very welcome contribution.

Changes to agent configuration, hooks, or anything that runs automatically on a contributor's machine get extra scrutiny in review, because they can execute code.
