---
api_count: 2
api_specs:
- filename: grafana-dashboard-openapi.yml
  format: yaml
  label: Grafana HTTP API
  slug: grafana
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tableaux-de-bord/refs/heads/main/openapi/grafana-dashboard-openapi.yml
apis:
- description: 'The Grafana HTTP API provides programmatic access to Grafana''s dashboard, datasource, alerting, organization, user, and annotation management capabilities. Grafana is an open-source observability and '
  name: Grafana HTTP API
  slug: grafana
- description: 'The Metabase REST API enables automation of business intelligence workflows including creating and managing dashboards, running questions (queries), managing users and groups, and embedding analytics '
  name: Metabase API
  slug: metabase
common:
- title: ''
  type: Grafana Website
  url: https://grafana.com/
- title: ''
  type: Metabase Website
  url: https://www.metabase.com/
- title: ''
  type: Grafana Documentation
  url: https://grafana.com/docs/grafana/latest/developer-resources/api-reference/http-api/
- title: ''
  type: Metabase Documentation
  url: https://www.metabase.com/learn/metabase-basics/administration/administration-and-operation/metabase-api
- title: ''
  type: Grafana GitHub
  url: https://github.com/grafana/grafana
- title: ''
  type: Metabase GitHub
  url: https://github.com/metabase/metabase
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/tableaux-de-bord/refs/heads/main/vocabulary/tableaux-de-bord-vocabulary.yml
created: '2026-03-16'
description: Tableaux de Bord (French for "dashboards") is an API industry topic covering dashboard and data visualization APIs. The landscape includes open-source platforms such as Grafana (with its comprehensive HTTP API for dashboards, datasources, and alerting) and Metabase (with its REST API for questions, dashboards, and administration). These tools enable programmatic creation and management of business intelligence dashboards for monitoring, analytics, and operational visibility.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 22
  name: Tableaux De Bord Context
  property_count: 0
  slug: tableaux-de-bord-context
layout: provider
modified: '2026-05-03'
name: Tableaux De Bord
skills: []
slug: tableaux-de-bord
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tableaux-de-bord\nname: Tableaux De Bord\ndescription: >-\n  Tableaux de Bord (French for \"dashboards\") is an API industry topic covering\n  dashboard and data visualization APIs. The landscape includes open-source\n  platforms such as Grafana (with its comprehensive HTTP API for dashboards,\n  datasources, and alerting) and Metabase (with its REST API for questions,\n  dashboards, and administration). These tools enable programmatic creation and\n  management of business intelligence dashboards for monitoring, analytics, and\n  operational visibility.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Dashboards\n  - Business Intelligence\n  - Analytics\n  - Data Visualization\n  - Monitoring\n  - Grafana\n  - Metabase\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tableaux-de-bord/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ tableaux-de-bord:grafana\n    name: Grafana HTTP API\n    description: >-\n      The Grafana HTTP API provides programmatic access to Grafana's dashboard,\n      datasource, alerting, organization, user, and annotation management\n      capabilities. Grafana is an open-source observability and analytics\n      platform widely used for infrastructure and application monitoring.\n    humanURL: https://grafana.com/docs/grafana/latest/developer-resources/api-reference/http-api/\n    baseURL: https://your-grafana-instance.com\n    tags:\n      - Grafana\n      - Dashboards\n      - Monitoring\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://grafana.com/docs/grafana/latest/developer-resources/api-reference/http-api/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tableaux-de-bord/refs/heads/main/openapi/grafana-dashboard-openapi.yml\n      - type: GitHub\n        url: https://github.com/grafana/grafana\n\
  \n  - aid: tableaux-de-bord:metabase\n    name: Metabase API\n    description: >-\n      The Metabase REST API enables automation of business intelligence workflows\n      including creating and managing dashboards, running questions (queries),\n      managing users and groups, and embedding analytics in applications.\n    humanURL: https://www.metabase.com/learn/metabase-basics/administration/administration-and-operation/metabase-api\n    baseURL: https://your-metabase-instance.com\n    tags:\n      - Metabase\n      - Business Intelligence\n      - Analytics\n      - Dashboards\n    properties:\n      - type: Documentation\n        url: https://www.metabase.com/learn/metabase-basics/administration/administration-and-operation/metabase-api\n      - type: GitHub\n        url: https://github.com/metabase/metabase\n\ncommon:\n  - type: Grafana Website\n    url: https://grafana.com/\n  - type: Metabase Website\n    url: https://www.metabase.com/\n  - type: Grafana Documentation\n    url:\
  \ https://grafana.com/docs/grafana/latest/developer-resources/api-reference/http-api/\n  - type: Metabase Documentation\n    url: https://www.metabase.com/learn/metabase-basics/administration/administration-and-operation/metabase-api\n  - type: Grafana GitHub\n    url: https://github.com/grafana/grafana\n  - type: Metabase GitHub\n    url: https://github.com/metabase/metabase\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tableaux-de-bord/refs/heads/main/vocabulary/tableaux-de-bord-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tableaux-de-bord/refs/heads/main/apis.yml
tags:
- Dashboards
- Business Intelligence
- Analytics
- Data Visualization
- Monitoring
- Grafana
- Metabase
url: https://raw.githubusercontent.com/api-evangelist/tableaux-de-bord/refs/heads/main/apis.yml
use_cases: []
---
