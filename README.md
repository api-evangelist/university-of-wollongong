# University of Wollongong (university-of-wollongong)

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
