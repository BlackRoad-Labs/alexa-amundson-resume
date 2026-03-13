# Alexa Amundson

**Data Engineer**

amundsonalexa@gmail.com | [github.com/blackboxprogramming](https://github.com/blackboxprogramming)

---

## Summary

Data engineer building pipelines that collect, aggregate, and report 60+ KPIs daily across 9 data sources. Manages 283 databases (PostgreSQL, SQLite, D1, KV), FTS5 search indexes, and distributed tracing infrastructure across a 7-node fleet.

---

## Experience

### BlackRoad OS | Founder & Data Lead | 2024–Present

**Data Pipelines**
- Built 9-collector KPI pipeline: GitHub API, Gitea API, SSH fleet probes, Cloudflare API, local system metrics
- Daily aggregation of 60+ metrics into timestamped JSON snapshots
- Day-over-day delta computation for trend tracking
- Multi-format output: terminal report, Slack (block kit), markdown, raw JSON

**Data Collection**
- GitHub collector: commits, PRs, events, languages, stars, forks via `gh` CLI API
- Fleet collector: Python probes piped over SSH to each node (CPU, RAM, disk, Docker, Ollama)
- Services collector: deep inspection of Ollama, Docker, PostgreSQL, Nginx, systemd per node
- Autonomy collector: self-healing events, cron jobs, timers, service restarts
- Cloudflare collector: D1 databases, KV namespaces, R2 buckets, Pages projects

**Data Storage**
- 11 PostgreSQL databases across fleet
- 230 SQLite databases (1.4 GB) with 111 registered systems
- 22 D1 databases (40 MB) for serverless applications
- 46 KV namespaces for edge state
- FTS5 index across 354 repos and 156,675 memory entries

**Data Quality**
- All KPI metrics machine-verified from live sources
- Automated collection via cron (6 AM daily) + GitHub Actions
- Snapshot retention: daily JSON files with full source data
- Distributed tracing with nanosecond-precision spans

**Reporting**
- Terminal dashboard with color-coded metrics and progress bars
- Slack webhook integration with block kit formatting
- Markdown report for GitHub README auto-update
- Historical comparison with delta indicators

---

## Technical Skills

**Pipelines:** Bash, Python, SSH, cron, GitHub Actions
**Databases:** PostgreSQL, SQLite/FTS5, Cloudflare D1, KV
**APIs:** GitHub API, Cloudflare API, Gitea API, Ollama API
**Formats:** JSON, Markdown, Slack Block Kit
**Tools:** gh CLI, Wrangler, Python (json, urllib), Bash

---

## Metrics

| Metric | Value |
|--------|-------|
| Daily KPIs tracked | 60+ |
| Data collectors | 9 |
| Databases managed | 283 |
| Data pipeline runs | Daily automated |
| Repos indexed | 354 |
| Memory entries | 156,675 |
| Report formats | 4 |
