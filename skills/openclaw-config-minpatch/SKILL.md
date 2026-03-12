---
name: openclaw-config-minpatch
description: Apply minimal deterministic patches to OpenClaw configuration files. Use when a request asks to add, change, or remove specific config keys while preserving all unrelated structure and values.
---

# OpenClaw Config Minpatch

## Workflow

1. Read the target config file once and locate exact key paths.
2. Identify the smallest valid change set that satisfies the request.
3. Patch only affected keys; do not reformat unrelated sections.
4. Re-read the file and verify only intended keys changed.

## Output Contract

Return only one of:

- Executable config patch/content with no extra text
- `CLARIFY: <single concise question>` when required inputs are missing

## Verification

1. Validate syntax with `jq . <file>` for JSON files.
2. Compare diff and confirm no unrelated edits are present.
