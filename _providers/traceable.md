---
api_count: 3
api_specs:
- filename: traceable-platform-openapi.yml
  format: yaml
  label: Traceable Platform GraphQL API
  slug: traceable-platform-graphql
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/traceable/refs/heads/main/openapi/traceable-platform-openapi.yml
apis:
- description: The Traceable Platform GraphQL API provides programmatic access to API security configuration and operational data. Supports queries for API discovery analytics, vulnerability data, threat activity, e
  name: Traceable Platform GraphQL API
  slug: traceable-platform-graphql
- description: Traceable provides an intelligent API security platform offering API discovery, threat detection and protection, and API security testing. It uses distributed tracing and context-aware AI to understan
  name: Traceable API Security Platform
  slug: traceable-platform
- description: Traceable Active Security Testing (AST) provides automated API security testing with GraphQL-based configuration for scan creation, suite management, and CI/CD pipeline integration. Supports GitHub Ac
  name: Traceable Active Security Testing
  slug: traceable-ast
capabilities:
- description: Unified API security operations workflow combining API discovery analytics, vulnerability management, threat activity monitoring, and security testing. Used by security engineers and SOC analysts to m
  name: Traceable API Security Operations
  slug: api-security-operations
common:
- title: ''
  type: Website
  url: https://www.traceable.ai
- title: ''
  type: Documentation
  url: https://docs.traceable.ai
- title: ''
  type: Blog
  url: https://www.traceable.ai/blog
- title: ''
  type: About
  url: https://www.traceable.ai/company
- title: ''
  type: Contact
  url: https://www.traceable.ai/contact
- title: ''
  type: Demo
  url: https://www.traceable.ai/request-demo
- title: ''
  type: Partners
  url: https://www.traceable.ai/partners
- title: ''
  type: Resources
  url: https://www.traceable.ai/resources
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/traboraceable/
- title: ''
  type: Twitter
  url: https://twitter.com/ATraceableAI
- title: ''
  type: GitHub
  url: https://github.com/Traceableai
- title: ''
  type: MCPServer
  url: https://docs.traceable.ai/docs/traceable-mcp-server
created: '2025-01-08'
description: Traceable is an API security and observability platform that provides API discovery, threat detection, and protection across the full application lifecycle. It uses context-aware AI to detect and block API-based attacks while providing deep visibility into API behavior and risk. Traceable exposes public GraphQL APIs for configuration, analytics, and operational data access, as well as an MCP server with 12 tools for AI-assisted security workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 33
  name: Traceable Context
  property_count: 0
  slug: traceable-context
layout: provider
modified: '2026-05-03'
name: Traceable
rules:
- name: Traceable API Rules
  rule_count: 10
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 5
  slug: traceable-rules
