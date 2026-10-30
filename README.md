# National Tsing Hua University

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

National Tsing Hua University (NTHU) is a national public research university in Hsinchu, Taiwan, founded in Beijing in 1911 and re-established in Taiwan in 1956. It has no central developer portal, no API catalog and no institution-wide API program, and this profile is deliberately small because the honest footprint is small. It does, however, hold something most of this cohort does not: one genuinely institution-operated, institution-governed API. NTHU's Computer and Communication Center runs an OAuth 2.0 authorization and identity service at oauth.ccxp.nthu.edu.tw, fronting the Academic Information System (CCXP), documented by the university in its own interface manual, governed by a regulation passed by the Computer and Communication Committee in December 2020, and carrying a published scheduled repeal date of 2027-07-31. It is not self-service — a request needs a unit head's signature, Computer and Communication Center review, and sign-off from every unit that owns a requested data field — but it is NTHU's own engineering on NTHU's own host. Everything else programmable that carries NTHU's name is operated by someone else. The widely cited NTHU Data API, a live FastAPI service with an OpenAPI 3.1.0 description and 22 keyless public paths over campus announcements, buses, courses, departments, dining, energy, library spaces, locations and newsletters, is built and hosted by the NTHU Student Association on nthusa.tw, not by the university on nthu.edu.tw. The research portal at scholars.nthu.edu.tw is an Ex Libris Esploro tenant, and the library discovery service is an Ex Libris Primo VE tenant shared through the University System of Taiwan consortium. Those are real institutional facts and they are recorded as tenant relationships, but they are not NTHU's contracts and are not scored as such.

**Areas:** Education · Higher Education · University · Taiwan · Public Research University · Identity · Authentication · Open Data · Campus · Course Catalog · Research Repository · Library

## National Tsing Hua University on APIs.io

Everything profiled for National Tsing Hua University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nthu/](https://apis.io/providers/nthu/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [NTHU Data API](https://apis.io/apis/nthu/nthu-data-api/) — A live, keyless, MIT-licensed FastAPI service publishing 22 paths over NTHU campus data — announcements by unit, campus bus routes and schedules, the course…
- [NTHU Research Portal (Esploro tenant)](https://apis.io/apis/nthu/nthu-research-portal/) — NTHU's institutional research repository and researcher-profile portal, running on Ex Libris Esploro. The former institutional repository host…
- [NTHU Library Discovery (Primo VE tenant)](https://apis.io/apis/nthu/nthu-library-discovery/) — NTHU Library's discovery service on Ex Libris Primo VE. Notable for what it reveals rather than what it offers: its sign-in link declares…
- [National Tsing Hua University O Auth API](https://apis.io/apis/nthu/nthu-oauth-api/) — Authorization-code flow against NTHU Academic Information System accounts.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Nthu Agentic Access](https://apis.io/agentic-access/nthu/nthu-agentic-access/)

#### JSON Schema (15)

The data models the API reads and writes.

- [AnnouncementDetail](https://apis.io/schemas/nthu/nthu-announcement/)
- [AnnouncementDetail](https://apis.io/schemas/nthu/nthu-announcement-detail/)
- [BusInfo](https://apis.io/schemas/nthu/nthu-bus/)
- [BusSchedule](https://apis.io/schemas/nthu/nthu-bus-schedule/)
- [BusStopsQueryResult](https://apis.io/schemas/nthu/nthu-bus-stops-query-result/)
- [CourseData](https://apis.io/schemas/nthu/nthu-course/)
- [CourseData](https://apis.io/schemas/nthu/nthu-course-data/)
- [Department](https://apis.io/schemas/nthu/nthu-department/)
- [DiningRestaurant](https://apis.io/schemas/nthu/nthu-dining-restaurant/)
- [EnergyElectricityInfo](https://apis.io/schemas/nthu/nthu-energy/)
- [IdentityResource](https://apis.io/schemas/nthu/nthu-identity-resource/)
- [LibraryRssItem](https://apis.io/schemas/nthu/nthu-library-rss-item/)
- [LibrarySpace](https://apis.io/schemas/nthu/nthu-library-space/)
- [LocationDetail](https://apis.io/schemas/nthu/nthu-location/)
- [TokenResponse](https://apis.io/schemas/nthu/nthu-token-response/)

#### JSON Structure (5)

Data models expressed in JSON Structure.

- [Nthu Bus Structure](https://apis.io/json-structure/nthu/nthu-bus-structure/)
- [Nthu Course Structure](https://apis.io/json-structure/nthu/nthu-course-structure/)
- [Nthu Energy Structure](https://apis.io/json-structure/nthu/nthu-energy-structure/)
- [Nthu Library Space Structure](https://apis.io/json-structure/nthu/nthu-library-space-structure/)
- [Nthu Location Structure](https://apis.io/json-structure/nthu/nthu-location-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Nthu Context](https://apis.io/jsonld/nthu/nthu-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [NTHU Data API Vocabulary](https://apis.io/vocabularies/nthu/nthu-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Nthu Getbusroutedata Example](https://apis.io/examples/nthu/nthu-getBusRouteData-example/)
- [Nthu Searchcoursesbycondition_Request Example](https://apis.io/examples/nthu/nthu-searchCoursesByCondition_request-example/)

#### Collections (9)

Postman and Open Collection request collections.

- [NTHU Data Announcements API](https://apis.io/collections/nthu/open-nthu-announcements-api/)
- [NTHU Data Announcements Buses API](https://apis.io/collections/nthu/open-nthu-buses-api/)
- [NTHU Data Announcements Courses API](https://apis.io/collections/nthu/open-nthu-courses-api/)
- [NTHU Data Announcements Departments API](https://apis.io/collections/nthu/open-nthu-departments-api/)
- [NTHU Data Announcements Dining API](https://apis.io/collections/nthu/open-nthu-dining-api/)
- [NTHU Data Announcements Energy API](https://apis.io/collections/nthu/open-nthu-energy-api/)
- [NTHU Data Announcements Libraries API](https://apis.io/collections/nthu/open-nthu-libraries-api/)
- [NTHU Data Announcements Locations API](https://apis.io/collections/nthu/open-nthu-locations-api/)
- [NTHU Data Announcements Newsletters API](https://apis.io/collections/nthu/open-nthu-newsletters-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [National Tsing Hua University — jsonschema rules](https://apis.io/rules/nthu/nthu-jsonschema-spectral-rules/)
- [National Tsing Hua University API Rules](https://apis.io/rules/nthu/nthu-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Nthu Authentication](https://apis.io/security/nthu/nthu-authentication/)
- [Nthu Domain Security](https://apis.io/security/nthu/nthu-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Nthu Scopes](https://apis.io/scopes/nthu/nthu-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Nthu Plans Pricing](https://apis.io/plans/nthu/nthu-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Nthu Rate Limits](https://apis.io/rate-limits/nthu/nthu-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Nthu Finops](https://apis.io/finops/nthu/nthu-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.nthu.edu.tw/)
- [Documentation](https://oauth.ccxp.nthu.edu.tw/v1.1/doc/)
- [API reference](https://api.nthusa.tw/docs)
- [Support](https://ccc.site.nthu.edu.tw/)
- [Terms of service](https://law.site.nthu.edu.tw/p/406-1326-197509,r6923.php)

## API Evangelist rating

**Kin Score 35.0** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 55.5 |
| Contract governance | 18.2 |
| Operational transparency | 18.4 |
| Developer ergonomics | 28.6 |
| Access clarity | 15.8 |

**Agent readiness 25.3** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 30.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nthu/](https://apis.io/providers/nthu/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for National Tsing Hua University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nthu/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
