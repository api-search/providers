---
api_count: 7
apis:
- description: Provides item-level product master data including SKU identifiers, descriptions, varietal and category metadata, and pointers to digital assets. Used by partners to keep distributor and retailer catal
  name: Product Items API
  slug: product
- description: Returns promotional bottle-shot imagery for Constellation Brands products in multiple formats (PNG, JPG) and resolutions for use on partner sites, e-commerce experiences, and printed materials.
  name: Bottle Shots API
  slug: bottle-shots
- description: Retrieves tasting-note documents for wine and spirits brands so partners can render or print structured tasting copy alongside bottle shots and pricing.
  name: Tasting Notes API
  slug: tasting-notes
- description: Delivers "hot sheets" containing critical-review scores, awards, and promotional copy that distributors use to merchandise Constellation brands at retail.
  name: Hot Sheets API
  slug: hot-sheets
- description: Provides point-of-sale shelf-talker artwork keyed to specific products and promotional periods.
  name: Shelf Talkers API
  slug: shelf-talkers
- description: Returns neck-hanger artwork that distributors and retailers attach to bottles for in-store merchandising and promotions.
  name: Neck Hangers API
  slug: neck-hangers
- description: Supplies cocktail and beverage recipes featuring Constellation brands so on-premise partners and digital experiences can surface branded drink ideas.
  name: Recipes API
  slug: recipes
common:
- title: ''
  type: Website
  url: https://www.cbrands.com/
- title: ''
  type: Developer Portal
  url: https://dev.cbrands.com/docs/
- title: ''
  type: GitHub Organization
  url: https://github.com/ConstellationBrands
- title: ''
  type: Investor Relations
  url: https://ir.cbrands.com/
- title: ''
  type: Careers
  url: https://careers.cbrands.com/
- title: ''
  type: Privacy Policy
  url: https://www.cbrands.com/privacy-notice
- title: ''
  type: Terms of Service
  url: https://www.cbrands.com/terms-of-use
