---
api_count: 6
api_specs:
- filename: overview
  format: yaml
  label: SAP Analytics Cloud API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_ANALYTICS_CLOUD/overview
- filename: overview
  format: yaml
  label: SAP BusinessObjects BI Platform REST API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/BOBJ_BIPLATFORM/overview
- filename: sap-bi-bw4hana-odata-openapi.yml
  format: yaml
  label: SAP BW/4HANA OData API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-bi/refs/heads/main/openapi/sap-bi-bw4hana-odata-openapi.yml
- filename: overview
  format: yaml
  label: SAP Datasphere API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/datasphere/overview
apis:
- description: REST API for SAP Analytics Cloud enabling data integration, story management, and analytics operations.
  name: SAP Analytics Cloud API
  slug: ''
- description: RESTful web services for SAP BusinessObjects BI Platform administration, content management, and reporting.
  name: SAP BusinessObjects BI Platform REST API
  slug: ''
- description: APIs for building analytics applications on SAP HANA XS Advanced platform.
  name: SAP HANA XS Advanced API
  slug: ''
- description: OData services for accessing SAP BW/4HANA data warehouse content and metadata.
  name: SAP BW/4HANA OData API
  slug: ''
- description: APIs for SAP Datasphere (formerly SAP Data Warehouse Cloud) for data integration and analytics.
  name: SAP Datasphere API
  slug: ''
- description: APIs for embedding and automating SAP Crystal Reports in applications.
  name: SAP Crystal Reports API
  slug: ''
capabilities:
- description: 'Workflow capability for creating, managing, and distributing analytics content across SAP Analytics Cloud and SAP BusinessObjects BI Platform. Supports story authoring, report scheduling, and content '
  name: SAP Business Intelligence Analytics and Reporting
  slug: analytics-and-reporting
- description: Workflow capability for accessing and querying data from SAP BW/4HANA data warehouse and SAP Datasphere platform. Enables data discovery, model browsing, connection management, and analytical data con
  name: SAP Business Intelligence Data Warehouse Access
  slug: data-warehouse-access
common:
- title: ''
  type: Portal
  url: https://api.sap.com/
- title: ''
  type: Authentication
  url: https://help.sap.com/docs/SAP_CLOUD_PLATFORM/65de2977205c403bbc107264b8eccf4b/3670474a58c24ac2b082e76cbbd9dc19.html
- title: ''
  type: Support
  url: https://support.sap.com/en/index.html
- title: ''
  type: Community
  url: https://community.sap.com/
- title: ''
  type: Terms of Service
  url: https://www.sap.com/about/legal/terms-of-use.html
- title: ''
  type: Privacy Policy
  url: https://www.sap.com/about/legal/privacy.html
- title: ''
  type: OpenAPI
  url: openapi/sap-bi-analytics-cloud-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/sap-bi-businessobjects-platform-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/sap-bi-bw4hana-odata-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/sap-bi-datasphere-openapi.yml
- title: ''
  type: JSON-LD
  url: json-ld/sap-bi-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/sap-bi-story-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sap-bi-report-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sap-bi-data-source-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/sap-bi-story-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/sap-bi-space-structure.json
- title: ''
  type: SpectralRules
  url: rules/sap-bi-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/analytics-and-reporting.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/data-warehouse-access.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/sap-bi-vocabulary.yml
created: '2024'
description: Collection of APIs for SAP Business Intelligence (BI) platform, including analytics, reporting, and data visualization services.
features: []
image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg
integrations: []
jsonld:
- class_count: 0
  name: Sap Bi Context
  property_count: 9
  slug: sap-bi-context
layout: provider
modified: '2026-05-02'
name: SAP Business Intelligence
rules:
- name: SAP Business Intelligence API Rules
  rule_count: 10
  severity_counts:
    error: 1
    hint: 0
    info: 3
    warn: 6
  slug: sap-bi-rules
