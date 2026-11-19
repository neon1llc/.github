# neon1 .github

Organization-wide GitHub settings and public profile.

---

## Content

- [`profile/README.md`](profile/README.md) → public GitHub organization profile
- [`SECURITY.md`](SECURITY.md) and [`SUPPORT.md`](SUPPORT.md) → default security-reporting and support policies for repositories that don't have their own
- [`.github/workflows/docs.yml`](.github/workflows/docs.yml) → documentation and workflow checks
- [`.markdownlint-cli2.yaml`](.markdownlint-cli2.yaml) → Markdown linting configuration

---

## Static File Checks

- Markdown (`**/*.md`): Markdownlint for structure, Codespell for spelling, Lychee for links.
- GitHub Actions (`.github/workflows/*.yml|*.yaml`): Actionlint for workflow validation.

Checks run on relevant pushes and pull requests. Link checks also run weekly.

---

## neon1

[neon1.tech](https://neon1.tech)

---

<sub>© 2026 neon1 LLC. Each repository states its own license.</sub>
