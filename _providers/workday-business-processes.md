---
api_count: 1
api_specs:
- filename: Business_Process_Service.yaml
  format: yaml
  label: Workday Business Process API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Business_Process_Service/v41.1/Business_Process_Service.yaml
apis:
- description: API for initiating, managing, and monitoring business processes in Workday, including approvals, onboarding, and other workflow operations.
  name: Workday Business Process API
  slug: ''
capabilities:
- description: Unified capability for managers and HR teams managing Workday business processes including initiating workflows, processing approvals, managing inbox items, and monitoring process status.
  name: Workday Workflow Management
  slug: workflow-management
common:
- title: ''
  type: Portal
  url: https://community.workday.com
- title: ''
  type: Getting Started
  url: https://doc.workday.com/admin-guide/en-us/workday-web-services/wws-overview/getting-started-with-workday-web-services.html
- title: ''
  type: API Standards
  url: https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-overview.html
- title: ''
  type: Privacy Policy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: Terms of Service
  url: https://www.workday.com/en-us/terms-of-service.html
- title: ''
  type: Security
  url: https://www.workday.com/en-us/why-workday/our-technology/security.html
- title: ''
  type: JSON-LD
  url: json-ld/workday-business-processes-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/workday-business-processes-spectral-rules.yml
- title: ''
  type: NaftikoCapability - Workflow Management
  url: capabilities/workflow-management.yaml
- title: ''
  type: NaftikoCapability - Business Processes (Shared)
  url: capabilities/shared/business-processes.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/workday-business-processes-vocabulary.yml
created: '2024-01-01'
description: APIs for managing and executing business processes within Workday, including initiating, monitoring, and completing various workflow processes.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 31
  name: Workday Business Processes Context
  property_count: 11
  slug: workday-business-processes-context
layout: provider
modified: '2026-05-03'
name: Workday Business Processes
rules:
- name: Workday Business Processes API Rules
  rule_count: 36
  severity_counts:
    error: 7
    hint: 0
    info: 8
    warn: 21
  slug: workday-business-processes-spectral-rules
skills: []
slug: workday-business-processes
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: workday-business-processes\nname: Workday Business Processes\ndescription: APIs for managing and executing business processes within Workday, including initiating, monitoring, and completing various workflow processes.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/workday-business-processes/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - name: Workday Business Process API\n    description: API for initiating, managing, and monitoring business processes in Workday, including approvals, onboarding, and other workflow operations.\n    image: https://www.workday.com/content/dam/web/images/logos/workday-logo.svg\n    humanURL: https://www.workday.com/en-us/products/financial-management/business-process.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/service\n    tags:\n      - Approvals\n      - Business\
  \ Processes\n      - Finance\n      - HCM\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Business_Process_Service/v41.1/Business_Process_Service.yaml\n      - type: Authentication\n        url: https://doc.workday.com/admin-guide/en-us/workday-web-services/wws-overview/wws-authentication.html\n      - type: SDKs\n        url: https://github.com/Workday\n      - type: Rate Limits\n        url: https://doc.workday.com/admin-guide/en-us/workday-web-services/wws-overview/wws-rate-limits.html\n      - type: Webhooks\n        url: https://doc.workday.com/admin-guide/en-us/workday-integrations/integration-concepts/workday-webhooks.html\n      - type: Changelog\n        url: https://community.workday.com/api-release-notes\n      - type: Status\n        url: https://status.workday.com\n\
  \      - type: Support\n        url: https://community.workday.com\n      - type: OpenAPI\n        url: openapi/workday-business-processes-openapi.yml\n      - type: JSONSchema\n        url: json-schema/workday-business-processes-business-process-definition-schema.json\n      - type: JSONSchema\n        url: json-schema/workday-business-processes-process-instance-schema.json\n      - type: JSONSchema\n        url: json-schema/workday-business-processes-initiate-process-request-schema.json\n      - type: JSONSchema\n        url: json-schema/workday-business-processes-process-step-schema.json\n      - type: JSONSchema\n        url: json-schema/workday-business-processes-inbox-item-schema.json\n      - type: JSONSchema\n        url: json-schema/workday-business-processes-approval-request-schema.json\n      - type: JSONSchema\n        url: json-schema/workday-business-processes-denial-request-schema.json\n      - type: JSONStructure\n        url: json-structure/workday-business-processes-business-process-definition-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/workday-business-processes-process-instance-structure.json\n      - type: JSONStructure\n        url: json-structure/workday-business-processes-initiate-process-request-structure.json\n      - type: JSONStructure\n        url: json-structure/workday-business-processes-process-step-structure.json\n      - type: JSONStructure\n        url: json-structure/workday-business-processes-inbox-item-structure.json\n      - type: JSONStructure\n        url: json-structure/workday-business-processes-approval-request-structure.json\n      - type: JSONStructure\n        url: json-structure/workday-business-processes-denial-request-structure.json\n      - type: JSONLd\n        url: json-ld/workday-business-processes-context.jsonld\n      - type: SpectralRules\n        url: rules/workday-business-processes-spectral-rules.yml\n      - type: NaftikoCapability - Workflow Management\n        url: capabilities/workflow-management.yaml\n      - type:\
  \ NaftikoCapability - Business Processes (Shared)\n        url: capabilities/shared/business-processes.yaml\n      - type: Vocabulary\n        url: vocabulary/workday-business-processes-vocabulary.yml\n    contact:\n      - type: Support\n        url: https://www.workday.com/en-us/company/customer-support.html\ncommon:\n  - type: Portal\n    url: https://community.workday.com\n  - type: Getting Started\n    url: https://doc.workday.com/admin-guide/en-us/workday-web-services/wws-overview/getting-started-with-workday-web-services.html\n  - type: API Standards\n    url: https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-overview.html\n  - type: Privacy Policy\n    url: https://www.workday.com/en-us/privacy.html\n  - type: Terms of Service\n    url: https://www.workday.com/en-us/terms-of-service.html\n  - type: Security\n    url: https://www.workday.com/en-us/why-workday/our-technology/security.html\n  - type: JSON-LD\n    url: json-ld/workday-business-processes-context.jsonld\n\
  \  - type: SpectralRules\n    url: rules/workday-business-processes-spectral-rules.yml\n  - type: NaftikoCapability - Workflow Management\n    url: capabilities/workflow-management.yaml\n  - type: NaftikoCapability - Business Processes (Shared)\n    url: capabilities/shared/business-processes.yaml\n  - type: Vocabulary\n    url: vocabulary/workday-business-processes-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday-business-processes/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/workday-business-processes/refs/heads/main/apis.yml
use_cases: []
---
