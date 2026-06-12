# Motive (motive)

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
