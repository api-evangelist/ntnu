# Norwegian University of Science and Technology (ntnu)

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

The Norwegian University of Science and Technology (NTNU) is Norway's largest university, headquartered in Trondheim with campuses in Gjoverik and Alesund, and ranked #264 in the QS World University Rankings 2025. NTNU does not run a single consolidated institutional developer portal; its public, machine-readable footprint is delivered mostly through national shared research and education infrastructure operated by Sikt (the Norwegian Agency for Shared Services in Education and Research). This repository catalogs that footprint as an [APIs.json](https://apisjson.org) provider profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ntnu/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ntnu-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Norway, Scandinavia

## APIs

- **Cristin Research Information API** — National CRIS exposing NTNU research output, persons and projects (NTNU is Cristin institution 194). Docs: https://api.cristin.no/v2/doc/index.html
- **NVA Nasjonalt Vitenarkiv API** — Sikt national research archive now hosting the migrated NTNU Open institutional repository. Docs: https://nva.sikt.no/
- **DataverseNO Research Data API** — National Dataverse research-data repository with NTNU dataverse and native REST API. Docs: https://guides.dataverse.org/en/latest/api/
- **TP Timetable Web Service** — NTNU timetable/room/course web service at tp.educloud.no/ntnu/ws/ (access controlled, returns HTTP 401). Docs: https://tp.educloud.no/ntnu/timeplan/
- **Feide / Dataporten Identity** — National Feide/Dataporten OpenID Connect, OAuth2 and SAML identity APIs used by NTNU. Docs: https://docs.feide.no/

## Plans, Rate Limits & FinOps

- Plans & Pricing: [plans/ntnu-plans-pricing.yml](plans/ntnu-plans-pricing.yml)
- Rate Limits: [rate-limits/ntnu-rate-limits.yml](rate-limits/ntnu-rate-limits.yml)
- FinOps: [finops/ntnu-finops.yml](finops/ntnu-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ntnu.edu/
- GitHub: https://github.com/EECS-NTNU
- LinkedIn: https://www.linkedin.com/school/ntnu/
- Developer Portal / Authentication: https://docs.feide.no/
- Review: [review.yml](review.yml)

## Notes

- No single official NTNU institutional developer portal or GitHub org was found; the public API footprint is delivered through national Sikt-operated services (Cristin, NVA, Feide/Dataporten) and the shared DataverseNO and TP platforms.
- The legacy NTNU Open OAI-PMH endpoint (ntnuopen.ntnu.no) now redirects into the Sikt NVA single-page application, indicating the institutional repository has been migrated to NVA.
- The TP timetable web service exists but is access controlled (HTTP 401); programmatic use requires institutional authorization. No endpoints were fabricated — gated and migrated services are flagged honestly.
- The LinkedIn school page returns HTTP 999 to automated probes (LinkedIn bot-blocking), which is not evidence of absence.

## Maintainers

- Kin Lane — kin@apievangelist.com
