# Apache Helix (apache-helix)

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

Apache Helix is a generic cluster management framework for partitioned and replicated distributed resources. It automates partition management, replication, fault tolerance, and cluster expansion for distributed systems, providing a REST API for cluster administration and a Java API for participant, spectator, and controller roles.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-helix/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-helix/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Apache
- Cluster Management
- Distributed Systems
- Open Source
- Partitioning
- Replication

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Apache Helix REST API

REST API for managing Apache Helix clusters, instances, resources, and partition state assignments, including ideal state queries and external view inspection.

- **Human URL:** [https://helix.apache.org/0.9.9-docs/tutorial_admin.html](https://helix.apache.org/0.9.9-docs/tutorial_admin.html)
- **Base URL:** `http://localhost:9100`

#### Tags

- Cluster Management
- Instances
- Partitions
- REST
- Resources

#### Properties

- [Documentation](https://helix.apache.org/0.9.9-docs/tutorial_admin.html)
- [OpenAPI](openapi/apache-helix-rest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-helix-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-helix-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/helix-rest-cluster-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/apache-helix-rest-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Apache Helix Java API

Java API for implementing Helix participant, spectator, and controller roles, with APIs for resource management, task execution, and state machine definitions.

- **Human URL:** [https://helix.apache.org/0.9.9-docs/tutorial_participant.html](https://helix.apache.org/0.9.9-docs/tutorial_participant.html)

#### Tags

- Java
- SDK
- State Machine

#### Properties

- [Documentation](https://helix.apache.org/0.9.9-docs/tutorial_participant.html)
- [SDK](https://search.maven.org/artifact/org.apache.helix/helix-core)
- [Postman Collection](collections/apache-helix-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-helix-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Documentation](https://helix.apache.org/)
- [Getting Started](https://helix.apache.org/0.9.9-docs/Quickstart.html)
- [GitHub Organization](https://github.com/apache)
- [GitHub Repository](https://github.com/apache/helix)
- [Spectral Rules](rules/apache-helix-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-helix-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
