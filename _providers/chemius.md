---
api_count: 7
apis:
- description: Programmatic access to Chemius Safety Data Sheet (SDS) creation, retrieval, and version control. Supports multilingual SDS generation aligned with CLP 1272/2008, REACH 1907/2006, and GHS formats.
  name: Chemius Safety Data Sheet API
  slug: sds-api
- description: API for generating and retrieving Technical Data Sheets (TDS) for chemical products, including version control and translation.
  name: Chemius Technical Data Sheet API
  slug: tds-api
- description: API for generating ADR (European Agreement concerning the International Carriage of Dangerous Goods by Road) transport documentation for chemical shipments.
  name: Chemius ADR Transport API
  slug: adr-api
- description: API for integrating Chemius product, SDS, TDS, and label data with enterprise ERP systems for synchronized chemical product information.
  name: Chemius ERP Integration API
  slug: erp-api
- description: API for generating regulatory-compliant chemical product labels with QR codes, hazard pictograms, and multilingual content.
  name: Chemius Label API
  slug: label-api
- description: API exposing chemical product data, SDSs, and TDSs for embedding in e-commerce experiences and customer-facing web shops.
  name: Chemius Web Shop API
  slug: web-shop-api
- description: API for rendering Chemius SDSs, TDSs, labels, and other compliance documents as PDF artifacts for distribution and archival.
  name: Chemius PDF API
  slug: pdf-api
common:
- title: ''
  type: Website
  url: https://www.chemius.net/
- title: ''
  type: Documentation
  url: https://www.chemius.net/chemius-api/
- title: ''
  type: Pricing
  url: https://www.chemius.net/pricing/
- title: ''
  type: Contact
  url: https://www.chemius.net/contact/
- title: ''
  type: JSONLD
  url: json-ld/chemius-context.jsonld
- title: ''
  type: Standards
  url: ''
created: '2025-03-01'
description: Chemius is a cloud-based chemical compliance platform that automates Safety Data Sheet (SDS), Technical Data Sheet (TDS), and regulatory label creation in 38+ languages for organizations handling chemical products. The platform exposes an API suite covering SDS, TDS, ADR transport documentation, ERP integration, labels, web shop product data, and PDF generation, and offers AI-assisted authoring through the Chemius AI SDS assistant. Chemius is hosted in DIN ISO/IEC 27001-certified German data centers and supports CLP 1272/2008, REACH 1907/2006, detergents, aerosols, and US OSHA / GHS regulatory frameworks.
features:
- name: Automated SDS Authoring
- name: Multilingual Output (38+ Languages)
- name: Technical Data Sheets
- name: Regulatory Labels with QR Codes
- name: ADR Transport Documents
- name: AI SDS Assistant
- name: Version Control with Change Tracking
- name: Real-Time Compliance Monitoring
- name: UFI and Poison Centre Notifications
- name: Regulatory Dashboard
- name: ERP Integration
- name: Web Shop Product Feeds
- name: PDF Rendering
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Chemius Context
  property_count: 4
  slug: chemius-context
