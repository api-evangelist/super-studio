# SUPER STUDIO

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

SUPER STUDIO (株式会社SUPER STUDIO) is a Tokyo-based commerce software company founded in 2014 that builds "ecforce", an AI commerce platform used by Japanese D2C and subscription brands for storefronts, order management, subscriptions, CRM, marketing automation and BI. The platform is multi-tenant and API-integrable: ecforce exposes a versioned REST admin/customer API (v2, JSON:API shaped, token authenticated) on each merchant's own shop host, a webhook surface signalled with an x-ecf-event header, and — since August 2026 — an OAuth-protected remote MCP server under agent.ec-force.com that lets external AI tools such as Claude Code, Cursor and the ChatGPT app read ecforce order and product data and drive ecforce bi, ma and AIdp. SUPER STUDIO also publishes first-party npm packages for the ecforce AI Agent (server SDK and React chat UI) and the "albers" design system. The API reference itself sits behind HTTP Basic auth at apidoc.ec-force.com and API integration is a paid contract option.

**Areas:** Company · E-Commerce · Commerce · Subscription Commerce · Order Management · Marketing Automation · Business Intelligence · Software-as-a-Service · Artificial Intelligence · Agents · MCP · Japan

## SUPER STUDIO on APIs.io

Everything profiled for SUPER STUDIO is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/super-studio/](https://apis.io/providers/super-studio/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [ecforce API v2](https://apis.io/apis/super-studio/ecforce-api-v2/) — The ecforce platform REST API. Version 2 splits into v2/admin (administrator-scoped, mirroring the ecforce management screens) and v2/customer…
- [ecforce AI Agent API](https://apis.io/apis/super-studio/ecforce-ai-agent-api/) — The internal HTTP API behind ecforce AI, called from the first-party @super_studio/ecforce-ai-agent-server npm SDK. It issues chat session tokens, resolves…
- [ecforce AI MCP](https://apis.io/apis/super-studio/ecforce-ai-mcp/) — A remote, OAuth-protected Model Context Protocol server launched 2026-08-04 that lets external AI tools (Claude Code, Cursor, the ChatGPT app/Codex) read…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Super Studio Ecforce Webhooks](https://apis.io/asyncapis/super-studio/super-studio-ecforce-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [ecforce AI MCP](https://apis.io/servers/super-studio/ecforce-ai-mcp/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Super Studio Authentication](https://apis.io/security/super-studio/super-studio-authentication/)
- [Super Studio Domain Security](https://apis.io/security/super-studio/super-studio-domain-security/)
- [Super Studio Trust Center](https://apis.io/security/super-studio/super-studio-trust-center/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Super Studio Scopes](https://apis.io/scopes/super-studio/super-studio-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Super Studio Plans Pricing](https://apis.io/plans/super-studio/super-studio-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Super Studio Rate Limits](https://apis.io/rate-limits/super-studio/super-studio-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.super-studio.jp/)
- [Documentation](https://docs.ec-force.com/)
- [Getting started](https://ec-force.com/startguide)
- [API reference](https://apidoc.ec-force.com/apidoc/v2/admin/index.html)
- [Pricing](https://ec-force.com/product_plan)
- [Sign up](https://ec-force.com/contact/new)
- [Support](https://ec-force.com/support)
- [Blog](https://ec-force.com/blog/)
- [Compliance](https://ec-force.com/security)
- [Terms of service](https://ec-force.com/info/customer_term)
- [Privacy policy](https://www.super-studio.jp/privacy)
- [GitHub](https://github.com/super-studio)

## API Evangelist rating

**Kin Score 53.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 76.7 |
| Contract quality | 39.0 |
| Contract governance | 4.5 |
| Operational transparency | 26.3 |
| Developer ergonomics | 51.2 |
| Access clarity | 92.1 |

**Agent readiness 39.1** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 36.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/super-studio/](https://apis.io/providers/super-studio/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for SUPER STUDIO: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/super-studio/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
