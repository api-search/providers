---
api_count: 4
api_specs:
- filename: nomad-http-api-openapi.yml
  format: yaml
  label: HashiCorp Nomad HTTP API
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomad/refs/heads/main/openapi/nomad-http-api-openapi.yml
apis:
- description: The HashiCorp Nomad HTTP API provides programmatic access to all Nomad functionality including job scheduling, allocation management, node operations, deployments, services, evaluations, namespaces, A
  name: HashiCorp Nomad HTTP API
  slug: http-api
- description: The HashiCorp Nomad Go SDK is the official Go client library for interacting with the Nomad HTTP API. It provides a high-level, idiomatic Go interface for managing jobs, allocations, nodes, deployment
  name: HashiCorp Nomad Go SDK
  slug: go-sdk
- description: The python-nomad library is a Python client for the HashiCorp Nomad HTTP API. It provides Pythonic access to Nomad resources including jobs, nodes, allocations, deployments, evaluations, namespaces, a
  name: HashiCorp Nomad Python SDK
  slug: python-sdk
- description: The Nomad Java SDK is an official Java client library for the HashiCorp Nomad HTTP API. It enables Java and JVM-based applications to interact with Nomad clusters for submitting jobs, querying allocat
  name: HashiCorp Nomad Java SDK
  slug: java-sdk
asyncapis:
- description: The Nomad Event Stream provides a way to subscribe to Job, Allocation, Evaluation, Deployment, Node, Node Pool, and Service changes in near real time. The /v1/event/stream endpoint streams events as n
  name: HashiCorp Nomad Event Stream
  slug: nomad-event-stream-asyncapi
common:
- title: ''
  type: Portal
  url: https://developer.hashicorp.com/nomad
- title: ''
  type: Documentation
  url: https://developer.hashicorp.com/nomad/docs
- title: ''
  type: Website
  url: https://www.nomadproject.io/
- title: ''
  type: PrivacyPolicy
  url: https://www.hashicorp.com/privacy
- title: ''
  type: TermsOfService
  url: https://www.hashicorp.com/terms-of-service
- title: ''
  type: Support
  url: https://support.hashicorp.com/
- title: ''
  type: Blog
  url: https://www.hashicorp.com/blog
- title: ''
  type: Login
  url: https://portal.cloud.hashicorp.com/sign-in
- title: ''
  type: JSON-LD
  url: json-ld/nomad-context.jsonld
created: '2026-03-20'
description: HashiCorp Nomad is a flexible workload orchestrator that enables organizations to deploy and manage containers, legacy applications, and batch jobs across any infrastructure. The Nomad developer platform provides a comprehensive HTTP API, official SDKs, and tooling for automating job scheduling, cluster management, and service orchestration at scale.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Nomad Context
  property_count: 13
  slug: nomad-context
