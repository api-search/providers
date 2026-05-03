---
api_count: 1
api_specs:
- filename: united-states-steel-steeltrack-openapi.yml
  format: yaml
  label: U.S. Steel SteelTrack API
  slug: steeltrack-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-steel/refs/heads/main/openapi/united-states-steel-steeltrack-openapi.yml
apis:
- description: 'SteelTrack is U.S. Steel''s internet-based customer platform providing order status reporting, inventory tracking, shipment history, material release, and physical and chemical test reporting. The API '
  name: U.S. Steel SteelTrack API
  slug: steeltrack-api
capabilities:
- description: Workflow capability for managing the complete U.S. Steel supply chain relationship. Combines order management, inventory tracking, shipment visibility, and quality documentation from the SteelTrack pl
  name: U.S. Steel Supply Chain Management
  slug: supply-chain-management
common:
- title: ''
  type: Website
  url: https://www.ussteel.com
- title: ''
  type: Portal
  url: https://www.ussteel.com/customers/solutions
- title: ''
  type: Documentation
  url: https://www.ussteel.com/about-us/doing-business-with-u.-s.-steel
- title: ''
  type: SpectralRules
  url: rules/united-states-steel-spectral-rules.yml
- title: Supply Chain Management
  type: NaftikoCapability
  url: capabilities/supply-chain-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/united-states-steel-vocabulary.yaml
created: ''
description: United States Steel Corporation (U.S. Steel) is an integrated steel producer headquartered in Pittsburgh, Pennsylvania, with major production operations in the United States and Central Europe. The company serves customers in automotive, construction, container, energy, and industrial markets with advanced high-strength steels, coated products, hot-rolled and cold-rolled coils, electrical steel, and tubular products. U.S. Steel provides digital customer tools through the SteelTrack platform for order management, inventory tracking, shipment history, and certified test reporting.
features:
- description: Customizable reports on order availability and status across all U.S. Steel facilities.
  name: Order Status Reporting
- description: On-demand inventory reporting filterable by OP, customer, PO, and part number with flexible sorting.
  name: Inventory Tracking
- description: Load history searchable by order item, part number, and PO with optional coil-level detail.
  name: Shipment History
- description: Physical, mechanical, and chemical test reports with electronic certification signatures.
  name: Certified Test Reports
- description: SteelTrack platform operates 24 hours a day, 7 days a week with console dashboard and workflow guidance.
  name: 24/7 Availability
- description: Consolidated view across all U.S. Steel production facilities including Gary Works, Mon Valley, and Big River Steel.
  name: Multi-Facility Coverage
- description: New and updated test report information relayed throughout the day to the Test Reports System.
  name: Real-Time Updates
image: ''
integrations:
- description: SteelTrack data integrates with SAP ERP for automated purchase order management and goods receipt processing.
  name: SAP
- description: Order and inventory data connects to Oracle ERP Cloud for supply chain and procurement workflows.
  name: Oracle ERP
- description: Electronic Data Interchange for standard steel industry transaction sets including orders, shipment notices, and invoices.
  name: EDI
- description: Technology partnership with Nippon Steel Corporation following acquisition for shared manufacturing intelligence.
  name: Nippon Steel
jsonld:
- class_count: 8
  name: United States Steel Steeltrack Context
  property_count: 33
  slug: united-states-steel-steeltrack-context
layout: provider
modified: '2026-05-03'
name: United States Steel
rules:
- name: United States Steel API Rules
  rule_count: 27
  severity_counts:
    error: 13
    hint: 0
    info: 4
    warn: 10
  slug: united-states-steel-spectral-rules
