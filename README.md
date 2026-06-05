# Apache Helix (apache-helix)

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
