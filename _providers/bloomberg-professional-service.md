---
api_count: 9
apis:
- description: Provides programmatic access to Bloomberg's comprehensive financial data including pricing, reference data, fundamentals, and historical information. Content can be accessed via a REST API, SFTP, or n
  name: Bloomberg Data License API
  slug: ''
- description: Desktop API enabling custom applications to access Bloomberg data and functionality programmatically through the Bloomberg Terminal. Supports development in C++, Java, C# (.NET), Python, and other lan
  name: Bloomberg API (BLPAPI)
  slug: ''
- description: Server-side API delivering the same real-time market data, historical data, premium reference data, and calculation tools available with the Bloomberg Terminal for seamless use in proprietary and Bloo
  name: Bloomberg SAPI (Server API)
  slug: ''
- description: Real-time streaming market data feed providing access to 35 million instruments across all asset classes, aggregated from 330+ exchanges and 5,000+ contributors. Supports Bloomberg composite tickers a
  name: Bloomberg B-PIPE
  slug: ''
- description: 'Provides programmatic access to Data License content with a combination of request-response and subscription-based services. Available content includes reference, pricing, regulatory, and alternative '
  name: Bloomberg Hypermedia API (HAPI)
  slug: ''
- description: HTTP wrapper making the Bloomberg Open API available via HTTP and WebSockets, allowing clients to access reference and historical request/response data as well as make subscriptions for live data with
  name: Bloomberg HTTP API
  slug: ''
- description: Enables synchronization of actions across third-party applications and the Bloomberg Terminal. Allows developers to initiate Bloomberg functions within external applications and synchronize with Bloom
  name: Bloomberg Terminal Connect API
  slug: ''
- description: Platform for building, connecting, and scaling third-party applications within the Bloomberg Terminal ecosystem. Developers can create extensions published and distributed to Bloomberg Terminal subscr
  name: Bloomberg App Portal
  slug: ''
- description: Fully managed, public cloud-based data management solution that brings Bloomberg data together in a centralized platform for easier and more consistent delivery to downstream systems.
  name: Bloomberg Data License Plus (DL+)
  slug: ''
common:
- title: ''
  type: Portal
  url: https://www.bloomberg.com/professional/
- title: ''
  type: DeveloperPortal
  url: https://developer.bloomberg.com/
- title: ''
  type: DeveloperPortal
  url: https://www.bloomberg.com/professional/solutions/asset-management/developer/
- title: ''
  type: Documentation
  url: https://bloomberg.github.io/blpapi-docs/
- title: ''
  type: Documentation
  url: https://www.bloomberg.com/professional/support/api-library/
- title: ''
  type: Support
  url: https://www.bloomberg.com/professional/support/
- title: ''
  type: StatusPage
  url: https://www.bloomberg.com/professional/support/software-updates/
- title: ''
  type: GitHubOrganization
  url: https://github.com/bloomberg
- title: ''
  type: Resources
  url: https://bloomberg.github.io/
- title: ''
  type: Resources
  url: https://www.bloomberg.com/professional/products/data/data-connectivity/
- title: ''
  type: TermsOfService
  url: https://www.bloomberg.com/notices/tos/
- title: ''
  type: PrivacyPolicy
  url: https://www.bloomberg.com/notices/
- title: ''
  type: Contact
  url: https://www.bloomberg.com/professional/request-demo/
