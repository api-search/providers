---
api_count: 3
api_specs:
- filename: cardtonic-openapi.yml
  format: yaml
  label: Cardtonic Gift Card Developer API
  slug: gift-card-developer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cardtonic/refs/heads/main/openapi/cardtonic-openapi.yml
apis:
- description: The Cardtonic Gift Card Developer API enables merchants and platforms to integrate gift card services into their websites, mobile apps, and point-of-sale systems. The API exposes a catalog of more tha
  name: Cardtonic Gift Card Developer API
  slug: gift-card-developer-api
- description: Cardtonic Virtual Dollar Cards are user-facing USD-denominated cards that let African customers pay merchants that accept Visa/Mastercard globally. The product is currently consumed through the Cardto
  name: Cardtonic Virtual Dollar Card
  slug: virtual-dollar-card
- description: Cardtonic Bill Payments cover airtime top-ups, mobile data, electricity, TV subscriptions, and betting wallets across more than 100 countries, consumed through the Cardtonic app and dashboard. Partner
  name: Cardtonic Bill Payments
  slug: bill-payments
common:
- title: ''
  type: Website
  url: https://cardtonic.com/
- title: ''
  type: Developer
  url: https://cardtonic.com/developer
- title: ''
  type: Dashboard
  url: https://dashboard.cardtonic.com/
- title: ''
  type: Login
  url: https://cardtonic.com/login
- title: ''
  type: Sign Up
  url: https://cardtonic.com/register
- title: ''
  type: About
  url: https://cardtonic.com/about
- title: ''
  type: Blog
  url: https://cardtonic.com/blog
- title: ''
  type: FAQ
  url: https://cardtonic.com/faq
- title: ''
  type: Contact
  url: https://cardtonic.com/contact
- title: ''
  type: Terms of Service
  url: https://cardtonic.com/terms
- title: ''
  type: Privacy Policy
  url: https://cardtonic.com/privacy
- title: ''
  type: X
  url: https://x.com/cardtonic
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/cardtonic
- title: ''
  type: Instagram
  url: https://www.instagram.com/cardtonic/
