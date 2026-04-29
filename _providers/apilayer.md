---
api_count: 1
apis:
- description: 'The APILayer Marketplace API provides access to 100+ APIs across geolocation, currency, weather, dev tools, marketing, finance, security, and AI/ML categories. Individual APIs include IPstack, Fixer, '
  name: APILayer Marketplace API
  slug: apilayer-api
common:
- title: ''
  type: Website
  url: https://apilayer.com/
- title: ''
  type: Documentation
  url: https://apilayer.com/
- title: ''
  type: Pricing
  url: https://apilayer.com/pricing
- title: ''
  type: SignUp
  url: https://apilayer.com/signup
- title: ''
  type: Login
  url: https://apilayer.com/login
- title: ''
  type: Blog
  url: https://blog.apilayer.com/
created: '2025-03-01'
description: APILayer is an API marketplace and hub that enables developers to discover, integrate, and build with high-quality, reliable API services. The platform hosts 100+ APIs across categories including geolocation, currency, weather, dev tools, marketing, finance, security, and AI/ML, serving 445,000+ developers with 30 million+ API calls monthly.
features:
- description: Browse and integrate 100+ high-quality APIs across categories including geolocation, currency, weather, dev tools, and more.
  name: API Marketplace
- description: Single API key management across multiple APIs from the APILayer platform.
  name: Unified Authentication
- description: High-performance, reliable API infrastructure with global CDN for low-latency responses.
  name: Low Latency Infrastructure
- description: Centralized dashboard to manage API subscriptions, monitor usage, and access documentation.
  name: Developer Dashboard
- description: Real-time usage tracking and analytics across all subscribed APIs.
  name: Usage Analytics
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: IP geolocation API for geographic profiling and location intelligence.
  name: IPstack
- description: Real-time and historical currency exchange rate data API.
  name: Fixer
- description: Real-time weather data and forecasting API.
  name: Weatherstack
- description: Search engine results page scraping and SERP data API.
  name: Serpstack
- description: Live and historical news data API for media monitoring.
  name: Mediastack
- description: Global phone number validation and carrier lookup API.
  name: Numverify
- description: Real-time cryptocurrency exchange rate data API.
  name: Coinlayer
- description: HTML to PDF conversion and document generation API.
  name: Pdflayer
jsonld:
- class_count: 12
  name: Apilayer Context
  property_count: 1
  slug: apilayer-context
layout: provider
modified: '2026-04-19'
name: APILayer
skills: []
slug: apilayer
solutions:
- description: Limited free tier for each API to explore and prototype integrations.
  name: Free Plan
- description: Entry-level paid plan with increased request limits for individual APIs.
  name: Basic Plan
- description: Higher volume plans for production applications requiring reliable API access.
  name: Professional Plan
- description: Custom volume and SLA guarantees for enterprise-scale API consumption.
  name: Enterprise Plan
