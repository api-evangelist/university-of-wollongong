# University of Wollongong

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

The University of Wollongong (UOW) is a public research university in Wollongong, New South Wales, Australia, established in 1951 (ROR 00jtmb277, GRID grid.1007.6, ISNI 0000 0004 0486 528X). UOW operates no public, self-service developer portal and publishes no API specification: www.uow.edu.au carries no /api, /apis or /developer page across its 5,092-URL sitemap, and there is no llms.txt or .well-known/security.txt. What it does operate that is machine-readable is an identity surface, not a data surface — a Shibboleth SAML 2.0 Identity Provider at idp.uow.edu.au whose EntityDescriptor is served publicly and is registered in the Australian Access Federation aggregate — plus registry memberships in DataCite, Crossref and ROR that carry its own DOI prefixes. Its research and library platforms are vendor tenancies: Research Online (ro.uow.edu.au) is a Figshare instance, UOW Scholars (scholars.uow.edu.au) is a Symplectic Elements/Discovery instance, and library discovery runs on Ex Libris Primo/Alma. Two institution-hosted API gateways exist under uow.edu.au — an AWS API Gateway behind the UOW Handbook at courses.uow.edu.au/api and a MuleSoft CloudHub endpoint at api.uow.edu.au — but neither is publicly documented and neither answers an anonymous request.

**Areas:** Education · Higher Education · University · Australia · New South Wales · Public Research University · Identity Federation · Research Repository · Library · Course Catalog · Open Access · Persistent Identifiers

## University of Wollongong on APIs.io

Everything profiled for University of Wollongong is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-wollongong/](https://apis.io/providers/university-of-wollongong/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [UOW Shibboleth Identity Provider (SAML 2.0 metadata)](https://apis.io/apis/university-of-wollongong/idp-saml-metadata/) — The University of Wollongong's own SAML 2.0 Identity Provider. Its EntityDescriptor is served publicly and unauthenticated at…
- [Research Online (Figshare tenancy)](https://apis.io/apis/university-of-wollongong/research-online-figshare/) — Research Online is UOW's open access institutional repository, and since its 2025 platform migration it is a Figshare tenancy, not the bepress Digital…
- [UOW Scholars (Symplectic Elements / Discovery tenancy)](https://apis.io/apis/university-of-wollongong/uow-scholars-symplectic/) — UOW Scholars is the university's public researcher-profile portal, running on Symplectic Elements with the Symplectic Discovery front end.…
- [UOW Library Discovery (Ex Libris Primo / Alma tenancy)](https://apis.io/apis/university-of-wollongong/library-primo-alma/) — The UOW Library runs on the Ex Libris Alma library services platform with the Primo discovery layer, on the institution-specific tenant host…
- [UOW Handbook course catalog API (undocumented)](https://apis.io/apis/university-of-wollongong/course-handbook-api/) — The UOW Handbook at courses.uow.edu.au is a Next.js application served from CloudFront on UOW's own registrable domain and backed by an AWS API Gateway at…
- [DataCite membership (repository uow.figshare)](https://apis.io/apis/university-of-wollongong/datacite-membership/) — The University of Wollongong is a DataCite consortium organization, symbol UOW, provider id uow, created 2024-08-26, holding the DOI prefix 10.71747 and…
- [Crossref membership (University of Wollongong Library, member 5587)](https://apis.io/apis/university-of-wollongong/crossref-membership/) — The University of Wollongong Library is Crossref member 5587, holding the DOI prefix 10.14453 with 1,611 registered DOIs (277 current, 1,334 backfile) as of…
- [ROR registration (00jtmb277)](https://apis.io/apis/university-of-wollongong/ror-registration/) — The University of Wollongong is registered in the Research Organization Registry as https://ror.org/00jtmb277 (status active, established 1951),…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Wollongong Context](https://apis.io/jsonld/university-of-wollongong/university-of-wollongong-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Wollongong Authentication](https://apis.io/security/university-of-wollongong/university-of-wollongong-authentication/)
- [University Of Wollongong Domain Security](https://apis.io/security/university-of-wollongong/university-of-wollongong-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Wollongong Plans Pricing](https://apis.io/plans/university-of-wollongong/university-of-wollongong-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Wollongong Rate Limits](https://apis.io/rate-limits/university-of-wollongong/university-of-wollongong-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Wollongong Finops](https://apis.io/finops/university-of-wollongong/university-of-wollongong-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.uow.edu.au/)
- [Documentation](https://www.uow.edu.au/about/policy/)
- [Support](https://www.uow.edu.au/about/contacts/)
- [Blog](https://www.uow.edu.au/media/)
- [Terms of service](https://www.uow.edu.au/about/governance/copyright-and-disclaimer/)
- [Privacy policy](https://www.uow.edu.au/privacy/)
- [GitHub](https://github.com/uowits)

## API Evangelist rating

**Kin Score 26.1** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 14.3 |
| Contract governance | 18.2 |
| Operational transparency | 7.9 |
| Developer ergonomics | 28.6 |
| Access clarity | 26.3 |

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

**Regulatory alignment 32.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-wollongong/](https://apis.io/providers/university-of-wollongong/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Wollongong: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-wollongong/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
