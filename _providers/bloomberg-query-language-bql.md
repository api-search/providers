---
api_count: 2
apis:
- description: Execute BQL queries programmatically via the Bloomberg API to retrieve custom computed financial data, filtered security sets, and time series expressions from Bloomberg's data universe. Accessible vi
  name: Bloomberg Query Language (BQL) API
  slug: bql-api
- description: Use Bloomberg Query Language directly in Microsoft Excel to execute complex data queries and retrieve computed results in spreadsheet cells. Supports multi-row outputs, time series, and calculated fie
  name: BQL in Bloomberg Excel Add-in
  slug: bql-excel
common:
- title: ''
  type: Portal
  url: https://www.bloomberg.com/professional/
- title: ''
  type: Documentation
  url: https://www.bloomberg.com/professional/support/api-library/
- title: ''
  type: TermsOfService
  url: https://www.bloomberg.com/notices/tos/
- title: ''
  type: PrivacyPolicy
  url: https://www.bloomberg.com/privacy/
- title: ''
  type: Support
  url: https://www.bloomberg.com/professional/support/
created: '2024-01-01'
description: Bloomberg Query Language (BQL) is a proprietary query language for accessing, filtering, aggregating, and computing on Bloomberg's financial data universe. BQL enables users to write flexible data requests that go beyond standard API fields, supporting derived calculations, time series expressions, and complex filtering of securities and data points. Available in the Bloomberg Terminal, Excel Add-in, and via API.
features:
- description: Filter securities using complex logical and conditional expressions.
  name: Security Universe Filtering
- description: Compute derived financial metrics and ratios in BQL expressions.
  name: Derived Calculations
- description: Build time series queries for historical data analysis.
  name: Time Series Expressions
- description: Aggregate data with sum, average, rank, and other functions.
  name: Aggregation Functions
- description: Query Bloomberg data across equities, fixed income, FX, and commodities.
  name: Cross-Asset Data Access
- description: Execute BQL queries directly in Excel cells for spreadsheet analysis.
  name: BQL in Excel
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Query Language (BQL)
skills: []
slug: bloomberg-query-language-bql
solutions: []
source_yaml: "aid: bloomberg-query-language-bql\nname: Bloomberg Query Language (BQL)\ndescription: Bloomberg Query Language (BQL) is a proprietary query language for\n  accessing, filtering, aggregating, and computing on Bloomberg's financial data universe.\n  BQL enables users to write flexible data requests that go beyond standard API fields,\n  supporting derived calculations, time series expressions, and complex filtering\n  of securities and data points. Available in the Bloomberg Terminal, Excel Add-in,\n  and via API.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-query-language-bql/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- BQL\n- Query Language\n- Financial Data\n- Analytics\n- Data Query\n- Bloomberg\napis:\n- aid: bloomberg-query-language-bql:bql-api\n  name: Bloomberg Query Language (BQL) API\n \
  \ description: Execute BQL queries programmatically via the Bloomberg API to retrieve\n    custom computed financial data, filtered security sets, and time series expressions\n    from Bloomberg's data universe. Accessible via BLPAPI and Bloomberg Excel Add-in.\n  humanURL: https://www.bloomberg.com/professional/support/api-library/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - BQL\n  - Query API\n  - Financial Data\n  - Time Series\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/support/api-library/\n- aid: bloomberg-query-language-bql:bql-excel\n  name: BQL in Bloomberg Excel Add-in\n  description: Use Bloomberg Query Language directly in Microsoft Excel to execute\n    complex data queries and retrieve computed results in spreadsheet cells. Supports\n    multi-row outputs, time series, and calculated fields.\n  humanURL: https://www.bloomberg.com/professional/solution/bloomberg-excel/\n  baseURL: https://bloomberg.com/bql-excel\n  tags:\n\
  \  - BQL\n  - Excel\n  - Spreadsheet\n  - Formulas\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/bloomberg-excel/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://www.bloomberg.com/professional/support/api-library/\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n  data:\n  - name: Security Universe Filtering\n    description: Filter securities using complex logical and conditional expressions.\n  - name: Derived Calculations\n    description: Compute derived financial metrics and ratios in BQL expressions.\n  - name: Time Series Expressions\n    description: Build time series queries for historical data analysis.\n  - name: Aggregation Functions\n    description: Aggregate data with sum, average,\
  \ rank, and other functions.\n  - name: Cross-Asset Data Access\n    description: Query Bloomberg data across equities, fixed income, FX, and commodities.\n  - name: BQL in Excel\n    description: Execute BQL queries directly in Excel cells for spreadsheet analysis.\n- type: UseCases\n  data:\n  - name: Quantitative Screening\n    description: Screen securities using complex fundamental and technical criteria.\n  - name: Custom Analytics\n    description: Create custom financial metrics not available as standard data fields.\n  - name: Portfolio Analysis\n    description: Analyze portfolio characteristics using flexible BQL expressions.\n  - name: Backtesting\n    description: Access historical data via BQL time series for strategy backtesting.\n  - name: Risk Reporting\n    description: Compute and aggregate risk metrics across portfolios using BQL.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-query-language-bql/refs/heads/main/apis.yml
tags:
- BQL
- Query Language
- Financial Data
- Analytics
- Data Query
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-query-language-bql/refs/heads/main/apis.yml
use_cases:
- description: Screen securities using complex fundamental and technical criteria.
  name: Quantitative Screening
- description: Create custom financial metrics not available as standard data fields.
  name: Custom Analytics
- description: Analyze portfolio characteristics using flexible BQL expressions.
  name: Portfolio Analysis
- description: Access historical data via BQL time series for strategy backtesting.
  name: Backtesting
- description: Compute and aggregate risk metrics across portfolios using BQL.
  name: Risk Reporting
---
