# Spike.sh

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
