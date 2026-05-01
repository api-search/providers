---
api_count: 1
api_specs:
- filename: grafana-api.yml
  format: yaml
  label: Grafana HTTP API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grafana/refs/heads/main/openapi/grafana-api.yml
apis:
- description: RESTful API for managing Grafana resources including dashboards, data sources, alert rules, users, organizations, folders, annotations, and teams. Supports authentication via API keys, basic auth, and
  name: Grafana HTTP API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://grafana.com
- title: ''
  type: Getting Started
  url: https://grafana.com/docs/grafana/latest/getting-started/
- title: ''
  type: Documentation
  url: https://grafana.com/docs/grafana/latest/
- title: ''
  type: Authentication
  url: https://grafana.com/docs/grafana/latest/administration/service-accounts/
- title: ''
  type: Pricing
  url: https://grafana.com/pricing/
- title: ''
  type: Terms of Service
  url: https://grafana.com/legal/terms/
- title: ''
  type: Privacy Policy
  url: https://grafana.com/legal/privacy-policy/
- title: ''
  type: Status
  url: https://status.grafana.com/
- title: ''
  type: Support
  url: https://grafana.com/support/
- title: ''
  type: Blog
  url: https://grafana.com/blog/
created: '2025-01-01'
description: Grafana is the open-source analytics and monitoring platform that connects to a wide range of data sources including Prometheus, Loki, Elasticsearch, InfluxDB, MySQL, PostgreSQL, and cloud providers. It provides a comprehensive HTTP API for managing dashboards, data sources, alert rules, users, organizations, folders, annotations, and teams.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Grafana Context
  property_count: 12
  slug: grafana-context
layout: provider
modified: '2026-03-16'
name: Grafana
skills: []
slug: grafana
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: grafana\nname: Grafana\ndescription: >-\n  Grafana is the open-source analytics and monitoring platform that connects\n  to a wide range of data sources including Prometheus, Loki, Elasticsearch,\n  InfluxDB, MySQL, PostgreSQL, and cloud providers. It provides a comprehensive\n  HTTP API for managing dashboards, data sources, alert rules, users,\n  organizations, folders, annotations, and teams.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://grafana.com\ncreated: '2025-01-01'\nmodified: '2026-03-16'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Alerting\n  - Analytics\n  - Dashboards\n  - Logs\n  - Metrics\n  - Monitoring\n  - Observability\n  - Traces\n  - Visualization\napis:\n  - name: Grafana HTTP API\n    description: >-\n      RESTful API for managing Grafana resources including dashboards, data\n      sources, alert rules, users, organizations, folders, annotations, and\n      teams. Supports authentication\
  \ via API keys, basic auth, and OAuth tokens.\n    humanURL: https://grafana.com/docs/grafana/latest/developers/http_api/\n    baseURL: http://localhost:3000/api\n    tags:\n      - Alerts\n      - Annotations\n      - Dashboards\n      - Data Sources\n      - Folders\n      - Organizations\n      - Teams\n      - Users\n    properties:\n      - type: Documentation\n        url: https://grafana.com/docs/grafana/latest/developers/http_api/\n      - type: OpenAPI\n        url: openapi/grafana-api.yml\n      - type: Authentication\n        url: https://grafana.com/docs/grafana/latest/administration/service-accounts/\n      - type: Getting Started\n        url: https://grafana.com/docs/grafana/latest/getting-started/\n      - type: JSONSchema\n        url: json-schema/dashboard.json\ncommon:\n  - type: Portal\n    url: https://grafana.com\n  - type: Getting Started\n    url: https://grafana.com/docs/grafana/latest/getting-started/\n  - type: Documentation\n    url: https://grafana.com/docs/grafana/latest/\n\
  \  - type: Authentication\n    url: https://grafana.com/docs/grafana/latest/administration/service-accounts/\n  - type: Pricing\n    url: https://grafana.com/pricing/\n  - type: Terms of Service\n    url: https://grafana.com/legal/terms/\n  - type: Privacy Policy\n    url: https://grafana.com/legal/privacy-policy/\n  - type: Status\n    url: https://status.grafana.com/\n  - type: Support\n    url: https://grafana.com/support/\n  - type: Blog\n    url: https://grafana.com/blog/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/grafana/refs/heads/main/apis.yml
tags:
- Alerting
- Analytics
- Dashboards
- Logs
- Metrics
- Monitoring
- Observability
- Traces
- Visualization
url: https://grafana.com
use_cases: []
---
