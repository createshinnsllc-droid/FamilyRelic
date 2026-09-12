---
name: openclaw-cheap-triage
description: DEPRECATED 2026-09-12. OpenClaw is permanently retired. Do not use this skill. Local work uses the PC DeepSeek harness only; cloud work uses Cursor Cloud Agents.
---

# DEPRECATED — OpenClaw Cheap Triage

**OpenClaw is permanently retired (2026-09-12).** Do not run these commands. Do not diagnose or revive OpenClaw.

Use instead:
- **Cloud:** Cursor Cloud Agents (iOS / web)
- **Local:** PC DeepSeek harness only

The former workflow below is historical archive only.

## Former workflow (do not execute)

1. Collect the smallest useful snapshot first: status output and short log tail.
2. Prefer read-only diagnostics before any config writes or restarts.
3. Make one targeted change at a time.
4. Verify outcome immediately after each change.

## Former commands (do not execute)

- `scripts/openclaw-triage.sh`
- `openclaw channels status --probe`
- `tail -n 120 /tmp/openclaw-gateway.log`
