---
api_count: 3
apis:
- description: The Trustpilot Business API provides programmatic access to business profile data, reviews, and review management capabilities on the Trustpilot platform. Businesses can retrieve their profile informa
  name: Trustpilot Business API
  slug: trustpilot-business-api
- description: The Trustpilot Invitation API allows businesses to programmatically send review invitations to their customers via email or SMS after a transaction or service interaction. It supports creating and man
  name: Trustpilot Invitation API
  slug: trustpilot-invitation-api
- description: The Trustpilot Consumer API provides public read access to business profiles, reviews, categories, and star ratings published on Trustpilot. Developers can retrieve lists of reviews for a business uni
  name: Trustpilot Consumer API
  slug: trustpilot-consumer-api
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
created: '2026-03-24'
description: Trustpilot is a global consumer review platform that connects businesses with their customers to build trust through transparent, verified reviews. Founded in 2007, Trustpilot hosts hundreds of millions of reviews across millions of businesses worldwide. The platform offers business APIs that allow companies to collect, manage, and display reviews programmatically, integrate review data into their own systems, and automate invitation workflows to gather customer feedback at scale.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-24'
name: Trustpilot
skills: []
slug: trustpilot
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trustpilot\nurl: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/apis.yml\napis:\n  - aid: trustpilot:trustpilot-business-api\n    name: Trustpilot Business API\n    tags:\n      - Business Profiles\n      - Consumer Reviews\n      - Reviews\n      - Trust\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trustpilot.com/v1\n    humanURL: https://developers.trustpilot.com/\n    properties:\n      - url: https://developers.trustpilot.com/\n        type: Documentation\n      - url: https://developers.trustpilot.com/authentication\n        type: Authentication\n      - url: https://developers.trustpilot.com/business-units-api\n        type: Documentation\n      - url: https://developers.trustpilot.com/reviews-api\n        type: Documentation\n    description: >-\n      The Trustpilot Business API provides programmatic access to business profile\n      data, reviews, and review management\
  \ capabilities on the Trustpilot platform.\n      Businesses can retrieve their profile information, access and respond to consumer\n      reviews, manage review invitations, and retrieve aggregate review statistics\n      and star ratings. The API supports OAuth 2.0 authentication and enables integration\n      of Trustpilot review data into business dashboards, CRM systems, and customer\n      experience workflows.\n  - aid: trustpilot:trustpilot-invitation-api\n    name: Trustpilot Invitation API\n    tags:\n      - Consumer Reviews\n      - Email\n      - Invitations\n      - Reviews\n      - Trust\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trustpilot.com/v1\n    humanURL: https://developers.trustpilot.com/invitation-api\n    properties:\n      - url: https://developers.trustpilot.com/invitation-api\n        type: Documentation\n      - url: https://developers.trustpilot.com/authentication\n        type: Authentication\n\
  \    description: >-\n      The Trustpilot Invitation API allows businesses to programmatically send review\n      invitations to their customers via email or SMS after a transaction or service\n      interaction. It supports creating and managing invitation templates, scheduling\n      bulk invitation sends, and tracking invitation delivery and response rates.\n      The API integrates with e-commerce platforms and order management systems to\n      automate post-purchase review collection at scale.\n  - aid: trustpilot:trustpilot-consumer-api\n    name: Trustpilot Consumer API\n    tags:\n      - Consumer Reviews\n      - Reviews\n      - Trust\n      - Widgets\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trustpilot.com/v1\n    humanURL: https://developers.trustpilot.com/consumer-api\n    properties:\n      - url: https://developers.trustpilot.com/consumer-api\n        type: Documentation\n      - url: https://developers.trustpilot.com/authentication\n\
  \        type: Authentication\n    description: >-\n      The Trustpilot Consumer API provides public read access to business profiles,\n      reviews, categories, and star ratings published on Trustpilot. Developers can\n      retrieve lists of reviews for a business unit, search for business profiles\n      by name or domain, and fetch aggregate rating data including TrustScore and\n      review counts.\nname: Trustpilot\ndescription: >-\n  Trustpilot is a global consumer review platform that connects businesses with their\n  customers to build trust through transparent, verified reviews. Founded in 2007,\n  Trustpilot hosts hundreds of millions of reviews across millions of businesses worldwide.\n  The platform offers business APIs that allow companies to collect, manage, and display\n  reviews programmatically, integrate review data into their own systems, and automate\n  invitation workflows to gather customer feedback at scale.\ntags:\n  - Consumer Reviews\n  - Reviews\n  - Trust\n\
  type: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://www.trustpilot.com/\n    name: Trustpilot Website\n    type: Website\n  - url: https://developers.trustpilot.com/\n    name: Developer Portal\n    type: Portal\n  - url: https://developers.trustpilot.com/\n    name: API Documentation\n    type: Documentation\n  - url: https://www.trustpilot.com/signup/business\n    name: Sign Up\n    type: SignUp\n  - url: https://businessapp.b2b.trustpilot.com/login\n    name: Login\n    type: Login\n  - url: https://www.trustpilot.com/pricing\n    name: Pricing\n    type: Pricing\n  - url: https://developers.trustpilot.com/authentication\n    name: Authentication\n    type: Authentication\n  - url: https://developers.trustpilot.com/changelog\n    name: Changelog\n    type: ChangeLog\n  - url: https://support.trustpilot.com/\n    name: Support\n    type: Support\n  - url: https://www.trustpilot.com/legal/terms-and-conditions-for-businesses\n\
  \    name: Terms of Service\n    type: TermsOfService\n  - url: https://www.trustpilot.com/legal/privacy-policy\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://blog.trustpilot.com/\n    name: Trustpilot Blog\n    type: Blog\n  - url: https://status.trustpilot.com/\n    name: Status Page\n    type: Status\n  - url: https://twitter.com/trustpilot\n    name: Trustpilot on X (Twitter)\n    type: X\n  - url: https://www.linkedin.com/company/trustpilot\n    name: Trustpilot on LinkedIn\n    type: LinkedIn\n  - url: https://www.facebook.com/trustpilot\n    name: Trustpilot on Facebook\n    type: Facebook\n  - url: https://github.com/trustpilot\n    name: Trustpilot on GitHub\n    type: GitHub\ncreated: '2026-03-24'\nmodified: '2026-03-24'\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/apis.yml
tags:
- Consumer Reviews
- Reviews
- Trust
url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/apis.yml
use_cases: []
---
