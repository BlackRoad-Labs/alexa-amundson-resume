# Alexa Amundson

**Site Reliability Engineer**

amundsonalexa@gmail.com | [github.com/blackboxprogramming](https://github.com/blackboxprogramming)

---

## Summary

SRE managing a 7-node distributed fleet with 256 systemd services, 52 automated tasks, and self-healing autonomy. Maintains 48+ production domains, 99 Cloudflare deployments, and a daily KPI system tracking 60+ reliability metrics across 9 data sources.

---

## Experience

### BlackRoad OS | Founder & SRE Lead | 2024–Present

**Reliability & Uptime**
- Operate 5 Raspberry Pi edge nodes + 2 cloud VMs with WireGuard mesh connectivity
- Implement self-healing cron automation: heartbeat every 1 minute, heal cycle every 5 minutes
- Monitor and resolve 12 failed systemd units across fleet with automated restart policies
- Manage 48 Nginx reverse proxy sites routing traffic to backend services

**Incident Response**
- Identified and resolved thermal throttling (73.8°C → 57.9°C) caused by runaway Ollama loops
- Fixed undervoltage issues across Pi fleet via config.txt tuning (+95mV recovery)
- Discovered and removed obfuscated cron dropper (security incident on Cecilia)
- Resolved swap exhaustion (100% on Cecilia) by identifying memory-hungry services
- Migrated leaked credentials from plaintext crontabs to secured env files (chmod 600)

**Monitoring & Observability**
- Built 9-collector KPI system: GitHub, Gitea, fleet, services, autonomy, LOC, local, Cloudflare, deep GitHub
- Track 60+ metrics daily: commits, fleet health, temperatures, swap, processes, connections
- Distributed tracing database with nanosecond-precision spans
- Per-node SSH health probes with Python-based remote execution
- Power monitoring deployed to all nodes (cron every 5 minutes, persistent logs)

**Infrastructure Management**
- 14 Docker containers via Docker Swarm with leader election
- 11 PostgreSQL databases with automated backup
- 9 Tailscale mesh peers for secure cross-network access
- 4 Cloudflare tunnels routing 48+ domains to fleet services

**Capacity Planning**
- Fleet: 20 GB RAM, 707 GB storage, 52 TOPS AI compute
- Identified and disabled 16 skeleton microservices freeing 800 MB RAM
- Cleaned 19 GB of stale GitHub Actions runner directories
- Power optimization: conservative CPU governors, WiFi power management, GPU memory reduction

---

## Technical Skills

**SRE:** systemd, cron, Nginx, Docker Swarm, WireGuard, Tailscale, Cloudflare Tunnels
**Monitoring:** Custom KPI collection, distributed tracing, thermal/voltage monitoring, SSH probes
**Incident Response:** Root cause analysis, credential rotation, service isolation, capacity recovery
**Languages:** Bash (212 CLI tools), Python, JavaScript
**Cloud:** Cloudflare (99 Pages, 22 D1, 46 KV, 11 R2), DigitalOcean

---

## Metrics

| Metric | Value |
|--------|-------|
| Services managed | 256 |
| Automated tasks | 52 |
| Domains served | 48+ |
| KPI metrics tracked | 60+ |
| Fleet nodes | 7 |
| Incident resolutions | 10+ |
| Docker containers | 14 |
