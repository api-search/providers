---
api_count: 1
api_specs:
- filename: 1factory-openapi.json
  format: json
  label: 1Factory API
  slug: 1factory
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/1factory/refs/heads/main/openapi/1factory-openapi.json
apis:
- description: This API allows you to create and query a number of objects in your 1Factory account. The API accepts and returns request and response bodies as JSON, using UTF-8 encoding. Supports part master manage
  name: 1Factory API
  slug: 1factory
capabilities:
- description: Unified quality management workflow for 1Factory. Combines manufacturing inspections, receiving inspections, supplier quality, customer quality, FAI, part master management, and QMS records (NCRs, CAP
  name: 1Factory Quality Management
  slug: 1factory-quality-management
common:
- title: ''
  type: Website
  url: https://www.1factory.com/
- title: ''
  type: Documentation
  url: https://www.1factory.com/api-doc/index.html
- title: ''
  type: Security
  url: https://www.1factory.com/technical-overview.html
- title: ''
  type: Support
  url: https://1factoryhelp.zendesk.com/hc/en-us
- title: ''
  type: TermsOfService
  url: https://www.1factory.com/resources/TOS%20May%2020%202021.pdf
- title: ''
  type: RateLimits
  url: https://www.1factory.com/api-doc/index.html
- title: ''
  type: SpectralRules
  url: rules/1factory-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/1factory-quality-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/1factory-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/1factory-context.jsonld
created: '2025-02-08'
description: 1Factory is a leading provider of quality management software solutions for manufacturing companies. The platform helps businesses streamline their operations, improve efficiency, and ensure product quality at every stage of the production process. Features include real-time monitoring, automated data collection, advanced analytics, and integration with ERP and PLM systems via a REST API.
features:
- description: Factory floor quality control, inspection planning, and statistical process control (SPC)
  name: Manufacturing Quality Control
- description: Document control, training management, audits, and compliance workflows
  name: Quality Management System (QMS)
- description: Vendor oversight, incoming inspection management, and supplier corrective actions
  name: Supplier Quality Management
- description: Automated drawing ballooning and AS9102-compliant first article inspection
  name: First Article Inspection (FAI)
- description: Real-time quality analytics and audit-ready reporting dashboards
  name: Real-Time Analytics
- description: Automatic import of CMM measurement data with SPC analysis
  name: CMM Data Integration
- description: API-based integration with ERP and PLM systems for part and work order sync
  name: ERP/PLM Integration
image: /assets/icons/1factory.png
integrations:
- description: Sync part master data, work orders, and inspection records with ERP platforms
  name: ERP Systems
- description: Connect with PLM systems for design-to-manufacturing quality continuity
  name: PLM Systems
- description: Auto-import measurement data from CMM equipment directly into inspections
  name: CMM Equipment
jsonld:
- class_count: 29
  name: 1Factory Context
  property_count: 127
  slug: 1factory-context
layout: provider
modified: '2026-04-19'
name: 1Factory
rules:
- name: 1Factory API Rules
  rule_count: 32
  severity_counts:
    error: 13
    hint: 0
    info: 4
    warn: 15
  slug: 1factory-spectral-rules
skills: []
slug: 1factory
solutions: []
source_filename: apis.yml
source_yaml: "aid: 1factory\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/1factory/refs/heads/main/apis.yml\nname: 1Factory\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Data Collection\n  - Manufacturing\n  - Monitoring\n  - Quality\ndescription: >-\n  1Factory is a leading provider of quality management software solutions for manufacturing\n  companies. The platform helps businesses streamline their operations, improve efficiency,\n  and ensure product quality at every stage of the production process. Features include\n  real-time monitoring, automated data collection, advanced analytics, and integration\n  with ERP and PLM systems via a REST API.\ncreated: '2025-02-08'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: 1factory:1factory\n    name: 1Factory API\n    tags:\n      - Manufacturing\n      - Quality\n      - Inspections\n    humanURL: https://www.1factory.com/api-doc/index.html\n\
  \    baseURL: https://www.1factory.com/api/v1\n    properties:\n      - url: https://www.1factory.com/api-doc/index.html\n        type: Documentation\n      - url: openapi/1factory-openapi.json\n        type: OpenAPI\n      - url: json-schema/1factory-part-master-schema.json\n        type: JSONSchema\n      - url: json-schema/1factory-inspection-schema.json\n        type: JSONSchema\n      - url: json-schema/1factory-plan-schema.json\n        type: JSONSchema\n      - url: json-schema/1factory-fai-schema.json\n        type: JSONSchema\n      - url: json-schema/1factory-capa-schema.json\n        type: JSONSchema\n      - url: json-schema/1factory-ncr-schema.json\n        type: JSONSchema\n      - url: json-schema/1factory-complaint-schema.json\n        type: JSONSchema\n      - url: json-schema/1factory-supplier-schema.json\n        type: JSONSchema\n    description: >-\n      This API allows you to create and query a number of objects in your\n      1Factory account. The API accepts and\
  \ returns request and response bodies\n      as JSON, using UTF-8 encoding. Supports part master management, manufacturing\n      and receiving inspections, supplier quality, first article inspections (FAI),\n      and quality management system records (NCRs, CAPAs, complaints).\ncommon:\n  - type: Website\n    url: https://www.1factory.com/\n  - type: Documentation\n    url: https://www.1factory.com/api-doc/index.html\n  - type: Security\n    url: https://www.1factory.com/technical-overview.html\n  - type: Support\n    url: https://1factoryhelp.zendesk.com/hc/en-us\n  - type: TermsOfService\n    url: https://www.1factory.com/resources/TOS%20May%2020%202021.pdf\n  - type: RateLimits\n    url: https://www.1factory.com/api-doc/index.html\n    data:\n      - name: Minute Limit\n        description: 60 requests per minute\n      - name: Daily Limit\n        description: 1000 requests per day\n  - type: SpectralRules\n    url: rules/1factory-spectral-rules.yml\n  - type: NaftikoCapability\n\
  \    url: capabilities/1factory-quality-management.yaml\n  - type: Vocabulary\n    url: vocabulary/1factory-vocabulary.yaml\n  - type: JSON-LD\n    url: json-ld/1factory-context.jsonld\n  - type: Features\n    data:\n      - name: Manufacturing Quality Control\n        description: Factory floor quality control, inspection planning, and statistical process control (SPC)\n      - name: Quality Management System (QMS)\n        description: Document control, training management, audits, and compliance workflows\n      - name: Supplier Quality Management\n        description: Vendor oversight, incoming inspection management, and supplier corrective actions\n      - name: First Article Inspection (FAI)\n        description: Automated drawing ballooning and AS9102-compliant first article inspection\n      - name: Real-Time Analytics\n        description: Real-time quality analytics and audit-ready reporting dashboards\n      - name: CMM Data Integration\n        description: Automatic import\
  \ of CMM measurement data with SPC analysis\n      - name: ERP/PLM Integration\n        description: API-based integration with ERP and PLM systems for part and work order sync\n  - type: UseCases\n    data:\n      - name: Manufacturing Inspection\n        description: Create and track manufacturing inspections with measurement data and SPC analysis\n      - name: Supplier Qualification\n        description: Manage supplier certifications, conduct receiving inspections, and track supplier CAPAs\n      - name: Non-Conformance Management\n        description: Log, track, and resolve non-conformances, CAPAs, and customer complaints\n      - name: First Article Inspection\n        description: Conduct and document AS9102 first article inspections for aerospace and defense\n      - name: ERP Data Sync\n        description: Synchronize part master data, work orders, and inspection results with ERP systems\n  - type: Integrations\n    data:\n      - name: ERP Systems\n        description: Sync\
  \ part master data, work orders, and inspection records with ERP platforms\n      - name: PLM Systems\n        description: Connect with PLM systems for design-to-manufacturing quality continuity\n      - name: CMM Equipment\n        description: Auto-import measurement data from CMM equipment directly into inspections\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/1factory/refs/heads/main/apis.yml
tags:
- Analytics
- Data Collection
- Manufacturing
- Monitoring
- Quality
url: https://raw.githubusercontent.com/api-evangelist/1factory/refs/heads/main/apis.yml
use_cases:
- description: Create and track manufacturing inspections with measurement data and SPC analysis
  name: Manufacturing Inspection
- description: Manage supplier certifications, conduct receiving inspections, and track supplier CAPAs
  name: Supplier Qualification
- description: Log, track, and resolve non-conformances, CAPAs, and customer complaints
  name: Non-Conformance Management
- description: Conduct and document AS9102 first article inspections for aerospace and defense
  name: First Article Inspection
- description: Synchronize part master data, work orders, and inspection results with ERP systems
  name: ERP Data Sync
---
