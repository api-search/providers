---
api_count: 2
apis:
- description: Connexion is a contract-first Python web framework that loads an OpenAPI specification and routes requests to Python handlers based on operationId. It performs request validation, parameter parsing, a
  name: Connexion Python Framework
  slug: framework
- description: Connexion 3 introduces a stack of pluggable ASGI middlewares that handle exceptions, server errors, lifespan, security, routing, request validation, response validation, Swagger UI, and context propag
  name: Connexion Middleware Stack
  slug: middleware
common:
- title: ''
  type: Website
  url: https://connexion.readthedocs.io/
- title: ''
  type: Documentation
  url: https://connexion.readthedocs.io/en/latest/quickstart.html
- title: ''
  type: GitHubRepository
  url: https://github.com/spec-first/connexion
- title: ''
  type: GitHub Organization
  url: https://github.com/spec-first
- title: ''
  type: Issue Tracker
  url: https://github.com/spec-first/connexion/issues
- title: ''
  type: Change Log
  url: https://github.com/spec-first/connexion/releases
- title: ''
  type: License
  url: https://github.com/spec-first/connexion/blob/main/LICENSE
- title: ''
  type: PyPI
  url: https://pypi.org/project/connexion/
created: '2026-03-25'
description: 'Connexion is an open source Python framework that automatically handles HTTP requests based on OpenAPI specifications. Connexion 3 provides AsyncApp, FlaskApp, and ConnexionMiddleware as primary entry points, with built-in routing, request and response validation, parameter parsing, security enforcement, content negotiation, error handling, lifespan, and Swagger UI integration. Connexion takes a contract-first, design-first approach: the OpenAPI specification is the source of truth and Python handlers are resolved from operationId or via configurable resolvers.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Connexion
skills: []
slug: connexion
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: connexion\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/connexion/refs/heads/main/apis.yml\nname: Connexion\nx-type: opensource\ndescription: >-\n  Connexion is an open source Python framework that automatically handles HTTP\n  requests based on OpenAPI specifications. Connexion 3 provides AsyncApp,\n  FlaskApp, and ConnexionMiddleware as primary entry points, with built-in\n  routing, request and response validation, parameter parsing, security\n  enforcement, content negotiation, error handling, lifespan, and Swagger UI\n  integration. Connexion takes a contract-first, design-first approach: the\n  OpenAPI specification is the source of truth and Python handlers are\n  resolved from operationId or via configurable resolvers.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Design\n  - ASGI\n  - Design-First\n  - Flask\n  - OpenAPI\n  - Python\n  - Validation\n  - WSGI\ncreated: '2026-03-25'\nmodified: '2026-04-28'\n\
  specificationVersion: '0.19'\napis:\n  - aid: connexion:framework\n    name: Connexion Python Framework\n    description: >-\n      Connexion is a contract-first Python web framework that loads an\n      OpenAPI specification and routes requests to Python handlers based on\n      operationId. It performs request validation, parameter parsing, and\n      response validation against the specification, with first-class\n      support for security schemes and Swagger UI.\n    humanURL: https://connexion.readthedocs.io/en/latest/\n    baseURL: https://connexion.readthedocs.io\n    tags:\n      - Framework\n      - OpenAPI\n      - Python\n      - Validation\n    properties:\n      - type: Documentation\n        url: https://connexion.readthedocs.io/en/latest/\n      - type: Documentation\n        url: https://connexion.readthedocs.io/en/latest/quickstart.html\n      - type: GitHubRepository\n        url: https://github.com/spec-first/connexion\n      - type: License\n        url: https://github.com/spec-first/connexion/blob/main/LICENSE\n\
  \      - type: Issue Tracker\n        url: https://github.com/spec-first/connexion/issues\n    x-features:\n      - AsyncApp, FlaskApp, and ConnexionMiddleware entry points\n      - Native ASGI server support and Flask compatibility\n      - Automatic routing from operationId via RestyResolver\n      - Request and response validation against OpenAPI\n      - Security middleware honoring OpenAPI security schemes\n      - Swagger UI mounted from the framework\n      - Pythonic snake_case parameter conversion\n      - Strict parameter validation modes\n    x-useCases:\n      - Build Python APIs from an OpenAPI 3.x specification\n      - Migrate Flask applications to a contract-first model\n      - Add request and response validation to an existing ASGI app\n      - Generate Swagger UI alongside your API automatically\n      - Compose multiple OpenAPI specifications under a single app\n  - aid: connexion:middleware\n    name: Connexion Middleware Stack\n    description: >-\n      Connexion\
  \ 3 introduces a stack of pluggable ASGI middlewares that\n      handle exceptions, server errors, lifespan, security, routing,\n      request validation, response validation, Swagger UI, and context\n      propagation. The middleware stack can be applied to any ASGI or\n      WSGI application via ConnexionMiddleware.\n    humanURL: https://connexion.readthedocs.io/en/latest/middleware.html\n    baseURL: https://connexion.readthedocs.io\n    tags:\n      - ASGI\n      - Middleware\n      - WSGI\n    properties:\n      - type: Documentation\n        url: https://connexion.readthedocs.io/en/latest/middleware.html\n      - type: Reference\n        url: https://github.com/spec-first/connexion/tree/main/connexion/middleware\n    x-features:\n      - Routing, security, request, and response validation middleware\n      - SwaggerUIMiddleware for interactive docs\n      - LifespanMiddleware for startup and shutdown hooks\n      - ContextMiddleware to propagate request context\n    x-useCases:\n\
  \      - Add Connexion validation to FastAPI or Starlette\n      - Wrap an existing WSGI application without rewriting handlers\n      - Customize the middleware stack for a specific deployment\ncommon:\n  - type: Website\n    url: https://connexion.readthedocs.io/\n  - type: Documentation\n    url: https://connexion.readthedocs.io/en/latest/quickstart.html\n  - type: GitHubRepository\n    url: https://github.com/spec-first/connexion\n  - type: GitHub Organization\n    url: https://github.com/spec-first\n  - type: Issue Tracker\n    url: https://github.com/spec-first/connexion/issues\n  - type: Change Log\n    url: https://github.com/spec-first/connexion/releases\n  - type: License\n    url: https://github.com/spec-first/connexion/blob/main/LICENSE\n  - type: PyPI\n    url: https://pypi.org/project/connexion/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/connexion/refs/heads/main/apis.yml
tags:
- API Design
- ASGI
- Design-First
- Flask
- OpenAPI
- Python
- Validation
- WSGI
url: https://raw.githubusercontent.com/api-evangelist/connexion/refs/heads/main/apis.yml
use_cases: []
---