skills: []
slug: traceable
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: traceable\nname: Traceable\ndescription: >-\n  Traceable is an API security and observability platform that provides API\n  discovery, threat detection, and protection across the full application\n  lifecycle. It uses context-aware AI to detect and block API-based attacks\n  while providing deep visibility into API behavior and risk. Traceable exposes\n  public GraphQL APIs for configuration, analytics, and operational data access,\n  as well as an MCP server with 12 tools for AI-assisted security workflows.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Discovery\n  - API Protection\n  - API Security\n  - API Testing\n  - Observability\n  - Security\n  - Threat Detection\ncreated: '2025-01-08'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/traceable/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: traceable:traceable-platform-graphql\n\
  \    name: Traceable Platform GraphQL API\n    description: >-\n      The Traceable Platform GraphQL API provides programmatic access to API\n      security configuration and operational data. Supports queries for API\n      discovery analytics, vulnerability data, threat activity, entity scoping,\n      and API test suite management. Authentication uses a platform API token\n      passed in the Authorization header.\n    humanURL: https://docs.traceable.ai/docs/public-apis\n    baseURL: https://api.traceable.ai\n    tags:\n      - API Discovery\n      - API Security\n      - GraphQL\n      - Threat Detection\n      - Vulnerability Management\n    properties:\n      - type: Documentation\n        url: https://docs.traceable.ai/docs/public-apis\n      - type: OpenAPI\n        url: openapi/traceable-platform-openapi.yml\n      - type: JSONSchema\n        url: json-schema/traceable-api-entity-schema.json\n      - type: JSONStructure\n        url: json-structure/traceable-api-entity-structure.json\n\
  \      - type: JSONLd\n        url: json-ld/traceable-context.jsonld\n      - type: SpectralRules\n        url: rules/traceable-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/api-security-operations.yaml\n      - type: Vocabulary\n        url: vocabulary/traceable-vocabulary.yml\n      - type: GraphQL\n        url: https://api.traceable.ai/graphql\n      - type: APISpecDownload\n        url: https://docs.traceable.ai/docs/download-api-spec\n  - aid: traceable:traceable-platform\n    name: Traceable API Security Platform\n    description: >-\n      Traceable provides an intelligent API security platform offering API\n      discovery, threat detection and protection, and API security testing. It\n      uses distributed tracing and context-aware AI to understand API behavior,\n      detect threats, and protect APIs across the full application lifecycle.\n      The platform supports REST, SOAP, gRPC, GraphQL, and WebSocket APIs.\n    humanURL: https://www.traceable.ai\n\
  \    tags:\n      - API Discovery\n      - API Security\n      - API Testing\n      - Observability\n      - Threat Detection\n    properties:\n      - type: Documentation\n        url: https://docs.traceable.ai\n      - type: APIDiscovery\n        url: https://www.traceable.ai/product/api-discovery\n      - type: ThreatDetection\n        url: https://www.traceable.ai/product/threat-detection\n      - type: APISecurityTesting\n        url: https://www.traceable.ai/product/api-security-testing\n      - type: MCPServer\n        url: https://docs.traceable.ai/docs/traceable-mcp-server\n  - aid: traceable:traceable-ast\n    name: Traceable Active Security Testing\n    description: >-\n      Traceable Active Security Testing (AST) provides automated API security\n      testing with GraphQL-based configuration for scan creation, suite\n      management, and CI/CD pipeline integration. Supports GitHub Actions,\n      GitLab CI, and Jenkins integrations.\n    humanURL: https://docs.traceable.ai/docs/en/ast-getting-started\n\
  \    tags:\n      - API Security Testing\n      - CI/CD\n      - DAST\n      - Security Automation\n    properties:\n      - type: Documentation\n        url: https://docs.traceable.ai/docs/en/ast-getting-started\n      - type: GitHubAction\n        url: https://github.com/Traceableai/ast-action\n      - type: JenkinsPlugin\n        url: https://github.com/Traceableai/traceable-xast-jenkins-plugin\n      - type: GraphQLScanAPI\n        url: https://docs.traceable.ai/docs/scans-using-graphql-api\n      - type: GraphQLSuiteAPI\n        url: https://docs.traceable.ai/docs/suites-using-graphql-api\ncommon:\n  - type: Website\n    url: https://www.traceable.ai\n  - type: Documentation\n    url: https://docs.traceable.ai\n  - type: Blog\n    url: https://www.traceable.ai/blog\n  - type: About\n    url: https://www.traceable.ai/company\n  - type: Contact\n    url: https://www.traceable.ai/contact\n  - type: Demo\n    url: https://www.traceable.ai/request-demo\n  - type: Partners\n    url: https://www.traceable.ai/partners\n\
  \  - type: Resources\n    url: https://www.traceable.ai/resources\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/traboraceable/\n  - type: Twitter\n    url: https://twitter.com/ATraceableAI\n  - type: GitHub\n    url: https://github.com/Traceableai\n  - type: MCPServer\n    url: https://docs.traceable.ai/docs/traceable-mcp-server\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/traceable/refs/heads/main/apis.yml
tags:
- API Discovery
- API Protection
- API Security
- API Testing
- Observability
- Security
- Threat Detection
url: https://raw.githubusercontent.com/api-evangelist/traceable/refs/heads/main/apis.yml
use_cases: []
---
