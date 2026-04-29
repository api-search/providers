---
api_count: 2
api_specs:
- filename: apache-helix-rest-openapi.yml
  format: yaml
  label: Apache Helix REST API
  slug: apache-helix-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-helix/refs/heads/main/openapi/apache-helix-rest-openapi.yml
apis:
- description: REST API for managing Apache Helix clusters, instances, resources, and partition state assignments, including ideal state queries and external view inspection.
  name: Apache Helix REST API
  slug: apache-helix-rest-api
- description: Java API for implementing Helix participant, spectator, and controller roles, with APIs for resource management, task execution, and state machine definitions.
  name: Apache Helix Java API
  slug: apache-helix-java-api
capabilities:
- description: ''
  name: Helix Cluster Management
  slug: helix-cluster-management
common:
- title: ''
  type: Documentation
  url: https://helix.apache.org/
- title: ''
  type: GettingStarted
  url: https://helix.apache.org/0.9.9-docs/Quickstart.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/helix
- title: ''
  type: SpectralRules
  url: rules/apache-helix-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-helix-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/helix-cluster-management.yaml
created: '2026-03-16'
description: Apache Helix is a generic cluster management framework for partitioned and replicated distributed resources. It automates partition management, replication, fault tolerance, and cluster expansion for distributed systems, providing a REST API for cluster administration and a Java API for participant, spectator, and controller roles.
features:
- description: Automatically assign and balance partitions across cluster nodes using pluggable rebalancer algorithms.
  name: Automatic Partition Management
- description: Define custom resource state machines (e.g., Master-Slave, Leader-Standby) for any distributed service.
  name: State Machine Framework
- description: Detect node failures and automatically reassign partitions to maintain replication targets.
  name: Fault Tolerance
- description: HTTP REST API for cluster administration, resource management, and state inspection.
  name: REST API
- description: Distributed task scheduling framework for batch jobs and recurring workflows with failure handling.
  name: Task Framework
- description: Uses Apache ZooKeeper as the distributed coordination backend for cluster state storage.
  name: ZooKeeper Integration
- description: Read-only API for external services to observe resource state and routing decisions.
  name: Spectator API
- description: Rack and zone-aware partition placement for fault-domain isolation in cloud environments.
  name: Cloud-Aware Rebalancing
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: ZooKeeper is the required coordination backend for Helix cluster state management.
  name: Apache ZooKeeper
- description: Helix is used internally by some Kafka ecosystem projects for partition management.
  name: Apache Kafka
- description: Apache Pinot uses Helix for real-time OLAP cluster partition and segment management.
  name: LinkedIn Pinot
- description: Venice feature store uses Helix for managing data store partition assignments.
  name: LinkedIn Venice
jsonld:
- class_count: 16
  name: Apache Helix Rest Context
  property_count: 0
  slug: apache-helix-rest-context
