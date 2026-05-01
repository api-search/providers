---
api_count: 1
api_specs:
- filename: debezium-connect.yml
  format: yaml
  label: Debezium Kafka Connect REST API
  slug: debezium-kafka-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/debezium/refs/heads/main/openapi/debezium-connect.yml
apis:
- description: Debezium runs as Kafka Connect source connectors. This API manages Debezium CDC connectors, their configurations, tasks, and offsets via the standard Kafka Connect REST interface.
  name: Debezium Kafka Connect REST API
  slug: debezium-kafka-connect-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://debezium.io/
- title: ''
  type: Documentation
  url: https://debezium.io/documentation/
- title: ''
  type: Getting Started
  url: https://debezium.io/documentation/reference/stable/tutorial.html
- title: ''
  type: GitHub
  url: https://github.com/debezium/debezium
- title: ''
  type: Blog
  url: https://debezium.io/blog/
- title: ''
  type: Community
  url: https://debezium.io/community/
- title: ''
  type: License
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: JSON-LD
  url: json-ld/debezium-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/debezium-vocabulary.yml
created: '2026-03-26'
description: Debezium is an open source distributed platform for change data capture (CDC) that converts changes in existing databases into event streams, enabling applications to detect and respond to row-level changes in databases in real time.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Debezium Context
  property_count: 9
  slug: debezium-context
layout: provider
modified: '2026-04-28'
name: Debezium
rules:
- name: Debezium API Rules
  rule_count: 5
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 4
  slug: debezium-kafka-connect-api-rules
skills: []
slug: debezium
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: debezium\nname: Debezium\ndescription: >-\n  Debezium is an open source distributed platform for change data capture\n  (CDC) that converts changes in existing databases into event streams,\n  enabling applications to detect and respond to row-level changes in\n  databases in real time.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache Kafka\n  - CDC\n  - Change Data Capture\n  - Databases\n  - Event Streaming\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/debezium/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: opensource\napis:\n  - aid: debezium:debezium-kafka-connect-api\n    name: Debezium Kafka Connect REST API\n    description: >-\n      Debezium runs as Kafka Connect source connectors. This API manages\n      Debezium CDC connectors, their configurations, tasks, and offsets\n      via the standard Kafka Connect\
  \ REST interface.\n    humanURL: https://debezium.io/documentation/reference/stable/connectors/index.html\n    baseURL: http://localhost:8083\n    tags:\n      - CDC\n      - Connectors\n      - Kafka Connect\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://debezium.io/documentation/reference/stable/connectors/index.html\n      - type: OpenAPI\n        url: openapi/debezium-connect.yml\n      - type: JSONSchema\n        url: json-schema/debezium-change-event.json\n      - type: Rules\n        url: rules/debezium-kafka-connect-api-rules.yml\n      - type: Capabilities\n        url: capabilities/debezium-kafka-connect-api-capabilities.yml\ncommon:\n  - type: Website\n    url: https://debezium.io/\n  - type: Documentation\n    url: https://debezium.io/documentation/\n  - type: Getting Started\n    url: https://debezium.io/documentation/reference/stable/tutorial.html\n  - type: GitHub\n    url: https://github.com/debezium/debezium\n  - type: Blog\n    url:\
  \ https://debezium.io/blog/\n  - type: Community\n    url: https://debezium.io/community/\n  - type: License\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: JSON-LD\n    url: json-ld/debezium-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/debezium-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/debezium/refs/heads/main/apis.yml
tags:
- Apache Kafka
- CDC
- Change Data Capture
- Databases
- Event Streaming
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/debezium/refs/heads/main/apis.yml
use_cases: []
---
