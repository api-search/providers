---
api_count: 1
apis:
- description: The CloudAlly API is a JSON REST interface at api.cloudally.com. Partners authenticate by exchanging a Client ID and Client Secret at /auth/partner for an access token, while portal users sign in at /
  name: CloudAlly API
  slug: cloudally-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.cloudally.com
- title: ''
  type: Documentation
  url: https://api.cloudally.com/documentation
- title: ''
  type: Support
  url: https://support.cloudally.com/
- title: ''
  type: TermsOfService
  url: https://www.cloudally.com/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://www.cloudally.com/privacy-policy/
- title: ''
  type: ParentCompany
  url: https://cybersecurity.opentext.com/legacy/cloudally/
- title: ''
  type: OpenAPI
  url: openapi/cloudally-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/cloudally-backup-task-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/cloudally-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloudally-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cloudally-capabilities.yml
created: '2026-03-27'
description: CloudAlly (now part of OpenText Cybersecurity) is a SaaS backup and recovery service that protects business data in Microsoft 365, Google Workspace, Salesforce, Box, Dropbox, SharePoint, and OneDrive. The platform offers automated daily backups, point-in-time restore, cross-user restore, granular search, and partner-portal multitenancy features. Beyond the web console, CloudAlly exposes a REST API at api.cloudally.com that lets administrators and partners automate backup-task management, restore/download requests, user provisioning, partner-portal operations, and billing reporting.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Cloudally Context
  property_count: 8
  slug: cloudally-context
layout: provider
modified: '2026-04-27'
name: CloudAlly
rules:
- name: CloudAlly API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: cloudally-rules
skills: []
slug: cloudally
solutions: []
source_yaml: "aid: cloudally\nname: CloudAlly\nurl: https://raw.githubusercontent.com/api-evangelist/cloudally/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-27'\nspecificationVersion: '0.19'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nx-type: company\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Backup\n  - Box\n  - Data Protection\n  - Disaster Recovery\n  - Dropbox\n  - Google Workspace\n  - Microsoft 365\n  - OpenText\n  - SaaS Backup\n  - Salesforce\ndescription: >-\n  CloudAlly (now part of OpenText Cybersecurity) is a SaaS backup and\n  recovery service that protects business data in Microsoft 365, Google\n  Workspace, Salesforce, Box, Dropbox, SharePoint, and OneDrive. The\n  platform offers automated daily backups, point-in-time restore,\n  cross-user restore, granular search, and partner-portal multitenancy\n  features. Beyond the web console, CloudAlly exposes a REST API at\n  api.cloudally.com that\
  \ lets administrators and partners automate\n  backup-task management, restore/download requests, user provisioning,\n  partner-portal operations, and billing reporting.\napis:\n  - aid: cloudally:cloudally-api\n    name: CloudAlly API\n    tags:\n      - Backup\n      - Data Protection\n      - Partner Portal\n      - Restore\n      - SaaS Backup\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://api.cloudally.com/documentation\n    baseURL: https://api.cloudally.com\n    properties:\n      - url: https://api.cloudally.com/documentation\n        type: Documentation\n      - url: https://support.cloudally.com/\n        type: Support\n      - url: openapi/cloudally-openapi.yml\n        type: OpenAPI\n    description: >-\n      The CloudAlly API is a JSON REST interface at api.cloudally.com.\n      Partners authenticate by exchanging a Client ID and Client Secret\n      at /auth/partner for an access token, while portal users sign\
  \ in\n      at /auth; the resulting token is presented as an Authorization\n      Bearer header. Endpoints expose backup tasks, restore/download\n      jobs, partner profile data, billing, resellers, and user\n      management. The Partner Portal API today is read-oriented (GET),\n      with administrative actions performed via the standard tenant\n      endpoints.\ncommon:\n  - type: Website\n    url: https://www.cloudally.com\n  - type: Documentation\n    url: https://api.cloudally.com/documentation\n  - type: Support\n    url: https://support.cloudally.com/\n  - type: TermsOfService\n    url: https://www.cloudally.com/terms-of-service/\n  - type: PrivacyPolicy\n    url: https://www.cloudally.com/privacy-policy/\n  - type: ParentCompany\n    url: https://cybersecurity.opentext.com/legacy/cloudally/\n  - type: OpenAPI\n    url: openapi/cloudally-openapi.yml\n  - type: JSONSchema\n    url: json-schema/cloudally-backup-task-schema.json\n  - type: JSONLDContext\n    url: json-ld/cloudally-context.jsonld\n\
  \  - type: Spectral\n    url: rules/cloudally-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cloudally-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudally/refs/heads/main/apis.yml
tags:
- Backup
- Box
- Data Protection
- Disaster Recovery
- Dropbox
- Google Workspace
- Microsoft 365
- OpenText
- SaaS Backup
- Salesforce
url: https://raw.githubusercontent.com/api-evangelist/cloudally/refs/heads/main/apis.yml
use_cases: []
---
