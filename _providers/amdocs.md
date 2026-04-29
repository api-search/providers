---
api_count: 3
apis:
- description: The Amdocs connectX BSS API provides cloud-native SaaS BSS capabilities for telecom operators, covering billing, provisioning, customer management, and subscription lifecycle. Built on TM Forum Open A
  name: Amdocs connectX BSS API
  slug: amdocs-connectx-api
- description: The Amdocs MarketONE API provides digital BSS capabilities for telecoms, supporting catalog management, order management, customer management, and digital service delivery. REST APIs enable integratio
  name: Amdocs MarketONE API
  slug: amdocs-marketone-api
- description: The Amdocs NetCracker OSS API provides network inventory management, network provisioning, and service assurance capabilities for telecom operators. REST and SOAP APIs support integration with network
  name: Amdocs NetCracker OSS API
  slug: amdocs-netcracker-oss-api
asyncapis:
- description: The Amdocs connectX BSS Event API delivers real-time event notifications for telecom BSS operations including customer lifecycle events, subscription changes, billing events, and provisioning status u
  name: Amdocs connectX BSS Event API
  slug: amdocs-events-asyncapi
capabilities:
- description: Unified workflow for telecom operators managing customer accounts, subscriptions, billing, and service catalog via Amdocs connectX BSS API. Supports BSS operators, customer care agents, and billing te
  name: Amdocs Telco Customer Management
  slug: telco-customer-management
common:
- title: ''
  type: Website
  url: https://www.amdocs.com/
- title: ''
  type: Portal
  url: https://devportal.amdocs-dbs.com/
- title: ''
  type: Documentation
  url: https://knowledge.amdocs-dbs.com/
- title: ''
  type: GettingStarted
  url: https://developer.amdocs-dbs.com/reference/getting-started-with-your-api
- title: ''
  type: GitHubOrganization
  url: https://github.com/open-amdocs
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/json-schema/amdocs-customer-schema.json
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/json-ld/amdocs-context.jsonld
created: '2026-03-18'
description: Amdocs is a global technology company providing software and services to communications and media companies worldwide. Its connectX platform is a cloud-native SaaS BSS solution for telecom operators covering customer management, billing, provisioning, and subscription lifecycle. Amdocs also provides MarketONE for digital BSS, NetCracker for OSS network management, and an expanding suite of AI-powered telco solutions built on TM Forum Open APIs.
features:
- description: All connectX APIs comply with TM Forum Open API standards, enabling fast integration with third-party systems and reducing customization requirements.
  name: TM Forum Open API Compliance
- description: GenAI-powered platform capabilities including AI-driven customer journeys, predictive analytics, and automated decision making for telco operations.
  name: AI-Native Capabilities
- description: Serverless microservices architecture deployed on AWS providing elastic scalability, local data residency compliance, and rapid deployment for MVNOs and telcos.
  name: Cloud-Native SaaS Architecture
- description: Built-in eSIM lifecycle management enabling telcos and MVNOs to support digital SIM provisioning without physical SIM cards.
  name: eSIM Management
- description: Pre-built customer journeys spanning mobile apps, web self-service, and multi-channel support for consumer and business segments.
  name: Omnichannel Customer Experience
- description: End-to-end MVNO and MVNE capabilities including wireless prepaid, postpaid, and B2C solutions with rapid market launch support.
  name: MVNO and MVNE Support
- description: Flexible product catalog management for bundling connectivity with digital services, plus end-to-end order management across consumer, business, and enterprise segments.
  name: Catalog and Order Management
- description: Converged billing, revenue assurance, and monetization capabilities supporting current and emerging revenue models including subscription and usage-based billing.
  name: Revenue Management
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: connectX is powered by Amazon Web Services providing cloud infrastructure, elastic scalability, and global reach.
  name: AWS
- description: Full compliance with TM Forum Open API standards enabling plug-and-play integration with ecosystem partners and third-party systems.
  name: TM Forum Open APIs
- description: Customer Engagement Platform partnership with Microsoft for AI-driven customer interactions and analytics.
  name: Microsoft
- description: Integration with multi-vendor network management systems and OSS platforms via NetCracker APIs.
  name: Network Management Systems
jsonld:
- class_count: 4
  name: Amdocs Amdocs Context
  property_count: 11
  slug: amdocs-amdocs-context
- class_count: 18
  name: Amdocs Connectx Context
  property_count: 42
  slug: amdocs-connectx-context
- class_count: 0
  name: Amdocs Context
  property_count: 5
  slug: amdocs-context
layout: provider
modified: '2026-04-19'
name: Amdocs
rules:
- name: Amdocs API Rules
  rule_count: 21
  severity_counts:
    error: 12
    hint: 0
    info: 2
    warn: 7
  slug: amdocs-spectral-rules
skills: []
slug: amdocs
solutions:
- description: All-in-one SaaS BSS platform for telcos and MVNOs with AI-powered customer management, billing, and monetization capabilities.
  name: connectX
