---
api_count: 10
api_specs:
- filename: telefonica-number-verification-openapi.yml
  format: yaml
  label: Telefónica Number Verification API
  slug: number-verification-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/openapi/telefonica-number-verification-openapi.yml
- filename: telefonica-sim-swap-openapi.yml
  format: yaml
  label: Telefónica SIM Swap API
  slug: sim-swap-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/openapi/telefonica-sim-swap-openapi.yml
- filename: telefonica-kyc-match-openapi.yml
  format: yaml
  label: Telefónica Know Your Customer Match API
  slug: kyc-match-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/openapi/telefonica-kyc-match-openapi.yml
- filename: telefonica-location-verification-openapi.yml
  format: yaml
  label: Telefónica Location Verification API
  slug: location-verification-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/openapi/telefonica-location-verification-openapi.yml
- filename: telefonica-quality-on-demand-openapi.yml
  format: yaml
  label: Telefónica Quality on Demand API
  slug: quality-on-demand-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/openapi/telefonica-quality-on-demand-openapi.yml
- filename: telefonica-device-roaming-openapi.yml
  format: yaml
  label: Telefónica Device Roaming Status API
  slug: device-roaming-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/openapi/telefonica-device-roaming-openapi.yml
apis:
- description: The Number Verification API enables automatic verification that users are interacting via devices with SIM cards associated with their phone numbers, eliminating the need for credential entry or one-t
  name: Telefónica Number Verification API
  slug: number-verification-api
- description: 'The SIM Swap API enables applications to detect recent SIM card swaps on a mobile number, a common indicator of account takeover fraud. Returns whether a SIM swap occurred on the mobile line and when '
  name: Telefónica SIM Swap API
  slug: sim-swap-api
- description: 'The KYC Match API validates a user''s contact information (name, address, phone number, email) against reliable mobile carrier data, enabling quick identity verification without sharing personal data. '
  name: Telefónica Know Your Customer Match API
  slug: kyc-match-api
- description: The Location Verification API verifies the geographical location of a SIM-based device, confirming whether the device is present within a requested geographic area. Uses network data rather than GPS t
  name: Telefónica Location Verification API
  slug: location-verification-api
- description: 'The Quality on Demand (QoD) API provides applications with precise control over mobile network connectivity quality, enabling guaranteed bandwidth and low latency for specific application flows. Used '
  name: Telefónica Quality on Demand API
  slug: quality-on-demand-api
- description: The Device Roaming Status API verifies the roaming status of a SIM-based device securely using carrier network data, without relying on GPS or identity theft risks. Enables fraud detection, access con
  name: Telefónica Device Roaming Status API
  slug: device-roaming-status-api
- description: The Scam Signal API enables companies to protect their customers from phishing scams and voice fraud by detecting active scam calls in real time using Telefónica's network intelligence. Available in S
  name: Telefónica Scam Signal API
  slug: scam-signal-api
- description: The Age Verification API allows companies to confirm in real time whether a mobile user meets a specified age threshold, using carrier data for privacy-preserving age checks without sharing personal d
  name: Telefónica Age Verification API
  slug: age-verification-api
- description: The Line Tenure API indicates how long a mobile number has belonged to its current user, providing a fraud risk signal for identity validation and account security workflows. Available in Spain, Brazi
  name: Telefónica Line Tenure API
  slug: line-tenure-api
- description: The Population Density Data API provides dynamic real-time data on population density in a specific geographic area and time window, derived from anonymized and aggregated mobile network data. Used fo
  name: Telefónica Population Density Data API
  slug: population-density-data-api
capabilities:
- description: Fraud prevention capability combining Telefónica's Number Verification, SIM Swap, KYC Match, and Location Verification APIs into a unified workflow. Enables financial services, e-commerce, and insuran
  name: Telefónica Fraud Prevention
  slug: fraud-prevention
- description: Network quality management capability combining Telefónica's Quality on Demand and Device Roaming Status APIs. Enables application developers, IoT platform providers, and telecom integrators to guaran
  name: Telefónica Network Quality Management
  slug: network-quality-management
common:
- title: ''
  type: Website
  url: https://opengateway.telefonica.com/en
- title: ''
  type: DeveloperPortal
  url: https://opengateway.telefonica.com/en/developer-hub
