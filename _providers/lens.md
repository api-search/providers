---
api_count: 1
api_specs:
- filename: lens-openapi.yml
  format: yaml
  label: Lens API
  slug: lens-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lens/refs/heads/main/openapi/lens-openapi.yml
apis:
- description: The Lens API exposes the full corpus of Lens scholarly works and patents via a REST interface. Search endpoints accept Elasticsearch-style query DSL via POST or simple Lucene query strings via GET, wi
  name: Lens API
  slug: lens-api
common:
- title: ''
  type: Website
  url: https://www.lens.org/
- title: ''
  type: Documentation
  url: https://docs.api.lens.org/
- title: ''
  type: Plans
  url: https://www.lens.org/lens/user/subscriptions
- title: ''
  type: About
  url: https://www.lens.org/lens/about
- title: ''
  type: TermsOfService
  url: https://www.lens.org/lens/terms-and-conditions
- title: ''
  type: PrivacyPolicy
  url: https://www.lens.org/lens/privacy-policy
created: '2025-02-06'
description: Lens is an open knowledge platform from Cambia that aggregates global scholarly works and patent records and exposes them through a REST API. The versioned API supports rich Elasticsearch-style queries, cursor pagination, and field projection across the full Lens scholarly and patent corpora, enabling research, science policy, technology landscape, and patent intelligence applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Lens
skills: []
slug: lens
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: lens\nname: Lens\ndescription: >-\n  Lens is an open knowledge platform from Cambia that aggregates global\n  scholarly works and patent records and exposes them through a REST API. The\n  versioned API supports rich Elasticsearch-style queries, cursor pagination,\n  and field projection across the full Lens scholarly and patent corpora,\n  enabling research, science policy, technology landscape, and patent\n  intelligence applications.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Scholarly\n  - Patents\n  - Research\n  - Science\n  - Open Data\nurl: https://raw.githubusercontent.com/api-evangelist/lens/refs/heads/main/apis.yml\ncreated: '2025-02-06'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: lens:lens-api\n    name: Lens API\n    description: >-\n      The Lens API exposes the full corpus of Lens scholarly works and patents\n      via a REST\
  \ interface. Search endpoints accept Elasticsearch-style query\n      DSL via POST or simple Lucene query strings via GET, with cursor-based\n      pagination, field projection, sorting, stemming controls, and patent\n      family grouping. Authentication is via a bearer token issued from the\n      Lens user profile.\n    humanURL: https://docs.api.lens.org/\n    baseURL: https://api.lens.org\n    tags:\n      - Scholarly\n      - Patents\n      - Search\n      - Research\n    properties:\n      - url: https://docs.api.lens.org/\n        type: Documentation\n      - url: https://api.lens.org/swagger-ui.html\n        type: SwaggerUI\n      - url: openapi/lens-openapi.yml\n        type: OpenAPI\ncommon:\n  - url: https://www.lens.org/\n    type: Website\n  - url: https://docs.api.lens.org/\n    type: Documentation\n  - url: https://www.lens.org/lens/user/subscriptions\n    type: Plans\n  - url: https://www.lens.org/lens/about\n    type: About\n  - url: https://www.lens.org/lens/terms-and-conditions\n\
  \    type: TermsOfService\n  - url: https://www.lens.org/lens/privacy-policy\n    type: PrivacyPolicy\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/lens/refs/heads/main/apis.yml
tags:
- Scholarly
- Patents
- Research
- Science
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/lens/refs/heads/main/apis.yml
use_cases: []
---