created: '2025-02-08'
description: Cardtonic is an Africa-focused fintech platform that lets users trade gift cards (sell unused cards for cash and buy over 14,000 local and international gift cards), issue virtual dollar cards, pay bills (airtime, data, electricity, TV, betting), purchase eSIMs in 140+ countries, and shop for gadgets through its Just Gadgets storefront. Cardtonic supports Naira and Cedi settlement for users in Nigeria and Ghana, holds PCI DSS certification, and operates under Nigeria Data Protection Commission (NDPC) oversight. For businesses, Cardtonic offers a Gift Card Developer API (currently waitlist-only) that lets merchants embed gift card purchasing, sales, bulk ordering, inventory, and redemption into websites, mobile apps, and point-of-sale systems.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Cardtonic
skills: []
slug: cardtonic
solutions: []
source_filename: apis.yml
source_yaml: "aid: cardtonic\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cardtonic/refs/heads/main/apis.yml\nname: Cardtonic\ndescription: >-\n  Cardtonic is an Africa-focused fintech platform that lets users trade\n  gift cards (sell unused cards for cash and buy over 14,000 local and\n  international gift cards), issue virtual dollar cards, pay bills\n  (airtime, data, electricity, TV, betting), purchase eSIMs in 140+\n  countries, and shop for gadgets through its Just Gadgets storefront.\n  Cardtonic supports Naira and Cedi settlement for users in Nigeria and\n  Ghana, holds PCI DSS certification, and operates under Nigeria Data\n  Protection Commission (NDPC) oversight. For businesses, Cardtonic\n  offers a Gift Card Developer API (currently waitlist-only) that lets\n  merchants embed gift card purchasing, sales, bulk ordering, inventory,\n  and redemption into websites, mobile apps, and point-of-sale systems.\ntype: Index\nx-type: company\nposition: Consumer\naccess:\
  \ 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Africa\n  - Bill Payments\n  - eSIM\n  - Finance\n  - Fintech\n  - Gift Cards\n  - Ghana\n  - Nigeria\n  - Payments\n  - Virtual Dollar Cards\ncreated: '2025-02-08'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: cardtonic:gift-card-developer-api\n    name: Cardtonic Gift Card Developer API\n    description: >-\n      The Cardtonic Gift Card Developer API enables merchants and\n      platforms to integrate gift card services into their websites,\n      mobile apps, and point-of-sale systems. The API exposes a\n      catalog of more than 14,000 gift cards for purchase and sale,\n      bulk ordering with instant reporting, inventory and redemption\n      management, and branding/customization hooks. As of 2026 the\n      API is in waitlist mode and developer credentials are issued\n      through Cardtonic on request.\n    humanURL: https://cardtonic.com/developer\n\
  \    tags:\n      - Gift Cards\n      - Fintech\n      - Payments\n    properties:\n      - url: https://cardtonic.com/developer\n        type: Documentation\n      - url: https://cardtonic.com/developer\n        type: Signup\n      - url: openapi/cardtonic-openapi.yml\n        type: OpenAPI\n    x-features:\n      - Catalog of 14,000+ local and international gift cards\n      - Purchase and sale flows for merchant integration\n      - Bulk ordering with instant reporting\n      - Inventory and redemption management\n      - Branding/white-label customization hooks\n      - Web, mobile, and POS integration patterns\n      - Waitlist-based onboarding\n    x-use-cases:\n      - Rewards and employee recognition platforms\n      - Remittance and cross-border cash-out flows\n      - Neobank and wallet gift card storefronts\n      - Retail POS gift card upsell and resale\n      - Loyalty and referral programs\n      - Corporate procurement and bulk gifting\n  - aid: cardtonic:virtual-dollar-card\n\
  \    name: Cardtonic Virtual Dollar Card\n    description: >-\n      Cardtonic Virtual Dollar Cards are user-facing USD-denominated\n      cards that let African customers pay merchants that accept\n      Visa/Mastercard globally. The product is currently consumed\n      through the Cardtonic app and dashboard; programmatic access\n      for partners is available on request alongside the Gift Card\n      Developer API waitlist.\n    humanURL: https://cardtonic.com/virtual-dollar-card\n    tags:\n      - Cards\n      - Fintech\n      - Virtual Dollar Cards\n    properties:\n      - url: https://cardtonic.com/virtual-dollar-card\n        type: Documentation\n    x-features:\n      - USD-denominated virtual cards for online spending\n      - Load and settle in Naira/Cedis\n      - App and dashboard controls for issuance and spend\n      - PCI DSS certified issuance\n    x-use-cases:\n      - Cross-border subscription payments (SaaS, streaming)\n      - Online shopping on global merchants\n\
  \      - Travel and ad-platform spend for SMBs\n      - Remote worker payouts\n  - aid: cardtonic:bill-payments\n    name: Cardtonic Bill Payments\n    description: >-\n      Cardtonic Bill Payments cover airtime top-ups, mobile data,\n      electricity, TV subscriptions, and betting wallets across more\n      than 100 countries, consumed through the Cardtonic app and\n      dashboard. Partner access is available on request.\n    humanURL: https://cardtonic.com/\n    tags:\n      - Bill Payments\n      - Fintech\n      - Payments\n    properties:\n      - url: https://cardtonic.com/\n        type: Documentation\n    x-features:\n      - Airtime and mobile data top-ups\n      - Electricity and TV subscription payments\n      - Betting wallet funding\n      - 100+ country coverage\n      - App, web, and dashboard channels\n    x-use-cases:\n      - Consumer bill-payment super-app scenarios\n      - Diaspora bill pay for family members\n      - Agent-banking and mobile-money integrations\n\
  common:\n  - type: Website\n    url: https://cardtonic.com/\n  - type: Developer\n    url: https://cardtonic.com/developer\n  - type: Dashboard\n    url: https://dashboard.cardtonic.com/\n  - type: Login\n    url: https://cardtonic.com/login\n  - type: Sign Up\n    url: https://cardtonic.com/register\n  - type: About\n    url: https://cardtonic.com/about\n  - type: Blog\n    url: https://cardtonic.com/blog\n  - type: FAQ\n    url: https://cardtonic.com/faq\n  - type: Contact\n    url: https://cardtonic.com/contact\n  - type: Terms of Service\n    url: https://cardtonic.com/terms\n  - type: Privacy Policy\n    url: https://cardtonic.com/privacy\n  - type: X\n    url: https://x.com/cardtonic\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/cardtonic\n  - type: Instagram\n    url: https://www.instagram.com/cardtonic/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cardtonic/refs/heads/main/apis.yml
tags:
- Africa
- Bill Payments
- eSIM
- Finance
- Fintech
- Gift Cards
- Ghana
- Nigeria
- Payments
- Virtual Dollar Cards
url: https://raw.githubusercontent.com/api-evangelist/cardtonic/refs/heads/main/apis.yml
use_cases: []
---
