---
api_count: 1
apis:
- description: Curator provides a high-level Java API with fluent builders for ZooKeeper operations, along with pre-built recipes for leader election, distributed locks (shared, reentrant, read-write, semaphore), ba
  name: Apache Curator
  slug: apache-curator
common:
- title: ''
  type: Portal
  url: https://curator.apache.org/
- title: ''
  type: Documentation
  url: https://curator.apache.org/docs/
- title: ''
  type: GettingStarted
  url: https://curator.apache.org/docs/getting-started
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/curator
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/curator
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/vocabulary/apache-curator-vocabulary.yaml
created: '2026-03-16'
description: Apache Curator is a Java/JVM client library for Apache ZooKeeper, governed by the Apache Software Foundation, that provides a high-level API framework, fluent builders, and pre-built distributed coordination recipes including leader election, distributed locks, barriers, caches, counters, and service discovery. It significantly simplifies writing reliable distributed applications.
features:
- description: Wraps the raw ZooKeeper client with connection management, retry policies, and error handling for reliable distributed coordination.
  name: High-Level ZooKeeper Client
- description: Provides a chainable, readable Java DSL for all ZooKeeper CRUD operations including watchers, transactions, and ACLs.
  name: Fluent Builder API
- description: 'Pre-built implementations of distributed patterns: leader election, locks, semaphores, barriers, counters, queues, and group membership.'
  name: Distributed Coordination Recipes
- description: curator-x-discovery provides a ZooKeeper-based service registry and discovery mechanism with instance registration and lookup.
  name: Service Discovery
- description: curator-async provides a CompletionStage-based async API with O/R modeling and schema migration for ZooKeeper data.
  name: Asynchronous DSL
- description: CuratorCache provides an efficient local replica of ZooKeeper subtrees with near-real-time change notifications.
  name: Node Caching
- description: curator-test includes TestingServer (embedded ZooKeeper) and TestingCluster for writing reliable unit and integration tests.
  name: Testing Support
- description: Configurable retry policies (ExponentialBackoff, BoundedExponentialBackoff, RetryNTimes, etc.) for handling transient failures.
  name: Retry Policies
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Curator is built on top of ZooKeeper and requires a running ZooKeeper ensemble.
  name: Apache ZooKeeper
- description: Earlier versions of Kafka used ZooKeeper (managed via Curator) for broker coordination and metadata.
  name: Apache Kafka
- description: HBase uses ZooKeeper for master election and region server coordination, often managed via Curator.
  name: Apache HBase
- description: Storm uses Curator for its ZooKeeper-based cluster state management.
  name: Apache Storm
- description: Spring Cloud Zookeeper integrates with Apache Curator for service discovery and distributed configuration.
  name: Spring Framework
- description: All Curator modules are published to Maven Central under org.apache.curator group ID.
  name: Maven Central
jsonld:
- class_count: 5
  name: Apache Curator Context
  property_count: 27
  slug: apache-curator-context
