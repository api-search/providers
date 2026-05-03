---
api_count: 1
api_specs:
- filename: saasment-openapi.yml
  format: yaml
  label: Saasment API
  slug: saasment
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/saasment/refs/heads/main/openapi/saasment-openapi.yml
apis:
- description: The Saasment API provides programmatic access to SaaS security posture management capabilities including configuration scanning, compliance assessment, misconfigurations detection, cost optimization r
  name: Saasment API
  slug: saasment
capabilities:
- description: Unified workflow for SaaS security posture management, misconfiguration detection, compliance assessment, and cost optimization. Used by security teams to continuously monitor and improve their SaaS s
  name: Saasment SaaS Security Posture Management
  slug: saas-security-posture
common:
- title: ''
  type: Website
  url: https://www.saasment.com
- title: ''
  type: Documentation
  url: https://www.saasment.com/resources
- title: ''
  type: Blog
  url: https://www.saasment.com/blog
- title: ''
  type: OpenAPI
  url: openapi/saasment-openapi.yml
- title: ''
  type: SpectralRules
  url: rules/saasment-rules.yml
- title: ''
  type: JSONSchema
  url: json-schema/saasment-misconfiguration-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/saasment-application-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/saasment-misconfiguration-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/saasment-application-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/saasment-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/saasment-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/saas-security-posture.yaml
created: '2026-03-27'
description: Saasment is an AI-powered SaaS security posture management (SSPM) and cloud cost optimization platform that detects misconfigurations, compliance gaps, and cost inefficiencies across cloud applications. It provides continuous monitoring, automated breach and attack simulation, privileged access management, and seamless integrations with identity management systems and other security tools.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 26
  name: Saasment Context
  property_count: 0
  slug: saasment-context
layout: provider
modified: '2026-05-02'
name: Saasment
rules:
- name: Saasment API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 5
  slug: saasment-rules
skills: []
slug: saasment
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: saasment\nname: Saasment\ndescription: >-\n  Saasment is an AI-powered SaaS security posture management (SSPM) and cloud\n  cost optimization platform that detects misconfigurations, compliance gaps,\n  and cost inefficiencies across cloud applications. It provides continuous\n  monitoring, automated breach and attack simulation, privileged access\n  management, and seamless integrations with identity management systems and\n  other security tools.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - SaaS Security\n  - SSPM\n  - Cloud Security\n  - Cost Optimization\n  - Compliance\n  - Misconfigurations\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/saasment/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: saasment:saasment\n    name: Saasment API\n    description: >-\n      The Saasment API provides programmatic access to SaaS security\
  \ posture\n      management capabilities including configuration scanning, compliance\n      assessment, misconfigurations detection, cost optimization recommendations,\n      and integration with cloud identity systems to secure SaaS estates.\n    humanURL: https://www.saasment.com\n    tags:\n      - SaaS Security\n      - SSPM\n      - Cloud Security\n      - Compliance\n      - Cost Optimization\n    properties:\n      - type: Documentation\n        url: https://www.saasment.com/resources\n      - type: Website\n        url: https://www.saasment.com\n      - type: OpenAPI\n        url: openapi/saasment-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.saasment.com\n  - type: Documentation\n    url: https://www.saasment.com/resources\n  - type: Blog\n    url: https://www.saasment.com/blog\n  - type: OpenAPI\n    url: openapi/saasment-openapi.yml\n  - type: SpectralRules\n    url: rules/saasment-rules.yml\n  - type: JSONSchema\n    url: json-schema/saasment-misconfiguration-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/saasment-application-schema.json\n  - type: JSONStructure\n    url: json-structure/saasment-misconfiguration-structure.json\n  - type: JSONStructure\n    url: json-structure/saasment-application-structure.json\n  - type: JSONLDContext\n    url: json-ld/saasment-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/saasment-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/saas-security-posture.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/saasment/refs/heads/main/apis.yml
tags:
- SaaS Security
- SSPM
- Cloud Security
- Cost Optimization
- Compliance
- Misconfigurations
url: https://raw.githubusercontent.com/api-evangelist/saasment/refs/heads/main/apis.yml
use_cases: []
---
