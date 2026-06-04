# National Tsing Hua University (nthu)

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
