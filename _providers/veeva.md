---
api_count: 4
api_specs:
- filename: veeva-vault-openapi.yml
  format: yaml
  label: Veeva Vault Platform API
  slug: veeva-vault-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/openapi/veeva-vault-openapi.yml
- filename: veeva-vault-openapi.yml
  format: yaml
  label: Veeva Vault Query Language (VQL) API
  slug: veeva-vault-query-language
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/openapi/veeva-vault-openapi.yml
apis:
- description: Veeva Vault provides life sciences cloud platform APIs for regulatory document management, quality management (QMS), clinical operations, and commercial content management. REST APIs enable document l
  name: Veeva Vault Platform API
  slug: veeva-vault-api
- description: 'The Veeva Vault Java SDK (VAPIL) is an open-source Java-based REST API client for the Vault REST API. Provides type-safe access to all Vault API operations including document management, object CRUD, '
  name: Veeva Vault Java SDK
  slug: veeva-vault-java-sdk
- description: Vault Query Language (VQL) provides SQL-like query capabilities for accessing and retrieving Vault data. Supports SELECT, FROM, WHERE, ORDER BY, relationship queries, and functions for querying docume
  name: Veeva Vault Query Language (VQL) API
  slug: veeva-vault-query-language
- description: 'The Veeva Vault Direct Data API provides high-speed, read-only bulk access to Vault data for integration, analytics, and reporting purposes. Supports bulk export of documents, objects, and attachment '
  name: Veeva Vault Direct Data API
  slug: veeva-vault-direct-data-api
capabilities:
- description: Customer workflow capability for life sciences document lifecycle management in Veeva Vault. Combines document CRUD, lifecycle actions, VQL queries, and object management for regulatory affairs teams,
  name: Veeva Vault Document Management
  slug: vault-document-management
common:
- title: ''
  type: Website
  url: https://www.veeva.com/
- title: ''
  type: Portal
  url: https://developer.veevavault.com/
- title: ''
  type: Documentation
  url: https://developer.veevavault.com/docs
- title: ''
  type: GettingStarted
  url: https://developer.veevavault.com/docs
- title: ''
  type: Authentication
  url: https://developer.veevavault.com/api/25.3/
- title: ''
  type: ChangeLog
  url: https://developer.veevavault.com/rn/25.3/
- title: ''
  type: SDKs
  url: https://developer.veevavault.com/sdk/
- title: ''
  type: Support
  url: https://support.veeva.com/hc/en-us
- title: ''
  type: PrivacyPolicy
  url: https://www.veeva.com/privacy/
- title: ''
  type: GitHubOrganization
  url: https://github.com/veeva
- title: Vault Document Schema
  type: JSONSchema
  url: json-schema/veeva-vault-document-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/veeva-context.jsonld
- title: Veeva Vault API Spectral Rules
  type: SpectralRules
  url: rules/veeva-spectral-rules.yml
- title: Veeva Vocabulary
  type: Vocabulary
  url: vocabulary/veeva-vocabulary.yml
- title: Vault Document Management
  type: NaftikoCapability
  url: capabilities/vault-document-management.yaml
created: ''
description: Veeva Systems is a leader in cloud-based software for the global life sciences industry, providing solutions to help pharmaceutical and biotechnology companies bring products to market more efficiently.
features:
- description: Full lifecycle management for controlled documents including draft, review, approval, and archival states with audit trails for regulatory compliance.
  name: Document Lifecycle Management
- description: SQL-like query engine for retrieving Vault data across documents, objects, users, and workflows with support for relationship traversal.
  name: Vault Query Language
- description: High-speed bulk data export for up to 500 records at a time for analytics, reporting, and integration with downstream systems.
  name: Direct Data API
- description: Create, read, update, and delete operations on configurable Vault business objects (studies, products, sites, etc.) via REST API.
  name: Vault Object CRUD
- description: Username/password authentication returning a session ID for subsequent API calls, with multi-vault support for complex enterprise deployments.
  name: Session Authentication
- description: Open-source Java client library providing type-safe access to all Vault REST API operations with automatic session management and error handling.
  name: Java SDK (VAPIL)
