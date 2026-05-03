---
api_count: 1
api_specs:
- filename: abilityone-procurement-list-api-openapi.yml
  format: yaml
  label: AbilityOne Procurement List API
  slug: procurement-list-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-abilityone-commission/refs/heads/main/openapi/abilityone-procurement-list-api-openapi.yml
apis:
- description: The Procurement List Information Management System (PLIMS) provides search access to the AbilityOne Procurement List — the catalog of products (identified by NSN) and services that federal agencies ar
  name: AbilityOne Procurement List API
  slug: procurement-list-api
capabilities:
- description: ''
  name: Disability Employment Procurement
  slug: disability-employment-procurement
common:
- title: ''
  type: Website
  url: https://www.abilityone.gov
- title: PLIMS - Procurement List Information Management System
  type: Portal
  url: https://plims.abilityone.gov
- title: ''
  type: Documentation
  url: https://www.abilityone.gov/procurement_list/
- title: Procurement List Data Downloads
  type: DataAPI
  url: https://plims.abilityone.gov/reports/
- title: ''
  type: JSONLD
  url: json-ld/us-abilityone-commission-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/us-abilityone-commission-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/us-abilityone-commission-vocabulary.yaml
- title: Disability Employment Procurement
  type: NaftikoCapability
  url: capabilities/disability-employment-procurement.yaml
- title: Procurement List API (Shared)
  type: NaftikoCapability
  url: capabilities/shared/procurement-list-api.yaml
created: '2024-11-20'
description: The US AbilityOne Commission is an independent federal agency that administers the AbilityOne Program, which creates employment opportunities for individuals who are blind or have significant disabilities. Operating under the Javits-Wagner-O'Day (JWOD) Act, the Commission maintains the AbilityOne Procurement List — a catalog of products and services that federal agencies are required to purchase from qualified nonprofit agencies employing people who are blind or have significant disabilities. The PLIMS (Procurement List Information Management System) provides web-based search access to the products and services list. Two central nonprofit agencies, NIB (National Industries for the Blind) and SourceAmerica, manage the affiliated nonprofit network.
features:
- description: Web-based search of the AbilityOne Procurement List by NSN, product description, agency, and nonprofit affiliate via PLIMS.
  name: Procurement List Search
- description: Searchable and downloadable catalog of products on the AbilityOne Procurement List, identified by National Stock Number (NSN).
  name: Products List
- description: Searchable catalog of services on the AbilityOne Procurement List, organized by service category and performing nonprofit agency.
  name: Services List
- description: Directory of NIB-affiliated and SourceAmerica-affiliated nonprofit agencies that employ people who are blind or have significant disabilities.
  name: Nonprofit Agency Directory
- description: Downloadable Excel reports of the Procurement List products and services, nonprofit agency rosters, and distributor lists.
  name: Reports and Data Downloads
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Central nonprofit agency managing blind-employing organizations participating in the AbilityOne program.
  name: NIB (National Industries for the Blind)
- description: Central nonprofit agency managing organizations employing people with significant disabilities in the AbilityOne program.
  name: SourceAmerica
- description: GSA procurement platform where AbilityOne products are listed and available for federal purchase.
  name: GSA Advantage
- description: System for Award Management integration for federal contract and acquisition data linked to AbilityOne awards.
  name: SAM.gov
- description: Federal Procurement Data System tracking AbilityOne program spending and contract awards across federal agencies.
  name: FPDS
jsonld:
- class_count: 23
  name: Us Abilityone Commission Context
  property_count: 16
  slug: us-abilityone-commission-context
layout: provider
modified: '2026-05-03'
name: US AbilityOne Commission
rules:
- name: US AbilityOne Commission API Rules
  rule_count: 25
  severity_counts:
    error: 7
    hint: 7
    info: 0
    warn: 11
  slug: us-abilityone-commission-spectral-rules
