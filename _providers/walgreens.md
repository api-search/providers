---
api_count: 4
api_specs:
- filename: walgreens-store-locator-openapi.yml
  format: yaml
  label: Walgreens Store Locator API
  slug: walgreens-store-locator
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/openapi/walgreens-store-locator-openapi.yml
- filename: walgreens-prescription-refill-openapi.yml
  format: yaml
  label: Walgreens Prescription Refill API
  slug: walgreens-prescription-refill
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/openapi/walgreens-prescription-refill-openapi.yml
- filename: walgreens-vaccine-scheduling-openapi.yml
  format: yaml
  label: Walgreens Vaccine Scheduling API
  slug: walgreens-vaccine-scheduling
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/openapi/walgreens-vaccine-scheduling-openapi.yml
apis:
- description: Returns dynamic store location data and service information for 8,000+ Walgreens and Duane Reade locations across the United States. Supports search by geolocation, address, or zip code with filtering
  name: Walgreens Store Locator API
  slug: walgreens-store-locator
- description: Enables medication management application developers to process prescription refills or transfers to any Walgreens pharmacy location. Supports both barcode scanning for refill initiation and image-bas
  name: Walgreens Prescription Refill API
  slug: walgreens-prescription-refill
- description: Allows developers to integrate vaccine and immunization appointment booking capabilities including eligibility checking, timeslot availability, appointment holds, patient registration, and booking con
  name: Walgreens Vaccine Scheduling API
  slug: walgreens-vaccine-scheduling
- description: Enables developers to offer photo printing services at 8,000+ Walgreens and Duane Reade stores for same-day pickup. Supports native JSON API integration with potential revenue share commissions for qu
  name: Walgreens Photo Prints API
  slug: walgreens-photo-prints
capabilities:
- description: 'Workflow capability combining Walgreens Store Locator and Vaccine Scheduling APIs for pharmacy and healthcare applications. Enables end-to-end patient workflows: finding nearby Walgreens pharmacies, c'
  name: Walgreens Pharmacy and Healthcare
  slug: pharmacy-and-healthcare
common:
- title: ''
  type: Website
  url: https://www.walgreens.com
- title: ''
  type: Portal
  url: https://developer.walgreens.com
- title: ''
  type: Documentation
  url: https://developer.walgreens.com/apis
- title: ''
  type: Blog
  url: https://developer.walgreens.com/blog
- title: ''
  type: SignUp
  url: https://developer.walgreens.com/user/register
created: '2025-03-01'
description: Walgreens is one of the largest pharmacy-led health and wellbeing companies in the United States, operating over 8,000 locations nationwide. The Walgreens Developer Program provides APIs enabling third-party applications to integrate pharmacy prescription management, vaccine scheduling, retail shopping, store locations, and product inventory. The APIs support seamless healthcare delivery, prescription refills, immunization appointments, and retail e-commerce integrations for mobile and web applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 40
  name: Walgreens Context
  property_count: 4
  slug: walgreens-context
layout: provider
modified: '2026-05-03'
name: Walgreens
rules:
- name: Walgreens API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 6
  slug: walgreens-rules
skills: []
slug: walgreens
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: walgreens\nname: Walgreens\ndescription: >-\n  Walgreens is one of the largest pharmacy-led health and wellbeing companies in the\n  United States, operating over 8,000 locations nationwide. The Walgreens Developer\n  Program provides APIs enabling third-party applications to integrate pharmacy\n  prescription management, vaccine scheduling, retail shopping, store locations, and\n  product inventory. The APIs support seamless healthcare delivery, prescription refills,\n  immunization appointments, and retail e-commerce integrations for mobile and web\n  applications.\ntype: Index\nposition: Producer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Pharmacy\n  - Healthcare\n  - Retail\n  - Prescriptions\n  - Vaccines\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: walgreens:walgreens-store-locator\n\
  \    name: Walgreens Store Locator API\n    description: >-\n      Returns dynamic store location data and service information for 8,000+ Walgreens\n      and Duane Reade locations across the United States. Supports search by geolocation,\n      address, or zip code with filtering by store services such as 24-hour pharmacy,\n      drive-thru, healthcare clinic, photo lab, flu shots, and immunization services.\n    humanURL: https://developer.walgreens.com/api/storelocator/rest\n    baseURL: https://services.walgreens.com\n    tags:\n      - Store Locator\n      - Retail\n      - Pharmacy\n      - Geolocation\n    properties:\n      - type: Documentation\n        url: https://developer.walgreens.com/api/storelocator/rest\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/openapi/walgreens-store-locator-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/json-schema/walgreens-store-schema.json\n\
  \  - aid: walgreens:walgreens-prescription-refill\n    name: Walgreens Prescription Refill API\n    description: >-\n      Enables medication management application developers to process prescription refills\n      or transfers to any Walgreens pharmacy location. Supports both barcode scanning\n      for refill initiation and image-based prescription transfers. Processes refills\n      from 8,200+ Walgreens pharmacies with mobile-optimized WebView checkout flows.\n    humanURL: https://developer.walgreens.com/api/rx/rest\n    baseURL: https://services.walgreens.com\n    tags:\n      - Pharmacy\n      - Prescriptions\n      - Healthcare\n      - Mobile\n    properties:\n      - type: Documentation\n        url: https://developer.walgreens.com/api/rx/rest\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/openapi/walgreens-prescription-refill-openapi.yml\n  - aid: walgreens:walgreens-vaccine-scheduling\n    name:\
  \ Walgreens Vaccine Scheduling API\n    description: >-\n      Allows developers to integrate vaccine and immunization appointment booking\n      capabilities including eligibility checking, timeslot availability, appointment\n      holds, patient registration, and booking confirmation across all Walgreens\n      locations in the United States and Puerto Rico. Supports 19+ vaccine types\n      including COVID-19, influenza, RSV, and travel immunizations.\n    humanURL: https://developer.walgreens.com/api/scheduling/v1\n    baseURL: https://services.walgreens.com\n    tags:\n      - Vaccines\n      - Healthcare\n      - Scheduling\n      - Immunizations\n    properties:\n      - type: Documentation\n        url: https://developer.walgreens.com/api/scheduling/v1\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/openapi/walgreens-vaccine-scheduling-openapi.yml\n      - type: JSONSchema\n        url: >-\n         \
  \ https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/json-schema/walgreens-vaccine-appointment-schema.json\n  - aid: walgreens:walgreens-photo-prints\n    name: Walgreens Photo Prints API\n    description: >-\n      Enables developers to offer photo printing services at 8,000+ Walgreens and Duane\n      Reade stores for same-day pickup. Supports native JSON API integration with\n      potential revenue share commissions for qualifying partners. Prints can be ordered\n      from mobile and web applications.\n    humanURL: https://developer.walgreens.com/api/photoprints/native\n    baseURL: https://services.walgreens.com\n    tags:\n      - Photo Printing\n      - Retail\n      - Mobile\n    properties:\n      - type: Documentation\n        url: https://developer.walgreens.com/api/photoprints/native\ncommon:\n  - type: Website\n    url: https://www.walgreens.com\n  - type: Portal\n    url: https://developer.walgreens.com\n  - type: Documentation\n    url: https://developer.walgreens.com/apis\n\
  \  - type: Blog\n    url: https://developer.walgreens.com/blog\n  - type: SignUp\n    url: https://developer.walgreens.com/user/register\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/apis.yml
tags:
- Pharmacy
- Healthcare
- Retail
- Prescriptions
- Vaccines
url: https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/apis.yml
use_cases: []
---
