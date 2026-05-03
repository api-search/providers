---
api_count: 27
api_specs:
- filename: refinitiv-data-platform-openapi.yml
  format: yaml
  label: Refinitiv Data Platform (RDP) API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/openapi/refinitiv-data-platform-openapi.yml
- filename: refinitiv-real-time-websocket-asyncapi.yml
  format: yaml
  label: Refinitiv Real-Time WebSocket API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/asyncapi/refinitiv-real-time-websocket-asyncapi.yml
- filename: refinitiv-datascope-select-openapi.yml
  format: yaml
  label: LSEG DataScope Select - REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/openapi/refinitiv-datascope-select-openapi.yml
- filename: refinitiv-world-check-one-openapi.yml
  format: yaml
  label: World-Check One API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/openapi/refinitiv-world-check-one-openapi.yml
- filename: refinitiv-qual-id-openapi.yml
  format: yaml
  label: Qual-ID API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/openapi/refinitiv-qual-id-openapi.yml
- filename: refinitiv-permid-entity-search-openapi.yml
  format: yaml
  label: PermID Entity Search API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/openapi/refinitiv-permid-entity-search-openapi.yml
apis:
- description: Cloud-enabled RESTful API providing access to streaming and non-streaming financial data, news, research, and analytics. It serves as the primary programmatic interface to the breadth of Refinitiv con
  name: Refinitiv Data Platform (RDP) API
  slug: ''
- description: Python library providing uniform access to the breadth and depth of financial data and services available on the LSEG Data Platform. It offers ease-of-use interfaces for streaming and non-streaming da
  name: Refinitiv Data Library for Python
  slug: ''
- description: .NET library providing uniform access to financial data and services available on the LSEG Data Platform. It supports streaming and non-streaming data retrieval and integrates with LSEG Workspace, the
  name: Refinitiv Data Library for .NET
  slug: ''
- description: Suite of ease-of-use libraries and interfaces for Python, TypeScript and JavaScript providing access to streaming and non-streaming data services on the LSEG Data Platform. These libraries have been s
  name: Refinitiv Data Platform Libraries
  slug: ''
- description: Python library providing access to financial data, news, and symbology from within the Refinitiv Eikon or LSEG Workspace desktop application. It enables Eikon end users to access data programmatically
  name: Eikon Data API
  slug: ''
- description: Low-latency streaming API for real-time market data using WebSocket connections. It supports the Open Message Model (OMM) and allows applications to connect directly to Refinitiv Real-Time distributio
  name: Refinitiv Real-Time WebSocket API
  slug: ''
- description: Open source Java SDK for the Refinitiv Real-Time platform, containing the Enterprise Message API (EMA) for ease-of-use rapid development and the Enterprise Transport API (ETA) for low-level, high-perf
  name: Refinitiv Real-Time SDK - Java
  slug: ''
- description: Open source C/C++ SDK for the Refinitiv Real-Time platform, providing the Enterprise Message API (EMA) and Enterprise Transport API (ETA) for building high-performance, low-latency applications that c
  name: Refinitiv Real-Time SDK - C/C++
  slug: ''
- description: Access to comprehensive news content from Refinitiv including real-time and historical news articles, Machine Readable News (MRN), and news analytics delivered through the Refinitiv Data Platform.
  name: Refinitiv News API
  slug: ''
- description: 'Access to environmental, social, and governance (ESG) data, scores, and analytics for sustainable investing. The API provides ESG scores, carbon emissions data, green revenue metrics, and controversy '
  name: Refinitiv ESG API
  slug: ''
- description: Internet-hosted REST API for programmatic access to global pricing, corporate actions, reference data, historical data, cross-reference, and entity data. It provides fully automated extraction workflo
  name: LSEG DataScope Select - REST API
  slug: ''
- description: SOAP-based web service API for DataScope Select, providing extraction functionality for global pricing, reference, and historical data. Clients are encouraged to migrate to the REST API for new develo
  name: LSEG DataScope Select - SOAP API
  slug: ''
- description: REST API providing access to historical high-frequency timestamped tick data across all global asset classes dating back to 1996. It supports custom reporting and Venue by Day standard reporting for c
  name: LSEG Tick History REST API
  slug: ''
