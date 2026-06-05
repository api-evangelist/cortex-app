# Cortex (cortex-app)

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
