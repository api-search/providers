---
api_count: 2
api_specs:
- filename: zookeeper-admin-api.yml
  format: yaml
  label: Apache ZooKeeper Admin Server API
  slug: apache-zookeeper-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-zookeeper/refs/heads/main/openapi/zookeeper-admin-api.yml
apis:
- description: The ZooKeeper Admin Server provides HTTP endpoints on port 8080 that expose the four-letter-word equivalent commands as REST endpoints for cluster monitoring, configuration, and diagnostics. Endpoints
  name: Apache ZooKeeper Admin Server API
  slug: apache-zookeeper-admin-api
- description: The ZooKeeper client API provides Java and C language bindings for distributed coordination operations. Operations include create (create znodes), delete, exists (check existence), getData, setData, g
  name: Apache ZooKeeper Client API
  slug: apache-zookeeper-client-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/zookeeper
- title: ''
  type: Documentation
  url: https://zookeeper.apache.org/doc/current/
- title: ''
  type: Portal
  url: https://zookeeper.apache.org/
- title: ''
  type: GettingStarted
  url: https://zookeeper.apache.org/doc/current/zookeeperStarted.html
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/zookeeper/releases
- title: ''
  type: Support
  url: https://zookeeper.apache.org/lists.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: ''
  type: SpectralRules
  url: rules/apache-zookeeper-spectral-rules.yml
- title: Python Kazoo Client
  type: SDK
  url: https://pypi.org/project/kazoo/
- title: Node.js Client
  type: SDK
  url: https://www.npmjs.com/package/node-zookeeper-client
created: '2026-03-16'
description: Apache ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services for distributed systems. It provides a hierarchical key-value store (znodes), watches for change notifications, ephemeral nodes for presence detection, and sequential nodes for leader election and distributed locking. ZooKeeper exposes a Java/C client API and an HTTP Admin Server API for monitoring and management. It is widely used by Kafka, Hadoop, HBase, Storm, and other distributed systems.
features:
- description: Tree-structured znode namespace similar to a filesystem for organized configuration storage.
  name: Hierarchical Namespace
- description: Client watches on znodes trigger one-time callbacks on change events for reactive patterns.
  name: Watch Notifications
- description: Nodes that disappear when the creating client session expires for presence detection.
  name: Ephemeral Nodes
- description: Auto-incrementing sequential znodes for implementing distributed queues and leader election.
  name: Sequential Nodes
- description: Compare-and-set and multi-operation batches for consistent distributed state updates.
  name: Atomic Operations
- description: Per-znode access control lists for authentication and authorization of znode operations.
  name: ACL Security
- description: Read-only observer servers for scaling read throughput without affecting write quorum.
  name: Observer Mode
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: ZooKeeper (legacy) for Kafka broker metadata and controller election (replaced by KRaft).
  name: Apache Kafka
- description: ZooKeeper for HBase region server coordination and master election.
  name: Apache HBase
- description: ZooKeeper for HDFS NameNode HA fencing and YARN ResourceManager HA.
  name: Apache Hadoop
- description: ZooKeeper for Storm Nimbus coordination and worker heartbeat tracking.
  name: Apache Storm
- description: ZooKeeper for SolrCloud cluster coordination, configuration, and leader election.
  name: Apache Solr
- description: High-level ZooKeeper client with recipes for common distributed patterns.
  name: Apache Curator
layout: provider
modified: '2026-04-19'
name: Apache ZooKeeper
rules:
- name: Apache ZooKeeper API Rules
  rule_count: 10
  severity_counts:
    error: 7
    hint: 0
    info: 2
    warn: 1
  slug: apache-zookeeper-spectral-rules