layout: provider
modified: '2026-04-28'
name: HashiCorp Nomad
skills: []
slug: nomad
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: nomad\nname: HashiCorp Nomad\ndescription: >-\n  HashiCorp Nomad is a flexible workload orchestrator that enables organizations\n  to deploy and manage containers, legacy applications, and batch jobs across\n  any infrastructure. The Nomad developer platform provides a comprehensive HTTP\n  API, official SDKs, and tooling for automating job scheduling, cluster\n  management, and service orchestration at scale.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/nomad/refs/heads/main/apis.yml\ncreated: '2026-03-20'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Workload Orchestration\n  - Container Orchestration\n  - Scheduling\n  - Infrastructure\n  - DevOps\napis:\n  - aid: nomad:http-api\n    name: HashiCorp Nomad HTTP API\n    description: >-\n      The HashiCorp Nomad HTTP API provides programmatic access to all Nomad\n      functionality including job scheduling,\
  \ allocation management, node\n      operations, deployments, services, evaluations, namespaces, ACL policies,\n      and cluster status. All API routes are prefixed with /v1/ and the default\n      port is 4646. The API is RESTful, responds to standard HTTP verbs, and\n      supports ACL token authentication via the X-Nomad-Token header or Bearer\n      scheme. Developers can use this API to submit and manage workloads,\n      monitor cluster health, query allocation status, and integrate Nomad\n      orchestration into their infrastructure automation workflows.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.hashicorp.com/nomad/api-docs\n    baseURL: http://localhost:4646\n    tags:\n      - Workload Orchestration\n      - Container Orchestration\n      - Scheduling\n      - Infrastructure\n      - DevOps\n      - Cloud\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/nomad/api-docs\n\
  \      - type: OpenAPI\n        url: openapi/nomad-http-api-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/nomad-event-stream-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/nomad-job-schema.json\n  - aid: nomad:go-sdk\n    name: HashiCorp Nomad Go SDK\n    description: >-\n      The HashiCorp Nomad Go SDK is the official Go client library for\n      interacting with the Nomad HTTP API. It provides a high-level, idiomatic\n      Go interface for managing jobs, allocations, nodes, deployments,\n      evaluations, and other Nomad resources. The SDK is maintained by\n      HashiCorp as part of the main Nomad repository and is used internally by\n      the Nomad CLI itself, making it the most comprehensive and up-to-date\n      client available.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://pkg.go.dev/github.com/hashicorp/nomad/api\n    tags:\n      - Workload Orchestration\n      - Go\n      - SDK\n\
  \      - DevOps\n    properties:\n      - type: Documentation\n        url: https://pkg.go.dev/github.com/hashicorp/nomad/api\n  - aid: nomad:python-sdk\n    name: HashiCorp Nomad Python SDK\n    description: >-\n      The python-nomad library is a Python client for the HashiCorp Nomad HTTP\n      API. It provides Pythonic access to Nomad resources including jobs,\n      nodes, allocations, deployments, evaluations, namespaces, and ACL\n      management. The library supports configuration via environment variables\n      such as NOMAD_ADDR, NOMAD_TOKEN, and NOMAD_NAMESPACE for consistency with\n      the Nomad CLI and other ecosystem tools.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/jrxFive/python-nomad\n    tags:\n      - Workload Orchestration\n      - Python\n      - SDK\n      - DevOps\n    properties:\n      - type: Documentation\n        url: https://github.com/jrxFive/python-nomad\n  - aid: nomad:java-sdk\n\
  \    name: HashiCorp Nomad Java SDK\n    description: >-\n      The Nomad Java SDK is an official Java client library for the HashiCorp\n      Nomad HTTP API. It enables Java and JVM-based applications to interact\n      with Nomad clusters for submitting jobs, querying allocations, managing\n      nodes, and performing other orchestration operations. The SDK provides a\n      typed Java interface over the Nomad REST API, making it suitable for\n      enterprise applications and microservice architectures running on the\n      JVM.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.hashicorp.com/nomad/api-docs/libraries-and-sdks\n    tags:\n      - Workload Orchestration\n      - Java\n      - SDK\n      - DevOps\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/nomad/api-docs/libraries-and-sdks\ncommon:\n  - type: Portal\n    url: https://developer.hashicorp.com/nomad\n  - type:\
  \ Documentation\n    url: https://developer.hashicorp.com/nomad/docs\n  - type: Website\n    url: https://www.nomadproject.io/\n  - type: PrivacyPolicy\n    url: https://www.hashicorp.com/privacy\n  - type: TermsOfService\n    url: https://www.hashicorp.com/terms-of-service\n  - type: Support\n    url: https://support.hashicorp.com/\n  - type: Blog\n    url: https://www.hashicorp.com/blog\n  - type: Login\n    url: https://portal.cloud.hashicorp.com/sign-in\n  - type: JSON-LD\n    url: json-ld/nomad-context.jsonld\nmaintainers:\n  - FN: API Evangelist\n    url: https://apievangelist.com\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nomad/refs/heads/main/apis.yml
tags:
- Workload Orchestration
- Container Orchestration
- Scheduling
- Infrastructure
- DevOps
url: https://raw.githubusercontent.com/api-evangelist/nomad/refs/heads/main/apis.yml
use_cases: []
---
