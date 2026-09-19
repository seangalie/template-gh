The Template Bootstrap workflow has filled in the repository name, owner, and
author placeholders. The items below still need a human.

### Content

- [ ] Replace every `> **[?]**` prompt in `README.md` (About, Built With, Prerequisites, Installation, Usage, Acknowledgements).
- [ ] Write the tagline under the project title in `README.md`.
- [ ] Fill in the development environment steps in `docs/CONTRIBUTING.md`.
- [ ] Replace `docs/logo.svg` and `docs/screenshot.png`.
- [ ] Start filling in `CHANGELOG.md`.

### Contact and policy

- [ ] Set a real contact method in `docs/CODE_OF_CONDUCT.md` (it currently reads `[INSERT CONTACT METHOD]`).
- [ ] Review the supported-versions table in `docs/SECURITY.md`.
- [ ] Add your copyright notice using the appendix at the end of `LICENSE` — in source headers or a `NOTICE` file. Leave the license text itself unmodified.

### Repository settings

- [ ] Enable **Discussions** (the README and the issue chooser both link to it).
- [ ] Enable **Private vulnerability reporting** under Settings → Security.
- [ ] Review `.github/CODEOWNERS`. Personal repositories use the owner account automatically; organization repositories must replace and uncomment the `@org/team-name` example.
- [ ] Run the **Sync labels** workflow once from the Actions tab to apply `.github/labels.yml`.
- [ ] Configure the CodeQL languages and build mode in `.github/workflows/codeql.yml`, then enable its automatic triggers — or delete the workflow if it does not apply.
- [ ] Uncomment the matching ecosystem in `.github/dependabot.yml`.
- [ ] Review `.gitignore` and `.gitattributes` for this project's language.