layout: provider
modified: '2026-04-19'
name: Apache Curator
skills: []
slug: apache-curator
solutions: []
source_filename: apis.yml
source_yaml: "aid: apache-curator\nname: Apache Curator\ndescription: >-\n  Apache Curator is a Java/JVM client library for Apache ZooKeeper, governed by the Apache Software Foundation, that provides a high-level API framework, fluent builders, and pre-built distributed coordination\n  recipes including leader election, distributed locks, barriers, caches, counters, and service discovery. It significantly simplifies writing reliable distributed applications.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Apache\n- Distributed Coordination\n- Distributed Systems\n- Java\n- Maven\n- Open Source\n- Service Discovery\n- ZooKeeper\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-curator:apache-curator\n  name: Apache Curator\n  description: >-\n  \
  \  Curator provides a high-level Java API with fluent builders for ZooKeeper operations, along with pre-built recipes for leader election, distributed locks (shared, reentrant, read-write, semaphore),\n    barriers, caches (CuratorCache, PathCache, TreeCache), distributed counters, queues, group membership, and service discovery via curator-x-discovery.\n  humanURL: https://curator.apache.org/docs/about\n  tags:\n  - Barriers\n  - Caches\n  - Distributed Locks\n  - Java\n  - Leader Election\n  - Maven\n  - Queues\n  - Service Discovery\n  - ZooKeeper\n  properties:\n  - type: Documentation\n    url: https://curator.apache.org/docs/about\n  - type: APIReference\n    url: https://curator.apache.org/apidocs/\n  - type: GettingStarted\n    url: https://curator.apache.org/docs/getting-started\n  - type: GitHubRepository\n    url: https://github.com/apache/curator\n  - type: SDK\n    url: https://mvnrepository.com/artifact/org.apache.curator/curator-framework\n    title: curator-framework (Maven)\n\
  \  - type: SDK\n    url: https://mvnrepository.com/artifact/org.apache.curator/curator-recipes\n    title: curator-recipes (Maven)\n  - type: SDK\n    url: https://mvnrepository.com/artifact/org.apache.curator/curator-x-discovery\n    title: curator-x-discovery (Maven)\n  - type: SDK\n    url: https://mvnrepository.com/artifact/org.apache.curator/curator-async\n    title: curator-async (Maven)\n  - type: Tools\n    url: https://mvnrepository.com/artifact/org.apache.curator/curator-test\n    title: curator-test (Testing)\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/json-schema/apache-curator-distributed-lock-schema.json\n    title: Distributed Lock\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/json-schema/apache-curator-leader-latch-state-schema.json\n    title: Leader Latch State\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/json-schema/apache-curator-node-data-schema.json\n\
  \    title: Node Data\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/json-schema/apache-curator-service-instance-schema.json\n    title: Service Instance\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/json-structure/apache-curator-distributed-lock-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/json-structure/apache-curator-leader-latch-state-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/json-structure/apache-curator-node-data-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/json-structure/apache-curator-service-instance-structure.json\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/json-ld/apache-curator-context.jsonld\n\
  \  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/examples/apache-curator-distributed-lock-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/examples/apache-curator-leader-latch-state-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/examples/apache-curator-node-data-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/examples/apache-curator-service-instance-example.json\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: Portal\n  url: https://curator.apache.org/\n- type: Documentation\n  url: https://curator.apache.org/docs/\n- type: GettingStarted\n  url: https://curator.apache.org/docs/getting-started\n- type: GitHubOrganization\n  url: https://github.com/apache\n- type: GitHubRepository\n\
  \  url: https://github.com/apache/curator\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/curator\n- type: Features\n  data:\n  - name: High-Level ZooKeeper Client\n    description: Wraps the raw ZooKeeper client with connection management, retry policies, and error handling for reliable distributed coordination.\n  - name: Fluent Builder API\n    description: Provides a chainable, readable Java DSL for all ZooKeeper CRUD operations including watchers, transactions, and ACLs.\n  - name: Distributed Coordination Recipes\n    description: 'Pre-built implementations of distributed patterns: leader election, locks, semaphores, barriers, counters, queues, and group membership.'\n  - name: Service Discovery\n    description: curator-x-discovery provides a ZooKeeper-based service registry and discovery mechanism with instance registration and lookup.\n  - name: Asynchronous DSL\n    description: curator-async provides a CompletionStage-based async API with O/R modeling\
  \ and schema migration for ZooKeeper data.\n  - name: Node Caching\n    description: CuratorCache provides an efficient local replica of ZooKeeper subtrees with near-real-time change notifications.\n  - name: Testing Support\n    description: curator-test includes TestingServer (embedded ZooKeeper) and TestingCluster for writing reliable unit and integration tests.\n  - name: Retry Policies\n    description: Configurable retry policies (ExponentialBackoff, BoundedExponentialBackoff, RetryNTimes, etc.) for handling transient failures.\n- type: UseCases\n  data:\n  - name: Distributed Leader Election\n    description: Elect a single leader across a cluster for coordinating distributed workloads, using LeaderLatch or LeaderSelector recipes.\n  - name: Distributed Locking\n    description: Prevent concurrent access to shared resources across JVMs using InterProcessMutex and related lock recipes.\n  - name: Service Registry and Discovery\n    description: Register microservices with ZooKeeper\
  \ and discover them by type using curator-x-discovery.\n  - name: Distributed Configuration\n    description: Store and watch shared configuration data across a cluster with automatic change notifications via NodeCache.\n  - name: Cluster Membership Tracking\n    description: Track which nodes are alive in a distributed cluster using GroupMember and PersistentNode recipes.\n  - name: Distributed Counters and IDs\n    description: Generate globally unique sequential IDs or maintain shared atomic counters across a cluster.\n- type: Integrations\n  data:\n  - name: Apache ZooKeeper\n    description: Curator is built on top of ZooKeeper and requires a running ZooKeeper ensemble.\n  - name: Apache Kafka\n    description: Earlier versions of Kafka used ZooKeeper (managed via Curator) for broker coordination and metadata.\n  - name: Apache HBase\n    description: HBase uses ZooKeeper for master election and region server coordination, often managed via Curator.\n  - name: Apache Storm\n    description:\
  \ Storm uses Curator for its ZooKeeper-based cluster state management.\n  - name: Spring Framework\n    description: Spring Cloud Zookeeper integrates with Apache Curator for service discovery and distributed configuration.\n  - name: Maven Central\n    description: All Curator modules are published to Maven Central under org.apache.curator group ID.\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/vocabulary/apache-curator-vocabulary.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/apis.yml
tags:
- Apache
- Distributed Coordination
- Distributed Systems
- Java
- Maven
- Open Source
- Service Discovery
- ZooKeeper
url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/apis.yml
use_cases:
- description: Elect a single leader across a cluster for coordinating distributed workloads, using LeaderLatch or LeaderSelector recipes.
  name: Distributed Leader Election
- description: Prevent concurrent access to shared resources across JVMs using InterProcessMutex and related lock recipes.
  name: Distributed Locking
- description: Register microservices with ZooKeeper and discover them by type using curator-x-discovery.
  name: Service Registry and Discovery
- description: Store and watch shared configuration data across a cluster with automatic change notifications via NodeCache.
  name: Distributed Configuration
- description: Track which nodes are alive in a distributed cluster using GroupMember and PersistentNode recipes.
  name: Cluster Membership Tracking
- description: Generate globally unique sequential IDs or maintain shared atomic counters across a cluster.
  name: Distributed Counters and IDs
---
