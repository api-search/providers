---
api_count: 1
api_specs:
- filename: basetrip-api-openapi.yml
  format: yaml
  label: Basetrip API
  slug: basetrip-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/basetrip/refs/heads/main/openapi/basetrip-api-openapi.yml
apis:
- description: The Basetrip API provides travel intelligence data including country details, city lists, travel phrases, safety ratings, visa requirements, cost estimates, and health advisories. Uses API key authent
  name: Basetrip API
  slug: basetrip-api
capabilities:
- description: ''
  name: Travel Intelligence
  slug: travel-intelligence
common:
- title: ''
  type: Website
  url: https://www.thebasetrip.com/
- title: ''
  type: Documentation
  url: https://www.thebasetrip.com/en/documentation/v3
- title: ''
  type: SignUp
  url: https://www.thebasetrip.com/en/sign_up
- title: ''
  type: Pricing
  url: https://www.thebasetrip.com/en/pricing
- title: ''
  type: SpectralRules
  url: rules/basetrip-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/basetrip-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/travel-intelligence.yaml
- title: ''
  type: JSON-LD
  url: json-ld/basetrip-context.jsonld
created: '2024-11-13'
description: Basetrip is a travel intelligence platform providing APIs for country and city data, travel phrases, safety ratings, visa requirements, cost of living estimates, and health advisories. Designed to help travel apps, booking platforms, and trip planning tools differentiate their products and improve traveler experiences. The Basetrip API v3 uses API key authentication and returns JSON.
features:
- description: Country names, slugs, alpha-2 codes, capital, currency, languages, population, and timezone.
  name: Country Data
- description: City names, slugs, geographic coordinates, and timezone information per country.
  name: City Data
- description: Language phrases for travel in English, French, German, Italian, and Spanish.
  name: Travel Phrases
- description: Country safety ratings and travel advisory levels from 1 (normal) to 4 (do not travel).
  name: Safety Ratings
- description: Daily budget estimates for budget, mid-range, and luxury traveler tiers.
  name: Cost Estimates
- description: Visa requirement lookup by passport country and destination country.
  name: Visa Requirements
- description: Vaccination requirements, health risks, drinking water safety, and medical facility ratings.
  name: Health Advisories
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: Booking.com
- name: Airbnb
- name: TripAdvisor
- name: Skyscanner
- name: Expedia
jsonld:
- class_count: 8
  name: Basetrip Context
  property_count: 32
  slug: basetrip-context
layout: provider
modified: '2026-04-21'
name: Basetrip
rules:
- name: Basetrip API Rules
  rule_count: 15
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 9
  slug: basetrip-spectral-rules
skills: []
slug: basetrip
solutions: []
source_filename: apis.yml
source_yaml: "aid: basetrip\nurl: https://raw.githubusercontent.com/api-evangelist/basetrip/refs/heads/main/apis.yml\nname: Basetrip\ndescription: >-\n  Basetrip is a travel intelligence platform providing APIs for country and city\n  data, travel phrases, safety ratings, visa requirements, cost of living estimates,\n  and health advisories. Designed to help travel apps, booking platforms, and trip\n  planning tools differentiate their products and improve traveler experiences.\n  The Basetrip API v3 uses API key authentication and returns JSON.\ntags:\n  - Cities\n  - Countries\n  - Health\n  - Safety\n  - Travel\n  - Visa\ntype: Contract\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncreated: '2024-11-13'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\napis:\n  - aid: basetrip:basetrip-api\n    name: Basetrip API\n    tags:\n      - Cities\n      - Countries\n      - Health\n      - Phrases\n      - Safety\n      - Travel\n  \
  \    - Visa\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.thebasetrip.com/v3\n    humanURL: https://www.thebasetrip.com/en/documentation/v3\n    properties:\n      - url: https://www.thebasetrip.com/en/documentation/v3\n        type: Documentation\n      - url: openapi/basetrip-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Basetrip API provides travel intelligence data including country details,\n      city lists, travel phrases, safety ratings, visa requirements, cost estimates,\n      and health advisories. Uses API key authentication via X-API-Key header.\ncommon:\n  - type: Website\n    url: https://www.thebasetrip.com/\n    name: Basetrip\n  - type: Documentation\n    url: https://www.thebasetrip.com/en/documentation/v3\n    name: Basetrip API Documentation\n  - type: SignUp\n    url: https://www.thebasetrip.com/en/sign_up\n    name: Sign Up\n  - type: Pricing\n    url: https://www.thebasetrip.com/en/pricing\n\
  \    name: Pricing\n  - type: SpectralRules\n    url: rules/basetrip-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/basetrip-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/travel-intelligence.yaml\n  - type: JSON-LD\n    url: json-ld/basetrip-context.jsonld\n  - name: Features\n    type: Features\n    data:\n      - name: Country Data\n        description: Country names, slugs, alpha-2 codes, capital, currency, languages, population, and timezone.\n      - name: City Data\n        description: City names, slugs, geographic coordinates, and timezone information per country.\n      - name: Travel Phrases\n        description: Language phrases for travel in English, French, German, Italian, and Spanish.\n      - name: Safety Ratings\n        description: Country safety ratings and travel advisory levels from 1 (normal) to 4 (do not travel).\n      - name: Cost Estimates\n        description: Daily budget estimates for budget, mid-range, and luxury traveler\
  \ tiers.\n      - name: Visa Requirements\n        description: Visa requirement lookup by passport country and destination country.\n      - name: Health Advisories\n        description: Vaccination requirements, health risks, drinking water safety, and medical facility ratings.\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Travel App Integration\n        description: Embed country and city intelligence directly into travel booking apps.\n      - name: Trip Planning Tools\n        description: Provide travelers with safety, cost, and visa information before booking.\n      - name: Destination Guides\n        description: Power destination content with live data on safety, costs, and health.\n      - name: Travel Risk Assessment\n        description: Assess travel risk using safety ratings and health advisories for corporate travel.\n      - name: Language Assistance\n        description: Surface travel phrases in destination language for traveler communication tools.\n\
  \  - name: Integrations\n    type: Integrations\n    data:\n      - name: Booking.com\n      - name: Airbnb\n      - name: TripAdvisor\n      - name: Skyscanner\n      - name: Expedia\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/basetrip/refs/heads/main/apis.yml
tags:
- Cities
- Countries
- Health
- Safety
- Travel
- Visa
url: https://raw.githubusercontent.com/api-evangelist/basetrip/refs/heads/main/apis.yml
use_cases:
- description: Embed country and city intelligence directly into travel booking apps.
  name: Travel App Integration
- description: Provide travelers with safety, cost, and visa information before booking.
  name: Trip Planning Tools
- description: Power destination content with live data on safety, costs, and health.
  name: Destination Guides
- description: Assess travel risk using safety ratings and health advisories for corporate travel.
  name: Travel Risk Assessment
- description: Surface travel phrases in destination language for traveler communication tools.
  name: Language Assistance
---
