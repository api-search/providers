---
api_count: 2
apis:
- description: Sheetz Distribution Services EDI and API integration capabilities enable suppliers and trading partners to exchange electronic data interchange documents including purchase orders, invoices, advance s
  name: Sheetz EDI Integration
  slug: sheetz-edi-integration
- description: The Sheetz Rewards loyalty platform powered by Ignite Retail Technology provides a unified loyalty engine with advanced data insights and integration across point of sale, mobile, and digital channels
  name: Sheetz Loyalty and Rewards API
  slug: sheetz-loyalty-api
common:
- title: ''
  type: Website
  url: https://www.sheetz.com
- title: ''
  type: Loyalty Program
  url: https://www.sheetz.com/mySheetz
- title: ''
  type: EDI Integration
  url: https://www.b2bgateway.net/trading-partner/sheetz-distribution-services/
- title: ''
  type: Careers
  url: https://www.sheetz.com/careers
- title: ''
  type: Privacy Policy
  url: https://www.sheetz.com/legal/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.sheetz.com/legal/terms-of-use
- title: ''
  type: GitHub Organization
  url: https://github.com/sheetz
created: '2025-01-01'
description: Sheetz, Inc. is an American chain of convenience stores and coffee shops headquartered in Altoona, Pennsylvania. Operating more than 800 company-owned stores across Pennsylvania, West Virginia, Maryland, Ohio, Virginia, North Carolina, and Michigan, Sheetz is one of the largest convenience store chains in the United States. The company offers fuel, food service, coffee, and retail products, supported by a mobile app for ordering, rewards, and store locator services. Sheetz provides B2B EDI and API integration capabilities for suppliers and distribution partners.
features:
- description: Order ahead through the Sheetz mobile app for food, drinks, and fuel.
  name: Mobile Ordering
- description: Earn and redeem points through the MySheetz Card loyalty program powered by Ignite Retail Technology.
  name: Loyalty Rewards
- description: Pay via mobile app at the pump and in-store with integrated digital wallet support.
  name: Digital Payments
- description: Find nearby Sheetz locations, hours, services, and amenities via API or mobile app.
  name: Store Locator
- description: B2B EDI integration for suppliers covering purchase orders, invoices, and advance ship notices.
  name: EDI Integration
- description: Access current fuel prices across Sheetz locations for integration with third-party mapping and fleet services.
  name: Fuel Price API
image: https://upload.wikimedia.org/wikipedia/commons/thumb/8/8f/Sheetz_logo.svg/2560px-Sheetz_logo.svg.png
integrations:
- description: Loyalty platform powering MySheetz Rewards with unified data insights across POS, mobile, and digital.
  name: Ignite Retail Technology
- description: Third-party EDI provider enabling supplier connectivity to Sheetz Distribution Services.
  name: TrueCommerce B2BGateway
- description: POS and payment terminal integration at Sheetz store locations.
  name: Verifone
jsonld:
- class_count: 4
  name: Sheetz Context
  property_count: 20
  slug: sheetz-context
