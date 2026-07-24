# Enable the documentation health check (CI)

Move the workflow file into `.github/workflows/` — this requires a maintainer:

```bash
mkdir -p .github/workflows
git mv docs/ci/docs-health-check.yml .github/workflows/docs-health-check.yml
git commit -m 'ci: add documentation health check workflow'
git push
```

Then go to **Settings → Branches**, edit the protection rule for `main`,
enable **Require status checks** and add **Run Documentation Health Check**.

Full guide: https://github.com/Application-Management-Division/engineering-knowledge-platform_CSO/blob/main/workflows/README.md
