# Alexa Amundson

**AI/ML Engineer**

amundsonalexa@gmail.com | [github.com/blackboxprogramming](https://github.com/blackboxprogramming)

---

## Summary

AI/ML engineer operating 27 deployed language models (48.1 GB) across a distributed edge fleet with 52 TOPS of dedicated AI acceleration. Builds custom model pipelines, inference APIs, and AI-powered automation across a 7-node infrastructure serving 48+ domains.

---

## Experience

### BlackRoad OS | Founder & AI Lead | 2025–Present

**Model Deployment & Operations**
- Deploy and manage 27 Ollama models (48.1 GB) across 3 edge nodes
- Fine-tuned 4 custom CECE personality models for domain-specific generation
- Operate 2× Hailo-8 NPUs (26 TOPS each = 52 TOPS total) for accelerated inference
- Built Ollama Bridge SSE proxy for streaming model responses to web clients

**AI Infrastructure**
- Designed multi-node inference routing across Pi 5 fleet (20 GB RAM total)
- Built AI image generation hub (images.blackroad.io) with 4 backend agents (DALL-E, Flux, SDXL)
- Manage model lifecycle: deployment, monitoring, memory optimization, thermal throttle prevention
- Reduced inference node temperature from 73.8°C to 57.9°C by isolating runaway generation loops

**APIs & Integration**
- Built CECE API (FastAPI) for custom model interaction and TTS generation
- Created code search engine indexing 354 repos with FTS5 full-text search
- Operate 11 PostgreSQL databases for AI application state
- Deploy AI services via Cloudflare Workers (99 Pages, 22 D1 databases)

**Data & Knowledge Systems**
- Manage 230 SQLite databases (1.4 GB) for agent memory, metrics, and state
- Built FTS5 knowledge index across 156,675 memory entries
- 111 registered systems tracked in systems database
- Custom RoadC programming language with tree-walking interpreter

**Automation & Monitoring**
- Daily automated KPI collection tracking 60+ AI and infrastructure metrics
- Power optimization across all AI nodes (CPU governors, voltage tuning)
- Self-healing autonomy scripts ensuring model availability

---

## Technical Skills

**AI/ML:** Ollama, Hailo-8 NPU, DALL-E, Flux, SDXL, custom fine-tuning, LLM orchestration
**Languages:** Python (470 repos), JavaScript (114 repos), TypeScript (85 repos), Bash, Go, C
**Frameworks:** FastAPI, Next.js, React, Node.js
**Infrastructure:** Raspberry Pi 5 fleet, Docker Swarm, WireGuard, Cloudflare
**Databases:** PostgreSQL, SQLite/FTS5, Cloudflare D1, KV stores, Qdrant (vector)
**Tools:** Ollama, Docker, GitHub Actions, Gitea, Wrangler

---

## Metrics

| Metric | Value |
|--------|-------|
| Models deployed | 27 (48.1 GB) |
| AI acceleration | 52 TOPS |
| Custom models | 4 fine-tuned |
| Image gen agents | 4 |
| Databases | 241 (11 PG + 230 SQLite) |
| Lines of code | 7,212,320 |
| Repos | 1,810 |
