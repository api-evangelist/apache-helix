# Apache Helix (apache-helix)
Apache Helix is a generic cluster management framework for partitioned and replicated distributed resources. It automates partition management, replication, fault tolerance, and cluster expansion for distributed systems, providing a REST API for cluster administration and a Java API for participant, spectator, and controller roles.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-helix/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache, Cluster Management, Distributed Systems, Open Source, Partitioning, Replication

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Helix REST API
REST API for managing Apache Helix clusters, instances, resources, and partition state assignments, including ideal state queries and external view inspection.

**Human URL:** [https://helix.apache.org/0.9.9-docs/tutorial_admin.html](https://helix.apache.org/0.9.9-docs/tutorial_admin.html)

#### Tags:

 - Cluster Management, Instances, Partitions, REST, Resources

#### Properties

- [Documentation](https://helix.apache.org/0.9.9-docs/tutorial_admin.html)
- [OpenAPI](openapi/apache-helix-rest-openapi.yml)
- [JSONSchema](json-schema/helix-rest-cluster-schema.json)
- [JSON-LD](json-ld/apache-helix-rest-context.jsonld)

### Apache Helix Java API
Java API for implementing Helix participant, spectator, and controller roles, with APIs for resource management, task execution, and state machine definitions.

**Human URL:** [https://helix.apache.org/0.9.9-docs/tutorial_participant.html](https://helix.apache.org/0.9.9-docs/tutorial_participant.html)

#### Tags:

 - Java, SDK, State Machine

#### Properties

- [Documentation](https://helix.apache.org/0.9.9-docs/tutorial_participant.html)
- [Java SDK (Maven Central)](https://search.maven.org/artifact/org.apache.helix/helix-core)

## Common Properties

- [Documentation](https://helix.apache.org/)
- [GettingStarted](https://helix.apache.org/0.9.9-docs/Quickstart.html)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/helix)

## Features

| Name | Description |
|------|-------------|
| Automatic Partition Management | Automatically assign and balance partitions across cluster nodes using pluggable rebalancer algorithms. |
| State Machine Framework | Define custom resource state machines (e.g., Master-Slave, Leader-Standby) for any distributed service. |
| Fault Tolerance | Detect node failures and automatically reassign partitions to maintain replication targets. |
| REST API | HTTP REST API for cluster administration, resource management, and state inspection. |
| Task Framework | Distributed task scheduling framework for batch jobs and recurring workflows with failure handling. |
| ZooKeeper Integration | Uses Apache ZooKeeper as the distributed coordination backend for cluster state storage. |
| Spectator API | Read-only API for external services to observe resource state and routing decisions. |
| Cloud-Aware Rebalancing | Rack and zone-aware partition placement for fault-domain isolation in cloud environments. |

## Use Cases

| Name | Description |
|------|-------------|
| Distributed Database Cluster Management | Manage shard assignment and replication for distributed databases like DistributedLog or Espresso. |
| Search Index Partition Management | Automatically balance and assign search index shards across a cluster of query servers. |
| Distributed Task Scheduling | Schedule and execute distributed batch tasks with automatic retry and failure recovery. |
| Microservices Load Balancing | Use Helix spectator API to implement client-side load balancing based on partition state. |
| Stateful Service Migration | Perform rolling upgrades and partition migrations without service downtime. |

## Integrations

| Name | Description |
|------|-------------|
| Apache ZooKeeper | ZooKeeper is the required coordination backend for Helix cluster state management. |
| Apache Kafka | Helix is used internally by some Kafka ecosystem projects for partition management. |
| LinkedIn Pinot | Apache Pinot uses Helix for real-time OLAP cluster partition and segment management. |
| LinkedIn Venice | Venice feature store uses Helix for managing data store partition assignments. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Helix REST API](openapi/apache-helix-rest-openapi.yml)

### JSON Schema

- 6 schema files in [json-schema/](json-schema/)

### JSON Structure

- 6 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Apache Helix REST Context](json-ld/apache-helix-rest-context.jsonld)

### Examples

- 6 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Helix REST API](capabilities/shared/helix-rest.yaml) — 5 operations for cluster and resource management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Helix Cluster Management](capabilities/helix-cluster-management.yaml) | helix-rest | 5 | Platform Engineer |

## Vocabulary

- [Apache Helix Vocabulary](vocabulary/apache-helix-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 5 actions, 1 workflow, and 1 persona across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache Helix Spectral Rules](rules/apache-helix-spectral-rules.yml) — 8 rules across 4 categories enforcing Apache Helix API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
