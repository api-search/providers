---
api_count: 2
api_specs:
- filename: apache-james-webadmin-rest-api.yaml
  format: yaml
  label: Apache James WebAdmin REST API
  slug: webadmin-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-james/refs/heads/main/openapi/apache-james-webadmin-rest-api.yaml
apis:
- description: The James WebAdmin API provides REST endpoints for managing domains, users, mailboxes, mail repositories, mail queues, quotas, drop lists, and async tasks. It is the primary management interface for J
  name: Apache James WebAdmin REST API
  slug: webadmin-rest-api
- description: The JMAP (JSON Meta Application Protocol) implementation in James provides a modern, efficient email protocol for synchronizing messages, mailboxes, contacts, and calendars for email clients.
  name: Apache James JMAP API
  slug: jmap-api
capabilities:
- description: Workflow capability for mail server administrators to manage domains, users, mailboxes, and monitor tasks in Apache James.
  name: Apache James Mail Server Management
  slug: mail-server-management
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/james-project
- title: ''
  type: Documentation
  url: https://james.apache.org/documentation.html
- title: ''
  type: GettingStarted
  url: https://james.apache.org/server/quick-start.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Blog
  url: https://james.apache.org/blog/
- title: ''
  type: Versioning
  url: https://james.apache.org/download.cgi
- title: ''
  type: SpectralRules
  url: rules/apache-james-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-james-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/mail-server-management.yaml
created: '2026-03-16'
description: Apache James (Java Apache Mail Enterprise Server) is a portable and enterprise-ready mail server built entirely in Java. It implements SMTP, IMAP, POP3, and JMAP protocols and provides a modular architecture with a comprehensive administration REST API and Cassandra-backed distributed deployment.
features:
- description: Full SMTP server implementation with TLS, DKIM, SPF, and DMARC support.
  name: SMTP Server
- description: IMAP4 server with full RFC compliance for email client access.
  name: IMAP Server
- description: Modern JMAP protocol implementation for efficient email synchronization.
  name: JMAP Support
- description: HTTP REST API for complete server administration without downtime.
  name: WebAdmin REST API
- description: Cassandra-backed distributed deployment for high availability.
  name: Distributed Architecture
- description: Pluggable architecture supporting custom protocols, storage, and authentication.
  name: Modular Design
- description: Persistent mail queuing with configurable retry strategies.
  name: Mail Queuing
- description: Per-user, per-domain, and global mailbox and message quota enforcement.
  name: Quota Management
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Distributed mail storage backend for high availability deployments.
  name: Apache Cassandra
- description: Event bus integration for distributed James deployments.
  name: Apache Kafka
- description: AMQP message queue for inter-node communication.
  name: RabbitMQ
- description: Full-text mail search indexing via Elasticsearch integration.
  name: Elasticsearch/OpenSearch
- description: LDAP authentication and directory integration for user management.
  name: OpenLDAP
jsonld:
- class_count: 9
  name: Apache James Webadmin Rest Api Context
  property_count: 19
  slug: apache-james-webadmin-rest-api-context
layout: provider
modified: '2026-04-19'
name: Apache James
rules:
- name: Apache James API Rules
  rule_count: 20
  severity_counts:
    error: 9
    hint: 0
    info: 4
    warn: 7
  slug: apache-james-spectral-rules