- description: API providing access to Datastream, the world's leading time series database with histories back to the 1900s and over 48 million individual instruments or indicators. Available via SOAP, REST (JSON/X
  name: Datastream Web Service API
  slug: ''
- description: RESTful API for integrating LSEG World-Check screening capabilities into existing workflows and internal systems. It enables automated customer and third-party screening for onboarding, KYC, and due d
  name: World-Check One API
  slug: ''
- description: RESTful API for automating identity verification and document verification processes. It helps organizations comply with regulations and identify potential financial crime using trusted and vetted dat
  name: Qual-ID API
  slug: ''
- description: REST API enabling clients to place orders for LSEG Due Diligence Reports from within their own internal systems and onboarding platforms. It uses OAuth2 for security and follows the OpenAPI 3 standard
  name: LSEG Due Diligence Portal API
  slug: ''
- description: API for wealth management that provides access to Refinitiv hosted content and capabilities. It integrates into advisor solutions, customer-facing investment portals, and online trading platforms thro
  name: Refinitiv Knowledge Direct API (RKD)
  slug: ''
- description: 'RESTful API enabling search of entities by name, ticker, or RIC to return PermIDs, or use PermIDs to retrieve entity information. PermID is an open and free entity identification scheme that provides '
  name: PermID Entity Search API
  slug: ''
- description: Natural language processing API that identifies and tags entities such as companies, people, deals, geographical locations, industries, and events within unstructured text. It maps recognized entities
  name: Intelligent Tagging RESTful API
  slug: ''
- description: End-to-end financial application development kit that allows developers to design a GUI, power it with market data, and integrate logic into workflows. It enables creation of web-based financial appli
  name: Workspace SDK
  slug: ''
- description: Interoperability API that connects client web applications to LSEG Workspace Web. It allows applications to authenticate, connect to a running Workspace instance in the same browser, and exchange meta
  name: Workspace Web Side by Side API
  slug: ''
- description: FIX protocol-based API for electronic FX trading on LSEG Matching venues, supporting spot and forwards currency trading. It uses FIX 5.0 SP2 with a specific set of FIX messages, tags, and workflows fo
  name: FX Trading - Spot and Forwards Matching API
  slug: ''
- description: FIX protocol-based API for electronic trading of non-deliverable forwards (NDFs) on LSEG Matching venues. It provides connectivity for trading participants to submit and manage NDF orders.
  name: FX Trading - NDF Matching API
  slug: ''
- description: Point-to-point market data service based on FIX SBE technology, allowing trading participants to receive real-time information for each instrument traded on Primary CLOBs for NDF Matching venues.
  name: FX Market Data - NDF Matching API
  slug: ''
- description: Service providing reference data for LSEG FX venues, offering instrument and venue configuration data to support FX trading operations on the replatformed spot and forward Matching venues.
  name: FX Reference Data API
  slug: ''
- description: API providing reporting and analytics for FX trading participants on LSEG venues, enabling access to execution quality metrics and participant insight data.
  name: FX Participant Insight Reporting API
  slug: ''
asyncapis:
- description: Low-latency streaming API for real-time market data using WebSocket connections. It supports the Open Message Model (OMM) and allows applications to connect directly to Refinitiv Real-Time distributio
  name: Refinitiv Real-Time WebSocket API
  slug: refinitiv-real-time-websocket-asyncapi
capabilities:
- description: Unified workflow capability for compliance officers and KYC analysts screening entities and verifying identities using Refinitiv's World-Check risk intelligence database and PermID entity search. Supp
  name: Refinitiv Compliance Screening
  slug: compliance-screening
- description: Unified workflow capability for financial analysts and quants accessing pricing data, ESG scores, news, and instrument search through the Refinitiv Data Platform. Combines historical and real-time pri
  name: Refinitiv Financial Market Data
  slug: financial-market-data
common:
- title: ''
  type: JSON-LD
  url: json-ld/refinitiv-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/refinitiv-instrument-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/refinitiv-esg-score-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/refinitiv-screening-case-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/refinitiv-news-article-schema.json
- title: ''
  type: Portal
  url: https://developers.lseg.com/en
- title: ''
  type: Getting Started
  url: https://developers.lseg.com/en/api-catalog
