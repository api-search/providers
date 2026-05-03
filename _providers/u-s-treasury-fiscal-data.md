---
api_count: 1
api_specs:
- filename: treasury-fiscal-data-api-openapi.yaml
  format: yaml
  label: Treasury Fiscal Data API
  slug: fiscal-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/openapi/treasury-fiscal-data-api-openapi.yaml
apis:
- description: The U.S. Treasury Fiscal Data API provides free, open access to federal financial data published by the Bureau of the Fiscal Service. Covers 80+ datasets including the Debt to the Penny dataset, Treas
  name: Treasury Fiscal Data API
  slug: fiscal-data-api
capabilities:
- description: Workflow capability for economists, policy analysts, financial journalists, and researchers to access U.S. Treasury federal financial data including national debt trends, exchange rates, interest rate
  name: Treasury Fiscal Data Intelligence
  slug: fiscal-data-intelligence
common:
- title: ''
  type: Website
  url: https://fiscaldata.treasury.gov/
- title: ''
  type: Documentation
  url: https://fiscaldata.treasury.gov/api-documentation/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/rules/treasury-fiscal-data-api-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/vocabulary/u-s-treasury-fiscal-data-vocabulary.yaml
- title: Fiscal Data Intelligence
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/capabilities/fiscal-data-intelligence.yaml
created: '2024-12-25'
description: The U.S. Treasury Bureau of the Fiscal Service manages the government's finances including collecting revenue, paying federal bills, managing federal debt, and producing the nation's financial accounts. Their Fiscal Data API provides free, open access to federal financial data through a standardized RESTful API covering 80+ datasets. Key datasets include the Debt to the Penny (daily public debt outstanding), Treasury Reporting Rates of Exchange (quarterly foreign currency rates), Average Interest Rates on U.S. Treasury Securities, Daily Treasury Statements, Monthly Treasury Statements, and U.S. savings bond data. No authentication required.
features:
- description: All Treasury Fiscal Data API endpoints are publicly accessible without API keys or registration, enabling immediate programmatic access.
  name: No Authentication Required
- description: Use the fields parameter to request only the specific data fields needed, reducing response payload size and improving performance.
  name: Flexible Field Selection
- description: Filter datasets using field:operator:value syntax supporting equality, range, and set membership operators across any field in the dataset.
  name: Advanced Filtering
- description: All endpoints support page[number] and page[size] pagination with metadata indicating total record count and total pages available.
  name: Pagination Support
- description: API responses available in JSON, XML, and CSV formats suitable for programmatic consumption, data warehousing, and spreadsheet analysis.
  name: Multiple Output Formats
- description: 80+ datasets covering all major Bureau of the Fiscal Service financial reports from the Debt to the Penny to Monthly Treasury Statements.
  name: Comprehensive Coverage
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Federal Reserve Economic Database (FRED) integrates Treasury Fiscal Data series for economic research and modeling applications.
  name: FRED Economic Database
- description: Federal spending transparency portal uses Bureau of the Fiscal Service data alongside Treasury Fiscal Data for comprehensive spending analysis.
  name: USASpending.gov
- description: Treasury exchange rates and fiscal data support OMB/FASAB-compliant financial reporting across federal agencies and programs.
  name: Federal Accounting Standards
- description: The official Treasury Fiscal Data portal provides data visualization, dataset explorer, and download tools built on the same API.
  name: fiscaldata.treasury.gov
jsonld:
- class_count: 0
  name: Treasury Fiscal Data Api Context
  property_count: 62
  slug: treasury-fiscal-data-api-context
layout: provider
modified: '2026-05-03'
name: U.S. Treasury Fiscal Data
rules:
- name: U.S. Treasury Fiscal Data API Rules
  rule_count: 31
  severity_counts:
    error: 6
    hint: 0
    info: 12
    warn: 13
  slug: treasury-fiscal-data-api-rules
