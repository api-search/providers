---
api_count: 4
api_specs:
- filename: trustradius-public-openapi.yml
  format: yaml
  label: TrustRadius Public API
  slug: trustradius-public-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trustradius/refs/heads/main/openapi/trustradius-public-openapi.yml
- filename: trustradius-reviews-openapi.yml
  format: yaml
  label: TrustRadius Reviews API
  slug: trustradius-reviews-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trustradius/refs/heads/main/openapi/trustradius-reviews-openapi.yml
apis:
- description: The TrustRadius Public API provides programmatic access to product data, verified user reviews, TrustRadius scores (trScores), software categories, and aggregate rating information. Vendors can retrie
  name: TrustRadius Public API
  slug: trustradius-public-api
- description: 'The TrustRadius Downstream Intent Data API delivers buyer and deal intelligence, revealing which accounts are actively researching a vendor''s products, competitor products, and software categories on '
  name: TrustRadius Downstream Intent Data API
  slug: trustradius-intent-data-api
- description: The TrustRadius Reviews API provides access to verified user reviews for software products, including detailed review content (400+ words), ratings across multiple dimensions (usability, support, like
  name: TrustRadius Reviews API
  slug: trustradius-reviews-api
- description: The TrustRadius Content Syndication API (TrustQuotes) enables vendors to extract and embed customer review quotes across marketing channels. Businesses can retrieve licensed review excerpts, quotes, a
  name: TrustRadius Content Syndication API
  slug: trustradius-content-syndication-api
capabilities:
- description: Unified B2B buyer intelligence capability combining product data, verified reviews, and category research. Used by sales and marketing teams to research software categories, compare products, access v
  name: TrustRadius Buyer Intelligence
  slug: buyer-intelligence
common:
- title: ''
  type: Website
  url: https://www.trustradius.com/
- title: ''
  type: Portal
  url: https://solutions.trustradius.com/
- title: ''
  type: Documentation
  url: https://apidocs.trustradius.com/
- title: ''
  type: Authentication
  url: https://trustradius.freshdesk.com/support/solutions/articles/43000639047
- title: ''
  type: Products
  url: https://solutions.trustradius.com/products/
- title: ''
  type: TermsOfService
  url: https://www.trustradius.com/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.trustradius.com/legal/privacy-policy
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/trustradius
- title: ''
  type: X
  url: https://twitter.com/TrustRadius
- title: ''
  type: GitHub
  url: https://github.com/trustradius
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/trustradius/refs/heads/main/rules/trustradius-rules.yml
created: '2026-05-03'
description: TrustRadius is a B2B buyer intelligence and software review platform that helps technology buyers make confident purchasing decisions and enables vendors to turn verified customer reviews into demand generation. Founded in 2012 and headquartered in Austin, Texas, TrustRadius hosts in-depth verified reviews averaging 400+ words, and provides vendors with downstream intent data showing who is actively researching their products, competitors, and categories. The platform offers REST APIs for accessing product review data, buyer intent signals, and content licensing capabilities, with integrations into Salesforce, HubSpot, 6sense, Demandbase, LinkedIn, Marketo, and Snowflake. Authentication uses API key access from the TrustRadius Vendor Portal.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 9
  name: Trustradius Context
  property_count: 22
  slug: trustradius-context
layout: provider
modified: '2026-05-03'
name: TrustRadius
rules:
- name: TrustRadius API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 6
  slug: trustradius-rules
skills: []
slug: trustradius
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trustradius\nurl: https://raw.githubusercontent.com/api-evangelist/trustradius/refs/heads/main/apis.yml\nname: TrustRadius\ndescription: >-\n  TrustRadius is a B2B buyer intelligence and software review platform that helps\n  technology buyers make confident purchasing decisions and enables vendors to turn\n  verified customer reviews into demand generation. Founded in 2012 and headquartered\n  in Austin, Texas, TrustRadius hosts in-depth verified reviews averaging 400+ words,\n  and provides vendors with downstream intent data showing who is actively researching\n  their products, competitors, and categories. The platform offers REST APIs for accessing\n  product review data, buyer intent signals, and content licensing capabilities, with\n  integrations into Salesforce, HubSpot, 6sense, Demandbase, LinkedIn, Marketo,\n  and Snowflake. Authentication uses API key access from the TrustRadius Vendor Portal.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  tags:\n  - B2B Software Reviews\n  - Buyer Intelligence\n  - Intent Data\n  - Software Reviews\n  - Reviews\n  - Product Reviews\n  - Categories\naccess: 3rd-Party\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: trustradius:trustradius-public-api\n    name: TrustRadius Public API\n    tags:\n      - B2B Software Reviews\n      - Product Reviews\n      - Reviews\n      - Software Categories\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trustradius.com/v1\n    humanURL: https://apidocs.trustradius.com/\n    properties:\n      - url: https://apidocs.trustradius.com/\n        type: Documentation\n      - url: https://apidocs.trustradius.com/docs/public-api/ZG9jOjQ1Mg-trust-radius-api\n        type: Documentation\n      - url: https://trustradius.freshdesk.com/support/solutions/articles/43000639047\n        type: Authentication\n      - url: https://raw.githubusercontent.com/api-evangelist/trustradius/refs/heads/main/openapi/trustradius-public-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The TrustRadius Public API provides programmatic access to product data, verified\n      user reviews, TrustRadius scores (trScores), software categories, and aggregate\n      rating information. Vendors can retrieve their product profile, reviews written by\n      customers, category information, and competitive comparison data. Authentication\n      uses an API key obtained from the TrustRadius Vendor Portal Integrations section.\n      The API is a REST-based service returning JSON responses.\n  - aid: trustradius:trustradius-intent-data-api\n    name: TrustRadius Downstream Intent Data API\n    tags:\n      - Intent Data\n      - Buyer Intelligence\n      - B2B\n      - ABM\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trustradius.com/v1\n    humanURL: https://solutions.trustradius.com/intent-data/\n    properties:\n      - url: https://solutions.trustradius.com/intent-data/\n\
  \        type: Documentation\n      - url: https://solutions.trustradius.com/integrations/\n        type: Documentation\n      - url: https://apidocs.trustradius.com/\n        type: Documentation\n    description: >-\n      The TrustRadius Downstream Intent Data API delivers buyer and deal intelligence,\n      revealing which accounts are actively researching a vendor's products, competitor\n      products, and software categories on TrustRadius. The API provides account-level\n      intent signals that can be integrated with Salesforce, HubSpot, 6sense, Demandbase,\n      Marketo, LinkedIn Matched Audiences, and Snowflake for account-based marketing\n      and sales acceleration workflows.\n  - aid: trustradius:trustradius-reviews-api\n    name: TrustRadius Reviews API\n    tags:\n      - Reviews\n      - B2B Software Reviews\n      - Product Reviews\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trustradius.com/v1\n  \
  \  humanURL: https://apidocs.trustradius.com/\n    properties:\n      - url: https://apidocs.trustradius.com/\n        type: Documentation\n      - url: https://trustradius.freshdesk.com/support/solutions/articles/43000639047\n        type: Authentication\n      - url: https://raw.githubusercontent.com/api-evangelist/trustradius/refs/heads/main/openapi/trustradius-reviews-openapi.yml\n        type: OpenAPI\n    description: >-\n      The TrustRadius Reviews API provides access to verified user reviews for software\n      products, including detailed review content (400+ words), ratings across multiple\n      dimensions (usability, support, likelihood to recommend), reviewer information,\n      and pros/cons data. Vendors can retrieve reviews for their own products and export\n      review content for content licensing and syndication programs.\n  - aid: trustradius:trustradius-content-syndication-api\n    name: TrustRadius Content Syndication API\n    tags:\n      - Content Licensing\n\
  \      - Reviews\n      - Marketing\n      - B2B\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trustradius.com/v1\n    humanURL: https://solutions.trustradius.com/products/\n    properties:\n      - url: https://solutions.trustradius.com/products/\n        type: Documentation\n      - url: https://apidocs.trustradius.com/\n        type: Documentation\n    description: >-\n      The TrustRadius Content Syndication API (TrustQuotes) enables vendors to extract\n      and embed customer review quotes across marketing channels. Businesses can retrieve\n      licensed review excerpts, quotes, and ratings for use in digital advertising,\n      landing pages, email campaigns, and sales collateral. Supports the Integrated\n      Content Syndication Network for broad review distribution.\ncommon:\n  - url: https://www.trustradius.com/\n    name: TrustRadius Website\n    type: Website\n  - url: https://solutions.trustradius.com/\n\
  \    name: TrustRadius for Vendors\n    type: Portal\n  - url: https://apidocs.trustradius.com/\n    name: API Documentation\n    type: Documentation\n  - url: https://trustradius.freshdesk.com/support/solutions/articles/43000639047\n    name: API Key Access\n    type: Authentication\n  - url: https://solutions.trustradius.com/integrations/\n    name: Integrations\n    type: Integrations\n  - url: https://solutions.trustradius.com/products/\n    name: Products\n    type: Products\n  - url: https://www.trustradius.com/legal/terms-of-use\n    name: Terms of Use\n    type: TermsOfService\n  - url: https://www.trustradius.com/legal/privacy-policy\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://www.linkedin.com/company/trustradius\n    name: TrustRadius on LinkedIn\n    type: LinkedIn\n  - url: https://twitter.com/TrustRadius\n    name: TrustRadius on X (Twitter)\n    type: X\n  - url: https://github.com/trustradius\n    name: TrustRadius on GitHub\n    type: GitHub\n \
  \ - url: https://raw.githubusercontent.com/api-evangelist/trustradius/refs/heads/main/rules/trustradius-rules.yml\n    name: Spectral Rules\n    type: SpectralRules\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trustradius/refs/heads/main/apis.yml
tags:
- B2B Software Reviews
- Buyer Intelligence
- Intent Data
- Software Reviews
- Reviews
- Product Reviews
- Categories
url: https://raw.githubusercontent.com/api-evangelist/trustradius/refs/heads/main/apis.yml
use_cases: []
---
