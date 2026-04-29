---
api_count: 1
api_specs:
- filename: climatiq-openapi.yml
  format: yaml
  label: Climatiq API
  slug: climatiq-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/climatiq/refs/heads/main/openapi/climatiq-openapi.yml
apis:
- description: The Climatiq API is a single REST surface at api.climatiq.io that groups search, estimation, and reference operations under a shared API-key (Bearer) auth model. It exposes /data/v1/search for discove
  name: Climatiq API
  slug: climatiq-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.climatiq.io/
- title: ''
  type: Portal
  url: https://www.climatiq.io/docs
- title: ''
  type: Documentation
  url: https://www.climatiq.io/docs/api-reference
- title: ''
  type: GettingStarted
  url: https://www.climatiq.io/docs/guides/tutorials/quickstart
- title: ''
  type: Pricing
  url: https://www.climatiq.io/pricing
- title: ''
  type: Blog
  url: https://www.climatiq.io/blog
- title: ''
  type: Trust
  url: https://trust.climatiq.io/
- title: ''
  type: Support
  url: https://www.climatiq.io/support
- title: ''
  type: Customers
  url: https://www.climatiq.io/customers
- title: ''
  type: Login
  url: https://auth.climatiq.io/login
- title: ''
  type: Playground
  url: https://www.climatiq.io/demo
- title: ''
  type: Partners
  url: https://www.climatiq.io/partner-with-climatiq
- title: ''
  type: Newsletter
  url: https://www.climatiq.io/newsletter
- title: ''
  type: Versioning
  url: https://www.climatiq.io/docs/changelogs/api-release
- title: ''
  type: OpenAPI
  url: openapi/climatiq-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/climatiq-emission-estimate-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/climatiq-context.jsonld
- title: ''
  type: Spectral
  url: rules/climatiq-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/climatiq-capabilities.yml
created: '2025-02-24'
description: Climatiq provides a developer-first API for carbon accounting and emissions calculations. The platform packages a curated emission-factor database together with calculation endpoints that turn activity or spend data into auditable CO2-equivalent estimates aligned with the GHG Protocol. Capabilities span search across the factor catalog, generic activity-based estimation, and purpose-built endpoints for travel, freight (GLEC), energy, cloud computing, procurement, and the EU Carbon Border Adjustment Mechanism. The API is keyed (Bearer token) and hosted at api.climatiq.io.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 9
  name: Climatiq Context
  property_count: 6
  slug: climatiq-context
layout: provider
modified: '2026-04-27'
name: Climatiq
rules:
- name: Climatiq API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: climatiq-rules
skills: []
slug: climatiq
solutions: []
source_filename: apis.yml
source_yaml: "aid: climatiq\nname: Climatiq\nurl: https://raw.githubusercontent.com/api-evangelist/climatiq/refs/heads/main/apis.yml\ncreated: '2025-02-24'\nmodified: '2026-04-27'\nspecificationVersion: '0.19'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nx-type: company\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Carbon Accounting\n  - Carbon Emissions\n  - Climate\n  - Energy\n  - Environment\n  - GHG Protocol\n  - Sustainability\ndescription: >-\n  Climatiq provides a developer-first API for carbon accounting and\n  emissions calculations. The platform packages a curated emission-factor\n  database together with calculation endpoints that turn activity or\n  spend data into auditable CO2-equivalent estimates aligned with the\n  GHG Protocol. Capabilities span search across the factor catalog,\n  generic activity-based estimation, and purpose-built endpoints for\n  travel, freight (GLEC), energy, cloud computing, procurement, and\
  \ the\n  EU Carbon Border Adjustment Mechanism. The API is keyed (Bearer\n  token) and hosted at api.climatiq.io.\napis:\n  - aid: climatiq:climatiq-api\n    name: Climatiq API\n    tags:\n      - Carbon Emissions\n      - Emission Factors\n      - GHG Protocol\n      - Sustainability\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.climatiq.io/docs/api-reference\n    baseURL: https://api.climatiq.io\n    properties:\n      - url: https://www.climatiq.io/docs/api-reference\n        type: Documentation\n      - url: https://www.climatiq.io/docs/guides/tutorials/quickstart\n        type: GettingStarted\n      - url: https://www.climatiq.io/docs/api-reference/search\n        type: Reference\n      - url: https://www.climatiq.io/docs/api-reference/estimate\n        type: Reference\n      - url: https://www.climatiq.io/docs/api-reference/travel\n        type: Reference\n      - url: https://www.climatiq.io/docs/api-reference/intermodal-freight\n\
  \        type: Reference\n      - url: https://www.climatiq.io/docs/api-reference/energy\n        type: Reference\n      - url: https://www.climatiq.io/docs/api-reference/computing\n        type: Reference\n      - url: https://www.climatiq.io/docs/api-reference/procurement\n        type: Reference\n      - url: https://www.climatiq.io/docs/api-reference/autopilot\n        type: Reference\n      - url: https://www.climatiq.io/docs/api-reference/classifications\n        type: Reference\n      - url: https://www.climatiq.io/docs/api-reference/custom-mappings\n        type: Reference\n      - url: https://www.climatiq.io/docs/api-reference/cbam\n        type: Reference\n      - url: https://www.climatiq.io/docs/changelogs/api-release\n        type: ChangeLog\n      - url: openapi/climatiq-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Climatiq API is a single REST surface at api.climatiq.io that\n      groups search, estimation, and reference operations under a shared\n\
  \      API-key (Bearer) auth model. It exposes /data/v1/search for\n      discovering emission factors; /data/v1/estimate for activity-based\n      estimation; family endpoints under /travel, /freight, /energy,\n      /compute, /procurement, /autopilot, /classifications, and /cbam\n      for purpose-built calculations; and reference endpoints for\n      regions and unit types. All endpoints return CO2e in kilograms\n      together with the underlying factor and gas breakdown.\ncommon:\n  - type: Website\n    url: https://www.climatiq.io/\n  - type: Portal\n    url: https://www.climatiq.io/docs\n  - type: Documentation\n    url: https://www.climatiq.io/docs/api-reference\n  - type: GettingStarted\n    url: https://www.climatiq.io/docs/guides/tutorials/quickstart\n  - type: Pricing\n    url: https://www.climatiq.io/pricing\n  - type: Blog\n    url: https://www.climatiq.io/blog\n  - type: Trust\n    url: https://trust.climatiq.io/\n  - type: Support\n    url: https://www.climatiq.io/support\n\
  \  - type: Customers\n    url: https://www.climatiq.io/customers\n  - type: Login\n    url: https://auth.climatiq.io/login\n  - type: Playground\n    url: https://www.climatiq.io/demo\n  - type: Partners\n    url: https://www.climatiq.io/partner-with-climatiq\n  - type: Newsletter\n    url: https://www.climatiq.io/newsletter\n  - type: Versioning\n    url: https://www.climatiq.io/docs/changelogs/api-release\n  - type: OpenAPI\n    url: openapi/climatiq-openapi.yml\n  - type: JSONSchema\n    url: json-schema/climatiq-emission-estimate-schema.json\n  - type: JSONLDContext\n    url: json-ld/climatiq-context.jsonld\n  - type: Spectral\n    url: rules/climatiq-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/climatiq-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/climatiq/refs/heads/main/apis.yml
tags:
- Carbon Accounting
- Carbon Emissions
- Climate
- Energy
- Environment
- GHG Protocol
- Sustainability
url: https://raw.githubusercontent.com/api-evangelist/climatiq/refs/heads/main/apis.yml
use_cases: []
---
