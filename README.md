# Acuity Scheduling (acuity)

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
