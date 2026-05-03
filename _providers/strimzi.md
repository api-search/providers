---
api_count: 2
api_specs:
- filename: strimzi-kafka-bridge-openapi.yml
  format: yaml
  label: Strimzi Kafka Bridge REST API
  slug: strimzi-kafka-bridge-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/openapi/strimzi-kafka-bridge-openapi.yml
apis:
- description: The Strimzi Operator API is expressed through Kubernetes Custom Resource Definitions (CRDs). Operators are controlled by creating and modifying Kafka, KafkaTopic, KafkaUser, KafkaConnect, KafkaMirrorM
  name: Strimzi Operator API
  slug: strimzi-operator-api
- description: The Strimzi Kafka Bridge provides an HTTP/REST interface to Apache Kafka, allowing HTTP clients to produce and consume messages, manage consumer groups, and query topic metadata without a native Kafka
  name: Strimzi Kafka Bridge REST API
  slug: strimzi-kafka-bridge-api
capabilities:
- description: Unified capability for Kafka messaging via the Strimzi Kafka Bridge REST API. Designed for application developers and platform engineers who need to produce and consume Kafka messages without a native
  name: Strimzi Kafka Messaging
  slug: kafka-messaging
common:
- title: ''
  type: Website
  url: https://strimzi.io
- title: ''
  type: Documentation
  url: https://strimzi.io/docs/operators/latest/
- title: ''
  type: GitHub
  url: https://github.com/strimzi/strimzi-kafka-operator
- title: ''
  type: Blog
  url: https://strimzi.io/blog/
- title: ''
  type: Helm Chart
  url: https://artifacthub.io/packages/helm/strimzi/strimzi-kafka-operator
- title: ''
  type: Slack
  url: https://slack.cncf.io
- title: ''
  type: Changelog
  url: https://github.com/strimzi/strimzi-kafka-operator/releases
- title: ''
  type: CNCF
  url: https://www.cncf.io/projects/strimzi/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/openapi/strimzi-kafka-bridge-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/json-schema/strimzi-kafka-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/json-ld/strimzi-context.jsonld
created: '2025-01-01'
description: Strimzi is a CNCF project providing a Kubernetes-native operator for running Apache Kafka on Kubernetes and OpenShift. It simplifies the deployment, management, scaling, and configuration of Kafka clusters using Kubernetes Custom Resource Definitions (CRDs). Strimzi manages the full Kafka ecosystem including brokers, ZooKeeper/KRaft, Kafka Connect, Kafka MirrorMaker 2, Kafka Bridge, and Schema Registry. The operator pattern lets teams declare desired Kafka topology via YAML manifests managed by Kubernetes.
features: []
image: https://strimzi.io/images/logo/strimzi-logo.png
integrations: []
jsonld:
- class_count: 0
  name: Strimzi Context
  property_count: 4
  slug: strimzi-context
layout: provider
modified: '2026-05-02'
name: Strimzi
rules:
- name: Strimzi API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 3
    warn: 4
  slug: strimzi-rules
skills: []
slug: strimzi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: strimzi\nname: Strimzi\ndescription: >-\n  Strimzi is a CNCF project providing a Kubernetes-native operator for running\n  Apache Kafka on Kubernetes and OpenShift. It simplifies the deployment,\n  management, scaling, and configuration of Kafka clusters using Kubernetes\n  Custom Resource Definitions (CRDs). Strimzi manages the full Kafka ecosystem\n  including brokers, ZooKeeper/KRaft, Kafka Connect, Kafka MirrorMaker 2,\n  Kafka Bridge, and Schema Registry. The operator pattern lets teams declare\n  desired Kafka topology via YAML manifests managed by Kubernetes.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/apis.yml\nimage: https://strimzi.io/images/logo/strimzi-logo.png\ntags:\n  - Kafka\n  - Kubernetes\n  - Messaging\n  - Operator\n  - Streaming\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: strimzi:strimzi-operator-api\n    name:\
  \ Strimzi Operator API\n    description: >-\n      The Strimzi Operator API is expressed through Kubernetes Custom Resource\n      Definitions (CRDs). Operators are controlled by creating and modifying\n      Kafka, KafkaTopic, KafkaUser, KafkaConnect, KafkaMirrorMaker2,\n      KafkaBridge, and related custom resources via the Kubernetes API.\n      The Strimzi operator watches these resources and reconciles the actual\n      cluster state to match the desired specification.\n    humanURL: https://strimzi.io/docs/operators/latest/configuring.html\n    tags:\n      - Kafka\n      - Kubernetes\n      - Messaging\n      - Operator\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://strimzi.io/docs/operators/latest/\n      - type: GitHub\n        url: https://github.com/strimzi/strimzi-kafka-operator\n      - type: KubernetesCRD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/crd/kafka-crd.yml\n      -\
  \ type: KubernetesCRD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/crd/kafkatopic-crd.yml\n      - type: KubernetesCRD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/crd/kafkauser-crd.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/json-schema/strimzi-kafka-schema.json\n  - aid: strimzi:strimzi-kafka-bridge-api\n    name: Strimzi Kafka Bridge REST API\n    description: >-\n      The Strimzi Kafka Bridge provides an HTTP/REST interface to Apache Kafka,\n      allowing HTTP clients to produce and consume messages, manage consumer\n      groups, and query topic metadata without a native Kafka client. The Bridge\n      implements part of the OpenAPI specification for HTTP-to-Kafka bridging.\n    humanURL: https://strimzi.io/docs/bridge/latest/\n    baseURL: http://localhost:8080\n    tags:\n      - Kafka\n\
  \      - Messaging\n      - REST API\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://strimzi.io/docs/bridge/latest/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/openapi/strimzi-kafka-bridge-openapi.yml\n      - type: GitHub\n        url: https://github.com/strimzi/strimzi-kafka-bridge\ncommon:\n  - type: Website\n    url: https://strimzi.io\n  - type: Documentation\n    url: https://strimzi.io/docs/operators/latest/\n  - type: GitHub\n    url: https://github.com/strimzi/strimzi-kafka-operator\n  - type: Blog\n    url: https://strimzi.io/blog/\n  - type: Helm Chart\n    url: https://artifacthub.io/packages/helm/strimzi/strimzi-kafka-operator\n  - type: Slack\n    url: https://slack.cncf.io\n  - type: Changelog\n    url: https://github.com/strimzi/strimzi-kafka-operator/releases\n  - type: CNCF\n    url: https://www.cncf.io/projects/strimzi/\n  - type: OpenAPI\n    url: >-\n\
  \      https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/openapi/strimzi-kafka-bridge-openapi.yml\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/json-schema/strimzi-kafka-schema.json\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/json-ld/strimzi-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/apis.yml
tags:
- Kafka
- Kubernetes
- Messaging
- Operator
- Streaming
url: https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/apis.yml
use_cases: []
---
