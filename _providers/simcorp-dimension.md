---
api_count: 6
apis:
- description: RESTful API for accessing portfolio data, positions, transactions, and market data from SimCorp Dimension.
  name: SimCorp Dimension Data API
  slug: ''
- description: API for integrating third-party systems with SimCorp Dimension for data synchronization and workflow automation.
  name: SimCorp Dimension Integration API
  slug: ''
- description: API for accessing analytics, performance metrics, risk calculations, and reporting data.
  name: SimCorp Dimension Analytics API
  slug: ''
- description: Web API providing HTTP-based interfaces for accessing and manipulating SimCorp Dimension data in real-time, supporting stateless RESTful operations across the investment management lifecycle.
  name: SimCorp Dimension Web API
  slug: ''
- description: API for distributing and sharing investment data across integrated systems, supporting event streaming channels and direct data access from SimCorp Dimension.
  name: SimCorp Dimension Data Distribution API
  slug: ''
- description: Real-time streaming API for delivering live investment data, market updates, and event-driven notifications from SimCorp Dimension.
  name: SimCorp Dimension Streaming API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://www.simcorp.com/solutions/simcorp-one
- title: ''
  type: Documentation
  url: https://thesim.dev/
- title: ''
  type: Portfolio Management
  url: https://www.simcorp.com/solutions/simcorp-one/portfolio-management
- title: ''
  type: Trading and Compliance
  url: https://www.simcorp.com/solutions/simcorp-one/trading-and-compliance
- title: ''
  type: Risk and Performance
  url: https://www.simcorp.com/solutions/simcorp-one/risk-and-performance
- title: ''
  type: Operations
  url: https://www.simcorp.com/solutions/simcorp-one/operations
- title: ''
  type: Accounting
  url: https://www.simcorp.com/solutions/simcorp-one/accounting
- title: ''
  type: Data Management
  url: https://www.simcorp.com/solutions/simcorp-one/data-management
- title: ''
  type: Reporting
  url: https://www.simcorp.com/solutions/simcorp-one/reporting
- title: ''
  type: Client Communications
  url: https://www.simcorp.com/solutions/simcorp-one/Client-Communications-and-Regulatory-Reporting
- title: ''
  type: Partners
  url: https://www.simcorp.com/partners/open-platform-partners
- title: ''
  type: Resources
  url: https://en.wikipedia.org/wiki/SimCorp
- title: ''
  type: Resources
  url: https://www.simcorp.com/about-us/news/2024/simcorp-introduces-new-flagship-platform-simcorp-one
- title: ''
  type: Support
  url: https://www.dimensionalcommunity.com/insights
- title: ''
  type: JSONLD
  url: json-ld/simcorp-dimension-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/simcorp-dimension-portfolio-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/simcorp-dimension-instrument-schema.json
created: '2024'
description: Investment management software solution providing APIs for portfolio management, accounting, risk management, and investment operations. SimCorp Dimension is part of the SimCorp One integrated platform, offering Web APIs, Data Distribution APIs, and Streaming APIs through the SimCorp Integration Model (SIM) for front-to-back office investment management.
features:
- Front-to-back investment management
- Real-time portfolio data and analytics
- Event-driven streaming data distribution
- Risk and performance measurement
- Accounting and operations management
- Trading and compliance monitoring
- Client communications and regulatory reporting
- Open platform integration model
image: https://www.simcorp.com/logo.png
integrations:
- Bloomberg
- Reuters/Refinitiv
- SWIFT
- Clearstream
- Euroclear
- Microsoft Excel
- Tableau
- Power BI
jsonld:
- class_count: 0
  name: Simcorp Dimension Context
  property_count: 8
  slug: simcorp-dimension-context
