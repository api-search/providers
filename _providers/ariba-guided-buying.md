---
api_count: 2
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
