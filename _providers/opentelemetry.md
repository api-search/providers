---
api_count: 4
api_specs:
- filename: openapi.yml
  format: yaml
  label: OpenTelemetry Protocol (OTLP) HTTP API
  slug: opentelemetry-protocol-otlp-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opentelemetry/refs/heads/main/openapi.yml
apis:
- description: The OTLP HTTP API provides endpoints for exporting traces, metrics, and logs using the OpenTelemetry Protocol, the native wire format for transmitting telemetry data between instrumented applications,
  name: OpenTelemetry Protocol (OTLP) HTTP API
  slug: opentelemetry-protocol-otlp-http-api
- description: The OTLP gRPC API defines Protocol Buffers service definitions for exporting traces, metrics, and logs over gRPC. It is the primary transport for OpenTelemetry data between SDK instrumentation, the Op
  name: OpenTelemetry Protocol (OTLP) gRPC API
  slug: opentelemetry-protocol-otlp-grpc-api
- description: 'The OpenTelemetry Collector is a vendor-agnostic proxy for receiving, processing, and exporting telemetry data. It exposes HTTP and gRPC endpoints for receiving OTLP data and provides a configuration '
  name: OpenTelemetry Collector API
  slug: opentelemetry-collector-api
- description: The OpenTelemetry SDK API specifies language-level interfaces for instrumentation, including the Tracer, Meter, and Logger APIs used by application code to create spans, record metrics, and emit log r
  name: OpenTelemetry SDK API
  slug: opentelemetry-sdk-api
asyncapis:
- description: The OpenTelemetry Protocol (OTLP) defines the event-driven telemetry export pipeline through which instrumented applications and OpenTelemetry Collectors push batches of traces, metrics, and logs to o
  name: OpenTelemetry Protocol (OTLP) Telemetry Events
  slug: opentelemetry-otlp-asyncapi
common:
- title: ''
  type: Website
  url: https://opentelemetry.io/
- title: ''
  type: Documentation
  url: https://opentelemetry.io/docs/
- title: ''
  type: Getting Started
  url: https://opentelemetry.io/docs/getting-started/
- title: ''
  type: GitHub Organization
  url: https://github.com/open-telemetry
- title: ''
  type: GitHubRepository
  url: https://github.com/open-telemetry/opentelemetry-specification
- title: ''
  type: SDKs
  url: https://opentelemetry.io/docs/languages/
- title: ''
  type: Blog
  url: https://opentelemetry.io/blog/
- title: ''
  type: Community
  url: https://opentelemetry.io/community/
- title: ''
  type: Slack
  url: https://cloud-native.slack.com/archives/CJFCJHG4Q
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/open-telemetry
- title: ''
  type: Change Log
  url: https://github.com/open-telemetry/opentelemetry-specification/blob/main/CHANGELOG.md
- title: ''
  type: Security
  url: https://github.com/open-telemetry/opentelemetry-collector/security/policy