skills: []
slug: u-s-treasury-fiscal-data
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: u-s-treasury-fiscal-data\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/apis.yml\napis:\n  - aid: u-s-treasury-fiscal-data:fiscal-data-api\n    name: Treasury Fiscal Data API\n    tags:\n      - National Debt\n      - Exchange Rates\n      - Treasury Statements\n      - Securities\n      - Federal Finance\n    humanURL: https://fiscaldata.treasury.gov/\n    baseURL: https://api.fiscaldata.treasury.gov/services/api/fiscal_service\n    properties:\n      - url: https://fiscaldata.treasury.gov/api-documentation/\n        type: Documentation\n      - url: https://fiscaldata.treasury.gov/api-documentation/\n        type: GettingStarted\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/openapi/treasury-fiscal-data-api-openapi.yaml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/json-schema/treasury-debt-record-schema.json\n\
  \        type: JSONSchema\n        title: Debt Record Schema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/json-schema/treasury-exchange-rate-record-schema.json\n        type: JSONSchema\n        title: Exchange Rate Record Schema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/json-schema/treasury-interest-rate-record-schema.json\n        type: JSONSchema\n        title: Interest Rate Record Schema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/json-schema/treasury-daily-treasury-record-schema.json\n        type: JSONSchema\n        title: Daily Treasury Statement Record Schema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/json-schema/treasury-monthly-treasury-record-schema.json\n        type: JSONSchema\n\
  \        title: Monthly Treasury Statement Record Schema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/json-ld/treasury-fiscal-data-api-context.jsonld\n        type: JSON-LD\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/examples/treasury-debt-record-example.json\n        type: Example\n        title: Debt Record Example\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/examples/treasury-exchange-rate-record-example.json\n        type: Example\n        title: Exchange Rate Record Example\n    description: >-\n      The U.S. Treasury Fiscal Data API provides free, open access to federal\n      financial data published by the Bureau of the Fiscal Service. Covers 80+\n      datasets including the Debt to the Penny dataset, Treasury Reporting Rates\n      of Exchange, average interest\
  \ rates on Treasury securities, Daily Treasury\n      Statements, Monthly Treasury Statements, U.S. savings bond redemption\n      tables, and public debt outstanding by security type. No authentication\n      required. Supports filtering, sorting, field selection, and pagination.\n\nname: U.S. Treasury Fiscal Data\ntags:\n  - Federal Government\n  - Finance\n  - Treasury\n  - National Debt\n  - Exchange Rates\n  - Economics\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - type: Website\n    url: https://fiscaldata.treasury.gov/\n  - type: Documentation\n    url: https://fiscaldata.treasury.gov/api-documentation/\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/rules/treasury-fiscal-data-api-rules.yml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/vocabulary/u-s-treasury-fiscal-data-vocabulary.yaml\n\
  \  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/capabilities/fiscal-data-intelligence.yaml\n    title: Fiscal Data Intelligence\n  - type: Features\n    data:\n      - name: No Authentication Required\n        description: >-\n          All Treasury Fiscal Data API endpoints are publicly accessible without\n          API keys or registration, enabling immediate programmatic access.\n      - name: Flexible Field Selection\n        description: >-\n          Use the fields parameter to request only the specific data fields needed,\n          reducing response payload size and improving performance.\n      - name: Advanced Filtering\n        description: >-\n          Filter datasets using field:operator:value syntax supporting equality,\n          range, and set membership operators across any field in the dataset.\n      - name: Pagination Support\n        description: >-\n          All endpoints\
  \ support page[number] and page[size] pagination with\n          metadata indicating total record count and total pages available.\n      - name: Multiple Output Formats\n        description: >-\n          API responses available in JSON, XML, and CSV formats suitable for\n          programmatic consumption, data warehousing, and spreadsheet analysis.\n      - name: Comprehensive Coverage\n        description: >-\n          80+ datasets covering all major Bureau of the Fiscal Service financial\n          reports from the Debt to the Penny to Monthly Treasury Statements.\n  - type: UseCases\n    data:\n      - name: National Debt Tracking\n        description: >-\n          Journalists, economists, and citizens monitor daily changes in U.S.\n          public debt outstanding including amounts held by the public and\n          intragovernmental holdings.\n      - name: Exchange Rate Research\n        description: >-\n          Federal agencies, researchers, and businesses use Treasury exchange\n\
  \          rates for reporting foreign currency transactions in accordance with\n          federal accounting standards.\n      - name: Budget Analysis\n        description: >-\n          Policy analysts and budget offices track federal government receipts\n          and outlays from Monthly Treasury Statements to assess deficit trends.\n      - name: Interest Rate Monitoring\n        description: >-\n          Economists and investors track average interest rates on Treasury\n          securities to analyze government borrowing costs and monetary policy.\n      - name: Treasury Cash Management\n        description: >-\n          Financial researchers analyze Daily Treasury Statement data to\n          understand federal government cash flows and liquidity management.\n  - type: Integrations\n    data:\n      - name: FRED Economic Database\n        description: >-\n          Federal Reserve Economic Database (FRED) integrates Treasury Fiscal\n          Data series for economic research\
  \ and modeling applications.\n      - name: USASpending.gov\n        description: >-\n          Federal spending transparency portal uses Bureau of the Fiscal Service\n          data alongside Treasury Fiscal Data for comprehensive spending analysis.\n      - name: Federal Accounting Standards\n        description: >-\n          Treasury exchange rates and fiscal data support OMB/FASAB-compliant\n          financial reporting across federal agencies and programs.\n      - name: fiscaldata.treasury.gov\n        description: >-\n          The official Treasury Fiscal Data portal provides data visualization,\n          dataset explorer, and download tools built on the same API.\ncreated: '2024-12-25'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  The U.S. Treasury Bureau of the Fiscal Service manages the government's\n  finances including collecting revenue, paying federal bills, managing\n  federal debt, and producing the nation's financial accounts. Their Fiscal\n  Data\
  \ API provides free, open access to federal financial data through a\n  standardized RESTful API covering 80+ datasets. Key datasets include the\n  Debt to the Penny (daily public debt outstanding), Treasury Reporting Rates\n  of Exchange (quarterly foreign currency rates), Average Interest Rates on\n  U.S. Treasury Securities, Daily Treasury Statements, Monthly Treasury\n  Statements, and U.S. savings bond data. No authentication required.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/apis.yml
tags:
- Federal Government
- Finance
- Treasury
- National Debt
- Exchange Rates
- Economics
url: https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/apis.yml
use_cases:
- description: Journalists, economists, and citizens monitor daily changes in U.S. public debt outstanding including amounts held by the public and intragovernmental holdings.
  name: National Debt Tracking
- description: Federal agencies, researchers, and businesses use Treasury exchange rates for reporting foreign currency transactions in accordance with federal accounting standards.
  name: Exchange Rate Research
- description: Policy analysts and budget offices track federal government receipts and outlays from Monthly Treasury Statements to assess deficit trends.
  name: Budget Analysis
- description: Economists and investors track average interest rates on Treasury securities to analyze government borrowing costs and monetary policy.
  name: Interest Rate Monitoring
- description: Financial researchers analyze Daily Treasury Statement data to understand federal government cash flows and liquidity management.
  name: Treasury Cash Management
---
