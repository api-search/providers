---
api_count: 1
api_specs:
- filename: shopper-approved-openapi.yml
  format: yaml
  label: Shopper Approved API
  slug: shopper-approved-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shopper-approved/refs/heads/main/openapi/shopper-approved-openapi.yml
apis:
- description: The Shopper Approved API enables merchants to pull review data, submit orders for review collection, retrieve site statistics, manage product reviews, and update review follow-up scheduling. All API r
  name: Shopper Approved API
  slug: shopper-approved-api
capabilities:
- description: Workflow capability for managing customer reviews and ratings through Shopper Approved. Covers review collection via order submission, review retrieval for display, product review management, site sta
  name: Shopper Approved Review Management
  slug: review-management
common: []
created: '2026-05-02'
description: Shopper Approved is an e-commerce ratings and reviews platform that helps merchants collect, manage, and display verified customer reviews to improve conversion rates and build trust. The platform powers Google Seller Ratings, enabling reviews to appear in Google Shopping ads and organic search results. Shopper Approved offers a REST API for programmatic access to review data, order submission for review collection, product review management, and site statistics.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 23
  name: Shopper Approved Context
  property_count: 2
  slug: shopper-approved-context
layout: provider
modified: '2026-05-02'
name: Shopper Approved
rules:
- name: Shopper Approved API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 4
  slug: shopper-approved-rules
skills: []
slug: shopper-approved
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: shopper-approved\nname: Shopper Approved\ndescription: >-\n  Shopper Approved is an e-commerce ratings and reviews platform that helps\n  merchants collect, manage, and display verified customer reviews to improve\n  conversion rates and build trust. The platform powers Google Seller Ratings,\n  enabling reviews to appear in Google Shopping ads and organic search results.\n  Shopper Approved offers a REST API for programmatic access to review data,\n  order submission for review collection, product review management, and site\n  statistics.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Reviews\n  - Ratings\n  - Ecommerce\n  - Customer Feedback\n  - Social Proof\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/shopper-approved/refs/heads/main/apis.yml\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: shopper-approved:shopper-approved-api\n    name: Shopper\
  \ Approved API\n    description: >-\n      The Shopper Approved API enables merchants to pull review data, submit\n      orders for review collection, retrieve site statistics, manage product\n      reviews, and update review follow-up scheduling. All API requests require\n      a Site ID (included in the URL path) and an API token (passed as a query\n      parameter), both available in the Shopper Approved merchant dashboard.\n    humanURL: https://help.shopperapproved.com/en/articles/9796973-how-to-use-our-api\n    baseURL: https://api.shopperapproved.com\n    tags:\n      - Reviews\n      - Ratings\n      - Ecommerce\n      - Customer Feedback\n    properties:\n      - type: Documentation\n        url: https://help.shopperapproved.com/en/articles/9796973-how-to-use-our-api\n      - type: HelpCenter\n        url: https://help.shopperapproved.com/en/collections/10456439-api\n      - type: Authentication\n        url: https://help.shopperapproved.com/en/articles/9796973-how-to-use-our-api\n\
  \      - type: Website\n        url: https://www.shopperapproved.com/\n      - type: OpenAPI\n        url: openapi/shopper-approved-openapi.yml\n      - type: JSONSchema\n        url: json-schema/shopper-approved-review-schema.json\n      - type: JSONSchema\n        url: json-schema/shopper-approved-product-review-schema.json\n      - type: JSONStructure\n        url: json-structure/shopper-approved-review-structure.json\n      - type: JSONLD\n        url: json-ld/shopper-approved-context.jsonld\n      - type: SpectralRules\n        url: rules/shopper-approved-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/review-management.yaml\n      - type: Vocabulary\n        url: vocabulary/shopper-approved-vocabulary.yml\n    contact:\n      - FN: Shopper Approved Support\n        url: https://help.shopperapproved.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/shopper-approved/refs/heads/main/apis.yml
tags:
- Reviews
- Ratings
- Ecommerce
- Customer Feedback
- Social Proof
url: https://raw.githubusercontent.com/api-evangelist/shopper-approved/refs/heads/main/apis.yml
use_cases: []
---
