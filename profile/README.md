<p align="center"><img src="devi-banner.png" alt="DEVI" width="600"></p>

## DEVI

**Digital Evidence, Vision & Innovation.** Free tools for digital forensics, built by experienced digital forensic examiners.

Every DEVI tool is built around a few rules: work offline, open evidence read-only, say plainly what a result can and cannot show, and publish a SHA-256 for every download so anyone can check it.

### Tools

| Tool | What it does | Source |
| --- | --- | --- |
| [DEVI Validate](https://deviops.app/tools/devi-validate/) | Re-checks the hash values another tool recorded for your evidence, offline and read-only, and writes a PDF verification record. | [Open source](https://github.com/Deviops-app/DEVI-Validate) (Apache 2.0) — complete application source |
| [DEVI Decrypt](https://deviops.app/tools/devi-decrypt/) | Decrypts Apple and iCloud OpenPGP provider returns offline on Windows. | [Open source](https://github.com/Deviops-app/DEVI-Decrypt) (Apache 2.0) — scaffold; fuller source lands as released |
| [DEVI Registry](https://deviops.app/tools/devi-registry/) | A sourced database of app and artifact metadata for examiners, with an offline Windows app. | [Open source](https://github.com/Deviops-app/DEVI-Registry) (Apache 2.0) — scaffold; fuller source lands as released |

Downloads, release notes, and articles are on **[deviops.app](https://deviops.app)**.

### Open source

Every DEVI Windows tool has a public repository. DEVI Validate publishes complete application source, build steps, and tests. DEVI Decrypt and DEVI Registry are at the scaffold stage today: project skeleton and community health files are public; fuller application source lands as it is released.

- Found a bug or want a feature? Open an issue in the tool's repository. Organization issue and pull request forms live in [Deviops-app/.github](https://github.com/Deviops-app/.github).
- Found a security problem? Report it privately. See [SECURITY.md](https://github.com/Deviops-app/.github/blob/main/SECURITY.md).
- Want to contribute? Start with [CONTRIBUTING.md](https://github.com/Deviops-app/.github/blob/main/CONTRIBUTING.md).

Please never post real evidence, case material, or personal data in an issue or pull request.

DEVI tools do not carry a court, standards-body, or laboratory certification. Each lab should validate a tool under its own procedures before relying on it in casework.
