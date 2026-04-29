---
api_count: 3
apis:
- description: Brand API provides programmatic access to any company's brand assets through a single API call. Returns the latest logos, color schemes, fonts, images, and firmographic information. Supports lookup by
  name: Brandfetch Brand API
  slug: brandfetch-brand-api
- description: Logo Link delivers brand logos directly via CDN URL embedding. Supports lookup by domain, stock ticker, crypto symbol, or ISIN. Parameters include logo type (icon, symbol, logo), theme (light/dark), h
  name: Brandfetch Logo Link API
  slug: brandfetch-logo-link-api
- description: 'Brand Search API matches brand names to their corresponding domain URLs and unique identifiers, enabling rich autocomplete experiences. Endpoint: GET https://api.brandfetch.io/v2/search/:name. Authent'
  name: Brandfetch Brand Search API
  slug: brandfetch-brand-search-api
common:
- title: ''
  type: Customers
  url: https://brandfetch.com/developers/customers
- title: ''
  type: Pricing
  url: https://brandfetch.com/developers/pricing
- title: ''
  type: GettingStarted
  url: https://docs.brandfetch.com/docs/getting-started
- title: ''
  type: Webhooks
  url: https://docs.brandfetch.com/docs/webhooks/overview
- title: ''
  type: EventTypes
  url: https://docs.brandfetch.com/docs/webhooks/event-types
- title: ''
  type: Support
  url: https://docs.brandfetch.com/support/getting-help
- title: ''
  type: Issues
  url: https://docs.brandfetch.com/support/report-inaccuracies
- title: ''
  type: Recipes
  url: https://docs.brandfetch.com/recipes/overview
- title: ''
  type: Documentation
  url: https://docs.brandfetch.com/reference/overview
- title: ''
  type: Sandbox
  url: https://docs.brandfetch.com/docs/brand-api#testing-sandbox
- title: ''
  type: ChangeLog
  url: https://docs.brandfetch.com/changelog/2024
- title: ''
  type: Login
  url: https://developers.brandfetch.com/
- title: ''
  type: SignUp
  url: https://developers.brandfetch.com/register
- title: ''
  type: LLMsTxt
  url: https://docs.brandfetch.com/llms.txt
