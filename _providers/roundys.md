---
api_count: 4
api_specs:
- filename: Kroger-API-Spec-23c0b0b34f55c3d32d60fcb23de33a86.yaml
  format: yaml
  label: Kroger Product Catalog API
  slug: kroger-product-catalog-api
  spec_type: OpenAPI
  url: https://developer.kroger.com/assets/files/Kroger-API-Spec-23c0b0b34f55c3d32d60fcb23de33a86.yaml
apis:
- description: As a Kroger subsidiary, Roundy's stores (Pick 'n Save, Metro Market, Mariano's) are accessible through the Kroger Developer Platform product catalog API. The API enables searching and browsing product
  name: Kroger Product Catalog API
  slug: kroger-product-catalog-api
- description: The Kroger Store Locator API allows developers to find Pick 'n Save, Metro Market, and Mariano's store locations by geographic coordinates, ZIP code, or radius. Returns store details including address
  name: Kroger Store Locator API
  slug: kroger-stores-api
- description: The Kroger Cart API allows authenticated customers to add items directly to their Pick 'n Save, Metro Market, or Mariano's shopping cart for in-store pickup or delivery. Supports product quantity mana
  name: Kroger Cart and Checkout API
  slug: kroger-cart-api
- description: 'The Kroger Identity API provides OAuth 2.0-based authentication for Kroger customers including Roundy''s banner shoppers, enabling access to customer profiles, Plus Card loyalty data, digital coupons, '
  name: Kroger Identity and Loyalty API
  slug: kroger-identity-api
common:
- title: ''
  type: Website
  url: https://www.roundys.com
- title: ''
  type: Pick n Save
  url: https://www.picknsave.com
- title: ''
  type: Metro Market
  url: https://www.metromarket.net
- title: ''
  type: Marianos
  url: https://www.marianos.com
- title: ''
  type: Kroger Developer Platform
  url: https://developer.kroger.com/
- title: ''
  type: Vocabulary
  url: vocabulary/roundys-vocabulary.yml
- title: ''
  type: JSON-LD
  url: json-ld/roundys-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/roundys-store-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/roundys-store-structure.json
created: '2025-01-01'
description: 'Roundy''s, Inc. is a Midwest grocery retailer and wholly-owned subsidiary of The Kroger Co., founded in Milwaukee, Wisconsin in 1872. Roundy''s operates approximately 150 grocery stores under three retail banners: Pick ''n Save (106 locations throughout Wisconsin), Metro Market (premium Wisconsin grocery stores), and Mariano''s (44 Fresh Market locations throughout the Chicago area). As a Kroger subsidiary, Roundy''s leverages the Kroger developer platform and technology infrastructure including the Kroger API for product catalog, digital coupons, store locations, and loyalty program integrations.'
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Roundys Context
  property_count: 5
  slug: roundys-context
layout: provider
modified: '2026-05-02'
name: Roundy's
skills: []
slug: roundys
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: roundys\nname: Roundy's\ndescription: >-\n  Roundy's, Inc. is a Midwest grocery retailer and wholly-owned subsidiary of\n  The Kroger Co., founded in Milwaukee, Wisconsin in 1872. Roundy's operates\n  approximately 150 grocery stores under three retail banners: Pick 'n Save\n  (106 locations throughout Wisconsin), Metro Market (premium Wisconsin grocery\n  stores), and Mariano's (44 Fresh Market locations throughout the Chicago area).\n  As a Kroger subsidiary, Roundy's leverages the Kroger developer platform and\n  technology infrastructure including the Kroger API for product catalog, digital\n  coupons, store locations, and loyalty program integrations.\ntype: Index\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/roundys/refs/heads/main/apis.yml\ntags:\n  - Grocery\n  - Kroger\n  - Midwest\n  - Retail\n  - Supermarket\n  - Wisconsin\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: roundys:kroger-product-catalog-api\n\
  \    name: Kroger Product Catalog API\n    description: >-\n      As a Kroger subsidiary, Roundy's stores (Pick 'n Save, Metro Market,\n      Mariano's) are accessible through the Kroger Developer Platform product\n      catalog API. The API enables searching and browsing products by keyword,\n      brand, UPC, or department, and retrieving pricing, availability, and\n      location-specific inventory data for Roundy's banner stores.\n    humanURL: https://developer.kroger.com/reference/\n    properties:\n      - type: Documentation\n        url: https://developer.kroger.com/reference/\n      - type: OpenAPI\n        url: https://developer.kroger.com/assets/files/Kroger-API-Spec-23c0b0b34f55c3d32d60fcb23de33a86.yaml\n    tags:\n      - Grocery\n      - Inventory\n      - Product Catalog\n      - Retail\n  - aid: roundys:kroger-stores-api\n    name: Kroger Store Locator API\n    description: >-\n      The Kroger Store Locator API allows developers to find Pick 'n Save,\n      Metro Market,\
  \ and Mariano's store locations by geographic coordinates,\n      ZIP code, or radius. Returns store details including address, hours,\n      departments, phone number, and available services (pharmacy, fuel,\n      click-and-collect).\n    humanURL: https://developer.kroger.com/reference/\n    properties:\n      - type: Documentation\n        url: https://developer.kroger.com/reference/\n    tags:\n      - Grocery\n      - Location\n      - Retail\n      - Store Locator\n  - aid: roundys:kroger-cart-api\n    name: Kroger Cart and Checkout API\n    description: >-\n      The Kroger Cart API allows authenticated customers to add items directly\n      to their Pick 'n Save, Metro Market, or Mariano's shopping cart for\n      in-store pickup or delivery. Supports product quantity management and\n      shopping list integrations through the Kroger customer identity platform.\n    humanURL: https://developer.kroger.com/reference/\n    properties:\n      - type: Documentation\n        url: https://developer.kroger.com/reference/\n\
  \    tags:\n      - Cart\n      - Checkout\n      - Grocery\n      - Retail\n      - Shopping\n  - aid: roundys:kroger-identity-api\n    name: Kroger Identity and Loyalty API\n    description: >-\n      The Kroger Identity API provides OAuth 2.0-based authentication for\n      Kroger customers including Roundy's banner shoppers, enabling access to\n      customer profiles, Plus Card loyalty data, digital coupons, purchase\n      history, and personalized offers.\n    humanURL: https://developer.kroger.com/reference/\n    properties:\n      - type: Documentation\n        url: https://developer.kroger.com/reference/\n    tags:\n      - Authentication\n      - Grocery\n      - Identity\n      - Loyalty\n      - OAuth\ncommon:\n  - type: Website\n    url: https://www.roundys.com\n  - type: Pick n Save\n    url: https://www.picknsave.com\n  - type: Metro Market\n    url: https://www.metromarket.net\n  - type: Marianos\n    url: https://www.marianos.com\n  - type: Kroger Developer Platform\n\
  \    url: https://developer.kroger.com/\n  - type: Vocabulary\n    url: vocabulary/roundys-vocabulary.yml\n  - type: JSON-LD\n    url: json-ld/roundys-context.jsonld\n  - type: JSONSchema\n    url: json-schema/roundys-store-schema.json\n  - type: JSONStructure\n    url: json-structure/roundys-store-structure.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/roundys/refs/heads/main/apis.yml
tags:
- Grocery
- Kroger
- Midwest
- Retail
- Supermarket
- Wisconsin
url: https://raw.githubusercontent.com/api-evangelist/roundys/refs/heads/main/apis.yml
use_cases: []
---
