---
api_count: 3
apis:
- description: The CarMax Store Locations API, discussed publicly on the CarMax Engineering Blog, exposes details about all CarMax store locations including addresses, hours, services offered, and geographic metadat
  name: CarMax Store Locations API
  slug: store-locations-api
- description: 'The CarMax Vehicle Inventory API exposes details about all used vehicles currently in CarMax''s nationwide inventory, including year/make/model, trim, mileage, price, exterior and interior attributes, '
  name: CarMax Vehicle Inventory API
  slug: vehicle-inventory-api
- description: The CarMax Vehicle Search Server-Driven UI API controls the search filters and list layouts presented across carmax.com and CarMax's mobile apps. It was rewritten approximately three years prior to Ma
  name: CarMax Vehicle Search Server-Driven UI API
  slug: vehicle-search-sdui-api
common:
- title: ''
  type: Website
  url: https://www.carmax.com/
- title: ''
  type: Stores
  url: https://www.carmax.com/stores
- title: ''
  type: Cars
  url: https://www.carmax.com/cars
- title: ''
  type: Finance
  url: https://www.carmax.com/finance
- title: ''
  type: Sell Your Car
  url: https://www.carmax.com/sell-my-car
- title: ''
  type: Engineering Blog
  url: https://medium.com/carmax-engineering-blog
- title: ''
  type: Careers
  url: https://jobs.carmax.com/
- title: ''
  type: Investor Relations
  url: https://investors.carmax.com/
- title: ''
  type: Contact
  url: https://www.carmax.com/customer-service
- title: ''
  type: Terms of Service
  url: https://www.carmax.com/terms
- title: ''
  type: Privacy Policy
  url: https://www.carmax.com/privacy
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/carmax
- title: ''
  type: X
  url: https://x.com/CarMax
- title: ''
  type: Facebook
  url: https://www.facebook.com/CarMax
