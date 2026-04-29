---
api_count: 1
api_specs:
- filename: appsumo-licensing-openapi.yaml
  format: yaml
  label: AppSumo Licensing API
  slug: appsumo-licensing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appsumo/refs/heads/main/openapi/appsumo-licensing-openapi.yaml
apis:
- description: The AppSumo Licensing API (v2) enables software partners selling products on the AppSumo marketplace to programmatically manage licenses for their customers. Partners can retrieve license details, val
  name: AppSumo Licensing API
  slug: appsumo-licensing-api
capabilities:
- description: Workflow capability for managing AppSumo marketplace licenses within a SaaS partner application. Enables validating purchases, activating licenses, and managing customer access for products sold throu
  name: AppSumo License Management
  slug: license-management
common:
- title: ''
  type: Website
  url: https://appsumo.com/
- title: ''
  type: Documentation
  url: https://docs.licensing.appsumo.com/
- title: ''
  type: SignUp
  url: https://appsumo.com/sign-up/
- title: ''
  type: Login
  url: https://appsumo.com/login/
- title: ''
  type: Pricing
  url: https://appsumo.com/pricing/
- title: ''
  type: GettingStarted
  url: https://docs.licensing.appsumo.com/api/api__getting_started.html
- title: ''
  type: OAuth
  url: https://docs.licensing.appsumo.com/faq/faq__oauth.html
- title: ''
  type: Webhooks
  url: https://docs.licensing.appsumo.com/webhook/webhook__getting_started.html
- title: ''
  type: GettingStarted
  url: https://appsumooriginals.helpscoutdocs.com/article/889-api-access-for-developers
- title: ''
  type: Support
  url: https://appsumo.com/help/
- title: ''
  type: TermsOfService
  url: https://appsumo.com/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://appsumo.com/privacy-policy/
- title: ''
  type: Blog
  url: https://blog.appsumo.com/
- title: ''
  type: PartnerProgram
  url: https://appsumo.com/partners/
- title: ''
  type: Affiliate
  url: https://appsumo.com/affiliate/
- title: ''
  type: X
  url: https://twitter.com/appsumo
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/appsumo
- title: ''
  type: Facebook
  url: https://www.facebook.com/AppSumo
- title: ''
  type: YouTube
  url: https://www.youtube.com/appsumo
created: '2026-03-24'
description: AppSumo Licensing API Documentation - v2.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 10
  name: Appsumo Context
  property_count: 0
  slug: appsumo-context
layout: provider
modified: '2026-04-19'
name: AppSumo
rules:
- name: AppSumo API Rules
  rule_count: 16
  severity_counts:
    error: 8
    hint: 0
    info: 0
    warn: 8
  slug: appsumo-spectral-rules
skills: []
slug: appsumo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: appsumo\nurl: https://raw.githubusercontent.com/api-evangelist/appsumo/refs/heads/main/apis.yml\napis:\n- aid: appsumo:appsumo-licensing-api\n  name: AppSumo Licensing API\n  tags:\n  - Licensing\n  - Marketplace\n  - SaaS\n  - Software Deals\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://appsumo.com\n  humanURL: https://docs.licensing.appsumo.com/\n  properties:\n  - url: https://docs.licensing.appsumo.com/\n    type: Documentation\n  - url: openapi/appsumo-licensing-openapi.yaml\n    type: OpenAPI\n  - url: json-schema/license-schema.json\n    type: JSONSchema\n  - url: json-structure/license-structure.json\n    type: JSONStructure\n  - url: examples/license-example.json\n    type: Example\n  - url: json-ld/appsumo-context.jsonld\n    type: JSONLD\n  - url: rules/appsumo-spectral-rules.yml\n    type: SpectralRules\n  - url: capabilities/shared/appsumo-api.yaml\n    type: NaftikoCapability\n  - url: capabilities/license-management.yaml\n\
  \    type: NaftikoCapability\n  - url: vocabulary/appsumo-vocabulary.yaml\n    type: Vocabulary\n  description: >-\n    The AppSumo Licensing API (v2) enables software partners selling products on\n    the AppSumo marketplace to programmatically manage licenses for their customers.\n    Partners can retrieve license details, validate activations, and manage license\n    states via REST API endpoints authenticated with an API key. The API also supports\n    OAuth integration, allowing customers to connect their AppSumo purchases directly\n    to partner applications.\nname: AppSumo\ntags:\n- Marketplace\n- SaaS\n- Software Deals\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n- url: https://appsumo.com/\n  name: AppSumo Website\n  type: Website\n- url: https://docs.licensing.appsumo.com/\n  name: Licensing API Documentation\n  type: Documentation\n- url: https://appsumo.com/sign-up/\n  name: Sign Up\n  type: SignUp\n\
  - url: https://appsumo.com/login/\n  name: Login\n  type: Login\n- url: https://appsumo.com/pricing/\n  name: Pricing\n  type: Pricing\n- url: https://docs.licensing.appsumo.com/api/api__getting_started.html\n  name: Getting Started\n  type: GettingStarted\n- url: https://docs.licensing.appsumo.com/faq/faq__oauth.html\n  name: OAuth\n  type: OAuth\n- url: https://docs.licensing.appsumo.com/webhook/webhook__getting_started.html\n  name: Webhooks\n  type: Webhooks\n- url: https://appsumooriginals.helpscoutdocs.com/article/889-api-access-for-developers\n  name: API Access for Developers\n  type: GettingStarted\n- url: https://appsumo.com/help/\n  name: Help Center\n  type: Support\n- url: https://appsumo.com/terms-of-service/\n  name: Terms of Service\n  type: TermsOfService\n- url: https://appsumo.com/privacy-policy/\n  name: Privacy Policy\n  type: PrivacyPolicy\n- url: https://blog.appsumo.com/\n  name: AppSumo Blog\n  type: Blog\n- url: https://appsumo.com/partners/\n  name: Partner Program\n\
  \  type: PartnerProgram\n- url: https://appsumo.com/affiliate/\n  name: Affiliate Program\n  type: Affiliate\n- url: https://twitter.com/appsumo\n  name: AppSumo on X (Twitter)\n  type: X\n- url: https://www.linkedin.com/company/appsumo\n  name: AppSumo on LinkedIn\n  type: LinkedIn\n- url: https://www.facebook.com/AppSumo\n  name: AppSumo on Facebook\n  type: Facebook\n- url: https://www.youtube.com/appsumo\n  name: AppSumo on YouTube\n  type: YouTube\ncreated: '2026-03-24'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ndescription: >-\n  AppSumo Licensing API Documentation - v2.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/appsumo/refs/heads/main/apis.yml
tags:
- Marketplace
- SaaS
- Software Deals
url: https://raw.githubusercontent.com/api-evangelist/appsumo/refs/heads/main/apis.yml
use_cases: []
---
