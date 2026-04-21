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
