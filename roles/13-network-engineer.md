# Alexa Amundson

**Network Engineer**

amundsonalexa@gmail.com | [github.com/blackboxprogramming](https://github.com/blackboxprogramming)

---

## Summary

Network engineer operating a multi-layer network stack: WireGuard mesh VPN, Tailscale overlay (9 peers), RoadNet WiFi mesh (5 APs), 4 Cloudflare tunnels serving 48+ domains, DNS infrastructure (Pi-hole + PowerDNS + dnsmasq), and 48 Nginx reverse proxy sites across a 7-node fleet.

---

## Experience

### BlackRoad OS | Founder & Network Lead | 2025–Present

**VPN & Mesh Networking**
- WireGuard mesh VPN (10.8.0.x subnet) with DigitalOcean hub routing to all edge nodes
- Tailscale overlay network: 9 peers for management access across network boundaries
- RoadNet WiFi mesh: 5 access points on non-overlapping channels (1, 6, 11)
- Dedicated subnets: 10.10.{1-5}.0/24 per node with NAT through wlan0

**DNS Infrastructure**
- Pi-hole on Alice: fleet-wide ad blocking and DNS resolution
- PowerDNS on Lucidia (Docker): authoritative DNS for custom zones
- dnsmasq on Cecilia: custom DNS zones (.cece, .blackroad, .entity, .soul, .dream)
- Cloudflare DNS for 48+ public domains

**Reverse Proxy & Load Balancing**
- 48 Nginx sites routing traffic to fleet services
- 4 Cloudflare tunnels for zero-trust external access
- Per-service routing: API, web, git, AI inference endpoints
- SSL/TLS termination via Cloudflare

**Monitoring & Diagnostics**
- 106 active network connections monitored across fleet
- 867 processes tracked for network resource usage
- SSH-based fleet probing with health checks
- Daily KPI collection including connection counts and peer status

**Security**
- Zero-trust architecture via Cloudflare tunnels (no exposed ports)
- WireGuard encryption for all inter-node traffic
- UFW firewall on edge nodes (INPUT DROP policy)
- SSH key management across 50+ authorized keys

---

## Technical Skills

**VPN:** WireGuard, Tailscale
**DNS:** Pi-hole, PowerDNS, dnsmasq, Cloudflare DNS
**Proxy:** Nginx, Cloudflare Tunnels
**WiFi:** hostapd, RoadNet mesh configuration
**Security:** UFW, nftables, SSH hardening, TLS
**Monitoring:** Custom probes, ss, connection tracking

---

## Metrics

| Metric | Value |
|--------|-------|
| VPN nodes | 7 (WireGuard) |
| Tailscale peers | 9 |
| WiFi APs | 5 |
| Domains | 48+ |
| Nginx sites | 48 |
| CF tunnels | 4 |
| Connections | 106 |
