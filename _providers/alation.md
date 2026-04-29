---
api_count: 4
apis:
- description: REST API for managing data sources, schemas, tables, columns, and custom field values in the Alation data catalog. Supports metadata retrieval and batch updates for catalog objects.
  name: Alation Data Catalog API
  slug: data-catalog-api
- description: REST API for managing data lineage and dataflow objects in Alation. Supports creating, retrieving, updating, and deleting lineage paths between catalog objects.
  name: Alation Lineage API
  slug: lineage-api
- description: REST API for data governance workflows in Alation, including business glossary management, governance policy enforcement, and data quality rules and scoring.
  name: Alation Governance API
  slug: governance-api
- description: REST API for searching and discovering catalog assets in Alation. Supports full-text search, AI-powered aggregated context retrieval, and article browsing.
  name: Alation Search API
  slug: search-api
capabilities:
- description: Workflow capability for data intelligence operations combining catalog search, lineage tracking, governance, and metadata management in the Alation platform. Enables data stewards, analysts, and AI ag
  name: Alation Data Intelligence
  slug: data-intelligence
common:
- title: ''
  type: Website
  url: https://alation.com
- title: ''
  type: Documentation
  url: https://developer.alation.com
- title: ''
  type: GettingStarted
  url: https://developer.alation.com/dev/docs/about-the-alation-apis
- title: ''
  type: GitHubOrganization
  url: https://github.com/Alation
- title: ''
  type: SpectralRules
  url: rules/alation-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/alation-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/alation-alation-context.jsonld
- title: Alation Data Catalog Shared Capability
  type: NaftikoCapability
  url: capabilities/shared/data-catalog-api.yaml
- title: Alation Lineage Shared Capability
  type: NaftikoCapability
  url: capabilities/shared/lineage-api.yaml
- title: Alation Governance Shared Capability
  type: NaftikoCapability
  url: capabilities/shared/governance-api.yaml
- title: Alation Search Shared Capability
  type: NaftikoCapability
  url: capabilities/shared/search-api.yaml
- title: Data Intelligence Workflow
  type: NaftikoCapability
  url: capabilities/data-intelligence.yaml
created: '2025-01-08'
description: Alation is a data intelligence platform that helps organizations harness the power of their data by providing a centralized platform for data cataloging, governance, and collaboration. By enabling users to easily search, understand, and trust their data, Alation empowers organizations to make data-driven decisions with confidence. Through advanced analytics and AI capabilities, Alation helps organizations uncover insights, improve data quality, and drive innovation.
features:
- description: Centralized catalog for data sources, schemas, tables, and columns with rich metadata, descriptions, and custom fields for discoverability.
  name: Data Catalog
- description: End-to-end data lineage tracking via dataflow objects showing how data moves between sources, transformations, and targets.
  name: Data Lineage
- description: Collaborative business glossary for defining standardized terms, abbreviations, and synonyms with stewardship assignments.
  name: Business Glossary
- description: Comprehensive data quality rules covering accuracy, completeness, consistency, timeliness, uniqueness, validity, and custom dimensions.
  name: Data Quality
- description: Governance policy management for data protection, retention, access control, and quality enforcement across the enterprise.
  name: Governance Policies
- description: Full-text and semantic search powered by AI for discovering trusted data assets, with aggregated context for LLM consumption.
  name: AI-Powered Search
- description: Specialized API for AI applications to retrieve structured catalog context for natural language queries, enabling RAG and AI agent workflows.
  name: Aggregated Context API
- description: Extensible metadata framework with custom fields for any catalog object type, supporting batch updates via the REST API.
  name: Custom Fields
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Snowflake integration for automatic metadata harvesting and query log analysis to build comprehensive data lineage.
  name: Snowflake
- description: dbt integration for capturing transformation lineage and linking dbt models to physical tables in the Alation catalog.
  name: dbt
- description: BI metadata integration for cataloging Tableau reports and dashboards with lineage to underlying data sources.
  name: Tableau
- description: Official Python SDK and AI Agent SDK for programmatic access to Alation catalog APIs and AI agent development.
  name: Python SDK
- description: Integration with Apache Atlas for federated metadata management across heterogeneous data platforms.
  name: Apache Atlas
jsonld:
- class_count: 0
  name: Alation Alation Context
  property_count: 60
  slug: alation-alation-context
