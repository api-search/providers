---
api_count: 1
api_specs:
- filename: Benefits.json
  format: json
  label: Workday Benefits API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Benefits/v40.2/Benefits.json
apis:
- description: Comprehensive API for managing employee benefits including health insurance, retirement plans, time off, and other benefit programs.
  name: Workday Benefits API
  slug: ''
capabilities:
- description: Unified capability for HR and benefits teams managing Workday employee benefits including health insurance enrollments, retirement plans, dependent management, qualifying life events, and time off adm
  name: Workday Benefits Administration
  slug: benefits-administration
common:
- title: ''
  type: Getting Started
  url: https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/_wTPrHlQFO6kuhPPQvXUdg
- title: ''
  type: Developer Portal
  url: https://developer.workday.com
- title: ''
  type: Authentication Guide
  url: https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/bRN0dJVT1fKqLxCRjJCx6w
- title: ''
  type: SDKs
  url: https://github.com/Workday
- title: ''
  type: Blog
  url: https://blog.workday.com/en-us/technology.html
- title: ''
  type: Privacy Policy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: JSON-LD
  url: json-ld/workday-benefits-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/workday-benefits-spectral-rules.yml
- title: ''
  type: NaftikoCapability - Benefits Administration
  url: capabilities/benefits-administration.yaml
- title: ''
  type: NaftikoCapability - Benefits (Shared)
  url: capabilities/shared/benefits.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/workday-benefits-vocabulary.yml
created: '2024-01-01'
description: APIs for managing employee benefits, enrollments, and benefits administration in Workday.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 25
  name: Workday Benefits Context
  property_count: 14
  slug: workday-benefits-context
layout: provider
modified: '2026-05-03'
name: Workday Benefits
rules:
- name: Workday Benefits API Rules
  rule_count: 36
  severity_counts:
    error: 6
    hint: 0
    info: 11
    warn: 19
  slug: workday-benefits-spectral-rules
skills: []
slug: workday-benefits
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: workday-benefits\nname: Workday Benefits\ndescription: >-\n  APIs for managing employee benefits, enrollments, and benefits administration in\n  Workday.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/workday-benefits/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - name: Workday Benefits API\n    description: >-\n      Comprehensive API for managing employee benefits including health insurance,\n      retirement plans, time off, and other benefit programs.\n    image: https://www.workday.com/content/dam/web/images/logo.png\n    humanURL: https://www.workday.com/en-us/products/human-capital-management/benefits.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/service\n    tags:\n      - Benefits\n      - Employee Benefits\n      - Enrollments\n      - Health Insurance\n      - Human Resources\n    \
  \  - Retirement\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Benefits/v40.2/Get_Benefits.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Benefits/v40.2/Benefits.json\n      - type: Authentication\n        url: https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/bRN0dJVT1fKqLxCRjJCx6w\n      - type: Postman Collection\n        url: https://www.postman.com/workday/workspace/workday-rest-api\n      - type: Rate Limits\n        url: https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/VNmXGO5eT8oGWtOQRPd46w\n      - type: Change Log\n        url: https://community.workday.com/api-versions\n      - type: Status Page\n        url: https://status.workday.com\n      - type: Terms of Service\n        url: https://www.workday.com/en-us/legal.html\n      - type: Support\n        url: https://community.workday.com/\n      - type: OpenAPI\n\
  \        url: openapi/workday-benefits-openapi.yml\n      - type: JSONSchema\n        url: json-schema/workday-benefits-benefit-plan-schema.json\n      - type: JSONSchema\n        url: json-schema/workday-benefits-benefit-enrollment-schema.json\n      - type: JSONSchema\n        url: json-schema/workday-benefits-benefit-enrollment-request-schema.json\n      - type: JSONSchema\n        url: json-schema/workday-benefits-dependent-schema.json\n      - type: JSONSchema\n        url: json-schema/workday-benefits-benefit-event-schema.json\n      - type: JSONSchema\n        url: json-schema/workday-benefits-time-off-plan-schema.json\n      - type: JSONSchema\n        url: json-schema/workday-benefits-employee-benefits-schema.json\n      - type: JSONStructure\n        url: json-structure/workday-benefits-benefit-plan-structure.json\n      - type: JSONStructure\n        url: json-structure/workday-benefits-benefit-enrollment-structure.json\n      - type: JSONStructure\n        url: json-structure/workday-benefits-benefit-enrollment-request-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/workday-benefits-dependent-structure.json\n      - type: JSONStructure\n        url: json-structure/workday-benefits-benefit-event-structure.json\n      - type: JSONStructure\n        url: json-structure/workday-benefits-time-off-plan-structure.json\n      - type: JSONStructure\n        url: json-structure/workday-benefits-employee-benefits-structure.json\n      - type: JSONLd\n        url: json-ld/workday-benefits-context.jsonld\n      - type: SpectralRules\n        url: rules/workday-benefits-spectral-rules.yml\n      - type: NaftikoCapability - Benefits Administration\n        url: capabilities/benefits-administration.yaml\n      - type: NaftikoCapability - Benefits (Shared)\n        url: capabilities/shared/benefits.yaml\n      - type: Vocabulary\n        url: vocabulary/workday-benefits-vocabulary.yml\n    contact:\n      - type: Support\n        url: https://community.workday.com/support\ncommon:\n  - type: Getting Started\n\
  \    url: https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/_wTPrHlQFO6kuhPPQvXUdg\n  - type: Developer Portal\n    url: https://developer.workday.com\n  - type: Authentication Guide\n    url: https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/bRN0dJVT1fKqLxCRjJCx6w\n  - type: SDKs\n    url: https://github.com/Workday\n  - type: Blog\n    url: https://blog.workday.com/en-us/technology.html\n  - type: Privacy Policy\n    url: https://www.workday.com/en-us/privacy.html\n  - type: JSON-LD\n    url: json-ld/workday-benefits-context.jsonld\n  - type: SpectralRules\n    url: rules/workday-benefits-spectral-rules.yml\n  - type: NaftikoCapability - Benefits Administration\n    url: capabilities/benefits-administration.yaml\n  - type: NaftikoCapability - Benefits (Shared)\n    url: capabilities/shared/benefits.yaml\n  - type: Vocabulary\n    url: vocabulary/workday-benefits-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday-benefits/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/workday-benefits/refs/heads/main/apis.yml
use_cases: []
---
