---
api_count: 6
api_specs:
- filename: cribl-cloud-api-openapi.yml
  format: yaml
  label: Cribl Cloud API
  slug: cribl-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/openapi/cribl-cloud-api-openapi.yml
- filename: cribl-stream-api-openapi.yml
  format: yaml
  label: Cribl Stream API
  slug: cribl-stream-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/openapi/cribl-stream-api-openapi.yml
- filename: cribl-edge-api-openapi.yml
  format: yaml
  label: Cribl Edge API
  slug: cribl-edge-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/openapi/cribl-edge-api-openapi.yml
- filename: cribl-search-api-openapi.yml
  format: yaml
  label: Cribl Search API
  slug: cribl-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/openapi/cribl-search-api-openapi.yml
- filename: cribl-lake-api-openapi.yml
  format: yaml
  label: Cribl Lake API
  slug: cribl-lake-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/openapi/cribl-lake-api-openapi.yml
- filename: cribl-as-code-api-openapi.yml
  format: yaml
  label: Cribl As Code API
  slug: cribl-as-code-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/openapi/cribl-as-code-api-openapi.yml
apis:
- description: The Cribl Cloud API is a RESTful control plane API for programmatically configuring and managing Cribl resources across Stream, Edge, Search, and Lake deployments. It allows developers to retrieve and
  name: Cribl Cloud API
  slug: cribl-cloud-api
- description: The Cribl Stream API provides programmatic access to Cribl Stream, an observability pipeline platform that processes and routes telemetry data in real time. Through the API, developers can manage pipe
  name: Cribl Stream API
  slug: cribl-stream-api
- description: The Cribl Edge API provides programmatic access to Cribl Edge, which extends Stream capabilities to the network edge by deploying lightweight agents on endpoints. The API allows developers to manage e
  name: Cribl Edge API
  slug: cribl-edge-api
- description: 'The Cribl Search API provides programmatic access to Cribl Search, a tool for exploring and querying both live and stored observability data in real time. Developers can use the API to execute search '
  name: Cribl Search API
  slug: cribl-search-api
- description: The Cribl Lake API provides programmatic access to Cribl Lake, a data lake solution purpose-built for observability and security data. The API enables developers to manage data storage, retention poli
  name: Cribl Lake API
  slug: cribl-lake-api
- description: The Cribl As Code API enables developers to manage Cribl configurations programmatically using infrastructure-as-code principles. It supports exporting and importing configurations across deployments,
  name: Cribl As Code API
  slug: cribl-as-code-api
capabilities: []
common:
- title: ''
  type: JSONLD
  url: json-ld/cribl-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cribl-pipeline-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cribl-route-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cribl-source-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cribl-destination-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cribl-worker-group-schema.json
- title: ''
  type: Website
  url: https://cribl.io/
- title: ''
  type: Documentation
  url: https://docs.cribl.io/
- title: ''
  type: Portal
  url: https://docs.cribl.io/
- title: ''
  type: Login
  url: https://login.cribl.cloud/
- title: ''
  type: Blog
  url: https://cribl.io/blog/
- title: ''
  type: PrivacyPolicy
  url: https://cribl.io/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://cribl.io/terms-of-service/
created: '2025-03-05'
description: Cribl is an observability pipeline company providing a suite of products for collecting, processing, routing, searching, and storing telemetry data at scale. Cribl's developer platform offers REST APIs across Stream, Edge, Search, Lake, and the As Code product line, exposing programmatic control over data pipelines, edge agents, federated search jobs, lake datasets, and infrastructure-as-code configuration management. The Cribl Cloud API acts as a centrally managed control plane across all deployments and authenticates with OAuth 2.0 client credentials.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cribl Context
  property_count: 11
  slug: cribl-context
layout: provider
modified: '2026-04-28'
name: Cribl
rules:
- name: Cribl API Rules
  rule_count: 6
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 1
  slug: cribl-as-code-api-rules
- name: Cribl API Rules
  rule_count: 6
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 1
  slug: cribl-cloud-api-rules
- name: Cribl API Rules
  rule_count: 5
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 0
  slug: cribl-edge-api-rules
- name: Cribl API Rules
  rule_count: 5
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 0
  slug: cribl-lake-api-rules
