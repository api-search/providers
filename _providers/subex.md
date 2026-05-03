---
api_count: 1
api_specs:
- filename: subex-revenue-assurance-openapi.yml
  format: yaml
  label: Subex Revenue Assurance & Fraud Management API
  slug: subex-revenue-assurance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/subex/refs/heads/main/openapi/subex-revenue-assurance-openapi.yml
apis:
- description: Subex ROC (Revenue Operations Center) API for telecom operators. Provides revenue leakage detection and management, fraud case investigation, subscriber risk scoring, CDR reconciliation, and analytics
  name: Subex Revenue Assurance & Fraud Management API
  slug: subex-revenue-assurance-api
capabilities:
- description: Unified capability for telecom revenue operations. Combines Subex ROC APIs for revenue leakage detection, fraud case management, subscriber risk scoring, CDR reconciliation, and analytics. Used by tel
  name: Subex Revenue Operations Center
  slug: revenue-operations-center
common:
- title: ''
  type: Website
  url: https://www.subex.com
- title: ''
  type: Portal
  url: https://www.subex.com/roc/
- title: ''
  type: Blog
  url: https://www.subex.com/blog/
- title: ''
  type: Support
  url: https://www.subex.com/contact-us/
- title: ''
  type: Privacy Policy
  url: https://www.subex.com/privacy-policy/
- title: ''
  type: Change Log
  url: https://www.subex.com/newsroom/
- title: ''
  type: Spectral Rules
  url: rules/subex-rules.yml
- title: ''
  type: Naftiko Capability
  url: capabilities/revenue-operations-center.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/subex-vocabulary.yml
- title: ''
  type: JSON Schema
  url: json-schema/subex-fraud-case-schema.json
- title: ''
  type: JSON Structure
  url: json-structure/subex-leakage-alert-structure.json
- title: ''
  type: JSON-LD Context
  url: json-ld/subex-context.jsonld
- title: ''
  type: Example
  url: examples/subex-list-fraud-cases-example.json
- title: ''
  type: Example
  url: examples/subex-get-subscriber-risk-score-example.json
created: '2026-03-18'
description: Subex is a telecom analytics company providing revenue assurance, fraud management, and network analytics solutions through its ROC (Revenue Operations Center) platform. Subex helps telecom operators detect and prevent revenue leakage, manage telecom fraud (SIM swap, IRSF, bypass fraud, roaming fraud), reconcile CDR data, and gain analytics insights across their business support systems.
features: []
image: ''
integrations: []
jsonld:
- class_count: 30
  name: Subex Context
  property_count: 3
  slug: subex-context
layout: provider
modified: '2026-05-02'
name: Subex
rules:
- name: Subex API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 2
    info: 0
    warn: 4
  slug: subex-rules
skills: []
slug: subex
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: subex\nurl: https://raw.githubusercontent.com/api-evangelist/subex/refs/heads/main/apis.yml\napis:\n  - aid: subex:subex-revenue-assurance-api\n    name: Subex Revenue Assurance & Fraud Management API\n    tags:\n      - Revenue Assurance\n      - Fraud Management\n      - CDR Reconciliation\n      - Analytics\n      - Telecom\n    humanURL: https://www.subex.com/roc/\n    properties:\n      - url: https://www.subex.com/roc/\n        type: Documentation\n      - url: https://www.subex.com/contact-us/\n        type: Contact\n      - url: openapi/subex-revenue-assurance-openapi.yml\n        type: OpenAPI\n    description: >-\n      Subex ROC (Revenue Operations Center) API for telecom operators. Provides revenue leakage\n      detection and management, fraud case investigation, subscriber risk scoring, CDR\n      reconciliation, and analytics across voice, data, roaming, and digital services.\n\nname: Subex\ntags:\n  - Telecom\n  - Revenue Assurance\n  - Fraud Management\n\
  \  - Analytics\n  - BSS/OSS\ntype: Contract\naccess: 3rd-Party\ncreated: '2026-03-18'\nmodified: '2026-05-02'\nposition: Consuming\ndescription: >-\n  Subex is a telecom analytics company providing revenue assurance, fraud management, and\n  network analytics solutions through its ROC (Revenue Operations Center) platform. Subex\n  helps telecom operators detect and prevent revenue leakage, manage telecom fraud (SIM swap,\n  IRSF, bypass fraud, roaming fraud), reconcile CDR data, and gain analytics insights\n  across their business support systems.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - url: https://www.subex.com\n    type: Website\n  - url: https://www.subex.com/roc/\n    type: Portal\n  - url: https://www.subex.com/blog/\n    type: Blog\n  - url: https://www.subex.com/contact-us/\n    type: Support\n  - url: https://www.subex.com/privacy-policy/\n    type: Privacy Policy\n  - url: https://www.subex.com/newsroom/\n\
  \    type: Change Log\n  - url: rules/subex-rules.yml\n    type: Spectral Rules\n  - url: capabilities/revenue-operations-center.yaml\n    type: Naftiko Capability\n  - url: vocabulary/subex-vocabulary.yml\n    type: Vocabulary\n  - url: json-schema/subex-fraud-case-schema.json\n    type: JSON Schema\n  - url: json-structure/subex-leakage-alert-structure.json\n    type: JSON Structure\n  - url: json-ld/subex-context.jsonld\n    type: JSON-LD Context\n  - url: examples/subex-list-fraud-cases-example.json\n    type: Example\n  - url: examples/subex-get-subscriber-risk-score-example.json\n    type: Example\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/subex/refs/heads/main/apis.yml
tags:
- Telecom
- Revenue Assurance
- Fraud Management
- Analytics
- BSS/OSS
url: https://raw.githubusercontent.com/api-evangelist/subex/refs/heads/main/apis.yml
use_cases: []
---
