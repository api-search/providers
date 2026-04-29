---
api_count: 7
api_specs:
- filename: informatica-platform-rest-api-openapi.yml
  format: yaml
  label: Informatica Platform REST API
  slug: informatica
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/informatica/refs/heads/main/openapi/informatica-platform-rest-api-openapi.yml
apis:
- description: The Informatica Intelligent Cloud Services Platform REST API provides access to platform-level resources including login and authentication, roles and privileges, user and user group management, organ
  name: Informatica Platform REST API
  slug: informatica
- description: The Data Integration REST API provides programmatic access to manage data integration assets and operations, including connections, mappings, mapping tasks, dynamic mapping tasks, taskflows, code task
  name: Informatica Data Integration REST API
  slug: data-integration-rest-api
- description: 'The Cloud Data Governance and Catalog API enables programmatic creation and management of assets, searching for assets, and viewing asset details within Informatica Data Governance and Catalog. Calls '
  name: Informatica Cloud Data Governance and Catalog API
  slug: cloud-data-governance-and-catalog-api
- description: The Cloud Data Profiling REST API allows interaction with the Data Profiling Service through API calls to create, delete, update, and run queries and profiles within your organization. Supports platfo
  name: Informatica Cloud Data Profiling REST API
  slug: cloud-data-profiling-rest-api
- description: The Cloud Address Verification API is a REST API-based solution for verifying and validating postal addresses in real time. You can integrate the Address Verification service API endpoints into your a
  name: Informatica Cloud Address Verification API
  slug: cloud-address-verification-api
- description: The B2B Gateway REST APIs enable running inbound and outbound partner flows, querying the status of events, and getting control numbers for outbound EDI X12 and EDIFACT messages through programmatic A
  name: Informatica B2B Gateway REST API
  slug: b2b-gateway-rest-api
- description: 'The Reference 360 REST API enables programmatic management of reference data, including exporting and importing reference data sets, managing code values and value mappings, retrieving asset details, '
  name: Informatica Reference 360 REST API
  slug: reference-360-rest-api
capabilities:
- description: Unified workflow for managing data integration pipelines including connections, mappings, mapping tasks, job execution, scheduling, and activity monitoring. Used by data engineers and ETL developers.
  name: Informatica Data Integration
  slug: data-integration
common:
- title: ''
  type: Portal
  url: https://developer.informatica.com/
- title: ''
  type: Documentation
  url: https://docs.informatica.com/
- title: ''
  type: KnowledgeCenter
  url: https://knowledge.informatica.com/
- title: ''
  type: Support
  url: https://www.informatica.com/support.html
- title: Community
  type: Support
  url: https://network.informatica.com/
- title: ''
  type: Login
  url: https://dm-us.informaticacloud.com/identity-service/home
- title: ''
  type: SpectralRules
  url: rules/informatica-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/informatica-vocabulary.yaml
- title: Platform REST API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/platform-rest-api.yaml
- title: Data Integration Workflow
  type: NaftikoCapability
  url: capabilities/data-integration.yaml
created: '2025-01-08'
description: Collection of APIs for Informatica Intelligent Cloud Services (IICS) and Intelligent Data Management Cloud (IDMC), providing programmatic access to data integration, data governance, data quality, master data management, B2B gateway, and platform administration capabilities.
features:
- description: Connect, transform, and move data across cloud and on-premises environments using visual mapping interfaces.
  name: Data Integration
- description: Discover, catalog, and govern data assets with automated classification and lineage tracking.
  name: Data Governance
- description: Profile, cleanse, standardize, and validate data to ensure accuracy and consistency.
  name: Data Quality
- description: Create and manage golden records for critical business entities across the enterprise.
  name: Master Data Management
- description: Validate and standardize postal addresses globally in real time.
  name: Address Verification
- description: Exchange EDI documents with trading partners using X12, EDIFACT, and other B2B protocols.
  name: B2B Gateway
