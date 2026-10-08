# Contributing to DEVI

Thanks for helping make DEVI tools better. This guide applies to every repository in the Deviops-app organization unless a repository has its own `CONTRIBUTING.md`, which takes priority.

## The one hard rule

**Never share real evidence, case material, or personal data** in an issue, pull request, test, screenshot, or log. Use synthetic files. If a bug only shows with real data, describe the input instead of attaching it.

## Ways to help

- **Report a bug.** Open an issue with the tool version, the Windows version, the steps to reproduce, what you expected, and what happened.
- **Suggest a feature.** Open an issue that describes the task you are trying to do, not only the feature.
- **Improve documentation.** Plain-language fixes are always welcome.
- **Send code.** For anything larger than a small fix, open an issue first so we can agree on the approach.

## Pull requests

1. Fork the repository and create a branch from `main`.
2. Keep the change focused on one thing.
3. Add or update tests. Tests must create their own synthetic files.
4. Run the tool's build and tests locally (see its README).
5. Update `CHANGELOG.md` if users will notice the change.
6. Open the pull request and fill in the template.

Pull requests are squash-merged after review and a passing CI check.

## Design rules for DEVI tools

- Evidence is opened read-only. A tool never writes into the evidence location.
- Core work runs offline. Any network use must be optional, off by default, and documented.
- Results say what was observed, not why it happened.
- No telemetry.

## License

By contributing, you agree that your contribution is licensed under the license of the repository you contribute to (Apache 2.0 for DEVI Validate, DEVI Decrypt, and DEVI Registry).

## Code of Conduct

Everyone taking part is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
