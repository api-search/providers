---
api_count: 2
api_specs:
- filename: ariba-guided-buying-catalog-shop-api.yaml
  format: yaml
  label: Ariba Guided Buying - Public Catalogs Shop API
  slug: ariba-guided-buying-catalog-shop-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ariba-guided-buying/refs/heads/main/openapi/ariba-guided-buying-catalog-shop-api.yaml
- filename: ariba-guided-buying-asset-management-api.yaml
  format: yaml
  label: Ariba Guided Buying - Asset Management API
  slug: ariba-guided-buying-asset-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ariba-guided-buying/refs/heads/main/openapi/ariba-guided-buying-asset-management-api.yaml
apis:
- description: The Public Catalogs Shop API enables applications to retrieve data related to catalog items, filter facets, and matching search suggestions from public catalogs on SAP Business Network. This API suppo
  name: Ariba Guided Buying - Public Catalogs Shop API
  slug: ariba-guided-buying-catalog-shop-api
- description: The Asset Management API enables developers to retrieve purchase requisitions consisting of asset items and update asset data on those requisitions. This API is applicable for SAP ERP-integrated sites
  name: Ariba Guided Buying - Asset Management API
  slug: ariba-guided-buying-asset-management-api
capabilities:
- description: Unified procurement operations workflow combining catalog shopping and asset management for enterprise buyers and procurement administrators.
  name: Ariba Guided Buying - Procurement Operations
  slug: procurement-operations
common:
- title: ''
  type: Website
  url: https://www.sap.com/products/spend-management/guided-buying.html
- title: ''
  type: Documentation
  url: https://help.sap.com/docs/ariba-apis
- title: ''
  type: GettingStarted
  url: https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/sap-ariba-developer-portal-quick-start-guide-for-developers
- title: ''
  type: Portal
  url: https://developer.ariba.com
- title: ''
  type: Authentication
  url: https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/sap-ariba-developer-portal-authentication
- title: ''
  type: TermsOfService
  url: https://www.sap.com/corporate/en/legal/terms-of-use.html
- title: ''
  type: PrivacyPolicy
  url: https://www.sap.com/about/legal/privacy.html
- title: ''
  type: Support
  url: https://help.sap.com/ariba
- title: ''
  type: GitHubOrganization
  url: https://github.com/SAP-samples
- title: SAP Ariba Extensibility Samples
  type: CodeExamples
  url: https://github.com/SAP-samples/ariba-extensibility-samples
- title: ''
  type: SpectralRules
  url: rules/ariba-guided-buying-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/procurement-operations.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/ariba-guided-buying-vocabulary.yaml
created: '2024-01-01'
description: SAP Ariba Guided Buying provides a consumer-like shopping experience for enterprise procurement, enabling employees to find and purchase goods and services through an intuitive catalog-driven interface with built-in approval workflows and policy compliance.
features:
- description: Provides employees with an intuitive catalog-driven shopping interface similar to consumer e-commerce applications.
  name: Consumer-Like Shopping Experience
- description: Full-text search with typeahead autocomplete for finding catalog items from suppliers on SAP Business Network.
  name: Catalog Search and Typeahead
- description: Built-in procurement policy checks ensure purchases comply with organizational spending rules and approval workflows.
  name: Policy Compliance Enforcement
- description: Integrates with SAP ERP asset management to assign and track asset numbers on requisition line items.
  name: Asset Management Integration
- description: Secure API access using OAuth 2.0 client credentials flow with per-API credentials.
  name: OAuth 2.0 Authentication
- description: Retrieves filter facets alongside catalog items enabling refined product browsing and discovery.
  name: Faceted Search
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integrates with SAP S/4HANA Cloud Public Edition for purchase request creation and order management.
  name: SAP S/4HANA Cloud
- description: Connects to SAP Business Network to access public supplier catalogs and pricing.
  name: SAP Business Network
- description: Integrates with SAP ERP systems for asset management and purchase order creation.
  name: SAP ERP
- description: Extends SAP Ariba functionality through SAP Integration Suite for custom workflows and data transformations.
  name: SAP Integration Suite