- title: ''
  type: Documentation
  url: https://developers.lseg.com/en/api-catalog
- title: ''
  type: Support
  url: https://developers.lseg.com/en/support
- title: ''
  type: Blog
  url: https://developers.lseg.com/en/article-catalog
- title: ''
  type: GitHub Organization
  url: https://github.com/LSEG-API-Samples
- title: ''
  type: GitHub Organization
  url: https://github.com/Refinitiv-API-Samples
- title: ''
  type: Terms of Service
  url: https://developers.lseg.com/en/terms-and-conditions
- title: ''
  type: Contact
  url: https://developers.lseg.com/en/contact-us
- title: ''
  type: Privacy Policy
  url: https://www.lseg.com/en/policies/privacy-statement
- title: ''
  type: Community
  url: https://community.developers.refinitiv.com/
- title: ''
  type: Website
  url: https://www.lseg.com/en
- title: ''
  type: Login
  url: https://www.lseg.com/en/product-logins
- title: ''
  type: Developer Tools
  url: https://developers.lseg.com/en/tools-catalog
- title: ''
  type: Medium
  url: https://medium.com/lseg-developer-community
- title: ''
  type: OpenAPI
  url: openapi/refinitiv-data-platform-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/refinitiv-datascope-select-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/refinitiv-permid-entity-search-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/refinitiv-qual-id-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/refinitiv-world-check-one-openapi.yml
- title: ''
  type: AsyncAPI
  url: asyncapi/refinitiv-real-time-websocket-asyncapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/refinitiv-instrument-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/refinitiv-esg-score-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/refinitiv-news-article-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/refinitiv-screening-case-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/refinitiv-data-platform-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/refinitiv-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/refinitiv-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/financial-market-data.yaml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/compliance-screening.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/refinitiv-vocabulary.yml
created: '2024-01-01'
description: Refinitiv, an LSEG (London Stock Exchange Group) business, provides financial market data, infrastructure, and analytics to businesses and financial professionals worldwide.
features: []
image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg
integrations: []
jsonld:
- class_count: 0
  name: Refinitiv Context
  property_count: 7
  slug: refinitiv-context
layout: provider
modified: '2026-03-16'
name: Refinitiv
rules:
- name: Refinitiv API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 4
  slug: refinitiv-rules
