---
api_count: 3
apis:
- description: 'Internal API platform built on MuleSoft Anypoint that exposes reusable experience, process, and system APIs across The Coca-Cola Company''s bottling, marketing, ecommerce, and supply-chain operations. '
  name: Coca-Cola Internal API Platform
  slug: coca-cola-internal-api-platform
- description: Historical Coca-Cola Enterprises (CCE) Product API that exposed product catalog metadata and was published through an I/O Docs portal at developer.cokecce.com. Following the 2016 reorganization that c
  name: Coca-Cola Enterprises Product API (Legacy)
  slug: coca-cola-enterprises-product-api-legacy
- description: Historical Coca-Cola Enterprises (CCE) Location API that exposed Coca-Cola product availability and bottler/distribution location data. No longer maintained as a public developer program after the reo
  name: Coca-Cola Enterprises Location API (Legacy)
  slug: coca-cola-enterprises-location-api-legacy
common:
- title: ''
  type: Website
  url: https://www.coca-colacompany.com/
- title: ''
  type: Brands
  url: https://www.coca-colacompany.com/brands
- title: ''
  type: Innovation
  url: https://www.coca-colacompany.com/innovation
- title: ''
  type: Investors
  url: https://investors.coca-colacompany.com/
- title: ''
  type: Press
  url: https://www.coca-colacompany.com/media-center
- title: ''
  type: Sustainability
  url: https://www.coca-colacompany.com/sustainability
- title: ''
  type: Careers
  url: https://www.coca-colacompany.com/careers
- title: ''
  type: PrivacyPolicy
  url: https://www.coca-colacompany.com/policies-and-practices/privacy-policy
- title: ''
  type: TermsOfService
  url: https://www.coca-colacompany.com/policies-and-practices/terms-of-use
