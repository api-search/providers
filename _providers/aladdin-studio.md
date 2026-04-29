---
api_count: 4
api_specs:
- filename: aladdin-studio-graph-openapi.yaml
  format: yaml
  label: Aladdin Graph API
  slug: graph-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aladdin-studio/refs/heads/main/openapi/aladdin-studio-graph-openapi.yaml
- filename: aladdin-studio-data-cloud-openapi.yaml
  format: yaml
  label: Aladdin Data Cloud API
  slug: data-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aladdin-studio/refs/heads/main/openapi/aladdin-studio-data-cloud-openapi.yaml
- filename: aladdin-studio-trading-openapi.yaml
  format: yaml
  label: Aladdin Trading API
  slug: trading-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aladdin-studio/refs/heads/main/openapi/aladdin-studio-trading-openapi.yaml
- filename: aladdin-studio-investment-research-openapi.yaml
  format: yaml
  label: Aladdin Investment Research API
  slug: investment-research-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aladdin-studio/refs/heads/main/openapi/aladdin-studio-investment-research-openapi.yaml
apis:
- description: The Aladdin Graph API provides RESTful access to portfolio data, securities, positions, risk analytics, and other Aladdin platform capabilities. Powers the AladdinSDK Python client with OAuth and Basi
  name: Aladdin Graph API
  slug: graph-api
- description: The Aladdin Data Cloud API provides access to Snowflake-based analytics data warehousing with OAuth and JWT authentication. Enables large-scale portfolio analytics and data science workflows using Sno
  name: Aladdin Data Cloud API
  slug: data-cloud-api
- description: The Aladdin Trading API enables order management and trading workflow integration. Available as the asdk_plugin_trading Python package built on the AladdinSDK framework.
  name: Aladdin Trading API
  slug: trading-api
- description: The Aladdin Investment Research API provides access to research data, analyst insights, and quantitative analytics built on Aladdin's data infrastructure. Available as the asdk_plugin_investment_resea
  name: Aladdin Investment Research API
  slug: investment-research-api
capabilities:
- description: Workflow capability combining the Aladdin Graph API and Data Cloud API for institutional portfolio analytics. Provides portfolio managers, risk analysts, and quantitative researchers with unified acce
  name: Aladdin Studio Portfolio Analytics
  slug: portfolio-analytics
common:
- title: ''
  type: Portal
  url: https://www.blackrock.com/aladdin/products/apis
- title: ''
  type: Documentation
  url: https://www.blackrock.com/aladdin/products/aladdin-studio
- title: ''
  type: GitHubOrganization
  url: https://github.com/blackrock
- title: Python SDK (AladdinSDK)
  type: SDK
  url: https://github.com/blackrock/aladdinsdk
- title: Python SDK (PyPI)
  type: SDK
  url: https://pypi.org/project/aladdinsdk/
- title: Plugin Builder
  type: SDK
  url: https://github.com/blackrock/aladdinsdk-plugin-builder
- title: ''
  type: SpectralRules
  url: rules/aladdin-studio-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/aladdin-studio-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/aladdin-studio-context.jsonld
- title: Aladdin Graph API Shared Capability
  type: NaftikoCapability
  url: capabilities/shared/graph-api.yaml
- title: Aladdin Data Cloud API Shared Capability
  type: NaftikoCapability
  url: capabilities/shared/data-cloud-api.yaml
- title: Portfolio Analytics Workflow
  type: NaftikoCapability
  url: capabilities/portfolio-analytics.yaml
created: '2024-03-05'
description: Aladdin Studio is BlackRock's developer platform enabling institutional investors, asset managers, and wealth managers to build custom solutions on top of the Aladdin investment operating system. APIs provide access to portfolio data, risk analytics, trading, investment research, and the Aladdin Data Cloud, supporting approximately $25 trillion in assets managed on the platform.
features:
- description: Retrieve comprehensive portfolio data including positions, holdings, securities, and performance metrics across asset classes.
  name: Portfolio Data Access
- description: Access Aladdin's institutional-grade risk analytics including factor exposures, VaR, scenario analysis, and stress testing across public and private markets.
  name: Risk Analytics
