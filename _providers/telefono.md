---
api_count: 3
api_specs:
- filename: telefono-validation-openapi.yml
  format: yaml
  label: Telefono Phone Validation API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefono/refs/heads/main/openapi/telefono-validation-openapi.yml
- filename: telefono-carrier-openapi.yml
  format: yaml
  label: Telefono Carrier Lookup API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefono/refs/heads/main/openapi/telefono-carrier-openapi.yml
- filename: telefono-format-openapi.yml
  format: yaml
  label: Telefono Number Formatting API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefono/refs/heads/main/openapi/telefono-format-openapi.yml
apis:
- description: Validate phone numbers in real-time to determine if they are valid, active, and reachable. Returns validity status, number type (mobile, landline, VoIP, toll-free), formatted number in E.164 and natio
  name: Telefono Phone Validation API
  slug: ''
- description: Look up carrier and network information for any phone number worldwide. Returns the current carrier name, network type (GSM, CDMA, UMTS, LTE, 5G), mobile country code (MCC), mobile network code (MNC),
  name: Telefono Carrier Lookup API
  slug: ''
- description: Format phone numbers consistently across different national and international formats. Convert between E.164, national, international, and RFC3966 formats. Supports parsing of phone numbers with count
  name: Telefono Number Formatting API
  slug: ''
capabilities:
- description: Unified phone number intelligence capability combining validation, carrier lookup, and number formatting APIs. Designed for developers building fraud prevention, user verification, data enrichment, an
  name: Telefono Phone Intelligence
  slug: phone-intelligence
common:
- title: ''
  type: Authentication
  url: https://developers.telefono.com/authentication
- title: ''
  type: Getting Started
  url: https://developers.telefono.com/getting-started
- title: ''
  type: Rate Limits
  url: https://developers.telefono.com/rate-limits
- title: ''
  type: Sign Up
  url: https://www.telefono.com/signup
- title: ''
  type: Pricing
  url: https://www.telefono.com/pricing
- title: ''
  type: Terms of Service
  url: https://www.telefono.com/terms
- title: ''
  type: Privacy Policy
  url: https://www.telefono.com/privacy
- title: ''
  type: Status
  url: https://status.telefono.com
- title: ''
  type: Support
  url: https://www.telefono.com/support
- title: ''
  type: GitHub
  url: https://github.com/telefono-api
created: '2024-01-15'
description: Telefono is a phone number intelligence and validation API platform providing real-time phone number lookup, validation, carrier information, line type detection, and number formatting services for developers. The platform helps businesses verify user phone numbers, detect fraud, improve deliverability of SMS campaigns, and enrich contact data with carrier and geographic information.
features: []
image: https://www.telefono.com/logo.png
integrations: []
jsonld:
- class_count: 4
  name: Telefono Context
  property_count: 18
  slug: telefono-context
layout: provider
modified: '2026-05-03'
name: Telefono
rules:
- name: Telefono API Rules
  rule_count: 11
  severity_counts:
    error: 5
    hint: 0
    info: 2
    warn: 4
  slug: telefono-rules
