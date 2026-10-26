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

Education, Higher Education, University, Research, Research Data, Open Access, Open Data, Identity, Course Catalog, Norway, Scandinavia

## APIs

Every entry carries an operator. `institution` means NTNU runs the thing the entry describes;
`tenant` means NTNU holds an account or collection on a platform somebody else operates, so the
data is NTNU's and the contract is not.

- **NTNU Open Access Journals OAI-PMH** (`institution`) — NTNU's own Open Journal Systems
  installation at www.ntnu.no/ojs, serving sixteen NTNU-published journals over an open,
  unauthenticated OAI-PMH 2.0 interface. Identify, ListMetadataFormats (oai_dc, marcxml, oai_marc,
  rfc1807) and ListSets all return 200. The only openly callable API in this profile that NTNU
  itself operates. Base: https://www.ntnu.no/ojs/index.php/index/oai
- **NTNU API Gateway** (`institution`) — api.ntnu.no is live and NTNU-run, but every path
  redirects to Feide OAuth; /docs, /openapi.json and /status all serve the account-chooser page.
  No public contract, scope list or registration. Docs: https://docs.feide.no/
- **Cristin Research Information API** (`tenant`) — Sikt-operated national CRIS; NTNU is
  institution 194. Docs: https://api.cristin.no/v2/doc/index.html
- **NVA Nasjonalt Vitenarkiv API** (`tenant`) — Sikt national research archive that absorbed NTNU
  Open; api.nva.unit.no returns 403 unauthenticated. Docs: https://nva.sikt.no/
- **DataverseNO — NTNU Research Data Collection** (`tenant`) — the "ntnu" collection (id 5622,
  contact research-data@ntnu.no) inside DataverseNO, run by UiT The Arctic University of Norway.
  Docs: https://site.uit.no/dataverseno/
- **TP Timetable Web Service** (`tenant`) — NTNU's instance on the shared educloud.no platform;
  /ntnu/ws/ returns HTTP 403 unauthenticated. Docs: https://tp.educloud.no/ntnu/timeplan/
- **Feide / Dataporten Identity Federation** (`tenant`) — NTNU has no eduGAIN entity of its own; it
  appears as the shibmd:Scope "ntnu.no" on Sikt's idp.feide.no. Docs: https://docs.feide.no/

## Standards Conformance

- [conformance/ntnu-conformance.yml](conformance/ntnu-conformance.yml) — education-regime domain
  standards, established by live probe. One institution-operated hit: **oai-pmh**. SAML and
  Shibboleth are met through Feide and are recorded as tenant conformance.

## Plans, Rate Limits & FinOps

- Plans & Pricing: [plans/ntnu-plans-pricing.yml](plans/ntnu-plans-pricing.yml)
- Rate Limits: [rate-limits/ntnu-rate-limits.yml](rate-limits/ntnu-rate-limits.yml)
- FinOps: [finops/ntnu-finops.yml](finops/ntnu-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-30

## Common Properties

- Website: https://www.ntnu.edu/
- GitHub Organization: https://github.com/EECS-NTNU
- LinkedIn: https://www.linkedin.com/school/ntnu/
- Authentication: https://docs.feide.no/
- security.txt: https://www.ntnu.no/.well-known/security.txt
- Identity Federation: https://metadata.feide.no/feide-edugain-metadata.xml
- Open Data: https://data.ntnu.no/
- Research Repository: https://dataverse.no/dataverse/ntnu · https://nva.sikt.no/
- Course Catalog: https://www.ntnu.no/studier/emner
- Research Computing: https://www.hpc.ntnu.no/
- AI Policy: https://i.ntnu.no/wiki/-/wiki/English/Use+of+ICT+tools+with+generative+artificial+intelligence+at+NTNU+-+policy
- AI Tooling: https://i.ntnu.no/en/ki-for-ansatte
- Review: [review.yml](review.yml)

## Notes

- **Vendor contracts removed 2026-08-30.** This repo previously held 35 OpenAPI files
  (`ntnu-*-api-openapi.yml`) plus 87 artifacts derived from them — JSON Schema, JSON Structure,
  examples, Spectral rules, vocabulary, JSON-LD, Postman/OpenCollection collections and an
  agentic-access map. All 35 were per-tag splits of one source, `openapi/_original/ntnu-dataverseno.yaml`,
  whose `info.title` is "Dataverse API" and whose `servers[]` is `https://dataverse.no/api`. That is
  the generic Dataverse 6.6 product contract, shipped by six to eight other institutions in this
  catalog and served by DataverseNO (UiT), not by NTNU. The `apis.yml` entries built on it also
  carried a wrong `baseURL` of `https://api.cristin.no/v2/` — a second, unrelated service. The
  relationship is preserved as a single `tenant` entry; the vendor's contract is not.
- NTNU publishes no API contract of its own — no OpenAPI, AsyncAPI, GraphQL schema or llms.txt on
  any NTNU host (www.ntnu.no/llms.txt 404, developer.ntnu.no does not resolve).
- The one previously uncatalogued institution-operated surface found in this pass is the OAI-PMH
  interface of NTNU Open Access Journals at www.ntnu.no/ojs.
- data.ntnu.no resolves and returns a one-line page ("Adresse for publisering av åpne data")
  directing readers to the national portal data.norge.no — NTNU's open data is published there.
- The legacy NTNU Open OAI-PMH endpoint (ntnuopen.ntnu.no) now redirects into the Sikt NVA
  single-page application; the institutional repository has been migrated to NVA.
- github.com/NTNU is a personal user account with one repository, last updated 2015 — it is not an
  institutional organization and is not credited here. github.com/EECS-NTNU is a departmental org.
- i.ntnu.no returns HTTP 200 for any path with a generic "Kunnskapsbasen" title; the AI policy and
  AI tooling pointers were confirmed against a deliberately bogus control URL (17,420 and 11,849
  characters of body text versus 1,615 for the control).
- The LinkedIn school page returns HTTP 999 to automated probes (LinkedIn bot-blocking), which
  grades live, not dead.

## Maintainers

- Kin Lane — kin@apievangelist.com
