---
api_count: 1
apis:
- description: The Coupang Open API is a RESTful seller (vendor) API for managing the full marketplace lifecycle including product catalog creation, order processing, return and cancellation handling, settlement que
  name: Coupang Open API
  slug: ''
common:
- title: ''
  type: Website
  url: https://www.coupang.com
- title: ''
  type: DeveloperPortal
  url: https://developers.coupangcorp.com/
- title: ''
  type: SellerPortal
  url: https://wing.coupang.com/
- title: ''
  type: About
  url: https://www.aboutcoupang.com/
- title: ''
  type: TermsOfService
  url: https://www.coupang.com/np/policies/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.coupang.com/np/policies/privacy
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/coupang
created: '2024-01-01'
description: Coupang is a South Korean e-commerce company offering rapid delivery of a wide range of products including groceries, electronics, fashion, and household goods through its mobile app and website. Coupang exposes an Open API platform for marketplace sellers (vendors) to integrate product catalog, order, return, cancellation, settlement, and inquiry workflows.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Coupang
skills: []
slug: coupang
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: coupang\nname: Coupang\nx-type: company\ndescription: >-\n  Coupang is a South Korean e-commerce company offering rapid delivery of a wide\n  range of products including groceries, electronics, fashion, and household\n  goods through its mobile app and website. Coupang exposes an Open API platform\n  for marketplace sellers (vendors) to integrate product catalog, order, return,\n  cancellation, settlement, and inquiry workflows.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/coupang/refs/heads/main/apis.yml\ntype: Index\naccess: 3rd-Party\nposition: Consuming\ncreated: '2024-01-01'\nmodified: '2026-04-28'\ntags:\n  - Cancellations\n  - E-commerce\n  - Korea\n  - Marketplace\n  - Open API\n  - Orders\n  - Products\n  - Returns\n  - Sellers\n  - Settlement\n  - Vendors\napis:\n  - name: Coupang Open API\n    description: >-\n      The Coupang Open API is a RESTful seller (vendor) API\
  \ for managing the\n      full marketplace lifecycle including product catalog creation, order\n      processing, return and cancellation handling, settlement queries, and\n      customer inquiries. Authentication uses HMAC-signed Authorization headers\n      with an X-Requested-By header issued from the WING seller portal.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.coupangcorp.com/\n    baseURL: https://api-gateway.coupang.com\n    tags:\n      - HMAC\n      - Marketplace\n      - Open API\n      - Orders\n      - Products\n      - REST\n      - Sellers\n      - Vendors\n    properties:\n      - type: Documentation\n        url: https://developers.coupangcorp.com/\n      - type: GettingStarted\n        url: https://developers.coupangcorp.com/hc/en-us/articles/360033917473-Coupang-OPEN-API\n      - type: TestGuide\n        url: https://developers.coupangcorp.com/hc/en-us/articles/360033988873-OPEN-API-Test-Guide\n\
  \      - type: ProductAPI\n        url: https://developers.coupangcorp.com/hc/en-us/sections/360004260614-Product-API\n      - type: ReturnAPI\n        url: https://developers.coupangcorp.com/hc/en-us/sections/360004302273-Return-API\n      - type: SettlementAPI\n        url: https://developers.coupangcorp.com/hc/en-us/articles/360034152213-Settlement-Detail-Query\n      - type: ProductListingGuide\n        url: https://developers.coupangcorp.com/hc/en-us/articles/360034889893-OPEN-API-Product-Listing-Guide\n      - type: FAQ\n        url: https://developers.coupangcorp.com/hc/en-us/categories/360001818893-FAQs\n    features:\n      - name: HMAC Authentication\n        description: Requests are signed using HMAC-SHA256 with the Open API key issued from WING.\n      - name: Vendor-Scoped Endpoints\n        description: All operations are scoped to a vendor ID issued by Coupang.\n      - name: Full Marketplace Lifecycle\n        description: Product catalog, order processing, returns, cancellations,\
  \ settlements, and inquiries.\n    useCases:\n      - name: Seller Inventory Sync\n        description: Synchronize SKUs and inventory between an external commerce platform and Coupang.\n      - name: Order Fulfillment Automation\n        description: Pull new orders, push shipping confirmations, and manage cancellations and returns.\n      - name: Settlement Reconciliation\n        description: Pull settlement histories for finance and accounting reconciliation.\n    contact:\n      - type: Support\n        url: https://developers.coupangcorp.com/hc/en-us\ncommon:\n  - type: Website\n    url: https://www.coupang.com\n  - type: DeveloperPortal\n    url: https://developers.coupangcorp.com/\n  - type: SellerPortal\n    url: https://wing.coupang.com/\n  - type: About\n    url: https://www.aboutcoupang.com/\n  - type: TermsOfService\n    url: https://www.coupang.com/np/policies/terms\n  - type: PrivacyPolicy\n    url: https://www.coupang.com/np/policies/privacy\n  - type: LinkedIn\n    url:\
  \ https://www.linkedin.com/company/coupang\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/coupang/refs/heads/main/apis.yml
tags:
- Cancellations
- E-commerce
- Korea
- Marketplace
- Open API
- Orders
- Products
- Returns
- Sellers
- Settlement
- Vendors
url: https://raw.githubusercontent.com/api-evangelist/coupang/refs/heads/main/apis.yml
use_cases: []
---
