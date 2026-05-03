---
api_count: 3
api_specs:
- filename: scansource-product-openapi.yml
  format: yaml
  label: ScanSource Product API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scansource/refs/heads/main/openapi/scansource-product-openapi.yml
- filename: scansource-sales-order-openapi.yml
  format: yaml
  label: ScanSource Sales Order API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scansource/refs/heads/main/openapi/scansource-sales-order-openapi.yml
- filename: scansource-invoice-openapi.yml
  format: yaml
  label: ScanSource Invoice API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scansource/refs/heads/main/openapi/scansource-invoice-openapi.yml
apis:
- description: The ScanSource Product API provides real-time product information, pricing, and availability checks for technology distribution partners. Supports single and batch queries for up to 40 items per reque
  name: ScanSource Product API
  slug: ''
- description: The ScanSource Sales Order API enables partners to create, track, and manage purchase orders programmatically. Supports synchronous and asynchronous order creation, order status queries, shipping quot
  name: ScanSource Sales Order API
  slug: ''
- description: The ScanSource Invoice API provides access to invoicing data including invoice summaries, detailed invoice lists, individual invoice details, and PDF exports. Supports filtering by date range, sales o
  name: ScanSource Invoice API
  slug: ''
capabilities:
- description: 'Unified capability for ScanSource technology distribution partners. Combines product catalog, pricing, availability, order management, tracking, and invoicing into a single partner commerce workflow. '
  name: ScanSource Partner Commerce
  slug: partner-commerce
common:
- title: ''
  type: Website
  url: https://www.scansource.com
- title: ''
  type: DeveloperPortal
  url: https://partnerportal.scansource.com
- title: ''
  type: Documentation
  url: https://services.scansource.com/api/Help
- title: ''
  type: GettingStarted
  url: https://partnerportal.scansource.com/getstarted
- title: ''
  type: PartnerPortal
  url: https://partnerdevportal.scansource.com
- title: ''
  type: SpectralRules
  url: rules/scansource-rules.yml
- title: ''
  type: JSONStructure
  url: json-structure/scansource-product-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/scansource-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/scansource-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/partner-commerce.yaml
created: '2026-05-02'
description: ScanSource is an international technology distributor specializing in point-of-sale (POS), payments, barcode, physical security, unified communications, collaboration, telecom, and cloud services. Founded in 1992 in Greenville, South Carolina, ScanSource provides APIs that give partners real-time access to inventory, pricing, order management, and product information to automate the sales cycle and integrate with backend ERP systems and customer portals.
features: []
image: ''
integrations: []
jsonld:
- class_count: 7
  name: Scansource Context
  property_count: 27
  slug: scansource-context
layout: provider
modified: '2026-05-02'
name: ScanSource
rules:
- name: ScanSource API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 6
  slug: scansource-rules
skills: []
slug: scansource
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: ScanSource\ndescription: ScanSource is an international technology distributor specializing in point-of-sale (POS), payments, barcode, physical security, unified communications, collaboration, telecom, and cloud services. Founded in 1992 in Greenville, South Carolina, ScanSource provides APIs that give partners real-time access to inventory, pricing, order management, and product information to automate the sales cycle and integrate with backend ERP systems and customer portals.\nurl: https://github.com/api-evangelist/scansource\nx-type: company\nbapiId: scansource\ntags:\n- ScanSource\n- Distribution\n- Barcode\n- Point Of Sale\n- AIDC\n- Inventory\n- Order Management\n- E-Commerce\ncreated: '2026-05-02'\nmodified: '2026-05-02'\napis:\n- name: ScanSource Product API\n  description: The ScanSource Product API provides real-time product information, pricing, and availability checks for technology distribution partners. Supports single and batch queries for up to 40 items\
  \ per request, with integration targets including ERP systems, sales tools, and customer self-service portals.\n  humanURL: https://services.scansource.com/api/Help\n  baseURL: https://services.scansource.com/api\n  tags:\n  - Products\n  - Pricing\n  - Availability\n  - Inventory\n  properties:\n  - type: Documentation\n    url: https://services.scansource.com/api/Help\n  - type: OpenAPI\n    url: openapi/scansource-product-openapi.yml\n  - type: JSONSchema\n    url: json-schema/scansource-product-schema.json\n  contact:\n  - FN: ScanSource Partner Support\n    email: B2BRequest@scansource.com\n  x-auth:\n    type: apiKey\n    name: Ocp-Apim-Subscription-Key\n    in: header\n\n- name: ScanSource Sales Order API\n  description: The ScanSource Sales Order API enables partners to create, track, and manage purchase orders programmatically. Supports synchronous and asynchronous order creation, order status queries, shipping quotes, order cancellation, and serial number tracking.\n  humanURL:\
  \ https://services.scansource.com/api/Help\n  baseURL: https://services.scansource.com/api\n  tags:\n  - Orders\n  - Sales\n  - Commerce\n  - Fulfillment\n  properties:\n  - type: Documentation\n    url: https://services.scansource.com/api/Help\n  - type: OpenAPI\n    url: openapi/scansource-sales-order-openapi.yml\n  - type: JSONSchema\n    url: json-schema/scansource-order-schema.json\n  contact:\n  - FN: ScanSource Partner Support\n    email: B2BRequest@scansource.com\n  x-auth:\n    type: apiKey\n    name: Ocp-Apim-Subscription-Key\n    in: header\n\n- name: ScanSource Invoice API\n  description: The ScanSource Invoice API provides access to invoicing data including invoice summaries, detailed invoice lists, individual invoice details, and PDF exports. Supports filtering by date range, sales order number, invoice number, and purchase order number.\n  humanURL: https://services.scansource.com/api/Help\n  baseURL: https://services.scansource.com/api\n  tags:\n  - Invoices\n  - Billing\n\
  \  - Finance\n  - Accounting\n  properties:\n  - type: Documentation\n    url: https://services.scansource.com/api/Help\n  - type: OpenAPI\n    url: openapi/scansource-invoice-openapi.yml\n  contact:\n  - FN: ScanSource Partner Support\n    email: B2BRequest@scansource.com\n  x-auth:\n    type: apiKey\n    name: Ocp-Apim-Subscription-Key\n    in: header\n\ncommon:\n- type: Website\n  url: https://www.scansource.com\n- type: DeveloperPortal\n  url: https://partnerportal.scansource.com\n- type: Documentation\n  url: https://services.scansource.com/api/Help\n- type: GettingStarted\n  url: https://partnerportal.scansource.com/getstarted\n- type: PartnerPortal\n  url: https://partnerdevportal.scansource.com\n- type: SpectralRules\n  url: rules/scansource-rules.yml\n- type: JSONStructure\n  url: json-structure/scansource-product-structure.json\n- type: JSONLDContext\n  url: json-ld/scansource-context.jsonld\n- type: Vocabulary\n  url: vocabulary/scansource-vocabulary.yml\n- type: Capabilities\n\
  \  url: capabilities/partner-commerce.yaml\nmaintainers:\n- FN: API Evangelist\n  email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scansource/refs/heads/main/apis.yml
tags:
- ScanSource
- Distribution
- Barcode
- Point Of Sale
- AIDC
- Inventory
- Order Management
- E-Commerce
url: https://github.com/api-evangelist/scansource
use_cases: []
---