- description: Manage code lists, crosswalks, and hierarchies for standardized reference data across systems.
  name: Reference Data Management
- description: Build and manage API-led integrations connecting SaaS, cloud, and on-premises applications.
  name: API and Application Integration
image: https://companieslogo.com/img/orig/INFA-3e1d4e5a.png
integrations:
- description: Native connectors for bidirectional data integration with Salesforce CRM and platform.
  name: Salesforce
- description: Pre-built connectors for SAP ERP, S/4HANA, and SAP BW data integration.
  name: SAP
- description: Optimized connectors for loading, transforming, and managing data in Snowflake.
  name: Snowflake
- description: Native connectors for S3, Redshift, DynamoDB, and other AWS data services.
  name: Amazon Web Services
- description: Connectors for Azure SQL, Blob Storage, Synapse Analytics, and other Azure services.
  name: Microsoft Azure
- description: Connectors for BigQuery, Cloud Storage, and other GCP data services.
  name: Google Cloud Platform
- description: Pre-built connectors for Workday HCM and financial data integration.
  name: Workday
- description: Connectors for ServiceNow ITSM and platform data integration.
  name: ServiceNow
jsonld:
- class_count: 0
  name: Informatica Context
  property_count: 7
  slug: informatica-context
- class_count: 0
  name: Informatica Platform Rest Context
  property_count: 0
  slug: informatica-platform-rest-context
