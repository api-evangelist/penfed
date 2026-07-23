# PenFed Credit Union (penfed)

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
