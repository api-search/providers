---
api_count: 1
apis:
- description: CouchDB exposes a complete RESTful HTTP/JSON API covering server and database management, document CRUD operations, bulk operations, design documents with MapReduce views, Mango (declarative JSON) que
  name: Apache CouchDB HTTP API
  slug: apache-couchdb-http-api
capabilities:
- description: Workflow capability for managing CouchDB documents, databases, and queries. Combines document CRUD, Mango queries, changes feed, and replication for developers and data engineers.
  name: Apache CouchDB Document Management
  slug: couchdb-document-management
common:
- title: ''
  type: Portal
  url: https://couchdb.apache.org/
- title: ''
  type: Documentation
  url: https://docs.couchdb.org/en/stable/
- title: ''
  type: GettingStarted
  url: https://docs.couchdb.org/en/stable/intro/
- title: ''
  type: Blog
  url: https://blog.couchdb.org/
- title: ''
  type: ReleaseNotes
  url: https://docs.couchdb.org/en/stable/whatsnew/
- title: ''
  type: Support
  url: https://couchdb.apache.org/#mailing-list
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/couchdb
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/rules/apache-couchdb-spectral-rules.yml
- title: CouchDB Document Management
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/capabilities/couchdb-document-management.yaml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/vocabulary/apache-couchdb-vocabulary.yaml
created: '2026-03-16'
description: Apache CouchDB is an open-source distributed document-oriented NoSQL database governed by the Apache Software Foundation. It uses JSON for data storage, a RESTful HTTP/JSON API for all database operations, and the Couch Replication Protocol for multi-primary synchronization across servers, mobile devices, and browsers. CouchDB supports Mango queries, MapReduce views, and offline-first application architectures.
features:
- description: All database operations are performed via a clean HTTP API using JSON, making it accessible from any HTTP-capable client.
  name: RESTful HTTP/JSON API
- description: The Couch Replication Protocol enables seamless bidirectional synchronization across servers, mobile, and browser environments.
  name: Multi-Primary Replication
- description: Applications can operate fully offline and sync changes when connectivity is restored, enabled by conflict-aware replication.
  name: Offline-First Architecture
- description: Declarative JSON-based query language for ad-hoc document queries with index support, similar to MongoDB query syntax.
  name: Mango Query Language
- description: Persistent, incrementally updated secondary indexes defined via JavaScript MapReduce functions stored as design documents.
  name: MapReduce Views
- description: Real-time notification feed of all database changes, supporting long-polling, continuous, and event-source modes.
  name: Changes Feed
- description: Built-in clustering with consistent hashing for horizontal scaling and high availability across multiple nodes.
  name: Cluster Support
- description: Multi-Version Concurrency Control ensures non-blocking reads; document updates are ACID-compliant at the document level.
  name: MVCC and ACID
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Browser and Node.js database that syncs with CouchDB via the Couch Replication Protocol.
  name: PouchDB
- description: IBM Cloudant is a fully managed cloud database service based on Apache CouchDB, API-compatible.
  name: IBM Cloudant
- description: Official CouchDB Docker images for container-based deployments.
  name: Docker
- description: Official Helm chart for deploying CouchDB clusters on Kubernetes.
  name: Kubernetes / Helm
- description: CouchDB changes feed can be consumed and bridged to Kafka for event streaming pipelines.
  name: Apache Kafka
- description: CouchDB clusters are typically fronted by Nginx or HAProxy for SSL termination and load balancing.
  name: Nginx / Load Balancers
jsonld:
- class_count: 26
  name: Apache Couchdb Http Api Context
  property_count: 62
  slug: apache-couchdb-http-api-context
layout: provider
modified: '2026-04-19'
name: Apache CouchDB
rules:
- name: Apache CouchDB API Rules
  rule_count: 28
  severity_counts:
    error: 11
    hint: 0
    info: 2
    warn: 15
  slug: apache-couchdb-spectral-rules
