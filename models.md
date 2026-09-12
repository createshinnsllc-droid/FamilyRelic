# Model Infrastructure

## Cloud (Cursor Cloud Agents)
- Use whatever model the Cloud Agent run is configured with.
- Operator surface: iOS / web Cloud Agents (Mac Remote Control is unavailable).

## Local (ONLY relevant local stack)
- **PC DeepSeek harness** — sole local runtime for offline / private / “local brain” work.
- Do not route local work to OpenClaw, LM Studio, Ollama, or Mac hosts.

## Retired / do not use
- **OpenClaw** — permanently retired 2026-09-12. Config, gateway, and OpenClaw model routing are historical only.
- **Mac LM Studio / Mac Ollama** — host decommissioned; not the local stack.

## Legacy notes (historical — not active routing)
Former OpenClaw primary/fallback chains, OpenRouter free-tier keys, and Mac MLX LM Studio entries lived here through early 2026. They are obsolete. Do not resurrect them into live routing.

## Tavily Search API
- Key present in older notes; re-verify before use.
- Endpoint: https://api.tavily.com/search
- Usage: POST with `{"api_key":"<key>","query":"<query>","max_results":5}`
- Status: last verified 2026-03-10 (may be stale)
