---
api_count: 2
api_specs:
- filename: united-airlines-ndc-openapi.yml
  format: yaml
  label: United Airlines NDC API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/openapi/united-airlines-ndc-openapi.yml
apis:
- description: United Airlines NDC (New Distribution Capability) API enables travel agencies, online booking tools, and corporate travel platforms to search, book, and service United flights with full access to cont
  name: United Airlines NDC API
  slug: ''
- description: United Airlines Flight Status API providing real-time flight status including estimated and actual departure and arrival times, gate information, delays, and flight tracking for United-operated flight
  name: United Airlines Flight Status API
  slug: ''
capabilities:
- description: United Airlines flight booking and travel management capability combining NDC shopping, booking creation, servicing, and flight status into a unified workflow for travel agencies, corporate booking to
  name: United Airlines Flight Booking
  slug: flight-booking
common:
- title: ''
  type: Website
  url: https://www.united.com
- title: ''
  type: Developer Portal
  url: https://united.business/NDC-corporate
- title: ''
  type: NDC Capabilities
  url: https://united.business/NDC-capabilities
- title: ''
  type: Contact
  url: https://united.business/contact-form.html
- title: ''
  type: IATA Developer Portal
  url: https://api.developer.iata.org/united-airlines-united-airlines-default/api/flight-status2
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/united-airlines
- title: ''
  type: X
  url: https://twitter.com/united
- title: ''
  type: MileagePlus
  url: https://www.united.com/en/us/fly/mileageplus.html
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/openapi/united-airlines-ndc-openapi.yml
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/rules/united-airlines-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/capabilities/flight-booking.yaml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/json-schema/united-airlines-booking-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/json-schema/united-airlines-flight-status-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/json-ld/united-airlines-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/vocabulary/united-airlines-vocabulary.yml
created: '2026-03-21'
description: United Airlines is a major American airline headquartered in Chicago, Illinois. It operates one of the largest route networks in the world with hubs in Chicago, Denver, Houston, Los Angeles, New York, San Francisco, and Washington, D.C. United provides NDC (New Distribution Capability) APIs for flight shopping, booking, and servicing, as well as corporate travel integration capabilities.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: United Airlines Context
  property_count: 41
  slug: united-airlines-context
layout: provider
modified: '2026-05-03'
name: United Airlines
rules:
- name: United Airlines API Rules
  rule_count: 15
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 9
  slug: united-airlines-rules
skills: []
slug: united-airlines
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: united-airlines\nurl: https://raw.githubusercontent.com/api-evangelist/united-airlines/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-05-03'\nname: United Airlines\ndescription: >-\n  United Airlines is a major American airline headquartered in Chicago, Illinois.\n  It operates one of the largest route networks in the world with hubs in Chicago,\n  Denver, Houston, Los Angeles, New York, San Francisco, and Washington, D.C.\n  United provides NDC (New Distribution Capability) APIs for flight shopping,\n  booking, and servicing, as well as corporate travel integration capabilities.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Airlines\n  - Travel\n  - Flight Booking\n  - NDC\n  - Loyalty\n  - Fortune 100\napis:\n  - name: United Airlines NDC API\n    description: >-\n      United Airlines NDC (New Distribution Capability) API enables travel agencies,\n      online booking tools, and corporate travel platforms\
  \ to search, book, and\n      service United flights with full access to continuous pricing, dynamic bundled\n      fares, ancillary products, hold bookings, exchanges, refunds, cancellations,\n      schedule change alerts, and ARC/BSP reporting. Supports 30+ bundle combinations.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://united.business/NDC-corporate\n    baseURL: https://api.united.com/v1\n    tags:\n      - Airlines\n      - Flight Booking\n      - NDC\n      - Travel\n      - Shopping\n      - Booking\n      - Servicing\n    properties:\n      - type: Documentation\n        url: https://united.business/NDC-corporate\n      - type: NDC Capabilities\n        url: https://united.business/NDC-capabilities\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/openapi/united-airlines-ndc-openapi.yml\n    contact:\n      - FN: United Airlines NDC Support\n        email:\
  \ ndcagency@united.com\n  - name: United Airlines Flight Status API\n    description: >-\n      United Airlines Flight Status API providing real-time flight status including\n      estimated and actual departure and arrival times, gate information, delays,\n      and flight tracking for United-operated flights.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://api.developer.iata.org/united-airlines-united-airlines-default/api/flight-status2\n    baseURL: https://api.united.com/v1\n    tags:\n      - Airlines\n      - Flight Status\n      - Real-Time\n      - IATA\n    properties:\n      - type: Documentation\n        url: https://api.developer.iata.org/united-airlines-united-airlines-default/api/flight-status2\ncommon:\n  - type: Website\n    url: https://www.united.com\n  - type: Developer Portal\n    url: https://united.business/NDC-corporate\n  - type: NDC Capabilities\n    url: https://united.business/NDC-capabilities\n  -\
  \ type: Contact\n    url: https://united.business/contact-form.html\n  - type: IATA Developer Portal\n    url: https://api.developer.iata.org/united-airlines-united-airlines-default/api/flight-status2\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/united-airlines\n  - type: X\n    url: https://twitter.com/united\n  - type: MileagePlus\n    url: https://www.united.com/en/us/fly/mileageplus.html\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/openapi/united-airlines-ndc-openapi.yml\n  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/rules/united-airlines-rules.yml\n  - type: NaftikoCapabilities\n    url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/capabilities/flight-booking.yaml\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/json-schema/united-airlines-booking-schema.json\n  - type: JSONSchema\n\
  \    url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/json-schema/united-airlines-flight-status-schema.json\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/json-ld/united-airlines-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/vocabulary/united-airlines-vocabulary.yml\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/united-airlines/refs/heads/main/apis.yml
tags:
- Airlines
- Travel
- Flight Booking
- NDC
- Loyalty
- Fortune 100
url: https://raw.githubusercontent.com/api-evangelist/united-airlines/refs/heads/main/apis.yml
use_cases: []
---
