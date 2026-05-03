---
api_count: 13
api_specs:
- filename: overview
  format: yaml
  label: SAP Analytics Cloud API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/SACOpenAPI/overview
- filename: overview
  format: yaml
  label: SAP HANA Cloud Data Lake Files REST API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/HanaCloudDataLake/overview
- filename: overview
  format: yaml
  label: SAP Datasphere API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/Datasphere/overview
apis:
- description: RESTful API for SAP Analytics Cloud enabling data manipulation, story creation, and model management.
  name: SAP Analytics Cloud API
  slug: ''
- description: OData-based API for exporting fact data and master data from SAP Analytics Cloud models. Allows programmatic extraction of underlying data and metadata for integration with external systems and data p
  name: SAP Analytics Cloud Data Export API
  slug: ''
- description: REST API for managing content in the SAP Analytics Cloud Content Network. Enables programmatic access to get, publish, and delete private and public content items available through the Content Network
  name: SAP Analytics Cloud Content Network REST API
  slug: ''
- description: JavaScript-based API for building interactive analytic applications in SAP Analytics Cloud Analytics Designer. Provides scripting capabilities to control widgets, data sources, planning operations, an
  name: SAP Analytics Cloud Analytics Designer API
  slug: ''
- description: REST API for SAP BusinessObjects BI Platform for managing documents, users, and scheduling reports.
  name: SAP BusinessObjects BI Platform RESTful Web Services
  slug: ''
- description: REST API for SAP BusinessObjects Web Intelligence for creating, modifying, and exporting Web Intelligence reports. Provides endpoints for report management, data provider operations, and document sche
  name: SAP BusinessObjects Web Intelligence RESTful Web Services API
  slug: ''
- description: REST API for working with SAP BusinessObjects BI Semantic Layer universes. Allows querying and managing universes, executing queries against semantic layer data sources, and handling prompts and conte
  name: SAP BusinessObjects BI Semantic Layer REST API
  slug: ''
- description: RESTful API for SAP Crystal Reports for Enterprise that enables consuming and embedding Crystal Reports data in web and mobile applications. Supports retrieving report metadata, fetching data rows, se
  name: SAP Crystal Reports RESTful Web Services API
  slug: ''
- description: .NET SDK for integrating SAP Crystal Reports into Visual Studio applications. Enables developers to embed Crystal Reports into .NET web and desktop applications, programmatically create and modify rep
  name: SAP Crystal Reports .NET SDK
  slug: ''
- description: JavaScript API for creating custom visualizations and extensions in SAP Lumira.
  name: SAP Lumira Discovery Extensions API
  slug: ''
- description: RESTful API for accessing and managing files in SAP HANA Cloud Data Lake file containers. Supports file operations, auditing file access, and managing data stored in the HANA Cloud Data Lake for BI an
  name: SAP HANA Cloud Data Lake Files REST API
  slug: ''
- description: API for SAP Datasphere (formerly SAP Data Warehouse Cloud) for data integration, modeling, and consumption. Provides REST and OData endpoints for managing spaces, connections, data products, and consu
  name: SAP Datasphere API
  slug: ''
- description: 'OData V4 API for browsing the SAP Datasphere catalog and consuming datasets and metadata from consumable data assets. Enables external applications to discover available spaces, access relational and '
  name: SAP Datasphere Consumption and Catalog API
  slug: ''
capabilities:
- description: Unified workflow capability for managing analytics content across SAP Analytics Cloud, including story lifecycle management, content network publishing, and file repository governance. Used by BI admi
  name: SAP BI Tools Analytics Content Management
  slug: analytics-content-management
- description: Workflow capability for extracting data from SAP Analytics Cloud models and managing BusinessObjects reports. Combines data export pipelines with traditional BI report scheduling and delivery. Used by
  name: SAP BI Tools Data Extraction and Reporting
  slug: data-extraction-and-reporting
- description: Workflow capability for provisioning and managing users, teams, and access control across SAP Analytics Cloud using SCIM 2.0. Used by IT administrators and system integrators for identity lifecycle ma
  name: SAP BI Tools User and Access Management
  slug: user-and-access-management
