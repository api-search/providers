---
api_count: 3
apis:
- description: The core API providing programmatic access to the Bloomberg data ecosystem including real-time prices, reference data, news, analytics, and Terminal functions.
  name: Bloomberg Open API (BLPAPI)
  slug: blpapi
- description: Enterprise bulk data delivery platform for acquiring Bloomberg reference data, pricing, corporate actions, and analytics at scale for data management and downstream applications.
  name: Bloomberg Data License
  slug: data-license
- description: Remote access service extending Bloomberg Terminal capabilities to any internet-connected device, enabling mobile and remote access to Bloomberg data, analytics, and messaging.
  name: Bloomberg Anywhere
  slug: bloomberg-anywhere
common:
- title: ''
  type: Portal
  url: https://www.bloomberg.com/professional/
- title: ''
  type: Documentation
  url: https://developer.bloomberg.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/bloomberg
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
description: Bloomberg's Product Suite encompasses the complete portfolio of Bloomberg professional products including the Bloomberg Terminal, data products, analytics solutions, trading platforms, media, and technology infrastructure. The suite serves financial professionals across asset management, banking, insurance, government, and corporate sectors with integrated data, analytics, and workflow tools.
features:
- description: Professional financial workstation with data, analytics, and messaging.
  name: Bloomberg Terminal
- description: B-PIPE and Data License for enterprise-wide data distribution.
  name: Enterprise Data
- description: PORT and multi-asset analytics for portfolio management.
  name: Portfolio Analytics
- description: EMSX and Tradebook for electronic order routing and execution.
  name: Trading Solutions
- description: Credit and market risk analytics across asset classes.
  name: Risk Solutions
- description: Bloomberg Intelligence research and analytics.
  name: Research Solutions
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Product Suite
skills: []
slug: bloomberg-product-suite
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bloomberg-product-suite\nname: Bloomberg Product Suite\ndescription: Bloomberg's Product Suite encompasses the complete portfolio of Bloomberg\n  professional products including the Bloomberg Terminal, data products, analytics\n  solutions, trading platforms, media, and technology infrastructure. The suite serves\n  financial professionals across asset management, banking, insurance, government,\n  and corporate sectors with integrated data, analytics, and workflow tools.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-product-suite/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Product Suite\n- Terminal\n- Data\n- Analytics\n- Trading\n- Financial Technology\n- Bloomberg\napis:\n- aid: bloomberg-product-suite:blpapi\n  name: Bloomberg Open API (BLPAPI)\n  description: The core API providing programmatic\
  \ access to the Bloomberg data ecosystem\n    including real-time prices, reference data, news, analytics, and Terminal functions.\n  humanURL: https://bloomberg.github.io/blpapi-docs/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Core API\n  - Market Data\n  - Reference Data\n  properties:\n  - type: Documentation\n    url: https://bloomberg.github.io/blpapi-docs/\n- aid: bloomberg-product-suite:data-license\n  name: Bloomberg Data License\n  description: Enterprise bulk data delivery platform for acquiring Bloomberg reference\n    data, pricing, corporate actions, and analytics at scale for data management\n    and downstream applications.\n  humanURL: https://www.bloomberg.com/professional/products/data/data-management/data-license/\n  baseURL: https://dlws.bloomberg.com\n  tags:\n  - Data License\n  - Bulk Data\n  - Enterprise\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/products/data/data-management/data-license/\n- aid: bloomberg-product-suite:bloomberg-anywhere\n\
  \  name: Bloomberg Anywhere\n  description: Remote access service extending Bloomberg Terminal capabilities to\n    any internet-connected device, enabling mobile and remote access to Bloomberg\n    data, analytics, and messaging.\n  humanURL: https://www.bloomberg.com/professional/solution/bloomberg-anywhere/\n  baseURL: https://bba.bloomberg.net\n  tags:\n  - Remote Access\n  - Mobile\n  - Bloomberg Anywhere\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/bloomberg-anywhere/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://developer.bloomberg.com/\n- type: GitHubOrganization\n  url: https://github.com/bloomberg\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n  data:\n  - name: Bloomberg Terminal\n\
  \    description: Professional financial workstation with data, analytics, and messaging.\n  - name: Enterprise Data\n    description: B-PIPE and Data License for enterprise-wide data distribution.\n  - name: Portfolio Analytics\n    description: PORT and multi-asset analytics for portfolio management.\n  - name: Trading Solutions\n    description: EMSX and Tradebook for electronic order routing and execution.\n  - name: Risk Solutions\n    description: Credit and market risk analytics across asset classes.\n  - name: Research Solutions\n    description: Bloomberg Intelligence research and analytics.\n- type: UseCases\n  data:\n  - name: Investment Management\n    description: Full-lifecycle investment data and analytics for portfolio managers.\n  - name: Trading and Execution\n    description: Order management and execution across equities, fixed income, FX,\n      and derivatives.\n  - name: Risk and Compliance\n    description: Integrated risk analytics and regulatory compliance solutions.\n\
  \  - name: Corporate Finance\n    description: M&A, capital markets, and corporate treasury data and analytics.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-product-suite/refs/heads/main/apis.yml
tags:
- Product Suite
- Terminal
- Data
- Analytics
- Trading
- Financial Technology
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-product-suite/refs/heads/main/apis.yml
use_cases:
- description: Full-lifecycle investment data and analytics for portfolio managers.
  name: Investment Management
- description: Order management and execution across equities, fixed income, FX, and derivatives.
  name: Trading and Execution
- description: Integrated risk analytics and regulatory compliance solutions.
  name: Risk and Compliance
- description: M&A, capital markets, and corporate treasury data and analytics.
  name: Corporate Finance
---
