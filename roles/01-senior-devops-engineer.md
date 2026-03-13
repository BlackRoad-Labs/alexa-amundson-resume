# Alexa Amundson

**Senior DevOps Engineer**

amundsonalexa@gmail.com | [github.com/blackboxprogramming](https://github.com/blackboxprogramming)

---

## Summary

DevOps engineer operating a 7-node distributed infrastructure spanning edge devices and cloud, with 52 automated tasks, 256 managed systemd services, and 99 Cloudflare deployments. Builds self-healing systems with automated monitoring, fleet-wide power optimization, and daily KPI collection across 9 data sources.

---

## Experience

### BlackRoad OS | Founder & Infrastructure Lead | 2025–Present

**Infrastructure Operations**
- Operate 5 Raspberry Pi nodes + 2 DigitalOcean droplets with WireGuard mesh VPN connecting all endpoints
- Manage 256 systemd services and 35 timers across fleet with self-healing autonomy scripts
- Deploy and maintain 14 Docker containers via Docker Swarm orchestration
- Route 48+ custom domains through 4 Cloudflare tunnels to backend services

**CI/CD & Automation**
- Built 212 CLI tools (121 MB) for infrastructure management and deployment
- Maintain 17 Mac cron jobs + 35 fleet timers for continuous automation
- Operate GitHub Actions CI/CD pipelines and self-hosted Gitea (207 repos)
- Automated GitHub-to-Gitea relay syncing every 30 minutes

**Cloud Infrastructure (Cloudflare)**
- Deployed 99 Pages projects, 22 D1 databases, 46 KV namespaces, 11 R2 buckets
- Manage Cloudflare Workers for edge compute and API routing

**Monitoring & Observability**
- Built daily KPI collection system tracking 60+ metrics across 9 collectors
- Implemented fleet power optimization with CPU governor tuning, voltage monitoring (avg 44.8°C)
- Created distributed observability with traces database and per-node SSH health probes
- Manage 48 Nginx reverse proxy sites with health checking

**Reliability**
- Implemented self-healing cron-based autonomy on all nodes (heartbeat 1m, heal 5m)
- Reduced node temperature from 73.8°C to 57.9°C by identifying and disabling runaway services
- Resolved undervoltage throttling via config.txt optimization (+95mV on one node)

---

## Technical Skills

**Infrastructure:** Linux (Debian/Raspberry Pi OS), Docker, Docker Swarm, systemd, Nginx, WireGuard
**Cloud:** Cloudflare (Pages, Workers, D1, KV, R2, Tunnels), DigitalOcean, Tailscale
**CI/CD:** GitHub Actions, Gitea, shell scripting, cron automation
**Languages:** Bash (91 scripts, 212 CLI tools), Python, JavaScript/TypeScript
**Monitoring:** Custom KPI system, power monitoring, thermal management, distributed tracing
**Databases:** PostgreSQL (11 DBs), SQLite (230 DBs), D1, KV stores

---

## Metrics

| Metric | Value |
|--------|-------|
| Nodes managed | 7 |
| Systemd services | 256 |
| Automated tasks | 52 |
| Docker containers | 14 |
| Cloudflare deployments | 99 |
| CLI tools built | 212 |
| Repos managed | 1,603 GitHub + 207 Gitea |