skills: []
slug: sap-bi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SAP Business Intelligence\ndescription: >-\n  Collection of APIs for SAP Business Intelligence (BI) platform, including analytics,\n  reporting, and data visualization services.\nimage: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\nurl: https://api.sap.com/business-intelligence\ntags:\n  - Analytics\n  - Business Intelligence\n  - Data Visualization\n  - Reporting\n  - SAP\ncreated: '2024'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\napis:\n  - name: SAP Analytics Cloud API\n    description: >-\n      REST API for SAP Analytics Cloud enabling data integration, story management,\n      and analytics operations.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD\n    baseURL: https://[tenant].sapanalytics.cloud/api/v1\n    tags:\n      - Analytics\n      - Cloud\n      - Dashboards\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/14cac91febef464dbb1efce20e3f1613/147c1fd5bb3-4f8ba65b37acf1d6dbce.html\n\
  \      - type: OpenAPI\n        url: https://api.sap.com/api/API_ANALYTICS_CLOUD/overview\n      - type: Authentication\n        url: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/00f68c2e08b941f081002fd3691d86a7/c7e7c53f91bb41f8bd1440afd47ca49e.html\n      - type: Swagger\n        url: https://[tenant].sapanalytics.cloud/api/v1/swagger-ui.html\n      - type: OpenAPI\n        url: openapi/sap-bi-analytics-cloud-openapi.yml\n  - name: SAP BusinessObjects BI Platform REST API\n    description: >-\n      RESTful web services for SAP BusinessObjects BI Platform administration, content\n      management, and reporting.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM\n    baseURL: https://[server]:[port]/biprws\n    tags:\n      - BusinessObjects\n      - Platform Administration\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM/ca1da879759d4c76894329a42c5b88c3/5051e4f36d6d1014b3fc9283b0e91070.html\n\
  \      - type: OpenAPI\n        url: https://api.sap.com/api/BOBJ_BIPLATFORM/overview\n      - type: SDK Documentation\n        url: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM/ca1da879759d4c76894329a42c5b88c3/49e9e7f26d6d1014910c91fa5b0c2cc3.html\n      - type: Authentication\n        url: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM/ca1da879759d4c76894329a42c5b88c3/4f0990926d6d1014a74b9c23f567b6f4.html\n      - type: OpenAPI\n        url: openapi/sap-bi-businessobjects-platform-openapi.yml\n  - name: SAP HANA XS Advanced API\n    description: >-\n      APIs for building analytics applications on SAP HANA XS Advanced platform.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_HANA_PLATFORM\n    baseURL: https://[host]:[port]\n    tags:\n      - Analytics\n      - Database\n      - HANA\n      - XS Advanced\n    properties:\n      - type: Documentation\n\
  \        url: https://help.sap.com/docs/SAP_HANA_PLATFORM/4505d0bdaf4948449b7f7379d24d0f0d/df19a03dc07e4ba19db4e0006c1da429.html\n      - type: Developer Guide\n        url: https://help.sap.com/docs/SAP_HANA_PLATFORM/4505d0bdaf4948449b7f7379d24d0f0d/3ec885c07e844d9fb4f40e3c4af0adb8.html\n      - type: API Reference\n        url: https://help.sap.com/docs/SAP_HANA_PLATFORM/4505d0bdaf4948449b7f7379d24d0f0d/c102c07e04c541cc906f5fcdb3e02105.html\n  - name: SAP BW/4HANA OData API\n    description: >-\n      OData services for accessing SAP BW/4HANA data warehouse content and metadata.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_BW4HANA\n    baseURL: https://[server]:[port]/sap/opu/odata/sap/\n    tags:\n      - BW/4HANA\n      - Data Warehouse\n      - ETL\n      - OData\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_BW4HANA/107a6e8a38b74ede94c833ca3b7b6f51/5e467a851e874e48afcfa4cc88b5dd28.html\n\
  \      - type: OData Reference\n        url: https://api.sap.com/package/SAPBW4HANA/odata\n      - type: Integration Guide\n        url: https://help.sap.com/docs/SAP_BW4HANA/107a6e8a38b74ede94c833ca3b7b6f51/3801c14d27f046a79eed60a22ac6bd23.html\n      - type: OpenAPI\n        url: openapi/sap-bi-bw4hana-odata-openapi.yml\n  - name: SAP Datasphere API\n    description: >-\n      APIs for SAP Datasphere (formerly SAP Data Warehouse Cloud) for data integration\n      and analytics.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_DATASPHERE\n    baseURL: https://[tenant].datasphere.cloud.sap/api/v1\n    tags:\n      - Cloud\n      - Data Integration\n      - Data Warehouse\n      - Datasphere\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_DATASPHERE/9f804b8efa8043539289f42f372c4862/7f1a91f95e794a5e9f29abce8856c8cf.html\n      - type: OpenAPI\n        url: https://api.sap.com/api/datasphere/overview\n\
  \      - type: API Reference\n        url: https://help.sap.com/docs/SAP_DATASPHERE/c8a54ee704e94e15926551293243fd1d/6c35457c1fc54a47b39aa5cdbc16d5e7.html\n      - type: Authentication\n        url: https://help.sap.com/docs/SAP_DATASPHERE/9f804b8efa8043539289f42f372c4862/3de81838d5cd43ee91576a3b0b4e5e36.html\n      - type: OpenAPI\n        url: openapi/sap-bi-datasphere-openapi.yml\n  - name: SAP Crystal Reports API\n    description: >-\n      APIs for embedding and automating SAP Crystal Reports in applications.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_CRYSTAL_REPORTS\n    baseURL: https://[server]/crystal/\n    tags:\n      - Crystal Reports\n      - Embedded Analytics\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_CRYSTAL_REPORTS/9e08a56e98d446b58af012538c121ff9/4650e1fe6d6d1014b3fc9283b0e91070.html\n      - type: SDK Guide\n        url: https://help.sap.com/docs/SAP_CRYSTAL_REPORTS/9e08a56e98d446b58af012538c121ff9/461aff6a6d6d1014910c91fa5b0c2cc3.html\n\
  \      - type: Integration Samples\n        url: https://wiki.scn.sap.com/wiki/display/BOBJ/Crystal+Reports+Developer+Center\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://api.sap.com/\n  - type: Authentication\n    url: https://help.sap.com/docs/SAP_CLOUD_PLATFORM/65de2977205c403bbc107264b8eccf4b/3670474a58c24ac2b082e76cbbd9dc19.html\n  - type: Support\n    url: https://support.sap.com/en/index.html\n  - type: Community\n    url: https://community.sap.com/\n  - type: Terms of Service\n    url: https://www.sap.com/about/legal/terms-of-use.html\n  - type: Privacy Policy\n    url: https://www.sap.com/about/legal/privacy.html\n  - type: OpenAPI\n    url: openapi/sap-bi-analytics-cloud-openapi.yml\n  - type: OpenAPI\n    url: openapi/sap-bi-businessobjects-platform-openapi.yml\n  - type: OpenAPI\n    url: openapi/sap-bi-bw4hana-odata-openapi.yml\n  - type: OpenAPI\n    url: openapi/sap-bi-datasphere-openapi.yml\n  - type: JSON-LD\n\
  \    url: json-ld/sap-bi-context.jsonld\n  - type: JSONSchema\n    url: json-schema/sap-bi-story-schema.json\n  - type: JSONSchema\n    url: json-schema/sap-bi-report-schema.json\n  - type: JSONSchema\n    url: json-schema/sap-bi-data-source-schema.json\n  - type: JSONStructure\n    url: json-structure/sap-bi-story-structure.json\n  - type: JSONStructure\n    url: json-structure/sap-bi-space-structure.json\n  - type: SpectralRules\n    url: rules/sap-bi-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/analytics-and-reporting.yaml\n  - type: NaftikoCapability\n    url: capabilities/data-warehouse-access.yaml\n  - type: Vocabulary\n    url: vocabulary/sap-bi-vocabulary.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sap-bi/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Data Visualization
- Reporting
- SAP
url: https://api.sap.com/business-intelligence
use_cases: []
---
