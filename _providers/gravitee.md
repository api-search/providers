---
api_count: 3
api_specs:
- filename: gravitee-management-api-openapi.yml
  format: yaml
  label: Gravitee Management API
  slug: gravitee-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gravitee/refs/heads/main/openapi/gravitee-management-api-openapi.yml
- filename: gravitee-access-management-api-openapi.yml
  format: yaml
  label: Gravitee Access Management API
  slug: gravitee-access-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gravitee/refs/heads/main/openapi/gravitee-access-management-api-openapi.yml
apis:
- description: Gravitee APIM is an open-source, flexible, and fast API management platform that helps organizations control, expose, and analyze their APIs with a full lifecycle management approach.
  name: Gravitee API Management
  slug: gravitee
- description: The Gravitee Management API provides a RESTful interface for programmatic administration of the Gravitee APIM platform. It exposes endpoints for creating and deploying APIs, managing plans, subscripti
  name: Gravitee Management API
  slug: gravitee-management-api
- description: The Gravitee Access Management (AM) API is a RESTful administration interface for the Gravitee AM identity and access management platform. It manages security domains, applications, users, roles, flow
  name: Gravitee Access Management API
  slug: gravitee-access-management-api
common:
- title: ''
  type: Website
  url: https://www.gravitee.io/
- title: ''
  type: Documentation
  url: https://documentation.gravitee.io/
- title: ''
  type: Getting Started
  url: https://documentation.gravitee.io/apim/getting-started
- title: ''
  type: Blog
  url: https://www.gravitee.io/blog/all
- title: ''
  type: Change Log
  url: https://documentation.gravitee.io/apim/release-information/changelog
- title: ''
  type: GitHub Organization
  url: https://github.com/gravitee-io
- title: ''
  type: GitHubRepository
  url: https://github.com/gravitee-io/gravitee-api-management
- title: ''
  type: Community
  url: https://community.gravitee.io/
- title: ''
  type: Issue Tracker
  url: https://github.com/gravitee-io/gravitee-api-management/issues
- title: ''
  type: JSON-LD Context
  url: json-ld/gravitee-context.jsonld
- title: ''
  type: JSON Schema
  url: json-schema/gravitee-api-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/gravitee-plan-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/gravitee-domain-schema.json
created: '2026-03-18'
description: Gravitee.io is an open-source API management platform offering an API gateway, developer portal, and API analytics with support for REST, GraphQL, WebSocket, gRPC, and event-driven APIs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Gravitee Context
  property_count: 10
  slug: gravitee-context
