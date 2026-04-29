---
api_count: 2
apis:
- description: 'The Assurant APEX (Assurant Product Experience Exchange) platform provides embedded insurance APIs that enable partners to integrate protection products, claims management, and diagnostics into their '
  name: Assurant APEX Embedded Insurance API
  slug: apex-insurance-api
- description: The Assurant Global Housing API provides property management companies and housing partners with programmatic access to insurance products including renter's insurance, lender-placed insurance, and pr
  name: Assurant Global Housing API
  slug: global-housing-api
common:
- title: Assurant Website
  type: Portal
  url: https://www.assurant.com/
- title: APEX Partner Platform
  type: Portal
  url: https://www.assurant.com/partner-with-us/apex
- title: Partner with Assurant
  type: SignUp
  url: https://www.assurant.com/partner-with-us/apex
created: '2024-01-15'
description: Assurant is a global provider of lifestyle and housing solutions that help people thrive in a connected world. The company provides protection products and services including device protection, renter's insurance, auto F&I products, and connected living services. Assurant's APEX (Assurant Product Experience Exchange) platform provides embedded insurance APIs that enable partners to integrate protection products, claims management, and diagnostics directly into their workflows and customer experiences. The APEX platform supports 99.95% uptime and covers multiple product lines across technology, real estate, auto, and retail industries.
features:
- description: APIs for embedding smartphone, tablet, and consumer electronics protection programs directly into carrier, retailer, and OEM customer experiences.
  name: Embedded Device Protection
- description: End-to-end claims management APIs supporting claim filing, status tracking, device diagnostics, and repair/replacement fulfillment.
  name: Claims Management
- description: API integration for embedding renter's insurance enrollment, policy management, and claims into property management platforms.
  name: Renter's Insurance
- description: Finance and insurance product APIs for automotive dealers including vehicle service contracts, GAP insurance, and protection products.
  name: Auto F&I Products
- description: Smart home device protection and tech support service APIs for connected device ecosystems.
  name: Connected Living Services
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration with mobile carrier billing and CRM systems for device protection plan enrollment and premium collection.
  name: Carrier Billing Systems
- description: Integration with property management software including Yardi, RealPage, and AppFolio for renter's insurance programs.
  name: Property Management Platforms
- description: Integration with automotive DMS platforms for F&I product enrollment and vehicle protection program management.
  name: Dealer Management Systems