- description: Snowflake-based data warehousing providing access to large-scale portfolio analytics with OAuth and JWT authentication supporting both Snowflake connectors and Snowpark.
  name: Aladdin Data Cloud
- description: Order management and trading workflow APIs enabling integration with Aladdin's trading platform for order creation, tracking, and execution.
  name: Trading Integration
- description: APIs for accessing investment research data, analyst insights, and quantitative analytics built on Aladdin's data infrastructure.
  name: Investment Research Access
- description: Support for long-running operation (LRO) patterns with configurable polling, enabling asynchronous processing of computationally intensive analytics requests.
  name: Long-Running Operations
- description: Batch API support with sequential and parallel execution capabilities for processing large volumes of portfolio data operations efficiently.
  name: Batch Processing
- description: Flexible authentication supporting Basic Auth with API tokens, OAuth client credentials flow, OAuth refresh token flow, and Snowflake JWT for Data Cloud access.
  name: Multi-Auth Support
- description: Extensible SDK plugin architecture enabling domain-specific packages (trading, investment research) built on top of the core AladdinSDK.
  name: Plugin Architecture
- description: Downloadable Python Jupyter Notebooks and code samples in multiple languages for rapid solution development and prototyping.
  name: Jupyter Notebook Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Aladdin Data Cloud integration with Snowflake for large-scale analytics, supporting both standard connectors and Snowpark for Python-based data science workflows.
  name: Snowflake
- description: Aladdin available on AWS infrastructure (general availability expected second half of 2026) complementing existing Azure deployment.
  name: Amazon Web Services
- description: Primary cloud infrastructure for Aladdin platform, supporting enterprise deployments across institutional clients.
  name: Microsoft Azure
- description: Private markets data integrated into Aladdin ecosystem following BlackRock's acquisition for alternatives and private market analytics.
  name: Preqin
- description: First-class Python support via AladdinSDK on PyPI, with Jupyter Notebook examples and plugin architecture for domain extensions.
  name: Python Ecosystem
- description: ESG risk data integrated into Aladdin portfolio management for reputational and environmental risk analysis.
  name: RepRisk
jsonld:
- class_count: 18
  name: Aladdin Studio Context
  property_count: 72
  slug: aladdin-studio-context
layout: provider
modified: '2026-04-19'
name: Aladdin Studio
rules:
- name: Aladdin Studio API Rules
  rule_count: 36
  severity_counts:
    error: 16
    hint: 0
    info: 3
    warn: 17
  slug: aladdin-studio-spectral-rules