common:
- title: ''
  type: Portal
  url: https://api.sap.com
- title: ''
  type: Getting Started
  url: https://developers.sap.com/topics/business-technology-platform..html
- title: ''
  type: Documentation
  url: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD
- title: ''
  type: Authentication
  url: https://help.sap.com/docs/authentication
- title: ''
  type: Terms of Service
  url: https://www.sap.com/about/legal/terms-of-use.html
- title: ''
  type: Privacy Policy
  url: https://www.sap.com/about/legal/privacy.html
- title: ''
  type: Status
  url: https://www.sap.com/about/trust-center/cloud-service-status.html
- title: ''
  type: Support
  url: https://support.sap.com
- title: ''
  type: Community
  url: https://community.sap.com
- title: ''
  type: Blog
  url: https://community.sap.com/t5/application-development-and-automation-blog-posts/bg-p/application-developmentblog-board
- title: ''
  type: Learning
  url: https://learning.sap.com
- title: ''
  type: Change Log
  url: https://pages.community.sap.com/topics/cloud-analytics/product-updates
- title: ''
  type: GitHub Organization
  url: https://github.com/SAP
- title: ''
  type: Website
  url: https://www.sap.com
- title: ''
  type: Sign Up
  url: https://developers.sap.com
- title: ''
  type: SDKs
  url: https://developers.sap.com/topics/cloud-sdk.html
- title: ''
  type: OpenAPI
  url: openapi/sap-analytics-cloud-api-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/sap-analytics-cloud-content-network-api-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/sap-analytics-cloud-data-export-api-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/sap-businessobjects-bi-platform-api-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/sap-bi-tools-story-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sap-bi-tools-user-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sap-bi-tools-content-item-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/sap-bi-tools-story-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/sap-bi-tools-user-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/sap-bi-tools-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/sap-bi-tools-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/sap-bi-tools-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/analytics-content-management.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/data-extraction-and-reporting.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/user-and-access-management.yaml
created: '2024-01-20'
description: Collection of SAP Business Intelligence tools and APIs for analytics, reporting, and data visualization.
features: []
image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg
integrations: []
jsonld:
- class_count: 26
  name: Sap Bi Tools Context
  property_count: 4
  slug: sap-bi-tools-context
layout: provider
modified: '2026-05-02'
name: SAP BI Tools
rules:
- name: SAP BI Tools API Rules
  rule_count: 10
  severity_counts:
    error: 1
    hint: 0
    info: 2
    warn: 7
  slug: sap-bi-tools-rules
