---
api_count: 1
api_specs:
- filename: spiceworks-cloud-apps-openapi.yml
  format: yaml
  label: Spiceworks Cloud Apps API
  slug: spiceworks-cloud-apps-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spiceworks/refs/heads/main/openapi/spiceworks-cloud-apps-openapi.yml
apis:
- description: The Spiceworks Cloud Apps API provides a JavaScript SDK for building integrated apps within the Spiceworks platform, with access to Help Desk ticketing data, device inventory, and user information. It
  name: Spiceworks Cloud Apps API
  slug: spiceworks-cloud-apps-api
capabilities:
- description: Workflow capability for IT professionals using Spiceworks to manage help desk ticketing, device inventory, and user administration. Combines ticket lifecycle management with device inventory lookup fo
  name: Spiceworks IT Management
  slug: it-management
common:
- title: ''
  type: Website
  url: https://community.spiceworks.com/
- title: ''
  type: SignUp
  url: https://community.spiceworks.com/register
- title: ''
  type: Login
  url: https://community.spiceworks.com/login
- title: ''
  type: Portal
  url: https://spiceworks.github.io/developers.spiceworks.com/
- title: ''
  type: Documentation
  url: https://spiceworks.github.io/developers.spiceworks.com/documentation/cloud-apps/
- title: ''
  type: SDKs
  url: https://github.com/spiceworks/spiceworks-js-sdk
- title: ''
  type: Support
  url: https://community.spiceworks.com/help
- title: ''
  type: TermsOfService
  url: https://community.spiceworks.com/legal/terms
- title: ''
  type: PrivacyPolicy
  url: https://community.spiceworks.com/legal/privacy
- title: ''
  type: Blog
  url: https://community.spiceworks.com/blog
- title: ''
  type: X
  url: https://twitter.com/spiceworks
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/spiceworks
- title: ''
  type: Facebook
  url: https://www.facebook.com/Spiceworks
- title: ''
  type: YouTube
  url: https://www.youtube.com/spiceworks
- title: ''
  type: GitHub
  url: https://github.com/spiceworks
- title: ''
  type: OpenAPI
  url: openapi/spiceworks-cloud-apps-openapi.yml
- title: ''
  type: SpectralRules
  url: rules/spiceworks-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/spiceworks-vocabulary.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/it-management.yaml
created: '2024-01-01'
description: Spiceworks is an online community and marketplace where IT professionals can find advice, manage their networks, and discover and purchase IT products and services. The Spiceworks Cloud Apps API enables developers to build integrated applications within the Spiceworks platform, accessing Help Desk ticketing, device inventory, and user management data through a JavaScript SDK with OAuth-based authentication.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Spiceworks Context
  property_count: 29
  slug: spiceworks-context
layout: provider
modified: '2026-05-02'
name: Spiceworks
rules:
- name: Spiceworks API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 6
  slug: spiceworks-rules
skills: []
slug: spiceworks
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spiceworks\nurl: https://raw.githubusercontent.com/api-evangelist/spiceworks/refs/heads/main/apis.yml\napis:\n  - aid: spiceworks:spiceworks-cloud-apps-api\n    name: Spiceworks Cloud Apps API\n    tags:\n      - Cloud Apps\n      - Community\n      - Help Desk\n      - IT Management\n      - Ticketing\n    humanURL: https://spiceworks.github.io/developers.spiceworks.com/documentation/cloud-apps/\n    properties:\n      - url: https://spiceworks.github.io/developers.spiceworks.com/documentation/cloud-apps/\n        type: Documentation\n      - url: https://spiceworks.github.io/developers.spiceworks.com/documentation/cloud-apps/authentication/\n        type: Authentication\n      - url: https://spiceworks.github.io/developers.spiceworks.com/documentation/cloud-apps/reference/helpdesk/\n        type: Documentation\n      - url: https://github.com/spiceworks/spiceworks-js-sdk\n        type: SDKs\n      - url: https://github.com/spiceworks/spiceworks-js-sdk/tree/master/examples/hello-world\n\
  \        type: Examples\n      - url: openapi/spiceworks-cloud-apps-openapi.yml\n        type: OpenAPI\n      - url: rules/spiceworks-rules.yml\n        type: SpectralRules\n      - url: capabilities/shared/cloud-apps.yaml\n        type: NaftikoCapabilities\n    description: The Spiceworks Cloud Apps API provides a JavaScript SDK for building\n      integrated apps within the Spiceworks platform, with access to Help Desk ticketing\n      data, device inventory, and user information. It allows developers to create custom\n      apps embedded in the Spiceworks interface with access to IT management data.\nname: Spiceworks\ntags:\n  - Community\n  - Enterprise IT\n  - IT Management\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ncommon:\n  - url: https://community.spiceworks.com/\n    name: Spiceworks Community Website\n    type: Website\n  - url:\
  \ https://community.spiceworks.com/register\n    name: Sign Up\n    type: SignUp\n  - url: https://community.spiceworks.com/login\n    name: Login\n    type: Login\n  - url: https://spiceworks.github.io/developers.spiceworks.com/\n    name: Developer Portal\n    type: Portal\n  - url: https://spiceworks.github.io/developers.spiceworks.com/documentation/cloud-apps/\n    name: Developer Documentation\n    type: Documentation\n  - url: https://github.com/spiceworks/spiceworks-js-sdk\n    name: Spiceworks JavaScript SDK\n    type: SDKs\n  - url: https://community.spiceworks.com/help\n    name: Help Center\n    type: Support\n  - url: https://community.spiceworks.com/legal/terms\n    name: Terms of Service\n    type: TermsOfService\n  - url: https://community.spiceworks.com/legal/privacy\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://community.spiceworks.com/blog\n    name: Spiceworks Blog\n    type: Blog\n  - url: https://twitter.com/spiceworks\n    name: Spiceworks on\
  \ X (Twitter)\n    type: X\n  - url: https://www.linkedin.com/company/spiceworks\n    name: Spiceworks on LinkedIn\n    type: LinkedIn\n  - url: https://www.facebook.com/Spiceworks\n    name: Spiceworks on Facebook\n    type: Facebook\n  - url: https://www.youtube.com/spiceworks\n    name: Spiceworks on YouTube\n    type: YouTube\n  - url: https://github.com/spiceworks\n    name: Spiceworks on GitHub\n    type: GitHub\n  - url: openapi/spiceworks-cloud-apps-openapi.yml\n    name: Spiceworks Cloud Apps OpenAPI\n    type: OpenAPI\n  - url: rules/spiceworks-rules.yml\n    name: Spiceworks Spectral Rules\n    type: SpectralRules\n  - url: vocabulary/spiceworks-vocabulary.yml\n    name: Spiceworks Vocabulary\n    type: Vocabulary\n  - url: capabilities/it-management.yaml\n    name: Spiceworks IT Management Capabilities\n    type: NaftikoCapabilities\ndescription: >-\n  Spiceworks is an online community and marketplace where IT professionals can find\n  advice, manage their networks, and discover\
  \ and purchase IT products and services.\n  The Spiceworks Cloud Apps API enables developers to build integrated applications\n  within the Spiceworks platform, accessing Help Desk ticketing, device inventory,\n  and user management data through a JavaScript SDK with OAuth-based authentication.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spiceworks/refs/heads/main/apis.yml
tags:
- Community
- Enterprise IT
- IT Management
url: https://raw.githubusercontent.com/api-evangelist/spiceworks/refs/heads/main/apis.yml
use_cases: []
---
