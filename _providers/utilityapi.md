---
api_count: 1
api_specs:
- filename: utilityapi-openapi.yml
  format: yaml
  label: UtilityAPI
  slug: utilityapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/openapi/utilityapi-openapi.yml
apis:
- description: UtilityAPI provides a REST API for accessing utility data including meters, bills, intervals, authorizations, and webhook events. Supports Green Button standard for energy data sharing.
  name: UtilityAPI
  slug: utilityapi
capabilities:
- description: Unified workflow capability for accessing utility energy data including meters, billing history, interval usage, and authorization management. Designed for cleantech developers, energy analytics platf
  name: UtilityAPI Energy Data Access
  slug: energy-data-access
common:
- title: ''
  type: Website
  url: https://utilityapi.com/
- title: ''
  type: Documentation
  url: https://utilityapi.com/docs
- title: ''
  type: Sign Up
  url: https://utilityapi.com/register
- title: ''
  type: Pricing
  url: https://utilityapi.com/pricing
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/openapi/utilityapi-openapi.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/capabilities/energy-data-access.yaml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/vocabulary/utilityapi-vocabulary.yml
created: '2025-05-02'
description: UtilityAPI collects, standardizes, and shares utility data seamlessly and securely, providing a platform for accessing energy and utility billing data, meter intervals, and authorization workflows for energy companies, cleantech firms, and developers.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 18
  name: Utilityapi Context
  property_count: 2
  slug: utilityapi-context
layout: provider
modified: '2026-05-03'
name: UtilityAPI
rules:
- name: UtilityAPI API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 6
  slug: utilityapi-rules
skills: []
slug: utilityapi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: utilityapi\nname: UtilityAPI\ndescription: >-\n  UtilityAPI collects, standardizes, and shares utility data seamlessly and securely,\n  providing a platform for accessing energy and utility billing data, meter intervals,\n  and authorization workflows for energy companies, cleantech firms, and developers.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Energy\n  - Utilities\n  - Green Button\n  - Billing Data\n  - Meter Data\n  - Clean Energy\ncreated: '2025-05-02'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: utilityapi:utilityapi\n    name: UtilityAPI\n    description: >-\n      UtilityAPI provides a REST API for accessing utility data including meters,\n      bills, intervals, authorizations, and webhook events. Supports Green Button\n      standard\
  \ for energy data sharing.\n    humanURL: https://utilityapi.com/\n    baseURL: https://utilityapi.com/api/v2\n    tags:\n      - Energy\n      - Utilities\n      - Billing\n      - Meter Data\n      - Green Button\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://utilityapi.com/docs\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/openapi/utilityapi-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/json-schema/utilityapi-meter-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/json-schema/utilityapi-bill-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/json-schema/utilityapi-interval-schema.json\n      - type: SpectralRules\n        url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/rules/utilityapi-rules.yml\n\
  \    contact:\n      - FN: UtilityAPI Support\n        url: https://utilityapi.com/contact\n    features:\n      - name: Meter Data Access\n        description: Access utility service and meter data for authorized customers\n      - name: Bill Retrieval\n        description: Retrieve utility billing information and billing summaries\n      - name: Interval Data\n        description: Access meter usage intervals for energy monitoring\n      - name: Authorization Workflows\n        description: Manage customer authorization forms and submitted authorizations\n      - name: Webhook Events\n        description: Event notifications for authorization and data collection activities\n      - name: Green Button Support\n        description: Compatibility with Green Button standard including XML feeds and OAuth\n      - name: Accounting\n        description: Access billing accounts and billing summaries\n    useCases:\n      - name: Clean Energy Applications\n        description: Enable cleantech\
  \ apps to access utility data for energy analysis\n      - name: EV Charging Optimization\n        description: Access meter interval data to optimize EV charging schedules\n      - name: Energy Benchmarking\n        description: Retrieve billing data for energy benchmarking and reporting\n      - name: Solar and Storage\n        description: Access utility data for solar and battery storage sizing\n    integrations:\n      - name: Green Button\n        description: Connect standard for energy data sharing\n        url: https://www.greenbuttonalliance.org/\n    solutions:\n      - name: Energy Data Platform\n        description: Comprehensive utility data collection and standardization platform\ncommon:\n  - type: Website\n    url: https://utilityapi.com/\n  - type: Documentation\n    url: https://utilityapi.com/docs\n  - type: Sign Up\n    url: https://utilityapi.com/register\n  - type: Pricing\n    url: https://utilityapi.com/pricing\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/openapi/utilityapi-openapi.yml\n\
  \  - type: NaftikoCapabilities\n    url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/capabilities/energy-data-access.yaml\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/vocabulary/utilityapi-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/apis.yml
tags:
- Energy
- Utilities
- Green Button
- Billing Data
- Meter Data
- Clean Energy
url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/apis.yml
use_cases: []
---
