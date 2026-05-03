---
api_count: 3
api_specs:
- filename: telefoon-voice-openapi.yml
  format: yaml
  label: Telefoon Voice API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefoon/refs/heads/main/openapi/telefoon-voice-openapi.yml
- filename: telefoon-sms-openapi.yml
  format: yaml
  label: Telefoon SMS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefoon/refs/heads/main/openapi/telefoon-sms-openapi.yml
- filename: telefoon-numbers-openapi.yml
  format: yaml
  label: Telefoon Number Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefoon/refs/heads/main/openapi/telefoon-numbers-openapi.yml
apis:
- description: Programmable voice API for making and receiving calls across European networks. Supports outbound dialing, inbound call handling, IVR with multi-language text-to-speech (Dutch, French, German, English
  name: Telefoon Voice API
  slug: ''
- description: Send and receive SMS messages across European networks with full GDPR compliance. Supports A2P messaging, two-way SMS, delivery reports, unicode for European character sets (Dutch, German, French), bu
  name: Telefoon SMS API
  slug: ''
- description: Search, purchase, and manage Dutch, Belgian, German, and broader European phone numbers. Supports local geographic numbers (NDC/area codes), national numbers, toll-free (0800), premium-rate (0900), an
  name: Telefoon Number Management API
  slug: ''
capabilities:
- description: Unified GDPR-compliant communications capability for European markets. Combines Telefoon Voice and SMS APIs for Dutch, Belgian, German, and EU-wide communications. Supports branded sender IDs, multi-l
  name: Telefoon EU Communications
  slug: eu-communications
common:
- title: ''
  type: Authentication
  url: https://developers.telefoon.com/authentication
- title: ''
  type: Getting Started
  url: https://developers.telefoon.com/getting-started
- title: ''
  type: Rate Limits
  url: https://developers.telefoon.com/rate-limits
- title: ''
  type: GDPR
  url: https://www.telefoon.com/gdpr
- title: ''
  type: Status
  url: https://status.telefoon.com
- title: ''
  type: Terms of Service
  url: https://www.telefoon.com/terms
- title: ''
  type: Privacy Policy
  url: https://www.telefoon.com/privacy
- title: ''
  type: Pricing
  url: https://www.telefoon.com/pricing
- title: ''
  type: Support
  url: https://www.telefoon.com/support
- title: ''
  type: Blog
  url: https://blog.telefoon.com
created: '2024-01-01'
description: Telefoon is a cloud telephony and communications platform offering programmable voice, SMS, and number management APIs tailored for European markets. Built for GDPR compliance and EU regulatory requirements, Telefoon provides developers with REST APIs to build voice calling, SMS notification, number provisioning, and interactive voice response (IVR) solutions. The platform supports Dutch, Belgian, German, and broader European telecommunications infrastructure with local number availability and EU data residency.
features: []
image: https://www.telefoon.com/logo.png
integrations: []
jsonld:
- class_count: 4
  name: Telefoon Context
  property_count: 18
  slug: telefoon-context
layout: provider
modified: '2026-05-03'
name: Telefoon
rules:
- name: Telefoon API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 5
  slug: telefoon-rules
skills: []
slug: telefoon
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Telefoon\ndescription: >-\n  Telefoon is a cloud telephony and communications platform offering programmable\n  voice, SMS, and number management APIs tailored for European markets. Built for\n  GDPR compliance and EU regulatory requirements, Telefoon provides developers with\n  REST APIs to build voice calling, SMS notification, number provisioning, and\n  interactive voice response (IVR) solutions. The platform supports Dutch, Belgian,\n  German, and broader European telecommunications infrastructure with local number\n  availability and EU data residency.\nimage: https://www.telefoon.com/logo.png\nurl: https://www.telefoon.com\ntype: Index\ntags:\n  - Belgium\n  - CPaaS\n  - EU Data Residency\n  - Europe\n  - GDPR Compliant\n  - Messaging\n  - Netherlands\n  - Number Provisioning\n  - SMS\n  - Telephony\n  - Voice\ncreated: '2024-01-01'\nmodified: '2026-05-03'\napis:\n  - name: Telefoon Voice API\n    description: >-\n      Programmable voice API for making and receiving\
  \ calls across European networks.\n      Supports outbound dialing, inbound call handling, IVR with multi-language\n      text-to-speech (Dutch, French, German, English), call conferencing, call\n      recording, and SIP trunking. Built with EU data residency and GDPR compliance\n      for European enterprise customers.\n    image: https://www.telefoon.com/images/voice-api.png\n    humanURL: https://developers.telefoon.com/voice\n    baseURL: https://api.telefoon.com/v1/voice\n    tags:\n      - Calls\n      - EU Telephony\n      - IVR\n      - Netherlands\n      - Telephony\n      - TTS\n      - Voice\n    properties:\n      - type: Documentation\n        url: https://developers.telefoon.com/voice\n      - type: OpenAPI\n        url: openapi/telefoon-voice-openapi.yml\n      - type: Authentication\n        url: https://developers.telefoon.com/authentication\n      - type: GettingStarted\n        url: https://developers.telefoon.com/getting-started\n      - type: RateLimits\n        url:\
  \ https://developers.telefoon.com/rate-limits\n    contact:\n      - type: Support\n        url: https://www.telefoon.com/support\n      - type: Email\n        url: mailto:api-support@telefoon.com\n\n  - name: Telefoon SMS API\n    description: >-\n      Send and receive SMS messages across European networks with full GDPR\n      compliance. Supports A2P messaging, two-way SMS, delivery reports, unicode\n      for European character sets (Dutch, German, French), bulk SMS, and message\n      archiving for GDPR audit trails. Provides SMS sender ID registration for\n      branded messaging in EU markets.\n    image: https://www.telefoon.com/images/sms-api.png\n    humanURL: https://developers.telefoon.com/sms\n    baseURL: https://api.telefoon.com/v1/sms\n    tags:\n      - A2P Messaging\n      - Europe\n      - GDPR\n      - Messaging\n      - SMS\n      - Sender ID\n    properties:\n      - type: Documentation\n        url: https://developers.telefoon.com/sms\n      - type: OpenAPI\n  \
  \      url: openapi/telefoon-sms-openapi.yml\n      - type: Authentication\n        url: https://developers.telefoon.com/authentication\n      - type: RateLimits\n        url: https://developers.telefoon.com/rate-limits\n    contact:\n      - type: Support\n        url: https://www.telefoon.com/support\n      - type: Email\n        url: mailto:api-support@telefoon.com\n\n  - name: Telefoon Number Management API\n    description: >-\n      Search, purchase, and manage Dutch, Belgian, German, and broader European\n      phone numbers. Supports local geographic numbers (NDC/area codes), national\n      numbers, toll-free (0800), premium-rate (0900), and service numbers (0906).\n      Handles regulatory requirements including address registration for Dutch and\n      Belgian number types and porting requests (number portability).\n    image: https://www.telefoon.com/images/numbers-api.png\n    humanURL: https://developers.telefoon.com/numbers\n    baseURL: https://api.telefoon.com/v1/numbers\n\
  \    tags:\n      - Belgian Numbers\n      - Dutch Numbers\n      - EU Numbers\n      - Number Management\n      - Number Portability\n      - Number Provisioning\n      - Phone Numbers\n    properties:\n      - type: Documentation\n        url: https://developers.telefoon.com/numbers\n      - type: OpenAPI\n        url: openapi/telefoon-numbers-openapi.yml\n      - type: Authentication\n        url: https://developers.telefoon.com/authentication\n    contact:\n      - type: Support\n        url: https://www.telefoon.com/support\n      - type: Email\n        url: mailto:api-support@telefoon.com\n\ncommon:\n  - type: Authentication\n    url: https://developers.telefoon.com/authentication\n  - type: Getting Started\n    url: https://developers.telefoon.com/getting-started\n  - type: Rate Limits\n    url: https://developers.telefoon.com/rate-limits\n  - type: GDPR\n    url: https://www.telefoon.com/gdpr\n  - type: Status\n    url: https://status.telefoon.com\n  - type: Terms of Service\n\
  \    url: https://www.telefoon.com/terms\n  - type: Privacy Policy\n    url: https://www.telefoon.com/privacy\n  - type: Pricing\n    url: https://www.telefoon.com/pricing\n  - type: Support\n    url: https://www.telefoon.com/support\n  - type: Blog\n    url: https://blog.telefoon.com\nmaintainers:\n  - name: Telefoon API Team\n    email: api-team@telefoon.com\n    url: https://www.telefoon.com/about/api-team\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/telefoon/refs/heads/main/apis.yml
tags:
- Belgium
- CPaaS
- EU Data Residency
- Europe
- GDPR Compliant
- Messaging
- Netherlands
- Number Provisioning
- SMS
- Telephony
- Voice
url: https://www.telefoon.com
use_cases: []
---