layout: provider
modified: '2026-04-23'
name: Chemius
skills: []
slug: chemius
solutions: []
source_yaml: "aid: chemius\nname: Chemius\nx-type: company\ndescription: >-\n  Chemius is a cloud-based chemical compliance platform that automates Safety\n  Data Sheet (SDS), Technical Data Sheet (TDS), and regulatory label creation\n  in 38+ languages for organizations handling chemical products. The platform\n  exposes an API suite covering SDS, TDS, ADR transport documentation, ERP\n  integration, labels, web shop product data, and PDF generation, and offers\n  AI-assisted authoring through the Chemius AI SDS assistant. Chemius is\n  hosted in DIN ISO/IEC 27001-certified German data centers and supports\n  CLP 1272/2008, REACH 1907/2006, detergents, aerosols, and US OSHA / GHS\n  regulatory frameworks.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/chemius/refs/heads/main/apis.yml\ntags:\n  - ADR\n  - AI\n  - Chemicals\n  - Chemists\n  -\
  \ Compliance\n  - GHS\n  - Hazard Communication\n  - Labels\n  - REACH\n  - Regulatory\n  - Research\n  - Safety Data Sheets\n  - SaaS\n  - SDS\n  - TDS\ncreated: '2025-03-01'\nmodified: '2026-04-23'\nspecificationVersion: '0.20'\napis:\n  - aid: chemius:sds-api\n    name: Chemius Safety Data Sheet API\n    description: >-\n      Programmatic access to Chemius Safety Data Sheet (SDS) creation,\n      retrieval, and version control. Supports multilingual SDS\n      generation aligned with CLP 1272/2008, REACH 1907/2006, and GHS\n      formats.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.chemius.net/chemius-api/\n    tags:\n      - Compliance\n      - SDS\n      - Safety Data Sheets\n    properties:\n      - type: Documentation\n        url: https://www.chemius.net/chemius-api/\n  - aid: chemius:tds-api\n    name: Chemius Technical Data Sheet API\n    description: >-\n      API for generating and retrieving Technical Data\
  \ Sheets (TDS) for\n      chemical products, including version control and translation.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.chemius.net/chemius-api/\n    tags:\n      - Compliance\n      - TDS\n      - Technical Data Sheets\n    properties:\n      - type: Documentation\n        url: https://www.chemius.net/chemius-api/\n  - aid: chemius:adr-api\n    name: Chemius ADR Transport API\n    description: >-\n      API for generating ADR (European Agreement concerning the\n      International Carriage of Dangerous Goods by Road) transport\n      documentation for chemical shipments.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.chemius.net/chemius-api/\n    tags:\n      - ADR\n      - Transport\n      - Compliance\n    properties:\n      - type: Documentation\n        url: https://www.chemius.net/chemius-api/\n  - aid: chemius:erp-api\n    name: Chemius\
  \ ERP Integration API\n    description: >-\n      API for integrating Chemius product, SDS, TDS, and label data with\n      enterprise ERP systems for synchronized chemical product\n      information.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.chemius.net/chemius-api/\n    tags:\n      - ERP\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://www.chemius.net/chemius-api/\n  - aid: chemius:label-api\n    name: Chemius Label API\n    description: >-\n      API for generating regulatory-compliant chemical product labels\n      with QR codes, hazard pictograms, and multilingual content.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.chemius.net/chemius-api/\n    tags:\n      - Labels\n      - Compliance\n      - GHS\n    properties:\n      - type: Documentation\n        url: https://www.chemius.net/chemius-api/\n  - aid:\
  \ chemius:web-shop-api\n    name: Chemius Web Shop API\n    description: >-\n      API exposing chemical product data, SDSs, and TDSs for embedding\n      in e-commerce experiences and customer-facing web shops.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.chemius.net/chemius-api/\n    tags:\n      - E-Commerce\n      - Web Shop\n    properties:\n      - type: Documentation\n        url: https://www.chemius.net/chemius-api/\n  - aid: chemius:pdf-api\n    name: Chemius PDF API\n    description: >-\n      API for rendering Chemius SDSs, TDSs, labels, and other compliance\n      documents as PDF artifacts for distribution and archival.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.chemius.net/chemius-api/\n    tags:\n      - PDF\n      - Documents\n    properties:\n      - type: Documentation\n        url: https://www.chemius.net/chemius-api/\ncommon:\n\
  \  - type: Website\n    url: https://www.chemius.net/\n  - type: Documentation\n    url: https://www.chemius.net/chemius-api/\n  - type: Pricing\n    url: https://www.chemius.net/pricing/\n  - type: Contact\n    url: https://www.chemius.net/contact/\n  - type: JSONLD\n    url: json-ld/chemius-context.jsonld\n  - name: Features\n    type: Features\n    data:\n      - name: Automated SDS Authoring\n      - name: Multilingual Output (38+ Languages)\n      - name: Technical Data Sheets\n      - name: Regulatory Labels with QR Codes\n      - name: ADR Transport Documents\n      - name: AI SDS Assistant\n      - name: Version Control with Change Tracking\n      - name: Real-Time Compliance Monitoring\n      - name: UFI and Poison Centre Notifications\n      - name: Regulatory Dashboard\n      - name: ERP Integration\n      - name: Web Shop Product Feeds\n      - name: PDF Rendering\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: SDS Authoring at Scale\n      - name: Multilingual\
  \ Chemical Compliance\n      - name: Hazard Label Production\n      - name: ADR Shipment Documentation\n      - name: Poison Centre Notification Filing\n      - name: ERP-Driven Chemical Product Catalogs\n      - name: Customer-Facing SDS Portals\n      - name: Regulatory Change Monitoring\n  - name: Standards\n    type: Standards\n    data:\n      - name: CLP 1272/2008\n      - name: REACH 1907/2006\n      - name: GHS\n      - name: ADR\n      - name: US OSHA Hazard Communication\n      - name: UFI\n      - name: ISO/IEC 27001\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/chemius/refs/heads/main/apis.yml
tags:
- ADR
- AI
- Chemicals
- Chemists
- Compliance
- GHS
- Hazard Communication
- Labels
- REACH
- Regulatory
- Research
- Safety Data Sheets
- SaaS
- SDS
- TDS
url: https://raw.githubusercontent.com/api-evangelist/chemius/refs/heads/main/apis.yml
use_cases:
- name: SDS Authoring at Scale
- name: Multilingual Chemical Compliance
- name: Hazard Label Production
- name: ADR Shipment Documentation
- name: Poison Centre Notification Filing
- name: ERP-Driven Chemical Product Catalogs
- name: Customer-Facing SDS Portals
- name: Regulatory Change Monitoring
---
