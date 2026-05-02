---
api_count: 1
api_specs:
- filename: kibana-openapi-original.yml
  format: yaml
  label: Kibana API
  slug: kibana-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kibana/refs/heads/main/openapi/kibana-openapi-original.yml
apis:
- description: The Kibana REST API enables programmatic management of Kibana resources including spaces, saved objects, dashboards, data views, connectors, rules, and configuration. The API is stateless and uses sta
  name: Kibana API
  slug: kibana-api
common:
- title: ''
  type: Website
  url: https://www.elastic.co/kibana
- title: ''
  type: Documentation
  url: https://www.elastic.co/guide/en/kibana/current/index.html
- title: ''
  type: APIDocumentation
  url: https://www.elastic.co/guide/en/kibana/current/api.html
- title: ''
  type: Downloads
  url: https://www.elastic.co/downloads/kibana
- title: ''
  type: GitHub
  url: https://github.com/elastic/kibana
- title: ''
  type: Blog
  url: https://www.elastic.co/blog/category/kibana
- title: ''
  type: Pricing
  url: https://www.elastic.co/pricing
- title: ''
  type: Support
  url: https://www.elastic.co/support
- title: ''
  type: Forum
  url: https://discuss.elastic.co/c/kibana
- title: ''
  type: TermsOfService
  url: https://www.elastic.co/legal/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.elastic.co/legal/privacy-statement
created: '2024-01-15'
description: Kibana is an open-source data visualization and exploration tool used for log and time-series analytics, application monitoring, and operational intelligence. Kibana provides histograms, line graphs, pie charts, heat maps, geospatial visualizations, dashboards, alerting, and management of saved objects across spaces, exposing a comprehensive REST API for programmatic configuration and automation.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Kibana
skills: []
slug: kibana
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kibana\nname: Kibana\ndescription: >-\n  Kibana is an open-source data visualization and exploration tool used for\n  log and time-series analytics, application monitoring, and operational\n  intelligence. Kibana provides histograms, line graphs, pie charts, heat\n  maps, geospatial visualizations, dashboards, alerting, and management of\n  saved objects across spaces, exposing a comprehensive REST API for\n  programmatic configuration and automation.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Alerting\n  - Analytics\n  - Dashboards\n  - Elastic Stack\n  - Logging\n  - Monitoring\n  - Observability\n  - Visualization\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/kibana/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: kibana:kibana-api\n    name: Kibana API\n    description: >-\n      The Kibana REST API enables programmatic\
  \ management of Kibana resources\n      including spaces, saved objects, dashboards, data views, connectors,\n      rules, and configuration. The API is stateless and uses standard HTTP\n      verbs (GET, POST, PUT, DELETE) returning JSON responses, making it well\n      suited for automation, CI/CD pipelines, and integrating Kibana with\n      external systems.\n    humanURL: https://www.elastic.co/guide/en/kibana/current/api.html\n    baseURL: https://localhost:5601/api\n    tags:\n      - Configuration\n      - Dashboards\n      - Management\n      - Saved Objects\n      - Spaces\n    properties:\n      - type: Documentation\n        url: https://www.elastic.co/guide/en/kibana/current/api.html\n      - type: OpenAPI\n        url: openapi/kibana-openapi-original.yml\n      - type: Authentication\n        url: https://www.elastic.co/guide/en/kibana/current/api-authentication.html\ncommon:\n  - type: Website\n    url: https://www.elastic.co/kibana\n  - type: Documentation\n    url: https://www.elastic.co/guide/en/kibana/current/index.html\n\
  \  - type: APIDocumentation\n    url: https://www.elastic.co/guide/en/kibana/current/api.html\n  - type: Downloads\n    url: https://www.elastic.co/downloads/kibana\n  - type: GitHub\n    url: https://github.com/elastic/kibana\n  - type: Blog\n    url: https://www.elastic.co/blog/category/kibana\n  - type: Pricing\n    url: https://www.elastic.co/pricing\n  - type: Support\n    url: https://www.elastic.co/support\n  - type: Forum\n    url: https://discuss.elastic.co/c/kibana\n  - type: TermsOfService\n    url: https://www.elastic.co/legal/terms-of-service\n  - type: PrivacyPolicy\n    url: https://www.elastic.co/legal/privacy-statement\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kibana/refs/heads/main/apis.yml
tags:
- Alerting
- Analytics
- Dashboards
- Elastic Stack
- Logging
- Monitoring
- Observability
- Visualization
url: https://raw.githubusercontent.com/api-evangelist/kibana/refs/heads/main/apis.yml
use_cases: []
---