skills: []
slug: aladdin-studio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: aladdin-studio\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/aladdin-studio/refs/heads/main/apis.yml\nname: Aladdin Studio\ntags:\n  - Financial\n  - Investment Management\n  - Portfolio Analytics\n  - Risk Management\n  - Asset Management\n  - BlackRock\n  - Data Cloud\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  Aladdin Studio is BlackRock's developer platform enabling institutional\n  investors, asset managers, and wealth managers to build custom solutions on\n  top of the Aladdin investment operating system. APIs provide access to\n  portfolio data, risk analytics, trading, investment research, and the Aladdin\n  Data Cloud, supporting approximately $25 trillion in assets managed on the\n  platform.\ncreated: '2024-03-05'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: aladdin-studio:graph-api\n    name: Aladdin Graph API\n    tags:\n      - Portfolio Data\n\
  \      - Investment Management\n      - REST\n    properties:\n      - url: https://www.blackrock.com/aladdin/products/apis\n        type: Documentation\n      - url: https://www.blackrock.com/aladdin/products/apis\n        type: APIReference\n      - url: openapi/aladdin-studio-graph-openapi.yaml\n        type: OpenAPI\n      - url: json-schema/aladdin-studio-graph-portfolio-schema.json\n        type: JSONSchema\n      - url: json-schema/aladdin-studio-graph-portfolio-list-schema.json\n        type: JSONSchema\n      - url: json-schema/aladdin-studio-graph-position-schema.json\n        type: JSONSchema\n      - url: json-schema/aladdin-studio-graph-position-list-schema.json\n        type: JSONSchema\n      - url: json-schema/aladdin-studio-graph-factor-exposure-schema.json\n        type: JSONSchema\n      - url: json-schema/aladdin-studio-graph-portfolio-risk-schema.json\n        type: JSONSchema\n      - url: json-schema/aladdin-studio-graph-security-schema.json\n        type: JSONSchema\n\
  \      - url: json-structure/aladdin-studio-graph-portfolio-structure.json\n        type: JSONStructure\n      - url: json-structure/aladdin-studio-graph-position-structure.json\n        type: JSONStructure\n      - url: json-structure/aladdin-studio-graph-portfolio-risk-structure.json\n        type: JSONStructure\n      - url: json-structure/aladdin-studio-graph-security-structure.json\n        type: JSONStructure\n      - url: examples/aladdin-studio-graph-portfolio-example.json\n        type: Example\n      - url: examples/aladdin-studio-graph-position-example.json\n        type: Example\n      - url: examples/aladdin-studio-graph-portfolio-risk-example.json\n        type: Example\n      - url: examples/aladdin-studio-graph-security-example.json\n        type: Example\n    humanURL: https://www.blackrock.com/aladdin/products/apis\n    baseURL: https://api.blackrock.com/v1\n    description: >-\n      The Aladdin Graph API provides RESTful access to portfolio data,\n      securities,\
  \ positions, risk analytics, and other Aladdin platform\n      capabilities. Powers the AladdinSDK Python client with OAuth and Basic\n      Auth authentication.\n  - aid: aladdin-studio:data-cloud-api\n    name: Aladdin Data Cloud API\n    tags:\n      - Data Cloud\n      - Snowflake\n      - Analytics\n    properties:\n      - url: https://www.blackrock.com/aladdin/products/apis\n        type: Documentation\n      - url: openapi/aladdin-studio-data-cloud-openapi.yaml\n        type: OpenAPI\n      - url: json-schema/aladdin-studio-data-cloud-connection-schema.json\n        type: JSONSchema\n      - url: json-schema/aladdin-studio-data-cloud-query-request-schema.json\n        type: JSONSchema\n      - url: json-schema/aladdin-studio-data-cloud-query-result-schema.json\n        type: JSONSchema\n      - url: json-schema/aladdin-studio-data-cloud-dataset-schema.json\n        type: JSONSchema\n      - url: json-structure/aladdin-studio-data-cloud-connection-structure.json\n        type: JSONStructure\n\
  \      - url: json-structure/aladdin-studio-data-cloud-query-result-structure.json\n        type: JSONStructure\n      - url: json-structure/aladdin-studio-data-cloud-dataset-structure.json\n        type: JSONStructure\n      - url: examples/aladdin-studio-data-cloud-connection-example.json\n        type: Example\n      - url: examples/aladdin-studio-data-cloud-query-result-example.json\n        type: Example\n      - url: examples/aladdin-studio-data-cloud-dataset-example.json\n        type: Example\n    humanURL: https://www.blackrock.com/aladdin/products/apis\n    baseURL: https://api.blackrock.com/adc/v1\n    description: >-\n      The Aladdin Data Cloud API provides access to Snowflake-based analytics\n      data warehousing with OAuth and JWT authentication. Enables large-scale\n      portfolio analytics and data science workflows using Snowflake connectors\n      and Snowpark.\n  - aid: aladdin-studio:trading-api\n    name: Aladdin Trading API\n    tags:\n      - Trading\n     \
  \ - Order Management\n      - Financial\n    properties:\n      - url: https://www.blackrock.com/aladdin/products/apis\n        type: Documentation\n      - url: openapi/aladdin-studio-trading-openapi.yaml\n        type: OpenAPI\n      - url: https://pypi.org/project/asdk-plugin-trading/\n        type: SDK\n        title: Python Trading Plugin\n      - url: json-schema/aladdin-studio-trading-order-schema.json\n        type: JSONSchema\n      - url: json-schema/aladdin-studio-trading-order-request-schema.json\n        type: JSONSchema\n      - url: json-structure/aladdin-studio-trading-order-structure.json\n        type: JSONStructure\n      - url: examples/aladdin-studio-trading-order-example.json\n        type: Example\n    humanURL: https://www.blackrock.com/aladdin/products/apis\n    baseURL: https://api.blackrock.com/trading/v1\n    description: >-\n      The Aladdin Trading API enables order management and trading workflow\n      integration. Available as the asdk_plugin_trading Python\
  \ package built\n      on the AladdinSDK framework.\n  - aid: aladdin-studio:investment-research-api\n    name: Aladdin Investment Research API\n    tags:\n      - Investment Research\n      - Analytics\n      - Portfolio\n    properties:\n      - url: https://www.blackrock.com/aladdin/products/apis\n        type: Documentation\n      - url: openapi/aladdin-studio-investment-research-openapi.yaml\n        type: OpenAPI\n      - url: https://pypi.org/project/asdk-plugin-investment-research/\n        type: SDK\n        title: Python Investment Research Plugin\n      - url: json-schema/aladdin-studio-investment-research-security-research-schema.json\n        type: JSONSchema\n      - url: json-schema/aladdin-studio-investment-research-portfolio-analytics-schema.json\n        type: JSONSchema\n      - url: json-structure/aladdin-studio-investment-research-security-research-structure.json\n        type: JSONStructure\n      - url: json-structure/aladdin-studio-investment-research-portfolio-analytics-structure.json\n\
  \        type: JSONStructure\n      - url: examples/aladdin-studio-investment-research-security-research-example.json\n        type: Example\n      - url: examples/aladdin-studio-investment-research-portfolio-analytics-example.json\n        type: Example\n    humanURL: https://www.blackrock.com/aladdin/products/apis\n    baseURL: https://api.blackrock.com/research/v1\n    description: >-\n      The Aladdin Investment Research API provides access to research data,\n      analyst insights, and quantitative analytics built on Aladdin's data\n      infrastructure. Available as the asdk_plugin_investment_research Python\n      package.\ncommon:\n  - url: https://www.blackrock.com/aladdin/products/apis\n    type: Portal\n  - url: https://www.blackrock.com/aladdin/products/aladdin-studio\n    type: Documentation\n  - url: https://github.com/blackrock\n    type: GitHubOrganization\n  - url: https://github.com/blackrock/aladdinsdk\n    type: SDK\n    title: Python SDK (AladdinSDK)\n  - url: https://pypi.org/project/aladdinsdk/\n\
  \    type: SDK\n    title: Python SDK (PyPI)\n  - url: https://github.com/blackrock/aladdinsdk-plugin-builder\n    type: SDK\n    title: Plugin Builder\n  - url: rules/aladdin-studio-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/aladdin-studio-vocabulary.yaml\n    type: Vocabulary\n  - url: json-ld/aladdin-studio-context.jsonld\n    type: JSONLD\n  - url: capabilities/shared/graph-api.yaml\n    type: NaftikoCapability\n    title: Aladdin Graph API Shared Capability\n  - url: capabilities/shared/data-cloud-api.yaml\n    type: NaftikoCapability\n    title: Aladdin Data Cloud API Shared Capability\n  - url: capabilities/portfolio-analytics.yaml\n    type: NaftikoCapability\n    title: Portfolio Analytics Workflow\n  - type: Features\n    data:\n      - name: Portfolio Data Access\n        description: >-\n          Retrieve comprehensive portfolio data including positions, holdings,\n          securities, and performance metrics across asset classes.\n      - name: Risk\
  \ Analytics\n        description: >-\n          Access Aladdin's institutional-grade risk analytics including factor\n          exposures, VaR, scenario analysis, and stress testing across public\n          and private markets.\n      - name: Aladdin Data Cloud\n        description: >-\n          Snowflake-based data warehousing providing access to large-scale\n          portfolio analytics with OAuth and JWT authentication supporting\n          both Snowflake connectors and Snowpark.\n      - name: Trading Integration\n        description: >-\n          Order management and trading workflow APIs enabling integration with\n          Aladdin's trading platform for order creation, tracking, and execution.\n      - name: Investment Research Access\n        description: >-\n          APIs for accessing investment research data, analyst insights, and\n          quantitative analytics built on Aladdin's data infrastructure.\n      - name: Long-Running Operations\n        description: >-\n  \
  \        Support for long-running operation (LRO) patterns with configurable\n          polling, enabling asynchronous processing of computationally intensive\n          analytics requests.\n      - name: Batch Processing\n        description: >-\n          Batch API support with sequential and parallel execution capabilities\n          for processing large volumes of portfolio data operations efficiently.\n      - name: Multi-Auth Support\n        description: >-\n          Flexible authentication supporting Basic Auth with API tokens, OAuth\n          client credentials flow, OAuth refresh token flow, and Snowflake JWT\n          for Data Cloud access.\n      - name: Plugin Architecture\n        description: >-\n          Extensible SDK plugin architecture enabling domain-specific packages\n          (trading, investment research) built on top of the core AladdinSDK.\n      - name: Jupyter Notebook Integration\n        description: >-\n          Downloadable Python Jupyter Notebooks\
  \ and code samples in multiple\n          languages for rapid solution development and prototyping.\n  - type: UseCases\n    data:\n      - name: Custom Portfolio Analytics\n        description: >-\n          Build bespoke portfolio analysis tools using Aladdin's risk and\n          performance data to generate custom insights for investment teams.\n      - name: Automated Risk Reporting\n        description: >-\n          Automate generation of risk reports, factor exposure summaries,\n          and stress test results using Aladdin's risk analytics APIs.\n      - name: Trading Workflow Automation\n        description: >-\n          Integrate Aladdin trading data into proprietary order management\n          systems and automate trading workflow processes.\n      - name: Investment Research Integration\n        description: >-\n          Connect internal research platforms to Aladdin's investment research\n          data for unified analyst workflow tooling.\n      - name: Data Science\
  \ and Quantitative Research\n        description: >-\n          Access Aladdin Data Cloud from Snowflake-based data science\n          environments for quantitative model development and backtesting.\n      - name: Client Reporting Automation\n        description: >-\n          Build automated client reporting solutions pulling portfolio\n          performance, risk, and holdings data from Aladdin APIs.\n      - name: Multi-Asset Class Analytics\n        description: >-\n          Analyze portfolios across public equities, fixed income, alternatives,\n          and private markets using Aladdin's unified data platform.\n  - type: Integrations\n    data:\n      - name: Snowflake\n        description: >-\n          Native Aladdin Data Cloud integration with Snowflake for large-scale\n          analytics, supporting both standard connectors and Snowpark for\n          Python-based data science workflows.\n      - name: Amazon Web Services\n        description: >-\n          Aladdin available\
  \ on AWS infrastructure (general availability\n          expected second half of 2026) complementing existing Azure deployment.\n      - name: Microsoft Azure\n        description: >-\n          Primary cloud infrastructure for Aladdin platform, supporting\n          enterprise deployments across institutional clients.\n      - name: Preqin\n        description: >-\n          Private markets data integrated into Aladdin ecosystem following\n          BlackRock's acquisition for alternatives and private market analytics.\n      - name: Python Ecosystem\n        description: >-\n          First-class Python support via AladdinSDK on PyPI, with Jupyter\n          Notebook examples and plugin architecture for domain extensions.\n      - name: RepRisk\n        description: >-\n          ESG risk data integrated into Aladdin portfolio management for\n          reputational and environmental risk analysis.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aladdin-studio/refs/heads/main/apis.yml
tags:
- Financial
- Investment Management
- Portfolio Analytics
- Risk Management
- Asset Management
- BlackRock
- Data Cloud
url: https://raw.githubusercontent.com/api-evangelist/aladdin-studio/refs/heads/main/apis.yml
use_cases:
- description: Build bespoke portfolio analysis tools using Aladdin's risk and performance data to generate custom insights for investment teams.
  name: Custom Portfolio Analytics
- description: Automate generation of risk reports, factor exposure summaries, and stress test results using Aladdin's risk analytics APIs.
  name: Automated Risk Reporting
- description: Integrate Aladdin trading data into proprietary order management systems and automate trading workflow processes.
  name: Trading Workflow Automation
- description: Connect internal research platforms to Aladdin's investment research data for unified analyst workflow tooling.
  name: Investment Research Integration
- description: Access Aladdin Data Cloud from Snowflake-based data science environments for quantitative model development and backtesting.
  name: Data Science and Quantitative Research
- description: Build automated client reporting solutions pulling portfolio performance, risk, and holdings data from Aladdin APIs.
  name: Client Reporting Automation
- description: Analyze portfolios across public equities, fixed income, alternatives, and private markets using Aladdin's unified data platform.
  name: Multi-Asset Class Analytics
---