layout: provider
modified: '2026-04-19'
name: Assurant
skills: []
slug: assurant
solutions: []
source_yaml: "aid: assurant\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/assurant/refs/heads/main/apis.yml\nname: Assurant\ndescription: >-\n  Assurant is a global provider of lifestyle and housing solutions that help\n  people thrive in a connected world. The company provides protection products\n  and services including device protection, renter's insurance, auto F&I\n  products, and connected living services. Assurant's APEX (Assurant Product\n  Experience Exchange) platform provides embedded insurance APIs that enable\n  partners to integrate protection products, claims management, and diagnostics\n  directly into their workflows and customer experiences. The APEX platform\n  supports 99.95% uptime and covers multiple product lines across technology,\n  real estate, auto, and retail industries.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Insurance\n  - Device Protection\n  - Embedded Insurance\n  - Housing\n\
  \  - Claims\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: assurant:apex-insurance-api\n    name: Assurant APEX Embedded Insurance API\n    description: >-\n      The Assurant APEX (Assurant Product Experience Exchange) platform\n      provides embedded insurance APIs that enable partners to integrate\n      protection products, claims management, and diagnostics into their\n      workflows. The scalable API platform supports 99.95% uptime and\n      covers product lines including device protection, renter's insurance,\n      auto F&I products, and connected living services across multiple\n      industries.\n    humanURL: https://www.assurant.com/partner-with-us/apex\n    baseURL: https://api-prod.portal.assurant.com\n    tags:\n      - Claims\n      - Device Protection\n      - Embedded Insurance\n      - Insurance\n    properties:\n      - type: Documentation\n        url: https://www.assurant.com/partner-with-us/apex\n      - type: OpenAPI\n\
  \        url: openapi/assurant-apex-insurance-api-openapi.yml\n  - aid: assurant:global-housing-api\n    name: Assurant Global Housing API\n    description: >-\n      The Assurant Global Housing API provides property management companies\n      and housing partners with programmatic access to insurance products\n      including renter's insurance, lender-placed insurance, and property\n      preservation services. The API enables seamless integration of\n      housing protection solutions into partner platforms.\n    humanURL: https://www.assurant.com/partner-with-us/apex/global-housing\n    baseURL: https://housing-apis.developer.assurant.com\n    tags:\n      - Housing\n      - Insurance\n      - Property\n      - Renters Insurance\n    properties:\n      - type: Documentation\n        url: https://www.assurant.com/partner-with-us/apex/global-housing\ncommon:\n  - type: Portal\n    url: https://www.assurant.com/\n    title: Assurant Website\n  - type: Portal\n    url: https://www.assurant.com/partner-with-us/apex\n\
  \    title: APEX Partner Platform\n  - type: SignUp\n    url: https://www.assurant.com/partner-with-us/apex\n    title: Partner with Assurant\n  - type: Features\n    data:\n      - name: Embedded Device Protection\n        description: >-\n          APIs for embedding smartphone, tablet, and consumer electronics\n          protection programs directly into carrier, retailer, and OEM\n          customer experiences.\n      - name: Claims Management\n        description: >-\n          End-to-end claims management APIs supporting claim filing, status\n          tracking, device diagnostics, and repair/replacement fulfillment.\n      - name: Renter's Insurance\n        description: >-\n          API integration for embedding renter's insurance enrollment, policy\n          management, and claims into property management platforms.\n      - name: Auto F&I Products\n        description: >-\n          Finance and insurance product APIs for automotive dealers including\n          vehicle service\
  \ contracts, GAP insurance, and protection products.\n      - name: Connected Living Services\n        description: >-\n          Smart home device protection and tech support service APIs for\n          connected device ecosystems.\n  - type: UseCases\n    data:\n      - name: Mobile Carrier Device Protection\n        description: >-\n          Mobile carriers integrate APEX APIs to offer device protection plans\n          at point of sale and manage claims for damaged or lost devices.\n      - name: Property Management Renters Insurance\n        description: >-\n          Property management companies integrate the Global Housing API to\n          offer and track renter's insurance compliance among tenants.\n      - name: Auto Dealer F&I Integration\n        description: >-\n          Auto dealers and F&I providers integrate Assurant's vehicle protection\n          APIs into dealer management systems for protection product sales.\n      - name: E-Commerce Protection Programs\n      \
  \  description: >-\n          Retailers integrate APEX APIs to offer product protection programs\n          at checkout for electronics, appliances, and other products.\n  - type: Integrations\n    data:\n      - name: Carrier Billing Systems\n        description: >-\n          Integration with mobile carrier billing and CRM systems for device\n          protection plan enrollment and premium collection.\n      - name: Property Management Platforms\n        description: >-\n          Integration with property management software including Yardi,\n          RealPage, and AppFolio for renter's insurance programs.\n      - name: Dealer Management Systems\n        description: >-\n          Integration with automotive DMS platforms for F&I product enrollment\n          and vehicle protection program management.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/assurant/refs/heads/main/apis.yml
tags:
- Insurance
- Device Protection
- Embedded Insurance
- Housing
- Claims
url: https://raw.githubusercontent.com/api-evangelist/assurant/refs/heads/main/apis.yml
use_cases:
- description: Mobile carriers integrate APEX APIs to offer device protection plans at point of sale and manage claims for damaged or lost devices.
  name: Mobile Carrier Device Protection
- description: Property management companies integrate the Global Housing API to offer and track renter's insurance compliance among tenants.
  name: Property Management Renters Insurance
- description: Auto dealers and F&I providers integrate Assurant's vehicle protection APIs into dealer management systems for protection product sales.
  name: Auto Dealer F&I Integration
- description: Retailers integrate APEX APIs to offer product protection programs at checkout for electronics, appliances, and other products.
  name: E-Commerce Protection Programs
---
