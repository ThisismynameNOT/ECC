# ECC lean profile for Adham Studio

This **personal fork** intentionally exposes only five engineering skills in the Claude Code and Codex plugin manifests:

- `frontend-patterns` — React/Next.js engineering and performance
- `e2e-testing` — browser automation and acceptance testing
- `security-review` — security and input/secret checks
- `verification-loop` — evidence before declaring completion
- `tdd-workflow` — tests for new features and defects

The full upstream-format `skills/` catalog, translations, platform adapters, code, agents, and workflow assets remain in this repo for compatibility, source attribution and recovery. **Only** `core-skills/` is exposed by this fork's plugin manifests. The core adapters have no independent rule logic; each loads the matching canonical file from `skills/` with relative references resolved from that canonical folder.

Do not install both this fork's plugin and `affaan-m/ECC` native plugin in one Codex/Claude profile. Do not stack native plugin and legacy manual-sync installs. An existing upstream ECC installation is not changed remotely by this GitHub update.

The five skill adapters are supplementary to the primary `premium-frontend-director` skill in `ThisismynameNOT/Claude`, plus design lookup from UI UX Pro Max and cinematic Scroll Craft when explicitly relevant. No source or package assets were removed. Snapshot before cleanup: `backup/skills-before-cleanup-20261113`.