skills: []
slug: refinitiv
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: refinitiv\nname: Refinitiv\ndescription: >-\n  Refinitiv, an LSEG (London Stock Exchange Group) business, provides financial\n  market data, infrastructure, and analytics to businesses and financial\n  professionals worldwide.\ntype: Index\nimage: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\nurl: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-03-16'\nspecificationVersion: '0.19'\napis:\n  - name: Refinitiv Data Platform (RDP) API\n    description: >-\n      Cloud-enabled RESTful API providing access to streaming and non-streaming\n      financial data, news, research, and analytics. It serves as the primary\n      programmatic interface to the breadth of Refinitiv content on the LSEG Data\n      Platform.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis\n\
  \    baseURL: https://api.refinitiv.com\n    tags:\n      - Analytics\n      - Financial Data\n      - Market Data\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis/quick-start\n      - type: Tutorials\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis/tutorials\n      - type: Downloads\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis/download\n      - type: API Playground\n        url: https://apidocs.refinitiv.com/Apps/ApiDocs\n      - type: Pricing\n        url: https://www.lseg.com/en/data-analytics/financial-data\n      - type: OpenAPI\n        url: openapi/refinitiv-data-platform-openapi.yml\n\
  \  - name: Refinitiv Data Library for Python\n    description: >-\n      Python library providing uniform access to the breadth and depth of\n      financial data and services available on the LSEG Data Platform. It offers\n      ease-of-use interfaces for streaming and non-streaming data, and can be\n      used from within LSEG Workspace, through the Data Platform, or deployed\n      on-premise.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-library-for-python\n    baseURL: https://api.refinitiv.com\n    tags:\n      - Data Library\n      - Financial Data\n      - Python\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-library-for-python/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-library-for-python/quick-start\n\
  \      - type: Tutorials\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-library-for-python/tutorials\n      - type: GitHub Repository\n        url: https://github.com/LSEG-API-Samples/Example.DataLibrary.Python\n  - name: Refinitiv Data Library for .NET\n    description: >-\n      .NET library providing uniform access to financial data and services\n      available on the LSEG Data Platform. It supports streaming and non-streaming\n      data retrieval and integrates with LSEG Workspace, the Data Platform, and\n      on-premise deployed infrastructure.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-library-for--net\n    baseURL: https://api.refinitiv.com\n    tags:\n      - .NET\n      - Data Library\n      - Financial Data\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-library-for--net/documentation\n\
  \      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-library-for--net/quick-start\n  - name: Refinitiv Data Platform Libraries\n    description: >-\n      Suite of ease-of-use libraries and interfaces for Python, TypeScript and\n      JavaScript providing access to streaming and non-streaming data services on\n      the LSEG Data Platform. These libraries have been superseded by the newer\n      Refinitiv Data Libraries for new development.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-libraries\n    baseURL: https://api.refinitiv.com\n    tags:\n      - Financial Data\n      - JavaScript\n      - Libraries\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-libraries/documentation\n\
  \      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-libraries/quick-start\n      - type: Tutorials\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-libraries/tutorials\n  - name: Eikon Data API\n    description: >-\n      Python library providing access to financial data, news, and symbology from\n      within the Refinitiv Eikon or LSEG Workspace desktop application. It enables\n      Eikon end users to access data programmatically from their desktop session.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/eikon/eikon-data-api\n    baseURL: https://api.refinitiv.com\n    tags:\n      - Desktop\n      - Eikon\n      - Financial Data\n      - Python\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/eikon/eikon-data-api/documentation\n\
  \      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/eikon/eikon-data-api/quick-start\n      - type: Tutorials\n        url: https://developers.lseg.com/en/api-catalog/eikon/eikon-data-api/tutorials\n      - type: Downloads\n        url: https://developers.lseg.com/en/api-catalog/eikon/eikon-data-api/download\n  - name: Refinitiv Real-Time WebSocket API\n    description: >-\n      Low-latency streaming API for real-time market data using WebSocket\n      connections. It supports the Open Message Model (OMM) and allows\n      applications to connect directly to Refinitiv Real-Time distribution\n      systems or the LSEG Data Platform for streaming data.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/refinitiv-real-time-opnsrc/refinitiv-websocket-api\n    baseURL: wss://api.refinitiv.com\n    tags:\n      - Market Data\n      - Real-Time\n      - Streaming\n\
  \      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-real-time-opnsrc/refinitiv-websocket-api/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-real-time-opnsrc/refinitiv-websocket-api/quick-start\n      - type: Tutorials\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-real-time-opnsrc/refinitiv-websocket-api/tutorials\n      - type: Downloads\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-real-time-opnsrc/refinitiv-websocket-api/download\n      - type: AsyncAPI\n        url: asyncapi/refinitiv-real-time-websocket-asyncapi.yml\n  - name: Refinitiv Real-Time SDK - Java\n    description: >-\n      Open source Java SDK for the Refinitiv Real-Time platform, containing the\n      Enterprise Message API (EMA) for ease-of-use rapid development and the\n      Enterprise Transport API (ETA) for low-level, high-performance\
  \ access to\n      real-time streaming market data.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/real-time-opnsrc/rt-sdk-java\n    baseURL: https://api.refinitiv.com\n    tags:\n      - Java\n      - Real-Time\n      - SDK\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/real-time-opnsrc/rt-sdk-java/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/real-time-opnsrc/rt-sdk-java/quick-start\n      - type: Tutorials\n        url: https://developers.lseg.com/en/api-catalog/real-time-opnsrc/rt-sdk-java/tutorials\n      - type: Downloads\n        url: https://developers.lseg.com/en/api-catalog/real-time-opnsrc/rt-sdk-java/download\n      - type: GitHub Repository\n        url: https://github.com/Refinitiv/Real-Time-SDK\n  - name: Refinitiv Real-Time SDK - C/C++\n    description:\
  \ >-\n      Open source C/C++ SDK for the Refinitiv Real-Time platform, providing the\n      Enterprise Message API (EMA) and Enterprise Transport API (ETA) for\n      building high-performance, low-latency applications that consume and\n      contribute real-time market data.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/real-time-opnsrc/rt-sdk-cc\n    baseURL: https://api.refinitiv.com\n    tags:\n      - C++\n      - Real-Time\n      - SDK\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/real-time-opnsrc/rt-sdk-cc/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/real-time-opnsrc/rt-sdk-cc/quick-start\n      - type: GitHub Repository\n        url: https://github.com/Refinitiv/Real-Time-SDK\n  - name: Refinitiv News API\n    description: >-\n      Access to comprehensive\
  \ news content from Refinitiv including real-time and\n      historical news articles, Machine Readable News (MRN), and news analytics\n      delivered through the Refinitiv Data Platform.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis\n    baseURL: https://api.refinitiv.com\n    tags:\n      - Content\n      - Media\n      - News\n      - Research\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis/documentation\n      - type: Tutorials\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis/tutorials\n  - name: Refinitiv ESG API\n    description: >-\n      Access to environmental, social, and governance (ESG) data, scores, and\n      analytics for sustainable investing. The API provides\
  \ ESG scores, carbon\n      emissions data, green revenue metrics, and controversy tracking across\n      thousands of companies.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis\n    baseURL: https://api.refinitiv.com\n    tags:\n      - Analytics\n      - Environmental\n      - ESG\n      - Sustainability\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis/documentation\n      - type: Pricing\n        url: https://www.lseg.com/en/data-analytics/sustainable-finance/esg-scores\n  - name: LSEG DataScope Select - REST API\n    description: >-\n      Internet-hosted REST API for programmatic access to global pricing,\n      corporate actions, reference data, historical data, cross-reference, and\n      entity data. It provides fully automated\
  \ extraction workflows and batch\n      processing capabilities for large-scale data retrieval.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/datascope-select/datascope-select-rest-api\n    baseURL: https://selectapi.datascope.lseg.com/RestApi/v1\n    tags:\n      - Data Extraction\n      - Historical Data\n      - Pricing\n      - Reference Data\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/datascope-select/datascope-select-rest-api/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/datascope-select/datascope-select-rest-api/quick-start\n      - type: Tutorials\n        url: https://developers.lseg.com/en/api-catalog/datascope-select/datascope-select-rest-api/tutorials\n      - type: Downloads\n        url: https://developers.lseg.com/en/api-catalog/datascope-select/datascope-select-rest-api/download\n\
  \      - type: OpenAPI\n        url: openapi/refinitiv-datascope-select-openapi.yml\n  - name: LSEG DataScope Select - SOAP API\n    description: >-\n      SOAP-based web service API for DataScope Select, providing extraction\n      functionality for global pricing, reference, and historical data. Clients\n      are encouraged to migrate to the REST API for new development, as all future\n      functionality will be designed around REST.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/datascope-select/datascope-select-soap-api\n    baseURL: https://selectapi.datascope.lseg.com\n    tags:\n      - Data Extraction\n      - Legacy\n      - Reference Data\n      - SOAP\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/datascope-select/datascope-select-soap-api/documentation\n      - type: Downloads\n        url: https://developers.lseg.com/en/api-catalog/datascope-select/datascope-select-soap-api/download\n\
  \  - name: LSEG Tick History REST API\n    description: >-\n      REST API providing access to historical high-frequency timestamped tick data\n      across all global asset classes dating back to 1996. It supports custom\n      reporting and Venue by Day standard reporting for complete trading data\n      extraction.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/refinitiv-tick-history/refinitiv-tick-history-rth-rest-api\n    baseURL: https://selectapi.datascope.lseg.com/RestApi/v1\n    tags:\n      - High Frequency\n      - Historical Data\n      - Tick Data\n      - Trading\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-tick-history/refinitiv-tick-history-rth-rest-api/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-tick-history/refinitiv-tick-history-rth-rest-api/quick-start\n\
  \      - type: Tutorials\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-tick-history/refinitiv-tick-history-rth-rest-api/tutorials\n      - type: Downloads\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-tick-history/refinitiv-tick-history-rth-rest-api/download\n  - name: Datastream Web Service API\n    description: >-\n      API providing access to Datastream, the world's leading time series database\n      with histories back to the 1900s and over 48 million individual instruments\n      or indicators. Available via SOAP, REST (JSON/XML), and .NET library\n      interfaces for Python, R, MATLAB, and EViews.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/eikon/datastream-web-service\n    baseURL: https://product.datastream.com\n    tags:\n      - Datastream\n      - Economic Data\n      - Historical Data\n      - Time Series\n    properties:\n      -\
  \ type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/eikon/datastream-web-service/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/eikon/datastream-web-service/quick-start\n      - type: Tutorials\n        url: https://developers.lseg.com/en/api-catalog/eikon/datastream-web-service/tutorials\n      - type: Downloads\n        url: https://developers.lseg.com/en/api-catalog/eikon/datastream-web-service/download\n  - name: World-Check One API\n    description: >-\n      RESTful API for integrating LSEG World-Check screening capabilities into\n      existing workflows and internal systems. It enables automated customer and\n      third-party screening for onboarding, KYC, and due diligence processes\n      against the World-Check risk intelligence database.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/customer-and-third-party-screening/world-check-one-api\n\
  \    baseURL: https://api.refinitiv.com\n    tags:\n      - Compliance\n      - KYC\n      - Risk Intelligence\n      - Screening\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/customer-and-third-party-screening/world-check-one-api/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/customer-and-third-party-screening/world-check-one-api/quick-start\n      - type: Downloads\n        url: https://developers.lseg.com/en/api-catalog/customer-and-third-party-screening/world-check-one-api/download\n      - type: OpenAPI\n        url: openapi/refinitiv-world-check-one-openapi.yml\n  - name: Qual-ID API\n    description: >-\n      RESTful API for automating identity verification and document verification\n      processes. It helps organizations comply with regulations and identify\n      potential financial crime using trusted and vetted data sources with\n      normalized data fields.\n \
  \   image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/customer-and-third-party-screening/qual-id-api\n    baseURL: https://api.refinitiv.com/verification/v1\n    tags:\n      - Compliance\n      - Document Verification\n      - Identity Verification\n      - KYC\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/customer-and-third-party-screening/qual-id-api/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/customer-and-third-party-screening/qual-id-api/quick-start\n      - type: OpenAPI\n        url: openapi/refinitiv-qual-id-openapi.yml\n  - name: LSEG Due Diligence Portal API\n    description: >-\n      REST API enabling clients to place orders for LSEG Due Diligence Reports\n      from within their own internal systems and onboarding platforms. It uses\n      OAuth2 for security and follows the\
  \ OpenAPI 3 standard for documentation.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/lseg-due-diligence/lseg-due-diligence-reports-api\n    baseURL: https://api.refinitiv.com\n    tags:\n      - Compliance\n      - Due Diligence\n      - Risk\n      - Screening\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/lseg-due-diligence/lseg-due-diligence-reports-api/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/lseg-due-diligence/lseg-due-diligence-reports-api/quick-start\n  - name: Refinitiv Knowledge Direct API (RKD)\n    description: >-\n      API for wealth management that provides access to Refinitiv hosted content\n      and capabilities. It integrates into advisor solutions, customer-facing\n      investment portals, and online trading platforms through a suite of\n      endpoints\
  \ for pricing, news, referential data, and specialized services.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/refinitiv-knowledge-direct/refinitiv-knowledge-direct-api-rkd-api\n    baseURL: https://api.rkd.refinitiv.com\n    tags:\n      - Financial Data\n      - News\n      - Pricing\n      - Wealth Management\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-knowledge-direct/refinitiv-knowledge-direct-api-rkd-api/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/refinitiv-knowledge-direct/refinitiv-knowledge-direct-api-rkd-api/quick-start\n      - type: API Playground\n        url: https://support-portal.rkd.refinitiv.com/\n  - name: PermID Entity Search API\n    description: >-\n      RESTful API enabling search of entities by name, ticker, or RIC to return\n      PermIDs,\
  \ or use PermIDs to retrieve entity information. PermID is an open\n      and free entity identification scheme that provides a unique identifier for\n      organizations, instruments, and quotes.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/open-perm-id/permid-entity-search\n    baseURL: https://api-eit.refinitiv.com\n    tags:\n      - Entity Search\n      - Open Data\n      - PermID\n      - Symbology\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/open-perm-id/permid-entity-search/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/open-perm-id/permid-entity-search/quick-start\n      - type: Website\n        url: https://permid.org/\n      - type: OpenAPI\n        url: openapi/refinitiv-permid-entity-search-openapi.yml\n  - name: Intelligent Tagging RESTful API\n    description: >-\n\
  \      Natural language processing API that identifies and tags entities such as\n      companies, people, deals, geographical locations, industries, and events\n      within unstructured text. It maps recognized entities to Refinitiv PermIDs\n      for unambiguous identification and linking across documents.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/open-perm-id/intelligent-tagging-restful-api\n    baseURL: https://api-eit.refinitiv.com\n    tags:\n      - Entity Recognition\n      - NLP\n      - Tagging\n      - Text Analytics\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/open-perm-id/intelligent-tagging-restful-api/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/open-perm-id/intelligent-tagging-restful-api/quick-start\n  - name: Workspace SDK\n    description: >-\n      End-to-end\
  \ financial application development kit that allows developers to\n      design a GUI, power it with market data, and integrate logic into workflows.\n      It enables creation of web-based financial applications that run side by\n      side with LSEG Workspace.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/workspace-sdk/workspace-sdk\n    baseURL: https://api.refinitiv.com\n    tags:\n      - Application Development\n      - Desktop\n      - SDK\n      - Workspace\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/workspace-sdk/workspace-sdk/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/workspace-sdk/workspace-sdk/quick-start\n      - type: Tutorials\n        url: https://developers.lseg.com/en/api-catalog/workspace-sdk/workspace-sdk/tutorials\n  - name: Workspace Web Side by Side API\n\
  \    description: >-\n      Interoperability API that connects client web applications to LSEG Workspace\n      Web. It allows applications to authenticate, connect to a running Workspace\n      instance in the same browser, and exchange metadata such as active RICs\n      between applications.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/eikon/workspace-web-side-by-side-api\n    baseURL: https://api.refinitiv.com\n    tags:\n      - Desktop\n      - Interoperability\n      - Web\n      - Workspace\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/eikon/workspace-web-side-by-side-api/documentation\n      - type: Getting Started\n        url: https://developers.lseg.com/en/api-catalog/eikon/workspace-web-side-by-side-api/quick-start\n  - name: FX Trading - Spot and Forwards Matching API\n    description: >-\n      FIX protocol-based API\
  \ for electronic FX trading on LSEG Matching venues,\n      supporting spot and forwards currency trading. It uses FIX 5.0 SP2 with a\n      specific set of FIX messages, tags, and workflows for order submission and\n      execution.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/fx-venues/fx-trading-spot-forwards-matching\n    baseURL: https://api.refinitiv.com\n    tags:\n      - FIX Protocol\n      - Forwards\n      - FX Trading\n      - Spot\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/fx-venues/fx-trading-spot-forwards-matching/documentation\n  - name: FX Trading - NDF Matching API\n    description: >-\n      FIX protocol-based API for electronic trading of non-deliverable forwards\n      (NDFs) on LSEG Matching venues. It provides connectivity for trading\n      participants to submit and manage NDF orders.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n\
  \    humanURL: https://developers.lseg.com/en/api-catalog/fx-venues/fx-trading-matching\n    baseURL: https://api.refinitiv.com\n    tags:\n      - Derivatives\n      - FIX Protocol\n      - FX Trading\n      - NDF\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/fx-venues/fx-trading-matching/documentation\n  - name: FX Market Data - NDF Matching API\n    description: >-\n      Point-to-point market data service based on FIX SBE technology, allowing\n      trading participants to receive real-time information for each instrument\n      traded on Primary CLOBs for NDF Matching venues.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/fx-venues/fx-market-data\n    baseURL: https://api.refinitiv.com\n    tags:\n      - FX Market Data\n      - NDF\n      - Real-Time\n      - Trading\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/fx-venues/fx-market-data/documentation\n\
  \  - name: FX Reference Data API\n    description: >-\n      Service providing reference data for LSEG FX venues, offering instrument\n      and venue configuration data to support FX trading operations on the\n      replatformed spot and forward Matching venues.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n    humanURL: https://developers.lseg.com/en/api-catalog/fx-venues/FX-Reference-Data-API\n    baseURL: https://api.refinitiv.com\n    tags:\n      - FX\n      - Reference Data\n      - Trading\n      - Venue\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/fx-venues/FX-Reference-Data-API/documentation\n  - name: FX Participant Insight Reporting API\n    description: >-\n      API providing reporting and analytics for FX trading participants on LSEG\n      venues, enabling access to execution quality metrics and participant insight\n      data.\n    image: https://www.refinitiv.com/etc/designs/refinitiv/images/refinitiv-logo.svg\n\
  \    humanURL: https://developers.lseg.com/en/api-catalog/fx-venues/fx-reporting\n    baseURL: https://api.refinitiv.com\n    tags:\n      - Analytics\n      - FX\n      - Reporting\n      - Trading\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/api-catalog/fx-venues/fx-reporting/documentation\ncommon:\n  - type: JSON-LD\n    url: json-ld/refinitiv-context.jsonld\n  - type: JSONSchema\n    url: json-schema/refinitiv-instrument-schema.json\n  - type: JSONSchema\n    url: json-schema/refinitiv-esg-score-schema.json\n  - type: JSONSchema\n    url: json-schema/refinitiv-screening-case-schema.json\n  - type: JSONSchema\n    url: json-schema/refinitiv-news-article-schema.json\n  - type: Portal\n    url: https://developers.lseg.com/en\n  - type: Getting Started\n    url: https://developers.lseg.com/en/api-catalog\n  - type: Documentation\n    url: https://developers.lseg.com/en/api-catalog\n  - type: Support\n    url: https://developers.lseg.com/en/support\n\
  \  - type: Blog\n    url: https://developers.lseg.com/en/article-catalog\n  - type: GitHub Organization\n    url: https://github.com/LSEG-API-Samples\n  - type: GitHub Organization\n    url: https://github.com/Refinitiv-API-Samples\n  - type: Terms of Service\n    url: https://developers.lseg.com/en/terms-and-conditions\n  - type: Contact\n    url: https://developers.lseg.com/en/contact-us\n  - type: Privacy Policy\n    url: https://www.lseg.com/en/policies/privacy-statement\n  - type: Community\n    url: https://community.developers.refinitiv.com/\n  - type: Website\n    url: https://www.lseg.com/en\n  - type: Login\n    url: https://www.lseg.com/en/product-logins\n  - type: Developer Tools\n    url: https://developers.lseg.com/en/tools-catalog\n  - type: Medium\n    url: https://medium.com/lseg-developer-community\n  - type: OpenAPI\n    url: openapi/refinitiv-data-platform-openapi.yml\n  - type: OpenAPI\n    url: openapi/refinitiv-datascope-select-openapi.yml\n  - type: OpenAPI\n  \
  \  url: openapi/refinitiv-permid-entity-search-openapi.yml\n  - type: OpenAPI\n    url: openapi/refinitiv-qual-id-openapi.yml\n  - type: OpenAPI\n    url: openapi/refinitiv-world-check-one-openapi.yml\n  - type: AsyncAPI\n    url: asyncapi/refinitiv-real-time-websocket-asyncapi.yml\n  - type: JSONSchema\n    url: json-schema/refinitiv-instrument-schema.json\n  - type: JSONSchema\n    url: json-schema/refinitiv-esg-score-schema.json\n  - type: JSONSchema\n    url: json-schema/refinitiv-news-article-schema.json\n  - type: JSONSchema\n    url: json-schema/refinitiv-screening-case-schema.json\n  - type: JSONStructure\n    url: json-structure/refinitiv-data-platform-structure.json\n  - type: JSONLDContext\n    url: json-ld/refinitiv-context.jsonld\n  - type: SpectralRules\n    url: rules/refinitiv-rules.yml\n  - type: NaftikoCapabilities\n    url: capabilities/financial-market-data.yaml\n  - type: NaftikoCapabilities\n    url: capabilities/compliance-screening.yaml\n  - type: Vocabulary\n \
  \   url: vocabulary/refinitiv-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/apis.yml
use_cases: []
---
