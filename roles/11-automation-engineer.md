# Alexa Amundson

**Automation Engineer**

amundsonalexa@gmail.com | [github.com/blackboxprogramming](https://github.com/blackboxprogramming)

---

## Summary

Automation engineer who built 212 CLI tools, 52 scheduled tasks, and self-healing fleet automation across a 7-node infrastructure. Automates KPI collection (60+ metrics daily), deployment pipelines, fleet monitoring, power optimization, and cross-platform repository sync.

---

## Experience

### BlackRoad OS | Founder & Automation Lead | 2024–Present

**CLI Tooling**
- Built 212 CLI tools (121 MB) in ~/bin covering deployment, monitoring, stats, and fleet management
- 91 shell scripts for infrastructure automation
- Custom RoadC programming language with lexer, parser, and tree-walking interpreter
- `br-stats`, `br-upload`, `br-generate`, `roadid`, `carpool` — production CLI tools

**Scheduled Automation**
- 17 Mac cron jobs: health monitoring (5m), sync (15m), website automation (30m), backups (daily/6h/12h)
- 35 systemd timers across fleet for service monitoring and data collection
- Self-healing autonomy: heartbeat (1m) + heal (5m) cycles on all Pi nodes
- GitHub-to-Gitea relay: 30-minute sync across 207 repos

**KPI Automation**
- 9-collector daily KPI system: GitHub, Gitea, fleet, services, autonomy, LOC, local, Cloudflare, deep GitHub
- Automated fleet probing via SSH with Python-based remote execution
- Daily Slack reporting (block kit formatting)
- Markdown report generation for GitHub README auto-update
- Day-over-day delta tracking with visual progress bars

**Deployment Automation**
- 99 Cloudflare Pages with git-push deployment
- GitHub Actions CI/CD pipelines
- Docker Swarm service orchestration
- Fleet-wide power optimization with --apply mode

**Fleet Automation**
- Power monitoring deployed to all nodes (5-minute intervals)
- CPU governor persistence via tmpfiles.d
- Automated service discovery and restart
- Credential rotation from plaintext to secured env files

---

## Technical Skills

**Scripting:** Bash (212 tools), Python, JavaScript
**Automation:** cron, systemd timers, GitHub Actions, Docker Swarm
**Tools:** Wrangler, gh CLI, SSH, rsync, rclone
**Monitoring:** Custom KPI system, Slack webhooks, distributed tracing
**Infrastructure:** Linux, Docker, Cloudflare, WireGuard

---

## Metrics

| Metric | Value |
|--------|-------|
| CLI tools | 212 |
| Automated tasks | 52 |
| KPI metrics | 60+ |
| Data collectors | 9 |
| Shell scripts | 91 |
| Cron jobs (Mac) | 17 |
| Fleet timers | 35 |
