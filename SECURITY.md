# Security policy

## Reporting a vulnerability

Please **don't** open a public issue for security problems.

Use GitHub's private vulnerability reporting instead: go to the affected repo, open the **Security** tab and choose **Report a vulnerability**. If that isn't available, email **hello@ayeo.io** with "security" in the subject.

Include what you found, how to reproduce it, and which version or commit you tested. We'll acknowledge within a few working days and keep you updated while we fix it. We're happy to credit you in the release notes if you'd like.

## Supported versions

We fix security issues in the latest release of each project. Older versions are fixed only if the repo says so.

## What's in scope

Our tools run inside developer environments and alongside coding agents, so we're especially interested in:

- Hooks, scripts or commands that could run unexpected code on a user's machine.
- Ways a repo, spec, issue or other content could inject instructions into an agent using our tools (prompt injection) and cause it to do something the user didn't ask for.
- Policy or guardrail checks that can be bypassed.
- Leaks of secrets, tokens or local file contents into logs, artefacts or commits.
- The usual suspects: dependency vulnerabilities, path traversal, unsafe file handling.

Problems in Claude Code itself, or in other third-party tools, should go to their own maintainers.