layout: provider
modified: '2026-03-26'
name: Gravitee
skills: []
slug: gravitee
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: gravitee\nname: Gravitee\ndescription: >-\n  Gravitee.io is an open-source API management platform offering an API\n  gateway, developer portal, and API analytics with support for REST, GraphQL,\n  WebSocket, gRPC, and event-driven APIs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - API Management\n  - GraphQL\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/gravitee/refs/heads/main/apis.yml\ncreated: '2026-03-18'\nmodified: '2026-03-26'\nspecificationVersion: '0.19'\napis:\n  - aid: gravitee:gravitee\n    name: Gravitee API Management\n    description: >-\n      Gravitee APIM is an open-source, flexible, and fast API management\n      platform that helps organizations control, expose, and analyze their APIs\n      with a full lifecycle management approach.\n    humanURL: https://www.gravitee.io/\n    tags:\n      - API Gateway\n      - API Management\n    properties:\n\
  \      - type: Documentation\n        url: https://documentation.gravitee.io/\n      - type: Getting Started\n        url: https://documentation.gravitee.io/apim/getting-started\n      - type: Change Log\n        url: https://documentation.gravitee.io/apim/release-information/changelog\n      - type: GitHubRepository\n        url: https://github.com/gravitee-io/gravitee-api-management\n      - type: JSON-LD Context\n        url: json-ld/gravitee-context.jsonld\n      - type: JSON Schema\n        url: json-schema/gravitee-api-schema.json\n      - type: JSON Schema\n        url: json-schema/gravitee-plan-schema.json\n  - aid: gravitee:gravitee-management-api\n    name: Gravitee Management API\n    description: >-\n      The Gravitee Management API provides a RESTful interface for programmatic\n      administration of the Gravitee APIM platform. It exposes endpoints for\n      creating and deploying APIs, managing plans, subscriptions, applications,\n      users, and platform configuration.\
  \ Two subcomponent versions (V1 and V2)\n      cover both v2 and v4 API management operations.\n    humanURL: https://documentation.gravitee.io/apim/configure-and-manage-the-platform/management-api\n    baseURL: https://www.gravitee.io/\n    tags:\n      - Administration\n      - Configuration\n      - Management\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://documentation.gravitee.io/apim/configure-and-manage-the-platform/management-api\n      - type: Reference\n        url: https://documentation.gravitee.io/apim/management-api-reference\n      - type: GitHubRepository\n        url: https://github.com/gravitee-io/gravitee-api-management\n      - type: OpenAPI\n        url: openapi/gravitee-management-api-openapi.yml\n      - type: JSON-LD Context\n        url: json-ld/gravitee-context.jsonld\n      - type: JSON Schema\n        url: json-schema/gravitee-api-schema.json\n      - type: JSON Schema\n        url: json-schema/gravitee-plan-schema.json\n\
  \  - aid: gravitee:gravitee-access-management-api\n    name: Gravitee Access Management API\n    description: >-\n      The Gravitee Access Management (AM) API is a RESTful administration\n      interface for the Gravitee AM identity and access management platform.\n      It manages security domains, applications, users, roles, flows, and\n      policies, and is secured using Bearer token authorization.\n    humanURL: https://documentation.gravitee.io/am\n    baseURL: https://www.gravitee.io/\n    tags:\n      - Access Management\n      - Identity\n      - OAuth2\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://documentation.gravitee.io/am\n      - type: Reference\n        url: https://documentation.gravitee.io/am/reference/am-api-reference\n      - type: Change Log\n        url: https://documentation.gravitee.io/am/releases-and-changelog/release-notes\n      - type: GitHubRepository\n        url: https://github.com/gravitee-io/gravitee-api-management\n\
  \      - type: OpenAPI\n        url: openapi/gravitee-access-management-api-openapi.yml\n      - type: JSON-LD Context\n        url: json-ld/gravitee-context.jsonld\n      - type: JSON Schema\n        url: json-schema/gravitee-domain-schema.json\ncommon:\n  - type: Website\n    url: https://www.gravitee.io/\n  - type: Documentation\n    url: https://documentation.gravitee.io/\n  - type: Getting Started\n    url: https://documentation.gravitee.io/apim/getting-started\n  - type: Blog\n    url: https://www.gravitee.io/blog/all\n  - type: Change Log\n    url: https://documentation.gravitee.io/apim/release-information/changelog\n  - type: GitHub Organization\n    url: https://github.com/gravitee-io\n  - type: GitHubRepository\n    url: https://github.com/gravitee-io/gravitee-api-management\n  - type: Community\n    url: https://community.gravitee.io/\n  - type: Issue Tracker\n    url: https://github.com/gravitee-io/gravitee-api-management/issues\n  - type: JSON-LD Context\n    url: json-ld/gravitee-context.jsonld\n\
  \  - type: JSON Schema\n    url: json-schema/gravitee-api-schema.json\n  - type: JSON Schema\n    url: json-schema/gravitee-plan-schema.json\n  - type: JSON Schema\n    url: json-schema/gravitee-domain-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/gravitee/refs/heads/main/apis.yml
tags:
- API Gateway
- API Management
- GraphQL
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/gravitee/refs/heads/main/apis.yml
use_cases: []
---
