# Apache EventMesh (apache-event-mesh)
Apache EventMesh is a dynamic event-driven application runtime used to decouple the application and backend middleware layer, providing a serverless platform for building distributed event-driven architectures with support for CloudEvents and multiple messaging protocols including HTTP, TCP, and gRPC.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-event-mesh/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache, CloudEvents, Event-Driven, Messaging, Open Source, Pub-Sub, Serverless

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-19

## APIs

### Apache EventMesh Admin API
HTTP endpoints for managing the EventMesh runtime including topic management, subscription management, event publishing via HTTP, client monitoring, and runtime metrics.

**Human URL:** [https://eventmesh.apache.org/docs/instruction/quickstart](https://eventmesh.apache.org/docs/instruction/quickstart)

#### Tags:

 - Admin, CloudEvents, REST API, Topics

#### Properties

- [Documentation](https://eventmesh.apache.org/docs/introduction)
- [OpenAPI](openapi/eventmesh-admin.yml)
- [JSONSchema](json-schema/eventmesh-admin-cloud-event-schema.json)
- [JSON-LD](json-ld/apache-event-mesh-admin-context.jsonld)

### Apache EventMesh Messaging API
Event-driven messaging via TCP, HTTP, and gRPC protocols. Events follow the CloudEvents specification. Supports pub-sub, request-reply, and broadcast messaging patterns.

**Human URL:** [https://eventmesh.apache.org/docs/sdk-java/tcp-sdk-usage](https://eventmesh.apache.org/docs/sdk-java/tcp-sdk-usage)

#### Tags:

 - CloudEvents, Event-Driven, Messaging, Pub-Sub

#### Properties

- [Documentation](https://eventmesh.apache.org/docs/sdk-java/tcp-sdk-usage)
- [AsyncAPI](asyncapi/eventmesh-messaging.yml)

## Common Properties

- [Documentation](https://eventmesh.apache.org/docs/introduction)
- [GettingStarted](https://eventmesh.apache.org/docs/instruction/quickstart)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/eventmesh)
- [Blog](https://eventmesh.apache.org/blog)
- [Support](https://eventmesh.apache.org/community)

## Features

| Name | Description |
|------|-------------|
| CloudEvents Support | Native CloudEvents specification support for standardized event envelopes across all messaging protocols. |
| Multi-Protocol Messaging | Support for HTTP, TCP, and gRPC messaging protocols enabling flexible client connectivity. |
| Pub-Sub Messaging | Publish-subscribe messaging pattern with topic-based routing for event-driven architectures. |
| Request-Reply Pattern | Synchronous request-reply messaging over asynchronous infrastructure for RPC-style interactions. |
| Event Store | Durable event storage with replay capability for reliable event delivery and audit trails. |
| Workflow Orchestration | Event-driven workflow engine for coordinating distributed business processes and sagas. |
| Multi-Runtime Support | Pluggable connector model supporting Kafka, RocketMQ, Pulsar, and other messaging backends. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservices Decoupling | Decouple microservices through asynchronous event-driven communication reducing direct service dependencies. |
| Event Streaming Pipelines | Build scalable event streaming pipelines with durable delivery and replay capabilities. |
| Distributed Workflows | Orchestrate distributed business processes using event-driven saga and choreography patterns. |
| IoT Event Ingestion | Ingest and process high-volume IoT device events through standardized CloudEvents format. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Kafka | Kafka connector for event streaming with durable storage and consumer groups. |
| Apache RocketMQ | RocketMQ connector for high-throughput message queueing and topic management. |
| Apache Pulsar | Pulsar connector for multi-tenant event streaming with geo-replication. |
| Kubernetes | Cloud-native deployment on Kubernetes with operator support for cluster management. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache EventMesh Admin API](openapi/eventmesh-admin.yml)

### AsyncAPI

- [Apache EventMesh Messaging API](asyncapi/eventmesh-messaging.yml)

### JSON Schema

- 4 schema files in [json-schema/](json-schema/)

### JSON Structure

- 4 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Apache EventMesh Admin Context](json-ld/apache-event-mesh-admin-context.jsonld)

### Examples

- 4 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache EventMesh Admin API](capabilities/shared/eventmesh-admin.yaml) — 5 operations for topic and event management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache EventMesh Event Streaming](capabilities/eventmesh-event-streaming.yaml) | eventmesh-admin | 4 | Platform Engineer, Developer |

## Vocabulary

- [Apache EventMesh Vocabulary](vocabulary/apache-event-mesh-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 5 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache EventMesh Spectral Rules](rules/apache-event-mesh-spectral-rules.yml) — 10 rules across 4 categories enforcing Apache EventMesh API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