- title: ''
  type: Documentation
  url: https://developers.opengateway.telefonica.com/docs/initiative
- title: ''
  type: GitHub
  url: https://github.com/Telefonica
- title: ''
  type: GitHub
  url: https://github.com/camaraproject
- title: ''
  type: APIs
  url: https://opengateway.telefonica.com/en/apis
- title: ''
  type: Signup
  url: https://opengateway.telefonica.com/en/developer-hub/join
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/telefonica
- title: ''
  type: X
  url: https://x.com/Telefonica
created: '2025-03-01'
description: Telefónica is one of the world's leading telecommunications companies, operating in Europe and Latin America. Through its Open Gateway initiative, Telefónica exposes standardized network capabilities as APIs following the CAMARA (Cloud and Edge for Mobile Access and Real-time Execution) open standards developed by the GSMA. The Open Gateway APIs enable developers and enterprises to build applications leveraging Telefónica's network infrastructure for authentication, fraud prevention, location services, quality of service, and device management. APIs are available in Spain, Germany, Brazil, and the United Kingdom through the Telefónica Open Gateway sandbox and partner program.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 38
  name: Telefonica Context
  property_count: 0
  slug: telefonica-context
layout: provider
modified: '2026-05-03'
name: Telefónica
rules:
- name: Telefónica API Rules
  rule_count: 11
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 6
  slug: telefonica-rules