layout: provider
modified: '2026-04-18'
name: SimCorp Dimension
skills: []
slug: simcorp-dimension
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SimCorp Dimension\ndescription: Investment management software solution providing APIs for portfolio management, accounting, risk management, and investment operations. SimCorp Dimension is part of the SimCorp One integrated platform, offering Web APIs, Data Distribution APIs, and Streaming APIs through the SimCorp Integration Model (SIM) for front-to-back office investment management.\nimage: https://www.simcorp.com/logo.png\nurl: https://www.simcorp.com\ncreated: '2024'\nmodified: '2026-04-18'\napis:\n  - name: SimCorp Dimension Data API\n    description: >-\n      RESTful API for accessing portfolio data, positions, transactions, and market\n      data from SimCorp Dimension.\n    image: https://www.simcorp.com/api-logo.png\n    humanURL: https://www.simcorp.com/products/simcorp-dimension\n    baseURL: https://api.simcorp.com/dimension/v1\n    tags:\n      - Asset Management\n      - Financial Services\n      - Investment Data\n      - Portfolio Management\n    properties:\n\
  \      - type: Documentation\n        url: https://developer.simcorp.com/dimension/data-api\n      - type: OpenAPI\n        url: https://api.simcorp.com/dimension/v1/openapi.json\n      - type: Authentication\n        url: https://developer.simcorp.com/dimension/authentication\n    contact:\n      - FN: SimCorp API Support\n        email: apisupport@simcorp.com\n        url: https://www.simcorp.com/support\n  - name: SimCorp Dimension Integration API\n    description: >-\n      API for integrating third-party systems with SimCorp Dimension for data synchronization\n      and workflow automation.\n    image: https://www.simcorp.com/api-logo.png\n    humanURL: https://www.simcorp.com/products/simcorp-dimension/integration\n    baseURL: https://api.simcorp.com/dimension/integration/v1\n    tags:\n      - Data Synchronization\n      - Financial Services\n      - Integration\n      - Workflow Automation\n    properties:\n      - type: Documentation\n        url: https://developer.simcorp.com/dimension/integration-api\n\
  \      - type: OpenAPI\n        url: https://api.simcorp.com/dimension/integration/v1/openapi.json\n      - type: Webhooks\n        url: https://developer.simcorp.com/dimension/webhooks\n    contact:\n      - FN: SimCorp API Support\n        email: apisupport@simcorp.com\n        url: https://www.simcorp.com/support\n  - name: SimCorp Dimension Analytics API\n    description: >-\n      API for accessing analytics, performance metrics, risk calculations, and reporting\n      data.\n    image: https://www.simcorp.com/api-logo.png\n    humanURL: https://www.simcorp.com/products/simcorp-dimension/analytics\n    baseURL: https://api.simcorp.com/dimension/analytics/v1\n    tags:\n      - Analytics\n      - Performance\n      - Reporting\n      - Risk Management\n    properties:\n      - type: Documentation\n        url: https://developer.simcorp.com/dimension/analytics-api\n      - type: OpenAPI\n        url: https://api.simcorp.com/dimension/analytics/v1/openapi.json\n      - type: RateLimits\n\
  \        url: https://developer.simcorp.com/dimension/rate-limits\n    contact:\n      - FN: SimCorp API Support\n        email: apisupport@simcorp.com\n        url: https://www.simcorp.com/support\n  - name: SimCorp Dimension Web API\n    description: Web API providing HTTP-based interfaces for accessing and manipulating SimCorp Dimension data in real-time, supporting stateless RESTful operations across the investment management lifecycle.\n    image: https://www.simcorp.com/api-logo.png\n    humanURL: https://www.simcorp.com/solutions/simcorp-one\n    baseURL: https://api.simcorp.com/dimension/web/v1\n    tags:\n      - Investment Management\n      - Real-Time Data\n      - REST\n      - Web API\n    properties:\n      - type: Documentation\n        url: https://thesim.dev/\n    contact:\n      - FN: SimCorp API Support\n        email: apisupport@simcorp.com\n        url: https://www.simcorp.com/support\n  - name: SimCorp Dimension Data Distribution API\n    description: API for distributing\
  \ and sharing investment data across integrated systems, supporting event streaming channels and direct data access from SimCorp Dimension.\n    image: https://www.simcorp.com/api-logo.png\n    humanURL: https://www.simcorp.com/solutions/simcorp-one/data-management\n    baseURL: https://api.simcorp.com/dimension/datadistribution/v1\n    tags:\n      - Data Distribution\n      - Data Sharing\n      - Event Streaming\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://thesim.dev/\n    contact:\n      - FN: SimCorp API Support\n        email: apisupport@simcorp.com\n        url: https://www.simcorp.com/support\n  - name: SimCorp Dimension Streaming API\n    description: Real-time streaming API for delivering live investment data, market updates, and event-driven notifications from SimCorp Dimension.\n    image: https://www.simcorp.com/api-logo.png\n    humanURL: https://www.simcorp.com/solutions/simcorp-one/data-management\n    baseURL: https://api.simcorp.com/dimension/streaming/v1\n\
  \    tags:\n      - Event-Driven\n      - Market Data\n      - Real-Time Data\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://thesim.dev/\n    contact:\n      - FN: SimCorp API Support\n        email: apisupport@simcorp.com\n        url: https://www.simcorp.com/support\ncommon:\n  - type: Portal\n    url: https://www.simcorp.com/solutions/simcorp-one\n  - type: Documentation\n    url: https://thesim.dev/\n  - type: Portfolio Management\n    url: https://www.simcorp.com/solutions/simcorp-one/portfolio-management\n  - type: Trading and Compliance\n    url: https://www.simcorp.com/solutions/simcorp-one/trading-and-compliance\n  - type: Risk and Performance\n    url: https://www.simcorp.com/solutions/simcorp-one/risk-and-performance\n  - type: Operations\n    url: https://www.simcorp.com/solutions/simcorp-one/operations\n  - type: Accounting\n    url: https://www.simcorp.com/solutions/simcorp-one/accounting\n  - type: Data Management\n    url: https://www.simcorp.com/solutions/simcorp-one/data-management\n\
  \  - type: Reporting\n    url: https://www.simcorp.com/solutions/simcorp-one/reporting\n  - type: Client Communications\n    url: https://www.simcorp.com/solutions/simcorp-one/Client-Communications-and-Regulatory-Reporting\n  - type: Partners\n    url: https://www.simcorp.com/partners/open-platform-partners\n  - type: Resources\n    url: https://en.wikipedia.org/wiki/SimCorp\n  - type: Resources\n    url: https://www.simcorp.com/about-us/news/2024/simcorp-introduces-new-flagship-platform-simcorp-one\n  - type: Support\n    url: https://www.dimensionalcommunity.com/insights\n  - type: JSONLD\n    url: json-ld/simcorp-dimension-context.jsonld\n  - type: JSONSchema\n    url: json-schema/simcorp-dimension-portfolio-schema.json\n  - type: JSONSchema\n    url: json-schema/simcorp-dimension-instrument-schema.json\n  - type: Features\n    data:\n      - Front-to-back investment management\n      - Real-time portfolio data and analytics\n      - Event-driven streaming data distribution\n      -\
  \ Risk and performance measurement\n      - Accounting and operations management\n      - Trading and compliance monitoring\n      - Client communications and regulatory reporting\n      - Open platform integration model\n  - type: UseCases\n    data:\n      - Portfolio management and analysis\n      - Investment data integration and distribution\n      - Risk and performance reporting\n      - Regulatory compliance and reporting\n      - Real-time market data streaming\n      - Multi-asset investment operations\n  - type: Integrations\n    data:\n      - Bloomberg\n      - Reuters/Refinitiv\n      - SWIFT\n      - Clearstream\n      - Euroclear\n      - Microsoft Excel\n      - Tableau\n      - Power BI\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Accounting\n  - Asset Management\n  - Compliance\n  - Data Distribution\n  - Enterprise Software\n  - Financial Data\n  - Financial Technology\n  - Investment Management\n\
  \  - Portfolio Management\n  - Risk Management\n  - SimCorp One\n  - Streaming\n  - Trading\ninclude:\n  - name: Developer Portal\n    url: https://developer.simcorp.com\n  - name: API Status\n    url: https://status.simcorp.com\n  - name: Release Notes\n    url: https://developer.simcorp.com/changelog\n  - name: SimCorp Data Model Portal\n    url: https://thesim.dev/\n  - name: Dimensional Community\n    url: https://www.dimensionalcommunity.com/insights\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/simcorp-dimension/refs/heads/main/apis.yml
tags:
- Accounting
- Asset Management
- Compliance
- Data Distribution
- Enterprise Software
- Financial Data
- Financial Technology
- Investment Management
- Portfolio Management
- Risk Management
- SimCorp One
- Streaming
- Trading
url: https://www.simcorp.com
use_cases:
- Portfolio management and analysis
- Investment data integration and distribution
- Risk and performance reporting
- Regulatory compliance and reporting
- Real-time market data streaming
- Multi-asset investment operations
---
