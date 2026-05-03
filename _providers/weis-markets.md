---
api_count: 2
apis:
- description: The Weis Markets Vendor Integration API enables supplier and vendor partners to exchange purchase orders, invoices, item management data, and vendor contact information electronically. The platform us
  name: Weis Markets Vendor Integration API
  slug: vendor-integration-api
- description: The Weis Markets Loyalty Rewards API supports the Weis Rewards program, enabling digital loyalty card management, points accumulation, personalized offers, and integration with third-party platforms i
  name: Weis Markets Loyalty Rewards API
  slug: loyalty-rewards-api
common:
- title: ''
  type: Website
  url: https://www.weismarkets.com
- title: ''
  type: VendorPortal
  url: https://weismarkets.streamcollab.com/
- title: ''
  type: MobileApp
  url: https://www.weismarkets.com/wendys-app
- title: ''
  type: GitHubOrg
  url: https://github.com/weis-markets
- title: ''
  type: JSONLDContext
  url: json-ld/weis-markets-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/weis-markets-vocabulary.yml
created: ''
description: Weis Markets is a regional supermarket chain operating grocery stores in the mid-Atlantic United States, with 197 store locations across Pennsylvania, Maryland, Delaware, New Jersey, New York, Virginia, and West Virginia. The company operates a digital commerce platform, loyalty rewards program (Weis Rewards), mobile app, and vendor/supplier integration ecosystem using EDI and supply chain APIs. Weis Markets uses Toshiba ELERA commerce platform for unified in-store and online commerce.
features: []
image: ''
integrations: []
jsonld:
- class_count: 6
  name: Weis Markets Context
  property_count: 23
  slug: weis-markets-context
layout: provider
modified: '2026-05-03'
name: weis-markets
skills: []
slug: weis-markets
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: weis-markets\nurl: https://raw.githubusercontent.com/api-evangelist/weis-markets/refs/heads/main/apis.yml\nmodified: '2026-05-03'\ndescription: >-\n  Weis Markets is a regional supermarket chain operating grocery stores in the\n  mid-Atlantic United States, with 197 store locations across Pennsylvania,\n  Maryland, Delaware, New Jersey, New York, Virginia, and West Virginia. The\n  company operates a digital commerce platform, loyalty rewards program (Weis\n  Rewards), mobile app, and vendor/supplier integration ecosystem using EDI and\n  supply chain APIs. Weis Markets uses Toshiba ELERA commerce platform for\n  unified in-store and online commerce.\ncommon:\n  - type: Website\n    url: https://www.weismarkets.com\n  - type: VendorPortal\n    url: https://weismarkets.streamcollab.com/\n  - type: MobileApp\n    url: https://www.weismarkets.com/wendys-app\n  - type: GitHubOrg\n    url: https://github.com/weis-markets\n  - type: JSONLDContext\n    url: json-ld/weis-markets-context.jsonld\n\
  \  - type: Vocabulary\n    url: vocabulary/weis-markets-vocabulary.yml\napis:\n  - aid: weis-markets:vendor-integration-api\n    name: Weis Markets Vendor Integration API\n    tags:\n      - Grocery\n      - Retail\n      - Supply Chain\n      - EDI\n      - Vendor Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://weismarkets.streamcollab.com\n    humanURL: https://www.weismarkets.com/vendor-partners\n    description: >-\n      The Weis Markets Vendor Integration API enables supplier and vendor\n      partners to exchange purchase orders, invoices, item management data, and\n      vendor contact information electronically. The platform uses the Biceps\n      purchase order system with EDI connectivity and supports vendor deal\n      submissions, item setup, and performance monitoring. Third-party EDI\n      providers such as Vantree, TrueCommerce, and eZCom Software can automate\n      workflows for vendors connecting\
  \ to the Weis Markets supply chain network.\n    properties:\n      - url: https://www.weismarkets.com/vendor-partners\n        type: Documentation\n      - url: https://weismarkets.streamcollab.com/\n        type: Portal\n      - url: examples/weis-markets-vendor-purchase-order-example.json\n        type: Example\n  - aid: weis-markets:loyalty-rewards-api\n    name: Weis Markets Loyalty Rewards API\n    tags:\n      - Grocery\n      - Retail\n      - Loyalty\n      - Rewards\n      - Digital Commerce\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://www.weismarkets.com\n    humanURL: https://www.weismarkets.com\n    description: >-\n      The Weis Markets Loyalty Rewards API supports the Weis Rewards program,\n      enabling digital loyalty card management, points accumulation, personalized\n      offers, and integration with third-party platforms including Amazon. The\n      program is powered by Birdzi analytics and CitrusAd\
  \ digital advertising,\n      providing customer insights and targeted promotions through the Weis\n      Markets mobile app and e-grocery website (Mercatus-powered).\n    properties:\n      - url: https://www.weismarkets.com/wendys-app\n        type: Documentation\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/weis-markets/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/weis-markets/refs/heads/main/apis.yml
use_cases: []
---
