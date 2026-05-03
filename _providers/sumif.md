---
api_count: 1
api_specs:
- filename: sumif.json
  format: json
  label: SUMIF API
  slug: ''
  spec_type: OpenAPI
  url: https://api.example.com/openapi/sumif.json
apis:
- description: Performs conditional summation based on specified criteria.
  name: SUMIF API
  slug: ''
common: []
created: '2024-01-15'
description: API for conditional sum operations across datasets.
features: []
image: https://example.com/sumif-logo.png
integrations: []
layout: provider
modified: '2026-03-16'
name: SUMIF
skills: []
slug: sumif
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SUMIF\ndescription: >-\n  API for conditional sum operations across datasets.\nimage: https://example.com/sumif-logo.png\nurl: https://api.example.com/sumif\ntags:\n  - Aggregation\n  - Calculation\n  - Conditional\n  - Data Analysis\n  - Spreadsheet\ncreated: '2024-01-15'\nmodified: '2026-03-16'\napis:\n  - name: SUMIF API\n    description: >-\n      Performs conditional summation based on specified criteria.\n    image: https://example.com/sumif-api.png\n    humanURL: https://docs.example.com/sumif\n    baseURL: https://api.example.com/v1\n    version: '1.0'\n    tags:\n      - Conditional\n      - Filtering\n      - Sum\n    properties:\n      - type: Documentation\n        url: https://docs.example.com/sumif/reference\n      - type: OpenAPI\n        url: https://api.example.com/openapi/sumif.json\n      - type: Swagger\n        url: https://api.example.com/swagger/sumif\n      - type: Postman Collection\n        url: https://www.postman.com/collections/sumif-api\n\
  \      - type: Authentication\n        url: https://docs.example.com/sumif/authentication\n      - type: Pricing\n        url: https://example.com/pricing\n      - type: Rate Limits\n        url: https://docs.example.com/sumif/rate-limits\n      - type: Status\n        url: https://status.example.com\n      - type: Support\n        url: https://support.example.com\n      - type: Terms of Service\n        url: https://example.com/terms\n      - type: Privacy Policy\n        url: https://example.com/privacy\n    contact:\n      - type: Email\n        url: mailto:api@example.com\n      - type: Twitter\n        url: https://twitter.com/exampleapi\n      - type: Support\n        url: https://support.example.com/contact\n    endpoints:\n      - name: Basic SUMIF\n        description: Sum values based on a single condition\n        method: POST\n        path: /sumif\n        parameters:\n          - name: range\n            type: array\n            required: true\n            description: Array\
  \ of values to evaluate\n          - name: criteria\n            type: string\n            required: true\n            description: Condition to match (e.g., \">100\", \"=Active\")\n          - name: sum_range\n            type: array\n            required: false\n            description: Array of values to sum (uses range if not specified)\n      - name: SUMIFS (Multiple Criteria)\n        description: Sum values based on multiple conditions\n        method: POST\n        path: /sumifs\n        parameters:\n          - name: sum_range\n            type: array\n            required: true\n            description: Array of values to sum\n          - name: criteria_ranges\n            type: array\n            required: true\n            description: Array of ranges to evaluate\n          - name: criteria\n            type: array\n            required: true\n            description: Array of conditions to match\n      - name: Batch SUMIF\n        description: Process multiple SUMIF operations\
  \ in a single request\n        method: POST\n        path: /sumif/batch\n        parameters:\n          - name: operations\n            type: array\n            required: true\n            description: Array of SUMIF operation objects\nmaintainers:\n  - name: API Team\n    email: api-team@example.com\n    url: https://example.com/team\ninclude:\n  - name: Related APIs\n    url: https://api.example.com/apis.json\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sumif/refs/heads/main/apis.yml
tags:
- Aggregation
- Calculation
- Conditional
- Data Analysis
- Spreadsheet
url: https://api.example.com/sumif
use_cases: []
---