image: ''
integrations:
- description: Bidirectional integration between Vault and Veeva CRM for commercial content lifecycle management and promotional material approval workflows.
  name: Veeva CRM
- description: Connect Vault document approval workflows with Salesforce opportunities, accounts, and contacts via REST API integration.
  name: Salesforce
- description: Synchronize quality events, deviations, and regulatory submissions between Vault and SAP ERP using REST API and Direct Data API.
  name: SAP
- description: Pre-built MuleSoft connectors for Vault REST API integration with enterprise middleware platforms and iPaaS solutions.
  name: MuleSoft
- description: Deploy Vault integrations on Azure using Logic Apps, Azure Functions, or Azure Data Factory with Vault REST API support.
  name: Microsoft Azure
jsonld:
- class_count: 25
  name: Veeva Context
  property_count: 7
  slug: veeva-context
layout: provider
modified: '2026-05-03'
name: veeva
rules:
- name: veeva API Rules
  rule_count: 34
  severity_counts:
    error: 11
    hint: 0
    info: 4
    warn: 19
  slug: veeva-spectral-rules
skills: []
slug: veeva
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: veeva\nurl: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/apis.yml\napis:\n  - aid: veeva:veeva-vault-api\n    name: Veeva Vault Platform API\n    tags:\n      - Clinical\n      - Life Sciences\n      - Pharma\n      - QMS\n      - Regulatory\n    image: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/image.png\n    humanURL: https://developer.veevavault.com/\n    baseURL: https://myvault.veevavault.com/api/v25.3\n    properties:\n      - url: https://developer.veevavault.com/\n        type: Portal\n      - url: https://developer.veevavault.com/docs\n        type: Documentation\n      - url: https://developer.veevavault.com/api/25.3/\n        type: Reference\n      - url: https://developer.veevavault.com/api/25.3/\n        type: Authentication\n      - url: https://developer.veevavault.com/rn/25.3/\n        type: ChangeLog\n      - url: https://developer.veevavault.com/docs\n        type: GettingStarted\n      - url: openapi/veeva-vault-openapi.yml\n\
  \        type: OpenAPI\n      - url: json-schema/veeva-vault-auth-response-schema.json\n        type: JSONSchema\n        title: Auth Response Schema\n      - url: json-schema/veeva-vault-document-fields-schema.json\n        type: JSONSchema\n        title: Document Fields Schema\n      - url: json-schema/veeva-vault-document-list-response-schema.json\n        type: JSONSchema\n        title: Document List Response Schema\n      - url: json-schema/veeva-vault-document-create-response-schema.json\n        type: JSONSchema\n        title: Document Create Response Schema\n      - url: json-schema/veeva-vault-document-update-response-schema.json\n        type: JSONSchema\n        title: Document Update Response Schema\n      - url: json-schema/veeva-vault-document-response-schema.json\n        type: JSONSchema\n        title: Document Response Schema\n      - url: json-schema/veeva-vault-object-list-response-schema.json\n        type: JSONSchema\n        title: Object List Response Schema\n\
  \      - url: json-schema/veeva-vault-object-create-response-schema.json\n        type: JSONSchema\n        title: Object Create Response Schema\n      - url: json-schema/veeva-vault-object-record-response-schema.json\n        type: JSONSchema\n        title: Object Record Response Schema\n      - url: json-schema/veeva-vault-query-response-schema.json\n        type: JSONSchema\n        title: Query Response Schema\n      - url: json-schema/veeva-vault-user-list-response-schema.json\n        type: JSONSchema\n        title: User List Response Schema\n      - url: json-structure/veeva-vault-auth-response-structure.json\n        type: JSONStructure\n        title: Auth Response Structure\n      - url: json-structure/veeva-vault-document-fields-structure.json\n        type: JSONStructure\n        title: Document Fields Structure\n      - url: json-structure/veeva-vault-document-list-response-structure.json\n        type: JSONStructure\n        title: Document List Response Structure\n   \
  \   - url: json-structure/veeva-vault-query-response-structure.json\n        type: JSONStructure\n        title: Query Response Structure\n      - url: examples/veeva-vault-auth-response-example.json\n        type: Example\n        title: Auth Response Example\n      - url: examples/veeva-vault-document-fields-example.json\n        type: Example\n        title: Document Fields Example\n      - url: examples/veeva-vault-document-list-response-example.json\n        type: Example\n        title: Document List Response Example\n      - url: examples/veeva-vault-query-response-example.json\n        type: Example\n        title: Query Response Example\n    description: >-\n      Veeva Vault provides life sciences cloud platform APIs for regulatory document\n      management, quality management (QMS), clinical operations, and commercial content\n      management. REST APIs enable document lifecycle management, workflow automation,\n      and compliance-validated data exchange.\n\n  - aid: veeva:veeva-vault-java-sdk\n\
  \    name: Veeva Vault Java SDK\n    tags:\n      - Java\n      - Life Sciences\n      - Pharma\n      - SDK\n    image: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/image.png\n    humanURL: https://developer.veevavault.com/sdk/\n    baseURL: https://myvault.veevavault.com/api\n    properties:\n      - url: https://developer.veevavault.com/sdk/\n        type: Documentation\n      - url: https://github.com/veeva/vault-api-library\n        type: SDKs\n      - url: https://mvnrepository.com/artifact/com.veeva/vault-api-library\n        type: SDKs\n        title: Maven Central\n    description: >-\n      The Veeva Vault Java SDK (VAPIL) is an open-source Java-based REST API client\n      for the Vault REST API. Provides type-safe access to all Vault API operations\n      including document management, object CRUD, workflow execution, and administrative\n      functions.\n\n  - aid: veeva:veeva-vault-query-language\n    name: Veeva Vault Query Language (VQL) API\n\
  \    tags:\n      - Life Sciences\n      - Pharma\n      - Query Language\n      - SQL\n    image: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/image.png\n    humanURL: https://developer.veevavault.com/vql/\n    baseURL: https://myvault.veevavault.com/api\n    properties:\n      - url: https://developer.veevavault.com/vql/\n        type: Documentation\n      - url: openapi/veeva-vault-openapi.yml\n        type: OpenAPI\n    description: >-\n      Vault Query Language (VQL) provides SQL-like query capabilities for accessing\n      and retrieving Vault data. Supports SELECT, FROM, WHERE, ORDER BY, relationship\n      queries, and functions for querying documents, objects, users, workflows, and\n      system data.\n\n  - aid: veeva:veeva-vault-direct-data-api\n    name: Veeva Vault Direct Data API\n    tags:\n      - Bulk Data\n      - Data Access\n      - Life Sciences\n      - Pharma\n    image: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/image.png\n\
  \    humanURL: https://developer.veevavault.com/docs\n    baseURL: https://myvault.veevavault.com/api\n    properties:\n      - url: https://developer.veevavault.com/docs\n        type: Documentation\n    description: >-\n      The Veeva Vault Direct Data API provides high-speed, read-only bulk access to\n      Vault data for integration, analytics, and reporting purposes. Supports bulk\n      export of documents, objects, and attachment field files for up to 500 records.\n\ncommon:\n  - url: https://www.veeva.com/\n    type: Website\n  - url: https://developer.veevavault.com/\n    type: Portal\n  - url: https://developer.veevavault.com/docs\n    type: Documentation\n  - url: https://developer.veevavault.com/docs\n    type: GettingStarted\n  - url: https://developer.veevavault.com/api/25.3/\n    type: Authentication\n  - url: https://developer.veevavault.com/rn/25.3/\n    type: ChangeLog\n  - url: https://developer.veevavault.com/sdk/\n    type: SDKs\n  - url: https://support.veeva.com/hc/en-us\n\
  \    type: Support\n  - url: https://www.veeva.com/privacy/\n    type: PrivacyPolicy\n  - url: https://github.com/veeva\n    type: GitHubOrganization\n  - url: json-schema/veeva-vault-document-schema.json\n    type: JSONSchema\n    title: Vault Document Schema\n  - url: json-ld/veeva-context.jsonld\n    type: JSONLDContext\n  - url: rules/veeva-spectral-rules.yml\n    type: SpectralRules\n    title: Veeva Vault API Spectral Rules\n  - url: vocabulary/veeva-vocabulary.yml\n    type: Vocabulary\n    title: Veeva Vocabulary\n  - url: capabilities/vault-document-management.yaml\n    type: NaftikoCapability\n    title: Vault Document Management\n  - type: Features\n    data:\n      - name: Document Lifecycle Management\n        description: >-\n          Full lifecycle management for controlled documents including draft, review,\n          approval, and archival states with audit trails for regulatory compliance.\n      - name: Vault Query Language\n        description: >-\n          SQL-like\
  \ query engine for retrieving Vault data across documents, objects,\n          users, and workflows with support for relationship traversal.\n      - name: Direct Data API\n        description: >-\n          High-speed bulk data export for up to 500 records at a time for analytics,\n          reporting, and integration with downstream systems.\n      - name: Vault Object CRUD\n        description: >-\n          Create, read, update, and delete operations on configurable Vault business\n          objects (studies, products, sites, etc.) via REST API.\n      - name: Session Authentication\n        description: >-\n          Username/password authentication returning a session ID for subsequent API\n          calls, with multi-vault support for complex enterprise deployments.\n      - name: Java SDK (VAPIL)\n        description: >-\n          Open-source Java client library providing type-safe access to all Vault\n          REST API operations with automatic session management and error handling.\n\
  \  - type: UseCases\n    data:\n      - name: Regulatory Document Submission\n        description: >-\n          Automate the assembly and submission of regulatory dossiers (CTD, eCTD)\n          by programmatically managing document lifecycle, approvals, and publishing.\n      - name: Clinical Trial Data Management\n        description: >-\n          Integrate Vault with CTMS, EDC, and LIMS systems to automate study document\n          workflows, protocol amendments, and site activation packages.\n      - name: Quality Management Automation\n        description: >-\n          Automate SOPs, CAPAs, deviations, and audit workflows in QMS Vault through\n          lifecycle actions, object creation, and workflow task assignment.\n      - name: Content Analytics\n        description: >-\n          Export Vault document and object data in bulk for BI dashboards, compliance\n          reporting, and cross-Vault analytics using the Direct Data API.\n      - name: Enterprise Integration\n    \
  \    description: >-\n          Integrate Vault with SAP, Salesforce, Veeva CRM, and other enterprise\n          systems using REST APIs for bidirectional data synchronization.\n  - type: Integrations\n    data:\n      - name: Veeva CRM\n        description: >-\n          Bidirectional integration between Vault and Veeva CRM for commercial content\n          lifecycle management and promotional material approval workflows.\n      - name: Salesforce\n        description: >-\n          Connect Vault document approval workflows with Salesforce opportunities,\n          accounts, and contacts via REST API integration.\n      - name: SAP\n        description: >-\n          Synchronize quality events, deviations, and regulatory submissions between\n          Vault and SAP ERP using REST API and Direct Data API.\n      - name: MuleSoft\n        description: >-\n          Pre-built MuleSoft connectors for Vault REST API integration with enterprise\n          middleware platforms and iPaaS solutions.\n\
  \      - name: Microsoft Azure\n        description: >-\n          Deploy Vault integrations on Azure using Logic Apps, Azure Functions, or\n          Azure Data Factory with Vault REST API support.\n\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n\nmodified: '2026-05-03'\ndescription: >-\n  Veeva Systems is a leader in cloud-based software for the global life sciences industry,\n  providing solutions to help pharmaceutical and biotechnology companies bring products\n  to market more efficiently.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/apis.yml
use_cases:
- description: Automate the assembly and submission of regulatory dossiers (CTD, eCTD) by programmatically managing document lifecycle, approvals, and publishing.
  name: Regulatory Document Submission
- description: Integrate Vault with CTMS, EDC, and LIMS systems to automate study document workflows, protocol amendments, and site activation packages.
  name: Clinical Trial Data Management
- description: Automate SOPs, CAPAs, deviations, and audit workflows in QMS Vault through lifecycle actions, object creation, and workflow task assignment.
  name: Quality Management Automation
- description: Export Vault document and object data in bulk for BI dashboards, compliance reporting, and cross-Vault analytics using the Direct Data API.
  name: Content Analytics
- description: Integrate Vault with SAP, Salesforce, Veeva CRM, and other enterprise systems using REST APIs for bidirectional data synchronization.
  name: Enterprise Integration
---
