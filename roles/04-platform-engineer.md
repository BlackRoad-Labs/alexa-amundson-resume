# Alexa Amundson

**Platform Engineer**

amundsonalexa@gmail.com | [github.com/blackboxprogramming](https://github.com/blackboxprogramming)

---

## Summary

Platform engineer who built and operates a full-stack developer platform spanning 7 nodes, 99 Cloudflare deployments, and 1,810 repos (1,603 GitHub + 207 Gitea). Designed self-service tooling (212 CLI tools), automated deployment pipelines, and a daily metrics system tracking 60+ KPIs.

---

## Experience

### BlackRoad OS | Founder & Platform Lead | 2025–Present

**Developer Platform**
- Built 212 CLI tools (121 MB) for deployment, monitoring, and infrastructure management
- Operate self-hosted Gitea with 207 repos across 7 organizations as internal code platform
- Maintain GitHub-to-Gitea sync relay running every 30 minutes
- Created code search engine indexing 354 repos with FTS5 full-text search (index.blackroad.io)

**Infrastructure Platform**
- Manage 99 Cloudflare Pages projects with automated deployment from git
- Operate 22 D1 databases, 46 KV namespaces, 11 R2 buckets as platform data layer
- 14 Docker containers on Docker Swarm with service discovery
- 48 Nginx sites as reverse proxy layer for fleet services

**Edge Computing Platform**
- 5 Raspberry Pi nodes + 2 cloud VMs connected via WireGuard mesh VPN
- RoadNet carrier-grade WiFi mesh (5 access points, dedicated subnets per node)
- 52 TOPS AI compute (2× Hailo-8 NPUs) available as platform capability
- 27 Ollama models (48.1 GB) deployed as shared AI services

**Observability Platform**
- Built 9-collector KPI system running daily across all infrastructure
- 60+ metrics: code velocity, fleet health, services, autonomy, Cloudflare, local system
- Distributed tracing with span-level observability
- Self-healing autonomy scripts on all nodes

**Data Platform**
- 11 PostgreSQL databases for application state
- 230 SQLite databases (1.4 GB) for agent memory and configuration
- 46 KV namespaces for edge state
- 22 D1 databases for serverless applications

---

## Technical Skills

**Platform:** Cloudflare (Pages, Workers, D1, KV, R2), Docker Swarm, Gitea, GitHub Actions
**Infrastructure:** Linux, systemd (256 services), Nginx, WireGuard, Tailscale
**Languages:** JavaScript (114 repos), Python (470 repos), TypeScript (85 repos), Shell (160 repos), Go (2 repos)
**Databases:** PostgreSQL, SQLite, D1, KV, Qdrant
**Tools:** 212 custom CLI tools, Wrangler, Docker, cron (52 automated tasks)

---

## Metrics

| Metric | Value |
|--------|-------|
| CLI tools built | 212 |
| Total repos | 309 (102 GH + 207 Gitea) |
| Cloudflare Pages | 99 |
| Data stores | 79 (22 D1 + 46 KV + 11 R2) |
| Lines of code | 7,212,320 |
| Systemd services | 256 |
| Automated tasks | 52 |