skills: []
slug: apache-james
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-james\nname: Apache James\ndescription: >-\n  Apache James (Java Apache Mail Enterprise Server) is a portable and enterprise-ready mail server built entirely in Java. It implements SMTP, IMAP, POP3, and JMAP protocols and provides a modular architecture with a comprehensive administration REST API and Cassandra-backed distributed deployment.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Email\n  - IMAP\n  - Java\n  - JMAP\n  - Mail Server\n  - Open Source\n  - SMTP\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-james/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-james:webadmin-rest-api\n    name: Apache James WebAdmin REST API\n    description: >-\n      The James WebAdmin API provides REST endpoints for managing domains, users, mailboxes, mail repositories, mail\
  \ queues, quotas, drop lists, and async tasks. It is the primary management interface for James server instances.\n    humanURL: https://james.apache.org/server/manage-webadmin.html\n    tags:\n      - Administration\n      - Email\n      - REST\n    properties:\n      - type: Documentation\n        url: https://james.apache.org/server/manage-webadmin.html\n      - type: OpenAPI\n        url: openapi/apache-james-webadmin-rest-api.yaml\n\n  - aid: apache-james:jmap-api\n    name: Apache James JMAP API\n    description: >-\n      The JMAP (JSON Meta Application Protocol) implementation in James provides a modern, efficient email protocol for synchronizing messages, mailboxes, contacts, and calendars for email clients.\n    humanURL: https://james.apache.org/server/rfcs-compliance.html\n    tags:\n      - Email\n      - JMAP\n      - JSON\n    properties:\n      - type: Documentation\n        url: https://james.apache.org/server/rfcs-compliance.html\n\ncommon:\n  - type: GitHubOrganization\n\
  \    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/james-project\n  - type: Documentation\n    url: https://james.apache.org/documentation.html\n  - type: GettingStarted\n    url: https://james.apache.org/server/quick-start.html\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Blog\n    url: https://james.apache.org/blog/\n  - type: Versioning\n    url: https://james.apache.org/download.cgi\n  - type: SpectralRules\n    url: rules/apache-james-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-james-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/mail-server-management.yaml\n  - type: Features\n    data:\n      - name: SMTP Server\n        description: Full SMTP server implementation with TLS, DKIM, SPF, and DMARC support.\n      - name: IMAP Server\n        description: IMAP4 server with full RFC compliance for email client access.\n      - name: JMAP Support\n\
  \        description: Modern JMAP protocol implementation for efficient email synchronization.\n      - name: WebAdmin REST API\n        description: HTTP REST API for complete server administration without downtime.\n      - name: Distributed Architecture\n        description: Cassandra-backed distributed deployment for high availability.\n      - name: Modular Design\n        description: Pluggable architecture supporting custom protocols, storage, and authentication.\n      - name: Mail Queuing\n        description: Persistent mail queuing with configurable retry strategies.\n      - name: Quota Management\n        description: Per-user, per-domain, and global mailbox and message quota enforcement.\n  - type: UseCases\n    data:\n      - name: Enterprise Mail Server\n        description: Deploy a full-featured enterprise mail server with SMTP, IMAP, and JMAP.\n      - name: Mail Server Migration\n        description: Migrate from other mail servers with full protocol compatibility.\n\
  \      - name: Automated Email Processing\n        description: Build automated email pipelines using James mailet and matcher APIs.\n      - name: High-Availability Mail\n        description: Deploy distributed James clusters with Cassandra and RabbitMQ for HA.\n  - type: Integrations\n    data:\n      - name: Apache Cassandra\n        description: Distributed mail storage backend for high availability deployments.\n      - name: Apache Kafka\n        description: Event bus integration for distributed James deployments.\n      - name: RabbitMQ\n        description: AMQP message queue for inter-node communication.\n      - name: Elasticsearch/OpenSearch\n        description: Full-text mail search indexing via Elasticsearch integration.\n      - name: OpenLDAP\n        description: LDAP authentication and directory integration for user management.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-james/refs/heads/main/apis.yml
tags:
- Email
- IMAP
- Java
- JMAP
- Mail Server
- Open Source
- SMTP
url: https://raw.githubusercontent.com/api-evangelist/apache-james/refs/heads/main/apis.yml
use_cases:
- description: Deploy a full-featured enterprise mail server with SMTP, IMAP, and JMAP.
  name: Enterprise Mail Server
- description: Migrate from other mail servers with full protocol compatibility.
  name: Mail Server Migration
- description: Build automated email pipelines using James mailet and matcher APIs.
  name: Automated Email Processing
- description: Deploy distributed James clusters with Cassandra and RabbitMQ for HA.
  name: High-Availability Mail
---
