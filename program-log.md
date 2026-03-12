# program-log.md — Research Agent Learning Log
*Append-only. The agent reads this before every run and updates it after every run.*
*This is how the system gets smarter over time.*

---

## How to Use This File
- Before each research run: read all entries, extract best-performing queries and sources
- After each research run: append a new entry with what worked, what didn't, best queries found
- Never delete entries — the history of what worked is the intelligence

---

## Run Log

### 2026-03-10 — Domain 3: Content Strategy (Manual test run)
**Sources that hit (4-5/5):**
- Reddit JSON API: ✅ 5/5 — "digital legacy AI" returned emotionally powerful posts (60K+ upvotes combined)
- Hacker News Algolia: ✅ 5/5 — 107 hits on "digital legacy", high signal
- YouTube via browser: ✅ 4/5 — confirmed near-empty niche, surfaced Ray Fernando as adjacent creator
- Tavily: ✅ 4/5 — solid broad coverage, good for news and articles

**Sources that underperformed (1-3/5):**
- Semantic Scholar: ⚠️ 2/5 — returned 0 results on multiple queries, needs different query patterns
- GDELT: ✅ 3/5 — works but articles are often surface-level news, not deep insight
- ArXiv: ✅ 3/5 — academic but queries need to be very specific to get hits

**Best-performing search queries:**
- "digital legacy AI" → Reddit gold
- "digital will open source" → GitHub hits
- "what happens to your digital life when you die" → emotional content angle
- "AI memory preservation" → academic angle

**Worst-performing queries:**
- "digital legacy AI" on Semantic Scholar → 0 results
- "posthumous digital memory" on Semantic Scholar → 0 results

**Key insight from this run:**
The emotional demand is proven and massive (60K+ upvotes on Reddit) but the supply side (YouTube creators, tools) is nearly empty. This is the opportunity window.

**Actionable refinement for next run:**
- Try Semantic Scholar with: "personal information management posthumous" or "digital archive deceased"
- Reddit: dig into r/grief specifically for pain point language
- YouTube: search creator names not just topics to find adjacent channels faster

---
*New entries appended below after each run*

### 2026-03-12 — Domain 2: Philosophy Connections
**Sources that hit (4-5/5):**
- Tavily: ✅ 5/5 — Surfaced the critical Feb 2025 ACM study and recent BharatGPT founder video.
- HN Algolia: ✅ 4/5 — Good for finding niche philosophical theories on "digital will to power."
- ArXiv: ✅ 4/5 — XML response contained the "AI Afterlife" paper which mirrors Tydro's terminology.
- YouTube via browser: ✅ 4/5 — Confirmed Robert Greene/Daily Stoic skepticism as a high-value audience niche.

**Sources that underperformed:**
- GDELT: ⚠️ 2/5 — Queries for philosophy were too broad, returned generic news; needs (parentheses) for OR logic.
- Wikipedia: ⚠️ 3/5 — Good for grounding, but the summary endpoint is too static for "emerging" connections.

**Best-performing search queries:**
- "philosophical implications of digital immortality AI afterlife 2026"
- "Schopenhauer vs Nietzsche on legacy and persistence in the AI age"
- "digital legacy philosophy AI identity"

**Worst-performing queries:**
- "Buddhism impermanence vs digital preservation AI legacy ethics" (too specific, low signal hits)
- "Marcus Aurelius memento mori digital legacy stoicism" (returned too many 2023/old hits)

**Key insight from this run:**
There is a profound academic and popular shift toward "Identity Consistency"—people don't want a data dump; they want a "Representation" of the soul's reasoning. This perfectly aligns with Family Relic's interactive goal.

**Actionable refinement for next run:**
- Use the (OR) logic syntax for GDELT to avoid query errors.
- Prioritize search terms like "Identity Consistency" and "Algorithmic Temporality" to bridge tech and philosophy.
- Check YouTube comments on "Daily Stoic" videos to find the specific philosophical pushback against "AI Immortality."
