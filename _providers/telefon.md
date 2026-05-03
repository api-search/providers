---
api_count: 4
api_specs:
- filename: openapi.json
  format: json
  label: Telefon Voice API
  slug: ''
  spec_type: OpenAPI
  url: https://api.telefon.example.com/v1/voice/openapi.json
- filename: openapi.json
  format: json
  label: Telefon SMS API
  slug: ''
  spec_type: OpenAPI
  url: https://api.telefon.example.com/v1/sms/openapi.json
- filename: openapi.json
  format: json
  label: Telefon Number Management API
  slug: ''
  spec_type: OpenAPI
  url: https://api.telefon.example.com/v1/numbers/openapi.json
- filename: openapi.json
  format: json
  label: Telefon Call Recording API
  slug: ''
  spec_type: OpenAPI
  url: https://api.telefon.example.com/v1/recording/openapi.json
apis:
- description: API for making and managing voice calls through the Telefon platform.
  name: Telefon Voice API
  slug: ''
- description: API for sending and receiving SMS messages.
  name: Telefon SMS API
  slug: ''
- description: API for purchasing, configuring, and managing phone numbers.
  name: Telefon Number Management API
  slug: ''
- description: API for recording, storing, and retrieving call recordings.
  name: Telefon Call Recording API
  slug: ''
common:
- title: ''
  type: Getting Started
  url: https://telefon.example.com/docs/getting-started
- title: ''
  type: Authentication
  url: https://telefon.example.com/docs/authentication
- title: ''
  type: SDKs
  url: https://telefon.example.com/sdks
- title: ''
  type: Status Page
  url: https://status.telefon.example.com
- title: ''
  type: Terms of Service
  url: https://telefon.example.com/terms
- title: ''
  type: Privacy Policy
  url: https://telefon.example.com/privacy
- title: ''
  type: Support
  url: https://telefon.example.com/support
- title: ''
  type: Blog
  url: https://telefon.example.com/blog
- title: ''
  type: Change Log
  url: https://telefon.example.com/changelog
- title: ''
  type: Pricing
  url: https://telefon.example.com/pricing
created: '2024-01-15'
description: APIs for the Telefon communication platform.
features: []
image: https://example.com/telefon-logo.png
integrations: []
layout: provider
modified: '2026-03-16'
name: Telefon
skills: []
slug: telefon
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Telefon\ndescription: >-\n  APIs for the Telefon communication platform.\nimage: https://example.com/telefon-logo.png\ncreated: '2024-01-15'\nmodified: '2026-03-16'\nurl: https://telefon.example.com/apis.json\nspecificationVersion: '0.16'\napis:\n  - name: Telefon Voice API\n    description: >-\n      API for making and managing voice calls through the Telefon platform.\n    image: https://example.com/telefon-voice-icon.png\n    humanURL: https://telefon.example.com/docs/voice\n    baseURL: https://api.telefon.example.com/v1/voice\n    version: v1\n    tags:\n      - Calls\n      - Communications\n      - Telephony\n      - Voice\n    properties:\n      - type: Documentation\n        url: https://telefon.example.com/docs/voice/reference\n      - type: OpenAPI\n        url: https://api.telefon.example.com/v1/voice/openapi.json\n      - type: Swagger\n        url: https://api.telefon.example.com/v1/voice/swagger.json\n      - type: Authentication\n        url: https://telefon.example.com/docs/authentication\n\
  \      - type: Pricing\n        url: https://telefon.example.com/pricing/voice\n    contact:\n      - FN: Telefon Voice API Support\n        email: voice-api@telefon.example.com\n        X-twitter: telefonvoice\n  - name: Telefon SMS API\n    description: >-\n      API for sending and receiving SMS messages.\n    image: https://example.com/telefon-sms-icon.png\n    humanURL: https://telefon.example.com/docs/sms\n    baseURL: https://api.telefon.example.com/v1/sms\n    version: v1\n    tags:\n      - Communications\n      - Messaging\n      - SMS\n      - Text Messages\n    properties:\n      - type: Documentation\n        url: https://telefon.example.com/docs/sms/reference\n      - type: OpenAPI\n        url: https://api.telefon.example.com/v1/sms/openapi.json\n      - type: Swagger\n        url: https://api.telefon.example.com/v1/sms/swagger.json\n      - type: Authentication\n        url: https://telefon.example.com/docs/authentication\n      - type: Pricing\n        url: https://telefon.example.com/pricing/sms\n\
  \      - type: Rate Limits\n        url: https://telefon.example.com/docs/sms/rate-limits\n    contact:\n      - FN: Telefon SMS API Support\n        email: sms-api@telefon.example.com\n        X-twitter: telefonsms\n  - name: Telefon Number Management API\n    description: >-\n      API for purchasing, configuring, and managing phone numbers.\n    image: https://example.com/telefon-numbers-icon.png\n    humanURL: https://telefon.example.com/docs/numbers\n    baseURL: https://api.telefon.example.com/v1/numbers\n    version: v1\n    tags:\n      - Number Management\n      - Number Provisioning\n      - Phone Numbers\n      - Telephony\n    properties:\n      - type: Documentation\n        url: https://telefon.example.com/docs/numbers/reference\n      - type: OpenAPI\n        url: https://api.telefon.example.com/v1/numbers/openapi.json\n      - type: Authentication\n        url: https://telefon.example.com/docs/authentication\n      - type: Pricing\n        url: https://telefon.example.com/pricing/numbers\n\
  \    contact:\n      - FN: Telefon Numbers API Support\n        email: numbers-api@telefon.example.com\n  - name: Telefon Call Recording API\n    description: >-\n      API for recording, storing, and retrieving call recordings.\n    image: https://example.com/telefon-recording-icon.png\n    humanURL: https://telefon.example.com/docs/recording\n    baseURL: https://api.telefon.example.com/v1/recording\n    version: v1\n    tags:\n      - Audio\n      - Call Recording\n      - Compliance\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://telefon.example.com/docs/recording/reference\n      - type: OpenAPI\n        url: https://api.telefon.example.com/v1/recording/openapi.json\n      - type: Authentication\n        url: https://telefon.example.com/docs/authentication\n      - type: Privacy Policy\n        url: https://telefon.example.com/privacy\n      - type: Compliance\n        url: https://telefon.example.com/compliance\n    contact:\n      - FN: Telefon\
  \ Recording API Support\n        email: recording-api@telefon.example.com\ncommon:\n  - type: Getting Started\n    url: https://telefon.example.com/docs/getting-started\n  - type: Authentication\n    url: https://telefon.example.com/docs/authentication\n  - type: SDKs\n    url: https://telefon.example.com/sdks\n  - type: Status Page\n    url: https://status.telefon.example.com\n  - type: Terms of Service\n    url: https://telefon.example.com/terms\n  - type: Privacy Policy\n    url: https://telefon.example.com/privacy\n  - type: Support\n    url: https://telefon.example.com/support\n  - type: Blog\n    url: https://telefon.example.com/blog\n  - type: Change Log\n    url: https://telefon.example.com/changelog\n  - type: Pricing\n    url: https://telefon.example.com/pricing\nmaintainers:\n  - FN: Telefon API Team\n    email: api-team@telefon.example.com\n    X-twitter: telefonapi\n    X-github: telefon\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/telefon/refs/heads/main/apis.yml
tags: []
url: https://telefon.example.com/apis.json
use_cases: []
---
