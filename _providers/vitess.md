---
api_count: 4
api_specs:
- filename: vitess-vtadmin-openapi.yml
  format: yaml
  label: Vitess VTAdmin API
  slug: vtadmin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vitess/refs/heads/main/openapi/vitess-vtadmin-openapi.yml
apis:
- description: VTGate is the stateless proxy that routes queries to the appropriate VTTablet instances. It exposes a MySQL-compatible interface and a gRPC API that clients use to interact with the Vitess cluster, ha
  name: Vitess VTGate API
  slug: vtgate-api
- description: VTAdmin is the administrative web application and REST API for managing Vitess clusters. It provides endpoints for inspecting cluster topology, tablets, keyspaces, shards, schemas, and VReplication wo
  name: Vitess VTAdmin API
  slug: vtadmin-api
- description: VTCtld is the Vitess topology management daemon that exposes a gRPC and HTTP API for administrative operations on the cluster topology including creating and managing keyspaces, shards, tablets, and e
  name: Vitess VTCtld API
  slug: vtctld-api
- description: VReplication is the Vitess framework for replicating and transforming data streams within and across Vitess clusters. It powers features such as MoveTables, Reshard, Materialize, and CreateLookupVinde
  name: Vitess VReplication API
  slug: vreplication-api
capabilities:
- description: Workflow capability for administering Vitess database clusters via the VTAdmin API. Combines cluster topology inspection, tablet management, keyspace and schema administration, VReplication workflow m
  name: Vitess Cluster Administration
  slug: cluster-administration
common:
- title: ''
  type: JSONSchema
  url: json-schema/vitess-topology-schema.json
- title: ''
  type: JSONLD
  url: json-ld/vitess-context.jsonld
- title: ''
  type: JSONStructure
  url: json-structure/vitess-tablet-structure.json
- title: ''
  type: OpenAPI
  url: openapi/vitess-vtadmin-openapi.yml
- title: ''
  type: SpectralRules
  url: rules/vitess-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/vitess-vocabulary.yml
- title: ''
  type: Website
  url: https://vitess.io
- title: ''
  type: Documentation
  url: https://vitess.io/docs/
- title: ''
  type: Getting Started
  url: https://vitess.io/docs/get-started/
- title: ''
  type: GitHub Organization
  url: https://github.com/vitessio
- title: ''
  type: GitHubRepository
  url: https://github.com/vitessio/vitess
- title: ''
  type: Blog
  url: https://vitess.io/blog/
- title: ''
  type: Community
  url: https://vitess.io/community/
- title: ''
  type: Slack
  url: https://vitess.io/slack
- title: ''
  type: Change Log
  url: https://github.com/vitessio/vitess/blob/main/changelog/
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/vitess
- title: ''
  type: Security
  url: https://github.com/vitessio/vitess/blob/main/SECURITY.md
created: '2025'
description: Vitess is a CNCF graduated database clustering system for horizontal scaling of MySQL through generalized sharding. It provides MySQL protocol compatibility, automated resharding, query routing, and connection pooling, making it suitable for running large-scale MySQL deployments on Kubernetes or other container orchestration platforms.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Vitess Context
  property_count: 9
  slug: vitess-context
layout: provider
modified: '2026-05-03'
name: Vitess
rules:
- name: Vitess API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 2
    info: 0
    warn: 5
  slug: vitess-rules
