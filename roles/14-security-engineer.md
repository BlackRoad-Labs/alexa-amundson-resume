# Alexa Amundson

**Security Engineer**

amundsonalexa@gmail.com | [github.com/blackboxprogramming](https://github.com/blackboxprogramming)

---

## Summary

Security engineer who identified and remediated malware, credential leaks, and misconfigurations across a 7-node distributed fleet. Implements zero-trust networking via Cloudflare tunnels, WireGuard encryption, firewall policies, and credential management across 256 managed services.

---

## Experience

### BlackRoad OS | Founder & Security Lead | 2025–Present

**Incident Response**
- Discovered and removed obfuscated cron dropper executing from /tmp/op.py (Cecilia)
- Identified leaked GitHub PAT (gho_Gfu...) in Lucidia service file, initiated rotation
- Found and investigated xmrig crypto miner service configuration on Lucidia
- Migrated credentials from plaintext crontabs to secured env files (chmod 600) fleet-wide

**Network Security**
- Zero-trust architecture: all external access through 4 Cloudflare tunnels (no exposed ports)
- WireGuard encryption for all inter-node communication (10.8.0.x mesh)
- UFW firewall with INPUT DROP policy on edge nodes
- Tailscale ACLs for management access (9 peers)

**Access Management**
- SSH key audit: identified 50+ keys on Alice and Octavia requiring cleanup
- NOPASSWD sudo policies documented across all nodes
- Identified 3 Tailscale ghost nodes (offline 15+ days) for decommissioning
- Per-user cron job audit across all fleet nodes

**Infrastructure Hardening**
- Disabled 16 unused skeleton microservices (freed 800 MB RAM, reduced attack surface)
- Masked crash-looping services (rpi-connect-wayvnc) to prevent service abuse
- Removed overclock settings causing instability
- Secured GitHub relay credentials in ~/.github-relay.env (chmod 600)

**Monitoring & Detection**
- Self-healing autonomy scripts detecting and restarting failed services
- 12 failed systemd units tracked and investigated daily
- Fleet-wide power monitoring detecting anomalous CPU usage
- Daily KPI collection tracking security-relevant metrics

---

## Technical Skills

**Security:** Incident response, credential management, malware removal, hardening
**Networking:** WireGuard, Cloudflare Tunnels (zero-trust), UFW, nftables, Tailscale
**Linux:** systemd, SSH, file permissions, audit, service isolation
**Monitoring:** Custom KPI system, anomaly detection, SSH probes
**Tools:** Bash (212 CLI tools), Python, GitHub CLI

---

## Metrics

| Metric | Value |
|--------|-------|
| Incidents remediated | 5+ |
| Services managed | 256 |
| Firewall policies | UFW + nftables |
| VPN tunnels | 4 CF + 7 WG |
| Services disabled | 16+ |
| Credentials rotated | 4+ |
| Fleet nodes secured | 7 |
