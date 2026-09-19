### neon1 .github

Organization-wide GitHub configuration and public profile for neon1.

---

#### Content

- [`profile/README.md`](profile/README.md) → public GitHub organization profile
- [`.github/workflows/docs.yml`](.github/workflows/docs.yml) → documentation and workflow checks
- [`.markdownlint-cli2.yaml`](.markdownlint-cli2.yaml) → Markdown linting configuration

---

#### Static File Checks

- Markdown — `**/*.md`
  - **Markdownlint** → structure and consistency
  - **Codespell** → spelling
  - **Lychee** → link validation

- GitHub Actions — `.github/workflows/*.yml|*.yaml`
  - **Actionlint** → workflow validation

> Checks run on relevant pushes and pull requests; link validation also runs weekly.

---

#### neon1

Software, automation, infrastructure, IoT, AI.

[neon1.tech](https://neon1.tech)

---

<sub>© 2026 neon1 LLC. All rights reserved.</sub>