skills: []
slug: apache-couchdb
solutions: []
source_filename: apis.yml
source_yaml: "aid: apache-couchdb\nname: Apache CouchDB\ndescription: >-\n  Apache CouchDB is an open-source distributed document-oriented NoSQL database governed by the Apache Software Foundation. It uses JSON for data storage, a RESTful HTTP/JSON API for all database operations,\n  and the Couch Replication Protocol for multi-primary synchronization across servers, mobile devices, and browsers. CouchDB supports Mango queries, MapReduce views, and offline-first application architectures.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Apache\n- Database\n- Document Store\n- JSON\n- NoSQL\n- Open Source\n- Replication\n- REST\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-couchdb:apache-couchdb-http-api\n  name: Apache CouchDB HTTP API\n  description:\
  \ >-\n    CouchDB exposes a complete RESTful HTTP/JSON API covering server and database management, document CRUD operations, bulk operations, design documents with MapReduce views, Mango (declarative JSON) query\n    API, replication, changes feeds, authentication, and cluster administration.\n  humanURL: https://docs.couchdb.org/en/stable/api/index.html\n  tags:\n  - Cluster\n  - Database\n  - Document\n  - HTTP\n  - JSON\n  - Mango\n  - NoSQL\n  - Replication\n  - REST\n  - Views\n  properties:\n  - type: Documentation\n    url: https://docs.couchdb.org/en/stable/api/index.html\n  - type: GettingStarted\n    url: https://docs.couchdb.org/en/stable/intro/index.html\n  - type: APIReference\n    url: https://docs.couchdb.org/en/stable/api/\n  - type: GitHubRepository\n    url: https://github.com/apache/couchdb\n  - type: SDK\n    url: https://www.npmjs.com/package/nano\n    title: Node.js SDK (Nano)\n  - type: SDK\n    url: https://pypi.org/project/couchdb/\n    title: Python SDK\n  -\
  \ type: SDK\n    url: https://pypi.org/project/aiocouch/\n    title: Python Async SDK (aiocouch)\n  - type: Tools\n    url: https://github.com/apache/couchdb-fauxton\n    title: Fauxton Web UI\n  - type: Tools\n    url: https://github.com/apache/couchdb-docker\n    title: Docker Images\n  - type: Tools\n    url: https://github.com/apache/couchdb-helm\n    title: Helm Chart\n  - type: SDK\n    url: https://github.com/apache/pouchdb\n    title: PouchDB (Browser/Mobile Sync)\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/openapi/apache-couchdb-http-api-openapi.yaml\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-all-docs-response-schema.json\n    title: All Docs Response\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-bulk-docs-request-schema.json\n\
  \    title: Bulk Docs Request\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-change-row-schema.json\n    title: Change Row\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-changes-response-schema.json\n    title: Changes Response\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-cluster-setup-response-schema.json\n    title: Cluster Setup Response\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-create-index-request-schema.json\n    title: Create Index Request\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-create-index-response-schema.json\n\
  \    title: Create Index Response\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-database-info-schema.json\n    title: Database Info\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-doc-row-schema.json\n    title: Doc Row\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-document-input-schema.json\n    title: Document Input\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-document-schema.json\n    title: Document\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-error-response-schema.json\n    title: Error Response\n  - type: JSONSchema\n    url:\
  \ https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-find-request-schema.json\n    title: Find Request\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-find-response-schema.json\n    title: Find Response\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-indexes-response-schema.json\n    title: Indexes Response\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-keys-request-schema.json\n    title: Keys Request\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-ok-response-schema.json\n    title: Ok Response\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-replication-request-schema.json\n\
  \    title: Replication Request\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-replication-response-schema.json\n    title: Replication Response\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-server-info-schema.json\n    title: Server Info\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-session-info-schema.json\n    title: Session Info\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-session-request-schema.json\n    title: Session Request\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-view-response-schema.json\n    title: View Response\n\
  \  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-schema/apache-couchdb-write-response-schema.json\n    title: Write Response\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-all-docs-response-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-bulk-docs-request-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-change-row-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-changes-response-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-cluster-setup-response-structure.json\n\
  \  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-create-index-request-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-create-index-response-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-database-info-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-doc-row-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-document-input-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-document-structure.json\n\
  \  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-error-response-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-find-request-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-find-response-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-indexes-response-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-keys-request-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-ok-response-structure.json\n\
  \  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-replication-request-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-replication-response-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-server-info-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-session-info-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-session-request-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-view-response-structure.json\n\
  \  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-structure/apache-couchdb-write-response-structure.json\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-ld/apache-couchdb-http-api-context.jsonld\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-all-docs-response-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-bulk-docs-request-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-change-row-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-changes-response-example.json\n  - type: Example\n \
  \   url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-cluster-setup-response-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-create-index-request-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-create-index-response-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-database-info-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-doc-row-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-document-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-document-input-example.json\n\
  \  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-error-response-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-find-request-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-find-response-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-indexes-response-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-keys-request-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-ok-response-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-replication-request-example.json\n\
  \  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-replication-response-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-server-info-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-session-info-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-session-request-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-view-response-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/examples/apache-couchdb-write-response-example.json\nmaintainers:\n- FN: Kin Lane\n \
  \ email: info@apievangelist.com\ncommon:\n- type: Portal\n  url: https://couchdb.apache.org/\n- type: Documentation\n  url: https://docs.couchdb.org/en/stable/\n- type: GettingStarted\n  url: https://docs.couchdb.org/en/stable/intro/\n- type: Blog\n  url: https://blog.couchdb.org/\n- type: ReleaseNotes\n  url: https://docs.couchdb.org/en/stable/whatsnew/\n- type: Support\n  url: https://couchdb.apache.org/#mailing-list\n- type: GitHubOrganization\n  url: https://github.com/apache\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/couchdb\n- type: Features\n  data:\n  - name: RESTful HTTP/JSON API\n    description: All database operations are performed via a clean HTTP API using JSON, making it accessible from any HTTP-capable client.\n  - name: Multi-Primary Replication\n    description: The Couch Replication Protocol enables seamless bidirectional synchronization across servers, mobile, and browser environments.\n  - name: Offline-First Architecture\n    description:\
  \ Applications can operate fully offline and sync changes when connectivity is restored, enabled by conflict-aware replication.\n  - name: Mango Query Language\n    description: Declarative JSON-based query language for ad-hoc document queries with index support, similar to MongoDB query syntax.\n  - name: MapReduce Views\n    description: Persistent, incrementally updated secondary indexes defined via JavaScript MapReduce functions stored as design documents.\n  - name: Changes Feed\n    description: Real-time notification feed of all database changes, supporting long-polling, continuous, and event-source modes.\n  - name: Cluster Support\n    description: Built-in clustering with consistent hashing for horizontal scaling and high availability across multiple nodes.\n  - name: MVCC and ACID\n    description: Multi-Version Concurrency Control ensures non-blocking reads; document updates are ACID-compliant at the document level.\n- type: UseCases\n  data:\n  - name: Mobile Sync Applications\n\
  \    description: Sync data between a CouchDB server and PouchDB in mobile/browser apps, supporting offline-first user experiences.\n  - name: Content Management\n    description: Store and retrieve rich JSON documents for CMS, blogs, catalogs, and document management systems.\n  - name: IoT Data Collection\n    description: Edge devices write data locally to CouchDB and replicate to central servers when connected.\n  - name: Multi-Region Replication\n    description: Replicate database contents across geographic regions for low-latency reads and disaster recovery.\n  - name: User Data Storage\n    description: Per-user database pattern for storing isolated user data with built-in CouchDB authentication.\n  - name: Event Sourcing\n    description: Use the changes feed as an event stream for event-driven architectures and audit logging.\n- type: Integrations\n  data:\n  - name: PouchDB\n    description: Browser and Node.js database that syncs with CouchDB via the Couch Replication Protocol.\n\
  \  - name: IBM Cloudant\n    description: IBM Cloudant is a fully managed cloud database service based on Apache CouchDB, API-compatible.\n  - name: Docker\n    description: Official CouchDB Docker images for container-based deployments.\n  - name: Kubernetes / Helm\n    description: Official Helm chart for deploying CouchDB clusters on Kubernetes.\n  - name: Apache Kafka\n    description: CouchDB changes feed can be consumed and bridged to Kafka for event streaming pipelines.\n  - name: Nginx / Load Balancers\n    description: CouchDB clusters are typically fronted by Nginx or HAProxy for SSL termination and load balancing.\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/rules/apache-couchdb-spectral-rules.yml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/capabilities/couchdb-document-management.yaml\n  title: CouchDB Document Management\n- type: Vocabulary\n\
  \  url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/vocabulary/apache-couchdb-vocabulary.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/apis.yml
tags:
- Apache
- Database
- Document Store
- JSON
- NoSQL
- Open Source
- Replication
- REST
url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/apis.yml
use_cases:
- description: Sync data between a CouchDB server and PouchDB in mobile/browser apps, supporting offline-first user experiences.
  name: Mobile Sync Applications
- description: Store and retrieve rich JSON documents for CMS, blogs, catalogs, and document management systems.
  name: Content Management
- description: Edge devices write data locally to CouchDB and replicate to central servers when connected.
  name: IoT Data Collection
- description: Replicate database contents across geographic regions for low-latency reads and disaster recovery.
  name: Multi-Region Replication
- description: Per-user database pattern for storing isolated user data with built-in CouchDB authentication.
  name: User Data Storage
- description: Use the changes feed as an event stream for event-driven architectures and audit logging.
  name: Event Sourcing
---
