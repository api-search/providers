---
api_count: 2
apis:
- description: RESTful API for managing rights, licenses, and availability data. Supports creation, retrieval, modification, and deletion of up to 100 records per request. Enables automation of rights tracking, avai
  name: Rightsline Rights API
  slug: rights-api
- description: RESTful API for managing royalties, revenue data, and financial workflows. Supports bulk loading of revenue, sales, and usage data. Enables automation of finance billing requests and royalty calculati
  name: Rightsline Royalties API
  slug: royalties-api
capabilities:
- description: 'Unified capability for Rightsline rights and royalties management. Enables rights licensing workflows, content availability checking, royalty tracking, workflow automation, and audit trail access for '
  name: Rightsline Rights and Royalties Management
  slug: rights-royalties-management
common:
- title: ''
  type: Website
  url: https://www.rightsline.com
- title: ''
  type: Documentation
  url: https://api-docs.rightsline.com/
- title: ''
  type: Portal
  url: https://app.rightsline.com
- title: ''
  type: PostmanWorkspace
  url: https://postman.rightsline.com/
- title: ''
  type: Authentication
  url: https://api-docs.rightsline.com/authentication/user-permissions
- title: ''
  type: GettingStarted
  url: https://api-docs.rightsline.com/getting-started
- title: ''
  type: Blog
  url: https://www.rightsline.com/resources/api-integration/
- title: ''
  type: TermsOfService
  url: https://www.rightsline.com/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://www.rightsline.com/privacy-policy/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/openapi/rightsline-openapi.yml
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/rules/rightsline-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/capabilities/rights-royalties-management.yaml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/json-schema/rightsline-right-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/json-schema/rightsline-royalty-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/json-ld/rightsline-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/vocabulary/rightsline-vocabulary.yml
created: '2025-02-08'
description: Rightsline is the leading rights and royalties software platform for media, entertainment, and content businesses. Its REST API enables real-time integration of contacts, product catalogs, revenue data, and workflow automation for rights tracking, availability, royalty calculations, and vendor delivery across the content lifecycle.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 35
  name: Rightsline Context
  property_count: 0
  slug: rightsline-context
layout: provider
modified: '2026-05-02'
name: Rightsline
rules:
- name: Rightsline API Rules
  rule_count: 11
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 6
  slug: rightsline-rules
skills: []
slug: rightsline
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rightsline\nname: Rightsline\ndescription: >-\n  Rightsline is the leading rights and royalties software platform for media,\n  entertainment, and content businesses. Its REST API enables real-time\n  integration of contacts, product catalogs, revenue data, and workflow\n  automation for rights tracking, availability, royalty calculations, and\n  vendor delivery across the content lifecycle.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Content Management\n  - Entertainment\n  - Media\n  - Rights Management\n  - Royalties\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/apis.yml\ncreated: '2025-02-08'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rightsline:rights-api\n    name: Rightsline Rights API\n    description: >-\n      RESTful API for managing rights, licenses, and availability data.\n      Supports creation, retrieval, modification, and\
  \ deletion of up to 100\n      records per request. Enables automation of rights tracking, availability\n      validation, vendor delivery requests, and workflow actions.\n    humanURL: https://api-docs.rightsline.com/\n    baseURL: https://app.rightsline.com/v4\n    tags:\n      - Availability\n      - Content\n      - Rights Management\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://api-docs.rightsline.com/\n      - type: PostmanWorkspace\n        url: https://postman.rightsline.com/\n      - type: Authentication\n        url: https://api-docs.rightsline.com/authentication/user-permissions\n  - aid: rightsline:royalties-api\n    name: Rightsline Royalties API\n    description: >-\n      RESTful API for managing royalties, revenue data, and financial workflows.\n      Supports bulk loading of revenue, sales, and usage data. Enables\n      automation of finance billing requests and royalty calculations.\n    humanURL: https://api-docs.rightsline.com/\n\
  \    baseURL: https://app.rightsline.com/v4\n    tags:\n      - Billing\n      - Finance\n      - Revenue\n      - Royalties\n    properties:\n      - type: Documentation\n        url: https://api-docs.rightsline.com/\n      - type: PostmanWorkspace\n        url: https://postman.rightsline.com/\ncommon:\n  - type: Website\n    url: https://www.rightsline.com\n  - type: Documentation\n    url: https://api-docs.rightsline.com/\n  - type: Portal\n    url: https://app.rightsline.com\n  - type: PostmanWorkspace\n    url: https://postman.rightsline.com/\n  - type: Authentication\n    url: https://api-docs.rightsline.com/authentication/user-permissions\n  - type: GettingStarted\n    url: https://api-docs.rightsline.com/getting-started\n  - type: Blog\n    url: https://www.rightsline.com/resources/api-integration/\n  - type: TermsOfService\n    url: https://www.rightsline.com/terms-of-service/\n  - type: PrivacyPolicy\n    url: https://www.rightsline.com/privacy-policy/\n  - type: OpenAPI\n  \
  \  url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/openapi/rightsline-openapi.yml\n  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/rules/rightsline-rules.yml\n  - type: NaftikoCapabilities\n    url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/capabilities/rights-royalties-management.yaml\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/json-schema/rightsline-right-schema.json\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/json-schema/rightsline-royalty-schema.json\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/json-ld/rightsline-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/vocabulary/rightsline-vocabulary.yml\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/apis.yml
tags:
- Content Management
- Entertainment
- Media
- Rights Management
- Royalties
url: https://raw.githubusercontent.com/api-evangelist/rightsline/refs/heads/main/apis.yml
use_cases: []
---