created: '2026-03-21'
description: Constellation Brands is a Fortune 500 producer and marketer of beer, wine, and spirits brands such as Corona, Modelo, Robert Mondavi, and Casa Noble. Constellation publishes a partner-oriented API catalog at dev.cbrands.com that exposes product, brand, and digital-asset data (bottle shots, tasting notes, hot sheets, shelf talkers, neck hangers, recipes, and an items product API) to distributors, retailers, and on-premise partners. Most endpoints require an API key issued through the developer registration process.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-29'
name: Constellation Brands
skills: []
slug: constellation-brands
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: constellation-brands\nname: Constellation Brands\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/constellation-brands/refs/heads/main/apis.yml\ntags:\n  - Alcohol\n  - Beer\n  - Beverages\n  - Digital Assets\n  - Fortune 500\n  - Spirits\n  - Wine\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-21'\nmodified: '2026-04-29'\nposition: Consumer\nspecificationVersion: '0.19'\nx-type: company\ndescription: >-\n  Constellation Brands is a Fortune 500 producer and marketer of beer, wine,\n  and spirits brands such as Corona, Modelo, Robert Mondavi, and Casa Noble.\n  Constellation publishes a partner-oriented API catalog at dev.cbrands.com\n  that exposes product, brand, and digital-asset data (bottle shots, tasting\n  notes, hot sheets, shelf talkers, neck hangers, recipes, and an items\n  product API) to distributors, retailers, and on-premise partners. Most\n  endpoints require\
  \ an API key issued through the developer registration\n  process.\napis:\n  - aid: constellation-brands:product\n    name: Product Items API\n    tags:\n      - Catalog\n      - Items\n      - Products\n    humanURL: https://dev.cbrands.com/docs/\n    baseURL: https://api.cbrands.com/v3\n    properties:\n      - url: https://dev.cbrands.com/docs/\n        type: Documentation\n    description: >-\n      Provides item-level product master data including SKU identifiers,\n      descriptions, varietal and category metadata, and pointers to digital\n      assets. Used by partners to keep distributor and retailer catalogs in\n      sync with Constellation's source-of-truth data.\n  - aid: constellation-brands:bottle-shots\n    name: Bottle Shots API\n    tags:\n      - Bottle Shots\n      - Digital Assets\n      - Images\n    humanURL: https://dev.cbrands.com/docs/\n    baseURL: https://api.cbrands.com/api/1.0\n    properties:\n      - url: https://dev.cbrands.com/docs/\n        type: Documentation\n\
  \    description: >-\n      Returns promotional bottle-shot imagery for Constellation Brands\n      products in multiple formats (PNG, JPG) and resolutions for use on\n      partner sites, e-commerce experiences, and printed materials.\n  - aid: constellation-brands:tasting-notes\n    name: Tasting Notes API\n    tags:\n      - Documents\n      - Tasting Notes\n      - Wine\n    humanURL: https://dev.cbrands.com/docs/\n    baseURL: https://api.cbrands.com/api/1.0\n    properties:\n      - url: https://dev.cbrands.com/docs/\n        type: Documentation\n    description: >-\n      Retrieves tasting-note documents for wine and spirits brands so\n      partners can render or print structured tasting copy alongside bottle\n      shots and pricing.\n  - aid: constellation-brands:hot-sheets\n    name: Hot Sheets API\n    tags:\n      - Awards\n      - Documents\n      - Reviews\n    humanURL: https://dev.cbrands.com/docs/\n    baseURL: https://api.cbrands.com/api/1.0\n    properties:\n      -\
  \ url: https://dev.cbrands.com/docs/\n        type: Documentation\n    description: >-\n      Delivers \"hot sheets\" containing critical-review scores, awards, and\n      promotional copy that distributors use to merchandise Constellation\n      brands at retail.\n  - aid: constellation-brands:shelf-talkers\n    name: Shelf Talkers API\n    tags:\n      - Merchandising\n      - POS\n      - Retail\n    humanURL: https://dev.cbrands.com/docs/\n    baseURL: https://api.cbrands.com/api/1.0\n    properties:\n      - url: https://dev.cbrands.com/docs/\n        type: Documentation\n    description: >-\n      Provides point-of-sale shelf-talker artwork keyed to specific\n      products and promotional periods.\n  - aid: constellation-brands:neck-hangers\n    name: Neck Hangers API\n    tags:\n      - Merchandising\n      - POS\n      - Retail\n    humanURL: https://dev.cbrands.com/docs/\n    baseURL: https://api.cbrands.com/api/1.0\n    properties:\n      - url: https://dev.cbrands.com/docs/\n\
  \        type: Documentation\n    description: >-\n      Returns neck-hanger artwork that distributors and retailers attach to\n      bottles for in-store merchandising and promotions.\n  - aid: constellation-brands:recipes\n    name: Recipes API\n    tags:\n      - Cocktails\n      - Recipes\n    humanURL: https://dev.cbrands.com/docs/\n    baseURL: https://api.cbrands.com/api/1.0\n    properties:\n      - url: https://dev.cbrands.com/docs/\n        type: Documentation\n    description: >-\n      Supplies cocktail and beverage recipes featuring Constellation\n      brands so on-premise partners and digital experiences can surface\n      branded drink ideas.\ncommon:\n  - type: Website\n    url: https://www.cbrands.com/\n  - type: Developer Portal\n    url: https://dev.cbrands.com/docs/\n  - type: GitHub Organization\n    url: https://github.com/ConstellationBrands\n  - type: Investor Relations\n    url: https://ir.cbrands.com/\n  - type: Careers\n    url: https://careers.cbrands.com/\n\
  \  - type: Privacy Policy\n    url: https://www.cbrands.com/privacy-notice\n  - type: Terms of Service\n    url: https://www.cbrands.com/terms-of-use\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/constellation-brands/refs/heads/main/apis.yml
tags:
- Alcohol
- Beer
- Beverages
- Digital Assets
- Fortune 500
- Spirits
- Wine
url: https://raw.githubusercontent.com/api-evangelist/constellation-brands/refs/heads/main/apis.yml
use_cases: []
---
