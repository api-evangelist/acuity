# Acuity Scheduling (acuity)

Acuity Scheduling is an online appointment scheduling platform that enables businesses and independent professionals to automate their booking workflows. The platform provides a REST API for managing appointment types, client availability, bookings, and client records. Developers can integrate scheduling functionality into applications using HTTP Basic Auth or OAuth2, with support for webhooks to receive real-time event notifications. Acuity is a subsidiary of Squarespace and offers SDKs for Node.js and PHP alongside its embeddable client scheduler widget.

APIs.json: https://raw.githubusercontent.com/api-evangelist/acuity/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=acuity-api-evangelist&utm_content=repo

## Tags

- Scheduling
- Appointments
- Calendar
- Booking
- HIPAA
- Webhooks

## APIs

### Acuity Scheduling API

The Acuity Scheduling REST API allows developers to programmatically manage appointments, appointment types, availability, client records, calendar integrations, packages, gift certificates, and forms. Authentication is supported via HTTP Basic Auth or OAuth2 for multi-account integrations. The API base URL is `https://acuityscheduling.com/api/v1/` and all responses are JSON.

- Documentation: https://developers.acuityscheduling.com/
- Base URL: https://acuityscheduling.com/api/v1/
- OpenAPI index: https://developers.acuityscheduling.com/llms.txt

## Plans, Rate Limits & FinOps

- Plans & Pricing: [plans/acuity-plans-pricing.yml](plans/acuity-plans-pricing.yml)
- Rate Limits: [rate-limits/acuity-rate-limits.yml](rate-limits/acuity-rate-limits.yml)
- FinOps: [finops/acuity-finops.yml](finops/acuity-finops.yml)

**Pricing summary:**

| Plan | Monthly | Annual (per month) | API Access |
|---|---|---|---|
| Starter | $20 | $16 | No |
| Standard | $34 | $27 | No |
| Premium | $61 | $49 | Yes |
| Enterprise | Custom | Custom | Yes |

**Rate limits:** 10 requests/second per IP, 20 concurrent connections, 25 webhooks per account.

## Timestamps

- Created: 2026-06-13
- Modified: 2026-06-13

## Common

| Type | URL |
|---|---|
| Website | https://acuityscheduling.com/ |
| Documentation | https://developers.acuityscheduling.com/ |
| GitHub Org | https://github.com/AcuityScheduling |
| LinkedIn | https://www.linkedin.com/company/acuity-scheduling |
| Blog | https://www.acuityscheduling.com/learn |
| Pricing | https://acuityscheduling.com/signup.php |
| Status Page | https://status.acuityscheduling.com/ |
| X | https://twitter.com/acuityschedulin |

## Maintainers

- Kin Lane (kin@apievangelist.com)
