---
api_count: 13
api_specs:
- filename: dapr-state-management-openapi.yml
  format: yaml
  label: Dapr State Management API
  slug: state-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-state-management-openapi.yml
- filename: dapr-pubsub-openapi.yml
  format: yaml
  label: Dapr Pub/Sub API
  slug: pubsub
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-pubsub-openapi.yml
- filename: dapr-service-invocation-openapi.yml
  format: yaml
  label: Dapr Service Invocation API
  slug: service-invocation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-service-invocation-openapi.yml
- filename: dapr-bindings-openapi.yml
  format: yaml
  label: Dapr Bindings API
  slug: bindings
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-bindings-openapi.yml
- filename: dapr-secrets-openapi.yml
  format: yaml
  label: Dapr Secrets API
  slug: secrets
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-secrets-openapi.yml
- filename: dapr-actors-openapi.yml
  format: yaml
  label: Dapr Actors API
  slug: actors
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-actors-openapi.yml
- filename: dapr-workflow-openapi.yml
  format: yaml
  label: Dapr Workflow API
  slug: workflow
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-workflow-openapi.yml
- filename: dapr-configuration-openapi.yml
  format: yaml
  label: Dapr Configuration API
  slug: configuration
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-configuration-openapi.yml
- filename: dapr-distributed-lock-openapi.yml
  format: yaml
  label: Dapr Distributed Lock API
  slug: distributed-lock
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-distributed-lock-openapi.yml
- filename: dapr-cryptography-openapi.yml
  format: yaml
  label: Dapr Cryptography API
  slug: cryptography
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-cryptography-openapi.yml
- filename: dapr-jobs-openapi.yml
  format: yaml
  label: Dapr Jobs API
  slug: jobs
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-jobs-openapi.yml
- filename: dapr-health-openapi.yml
  format: yaml
  label: Dapr Health API
  slug: health
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-health-openapi.yml
- filename: dapr-metadata-openapi.yml
  format: yaml
  label: Dapr Metadata API
  slug: metadata
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-metadata-openapi.yml
apis:
- description: The Dapr State Management API provides key/value-based state management capabilities for distributed applications. It supports saving, retrieving, deleting, and performing bulk and transactional opera
  name: Dapr State Management API
  slug: state-management
- description: The Dapr Pub/Sub API enables publish and subscribe messaging between applications. It supports publishing events to topics, bulk publishing, and discovering topic subscriptions using the CloudEvents 1
  name: Dapr Pub/Sub API
  slug: pubsub
- description: The Dapr Service Invocation API enables applications to communicate with each other through well-known endpoints using HTTP methods. Dapr acts as a reverse proxy with built-in service discovery, distr
  name: Dapr Service Invocation API
  slug: service-invocation
- description: The Dapr Bindings API enables applications to trigger and invoke external resources through output bindings, and receive events from external resources through input bindings. Supported bindings inclu
  name: Dapr Bindings API
  slug: bindings
- description: The Dapr Secrets API provides a consistent way to retrieve application secrets from various secret stores, including Hashicorp Vault, AWS Secrets Manager, Azure Key Vault, GCP Secret Manager, and Kube
  name: Dapr Secrets API
  slug: secrets
- description: The Dapr Actors API provides virtual actor capabilities for distributed applications, including actor method invocation, state management, timers, and reminders with guaranteed single-threaded executi
  name: Dapr Actors API
  slug: actors
- description: The Dapr Workflow API provides the ability to manage workflow instances, including starting, getting status, pausing, resuming, terminating, purging, and raising events to workflows.
  name: Dapr Workflow API
  slug: workflow
- description: The Dapr Configuration API enables applications to retrieve and subscribe to configuration items from supported configuration stores, allowing applications to react to configuration changes in real ti
  name: Dapr Configuration API
  slug: configuration
- description: The Dapr Distributed Lock API enables applications to acquire and release locks on shared resources, ensuring mutual exclusion across multiple application instances using a lease-based locking mechani
  name: Dapr Distributed Lock API
  slug: distributed-lock
- description: 'The Dapr Cryptography API enables applications to perform cryptographic operations such as encrypting and decrypting data using configured cryptography components, without exposing cryptographic keys '
  name: Dapr Cryptography API
  slug: cryptography
