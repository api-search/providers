---
api_count: 1
api_specs:
- filename: flink-rest-api-openapi-original.yml
  format: yaml
  label: Apache Flink REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/flink/refs/heads/main/openapi/flink-rest-api-openapi-original.yml
apis:
- description: The Flink REST API is exposed by the JobManager Dispatcher and provides monitoring and management capabilities for a Flink cluster. It covers cluster configuration, JobManager environment and metrics,
  name: Apache Flink REST API
  slug: rest-api
common:
- title: ''
  type: Website
  url: https://flink.apache.org/
- title: ''
  type: Documentation
  url: https://nightlies.apache.org/flink/flink-docs-stable/
- title: ''
  type: RESTAPIDocumentation
  url: https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/rest_api/
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/flink
- title: ''
  type: Blog
  url: https://flink.apache.org/posts/
- title: ''
  type: Community
  url: https://flink.apache.org/community/
created: '2025-01-01'
description: Apache Flink is an open-source framework and distributed processing engine for stateful computations over unbounded and bounded data streams. It is designed to run in all common cluster environments and to perform computations at in-memory speed and at any scale. Flink exposes a REST API on the JobManager Dispatcher that allows external systems to query cluster status, submit and manage jobs, trigger savepoints and checkpoints, upload and run JARs, and inspect metrics, accumulators, and exception histories. The same REST endpoints power the Flink Web UI.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Apache Flink
skills: []
slug: flink
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: flink\nname: Apache Flink\ndescription: >-\n  Apache Flink is an open-source framework and distributed processing engine\n  for stateful computations over unbounded and bounded data streams. It is\n  designed to run in all common cluster environments and to perform\n  computations at in-memory speed and at any scale. Flink exposes a REST API\n  on the JobManager Dispatcher that allows external systems to query cluster\n  status, submit and manage jobs, trigger savepoints and checkpoints, upload\n  and run JARs, and inspect metrics, accumulators, and exception histories.\n  The same REST endpoints power the Flink Web UI.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/flink/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Big Data\n  - Distributed Computing\n  - Real-Time Analytics\n  - Stream Processing\n\
  \  - Workflows\napis:\n  - aid: flink:rest-api\n    name: Apache Flink REST API\n    description: >-\n      The Flink REST API is exposed by the JobManager Dispatcher and provides\n      monitoring and management capabilities for a Flink cluster. It covers\n      cluster configuration, JobManager environment and metrics, job lifecycle\n      (submit, list, cancel, stop), checkpoint and savepoint management, JAR\n      upload and execution, dataset operations, and TaskManager inspection.\n      The same REST API powers the Flink Web UI and is the primary\n      programmatic interface for operating a Flink cluster.\n    humanURL: https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/rest_api/\n    baseURL: http://localhost:8081\n    tags:\n      - Stream Processing\n      - Job Management\n      - Cluster Management\n      - Checkpoints\n      - Monitoring\n    properties:\n      - url: https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/rest_api/\n        type: Documentation\n\
  \      - url: https://flink.apache.org/\n        type: Website\n      - url: https://github.com/apache/flink\n        type: GitHubRepository\n      - url: openapi/flink-rest-api-openapi-original.yml\n        type: OpenAPI\ncommon:\n  - type: Website\n    url: https://flink.apache.org/\n  - type: Documentation\n    url: https://nightlies.apache.org/flink/flink-docs-stable/\n  - type: RESTAPIDocumentation\n    url: https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/rest_api/\n  - type: GitHubRepository\n    url: https://github.com/apache/flink\n  - type: Blog\n    url: https://flink.apache.org/posts/\n  - type: Community\n    url: https://flink.apache.org/community/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/flink/refs/heads/main/apis.yml
tags:
- Big Data
- Distributed Computing
- Real-Time Analytics
- Stream Processing
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/flink/refs/heads/main/apis.yml
use_cases: []
---
