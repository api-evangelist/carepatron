# Carepatron (carepatron)

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

Carepatron is a cloud-based healthcare practice management and EHR platform for therapists, counselors, psychologists, health coaches, nutritionists, and other practitioners. It brings client records, appointment scheduling and online booking, telehealth, AI-assisted clinical notes and documentation, and billing/invoicing with insurance claims into one workspace, and markets HIPAA/SOC/GDPR compliance across 100,000+ clinicians in 120+ countries.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/carepatron/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/carepatron/refs/heads/main/apis.yml)

## API Access Status: Gated / "Coming Soon"

As of this review (2026-07-10), **Carepatron does not publish a documented public developer API.** Specifically:

- Carepatron's own [pricing page](https://www.carepatron.com/pricing/) lists **"API (coming soon)"** as an Advanced-plan feature — programmatic access is planned but not yet generally available.
- There is **no developer portal, no API reference, no published base URL, no OpenAPI/Swagger definition, and no official SDK.**
- The public [GitHub organization](https://github.com/Carepatron) contains only build/tooling repositories (no API, SDK, or API-docs repo).
- Third-party connectivity today is limited to a small set of native integrations (Zoom, accounting software, Google Tag Manager) surfaced in the "Connecting Third Party Apps" help collection.

Because there is no documented API surface, the APIs listed in `apis.yml` are **logical product-area groupings modeled from Carepatron's feature set for cataloging purposes only**. Their endpoints are marked `endpointsModeled: true` and are **not confirmed or documented** — no base URLs or endpoints have been fabricated.

## Modeled APIs

- **Carepatron Clients API (Modeled)** — client/patient records, demographics, intake.
- **Carepatron Appointments API (Modeled)** — scheduling, online booking, reminders.
- **Carepatron Notes and Documentation API (Modeled)** — clinical notes, forms, intakes, AI scribe.
- **Carepatron Billing API (Modeled)** — invoices, payments, insurance claims.

## Tags

- Healthcare
- Practice Management
- EHR
- Therapy
- Telehealth
- Scheduling
- Clinical Notes
- Medical Billing

## Timestamps

- **Created:** 2026-07-10
- **Modified:** 2026-07-10

## Pricing

Carepatron is priced **per practitioner (per user) per month** with a free-forever tier. Regular rates from the public pricing page:

- **Free** — $0 (telehealth, client portal, scheduling, AI scribe; 1 GB storage, 1M AI tokens, 1K tasks).
- **Plus** — $31/user/month (unlimited storage, AI tokens, tasks, advanced workflows). Promotional $15.50 for 6 months.
- **Advanced** — $39/user/month (group telehealth, roles & permissions, white labeling, premium support, "API coming soon"). Promotional $19.50 for 6 months.

See [plans/carepatron-plans-pricing.yml](plans/carepatron-plans-pricing.yml).

## Common Properties

- [Website](https://www.carepatron.com)
- [LinkedIn](https://www.linkedin.com/company/carepatron)
- [GitHub Organization](https://github.com/Carepatron)
- [Documentation](https://help.carepatron.com/en/)
- [Plans](plans/carepatron-plans-pricing.yml)
- [Pricing](https://www.carepatron.com/pricing/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
