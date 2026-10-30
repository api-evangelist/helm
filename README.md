# Helm

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

Package manager for Kubernetes that helps you define, install, and upgrade complex Kubernetes applications using charts. Helm uses a packaging format called charts, which are collections of files that describe a related set of Kubernetes resources. A chart repository is an HTTP server that houses an index.yaml file and packaged chart archives.

**Areas:** Helm · Charts · Cloud-Native · Container Orchestration · DevOps · Kubernetes · Package Manager

## Helm on APIs.io

Everything profiled for Helm is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/helm/](https://apis.io/providers/helm/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Helm Chart.yaml Schema](https://apis.io/apis/helm/chart-yaml-schema/) — JSON Schema defining the structure and validation rules for Chart.yaml, the metadata file required in every Helm chart. Describes chart name, version,…
- [Helm Values YAML Schema](https://apis.io/apis/helm/values-yaml-schema/) — JSON Schema describing common conventional patterns for values.yaml files in Helm charts. Values.yaml provides default configuration values including…
- [Helm Repository Index Schema](https://apis.io/apis/helm/repository-index-schema/) — JSON Schema for the index.yaml file served by Helm chart repositories. The index is the primary discovery mechanism listing all available charts and…
- [Helm JSON-LD Context](https://apis.io/apis/helm/json-ld-context/) — JSON-LD context document mapping Helm concepts to linked data vocabularies including Schema.org, Dublin Core, SPDX, FOAF, and W3C PROV. Enables semantic…
- [Helm Go SDK](https://apis.io/apis/helm/go-sdk/) — The Helm Go SDK provides Go packages for programmatically performing Helm actions such as install, upgrade, list, and rollback without using the CLI. The…
- [Helm Plugins](https://apis.io/apis/helm/plugins/) — The Helm Plugins API defines the interface for extending the Helm CLI with additional subcommands. Plugins live in a single directory with a plugin.yaml…
- [Helm Chart Template API](https://apis.io/apis/helm/chart-template-api/) — The Helm Chart Template API defines the Go template language extensions, built-in objects, and Sprig function library available for authoring Helm chart…
- [Helm ChartMuseum API](https://apis.io/apis/helm/helm-chartmuseum-api/) — Extended API endpoints provided by ChartMuseum and compatible chart repository servers for JSON-based chart management.
- [Helm Charts API](https://apis.io/apis/helm/helm-charts-api/) — Chart package download endpoints for retrieving packaged chart archives and provenance files for signature verification.
- [Helm Repository API](https://apis.io/apis/helm/helm-repository-api/) — Standard Helm chart repository endpoints for index and chart download. These endpoints are required for any Helm-compatible chart repository.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Helm Agentic Access](https://apis.io/agentic-access/helm/helm-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Helm Chart.yaml](https://apis.io/schemas/helm/helm-chart-yaml/)
- [Helm Plugin Descriptor](https://apis.io/schemas/helm/helm-plugin/)
- [Helm Chart Repository Index](https://apis.io/schemas/helm/helm-repository-index/)
- [Helm Values YAML](https://apis.io/schemas/helm/helm-values-yaml/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Helm Context](https://apis.io/jsonld/helm/helm-context/)

#### Collections (4)

Postman and Open Collection request collections.

- [Helm Chart Repository API](https://apis.io/collections/helm/open-helm-chart-repository/)
- [Helm Chart Repository ChartMuseum API](https://apis.io/collections/helm/open-helm-chartmuseum-api/)
- [Helm Chart Repository ChartMuseum Charts API](https://apis.io/collections/helm/open-helm-charts-api/)
- [Helm Chart ChartMuseum Repository API](https://apis.io/collections/helm/open-helm-repository-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Helm — jsonschema rules](https://apis.io/rules/helm/helm-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Helm Domain Security](https://apis.io/security/helm/helm-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Helm Plans Pricing](https://apis.io/plans/helm/helm-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Helm Rate Limits](https://apis.io/rate-limits/helm/helm-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Helm Finops](https://apis.io/finops/helm/helm-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://helm.sh/)
- [Documentation](https://helm.sh/docs/)
- [Getting started](https://helm.sh/docs/intro/quickstart/)
- [Changelog](https://helm.sh/docs/changelog/)
- [Blog](https://helm.sh/blog/)
- [Security](https://helm.sh/community/SECURITY)
- [GitHub](https://github.com/helm)

## API Evangelist rating

**Kin Score 39.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 54.0 |
| Contract governance | 9.8 |
| Operational transparency | 36.8 |
| Developer ergonomics | 35.7 |
| Access clarity | 5.3 |

**Agent readiness 19.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
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
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 10.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/helm/](https://apis.io/providers/helm/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Helm: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/helm/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
