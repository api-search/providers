---
api_count: 13
api_specs:
- filename: sap-hana-cloud-rest-api.yml
  format: yaml
  label: SAP HANA Cloud REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-hana/refs/heads/main/openapi/sap-hana-cloud-rest-api.yml
apis:
- description: REST API for managing SAP HANA Cloud instances, monitoring, and administration.
  name: SAP HANA Cloud REST API
  slug: ''
- description: SQL interface for querying and managing data in SAP HANA databases.
  name: SAP HANA SQL API
  slug: ''
- description: Extended Application Services (XS) for building applications directly on SAP HANA.
  name: SAP HANA XS Engine API
  slug: ''
- description: RESTful API for SAP HANA Cockpit administration and monitoring.
  name: SAP HANA Cockpit API
  slug: ''
- description: APIs for data provisioning, replication, and integration.
  name: SAP HANA Smart Data Integration API
  slug: ''
- description: REST API for accessing triggered alerts, database metrics, and metering data for SAP HANA Cloud instances.
  name: SAP HANA Cloud Alerts and Metrics REST API
  slug: ''
- description: REST API providing geocoding, routing, and mapping services through a unified interface supporting multiple back-end service providers.
  name: SAP HANA Spatial Services API
  slug: ''
- description: REST API for managing, uploading, reading, deleting, and listing files in SAP HANA Cloud Data Lake file containers.
  name: SAP HANA Cloud Data Lake Files REST API
  slug: ''
- description: API for managing HDI containers used to deploy database artifacts in isolated schemas with dependency management and lifecycle support.
  name: SAP HANA Deployment Infrastructure (HDI) API
  slug: ''
- description: In-database machine learning and statistical algorithms library providing clustering, classification, regression, and time series analysis capabilities.
  name: SAP HANA Predictive Analysis Library (PAL) API
  slug: ''
- description: API for storing, querying, and managing semi-structured JSON documents within SAP HANA using a hybrid relational and document-oriented approach.
  name: SAP HANA JSON Document Store API
  slug: ''
- description: Graph processing engine for network analysis with built-in algorithms for path finding, pattern matching, and knowledge graph capabilities using OpenCypher and SPARQL.
  name: SAP HANA Graph Engine API
  slug: ''
- description: REST API for retrieving system information and metadata about SAP HANA Platform instances.
  name: SAP HANA REST Info API
  slug: ''
capabilities:
- description: Unified workflow for SAP HANA Cloud database administration including instance lifecycle management, monitoring alerts, performance metrics, and metering. Used by database administrators and cloud pla
  name: SAP HANA Cloud Administration
  slug: cloud-administration
common:
- title: ''
  type: DeveloperPortal
  url: https://api.sap.com/
- title: ''
  type: Support
  url: https://support.sap.com/
- title: ''
  type: Pricing
  url: https://www.sap.com/products/technology-platform/hana/pricing.html
- title: ''
  type: StatusPage
  url: https://www.sap.com/about/trust-center/cloud-service-status.html
- title: ''
  type: TermsOfService
  url: https://www.sap.com/about/trust-center/agreements.html
- title: ''
  type: GettingStarted
  url: https://www.sap.com/products/data-cloud/hana/get-started.html
- title: ''
  type: Tutorials
  url: https://developers.sap.com/tutorial-navigator.html
- title: ''
  type: GitHubRepository
  url: https://github.com/SAP-samples
- title: ''
  type: PrivacyPolicy
  url: https://www.sap.com/about/legal/privacy.html
- title: ''
  type: JSONLD
  url: json-ld/sap-hana-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/sap-hana-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/cloud-administration.yaml
created: '2024-01-01'
description: APIs for SAP HANA, an in-memory, column-oriented, relational database management system developed and marketed by SAP SE.
features:
- description: Process massive datasets in real-time using columnar in-memory storage for analytics and transactions.
  name: In-Memory Computing
- description: Support for relational, graph, spatial, JSON document, and time series data in a single database.
  name: Multi-Model Processing
- description: Fully managed cloud database service with elastic scaling, automated backups, and multi-region deployment.
  name: Cloud Native
- description: Built-in machine learning algorithms through the Predictive Analysis Library for in-database analytics.
  name: Predictive Analytics
- description: Seamlessly extend storage with SAP HANA Cloud Data Lake for cost-effective warm and cold data management.
  name: Data Lake Integration
- description: Real-time and batch data replication from heterogeneous sources with built-in data quality.
  name: Smart Data Integration
image: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg
integrations:
- description: Native integration with SAP Business Technology Platform for enterprise application development.
  name: SAP BTP
- description: Serve as the underlying database for SAP S/4HANA ERP suite.
  name: SAP S/4HANA
- description: Direct live connections for real-time business intelligence dashboards and planning.
  name: SAP Analytics Cloud
