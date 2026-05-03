---
api_count: 1
api_specs:
- filename: trabex-trade-compliance-openapi.yml
  format: yaml
  label: Trabex Trade Compliance API
  slug: trade-compliance
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trabex/refs/heads/main/openapi/trabex-trade-compliance-openapi.yml
apis:
- description: 'The Trabex Trade Compliance API provides programmatic access to export compliance automation including shipment data submission, export documentation generation, Automated Export System (AES) filing, '
  name: Trabex Trade Compliance API
  slug: trade-compliance
capabilities:
- description: End-to-end export compliance workflow combining shipment management, restricted party screening, AES filing, and compliance document generation. Used by export compliance teams to automate EEI filing,
  name: Trabex Export Compliance
  slug: export-compliance
common:
- title: ''
  type: Website
  url: https://trabex.io
- title: ''
  type: Documentation
  url: https://apidocs.trabex.io/
- title: ''
  type: Support
  url: https://support.trabex.io/support/home
created: '2026-03-16'
description: Trabex is a trade compliance platform that provides automated export compliance, shipment management, restricted party screening, and Automated Export System (AES) filing services. Trabex offers APIs for integrating trade compliance workflows including shipment data ingestion, export documentation generation, financial reporting, and ancillary compliance data to help organizations manage global trade risk.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 39
  name: Trabex Context
  property_count: 0
  slug: trabex-context
layout: provider
modified: '2026-05-03'
name: Trabex
rules:
- name: Trabex API Rules
  rule_count: 11
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 6
  slug: trabex-rules
skills: []
slug: trabex
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trabex\nname: Trabex\ndescription: >-\n  Trabex is a trade compliance platform that provides automated export\n  compliance, shipment management, restricted party screening, and Automated\n  Export System (AES) filing services. Trabex offers APIs for integrating trade\n  compliance workflows including shipment data ingestion, export documentation\n  generation, financial reporting, and ancillary compliance data to help\n  organizations manage global trade risk.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Compliance\n  - Export Control\n  - Logistics\n  - Restricted Party Screening\n  - Shipment Management\n  - Trade Compliance\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/trabex/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: trabex:trade-compliance\n    name: Trabex Trade Compliance API\n    description: >-\n      The Trabex\
  \ Trade Compliance API provides programmatic access to export\n      compliance automation including shipment data submission, export\n      documentation generation, Automated Export System (AES) filing, and\n      restricted party screening. The API enables organizations to integrate\n      compliance workflows into logistics and ERP systems, supporting single\n      shipments, batch screening, and continuous compliance operations.\n    humanURL: https://apidocs.trabex.io/\n    baseURL: https://api.trabex.io\n    tags:\n      - AES Filing\n      - Compliance\n      - Export Control\n      - Logistics\n      - Restricted Party Screening\n      - Shipment Management\n      - Trade\n    properties:\n      - type: Documentation\n        url: https://apidocs.trabex.io/\n      - type: OpenAPI\n        url: openapi/trabex-trade-compliance-openapi.yml\n      - type: JSONSchema\n        url: json-schema/trabex-shipment-schema.json\n      - type: JSONStructure\n        url: json-structure/trabex-shipment-structure.json\n\
  \      - type: JSONLd\n        url: json-ld/trabex-context.jsonld\n      - type: SpectralRules\n        url: rules/trabex-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/export-compliance.yaml\n      - type: Vocabulary\n        url: vocabulary/trabex-vocabulary.yml\n      - type: Support\n        url: https://support.trabex.io/support/home\ncommon:\n  - type: Website\n    url: https://trabex.io\n  - type: Documentation\n    url: https://apidocs.trabex.io/\n  - type: Support\n    url: https://support.trabex.io/support/home\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trabex/refs/heads/main/apis.yml
tags:
- Compliance
- Export Control
- Logistics
- Restricted Party Screening
- Shipment Management
- Trade Compliance
url: https://raw.githubusercontent.com/api-evangelist/trabex/refs/heads/main/apis.yml
use_cases: []
---
