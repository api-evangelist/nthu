# National Tsing Hua University (nthu)

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

National Tsing Hua University (NTHU) is a national public research university in Hsinchu, Taiwan, ranked #210 in the QS World University Rankings 2025. This repository catalogs NTHU's public developer/API footprint as an [APIs.json](http://apisjson.org) provider profile. NTHU has no official institution-wide developer portal; its confirmed public API surface centers on the community-maintained **NTHU Data API**.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/nthu/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=nthu-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Taiwan, Open Data, Campus

## APIs

- **NTHU Data API** — Public REST API (v2.0.0, FastAPI/OpenAPI) aggregating campus data: announcements, buses, courses, departments, dining, energy usage, libraries, locations, and newsletters.
  - Docs: https://api.nthusa.tw/docs
  - OpenAPI: https://api.nthusa.tw/openapi.json
  - Source: https://github.com/NTHU-SA/NTHU-Data-API

## Plans

- [plans/nthu-plans-pricing.yml](plans/nthu-plans-pricing.yml)

## Rate Limits

- [rate-limits/nthu-rate-limits.yml](rate-limits/nthu-rate-limits.yml)

## FinOps

- [finops/nthu-finops.yml](finops/nthu-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.nthu.edu.tw/
- GitHub: https://github.com/NTHU-SA
- LinkedIn: https://www.linkedin.com/school/national-tsing-hua-university/
- Plans: plans/nthu-plans-pricing.yml
- Rate Limits: rate-limits/nthu-rate-limits.yml
- FinOps: finops/nthu-finops.yml
- Review: review.yml

## Notes

- The NTHU Data API is community/student-maintained (NTHU-SA, "NTHUSA 32nd"), not an official university service; endpoints were verified live (200) at /docs and /openapi.json on 2026-06-03.
- No official institution-wide developer portal, open-data portal, or documented authentication/SSO API was confirmed for NTHU.
- The institutional repository host (nthur.lib.nthu.edu.tw) did not resolve over TLS during review and is not cataloged as an API.
- No endpoints were fabricated; only verified URLs are recorded.

## Maintainers

- Kin Lane — kin@apievangelist.com
