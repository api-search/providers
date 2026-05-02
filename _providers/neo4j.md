---
api_count: 8
api_specs:
- filename: neo4j-http-api-openapi.yml
  format: yaml
  label: Neo4j HTTP API
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/neo4j/refs/heads/main/openapi/neo4j-http-api-openapi.yml
- filename: neo4j-query-api-openapi.yml
  format: yaml
  label: Neo4j Query API
  slug: query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/neo4j/refs/heads/main/openapi/neo4j-query-api-openapi.yml
- filename: neo4j-aura-api-openapi.yml
  format: yaml
  label: Neo4j Aura API
  slug: aura-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/neo4j/refs/heads/main/openapi/neo4j-aura-api-openapi.yml
apis:
- description: The Neo4j HTTP API allows developers to execute Cypher queries against a Neo4j database through HTTP requests. It supports both implicit transactions, where the API handles transaction management auto
  name: Neo4j HTTP API
  slug: http-api
- description: The Neo4j Query API enables the execution of Cypher statements against a Neo4j server through HTTP requests. It provides a streamlined interface for running graph database queries, supporting both sel
  name: Neo4j Query API
  slug: query-api
- description: 'The Neo4j Aura API provides programmatic access to manage Neo4j AuraDB cloud database instances. It supports operations across three primary resources: instances, tenants, and snapshots. Developers au'
  name: Neo4j Aura API
  slug: aura-api
- description: The Neo4j GraphQL Library is an open source JavaScript library that enables rapid development of GraphQL APIs backed by a Neo4j graph database. It automatically generates a single optimized Cypher que
  name: Neo4j GraphQL Library
  slug: graphql-library
- description: The Neo4j Bolt Protocol is a binary application protocol designed for efficient execution of database queries using the Cypher query language. It operates over TCP or WebSocket connections on the defa
  name: Neo4j Bolt Protocol
  slug: bolt-protocol
- description: The Neo4j Python Driver is the official library for interacting with Neo4j graph databases from Python applications. It communicates using the Bolt protocol and supports both single instance and clust
  name: Neo4j Python Driver
  slug: python-driver
- description: The Neo4j Java Driver is the official library for connecting Java applications to Neo4j graph databases. Distributed via Maven, it uses the Bolt protocol for network communication and supports both si
  name: Neo4j Java Driver
  slug: java-driver
- description: The Neo4j JavaScript Driver is the official library for interacting with Neo4j graph databases from JavaScript and Node.js applications. It uses the Bolt protocol for efficient communication and can b
  name: Neo4j JavaScript Driver
  slug: javascript-driver
common:
- title: ''
  type: Portal
  url: https://neo4j.com/developer/
- title: ''
  type: Documentation
  url: https://neo4j.com/docs/
- title: ''
  type: Website
  url: https://neo4j.com
- title: ''
  type: PrivacyPolicy
  url: https://neo4j.com/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://neo4j.com/terms/
- title: ''
  type: Support
  url: https://support.neo4j.com/
- title: ''
  type: Blog
  url: https://neo4j.com/blog/
- title: ''
  type: Login
  url: https://console.neo4j.io/
created: '2025-03-05'
description: Neo4j is the leading graph database platform, enabling developers to build applications powered by connected data. Their developer platform provides HTTP, Query, and Aura cloud APIs alongside official drivers for Python, Java, and JavaScript, as well as a GraphQL library for rapid API development backed by the Neo4j graph database.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Neo4J Context
  property_count: 7
  slug: neo4j-context
