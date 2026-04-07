# Contributing to Turing.jl Organization Repositories

This policy applies organization-wide through the shared `.github` repository. Individual repositories may add project-specific requirements, but this document defines the default expectations.

## Overall expectations

- Write clear and professional English in issues, pull requests, and review comments.
- Explain reasoning, not only the code delta. For bug fixes, describe the root cause and why your fix addresses it.
- Keep contributions focused and appropriately scoped for review.
- Be ready to answer technical questions about your changes during review.

Our standard is simple: a contribution should be worth more to the project than the time required to review it.

## AI and tool-use policy

Contributors may use AI tools, editors, and automation with one non-negotiable rule: **a human must stay in the loop**.

### Required

- You must read, review, and understand all tool-generated code or text before requesting review.
- You are the author of the contribution and fully accountable for correctness, quality, licensing, and security.
- You must be transparent about substantial tool usage.
  - Add an AI disclosure in your pull request description.
  - Include the model/tool name and a short note on how it was used.

### Not allowed

- Submitting unreviewed AI output for maintainers to debug or redesign.
- Using AI tools to resolve issues labeled `good first issue`.
  - These are learning-oriented tasks intended for hands-on contributor growth.

### Recommended

- Start with small, understandable changes if you are new to a repository.
- Write PR descriptions yourself (you may use tools for copy-editing or translation).
- Prefer incremental PRs over large, hard-to-review submissions.

## Pull request guidelines

- Keep PRs small enough for effective review. If a PR becomes very large, split it.
- Include tests for behavior changes.
- Update documentation when public behavior, APIs, or workflows change.
- Add clear reproduction and validation steps so reviewers can verify quickly.

### PR description format (for non-trivial changes)

- **What**: Concrete summary of behavior changes.
- **Why**: Problem statement, motivation, and why this approach was chosen.
- **How to test**: Exact steps and expected results.
- **Before/After**: Required for UI or UX changes (screenshots or video).
- **Risks/Open questions**: Any known limitations, trade-offs, or follow-ups.

End with an AI disclosure after a separator (`---`) when AI/tool assistance was substantial.

## Quality bar

Before opening a PR, ensure:

- You can explain the change end-to-end.
- Tests pass locally (or in CI where appropriate).
- The patch is intentionally scoped and not padded with unrelated edits.
- Commit messages and PR descriptions are clear and useful to reviewers.

## Copyright and licensing

By contributing, you confirm that you have the right to submit the content under the repository license.

Using AI tools does not remove copyright obligations. Do not submit generated content that reproduces copyrighted or otherwise restricted material without proper rights.

## Handling policy violations

Maintainers may request changes, pause review, or close/lock threads when contributions are repeatedly extractive or non-compliant.

When a contribution appears non-compliant with this policy, maintainers may use the template below:

> This contribution does not appear to meet our policy for tool-assisted submissions.
> Please revise it to make the change easier to review and add the required disclosure.
> In particular, ensure the PR clearly explains motivation, implementation decisions,
> and how you validated correctness.

## Need help?

- Look for issues labeled `help wanted`.
- If you are unsure about scope or design, open a discussion before implementing a large change.

Thanks for helping make the TuringLang community sustainable, welcoming, and high quality.