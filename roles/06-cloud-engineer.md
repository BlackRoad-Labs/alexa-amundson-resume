# Alexa Amundson

**Cloud Engineer**

amundsonalexa@gmail.com | [github.com/blackboxprogramming](https://github.com/blackboxprogramming)

---

## Summary

Cloud engineer managing a hybrid edge-cloud infrastructure: 99 Cloudflare Pages, 22 D1 databases, 46 KV namespaces, 11 R2 buckets, 2 DigitalOcean droplets, and 5 edge nodes connected via WireGuard mesh VPN. Serves 48+ domains through 4 Cloudflare tunnels.

---

## Experience

### BlackRoad OS | Founder & Cloud Architect | 2024–Present

**Cloudflare Platform**
- Deploy and manage 99 Pages projects with git-based CI/CD
- Operate 22 D1 serverless databases (40 MB total) for application state
- Manage 46 KV namespaces for edge configuration and caching
- Maintain 11 R2 object storage buckets for assets, models, and artifacts
- Route 48+ custom domains through 4 Cloudflare tunnels to fleet services

**Hybrid Cloud Architecture**
- 5 Raspberry Pi edge nodes (4× Pi 5, 1× Pi 400) with 20 GB RAM, 707 GB storage
- 2 DigitalOcean droplets (NYC regions) for WireGuard hub and public services
- WireGuard mesh VPN connecting all nodes (10.8.0.x subnet)
- Tailscale overlay network with 9 peers for management access
- RoadNet WiFi mesh (5 APs) for local device connectivity

**Compute & Services**
- 14 Docker containers via Docker Swarm (leader on Octavia)
- 256 systemd services managed across fleet
- 48 Nginx reverse proxy sites
- 11 PostgreSQL databases, 230 SQLite databases

**Security & Networking**
- Cloudflare tunnels for zero-trust access to fleet services
- WireGuard encryption for inter-node communication
- UFW firewall policies on edge nodes
- Credential management via secured env files (chmod 600)

**Monitoring**
- Daily KPI collection across all cloud and edge infrastructure
- 60+ metrics tracked: deployments, database sizes, fleet health
- Power and thermal monitoring on all edge nodes
- Automated alerting for service failures

---

## Technical Skills

**Cloud:** Cloudflare (Pages, Workers, D1, KV, R2, Tunnels, DNS), DigitalOcean
**Networking:** WireGuard, Tailscale, Nginx, DNS (Pi-hole, PowerDNS), Cloudflare DNS
**Containers:** Docker, Docker Swarm, container orchestration
**Infrastructure:** Linux, systemd, Raspberry Pi, edge computing
**IaC:** Shell automation (212 CLI tools), cron, GitHub Actions

---

## Metrics

| Metric | Value |
|--------|-------|
| Cloudflare Pages | 99 |
| D1 databases | 22 |
| KV namespaces | 46 |
| R2 buckets | 11 |
| Domains managed | 48+ |
| CF tunnels | 4 |
| Edge nodes | 5 |
| Cloud VMs | 2 |
