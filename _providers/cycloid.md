---
api_count: 1
api_specs:
- filename: cycloid-api-openapi.yml
  format: yaml
  label: Cycloid HTTP API
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cycloid/refs/heads/main/openapi/cycloid-api-openapi.yml
apis:
- description: The Cycloid HTTP API is the programmatic surface of the Cycloid Internal Developer Portal & Platform. It manages organizations, members, teams, projects, environments, stacks (Service Catalog), pipeli
  name: Cycloid HTTP API
  slug: http-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.cycloid.io
- title: ''
  type: Documentation
  url: https://docs.cycloid.io
- title: ''
  type: Pricing
  url: https://www.cycloid.io/pricing
- title: ''
  type: GitHubOrganization
  url: https://github.com/cycloidio
- title: ''
  type: Blog
  url: https://www.cycloid.io/blog
- title: ''
  type: Status
  url: https://status.cycloid.io
- title: ''
  type: Login
  url: https://console.cycloid.io
- title: ''
  type: TermsOfService
  url: https://www.cycloid.io/legal/terms-and-conditions
- title: ''
  type: PrivacyPolicy
  url: https://www.cycloid.io/legal/privacy-policy
- title: ''
  type: Contact
  url: https://www.cycloid.io/contact
- title: ''
  type: JSON-LD
  url: json-ld/cycloid-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cycloid-organization-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cycloid-stack-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/cycloid-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/cycloid-api-capabilities.yml
- title: ''
  type: Rules
  url: rules/cycloid-api-rules.yml
created: '2026-03-27'
description: Cycloid is a unified Internal Developer Portal & Platform combining self-service Service Catalogs (Stacks and StackForms), Infrastructure as Code orchestration, multi-cloud asset inventory (Asset Inventory and InfraView), CI/CD pipeline centralization, FinOps and GreenOps cost / carbon dashboards, RBAC governance, and an MCP server for natural-language interaction. Cycloid exposes a public HTTP REST API at http-api.cycloid.io for programmatic management of organizations, projects, environments, stacks, pipelines, credentials, config repositories, and cloud cost dashboards. Authentication is via API key or OAuth2 with token refresh; the canonical Swagger / Redoc reference is published at docs.cycloid.io.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: Cycloid Context
  property_count: 0
  slug: cycloid-context
layout: provider
modified: '2026-04-28'
name: Cycloid
rules:
- name: Cycloid API Rules
  rule_count: 6
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 3
  slug: cycloid-api-rules
skills: []
slug: cycloid
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cycloid\nname: Cycloid\nx-type: company\ndescription: >-\n  Cycloid is a unified Internal Developer Portal & Platform combining\n  self-service Service Catalogs (Stacks and StackForms), Infrastructure\n  as Code orchestration, multi-cloud asset inventory (Asset Inventory\n  and InfraView), CI/CD pipeline centralization, FinOps and GreenOps\n  cost / carbon dashboards, RBAC governance, and an MCP server for\n  natural-language interaction. Cycloid exposes a public HTTP REST API\n  at http-api.cycloid.io for programmatic management of organizations,\n  projects, environments, stacks, pipelines, credentials, config\n  repositories, and cloud cost dashboards. Authentication is via API\n  key or OAuth2 with token refresh; the canonical Swagger / Redoc\n  reference is published at docs.cycloid.io.\nurl: https://raw.githubusercontent.com/api-evangelist/cycloid/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\n\
  access: 3rd-Party\nposition: Consumer\ncreated: '2026-03-27'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntags:\n  - Asset Inventory\n  - CI/CD\n  - Cloud Cost Management\n  - Cloud Management\n  - Developer Experience\n  - DevOps\n  - FinOps\n  - GitOps\n  - GreenOps\n  - Infrastructure as Code\n  - Internal Developer Platform\n  - Internal Developer Portal\n  - Multi-Cloud\n  - Platform Engineering\n  - RBAC\n  - Self-Service\n  - Service Catalog\n  - StackForms\n  - Terraform\napis:\n  - aid: cycloid:http-api\n    name: Cycloid HTTP API\n    description: >-\n      The Cycloid HTTP API is the programmatic surface of the Cycloid\n      Internal Developer Portal & Platform. It manages organizations,\n      members, teams, projects, environments, stacks (Service Catalog),\n      pipelines, infrastructure resources, credentials, config\n      repositories, cloud cost dashboards, and inventory. Authentication\n      uses an API key or OAuth2 with token refresh.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://docs.cycloid.io/\n    baseURL: https://http-api.cycloid.io\n    tags:\n      - API Key\n      - Cloud Cost\n      - Credentials\n      - Inventory\n      - OAuth2\n      - Organizations\n      - Pipelines\n      - Projects\n      - Service Catalog\n      - Stacks\n    properties:\n      - type: Documentation\n        url: https://docs.cycloid.io/\n      - type: GettingStarted\n        url: https://docs.cycloid.io/getting-started\n      - type: OpenAPI\n        url: openapi/cycloid-api-openapi.yml\n      - type: Capabilities\n        url: capabilities/cycloid-api-capabilities.yml\n      - type: Rules\n        url: rules/cycloid-api-rules.yml\ncommon:\n  - type: Website\n    url: https://www.cycloid.io\n  - type: Documentation\n    url: https://docs.cycloid.io\n  - type: Pricing\n    url: https://www.cycloid.io/pricing\n  - type: GitHubOrganization\n    url: https://github.com/cycloidio\n  - type: Blog\n    url: https://www.cycloid.io/blog\n  - type: Status\n    url:\
  \ https://status.cycloid.io\n  - type: Login\n    url: https://console.cycloid.io\n  - type: TermsOfService\n    url: https://www.cycloid.io/legal/terms-and-conditions\n  - type: PrivacyPolicy\n    url: https://www.cycloid.io/legal/privacy-policy\n  - type: Contact\n    url: https://www.cycloid.io/contact\n  - type: JSON-LD\n    url: json-ld/cycloid-context.jsonld\n  - type: JSONSchema\n    url: json-schema/cycloid-organization-schema.json\n  - type: JSONSchema\n    url: json-schema/cycloid-stack-schema.json\n  - type: Vocabulary\n    url: vocabulary/cycloid-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/cycloid-api-capabilities.yml\n  - type: Rules\n    url: rules/cycloid-api-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cycloid/refs/heads/main/apis.yml
tags:
- Asset Inventory
- CI/CD
- Cloud Cost Management
- Cloud Management
- Developer Experience
- DevOps
- FinOps
- GitOps
- GreenOps
- Infrastructure as Code
- Internal Developer Platform
- Internal Developer Portal
- Multi-Cloud
- Platform Engineering
- RBAC
- Self-Service
- Service Catalog
- StackForms
- Terraform
url: https://raw.githubusercontent.com/api-evangelist/cycloid/refs/heads/main/apis.yml
use_cases: []
---
