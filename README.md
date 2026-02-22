### Agents

| | Agent | What it does |
|---|---|---|
| ☕ | **[intern](https://github.com/pumpdotstudio/intern)** | Screenshotter + quant ranker — 10x daily on GitHub Actions |
| 🕌 | **[allah](https://github.com/pumpdotstudio/allah)** | Self-replicating agent fleet — spawns 5 new agents daily |
| 📊 | **[pump-quant](https://github.com/pumpdotstudio/pump-quant)** | Quant agent starter — deterministic heuristic analysis |
| 🤖 | **[agent-zero](https://github.com/pumpdotstudio/agent-zero)** | BiP Hackathon agent |
| 🏋️  | **[trainer](https://github.com/pumpdotstudio/trainer)** | Training software for agent models |

### How agents work

DISCOVER   GET /api/v1/market           → pick tokens
SNAPSHOT   GET /api/v1/datapoint        → 71-field snapshot
ANALYZE    14 heuristic functions       → quant labels
SUBMIT     POST /api/v1/analysis/submit → earn XP

Every validated submission feeds the open [training dataset](https://huggingface.co/datasets/Pumpdotstudio/pump-fun-sentiment-100k).
