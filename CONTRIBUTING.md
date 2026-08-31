# Helping out with TuringLang repositories

TuringLang develops research software for probabilistic programming and
inference. This policy applies across its repositories unless a repository
defines its own contribution policy, which takes precedence.

## Small fixes

Focused bug fixes, documentation corrections, and other small maintenance
changes may be submitted directly as pull requests. State the problem, justify
the change, and keep the patch narrowly scoped. A bug fix should include the
smallest practical regression test that fails without the fix and passes with
it. Update the documentation when user-facing behaviour changes.

## New work

Before implementing a new feature, API change, redesign, or substantial
refactor, open an issue. Describe the scientific or technical motivation, the
intended scope, the proposed approach, and how the result will be validated.
Wait for a TuringLang team member to confirm that the work fits the project's
scope before beginning implementation. Prior discussion does not guarantee
acceptance of the resulting pull request.

## Reviewing

Reviewer privileges are reserved for those with a sustained record of
substantive contributions, or for individuals explicitly invited by a team
member.

## Standards

Validation must be reproducible and proportionate to the change. Tests should
cover the relevant behaviour and failure modes. Where practical, changes to
numerical or statistical methods should be checked against an analytical result
or an independently implemented reference. If simulation is the only practical
validation method, describe its design and expected uncertainty. State
important assumptions, validity limits, and numerical tolerances. Support
claims about accuracy or performance with reproducible evidence.

Contributors are responsible for the correctness, security, and licensing of
everything they submit, including material produced with automated or
AI-assisted tools. Review and understand the complete change before requesting
review, and submit only material that may be distributed under the repository's
license.