created: '2026-03-21'
description: 'CarMax (NYSE: KMX) is the largest retailer of used cars in the United States, operating an omnichannel business that spans brick-and-mortar stores, carmax.com online purchasing, home delivery, financing, appraisals, and trade-ins. CarMax does not publish a public developer portal, but its engineering organization operates an extensive internal API program built around distinct API roles (Data Access Layer, Business Logic Layer, Server-Driven UI, Backend for Frontend). Public-facing APIs documented by the CarMax Engineering Blog include a Store Locations API and a Vehicle Inventory API, and CarMax has publicly discussed a Server-Driven UI API that controls vehicle search filters across web and mobile. Partner and syndication integrations are handled case by case rather than through a self-service portal.'
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: CarMax
skills: []
slug: carmax
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: carmax\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/carmax/refs/heads/main/apis.yml\nname: CarMax\ndescription: >-\n  CarMax (NYSE: KMX) is the largest retailer of used cars in the\n  United States, operating an omnichannel business that spans\n  brick-and-mortar stores, carmax.com online purchasing, home\n  delivery, financing, appraisals, and trade-ins. CarMax does not\n  publish a public developer portal, but its engineering organization\n  operates an extensive internal API program built around distinct\n  API roles (Data Access Layer, Business Logic Layer, Server-Driven\n  UI, Backend for Frontend). Public-facing APIs documented by the\n  CarMax Engineering Blog include a Store Locations API and a\n  Vehicle Inventory API, and CarMax has publicly discussed a\n  Server-Driven UI API that controls vehicle search filters across\n  web and mobile. Partner and syndication integrations are handled\n  case by case rather than through a self-service portal.\n\
  type: Index\nx-type: company\nposition: Consumer\naccess: Partner\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Auto Financing\n  - Auto Retail\n  - Appraisals\n  - Automotive\n  - Omnichannel\n  - Retail\n  - Server-Driven UI\n  - Used Cars\n  - Vehicle Inventory\n  - VIN Lookup\ncreated: '2026-03-21'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: carmax:store-locations-api\n    name: CarMax Store Locations API\n    description: >-\n      The CarMax Store Locations API, discussed publicly on the\n      CarMax Engineering Blog, exposes details about all CarMax store\n      locations including addresses, hours, services offered, and\n      geographic metadata. It is consumed primarily by carmax.com,\n      the CarMax mobile app, and CarMax's digital marketing and SEO\n      systems. The API is not offered as a self-service product to\n      third parties.\n    humanURL: https://www.carmax.com/stores\n    tags:\n  \
  \    - Auto Retail\n      - Store Locator\n    properties:\n      - url: https://www.carmax.com/stores\n        type: Documentation\n      - url: https://medium.com/carmax-engineering-blog\n        type: Engineering Blog\n    x-features:\n      - Address, hours, and services per store\n      - Geographic metadata for mapping\n      - Used as a source of truth across CarMax channels\n    x-use-cases:\n      - Store locator on carmax.com and mobile\n      - SEO and local-landing-page generation\n      - Internal operations dashboards\n  - aid: carmax:vehicle-inventory-api\n    name: CarMax Vehicle Inventory API\n    description: >-\n      The CarMax Vehicle Inventory API exposes details about all\n      used vehicles currently in CarMax's nationwide inventory,\n      including year/make/model, trim, mileage, price, exterior and\n      interior attributes, photos, and stock number. The API powers\n      carmax.com's search experience and the Vehicle Detail Page.\n      It is consumed internally\
  \ and surfaced to customers through\n      CarMax's own products rather than opened as a public partner\n      feed.\n    humanURL: https://www.carmax.com/cars\n    tags:\n      - Auto Retail\n      - Automotive\n      - Used Cars\n      - Vehicle Inventory\n    properties:\n      - url: https://www.carmax.com/cars\n        type: Documentation\n      - url: https://medium.com/carmax-engineering-blog/api-roles-aec7999c095c\n        type: Engineering Blog\n    x-features:\n      - Nationwide used-vehicle inventory\n      - Year/make/model/trim, mileage, price, stock number\n      - Exterior, interior, and photo metadata\n      - Powers carmax.com search and VDP\n    x-use-cases:\n      - Online vehicle search and listing pages\n      - Home delivery and store-transfer eligibility\n      - Price and market analytics\n      - Third-party automotive marketplaces (via syndication agreements)\n  - aid: carmax:vehicle-search-sdui-api\n    name: CarMax Vehicle Search Server-Driven UI API\n    description:\
  \ >-\n      The CarMax Vehicle Search Server-Driven UI API controls the\n      search filters and list layouts presented across carmax.com\n      and CarMax's mobile apps. It was rewritten approximately three\n      years prior to March 2026 and is an example of a Server-Driven\n      UI pattern where the back end determines which filters and\n      controls render on the client. It is an internal API, not\n      published for external developers.\n    humanURL: https://www.carmax.com/cars\n    tags:\n      - Auto Retail\n      - Omnichannel\n      - Server-Driven UI\n    properties:\n      - url: https://medium.com/carmax-engineering-blog/api-roles-aec7999c095c\n        type: Engineering Blog\n    x-features:\n      - Server-Driven UI filter and layout payloads\n      - Consistent web and mobile experience\n      - Back-end controlled A/B testing and rollout\n    x-use-cases:\n      - Unified search UX across channels\n      - Rapid filter experimentation\n      - Per-market and per-user\
  \ personalization\ncommon:\n  - type: Website\n    url: https://www.carmax.com/\n  - type: Stores\n    url: https://www.carmax.com/stores\n  - type: Cars\n    url: https://www.carmax.com/cars\n  - type: Finance\n    url: https://www.carmax.com/finance\n  - type: Sell Your Car\n    url: https://www.carmax.com/sell-my-car\n  - type: Engineering Blog\n    url: https://medium.com/carmax-engineering-blog\n  - type: Careers\n    url: https://jobs.carmax.com/\n  - type: Investor Relations\n    url: https://investors.carmax.com/\n  - type: Contact\n    url: https://www.carmax.com/customer-service\n  - type: Terms of Service\n    url: https://www.carmax.com/terms\n  - type: Privacy Policy\n    url: https://www.carmax.com/privacy\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/carmax\n  - type: X\n    url: https://x.com/CarMax\n  - type: Facebook\n    url: https://www.facebook.com/CarMax\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/carmax/refs/heads/main/apis.yml
tags:
- Auto Financing
- Auto Retail
- Appraisals
- Automotive
- Omnichannel
- Retail
- Server-Driven UI
- Used Cars
- Vehicle Inventory
- VIN Lookup
url: https://raw.githubusercontent.com/api-evangelist/carmax/refs/heads/main/apis.yml
use_cases: []
---
