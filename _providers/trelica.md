---
api_count: 1
api_specs:
- filename: trelica-rest-api-openapi.yml
  format: yaml
  label: Trelica REST API
  slug: trelica
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trelica/refs/heads/main/openapi/trelica-rest-api-openapi.yml
apis:
- description: The Trelica REST API provides programmatic access to the core areas of the Trelica SaaS management platform, including applications, people, contracts, workflows, assets, audit logs, and user manageme
  name: Trelica REST API
  slug: trelica
capabilities:
- description: Unified capability for IT teams to discover, manage, and optimize SaaS applications across the organization. Combines application discovery, user license tracking, contract management, workflow automa
  name: Trelica SaaS Management
  slug: saas-management
common:
- title: ''
  type: Website
  url: https://www.trelica.com
- title: ''
  type: Documentation
  url: https://trelica.gitbook.io/trelica-api
- title: ''
  type: HelpCenter
  url: https://help.trelica.com/hc/en-us/sections/7739034184093-API
- title: ''
  type: Authentication
  url: https://help.trelica.com/hc/en-us/articles/7739283478941-Trelica-API
- title: ''
  type: GitHubOrganization
  url: https://github.com/trelica
- title: ''
  type: SDK
  url: https://github.com/trelica/trelica-api-sdk
- title: ''
  type: SDK
  url: https://github.com/trelica/node
- title: ''
  type: SDK
  url: https://github.com/trelica/powershell
- title: ''
  type: JSONSchema
  url: json-schema/trelica-application-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/trelica-person-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/trelica-contract-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/trelica-application-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/trelica-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/trelica-spectral-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/saas-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/trelica-vocabulary.yml
created: '2026-03-27'
description: Trelica is a SaaS management platform (now part of 1Password SaaS Manager) providing application discovery, license optimization, contract management, and workflow automation for IT teams. The platform offers a REST API covering applications, users, people, contracts, workflows, assets, and audit logs with OAuth 2.0 authentication using Client Credentials and Authorization Code flows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 23
  name: Trelica Context
  property_count: 15
  slug: trelica-context
layout: provider
modified: '2026-05-03'
name: Trelica
rules:
- name: Trelica API Rules
  rule_count: 13
  severity_counts:
    error: 2
    hint: 0
    info: 4
    warn: 7
  slug: trelica-spectral-rules
skills: []
slug: trelica
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trelica\nname: Trelica\ndescription: >-\n  Trelica is a SaaS management platform (now part of 1Password SaaS Manager)\n  providing application discovery, license optimization, contract management,\n  and workflow automation for IT teams. The platform offers a REST API covering\n  applications, users, people, contracts, workflows, assets, and audit logs\n  with OAuth 2.0 authentication using Client Credentials and Authorization Code\n  flows.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Contract Management\n  - IT Management\n  - License Management\n  - SaaS Management\n  - Software Asset Management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/trelica/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: trelica:trelica\n    name: Trelica REST API\n    description: >-\n      The Trelica REST API provides programmatic access to the\
  \ core areas of the\n      Trelica SaaS management platform, including applications, people,\n      contracts, workflows, assets, audit logs, and user management. The API\n      uses OAuth 2.0 with either Client Credentials (for integrations) or\n      Authorization Code flow (for third-party developer apps). The Users\n      endpoint follows the SCIM protocol.\n    humanURL: https://trelica.gitbook.io/trelica-api\n    baseURL: https://app.trelica.com/api\n    tags:\n      - Application Discovery\n      - Contract Management\n      - IT Management\n      - License Management\n      - SaaS Management\n      - Software Asset Management\n    properties:\n      - type: Documentation\n        url: https://trelica.gitbook.io/trelica-api\n      - type: Documentation\n        url: https://help.trelica.com/hc/en-us/sections/7739034184093-API\n      - type: Authentication\n        url: https://help.trelica.com/hc/en-us/articles/7739283478941-Trelica-API\n      - type: OpenAPI\n        url: openapi/trelica-rest-api-openapi.yml\n\
  \      - type: GitHubOrganization\n        url: https://github.com/trelica\n      - type: GitHubRepository\n        url: https://github.com/trelica/trelica-api-sdk\n      - type: GitHubRepository\n        url: https://github.com/trelica/powershell\n      - type: GitHubRepository\n        url: https://github.com/trelica/node\ncommon:\n  - type: Website\n    url: https://www.trelica.com\n  - type: Documentation\n    url: https://trelica.gitbook.io/trelica-api\n  - type: HelpCenter\n    url: https://help.trelica.com/hc/en-us/sections/7739034184093-API\n  - type: Authentication\n    url: https://help.trelica.com/hc/en-us/articles/7739283478941-Trelica-API\n  - type: GitHubOrganization\n    url: https://github.com/trelica\n  - type: SDK\n    url: https://github.com/trelica/trelica-api-sdk\n  - type: SDK\n    url: https://github.com/trelica/node\n  - type: SDK\n    url: https://github.com/trelica/powershell\n  - type: JSONSchema\n    url: json-schema/trelica-application-schema.json\n  - type:\
  \ JSONSchema\n    url: json-schema/trelica-person-schema.json\n  - type: JSONSchema\n    url: json-schema/trelica-contract-schema.json\n  - type: JSONStructure\n    url: json-structure/trelica-application-structure.json\n  - type: JSON-LD\n    url: json-ld/trelica-context.jsonld\n  - type: SpectralRules\n    url: rules/trelica-spectral-rules.yml\n  - type: NaftikoCapabilities\n    url: capabilities/saas-management.yaml\n  - type: Vocabulary\n    url: vocabulary/trelica-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trelica/refs/heads/main/apis.yml
tags:
- Contract Management
- IT Management
- License Management
- SaaS Management
- Software Asset Management
url: https://raw.githubusercontent.com/api-evangelist/trelica/refs/heads/main/apis.yml
use_cases: []
---
