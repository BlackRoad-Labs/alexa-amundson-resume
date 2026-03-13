# Alexa Amundson

**Infrastructure Engineer**

amundsonalexa@gmail.com | [github.com/blackboxprogramming](https://github.com/blackboxprogramming)

---

## Summary

Infrastructure engineer building and operating a 7-node distributed compute fleet with 707 GB storage, 20 GB RAM, 52 TOPS AI acceleration, and WireGuard mesh networking. Manages 256 systemd services, 14 Docker containers, and 48+ production domains with automated monitoring and self-healing.

---

## Experience

### BlackRoad OS | Founder & Infrastructure Lead | 2024–Present

**Physical Infrastructure**
- Built and maintain 5 Raspberry Pi edge nodes (4× Pi 5 with NVMe, 1× Pi 400)
- Installed and configured 2× Hailo-8 AI accelerators (52 TOPS combined)
- Managed hardware: NVMe drives, Pironman5 enclosures, OLED displays (I2C), UART adapters
- Resolved undervoltage issues via config.txt tuning, power supply assessment, overclock removal

**Network Infrastructure**
- WireGuard mesh VPN (10.8.0.x) connecting all nodes through DigitalOcean hub
- RoadNet WiFi mesh: 5 access points on channels 1/6/11, dedicated 10.10.x.0/24 subnets per node
- 4 Cloudflare tunnels for zero-trust external access to 48+ domains
- 48 Nginx reverse proxy configurations
- DNS infrastructure: Pi-hole (Alice), PowerDNS (Lucidia), custom dnsmasq zones (Cecilia)

**Compute Management**
- 256 systemd services and 35 timers across fleet
- 14 Docker containers via Docker Swarm
- 27 Ollama models (48.1 GB) across 3 inference nodes
- 11 PostgreSQL databases, 230 SQLite databases

**Automation**
- 212 CLI tools for fleet management
- 52 automated tasks (17 Mac cron + 35 fleet timers)
- Self-healing autonomy on all nodes (heartbeat + heal cycles)
- Fleet power optimization: CPU governors, swappiness, dirty_ratio, WiFi PM, GPU memory reduction

---

## Technical Skills

**Hardware:** Raspberry Pi 5, Hailo-8 NPU, NVMe, I2C, GPIO, USB, PCIe
**Networking:** WireGuard, Tailscale, Nginx, DNS (Pi-hole, PowerDNS, dnsmasq), Cloudflare Tunnels
**OS:** Debian/Raspberry Pi OS, systemd, udev, kernel tuning (cmdline.txt, config.txt, sysctl)
**Containers:** Docker, Docker Swarm
**Monitoring:** Custom KPI system (60+ metrics), thermal monitoring, voltage tracking

---

## Metrics

| Metric | Value |
|--------|-------|
| Fleet nodes | 7 |
| Total storage | 707 GB |
| Total RAM | 20 GB |
| AI compute | 52 TOPS |
| Systemd services | 256 |
| Network connections | 106 |
| Domains served | 48+ |
