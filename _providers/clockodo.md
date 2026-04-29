---
api_count: 1
api_specs:
- filename: clockodo-openapi.yml
  format: yaml
  label: Clockodo API
  slug: clockodo-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clockodo/refs/heads/main/openapi/clockodo-openapi.yml
apis:
- description: The Clockodo API is a REST interface at my.clockodo.com that lets developers automate time tracking and project management. v2 endpoints under /api/v2 cover entries, customers, projects, services, use
  name: Clockodo API
  slug: clockodo-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.clockodo.com/en/
- title: ''
  type: Documentation
  url: https://www.clockodo.com/en/api/
- title: ''
  type: Blog
  url: https://www.clockodo.com/en/blog/
- title: ''
  type: Pricing
  url: https://www.clockodo.com/en/pricing/
- title: ''
  type: TermsOfService
  url: https://www.clockodo.com/en/terms-and-conditions/
- title: ''
  type: PrivacyPolicy
  url: https://www.clockodo.com/en/data-privacy/
- title: ''
  type: OpenAPI
  url: openapi/clockodo-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/clockodo-entry-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/clockodo-context.jsonld
- title: ''
  type: Spectral
  url: rules/clockodo-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/clockodo-capabilities.yml
created: '2025-02-17'
description: 'Clockodo is a German-built, cloud-based time-tracking and project- management application used by service firms, agencies, and freelancers. In addition to its web and mobile apps, Clockodo exposes a REST API at my.clockodo.com that mirrors the objects in the UI: time entries, customers, projects, services, users, absences, holiday quotas, lump-sum services, and a real-time stop-clock. Authentication uses a per-user email plus per-user API key delivered as the X-ClockodoApiUser/X-ClockodoApiKey header pair (or HTTP Basic), and every call must include the X-Clockodo-External-Application header identifying the integrating application.'
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 7
  name: Clockodo Context
  property_count: 10
  slug: clockodo-context
layout: provider
modified: '2026-04-27'
name: Clockodo
rules:
- name: Clockodo API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: clockodo-rules
skills: []
slug: clockodo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: clockodo\nname: Clockodo\nurl: https://raw.githubusercontent.com/api-evangelist/clockodo/refs/heads/main/apis.yml\ncreated: '2025-02-17'\nmodified: '2026-04-27'\nspecificationVersion: '0.19'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nx-type: company\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Absence Management\n  - Billing\n  - Project Management\n  - Stop Clock\n  - Time Tracking\n  - Timesheets\ndescription: >-\n  Clockodo is a German-built, cloud-based time-tracking and project-\n  management application used by service firms, agencies, and freelancers.\n  In addition to its web and mobile apps, Clockodo exposes a REST API at\n  my.clockodo.com that mirrors the objects in the UI: time entries,\n  customers, projects, services, users, absences, holiday quotas,\n  lump-sum services, and a real-time stop-clock. Authentication uses a\n  per-user email plus per-user API key delivered as the\n  X-ClockodoApiUser/X-ClockodoApiKey\
  \ header pair (or HTTP Basic), and\n  every call must include the X-Clockodo-External-Application header\n  identifying the integrating application.\napis:\n  - aid: clockodo:clockodo-api\n    name: Clockodo API\n    tags:\n      - Absence Management\n      - Billing\n      - Project Management\n      - Stop Clock\n      - Time Tracking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.clockodo.com/en/api/\n    baseURL: https://my.clockodo.com/api\n    properties:\n      - url: https://www.clockodo.com/en/api/\n        type: Documentation\n      - url: https://www.clockodo.com/en/api/authentication/\n        type: Authentication\n      - url: openapi/clockodo-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Clockodo API is a REST interface at my.clockodo.com that lets\n      developers automate time tracking and project management. v2\n      endpoints under /api/v2 cover entries, customers, projects,\n  \
  \    services, users, lump-sum services, and the stop-clock; legacy\n      endpoints under /api cover absences and holiday quotas. Calls\n      authenticate with X-ClockodoApiUser plus X-ClockodoApiKey (or\n      HTTP Basic with the same credentials) and identify the calling\n      app via X-Clockodo-External-Application; responses are JSON.\ncommon:\n  - type: Website\n    url: https://www.clockodo.com/en/\n  - type: Documentation\n    url: https://www.clockodo.com/en/api/\n  - type: Blog\n    url: https://www.clockodo.com/en/blog/\n  - type: Pricing\n    url: https://www.clockodo.com/en/pricing/\n  - type: TermsOfService\n    url: https://www.clockodo.com/en/terms-and-conditions/\n  - type: PrivacyPolicy\n    url: https://www.clockodo.com/en/data-privacy/\n  - type: OpenAPI\n    url: openapi/clockodo-openapi.yml\n  - type: JSONSchema\n    url: json-schema/clockodo-entry-schema.json\n  - type: JSONLDContext\n    url: json-ld/clockodo-context.jsonld\n  - type: Spectral\n    url: rules/clockodo-rules.yml\n\
  \  - type: Naftiko Capabilities\n    url: capabilities/clockodo-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/clockodo/refs/heads/main/apis.yml
tags:
- Absence Management
- Billing
- Project Management
- Stop Clock
- Time Tracking
- Timesheets
url: https://raw.githubusercontent.com/api-evangelist/clockodo/refs/heads/main/apis.yml
use_cases: []
---
