---
api_count: 2
apis:
- description: 'The Clerk.io API provides REST endpoints for managing products, categories, orders, customers, recommendations, and search. The API uses a dual-key authentication model: a public key identifies the st'
  name: Clerk.io API
  slug: clerk-io-api
- description: Clerk.js is the browser-side JavaScript library for embedding Clerk.io recommendation slots, search, and email opens on a storefront, with Liquid templating support and event tracking.
  name: Clerk.js Client Library
  slug: clerkjs
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.clerk.io/
- title: ''
  type: Documentation
  url: https://docs.clerk.io/
- title: ''
  type: Knowledgebase
  url: https://help.clerk.io/
- title: ''
  type: Status
  url: https://status.clerk.io/
- title: ''
  type: Blog
  url: https://www.clerk.io/blogs
- title: ''
  type: Pricing
  url: https://www.clerk.io/pricing
- title: ''
  type: Partners
  url: https://www.clerk.io/partners
- title: ''
  type: Trust Center
  url: https://trust.clerk.io/
- title: ''
  type: Terms of Service
  url: https://www.clerk.io/terms-of-service
- title: ''
  type: Privacy Policy
  url: https://www.clerk.io/privacy
- title: ''
  type: JSON-LD
  url: json-ld/clerk-io-context.jsonld
- title: ''
  type: Spectral
  url: rules/clerk-io-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/clerk-io-capabilities.yml
created: '2025-02-08'
description: Clerk.io is an e-commerce personalization platform that uses artificial intelligence and machine learning to deliver tailored product recommendations, on-site search results, audience-segmented email campaigns, and merchandising controls for online retailers. The platform exposes a REST API for product, category, order, and customer data ingestion, plus client-side JavaScript and Liquid templating for recommendation slots and search experiences.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Clerk Io Context
  property_count: 5
  slug: clerk-io-context
layout: provider
modified: '2026-04-26'
name: Clerk.io
rules:
- name: Clerk.io API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 4
  slug: clerk-io-rules
skills: []
slug: clerk-io
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: clerk-io\nname: Clerk.io\nurl: https://raw.githubusercontent.com/api-evangelist/clerk-io/refs/heads/main/apis.yml\ncreated: '2025-02-08'\nmodified: '2026-04-26'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nx-type: company\ntags:\n  - AI\n  - Commerce\n  - E-Commerce\n  - Email Marketing\n  - Personalization\n  - Recommendations\n  - Search\ndescription: >-\n  Clerk.io is an e-commerce personalization platform that uses artificial\n  intelligence and machine learning to deliver tailored product\n  recommendations, on-site search results, audience-segmented email\n  campaigns, and merchandising controls for online retailers. The platform\n  exposes a REST API for product, category, order, and customer data\n  ingestion, plus client-side JavaScript and Liquid templating for\n  recommendation slots and search experiences.\napis:\n  - aid: clerk-io:clerk-io-api\n\
  \    name: Clerk.io API\n    tags:\n      - Commerce\n      - Personalization\n      - Recommendations\n      - Search\n    humanURL: https://docs.clerk.io/\n    properties:\n      - url: https://docs.clerk.io/\n        type: Documentation\n      - url: https://docs.clerk.io/docs/how-the-clerkio-platform-works\n        type: Getting Started\n      - url: https://docs.clerk.io/docs/authentication\n        type: Authentication\n      - url: https://docs.clerk.io/docs/errors\n        type: Errors\n      - url: https://docs.clerk.io/docs/pagenation\n        type: Pagination\n    description: >-\n      The Clerk.io API provides REST endpoints for managing products,\n      categories, orders, customers, recommendations, and search. The API\n      uses a dual-key authentication model: a public key identifies the\n      store and is used in browser-side requests, while a private key is\n      required for sensitive operations and data ingestion. JSON is the\n      primary payload format and SSL\
  \ is required when sending the private\n      key.\n  - aid: clerk-io:clerkjs\n    name: Clerk.js Client Library\n    tags:\n      - Client Library\n      - JavaScript\n    humanURL: https://docs.clerk.io/docs/clerkjs-quick-start\n    properties:\n      - url: https://docs.clerk.io/docs/clerkjs-quick-start\n        type: Documentation\n    description: >-\n      Clerk.js is the browser-side JavaScript library for embedding\n      Clerk.io recommendation slots, search, and email opens on a\n      storefront, with Liquid templating support and event tracking.\ncommon:\n  - type: Website\n    url: https://www.clerk.io/\n  - type: Documentation\n    url: https://docs.clerk.io/\n  - type: Knowledgebase\n    url: https://help.clerk.io/\n  - type: Status\n    url: https://status.clerk.io/\n  - type: Blog\n    url: https://www.clerk.io/blogs\n  - type: Pricing\n    url: https://www.clerk.io/pricing\n  - type: Partners\n    url: https://www.clerk.io/partners\n  - type: Integrations\n    url: https://www.clerk.io/integrations\n\
  \  - type: Trust Center\n    url: https://trust.clerk.io/\n  - type: Terms of Service\n    url: https://www.clerk.io/terms-of-service\n  - type: Privacy Policy\n    url: https://www.clerk.io/privacy\n  - type: JSON-LD\n    url: json-ld/clerk-io-context.jsonld\n  - type: Spectral\n    url: rules/clerk-io-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/clerk-io-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/clerk-io/refs/heads/main/apis.yml
tags:
- AI
- Commerce
- E-Commerce
- Email Marketing
- Personalization
- Recommendations
- Search
url: https://raw.githubusercontent.com/api-evangelist/clerk-io/refs/heads/main/apis.yml
use_cases: []
---
