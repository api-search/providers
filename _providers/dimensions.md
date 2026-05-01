---
api_count: 1
apis:
- description: 'The Dimensions Analytics API provides programmatic access to the Dimensions research data platform via the Dimensions Search Language (DSL). It supports queries against publications, grants, patents, '
  name: Dimensions Analytics API
  slug: dimensions-analytics-api
common:
- title: ''
  type: Website
  url: https://www.dimensions.ai/
- title: ''
  type: Documentation
  url: https://docs.dimensions.ai/dsl/
- title: ''
  type: Support
  url: https://plus.dimensions.ai/support/
- title: ''
  type: Blog
  url: https://www.dimensions.ai/blog/
created: '2025-02-06'
description: Dimensions is a research data platform from Digital Science providing access to publications, grants, patents, clinical trials, datasets, and policy documents. The Dimensions Analytics API offers programmatic access to this research data via the Dimensions Search Language (DSL), enabling citation analysis, researcher discovery, organization benchmarking, and topic identification. The API is subscription-only and is not intended for bulk data extraction or to power dashboards or other derivative products.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Dimensions
skills: []
slug: dimensions
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dimensions\nname: Dimensions\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/dimensions/refs/heads/main/apis.yml\ndescription: >-\n  Dimensions is a research data platform from Digital Science providing access\n  to publications, grants, patents, clinical trials, datasets, and policy\n  documents. The Dimensions Analytics API offers programmatic access to this\n  research data via the Dimensions Search Language (DSL), enabling citation\n  analysis, researcher discovery, organization benchmarking, and topic\n  identification. The API is subscription-only and is not intended for bulk\n  data extraction or to power dashboards or other derivative products.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\nposition: Consumer\naccess: 3rd-Party\ntags:\n  - Analytics\n  - Research\n  - Publications\n  - Grants\n  - Patents\n  - Clinical Trials\n  - Jupyter Notebooks\ncreated: '2025-02-06'\nmodified: '2026-04-28'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: dimensions:dimensions-analytics-api\n    name: Dimensions Analytics API\n    description: >-\n      The Dimensions Analytics API provides programmatic access to the\n      Dimensions research data platform via the Dimensions Search Language\n      (DSL). It supports queries against publications, grants, patents,\n      clinical trials, datasets, organizations, and researchers. Authentication\n      uses an API key exchanged for a JWT token via POST to /api/auth, with\n      query requests sent to /api/dsl/v2 carrying the JWT in the Authorization\n      header. The API is subscription-only and rate limited to 30 requests per\n      IP per minute.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.dimensions.ai/dsl/\n    baseURL: https://app.dimensions.ai/api\n    tags:\n      - Analytics\n      - Research\n      - Publications\n      - Grants\n      - Patents\n      - Clinical Trials\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.dimensions.ai/dsl/\n      - type: API Access\n        url: https://docs.dimensions.ai/dsl/api.html\n      - type: DSL Reference\n        url: https://docs.dimensions.ai/dsl/language.html\n      - type: API Lab\n        url: https://api-lab.dimensions.ai/\n      - type: SourceCode\n        url: https://github.com/digital-science/dimcli\ncommon:\n  - type: Website\n    url: https://www.dimensions.ai/\n  - type: Documentation\n    url: https://docs.dimensions.ai/dsl/\n  - type: Support\n    url: https://plus.dimensions.ai/support/\n  - type: Blog\n    url: https://www.dimensions.ai/blog/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dimensions/refs/heads/main/apis.yml
tags:
- Analytics
- Research
- Publications
- Grants
- Patents
- Clinical Trials
- Jupyter Notebooks
url: https://raw.githubusercontent.com/api-evangelist/dimensions/refs/heads/main/apis.yml
use_cases: []
---
