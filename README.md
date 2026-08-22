# Cortex (cortex-app)

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

Cortex is an Internal Developer Portal and service catalog used by platform and engineering teams to inventory services, libraries, domains, teams, on-call rotations, and resources; measure them against Scorecards (production readiness, security, SLO compliance, cost, AI usage); and drive developer-facing experiences through Initiatives, Workflows, and Scaffolder templates. Cortex pulls signals from GitHub, GitLab, AWS, Azure, GCP, Datadog, PagerDuty, Slack, Jira, Snyk, SonarQube, and many other integrations, and exposes a REST API and an MCP server so that humans and AI agents can query the catalog, scorecards, dependencies, and entity descriptors.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cortex-app/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cortex-app/refs/heads/main/apis.yml)

## Tags

- Internal Developer Portal
- Service Catalog
- Scorecards
- Platform Engineering
- Developer Experience
- SRE

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Cortex Catalog API

REST endpoints to list and retrieve catalog entities (services, libraries, domains, resources, teams) and their descriptors. Supports filtering by tag, type, group, and ownership; returns the canonical entity descriptor and its OpenAPI definition where available.

- **Human URL:** [https://docs.cortex.io/](https://docs.cortex.io/)
- **Base URL:** `https://api.getcortexapp.com`

#### Tags

- REST API
- Catalog
- Entities

#### Properties

- [Documentation](https://docs.cortex.io/)
- [Postman Collection](collections/cortex-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cortex-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cortex Scorecards API

REST endpoints to list Scorecards, fetch scores for a Scorecard across entities, and surface recommended next steps for improving an entity's score. Underpins production-readiness, security, and cost programs.

- **Human URL:** [https://docs.cortex.io/](https://docs.cortex.io/)
- **Base URL:** `https://api.getcortexapp.com`

#### Tags

- REST API
- Scorecards
- Quality

#### Properties

- [Documentation](https://docs.cortex.io/)
- [Postman Collection](collections/cortex-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cortex-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cortex Dependencies API

REST endpoints to list and inspect entity-to-entity dependencies (caller and callee) and the relationships used to build the service graph.

- **Human URL:** [https://docs.cortex.io/](https://docs.cortex.io/)
- **Base URL:** `https://api.getcortexapp.com`

#### Tags

- REST API
- Dependencies
- Graph

#### Properties

- [Documentation](https://docs.cortex.io/)
- [Postman Collection](collections/cortex-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cortex-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cortex Initiatives API

REST endpoints to list and retrieve Initiatives - time-boxed cross-team programs that track Scorecard progress, owners, and deadlines.

- **Human URL:** [https://docs.cortex.io/](https://docs.cortex.io/)
- **Base URL:** `https://api.getcortexapp.com`

#### Tags

- REST API
- Initiatives
- Programs

#### Properties

- [Documentation](https://docs.cortex.io/)
- [Postman Collection](collections/cortex-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cortex-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cortex Workflow Runs API

REST endpoints for managing and querying Workflow runs, used to drive developer self-service actions and scaffolding from the Cortex IDP.

- **Human URL:** [https://docs.cortex.io/](https://docs.cortex.io/)
- **Base URL:** `https://api.getcortexapp.com`

#### Tags

- REST API
- Workflows
- Self-Service

#### Properties

- [Documentation](https://docs.cortex.io/)
- [Postman Collection](collections/cortex-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cortex-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cortex MCP Server

Model Context Protocol server exposing Cortex catalog, scorecards, dependencies, and on-call data to AI agents and copilots through MCP tools and resources.

- **Human URL:** [https://docs.cortex.io/](https://docs.cortex.io/)
- **Base URL:** `https://docs.cortex.io/`

#### Tags

- MCP
- AI
- Agents

#### Properties

- [Documentation](https://docs.cortex.io/)
- [Postman Collection](collections/cortex-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cortex-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/cortexapp)
- [Website](https://www.cortex.io/)
- [Documentation](https://docs.cortex.io/)
- [Git Hub](https://github.com/cortexapps)
- [Plans](plans/cortex-app-plans-pricing.yml)
- [Rate Limits](rate-limits/cortex-app-rate-limits.yml)
- [Fin Ops](finops/cortex-app-finops.yml)
- [Integrations](https://www.cortex.io/integrations)
- [L L Ms Txt](https://docs.cortex.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
