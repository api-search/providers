---
api_count: 4
apis:
- description: REST API that enables deep integration between Carvana and authorized partners (car rental companies, wholesalers, and fleet operators) for posting, updating, and managing used-vehicle inventory. Requ
  name: Carvana Partner API
  slug: partner-api
- description: API surface supporting Carvana Collective partner-collaborative workflows; access is restricted to authorized Carvana partners.
  name: Carvana Collective API
  slug: collective-api
- description: Carvana's used-car inventory and sales data product published on AWS Data Exchange for direct subscription and data-warehouse delivery to analytics, pricing, and market-research consumers.
  name: Carvana Car Sales Data (AWS Data Exchange)
  slug: aws-data-exchange
- description: Consumer-facing explainer describing how Carvana sources partner inventory (rental fleets and other partners) into the buyer catalog.
  name: Carvana Partner Inventory Help Center
  slug: partner-inventory-help
common:
- title: ''
  type: Website
  url: https://www.carvana.com
- title: ''
  type: Portal
  url: https://api-developer.carvana.com/
- title: ''
  type: Login
  url: https://api-developer.carvana.com/signin
- title: ''
  type: Help
  url: https://www.carvana.com/help
- title: ''
  type: Sell
  url: https://www.carvana.com/sell-car
- title: ''
  type: Finance
  url: https://www.carvana.com/finance
- title: ''
  type: VendingMachines
  url: https://www.carvana.com/vending-machine-locations
- title: ''
  type: About
  url: https://www.carvana.com/company/about_us
- title: ''
  type: InvestorRelations
  url: https://investors.carvana.com
- title: ''
  type: Careers
  url: https://www.carvana.com/careers
- title: ''
  type: Contact
  url: https://www.carvana.com/help/contact-us
- title: ''
  type: TermsOfService
  url: https://www.carvana.com/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.carvana.com/privacy-policy
created: '2026-03-21'
description: Carvana is an e-commerce platform for buying, selling, and financing used cars online, featuring home delivery or pickup at its distinctive car vending machines. Its primary developer-facing integration surface is the Carvana Partner REST API (published on Azure API Management at api-developer.carvana.com) which enables authorized rental companies, wholesalers, and fleet partners to post, update, and manage inventory in Carvana's catalog. A Carvana Collective API (api.collective.carvana.com) supports partner-collective workflows, and Carvana also distributes inventory data via AWS Data Exchange.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Carvana Context
  property_count: 9
  slug: carvana-context
layout: provider
modified: '2026-04-23'
name: Carvana
skills: []
slug: carvana
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: carvana\nname: Carvana\ndescription: >-\n  Carvana is an e-commerce platform for buying, selling, and financing used\n  cars online, featuring home delivery or pickup at its distinctive car\n  vending machines. Its primary developer-facing integration surface is\n  the Carvana Partner REST API (published on Azure API Management at\n  api-developer.carvana.com) which enables authorized rental companies,\n  wholesalers, and fleet partners to post, update, and manage inventory in\n  Carvana's catalog. A Carvana Collective API (api.collective.carvana.com)\n  supports partner-collective workflows, and Carvana also distributes\n  inventory data via AWS Data Exchange.\ntype: Index\nposition: Provider\naccess: Partner\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automotive\n  - E-Commerce\n  - Used Cars\n  - Inventory\n  - Partner API\n  - Fortune 500\ncreated: '2026-03-21'\nmodified: '2026-04-23'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/carvana/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: carvana:partner-api\n    name: Carvana Partner API\n    description: >-\n      REST API that enables deep integration between Carvana and authorized\n      partners (car rental companies, wholesalers, and fleet operators) for\n      posting, updating, and managing used-vehicle inventory. Requires\n      Carvana LLC authorization; the developer portal runs on Microsoft\n      Azure API Management.\n    humanURL: https://api-developer.carvana.com/\n    baseURL: https://api-developer.carvana.com\n    tags:\n      - Partner\n      - Inventory\n      - Authorized Access\n    properties:\n      - type: Portal\n        url: https://api-developer.carvana.com/\n      - type: Login\n        url: https://api-developer.carvana.com/signin\n      - type: Documentation\n        url: https://api-developer.carvana.com/\n      - type: TermsOfService\n        name: Carvana Property & Unauthorized Access Notice\n        url: https://api-developer.carvana.com/\n\
  \  - aid: carvana:collective-api\n    name: Carvana Collective API\n    description: >-\n      API surface supporting Carvana Collective partner-collaborative\n      workflows; access is restricted to authorized Carvana partners.\n    humanURL: https://api.collective.carvana.com/\n    baseURL: https://api.collective.carvana.com\n    tags:\n      - Partner\n      - Collective\n    properties:\n      - type: Documentation\n        url: https://api.collective.carvana.com/\n  - aid: carvana:aws-data-exchange\n    name: Carvana Car Sales Data (AWS Data Exchange)\n    description: >-\n      Carvana's used-car inventory and sales data product published on AWS\n      Data Exchange for direct subscription and data-warehouse delivery to\n      analytics, pricing, and market-research consumers.\n    humanURL: https://aws.amazon.com/marketplace/pp/prodview-y77x3t6zisn4w\n    tags:\n      - Data Product\n      - AWS Data Exchange\n      - Inventory\n    properties:\n      - type: Listing\n        url:\
  \ https://aws.amazon.com/marketplace/pp/prodview-y77x3t6zisn4w\n  - aid: carvana:partner-inventory-help\n    name: Carvana Partner Inventory Help Center\n    description: >-\n      Consumer-facing explainer describing how Carvana sources partner\n      inventory (rental fleets and other partners) into the buyer catalog.\n    humanURL: https://www.carvana.com/help/carvana-inventory/where-is-partner-inventory\n    tags:\n      - Partner\n      - Inventory\n      - Consumer\n    properties:\n      - type: Documentation\n        url: https://www.carvana.com/help/carvana-inventory/where-is-partner-inventory\ncommon:\n  - type: Website\n    url: https://www.carvana.com\n  - type: Portal\n    name: Carvana Developer Portal\n    url: https://api-developer.carvana.com/\n  - type: Login\n    url: https://api-developer.carvana.com/signin\n  - type: Help\n    url: https://www.carvana.com/help\n  - type: Sell\n    url: https://www.carvana.com/sell-car\n  - type: Finance\n    url: https://www.carvana.com/finance\n\
  \  - type: VendingMachines\n    url: https://www.carvana.com/vending-machine-locations\n  - type: About\n    url: https://www.carvana.com/company/about_us\n  - type: InvestorRelations\n    url: https://investors.carvana.com\n  - type: Careers\n    url: https://www.carvana.com/careers\n  - type: Contact\n    url: https://www.carvana.com/help/contact-us\n  - type: TermsOfService\n    url: https://www.carvana.com/terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.carvana.com/privacy-policy\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/carvana/refs/heads/main/apis.yml
tags:
- Automotive
- E-Commerce
- Used Cars
- Inventory
- Partner API
- Fortune 500
url: https://raw.githubusercontent.com/api-evangelist/carvana/refs/heads/main/apis.yml
use_cases: []
---
