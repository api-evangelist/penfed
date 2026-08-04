# PenFed Credit Union (penfed)

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

PenFed Credit Union (Pentagon Federal Credit Union), founded in 1935 and headquartered in McLean, Virginia, is a federally chartered, NCUA-regulated credit union and one of the largest in the United States, with roughly 2.9 million members. It is a not-for-profit, member-owned financial cooperative that began serving the U.S. military and defense community and now offers open membership across mortgages, auto loans, credit cards, personal loans, and deposit accounts.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/penfed/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/penfed/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Credit Union
- United States
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

PenFed does not publish a first-party public developer portal or a documented public API program. Probes of the common developer hosts (`developer.penfed.org`, `developers.penfed.org`, `apis.penfed.org`, `sandbox.penfed.org`, `openbanking.penfed.org`) return NXDOMAIN. A host at `api.penfed.org` resolves to an AWS EC2 address but serves no public, documented HTTP API — consistent with a private mobile/web application backend rather than a developer-facing product.

Consistent with the posture of most U.S. credit unions, consumer-permissioned account data is reached through third-party data aggregators (e.g. Plaid, MX, Finicity, Akoya) rather than a directly documented, first-party API. No first-party Financial Data Exchange (FDX) data-access API and no published CFPB Section 1033 developer program were found for PenFed as of the review date. This is an identity-only record with an honest "no public API" note.

## Common Properties

- [Website](https://www.penfed.org/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
