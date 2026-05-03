---
api_count: 5
api_specs:
- filename: trustpilot-business-units-openapi.yml
  format: yaml
  label: Trustpilot Business Units API
  slug: trustpilot-business-units-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-business-units-openapi.yml
- filename: trustpilot-service-reviews-openapi.yml
  format: yaml
  label: Trustpilot Service Reviews API
  slug: trustpilot-service-reviews-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-service-reviews-openapi.yml
- filename: trustpilot-invitation-openapi.yml
  format: yaml
  label: Trustpilot Invitation API
  slug: trustpilot-invitation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-invitation-openapi.yml
- filename: trustpilot-product-reviews-openapi.yml
  format: yaml
  label: Trustpilot Product Reviews API
  slug: trustpilot-product-reviews-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-product-reviews-openapi.yml
apis:
- description: The Trustpilot Business Units API provides endpoints to retrieve company profile information, reviews, images, categories, and web links for specific business units on Trustpilot. Developers can searc
  name: Trustpilot Business Units API
  slug: trustpilot-business-units-api
- description: The Trustpilot Service Reviews API enables businesses to manage service reviews, including posting replies, managing tags, finding reviewers, and retrieving review details. Businesses can respond to c
  name: Trustpilot Service Reviews API
  slug: trustpilot-service-reviews-api
- description: The Trustpilot Invitation API allows businesses to programmatically send review invitations to their customers via email or SMS after a transaction or service interaction. It supports creating invitat
  name: Trustpilot Invitation API
  slug: trustpilot-invitation-api
- description: The Trustpilot Product Reviews API enables management of product-level reviews, including retrieving product review summaries, accessing individual reviews, managing conversations and comments on prod
  name: Trustpilot Product Reviews API
  slug: trustpilot-product-reviews-api
- description: The Trustpilot Consumer API provides access to reviews written by individual consumers. Developers can retrieve a consumer's review history with filtering by stars, language, location, and business un
  name: Trustpilot Consumer API
  slug: trustpilot-consumer-api
capabilities:
- description: Unified review management capability combining business unit profiles, service review management, and invitation workflows. Used by customer experience teams and CRM integrations to monitor reviews, r
  name: Trustpilot Review Management
  slug: review-management
common:
- title: ''
  type: Website
  url: https://www.trustpilot.com/
- title: ''
  type: Portal
  url: https://developers.trustpilot.com/
- title: ''
  type: Documentation
  url: https://developers.trustpilot.com/
- title: ''
  type: SignUp
  url: https://www.trustpilot.com/signup/business
- title: ''
  type: Login
  url: https://businessapp.b2b.trustpilot.com/login
- title: ''
  type: Pricing
  url: https://www.trustpilot.com/pricing
- title: ''
  type: Authentication
  url: https://developers.trustpilot.com/authentication
- title: ''
  type: ChangeLog
  url: https://developers.trustpilot.com/changelog
- title: ''
  type: Support
  url: https://support.trustpilot.com/
- title: ''
  type: TermsOfService
  url: https://www.trustpilot.com/legal/terms-and-conditions-for-businesses
- title: ''
  type: PrivacyPolicy
  url: https://www.trustpilot.com/legal/privacy-policy
- title: ''
  type: Blog
  url: https://blog.trustpilot.com/
- title: ''
  type: Status
  url: https://status.trustpilot.com/
- title: ''
  type: X
  url: https://twitter.com/trustpilot
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/trustpilot
- title: ''
  type: Facebook
  url: https://www.facebook.com/trustpilot
- title: ''
  type: GitHub
  url: https://github.com/trustpilot
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/rules/trustpilot-rules.yml
created: '2026-03-24'
description: Trustpilot is a global consumer review platform that connects businesses with their customers to build trust through transparent, verified reviews. Founded in 2007, Trustpilot hosts hundreds of millions of reviews across millions of businesses worldwide. The platform offers business APIs that allow companies to collect, manage, and display reviews programmatically, integrate review data into their own systems, and automate invitation workflows to gather customer feedback at scale. Trustpilot's APIs cover business profile management, service reviews, product reviews, invitation management, consumer profiles, and public review data.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 14
  name: Trustpilot Context
  property_count: 9
  slug: trustpilot-context
layout: provider
modified: '2026-05-03'
name: Trustpilot
rules:
- name: Trustpilot API Rules
  rule_count: 11
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 9
  slug: trustpilot-rules