- description: Deploy SAP HANA Cloud instances on Azure infrastructure with cross-cloud governance.
  name: Microsoft Azure
jsonld:
- class_count: 0
  name: Sap Hana Cloud Rest Context
  property_count: 0
  slug: sap-hana-cloud-rest-context
- class_count: 0
  name: Sap Hana Context
  property_count: 14
  slug: sap-hana-context
layout: provider
modified: '2026-04-18'
name: SAP HANA
rules:
- name: SAP HANA API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: sap-hana-spectral-rules
skills: []
slug: sap-hana
solutions: []
source_filename: apis.yml
source_yaml: "name: SAP HANA\ndescription: >-\n  APIs for SAP HANA, an in-memory, column-oriented, relational database management\n  system developed and marketed by SAP SE.\nimage: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg\ntags:\n  - Analytics\n  - Cloud\n  - Database\n  - Enterprise\n  - In-Memory\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nurl: https://www.sap.com/products/technology-platform/hana.html\nspecificationVersion: '0.19'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\napis:\n  - name: SAP HANA Cloud REST API\n    description: >-\n      REST API for managing SAP HANA Cloud instances, monitoring, and administration.\n    image: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/HANA_CLOUD\n    baseURL: https://api.cf.{region}.hana.ondemand.com\n    tags:\n      - Administration\n      - Cloud\n      - Database Management\n    properties:\n      - type: Documentation\n   \
  \     url: https://help.sap.com/docs/HANA_CLOUD/9ae9104a46f74a6583ce5182e7fb20cb/\n      - type: OpenAPI\n        url: openapi/sap-hana-cloud-rest-api.yml\n      - type: Authentication\n        url: https://help.sap.com/docs/HANA_CLOUD/9ae9104a46f74a6583ce5182e7fb20cb/3670474a58c24ac2b082e76cbbd9dc19.html\n      - type: Tutorials\n        url: https://developers.sap.com/tutorials/hana-cloud-automation-rest..html\n      - type: JSONSchema\n        url: json-schema/sap-hana-database-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-service-instance-list-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-service-instance-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-instance-parameters-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-last-operation-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-create-service-instance-request-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-update-service-instance-request-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-inventory-instance-list-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-inventory-instance-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-alert-event-list-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-alert-event-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-alert-rule-list-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-alert-rule-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-update-alert-rules-request-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-metric-value-list-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-metric-series-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-metric-data-point-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-metering-value-list-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-metering-value-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-instance-mapping-list-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-instance-mapping-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-create-instance-mapping-request-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-hana-cloud-rest-error-schema.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-service-instance-list-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-service-instance-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-instance-parameters-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-last-operation-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-create-service-instance-request-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-update-service-instance-request-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-inventory-instance-list-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-inventory-instance-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-alert-event-list-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-alert-event-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-alert-rule-list-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-alert-rule-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-update-alert-rules-request-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-metric-value-list-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-metric-series-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-metric-data-point-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-metering-value-list-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-metering-value-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-instance-mapping-list-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-instance-mapping-structure.json\n      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-create-instance-mapping-request-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/sap-hana-cloud-rest-error-structure.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-service-instance-list-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-service-instance-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-instance-parameters-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-last-operation-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-create-service-instance-request-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-update-service-instance-request-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-inventory-instance-list-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-inventory-instance-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-alert-event-list-example.json\n\
  \      - type: Example\n        url: examples/sap-hana-cloud-rest-alert-event-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-alert-rule-list-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-alert-rule-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-update-alert-rules-request-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-metric-value-list-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-metric-series-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-metric-data-point-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-metering-value-list-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-metering-value-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-instance-mapping-list-example.json\n      - type: Example\n        url:\
  \ examples/sap-hana-cloud-rest-instance-mapping-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-create-instance-mapping-request-example.json\n      - type: Example\n        url: examples/sap-hana-cloud-rest-error-example.json\n      - type: JSONLD\n        url: json-ld/sap-hana-cloud-rest-context.jsonld\n  - name: SAP HANA SQL API\n    description: >-\n      SQL interface for querying and managing data in SAP HANA databases.\n    image: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/SAP_HANA_PLATFORM\n    baseURL: jdbc:sap://{host}:{port}\n    tags:\n      - Database\n      - Query\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_HANA_PLATFORM/4fe29514fd584807ac9f2a04f6754767/\n  - name: SAP HANA XS Engine API\n    description: >-\n      Extended Application Services (XS) for building applications directly on SAP HANA.\n    image: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg\n\
  \    humanURL: https://help.sap.com/docs/SAP_HANA_PLATFORM\n    baseURL: https://{host}:{port}\n    tags:\n      - Application Development\n      - JavaScript\n      - OData\n      - XS\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_HANA_PLATFORM/4505d0bdaf4948449b7f7379d24d0f0d/\n  - name: SAP HANA Cockpit API\n    description: >-\n      RESTful API for SAP HANA Cockpit administration and monitoring.\n    image: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/SAP_HANA_COCKPIT\n    baseURL: https://{host}:{port}/sap/hana/\n    tags:\n      - Administration\n      - Management\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_HANA_COCKPIT/afa922439b204e9caf22c78b6b69e4f2/\n  - name: SAP HANA Smart Data Integration API\n    description: >-\n      APIs for data provisioning, replication, and integration.\n    image: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg\n\
  \    humanURL: https://help.sap.com/docs/SAP_HANA_SMART_DATA_INTEGRATION\n    baseURL: https://{host}:{port}\n    tags:\n      - Data Integration\n      - ETL\n      - Replication\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_HANA_SMART_DATA_INTEGRATION/7952ef28a6914997abc01745fef1b607/\n  - name: SAP HANA Cloud Alerts and Metrics REST API\n    description: >-\n      REST API for accessing triggered alerts, database metrics, and metering data\n      for SAP HANA Cloud instances.\n    image: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://developers.sap.com/tutorials/hana-cloud-alerts-rest-api.html\n    baseURL: https://api.cf.{region}.hana.ondemand.com\n    tags:\n      - Alerts\n      - Metering\n      - Metrics\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/r/64f7d2b06c6b40a9b3097860c5930641/Cloud/en-US/9f02513389e64490a0652955fedce2ad.html\n\
  \      - type: Tutorials\n        url: https://developers.sap.com/tutorials/hana-cloud-alerts-rest-api.html\n  - name: SAP HANA Spatial Services API\n    description: >-\n      REST API providing geocoding, routing, and mapping services through a unified\n      interface supporting multiple back-end service providers.\n    image: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/sap-hana-spatial-services\n    baseURL: https://api.cf.{region}.hana.ondemand.com\n    tags:\n      - Geocoding\n      - Location\n      - Mapping\n      - Routing\n      - Spatial\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/sap-hana-spatial-services\n      - type: Tutorials\n        url: https://developers.sap.com/tutorials/hana-spatial-services-apis..html\n  - name: SAP HANA Cloud Data Lake Files REST API\n    description: >-\n      REST API for managing, uploading, reading, deleting, and listing files in\
  \ SAP\n      HANA Cloud Data Lake file containers.\n    image: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/hana-cloud-data-lake\n    baseURL: https://{host}:{port}\n    tags:\n      - Cloud Storage\n      - Data Lake\n      - File Storage\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/hana-cloud-data-lake\n      - type: Tutorials\n        url: https://developers.sap.com/tutorials/data-lake-file-containers-restapi..html\n  - name: SAP HANA Deployment Infrastructure (HDI) API\n    description: >-\n      API for managing HDI containers used to deploy database artifacts in isolated\n      schemas with dependency management and lifecycle support.\n    image: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/hana-cloud-database/sap-hana-cloud-sap-hana-database-deployment-infrastructure-hdi-reference/sap-hana-cloud-sap-hana-database-deployment-infrastructure-reference\n\
  \    baseURL: https://{host}:{port}\n    tags:\n      - Containers\n      - Deployment\n      - DevOps\n      - HDI\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/hana-cloud-database/sap-hana-cloud-sap-hana-database-deployment-infrastructure-hdi-reference/sap-hana-cloud-sap-hana-database-deployment-infrastructure-reference\n  - name: SAP HANA Predictive Analysis Library (PAL) API\n    description: >-\n      In-database machine learning and statistical algorithms library providing clustering,\n      classification, regression, and time series analysis capabilities.\n    image: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/hana-cloud-database/sap-hana-cloud-sap-hana-database-predictive-analysis-library/sap-hana-cloud-sap-hana-database-predictive-analysis-library-pal\n    baseURL: https://{host}:{port}\n    tags:\n      - AI\n      - Machine Learning\n      - Predictive Analytics\n\
  \      - Statistics\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/hana-cloud-database/sap-hana-cloud-sap-hana-database-predictive-analysis-library/sap-hana-cloud-sap-hana-database-predictive-analysis-library-pal\n  - name: SAP HANA JSON Document Store API\n    description: >-\n      API for storing, querying, and managing semi-structured JSON documents within\n      SAP HANA using a hybrid relational and document-oriented approach.\n    image: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/SAP_HANA_PLATFORM/6b94445c94ae495c83a19646e7c3fd56/5e783b7f5a9749bcbfffe167524aeccc.html\n    baseURL: https://{host}:{port}\n    tags:\n      - Document Store\n      - JSON\n      - Multi-Model\n      - NoSQL\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_HANA_PLATFORM/6b94445c94ae495c83a19646e7c3fd56/5e783b7f5a9749bcbfffe167524aeccc.html\n  - name: SAP\
  \ HANA Graph Engine API\n    description: >-\n      Graph processing engine for network analysis with built-in algorithms for path\n      finding, pattern matching, and knowledge graph capabilities using OpenCypher\n      and SPARQL.\n    image: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/hana-cloud-database/sap-hana-cloud-sap-hana-database-knowledge-graph-guide/sap-hana-cloud-sap-hana-database-knowledge-graph-engine-guide\n    baseURL: https://{host}:{port}\n    tags:\n      - Graph\n      - Knowledge Graph\n      - Multi-Model\n      - Network Analysis\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/hana-cloud-database/sap-hana-cloud-sap-hana-database-knowledge-graph-guide/sap-hana-cloud-sap-hana-database-knowledge-graph-engine-guide\n  - name: SAP HANA REST Info API\n    description: >-\n      REST API for retrieving system information and metadata about SAP HANA Platform\n \
  \     instances.\n    image: https://www.sap.com/content/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/SAP_HANA_PLATFORM/b3d0daf2a98e49ada00bf31b7ca7a42e/0e5335b66a9e4c64993605fc24ccd6d1.html\n    baseURL: https://{host}:{port}\n    tags:\n      - Metadata\n      - REST\n      - System Information\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_HANA_PLATFORM/b3d0daf2a98e49ada00bf31b7ca7a42e/0e5335b66a9e4c64993605fc24ccd6d1.html\ncommon:\n  - type: DeveloperPortal\n    url: https://api.sap.com/\n  - type: Support\n    url: https://support.sap.com/\n  - type: Pricing\n    url: https://www.sap.com/products/technology-platform/hana/pricing.html\n  - type: StatusPage\n    url: https://www.sap.com/about/trust-center/cloud-service-status.html\n  - type: TermsOfService\n    url: https://www.sap.com/about/trust-center/agreements.html\n  - type: GettingStarted\n    url: https://www.sap.com/products/data-cloud/hana/get-started.html\n\
  \  - type: Tutorials\n    url: https://developers.sap.com/tutorial-navigator.html\n  - type: GitHubRepository\n    url: https://github.com/SAP-samples\n  - type: PrivacyPolicy\n    url: https://www.sap.com/about/legal/privacy.html\n  - type: JSONLD\n    url: json-ld/sap-hana-context.jsonld\n  - type: SpectralRules\n    url: rules/sap-hana-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/cloud-administration.yaml\n  - type: Features\n    data:\n      - name: In-Memory Computing\n        description: Process massive datasets in real-time using columnar in-memory storage for analytics and transactions.\n      - name: Multi-Model Processing\n        description: Support for relational, graph, spatial, JSON document, and time series data in a single database.\n      - name: Cloud Native\n        description: Fully managed cloud database service with elastic scaling, automated backups, and multi-region deployment.\n      - name: Predictive Analytics\n        description:\
  \ Built-in machine learning algorithms through the Predictive Analysis Library for in-database analytics.\n      - name: Data Lake Integration\n        description: Seamlessly extend storage with SAP HANA Cloud Data Lake for cost-effective warm and cold data management.\n      - name: Smart Data Integration\n        description: Real-time and batch data replication from heterogeneous sources with built-in data quality.\n  - type: UseCases\n    data:\n      - name: Real-Time Analytics\n        description: Run complex analytical queries on live transactional data without ETL delays.\n      - name: Application Development\n        description: Build high-performance applications directly on the database using XS Engine and HDI containers.\n      - name: IoT Data Processing\n        description: Ingest and analyze high-volume sensor and device data with time series and spatial capabilities.\n      - name: Enterprise Data Warehousing\n        description: Consolidate enterprise data for reporting\
  \ and business intelligence with columnar compression.\n  - type: Integrations\n    data:\n      - name: SAP BTP\n        description: Native integration with SAP Business Technology Platform for enterprise application development.\n      - name: SAP S/4HANA\n        description: Serve as the underlying database for SAP S/4HANA ERP suite.\n      - name: SAP Analytics Cloud\n        description: Direct live connections for real-time business intelligence dashboards and planning.\n      - name: Microsoft Azure\n        description: Deploy SAP HANA Cloud instances on Azure infrastructure with cross-cloud governance.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sap-hana/refs/heads/main/apis.yml
tags:
- Analytics
- Cloud
- Database
- Enterprise
- In-Memory
url: https://www.sap.com/products/technology-platform/hana.html
use_cases:
- description: Run complex analytical queries on live transactional data without ETL delays.
  name: Real-Time Analytics
- description: Build high-performance applications directly on the database using XS Engine and HDI containers.
  name: Application Development
- description: Ingest and analyze high-volume sensor and device data with time series and spatial capabilities.
  name: IoT Data Processing
- description: Consolidate enterprise data for reporting and business intelligence with columnar compression.
  name: Enterprise Data Warehousing
---