skills: []
slug: apache-zookeeper
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-zookeeper\nname: Apache ZooKeeper\ndescription: >-\n  Apache ZooKeeper is a centralized service for maintaining configuration information, naming,\n  providing distributed synchronization, and providing group services for distributed systems.\n  It provides a hierarchical key-value store (znodes), watches for change notifications, ephemeral\n  nodes for presence detection, and sequential nodes for leader election and distributed locking.\n  ZooKeeper exposes a Java/C client API and an HTTP Admin Server API for monitoring and management.\n  It is widely used by Kafka, Hadoop, HBase, Storm, and other distributed systems.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Configuration Management\n  - Distributed Coordination\n  - Leader Election\n  - Service Discovery\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-zookeeper/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: apache-zookeeper:apache-zookeeper-admin-api\n    name: Apache ZooKeeper Admin Server API\n    description: >-\n      The ZooKeeper Admin Server provides HTTP endpoints on port 8080 that expose the four-letter-word\n      equivalent commands as REST endpoints for cluster monitoring, configuration, and diagnostics.\n      Endpoints include /commands/conf (server configuration), /commands/stats (server statistics),\n      /commands/mntr (monitoring metrics), /commands/envi (environment info), /commands/dump\n      (session/ephemeral node dump), /commands/crst (connection reset), and /commands/leader\n      (leader info for QuorumPeerMain).\n    humanURL: https://zookeeper.apache.org/doc/current/zookeeperAdmin.html#sc_4lw\n    baseURL: http://localhost:8080/commands\n    tags:\n      - REST\n      - Admin\n      - Monitoring\n      - Cluster Management\n    properties:\n      - type: Documentation\n        url: https://zookeeper.apache.org/doc/current/zookeeperAdmin.html#sc_4lw\n\
  \      - type: OpenAPI\n        url: openapi/zookeeper-admin-api.yml\n  - aid: apache-zookeeper:apache-zookeeper-client-api\n    name: Apache ZooKeeper Client API\n    description: >-\n      The ZooKeeper client API provides Java and C language bindings for distributed coordination\n      operations. Operations include create (create znodes), delete, exists (check existence), getData,\n      setData, getChildren, getACL, setACL, and multi (batch operations). Watch mechanisms notify\n      clients of znode changes. Curator is the recommended high-level Java client with recipes for\n      distributed locks, leader elections, service discovery, and caches.\n    humanURL: https://zookeeper.apache.org/doc/current/zookeeperProgrammers.html\n    tags:\n      - Java\n      - C\n      - Coordination\n      - Leader Election\n    properties:\n      - type: Documentation\n        url: https://zookeeper.apache.org/doc/current/zookeeperProgrammers.html\n      - type: APIReference\n        url: https://zookeeper.apache.org/doc/current/apidocs/zookeeper-server/\n\
  \      - type: SDK\n        url: https://search.maven.org/search?q=org.apache.zookeeper\n        title: Java Maven SDK\n      - type: SDK\n        url: https://curator.apache.org/\n        title: Apache Curator (High-Level Java Client)\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/zookeeper\n  - type: Documentation\n    url: https://zookeeper.apache.org/doc/current/\n  - type: Portal\n    url: https://zookeeper.apache.org/\n  - type: GettingStarted\n    url: https://zookeeper.apache.org/doc/current/zookeeperStarted.html\n  - type: ReleaseNotes\n    url: https://github.com/apache/zookeeper/releases\n  - type: Support\n    url: https://zookeeper.apache.org/lists.html\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: SpectralRules\n    url: rules/apache-zookeeper-spectral-rules.yml\n  - type: SDK\n    url: https://pypi.org/project/kazoo/\n    title: Python Kazoo Client\n  - type: SDK\n    url: https://www.npmjs.com/package/node-zookeeper-client\n\
  \    title: Node.js Client\n  - type: Features\n    data:\n      - name: Hierarchical Namespace\n        description: Tree-structured znode namespace similar to a filesystem for organized configuration storage.\n      - name: Watch Notifications\n        description: Client watches on znodes trigger one-time callbacks on change events for reactive patterns.\n      - name: Ephemeral Nodes\n        description: Nodes that disappear when the creating client session expires for presence detection.\n      - name: Sequential Nodes\n        description: Auto-incrementing sequential znodes for implementing distributed queues and leader election.\n      - name: Atomic Operations\n        description: Compare-and-set and multi-operation batches for consistent distributed state updates.\n      - name: ACL Security\n        description: Per-znode access control lists for authentication and authorization of znode operations.\n      - name: Observer Mode\n        description: Read-only observer servers\
  \ for scaling read throughput without affecting write quorum.\n  - type: UseCases\n    data:\n      - name: Leader Election\n        description: Distributed leader election using ephemeral sequential znodes for coordination.\n      - name: Distributed Configuration Management\n        description: Centralized configuration storage with watch-based change notification to services.\n      - name: Service Registry and Discovery\n        description: Service registration and lookup using ephemeral znodes as presence indicators.\n      - name: Distributed Locking\n        description: Distributed mutex and read/write locks using ephemeral sequential znode recipes.\n      - name: Cluster Coordination\n        description: Kafka broker coordination, HBase region server management, and Hadoop NameNode fencing.\n  - type: Integrations\n    data:\n      - name: Apache Kafka\n        description: ZooKeeper (legacy) for Kafka broker metadata and controller election (replaced by KRaft).\n      - name:\
  \ Apache HBase\n        description: ZooKeeper for HBase region server coordination and master election.\n      - name: Apache Hadoop\n        description: ZooKeeper for HDFS NameNode HA fencing and YARN ResourceManager HA.\n      - name: Apache Storm\n        description: ZooKeeper for Storm Nimbus coordination and worker heartbeat tracking.\n      - name: Apache Solr\n        description: ZooKeeper for SolrCloud cluster coordination, configuration, and leader election.\n      - name: Apache Curator\n        description: High-level ZooKeeper client with recipes for common distributed patterns.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-zookeeper/refs/heads/main/apis.yml
tags:
- Configuration Management
- Distributed Coordination
- Leader Election
- Service Discovery
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-zookeeper/refs/heads/main/apis.yml
use_cases:
- description: Distributed leader election using ephemeral sequential znodes for coordination.
  name: Leader Election
- description: Centralized configuration storage with watch-based change notification to services.
  name: Distributed Configuration Management
- description: Service registration and lookup using ephemeral znodes as presence indicators.
  name: Service Registry and Discovery
- description: Distributed mutex and read/write locks using ephemeral sequential znode recipes.
  name: Distributed Locking
- description: Kafka broker coordination, HBase region server management, and Hadoop NameNode fencing.
  name: Cluster Coordination
---
