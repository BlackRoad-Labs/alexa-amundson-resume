# Alexa Louise Amundson — Professional Resume Portfolio

[![Security Scan](https://github.com/blackboxprogramming/alexa-amundson-resume/actions/workflows/security-scan.yml/badge.svg)](https://github.com/blackboxprogramming/alexa-amundson-resume/actions/workflows/security-scan.yml)
[![Auto Deploy](https://github.com/blackboxprogramming/alexa-amundson-resume/actions/workflows/auto-deploy.yml/badge.svg)](https://github.com/blackboxprogramming/alexa-amundson-resume/actions/workflows/auto-deploy.yml)
[![Self-Healing](https://github.com/blackboxprogramming/alexa-amundson-resume/actions/workflows/self-healing.yml/badge.svg)](https://github.com/blackboxprogramming/alexa-amundson-resume/actions/workflows/self-healing.yml)

**The Executive Who Codes AND Closes**

---

## Contact Information

- **Email:** amundsonalexa@gmail.com | blackroad.systems@gmail.com
- **Phone:** (507) 828-0842
- **LinkedIn:** [linkedin.com/in/alexaamundson](https://linkedin.com/in/alexaamundson)
- **GitHub:** [@blackboxprogramming](https://github.com/blackboxprogramming)
- **Portfolio:** [lucidia.earth](https://lucidia.earth) | [blackroadinc.us](https://blackroadinc.us)
- **Live Platform:** [app.blackroad.io](https://app.blackroad.io)

---

## Repository Contents

This repository contains a complete professional resume portfolio, including technical documentation, performance reviews, and thought leadership white papers.

### Resume Formats

| File | Word Count | Purpose |
|------|------------|---------|
| [alexa-amundson-one-pager.md](alexa-amundson-one-pager.md) | ~710 | Quick intro, elevator pitch, email attachment |
| [alexa-amundson-resume.md](alexa-amundson-resume.md) | ~756 | Standard resume format |
| [alexa-amundson-resume-enhanced.md](alexa-amundson-resume-enhanced.md) | ~1,809 | Enhanced with detailed metrics |
| [alexa-amundson-resume-ultimate.md](alexa-amundson-resume-ultimate.md) | ~8,651 | Comprehensive technical + commercial |
| [alexa-amundson-resume-executive.md](alexa-amundson-resume-executive.md) | ~6,582 | Executive deep dive with financials |
| [alexa-amundson-resume-master.md](alexa-amundson-resume-master.md) | ~8,840 | Complete business case |

### Supporting Documents

| File | Word Count | Purpose |
|------|------------|---------|
| [alexa-amundson-testimonials.md](alexa-amundson-testimonials.md) | ~2,987 | Performance reviews, manager testimonials, peer references |
| [alexa-amundson-white-papers.md](alexa-amundson-white-papers.md) | ~4,471 | Technical deep dives, research papers, case studies |

### Total Portfolio

- **Total Word Count:** ~35,760 words
- **Total Files:** 8 resume/supporting documents + README

---

## Quick Start

**For Recruiters/Hiring Managers:**
- Start with: [One-Page Summary](alexa-amundson-one-pager.md)
- Then read: [Enhanced Resume](alexa-amundson-resume-enhanced.md)
- Deep dive: [Executive Resume](alexa-amundson-resume-executive.md)

**For Investors:**
- Start with: [Master Resume](alexa-amundson-resume-master.md)
- Deep dive: [Complete Master Resume](alexa-amundson-resume-master.md)

**For Technical Leaders:**
- Start with: [White Papers](alexa-amundson-white-papers.md)
- Deep dive: [Master Resume](alexa-amundson-resume-master.md)

---

## CI/CD & Infrastructure

This repository uses production-grade CI/CD with all GitHub Actions pinned to commit hashes.

### Workflows

| Workflow | Trigger | Purpose |
|----------|---------|---------|
| **Security Scan** | Push, PR, weekly schedule | Secret detection, markdown validation, dependency review |
| **Auto Deploy** | Push to main | Deploy to Cloudflare Pages, Vercel, or Railway (configurable) |
| **Self-Healing** | Every 6 hours, post-deploy | Health monitoring, auto-issue creation, content validation |

### Deployment Targets

Deployments are controlled via repository variables. Set the corresponding variable to `true` to enable:

| Platform | Variable | Secrets Required |
|----------|----------|-----------------|
| Cloudflare Pages | `CLOUDFLARE_ENABLED` | `CLOUDFLARE_API_TOKEN`, `CLOUDFLARE_ACCOUNT_ID` |
| Vercel | `VERCEL_ENABLED` | `VERCEL_TOKEN`, `VERCEL_ORG_ID`, `VERCEL_PROJECT_ID` |
| Railway | `RAILWAY_ENABLED` | `RAILWAY_TOKEN` |

### Health Monitoring

Set the `DEPLOY_URL` repository variable to enable health checks. The self-healing workflow will:
1. Check the deployment URL every 6 hours
2. Automatically create a GitHub issue if the health check fails
3. Avoid duplicate issues for the same failure

### Dependabot

Dependabot is configured to automatically update GitHub Actions dependencies weekly and create PRs for review.

### Pinned Action Versions

All GitHub Actions are pinned to specific commit hashes for supply-chain security:

| Action | Version | Hash |
|--------|---------|------|
| `actions/checkout` | v4.2.2 | `11bd71901bbe5b1630ceea73d27597364c9af683` |
| `actions/setup-node` | v4.4.0 | `49933ea5288caeca8642d1e84afbd3f7d6820020` |
| `actions/dependency-review-action` | v4.7.1 | `da24556b548a50705dd671f47852072ea4c105d9` |
| `actions/github-script` | v7.0.1 | `60a0d83039c74a4aee543508d2ffcb1c3799cdea` |
| `cloudflare/wrangler-action` | v3.14.1 | `da0e0dfe58b7a431659754fdf3f186c529afbe65` |

---

## Key Highlights

### The Rare Tri-Hybrid: Technical + Commercial + Compliance

- Built 466,408 lines of production code achieving 99.9% uptime (BlackRoad OS)
- Closed $26.8M in enterprise sales (92% quota in 11 months at Securian Financial)
- Passed SOX audits with zero findings (automated compliance engine)
- Led keynote presentations to 450+ attendees (4.8/5.0 rating)
- Earned Thought-Leadership Award (Ameriprise Financial)

### Quantified Impact (Last 18 Months)

| Category | Metric | Value |
|----------|--------|-------|
| Revenue Generated | Enterprise sales closed | $26.8M |
| Cost Reduction | Cloud + CRM automation | $438K/year |
| Platform Built | Production codebase | 466,408 LOC |
| System Reliability | Production uptime | 99.9% |
| Sales Performance | Close rate | 15% (2.5x team avg) |
| Team Impact | Productivity gains | $399K/year |

---

## License

This resume portfolio is covered by the BlackRoad OS, Inc. Proprietary License. See [LICENSE](LICENSE) for details.

---

## Contact

- **Email:** amundsonalexa@gmail.com
- **Phone:** (507) 828-0842
- **LinkedIn:** [linkedin.com/in/alexaamundson](https://linkedin.com/in/alexaamundson)
- **GitHub:** [@blackboxprogramming](https://github.com/blackboxprogramming)

---

**Last Updated:** March 2026
**Repository:** [github.com/blackboxprogramming/alexa-amundson-resume](https://github.com/blackboxprogramming/alexa-amundson-resume)
