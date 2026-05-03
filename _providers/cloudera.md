---
api_count: 6
apis:
- description: The Cloudera CDP Public Cloud Control Plane REST API manages CDP environments, datalakes, data hubs, machine learning workspaces, data warehouses and data engineering services. Access requires a Cloud
  name: Cloudera CDP Public Cloud Control Plane API
  slug: cdp-control-plane
- description: Cloudera Manager exposes a JSON REST API at /api/v{N} for managing clusters, services, roles, configurations, hosts, parcels, tags and audits. Authentication uses HTTP basic auth with the same credent
  name: Cloudera Manager API
  slug: manager
- description: Cruise Control on CDP exposes REST endpoints for rebalancing Kafka clusters, monitoring partition load, and triggering anomaly checks.
  name: Cloudera Cruise Control REST API
  slug: cruise-control
- description: Streams Replication Manager (SRM) exposes a REST API for inspecting cross-cluster Kafka replication topology, lag, and metrics.
  name: Streams Replication Manager Service REST API
  slug: srm
- description: The HBase REST Server provides a REST front-end to HBase tables for get/put/scan/delete, namespace and table management - installable via Cloudera Manager.
  name: HBase REST Server
  slug: hbase-rest
- description: YARN Queue Manager exposes a REST API for managing capacity scheduler queues, ACLs, and resource allocations on a CDP cluster.
  name: YARN Queue Manager API
  slug: yarn-queue-manager
common:
- title: ''
  type: Website
  url: https://www.cloudera.com/
- title: ''
  type: Documentation
  url: https://docs.cloudera.com/
- title: ''
  type: Support
  url: https://my.cloudera.com/knowledge.html
- title: ''
  type: Privacy Policy
  url: https://www.cloudera.com/legal/privacy.html
- title: ''
  type: GitHub
  url: https://github.com/cloudera
- title: ''
  type: JSON-LD
  url: json-ld/cloudera-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloudera-rules.yml
created: '2024-01-01'
description: Cloudera is a hybrid data platform company offering the Cloudera Data Platform (CDP) for data engineering, data warehousing, machine learning, streaming, and operational data. The platform exposes multiple REST APIs including the CDP Public Cloud Control Plane API for managing environments, datalakes, data hubs and workloads, the Cloudera Manager API for cluster lifecycle and configuration management, and per-service REST APIs across the runtime (Cruise Control, Streams Replication Manager, HBase REST, YARN Queue Manager, etc.). APIs are JSON, support standard CRUD, and are typically authenticated via API access keys, basic auth, or session cookies.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cloudera Context
  property_count: 7
  slug: cloudera-context
layout: provider
modified: '2026-04-25'
name: Cloudera
rules:
- name: Cloudera API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 5
  slug: cloudera-rules
