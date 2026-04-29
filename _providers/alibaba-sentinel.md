---
api_count: 1
apis:
- description: The Sentinel Dashboard API provides a REST interface for the Sentinel dashboard application, which allows real-time monitoring of clients and dynamic configuration of flow control, circuit breaking, a
  name: Sentinel Dashboard API
  slug: sentinel-dashboard-api
common:
- title: ''
  type: Website
  url: https://sentinelguard.io/
- title: ''
  type: Documentation
  url: https://sentinelguard.io/en-us/docs/introduction.html
- title: ''
  type: GettingStarted
  url: https://github.com/alibaba/Sentinel/wiki/How-to-Use
- title: ''
  type: GitHub
  url: https://github.com/alibaba/Sentinel
- title: ''
  type: GitHub
  url: https://github.com/alibaba/sentinel-golang
- title: ''
  type: GitHub
  url: https://github.com/alibaba
- title: ''
  type: Wiki
  url: https://github.com/alibaba/Sentinel/wiki
- title: ''
  type: Issues
  url: https://github.com/alibaba/Sentinel/issues
- title: ''
  type: Releases
  url: https://github.com/alibaba/Sentinel/releases
created: '2026-03-26'
description: Alibaba Sentinel is a powerful open source flow control component enabling reliability, resilience, and monitoring for microservices. Originally developed by Alibaba and used in production at Alibaba for over 10 years, Sentinel provides flow control, traffic shaping, concurrency limiting, circuit breaking, and system adaptive overload protection. The project is written primarily in Java with a Go implementation (sentinel-golang) also available. Sentinel integrates with major frameworks including Spring Cloud, Dubbo, gRPC, Apache RocketMQ, and Servlet. It provides a real-time monitoring dashboard for visualizing metrics and configuring rules dynamically. The project is hosted on GitHub under the Alibaba organization and is widely adopted in cloud-native microservice architectures.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-19'
name: Alibaba Sentinel
skills: []
slug: alibaba-sentinel
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: alibaba-sentinel\nname: Alibaba Sentinel\ndescription: >-\n  Alibaba Sentinel is a powerful open source flow control component enabling\n  reliability, resilience, and monitoring for microservices. Originally\n  developed by Alibaba and used in production at Alibaba for over 10 years,\n  Sentinel provides flow control, traffic shaping, concurrency limiting, circuit\n  breaking, and system adaptive overload protection. The project is written\n  primarily in Java with a Go implementation (sentinel-golang) also available.\n  Sentinel integrates with major frameworks including Spring Cloud, Dubbo,\n  gRPC, Apache RocketMQ, and Servlet. It provides a real-time monitoring\n  dashboard for visualizing metrics and configuring rules dynamically. The\n  project is hosted on GitHub under the Alibaba organization and is widely\n  adopted in cloud-native microservice architectures.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n\
  \  - Alibaba\n  - Circuit Breaker\n  - Flow Control\n  - Java\n  - Microservices\n  - Rate Limiting\n  - Resilience\n  - Traffic Shaping\n  - Open Source\n  - Cloud Native\n  - Spring Cloud\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/alibaba-sentinel/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: alibaba-sentinel:sentinel-dashboard-api\n    name: Sentinel Dashboard API\n    description: >-\n      The Sentinel Dashboard API provides a REST interface for the Sentinel\n      dashboard application, which allows real-time monitoring of clients and\n      dynamic configuration of flow control, circuit breaking, and system\n      protection rules. The dashboard supports cluster aggregation of runtime\n      info for up to 500 nodes and enables operators to manage resources and\n      rules without application restarts.\n    humanURL: https://sentinelguard.io/en-us/docs/dashboard.html\n    baseURL: https://localhost:8080\n\
  \    tags:\n      - Dashboard\n      - Monitoring\n      - Flow Control\n      - Circuit Breaker\n      - Rate Limiting\n    properties:\n      - type: Documentation\n        url: https://sentinelguard.io/en-us/docs/dashboard.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/alibaba-sentinel/refs/heads/main/openapi/sentinel-dashboard-api.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/alibaba-sentinel/refs/heads/main/json-schema/flow-rule.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/alibaba-sentinel/refs/heads/main/json-schema/degrade-rule.json\ncommon:\n  - type: Website\n    url: https://sentinelguard.io/\n  - type: Documentation\n    url: https://sentinelguard.io/en-us/docs/introduction.html\n  - type: GettingStarted\n    url: https://github.com/alibaba/Sentinel/wiki/How-to-Use\n  - type: GitHub\n    url: https://github.com/alibaba/Sentinel\n\
  \  - type: GitHub\n    url: https://github.com/alibaba/sentinel-golang\n  - type: GitHub\n    url: https://github.com/alibaba\n  - type: Wiki\n    url: https://github.com/alibaba/Sentinel/wiki\n  - type: Issues\n    url: https://github.com/alibaba/Sentinel/issues\n  - type: Releases\n    url: https://github.com/alibaba/Sentinel/releases\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/alibaba-sentinel/refs/heads/main/apis.yml
tags:
- Alibaba
- Circuit Breaker
- Flow Control
- Java
- Microservices
- Rate Limiting
- Resilience
- Traffic Shaping
- Open Source
- Cloud Native
- Spring Cloud
url: https://raw.githubusercontent.com/api-evangelist/alibaba-sentinel/refs/heads/main/apis.yml
use_cases: []
---
