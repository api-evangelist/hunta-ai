# hunta-ai

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

Hunta provides an Attestable Memory API for AI agents, enabling per‑tenant isolated agent memory over the MCP (Memory Control Protocol). The Gather service records everything an agent takes in, while the Instinct service ensures data that must never be forgotten is retained. The platform offers a free tier, supports bi‑temporal records, and provides a secure, signed isolation attestation for each memory. Documentation, API reference, pricing, and a quick start guide are available on the website. Hunta’s API is designed for developers building AI agents that need provable, auditable memory.

**Areas:** Company · AI · Memory · API · MCP · Attestable

## hunta-ai on APIs.io

Everything profiled for hunta-ai is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hunta-ai/](https://apis.io/providers/hunta-ai/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [Hunta API](https://apis.io/apis/hunta-ai/hunta-api/) — REST API for Hunta's Attestable Memory service, hosted at mcp.hunta.ai. Uses Bearer JWT authentication; the tenant is bound to the token.
- [hunta-ai Admin API](https://apis.io/apis/hunta-ai/hunta-ai-admin-api/) — The Admin API from hunta-ai — 7 operation(s) for admin.
- [hunta-ai Candidates API](https://apis.io/apis/hunta-ai/hunta-ai-candidates-api/) — The Candidates API from hunta-ai — 3 operation(s) for candidates.
- [hunta-ai Errata API](https://apis.io/apis/hunta-ai/hunta-ai-errata-api/) — The Errata API from hunta-ai — 2 operation(s) for errata.
- [hunta-ai Export API](https://apis.io/apis/hunta-ai/hunta-ai-export-api/) — The Export API from hunta-ai — 1 operation(s) for export.
- [hunta-ai Facts API](https://apis.io/apis/hunta-ai/hunta-ai-facts-api/) — The Facts API from hunta-ai — 5 operation(s) for facts.
- [hunta-ai Memories API](https://apis.io/apis/hunta-ai/hunta-ai-memories-api/) — The Memories API from hunta-ai — 4 operation(s) for memories.
- [hunta-ai Metrics API](https://apis.io/apis/hunta-ai/hunta-ai-metrics-api/) — The Metrics API from hunta-ai — 1 operation(s) for metrics.
- [hunta-ai Reckon API](https://apis.io/apis/hunta-ai/hunta-ai-reckon-api/) — The Reckon API from hunta-ai — 4 operation(s) for reckon.
- [hunta-ai Reconcile API](https://apis.io/apis/hunta-ai/hunta-ai-reconcile-api/) — The Reconcile API from hunta-ai — 1 operation(s) for reconcile.
- [hunta-ai Whoami API](https://apis.io/apis/hunta-ai/hunta-ai-whoami-api/) — The Whoami API from hunta-ai — 1 operation(s) for whoami.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Hunta Ai Agentic Access](https://apis.io/agentic-access/hunta-ai/hunta-ai-agentic-access/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Hunta Ai Openapi Overlay](https://apis.io/overlays/hunta-ai/hunta-ai-openapi-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [hunta-ai API Rules](https://apis.io/rules/hunta-ai/hunta-ai-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Hunta Ai Authentication](https://apis.io/security/hunta-ai/hunta-ai-authentication/)
- [Hunta Ai Domain Security](https://apis.io/security/hunta-ai/hunta-ai-domain-security/)
- [Hunta Ai Trust Center](https://apis.io/security/hunta-ai/hunta-ai-trust-center/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Hunta Ai Scopes](https://apis.io/scopes/hunta-ai/hunta-ai-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Hunta Ai Plans Pricing](https://apis.io/plans/hunta-ai/hunta-ai-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Hunta Ai Rate Limits](https://apis.io/rate-limits/hunta-ai/hunta-ai-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://hunta.ai/)
- [Documentation](https://docs.hunta.ai/)
- [Getting started](https://hunta.ai/get-started)
- [API reference](https://docs.hunta.ai/)
- [Pricing](https://hunta.ai/pricing)
- [Support](https://hunta.ai/connect)
- [Blog](https://hunta.ai/blog)
- [Security](https://hunta.ai/security)
- [Compliance](https://hunta.ai/trust)
- [Terms of service](https://hunta.ai/legal/terms)
- [Privacy policy](https://hunta.ai/legal/privacy)
- [GitHub](https://github.com/hunta-ai)

## API Evangelist rating

**Kin Score 59.9** — strong · rubric 0.25.0 · scored 2026-10-30

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 41.5 |
| Contract governance | 57.3 |
| Operational transparency | 15.8 |
| Developer ergonomics | 77.9 |
| Access clarity | 75.8 |

**Agent readiness 50.9** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 36.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hunta-ai/](https://apis.io/providers/hunta-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for hunta-ai: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hunta-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