- name: Cribl API Rules
  rule_count: 5
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 0
  slug: cribl-search-api-rules
- name: Cribl API Rules
  rule_count: 5
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 0
  slug: cribl-stream-api-rules
skills: []
slug: cribl
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cribl\nname: Cribl\nx-type: company\ndescription: >-\n  Cribl is an observability pipeline company providing a suite of products\n  for collecting, processing, routing, searching, and storing telemetry\n  data at scale. Cribl's developer platform offers REST APIs across Stream,\n  Edge, Search, Lake, and the As Code product line, exposing programmatic\n  control over data pipelines, edge agents, federated search jobs, lake\n  datasets, and infrastructure-as-code configuration management. The Cribl\n  Cloud API acts as a centrally managed control plane across all\n  deployments and authenticates with OAuth 2.0 client credentials.\nurl: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Configuration\n  - Data Lake\n  - Data Pipelines\n  - Data Routing\n  - Edge Computing\n  - Infrastructure as Code\n  - Observability\n  - Search\n  - Security Data\n\
  \  - Stream Processing\n  - Telemetry\ncreated: '2025-03-05'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntype: Index\naccess: 3rd-Party\nposition: Consuming\napis:\n  - aid: cribl:cribl-cloud-api\n    name: Cribl Cloud API\n    description: >-\n      The Cribl Cloud API is a RESTful control plane API for programmatically\n      configuring and managing Cribl resources across Stream, Edge, Search,\n      and Lake deployments. It allows developers to retrieve and manage\n      data, automate repetitive manual processes, and integrate with\n      third-party applications. The API uses OAuth 2.0 client credentials\n      and follows a resource-based structure where each endpoint\n      corresponds to a specific Cribl resource or collection.\n    humanURL: https://docs.cribl.io/api-reference/\n    baseURL: https://api.cribl.cloud\n    properties:\n      - type: Documentation\n        url: https://docs.cribl.io/api-reference/\n      - type: OpenAPI\n        url: openapi/cribl-cloud-api-openapi.yml\n\
  \      - type: Rules\n        url: rules/cribl-cloud-api-rules.yml\n      - type: Capabilities\n        url: capabilities/cribl-cloud-api-capabilities.yml\n    tags:\n      - Cloud\n      - Configuration\n      - Control Plane\n      - Data Pipelines\n      - Management\n      - Observability\n  - aid: cribl:cribl-stream-api\n    name: Cribl Stream API\n    description: >-\n      The Cribl Stream API provides programmatic access to Cribl Stream, an\n      observability pipeline platform that processes and routes telemetry\n      data in real time. Through the API, developers can manage pipelines,\n      routes, sources, destinations, and worker groups. It enables\n      automation of data collection, transformation, and routing\n      workflows.\n    humanURL: https://docs.cribl.io/stream/\n    baseURL: https://api.example.com\n    properties:\n      - type: Documentation\n        url: https://docs.cribl.io/stream/\n      - type: OpenAPI\n        url: openapi/cribl-stream-api-openapi.yml\n\
  \      - type: Rules\n        url: rules/cribl-stream-api-rules.yml\n      - type: Capabilities\n        url: capabilities/cribl-stream-api-capabilities.yml\n    tags:\n      - Data Pipelines\n      - Observability\n      - Routing\n      - Stream Processing\n      - Telemetry\n  - aid: cribl:cribl-edge-api\n    name: Cribl Edge API\n    description: >-\n      The Cribl Edge API provides programmatic access to Cribl Edge, which\n      extends Stream capabilities to the network edge by deploying\n      lightweight agents on endpoints. The API allows developers to manage\n      edge fleets, configure data collection from endpoints, and control\n      data processing closer to the source.\n    humanURL: https://docs.cribl.io/edge/\n    baseURL: https://api.example.com\n    properties:\n      - type: Documentation\n        url: https://docs.cribl.io/edge/\n      - type: OpenAPI\n        url: openapi/cribl-edge-api-openapi.yml\n      - type: Rules\n        url: rules/cribl-edge-api-rules.yml\n\
  \      - type: Capabilities\n        url: capabilities/cribl-edge-api-capabilities.yml\n    tags:\n      - Agents\n      - Data Collection\n      - Edge Computing\n      - Observability\n      - Telemetry\n  - aid: cribl:cribl-search-api\n    name: Cribl Search API\n    description: >-\n      The Cribl Search API provides programmatic access to Cribl Search, a\n      tool for exploring and querying both live and stored observability\n      data in real time. Developers can use the API to execute search\n      queries, retrieve results, and integrate search capabilities into\n      their own applications and workflows.\n    humanURL: https://docs.cribl.io/search/\n    baseURL: https://api.example.com\n    properties:\n      - type: Documentation\n        url: https://docs.cribl.io/search/\n      - type: OpenAPI\n        url: openapi/cribl-search-api-openapi.yml\n      - type: Rules\n        url: rules/cribl-search-api-rules.yml\n      - type: Capabilities\n        url: capabilities/cribl-search-api-capabilities.yml\n\
  \    tags:\n      - Analytics\n      - Data Exploration\n      - Federated Search\n      - Observability\n      - Querying\n  - aid: cribl:cribl-lake-api\n    name: Cribl Lake API\n    description: >-\n      The Cribl Lake API provides programmatic access to Cribl Lake, a data\n      lake solution purpose-built for observability and security data. The\n      API enables developers to manage data storage, retention policies,\n      and access controls for large volumes of telemetry data in open\n      formats.\n    humanURL: https://docs.cribl.io/lake/\n    baseURL: https://api.example.com\n    properties:\n      - type: Documentation\n        url: https://docs.cribl.io/lake/\n      - type: OpenAPI\n        url: openapi/cribl-lake-api-openapi.yml\n      - type: Rules\n        url: rules/cribl-lake-api-rules.yml\n      - type: Capabilities\n        url: capabilities/cribl-lake-api-capabilities.yml\n    tags:\n      - Analytics\n      - Data Lake\n      - Data Management\n      - Observability\n\
  \      - Storage\n  - aid: cribl:cribl-as-code-api\n    name: Cribl As Code API\n    description: >-\n      The Cribl As Code API enables developers to manage Cribl\n      configurations programmatically using infrastructure-as-code\n      principles. It supports exporting and importing configurations\n      across deployments, enabling version control, CI/CD integration,\n      and reproducible infrastructure management. Developers can use the\n      API alongside SDKs for Python, Go, and TypeScript or through\n      Terraform providers.\n    humanURL: https://docs.cribl.io/cribl-as-code/api/\n    baseURL: https://gateway.cribl.cloud\n    properties:\n      - type: Documentation\n        url: https://docs.cribl.io/cribl-as-code/api/\n      - type: OpenAPI\n        url: openapi/cribl-as-code-api-openapi.yml\n      - type: Rules\n        url: rules/cribl-as-code-api-rules.yml\n      - type: Capabilities\n        url: capabilities/cribl-as-code-api-capabilities.yml\n    tags:\n      - Automation\n\
  \      - Configuration\n      - DevOps\n      - Infrastructure as Code\n      - Version Control\ncommon:\n  - type: JSONLD\n    url: json-ld/cribl-context.jsonld\n  - type: JSONSchema\n    url: json-schema/cribl-pipeline-schema.json\n  - type: JSONSchema\n    url: json-schema/cribl-route-schema.json\n  - type: JSONSchema\n    url: json-schema/cribl-source-schema.json\n  - type: JSONSchema\n    url: json-schema/cribl-destination-schema.json\n  - type: JSONSchema\n    url: json-schema/cribl-worker-group-schema.json\n  - type: Website\n    url: https://cribl.io/\n  - type: Documentation\n    url: https://docs.cribl.io/\n  - type: Portal\n    url: https://docs.cribl.io/\n  - type: Login\n    url: https://login.cribl.cloud/\n  - type: Blog\n    url: https://cribl.io/blog/\n  - type: PrivacyPolicy\n    url: https://cribl.io/privacy-policy/\n  - type: TermsOfService\n    url: https://cribl.io/terms-of-service/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/apis.yml
tags:
- Configuration
- Data Lake
- Data Pipelines
- Data Routing
- Edge Computing
- Infrastructure as Code
- Observability
- Search
- Security Data
- Stream Processing
- Telemetry
url: https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/apis.yml
use_cases: []
---
