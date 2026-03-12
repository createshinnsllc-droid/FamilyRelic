# Model Infrastructure

## Primary Stack (openclaw.json)
- **Primary:** anthropic/claude-sonnet-4-6

## Fallback Chain (in order)
1. openai-codex/gpt-5.4
2. google-gemini-cli/gemini-3.1-pro-preview
3. google-antigravity/gemini-3-flash
4. ollama/glm-5:cloud
5. ollama/kimi-k2.5:cloud
6. ollama/minimax-m2:cloud (M2.1)
7. ollama/llama3.3:latest
8. ollama/qwen3.5:cloud
9. google-gemini-cli/gemini-2.5-flash
10. anthropic/claude-sonnet-4-6
11. anthropic/claude-opus-4-6
12. qwen-portal/coder-model
13. openrouter-tydroelite1/meta-llama/llama-3.3-70b-instruct:free
14. openrouter-tydrodacalmdon/mistralai/mistral-small-3.1-24b-instruct:free
15. openrouter-tydro/google/gemma-3-27b-it:free
16. openrouter-nizamshinn/qwen/qwen3-next-80b-a3b-instruct:free

## OpenRouter Keys (4 accounts — ROTATE ASAP, exposed in Telegram)
- **tydroelite1@gmail.com** → sk-or-v1-8eb8... → Active Primary → Llama 3.3 70B Free
- **tydrodacalmdon@gmail.com** → sk-or-v1-3b91... → Backup → Mistral Small 3.1 Free
- **tydro** → sk-or-v1-b926... → Backup → Gemma 3 27B Free
- **nizamshinn79@gmail.com** → sk-or-v1-1248... → Backup → Qwen 3 Next 80B Free

## Local Ollama Models Available
- glm-4.7-flash:latest (19 GB)
- qwen3-coder-next:cloud
- kimi-k2.5:cloud
- minimax-m2.5:cloud / minimax-m2:cloud
- qwen3.5:cloud
- glm-5:cloud
- llama3.3:latest (42 GB)
- minimax-m2:cloud
- qwen2.5-coder:14b / 7b
- llama3.1:8b
- qwen2.5:14b / 7b
- qwen3:8b
- gpt-oss:20b (13 GB)
- lfm2.5-thinking:1.2b

## LM Studio
- Primary: qwen3.5-9b-abliterated-mlx
- Fallback: mlx-qwen3.5-4b-claude-4.6-opus-reasoning-distilled

## Tavily Search API
- Key: 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
- Endpoint: https://api.tavily.com/search
- Usage: POST with {"api_key":"<key>","query":"<query>","max_results":5}
- Status: verified working 2026-03-10
- Note: Not natively supported by OpenClaw search config — used via exec/curl in overnight agent
