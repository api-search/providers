---
api_count: 3
api_specs:
- filename: drupal-rest-api-openapi.yml
  format: yaml
  label: Drupal REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/drupal/refs/heads/main/openapi/drupal-rest-api-openapi.yml
- filename: drupal-jsonapi-openapi.yml
  format: yaml
  label: Drupal JSON:API
  slug: jsonapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/drupal/refs/heads/main/openapi/drupal-jsonapi-openapi.yml
apis:
- description: The Drupal RESTful Web Services API is a core module that exposes Drupal entities and data as REST resources over HTTP. It supports multiple serialization formats and HTTP methods including GET, POST,
  name: Drupal REST API
  slug: rest-api
- description: The Drupal JSON:API module is a core component that exposes all Drupal entity types and bundles as a standards-compliant JSON:API interface, requiring no configuration to enable. Each entity bundle re
  name: Drupal JSON:API
  slug: jsonapi
- description: The Drupal GraphQL module is a contributed module that enables developers to craft and expose a GraphQL schema for Drupal 10 and 11, allowing client applications to query Drupal content and entities u
  name: Drupal GraphQL API
  slug: graphql
common:
- title: ''
  type: JSON-LD
  url: json-ld/drupal-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/drupal-node-schema.json
created: ''
description: Drupal is an open-source content management system written in PHP and used to build websites, applications, and digital experiences for individuals, organizations, and enterprises worldwide.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Drupal Context
  property_count: 8
  slug: drupal-context
layout: provider
modified: '2026-04-28'
name: drupal
skills: []
slug: drupal
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: drupal\nurl: https://raw.githubusercontent.com/api-evangelist/drupal/refs/heads/main/apis.yml\napis:\n  - aid: drupal:rest-api\n    name: Drupal REST API\n    tags:\n      - CMS\n      - Content Management\n      - REST\n      - Web Services\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://example.com\n    humanURL: https://www.drupal.org/docs/core-modules-and-themes/core-modules/restful-web-services-module\n    properties:\n      - url: https://www.drupal.org/docs/core-modules-and-themes/core-modules/restful-web-services-module\n        type: Documentation\n      - url: openapi/drupal-rest-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Drupal RESTful Web Services API is a core module that exposes Drupal entities\n      and data as REST resources over HTTP. It supports multiple serialization formats\n      and HTTP methods including GET, POST, PATCH, and DELETE, and is highly configurable\n\
  \      in terms of which resources, formats, and authentication methods are enabled.\n      Unlike the JSON:API module, it allows developers to define custom REST endpoints\n      for non-entity data and complex business logic operations.\n\n  - aid: drupal:jsonapi\n    name: Drupal JSON:API\n    tags:\n      - CMS\n      - Content Management\n      - Headless\n      - JSON:API\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://example.com/jsonapi\n    humanURL: https://www.drupal.org/docs/core-modules-and-themes/core-modules/jsonapi-module/api-overview\n    properties:\n      - url: https://www.drupal.org/docs/core-modules-and-themes/core-modules/jsonapi-module/api-overview\n        type: Documentation\n      - url: openapi/drupal-jsonapi-openapi.yml\n        type: OpenAPI\n      - url: json-schema/drupal-jsonapi-resource-schema.json\n        type: JSONSchema\n    description: >-\n      The Drupal JSON:API module\
  \ is a core component that exposes all Drupal entity\n      types and bundles as a standards-compliant JSON:API interface, requiring no\n      configuration to enable. Each entity bundle receives a unique URL path following\n      the pattern /jsonapi/{entity_type}/{bundle}, and the module supports GET, POST,\n      PATCH, and DELETE operations for full CRUD access.\n\n  - aid: drupal:graphql\n    name: Drupal GraphQL API\n    tags:\n      - CMS\n      - Content Management\n      - GraphQL\n      - Headless\n      - Query Language\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://example.com/graphql\n    humanURL: https://www.drupal.org/docs/contributed-modules/graphql\n    properties:\n      - url: https://www.drupal.org/docs/contributed-modules/graphql\n        type: Documentation\n      - url: https://drupal-graphql.gitbook.io/graphql/\n        type: Documentation\n    description: >-\n      The Drupal GraphQL module is a contributed\
  \ module that enables developers to\n      craft and expose a GraphQL schema for Drupal 10 and 11, allowing client applications\n      to query Drupal content and entities using GraphQL syntax. It supports both\n      queries and mutations for reading and writing data, and includes a built-in\n      GraphiQL Explorer interface at /graphql/explorer for interactive schema browsing\n      and query development.\n\ncommon:\n  - url: json-ld/drupal-context.jsonld\n    type: JSON-LD\n  - url: json-schema/drupal-node-schema.json\n    type: JSONSchema\n\nmodified: '2026-04-28'\ndescription: >-\n  Drupal is an open-source content management system written in PHP and used to build\n  websites, applications, and digital experiences for individuals, organizations,\n  and enterprises worldwide.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/drupal/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/drupal/refs/heads/main/apis.yml
use_cases: []
---