skills: []
slug: telefono
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Telefono\ndescription: >-\n  Telefono is a phone number intelligence and validation API platform providing\n  real-time phone number lookup, validation, carrier information, line type\n  detection, and number formatting services for developers. The platform helps\n  businesses verify user phone numbers, detect fraud, improve deliverability\n  of SMS campaigns, and enrich contact data with carrier and geographic information.\nimage: https://www.telefono.com/logo.png\nurl: https://www.telefono.com\ntype: Index\ntags:\n  - Carrier Lookup\n  - Data Enrichment\n  - Fraud Prevention\n  - Number Intelligence\n  - Number Verification\n  - Phone Lookup\n  - Phone Validation\n  - Telecommunications\ncreated: '2024-01-15'\nmodified: '2026-05-03'\nspecificationVersion: '0.18'\napis:\n  - name: Telefono Phone Validation API\n    description: >-\n      Validate phone numbers in real-time to determine if they are valid, active,\n      and reachable. Returns validity status, number type\
  \ (mobile, landline, VoIP,\n      toll-free), formatted number in E.164 and national formats, country information,\n      and whether the number is likely a virtual or disposable number.\n    image: https://www.telefono.com/api-logo.png\n    humanURL: https://developers.telefono.com/validation\n    baseURL: https://api.telefono.com/v1/validate\n    version: '1.0'\n    tags:\n      - E.164 Format\n      - Number Formatting\n      - Number Verification\n      - Phone Validation\n      - Real-Time Validation\n    properties:\n      - type: Documentation\n        url: https://developers.telefono.com/validation\n      - type: OpenAPI\n        url: openapi/telefono-validation-openapi.yml\n      - type: Authentication\n        url: https://developers.telefono.com/authentication\n      - type: GettingStarted\n        url: https://developers.telefono.com/getting-started\n      - type: Pricing\n        url: https://www.telefono.com/pricing\n      - type: RateLimits\n        url: https://developers.telefono.com/rate-limits\n\
  \    contact:\n      - type: Email\n        url: mailto:support@telefono.com\n      - type: Support\n        url: https://www.telefono.com/support\n\n  - name: Telefono Carrier Lookup API\n    description: >-\n      Look up carrier and network information for any phone number worldwide.\n      Returns the current carrier name, network type (GSM, CDMA, UMTS, LTE, 5G),\n      mobile country code (MCC), mobile network code (MNC), and roaming status.\n      Supports real-time HLR (Home Location Register) lookups for accurate\n      portability-aware carrier detection.\n    image: https://www.telefono.com/api-logo.png\n    humanURL: https://developers.telefono.com/carrier\n    baseURL: https://api.telefono.com/v1/carrier\n    version: '1.0'\n    tags:\n      - Carrier Detection\n      - Carrier Lookup\n      - HLR\n      - MCC MNC\n      - Network Type\n      - Telecommunications\n    properties:\n      - type: Documentation\n        url: https://developers.telefono.com/carrier\n      - type:\
  \ OpenAPI\n        url: openapi/telefono-carrier-openapi.yml\n      - type: Authentication\n        url: https://developers.telefono.com/authentication\n      - type: Pricing\n        url: https://www.telefono.com/pricing/carrier\n    contact:\n      - type: Email\n        url: mailto:support@telefono.com\n\n  - name: Telefono Number Formatting API\n    description: >-\n      Format phone numbers consistently across different national and international\n      formats. Convert between E.164, national, international, and RFC3966 formats.\n      Supports parsing of phone numbers with country code hints, extracting country\n      codes, and generating click-to-call compatible URIs.\n    image: https://www.telefono.com/api-logo.png\n    humanURL: https://developers.telefono.com/format\n    baseURL: https://api.telefono.com/v1/format\n    version: '1.0'\n    tags:\n      - E.164\n      - International Format\n      - National Format\n      - Number Formatting\n      - Phone Parsing\n    properties:\n\
  \      - type: Documentation\n        url: https://developers.telefono.com/format\n      - type: OpenAPI\n        url: openapi/telefono-format-openapi.yml\n      - type: Authentication\n        url: https://developers.telefono.com/authentication\n    contact:\n      - type: Email\n        url: mailto:support@telefono.com\n\ncommon:\n  - type: Authentication\n    url: https://developers.telefono.com/authentication\n  - type: Getting Started\n    url: https://developers.telefono.com/getting-started\n  - type: Rate Limits\n    url: https://developers.telefono.com/rate-limits\n  - type: Sign Up\n    url: https://www.telefono.com/signup\n  - type: Pricing\n    url: https://www.telefono.com/pricing\n  - type: Terms of Service\n    url: https://www.telefono.com/terms\n  - type: Privacy Policy\n    url: https://www.telefono.com/privacy\n  - type: Status\n    url: https://status.telefono.com\n  - type: Support\n    url: https://www.telefono.com/support\n  - type: GitHub\n    url: https://github.com/telefono-api\n\
  maintainers:\n  - name: Telefono Team\n    email: api@telefono.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/telefono/refs/heads/main/apis.yml
tags:
- Carrier Lookup
- Data Enrichment
- Fraud Prevention
- Number Intelligence
- Number Verification
- Phone Lookup
- Phone Validation
- Telecommunications
url: https://www.telefono.com
use_cases: []
---
