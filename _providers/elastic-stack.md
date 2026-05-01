---
api_count: 2
apis:
- description: Distributed search and analytics engine with RESTful API for indexing, searching, and analyzing data at scale.
  name: Elasticsearch API
  slug: elasticsearch-api
- description: Data visualization and exploration tool API for Elasticsearch, providing dashboards, saved objects, alerting, and spaces management.
  name: Kibana API
  slug: kibana-api
common:
- title: ''
  type: Website
  url: https://www.elastic.co/
- title: ''
  type: Documentation
  url: https://www.elastic.co/guide/index.html
- title: ''
  type: Pricing
  url: https://www.elastic.co/pricing
- title: ''
  type: Blog
  url: https://www.elastic.co/blog
- title: ''
  type: Support
  url: https://www.elastic.co/support
- title: ''
  type: Status
  url: https://status.elastic.co
- title: ''
  type: TermsOfService
  url: https://www.elastic.co/agreements
- title: ''
  type: PrivacyPolicy
  url: https://www.elastic.co/legal/privacy-statement
- title: ''
  type: GitHubOrganization
  url: https://github.com/elastic
created: '2024-01-01'
description: The Elastic Stack (formerly known as the ELK Stack) is a collection of open-source products from Elastic designed to help users take data from any source, in any format, and search, analyze, and visualize that data in real-time. The stack includes Elasticsearch for search and analytics, Kibana for visualization, Logstash for data processing, and Beats for data shipping.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Elastic Stack
skills: []
slug: elastic-stack
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: elastic-stack\nname: Elastic Stack\ndescription: >-\n  The Elastic Stack (formerly known as the ELK Stack) is a collection of\n  open-source products from Elastic designed to help users take data from any\n  source, in any format, and search, analyze, and visualize that data in\n  real-time. The stack includes Elasticsearch for search and analytics, Kibana\n  for visualization, Logstash for data processing, and Beats for data shipping.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Logging\n  - Monitoring\n  - Observability\n  - Search\nurl: https://www.elastic.co/elastic-stack/\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nposition: Consumer\naccess: 3rd-Party\nspecificationVersion: '0.19'\napis:\n  - aid: elastic-stack:elasticsearch-api\n    name: Elasticsearch API\n    description: >-\n      Distributed search and analytics engine with RESTful API for indexing,\n      searching, and analyzing\
  \ data at scale.\n    humanURL: https://www.elastic.co/elasticsearch/\n    baseURL: https://localhost:9200\n    tags:\n      - Analytics\n      - Indexing\n      - Search\n    properties:\n      - type: Documentation\n        url: https://www.elastic.co/guide/en/elasticsearch/reference/current/rest-apis.html\n  - aid: elastic-stack:kibana-api\n    name: Kibana API\n    description: >-\n      Data visualization and exploration tool API for Elasticsearch, providing\n      dashboards, saved objects, alerting, and spaces management.\n    humanURL: https://www.elastic.co/kibana/\n    baseURL: https://localhost:5601/api\n    tags:\n      - Analytics\n      - Dashboards\n      - Visualization\n    properties:\n      - type: Documentation\n        url: https://www.elastic.co/guide/en/kibana/current/api.html\ncommon:\n  - type: Website\n    url: https://www.elastic.co/\n  - type: Documentation\n    url: https://www.elastic.co/guide/index.html\n  - type: Pricing\n    url: https://www.elastic.co/pricing\n\
  \  - type: Blog\n    url: https://www.elastic.co/blog\n  - type: Support\n    url: https://www.elastic.co/support\n  - type: Status\n    url: https://status.elastic.co\n  - type: TermsOfService\n    url: https://www.elastic.co/agreements\n  - type: PrivacyPolicy\n    url: https://www.elastic.co/legal/privacy-statement\n  - type: GitHubOrganization\n    url: https://github.com/elastic\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/elastic-stack/refs/heads/main/apis.yml
tags:
- Analytics
- Logging
- Monitoring
- Observability
- Search
url: https://www.elastic.co/elastic-stack/
use_cases: []
---