- description: The Dapr Jobs API enables applications to schedule, retrieve, and delete jobs for future execution at specific times or intervals using cron expressions or duration specifications.
  name: Dapr Jobs API
  slug: jobs
- description: The Dapr Health API provides health check endpoints for the Dapr sidecar, usable with container orchestrators like Kubernetes for readiness and liveness probes.
  name: Dapr Health API
  slug: health
- description: The Dapr Metadata API provides information about the Dapr sidecar, including application connection details, registered components, active subscriptions, and HTTP endpoints. It also allows setting cus
  name: Dapr Metadata API
  slug: metadata
asyncapis:
- description: The Dapr Pub/Sub AsyncAPI defines the event-driven messaging interfaces for Dapr publish and subscribe operations. Applications publish events to topics and subscribe to receive events using the Cloud
  name: Dapr Pub/Sub Messaging API
  slug: dapr-pubsub-asyncapi
capabilities: []
common:
- title: ''
  type: Website
  url: https://dapr.io/
- title: ''
  type: Documentation
  url: https://docs.dapr.io/
- title: ''
  type: Getting Started
  url: https://docs.dapr.io/getting-started/
- title: ''
  type: Blog
  url: https://blog.dapr.io/
- title: ''
  type: GitHub Organization
  url: https://github.com/dapr
- title: ''
  type: GitHubRepository
  url: https://github.com/dapr/dapr
- title: ''
  type: SDKs
  url: https://docs.dapr.io/sdks/
- title: ''
  type: Community
  url: https://discord.gg/ptHhX6jc34
- title: ''
  type: Change Log
  url: https://github.com/dapr/dapr/blob/master/CHANGELOG.md
- title: ''
  type: Security
  url: https://github.com/dapr/dapr/security/policy
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/dapr
- title: ''
  type: JSON-LD
  url: json-ld/dapr-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/dapr-vocabulary.yml
- title: ''
  type: Rules
  url: rules/dapr-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/dapr-capabilities.yml
created: '2025-01-08'
description: Dapr (Distributed Application Runtime) is a portable, event-driven runtime that makes it easy for developers to build resilient, stateless, and stateful applications that run on the cloud and edge. It provides building block APIs for state management, pub/sub messaging, service invocation, bindings, actors, workflows, secrets, configuration, distributed locks, cryptography, jobs scheduling, health checks, and metadata.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Dapr Context
  property_count: 9
  slug: dapr-context
layout: provider
modified: '2026-04-28'
name: Dapr
rules:
- name: Dapr API Rules
  rule_count: 5
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 4
  slug: dapr-rules
