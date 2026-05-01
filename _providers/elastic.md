---
api_count: 3
api_specs:
- filename: elastic-elasticsearch-openapi.yml
  format: yaml
  label: Elasticsearch REST API
  slug: elasticsearch
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elastic/refs/heads/main/openapi/elastic-elasticsearch-openapi.yml
- filename: elastic-kibana-openapi.yml
  format: yaml
  label: Kibana API
  slug: kibana
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elastic/refs/heads/main/openapi/elastic-kibana-openapi.yml
- filename: elastic-cloud-openapi.yml
  format: yaml
  label: Elastic Cloud API
  slug: elastic-cloud
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elastic/refs/heads/main/openapi/elastic-cloud-openapi.yml
apis:
- description: The Elasticsearch REST API powers indexing, search, and cluster administration for the Elasticsearch search and analytics engine. It exposes operations for indexing documents, running queries, managin
  name: Elasticsearch REST API
  slug: elasticsearch
- description: The Kibana REST API manages Kibana resources including saved objects, data views, Spaces, connectors, and alerting rules. Calls are stateless and use the same authentication mechanisms as Elasticsearc
  name: Kibana API
  slug: kibana
- description: The Elastic Cloud API manages hosted Elasticsearch and Kibana deployments. It supports creating, updating, resizing, snapshotting, and deleting deployments, plus traffic filter and account-level opera
  name: Elastic Cloud API
  slug: elastic-cloud
common:
- title: ''
  type: Website
  url: https://www.elastic.co
- title: ''
  type: Documentation
  url: https://www.elastic.co/guide/index.html
- title: ''
  type: GitHub
  url: https://github.com/elastic
- title: ''
  type: Console
  url: https://cloud.elastic.co
- title: ''
  type: Pricing
  url: https://www.elastic.co/pricing
- title: ''
  type: License
  url: https://www.elastic.co/licensing/elastic-license
created: '2025-01-08'
description: Elastic is a software company that builds search-powered solutions for observability, security, and search use cases. The Elastic Stack (Elasticsearch, Kibana, and related tools) lets organizations ingest, search, analyze, and visualize structured and unstructured data in real time. Elastic Cloud delivers managed Elasticsearch and Kibana deployments with REST APIs for both data operations and deployment management.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Elastic
skills: []
slug: elastic
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: elastic\nname: Elastic\ndescription: >-\n  Elastic is a software company that builds search-powered solutions for\n  observability, security, and search use cases. The Elastic Stack\n  (Elasticsearch, Kibana, and related tools) lets organizations ingest,\n  search, analyze, and visualize structured and unstructured data in real\n  time. Elastic Cloud delivers managed Elasticsearch and Kibana deployments\n  with REST APIs for both data operations and deployment management.\ntype: Index\nposition: Producer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Search\n  - Analytics\n  - Observability\n  - Security\n  - Visualization\n  - Cloud\ncreated: '2025-01-08'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/elastic/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: elastic:elasticsearch\n    name: Elasticsearch REST API\n    description: >-\n      The\
  \ Elasticsearch REST API powers indexing, search, and cluster\n      administration for the Elasticsearch search and analytics engine. It\n      exposes operations for indexing documents, running queries, managing\n      indices and mappings, snapshots, security roles and API keys, and\n      cluster health.\n    humanURL: https://www.elastic.co/docs/api/doc/elasticsearch\n    baseURL: https://api.elastic-cloud.com\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Search\n      - Analytics\n      - Indexing\n      - Documents\n      - Cluster\n    properties:\n      - type: Documentation\n        url: https://www.elastic.co/docs/api/doc/elasticsearch\n      - type: OpenAPI\n        url: openapi/elastic-elasticsearch-openapi.yml\n  - aid: elastic:kibana\n    name: Kibana API\n    description: >-\n      The Kibana REST API manages Kibana resources including saved objects,\n      data views, Spaces, connectors, and alerting rules. Calls\
  \ are stateless\n      and use the same authentication mechanisms as Elasticsearch.\n    humanURL: https://www.elastic.co/docs/api/doc/kibana\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Visualization\n      - Dashboards\n      - SavedObjects\n      - DataViews\n    properties:\n      - type: Documentation\n        url: https://www.elastic.co/docs/api/doc/kibana\n      - type: OpenAPI\n        url: openapi/elastic-kibana-openapi.yml\n  - aid: elastic:elastic-cloud\n    name: Elastic Cloud API\n    description: >-\n      The Elastic Cloud API manages hosted Elasticsearch and Kibana\n      deployments. It supports creating, updating, resizing, snapshotting,\n      and deleting deployments, plus traffic filter and account-level\n      operations.\n    humanURL: https://www.elastic.co/docs/api/doc/cloud\n    baseURL: https://api.elastic-cloud.com\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    tags:\n      - Cloud\n      - Deployments\n      - Provisioning\n      - TrafficFilters\n    properties:\n      - type: Documentation\n        url: https://www.elastic.co/docs/api/doc/cloud\n      - type: OpenAPI\n        url: openapi/elastic-cloud-openapi.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - name: Elastic Website\n    url: https://www.elastic.co\n    type: Website\n  - name: Elastic Documentation\n    url: https://www.elastic.co/guide/index.html\n    type: Documentation\n  - name: Elastic GitHub Organization\n    url: https://github.com/elastic\n    type: GitHub\n  - name: Elastic Cloud Console\n    url: https://cloud.elastic.co\n    type: Console\n  - name: Elastic Pricing\n    url: https://www.elastic.co/pricing\n    type: Pricing\n  - name: Elastic License\n    url: https://www.elastic.co/licensing/elastic-license\n    type: License\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/elastic/refs/heads/main/apis.yml
tags:
- Search
- Analytics
- Observability
- Security
- Visualization
- Cloud
url: https://raw.githubusercontent.com/api-evangelist/elastic/refs/heads/main/apis.yml
use_cases: []
---