skills: []
slug: vitess
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vitess\nname: Vitess\ndescription: >-\n  Vitess is a CNCF graduated database clustering system for horizontal scaling\n  of MySQL through generalized sharding. It provides MySQL protocol\n  compatibility, automated resharding, query routing, and connection pooling,\n  making it suitable for running large-scale MySQL deployments on Kubernetes\n  or other container orchestration platforms.\ntype: Index\nurl: https://vitess.io\ntags:\n  - Cloud Native\n  - CNCF\n  - Database\n  - Distributed Systems\n  - Graduated\n  - MySQL\n  - Sharding\ncreated: '2025'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: vitess:vtgate-api\n    name: Vitess VTGate API\n    description: >-\n      VTGate is the stateless proxy that routes queries to the appropriate\n      VTTablet instances. It exposes a MySQL-compatible interface and a gRPC\n      API that clients use to interact with the Vitess cluster, handling query\n      routing, scatter queries, and transaction management\
  \ across shards.\n    humanURL: https://vitess.io/docs/reference/programs/vtgate/\n    properties:\n      - type: Documentation\n        url: https://vitess.io/docs/reference/programs/vtgate/\n      - type: Reference\n        url: https://vitess.io/docs/reference/query-serving/\n    tags:\n      - gRPC\n      - MySQL\n      - Proxy\n      - Query Routing\n      - SQL\n  - aid: vitess:vtadmin-api\n    name: Vitess VTAdmin API\n    description: >-\n      VTAdmin is the administrative web application and REST API for managing\n      Vitess clusters. It provides endpoints for inspecting cluster topology,\n      tablets, keyspaces, shards, schemas, and VReplication workflows, and\n      serves as the backend for the VTAdmin web UI.\n    humanURL: https://vitess.io/docs/reference/programs/vtadmin/\n    properties:\n      - type: Documentation\n        url: https://vitess.io/docs/reference/programs/vtadmin/\n      - type: Reference\n        url: https://vitess.io/docs/reference/vtadmin/\n   \
  \   - type: OpenAPI\n        url: openapi/vitess-vtadmin-openapi.yml\n    tags:\n      - Administration\n      - Cluster Management\n      - REST\n      - Web UI\n  - aid: vitess:vtctld-api\n    name: Vitess VTCtld API\n    description: >-\n      VTCtld is the Vitess topology management daemon that exposes a gRPC and\n      HTTP API for administrative operations on the cluster topology including\n      creating and managing keyspaces, shards, tablets, and executing\n      maintenance operations such as planned reparents and emergency reparents.\n    humanURL: https://vitess.io/docs/reference/programs/vtctld/\n    properties:\n      - type: Documentation\n        url: https://vitess.io/docs/reference/programs/vtctld/\n      - type: Reference\n        url: https://vitess.io/docs/reference/vtctl/\n    tags:\n      - Administration\n      - Cluster Management\n      - gRPC\n      - Topology\n  - aid: vitess:vreplication-api\n    name: Vitess VReplication API\n    description: >-\n      VReplication\
  \ is the Vitess framework for replicating and transforming\n      data streams within and across Vitess clusters. It powers features such\n      as MoveTables, Reshard, Materialize, and CreateLookupVindex and exposes\n      workflow management commands through the VTCtl API for orchestrating\n      data migrations and real-time replication workflows.\n    humanURL: https://vitess.io/docs/reference/vreplication/\n    properties:\n      - type: Documentation\n        url: https://vitess.io/docs/reference/vreplication/\n      - type: Reference\n        url: https://vitess.io/docs/reference/vreplication/vreplication/\n    tags:\n      - Data Migration\n      - Replication\n      - Streaming\n      - Workflows\ncommon:\n  - type: JSONSchema\n    url: json-schema/vitess-topology-schema.json\n  - type: JSONLD\n    url: json-ld/vitess-context.jsonld\n  - type: JSONStructure\n    url: json-structure/vitess-tablet-structure.json\n  - type: OpenAPI\n    url: openapi/vitess-vtadmin-openapi.yml\n \
  \ - type: SpectralRules\n    url: rules/vitess-rules.yml\n  - type: Vocabulary\n    url: vocabulary/vitess-vocabulary.yml\n  - type: Website\n    url: https://vitess.io\n  - type: Documentation\n    url: https://vitess.io/docs/\n  - type: Getting Started\n    url: https://vitess.io/docs/get-started/\n  - type: GitHub Organization\n    url: https://github.com/vitessio\n  - type: GitHubRepository\n    url: https://github.com/vitessio/vitess\n  - type: Blog\n    url: https://vitess.io/blog/\n  - type: Community\n    url: https://vitess.io/community/\n  - type: Slack\n    url: https://vitess.io/slack\n  - type: Change Log\n    url: https://github.com/vitessio/vitess/blob/main/changelog/\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/vitess\n  - type: Security\n    url: https://github.com/vitessio/vitess/blob/main/SECURITY.md\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vitess/refs/heads/main/apis.yml
tags:
- Cloud Native
- CNCF
- Database
- Distributed Systems
- Graduated
- MySQL
- Sharding
url: https://vitess.io
use_cases: []
---
