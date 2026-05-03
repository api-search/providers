---
api_count: 4
apis:
- description: 'Representational State Transfer (REST) is an architectural style originally defined by Roy Fielding. REST provides six guiding constraints: client-server separation, statelessness, cacheability, unifo'
  name: REST Architectural Style
  slug: rest-architectural-style
- description: The OpenAPI Specification (OAS) defines a standard, language-agnostic interface to RESTful APIs which allows both humans and computers to discover and understand capabilities of a service without acce
  name: OpenAPI Specification
  slug: openapi-specification
- description: RFC 9110 defines the semantics of the Hypertext Transfer Protocol (HTTP), the foundation of the World Wide Web and RESTful API communication, including methods, status codes, headers, and content nego
  name: HTTP Semantics
  slug: http-semantics
- description: JSON:API is a specification for how a client should request that resources be fetched or modified, and how a server should respond to those requests, built on top of REST principles with conventions f
  name: JSON:API
  slug: json-api
common:
- title: ''
  type: Website
  url: https://restfulapi.net
- title: ''
  type: Specification
  url: https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm
- title: ''
  type: RFC
  url: https://www.rfc-editor.org/rfc/rfc9110
- title: ''
  type: OpenAPI
  url: https://spec.openapis.org/oas/latest.html
- title: ''
  type: Tutorials
  url: https://restfulapi.net/rest-api-tutorial/
- title: ''
  type: GitHub
  url: https://github.com/OAI/OpenAPI-Specification
- title: ''
  type: Tooling
  url: https://openapi.tools
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/rest/refs/heads/main/json-schema/rest-api-schema.json
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/rest/refs/heads/main/vocabulary/rest-vocabulary.yml
created: '2025-01-01'
description: REST (Representational State Transfer) is an architectural style for designing networked applications, defined by Roy Fielding in his 2000 doctoral dissertation. REST uses stateless communication, standard HTTP methods (GET, POST, PUT, DELETE, PATCH), and resource-oriented URLs to provide scalable, cacheable, and loosely coupled interfaces. It has become the dominant approach for building web APIs, forming the foundation of modern API design principles and tooling ecosystems.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 9
  name: Rest Context
  property_count: 5
  slug: rest-context
layout: provider
modified: '2026-05-02'
name: REST
skills: []
slug: rest
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rest\nname: REST\ndescription: >-\n  REST (Representational State Transfer) is an architectural style for designing\n  networked applications, defined by Roy Fielding in his 2000 doctoral dissertation.\n  REST uses stateless communication, standard HTTP methods (GET, POST, PUT, DELETE,\n  PATCH), and resource-oriented URLs to provide scalable, cacheable, and loosely\n  coupled interfaces. It has become the dominant approach for building web APIs,\n  forming the foundation of modern API design principles and tooling ecosystems.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Design\n  - Architecture\n  - HTTP\n  - REST\n  - RESTful\n  - Web Services\nurl: https://raw.githubusercontent.com/api-evangelist/rest/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rest:rest-architectural-style\n    name: REST Architectural Style\n    description:\
  \ >-\n      Representational State Transfer (REST) is an architectural style originally\n      defined by Roy Fielding. REST provides six guiding constraints: client-server\n      separation, statelessness, cacheability, uniform interface, layered system,\n      and optional code-on-demand. Any API conforming to these constraints is\n      considered RESTful.\n    humanURL: https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm\n    tags:\n      - Architecture\n      - HTTP\n      - REST\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm\n      - type: Specification\n        url: https://www.rfc-editor.org/rfc/rfc7231\n  - aid: rest:openapi-specification\n    name: OpenAPI Specification\n    description: >-\n      The OpenAPI Specification (OAS) defines a standard, language-agnostic\n      interface to RESTful APIs which allows both humans and computers to discover\n\
  \      and understand capabilities of a service without access to source code,\n      documentation, or network traffic inspection.\n    humanURL: https://spec.openapis.org/oas/latest.html\n    tags:\n      - API Design\n      - API Documentation\n      - OpenAPI\n      - Specification\n    properties:\n      - type: Documentation\n        url: https://spec.openapis.org/oas/latest.html\n      - type: GitHub\n        url: https://github.com/OAI/OpenAPI-Specification\n  - aid: rest:http-semantics\n    name: HTTP Semantics\n    description: >-\n      RFC 9110 defines the semantics of the Hypertext Transfer Protocol (HTTP),\n      the foundation of the World Wide Web and RESTful API communication,\n      including methods, status codes, headers, and content negotiation.\n    humanURL: https://www.rfc-editor.org/rfc/rfc9110\n    tags:\n      - HTTP\n      - RFC\n      - Semantics\n      - Standards\n    properties:\n      - type: Specification\n        url: https://www.rfc-editor.org/rfc/rfc9110\n\
  \  - aid: rest:json-api\n    name: JSON:API\n    description: >-\n      JSON:API is a specification for how a client should request that resources\n      be fetched or modified, and how a server should respond to those requests,\n      built on top of REST principles with conventions for relationships, pagination,\n      filtering, and sparse fieldsets.\n    humanURL: https://jsonapi.org\n    tags:\n      - API Design\n      - JSON\n      - REST\n      - Specification\n    properties:\n      - type: Documentation\n        url: https://jsonapi.org/format/\n      - type: GitHub\n        url: https://github.com/json-api/json-api\ncommon:\n  - type: Website\n    url: https://restfulapi.net\n  - type: Specification\n    url: https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm\n  - type: RFC\n    url: https://www.rfc-editor.org/rfc/rfc9110\n  - type: OpenAPI\n    url: https://spec.openapis.org/oas/latest.html\n  - type: Tutorials\n    url: https://restfulapi.net/rest-api-tutorial/\n\
  \  - type: GitHub\n    url: https://github.com/OAI/OpenAPI-Specification\n  - type: Tooling\n    url: https://openapi.tools\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/rest/refs/heads/main/json-schema/rest-api-schema.json\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/rest/refs/heads/main/vocabulary/rest-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rest/refs/heads/main/apis.yml
tags:
- API Design
- Architecture
- HTTP
- REST
- RESTful
- Web Services
url: https://raw.githubusercontent.com/api-evangelist/rest/refs/heads/main/apis.yml
use_cases: []
---
