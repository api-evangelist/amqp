# AMQP (amqp)
AMQP (Advanced Message Queuing Protocol) is an open standard for message-oriented middleware governed by OASIS and standardized as ISO/IEC 19464. AMQP 1.0 enables interoperable, asynchronous communication between applications across different platforms and vendors. It defines a wire-level protocol supporting reliable queuing, flexible routing, publish/subscribe, and request/reply messaging patterns. Major implementations include Apache ActiveMQ/Artemis, RabbitMQ, Azure Service Bus, Red Hat AMQ, and Apache Qpid.

**URL:** [Visit APIs.json URL](https://www.amqp.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AMQP, Asynchronous, Message Queue, Messaging, Middleware, Open Standard, Publish Subscribe

## Timestamps

- **Created:** 2025
- **Modified:** 2026-04-19

## APIs

### AMQP Messaging API
AsyncAPI specification for AMQP messaging patterns including publish/subscribe, request/reply, and point-to-point messaging via exchanges, queues, and bindings.

**Human URL:** [https://www.amqp.org/](https://www.amqp.org/)

#### Tags:

 - AMQP, AsyncAPI, Messaging, Point to Point, Publish Subscribe, Request Reply

#### Properties

- [AsyncAPI](asyncapi/amqp-messaging.yml)

## Common Properties

- [JSONSchema](json-schema/amqp-message.json)
- [JSONSchema](json-schema/amqp-message-properties.json)
- [JSONSchema](json-schema/amqp-exchange.json)
- [JSONSchema](json-schema/amqp-queue.json)
- [JSONSchema](json-schema/amqp-binding.json)
- [JSONLD](json-ld/amqp-context.jsonld)
- [Portal](https://www.amqp.org/)
- [Documentation](https://www.amqp.org/resources/specifications)
- [GitHubOrganization](https://github.com/amqp)
- [GitHubOrganization](https://github.com/apache)
- [JSONStructure](json-structure/amqp-message-structure.json)
- [JSONStructure](json-structure/amqp-exchange-structure.json)
- [JSONStructure](json-structure/amqp-queue-structure.json)
- [SpectralRules](rules/amqp-spectral-rules.yml)
- [Vocabulary](vocabulary/amqp-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Reliable Messaging | Guaranteed delivery with acknowledgment and persistence support. |
| Flexible Routing | Exchange types (direct, fanout, topic, headers) for flexible message routing. |
| Publish/Subscribe | Fan-out delivery to multiple consumers via topic and fanout exchanges. |
| Request/Reply | Synchronous RPC patterns over asynchronous messaging infrastructure. |
| Transaction Support | Transactional message publishing and acknowledgment for data consistency. |
| Security | SASL authentication and TLS encryption for secure message transport. |
| Flow Control | Credit-based flow control preventing consumer overload (AMQP 1.0). |
| Multi-Vendor Interoperability | Wire-level protocol interoperability across different broker implementations. |

## UseCases

| Name | Description |
|------|-------------|
| Microservices Communication | Decoupled inter-service messaging in microservices architectures. |
| Event Streaming | Event-driven architecture with durable, ordered event delivery. |
| Task Queues | Distributed work queues for background job processing. |
| IoT Messaging | Device-to-cloud and cloud-to-device messaging for IoT platforms. |
| Financial Messaging | High-reliability financial transaction messaging with guaranteed delivery. |
| Log Aggregation | Centralized log collection and routing from distributed systems. |

## Integrations

| Name | Description |
|------|-------------|
| RabbitMQ | Popular AMQP 0-9-1 compliant broker with extensive plugin ecosystem. |
| Apache ActiveMQ | Java-based message broker supporting AMQP 1.0 and multiple protocols. |
| Azure Service Bus | Microsoft's cloud messaging service with AMQP 1.0 support. |
| Apache Qpid | AMQP 1.0 implementation with broker and client library support. |
| Red Hat AMQ | Enterprise messaging platform based on ActiveMQ Artemis with AMQP 1.0. |
| Solace PubSub+ | Enterprise event broker supporting AMQP 1.0 among multiple protocols. |

## Artifacts

Machine-readable API specifications organized by format.

### AsyncAPI

- [Amqp Messaging](asyncapi/amqp-messaging.yml)

### JSON Schema

- [Amqp Binding](json-schema/amqp-binding.json)
- [Amqp Queue](json-schema/amqp-queue.json)
- [Amqp Message](json-schema/amqp-message.json)
- [Amqp Message Properties](json-schema/amqp-message-properties.json)
- [Amqp Exchange](json-schema/amqp-exchange.json)

### JSON Structure

- [Amqp Message Structure](json-structure/amqp-message-structure.json)
- [Amqp Message Properties Structure](json-structure/amqp-message-properties-structure.json)
- [Amqp Binding Structure](json-structure/amqp-binding-structure.json)
- [Amqp Exchange Structure](json-structure/amqp-exchange-structure.json)
- [Amqp Queue Structure](json-structure/amqp-queue-structure.json)

### JSON-LD

- [Amqp Amqp Message Context](json-ld/amqp-amqp-message-context.jsonld)
- [Amqp Context](json-ld/amqp-context.jsonld)
- [Amqp Amqp Exchange Context](json-ld/amqp-amqp-exchange-context.jsonld)
- [Amqp Amqp Binding Context](json-ld/amqp-amqp-binding-context.jsonld)
- [Amqp Amqp Queue Context](json-ld/amqp-amqp-queue-context.jsonld)
- [Amqp Amqp Message Properties Context](json-ld/amqp-amqp-message-properties-context.jsonld)

### Examples

- [Amqp Queue Example](examples/amqp-queue-example.json)
- [Amqp Message Properties Example](examples/amqp-message-properties-example.json)
- [Amqp Binding Example](examples/amqp-binding-example.json)
- [Amqp Message Example](examples/amqp-message-example.json)
- [Amqp Exchange Example](examples/amqp-exchange-example.json)

## Vocabulary

- [AMQP Vocabulary](vocabulary/amqp-vocabulary.yaml) — Normative vocabulary for AMQP messaging concepts including exchanges, queues, bindings, and routing patterns

## Rules

- [AMQP Spectral Rules](rules/amqp-spectral-rules.yml) — Rules enforcing AsyncAPI quality for AMQP specifications

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
