# neon1 .github

neon1's organization-wide GitHub files.

- [`profile/README.md`](profile/README.md) is the organization profile.
- [`SECURITY.md`](SECURITY.md) and [`SUPPORT.md`](SUPPORT.md) are the defaults for repositories without their own.
- [`CONTRIBUTING.md`](CONTRIBUTING.md) explains how to report problems and propose changes.
- [`.github/workflows/quality.yml`](.github/workflows/quality.yml) is the reusable action, workflow, and secret check. `docs.yml` calls it here.
- [`.github/workflows/docs.yml`](.github/workflows/docs.yml) checks Markdown and links. [`.markdownlint-cli2.yaml`](.markdownlint-cli2.yaml) configures Markdownlint.

## Checks

- Markdown: Markdownlint for structure, Codespell for spelling, Lychee for links.
- GitHub Actions workflows: Actionlint.

They run on relevant pushes and pull requests. Link checks also run weekly.

Other neon1 repositories can call `quality.yml` from a workflow in their own repository. Pin the `uses` reference to the full commit SHA reviewed for that release. Each repository decides when to adopt it.

---

<sub>© 2026 neon1 LLC. Each repository states its own license. [neon1.tech](https://neon1.tech)</sub>
