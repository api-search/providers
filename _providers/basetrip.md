---
api_count: 1
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
