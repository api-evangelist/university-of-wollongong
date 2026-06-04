# University of Wollongong (university-of-wollongong)

The University of Wollongong (UOW) is a public research university in Wollongong, New South Wales, Australia, ranked #167 in the QS World University Rankings 2025. UOW does not run a public, self-service developer portal. Its confirmed machine-readable footprint sits on third-party platforms — the Research Online institutional repository (bepress Digital Commons, with an OAI-PMH interface) and the UOW Library on Ex Libris Alma/Primo (REST APIs via the Ex Libris Developer Network) — plus a small public GitHub org maintained by UOW IT Services.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-wollongong/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-wollongong-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Australia, Research Repository, Library, Open Access

## APIs

- **Research Online OAI-PMH** — OAI-PMH metadata harvesting for UOW's open access repository on bepress Digital Commons. Base URL: `https://ro.uow.edu.au/do/oai/`. Docs: https://v2.sherpa.ac.uk/id/repository/276
- **UOW Library Discovery (Ex Libris Primo/Alma)** — Primo discovery + Alma platform REST APIs (key-gated, documented on the Ex Libris Developer Network). Instance: https://uow.primo.exlibrisgroup.com/ — Docs: https://developers.exlibrisgroup.com/primo/apis/

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-wollongong-plans-pricing.yml](plans/university-of-wollongong-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-wollongong-rate-limits.yml](rate-limits/university-of-wollongong-rate-limits.yml)
- FinOps: [finops/university-of-wollongong-finops.yml](finops/university-of-wollongong-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uow.edu.au/
- GitHub: https://github.com/uowits
- LinkedIn: https://au.linkedin.com/school/university-of-wollongong/
- Review: [review.yml](review.yml)

## Notes

UOW exposes no public, self-documented API or developer portal. The APIs cataloged here are third-party platforms the university uses. The Research Online OAI-PMH endpoint is documented by Sherpa (repository 276) but returns a bot challenge (HTTP 202) to automated clients, so a valid Identify response could not be confirmed in this review. The Ex Libris Primo/Alma REST APIs generally require an institution-issued API key. No endpoints were fabricated; see review.yml for probed statuses.

## Maintainers

- Kin Lane — kin@apievangelist.com