skills: []
slug: dapr
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dapr\nurl: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/apis.yml\napis:\n  - aid: dapr:state-management\n    name: Dapr State Management API\n    tags:\n      - Distributed Systems\n      - Key Value\n      - State Management\n    humanURL: https://docs.dapr.io/reference/api/state_api/\n    properties:\n      - url: https://docs.dapr.io/reference/api/state_api/\n        type: Documentation\n      - url: openapi/dapr-state-management-openapi.yml\n        type: OpenAPI\n      - url: json-schema/state-item.json\n        type: JSONSchema\n      - url: https://docs.dapr.io/developing-applications/building-blocks/state-management/\n        type: Reference\n      - url: https://docs.dapr.io/sdks/\n        type: Client Libraries\n    description: >-\n      The Dapr State Management API provides key/value-based state management\n      capabilities for distributed applications. It supports saving, retrieving,\n      deleting, and performing bulk and transactional\
  \ operations on application\n      state using pluggable state stores.\n  - aid: dapr:pubsub\n    name: Dapr Pub/Sub API\n    tags:\n      - CloudEvents\n      - Events\n      - Messaging\n      - Pub/Sub\n    humanURL: https://docs.dapr.io/reference/api/pubsub_api/\n    properties:\n      - url: https://docs.dapr.io/reference/api/pubsub_api/\n        type: Documentation\n      - url: openapi/dapr-pubsub-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/dapr-pubsub-asyncapi.yml\n        type: AsyncAPI\n      - url: json-schema/cloud-event.json\n        type: JSONSchema\n      - url: https://docs.dapr.io/developing-applications/building-blocks/pubsub/\n        type: Reference\n      - url: https://docs.dapr.io/sdks/\n        type: Client Libraries\n    description: >-\n      The Dapr Pub/Sub API enables publish and subscribe messaging between\n      applications. It supports publishing events to topics, bulk publishing,\n      and discovering topic subscriptions using the CloudEvents\
  \ 1.0 specification.\n  - aid: dapr:service-invocation\n    name: Dapr Service Invocation API\n    tags:\n      - Microservices\n      - Service Discovery\n      - Service Invocation\n    humanURL: https://docs.dapr.io/reference/api/service_invocation_api/\n    properties:\n      - url: https://docs.dapr.io/reference/api/service_invocation_api/\n        type: Documentation\n      - url: openapi/dapr-service-invocation-openapi.yml\n        type: OpenAPI\n      - url: https://docs.dapr.io/developing-applications/building-blocks/service-invocation/\n        type: Reference\n      - url: https://docs.dapr.io/sdks/\n        type: Client Libraries\n    description: >-\n      The Dapr Service Invocation API enables applications to communicate with\n      each other through well-known endpoints using HTTP methods. Dapr acts as\n      a reverse proxy with built-in service discovery, distributed tracing,\n      and error handling.\n  - aid: dapr:bindings\n    name: Dapr Bindings API\n    tags:\n\
  \      - Bindings\n      - Event-Driven\n      - Integrations\n    humanURL: https://docs.dapr.io/reference/api/bindings_api/\n    properties:\n      - url: https://docs.dapr.io/reference/api/bindings_api/\n        type: Documentation\n      - url: openapi/dapr-bindings-openapi.yml\n        type: OpenAPI\n      - url: json-schema/binding.json\n        type: JSONSchema\n      - url: https://docs.dapr.io/developing-applications/building-blocks/bindings/\n        type: Reference\n      - url: https://docs.dapr.io/sdks/\n        type: Client Libraries\n    description: >-\n      The Dapr Bindings API enables applications to trigger and invoke external\n      resources through output bindings, and receive events from external\n      resources through input bindings. Supported bindings include Kafka,\n      RabbitMQ, Azure Event Hubs, AWS SQS, GCP Storage, and more.\n  - aid: dapr:secrets\n    name: Dapr Secrets API\n    tags:\n      - Key Management\n      - Secrets\n      - Security\n    humanURL:\
  \ https://docs.dapr.io/reference/api/secrets_api/\n    properties:\n      - url: https://docs.dapr.io/reference/api/secrets_api/\n        type: Documentation\n      - url: openapi/dapr-secrets-openapi.yml\n        type: OpenAPI\n      - url: json-schema/secret.json\n        type: JSONSchema\n      - url: https://docs.dapr.io/developing-applications/building-blocks/secrets/\n        type: Reference\n      - url: https://docs.dapr.io/sdks/\n        type: Client Libraries\n    description: >-\n      The Dapr Secrets API provides a consistent way to retrieve application\n      secrets from various secret stores, including Hashicorp Vault, AWS\n      Secrets Manager, Azure Key Vault, GCP Secret Manager, and Kubernetes\n      Secrets.\n  - aid: dapr:actors\n    name: Dapr Actors API\n    tags:\n      - Actors\n      - Distributed Systems\n      - Virtual Actors\n    humanURL: https://docs.dapr.io/reference/api/actors_api/\n    properties:\n      - url: https://docs.dapr.io/reference/api/actors_api/\n\
  \        type: Documentation\n      - url: openapi/dapr-actors-openapi.yml\n        type: OpenAPI\n      - url: json-schema/actor.json\n        type: JSONSchema\n      - url: https://docs.dapr.io/developing-applications/building-blocks/actors/\n        type: Reference\n      - url: https://docs.dapr.io/sdks/\n        type: Client Libraries\n    description: >-\n      The Dapr Actors API provides virtual actor capabilities for distributed\n      applications, including actor method invocation, state management, timers,\n      and reminders with guaranteed single-threaded execution and message ordering.\n  - aid: dapr:workflow\n    name: Dapr Workflow API\n    tags:\n      - Distributed Systems\n      - Orchestration\n      - Workflows\n    humanURL: https://docs.dapr.io/reference/api/workflow_api/\n    properties:\n      - url: https://docs.dapr.io/reference/api/workflow_api/\n        type: Documentation\n      - url: openapi/dapr-workflow-openapi.yml\n        type: OpenAPI\n      - url:\
  \ json-schema/workflow.json\n        type: JSONSchema\n      - url: https://docs.dapr.io/developing-applications/building-blocks/workflow/\n        type: Reference\n      - url: https://docs.dapr.io/sdks/\n        type: Client Libraries\n    description: >-\n      The Dapr Workflow API provides the ability to manage workflow instances,\n      including starting, getting status, pausing, resuming, terminating,\n      purging, and raising events to workflows.\n  - aid: dapr:configuration\n    name: Dapr Configuration API\n    tags:\n      - Configuration\n      - Distributed Systems\n      - Subscriptions\n    humanURL: https://docs.dapr.io/reference/api/configuration_api/\n    properties:\n      - url: https://docs.dapr.io/reference/api/configuration_api/\n        type: Documentation\n      - url: openapi/dapr-configuration-openapi.yml\n        type: OpenAPI\n      - url: json-schema/configuration-item.json\n        type: JSONSchema\n      - url: https://docs.dapr.io/developing-applications/building-blocks/configuration/\n\
  \        type: Reference\n      - url: https://docs.dapr.io/sdks/\n        type: Client Libraries\n    description: >-\n      The Dapr Configuration API enables applications to retrieve and subscribe\n      to configuration items from supported configuration stores, allowing\n      applications to react to configuration changes in real time.\n  - aid: dapr:distributed-lock\n    name: Dapr Distributed Lock API\n    tags:\n      - Concurrency\n      - Coordination\n      - Distributed Lock\n    humanURL: https://docs.dapr.io/reference/api/distributed_lock_api/\n    properties:\n      - url: https://docs.dapr.io/reference/api/distributed_lock_api/\n        type: Documentation\n      - url: openapi/dapr-distributed-lock-openapi.yml\n        type: OpenAPI\n      - url: https://docs.dapr.io/developing-applications/building-blocks/distributed-lock/\n        type: Reference\n      - url: https://docs.dapr.io/sdks/\n        type: Client Libraries\n    description: >-\n      The Dapr Distributed\
  \ Lock API enables applications to acquire and release\n      locks on shared resources, ensuring mutual exclusion across multiple\n      application instances using a lease-based locking mechanism.\n  - aid: dapr:cryptography\n    name: Dapr Cryptography API\n    tags:\n      - Cryptography\n      - Encryption\n      - Security\n    humanURL: https://docs.dapr.io/reference/api/cryptography_api/\n    properties:\n      - url: https://docs.dapr.io/reference/api/cryptography_api/\n        type: Documentation\n      - url: openapi/dapr-cryptography-openapi.yml\n        type: OpenAPI\n      - url: https://docs.dapr.io/developing-applications/building-blocks/cryptography/\n        type: Reference\n      - url: https://docs.dapr.io/sdks/\n        type: Client Libraries\n    description: >-\n      The Dapr Cryptography API enables applications to perform cryptographic\n      operations such as encrypting and decrypting data using configured\n      cryptography components, without exposing cryptographic\
  \ keys to the\n      application.\n  - aid: dapr:jobs\n    name: Dapr Jobs API\n    tags:\n      - Cron\n      - Jobs\n      - Scheduling\n    humanURL: https://docs.dapr.io/reference/api/jobs_api/\n    properties:\n      - url: https://docs.dapr.io/reference/api/jobs_api/\n        type: Documentation\n      - url: openapi/dapr-jobs-openapi.yml\n        type: OpenAPI\n      - url: json-schema/job.json\n        type: JSONSchema\n      - url: https://docs.dapr.io/developing-applications/building-blocks/jobs/\n        type: Reference\n      - url: https://docs.dapr.io/sdks/\n        type: Client Libraries\n    description: >-\n      The Dapr Jobs API enables applications to schedule, retrieve, and delete\n      jobs for future execution at specific times or intervals using cron\n      expressions or duration specifications.\n  - aid: dapr:health\n    name: Dapr Health API\n    tags:\n      - Health\n      - Kubernetes\n      - Monitoring\n    humanURL: https://docs.dapr.io/reference/api/health_api/\n\
  \    properties:\n      - url: https://docs.dapr.io/reference/api/health_api/\n        type: Documentation\n      - url: openapi/dapr-health-openapi.yml\n        type: OpenAPI\n      - url: https://docs.dapr.io/operations/observability/healthchecks/\n        type: Reference\n    description: >-\n      The Dapr Health API provides health check endpoints for the Dapr sidecar,\n      usable with container orchestrators like Kubernetes for readiness and\n      liveness probes.\n  - aid: dapr:metadata\n    name: Dapr Metadata API\n    tags:\n      - Metadata\n      - Observability\n      - Runtime\n    humanURL: https://docs.dapr.io/reference/api/metadata_api/\n    properties:\n      - url: https://docs.dapr.io/reference/api/metadata_api/\n        type: Documentation\n      - url: openapi/dapr-metadata-openapi.yml\n        type: OpenAPI\n      - url: json-schema/metadata.json\n        type: JSONSchema\n      - url: https://docs.dapr.io/operations/observability/\n        type: Reference\n  \
  \  description: >-\n      The Dapr Metadata API provides information about the Dapr sidecar,\n      including application connection details, registered components, active\n      subscriptions, and HTTP endpoints. It also allows setting custom metadata\n      attributes.\nname: Dapr\ntags:\n  - Distributed Systems\n  - Microservices\n  - Platform\n  - Pub/Sub\n  - State Management\n  - Workflows\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://dapr.io/\n    name: Website\n    type: Website\n    description: Official Dapr project website.\n  - url: https://docs.dapr.io/\n    name: Documentation\n    type: Documentation\n    description: Official Dapr documentation covering all building blocks, operations, and SDKs.\n  - url: https://docs.dapr.io/getting-started/\n    name: Getting Started\n    type: Getting Started\n    description: Guides for getting started with Dapr including installation and\
  \ quickstarts.\n  - url: https://blog.dapr.io/\n    name: Blog\n    type: Blog\n    description: Dapr project blog with release announcements and technical articles.\n  - url: https://github.com/dapr\n    name: GitHub Organization\n    type: GitHub Organization\n    description: Dapr GitHub organization containing all project repositories.\n  - url: https://github.com/dapr/dapr\n    name: GitHub Repository\n    type: GitHubRepository\n    description: Main Dapr runtime source code repository.\n  - url: https://docs.dapr.io/sdks/\n    name: SDKs\n    type: SDKs\n    description: Dapr SDK implementations for Go, Python, Java, .NET, JavaScript, PHP, and Rust.\n  - url: https://discord.gg/ptHhX6jc34\n    name: Discord\n    type: Community\n    description: Dapr community Discord server for discussions, support, and announcements.\n  - url: https://github.com/dapr/dapr/blob/master/CHANGELOG.md\n    name: Change Log\n    type: Change Log\n    description: Release notes and version history for\
  \ the Dapr runtime.\n  - url: https://github.com/dapr/dapr/security/policy\n    name: Security\n    type: Security\n    description: Security disclosure policy for the Dapr project.\n  - url: https://stackoverflow.com/questions/tagged/dapr\n    name: Stack Overflow\n    type: Stack Overflow\n    description: Dapr-tagged questions and answers on Stack Overflow.\n  - url: json-ld/dapr-context.jsonld\n    name: JSON-LD Context\n    type: JSON-LD\n    description: JSON-LD context file for Dapr API data models.\n  - url: vocabulary/dapr-vocabulary.yml\n    name: Vocabulary\n    type: Vocabulary\n    description: Shared vocabulary across Dapr building blocks.\n  - url: rules/dapr-rules.yml\n    name: Rules\n    type: Rules\n    description: Spectral rules for validating Dapr OpenAPI definitions.\n  - url: capabilities/dapr-capabilities.yml\n    name: Capabilities\n    type: Capabilities\n    description: Capability summary across Dapr building block APIs.\ncreated: '2025-01-08'\nmodified: '2026-04-28'\n\
  xType: opensource\nposition: Consumer\ndescription: >-\n  Dapr (Distributed Application Runtime) is a portable, event-driven runtime\n  that makes it easy for developers to build resilient, stateless, and stateful\n  applications that run on the cloud and edge. It provides building block APIs\n  for state management, pub/sub messaging, service invocation, bindings,\n  actors, workflows, secrets, configuration, distributed locks, cryptography,\n  jobs scheduling, health checks, and metadata.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/apis.yml
tags:
- Distributed Systems
- Microservices
- Platform
- Pub/Sub
- State Management
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/apis.yml
use_cases: []
---
