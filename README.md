# Spike.sh

Spike.sh is an incident management and on-call platform serving engineering teams in 40+ countries. It provides alerting via phone, SMS, WhatsApp, Telegram, Slack, and Microsoft Teams, along with on-call scheduling, escalation policies, status pages, war rooms, and 80+ integrations with tools like Prometheus, Datadog, AWS, Sentry, and Linear.

## APIs.json Profile

This repository contains an APIs.json 0.19 profile cataloging the public API footprint of Spike.sh.

- **APIs.json**: [apis.yml](apis.yml)
- **Plans & Pricing**: [plans/spike-sh-plans-pricing.yml](plans/spike-sh-plans-pricing.yml)
- **Rate Limits**: [rate-limits/spike-sh-rate-limits.yml](rate-limits/spike-sh-rate-limits.yml)
- **FinOps**: [finops/spike-sh-finops.yml](finops/spike-sh-finops.yml)

## Key Resources

| Resource | URL |
|----------|-----|
| Website | https://spike.sh |
| API Docs | https://docs.spike.sh/spike-api-docs |
| Base URL | https://api.spike.sh |
| GitHub Org | https://github.com/spikehq |
| Pricing | https://spike.sh/pricing |
| Status Page | https://status.spike.sh |
| Blog | https://spike.sh/blog |
| LinkedIn | https://linkedin.com/company/spike-hq |
| X/Twitter | https://twitter.com/spikedhq |

## API Overview

The Spike.sh REST API uses API key authentication via the `x-api-key` header and team-scoped requests via `x-team-id`. Core resource domains include:

- **Incidents** — create, list, trigger, and resolve incidents
- **Services** — manage monitored services and their integrations
- **On-Call Schedules** — configure rotation schedules
- **Escalation Policies** — define alert escalation chains
- **Integrations** — manage connections to third-party monitoring tools
- **Teams** — administer team memberships and settings
- **Users** — manage user accounts
- **Alert Routing Rules** — configure conditional alert routing

## Maintainer

Kin Lane — kin@apievangelist.com
