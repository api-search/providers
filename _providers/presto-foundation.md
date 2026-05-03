---
api_count: 2
apis:
- description: The Presto Client REST API is the HTTP protocol used by Presto clients to submit SQL queries to a Presto coordinator and stream back results. It centers on POST /v1/statement to submit a query, GET on
  name: Presto Client REST API
  slug: presto-client-rest-api
- description: The Presto Coordinator REST API exposes resources for inspecting and managing a running Presto cluster, including Node, Query, Stage, Statement, and Task resources. These endpoints are served by the c
  name: Presto Coordinator REST API
  slug: presto-coordinator-rest-api
common:
- title: ''
  type: Portal
  url: https://prestodb.io/
- title: ''
  type: Documentation
  url: https://prestodb.io/docs/current/
- title: ''
  type: Foundation
  url: https://prestodb.io/foundation/
- title: ''
  type: Blog
  url: https://prestodb.io/blog/
- title: ''
  type: Community
  url: https://prestodb.io/community/
- title: ''
  type: Events
  url: https://prestodb.io/events/
- title: ''
  type: Resources
  url: https://prestodb.io/resources/
- title: ''
  type: GitHub Organization
  url: https://github.com/prestodb
- title: ''
  type: Slack
  url: https://communityinviter.com/apps/prestodb/prestodb
- title: ''
  type: Twitter
  url: https://twitter.com/prestodb
- title: ''
  type: YouTube
  url: https://www.youtube.com/c/PrestoDB
- title: ''
  type: Linux Foundation
  url: https://www.linuxfoundation.org/projects/case-studies/presto/
created: '2026-03-16'
description: The Presto Foundation is a Linux Foundation project supporting Presto, an open source distributed SQL query engine for big data analytics. Founded by Facebook (Meta), Uber, Twitter, and Alibaba, Presto enables interactive analytics across diverse data sources at massive scale, with a vendor-neutral governance model and an active ecosystem of contributors and integrations.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Presto Foundation
skills: []
slug: presto-foundation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: presto-foundation\nname: Presto Foundation\ndescription: >-\n  The Presto Foundation is a Linux Foundation project supporting Presto, an\n  open source distributed SQL query engine for big data analytics. Founded by\n  Facebook (Meta), Uber, Twitter, and Alibaba, Presto enables interactive\n  analytics across diverse data sources at massive scale, with a vendor-neutral\n  governance model and an active ecosystem of contributors and integrations.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Big Data\n  - Distributed SQL\n  - Linux Foundation\n  - Open Source\n  - Query Engine\n  - SQL\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/presto-foundation/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: presto-foundation:presto-client-rest-api\n    name: Presto Client REST API\n\
  \    description: >-\n      The Presto Client REST API is the HTTP protocol used by Presto clients to\n      submit SQL queries to a Presto coordinator and stream back results. It\n      centers on POST /v1/statement to submit a query, GET on the returned\n      nextUri to fetch subsequent result batches, and DELETE on nextUri to\n      cancel a running query. Session context such as user, source, catalog,\n      schema, time zone, and language is conveyed through X-Presto-* headers,\n      and supports authentication mechanisms including Kerberos, LDAP,\n      password files, OAuth 2.0, and custom authenticators.\n    humanURL: https://prestodb.io/docs/current/develop/client-protocol.html\n    tags:\n      - Analytics\n      - Big Data\n      - Client Protocol\n      - REST API\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://prestodb.io/docs/current/develop/client-protocol.html\n      - type: REST API Reference\n        url: https://prestodb.io/docs/current/rest.html\n\
  \      - type: GitHub Repository\n        url: https://github.com/prestodb/presto\n  - aid: presto-foundation:presto-coordinator-rest-api\n    name: Presto Coordinator REST API\n    description: >-\n      The Presto Coordinator REST API exposes resources for inspecting and\n      managing a running Presto cluster, including Node, Query, Stage,\n      Statement, and Task resources. These endpoints are served by the\n      coordinator process and are used by clients, monitoring tools, and the\n      Presto worker protocol to coordinate distributed query execution and\n      observe cluster health.\n    humanURL: https://prestodb.io/docs/current/rest.html\n    tags:\n      - Analytics\n      - Big Data\n      - Cluster Management\n      - REST API\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://prestodb.io/docs/current/rest.html\n      - type: Node Resource\n        url: https://prestodb.io/docs/current/rest/node.html\n      - type: Query Resource\n      \
  \  url: https://prestodb.io/docs/current/rest/query.html\n      - type: Stage Resource\n        url: https://prestodb.io/docs/current/rest/stage.html\n      - type: Statement Resource\n        url: https://prestodb.io/docs/current/rest/statement.html\n      - type: Task Resource\n        url: https://prestodb.io/docs/current/rest/task.html\ncommon:\n  - type: Portal\n    url: https://prestodb.io/\n  - type: Documentation\n    url: https://prestodb.io/docs/current/\n  - type: Foundation\n    url: https://prestodb.io/foundation/\n  - type: Blog\n    url: https://prestodb.io/blog/\n  - type: Community\n    url: https://prestodb.io/community/\n  - type: Events\n    url: https://prestodb.io/events/\n  - type: Resources\n    url: https://prestodb.io/resources/\n  - type: GitHub Organization\n    url: https://github.com/prestodb\n  - type: Slack\n    url: https://communityinviter.com/apps/prestodb/prestodb\n  - type: Twitter\n    url: https://twitter.com/prestodb\n  - type: YouTube\n    url:\
  \ https://www.youtube.com/c/PrestoDB\n  - type: Linux Foundation\n    url: https://www.linuxfoundation.org/projects/case-studies/presto/\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/presto-foundation/refs/heads/main/apis.yml
tags:
- Analytics
- Big Data
- Distributed SQL
- Linux Foundation
- Open Source
- Query Engine
- SQL
url: https://raw.githubusercontent.com/api-evangelist/presto-foundation/refs/heads/main/apis.yml
use_cases: []
---
