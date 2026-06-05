# Apache EventMesh (apache-event-mesh)

Apache EventMesh is a dynamic event-driven application runtime used to decouple the application and backend middleware layer, providing a serverless platform for building distributed event-driven architectures with support for CloudEvents and multiple messaging protocols including HTTP, TCP, and gRPC.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-event-mesh/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-event-mesh/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Apache
- CloudEvents
- Event-Driven
- Messaging
- Open Source
- Pub-Sub
- Serverless

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-19

## APIs

### Apache EventMesh Admin API

HTTP endpoints for managing the EventMesh runtime including topic management, subscription management, event publishing via HTTP, client monitoring, and runtime metrics.

- **Human URL:** [https://eventmesh.apache.org/docs/instruction/quickstart](https://eventmesh.apache.org/docs/instruction/quickstart)
- **Base URL:** `http://localhost:10106`

#### Tags

- Admin
- CloudEvents
- REST API
- Topics

#### Properties

- [Documentation](https://eventmesh.apache.org/docs/introduction)
- [OpenAPI](openapi/eventmesh-admin.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/eventmesh-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eventmesh-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/eventmesh-admin-cloud-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/apache-event-mesh-admin-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Apache EventMesh Messaging API

Event-driven messaging via TCP, HTTP, and gRPC protocols. Events follow the CloudEvents specification. Supports pub-sub, request-reply, and broadcast messaging patterns.

- **Human URL:** [https://eventmesh.apache.org/docs/sdk-java/tcp-sdk-usage](https://eventmesh.apache.org/docs/sdk-java/tcp-sdk-usage)

#### Tags

- CloudEvents
- Event-Driven
- Messaging
- Pub-Sub

#### Properties

- [Documentation](https://eventmesh.apache.org/docs/sdk-java/tcp-sdk-usage)
- [AsyncAPI](asyncapi/eventmesh-messaging.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/eventmesh-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eventmesh-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Documentation](https://eventmesh.apache.org/docs/introduction)
- [Getting Started](https://eventmesh.apache.org/docs/instruction/quickstart)
- [GitHub Organization](https://github.com/apache)
- [GitHub Repository](https://github.com/apache/eventmesh)
- [Blog](https://eventmesh.apache.org/blog)
- [Support](https://eventmesh.apache.org/community)
- [Spectral Rules](rules/apache-event-mesh-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-event-mesh-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
