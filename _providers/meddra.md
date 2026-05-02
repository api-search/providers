---
api_count: 1
api_specs:
- filename: meddra-terminology-openapi.yml
  format: yaml
  label: MedDRA / WHO Drug Dictionary API
  slug: meddra-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/openapi/meddra-terminology-openapi.yml
apis:
- description: 'MedDRA (Medical Dictionary for Regulatory Activities) and the WHO Drug Dictionary provide standardized medical terminology APIs for adverse event coding, drug safety reporting, and pharmacovigilance. '
  name: MedDRA / WHO Drug Dictionary API
  slug: meddra-api
common:
- title: ''
  type: Portal
  url: https://www.meddra.org/
- title: ''
  type: Website
  url: https://www.meddra.org/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/openapi/meddra-terminology-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/json-schema/meddra-term-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/json-ld/meddra-context.jsonld
created: ''
description: MedDRA (Medical Dictionary for Regulatory Activities) is a clinically validated international medical terminology dictionary used by regulatory authorities and the regulated biopharmaceutical industry.
features: []
image: ''
integrations: []
jsonld:
- class_count: 2
  name: Meddra Context
  property_count: 13
  slug: meddra-context
layout: provider
modified: '2026-04-28'
name: meddra
skills: []
slug: meddra
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: meddra\nurl: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/apis.yml\napis:\n  - aid: meddra:meddra-api\n    name: MedDRA / WHO Drug Dictionary API\n    tags:\n      - Adverse Events\n      - Coding\n      - Medical Terminology\n      - Pharma\n    image: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/image.png\n    humanURL: https://www.meddra.org/\n    baseURL: https://api.meddra.example.com\n    properties:\n      - url: https://www.meddra.org/\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/openapi/meddra-terminology-openapi.yml\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/json-schema/meddra-term-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/json-ld/meddra-context.jsonld\n        type: JSONLDContext\n    description:\
  \ >-\n      MedDRA (Medical Dictionary for Regulatory Activities) and the WHO Drug Dictionary\n      provide standardized medical terminology APIs for adverse event coding, drug\n      safety reporting, and pharmacovigilance. APIs enable term lookup, hierarchy\n      navigation, and coding validation for regulatory submissions.\ncommon:\n  - url: https://www.meddra.org/\n    type: Portal\n  - url: https://www.meddra.org/\n    type: Website\n  - url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/openapi/meddra-terminology-openapi.yml\n    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/json-schema/meddra-term-schema.json\n    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/json-ld/meddra-context.jsonld\n    type: JSONLDContext\nmaintainer:\n  name: Kin Lane\n  email: kin@apievangelist.com\nmodified: '2026-04-28'\ndescription: >-\n  MedDRA (Medical Dictionary for Regulatory\
  \ Activities) is a clinically validated\n  international medical terminology dictionary used by regulatory authorities and\n  the regulated biopharmaceutical industry.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/apis.yml
use_cases: []
---
