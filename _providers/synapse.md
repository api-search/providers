---
api_count: 4
api_specs:
- filename: client-server
  format: yaml
  label: Synapse Client-Server API
  slug: synapse-client-server-api
  spec_type: OpenAPI
  url: https://github.com/matrix-org/matrix-spec/tree/main/data/api/client-server
- filename: server-server
  format: yaml
  label: Synapse Server-Server API
  slug: synapse-server-server-api
  spec_type: OpenAPI
  url: https://github.com/matrix-org/matrix-spec/tree/main/data/api/server-server
- filename: synapse-admin-api-openapi.yml
  format: yaml
  label: Synapse Admin API
  slug: synapse-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/synapse/refs/heads/main/openapi/synapse-admin-api-openapi.yml
apis:
- description: RESTful API for Matrix client applications to interact with the homeserver, enabling real-time messaging, room management, user authentication, event synchronization, and media uploads. Follows the Ma
  name: Synapse Client-Server API
  slug: synapse-client-server-api
- description: Federation API enabling different Matrix homeservers to communicate with each other, supporting decentralized messaging, event exchange, and room state synchronization across server boundaries.
  name: Synapse Server-Server API
  slug: synapse-server-server-api
- description: 'Administrative REST API for managing the Synapse homeserver. Provides server administrators with endpoints for user management, room administration, media management, federation control, registration '
  name: Synapse Admin API
  slug: synapse-admin-api
- description: API for integrating application services (bridges and bots) with the Matrix homeserver. Allows third-party applications to handle namespaced user IDs and room aliases, enabling Matrix bridges for IRC,
  name: Synapse Application Service API
  slug: synapse-application-service-api
capabilities:
- description: 'Workflow capability for administering a Synapse Matrix homeserver. Enables server administrators to manage users, rooms, registration, federation, and monitor server health through a unified REST and '
  name: Synapse Homeserver Administration
  slug: homeserver-administration
common:
- title: ''
  type: GitHub
  url: https://github.com/matrix-org/synapse
- title: ''
  type: GitHub
  url: https://github.com/element-hq/synapse
- title: ''
  type: Documentation
  url: https://matrix-org.github.io/synapse/latest/
- title: ''
  type: Getting Started
  url: https://matrix-org.github.io/synapse/latest/setup/installation.html
- title: ''
  type: Authentication
  url: https://matrix-org.github.io/synapse/latest/usage/configuration/config_documentation.html#authentication
- title: ''
  type: Rate Limits
  url: https://matrix-org.github.io/synapse/latest/usage/configuration/config_documentation.html#ratelimiting
- title: ''
  type: Changelog
  url: https://github.com/matrix-org/synapse/blob/develop/CHANGES.md
- title: ''
  type: License
  url: https://github.com/matrix-org/synapse/blob/develop/LICENSE
- title: ''
  type: Docker
  url: https://hub.docker.com/r/matrixdotorg/synapse
- title: ''
  type: PyPI
  url: https://pypi.org/project/matrix-synapse/
- title: ''
  type: Matrix Spec
  url: https://spec.matrix.org/latest/
created: '2026-05-03'
description: Synapse is the reference Matrix homeserver implementation maintained by Element (formerly by the Matrix.org Foundation). Written in Python and Rust, it implements the Matrix open standard for secure, decentralized real-time communication. Synapse powers thousands of deployments worldwide and provides Client-Server, Server-Server (federation), Application Service, Identity Service, and Admin APIs. Since version 1.99, maintained by Element under AGPL-3.0.
features: []
image: https://matrix.org/images/matrix-logo.svg
integrations: []
jsonld:
- class_count: 0
  name: Synapse Context
  property_count: 31
  slug: synapse-context
layout: provider
modified: '2026-05-03'
name: Synapse
rules:
- name: Synapse API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 2
    info: 0
    warn: 4
  slug: synapse-rules
