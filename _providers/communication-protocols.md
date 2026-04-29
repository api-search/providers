---
api_count: 8
apis:
- description: The application layer protocol that powers the World Wide Web and the majority of REST and HTTP APIs. HTTP/1.1 is defined in RFC 9110-9114, HTTP/2 in RFC 9113, and HTTP/3 in RFC 9114, the latter runni
  name: Hypertext Transfer Protocol (HTTP)
  slug: http
- description: A high-performance, contract-first RPC framework built on HTTP/2 with Protocol Buffers as the default IDL. gRPC supports unary, server streaming, client streaming, and bidirectional streaming and is w
  name: gRPC
  slug: grpc
- description: A query language and runtime for client-driven data APIs over HTTP and WebSockets. GraphQL exposes a single endpoint with a typed schema defining queries, mutations, and subscriptions, allowing client
  name: GraphQL
  slug: graphql
- description: A bidirectional, full-duplex communication protocol over a single TCP connection, defined in RFC 6455. WebSocket upgrades from HTTP and is widely used for chat, collaborative editing, live dashboards,
  name: WebSocket
  slug: websocket
- description: A lightweight publish-subscribe messaging protocol designed for constrained devices and unreliable networks. MQTT is an OASIS standard and is widely used in IoT, automotive, and edge environments. MQT
  name: MQTT
  slug: mqtt
- description: The Advanced Message Queuing Protocol, an OASIS standard for interoperable, broker-mediated messaging. AMQP 1.0 defines a wire protocol with strong typing, links, sessions, and connection-level securi
  name: AMQP
  slug: amqp
- description: An HTTP-based pattern for delivering event notifications from one service to another by performing an outbound HTTP POST to a URL registered by the consumer. Webhooks are not a single specification bu
  name: Webhooks
  slug: webhooks
- description: 'A simple, one-way, server-to-client streaming protocol defined as part of the HTML living standard. SSE runs over plain HTTP, supports automatic reconnection, and is widely used for live status feeds '
  name: Server-Sent Events (SSE)
  slug: server-sent-events
common:
- title: ''
  type: Documentation
  url: https://www.iana.org/assignments/uri-schemes/uri-schemes.xhtml
- title: ''
  type: Reference
  url: https://www.rfc-editor.org/standards
- title: ''
  type: Reference
  url: https://www.iso.org/standard/74534.html
- title: ''
  type: Reference
  url: https://en.wikipedia.org/wiki/Communication_protocol
- title: ''
  type: Resources
  url: https://www.cncf.io/