skills: []
slug: us-abilityone-commission
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-abilityone-commission\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-abilityone-commission/refs/heads/main/apis.yml\nname: US AbilityOne Commission\ntags:\n  - Federal Government\n  - Disability Employment\n  - Procurement\n  - Nonprofit\n  - Accessibility\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-20'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  The US AbilityOne Commission is an independent federal agency that administers\n  the AbilityOne Program, which creates employment opportunities for individuals\n  who are blind or have significant disabilities. Operating under the Javits-Wagner-O'Day\n  (JWOD) Act, the Commission maintains the AbilityOne Procurement List — a catalog\n  of products and services that federal agencies are required to purchase from\n  qualified nonprofit agencies employing people who are blind or have significant\n  disabilities.\
  \ The PLIMS (Procurement List Information Management System) provides\n  web-based search access to the products and services list. Two central nonprofit\n  agencies, NIB (National Industries for the Blind) and SourceAmerica, manage the\n  affiliated nonprofit network.\nspecificationVersion: '0.19'\napis:\n  - aid: us-abilityone-commission:procurement-list-api\n    name: AbilityOne Procurement List API\n    description: >-\n      The Procurement List Information Management System (PLIMS) provides\n      search access to the AbilityOne Procurement List — the catalog of\n      products (identified by NSN) and services that federal agencies are\n      mandated to procure from AbilityOne-participating nonprofit agencies.\n      Supports search by NSN, product description, service type, agency,\n      and nonprofit affiliate.\n    humanURL: https://plims.abilityone.gov/search-products/\n    baseURL: https://plims.abilityone.gov\n    tags:\n      - Procurement\n      - Products\n      - Services\n\
  \      - NSN\n      - Federal Acquisition\n    properties:\n      - type: Documentation\n        url: https://www.abilityone.gov/procurement_list/\n      - type: OpenAPI\n        url: openapi/abilityone-procurement-list-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/procurement-list-api-product-schema.json\n      - type: JSONSchema\n        url: json-schema/procurement-list-api-service-schema.json\ncommon:\n  - type: Website\n    url: https://www.abilityone.gov\n  - type: Portal\n    url: https://plims.abilityone.gov\n    title: PLIMS - Procurement List Information Management System\n  - type: Documentation\n    url: https://www.abilityone.gov/procurement_list/\n  - type: DataAPI\n    url: https://plims.abilityone.gov/reports/\n    title: Procurement List Data Downloads\n  - type: JSONLD\n    url: json-ld/us-abilityone-commission-context.jsonld\n  - type: SpectralRules\n    url: rules/us-abilityone-commission-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/us-abilityone-commission-vocabulary.yaml\n\
  \  - type: NaftikoCapability\n    url: capabilities/disability-employment-procurement.yaml\n    title: Disability Employment Procurement\n  - type: NaftikoCapability\n    url: capabilities/shared/procurement-list-api.yaml\n    title: Procurement List API (Shared)\n  - type: Features\n    data:\n      - name: Procurement List Search\n        description: >-\n          Web-based search of the AbilityOne Procurement List by NSN, product\n          description, agency, and nonprofit affiliate via PLIMS.\n      - name: Products List\n        description: >-\n          Searchable and downloadable catalog of products on the AbilityOne\n          Procurement List, identified by National Stock Number (NSN).\n      - name: Services List\n        description: >-\n          Searchable catalog of services on the AbilityOne Procurement List,\n          organized by service category and performing nonprofit agency.\n      - name: Nonprofit Agency Directory\n        description: >-\n          Directory\
  \ of NIB-affiliated and SourceAmerica-affiliated nonprofit\n          agencies that employ people who are blind or have significant disabilities.\n      - name: Reports and Data Downloads\n        description: >-\n          Downloadable Excel reports of the Procurement List products and services,\n          nonprofit agency rosters, and distributor lists.\n  - type: UseCases\n    data:\n      - name: Federal Acquisition Compliance\n        description: >-\n          Federal contracting officers verifying mandatory source requirements\n          for AbilityOne products and services before placing orders.\n      - name: Procurement List Lookup\n        description: >-\n          Defense and civilian agencies searching by NSN to determine if a\n          product must be procured through the AbilityOne program.\n      - name: Nonprofit Agency Discovery\n        description: >-\n          Federal buyers identifying which nonprofit agency supplies a specific\n          product or service in\
  \ their geographic region.\n      - name: Distributor Integration\n        description: >-\n          Authorized distributors accessing the Procurement List to maintain\n          current product catalogs and pricing.\n  - type: Integrations\n    data:\n      - name: NIB (National Industries for the Blind)\n        description: >-\n          Central nonprofit agency managing blind-employing organizations\n          participating in the AbilityOne program.\n      - name: SourceAmerica\n        description: >-\n          Central nonprofit agency managing organizations employing people\n          with significant disabilities in the AbilityOne program.\n      - name: GSA Advantage\n        description: >-\n          GSA procurement platform where AbilityOne products are listed\n          and available for federal purchase.\n      - name: SAM.gov\n        description: >-\n          System for Award Management integration for federal contract\n          and acquisition data linked to AbilityOne\
  \ awards.\n      - name: FPDS\n        description: >-\n          Federal Procurement Data System tracking AbilityOne program\n          spending and contract awards across federal agencies.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-abilityone-commission/refs/heads/main/apis.yml
tags:
- Federal Government
- Disability Employment
- Procurement
- Nonprofit
- Accessibility
url: https://raw.githubusercontent.com/api-evangelist/us-abilityone-commission/refs/heads/main/apis.yml
use_cases:
- description: Federal contracting officers verifying mandatory source requirements for AbilityOne products and services before placing orders.
  name: Federal Acquisition Compliance
- description: Defense and civilian agencies searching by NSN to determine if a product must be procured through the AbilityOne program.
  name: Procurement List Lookup
- description: Federal buyers identifying which nonprofit agency supplies a specific product or service in their geographic region.
  name: Nonprofit Agency Discovery
- description: Authorized distributors accessing the Procurement List to maintain current product catalogs and pricing.
  name: Distributor Integration
---