layout: provider
modified: '2026-04-19'
name: Apache Helix
rules:
- name: Apache Helix API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: apache-helix-spectral-rules
skills: []
slug: apache-helix
solutions: []
source_filename: apis.yml
source_yaml: "aid: apache-helix\nname: Apache Helix\ndescription: >-\n  Apache Helix is a generic cluster management framework for partitioned and replicated distributed resources. It automates partition management, replication, fault tolerance, and cluster expansion for distributed systems, providing a REST API for cluster administration and a Java API for participant, spectator, and controller roles.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache\n  - Cluster Management\n  - Distributed Systems\n  - Open Source\n  - Partitioning\n  - Replication\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-helix/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-helix:apache-helix-rest-api\n    name: Apache Helix REST API\n    description: >-\n      REST API for managing Apache Helix clusters, instances,\
  \ resources, and partition state assignments, including ideal state queries and external view inspection.\n    humanURL: https://helix.apache.org/0.9.9-docs/tutorial_admin.html\n    baseURL: http://localhost:9100\n    tags:\n      - Cluster Management\n      - Instances\n      - Partitions\n      - REST\n      - Resources\n    properties:\n      - type: Documentation\n        url: https://helix.apache.org/0.9.9-docs/tutorial_admin.html\n      - type: OpenAPI\n        url: openapi/apache-helix-rest-openapi.yml\n      - type: JSONSchema\n        url: json-schema/helix-rest-cluster-schema.json\n      - type: JSON-LD\n        url: json-ld/apache-helix-rest-context.jsonld\n\n  - aid: apache-helix:apache-helix-java-api\n    name: Apache Helix Java API\n    description: >-\n      Java API for implementing Helix participant, spectator, and controller roles, with APIs for resource management, task execution, and state machine definitions.\n    humanURL: https://helix.apache.org/0.9.9-docs/tutorial_participant.html\n\
  \    tags:\n      - Java\n      - SDK\n      - State Machine\n    properties:\n      - type: Documentation\n        url: https://helix.apache.org/0.9.9-docs/tutorial_participant.html\n      - type: SDK\n        url: https://search.maven.org/artifact/org.apache.helix/helix-core\n        title: Java SDK (Maven Central)\n\ncommon:\n  - type: Documentation\n    url: https://helix.apache.org/\n  - type: GettingStarted\n    url: https://helix.apache.org/0.9.9-docs/Quickstart.html\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/helix\n  - type: SpectralRules\n    url: rules/apache-helix-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-helix-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/helix-cluster-management.yaml\n  - type: Features\n    data:\n      - name: Automatic Partition Management\n        description: Automatically assign and balance partitions across cluster\
  \ nodes using pluggable rebalancer algorithms.\n      - name: State Machine Framework\n        description: Define custom resource state machines (e.g., Master-Slave, Leader-Standby) for any distributed service.\n      - name: Fault Tolerance\n        description: Detect node failures and automatically reassign partitions to maintain replication targets.\n      - name: REST API\n        description: HTTP REST API for cluster administration, resource management, and state inspection.\n      - name: Task Framework\n        description: Distributed task scheduling framework for batch jobs and recurring workflows with failure handling.\n      - name: ZooKeeper Integration\n        description: Uses Apache ZooKeeper as the distributed coordination backend for cluster state storage.\n      - name: Spectator API\n        description: Read-only API for external services to observe resource state and routing decisions.\n      - name: Cloud-Aware Rebalancing\n        description: Rack and zone-aware\
  \ partition placement for fault-domain isolation in cloud environments.\n  - type: UseCases\n    data:\n      - name: Distributed Database Cluster Management\n        description: Manage shard assignment and replication for distributed databases like DistributedLog or Espresso.\n      - name: Search Index Partition Management\n        description: Automatically balance and assign search index shards across a cluster of query servers.\n      - name: Distributed Task Scheduling\n        description: Schedule and execute distributed batch tasks with automatic retry and failure recovery.\n      - name: Microservices Load Balancing\n        description: Use Helix spectator API to implement client-side load balancing based on partition state.\n      - name: Stateful Service Migration\n        description: Perform rolling upgrades and partition migrations without service downtime.\n  - type: Integrations\n    data:\n      - name: Apache ZooKeeper\n        description: ZooKeeper is the required\
  \ coordination backend for Helix cluster state management.\n      - name: Apache Kafka\n        description: Helix is used internally by some Kafka ecosystem projects for partition management.\n      - name: LinkedIn Pinot\n        description: Apache Pinot uses Helix for real-time OLAP cluster partition and segment management.\n      - name: LinkedIn Venice\n        description: Venice feature store uses Helix for managing data store partition assignments.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-helix/refs/heads/main/apis.yml
tags:
- Apache
- Cluster Management
- Distributed Systems
- Open Source
- Partitioning
- Replication
url: https://raw.githubusercontent.com/api-evangelist/apache-helix/refs/heads/main/apis.yml
use_cases:
- description: Manage shard assignment and replication for distributed databases like DistributedLog or Espresso.
  name: Distributed Database Cluster Management
- description: Automatically balance and assign search index shards across a cluster of query servers.
  name: Search Index Partition Management
- description: Schedule and execute distributed batch tasks with automatic retry and failure recovery.
  name: Distributed Task Scheduling
- description: Use Helix spectator API to implement client-side load balancing based on partition state.
  name: Microservices Load Balancing
- description: Perform rolling upgrades and partition migrations without service downtime.
  name: Stateful Service Migration
---
