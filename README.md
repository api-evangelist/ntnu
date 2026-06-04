# Norwegian University of Science and Technology (ntnu)

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