created: 2024-01-20 00:00:00+00:00
description: Bloomberg Professional Service is a comprehensive financial data, news, and analytics platform serving investment professionals worldwide. It provides real-time and historical market data, trading capabilities, news, research, and analytical tools for financial markets.
features:
- Real-time and historical market data access
- Desktop API for Bloomberg Terminal integration
- Server-side API for enterprise applications
- B-PIPE low-latency streaming data feed
- Hypermedia API for Data License content
- HTTP/WebSocket wrapper for BLPAPI
- Terminal Connect for third-party app synchronization
- App Portal for Terminal ecosystem extensions
image: https://www.bloomberg.com/company/press/wp-content/uploads/sites/40/2018/02/Bloomberg_Logo_2018.png
integrations:
- Bloomberg Terminal
- AWS
- Microsoft Azure
- Python
- Java
- C++ / .NET
- Node.js
- Haskell
layout: provider
modified: '2026-04-18'
name: Bloomberg Professional Service
skills: []
slug: bloomberg-professional-service
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Bloomberg Professional Service\ndescription: Bloomberg Professional Service is a comprehensive financial data, news, and analytics platform serving investment professionals worldwide. It provides real-time and historical market data, trading capabilities, news, research, and analytical tools for financial markets.\nimage: https://www.bloomberg.com/company/press/wp-content/uploads/sites/40/2018/02/Bloomberg_Logo_2018.png\nurl: https://www.bloomberg.com/professional/\ncreated: 2024-01-20 00:00:00+00:00\nmodified: '2026-04-18'\napis:\n  - name: Bloomberg Data License API\n    description: Provides programmatic access to Bloomberg's comprehensive financial data including pricing, reference data, fundamentals, and historical information. Content can be accessed via a REST API, SFTP, or natively in all major cloud providers, with bulk datasets available daily spanning 20+ years of history.\n    baseURL: https://www.bloomberg.com/professional/product/data-license/\n    humanURL:\
  \ https://www.bloomberg.com/professional/products/data/data-management/data-license/\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/support/data-license/\n      - type: Pricing\n        url: https://www.bloomberg.com/professional/product/data-license/#pricing\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/products/data/data-management/data-license/\n    tags:\n      - Cloud\n      - ESG\n      - Financial Data\n      - Fundamentals\n      - Historical Data\n      - Market Data\n      - Reference Data\n  - name: Bloomberg API (BLPAPI)\n    description: Desktop API enabling custom applications to access Bloomberg data and functionality programmatically through the Bloomberg Terminal. Supports development in C++, Java, C# (.NET), Python, and other languages, providing 24x7 programmatic access to streaming real-time and delayed data, reference data, historical data, and intraday data.\n    baseURL: https://www.bloomberg.com/professional/support/api-library/\n\
  \    humanURL: https://www.bloomberg.com/professional/support/api-library/\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/support/api-library/\n      - type: Documentation\n        url: https://bloomberg.github.io/blpapi-docs/\n      - type: SDK\n        url: https://www.bloomberg.com/professional/support/software-updates/\n      - type: CodeExamples\n        url: https://www.bloomberg.com/professional/support/api-library/\n      - type: SDK\n        url: https://github.com/bloomberg/blpapi-node\n      - type: SDK\n        url: https://github.com/bloomberg/blpapi-hs\n    tags:\n      - Desktop API\n      - Real-Time Data\n      - SDK\n      - Terminal Integration\n      - Trading\n  - name: Bloomberg SAPI (Server API)\n    description: Server-side API delivering the same real-time market data, historical data, premium reference data, and calculation tools available with the Bloomberg Terminal for seamless use in proprietary and Bloomberg-approved\
  \ client server applications. Supports C++, .NET, VBA via COM, Java, and Python, and leverages existing Bloomberg Terminal exchange entitlements.\n    baseURL: https://www.bloomberg.com/professional/products/data/data-connectivity/server-api/\n    humanURL: https://www.bloomberg.com/professional/products/data/data-connectivity/server-api/\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/support/api-library/\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/products/data/data-connectivity/server-api/\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/insights/data/bloombergs-server-api-what-you-need-to-know/\n      - type: Support\n        url: https://www.bloomberg.com/professional/support/\n    tags:\n      - Cloud\n      - Enterprise\n      - Integration\n      - Market Data\n      - Server API\n  - name: Bloomberg B-PIPE\n    description: Real-time streaming market data feed\
  \ providing access to 35 million instruments across all asset classes, aggregated from 330+ exchanges and 5,000+ contributors. Supports Bloomberg composite tickers and market indices with low latency delivery for algorithmic trading, quantitative analysis, and non-display applications. Available via cloud connectivity on AWS and Azure.\n    baseURL: https://www.bloomberg.com/professional/product/b-pipe/\n    humanURL: https://www.bloomberg.com/professional/product/b-pipe/\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/support/api-library/\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/product/b-pipe/\n      - type: Marketplace\n        url: https://aws.amazon.com/financial-services/partner-solutions/bloomberg-b-pipe/\n    tags:\n      - Algorithmic Trading\n      - Cloud\n      - Low Latency\n      - Market Data Feed\n      - Real-Time\n      - Streaming\n  - name: Bloomberg Hypermedia API (HAPI)\n \
  \   description: Provides programmatic access to Data License content with a combination of request-response and subscription-based services. Available content includes reference, pricing, regulatory, and alternative data. Uses JWT authentication and supports both bulk subscription-based datasets and per-security datasets.\n    baseURL: https://www.bloomberg.com/professional/products/data/data-management/data-license/\n    humanURL: https://www.bloomberg.com/professional/products/data/data-management/data-license/\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/support/api-library/\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/products/data/data-management/data-license/\n    tags:\n      - Alternative Data\n      - Data License\n      - Pricing Data\n      - Reference Data\n      - Regulatory Data\n      - REST API\n  - name: Bloomberg HTTP API\n    description: HTTP wrapper making the Bloomberg Open\
  \ API available via HTTP and WebSockets, allowing clients to access reference and historical request/response data as well as make subscriptions for live data without native BLPAPI SDK integration.\n    baseURL: https://github.com/bloomberg/blpapi-http\n    humanURL: https://github.com/bloomberg/blpapi-http\n    properties:\n      - type: Documentation\n        url: https://github.com/bloomberg/blpapi-http/blob/develop/doc/http-api-guide.md\n      - type: GitHubRepository\n        url: https://github.com/bloomberg/blpapi-http\n    tags:\n      - Historical Data\n      - HTTP\n      - Open Source\n      - Real-Time Data\n      - REST API\n      - WebSockets\n  - name: Bloomberg Terminal Connect API\n    description: Enables synchronization of actions across third-party applications and the Bloomberg Terminal. Allows developers to initiate Bloomberg functions within external applications and synchronize with Bloomberg Launchpad for seamless Terminal integration workflows.\n    baseURL: https://www.bloomberg.com/professional/support/api-library/\n\
  \    humanURL: https://www.bloomberg.com/professional/support/api-library/\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/support/api-library/\n      - type: DeveloperPortal\n        url: https://developer.bloomberg.com/\n    tags:\n      - Desktop\n      - Launchpad\n      - Synchronization\n      - Terminal Integration\n  - name: Bloomberg App Portal\n    description: Platform for building, connecting, and scaling third-party applications within the Bloomberg Terminal ecosystem. Developers can create extensions published and distributed to Bloomberg Terminal subscribers across categories including data analysis, portfolio management, risk analysis, and data visualization.\n    baseURL: https://www.bloomberg.com/professional/solutions/asset-management/developer/\n    humanURL: https://www.bloomberg.com/professional/solutions/asset-management/developer/\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/solutions/asset-management/developer/\n\
  \      - type: DeveloperPortal\n        url: https://developer.bloomberg.com/\n    tags:\n      - App Marketplace\n      - Developer Platform\n      - Terminal Extensions\n      - Third Party Apps\n  - name: Bloomberg Data License Plus (DL+)\n    description: Fully managed, public cloud-based data management solution that brings Bloomberg data together in a centralized platform for easier and more consistent delivery to downstream systems.\n    baseURL: https://www.bloomberg.com/professional/products/data/data-management/dms/\n    humanURL: https://www.bloomberg.com/professional/products/data/data-management/dms/\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/products/data/data-management/dms/\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/support/api-library/\n    tags:\n      - Cloud\n      - Data License\n      - Data Management\n      - Enterprise\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n\
  \    url: https://apievangelist.com/\ncommon:\n  - type: Portal\n    url: https://www.bloomberg.com/professional/\n  - type: DeveloperPortal\n    url: https://developer.bloomberg.com/\n  - type: DeveloperPortal\n    url: https://www.bloomberg.com/professional/solutions/asset-management/developer/\n  - type: Documentation\n    url: https://bloomberg.github.io/blpapi-docs/\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/support/api-library/\n  - type: Support\n    url: https://www.bloomberg.com/professional/support/\n  - type: StatusPage\n    url: https://www.bloomberg.com/professional/support/software-updates/\n  - type: GitHubOrganization\n    url: https://github.com/bloomberg\n  - type: Resources\n    url: https://bloomberg.github.io/\n  - type: Resources\n    url: https://www.bloomberg.com/professional/products/data/data-connectivity/\n  - type: TermsOfService\n    url: https://www.bloomberg.com/notices/tos/\n  - type: PrivacyPolicy\n    url: https://www.bloomberg.com/notices/\n\
  \  - type: Contact\n    url: https://www.bloomberg.com/professional/request-demo/\n  - type: Features\n    data:\n      - Real-time and historical market data access\n      - Desktop API for Bloomberg Terminal integration\n      - Server-side API for enterprise applications\n      - B-PIPE low-latency streaming data feed\n      - Hypermedia API for Data License content\n      - HTTP/WebSocket wrapper for BLPAPI\n      - Terminal Connect for third-party app synchronization\n      - App Portal for Terminal ecosystem extensions\n  - type: UseCases\n    data:\n      - Algorithmic and quantitative trading\n      - Portfolio management and risk analysis\n      - Financial data integration and reporting\n      - Real-time market data distribution\n      - Custom Terminal application development\n      - Enterprise data management and analytics\n  - type: Integrations\n    data:\n      - Bloomberg Terminal\n      - AWS\n      - Microsoft Azure\n      - Python\n      - Java\n      - C++ / .NET\n\
  \      - Node.js\n      - Haskell\ntags:\n  - Analytics\n  - Cloud\n  - Data Management\n  - Enterprise\n  - Financial Services\n  - Market Data\n  - Open Source\n  - Real-Time Data\n  - Trading\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-professional-service/refs/heads/main/apis.yml
tags:
- Analytics
- Cloud
- Data Management
- Enterprise
- Financial Services
- Market Data
- Open Source
- Real-Time Data
- Trading
url: https://www.bloomberg.com/professional/
use_cases:
- Algorithmic and quantitative trading
- Portfolio management and risk analysis
- Financial data integration and reporting
- Real-time market data distribution
- Custom Terminal application development
- Enterprise data management and analytics
---