layout: provider
modified: '2026-04-28'
name: Neo4j
skills: []
slug: neo4j
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: neo4j\nname: Neo4j\ndescription: >-\n  Neo4j is the leading graph database platform, enabling developers to build\n  applications powered by connected data. Their developer platform provides\n  HTTP, Query, and Aura cloud APIs alongside official drivers for Python,\n  Java, and JavaScript, as well as a GraphQL library for rapid API development\n  backed by the Neo4j graph database.\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Graph Database\n  - Cypher\n  - Cloud\n  - GraphQL\n  - Drivers\n  - APIs\nurl: https://raw.githubusercontent.com/api-evangelist/neo4j/refs/heads/main/apis.yml\ncreated: '2025-03-05'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: neo4j:http-api\n    name: Neo4j HTTP API\n    description: >-\n      The Neo4j HTTP API allows developers to execute Cypher queries against\n      a Neo4j database through HTTP requests. It supports both implicit\n      transactions,\
  \ where the API handles transaction management\n      automatically, and explicit transactions, where developers control the\n      full transaction lifecycle including open, commit, and rollback\n      operations. By default the API uses port 7474 for HTTP and port 7473\n      for HTTPS on self-managed instances.\n    humanURL: https://neo4j.com/docs/http-api/current/\n    tags:\n      - Graph Database\n      - Cypher\n      - HTTP\n      - Transactions\n      - Database\n    properties:\n      - type: Documentation\n        url: https://neo4j.com/docs/http-api/current/\n      - type: OpenAPI\n        url: openapi/neo4j-http-api-openapi.yml\n  - aid: neo4j:query-api\n    name: Neo4j Query API\n    description: >-\n      The Neo4j Query API enables the execution of Cypher statements against\n      a Neo4j server through HTTP requests. It provides a streamlined\n      interface for running graph database queries, supporting both\n      self-managed and cloud-hosted Neo4j instances. The\
  \ Query API is\n      designed for applications that need to interact with Neo4j\n      programmatically and is particularly useful for languages where a\n      dedicated Neo4j driver is not available.\n    humanURL: https://neo4j.com/docs/query-api/current/\n    tags:\n      - Graph Database\n      - Cypher\n      - Query\n      - HTTP\n      - Database\n    properties:\n      - type: Documentation\n        url: https://neo4j.com/docs/query-api/current/\n      - type: OpenAPI\n        url: openapi/neo4j-query-api-openapi.yml\n  - aid: neo4j:aura-api\n    name: Neo4j Aura API\n    description: >-\n      The Neo4j Aura API provides programmatic access to manage Neo4j AuraDB\n      cloud database instances. It supports operations across three primary\n      resources: instances, tenants, and snapshots. Developers authenticate\n      using OAuth2 bearer tokens obtained through client credentials, and can\n      automate the provisioning, configuration, and management of their\n      cloud-hosted\
  \ Neo4j graph databases. The API is accessible through the\n      console.neo4j.io platform.\n    humanURL: https://neo4j.com/docs/aura/platform/api/specification/\n    tags:\n      - Cloud\n      - Graph Database\n      - Database Management\n      - Instances\n      - Snapshots\n    properties:\n      - type: Documentation\n        url: https://neo4j.com/docs/aura/platform/api/specification/\n      - type: OpenAPI\n        url: openapi/neo4j-aura-api-openapi.yml\n  - aid: neo4j:graphql-library\n    name: Neo4j GraphQL Library\n    description: >-\n      The Neo4j GraphQL Library is an open source JavaScript library that\n      enables rapid development of GraphQL APIs backed by a Neo4j graph\n      database. It automatically generates a single optimized Cypher query\n      for each GraphQL query or mutation, eliminating the N+1 problem common\n      in GraphQL implementations. The library supports schema-first\n      development and integrates with Neo4j AuraDB for cloud-hosted\n   \
  \   deployments, making it suitable for cross-platform and mobile\n      applications.\n    humanURL: https://neo4j.com/docs/graphql/current/\n    tags:\n      - GraphQL\n      - Graph Database\n      - JavaScript\n      - Low-Code\n      - API Development\n    properties:\n      - type: Documentation\n        url: https://neo4j.com/docs/graphql/current/\n  - aid: neo4j:bolt-protocol\n    name: Neo4j Bolt Protocol\n    description: >-\n      The Neo4j Bolt Protocol is a binary application protocol designed for\n      efficient execution of database queries using the Cypher query\n      language. It operates over TCP or WebSocket connections on the default\n      port 7687 and serves as the foundation for all official Neo4j drivers\n      including Java, Python, JavaScript, .NET, and Go. The protocol\n      supports both direct connections via the bolt:// scheme and routing\n      connections via bolt+routing:// for clustered deployments.\n    humanURL: https://neo4j.com/docs/bolt/current/bolt/\n\
  \    tags:\n      - Binary Protocol\n      - Graph Database\n      - Drivers\n      - Connectivity\n      - Networking\n    properties:\n      - type: Documentation\n        url: https://neo4j.com/docs/bolt/current/bolt/\n  - aid: neo4j:python-driver\n    name: Neo4j Python Driver\n    description: >-\n      The Neo4j Python Driver is the official library for interacting with\n      Neo4j graph databases from Python applications. It communicates using\n      the Bolt protocol and supports both single instance and clustered\n      database deployments. The driver is available on PyPI as the neo4j\n      package and provides a comprehensive API for session management,\n      transaction handling, and result processing.\n    humanURL: https://neo4j.com/docs/python-manual/current/\n    tags:\n      - Python\n      - SDK\n      - Driver\n      - Graph Database\n      - Bolt\n    properties:\n      - type: Documentation\n        url: https://neo4j.com/docs/python-manual/current/\n      - type:\
  \ Documentation\n        url: https://neo4j.com/docs/api/python-driver/current/\n  - aid: neo4j:java-driver\n    name: Neo4j Java Driver\n    description: >-\n      The Neo4j Java Driver is the official library for connecting Java\n      applications to Neo4j graph databases. Distributed via Maven, it uses\n      the Bolt protocol for network communication and supports both single\n      instance and clustered database configurations. The driver provides a\n      full API for managing connections, sessions, transactions, and query\n      results within Java applications.\n    humanURL: https://neo4j.com/docs/java-manual/current/\n    tags:\n      - Java\n      - SDK\n      - Driver\n      - Graph Database\n      - Bolt\n    properties:\n      - type: Documentation\n        url: https://neo4j.com/docs/java-manual/current/\n      - type: Documentation\n        url: https://neo4j.com/docs/api/java-driver/current/\n  - aid: neo4j:javascript-driver\n    name: Neo4j JavaScript Driver\n    description:\
  \ >-\n      The Neo4j JavaScript Driver is the official library for interacting\n      with Neo4j graph databases from JavaScript and Node.js applications.\n      It uses the Bolt protocol for efficient communication and can be\n      installed via npm. The driver supports both browser and server-side\n      environments and provides APIs for session management, transaction\n      control, and processing of query results from Neo4j databases.\n    humanURL: https://neo4j.com/docs/javascript-manual/current/\n    tags:\n      - JavaScript\n      - SDK\n      - Driver\n      - Graph Database\n      - Bolt\n      - Node.js\n    properties:\n      - type: Documentation\n        url: https://neo4j.com/docs/javascript-manual/current/\n      - type: Documentation\n        url: https://neo4j.com/docs/api/javascript-driver/current/\ncommon:\n  - type: Portal\n    url: https://neo4j.com/developer/\n  - type: Documentation\n    url: https://neo4j.com/docs/\n  - type: Website\n    url: https://neo4j.com\n\
  \  - type: PrivacyPolicy\n    url: https://neo4j.com/privacy-policy/\n  - type: TermsOfService\n    url: https://neo4j.com/terms/\n  - type: Support\n    url: https://support.neo4j.com/\n  - type: Blog\n    url: https://neo4j.com/blog/\n  - type: Login\n    url: https://console.neo4j.io/\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/neo4j/refs/heads/main/apis.yml
tags:
- Graph Database
- Cypher
- Cloud
- GraphQL
- Drivers
- APIs
url: https://raw.githubusercontent.com/api-evangelist/neo4j/refs/heads/main/apis.yml
use_cases: []
---
