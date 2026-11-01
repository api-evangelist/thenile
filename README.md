# Nile

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

Nile is a serverless PostgreSQL platform re-engineered for multi-tenant B2B applications, offering virtual tenant databases, tenant isolation, vector embeddings, and built-in user and tenant authentication (Nile Auth). Its control-plane REST API manages workspaces, databases, credentials, regions and billing, a database API manages tenants, users and OIDC providers, and a regional auth API powers sign-in, sessions and tenant membership.

**Areas:** Company · Database · PostgreSQL · Serverless · Multi-Tenant · Authentication · B2B SaaS

## Nile on APIs.io

Everything profiled for Nile is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/thenile/](https://apis.io/providers/thenile/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Nile Auth API](https://apis.io/apis/thenile/thenile-auth-api/) — The auth API from Nile — 10 operation(s) for auth.
- [Nile Authentication API](https://apis.io/apis/thenile/thenile-authentication-api/) — The authentication API from Nile — 18 operation(s) for authentication.
- [Nile Compute API](https://apis.io/apis/thenile/thenile-compute-api/) — The compute API from Nile — 2 operation(s) for compute.
- [Nile Credentials API](https://apis.io/apis/thenile/thenile-credentials-api/) — The credentials API from Nile — 3 operation(s) for credentials.
- [Nile Databases API](https://apis.io/apis/thenile/thenile-databases-api/) — The Databases API from Nile — 18 operation(s) for databases.
- [Nile Developers API](https://apis.io/apis/thenile/thenile-developers-api/) — The developers API from Nile — 6 operation(s) for developers.
- [Nile Internal API](https://apis.io/apis/thenile/thenile-internal-api/) — The Internal API from Nile — 2 operation(s) for internal.
- [Nile Tenants API](https://apis.io/apis/thenile/thenile-tenants-api/) — The tenants API from Nile — 7 operation(s) for tenants.
- [Nile Users API](https://apis.io/apis/thenile/thenile-users-api/) — The users API from Nile — 27 operation(s) for users.
- [Nile Workspaces API](https://apis.io/apis/thenile/thenile-workspaces-api/) — The Workspaces API from Nile — 17 operation(s) for workspaces.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Nile MCP Server](https://apis.io/servers/thenile/nile-mcp-server/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Thenile Agentic Access](https://apis.io/agentic-access/thenile/thenile-agentic-access/)

#### JSON Schema (17)

The data models the API reads and writes.

- [APIError](https://apis.io/schemas/thenile/thenile-apierror/)
- [CreateBasicUserRequest](https://apis.io/schemas/thenile/thenile-create-basic-user-request/)
- [CreateDatabaseRequest](https://apis.io/schemas/thenile/thenile-create-database-request/)
- [DedicatedComputeInstance](https://apis.io/schemas/thenile/thenile-dedicated-compute-instance/)
- [GetDatabaseResponse](https://apis.io/schemas/thenile/thenile-get-database-response/)
- [LogicalDatabase](https://apis.io/schemas/thenile/thenile-logical-database/)
- [MfaDisableRequest](https://apis.io/schemas/thenile/thenile-mfa-disable-request/)
- [MfaSetupResponse](https://apis.io/schemas/thenile/thenile-mfa-setup-response/)
- [MfaVerifyRequest](https://apis.io/schemas/thenile/thenile-mfa-verify-request/)
- [MfaVerifyResponse](https://apis.io/schemas/thenile/thenile-mfa-verify-response/)
- [OIDCProvider](https://apis.io/schemas/thenile/thenile-oidcprovider/)
- [OIDCRelyingParty](https://apis.io/schemas/thenile/thenile-oidcrelying-party/)
- [TenantSSORegistration](https://apis.io/schemas/thenile/thenile-tenant-ssoregistration/)
- [TenantUser](https://apis.io/schemas/thenile/thenile-tenant-user/)
- [UnauthenticatedProvisionDatabaseResponse](https://apis.io/schemas/thenile/thenile-unauthenticated-provision-database-response/)
- [User](https://apis.io/schemas/thenile/thenile-user/)
- [WorkspaceUsageResponse](https://apis.io/schemas/thenile/thenile-workspace-usage-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Thenile Context](https://apis.io/jsonld/thenile/thenile-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Nile API Rules](https://apis.io/rules/thenile/thenile-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Thenile Authentication](https://apis.io/security/thenile/thenile-authentication/)
- [Thenile Domain Security](https://apis.io/security/thenile/thenile-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Thenile Plans Pricing](https://apis.io/plans/thenile/thenile-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Thenile Rate Limits](https://apis.io/rate-limits/thenile/thenile-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.thenile.dev)
- [Documentation](https://www.thenile.dev/docs)
- [Getting started](https://www.thenile.dev/docs/getting-started)
- [API reference](https://www.thenile.dev/docs/api-reference/post-oauth2token)
- [Pricing](https://www.thenile.dev/pricing)
- [Sign up](https://console.thenile.dev)
- [Blog](https://www.thenile.dev/blog)
- [Terms of service](https://www.thenile.dev/terms-of-service)
- [Privacy policy](https://www.thenile.dev/privacy-policy)
- [GitHub](https://github.com/niledatabase)

## API Evangelist rating

**Kin Score 54.5** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 76.7 |
| Contract quality | 63.0 |
| Contract governance | 22.0 |
| Operational transparency | 5.3 |
| Developer ergonomics | 58.9 |
| Access clarity | 76.3 |

**Agent readiness 30.6** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | — |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/thenile/](https://apis.io/providers/thenile/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Nile: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/thenile/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