layout: provider
modified: '2026-05-02'
name: Sheetz
skills: []
slug: sheetz
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sheetz\nurl: https://raw.githubusercontent.com/api-evangelist/sheetz/refs/heads/main/apis.yml\napis:\n  - aid: sheetz:sheetz-edi-integration\n    name: Sheetz EDI Integration\n    tags:\n      - B2B\n      - EDI\n      - Supply Chain\n      - Retail\n    humanURL: https://www.b2bgateway.net/trading-partner/sheetz-distribution-services/\n    properties:\n      - url: https://www.b2bgateway.net/trading-partner/sheetz-distribution-services/\n        type: Documentation\n    description: >-\n      Sheetz Distribution Services EDI and API integration capabilities enable\n      suppliers and trading partners to exchange electronic data interchange\n      documents including purchase orders, invoices, advance ship notices, and\n      inventory feeds with Sheetz enterprise systems. Supported via third-party\n      EDI providers and direct API connections.\n  - aid: sheetz:sheetz-loyalty-api\n    name: Sheetz Loyalty and Rewards API\n    tags:\n      - Loyalty\n      - Rewards\n\
  \      - Mobile\n      - Retail\n    humanURL: https://www.sheetz.com/mySheetz\n    properties:\n      - url: https://www.sheetz.com/mySheetz\n        type: Documentation\n    description: >-\n      The Sheetz Rewards loyalty platform powered by Ignite Retail Technology\n      provides a unified loyalty engine with advanced data insights and\n      integration across point of sale, mobile, and digital channels. Enables\n      partners to access customer rewards, offers, and engagement data through\n      API-based integrations.\nname: Sheetz\ntags:\n  - Convenience Store\n  - Energy\n  - Food Service\n  - Fortune 500\n  - Fuel\n  - Retail\ntype: Contract\nimage: https://upload.wikimedia.org/wikipedia/commons/thumb/8/8f/Sheetz_logo.svg/2560px-Sheetz_logo.svg.png\naccess: 3rd-Party\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nposition: Consumer\ndescription: >-\n  Sheetz, Inc. is an American chain of convenience stores and coffee shops\n  headquartered in Altoona, Pennsylvania. Operating\
  \ more than 800 company-owned\n  stores across Pennsylvania, West Virginia, Maryland, Ohio, Virginia, North\n  Carolina, and Michigan, Sheetz is one of the largest convenience store chains\n  in the United States. The company offers fuel, food service, coffee, and\n  retail products, supported by a mobile app for ordering, rewards, and store\n  locator services. Sheetz provides B2B EDI and API integration capabilities for\n  suppliers and distribution partners.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - url: https://www.sheetz.com\n    type: Website\n  - url: https://www.sheetz.com/mySheetz\n    type: Loyalty Program\n  - url: https://www.b2bgateway.net/trading-partner/sheetz-distribution-services/\n    type: EDI Integration\n  - url: https://www.sheetz.com/careers\n    type: Careers\n  - url: https://www.sheetz.com/legal/privacy-policy\n    type: Privacy Policy\n  - url: https://www.sheetz.com/legal/terms-of-use\n    type:\
  \ Terms of Service\n  - url: https://github.com/sheetz\n    type: GitHub Organization\n  - type: Features\n    data:\n      - name: Mobile Ordering\n        description: Order ahead through the Sheetz mobile app for food, drinks, and fuel.\n      - name: Loyalty Rewards\n        description: Earn and redeem points through the MySheetz Card loyalty program powered by Ignite Retail Technology.\n      - name: Digital Payments\n        description: Pay via mobile app at the pump and in-store with integrated digital wallet support.\n      - name: Store Locator\n        description: Find nearby Sheetz locations, hours, services, and amenities via API or mobile app.\n      - name: EDI Integration\n        description: B2B EDI integration for suppliers covering purchase orders, invoices, and advance ship notices.\n      - name: Fuel Price API\n        description: Access current fuel prices across Sheetz locations for integration with third-party mapping and fleet services.\n  - type: UseCases\n\
  \    data:\n      - name: Supplier Integration\n        description: Connect supplier ERP systems to Sheetz distribution and ordering workflows via EDI.\n      - name: Fleet Fueling\n        description: Integrate Sheetz fuel pricing and payment data into fleet management systems.\n      - name: Loyalty Platform Integration\n        description: Connect third-party apps and services to the MySheetz Rewards loyalty engine.\n      - name: Mobile Commerce\n        description: Build integrations for mobile ordering, payment, and pickup at Sheetz locations.\n  - type: Integrations\n    data:\n      - name: Ignite Retail Technology\n        description: Loyalty platform powering MySheetz Rewards with unified data insights across POS, mobile, and digital.\n      - name: TrueCommerce B2BGateway\n        description: Third-party EDI provider enabling supplier connectivity to Sheetz Distribution Services.\n      - name: Verifone\n        description: POS and payment terminal integration at Sheetz\
  \ store locations.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sheetz/refs/heads/main/apis.yml
tags:
- Convenience Store
- Energy
- Food Service
- Fortune 500
- Fuel
- Retail
url: https://raw.githubusercontent.com/api-evangelist/sheetz/refs/heads/main/apis.yml
use_cases:
- description: Connect supplier ERP systems to Sheetz distribution and ordering workflows via EDI.
  name: Supplier Integration
- description: Integrate Sheetz fuel pricing and payment data into fleet management systems.
  name: Fleet Fueling
- description: Connect third-party apps and services to the MySheetz Rewards loyalty engine.
  name: Loyalty Platform Integration
- description: Build integrations for mobile ordering, payment, and pickup at Sheetz locations.
  name: Mobile Commerce
---
