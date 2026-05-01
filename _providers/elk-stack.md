---
api_count: 2
api_specs:
- filename: elasticsearch-serverless-openapi.json
  format: json
  label: Elasticsearch API
  slug: elasticsearch-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/elastic/elasticsearch-specification/main/output/openapi/elasticsearch-serverless-openapi.json
apis:
- description: Distributed, RESTful search and analytics engine serving as the heart of the Elastic Stack for centralized storage and search.
  name: Elasticsearch API
  slug: elasticsearch-api
- description: Data visualization and exploration tool for reviewing logs and events, providing real-time dashboards and analytics for Elasticsearch data.
  name: Kibana API
  slug: kibana-api
common:
- title: ''
  type: Website
  url: https://www.elastic.co/elastic-stack/
- title: ''
  type: Documentation
  url: https://www.elastic.co/guide/index.html
- title: ''
  type: GettingStarted
  url: https://www.elastic.co/guide/index.html
- title: ''
  type: Blog
  url: https://www.elastic.co/blog/
- title: ''
  type: Support
  url: https://www.elastic.co/support
- title: ''
  type: Pricing
  url: https://www.elastic.co/pricing/
- title: ''
  type: GitHubOrganization
  url: https://github.com/elastic
created: '2024-01-01'
description: The Elastic Stack (formerly known as the ELK Stack) is a collection of open-source products from Elastic - Elasticsearch, Logstash, Kibana, and Beats - designed for taking data from any source, in any format, and searching, analyzing, and visualizing it in real time. Widely used for log management, observability, and security analytics.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-16'
name: Elastic Stack (ELK Stack)
skills: []
slug: elk-stack
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: elk-stack\nname: Elastic Stack (ELK Stack)\ndescription: >-\n  The Elastic Stack (formerly known as the ELK Stack) is a collection of\n  open-source products from Elastic - Elasticsearch, Logstash, Kibana, and\n  Beats - designed for taking data from any source, in any format, and\n  searching, analyzing, and visualizing it in real time. Widely used for log\n  management, observability, and security analytics.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Logging\n  - Monitoring\n  - Observability\n  - Search\nurl: https://www.elastic.co/elastic-stack/\ncreated: '2024-01-01'\nmodified: '2026-03-16'\nposition: Consumer\naccess: 3rd-Party\nspecificationVersion: '0.19'\napis:\n  - aid: elk-stack:elasticsearch-api\n    name: Elasticsearch API\n    description: >-\n      Distributed, RESTful search and analytics engine serving as the heart\n      of the Elastic Stack for centralized storage and search.\n\
  \    humanURL: https://www.elastic.co/elasticsearch/\n    baseURL: https://localhost:9200\n    tags:\n      - Analytics\n      - Database\n      - Search\n    properties:\n      - type: Documentation\n        url: https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/elastic/elasticsearch-specification/main/output/openapi/elasticsearch-serverless-openapi.json\n  - aid: elk-stack:kibana-api\n    name: Kibana API\n    description: >-\n      Data visualization and exploration tool for reviewing logs and events,\n      providing real-time dashboards and analytics for Elasticsearch data.\n    humanURL: https://www.elastic.co/kibana/\n    baseURL: https://localhost:5601\n    tags:\n      - Analytics\n      - Dashboard\n      - Visualization\n    properties:\n      - type: Documentation\n        url: https://www.elastic.co/guide/en/kibana/current/index.html\ncommon:\n  - type: Website\n    url: https://www.elastic.co/elastic-stack/\n\
  \  - type: Documentation\n    url: https://www.elastic.co/guide/index.html\n  - type: GettingStarted\n    url: https://www.elastic.co/guide/index.html\n  - type: Blog\n    url: https://www.elastic.co/blog/\n  - type: Support\n    url: https://www.elastic.co/support\n  - type: Pricing\n    url: https://www.elastic.co/pricing/\n  - type: GitHubOrganization\n    url: https://github.com/elastic\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/elk-stack/refs/heads/main/apis.yml
tags:
- Analytics
- Logging
- Monitoring
- Observability
- Search
url: https://www.elastic.co/elastic-stack/
use_cases: []
---