source_filename: apis.yml
source_yaml: "aid: apilayer\nname: APILayer\ndescription: >-\n  APILayer is an API marketplace and hub that enables developers to discover,\n  integrate, and build with high-quality, reliable API services. The platform\n  hosts 100+ APIs across categories including geolocation, currency, weather,\n  dev tools, marketing, finance, security, and AI/ML, serving 445,000+\n  developers with 30 million+ API calls monthly.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Catalog\n  - API Discovery\n  - API Marketplace\n  - Developer Tools\n  - SaaS APIs\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apilayer/refs/heads/main/apis.yml\ncreated: '2025-03-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apilayer:apilayer-api\n    name: APILayer Marketplace API\n    description: >-\n      The APILayer Marketplace API provides access to 100+ APIs across\n      geolocation, currency, weather, dev tools,\
  \ marketing, finance, security,\n      and AI/ML categories. Individual APIs include IPstack, Fixer,\n      Currencylayer, Weatherstack, Serpstack, Mediastack, and many more,\n      each with their own endpoints and authentication.\n    humanURL: https://apilayer.com/\n    baseURL: https://api.apilayer.com\n    tags:\n      - API Marketplace\n      - Currency\n      - Geolocation\n      - Weather\n    properties:\n      - type: Documentation\n        url: https://apilayer.com/\n      - type: Pricing\n        url: https://apilayer.com/pricing\n      - type: JSONSchema\n        url: json-schema/apilayer-api-schema.json\n      - type: JSON-LD\n        url: json-ld/apilayer-context.jsonld\ncommon:\n  - type: Website\n    url: https://apilayer.com/\n  - type: Documentation\n    url: https://apilayer.com/\n  - type: Pricing\n    url: https://apilayer.com/pricing\n  - type: SignUp\n    url: https://apilayer.com/signup\n  - type: Login\n    url: https://apilayer.com/login\n  - type: Blog\n   \
  \ url: https://blog.apilayer.com/\n  - type: Features\n    data:\n      - name: API Marketplace\n        description: Browse and integrate 100+ high-quality APIs across categories including geolocation, currency, weather, dev tools, and more.\n      - name: Unified Authentication\n        description: Single API key management across multiple APIs from the APILayer platform.\n      - name: Low Latency Infrastructure\n        description: High-performance, reliable API infrastructure with global CDN for low-latency responses.\n      - name: Developer Dashboard\n        description: Centralized dashboard to manage API subscriptions, monitor usage, and access documentation.\n      - name: Usage Analytics\n        description: Real-time usage tracking and analytics across all subscribed APIs.\n  - type: UseCases\n    data:\n      - name: IP Geolocation\n        description: Determine user location, timezone, and geographic data from IP addresses using IPstack or IPapi.\n      - name: Currency\
  \ Conversion\n        description: Access real-time and historical currency exchange rates using Fixer or Currencylayer APIs.\n      - name: Weather Data\n        description: Integrate real-time weather forecasts and historical weather data using Weatherstack.\n      - name: Search Engine Data\n        description: Scrape search engine results programmatically using the Serpstack API.\n      - name: Phone Validation\n        description: Validate and look up phone number details globally using Numverify.\n  - type: Integrations\n    data:\n      - name: IPstack\n        description: IP geolocation API for geographic profiling and location intelligence.\n      - name: Fixer\n        description: Real-time and historical currency exchange rate data API.\n      - name: Weatherstack\n        description: Real-time weather data and forecasting API.\n      - name: Serpstack\n        description: Search engine results page scraping and SERP data API.\n      - name: Mediastack\n        description:\
  \ Live and historical news data API for media monitoring.\n      - name: Numverify\n        description: Global phone number validation and carrier lookup API.\n      - name: Coinlayer\n        description: Real-time cryptocurrency exchange rate data API.\n      - name: Pdflayer\n        description: HTML to PDF conversion and document generation API.\n  - type: Solutions\n    data:\n      - name: Free Plan\n        description: Limited free tier for each API to explore and prototype integrations.\n      - name: Basic Plan\n        description: Entry-level paid plan with increased request limits for individual APIs.\n      - name: Professional Plan\n        description: Higher volume plans for production applications requiring reliable API access.\n      - name: Enterprise Plan\n        description: Custom volume and SLA guarantees for enterprise-scale API consumption.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apilayer/refs/heads/main/apis.yml
tags:
- API Catalog
- API Discovery
- API Marketplace
- Developer Tools
- SaaS APIs
url: https://raw.githubusercontent.com/api-evangelist/apilayer/refs/heads/main/apis.yml
use_cases:
- description: Determine user location, timezone, and geographic data from IP addresses using IPstack or IPapi.
  name: IP Geolocation
- description: Access real-time and historical currency exchange rates using Fixer or Currencylayer APIs.
  name: Currency Conversion
- description: Integrate real-time weather forecasts and historical weather data using Weatherstack.
  name: Weather Data
- description: Scrape search engine results programmatically using the Serpstack API.
  name: Search Engine Data
- description: Validate and look up phone number details globally using Numverify.
  name: Phone Validation
---