skills: []
slug: synapse
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: synapse\nname: Synapse\ndescription: >-\n  Synapse is the reference Matrix homeserver implementation maintained by\n  Element (formerly by the Matrix.org Foundation). Written in Python and Rust,\n  it implements the Matrix open standard for secure, decentralized real-time\n  communication. Synapse powers thousands of deployments worldwide and provides\n  Client-Server, Server-Server (federation), Application Service, Identity\n  Service, and Admin APIs. Since version 1.99, maintained by Element under AGPL-3.0.\nimage: https://matrix.org/images/matrix-logo.svg\nurl: https://raw.githubusercontent.com/api-evangelist/synapse/refs/heads/main/apis.yml\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: synapse:synapse-client-server-api\n    name: Synapse Client-Server API\n    description: >-\n      RESTful API for Matrix client applications to interact with the homeserver,\n      enabling real-time messaging, room management, user authentication,\n\
  \      event synchronization, and media uploads. Follows the Matrix Client-Server\n      specification.\n    image: https://matrix.org/images/matrix-logo.svg\n    humanURL: https://spec.matrix.org/latest/client-server-api/\n    baseURL: https://matrix.example.com/_matrix/client\n    tags:\n      - Chat\n      - Client\n      - Collaboration\n      - Matrix\n      - Messaging\n      - Real-Time\n      - Rooms\n    properties:\n      - type: Documentation\n        url: https://spec.matrix.org/latest/client-server-api/\n      - type: OpenAPI\n        url: https://github.com/matrix-org/matrix-spec/tree/main/data/api/client-server\n  - aid: synapse:synapse-server-server-api\n    name: Synapse Server-Server API\n    description: >-\n      Federation API enabling different Matrix homeservers to communicate with\n      each other, supporting decentralized messaging, event exchange, and\n      room state synchronization across server boundaries.\n    image: https://matrix.org/images/matrix-logo.svg\n\
  \    humanURL: https://spec.matrix.org/latest/server-server-api/\n    baseURL: https://matrix.example.com/_matrix/federation\n    tags:\n      - Decentralized\n      - Federation\n      - Matrix\n      - Server-To-Server\n    properties:\n      - type: Documentation\n        url: https://spec.matrix.org/latest/server-server-api/\n      - type: OpenAPI\n        url: https://github.com/matrix-org/matrix-spec/tree/main/data/api/server-server\n  - aid: synapse:synapse-admin-api\n    name: Synapse Admin API\n    description: >-\n      Administrative REST API for managing the Synapse homeserver. Provides\n      server administrators with endpoints for user management, room\n      administration, media management, federation control, registration tokens,\n      background updates, event reports, and server statistics.\n    image: https://matrix.org/images/matrix-logo.svg\n    humanURL: https://matrix-org.github.io/synapse/latest/usage/administration/admin_api/\n    baseURL: https://matrix.example.com/_synapse/admin\n\
  \    tags:\n      - Administration\n      - Management\n      - Matrix\n      - Monitoring\n      - Users\n    properties:\n      - type: Documentation\n        url: https://matrix-org.github.io/synapse/latest/usage/administration/admin_api/\n      - type: OpenAPI\n        url: openapi/synapse-admin-api-openapi.yml\n      - type: GitHub\n        url: https://github.com/matrix-org/synapse/tree/develop/docs/admin_api\n  - aid: synapse:synapse-application-service-api\n    name: Synapse Application Service API\n    description: >-\n      API for integrating application services (bridges and bots) with the\n      Matrix homeserver. Allows third-party applications to handle namespaced\n      user IDs and room aliases, enabling Matrix bridges for IRC, Slack,\n      Telegram, and other platforms.\n    image: https://matrix.org/images/matrix-logo.svg\n    humanURL: https://spec.matrix.org/latest/application-service-api/\n    baseURL: https://matrix.example.com/_matrix/app\n    tags:\n      - Application-Services\n\
  \      - Bots\n      - Bridges\n      - Integration\n      - Matrix\n    properties:\n      - type: Documentation\n        url: https://spec.matrix.org/latest/application-service-api/\ncommon:\n  - type: GitHub\n    url: https://github.com/matrix-org/synapse\n  - type: GitHub\n    url: https://github.com/element-hq/synapse\n  - type: Documentation\n    url: https://matrix-org.github.io/synapse/latest/\n  - type: Getting Started\n    url: https://matrix-org.github.io/synapse/latest/setup/installation.html\n  - type: Authentication\n    url: https://matrix-org.github.io/synapse/latest/usage/configuration/config_documentation.html#authentication\n  - type: Rate Limits\n    url: https://matrix-org.github.io/synapse/latest/usage/configuration/config_documentation.html#ratelimiting\n  - type: Changelog\n    url: https://github.com/matrix-org/synapse/blob/develop/CHANGES.md\n  - type: License\n    url: https://github.com/matrix-org/synapse/blob/develop/LICENSE\n  - type: Docker\n    url: https://hub.docker.com/r/matrixdotorg/synapse\n\
  \  - type: PyPI\n    url: https://pypi.org/project/matrix-synapse/\n  - type: Matrix Spec\n    url: https://spec.matrix.org/latest/\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\ntags:\n  - Chat\n  - Collaboration\n  - Decentralized\n  - Federation\n  - Matrix\n  - Messaging\n  - Open-Source\n  - Real-Time\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/synapse/refs/heads/main/apis.yml
tags:
- Chat
- Collaboration
- Decentralized
- Federation
- Matrix
- Messaging
- Open-Source
- Real-Time
url: https://raw.githubusercontent.com/api-evangelist/synapse/refs/heads/main/apis.yml
use_cases: []
---
