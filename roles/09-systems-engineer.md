# Alexa Amundson

**Systems Engineer**

amundsonalexa@gmail.com | [github.com/blackboxprogramming](https://github.com/blackboxprogramming)

---

## Summary

Systems engineer managing 256 systemd services across a 7-node Linux fleet. Deep expertise in kernel tuning, power optimization, thermal management, device drivers (Hailo-8 NPU, I2C, GPIO, UART), and distributed system reliability with automated monitoring and self-healing.

---

## Experience

### BlackRoad OS | Founder & Systems Lead | 2025–Present

**Linux Systems**
- Manage 5 Raspberry Pi nodes (Debian Bookworm) + 2 Ubuntu VMs
- Configure and tune 256 systemd services and 35 timers
- Kernel parameter optimization: CPU governors, swappiness, dirty_ratio, WiFi power management
- Custom udev rules for device persistence (vcio, Hailo-8, USB peripherals)
- Boot configuration: cmdline.txt, config.txt, /etc/sysctl.d/ for persistent tuning

**Hardware & Device Drivers**
- 2× Hailo-8 AI accelerators: PCIe driver installation, /dev/hailo0 device management
- I2C devices: Pironman5 OLED display (0x3c), sensor interfaces
- UART/serial: CP2102 adapters, BL808 RISC-V dev boards
- GPIO: IR receivers, custom peripheral control
- NVMe storage: 1 TB drive on Octavia for high-speed workloads

**Performance Engineering**
- Resolved thermal throttling: identified runaway processes, reduced 73.8°C → 57.9°C
- Fixed undervoltage: removed overclock settings, tuned voltage (+95mV recovery)
- Power optimization deployed fleet-wide: conservative governors, GPU memory reduction (256→16 MB)
- Boot-persistent config via tmpfiles.d, rc.local, sysctl.d

**Networking**
- WireGuard mesh VPN across all nodes
- DNS infrastructure: Pi-hole, PowerDNS (Docker), dnsmasq with custom zones (.cece, .blackroad)
- Nginx (48 sites), Cloudflare tunnels (4), Tailscale (9 peers)
- Network diagnostics: 106 active connections monitored, 867 processes tracked

**Security**
- Credential rotation: migrated secrets from crontabs to env files (chmod 600)
- Identified and removed obfuscated cron dropper (malware)
- SSH key audit: 50+ keys on Alice/Octavia
- UFW firewall management on edge nodes

---

## Technical Skills

**OS:** Debian, Raspberry Pi OS, Ubuntu, systemd, udev, kernel tuning
**Hardware:** Hailo-8 NPU, Raspberry Pi 5, I2C, GPIO, UART, PCIe, NVMe
**Networking:** WireGuard, Tailscale, Nginx, DNS (Pi-hole, PowerDNS, dnsmasq)
**Security:** SSH hardening, credential management, firewall (UFW/nftables)
**Scripting:** Bash (212 tools, 91 scripts), Python

---

## Metrics

| Metric | Value |
|--------|-------|
| Systemd services | 256 |
| Fleet nodes | 7 |
| AI acceleration | 52 TOPS |
| Processes managed | 867 |
| Network connections | 106 |
| Automated tasks | 52 |
| CLI tools | 212 |
