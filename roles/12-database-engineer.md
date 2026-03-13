# Alexa Amundson

**Database Engineer**

amundsonalexa@gmail.com | [github.com/blackboxprogramming](https://github.com/blackboxprogramming)

---

## Summary

Database engineer managing 283 databases across 5 engines: 11 PostgreSQL, 230 SQLite (1.4 GB), 22 Cloudflare D1, 46 KV namespaces, and Qdrant vector DB. Designs schemas for AI agent memory, metrics collection, fleet state, and full-text search with FTS5.

---

## Experience

### BlackRoad OS | Founder & Data Lead | 2025–Present

**PostgreSQL**
- 11 production databases across 3 fleet nodes (Alice, Cecilia, Lucidia)
- Application state for CECE API, Lucidia API, and fleet services
- Automated backup and monitoring

**SQLite / FTS5**
- 230 SQLite databases (1.4 GB total) in ~/.blackroad/
- Key databases: metrics.db (6 tables), systems.db (111 entries), analytics.db, agents.db
- FTS5 full-text search index for code search across 354 repos
- Agent memory databases for AI conversation state
- Observability traces database with nanosecond-precision spans

**Cloudflare D1**
- 22 serverless databases (40 MB total) for edge applications
- images-blackroad: AI image generation metadata
- index-blackroad: code search index (2,524 files)
- blackroad-auth, blackroad-saas, blackroad-logs, and 17 more

**KV / Key-Value**
- 46 Cloudflare KV namespaces for edge state and configuration
- Agent inboxes, config, telemetry, templates, users, world state
- Low-latency edge reads for Cloudflare Workers

**Vector Database**
- Qdrant on Alice for semantic search and embeddings
- Knowledge retrieval for AI agent systems

**Schema Design**
- Metrics schema: metrics, counters, alerts, system_metrics, custom_metrics, metric_definitions
- Inventory schema: inventory, movements, locations
- Observability schema: traces, spans (parent-child), metrics, logs
- Dashboard schema: services, nodes, activity logs

---

## Technical Skills

**Databases:** PostgreSQL, SQLite, Cloudflare D1, KV stores, Qdrant
**Search:** FTS5 full-text search, vector similarity search
**Languages:** Python, SQL, JavaScript, Bash
**Infrastructure:** Linux, Docker, Cloudflare Workers
**Tools:** psql, sqlite3, Wrangler, custom CLI tools

---

## Metrics

| Metric | Value |
|--------|-------|
| Total databases | 283 |
| PostgreSQL DBs | 11 |
| SQLite DBs | 230 (1.4 GB) |
| D1 databases | 22 (40 MB) |
| KV namespaces | 46 |
| Systems tracked | 111 |
| Repos indexed | 354 |
