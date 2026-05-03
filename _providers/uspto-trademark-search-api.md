---
api_count: 1
api_specs:
- filename: uspto-trademark-search-api-openapi.yml
  format: yaml
  label: USPTO Trademark Search API Endpoints
  slug: uspto-trademark-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uspto-trademark-search-api/refs/heads/main/openapi/uspto-trademark-search-api-openapi.yml
apis:
- description: The core API for accessing USPTO trademark data, offering various search and retrieval functionalities including keyword search, availability check, serial number lookups, owner searches, and database
  name: USPTO Trademark Search API Endpoints
  slug: uspto-trademark-search-api
capabilities:
- description: Workflow capability for trademark research and brand protection using the USPTO Trademark Search API. Supports legal professionals, brand managers, startup founders, and IP attorneys conducting tradem
  name: USPTO Trademark Research
  slug: trademark-research
common:
- title: ''
  type: Signup
  url: https://rapidapi.com/pentium10/api/uspto-trademark/
- title: ''
  type: Login
  url: https://rapidapi.com/developer/dashboard
- title: ''
  type: Documentation
  url: https://rapidapi.com/pentium10/api/uspto-trademark
- title: ''
  type: Pricing
  url: https://rapidapi.com/pentium10/api/uspto-trademark/pricing
- title: ''
  type: FAQ
  url: https://rapidapi.com/pentium10/api/uspto-trademark/tutorials/faq-
- title: ''
  type: Blog
  url: https://medium.com/p/71274363605b
- title: ''
  type: Blog
  url: https://medium.com/p/19efc7e1cc6
- title: ''
  type: TermsOfService
  url: https://rapidapi.com/terms/
- title: ''
  type: Twitter
  url: https://twitter.com/martonkodok
- title: ''
  type: SpectralRules
  url: rules/uspto-trademark-search-api-rules.yml
- title: ''
  type: JSON-LD
  url: json-ld/uspto-trademark-search-api-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/uspto-trademark-search-api-vocabulary.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/trademark-research.yaml
created: '2025-05-27'
description: Instant trademark search and brand protection via the USPTO Trademark Search API. Check if a trademark keyword is available, search active trademarks, look up marks by serial number, and search by owner from United States Patent and Trademark Office data. Updated daily. Enables trademark availability checking, portfolio research, competitive intelligence, and due diligence workflows.
features: []
image: https://rapidapi.com/hub/_next/image?url=https%3A%2F%2Frapidapi-prod-apis.s3.amazonaws.com%2F9440240c-7bf2-4af0-8232-375b0bb7327f_medium&w=1920&q=75
integrations: []
jsonld:
- class_count: 13
  name: Uspto Trademark Search Api Context
  property_count: 25
  slug: uspto-trademark-search-api-context
layout: provider
modified: '2026-05-03'
name: USPTO Trademark Search API
rules:
- name: USPTO Trademark Search API API Rules
  rule_count: 19
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 10
  slug: uspto-trademark-search-api-rules
