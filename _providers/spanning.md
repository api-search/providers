---
api_count: 2
api_specs:
- filename: spanning-google-workspace-api-openapi.yml
  format: yaml
  label: Spanning Backup for Google Workspace API
  slug: spanning-google-workspace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/openapi/spanning-google-workspace-api-openapi.yml
apis:
- description: RESTful API for managing Spanning Backup for Google Workspace. Supports user license management (assign, unassign, list, get), shared drives backup management (list, export), and export operations (in
  name: Spanning Backup for Google Workspace API
  slug: spanning-google-workspace-api
- description: RESTful API for managing Spanning Backup for Microsoft 365. Region-specific endpoints (US, EU, AP, CA, UK) for user license management and data export operations. Authentication uses API tokens obtain
  name: Spanning Backup for Microsoft 365 API
  slug: spanning-microsoft365-api
capabilities:
- description: Workflow capability for managing SaaS data protection across Microsoft 365, Google Workspace, and Salesforce via Spanning Backup. Enables IT admins and MSPs to manage backup license assignments, monit
  name: Spanning SaaS Data Protection
  slug: saas-data-protection
common:
- title: ''
  type: Website
  url: https://spanning.com
- title: ''
  type: Documentation
  url: https://spanning.com/resources
- title: ''
  type: APIReference
  url: https://api.spanningbackup.com/index.html
- title: ''
  type: GitHub
  url: https://github.com/SpanningCloudApps
- title: ''
  type: Pricing
  url: https://spanning.com/pricing/
created: '2026-03-27'
description: Spanning (by Kaseya) is a SaaS backup and recovery platform providing cloud-to-cloud data protection for Microsoft 365, Google Workspace, and Salesforce. It protects over 24,000 organizations and 2.5 million users with automated daily backups, unlimited on-demand backups, infinite retention, and granular point-in-time restore. Spanning exposes RESTful APIs for managing user licenses and exporting backed-up account data for Google Workspace and Microsoft 365.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 10
  name: Spanning Context
  property_count: 11
  slug: spanning-context
layout: provider
modified: '2026-05-02'
name: Spanning
rules:
- name: Spanning API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 2
    warn: 5
  slug: spanning-rules
skills: []
slug: spanning
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spanning\nname: Spanning\ndescription: >-\n  Spanning (by Kaseya) is a SaaS backup and recovery platform providing cloud-to-cloud\n  data protection for Microsoft 365, Google Workspace, and Salesforce. It protects over\n  24,000 organizations and 2.5 million users with automated daily backups, unlimited\n  on-demand backups, infinite retention, and granular point-in-time restore. Spanning\n  exposes RESTful APIs for managing user licenses and exporting backed-up account data\n  for Google Workspace and Microsoft 365.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Protection\n  - SaaS Backup\n  - Cloud Backup\n  - Microsoft 365\n  - Google Workspace\n  - Salesforce\nurl: https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: spanning:spanning-google-workspace-api\n    name: Spanning Backup\
  \ for Google Workspace API\n    description: >-\n      RESTful API for managing Spanning Backup for Google Workspace. Supports user license\n      management (assign, unassign, list, get), shared drives backup management (list,\n      export), and export operations (initiate, list, get). Authentication uses API tokens\n      obtained from the Spanning admin portal Settings tab.\n    humanURL: https://spanning.com/products/google-workspace-backup/\n    baseURL: https://api.spanningbackup.com\n    tags:\n      - Data Protection\n      - SaaS Backup\n      - Google Workspace\n      - Cloud Backup\n    properties:\n      - type: Documentation\n        url: https://api.spanningbackup.com/index.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/openapi/spanning-google-workspace-api-openapi.yml\n      - type: SpectralRules\n        url: https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/rules/spanning-rules.yml\n\
  \      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/json-schema/spanning-user-schema.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/json-structure/spanning-user-structure.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/json-ld/spanning-context.jsonld\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/vocabulary/spanning-vocabulary.yml\n  - aid: spanning:spanning-microsoft365-api\n    name: Spanning Backup for Microsoft 365 API\n    description: >-\n      RESTful API for managing Spanning Backup for Microsoft 365. Region-specific\n      endpoints (US, EU, AP, CA, UK) for user license management and data export operations.\n      Authentication uses API tokens obtained from the Spanning admin portal.\n    humanURL: https://spanning.com/products/microsoft-365-backup/\n\
  \    baseURL: https://o365-us.spanningbackup.com\n    tags:\n      - Data Protection\n      - SaaS Backup\n      - Microsoft 365\n      - Cloud Backup\n    properties:\n      - type: Documentation\n        url: https://o365-docs.spanningbackup.com/\n      - type: GitHubRepository\n        url: https://github.com/SpanningCloudApps/SB365-Powershell\ncommon:\n  - type: Website\n    url: https://spanning.com\n  - type: Documentation\n    url: https://spanning.com/resources\n  - type: APIReference\n    url: https://api.spanningbackup.com/index.html\n  - type: GitHub\n    url: https://github.com/SpanningCloudApps\n  - type: Pricing\n    url: https://spanning.com/pricing/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/apis.yml
tags:
- Data Protection
- SaaS Backup
- Cloud Backup
- Microsoft 365
- Google Workspace
- Salesforce
url: https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/apis.yml
use_cases: []
---