skills: []
slug: trustpilot
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trustpilot\nurl: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/apis.yml\nname: Trustpilot\ndescription: >-\n  Trustpilot is a global consumer review platform that connects businesses with their\n  customers to build trust through transparent, verified reviews. Founded in 2007,\n  Trustpilot hosts hundreds of millions of reviews across millions of businesses worldwide.\n  The platform offers business APIs that allow companies to collect, manage, and display\n  reviews programmatically, integrate review data into their own systems, and automate\n  invitation workflows to gather customer feedback at scale. Trustpilot's APIs cover\n  business profile management, service reviews, product reviews, invitation management,\n  consumer profiles, and public review data.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Consumer Reviews\n  - Reviews\n  - Trust\n  - Ratings\n  - Business Profiles\n\
  \  - Product Reviews\naccess: 3rd-Party\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: trustpilot:trustpilot-business-units-api\n    name: Trustpilot Business Units API\n    tags:\n      - Business Profiles\n      - Reviews\n      - Trust\n      - Ratings\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trustpilot.com/v1\n    humanURL: https://developers.trustpilot.com/business-units-api\n    properties:\n      - url: https://developers.trustpilot.com/business-units-api\n        type: Documentation\n      - url: https://developers.trustpilot.com/authentication\n        type: Authentication\n      - url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-business-units-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Trustpilot Business Units API provides endpoints to retrieve company profile\n      information, reviews,\
  \ images, categories, and web links for specific business units\n      on Trustpilot. Developers can search for business units by name, retrieve public\n      and private reviews with filtering options, access business profile images and logos,\n      and list business categories. Public endpoints use API key authentication; private\n      review endpoints require OAuth 2.0.\n  - aid: trustpilot:trustpilot-service-reviews-api\n    name: Trustpilot Service Reviews API\n    tags:\n      - Reviews\n      - Consumer Reviews\n      - Trust\n      - Ratings\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trustpilot.com/v1\n    humanURL: https://developers.trustpilot.com/service-reviews-api/\n    properties:\n      - url: https://developers.trustpilot.com/service-reviews-api/\n        type: Documentation\n      - url: https://developers.trustpilot.com/authentication\n        type: Authentication\n      - url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-service-reviews-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The Trustpilot Service Reviews API enables businesses to manage service reviews,\n      including posting replies, managing tags, finding reviewers, and retrieving review\n      details. Businesses can respond to customer reviews, organize reviews with custom\n      tags, and retrieve the latest reviews by language. Most management endpoints require\n      OAuth 2.0 Business user tokens; public review endpoints are accessible with API keys.\n  - aid: trustpilot:trustpilot-invitation-api\n    name: Trustpilot Invitation API\n    tags:\n      - Invitations\n      - Consumer Reviews\n      - Email\n      - Reviews\n      - Trust\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trustpilot.com/v1\n    humanURL: https://developers.trustpilot.com/invitation-api\n    properties:\n      - url: https://developers.trustpilot.com/invitation-api\n        type: Documentation\n      - url:\
  \ https://developers.trustpilot.com/authentication\n        type: Authentication\n      - url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-invitation-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Trustpilot Invitation API allows businesses to programmatically send review\n      invitations to their customers via email or SMS after a transaction or service\n      interaction. It supports creating invitation links, triggering bulk email invitations\n      for service and product reviews, retrieving invitation templates, and deleting\n      invitation data by email or date range. All endpoints require OAuth 2.0 Business\n      user token authentication.\n  - aid: trustpilot:trustpilot-product-reviews-api\n    name: Trustpilot Product Reviews API\n    tags:\n      - Product Reviews\n      - Reviews\n      - Consumer Reviews\n      - Trust\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.trustpilot.com/v1\n    humanURL: https://developers.trustpilot.com/product-reviews-api/\n    properties:\n      - url: https://developers.trustpilot.com/product-reviews-api/\n        type: Documentation\n      - url: https://developers.trustpilot.com/authentication\n        type: Authentication\n      - url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-product-reviews-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Trustpilot Product Reviews API enables management of product-level reviews,\n      including retrieving product review summaries, accessing individual reviews,\n      managing conversations and comments on product reviews, creating product review\n      invitation links, and accessing attribute rating summaries. Supports both public\n      and private endpoints with API key and OAuth 2.0 authentication respectively.\n  - aid: trustpilot:trustpilot-consumer-api\n    name: Trustpilot\
  \ Consumer API\n    tags:\n      - Consumer Reviews\n      - Reviews\n      - Trust\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trustpilot.com/v1\n    humanURL: https://developers.trustpilot.com/consumer-api\n    properties:\n      - url: https://developers.trustpilot.com/consumer-api\n        type: Documentation\n      - url: https://developers.trustpilot.com/authentication\n        type: Authentication\n    description: >-\n      The Trustpilot Consumer API provides access to reviews written by individual\n      consumers. Developers can retrieve a consumer's review history with filtering\n      by stars, language, location, and business unit. Supports pagination and sorting\n      and requires API key authentication.\ncommon:\n  - url: https://www.trustpilot.com/\n    name: Trustpilot Website\n    type: Website\n  - url: https://developers.trustpilot.com/\n    name: Developer Portal\n    type: Portal\n  - url: https://developers.trustpilot.com/\n\
  \    name: API Documentation\n    type: Documentation\n  - url: https://www.trustpilot.com/signup/business\n    name: Sign Up\n    type: SignUp\n  - url: https://businessapp.b2b.trustpilot.com/login\n    name: Login\n    type: Login\n  - url: https://www.trustpilot.com/pricing\n    name: Pricing\n    type: Pricing\n  - url: https://developers.trustpilot.com/authentication\n    name: Authentication\n    type: Authentication\n  - url: https://developers.trustpilot.com/changelog\n    name: Changelog\n    type: ChangeLog\n  - url: https://support.trustpilot.com/\n    name: Support\n    type: Support\n  - url: https://www.trustpilot.com/legal/terms-and-conditions-for-businesses\n    name: Terms of Service\n    type: TermsOfService\n  - url: https://www.trustpilot.com/legal/privacy-policy\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://blog.trustpilot.com/\n    name: Trustpilot Blog\n    type: Blog\n  - url: https://status.trustpilot.com/\n    name: Status Page\n    type:\
  \ Status\n  - url: https://twitter.com/trustpilot\n    name: Trustpilot on X (Twitter)\n    type: X\n  - url: https://www.linkedin.com/company/trustpilot\n    name: Trustpilot on LinkedIn\n    type: LinkedIn\n  - url: https://www.facebook.com/trustpilot\n    name: Trustpilot on Facebook\n    type: Facebook\n  - url: https://github.com/trustpilot\n    name: Trustpilot on GitHub\n    type: GitHub\n  - url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/rules/trustpilot-rules.yml\n    name: Spectral Rules\n    type: SpectralRules\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/apis.yml
tags:
- Consumer Reviews
- Reviews
- Trust
- Ratings
- Business Profiles
- Product Reviews
url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/apis.yml
use_cases: []
---
