---
api_count: 3
apis:
- description: The Fusio Backend API provides a REST interface to configure and manage all aspects of a Fusio API management instance. It covers operations, routes, schemas, actions, connections, apps, users, and ma
  name: Fusio Backend API
  slug: fusio-backend-api
- description: The Fusio Consumer API is used by the developer portal application and enables third-party developers to request access tokens, manage their apps, and interact with protected API endpoints. It provide
  name: Fusio Consumer API
  slug: fusio-consumer-api
- description: The Fusio Worker API enables executing API action logic in multiple programming languages by forwarding requests to external worker processes. Workers are implemented in the target language (JavaScrip
  name: Fusio Worker API
  slug: fusio-worker-api
common:
- title: ''
  type: Documentation
  url: https://docs.fusio-project.org/
- title: ''
  type: GettingStarted
  url: https://docs.fusio-project.org/docs/bootstrap
- title: ''
  type: Blog
  url: https://www.fusio-project.org/blog
- title: ''
  type: ChangeLog
  url: https://github.com/apioo/fusio/blob/master/CHANGELOG.md
- title: ''
  type: GitHubOrganization
  url: https://github.com/apioo
- title: ''
  type: GitHubRepository
  url: https://github.com/apioo/fusio
- title: ''
  type: Support
  url: https://discord.com/invite/eMrMgwsc6e
- title: ''
  type: Marketplace
  url: https://www.fusio-project.org/marketplace
- title: ''
  type: SDK
  url: https://docs.fusio-project.org/docs/backend/development/sdk
created: '2026-03-16'
description: Fusio is an open source API management platform which helps to build and manage REST APIs. It provides capabilities for creating, managing, and documenting APIs with a built-in developer portal, marketplace, and support for multiple programming languages through worker processes.
features:
- description: Route and manage incoming API requests with built-in rate limiting and authentication.
  name: API Gateway
- description: Self-service developer portal for API consumers to register, browse APIs, and manage access tokens.
  name: Developer Portal
- description: Execute API action logic in JavaScript, Python, Java, PHP, and other languages through worker processes.
  name: Multi-Language Workers
- description: Browse and install pre-built API actions and adapters from the Fusio marketplace.
  name: Marketplace
- description: Define and manage API request and response schemas using TypeSchema format.
  name: Schema Management
- description: Built-in OAuth2 server for securing APIs with token-based authentication.
  name: OAuth2 Authentication
- description: Configure per-app and per-user rate limits to protect API resources.
  name: Rate Limiting
- description: Define webhook subscriptions to notify consumers of events.
  name: Webhook Support
image: /assets/icons/fusio.png
integrations:
- description: Connect to MySQL and PostgreSQL databases as data sources for API endpoints.
  name: MySQL and PostgreSQL
- description: Use MongoDB as a NoSQL data source for API endpoints.
  name: MongoDB
- description: Integrate with Elasticsearch for search-powered API endpoints.
  name: Elasticsearch
- description: Use RabbitMQ for asynchronous message processing in API workflows.
  name: RabbitMQ
- description: Deploy Fusio and worker containers using Docker and Docker Compose.
  name: Docker
layout: provider
modified: '2026-04-18'
name: Fusio
skills: []
slug: fusio
solutions: []
source_filename: apis.yml
source_yaml: "aid: fusio\nname: Fusio\ndescription: >-\n  Fusio is an open source API management platform which helps to build and\n  manage REST APIs. It provides capabilities for creating, managing, and\n  documenting APIs with a built-in developer portal, marketplace, and support\n  for multiple programming languages through worker processes.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-16'\nmodified: '2026-04-18'\nposition: Consumer\ntags:\n  - API Management\n  - Open Source\n  - REST API\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/fusio/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: fusio:fusio-backend-api\n    name: Fusio Backend API\n    description: >-\n      The Fusio Backend API provides a REST interface to configure and manage\n      all aspects of a Fusio API management instance. It covers operations,\n      routes, schemas, actions, connections,\
  \ apps, users, and marketplace\n      resources used by the Fusio backend application.\n    humanURL: https://docs.fusio-project.org/docs/use_cases/api_product/\n    baseURL: https://www.fusio-project.org/\n    tags:\n      - Backend\n      - Configuration\n      - Management\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://docs.fusio-project.org/docs/use_cases/api_product/\n      - type: GitHubRepository\n        url: https://github.com/apioo/fusio\n  - aid: fusio:fusio-consumer-api\n    name: Fusio Consumer API\n    description: >-\n      The Fusio Consumer API is used by the developer portal application and\n      enables third-party developers to request access tokens, manage their\n      apps, and interact with protected API endpoints. It provides the\n      authentication and user management layer for API consumers.\n    humanURL: https://docs.fusio-project.org/docs/backend/consumer/user/\n    baseURL: https://www.fusio-project.org/\n    tags:\n\
  \      - Authentication\n      - Consumer\n      - Developer Portal\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://docs.fusio-project.org/docs/backend/consumer/user/\n      - type: APIReference\n        url: https://docs.fusio-project.org/docs/backend/consumer/app\n      - type: GitHubRepository\n        url: https://github.com/apioo/fusio\n  - aid: fusio:fusio-worker-api\n    name: Fusio Worker API\n    description: >-\n      The Fusio Worker API enables executing API action logic in multiple\n      programming languages by forwarding requests to external worker processes.\n      Workers are implemented in the target language (JavaScript, Python, Java,\n      PHP, etc.) and communicate with the Fusio core via a simple REST\n      interface, enabling serverless deployments.\n    humanURL: https://docs.fusio-project.org/docs/concepts/worker_api\n    baseURL: https://www.fusio-project.org/\n    tags:\n      - Multi-Language\n      - REST API\n     \
  \ - Serverless\n      - Worker\n    properties:\n      - type: Documentation\n        url: https://docs.fusio-project.org/docs/concepts/worker_api\n      - type: GitHubRepository\n        url: https://github.com/apioo/fusio-worker-php\ncommon:\n  - type: Documentation\n    url: https://docs.fusio-project.org/\n  - type: GettingStarted\n    url: https://docs.fusio-project.org/docs/bootstrap\n  - type: Blog\n    url: https://www.fusio-project.org/blog\n  - type: ChangeLog\n    url: https://github.com/apioo/fusio/blob/master/CHANGELOG.md\n  - type: GitHubOrganization\n    url: https://github.com/apioo\n  - type: GitHubRepository\n    url: https://github.com/apioo/fusio\n  - type: Support\n    url: https://discord.com/invite/eMrMgwsc6e\n  - type: Marketplace\n    url: https://www.fusio-project.org/marketplace\n  - type: SDK\n    url: https://docs.fusio-project.org/docs/backend/development/sdk\n  - type: Features\n    data:\n      - name: API Gateway\n        description: Route and manage incoming\
  \ API requests with built-in rate limiting and authentication.\n      - name: Developer Portal\n        description: Self-service developer portal for API consumers to register, browse APIs, and manage access tokens.\n      - name: Multi-Language Workers\n        description: Execute API action logic in JavaScript, Python, Java, PHP, and other languages through worker processes.\n      - name: Marketplace\n        description: Browse and install pre-built API actions and adapters from the Fusio marketplace.\n      - name: Schema Management\n        description: Define and manage API request and response schemas using TypeSchema format.\n      - name: OAuth2 Authentication\n        description: Built-in OAuth2 server for securing APIs with token-based authentication.\n      - name: Rate Limiting\n        description: Configure per-app and per-user rate limits to protect API resources.\n      - name: Webhook Support\n        description: Define webhook subscriptions to notify consumers of\
  \ events.\n  - type: UseCases\n    data:\n      - name: API Product Building\n        description: Build and publish API products with documentation, authentication, and developer onboarding.\n      - name: Microservices Gateway\n        description: Use Fusio as an API gateway in front of microservices for unified access control.\n      - name: Data Integration\n        description: Connect to databases and external APIs to build data integration endpoints.\n      - name: Serverless API Backend\n        description: Build API backends that execute logic in multiple languages without managing servers.\n  - type: Integrations\n    data:\n      - name: MySQL and PostgreSQL\n        description: Connect to MySQL and PostgreSQL databases as data sources for API endpoints.\n      - name: MongoDB\n        description: Use MongoDB as a NoSQL data source for API endpoints.\n      - name: Elasticsearch\n        description: Integrate with Elasticsearch for search-powered API endpoints.\n      -\
  \ name: RabbitMQ\n        description: Use RabbitMQ for asynchronous message processing in API workflows.\n      - name: Docker\n        description: Deploy Fusio and worker containers using Docker and Docker Compose.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fusio/refs/heads/main/apis.yml
tags:
- API Management
- Open Source
- REST API
url: https://raw.githubusercontent.com/api-evangelist/fusio/refs/heads/main/apis.yml
use_cases:
- description: Build and publish API products with documentation, authentication, and developer onboarding.
  name: API Product Building
- description: Use Fusio as an API gateway in front of microservices for unified access control.
  name: Microservices Gateway
- description: Connect to databases and external APIs to build data integration endpoints.
  name: Data Integration
- description: Build API backends that execute logic in multiple languages without managing servers.
  name: Serverless API Backend
---
