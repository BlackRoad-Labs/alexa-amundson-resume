# Alexa Amundson

**Solutions Architect**

amundsonalexa@gmail.com | [github.com/blackboxprogramming](https://github.com/blackboxprogramming)

---

## Summary

Solutions architect who designed and built a complete hybrid edge-cloud platform: 7 compute nodes, 99 Cloudflare deployments, 1,810 repositories, 283 databases, 27 AI models, and 48+ production domains. Architects systems spanning infrastructure, application, data, and AI layers.

---

## Experience

### BlackRoad OS | Founder & Architect | 2024–Present

**Architecture Design**
- Hybrid edge-cloud: 5 Pi edge nodes + 2 cloud VMs + Cloudflare serverless
- Zero-trust networking: Cloudflare tunnels for external access, WireGuard for internal mesh
- Multi-database strategy: PostgreSQL (relational), SQLite (embedded), D1 (serverless), KV (cache), Qdrant (vector)
- AI inference tier: 27 models distributed across 3 nodes with NPU acceleration (52 TOPS)

**Platform Scale**
- 7,212,320 lines of code across 1,603 GitHub repos (20 languages)
- 207 Gitea repos across 7 organizations (self-hosted)
- 99 Cloudflare Pages, 22 D1, 46 KV, 11 R2 for serverless layer
- 256 systemd services, 14 Docker containers, 48 Nginx sites

**Integration Design**
- GitHub ↔ Gitea sync relay (30-minute automated mirror)
- Cloudflare tunnel routing: 4 tunnels mapping 48+ domains to fleet services
- AI pipeline: model deployment → inference API → SSE streaming → web client
- KPI pipeline: 9 collectors → aggregation → Slack + markdown + terminal reports

**Brand & Product**
- 75 design templates with brand-locked design system (gradient, fonts, rules)
- 15 page template types covering full SaaS application surface
- Code search engine: 354 repos indexed with FTS5
- AI image generation hub with 4 backend agents

**Operational Architecture**
- Self-healing: heartbeat/heal cycles on all nodes
- Observability: 60+ KPIs, distributed tracing, power monitoring
- Security: credential rotation, firewall policies, zero-trust access
- Capacity: 707 GB storage, 20 GB RAM, 52 TOPS AI, auto-scaling via Cloudflare

---

## Technical Skills

**Architecture:** Hybrid edge-cloud, microservices, event-driven, zero-trust
**Cloud:** Cloudflare (full stack), DigitalOcean, Tailscale
**Compute:** Raspberry Pi fleet, Docker Swarm, systemd, Hailo-8 NPU
**Data:** PostgreSQL, SQLite, D1, KV, R2, Qdrant, FTS5
**Languages:** Python, JavaScript, TypeScript, Bash, Go, C

---

## Metrics

| Metric | Value |
|--------|-------|
| Total LOC | 7,212,320 |
| Repos | 309 (102 GH + 207 Gitea) |
| Databases | 283 |
| CF resources | 178 (99 Pages + 22 D1 + 46 KV + 11 R2) |
| AI models | 27 (48.1 GB) |
| Domains | 48+ |
| Services | 256 |