skills: []
slug: telefonica
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: telefonica\nname: Telefónica\ndescription: >-\n  Telefónica is one of the world's leading telecommunications companies,\n  operating in Europe and Latin America. Through its Open Gateway initiative,\n  Telefónica exposes standardized network capabilities as APIs following the\n  CAMARA (Cloud and Edge for Mobile Access and Real-time Execution) open\n  standards developed by the GSMA. The Open Gateway APIs enable developers and\n  enterprises to build applications leveraging Telefónica's network infrastructure\n  for authentication, fraud prevention, location services, quality of service,\n  and device management. APIs are available in Spain, Germany, Brazil, and the\n  United Kingdom through the Telefónica Open Gateway sandbox and partner program.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Telecommunications\n  - Mobile Network\n  - CAMARA\n  - Open Gateway\n  - Authentication\n  - Fraud Prevention\n  - Location\
  \ Services\nurl: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/apis.yml\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: telefonica:number-verification-api\n    name: Telefónica Number Verification API\n    description: >-\n      The Number Verification API enables automatic verification that users\n      are interacting via devices with SIM cards associated with their phone\n      numbers, eliminating the need for credential entry or one-time passwords.\n      Uses carrier network data to verify the mobile number associated with\n      the device's active data connection. Available in Spain, Germany, and Brazil.\n    humanURL: https://opengateway.telefonica.com/en/apis/number-verification\n    baseURL: https://opengateway.telefonica.com\n    tags:\n      - Authentication\n      - Number Verification\n      - Fraud Prevention\n      - Mobile Identity\n      - SIM\n    properties:\n      - type: Documentation\n \
  \       url: https://developers.opengateway.telefonica.com/docs/numberverification\n      - type: OpenAPI\n        url: openapi/telefonica-number-verification-openapi.yml\n      - type: JSONSchema\n        url: json-schema/telefonica-device-schema.json\n      - type: GitHub\n        url: https://github.com/Telefonica/opengateway-developers-website\n  - aid: telefonica:sim-swap-api\n    name: Telefónica SIM Swap API\n    description: >-\n      The SIM Swap API enables applications to detect recent SIM card swaps\n      on a mobile number, a common indicator of account takeover fraud.\n      Returns whether a SIM swap occurred on the mobile line and when the\n      last swap happened. Based on CAMARA open standards. Available in Spain,\n      Germany, Brazil, and the United Kingdom.\n    humanURL: https://opengateway.telefonica.com/en/apis/sim-swap\n    baseURL: https://opengateway.telefonica.com\n    tags:\n      - Authentication\n      - Fraud Prevention\n      - SIM Swap\n      - Mobile\
  \ Security\n    properties:\n      - type: Documentation\n        url: https://developers.opengateway.telefonica.com/docs/simswap\n      - type: OpenAPI\n        url: openapi/telefonica-sim-swap-openapi.yml\n      - type: JSONSchema\n        url: json-schema/telefonica-device-schema.json\n      - type: GitHub\n        url: https://github.com/Telefonica/opengateway-samples-simswap\n  - aid: telefonica:kyc-match-api\n    name: Telefónica Know Your Customer Match API\n    description: >-\n      The KYC Match API validates a user's contact information (name, address,\n      phone number, email) against reliable mobile carrier data, enabling quick\n      identity verification without sharing personal data. Used for e-commerce,\n      financial services, and insurance KYC compliance. Available in Spain,\n      Germany, Brazil, and the United Kingdom.\n    humanURL: https://opengateway.telefonica.com/en/apis/kyc-match\n    baseURL: https://opengateway.telefonica.com\n    tags:\n      - Authentication\n\
  \      - Fraud Prevention\n      - KYC\n      - Identity Verification\n      - Financial Services\n    properties:\n      - type: Documentation\n        url: https://opengateway.telefonica.com/en/apis/kyc-match\n      - type: OpenAPI\n        url: openapi/telefonica-kyc-match-openapi.yml\n  - aid: telefonica:location-verification-api\n    name: Telefónica Location Verification API\n    description: >-\n      The Location Verification API verifies the geographical location of a\n      SIM-based device, confirming whether the device is present within a\n      requested geographic area. Uses network data rather than GPS to verify\n      location without privacy risks. Available in Spain, Germany, and Brazil.\n    humanURL: https://opengateway.telefonica.com/en/apis/location-verification\n    baseURL: https://opengateway.telefonica.com\n    tags:\n      - Location Services\n      - Device Location\n      - Fraud Prevention\n      - Mobile Network\n    properties:\n      - type: Documentation\n\
  \        url: https://opengateway.telefonica.com/en/apis/location-verification\n      - type: OpenAPI\n        url: openapi/telefonica-location-verification-openapi.yml\n  - aid: telefonica:quality-on-demand-api\n    name: Telefónica Quality on Demand API\n    description: >-\n      The Quality on Demand (QoD) API provides applications with precise\n      control over mobile network connectivity quality, enabling guaranteed\n      bandwidth and low latency for specific application flows. Used for\n      real-time communications, streaming, industrial IoT, and gaming.\n      Available in Spain, Germany, and Brazil.\n    humanURL: https://opengateway.telefonica.com/en/apis/quality-on-demand\n    baseURL: https://opengateway.telefonica.com\n    tags:\n      - Quality of Service\n      - Mobile Network\n      - IoT\n      - Network Slicing\n      - Communication Quality\n    properties:\n      - type: Documentation\n        url: https://opengateway.telefonica.com/en/apis/quality-on-demand\n\
  \      - type: OpenAPI\n        url: openapi/telefonica-quality-on-demand-openapi.yml\n      - type: JSONSchema\n        url: json-schema/telefonica-qod-session-schema.json\n  - aid: telefonica:device-roaming-status-api\n    name: Telefónica Device Roaming Status API\n    description: >-\n      The Device Roaming Status API verifies the roaming status of a\n      SIM-based device securely using carrier network data, without relying\n      on GPS or identity theft risks. Enables fraud detection, access control,\n      and compliance for applications requiring location awareness.\n      Available in Spain and Brazil.\n    humanURL: https://opengateway.telefonica.com/en/apis/device-roaming-status\n    baseURL: https://opengateway.telefonica.com\n    tags:\n      - Roaming\n      - Device Status\n      - Fraud Prevention\n      - Mobile Network\n    properties:\n      - type: Documentation\n        url: https://opengateway.telefonica.com/en/apis/device-roaming-status\n      - type: OpenAPI\n\
  \        url: openapi/telefonica-device-roaming-openapi.yml\n  - aid: telefonica:scam-signal-api\n    name: Telefónica Scam Signal API\n    description: >-\n      The Scam Signal API enables companies to protect their customers from\n      phishing scams and voice fraud by detecting active scam calls in real\n      time using Telefónica's network intelligence. Available in Spain.\n    humanURL: https://opengateway.telefonica.com/en/apis/scam-signal\n    baseURL: https://opengateway.telefonica.com\n    tags:\n      - Fraud Prevention\n      - Scam Detection\n      - Phishing\n      - Voice Fraud\n      - Security\n    properties:\n      - type: Documentation\n        url: https://opengateway.telefonica.com/en/apis/scam-signal\n  - aid: telefonica:age-verification-api\n    name: Telefónica Age Verification API\n    description: >-\n      The Age Verification API allows companies to confirm in real time\n      whether a mobile user meets a specified age threshold, using carrier\n      data\
  \ for privacy-preserving age checks without sharing personal data.\n      Available in the United Kingdom.\n    humanURL: https://opengateway.telefonica.com/en/apis/age-verification\n    baseURL: https://opengateway.telefonica.com\n    tags:\n      - Age Verification\n      - Compliance\n      - E-Commerce\n      - Media\n      - Privacy\n    properties:\n      - type: Documentation\n        url: https://opengateway.telefonica.com/en/apis/age-verification\n  - aid: telefonica:line-tenure-api\n    name: Telefónica Line Tenure API\n    description: >-\n      The Line Tenure API indicates how long a mobile number has belonged\n      to its current user, providing a fraud risk signal for identity\n      validation and account security workflows. Available in Spain, Brazil,\n      and the United Kingdom.\n    humanURL: https://opengateway.telefonica.com/en/apis/line-tenure\n    baseURL: https://opengateway.telefonica.com\n    tags:\n      - Fraud Prevention\n      - Identity Verification\n\
  \      - Financial Services\n      - Mobile Security\n    properties:\n      - type: Documentation\n        url: https://opengateway.telefonica.com/en/apis/line-tenure\n  - aid: telefonica:population-density-data-api\n    name: Telefónica Population Density Data API\n    description: >-\n      The Population Density Data API provides dynamic real-time data on\n      population density in a specific geographic area and time window,\n      derived from anonymized and aggregated mobile network data. Used for\n      transport planning, event management, and retail analytics.\n      Available in Spain.\n    humanURL: https://opengateway.telefonica.com/en/apis/population-density-data\n    baseURL: https://opengateway.telefonica.com\n    tags:\n      - Location Services\n      - Population Data\n      - Analytics\n      - Transport\n      - Smart City\n    properties:\n      - type: Documentation\n        url: https://opengateway.telefonica.com/en/apis/population-density-data\ncommon:\n  - url:\
  \ https://opengateway.telefonica.com/en\n    name: Telefónica Open Gateway\n    type: Website\n    description: Telefónica Open Gateway developer portal.\n  - url: https://opengateway.telefonica.com/en/developer-hub\n    name: Telefónica Open Gateway Developer Hub\n    type: DeveloperPortal\n    description: Developer Hub for testing Telefónica Open Gateway APIs in sandbox.\n  - url: https://developers.opengateway.telefonica.com/docs/initiative\n    name: Open Gateway Initiative Documentation\n    type: Documentation\n    description: Technical documentation for the Telefónica Open Gateway initiative.\n  - url: https://github.com/Telefonica\n    name: Telefónica GitHub\n    type: GitHub\n    description: Telefónica official GitHub organization.\n  - url: https://github.com/camaraproject\n    name: CAMARA Project GitHub\n    type: GitHub\n    description: GSMA CAMARA project - open standards for telco network APIs.\n  - url: https://opengateway.telefonica.com/en/apis\n    name: Telefónica\
  \ Open Gateway APIs\n    type: APIs\n    description: Complete list of available Telefónica Open Gateway APIs.\n  - url: https://opengateway.telefonica.com/en/developer-hub/join\n    name: Join Telefónica Developer Hub\n    type: Signup\n    description: Registration for the Telefónica Open Gateway Developer Hub.\n  - url: https://www.linkedin.com/company/telefonica\n    name: Telefónica on LinkedIn\n    type: LinkedIn\n    description: Telefónica LinkedIn company page.\n  - url: https://x.com/Telefonica\n    name: Telefónica on X\n    type: X\n    description: Telefónica on X (formerly Twitter).\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/apis.yml
tags:
- Telecommunications
- Mobile Network
- CAMARA
- Open Gateway
- Authentication
- Fraud Prevention
- Location Services
url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/apis.yml
use_cases: []
---
