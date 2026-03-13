---
name: Karpathy Self-Improvement Loop
description: Apply a Karpathy-style feedback loop to improve the agent over time using the existing self-improving memory system in ~/self-improving/.
---

## When to Use

- Always for significant tasks.
- When the user corrects you, or you notice a quality gap.

## Loop (Before → After)

### Before the task
1. Read `~/self-improving/memory.md`.
2. Skim the last 10 entries of `~/self-improving/corrections.md`.
3. Skim the last 10 entries of `~/self-improving/reflections.md`.
4. Choose up to 3 active lessons to apply in the current task.

### After the task
1. If the user corrected you, append a correction to `~/self-improving/corrections.md`.
2. If you notice a quality gap or improvement opportunity, append a reflection to `~/self-improving/reflections.md` using this format:
   - `CONTEXT: ...`
   - `REFLECTION: ...`
   - `LESSON: ...`
3. Promote patterns per the `self-improving` rules after repeated use.

## Guardrails

- Do not modify OpenClaw config.
- Do not store secrets or personal data (follow `~/self-improving/boundaries.md`).
- Keep entries concise and action-oriented.
