# Norwegian University of Science and Technology

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

The Norwegian University of Science and Technology (NTNU) is Norway's largest university, headquartered in Trondheim with campuses in Gjovik and Alesund. NTNU operates no consolidated institutional developer portal and publishes no OpenAPI, AsyncAPI or other machine-readable API contract of its own. Its one openly callable, institution-operated surface is the OAI-PMH interface of NTNU Open Access Journals at www.ntnu.no/ojs, which answers Identify, ListMetadataFormats and ListSets over sixteen NTNU-published journals. NTNU also runs an institutional API gateway at api.ntnu.no, but every path on it is behind Feide OAuth and no public documentation, contract or scope list is served without an institutional account. Everything else that looks programmable under NTNU's name is operated by somebody else and entered here as a tenant relationship, not as NTNU engineering: research data in the NTNU collection of DataverseNO (run by UiT The Arctic University of Norway on Dataverse software), research information in Cristin and the national research archive NVA (both run by Sikt), timetables in TP on educloud.no, identity in the Feide federation where NTNU exists as the scope ntnu.no on Sikt's national IdP rather than as its own eduGAIN entity, and teaching in a hosted Canvas tenant. This repo previously carried 35 OpenAPI files and 87 derived artifacts that were splits of the generic Dataverse 6.6 product contract; they were the vendor's, not NTNU's, and have been removed.

**Areas:** Education · Higher Education · University · Research · Research Data · Open Access · Open Data · Identity · Course Catalog · Norway · Scandinavia · Identity Federation

## Norwegian University of Science and Technology on APIs.io

Everything profiled for Norwegian University of Science and Technology is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ntnu/](https://apis.io/providers/ntnu/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [NTNU Open Access Journals OAI-PMH](https://apis.io/apis/ntnu/ojs-oai/) — NTNU runs its own Open Journal Systems installation, "NTNU Open Access Journals", on its own registrable domain at www.ntnu.no/ojs, publishing sixteen…
- [NTNU API Gateway (api.ntnu.no)](https://apis.io/apis/ntnu/api-ntnu/) — api.ntnu.no is an NTNU-operated API gateway serving internal and partner integrations. It is live and institution-run — responses carry NTNU's own…
- [Cristin Research Information API (NTNU institution 194)](https://apis.io/apis/ntnu/cristin/) — Cristin is Norway's national Current Research Information System, operated by Sikt (the Norwegian Agency for Shared Services in Education and Research) on…
- [NVA National Research Archive (NTNU Open successor)](https://apis.io/apis/ntnu/nva/) — Nasjonalt vitenarkiv (NVA) is the Sikt-operated national open research archive that absorbed NTNU's institutional repository — ntnuopen.ntnu.no now…
- [DataverseNO — NTNU Research Data Collection](https://apis.io/apis/ntnu/dataverseno/) — NTNU's research data is deposited into the "NTNU – Norwegian University of Science and Technology" collection (alias "ntnu") of DataverseNO, the Norwegian…
- [TP Timetable Web Service (NTNU instance)](https://apis.io/apis/ntnu/tp/) — TP (Timeplan) is the timetable, room-booking and course-activity system NTNU uses, hosted on the shared educloud.no platform at tp.educloud.no/ntnu. The…
- [Feide / Dataporten Identity Federation (NTNU membership)](https://apis.io/apis/ntnu/feide/) — NTNU authenticates through Feide, the Norwegian national identity federation operated by Sikt, with Dataporten providing OAuth2 / OpenID Connect and SAML…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Vocabulary (1)

The provider's domain terms, defined.

- [NTNU DataverseNO Research Data Vocabulary](https://apis.io/vocabularies/ntnu/ntnu-vocabulary/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Ntnu Domain Security](https://apis.io/security/ntnu/ntnu-domain-security/)
- [Ntnu Vulnerability Disclosure](https://apis.io/security/ntnu/ntnu-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ntnu Plans Pricing](https://apis.io/plans/ntnu/ntnu-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ntnu Rate Limits](https://apis.io/rate-limits/ntnu/ntnu-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ntnu Finops](https://apis.io/finops/ntnu/ntnu-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ntnu.edu/)
- [Blog](https://nyheter.ntnu.no/en/feed/)
- [GitHub](https://github.com/EECS-NTNU)

## API Evangelist rating

**Kin Score 20.1** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 82.1 |
| Contract quality | 4.4 |
| Contract governance | 18.2 |
| Operational transparency | 7.9 |
| Developer ergonomics | 23.8 |
| Access clarity | 5.3 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 30.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ntnu/](https://apis.io/providers/ntnu/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Norwegian University of Science and Technology: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ntnu/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