jsonld:
- class_count: 8
  name: Ariba Guided Buying Asset Management Api Context
  property_count: 17
  slug: ariba-guided-buying-asset-management-api-context
- class_count: 7
  name: Ariba Guided Buying Catalog Shop Api Context
  property_count: 15
  slug: ariba-guided-buying-catalog-shop-api-context
layout: provider
modified: '2026-04-19'
name: Ariba Guided Buying
rules:
- name: Ariba Guided Buying API Rules
  rule_count: 34
  severity_counts:
    error: 16
    hint: 0
    info: 3
    warn: 15
  slug: ariba-guided-buying-spectral-rules
skills: []
slug: ariba-guided-buying
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ariba-guided-buying\nname: Ariba Guided Buying\ndescription: >-\n  SAP Ariba Guided Buying provides a consumer-like shopping experience for\n  enterprise procurement, enabling employees to find and purchase goods and\n  services through an intuitive catalog-driven interface with built-in approval\n  workflows and policy compliance.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - B2B\n  - Catalog\n  - ERP\n  - Procurement\n  - Requisitions\n  - SAP\n  - Supply Chain\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ariba-guided-buying/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: ariba-guided-buying:ariba-guided-buying-catalog-shop-api\n    name: Ariba Guided Buying - Public Catalogs Shop API\n    description: >-\n      The Public Catalogs Shop API enables applications to retrieve data related\n      to catalog items, filter facets,\
  \ and matching search suggestions from\n      public catalogs on SAP Business Network. This API supports SAP Ariba\n      Buying, base edition, integrated with SAP S/4HANA Cloud Public Edition.\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/catalog-shop/v1/prod\n    tags:\n      - Catalog\n      - Procurement\n      - Shopping\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/doc/f2393ece78554efab2087b984c6fa90b/cloud/en-US/5e12bd6c87f24e0781a5fcdfb410ddc6.pdf\n      - type: OpenAPI\n        url: openapi/ariba-guided-buying-catalog-shop-api.yaml\n      - type: JSONSchema\n        url: json-schema/catalog-shop-api-shop-response-schema.json\n      - type: JSONSchema\n        url: json-schema/catalog-shop-api-catalog-item-schema.json\n      - type: JSONSchema\n        url: json-schema/catalog-shop-api-facet-schema.json\n      - type: JSONSchema\n        url: json-schema/catalog-shop-api-items-response-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/catalog-shop-api-auto-complete-response-schema.json\n      - type: JSONStructure\n        url: json-structure/catalog-shop-api-shop-response-structure.json\n      - type: JSONStructure\n        url: json-structure/catalog-shop-api-catalog-item-structure.json\n      - type: JSON-LD\n        url: json-ld/ariba-guided-buying-catalog-shop-api-context.jsonld\n  - aid: ariba-guided-buying:ariba-guided-buying-asset-management-api\n    name: Ariba Guided Buying - Asset Management API\n    description: >-\n      The Asset Management API enables developers to retrieve purchase\n      requisitions consisting of asset items and update asset data on those\n      requisitions. This API is applicable for SAP ERP-integrated sites that\n      have enabled the asset management feature.\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/asset-management/v1/prod\n    tags:\n      - Asset Management\n      - ERP\n\
  \      - Procurement\n      - Requisitions\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/doc/16e046861d874557a33a1831b778d998/cloud/en-US/45d3c37cf5a643c38b9e26cc31c97470.pdf\n      - type: OpenAPI\n        url: openapi/ariba-guided-buying-asset-management-api.yaml\n      - type: JSONSchema\n        url: json-schema/asset-management-api-requisition-schema.json\n      - type: JSONSchema\n        url: json-schema/asset-management-api-asset-line-item-schema.json\n      - type: JSONSchema\n        url: json-schema/asset-management-api-batch-asset-update-request-schema.json\n      - type: JSONStructure\n        url: json-structure/asset-management-api-requisition-structure.json\n      - type: JSONStructure\n        url: json-structure/asset-management-api-asset-line-item-structure.json\n      - type: JSON-LD\n        url: json-ld/ariba-guided-buying-asset-management-api-context.jsonld\ncommon:\n  - type: Website\n    url: https://www.sap.com/products/spend-management/guided-buying.html\n\
  \  - type: Documentation\n    url: https://help.sap.com/docs/ariba-apis\n  - type: GettingStarted\n    url: https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/sap-ariba-developer-portal-quick-start-guide-for-developers\n  - type: Portal\n    url: https://developer.ariba.com\n  - type: Authentication\n    url: https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/sap-ariba-developer-portal-authentication\n  - type: TermsOfService\n    url: https://www.sap.com/corporate/en/legal/terms-of-use.html\n  - type: PrivacyPolicy\n    url: https://www.sap.com/about/legal/privacy.html\n  - type: Support\n    url: https://help.sap.com/ariba\n  - type: GitHubOrganization\n    url: https://github.com/SAP-samples\n  - type: CodeExamples\n    url: https://github.com/SAP-samples/ariba-extensibility-samples\n    title: SAP Ariba Extensibility Samples\n  - type: SpectralRules\n    url: rules/ariba-guided-buying-spectral-rules.yml\n  - type: NaftikoCapability\n    url:\
  \ capabilities/procurement-operations.yaml\n  - type: Vocabulary\n    url: vocabulary/ariba-guided-buying-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Consumer-Like Shopping Experience\n        description: Provides employees with an intuitive catalog-driven shopping interface\n          similar to consumer e-commerce applications.\n      - name: Catalog Search and Typeahead\n        description: Full-text search with typeahead autocomplete for finding catalog\n          items from suppliers on SAP Business Network.\n      - name: Policy Compliance Enforcement\n        description: Built-in procurement policy checks ensure purchases comply with\n          organizational spending rules and approval workflows.\n      - name: Asset Management Integration\n        description: Integrates with SAP ERP asset management to assign and track asset\n          numbers on requisition line items.\n      - name: OAuth 2.0 Authentication\n        description: Secure API access using\
  \ OAuth 2.0 client credentials flow with\n          per-API credentials.\n      - name: Faceted Search\n        description: Retrieves filter facets alongside catalog items enabling refined\n          product browsing and discovery.\n  - type: UseCases\n    data:\n      - name: Employee Self-Service Procurement\n        description: Enable employees to browse and purchase approved goods from\n          supplier catalogs without manual procurement processes.\n      - name: ERP Asset Record Import\n        description: Import asset records from SAP ERP and assign unique asset values to\n          line items on approved requisitions.\n      - name: Catalog Integration\n        description: Integrate SAP Ariba Buying with SAP S/4HANA Cloud Public Edition to\n          access public supplier catalogs on SAP Business Network.\n      - name: Requisition Automation\n        description: Automate retrieval and processing of asset-based requisitions through\n          the Asset Workbench workflow.\n\
  \  - type: Integrations\n    data:\n      - name: SAP S/4HANA Cloud\n        description: Integrates with SAP S/4HANA Cloud Public Edition for purchase\n          request creation and order management.\n      - name: SAP Business Network\n        description: Connects to SAP Business Network to access public supplier catalogs\n          and pricing.\n      - name: SAP ERP\n        description: Integrates with SAP ERP systems for asset management and purchase\n          order creation.\n      - name: SAP Integration Suite\n        description: Extends SAP Ariba functionality through SAP Integration Suite for\n          custom workflows and data transformations.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ariba-guided-buying/refs/heads/main/apis.yml
tags:
- B2B
- Catalog
- ERP
- Procurement
- Requisitions
- SAP
- Supply Chain
url: https://raw.githubusercontent.com/api-evangelist/ariba-guided-buying/refs/heads/main/apis.yml
use_cases:
- description: Enable employees to browse and purchase approved goods from supplier catalogs without manual procurement processes.
  name: Employee Self-Service Procurement
- description: Import asset records from SAP ERP and assign unique asset values to line items on approved requisitions.
  name: ERP Asset Record Import
- description: Integrate SAP Ariba Buying with SAP S/4HANA Cloud Public Edition to access public supplier catalogs on SAP Business Network.
  name: Catalog Integration
- description: Automate retrieval and processing of asset-based requisitions through the Asset Workbench workflow.
  name: Requisition Automation
---
