# Alexa Amundson

**Edge Computing Engineer**

amundsonalexa@gmail.com | [github.com/blackboxprogramming](https://github.com/blackboxprogramming)

---

## Summary

Edge computing engineer operating a 5-node Raspberry Pi fleet with 52 TOPS AI acceleration, 27 deployed models, WireGuard mesh networking, and carrier-grade WiFi mesh. Builds edge-native services with self-healing automation, thermal management, and hybrid edge-cloud architecture.

---

## Experience

### BlackRoad OS | Founder & Edge Lead | 2025–Present

**Edge Fleet**
- 5 Raspberry Pi nodes: 4× Pi 5 (8 GB RAM, NVMe), 1× Pi 400 (4 GB RAM)
- 2× Hailo-8 NPUs (26 TOPS each) for on-device AI inference
- 707 GB total fleet storage, 20 GB total RAM
- Docker Swarm orchestration with automatic service placement

**Edge AI**
- 27 Ollama models (48.1 GB) running locally across 3 nodes
- 4 custom fine-tuned models for domain-specific inference
- SSE proxy for streaming model responses to web clients
- Image generation pipeline with 4 backend agents

**Edge Networking**
- RoadNet: 5 WiFi access points (channels 1/6/11), dedicated 10.10.x.0/24 subnets
- WireGuard mesh VPN (10.8.0.x) connecting all nodes to cloud hub
- 4 Cloudflare tunnels for secure external access
- Pi-hole DNS, PowerDNS, custom dnsmasq zones at edge

**Edge Reliability**
- Self-healing cron automation on every node
- Power optimization: CPU governors, voltage tuning, thermal throttle prevention
- Avg fleet temperature: 44.8°C (down from 73.8°C peak after optimization)
- 256 systemd services managed across fleet

**Hybrid Architecture**
- Edge nodes handle AI inference, local services, DNS, monitoring
- Cloud (Cloudflare) handles 99 Pages deployments, 22 D1 databases, CDN
- DigitalOcean VMs as WireGuard hubs and public endpoints
- Tailscale overlay (9 peers) for cross-network management

---

## Technical Skills

**Edge:** Raspberry Pi 5, Hailo-8 NPU, NVMe, PCIe, GPIO, I2C
**Networking:** WireGuard, WiFi mesh, Cloudflare Tunnels, DNS (Pi-hole, PowerDNS)
**AI:** Ollama, Hailo-8 inference, custom model fine-tuning
**Containers:** Docker, Docker Swarm
**Automation:** systemd (256 services), cron (52 tasks), self-healing scripts

---

## Metrics

| Metric | Value |
|--------|-------|
| Edge nodes | 5 |
| AI acceleration | 52 TOPS |
| Models deployed | 27 (48.1 GB) |
| WiFi APs | 5 |
| Fleet storage | 707 GB |
| Avg temperature | 44.8°C |
| Services | 256 |