created: '2026-03-21'
description: The Coca-Cola Company is the world's largest non-alcoholic beverage company, owning and marketing more than 200 brands across sparkling soft drinks, water, hydration, sports, coffee, tea, juice, dairy, and plant-based drinks. The company sells its products in more than 200 countries through a bottling and distribution partner network. While Coca-Cola does not currently publish a broadly available public REST API, it is a heavy enterprise API consumer running an internal API program on MuleSoft that connects ERP, manufacturing, distribution, retail, marketing, and consumer engagement systems through a Center for Enablement (C4E) model. Historical Coca-Cola Enterprises (CCE) Product and Location APIs at developer.cokecce.com are no longer maintained as a public-facing developer program.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-26'
name: The Coca-Cola Company
skills: []
slug: coca-cola
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: coca-cola\nurl: https://raw.githubusercontent.com/api-evangelist/coca-cola/refs/heads/main/apis.yml\nname: The Coca-Cola Company\ntags:\n  - Beverages\n  - Beverage Manufacturer\n  - Consumer Goods\n  - Distribution\n  - Retail\n  - Supply Chain\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nx-type: company\ncreated: '2026-03-21'\nmodified: '2026-04-26'\nposition: Consumer\ndescription: >-\n  The Coca-Cola Company is the world's largest non-alcoholic beverage company,\n  owning and marketing more than 200 brands across sparkling soft drinks,\n  water, hydration, sports, coffee, tea, juice, dairy, and plant-based drinks.\n  The company sells its products in more than 200 countries through a\n  bottling and distribution partner network. While Coca-Cola does not currently\n  publish a broadly available public REST API, it is a heavy enterprise API\n  consumer running an internal API program on MuleSoft that\
  \ connects ERP,\n  manufacturing, distribution, retail, marketing, and consumer engagement\n  systems through a Center for Enablement (C4E) model. Historical Coca-Cola\n  Enterprises (CCE) Product and Location APIs at developer.cokecce.com are no\n  longer maintained as a public-facing developer program.\napis:\n  - aid: coca-cola:coca-cola-internal-api-platform\n    name: Coca-Cola Internal API Platform\n    tags:\n      - API Management\n      - Enterprise Integration\n      - Microservices\n      - MuleSoft\n    humanURL: https://www.mulesoft.com/webinars/api/evaluation-to-implementation-coca-cola-company-journey\n    properties:\n      - url: https://www.mulesoft.com/webinars/api/how-coca-cola-accelerates\n        type: CaseStudy\n      - url: https://www.mulesoft.com/webinars/api/evaluation-to-implementation-coca-cola-company-journey\n        type: CaseStudy\n    description: >-\n      Internal API platform built on MuleSoft Anypoint that exposes reusable\n      experience, process,\
  \ and system APIs across The Coca-Cola Company's\n      bottling, marketing, ecommerce, and supply-chain operations. Governed\n      by a central Center for Enablement (C4E) team that defines design\n      standards, security policies, and reuse metrics. Not publicly accessible\n      but a frequently cited reference architecture for Fortune 50 API\n      programs.\n    x-features:\n      - API-led connectivity (system, process, experience APIs)\n      - Center for Enablement (C4E) governance\n      - Reusable assets across LOBs and bottling partners\n      - OAuth 2.0 / API key based access for partners\n    x-use-cases:\n      - Bottler integrations\n      - Retail and route-to-market data exchange\n      - Consumer engagement (Freestyle, loyalty)\n      - Supply-chain visibility and demand planning\n  - aid: coca-cola:coca-cola-enterprises-product-api-legacy\n    name: Coca-Cola Enterprises Product API (Legacy)\n    tags:\n      - Catalog\n      - Legacy\n      - Products\n    humanURL:\
  \ http://developer.cokecce.com/docs/Product_API\n    properties:\n      - url: http://developer.cokecce.com/io-docs\n        type: Documentation\n      - url: http://developer.cokecce.com/docs/Product_API\n        type: Documentation\n      - url: http://developer.cokecce.com/API_Terms_of_Use\n        type: TermsOfService\n    description: >-\n      Historical Coca-Cola Enterprises (CCE) Product API that exposed product\n      catalog metadata and was published through an I/O Docs portal at\n      developer.cokecce.com. Following the 2016 reorganization that created\n      Coca-Cola European Partners (now Coca-Cola Europacific Partners), the\n      CCE developer portal is no longer maintained as a public developer\n      program. Documented here for archival reference only.\n    x-features:\n      - Product catalog lookup\n      - I/O Docs interactive documentation\n      - API key authentication\n    x-use-cases:\n      - Retail merchandising integrations (historical)\n      - Product\
  \ information sharing with partners (historical)\n  - aid: coca-cola:coca-cola-enterprises-location-api-legacy\n    name: Coca-Cola Enterprises Location API (Legacy)\n    tags:\n      - Geolocation\n      - Legacy\n      - Locations\n    humanURL: http://developer.cokecce.com/docs/Location\n    properties:\n      - url: http://developer.cokecce.com/docs/Location\n        type: Documentation\n    description: >-\n      Historical Coca-Cola Enterprises (CCE) Location API that exposed\n      Coca-Cola product availability and bottler/distribution location data.\n      No longer maintained as a public developer program after the\n      reorganization into Coca-Cola European Partners. Documented here for\n      archival reference only.\n    x-features:\n      - Location and territory lookup\n      - Bottler/distributor metadata\n    x-use-cases:\n      - Field merchandising apps (historical)\n      - Distribution territory visualization (historical)\ncommon:\n  - type: Website\n    url: https://www.coca-colacompany.com/\n\
  \  - type: Brands\n    url: https://www.coca-colacompany.com/brands\n  - type: Innovation\n    url: https://www.coca-colacompany.com/innovation\n  - type: Investors\n    url: https://investors.coca-colacompany.com/\n  - type: Press\n    url: https://www.coca-colacompany.com/media-center\n  - type: Sustainability\n    url: https://www.coca-colacompany.com/sustainability\n  - type: Careers\n    url: https://www.coca-colacompany.com/careers\n  - type: PrivacyPolicy\n    url: https://www.coca-colacompany.com/policies-and-practices/privacy-policy\n  - type: TermsOfService\n    url: https://www.coca-colacompany.com/policies-and-practices/terms-of-use\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/coca-cola/refs/heads/main/apis.yml
tags:
- Beverages
- Beverage Manufacturer
- Consumer Goods
- Distribution
- Retail
- Supply Chain
url: https://raw.githubusercontent.com/api-evangelist/coca-cola/refs/heads/main/apis.yml
use_cases: []
---
