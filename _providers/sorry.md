---
api_count: 1
api_specs:
- filename: sorry-status-page-openapi.yml
  format: yaml
  label: Sorry Status Page API
  slug: sorry-status-page-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sorry/refs/heads/main/openapi/sorry-status-page-openapi.yml
apis:
- description: The Sorry™ REST API provides programmatic access to manage status pages, components, incident notices, notice updates, and subscriber lists. Supports Bearer token authentication and rate limiting of 1
  name: Sorry Status Page API
  slug: sorry-status-page-api
capabilities:
- description: Unified capability for automated incident communication workflows using the Sorry™ API. Enables DevOps and support teams to programmatically manage status pages, publish incident notices, post updates
  name: Sorry Incident Communications
  slug: incident-communications
common:
- title: ''
  type: Portal
  url: https://www.sorryapp.com/
- title: ''
  type: Documentation
  url: https://docs.sorryapp.com/v1
- title: ''
  type: Website
  url: https://www.sorryapp.com/
- title: ''
  type: Status API
  url: https://www.sorryapp.com/status-api/
- title: ''
  type: Dashboard
  url: https://app.sorryapp.com/
- title: ''
  type: GitHub Org
  url: https://github.com/sorry-app
- title: ''
  type: Pricing
  url: https://www.sorryapp.com/pricing/
- title: ''
  type: Blog
  url: https://www.sorryapp.com/blog/
- title: ''
  type: Status Page
  url: https://status.sorryapp.com/
- title: ''
  type: Terms
  url: https://www.sorryapp.com/terms/
- title: ''
  type: Privacy Policy
  url: https://www.sorryapp.com/privacy/
created: '2026-03-16'
description: Sorry™ (SorryApp) is a status page platform that enables teams to communicate planned and unplanned service interruptions to their customers. The Sorry REST API provides full programmatic control over status pages, components, incident notices, notice updates, and subscriber management. Build automated incident communication workflows that integrate with monitoring tools, alerting platforms, and customer notification systems.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Sorry Context
  property_count: 16
  slug: sorry-context
layout: provider
modified: '2026-05-02'
name: Sorry
rules:
- name: Sorry API Rules
  rule_count: 12
  severity_counts:
    error: 3
    hint: 0
    info: 2
    warn: 7
  slug: sorry-rules
skills: []
slug: sorry
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sorry\nname: Sorry\ndescription: >-\n  Sorry™ (SorryApp) is a status page platform that enables teams to communicate\n  planned and unplanned service interruptions to their customers. The Sorry REST\n  API provides full programmatic control over status pages, components, incident\n  notices, notice updates, and subscriber management. Build automated incident\n  communication workflows that integrate with monitoring tools, alerting platforms,\n  and customer notification systems.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Status Pages\n  - Incident Management\n  - Developer Tools\n  - Monitoring\n  - Notifications\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sorry/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: sorry:sorry-status-page-api\n    name: Sorry Status Page API\n    description:\
  \ >-\n      The Sorry™ REST API provides programmatic access to manage status pages,\n      components, incident notices, notice updates, and subscriber lists. Supports\n      Bearer token authentication and rate limiting of 10 requests per second.\n    humanURL: https://docs.sorryapp.com/v1\n    baseURL: https://api.sorryapp.com/v1\n    tags:\n      - Status Pages\n      - Incident Management\n      - Notifications\n      - Subscribers\n    properties:\n      - type: Documentation\n        url: https://docs.sorryapp.com/v1\n      - type: Reference\n        url: https://docs.sorryapp.com/v1\n      - type: Getting Started\n        url: https://app.sorryapp.com\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sorry/refs/heads/main/openapi/sorry-status-page-openapi.yml\n    contact:\n      - FN: Sorry App Support\n        url: https://www.sorryapp.com/\n        email: ''\ncommon:\n  - type: Portal\n    url: https://www.sorryapp.com/\n  -\
  \ type: Documentation\n    url: https://docs.sorryapp.com/v1\n  - type: Website\n    url: https://www.sorryapp.com/\n  - type: Status API\n    url: https://www.sorryapp.com/status-api/\n  - type: Dashboard\n    url: https://app.sorryapp.com/\n  - type: GitHub Org\n    url: https://github.com/sorry-app\n  - type: Pricing\n    url: https://www.sorryapp.com/pricing/\n  - type: Blog\n    url: https://www.sorryapp.com/blog/\n  - type: Status Page\n    url: https://status.sorryapp.com/\n  - type: Integrations\n    url: https://www.sorryapp.com/integrations/\n  - type: Terms\n    url: https://www.sorryapp.com/terms/\n  - type: Privacy Policy\n    url: https://www.sorryapp.com/privacy/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sorry/refs/heads/main/apis.yml
tags:
- Status Pages
- Incident Management
- Developer Tools
- Monitoring
- Notifications
url: https://raw.githubusercontent.com/api-evangelist/sorry/refs/heads/main/apis.yml
use_cases: []
---