layout: provider
modified: '2026-04-18'
name: Informatica
rules:
- name: Informatica API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: informatica-spectral-rules
skills: []
slug: informatica
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: informatica\nname: Informatica\nsegments:\n  - iPaaS\ndescription: >-\n  Collection of APIs for Informatica Intelligent Cloud Services (IICS) and\n  Intelligent Data Management Cloud (IDMC), providing programmatic access to\n  data integration, data governance, data quality, master data management,\n  B2B gateway, and platform administration capabilities.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://companieslogo.com/img/orig/INFA-3e1d4e5a.png\ntags:\n  - Address Verification\n  - B2B Gateway\n  - Cloud Services\n  - Data Governance\n  - Data Integration\n  - Data Profiling\n  - Data Quality\n  - Enterprise Software\n  - ETL\n  - IDMC\n  - IICS\n  - Master Data Management\n  - Reference Data Management\ncreated: '2025-01-08'\nmodified: '2026-04-18'\nurl: https://raw.githubusercontent.com/api-evangelist/informatica/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: informatica:informatica\n    name: Informatica Platform REST API\n\
  \    description: >-\n      The Informatica Intelligent Cloud Services Platform REST API provides\n      access to platform-level resources including login and authentication,\n      roles and privileges, user and user group management, organizations,\n      connections, schedules, runtime environments, Secure Agent services,\n      object permissions, export and import, source control, projects and\n      folders, licenses, metering data, and security logs. Supports version 2\n      (JSON and XML) and version 3 (JSON) resource formats.\n    humanURL: https://docs.informatica.com/integration-cloud/cloud-platform/current-version/rest-api-reference/informatica-intelligent-cloud-services-rest-api.html\n    tags:\n      - Authentication\n      - Platform\n      - Roles\n      - Users\n    properties:\n      - type: Documentation\n        url: https://docs.informatica.com/integration-cloud/cloud-platform/current-version/rest-api-reference/informatica-intelligent-cloud-services-rest-api.html\n\
  \      - type: Documentation\n        url: https://docs.informatica.com/integration-cloud/b2b-gateway/current-version/rest-api-reference/platform-rest-api-version-3-resources.html\n        title: Platform REST API v3\n      - type: Documentation\n        url: https://docs.informatica.com/integration-cloud/b2b-gateway/current-version/rest-api-reference/platform-rest-api-version-3-resources/roles.html\n        title: Roles API\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/informatica/refs/heads/main/openapi/informatica-platform-rest-api-openapi.yml\n      - type: OpenAPI\n        url: openapi/informatica-platform-rest-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/informatica-connection-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-login-request-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-login-response-schema.json\n      - type: JSONSchema\n\
  \        url: json-schema/informatica-platform-rest-connection-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-connection-create-request-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-connection-update-request-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-mapping-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-mapping-parameter-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-mapping-in-out-parameter-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-mapping-task-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-mapping-task-create-request-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-mapping-task-update-request-schema.json\n      - type: JSONSchema\n     \
  \   url: json-schema/informatica-platform-rest-job-start-request-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-job-start-response-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-job-stop-request-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-activity-log-entry-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-schedule-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-schedule-create-request-schema.json\n      - type: JSONSchema\n        url: json-schema/informatica-platform-rest-error-response-schema.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-login-request-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-login-response-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-connection-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-connection-create-request-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-connection-update-request-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-mapping-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-mapping-parameter-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-mapping-in-out-parameter-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-mapping-task-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-mapping-task-create-request-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-mapping-task-update-request-structure.json\n      - type: JSONStructure\n     \
  \   url: json-structure/informatica-platform-rest-job-start-request-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-job-start-response-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-job-stop-request-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-activity-log-entry-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-schedule-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-schedule-create-request-structure.json\n      - type: JSONStructure\n        url: json-structure/informatica-platform-rest-error-response-structure.json\n      - type: Example\n        url: examples/informatica-platform-rest-login-request-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-login-response-example.json\n      - type: Example\n\
  \        url: examples/informatica-platform-rest-connection-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-connection-create-request-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-connection-update-request-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-mapping-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-mapping-parameter-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-mapping-in-out-parameter-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-mapping-task-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-mapping-task-create-request-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-mapping-task-update-request-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-job-start-request-example.json\n\
  \      - type: Example\n        url: examples/informatica-platform-rest-job-start-response-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-job-stop-request-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-activity-log-entry-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-schedule-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-schedule-create-request-example.json\n      - type: Example\n        url: examples/informatica-platform-rest-error-response-example.json\n      - type: JSONLD\n        url: json-ld/informatica-context.jsonld\n      - type: JSONLD\n        url: json-ld/informatica-platform-rest-context.jsonld\n  - aid: informatica:data-integration-rest-api\n    name: Informatica Data Integration REST API\n    description: >-\n      The Data Integration REST API provides programmatic access to manage\n      data integration assets and operations,\
  \ including connections, mappings,\n      mapping tasks, dynamic mapping tasks, taskflows, code tasks, connectors,\n      data preview, fields, file listeners, file transfer, and hierarchical\n      mappers. Uses version 2 resources with JSON or XML format.\n    humanURL: https://docs.informatica.com/integration-cloud/data-integration/current-version/rest-api-reference/data-integration-rest-api.html\n    tags:\n      - Connections\n      - Data Integration\n      - ETL\n      - Mappings\n    properties:\n      - type: Documentation\n        url: https://docs.informatica.com/integration-cloud/data-integration/current-version/rest-api-reference/data-integration-rest-api.html\n      - type: APIReference\n        url: https://docs.informatica.com/integration-cloud/data-integration/current-version/rest-api-reference/rest-api-resource-quick-references/data-integration-resource-quick-reference.html\n  - aid: informatica:cloud-data-governance-and-catalog-api\n    name: Informatica Cloud Data Governance\
  \ and Catalog API\n    description: >-\n      The Cloud Data Governance and Catalog API enables programmatic creation\n      and management of assets, searching for assets, and viewing asset\n      details within Informatica Data Governance and Catalog. Calls can be\n      made using a REST client, the cURL tool, or a suitable programming\n      interface.\n    humanURL: https://docs.informatica.com/data-quality-cloud/cloud-data-governance-and-catalog/current-version.html\n    tags:\n      - Data Catalog\n      - Data Governance\n    properties:\n      - type: Documentation\n        url: https://docs.informatica.com/data-quality-cloud/cloud-data-governance-and-catalog/current-version.html\n  - aid: informatica:cloud-data-profiling-rest-api\n    name: Informatica Cloud Data Profiling REST API\n    description: >-\n      The Cloud Data Profiling REST API allows interaction with the Data\n      Profiling Service through API calls to create, delete, update, and\n      run queries and profiles\
  \ within your organization. Supports platform\n      REST API version 2 and version 3 resources and service-specific\n      resources.\n    humanURL: https://docs.informatica.com/data-governance-and-quality-cloud/cloud-data-profiling/current-version/data-profiling/data-profiling/data-profiling-rest-api.html\n    tags:\n      - Data Profiling\n      - Data Quality\n    properties:\n      - type: Documentation\n        url: https://docs.informatica.com/data-governance-and-quality-cloud/cloud-data-profiling/current-version/data-profiling/data-profiling/data-profiling-rest-api.html\n      - type: GettingStarted\n        url: https://docs.informatica.com/data-governance-and-quality-cloud/cloud-data-profiling/h2l/1547-getting-started-with-cloud-data-profiling-rest-api/getting-started-with-cloud-data-profiling-rest-api/overview.html\n  - aid: informatica:cloud-address-verification-api\n    name: Informatica Cloud Address Verification API\n    description: >-\n      The Cloud Address Verification\
  \ API is a REST API-based solution for\n      verifying and validating postal addresses in real time. You can integrate\n      the Address Verification service API endpoints into your application\n      using a REST client, the cURL tool, or any suitable programming\n      interface.\n    humanURL: https://docs.informatica.com/data-governance-and-quality-cloud/data-quality/current-version/cloud-address-verification-api/introduction.html\n    tags:\n      - Address Verification\n      - Data Quality\n    properties:\n      - type: Documentation\n        url: https://docs.informatica.com/data-governance-and-quality-cloud/data-quality/current-version/cloud-address-verification-api/introduction.html\n  - aid: informatica:b2b-gateway-rest-api\n    name: Informatica B2B Gateway REST API\n    description: >-\n      The B2B Gateway REST APIs enable running inbound and outbound partner\n      flows, querying the status of events, and getting control numbers for\n      outbound EDI X12 and EDIFACT\
  \ messages through programmatic API calls.\n    humanURL: https://docs.informatica.com/ipaas/b2b-gateway/current-version/rest-api-reference/informatica-intelligent-cloud-services-rest-api.html\n    tags:\n      - B2B\n      - EDI\n      - Gateway\n    properties:\n      - type: Documentation\n        url: https://docs.informatica.com/ipaas/b2b-gateway/current-version/rest-api-reference/informatica-intelligent-cloud-services-rest-api.html\n  - aid: informatica:reference-360-rest-api\n    name: Informatica Reference 360 REST API\n    description: >-\n      The Reference 360 REST API enables programmatic management of reference\n      data, including exporting and importing reference data sets, managing\n      code values and value mappings, retrieving asset details, managing code\n      lists, crosswalks, hierarchies, and audit trails. Supports multiple API\n      versions for model import and export operations.\n    humanURL: https://docs.informatica.com/master-data-management-cloud/reference-360/current-version/reference-360/reference-360-rest-api.html\n\
  \    tags:\n      - Master Data Management\n      - Reference Data\n    properties:\n      - type: Documentation\n        url: https://docs.informatica.com/master-data-management-cloud/reference-360/current-version/reference-360/reference-360-rest-api.html\ncommon:\n  - type: Portal\n    url: https://developer.informatica.com/\n  - type: Documentation\n    url: https://docs.informatica.com/\n  - type: KnowledgeCenter\n    url: https://knowledge.informatica.com/\n  - type: Support\n    url: https://www.informatica.com/support.html\n  - type: Support\n    url: https://network.informatica.com/\n    title: Community\n  - type: Login\n    url: https://dm-us.informaticacloud.com/identity-service/home\n  - type: SpectralRules\n    url: rules/informatica-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/informatica-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/shared/platform-rest-api.yaml\n    title: Platform REST API Shared Definition\n  - type: NaftikoCapability\n\
  \    url: capabilities/data-integration.yaml\n    title: Data Integration Workflow\n  - type: Features\n    data:\n      - name: Data Integration\n        description: Connect, transform, and move data across cloud and on-premises environments using visual mapping interfaces.\n      - name: Data Governance\n        description: Discover, catalog, and govern data assets with automated classification and lineage tracking.\n      - name: Data Quality\n        description: Profile, cleanse, standardize, and validate data to ensure accuracy and consistency.\n      - name: Master Data Management\n        description: Create and manage golden records for critical business entities across the enterprise.\n      - name: Address Verification\n        description: Validate and standardize postal addresses globally in real time.\n      - name: B2B Gateway\n        description: Exchange EDI documents with trading partners using X12, EDIFACT, and other B2B protocols.\n      - name: Reference Data Management\n\
  \        description: Manage code lists, crosswalks, and hierarchies for standardized reference data across systems.\n      - name: API and Application Integration\n        description: Build and manage API-led integrations connecting SaaS, cloud, and on-premises applications.\n  - type: UseCases\n    data:\n      - name: Cloud Data Warehouse Loading\n        description: Extract data from multiple sources and load into cloud data warehouses like Snowflake, Redshift, or BigQuery.\n      - name: Real-Time Data Synchronization\n        description: Synchronize data across CRM, ERP, and marketing platforms in real time using change data capture.\n      - name: Data Migration\n        description: Migrate data between legacy systems and modern cloud platforms with automated mapping and transformation.\n      - name: Regulatory Compliance\n        description: Ensure data quality and governance standards to meet GDPR, CCPA, and industry-specific regulations.\n      - name: Customer 360\n  \
  \      description: Create unified customer profiles by integrating and matching data from multiple source systems.\n  - type: Integrations\n    data:\n      - name: Salesforce\n        description: Native connectors for bidirectional data integration with Salesforce CRM and platform.\n      - name: SAP\n        description: Pre-built connectors for SAP ERP, S/4HANA, and SAP BW data integration.\n      - name: Snowflake\n        description: Optimized connectors for loading, transforming, and managing data in Snowflake.\n      - name: Amazon Web Services\n        description: Native connectors for S3, Redshift, DynamoDB, and other AWS data services.\n      - name: Microsoft Azure\n        description: Connectors for Azure SQL, Blob Storage, Synapse Analytics, and other Azure services.\n      - name: Google Cloud Platform\n        description: Connectors for BigQuery, Cloud Storage, and other GCP data services.\n      - name: Workday\n        description: Pre-built connectors for Workday\
  \ HCM and financial data integration.\n      - name: ServiceNow\n        description: Connectors for ServiceNow ITSM and platform data integration.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/informatica/refs/heads/main/apis.yml
tags:
- Address Verification
- B2B Gateway
- Cloud Services
- Data Governance
- Data Integration
- Data Profiling
- Data Quality
- Enterprise Software
- ETL
- IDMC
- IICS
- Master Data Management
- Reference Data Management
url: https://raw.githubusercontent.com/api-evangelist/informatica/refs/heads/main/apis.yml
use_cases:
- description: Extract data from multiple sources and load into cloud data warehouses like Snowflake, Redshift, or BigQuery.
  name: Cloud Data Warehouse Loading
- description: Synchronize data across CRM, ERP, and marketing platforms in real time using change data capture.
  name: Real-Time Data Synchronization
- description: Migrate data between legacy systems and modern cloud platforms with automated mapping and transformation.
  name: Data Migration
- description: Ensure data quality and governance standards to meet GDPR, CCPA, and industry-specific regulations.
  name: Regulatory Compliance
- description: Create unified customer profiles by integrating and matching data from multiple source systems.
  name: Customer 360
---