created: '2025-01-01'
description: Communication protocols are systems of rules that allow two or more entities in a networked system to exchange information. Modern API platforms rely on layered protocol stacks that span the physical and link layers, network and transport layers, and application protocols such as HTTP, gRPC, MQTT, AMQP, WebSockets, SSE, and Webhooks. The communication protocols topic surveys the most relevant standards bodies (IETF, W3C, IEEE, ITU, ISO), the most widely deployed protocols at each layer, and the way protocol choice shapes API design, performance, security, and interoperability.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Communication Protocols
skills: []
slug: communication-protocols
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: communication-protocols\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/communication-protocols/refs/heads/main/apis.yml\nname: Communication Protocols\nx-type: topic\ndescription: >-\n  Communication protocols are systems of rules that allow two or more entities\n  in a networked system to exchange information. Modern API platforms rely on\n  layered protocol stacks that span the physical and link layers, network and\n  transport layers, and application protocols such as HTTP, gRPC, MQTT, AMQP,\n  WebSockets, SSE, and Webhooks. The communication protocols topic surveys\n  the most relevant standards bodies (IETF, W3C, IEEE, ITU, ISO), the most\n  widely deployed protocols at each layer, and the way protocol choice shapes\n  API design, performance, security, and interoperability.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - APIs\n  - Application Protocols\n  - Communication Protocols\n  - Internet\n  - IETF\n\
  \  - Networking\n  - Real-Time\n  - Standards\n  - Transport\n  - Web\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: communication-protocols:http\n    name: Hypertext Transfer Protocol (HTTP)\n    description: >-\n      The application layer protocol that powers the World Wide Web and the\n      majority of REST and HTTP APIs. HTTP/1.1 is defined in RFC 9110-9114,\n      HTTP/2 in RFC 9113, and HTTP/3 in RFC 9114, the latter running over\n      QUIC. HTTP defines methods, status codes, headers, content negotiation,\n      caching, and conditional requests that underpin modern web APIs.\n    humanURL: https://httpwg.org/specs/\n    baseURL: https://httpwg.org\n    tags:\n      - Application Protocol\n      - HTTP\n      - IETF\n      - REST\n      - Web\n    properties:\n      - type: Specification\n        url: https://www.rfc-editor.org/rfc/rfc9110\n      - type: Specification\n        url: https://www.rfc-editor.org/rfc/rfc9112\n      -\
  \ type: Specification\n        url: https://www.rfc-editor.org/rfc/rfc9113\n      - type: Specification\n        url: https://www.rfc-editor.org/rfc/rfc9114\n      - type: Working Group\n        url: https://datatracker.ietf.org/wg/httpbis/about/\n    x-features:\n      - Stateless request/response model\n      - Methods, status codes, headers, content negotiation\n      - HTTP/2 multiplexing and HPACK header compression\n      - HTTP/3 over QUIC for low-latency, head-of-line-free transport\n      - Strong caching semantics with conditional requests\n    x-useCases:\n      - REST and resource-oriented APIs\n      - GraphQL and gRPC-Web transport\n      - Webhook delivery\n      - Browser-to-API communication\n  - aid: communication-protocols:grpc\n    name: gRPC\n    description: >-\n      A high-performance, contract-first RPC framework built on HTTP/2 with\n      Protocol Buffers as the default IDL. gRPC supports unary, server\n      streaming, client streaming, and bidirectional streaming\
  \ and is widely\n      used for microservice-to-microservice communication and for\n      polyglot APIs across cloud-native platforms.\n    humanURL: https://grpc.io/\n    baseURL: https://grpc.io\n    tags:\n      - CNCF\n      - HTTP/2\n      - Protocol Buffers\n      - RPC\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://grpc.io/docs/\n      - type: Specification\n        url: https://github.com/grpc/grpc/blob/master/doc/PROTOCOL-HTTP2.md\n      - type: GitHub Organization\n        url: https://github.com/grpc\n    x-features:\n      - HTTP/2 multiplexed transport with Protobuf payloads\n      - Four streaming modes (unary, server, client, bidi)\n      - Polyglot code generation across 11+ languages\n      - Pluggable authentication, deadlines, and interceptors\n    x-useCases:\n      - Internal microservice communication\n      - Mobile-to-backend APIs with low latency\n      - High-throughput streaming workloads\n      - Polyglot service interfaces\n\
  \  - aid: communication-protocols:graphql\n    name: GraphQL\n    description: >-\n      A query language and runtime for client-driven data APIs over HTTP and\n      WebSockets. GraphQL exposes a single endpoint with a typed schema\n      defining queries, mutations, and subscriptions, allowing clients to\n      request precisely the data they need.\n    humanURL: https://graphql.org/\n    baseURL: https://graphql.org\n    tags:\n      - API\n      - GraphQL\n      - HTTP\n      - Schema\n      - Subscriptions\n    properties:\n      - type: Specification\n        url: https://spec.graphql.org/\n      - type: Documentation\n        url: https://graphql.org/learn/\n      - type: Reference\n        url: https://github.com/graphql/graphql-spec\n    x-features:\n      - Strongly typed schema definition language (SDL)\n      - Single endpoint with arbitrary query shapes\n      - Subscriptions for real-time pushes over WebSocket\n      - Introspection enabling tooling and codegen\n    x-useCases:\n\
  \      - Aggregating data from multiple backends\n      - Tailored mobile and web client payloads\n      - BFF (backend for frontend) APIs\n      - Real-time dashboards via subscriptions\n  - aid: communication-protocols:websocket\n    name: WebSocket\n    description: >-\n      A bidirectional, full-duplex communication protocol over a single TCP\n      connection, defined in RFC 6455. WebSocket upgrades from HTTP and is\n      widely used for chat, collaborative editing, live dashboards, and game\n      servers.\n    humanURL: https://www.rfc-editor.org/rfc/rfc6455\n    baseURL: https://www.rfc-editor.org\n    tags:\n      - Bidirectional\n      - IETF\n      - Real-Time\n      - Web\n      - WebSocket\n    properties:\n      - type: Specification\n        url: https://www.rfc-editor.org/rfc/rfc6455\n      - type: Documentation\n        url: https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API\n    x-features:\n      - HTTP upgrade handshake to TCP-level full-duplex frames\n\
  \      - Text and binary frame types\n      - Subprotocol negotiation (e.g. graphql-ws, mqtt)\n      - Native support in browsers and most server runtimes\n    x-useCases:\n      - Real-time chat and collaboration\n      - Live tickers and dashboards\n      - GraphQL subscription transport\n      - Multiplayer games and signaling\n  - aid: communication-protocols:mqtt\n    name: MQTT\n    description: >-\n      A lightweight publish-subscribe messaging protocol designed for\n      constrained devices and unreliable networks. MQTT is an OASIS standard\n      and is widely used in IoT, automotive, and edge environments. MQTT 5\n      adds user properties, reason codes, shared subscriptions, and other\n      modern features.\n    humanURL: https://mqtt.org/\n    baseURL: https://mqtt.org\n    tags:\n      - IoT\n      - Lightweight\n      - OASIS\n      - Pub/Sub\n    properties:\n      - type: Specification\n        url: https://docs.oasis-open.org/mqtt/mqtt/v5.0/mqtt-v5.0.html\n      -\
  \ type: Documentation\n        url: https://mqtt.org/getting-started/\n      - type: Reference\n        url: https://www.hivemq.com/mqtt/mqtt-essentials/\n    x-features:\n      - Tiny binary protocol with three QoS levels\n      - Hierarchical topic-based pub/sub\n      - Retained messages and last-will-and-testament\n      - MQTT 5 reason codes, properties, and shared subscriptions\n    x-useCases:\n      - IoT telemetry and command/control\n      - Automotive and industrial messaging\n      - Mobile push and presence\n      - Edge-to-cloud streaming\n  - aid: communication-protocols:amqp\n    name: AMQP\n    description: >-\n      The Advanced Message Queuing Protocol, an OASIS standard for\n      interoperable, broker-mediated messaging. AMQP 1.0 defines a wire\n      protocol with strong typing, links, sessions, and connection-level\n      security and is used by RabbitMQ, Azure Service Bus, and many other\n      brokers.\n    humanURL: https://www.amqp.org/\n    baseURL: https://www.amqp.org\n\
  \    tags:\n      - Brokered\n      - Enterprise Messaging\n      - OASIS\n      - Queuing\n    properties:\n      - type: Specification\n        url: https://docs.oasis-open.org/amqp/core/v1.0/os/amqp-core-overview-v1.0-os.html\n      - type: Documentation\n        url: https://www.rabbitmq.com/protocol.html\n    x-features:\n      - Wire-level interoperability across brokers\n      - Reliable, transactional messaging with sessions and links\n      - SASL-based authentication and TLS transport\n    x-useCases:\n      - Enterprise integration and ESB scenarios\n      - Cross-language work queues and task distribution\n      - Cloud broker messaging on Azure Service Bus\n  - aid: communication-protocols:webhooks\n    name: Webhooks\n    description: >-\n      An HTTP-based pattern for delivering event notifications from one\n      service to another by performing an outbound HTTP POST to a URL\n      registered by the consumer. Webhooks are not a single specification\n      but the broader\
  \ pattern is increasingly governed by efforts such as\n      the CloudEvents specification and the IETF Webhook security drafts.\n    humanURL: https://webhooks.fyi/\n    baseURL: https://webhooks.fyi\n    tags:\n      - Async\n      - Events\n      - HTTP\n      - Push\n    properties:\n      - type: Reference\n        url: https://webhooks.fyi/\n      - type: Specification\n        url: https://cloudevents.io/\n      - type: Documentation\n        url: https://www.standardwebhooks.com/\n    x-features:\n      - Outbound HTTP POST event delivery\n      - Pluggable signing schemes (HMAC, JWT) for verification\n      - Replay protection with timestamps and nonces\n      - Aligns with CloudEvents and Standard Webhooks\n    x-useCases:\n      - Asynchronous event delivery between SaaS platforms\n      - Build, deploy, and CI pipeline notifications\n      - Payment and billing event hooks\n      - Third-party integrations without polling\n  - aid: communication-protocols:server-sent-events\n\
  \    name: Server-Sent Events (SSE)\n    description: >-\n      A simple, one-way, server-to-client streaming protocol defined as part\n      of the HTML living standard. SSE runs over plain HTTP, supports\n      automatic reconnection, and is widely used for live status feeds and\n      LLM token streaming.\n    humanURL: https://html.spec.whatwg.org/multipage/server-sent-events.html\n    baseURL: https://html.spec.whatwg.org\n    tags:\n      - HTML\n      - HTTP\n      - Real-Time\n      - Streaming\n    properties:\n      - type: Specification\n        url: https://html.spec.whatwg.org/multipage/server-sent-events.html\n      - type: Documentation\n        url: https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events\n    x-features:\n      - Plain HTTP text/event-stream responses\n      - Automatic browser reconnection with Last-Event-ID\n      - Simpler than WebSocket for one-way fan-out\n    x-useCases:\n      - LLM token streaming\n      - Live status and activity feeds\n\
  \      - Server-pushed dashboards\ncommon:\n  - type: Documentation\n    url: https://www.iana.org/assignments/uri-schemes/uri-schemes.xhtml\n  - type: Reference\n    url: https://www.rfc-editor.org/standards\n  - type: Reference\n    url: https://www.iso.org/standard/74534.html\n  - type: Reference\n    url: https://en.wikipedia.org/wiki/Communication_protocol\n  - type: Resources\n    url: https://www.cncf.io/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/communication-protocols/refs/heads/main/apis.yml
tags:
- APIs
- Application Protocols
- Communication Protocols
- Internet
- IETF
- Networking
- Real-Time
- Standards
- Transport
- Web
url: https://raw.githubusercontent.com/api-evangelist/communication-protocols/refs/heads/main/apis.yml
use_cases: []
---
