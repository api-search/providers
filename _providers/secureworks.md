---
api_count: 1
api_specs:
- filename: secureworks-taegis-xdr-openapi.yml
  format: yaml
  label: Secureworks Taegis XDR API
  slug: secureworks-taegis-xdr-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/secureworks/refs/heads/main/openapi/secureworks-taegis-xdr-openapi.yml
apis:
- description: 'The Secureworks Taegis XDR API provides GraphQL-based programmatic access to the Taegis extended detection and response platform. The API supports alerts, investigations, endpoint assets, identities, '
  name: Secureworks Taegis XDR API
  slug: secureworks-taegis-xdr-api
capabilities:
- description: Unified threat detection and response capability for the Secureworks Taegis XDR platform. Enables SOC analysts and security engineers to query alerts, manage investigations, monitor endpoint assets, a
  name: Secureworks Taegis Threat Detection and Response
  slug: threat-detection-response
common:
- title: ''
  type: Website
  url: https://www.secureworks.com
- title: ''
  type: Documentation
  url: https://docs.taegis.secureworks.com/apis/using_xdr_apis/
- title: ''
  type: Authentication
  url: https://docs.taegis.secureworks.com/apis/api_authenticate/
- title: ''
  type: GitHubOrganization
  url: https://github.com/secureworks
- title: ''
  type: SDK
  url: https://github.com/secureworks/taegis-sdk-python
- title: ''
  type: Documentation
  url: https://us2.vdr.secureworks.com/api/v2/spec
- title: ''
  type: Blog
  url: https://www.secureworks.com/blog/show-me-the-apis
- title: ''
  type: JSONSchema
  url: json-schema/secureworks-alert-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/secureworks-investigation-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/secureworks-context.jsonld
- title: ''
  type: Example
  url: examples/secureworks-query-alerts-example.json
- title: ''
  type: SpectralRuleset
  url: rules/secureworks-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/threat-detection-response.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/secureworks-vocabulary.yml
created: '2026-05-02'
description: Secureworks is a cybersecurity company that provides the Taegis XDR (Extended Detection and Response) platform, offering threat detection, investigation, and response capabilities backed by 20 years of security intelligence. Taegis ingests and correlates telemetry across endpoints, network, cloud, and identity sources to detect threats and automate response workflows. The Taegis XDR API exposes GraphQL APIs for alerts, investigations, endpoint assets, identities, threat intelligence, connectors, collectors, playbooks, and users, with OAuth2 client credentials authentication and multi-region deployment support.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 25
  name: Secureworks Context
  property_count: 3
  slug: secureworks-context
layout: provider
modified: '2026-05-02'
name: Secureworks
rules:
- name: Secureworks API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 2
    warn: 3
  slug: secureworks-rules
skills: []
slug: secureworks
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: secureworks\nurl: https://raw.githubusercontent.com/api-evangelist/secureworks/refs/heads/main/apis.yml\napis:\n  - aid: secureworks:secureworks-taegis-xdr-api\n    name: Secureworks Taegis XDR API\n    tags:\n      - XDR\n      - Threat Detection\n      - Security Operations\n      - GraphQL\n      - Incident Response\n    humanURL: https://docs.taegis.secureworks.com/apis/using_xdr_apis/\n    baseURL: https://api.ctpx.secureworks.com\n    properties:\n      - url: openapi/secureworks-taegis-xdr-openapi.yml\n        type: OpenAPI\n      - url: https://docs.taegis.secureworks.com/apis/using_xdr_apis/\n        type: Documentation\n      - url: https://docs.taegis.secureworks.com/apis/api_authenticate/\n        type: Authentication\n    description: >-\n      The Secureworks Taegis XDR API provides GraphQL-based programmatic access to\n      the Taegis extended detection and response platform. The API supports alerts,\n      investigations, endpoint assets, identities, threat\
  \ intelligence, collectors,\n      connectors, playbooks, and audit operations. Authentication uses OAuth2 client\n      credentials flow with bearer token authorization. The platform is available across\n      multiple regions in the US and EU, with each region served by a dedicated API\n      endpoint.\n\nname: Secureworks\ntags:\n  - Cybersecurity\n  - XDR\n  - Threat Detection\n  - Security Operations\n  - Incident Response\n  - MDR\n  - Threat Intelligence\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nposition: Consuming\ndescription: >-\n  Secureworks is a cybersecurity company that provides the Taegis XDR (Extended Detection\n  and Response) platform, offering threat detection, investigation, and response capabilities\n  backed by 20 years of security intelligence. Taegis ingests and correlates telemetry\n  across endpoints, network, cloud, and identity sources to\
  \ detect threats and automate\n  response workflows. The Taegis XDR API exposes GraphQL APIs for alerts, investigations,\n  endpoint assets, identities, threat intelligence, connectors, collectors, playbooks,\n  and users, with OAuth2 client credentials authentication and multi-region deployment\n  support.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: Website\n    url: https://www.secureworks.com\n    type: Website\n  - name: Taegis API Documentation\n    url: https://docs.taegis.secureworks.com/apis/using_xdr_apis/\n    type: Documentation\n  - name: API Authentication\n    url: https://docs.taegis.secureworks.com/apis/api_authenticate/\n    type: Authentication\n  - name: GitHub Organization\n    url: https://github.com/secureworks\n    type: GitHubOrganization\n  - name: Taegis Python SDK\n    url: https://github.com/secureworks/taegis-sdk-python\n    type: SDK\n  - name: VDR API Documentation\n    url: https://us2.vdr.secureworks.com/api/v2/spec\n\
  \    type: Documentation\n  - name: API Blog Post\n    url: https://www.secureworks.com/blog/show-me-the-apis\n    type: Blog\n  - url: json-schema/secureworks-alert-schema.json\n    type: JSONSchema\n  - url: json-structure/secureworks-investigation-structure.json\n    type: JSONStructure\n  - url: json-ld/secureworks-context.jsonld\n    type: JSONLDContext\n  - url: examples/secureworks-query-alerts-example.json\n    type: Example\n  - url: rules/secureworks-rules.yml\n    type: SpectralRuleset\n  - url: capabilities/threat-detection-response.yaml\n    type: NaftikoCapability\n  - url: vocabulary/secureworks-vocabulary.yml\n    type: Vocabulary\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/secureworks/refs/heads/main/apis.yml
tags:
- Cybersecurity
- XDR
- Threat Detection
- Security Operations
- Incident Response
- MDR
- Threat Intelligence
url: https://raw.githubusercontent.com/api-evangelist/secureworks/refs/heads/main/apis.yml
use_cases: []
---