skills: []
slug: sap-bi-tools
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SAP BI Tools\ndescription: >-\n  Collection of SAP Business Intelligence tools and APIs for analytics, reporting,\n  and data visualization.\nimage: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\ncreated: '2024-01-20'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\nurl: https://api.sap.com/bi-tools\ntags:\n  - Analytics\n  - Business Intelligence\n  - Data Visualization\n  - Reporting\n  - SAP\napis:\n  - name: SAP Analytics Cloud API\n    description: >-\n      RESTful API for SAP Analytics Cloud enabling data manipulation, story creation,\n      and model management.\n    image: https://www.sap.com/dam/application/shared/logos/sap-analytics-cloud.svg\n    humanURL: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD\n    baseURL: https://api.sapanalytics.cloud\n    version: '1.0'\n    tags:\n      - Analytics\n      - Cloud\n      - Models\n      - Stories\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/00f68c2e08b941f081002fd3691d86a7/\n\
  \      - type: OpenAPI\n        url: https://api.sap.com/api/SACOpenAPI/overview\n      - type: Authentication\n        url: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/00f68c2e08b941f081002fd3691d86a7/b4f4d1e6e7fb4c08b0964e0b6d14d849.html\n      - type: Rate Limits\n        url: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/00f68c2e08b941f081002fd3691d86a7/rate-limits\n      - type: Reference\n        url: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/00f68c2e08b941f081002fd3691d86a7/fc2c581619264a40a37b98c19753c542.html\n      - type: Getting Started\n        url: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/14cac91febef464dbb1efce20e3f1613/3ccfab3348dd407db089accb66cff9a2.html\n      - type: Change Log\n        url: https://www.sap.com/sea/products/data-cloud/cloud-analytics/features/release-highlights.html\n      - type: OpenAPI\n        url: openapi/sap-analytics-cloud-api-openapi.yml\n    contact:\n      - type: Support\n        url: https://support.sap.com/en/index.html\n  -\
  \ name: SAP Analytics Cloud Data Export API\n    description: >-\n      OData-based API for exporting fact data and master data from SAP Analytics\n      Cloud models. Allows programmatic extraction of underlying data and metadata\n      for integration with external systems and data pipelines.\n    image: https://www.sap.com/dam/application/shared/logos/sap-analytics-cloud.svg\n    humanURL: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/14cac91febef464dbb1efce20e3f1613/3ccfab3348dd407db089accb66cff9a2.html\n    baseURL: https://api.sapanalytics.cloud\n    tags:\n      - Analytics\n      - Cloud\n      - Data Export\n      - OData\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/14cac91febef464dbb1efce20e3f1613/3ccfab3348dd407db089accb66cff9a2.html\n      - type: GitHubRepository\n        url: https://github.com/SAP-samples/analytics-cloud-export-api-wrapper\n    contact:\n      - type: Support\n        url: https://support.sap.com/en/index.html\n\
  \  - name: SAP Analytics Cloud Content Network REST API\n    description: >-\n      REST API for managing content in the SAP Analytics Cloud Content Network.\n      Enables programmatic access to get, publish, and delete private and public\n      content items available through the Content Network.\n    image: https://www.sap.com/dam/application/shared/logos/sap-analytics-cloud.svg\n    humanURL: https://help.sap.com/doc/9825c700f68e489ca5634a3da101a94c/release/en-US/ca804ae1c3874053a1e140e7c9cea019.pdf\n    baseURL: https://api.sapanalytics.cloud\n    tags:\n      - Analytics\n      - Cloud\n      - Content Management\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/doc/9825c700f68e489ca5634a3da101a94c/release/en-US/ca804ae1c3874053a1e140e7c9cea019.pdf\n    contact:\n      - type: Support\n        url: https://support.sap.com/en/index.html\n  - name: SAP Analytics Cloud Analytics Designer API\n    description: >-\n      JavaScript-based API for building\
  \ interactive analytic applications in SAP\n      Analytics Cloud Analytics Designer. Provides scripting capabilities to\n      control widgets, data sources, planning operations, and application behavior\n      for embedded analytics scenarios.\n    image: https://www.sap.com/dam/application/shared/logos/sap-analytics-cloud.svg\n    humanURL: https://help.sap.com/doc/958d4c11261f42e992e8d01a4c0dde25/release/en-US/index.html\n    tags:\n      - Analytics\n      - Application Design\n      - Embedded Analytics\n      - JavaScript\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/doc/958d4c11261f42e992e8d01a4c0dde25/release/en-US/index.html\n      - type: Reference\n        url: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/00f68c2e08b941f081002fd3691d86a7/fc2c581619264a40a37b98c19753c542.html\n    contact:\n      - type: Support\n        url: https://support.sap.com/en/index.html\n  - name: SAP BusinessObjects BI Platform RESTful Web Services\n    description:\
  \ >-\n      REST API for SAP BusinessObjects BI Platform for managing documents, users,\n      and scheduling reports.\n    humanURL: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM\n    baseURL: https://server:port/biprws\n    version: '4.3'\n    tags:\n      - BusinessObjects\n      - Documents\n      - Reports\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM/e8c2e5877e9e44f9bfcc3085595b9208/\n      - type: API Reference\n        url: https://help.sap.com/doc/e39d9c134f1f4634addd5161f93dbf25/4.3/en-US/RESTful_Web_Services_User_Guide.pdf\n      - type: SDK\n        url: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM/e8c2e5877e9e44f9bfcc3085595b9208/sdk\n      - type: Authentication\n        url: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM/e8c2e5877e9e44f9bfcc3085595b9208/authentication\n\
  \      - type: API Hub\n        url: https://api.sap.com/package/BIPlatformRESTfulAPI\n    contact:\n      - type: Support\n        url: https://support.sap.com/en/index.html\n  - name: SAP BusinessObjects Web Intelligence RESTful Web Services API\n    description: >-\n      REST API for SAP BusinessObjects Web Intelligence for creating, modifying,\n      and exporting Web Intelligence reports. Provides endpoints for report\n      management, data provider operations, and document scheduling separate from\n      the general BI Platform REST API.\n    humanURL: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_WEB_INTELLIGENCE/58f583a7643e48cf944cf554eb961f5b/45f8735d6e041014910aba7db0e91070.html\n    baseURL: https://server:port/biprws\n    version: '4.3'\n    tags:\n      - BusinessObjects\n      - Data Providers\n      - Reports\n      - Web Intelligence\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/doc/1eeee826c0154c62a5cbd29359ecbc18/4.3/en-US/sbo43_webi_restws_dg_en.pdf\n\
  \      - type: Reference\n        url: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_WEB_INTELLIGENCE/58f583a7643e48cf944cf554eb961f5b/45f8735d6e041014910aba7db0e91070.html\n      - type: Quickstart\n        url: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_WEB_INTELLIGENCE/58f583a7643e48cf944cf554eb961f5b/7da2e2d66f701014aaab767bb0e91070.html\n      - type: API Hub\n        url: https://api.sap.com/api/SAPWebIntelligence/resource\n    contact:\n      - type: Support\n        url: https://support.sap.com/en/index.html\n  - name: SAP BusinessObjects BI Semantic Layer REST API\n    description: >-\n      REST API for working with SAP BusinessObjects BI Semantic Layer universes.\n      Allows querying and managing universes, executing queries against semantic\n      layer data sources, and handling prompts and contexts programmatically.\n    humanURL: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_WEB_INTELLIGENCE/58f583a7643e48cf944cf554eb961f5b/ec54808e6fdb101497906a7cb0e91070.html\n  \
  \  baseURL: https://server:port/biprws\n    version: '4.3'\n    tags:\n      - BusinessObjects\n      - Data Access\n      - Semantic Layer\n      - Universes\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/doc/a6296f37853c40388d5ada84c094d2cc/4.3.4/en-US/sbo43sp2_webisl_dev_guide_en.pdf\n      - type: Reference\n        url: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_WEB_INTELLIGENCE/58f583a7643e48cf944cf554eb961f5b/ec54808e6fdb101497906a7cb0e91070.html\n    contact:\n      - type: Support\n        url: https://support.sap.com/en/index.html\n  - name: SAP Crystal Reports RESTful Web Services API\n    description: >-\n      RESTful API for SAP Crystal Reports for Enterprise that enables consuming\n      and embedding Crystal Reports data in web and mobile applications. Supports\n      retrieving report metadata, fetching data rows, setting parameters, and\n      exporting reports in multiple formats.\n    humanURL: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM/0945312ac81f4b63be258130d2938055/45cecf3f6e041014910aba7db0e91070.html\n\
  \    version: '2020'\n    tags:\n      - Crystal Reports\n      - Embedded Analytics\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/CRYSTAL_REPORTS/c5fb6213b96b4cc1bf43a55d68d9d87b/\n      - type: SDK Download\n        url: https://support.sap.com/en/product/analytics/crystal-reports.html\n      - type: Developer Guide\n        url: https://help.sap.com/doc/8f2e87893e944ec98a9c378aefdbbdd2/4.3.1/en-US/sbo43sp1_cr_restws_en.pdf\n      - type: Reference\n        url: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM/0945312ac81f4b63be258130d2938055/45cecf3f6e041014910aba7db0e91070.html\n    contact:\n      - type: Support\n        url: https://support.sap.com/en/index.html\n  - name: SAP Crystal Reports .NET SDK\n    description: >-\n      .NET SDK for integrating SAP Crystal Reports into Visual Studio applications.\n      Enables developers to embed Crystal Reports into .NET web and desktop\n      applications,\
  \ programmatically create and modify reports, and manage report\n      data sources and parameters.\n    humanURL: https://help.sap.com/docs/SAP_CRYSTAL_REPORTS,_DEVELOPER_VERSION_FOR_MICROSOFT_VISUAL_STUDIO/0d6684e153174710b8b2eb114bb7f843/a2cb609cfb6949b6a67b2effe32a347e.html\n    version: '2020'\n    tags:\n      - .NET\n      - Crystal Reports\n      - SDK\n      - Visual Studio\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_CRYSTAL_REPORTS,_DEVELOPER_VERSION_FOR_MICROSOFT_VISUAL_STUDIO/0d6684e153174710b8b2eb114bb7f843/a2cb609cfb6949b6a67b2effe32a347e.html\n      - type: Community\n        url: https://pages.community.sap.com/topics/crystal-reports/visual-studio\n    contact:\n      - type: Support\n        url: https://support.sap.com/en/index.html\n  - name: SAP Lumira Discovery Extensions API\n    description: >-\n      JavaScript API for creating custom visualizations and extensions in SAP Lumira.\n    humanURL: https://help.sap.com/docs/LUMIRA\n\
  \    version: '2.4'\n    tags:\n      - Extensions\n      - JavaScript\n      - Lumira\n      - Visualization\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/LUMIRA/82b8ad67e9b74a48bad806dc52c96fcc/\n      - type: Extension API\n        url: https://help.sap.com/docs/LUMIRA/extensions-api\n      - type: Samples\n        url: https://github.com/SAP/lumira-extension-viz\n      - type: Developer Guide\n        url: https://help.sap.com/doc/9d0bf4daa0cb41cbb630e093450b1bd8/2.3.0.0/en-US/lum_23SP00_ds_devguide_en.pdf\n    contact:\n      - type: GitHub\n        url: https://github.com/SAP/lumira-extension-viz\n  - name: SAP HANA Cloud Data Lake Files REST API\n    description: >-\n      RESTful API for accessing and managing files in SAP HANA Cloud Data Lake\n      file containers. Supports file operations, auditing file access, and\n      managing data stored in the HANA Cloud Data Lake for BI and analytics\n      workloads.\n    humanURL: https://help.sap.com/docs/hana-cloud-data-lake\n\
  \    baseURL: https://api.hana.ondemand.com\n    version: '1.0'\n    tags:\n      - Cloud\n      - Data Access\n      - Data Lake\n      - HANA\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/hana-cloud-data-lake\n      - type: OpenAPI\n        url: https://api.sap.com/api/HanaCloudDataLake/overview\n      - type: Getting Started\n        url: https://developers.sap.com/tutorials/data-lake-file-containers-restapi..html\n      - type: Reference\n        url: https://help.sap.com/doc/9d084a41830f46d6904fd4c23cd4bbfa/QRC_3_2021/en-US/html/index.html\n      - type: API Hub\n        url: https://api.sap.com/package/SAPHanaCloud/rest\n    contact:\n      - type: Support\n        url: https://support.sap.com/en/index.html\n  - name: SAP Datasphere API\n    description: >-\n      API for SAP Datasphere (formerly SAP Data Warehouse Cloud) for data\n      integration, modeling, and consumption. Provides REST and OData endpoints\n      for managing spaces, connections,\
  \ data products, and consuming relational\n      and analytical models.\n    humanURL: https://help.sap.com/docs/SAP_DATASPHERE\n    baseURL: https://datasphere-api.cfapps.eu10.hana.ondemand.com\n    version: '2023'\n    tags:\n      - Data Modeling\n      - Data Warehouse\n      - Datasphere\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_DATASPHERE/9f804b8efa8043539289f42f372c4862/\n      - type: API Reference\n        url: https://help.sap.com/docs/SAP_DATASPHERE/api-reference\n      - type: OpenAPI\n        url: https://api.sap.com/api/Datasphere/overview\n      - type: API Hub\n        url: https://api.sap.com/package/sapdatasphere/overview\n    contact:\n      - type: Support\n        url: https://support.sap.com/en/index.html\n  - name: SAP Datasphere Consumption and Catalog API\n    description: >-\n      OData V4 API for browsing the SAP Datasphere catalog and consuming datasets\n      and metadata from consumable\
  \ data assets. Enables external applications to\n      discover available spaces, access relational and analytical models, and\n      retrieve data products programmatically.\n    humanURL: https://api.sap.com/api/DatasphereCatalog/resource/SAP_Datasphere_Consumption_Catalog\n    baseURL: https://datasphere-api.cfapps.eu10.hana.ondemand.com\n    tags:\n      - Catalog\n      - Data Consumption\n      - Datasphere\n      - OData\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_DATASPHERE/43509d67b8b84e66a30851e832f66911/7a453609c8694b029493e7d87e0de60a.html\n      - type: API Hub\n        url: https://api.sap.com/package/sapdatasphere/odatav4\n    contact:\n      - type: Support\n        url: https://support.sap.com/en/index.html\ncommon:\n  - type: Portal\n    url: https://api.sap.com\n  - type: Getting Started\n    url: https://developers.sap.com/topics/business-technology-platform..html\n  - type: Documentation\n    url: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD\n\
  \  - type: Authentication\n    url: https://help.sap.com/docs/authentication\n  - type: Terms of Service\n    url: https://www.sap.com/about/legal/terms-of-use.html\n  - type: Privacy Policy\n    url: https://www.sap.com/about/legal/privacy.html\n  - type: Status\n    url: https://www.sap.com/about/trust-center/cloud-service-status.html\n  - type: Support\n    url: https://support.sap.com\n  - type: Community\n    url: https://community.sap.com\n  - type: Blog\n    url: https://community.sap.com/t5/application-development-and-automation-blog-posts/bg-p/application-developmentblog-board\n  - type: Learning\n    url: https://learning.sap.com\n  - type: Change Log\n    url: https://pages.community.sap.com/topics/cloud-analytics/product-updates\n  - type: GitHub Organization\n    url: https://github.com/SAP\n  - type: Website\n    url: https://www.sap.com\n  - type: Sign Up\n    url: https://developers.sap.com\n  - type: SDKs\n    url: https://developers.sap.com/topics/cloud-sdk.html\n  -\
  \ type: OpenAPI\n    url: openapi/sap-analytics-cloud-api-openapi.yml\n  - type: OpenAPI\n    url: openapi/sap-analytics-cloud-content-network-api-openapi.yml\n  - type: OpenAPI\n    url: openapi/sap-analytics-cloud-data-export-api-openapi.yml\n  - type: OpenAPI\n    url: openapi/sap-businessobjects-bi-platform-api-openapi.yml\n  - type: JSONSchema\n    url: json-schema/sap-bi-tools-story-schema.json\n  - type: JSONSchema\n    url: json-schema/sap-bi-tools-user-schema.json\n  - type: JSONSchema\n    url: json-schema/sap-bi-tools-content-item-schema.json\n  - type: JSONStructure\n    url: json-structure/sap-bi-tools-story-structure.json\n  - type: JSONStructure\n    url: json-structure/sap-bi-tools-user-structure.json\n  - type: JSON-LD\n    url: json-ld/sap-bi-tools-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/sap-bi-tools-vocabulary.yml\n  - type: SpectralRules\n    url: rules/sap-bi-tools-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/analytics-content-management.yaml\n\
  \  - type: NaftikoCapability\n    url: capabilities/data-extraction-and-reporting.yaml\n  - type: NaftikoCapability\n    url: capabilities/user-and-access-management.yaml\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sap-bi-tools/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Data Visualization
- Reporting
- SAP
url: https://api.sap.com/bi-tools
use_cases: []
---
