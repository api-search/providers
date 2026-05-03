---
api_count: 1
api_specs:
- filename: saashub-openapi.yml
  format: yaml
  label: SaaSHub API
  slug: saashub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/saashub/refs/heads/main/openapi/saashub-openapi.yml
apis:
- description: 'The SaaSHub public API provides programmatic access to SaaSHub''s software discovery platform. The API offers two primary endpoints: a product endpoint that returns data for the first product matching '
  name: SaaSHub API
  slug: saashub-api
capabilities:
- description: Software discovery and alternatives research capability using the SaaSHub platform. Enables product research, competitive analysis, and vendor replacement discovery for SaaS procurement and IT asset m
  name: SaaSHub Software Discovery
  slug: software-discovery
common:
- title: ''
  type: Website
  url: https://www.saashub.com/
- title: ''
  type: Documentation
  url: https://www.saashub.com/site/api
- title: ''
  type: Authentication
  url: https://www.saashub.com/profile/api_key
- title: ''
  type: FAQ
  url: https://www.saashub.com/faq
- title: ''
  type: PrivacyPolicy
  url: https://www.saashub.com/site/privacy
- title: ''
  type: Newsletter
  url: https://www.saashub.com/newsletter
- title: ''
  type: SignUp
  url: https://www.saashub.com/users/sign_up
- title: ''
  type: Login
  url: https://www.saashub.com/users/sign_in
- title: ''
  type: X
  url: https://twitter.com/saashubcom
created: '2026-03-24'
description: SaaSHub is an independent software discovery platform that helps users find, compare, and discover software alternatives across SaaS, web, and cloud-based applications. The platform maintains a comprehensive catalog of software products with user reviews, pricing information, feature comparisons, and curated lists of alternatives. SaaSHub serves as a permanent directory where software vendors can list their products and users can discover alternatives to tools they already use.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 7
  name: Saashub Context
  property_count: 7
  slug: saashub-context
layout: provider
modified: '2026-05-02'
name: SaaSHub
rules:
- name: SaaSHub API Rules
  rule_count: 7
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 6
  slug: saashub-spectral-rules
skills: []
slug: saashub
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: saashub\nname: SaaSHub\ndescription: >-\n  SaaSHub is an independent software discovery platform that helps users find,\n  compare, and discover software alternatives across SaaS, web, and cloud-based\n  applications. The platform maintains a comprehensive catalog of software\n  products with user reviews, pricing information, feature comparisons, and\n  curated lists of alternatives. SaaSHub serves as a permanent directory where\n  software vendors can list their products and users can discover alternatives\n  to tools they already use.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/saashub/refs/heads/main/apis.yml\ntags:\n  - Alternatives\n  - SaaS\n  - Software Discovery\n  - Software Catalog\ncreated: '2026-03-24'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: saashub:saashub-api\n    name: SaaSHub API\n    description: >-\n      The SaaSHub\
  \ public API provides programmatic access to SaaSHub's software\n      discovery platform. The API offers two primary endpoints: a product\n      endpoint that returns data for the first product matching a query, and an\n      alternatives endpoint that returns the matching product along with its top\n      10 relevant alternatives. Responses follow the JSON:API specification.\n      Authentication requires an API key obtained from the SaaSHub user profile.\n    humanURL: https://www.saashub.com/site/api\n    baseURL: https://www.saashub.com/api\n    tags:\n      - Software Discovery\n      - Alternatives\n      - SaaS\n    properties:\n      - type: Documentation\n        url: https://www.saashub.com/site/api\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/saashub/refs/heads/main/openapi/saashub-openapi.yml\n      - type: Authentication\n        url: https://www.saashub.com/profile/api_key\ncommon:\n  - url: https://www.saashub.com/\n    name: SaaSHub\
  \ Website\n    type: Website\n  - url: https://www.saashub.com/site/api\n    name: API Documentation\n    type: Documentation\n  - url: https://www.saashub.com/profile/api_key\n    name: API Key\n    type: Authentication\n  - url: https://www.saashub.com/faq\n    name: FAQ\n    type: FAQ\n  - url: https://www.saashub.com/site/privacy\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://www.saashub.com/newsletter\n    name: Newsletter\n    type: Newsletter\n  - url: https://www.saashub.com/users/sign_up\n    name: Sign Up\n    type: SignUp\n  - url: https://www.saashub.com/users/sign_in\n    name: Login\n    type: Login\n  - url: https://twitter.com/saashubcom\n    name: SaaSHub on X\n    type: X\nfeatures:\n  - Software Product Search\n  - Alternative Software Discovery\n  - Software Comparison\n  - User Reviews\n  - Pricing Information\n  - Category Browsing\n  - Software Rankings\n  - Expert Curated Lists\nsolutions:\n  - Software Discovery\n  - Competitive Analysis\n\
  \  - Software Procurement Research\n  - Vendor Replacement Research\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/saashub/refs/heads/main/apis.yml
tags:
- Alternatives
- SaaS
- Software Discovery
- Software Catalog
url: https://raw.githubusercontent.com/api-evangelist/saashub/refs/heads/main/apis.yml
use_cases: []
---