skills: []
slug: uspto-trademark-search-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: uspto-trademark-search-api\nname: USPTO Trademark Search API\ndescription: >-\n  Instant trademark search and brand protection via the USPTO Trademark Search API.\n  Check if a trademark keyword is available, search active trademarks, look up marks\n  by serial number, and search by owner from United States Patent and Trademark Office\n  data. Updated daily. Enables trademark availability checking, portfolio research,\n  competitive intelligence, and due diligence workflows.\ntype: Collection\nimage: >-\n  https://rapidapi.com/hub/_next/image?url=https%3A%2F%2Frapidapi-prod-apis.s3.amazonaws.com%2F9440240c-7bf2-4af0-8232-375b0bb7327f_medium&w=1920&q=75\naccess: Public\ntags:\n  - Brand\n  - Brand Protection\n  - Business\n  - Data\n  - Government Data\n  - Intellectual Property\n  - Legal\n  - Search\n  - Trademark\n  - USPTO\ncreated: '2025-05-27'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/uspto-trademark-search-api/refs/heads/main/apis.yml\n\
  position: Provider\napis:\n  - aid: uspto-trademark-search-api:uspto-trademark-search-api\n    name: USPTO Trademark Search API Endpoints\n    description: >-\n      The core API for accessing USPTO trademark data, offering various search and\n      retrieval functionalities including keyword search, availability check, serial\n      number lookups, owner searches, and database status information. It supports\n      batch processing and pagination.\n    tags:\n      - Brand Protection\n      - Data Retrieval\n      - Legal Research\n      - Trademark Search\n      - USPTO Data\n    image: >-\n      https://rapidapi.com/hub/_next/image?url=https%3A%2F%2Frapidapi-prod-apis.s3.amazonaws.com%2F9440240c-7bf2-4af0-8232-375b0bb7327f_medium&w=1920&q=75\n    baseURL: https://uspto-trademark.p.rapidapi.com\n    humanURL: https://rapidapi.com/pentium10/api/uspto-trademark\n    contact:\n      - FN: MartonKodok\n        email: android482-one@yahoo.com\n        X-twitter: martonkodok\n    properties:\n\
  \      - url: https://rapidapi.com/pentium10/api/uspto-trademark\n        type: Documentation\n      - url: https://rapidapi.com/pentium10/api/uspto-trademark/tutorials/faq-\n        type: FAQ\n      - url: https://rapidapi.com/pentium10/api/uspto-trademark/pricing\n        type: Pricing\n      - url: https://medium.com/p/71274363605b\n        type: Blog\n        description: USPTO Trademark API — Search trademark & owner database — part 1\n      - url: https://medium.com/p/19efc7e1cc6\n        type: Blog\n        description: >-\n          Implementing trademark availability and search using USPTO Trademark\n          API — part 2\n      - url: https://rapidapi.com/pentium10/api/uspto-trademark#endpoints\n        type: StatusPage\n        description: >-\n          Database freshness and update information available via\n          /v1/databaseStatus endpoint.\n      - url: https://rapidapi.com/terms/\n        type: TermsOfService\n      - type: OpenAPI\n        url: openapi/uspto-trademark-search-api-openapi.yml\n\
  \      - type: JSONSchema\n        url: json-schema/uspto-trademark-search-api-trademark-schema.json\n      - type: JSONStructure\n        url: json-structure/uspto-trademark-search-api-trademark-structure.json\ncommon:\n  - url: https://rapidapi.com/pentium10/api/uspto-trademark/\n    type: Signup\n  - url: https://rapidapi.com/developer/dashboard\n    type: Login\n  - url: https://rapidapi.com/pentium10/api/uspto-trademark\n    type: Documentation\n  - url: https://rapidapi.com/pentium10/api/uspto-trademark/pricing\n    type: Pricing\n  - url: https://rapidapi.com/pentium10/api/uspto-trademark/tutorials/faq-\n    type: FAQ\n  - url: https://medium.com/p/71274363605b\n    type: Blog\n  - url: https://medium.com/p/19efc7e1cc6\n    type: Blog\n  - url: https://rapidapi.com/terms/\n    type: TermsOfService\n  - url: https://twitter.com/martonkodok\n    type: Twitter\n  - type: SpectralRules\n    url: rules/uspto-trademark-search-api-rules.yml\n  - type: JSON-LD\n    url: json-ld/uspto-trademark-search-api-context.jsonld\n\
  \  - type: Vocabulary\n    url: vocabulary/uspto-trademark-search-api-vocabulary.yml\n  - type: NaftikoCapability\n    url: capabilities/trademark-research.yaml\nmaintainers:\n  - FN: MartonKodok\n    email: android482-one@yahoo.com\n    X-twitter: martonkodok\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/uspto-trademark-search-api/refs/heads/main/apis.yml
tags:
- Brand
- Brand Protection
- Business
- Data
- Government Data
- Intellectual Property
- Legal
- Search
- Trademark
- USPTO
url: https://raw.githubusercontent.com/api-evangelist/uspto-trademark-search-api/refs/heads/main/apis.yml
use_cases: []
---