skills: []
slug: united-states-steel
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: united-states-steel\nname: United States Steel\nurl: https://raw.githubusercontent.com/api-evangelist/united-states-steel/refs/heads/main/apis.yml\ndescription: >-\n  United States Steel Corporation (U.S. Steel) is an integrated steel producer\n  headquartered in Pittsburgh, Pennsylvania, with major production operations in the\n  United States and Central Europe. The company serves customers in automotive,\n  construction, container, energy, and industrial markets with advanced high-strength\n  steels, coated products, hot-rolled and cold-rolled coils, electrical steel, and\n  tubular products. U.S. Steel provides digital customer tools through the SteelTrack\n  platform for order management, inventory tracking, shipment history, and certified\n  test reporting.\nmodified: '2026-05-03'\ntags:\n  - Steel\n  - Manufacturing\n  - Automotive\n  - Construction\n  - Energy\n  - Supply Chain\napis:\n  - name: U.S. Steel SteelTrack API\n    description: >-\n      SteelTrack is\
  \ U.S. Steel's internet-based customer platform providing order\n      status reporting, inventory tracking, shipment history, material release, and\n      physical and chemical test reporting. The API enables ERP and supply chain\n      integration for steel order management and quality documentation.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.ussteel.com/about-us/doing-business-with-u.-s.-steel\n    baseURL: https://steeltrack.ussteel.com/api\n    tags:\n      - Steel\n      - Supply Chain\n      - Order Management\n      - Manufacturing\n    properties:\n      - type: Documentation\n        url: https://www.ussteel.com/about-us/doing-business-with-u.-s.-steel\n      - type: OpenAPI\n        url: openapi/united-states-steel-steeltrack-openapi.yml\n      - type: JSONSchema\n        url: json-schema/steeltrack-order-schema.json\n        title: Order Schema\n      - type: JSONSchema\n        url: json-schema/steeltrack-shipment-schema.json\n\
  \        title: Shipment Schema\n      - type: JSONStructure\n        url: json-structure/steeltrack-order-structure.json\n        title: Order Structure\n      - type: JSON-LD\n        url: json-ld/united-states-steel-steeltrack-context.jsonld\n      - type: Example\n        url: examples/steeltrack-order-example.json\n        title: Order Example\n    aid: united-states-steel:steeltrack-api\ncommon:\n  - type: Website\n    url: https://www.ussteel.com\n  - type: Portal\n    url: https://www.ussteel.com/customers/solutions\n  - type: Documentation\n    url: https://www.ussteel.com/about-us/doing-business-with-u.-s.-steel\n  - type: SpectralRules\n    url: rules/united-states-steel-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/supply-chain-management.yaml\n    title: Supply Chain Management\n  - type: Vocabulary\n    url: vocabulary/united-states-steel-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Order Status Reporting\n        description: Customizable\
  \ reports on order availability and status across all U.S. Steel facilities.\n      - name: Inventory Tracking\n        description: On-demand inventory reporting filterable by OP, customer, PO, and part number with flexible sorting.\n      - name: Shipment History\n        description: Load history searchable by order item, part number, and PO with optional coil-level detail.\n      - name: Certified Test Reports\n        description: Physical, mechanical, and chemical test reports with electronic certification signatures.\n      - name: 24/7 Availability\n        description: SteelTrack platform operates 24 hours a day, 7 days a week with console dashboard and workflow guidance.\n      - name: Multi-Facility Coverage\n        description: Consolidated view across all U.S. Steel production facilities including Gary Works, Mon Valley, and Big River Steel.\n      - name: Real-Time Updates\n        description: New and updated test report information relayed throughout the day to the Test\
  \ Reports System.\n  - type: UseCases\n    data:\n      - name: ERP Integration\n        description: Integrate SteelTrack order and shipment data directly into customer ERP systems for automated procurement workflows.\n      - name: Quality Documentation\n        description: Automate retrieval of certified mill test reports for compliance, quality audits, and material traceability.\n      - name: Supply Chain Visibility\n        description: Track steel coil status from order placement through production and delivery for manufacturing planning.\n      - name: Inventory Planning\n        description: Monitor available inventory and in-transit material to optimize material release and production scheduling.\n      - name: Automotive Supplier Compliance\n        description: Access physical and chemical test data to meet automotive OEM supplier quality requirements (PPAP, IMDS).\n      - name: Shipment Reconciliation\n        description: Reconcile received shipments against orders using\
  \ coil-level shipping data for accounts payable processing.\n  - type: Integrations\n    data:\n      - name: SAP\n        description: SteelTrack data integrates with SAP ERP for automated purchase order management and goods receipt processing.\n      - name: Oracle ERP\n        description: Order and inventory data connects to Oracle ERP Cloud for supply chain and procurement workflows.\n      - name: EDI\n        description: Electronic Data Interchange for standard steel industry transaction sets including orders, shipment notices, and invoices.\n      - name: Nippon Steel\n        description: Technology partnership with Nippon Steel Corporation following acquisition for shared manufacturing intelligence.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/united-states-steel/refs/heads/main/apis.yml
tags:
- Steel
- Manufacturing
- Automotive
- Construction
- Energy
- Supply Chain
url: https://raw.githubusercontent.com/api-evangelist/united-states-steel/refs/heads/main/apis.yml
use_cases:
- description: Integrate SteelTrack order and shipment data directly into customer ERP systems for automated procurement workflows.
  name: ERP Integration
- description: Automate retrieval of certified mill test reports for compliance, quality audits, and material traceability.
  name: Quality Documentation
- description: Track steel coil status from order placement through production and delivery for manufacturing planning.
  name: Supply Chain Visibility
- description: Monitor available inventory and in-transit material to optimize material release and production scheduling.
  name: Inventory Planning
- description: Access physical and chemical test data to meet automotive OEM supplier quality requirements (PPAP, IMDS).
  name: Automotive Supplier Compliance
- description: Reconcile received shipments against orders using coil-level shipping data for accounts payable processing.
  name: Shipment Reconciliation
---