layout: provider
modified: '2026-04-19'
name: Alation
rules:
- name: Alation API Rules
  rule_count: 26
  severity_counts:
    error: 14
    hint: 0
    info: 2
    warn: 10
  slug: alation-spectral-rules
skills: []
slug: alation
solutions: []
source_yaml: "aid: alation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/alation/refs/heads/main/apis.yml\nname: Alation\ntags:\n  - Data Catalog\n  - Data Governance\n  - Data Intelligence\n  - Data Lineage\n  - Data Quality\n  - Business Glossary\n  - Metadata Management\n  - AI\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  Alation is a data intelligence platform that helps organizations harness the\n  power of their data by providing a centralized platform for data cataloging,\n  governance, and collaboration. By enabling users to easily search, understand,\n  and trust their data, Alation empowers organizations to make data-driven\n  decisions with confidence. Through advanced analytics and AI capabilities,\n  Alation helps organizations uncover insights, improve data quality, and drive\n  innovation.\ncreated: '2025-01-08'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: alation:data-catalog-api\n\
  \    name: Alation Data Catalog API\n    tags:\n      - Data Catalog\n      - Metadata\n      - Data Sources\n      - Schemas\n      - Tables\n      - Columns\n    properties:\n      - url: https://developer.alation.com\n        type: Documentation\n      - url: openapi/alation-data-catalog-openapi.yaml\n        type: OpenAPI\n      - url: json-schema/alation-alation-data-catalog-data-source-schema.json\n        type: JSONSchema\n      - url: json-schema/alation-alation-data-catalog-schema-schema.json\n        type: JSONSchema\n      - url: json-schema/alation-alation-data-catalog-table-schema.json\n        type: JSONSchema\n      - url: json-schema/alation-alation-data-catalog-column-schema.json\n        type: JSONSchema\n      - url: json-schema/alation-alation-data-catalog-custom-field-value-schema.json\n        type: JSONSchema\n      - url: json-structure/alation-alation-data-catalog-data-source-structure.json\n        type: JSONStructure\n      - url: json-structure/alation-alation-data-catalog-schema-structure.json\n\
  \        type: JSONStructure\n      - url: json-structure/alation-alation-data-catalog-table-structure.json\n        type: JSONStructure\n      - url: json-structure/alation-alation-data-catalog-column-structure.json\n        type: JSONStructure\n      - url: json-structure/alation-alation-data-catalog-custom-field-value-structure.json\n        type: JSONStructure\n      - url: examples/alation-alation-data-catalog-data-source-example.json\n        type: Example\n      - url: examples/alation-alation-data-catalog-schema-example.json\n        type: Example\n      - url: examples/alation-alation-data-catalog-table-example.json\n        type: Example\n      - url: examples/alation-alation-data-catalog-column-example.json\n        type: Example\n      - url: examples/alation-alation-data-catalog-custom-field-value-example.json\n        type: Example\n    humanURL: https://developer.alation.com\n    baseURL: https://your-instance.alation.com/integration/v2\n    description: >-\n      REST API\
  \ for managing data sources, schemas, tables, columns, and custom\n      field values in the Alation data catalog. Supports metadata retrieval\n      and batch updates for catalog objects.\n\n  - aid: alation:lineage-api\n    name: Alation Lineage API\n    tags:\n      - Data Lineage\n      - Dataflow\n      - Metadata\n    properties:\n      - url: https://developer.alation.com\n        type: Documentation\n      - url: openapi/alation-lineage-openapi.yaml\n        type: OpenAPI\n      - url: json-schema/alation-alation-lineage-dataflow-schema.json\n        type: JSONSchema\n      - url: json-schema/alation-alation-lineage-lineage-graph-schema.json\n        type: JSONSchema\n      - url: json-structure/alation-alation-lineage-dataflow-structure.json\n        type: JSONStructure\n      - url: json-structure/alation-alation-lineage-lineage-graph-structure.json\n        type: JSONStructure\n      - url: examples/alation-alation-lineage-dataflow-example.json\n        type: Example\n     \
  \ - url: examples/alation-alation-lineage-lineage-graph-example.json\n        type: Example\n    humanURL: https://developer.alation.com/dev/reference/lineage-overview\n    baseURL: https://your-instance.alation.com/api/v1\n    description: >-\n      REST API for managing data lineage and dataflow objects in Alation.\n      Supports creating, retrieving, updating, and deleting lineage paths\n      between catalog objects.\n\n  - aid: alation:governance-api\n    name: Alation Governance API\n    tags:\n      - Data Governance\n      - Business Glossary\n      - Data Quality\n      - Policies\n    properties:\n      - url: https://developer.alation.com\n        type: Documentation\n      - url: openapi/alation-governance-openapi.yaml\n        type: OpenAPI\n      - url: json-schema/alation-alation-governance-glossary-term-schema.json\n        type: JSONSchema\n      - url: json-schema/alation-alation-governance-policy-schema.json\n        type: JSONSchema\n      - url: json-schema/alation-alation-governance-data-quality-rule-schema.json\n\
  \        type: JSONSchema\n      - url: json-schema/alation-alation-governance-data-quality-score-schema.json\n        type: JSONSchema\n      - url: json-structure/alation-alation-governance-glossary-term-structure.json\n        type: JSONStructure\n      - url: json-structure/alation-alation-governance-policy-structure.json\n        type: JSONStructure\n      - url: json-structure/alation-alation-governance-data-quality-rule-structure.json\n        type: JSONStructure\n      - url: json-structure/alation-alation-governance-data-quality-score-structure.json\n        type: JSONStructure\n      - url: examples/alation-alation-governance-glossary-term-example.json\n        type: Example\n      - url: examples/alation-alation-governance-policy-example.json\n        type: Example\n      - url: examples/alation-alation-governance-data-quality-rule-example.json\n        type: Example\n      - url: examples/alation-alation-governance-data-quality-score-example.json\n        type: Example\n  \
  \  humanURL: https://developer.alation.com\n    baseURL: https://your-instance.alation.com/integration/v2\n    description: >-\n      REST API for data governance workflows in Alation, including business\n      glossary management, governance policy enforcement, and data quality\n      rules and scoring.\n\n  - aid: alation:search-api\n    name: Alation Search API\n    tags:\n      - Search\n      - Data Discovery\n      - AI\n      - Catalog\n    properties:\n      - url: https://developer.alation.com\n        type: Documentation\n      - url: openapi/alation-search-openapi.yaml\n        type: OpenAPI\n      - url: json-schema/alation-alation-search-search-result-schema.json\n        type: JSONSchema\n      - url: json-schema/alation-alation-search-search-results-schema.json\n        type: JSONSchema\n      - url: json-schema/alation-alation-search-context-request-schema.json\n        type: JSONSchema\n      - url: json-schema/alation-alation-search-article-schema.json\n        type:\
  \ JSONSchema\n      - url: json-structure/alation-alation-search-search-result-structure.json\n        type: JSONStructure\n      - url: json-structure/alation-alation-search-search-results-structure.json\n        type: JSONStructure\n      - url: json-structure/alation-alation-search-context-request-structure.json\n        type: JSONStructure\n      - url: json-structure/alation-alation-search-article-structure.json\n        type: JSONStructure\n      - url: examples/alation-alation-search-search-result-example.json\n        type: Example\n      - url: examples/alation-alation-search-search-results-example.json\n        type: Example\n      - url: examples/alation-alation-search-context-request-example.json\n        type: Example\n      - url: examples/alation-alation-search-article-example.json\n        type: Example\n    humanURL: https://developer.alation.com\n    baseURL: https://your-instance.alation.com/integration/v2\n    description: >-\n      REST API for searching and discovering\
  \ catalog assets in Alation.\n      Supports full-text search, AI-powered aggregated context retrieval,\n      and article browsing.\n\ncommon:\n  - url: https://alation.com\n    type: Website\n  - url: https://developer.alation.com\n    type: Documentation\n  - url: https://developer.alation.com/dev/docs/about-the-alation-apis\n    type: GettingStarted\n  - url: https://github.com/Alation\n    type: GitHubOrganization\n  - url: rules/alation-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/alation-vocabulary.yaml\n    type: Vocabulary\n  - url: json-ld/alation-alation-context.jsonld\n    type: JSONLD\n  - url: capabilities/shared/data-catalog-api.yaml\n    type: NaftikoCapability\n    title: Alation Data Catalog Shared Capability\n  - url: capabilities/shared/lineage-api.yaml\n    type: NaftikoCapability\n    title: Alation Lineage Shared Capability\n  - url: capabilities/shared/governance-api.yaml\n    type: NaftikoCapability\n    title: Alation Governance Shared Capability\n\
  \  - url: capabilities/shared/search-api.yaml\n    type: NaftikoCapability\n    title: Alation Search Shared Capability\n  - url: capabilities/data-intelligence.yaml\n    type: NaftikoCapability\n    title: Data Intelligence Workflow\n  - type: Features\n    data:\n      - name: Data Catalog\n        description: >-\n          Centralized catalog for data sources, schemas, tables, and columns\n          with rich metadata, descriptions, and custom fields for discoverability.\n      - name: Data Lineage\n        description: >-\n          End-to-end data lineage tracking via dataflow objects showing how\n          data moves between sources, transformations, and targets.\n      - name: Business Glossary\n        description: >-\n          Collaborative business glossary for defining standardized terms,\n          abbreviations, and synonyms with stewardship assignments.\n      - name: Data Quality\n        description: >-\n          Comprehensive data quality rules covering accuracy, completeness,\n\
  \          consistency, timeliness, uniqueness, validity, and custom dimensions.\n      - name: Governance Policies\n        description: >-\n          Governance policy management for data protection, retention,\n          access control, and quality enforcement across the enterprise.\n      - name: AI-Powered Search\n        description: >-\n          Full-text and semantic search powered by AI for discovering trusted\n          data assets, with aggregated context for LLM consumption.\n      - name: Aggregated Context API\n        description: >-\n          Specialized API for AI applications to retrieve structured catalog\n          context for natural language queries, enabling RAG and AI agent workflows.\n      - name: Custom Fields\n        description: >-\n          Extensible metadata framework with custom fields for any catalog object\n          type, supporting batch updates via the REST API.\n  - type: UseCases\n    data:\n      - name: Enterprise Data Discovery\n        description:\
  \ >-\n          Enable data teams to search and find trusted data assets across all\n          data sources using metadata-enriched catalog browsing and search.\n      - name: Data Governance Compliance\n        description: >-\n          Enforce data governance policies, maintain business glossaries, and\n          track stewardship for regulatory compliance and data accountability.\n      - name: AI Data Context\n        description: >-\n          Power AI applications with structured catalog context from the\n          aggregated context API, enabling accurate data-aware LLM responses.\n      - name: Data Lineage Auditing\n        description: >-\n          Track data flows between systems for compliance auditing, impact\n          analysis, and root cause investigation of data quality issues.\n      - name: Data Quality Management\n        description: >-\n          Define and score data quality rules across catalog objects for\n          continuous quality monitoring and improvement\
  \ workflows.\n  - type: Integrations\n    data:\n      - name: Snowflake\n        description: >-\n          Native Snowflake integration for automatic metadata harvesting and\n          query log analysis to build comprehensive data lineage.\n      - name: dbt\n        description: >-\n          dbt integration for capturing transformation lineage and linking\n          dbt models to physical tables in the Alation catalog.\n      - name: Tableau\n        description: >-\n          BI metadata integration for cataloging Tableau reports and\n          dashboards with lineage to underlying data sources.\n      - name: Python SDK\n        description: >-\n          Official Python SDK and AI Agent SDK for programmatic access to\n          Alation catalog APIs and AI agent development.\n      - name: Apache Atlas\n        description: >-\n          Integration with Apache Atlas for federated metadata management\n          across heterogeneous data platforms.\nmaintainers:\n  - FN: Kin Lane\n\
  \    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/alation/refs/heads/main/apis.yml
tags:
- Data Catalog
- Data Governance
- Data Intelligence
- Data Lineage
- Data Quality
- Business Glossary
- Metadata Management
- AI
url: https://raw.githubusercontent.com/api-evangelist/alation/refs/heads/main/apis.yml
use_cases:
- description: Enable data teams to search and find trusted data assets across all data sources using metadata-enriched catalog browsing and search.
  name: Enterprise Data Discovery
- description: Enforce data governance policies, maintain business glossaries, and track stewardship for regulatory compliance and data accountability.
  name: Data Governance Compliance
- description: Power AI applications with structured catalog context from the aggregated context API, enabling accurate data-aware LLM responses.
  name: AI Data Context
- description: Track data flows between systems for compliance auditing, impact analysis, and root cause investigation of data quality issues.
  name: Data Lineage Auditing
- description: Define and score data quality rules across catalog objects for continuous quality monitoring and improvement workflows.
  name: Data Quality Management
---
