---
name: openclaw-config-minpatch
description: DEPRECATED 2026-09-12. OpenClaw is permanently retired. Do not use this skill. Do not patch OpenClaw configs.
---

# DEPRECATED — OpenClaw Config Minpatch

**OpenClaw is permanently retired (2026-09-12).** Do not patch, install, or revive OpenClaw configuration.

Use instead:
- **Cloud:** Cursor Cloud Agents
- **Local:** PC DeepSeek harness only
- **Repo config:** FamilyRelic docs (`AGENTS.md`, `models.md`, `operating-rules.md`)

Former minpatch workflow retained below as archive only — do not execute against any OpenClaw install.

## Former workflow (do not execute)

1. Read the target config file once and locate exact key paths.
2. Identify the smallest valid change set that satisfies the request.
3. Patch only affected keys; do not reformat unrelated sections.
4. Re-read the file and verify only intended keys changed.
