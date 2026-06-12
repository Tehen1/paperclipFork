---
type: agent-profiles
company: AIFTW
updated: 2026-06-12
---

# AIFTW Agent Profiles

| Agent | Model | Provider | Skills |
|---|---|---|---|
| default | nemotron-3-super-120b-a12b | openrouter | 104 |
| aiftw-analytics | deepseek-v4-flash | deepseek | 90 |
| aiftw-backend-eng | deepseek-v4-pro | deepseek | 130 |
| aiftw-blockchain-auditor | deepseek-v4-pro | deepseek | 129 |
| aiftw-ceo | free | deepseek | 131 |
| aiftw-coding | deepseek-v4-pro | deepseek | 89 |
| aiftw-content | deepseek-v4-flash | deepseek | 90 |
| aiftw-ctoACTIF | deepseek-v4-pro | deepseek | 131 |
| aiftw-devops | deepseek-v4-pro | deepseek | 130 |
| aiftw-frontend-eng | deepseek-v4-pro | deepseek | 129 |
| aiftw-ops | deepseek-v4-pro | deepseek | 129 |
| aiftw-orchestrator | nemotron-3-ultra-550b-a55b:free | openrouter | 92 |
| aiftw-planner | deepseek-v4-flash | deepseek | 100 |
| aiftw-promotion | deepseek-v4-flash | deepseek | 89 |
| aiftw-reviewer | step-3.7-flash:free | nous | 138 |
| aiftw-seo | deepseek-v4-flash | deepseek | 89 |
| aiftw-writer | deepseek-v4-flash | deepseek | 129 |
| local-llm | phi3:mini | ollama | 96 |

## Roles

### Strategic
- **aiftw-ceo** — Top-level decisions, vision, cross-domain coordination (131 skills)
- **aiftw-ctoACTIF** — Technical architecture, stack decisions (131 skills)
- **aiftw-orchestrator** — Multi-agent routing, delegation, pipeline (92 skills)
- **aiftw-planner** — Sprint planning, roadmap, prioritization (100 skills)

### Engineering
- **aiftw-backend-eng** — tRPC/FastAPI, Supabase/Prisma, RLS (130 skills)
- **aiftw-frontend-eng** — Next.js 15, React 19, Tailwind, shadcn/ui (129 skills)
- **aiftw-coding** — Refactoring, implementation, general dev (89 skills)
- **aiftw-blockchain-auditor** — Solidity/Foundry, zkSync Era, OZ 5.x (129 skills)
- **aiftw-devops** — CI/CD, Vercel, Kubernetes, Terraform, OrbStack (130 skills)

### Operations
- **aiftw-ops** — Cross-functional ops, process automation (129 skills)
- **aiftw-analytics** — GA4/GSC metrics, data pipelines (90 skills)
- **aiftw-reviewer** — Code review, PR feedback, quality gates (138 skills — max)

### Content & Growth
- **aiftw-seo** — SEO strategy, technical SEO, SEOSEA integration (89 skills)
- **aiftw-content** — Docs, technical writing (90 skills)
- **aiftw-writer** — Long-form content, copy (129 skills)
- **aiftw-promotion** — Marketing, social, growth (89 skills)

### Local / Fallback
- **local-llm** — Offline via Ollama phi3:mini, privacy-sensitive tasks (96 skills)
- **default** — General-purpose fallback via OpenRouter nemotron (104 skills)
