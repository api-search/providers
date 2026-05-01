---
api_count: 3
api_specs:
- filename: falco-openapi.yml
  format: yaml
  label: Falco HTTP API
  slug: falco-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/falco/refs/heads/main/openapi/falco-openapi.yml
apis:
- description: REST API served by the Falco web server providing health checks, version information, and rules management endpoints for the Falco runtime security engine.
  name: Falco HTTP API
  slug: falco-http-api
- description: The Falco Plugin API provides a C ABI interface for developing plugins that extend Falco with new event sources and field extractors. Plugins are shared libraries that implement the plugin API and can
  name: Falco Plugin API
  slug: falco-plugin-api
- description: The Falco gRPC API provided a streaming interface for consuming Falco alert outputs and querying version information from a running Falco instance. The embedded gRPC server and gRPC Output have been d
  name: Falco gRPC API
  slug: falco-grpc-api
common:
- title: ''
  type: Website
  url: https://falco.org
- title: ''
  type: Documentation
  url: https://falco.org/docs/
- title: ''
  type: Blog
  url: https://falco.org/blog/
- title: ''
  type: Community
  url: https://falco.org/community/
- title: ''
  type: Getting Started
  url: https://falco.org/docs/getting-started/
- title: ''
  type: Change Log
  url: https://falco.org/docs/reference/changelog/
- title: ''
  type: GitHub Organization
  url: https://github.com/falcosecurity
- title: ''
  type: GitHubRepository
  url: https://github.com/falcosecurity/falco
- title: ''
  type: JSON-LD
  url: json-ld/falco-context.jsonld
created: '2025-01-01'
description: Falco is a cloud-native runtime security tool that detects unexpected application behavior and alerts on threats at runtime using eBPF. It is a CNCF graduated project that continuously monitors Linux kernel syscalls and compares them against configurable security rules to detect intrusions, privilege escalation, and other suspicious behaviors.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Falco Context
  property_count: 28
  slug: falco-context
layout: provider
modified: '2026-04-28'
name: Falco
skills: []
slug: falco
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: falco\nname: Falco\ndescription: >-\n  Falco is a cloud-native runtime security tool that detects unexpected\n  application behavior and alerts on threats at runtime using eBPF. It is a\n  CNCF graduated project that continuously monitors Linux kernel syscalls and\n  compares them against configurable security rules to detect intrusions,\n  privilege escalation, and other suspicious behaviors.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - eBPF\n  - Runtime Security\n  - Security\n  - Threat Detection\nurl: https://falco.org\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nposition: Consumer\naccess: 3rd-Party\nspecificationVersion: '0.19'\napis:\n  - aid: falco:falco-http-api\n    name: Falco HTTP API\n    description: >-\n      REST API served by the Falco web server providing health checks, version\n      information, and rules management endpoints for the Falco runtime security\n      engine.\n\
  \    humanURL: https://falco.org/docs/\n    tags:\n      - Health Check\n      - Runtime Security\n      - Security\n    properties:\n      - type: Documentation\n        url: https://falco.org/docs/\n      - type: Reference\n        url: https://falco.org/docs/reference/\n      - type: OpenAPI\n        url: openapi/falco-openapi.yml\n      - type: JSONSchema\n        url: json-schema/falco-alert-output.json\n      - type: JSONSchema\n        url: json-schema/falco-rules.json\n      - type: GitHubRepository\n        url: https://github.com/falcosecurity/falco\n  - aid: falco:falco-plugin-api\n    name: Falco Plugin API\n    description: >-\n      The Falco Plugin API provides a C ABI interface for developing plugins\n      that extend Falco with new event sources and field extractors. Plugins\n      are shared libraries that implement the plugin API and can be loaded at\n      runtime to add support for new data sources such as cloud audit logs,\n      container activity, and custom event\
  \ streams.\n    humanURL: https://falco.org/docs/reference/plugins/plugin-api-reference/\n    tags:\n      - Developer Tools\n      - Event Sources\n      - Plugin\n    properties:\n      - type: Documentation\n        url: https://falco.org/docs/developer-guide/\n      - type: Reference\n        url: https://falco.org/docs/reference/plugins/plugin-api-reference/\n      - type: GitHubRepository\n        url: https://github.com/falcosecurity/plugin-sdk-go\n  - aid: falco:falco-grpc-api\n    name: Falco gRPC API\n    description: >-\n      The Falco gRPC API provided a streaming interface for consuming Falco\n      alert outputs and querying version information from a running Falco\n      instance. The embedded gRPC server and gRPC Output have been deprecated\n      in Falco 0.43.0 and will be removed in a future release.\n    humanURL: https://falco.org/docs/developer-guide/grpc/\n    tags:\n      - Deprecated\n      - gRPC\n      - Security\n    properties:\n      - type: Documentation\n\
  \        url: https://falco.org/docs/developer-guide/grpc/\n      - type: Deprecation Notice\n        url: https://falco.org/blog/falco-0-43-0/\n      - type: GitHubRepository\n        url: https://github.com/falcosecurity/falco\ncommon:\n  - type: Website\n    url: https://falco.org\n  - type: Documentation\n    url: https://falco.org/docs/\n  - type: Blog\n    url: https://falco.org/blog/\n  - type: Community\n    url: https://falco.org/community/\n  - type: Getting Started\n    url: https://falco.org/docs/getting-started/\n  - type: Change Log\n    url: https://falco.org/docs/reference/changelog/\n  - type: GitHub Organization\n    url: https://github.com/falcosecurity\n  - type: GitHubRepository\n    url: https://github.com/falcosecurity/falco\n  - type: JSON-LD\n    url: json-ld/falco-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/falco/refs/heads/main/apis.yml
tags:
- Cloud Native
- eBPF
- Runtime Security
- Security
- Threat Detection
url: https://falco.org
use_cases: []
---
