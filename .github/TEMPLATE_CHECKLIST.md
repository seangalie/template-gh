The Template Bootstrap workflow has filled in the repository name, owner, and
author placeholders. The items below still need a human.

### Content

- [ ] Set a human-readable project title in `README.md`. The bootstrap uses the repository slug, so a repo named `my-cool-thing` currently has that as its heading.
- [ ] Write the tagline under the project title in `README.md`.
- [ ] Replace every `> **[?]**` prompt in `README.md` (About, Built With, Prerequisites, Installation, Usage, Acknowledgements).
- [ ] Fill in the development environment steps in `docs/CONTRIBUTING.md`.
- [ ] Replace `docs/logo.svg` and `docs/screenshot.png`.
- [ ] Start filling in `CHANGELOG.md`.

### Contact and policy

- [ ] Set a real contact method in `docs/CODE_OF_CONDUCT.md` (it currently reads `[INSERT CONTACT METHOD]`).
- [ ] Review the supported-versions table in `docs/SECURITY.md`.
- [ ] Add your copyright notice using the appendix at the end of `LICENSE` — in source headers or a `NOTICE` file. Leave the license text itself unmodified.

### Repository settings

- [ ] Set the repository description and topics — they drive GitHub search and the social card.
- [ ] Enable **Discussions** (the README and the issue chooser both link to it).
- [ ] Enable **Private vulnerability reporting** under Settings → Security.
- [ ] Review `.github/CODEOWNERS`. Personal repositories get the owner account automatically; organization repositories must replace and uncomment the `@org/team-name` example, and that team needs write access before GitHub will honor it.
- [ ] Confirm the labels from `.github/labels.yml` were applied. The bootstrap starts the **Sync labels** workflow; if it did not run, start it from the Actions tab. The **PR Labels** check fails until those labels exist.
- [ ] Set up branch protection or a ruleset on the default branch. If you require pull requests, also enable Settings → Actions → **Allow GitHub Actions to create and approve pull requests**, or automation cannot open PRs against it.
- [ ] Turn on code scanning. GitHub's **default setup** (Settings → Code security) is the recommended path for most projects — enable it and delete `.github/workflows/codeql.yml`. Keep that workflow only if you need a custom build or query packs, in which case configure its languages and uncomment its automatic triggers.
- [ ] Uncomment the matching ecosystem in `.github/dependabot.yml`.
- [ ] Review `.gitignore` and `.gitattributes` for this project's language.
