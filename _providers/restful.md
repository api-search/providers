---
api_count: 5
apis:
- description: 'A model by Leonard Richardson that breaks down the maturity of a RESTful API into four levels: Level 0 (The Swamp of POX), Level 1 (Resources), Level 2 (HTTP Verbs), and Level 3 (Hypermedia Controls /'
  name: Richardson Maturity Model
  slug: richardson-maturity-model
- description: A specification for building APIs in JSON that standardizes resource representation, relationships, error handling, and metadata. Reduces over-fetching and under-fetching with sparse fieldsets and com
  name: JSON:API
  slug: json-api
- description: A simple format for including hypermedia links in JSON or XML API responses. HAL uses _links for links and _embedded for embedded resources, providing a consistent way to make REST APIs navigable.
  name: HAL - Hypertext Application Language
  slug: hal-specification
- description: The OpenAPI Specification (OAS) defines a standard, language-agnostic interface for HTTP APIs. OpenAPI 3.x is the most widely-used format for describing RESTful APIs, enabling documentation, code gene
  name: OpenAPI Specification
  slug: openapi-specification
- description: 'The IETF standard defining HTTP semantics: methods, status codes, header fields, content negotiation, authentication, and request/response message formats. The authoritative reference for RESTful HTTP'
  name: RFC 9110 - HTTP Semantics
  slug: http-rfc-9110
common:
- title: ''
  type: Roy Fielding REST Dissertation
  url: https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm
- title: ''
  type: IANA HTTP Status Codes
  url: https://www.iana.org/assignments/http-status-codes/
- title: ''
  type: IANA Link Relations
  url: https://www.iana.org/assignments/link-relations/
- title: ''
  type: RFC 6570 URI Templates
  url: https://datatracker.ietf.org/doc/html/rfc6570
created: '2025-01-01'
description: 'Representational State Transfer (REST) is an architectural style for designing networked applications using stateless HTTP communication and uniform interfaces. RESTful describes systems and APIs that conform to the REST constraints: client-server separation, statelessness, cacheability, layered system, uniform interface, and (optionally) code-on-demand. This index covers the RESTful design paradigm including maturity models, API design patterns, documentation formats, and key reference implementations.'
features: []
image: ''
integrations: []
jsonld:
- class_count: 13
  name: Restful Context
  property_count: 7
  slug: restful-context
layout: provider
modified: '2026-05-02'
name: RESTful
skills: []
slug: restful
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: restful\nname: RESTful\ndescription: >-\n  Representational State Transfer (REST) is an architectural style for\n  designing networked applications using stateless HTTP communication and\n  uniform interfaces. RESTful describes systems and APIs that conform to the\n  REST constraints: client-server separation, statelessness, cacheability,\n  layered system, uniform interface, and (optionally) code-on-demand.\n  This index covers the RESTful design paradigm including maturity models,\n  API design patterns, documentation formats, and key reference implementations.\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/restful/refs/heads/main/apis.yml\ntags:\n  - Architecture\n  - HTTP\n  - Web Services\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: restful:richardson-maturity-model\n    name: Richardson Maturity Model\n    description: >-\n      A model by Leonard Richardson that breaks down the maturity of a RESTful\n\
  \      API into four levels: Level 0 (The Swamp of POX), Level 1 (Resources),\n      Level 2 (HTTP Verbs), and Level 3 (Hypermedia Controls / HATEOAS).\n      Most modern APIs target Level 2.\n    humanURL: https://martinfowler.com/articles/richardsonMaturityModel.html\n    tags:\n      - Best Practices\n      - Design Patterns\n      - Maturity Model\n    properties:\n      - type: Documentation\n        url: https://martinfowler.com/articles/richardsonMaturityModel.html\n\n  - aid: restful:json-api\n    name: JSON:API\n    description: >-\n      A specification for building APIs in JSON that standardizes resource\n      representation, relationships, error handling, and metadata. Reduces\n      over-fetching and under-fetching with sparse fieldsets and compound\n      documents.\n    humanURL: https://jsonapi.org/\n    tags:\n      - Hypermedia\n      - JSON\n      - Standards\n    properties:\n      - type: Documentation\n        url: https://jsonapi.org/format/\n      - type: Website\n\
  \        url: https://jsonapi.org/\n\n  - aid: restful:hal-specification\n    name: HAL - Hypertext Application Language\n    description: >-\n      A simple format for including hypermedia links in JSON or XML API\n      responses. HAL uses _links for links and _embedded for embedded\n      resources, providing a consistent way to make REST APIs navigable.\n    humanURL: https://stateless.co/hal_specification.html\n    tags:\n      - Hypermedia\n      - JSON\n      - Standards\n    properties:\n      - type: Documentation\n        url: https://stateless.co/hal_specification.html\n      - type: IETF Draft\n        url: https://datatracker.ietf.org/doc/html/draft-kelly-json-hal\n\n  - aid: restful:openapi-specification\n    name: OpenAPI Specification\n    description: >-\n      The OpenAPI Specification (OAS) defines a standard, language-agnostic\n      interface for HTTP APIs. OpenAPI 3.x is the most widely-used format for\n      describing RESTful APIs, enabling documentation, code generation,\
  \ and\n      validation.\n    humanURL: https://spec.openapis.org/oas/latest.html\n    tags:\n      - Documentation\n      - Standards\n      - Tooling\n    properties:\n      - type: Specification\n        url: https://spec.openapis.org/oas/latest.html\n      - type: Website\n        url: https://www.openapis.org/\n\n  - aid: restful:http-rfc-9110\n    name: RFC 9110 - HTTP Semantics\n    description: >-\n      The IETF standard defining HTTP semantics: methods, status codes, header\n      fields, content negotiation, authentication, and request/response\n      message formats. The authoritative reference for RESTful HTTP API design.\n    humanURL: https://datatracker.ietf.org/doc/html/rfc9110\n    tags:\n      - HTTP\n      - RFC\n      - Standards\n    properties:\n      - type: Standard\n        url: https://datatracker.ietf.org/doc/html/rfc9110\n\ncommon:\n  - type: Roy Fielding REST Dissertation\n    url: https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm\n \
  \ - type: IANA HTTP Status Codes\n    url: https://www.iana.org/assignments/http-status-codes/\n  - type: IANA Link Relations\n    url: https://www.iana.org/assignments/link-relations/\n  - type: RFC 6570 URI Templates\n    url: https://datatracker.ietf.org/doc/html/rfc6570\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/restful/refs/heads/main/apis.yml
tags:
- Architecture
- HTTP
- Web Services
url: https://raw.githubusercontent.com/api-evangelist/restful/refs/heads/main/apis.yml
use_cases: []
---
