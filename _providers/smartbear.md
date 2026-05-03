---
api_count: 3
api_specs:
- filename: smartbear-swaggerhub-openapi.yml
  format: yaml
  label: SwaggerHub API
  slug: swaggerhub
  spec_type: OpenAPI
  url: https://openapi/smartbear-swaggerhub-openapi.yml
apis:
- description: The SwaggerHub API provides programmatic access to manage API definitions, domains, projects, and integrations on the SwaggerHub platform. It allows teams to automate API lifecycle management includin
  name: SwaggerHub API
  slug: swaggerhub
- description: ReadyAPI is SmartBear's API quality platform for functional, security, and performance testing. It supports RESTful, GraphQL, and other API standards, and is used by more than 250,000 users running mo
  name: ReadyAPI
  slug: readyapi
- description: PactFlow is SmartBear's contract testing platform that ensures API changes do not break consumer applications. It integrates with SwaggerHub for bi-directional contract testing and uses REST principle
  name: PactFlow
  slug: pactflow
capabilities:
- description: Unified workflow capability for API design, documentation, and governance using SmartBear's SwaggerHub platform. Supports API teams in discovering existing APIs, managing API definitions through their
  name: SmartBear API Design And Governance
  slug: api-design-and-governance
common:
- title: ''
  type: Website
  url: https://smartbear.com/
- title: ''
  type: DeveloperPortal
  url: https://developer.smartbear.com/
- title: ''
  type: Documentation
  url: https://support.smartbear.com/documentation/
- title: ''
  type: Community
  url: https://community.smartbear.com/
- title: ''
  type: Blog
  url: https://smartbear.com/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/SmartBear
- title: ''
  type: GitHubOrganization
  url: https://github.com/SmartBear-DevRel
- title: ''
  type: Pricing
  url: https://swagger.io/product/pricing/
- title: ''
  type: OpenAPI
  url: openapi/smartbear-swaggerhub-openapi.yml
- title: ''
  type: Spectral
  url: rules/smartbear-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/api-design-and-governance.yaml
- title: ''
  type: JSONSchema
  url: json-schema/smartbear-api-entry-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/smartbear-integration-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/smartbear-swaggerhub-structure.json
- title: ''
  type: JSONLD
  url: json-ld/smartbear-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/smartbear-vocabulary.yml
created: '2025-01-08'
description: SmartBear is a software company that provides AI-powered tools for API lifecycle management including design, testing, documentation, and governance. Their product portfolio includes SwaggerHub for API design and documentation, ReadyAPI for API testing, PactFlow for contract testing, and other tools for software quality and performance. SmartBear's developer API enables programmatic access to manage API definitions, automate lifecycle workflows, and integrate SwaggerHub with CI/CD pipelines and third-party services.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 15
  name: Smartbear Context
  property_count: 7
  slug: smartbear-context
layout: provider
modified: '2026-05-02'
name: SmartBear
rules:
- name: SmartBear API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: smartbear-rules
skills: []
slug: smartbear
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: smartbear\nname: SmartBear\ndescription: >-\n  SmartBear is a software company that provides AI-powered tools for API\n  lifecycle management including design, testing, documentation, and governance.\n  Their product portfolio includes SwaggerHub for API design and documentation,\n  ReadyAPI for API testing, PactFlow for contract testing, and other tools\n  for software quality and performance. SmartBear's developer API enables\n  programmatic access to manage API definitions, automate lifecycle workflows,\n  and integrate SwaggerHub with CI/CD pipelines and third-party services.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/smartbear/refs/heads/main/apis.yml\ncreated: '2025-01-08'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - API Design\n  - API Documentation\n  - API Testing\n  - Contract Testing\n  - Governance\n  - Monitoring\n  - Platform\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  access: 3rd-Party\nposition: Consuming\napis:\n  - aid: smartbear:swaggerhub\n    name: SwaggerHub API\n    tags:\n      - API Design\n      - API Documentation\n      - Collaboration\n      - OpenAPI\n      - Governance\n    humanURL: https://swagger.io/product/\n    properties:\n      - url: https://support.smartbear.com/swaggerhub/docs/en/index.html\n        type: Documentation\n      - url: https://swagger.io/product/pricing/\n        type: Pricing\n      - url: https://github.com/SmartBear/swaggerhub-cli\n        type: GitHubRepository\n      - url: https://openapi/smartbear-swaggerhub-openapi.yml\n        type: OpenAPI\n    description: >-\n      The SwaggerHub API provides programmatic access to manage API definitions,\n      domains, projects, and integrations on the SwaggerHub platform. It allows\n      teams to automate API lifecycle management including creating, updating,\n      publishing, and versioning APIs. Base URL: https://api.swaggerhub.com.\n      Authentication via\
  \ API key in the Authorization header.\n  - aid: smartbear:readyapi\n    name: ReadyAPI\n    tags:\n      - API Testing\n      - Performance Testing\n      - Security Testing\n      - Functional Testing\n    humanURL: https://smartbear.com/product/ready-api/overview/\n    properties:\n      - url: https://support.smartbear.com/readyapi/docs/\n        type: Documentation\n      - url: https://github.com/SmartBear/readyapi4j\n        type: GitHubRepository\n    description: >-\n      ReadyAPI is SmartBear's API quality platform for functional, security,\n      and performance testing. It supports RESTful, GraphQL, and other API\n      standards, and is used by more than 250,000 users running more than 2\n      million tests per month.\n  - aid: smartbear:pactflow\n    name: PactFlow\n    tags:\n      - API Testing\n      - CI/CD\n      - Contract Testing\n      - Consumer-Driven Contracts\n    humanURL: https://pactflow.io/\n    properties:\n      - url: https://docs.pactflow.io/\n     \
  \   type: Documentation\n      - url: https://developer.smartbear.com/pactflow/default/pactflow_saas_api\n        type: APIReference\n    description: >-\n      PactFlow is SmartBear's contract testing platform that ensures API\n      changes do not break consumer applications. It integrates with SwaggerHub\n      for bi-directional contract testing and uses REST principles with\n      predictable resource-oriented URLs. Base URL: https://{account}.pactflow.io.\ncommon:\n  - type: Website\n    url: https://smartbear.com/\n  - type: DeveloperPortal\n    url: https://developer.smartbear.com/\n  - type: Documentation\n    url: https://support.smartbear.com/documentation/\n  - type: Community\n    url: https://community.smartbear.com/\n  - type: Blog\n    url: https://smartbear.com/blog/\n  - type: GitHubOrganization\n    url: https://github.com/SmartBear\n  - type: GitHubOrganization\n    url: https://github.com/SmartBear-DevRel\n  - type: Pricing\n    url: https://swagger.io/product/pricing/\n\
  \  - type: OpenAPI\n    url: openapi/smartbear-swaggerhub-openapi.yml\n  - type: Spectral\n    url: rules/smartbear-rules.yml\n  - type: Capabilities\n    url: capabilities/api-design-and-governance.yaml\n  - type: JSONSchema\n    url: json-schema/smartbear-api-entry-schema.json\n  - type: JSONSchema\n    url: json-schema/smartbear-integration-schema.json\n  - type: JSONStructure\n    url: json-structure/smartbear-swaggerhub-structure.json\n  - type: JSONLD\n    url: json-ld/smartbear-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/smartbear-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/smartbear/refs/heads/main/apis.yml
tags:
- API Design
- API Documentation
- API Testing
- Contract Testing
- Governance
- Monitoring
- Platform
url: https://raw.githubusercontent.com/api-evangelist/smartbear/refs/heads/main/apis.yml
use_cases: []
---