skills: []
slug: cloudera
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloudera\nname: Cloudera\ndescription: >-\n  Cloudera is a hybrid data platform company offering the Cloudera Data Platform\n  (CDP) for data engineering, data warehousing, machine learning, streaming,\n  and operational data. The platform exposes multiple REST APIs including the\n  CDP Public Cloud Control Plane API for managing environments, datalakes,\n  data hubs and workloads, the Cloudera Manager API for cluster lifecycle and\n  configuration management, and per-service REST APIs across the runtime\n  (Cruise Control, Streams Replication Manager, HBase REST, YARN Queue\n  Manager, etc.). APIs are JSON, support standard CRUD, and are typically\n  authenticated via API access keys, basic auth, or session cookies.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/cloudera/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-25'\nspecificationVersion: '0.19'\n\
  x-type: company\ntags:\n  - Big Data\n  - Data Engineering\n  - Data Lakehouse\n  - Data Platform\n  - Data Warehouse\n  - Hadoop\n  - Hybrid Cloud\n  - Machine Learning\n  - Streaming\napis:\n  - aid: cloudera:cdp-control-plane\n    name: Cloudera CDP Public Cloud Control Plane API\n    tags:\n      - Cloud\n      - Control Plane\n      - CDP\n      - Environments\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.cloudera.com/cdp-public-cloud/cloud/api/topics/mc-api-overview.html\n    properties:\n      - url: https://docs.cloudera.com/cdp-public-cloud/cloud/api/topics/mc-api-overview.html\n        type: Documentation\n      - url: https://github.com/cloudera/cdpcurl\n        type: CLI\n    description: >-\n      The Cloudera CDP Public Cloud Control Plane REST API manages CDP\n      environments, datalakes, data hubs, machine learning workspaces, data\n      warehouses and data engineering services. Access requires a Cloudera\n\
  \      user account with an API access key and private key. cdpcurl is the\n      Python CLI for signed calls.\n  - aid: cloudera:manager\n    name: Cloudera Manager API\n    tags:\n      - Cluster\n      - Configuration\n      - Management\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloudera.github.io/cm_api/\n    properties:\n      - url: https://cloudera.github.io/cm_api/\n        type: Documentation\n      - url: https://cloudera.github.io/cm_api/apidocs/v19/\n        type: Reference\n      - url: https://docs.cloudera.com/cdp-private-cloud-base/7.1.9/concepts/topics/cm-api-overview.html\n        type: Overview\n    description: >-\n      Cloudera Manager exposes a JSON REST API at /api/v{N} for managing\n      clusters, services, roles, configurations, hosts, parcels, tags and\n      audits. Authentication uses HTTP basic auth with the same credentials\n      as the Cloudera Manager web UI; subsequent requests can use\
  \ the\n      session cookie returned on authentication.\n  - aid: cloudera:cruise-control\n    name: Cloudera Cruise Control REST API\n    tags:\n      - Kafka\n      - Rebalancing\n      - Streaming\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.cloudera.com/runtime/7.2.18/cctrl-managing/topics/cctrl-using-rest-api.html\n    properties:\n      - url: https://docs.cloudera.com/runtime/7.2.18/cctrl-managing/topics/cctrl-using-rest-api.html\n        type: Documentation\n    description: >-\n      Cruise Control on CDP exposes REST endpoints for rebalancing Kafka\n      clusters, monitoring partition load, and triggering anomaly checks.\n  - aid: cloudera:srm\n    name: Streams Replication Manager Service REST API\n    tags:\n      - Kafka\n      - Replication\n      - Streaming\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.cloudera.com/cdp-private-cloud-base/7.1.9/srm-overview/topics/srm-rest-api-overview.html\n\
  \    properties:\n      - url: https://docs.cloudera.com/cdp-private-cloud-base/7.1.9/srm-overview/topics/srm-rest-api-overview.html\n        type: Documentation\n    description: >-\n      Streams Replication Manager (SRM) exposes a REST API for inspecting\n      cross-cluster Kafka replication topology, lag, and metrics.\n  - aid: cloudera:hbase-rest\n    name: HBase REST Server\n    tags:\n      - HBase\n      - NoSQL\n      - REST\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.cloudera.com/cdp-private-cloud-base/latest/accessing-hbase/topics/hbase-installing-rest-server-using-cm.html\n    properties:\n      - url: https://docs.cloudera.com/cdp-private-cloud-base/latest/accessing-hbase/topics/hbase-installing-rest-server-using-cm.html\n        type: Documentation\n    description: >-\n      The HBase REST Server provides a REST front-end to HBase tables for\n      get/put/scan/delete, namespace and table management -\
  \ installable via\n      Cloudera Manager.\n  - aid: cloudera:yarn-queue-manager\n    name: YARN Queue Manager API\n    tags:\n      - YARN\n      - Resource Management\n      - Scheduling\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.cloudera.com/cdp-private-cloud-base/7.1.9/yarn-reference/topics/yarn-qm-using-api.html\n    properties:\n      - url: https://docs.cloudera.com/cdp-private-cloud-base/7.1.9/yarn-reference/topics/yarn-qm-using-api.html\n        type: Documentation\n    description: >-\n      YARN Queue Manager exposes a REST API for managing capacity scheduler\n      queues, ACLs, and resource allocations on a CDP cluster.\ncommon:\n  - type: Website\n    url: https://www.cloudera.com/\n  - type: Documentation\n    url: https://docs.cloudera.com/\n  - type: Support\n    url: https://my.cloudera.com/knowledge.html\n  - type: Privacy Policy\n    url: https://www.cloudera.com/legal/privacy.html\n  - type: GitHub\n\
  \    url: https://github.com/cloudera\n  - type: JSON-LD\n    url: json-ld/cloudera-context.jsonld\n  - type: Spectral\n    url: rules/cloudera-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudera/refs/heads/main/apis.yml
tags:
- Big Data
- Data Engineering
- Data Lakehouse
- Data Platform
- Data Warehouse
- Hadoop
- Hybrid Cloud
- Machine Learning
- Streaming
url: https://raw.githubusercontent.com/api-evangelist/cloudera/refs/heads/main/apis.yml
use_cases: []
---
