# Contributing to Board Enthusiasts

Thanks for your interest in contributing to Board Enthusiasts (BE).

This organization contains code, tools, examples, and supporting resources for the BE ecosystem. We want contributions to be clear, reviewable, and aligned with the broader BE community experience.

## Before you start

For the main public-facing BE experience, announcements, and community entry points, start here:

- Website: [boardenthusiasts.com](https://boardenthusiasts.com/)
- Community Discord: _https://discord.gg/cz2zReWqcA_

In general:

- **Players and community members** should use the BE website and Discord for discussion, help, and feedback
- **Developers wanting to use BE tools in their games** should check out the [unity-tools](https://github.com/board-enthusiasts/unity-tools) repository for instructions of how to use our offerings such as the *BE Emulator* and *BE GDK*
- **Developers wishing to contribute directly** should use GitHub for code changes, implementation work, and contributor-facing project discussion
- **Maintainers** may convert feedback from Discord, website submissions, or internal planning into GitHub issues and project items

## Ways to contribute

Depending on the repository, useful contributions may include:

- Bug fixes
- Documentation improvements
- Tooling improvements
- Tests
- Examples and samples
- Developer experience improvements
- Small polish and usability changes

If you are unsure whether a contribution is a good fit, open a discussion with a maintainer first or ask in the BE Discord.

## Support vs. engineering work

Please use the right channel for the right kind of need.

### Use the website or Discord for:
- General help
- Community discussion
- Early feedback
- Feature ideas from players or general users
- Questions that are not yet actionable engineering work

### Use GitHub for:
- Pull requests
- Code-focused issues
- Documentation changes
- Confirmed and actionable implementation work
- Repository-specific technical discussion

Not every piece of community feedback should start as a GitHub issue. In many cases, maintainers will triage feedback first and create an issue only once the work is clear and actionable.

## Contribution workflow

### 1. Find or discuss the work
Before starting, make sure the work has already been discussed or tracked when appropriate.

Depending on the repo and the type of work, that may mean:

- an existing issue
- a maintainer request
- a roadmap item
- prior discussion in Discord
- repository discussion, if enabled

If there is no issue and the change is small, you can usually proceed with a PR. For larger changes, please align with a maintainer first.

### 2. Fork or branch
If you do not have direct write access:

- Fork the repository
- Create a branch for your change

If you do have write access:

- Create a feature branch from `main`
- Direct commits to `main` are not allowed

Branch name examples:

- `fix/login-null-check`
- `docs/setup-clarification`
- `feature/improve-session-export`

### 3. Make focused changes
Keep pull requests focused and easy to review.

Please avoid combining unrelated changes in a single PR.

Good:
- one bug fix
- one docs improvement
- one small feature
- one refactor with clear purpose

Avoid:
- mixing formatting, refactoring, docs, and feature work all together
- broad drive-by rewrites unless requested

### 4. Test your changes
Before opening a PR, do the relevant validation for the repository you are contributing to.

That may include:

- running tests
- building the project
- validating examples
- checking linting/formatting
- manually verifying behavior

If you were not able to run some validation, say so clearly in the PR.

### 5. Open a pull request
When opening a PR:

- explain **what changed**
- explain **why**
- link related issue(s) when applicable
- include screenshots or recordings for UI changes when helpful
- note any follow-up work or known limitations

## Pull request expectations

Pull requests **must**:

- be backward compatible within a major release version, or document the reason for a breaking change and required major version bump
- include unit and integration tests covering the new/changed code

Pull requests should generally:

- be scoped to a single clear purpose
- preserve existing behavior unless the change is intentional
- include documentation updates if the user or contributor workflow changed
- avoid unnecessary churn in unrelated files

A maintainer may ask for:
- smaller scope
- additional tests
- naming or structure changes
- alignment with repository conventions
- deferring the work until related architecture is decided

## Coding expectations

Specific standards may vary by repository, but in general:

- prefer readability over cleverness
- keep changes consistent with the existing codebase
- avoid introducing unnecessary dependencies
- document non-obvious decisions
- keep public-facing naming and UX clear
- document all non-private members with language-appropriate mechanisms (e.g. JSDoc in JavaScript, XML docs in C#)

If a repository has more specific standards, follow that repository’s README and local docs first.

## Documentation contributions

Documentation improvements are welcome.

Please contribute docs when you:
- change setup steps
- change user workflows
- add configuration
- fix outdated or misleading instructions
- add examples that reduce confusion

Documentation should be:

- compatible with GitHub markdown requirements
- nicely formatted and user-friendly (e.g. no walls of text, include screenshots, utilize markdown formatting and callouts as appropriate)

Clear docs are valuable contributions.

## Issue handling and triage

GitHub issues in this organization are intended to represent actionable work.

Maintainers may:
- create issues from Discord or website feedback
- move or relabel issues
- close issues that are duplicates, out of scope, or not yet actionable
- defer ideas until they are better defined

If your issue or PR is closed, that does not necessarily mean the idea is bad. It may simply mean the timing, scope, or implementation path is not right yet.

## Security issues

Please do **not** report security vulnerabilities through public issues.

If the repository has a `SECURITY.md`, follow the instructions there.

## Code of conduct

By participating in this project, you agree to follow the organization’s code of conduct. You also agree not to disparage, harass, or otherwise defame Board, Harris Hill, or any of their team and products.

Please be respectful, constructive, and collaborative.

## Questions

If you are unsure where something belongs:

- use the website and Discord for community-facing questions
- use repository issues/PRs for implementation-specific work
- ask a maintainer before investing heavily in a large change

## Contact if none of the above answers your question

support@boardenthusiasts.com