created: '2024-03-30'
description: Brandfetch provides programmatic access to brand assets and company data through a suite of APIs. The Brand API retrieves logos, color schemes, fonts, images, and firmographic information for any company via domain, stock ticker, ISIN code, or crypto symbol. The Logo Link API serves logos via CDN with support for multiple formats, themes, and sizes. The Brand Search API enables autocomplete experiences by matching brand names to their domains and identifiers. All APIs support Bearer token authentication with free access for development.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json-icons/brand-api-create-branded-experiences.png
integrations: []
layout: provider
modified: '2026-04-21'
name: Brand API (Brandfetch)
skills: []
slug: brand-api
solutions: []
source_yaml: "aid: brand-api\nurl: https://raw.githubusercontent.com/api-evangelist/brand-api/refs/heads/main/apis.yml\nname: Brand API (Brandfetch)\ntags:\n  - Brands\n  - Logos\n  - Brand Assets\n  - Company Data\n  - Firmographics\ntype: Index\nx-type: company\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json-icons/brand-api-create-branded-experiences.png\naccess: 3rd-Party\ncreated: '2024-03-30'\nmodified: '2026-04-21'\nposition: Consuming\ndescription: >-\n  Brandfetch provides programmatic access to brand assets and company data through\n  a suite of APIs. The Brand API retrieves logos, color schemes, fonts, images, and\n  firmographic information for any company via domain, stock ticker, ISIN code, or\n  crypto symbol. The Logo Link API serves logos via CDN with support for multiple\n  formats, themes, and sizes. The Brand Search API enables autocomplete experiences\n  by matching brand names to their domains and identifiers. All APIs support Bearer\n  token authentication\
  \ with free access for development.\napis:\n  - aid: brand-api:brandfetch-brand-api\n    name: Brandfetch Brand API\n    tags:\n      - Brands\n      - Logos\n      - Colors\n      - Fonts\n      - Firmographics\n    humanURL: https://docs.brandfetch.com/docs/brand-api\n    properties:\n      - url: openapi/brandfetch-brand-api.yml\n        type: OpenAPI\n      - url: https://docs.brandfetch.com/docs/brand-api\n        type: Documentation\n    description: >-\n      Brand API provides programmatic access to any company's brand assets through\n      a single API call. Returns the latest logos, color schemes, fonts, images,\n      and firmographic information. Supports lookup by domain (e.g. nike.com),\n      stock/ETF ticker (e.g. NKE), ISIN code, or crypto symbol (e.g. BTC).\n      Base endpoint: GET /v2/brands/{identifier}. Authentication via Bearer token.\n      Free sandbox testing available on the brandfetch.com domain.\n  - aid: brand-api:brandfetch-logo-link-api\n    name: Brandfetch\
  \ Logo Link API\n    tags:\n      - Logos\n      - CDN\n      - Brand Assets\n    humanURL: https://docs.brandfetch.com/docs/logo-link\n    properties:\n      - url: https://docs.brandfetch.com/docs/logo-link\n        type: Documentation\n    description: >-\n      Logo Link delivers brand logos directly via CDN URL embedding. Supports\n      lookup by domain, stock ticker, crypto symbol, or ISIN. Parameters include\n      logo type (icon, symbol, logo), theme (light/dark), height/width, format\n      (webp, png, jpg, svg), and fallback behavior. Base CDN URL:\n      https://cdn.brandfetch.io/{identifier}?c=CLIENT_ID. Free with fair-use\n      rate limits; no attribution required.\n  - aid: brand-api:brandfetch-brand-search-api\n    name: Brandfetch Brand Search API\n    tags:\n      - Brand Search\n      - Autocomplete\n      - Domain Matching\n    humanURL: https://docs.brandfetch.com/docs/brand-search-api\n    properties:\n      - url: https://docs.brandfetch.com/docs/brand-search-api\n\
  \        type: Documentation\n    description: >-\n      Brand Search API matches brand names to their corresponding domain URLs\n      and unique identifiers, enabling rich autocomplete experiences. Endpoint:\n      GET https://api.brandfetch.io/v2/search/:name. Authentication via Client ID\n      query parameter. Free to use; no attribution required.\ncommon:\n  - url: https://brandfetch.com/developers/customers\n    name: Customers\n    type: Customers\n  - url: https://brandfetch.com/developers/pricing\n    name: Pricing\n    type: Pricing\n  - url: https://docs.brandfetch.com/docs/getting-started\n    name: Getting Started\n    type: GettingStarted\n  - url: https://docs.brandfetch.com/docs/webhooks/overview\n    name: Webhooks\n    type: Webhooks\n  - url: https://docs.brandfetch.com/docs/webhooks/event-types\n    name: Event Types\n    type: EventTypes\n  - url: https://docs.brandfetch.com/support/getting-help\n    name: Support\n    type: Support\n  - url: https://docs.brandfetch.com/support/report-inaccuracies\n\
  \    name: Issues\n    type: Issues\n  - url: https://docs.brandfetch.com/recipes/overview\n    name: Recipes\n    type: Recipes\n  - url: https://docs.brandfetch.com/reference/overview\n    name: Reference\n    type: Documentation\n  - url: https://docs.brandfetch.com/docs/brand-api#testing-sandbox\n    name: Sandbox\n    type: Sandbox\n  - url: https://docs.brandfetch.com/changelog/2024\n    name: Change Log\n    type: ChangeLog\n  - url: https://developers.brandfetch.com/\n    name: Login\n    type: Login\n  - url: https://developers.brandfetch.com/register\n    name: Sign Up\n    type: SignUp\n  - url: https://docs.brandfetch.com/llms.txt\n    name: LLMs Reference\n    type: LLMsTxt\nproperties:\n  - type: x-domain\n    value: brandfetch.com\n  - type: x-authentication\n    value: Bearer token (Brand API), Client ID query parameter (Logo Link, Search)\n  - type: x-identifier-types\n    value: Domain, Stock/ETF ticker, ISIN code, Crypto symbol\n  - type: x-data-returned\n    value:\
  \ Logos, color palettes, fonts, images, firmographic data\n  - type: x-logo-formats\n    value: WebP, PNG, JPG, SVG\n  - type: x-logo-types\n    value: icon, symbol, logo\n  - type: x-logo-themes\n    value: light, dark\n  - type: x-use-cases\n    value: >-\n      B2B personalization, brand asset retrieval, company data enrichment,\n      financial platform logos, crypto app branding, multi-tenant SaaS branding,\n      brand autocomplete, CRM enrichment\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/brand-api/refs/heads/main/apis.yml
tags:
- Brands
- Logos
- Brand Assets
- Company Data
- Firmographics
url: https://raw.githubusercontent.com/api-evangelist/brand-api/refs/heads/main/apis.yml
use_cases: []
---
