---
api_count: 4
api_specs:
- filename: client-server
  format: yaml
  label: Synapse Client-Server API
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/matrix-org/matrix-spec/tree/main/data/api/client-server
- filename: server-server
  format: yaml
  label: Synapse Server-Server API
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/matrix-org/matrix-spec/tree/main/data/api/server-server
apis:
- description: RESTful API for client applications to interact with the Matrix homeserver, enabling messaging, room management, user authentication, and real-time events.
  name: Synapse Client-Server API
  slug: ''
- description: Federation API allowing different Matrix homeservers to communicate with each other, enabling decentralized messaging across servers.
  name: Synapse Server-Server API
  slug: ''
- description: Administrative API for managing the Synapse homeserver, including user management, room administration, server configuration, and monitoring.
  name: Synapse Admin API
  slug: ''
- description: API for integrating application services (bridges and bots) with the Matrix homeserver.
  name: Synapse Application Service API
  slug: ''
common:
- title: ''
  type: GitHub
  url: https://github.com/matrix-org/synapse
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
created: '2024-01-01'
description: An open-source Matrix homeserver implementation that provides decentralized, secure communication services including real-time messaging, voice/video calls, and collaboration features.
features: []
image: https://matrix.org/images/matrix-logo.svg
integrations: []
layout: provider
modified: '2026-03-16'
name: Synapse
skills: []
slug: synapse
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Synapse\ndescription: An open-source Matrix homeserver implementation that provides decentralized, secure communication services including real-time messaging, voice/video calls, and collaboration features.\nimage: https://matrix.org/images/matrix-logo.svg\nurl: https://matrix-org.github.io/synapse/\ncreated: '2024-01-01'\nmodified: '2026-03-16'\napis:\n  - name: Synapse Client-Server API\n    description: RESTful API for client applications to interact with the Matrix homeserver, enabling messaging, room management, user authentication, and real-time events.\n    image: https://matrix.org/images/matrix-logo.svg\n    humanURL: https://spec.matrix.org/latest/client-server-api/\n    baseURL: https://matrix.example.com/_matrix/client\n    tags:\n      - Chat\n      - Collaboration\n      - Messaging\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://spec.matrix.org/latest/client-server-api/\n      - type: OpenAPI\n        url: https://github.com/matrix-org/matrix-spec/tree/main/data/api/client-server\n\
  \    contact:\n      - FN: Matrix.org Team\n        email: support@matrix.org\n        url: https://matrix.org/support/\n  - name: Synapse Server-Server API\n    description: Federation API allowing different Matrix homeservers to communicate with each other, enabling decentralized messaging across servers.\n    image: https://matrix.org/images/matrix-logo.svg\n    humanURL: https://spec.matrix.org/latest/server-server-api/\n    baseURL: https://matrix.example.com/_matrix/federation\n    tags:\n      - Decentralized\n      - Federation\n      - Server-To-Server\n    properties:\n      - type: Documentation\n        url: https://spec.matrix.org/latest/server-server-api/\n      - type: OpenAPI\n        url: https://github.com/matrix-org/matrix-spec/tree/main/data/api/server-server\n  - name: Synapse Admin API\n    description: Administrative API for managing the Synapse homeserver, including user management, room administration, server configuration, and monitoring.\n    image: https://matrix.org/images/matrix-logo.svg\n\
  \    humanURL: https://matrix-org.github.io/synapse/latest/usage/administration/admin_api/\n    baseURL: https://matrix.example.com/_synapse/admin\n    tags:\n      - Administration\n      - Management\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://matrix-org.github.io/synapse/latest/usage/administration/admin_api/\n      - type: GitHub\n        url: https://github.com/matrix-org/synapse/tree/develop/docs/admin_api\n  - name: Synapse Application Service API\n    description: API for integrating application services (bridges and bots) with the Matrix homeserver.\n    image: https://matrix.org/images/matrix-logo.svg\n    humanURL: https://spec.matrix.org/latest/application-service-api/\n    baseURL: https://matrix.example.com/_matrix/app\n    tags:\n      - Application-Services\n      - Bots\n      - Bridges\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://spec.matrix.org/latest/application-service-api/\ncommon:\n\
  \  - type: GitHub\n    url: https://github.com/matrix-org/synapse\n  - type: Documentation\n    url: https://matrix-org.github.io/synapse/latest/\n  - type: Getting Started\n    url: https://matrix-org.github.io/synapse/latest/setup/installation.html\n  - type: Authentication\n    url: https://matrix-org.github.io/synapse/latest/usage/configuration/config_documentation.html#authentication\n  - type: Rate Limits\n    url: https://matrix-org.github.io/synapse/latest/usage/configuration/config_documentation.html#ratelimiting\n  - type: Changelog\n    url: https://github.com/matrix-org/synapse/blob/develop/CHANGES.md\n  - type: License\n    url: https://github.com/matrix-org/synapse/blob/develop/LICENSE\nmaintainers:\n  - FN: Matrix.org Foundation\n    email: support@matrix.org\n    url: https://matrix.org\ntags:\n  - Chat\n  - Collaboration\n  - Decentralized\n  - Federation\n  - Matrix\n  - Messaging\n  - Open-Source\n  - Real-Time\n"
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
url: https://matrix-org.github.io/synapse/
use_cases: []
---
