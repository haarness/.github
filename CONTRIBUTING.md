# Contributing to Haarness

Thanks for helping. Each repository explains its own setup and checks in its `CONTRIBUTING.md` or
README; this page holds what is the same everywhere.

By participating you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md). Security problems go to
[SECURITY.md](SECURITY.md), never to a public issue.

## Before you start

- **Bugs**: open an issue with the bug template first, unless the fix is small and obvious.
- **Features and larger changes**: open an issue describing the problem before writing code, so we can
  agree on the approach. Unsolicited large pull requests are hard to review and may be declined.
- Small documentation fixes and typo corrections can go straight to a pull request.

## Pull requests

- Keep each pull request to one logical change, with tests for new behaviour and for the bug fixed.
- Explain *why* in the commit message body, not only what changed.
- Update the documentation when behaviour changes, and describe what is true of the shipped build.
- User-visible text gets a key in every language catalog the project ships.
- Do not commit secrets, credentials, personal data or generated build output.

## Licensing of contributions

Unless you state otherwise, any contribution you intentionally submit for inclusion is licensed under
the license of the repository you submit it to. The open-source `haarness` repository additionally asks
you to sign off each commit under the [Developer Certificate of Origin](https://developercertificate.org/)
(`git commit -s`).
