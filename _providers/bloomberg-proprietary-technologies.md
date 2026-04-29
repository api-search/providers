---
api_count: 3
apis:
- description: Bloomberg's proprietary socket-based API protocol for accessing Bloomberg data, providing a high-performance connectivity layer between client applications and Bloomberg's data infrastructure.
  name: Bloomberg Open API (BLPAPI)
  slug: blpapi
- description: The Financial Instrument Global Identifier (FIGI) is Bloomberg's open standard for identifying financial instruments. The OpenFIGI API allows free mapping of tickers, ISINs, CUSIPs, and other identifi
  name: Bloomberg FIGI API
  slug: figi-api
- description: Bloomberg's proprietary query language enabling flexible data requests with filtering, aggregation, and calculated field capabilities across Bloomberg's data universe.
  name: Bloomberg Query Language (BQL)
  slug: bql
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
description: Bloomberg Proprietary Technologies encompasses the internally developed technology innovations that power Bloomberg's products and services. This includes Bloomberg's proprietary data network, the BLPAPI connectivity protocol, BQL query language, B-PIPE data distribution technology, FIGI (Financial Instrument Global Identifier) system, and the Bloomberg Generative AI capabilities integrated into its financial data platform.
features:
- description: Proprietary socket protocol for high-performance Bloomberg data connectivity.
  name: BLPAPI Protocol
- description: Proprietary query language for flexible financial data requests.
  name: Bloomberg Query Language
- description: Open standard financial instrument identifier with free API access.
  name: FIGI Identifier System
- description: Proprietary managed data distribution technology for enterprise.
  name: B-PIPE Distribution
- description: Machine learning and AI capabilities integrated into Bloomberg data products.
  name: Bloomberg AI/ML
- description: Cloud-native infrastructure enabling Bloomberg data access from major cloud platforms.
  name: Bloomberg Cloud Infrastructure
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Proprietary Technologies
skills: []
slug: bloomberg-proprietary-technologies
solutions: []
source_filename: apis.yml
source_yaml: "aid: bloomberg-proprietary-technologies\nname: Bloomberg Proprietary Technologies\ndescription: Bloomberg Proprietary Technologies encompasses the internally developed\n  technology innovations that power Bloomberg's products and services. This includes\n  Bloomberg's proprietary data network, the BLPAPI connectivity protocol, BQL query\n  language, B-PIPE data distribution technology, FIGI (Financial Instrument Global\n  Identifier) system, and the Bloomberg Generative AI capabilities integrated into\n  its financial data platform.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-proprietary-technologies/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Proprietary Technology\n- BLPAPI\n- BQL\n- FIGI\n- B-PIPE\n- Financial Technology\n- Bloomberg\napis:\n- aid: bloomberg-proprietary-technologies:blpapi\n\
  \  name: Bloomberg Open API (BLPAPI)\n  description: Bloomberg's proprietary socket-based API protocol for accessing Bloomberg\n    data, providing a high-performance connectivity layer between client applications\n    and Bloomberg's data infrastructure.\n  humanURL: https://bloomberg.github.io/blpapi-docs/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - BLPAPI\n  - Protocol\n  - Proprietary API\n  properties:\n  - type: Documentation\n    url: https://bloomberg.github.io/blpapi-docs/\n- aid: bloomberg-proprietary-technologies:figi-api\n  name: Bloomberg FIGI API\n  description: The Financial Instrument Global Identifier (FIGI) is Bloomberg's open\n    standard for identifying financial instruments. The OpenFIGI API allows free\n    mapping of tickers, ISINs, CUSIPs, and other identifiers to FIGI codes.\n  humanURL: https://www.openfigi.com/api\n  baseURL: https://api.openfigi.com\n  tags:\n  - FIGI\n  - Financial Identifiers\n  - OpenFIGI\n  - Mapping\n  properties:\n  - type: Documentation\n\
  \    url: https://www.openfigi.com/api\n  - type: OpenAPI\n    url: https://api.openfigi.com/schema/openapi.json\n- aid: bloomberg-proprietary-technologies:bql\n  name: Bloomberg Query Language (BQL)\n  description: Bloomberg's proprietary query language enabling flexible data requests\n    with filtering, aggregation, and calculated field capabilities across Bloomberg's\n    data universe.\n  humanURL: https://www.bloomberg.com/professional/support/api-library/\n  baseURL: bql://bloomberg.com\n  tags:\n  - BQL\n  - Query Language\n  - Proprietary\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/support/api-library/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://developer.bloomberg.com/\n- type: GitHubOrganization\n  url: https://github.com/bloomberg\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n\
  - type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n  data:\n  - name: BLPAPI Protocol\n    description: Proprietary socket protocol for high-performance Bloomberg data\n      connectivity.\n  - name: Bloomberg Query Language\n    description: Proprietary query language for flexible financial data requests.\n  - name: FIGI Identifier System\n    description: Open standard financial instrument identifier with free API access.\n  - name: B-PIPE Distribution\n    description: Proprietary managed data distribution technology for enterprise.\n  - name: Bloomberg AI/ML\n    description: Machine learning and AI capabilities integrated into Bloomberg data\n      products.\n  - name: Bloomberg Cloud Infrastructure\n    description: Cloud-native infrastructure enabling Bloomberg data access from\n      major cloud platforms.\n- type: UseCases\n  data:\n  - name: Instrument Identification\n    description: Map and resolve financial instrument identifiers using\
  \ FIGI.\n  - name: Custom Data Queries\n    description: Build custom data requests using Bloomberg Query Language.\n  - name: System Integration\n    description: Connect enterprise systems to Bloomberg data via BLPAPI.\n    url: https://bloomberg.github.io/blpapi-docs/\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-proprietary-technologies/refs/heads/main/apis.yml
tags:
- Proprietary Technology
- BLPAPI
- BQL
- FIGI
- B-PIPE
- Financial Technology
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-proprietary-technologies/refs/heads/main/apis.yml
use_cases:
- description: Map and resolve financial instrument identifiers using FIGI.
  name: Instrument Identification
- description: Build custom data requests using Bloomberg Query Language.
  name: Custom Data Queries
- description: Connect enterprise systems to Bloomberg data via BLPAPI.
  name: System Integration
  url: https://bloomberg.github.io/blpapi-docs/
---