- description: Digital BSS platform for managing and monetizing subscriptions with integrated digital partners and omnichannel delivery.
  name: MarketONE
- description: Telco cloud transformation solutions for 5G, fiber, and IoT network deployment and optimization.
  name: Amdocs Networks
- description: Mobile wallet and financial services enablement for telco operators entering digital banking and fintech markets.
  name: Digital Financial Services Platform
source_filename: apis.yml
source_yaml: "aid: amdocs\nname: Amdocs\ndescription: >-\n  Amdocs is a global technology company providing software and services to\n  communications and media companies worldwide. Its connectX platform is a\n  cloud-native SaaS BSS solution for telecom operators covering customer\n  management, billing, provisioning, and subscription lifecycle. Amdocs also\n  provides MarketONE for digital BSS, NetCracker for OSS network management,\n  and an expanding suite of AI-powered telco solutions built on TM Forum Open\n  APIs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Telecom\n  - BSS\n  - OSS\n  - Billing\n  - Customer Management\n  - MVNO\n  - 5G\n  - SaaS\nurl: https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/apis.yml\ncreated: '2026-03-18'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amdocs:amdocs-connectx-api\n    name: Amdocs connectX BSS API\n    description: >-\n      The Amdocs\
  \ connectX BSS API provides cloud-native SaaS BSS capabilities\n      for telecom operators, covering billing, provisioning, customer management,\n      and subscription lifecycle. Built on TM Forum Open APIs, it enables\n      integration with CRM, network management, and revenue assurance systems\n      for digital telco and MVNO operations. Powered by AWS with AI-native\n      capabilities and eSIM support.\n    humanURL: https://devportal.amdocs-dbs.com/\n    baseURL: https://api.amdocs-dbs.com\n    tags:\n      - Billing\n      - BSS\n      - Provisioning\n      - Telecom\n      - MVNO\n      - SaaS\n    properties:\n      - type: Documentation\n        url: https://devportal.amdocs-dbs.com/\n      - type: GettingStarted\n        url: https://developer.amdocs-dbs.com/reference/getting-started-with-your-api\n      - type: APIReference\n        url: https://developer.amdocs-dbs.com/reference/getting-started-with-your-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/openapi/amdocs-connectx-openapi.yml\n\
  \      - type: AsyncAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/asyncapi/amdocs-events-asyncapi.yml\n\n  - aid: amdocs:amdocs-marketone-api\n    name: Amdocs MarketONE API\n    description: >-\n      The Amdocs MarketONE API provides digital BSS capabilities for telecoms,\n      supporting catalog management, order management, customer management, and\n      digital service delivery. REST APIs enable integration with the Amdocs\n      MarketONE platform for telco digital transformation and omnichannel\n      service delivery including mobile apps and web self-services.\n    humanURL: https://developer.m1amdocs.com/\n    baseURL: https://api.m1amdocs.com\n    tags:\n      - BSS\n      - Digital Services\n      - Order Management\n      - Telecom\n    properties:\n      - type: Documentation\n        url: https://developer.m1amdocs.com/\n      - type: APIReference\n        url: https://developer.m1amdocs.com/api/\n      - type:\
  \ Authentication\n        url: https://developer.m1amdocs.com/documentation/Content/E-API%20Guides/ULMProcessGuide/ProcessCatalogue/AuthenticateUserProcess.htm\n\n  - aid: amdocs:amdocs-netcracker-oss-api\n    name: Amdocs NetCracker OSS API\n    description: >-\n      The Amdocs NetCracker OSS API provides network inventory management,\n      network provisioning, and service assurance capabilities for telecom\n      operators. REST and SOAP APIs support integration with network management\n      systems, trouble ticketing, and service fulfillment platforms across\n      multi-vendor network environments.\n    humanURL: https://www.amdocs.com/products-services\n    baseURL: https://api.amdocs.com\n    tags:\n      - Network Inventory\n      - Network Management\n      - OSS\n      - Telecom\n    properties:\n      - type: Documentation\n        url: https://www.amdocs.com/products-services\n\ncommon:\n  - type: Website\n    url: https://www.amdocs.com/\n  - type: Portal\n    url: https://devportal.amdocs-dbs.com/\n\
  \  - type: Documentation\n    url: https://knowledge.amdocs-dbs.com/\n  - type: GettingStarted\n    url: https://developer.amdocs-dbs.com/reference/getting-started-with-your-api\n  - type: GitHubOrganization\n    url: https://github.com/open-amdocs\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/json-schema/amdocs-customer-schema.json\n  - type: JSONLD\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/json-ld/amdocs-context.jsonld\n  - type: Features\n    data:\n      - name: TM Forum Open API Compliance\n        description: >-\n          All connectX APIs comply with TM Forum Open API standards, enabling\n          fast integration with third-party systems and reducing customization\n          requirements.\n      - name: AI-Native Capabilities\n        description: >-\n          GenAI-powered platform capabilities including AI-driven customer\n          journeys, predictive analytics,\
  \ and automated decision making for\n          telco operations.\n      - name: Cloud-Native SaaS Architecture\n        description: >-\n          Serverless microservices architecture deployed on AWS providing\n          elastic scalability, local data residency compliance, and rapid\n          deployment for MVNOs and telcos.\n      - name: eSIM Management\n        description: >-\n          Built-in eSIM lifecycle management enabling telcos and MVNOs to\n          support digital SIM provisioning without physical SIM cards.\n      - name: Omnichannel Customer Experience\n        description: >-\n          Pre-built customer journeys spanning mobile apps, web self-service,\n          and multi-channel support for consumer and business segments.\n      - name: MVNO and MVNE Support\n        description: >-\n          End-to-end MVNO and MVNE capabilities including wireless prepaid,\n          postpaid, and B2C solutions with rapid market launch support.\n      - name: Catalog and Order\
  \ Management\n        description: >-\n          Flexible product catalog management for bundling connectivity with\n          digital services, plus end-to-end order management across consumer,\n          business, and enterprise segments.\n      - name: Revenue Management\n        description: >-\n          Converged billing, revenue assurance, and monetization capabilities\n          supporting current and emerging revenue models including subscription\n          and usage-based billing.\n  - type: UseCases\n    data:\n      - name: MVNO Launch\n        description: >-\n          Rapidly launch new MVNO brands with pre-integrated telco-in-a-box\n          capabilities including customer management, billing, and digital\n          channels.\n      - name: BSS Digital Transformation\n        description: >-\n          Migrate from legacy BSS to cloud-native SaaS BSS with TM Forum Open\n          API compliance and pre-built integrations for telco digital\n          transformation.\n \
  \     - name: 5G Monetization\n        description: >-\n          Launch and monetize 5G services with flexible catalog management,\n          usage-based billing, and analytics for network slicing and IoT.\n      - name: Customer Self-Service\n        description: >-\n          Deploy omnichannel self-service portals and mobile apps with\n          pre-built customer journeys for account management, plan changes, and\n          billing.\n      - name: Gen Z Mobile Services\n        description: >-\n          Launch fully customizable mobile plans enabling subscribers to\n          configure data, calls, texts, and plan length via AI-powered apps.\n      - name: IoT Service Management\n        description: >-\n          Manage IoT connectivity, device onboarding, and usage-based billing\n          for enterprise IoT deployments across telecom networks.\n  - type: Integrations\n    data:\n      - name: AWS\n        description: >-\n          connectX is powered by Amazon Web Services providing\
  \ cloud\n          infrastructure, elastic scalability, and global reach.\n      - name: TM Forum Open APIs\n        description: >-\n          Full compliance with TM Forum Open API standards enabling plug-and-play\n          integration with ecosystem partners and third-party systems.\n      - name: Microsoft\n        description: >-\n          Customer Engagement Platform partnership with Microsoft for AI-driven\n          customer interactions and analytics.\n      - name: Network Management Systems\n        description: >-\n          Integration with multi-vendor network management systems and OSS\n          platforms via NetCracker APIs.\n  - type: Solutions\n    data:\n      - name: connectX\n        description: >-\n          All-in-one SaaS BSS platform for telcos and MVNOs with AI-powered\n          customer management, billing, and monetization capabilities.\n      - name: MarketONE\n        description: >-\n          Digital BSS platform for managing and monetizing subscriptions\
  \ with\n          integrated digital partners and omnichannel delivery.\n      - name: Amdocs Networks\n        description: >-\n          Telco cloud transformation solutions for 5G, fiber, and IoT network\n          deployment and optimization.\n      - name: Digital Financial Services Platform\n        description: >-\n          Mobile wallet and financial services enablement for telco operators\n          entering digital banking and fintech markets.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/apis.yml
tags:
- Telecom
- BSS
- OSS
- Billing
- Customer Management
- MVNO
- 5G
- SaaS
url: https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/apis.yml
use_cases:
- description: Rapidly launch new MVNO brands with pre-integrated telco-in-a-box capabilities including customer management, billing, and digital channels.
  name: MVNO Launch
- description: Migrate from legacy BSS to cloud-native SaaS BSS with TM Forum Open API compliance and pre-built integrations for telco digital transformation.
  name: BSS Digital Transformation
- description: Launch and monetize 5G services with flexible catalog management, usage-based billing, and analytics for network slicing and IoT.
  name: 5G Monetization
- description: Deploy omnichannel self-service portals and mobile apps with pre-built customer journeys for account management, plan changes, and billing.
  name: Customer Self-Service
- description: Launch fully customizable mobile plans enabling subscribers to configure data, calls, texts, and plan length via AI-powered apps.
  name: Gen Z Mobile Services
- description: Manage IoT connectivity, device onboarding, and usage-based billing for enterprise IoT deployments across telecom networks.
  name: IoT Service Management
---