created: '2025-01-01'
description: Vendor-neutral open-source observability framework for cloud-native software, providing a collection of tools, APIs, and SDKs for instrumenting, generating, collecting, and exporting telemetry data including metrics, logs, and traces.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: OpenTelemetry
skills: []
slug: opentelemetry
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: opentelemetry\nname: OpenTelemetry\ndescription: >-\n  Vendor-neutral open-source observability framework for cloud-native software,\n  providing a collection of tools, APIs, and SDKs for instrumenting, generating,\n  collecting, and exporting telemetry data including metrics, logs, and traces.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Logging\n  - Metrics\n  - Monitoring\n  - Observability\n  - Open Source\n  - Tracing\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/opentelemetry/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: opentelemetry:opentelemetry-protocol-otlp-http-api\n    name: OpenTelemetry Protocol (OTLP) HTTP API\n    description: >-\n      The OTLP HTTP API provides endpoints for exporting traces, metrics, and\n      logs using the OpenTelemetry Protocol,\
  \ the native wire format for\n      transmitting telemetry data between instrumented applications, collectors,\n      and observability backends.\n    humanURL: https://opentelemetry.io/docs/specs/otlp/\n    tags:\n      - Logging\n      - Metrics\n      - Observability\n      - Tracing\n    properties:\n      - type: Documentation\n        url: https://opentelemetry.io/docs/specs/otlp/\n      - type: OpenAPI\n        url: openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/opentelemetry-otlp-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema.json\n      - type: JSON-LD\n        url: context.jsonld\n      - type: Reference\n        url: https://opentelemetry.io/docs/specs/otlp/#otlphttp\n      - type: Getting Started\n        url: https://opentelemetry.io/docs/collector/\n      - type: Client Libraries\n        url: https://opentelemetry.io/docs/languages/\n  - aid: opentelemetry:opentelemetry-protocol-otlp-grpc-api\n    name: OpenTelemetry Protocol (OTLP) gRPC API\n\
  \    description: >-\n      The OTLP gRPC API defines Protocol Buffers service definitions for\n      exporting traces, metrics, and logs over gRPC. It is the primary\n      transport for OpenTelemetry data between SDK instrumentation, the\n      OpenTelemetry Collector, and observability backends, offering\n      bidirectional streaming and efficient binary encoding.\n    humanURL: https://opentelemetry.io/docs/specs/otlp/#otlpgrpc\n    tags:\n      - gRPC\n      - Logging\n      - Metrics\n      - Observability\n      - Tracing\n    properties:\n      - type: Documentation\n        url: https://opentelemetry.io/docs/specs/otlp/#otlpgrpc\n      - type: Reference\n        url: https://opentelemetry.io/docs/specs/otlp/#otlpgrpc-response\n      - type: GitHubRepository\n        url: https://github.com/open-telemetry/opentelemetry-proto\n  - aid: opentelemetry:opentelemetry-collector-api\n    name: OpenTelemetry Collector API\n    description: >-\n      The OpenTelemetry Collector is a vendor-agnostic\
  \ proxy for receiving,\n      processing, and exporting telemetry data. It exposes HTTP and gRPC\n      endpoints for receiving OTLP data and provides a configuration API\n      for managing pipelines, receivers, processors, and exporters at runtime\n      via the zPages diagnostic extension and config file hot-reloading.\n    humanURL: https://opentelemetry.io/docs/collector/\n    tags:\n      - Collector\n      - Configuration\n      - Observability\n      - Pipeline\n    properties:\n      - type: Documentation\n        url: https://opentelemetry.io/docs/collector/\n      - type: Reference\n        url: https://opentelemetry.io/docs/collector/configuration/\n      - type: GitHubRepository\n        url: https://github.com/open-telemetry/opentelemetry-collector\n  - aid: opentelemetry:opentelemetry-sdk-api\n    name: OpenTelemetry SDK API\n    description: >-\n      The OpenTelemetry SDK API specifies language-level interfaces for\n      instrumentation, including the Tracer, Meter, and\
  \ Logger APIs used\n      by application code to create spans, record metrics, and emit log\n      records. Implementations are available for all major programming\n      languages including Java, Python, Go, JavaScript, .NET, Ruby, and\n      others.\n    humanURL: https://opentelemetry.io/docs/specs/otel/\n    tags:\n      - Instrumentation\n      - Logging\n      - Metrics\n      - SDK\n      - Tracing\n    properties:\n      - type: Documentation\n        url: https://opentelemetry.io/docs/specs/otel/\n      - type: Reference\n        url: https://opentelemetry.io/docs/specs/otel/trace/api/\n      - type: Client Libraries\n        url: https://opentelemetry.io/docs/languages/\n      - type: GitHubRepository\n        url: https://github.com/open-telemetry/opentelemetry-specification\ncommon:\n  - url: https://opentelemetry.io/\n    name: OpenTelemetry\n    type: Website\n    description: Official OpenTelemetry project website.\n  - url: https://opentelemetry.io/docs/\n    name: Documentation\n\
  \    type: Documentation\n    description: Official OpenTelemetry documentation hub.\n  - url: https://opentelemetry.io/docs/getting-started/\n    name: Getting Started\n    type: Getting Started\n    description: Guides for getting started with OpenTelemetry instrumentation.\n  - url: https://github.com/open-telemetry\n    name: GitHub Organization\n    type: GitHub Organization\n    description: OpenTelemetry GitHub organization containing all project repositories.\n  - url: https://github.com/open-telemetry/opentelemetry-specification\n    name: OpenTelemetry Specification\n    type: GitHubRepository\n    description: The OpenTelemetry specification defining APIs, SDKs, and data models.\n  - url: https://opentelemetry.io/docs/languages/\n    name: SDKs\n    type: SDKs\n    description: OpenTelemetry SDK implementations for all supported programming languages.\n  - url: https://opentelemetry.io/blog/\n    name: Blog\n    type: Blog\n    description: OpenTelemetry project blog with announcements\
  \ and technical articles.\n  - url: https://opentelemetry.io/community/\n    name: Community\n    type: Community\n    description: Community resources including CNCF Slack, SIG meetings, and contribution guides.\n  - url: https://cloud-native.slack.com/archives/CJFCJHG4Q\n    name: Slack\n    type: Slack\n    description: OpenTelemetry community Slack channel in the CNCF Slack workspace.\n  - url: https://stackoverflow.com/questions/tagged/open-telemetry\n    name: Stack Overflow\n    type: Stack Overflow\n    description: OpenTelemetry-tagged questions and answers on Stack Overflow.\n  - url: https://github.com/open-telemetry/opentelemetry-specification/blob/main/CHANGELOG.md\n    name: Change Log\n    type: Change Log\n    description: Changelog for the OpenTelemetry specification.\n  - url: https://github.com/open-telemetry/opentelemetry-collector/security/policy\n    name: Security\n    type: Security\n    description: Security disclosure policy for the OpenTelemetry project.\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/opentelemetry/refs/heads/main/apis.yml
tags:
- Cloud Native
- Logging
- Metrics
- Monitoring
- Observability
- Open Source
- Tracing
url: https://raw.githubusercontent.com/api-evangelist/opentelemetry/refs/heads/main/apis.yml
use_cases: []
---
