# Chainalysis

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

Chainalysis is a blockchain analysis company providing data, software, and research to government agencies, exchanges, banks, and crypto businesses for compliance, investigation, and risk management. Core products include KYT (real-time transaction monitoring), Address Screening, the publicly hosted Sanctions API, Reactor (investigations and fund tracing), Crypto Investigations, Wallet Scan, Rapid (AI-assisted triage), VASP Risking, and Sentinel (stablecoin risk). Security-side products include Hexagate (web3 threat prevention) and Alterya (fraud prevention). Most APIs are REST-based and gated behind enterprise contracts, except the free public Sanctions Screening API.

**Areas:** Compliance · AML · Transaction Monitoring · Sanctions · Investigations · Blockchain Analytics · Risk Management · Cryptocurrency

## Chainalysis on APIs.io

Everything profiled for Chainalysis is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/chainalysis/](https://apis.io/providers/chainalysis/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Chainalysis Sanctions Screening API](https://apis.io/apis/chainalysis/sanctions-screening/) — Free public REST API that returns whether a given crypto address is identified as sanctioned by OFAC, EU, or UN sanctions authorities. No commercial licence…
- [Chainalysis KYT API](https://apis.io/apis/chainalysis/kyt-api/) — Enterprise REST API for real-time anti-money-laundering monitoring of crypto transactions - register deposits, withdrawals, and transfers, and receive risk…
- [Chainalysis Address Screening API](https://apis.io/apis/chainalysis/address-screening/) — Enterprise REST API for assessing a wallet's risk exposure - returns categorised exposure (e.g. darknet markets, sanctions, scams) and a risk score for a…
- [Chainalysis Entities API](https://apis.io/apis/chainalysis/entities-api/) — Enterprise REST API exposing Chainalysis's labelled-entity dataset - look up the entity behind a given address (exchange, mixer, sanctioned actor, scam,…
- [Chainalysis Reactor](https://apis.io/apis/chainalysis/reactor/) — Investigation product for tracing funds across blockchains - graph explorer, address clustering, and case management used by law enforcement, government,…
- [Chainalysis Crypto Investigations](https://apis.io/apis/chainalysis/crypto-investigations/) — Managed investigation service where Chainalysis analysts conduct or assist with crypto-related investigations on behalf of customers, including expert…
- [Chainalysis Rapid](https://apis.io/apis/chainalysis/rapid/) — AI-powered triage product for instant assessment of crypto addresses and transactions - surfaces key risk and entity context to speed up investigations and…
- [Chainalysis Wallet Scan](https://apis.io/apis/chainalysis/wallet-scan/) — Tool for scanning recovered seed phrases against the blockchain to identify wallets holding seizable cryptocurrency, used in law-enforcement asset-seizure…
- [Chainalysis VASP Risking](https://apis.io/apis/chainalysis/vasp-risking/) — Risk-profile product for Virtual Asset Service Providers - assesses exchanges and other VASPs against AML, sanctions, and counterparty risk criteria for use…
- [Chainalysis Sentinel](https://apis.io/apis/chainalysis/sentinel/) — Stablecoin-focused risk product that evaluates the risk profile of individual stablecoins, their issuers, and circulation patterns.
- [Hexagate (Chainalysis)](https://apis.io/apis/chainalysis/hexagate/) — Web3 security product (acquired by Chainalysis) that monitors smart contracts and on-chain activity in real time to detect and prevent exploits, governance…
- [Alterya (Chainalysis)](https://apis.io/apis/chainalysis/alterya/) — AI-powered fraud prevention product (acquired by Chainalysis) that identifies scams and fraud-victim relationships to help exchanges and payment platforms…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Chainalysis Authentication](https://apis.io/security/chainalysis/chainalysis-authentication/)
- [Chainalysis Domain Security](https://apis.io/security/chainalysis/chainalysis-domain-security/)
- [Chainalysis Trust Center](https://apis.io/security/chainalysis/chainalysis-trust-center/)
- [Chainalysis Vulnerability Disclosure](https://apis.io/security/chainalysis/chainalysis-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Chainalysis Plans Pricing](https://apis.io/plans/chainalysis/chainalysis-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Chainalysis Rate Limits](https://apis.io/rate-limits/chainalysis/chainalysis-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Chainalysis Finops](https://apis.io/finops/chainalysis/chainalysis-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.chainalysis.com/)
- [Documentation](https://developers.chainalysis.com/)
- [Sign up](https://www.chainalysis.com/request-a-demo/)
- [Support](https://support.chainalysis.com/hc/en-us)
- [Blog](https://www.chainalysis.com/blog/)
- [Security](https://www.chainalysis.com/vulnerability-disclosure-policy/)
- [Compliance](https://www.chainalysis.com/legal/)
- [Trust centre](https://trust.chainalysis.com/)
- [Terms of service](https://www.chainalysis.com/msa1023/)
- [Privacy policy](https://www.chainalysis.com/privacy-policy/)
- [GitHub](https://github.com/chainalysis)
- [Status](https://status.chainalysis.com/)

## API Evangelist rating

**Kin Score 40.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 50.0 |
| Developer ergonomics | 40.5 |
| Access clarity | 63.2 |

**Agent readiness 7.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
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
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 35.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/chainalysis/](https://apis.io/providers/chainalysis/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Chainalysis: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/chainalysis/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
