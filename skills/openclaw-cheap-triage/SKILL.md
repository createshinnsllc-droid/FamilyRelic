---
name: openclaw-cheap-triage
description: Troubleshoot OpenClaw with minimal token and compute cost. Use when diagnosing runtime failures, channel connectivity, or gateway health while avoiding deep probes and repeated heavy agent runs.
---

# OpenClaw Cheap Triage

## Workflow

1. Collect the smallest useful snapshot first: status output and short log tail.
2. Prefer read-only diagnostics before any config writes or restarts.
3. Make one targeted change at a time.
4. Verify outcome immediately after each change.

## Commands

- `scripts/openclaw-triage.sh`
- `openclaw channels status --probe`
- `tail -n 120 /tmp/openclaw-gateway.log`

## Escalation

Run deeper probes only when minimal checks do not isolate root cause.

## Verification

Confirm channel status recovers and errors stop increasing in fresh log tails.
