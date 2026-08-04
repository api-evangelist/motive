# Motive (motive)

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

Motive (formerly KeepTruckin) is a fleet management platform serving more than 120,000 businesses across trucking, logistics, construction, agriculture, and field service industries. The Motive REST API provides programmatic access to driver management, vehicle tracking, Hours of Service (HOS) compliance, IFTA reporting, dashcam events, dispatch workflows, geofencing, and real-time location data. Developers authenticate via OAuth 2.0 with scoped access tokens and can reach endpoints at `api.gomotive.com` (or the legacy `api.keeptruckin.com` base URL). The self-serve Developer Portal allows partners to build and publish apps to the Motive App Marketplace.

APIs.json: https://raw.githubusercontent.com/api-evangelist/motive/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=motive-api-evangelist&utm_content=repo

## Tags

Fleet Management, Trucking, Logistics, GPS Tracking, Hours of Service, ELD, IFTA, Dashcam, Dispatch, Compliance, Driver Management

## APIs

| Name | Description | Base URL |
|------|-------------|----------|
| Motive Fleet API | Core REST API for driver management, vehicle tracking, HOS, IFTA, dispatch, webhooks, and more | https://api.gomotive.com |

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/motive-plans-pricing.yml](plans/motive-plans-pricing.yml) |
| Rate Limits | [rate-limits/motive-rate-limits.yml](rate-limits/motive-rate-limits.yml) |
| FinOps | [finops/motive-finops.yml](finops/motive-finops.yml) |

Motive does not publish a public per-call API pricing schedule. API access is bundled with fleet management subscriptions (estimated ~$35/vehicle/month). Rate limits are set at Motive's discretion and are not publicly documented; a 429 status code with a `Retry-After` header is returned when limits are exceeded.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://gomotive.com/ |
| Developer Portal | https://developer.gomotive.com/ |
| Documentation | https://developer-docs.gomotive.com/docs/introduction |
| API Reference | https://developer-docs.gomotive.com/reference/introduction |
| GitHub Organization | https://github.com/KeepTruckin |
| LinkedIn | https://www.linkedin.com/company/motive-inc |
| X / Twitter | https://twitter.com/Motive_inc |
| Blog | https://gomotive.com/blog/ |
| Status Page | https://status.gomotive.com/ |
| Terms of Service | https://gomotive.com/legal/api-terms-of-service/ |

## Maintainers

- Kin Lane / kin@apievangelist.com
