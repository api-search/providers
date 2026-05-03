---
api_count: 2
api_specs:
- filename: swaggerhub-registry-api-openapi.yml
  format: yaml
  label: SwaggerHub Registry API
  slug: swaggerhub-registry-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/swaggerhub/refs/heads/main/openapi/swaggerhub-registry-api-openapi.yml
- filename: swaggerhub-user-management-openapi.yml
  format: yaml
  label: SwaggerHub User Management API
  slug: swaggerhub-user-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/swaggerhub/refs/heads/main/openapi/swaggerhub-user-management-openapi.yml
apis:
- description: The SwaggerHub Registry API allows programmatic access to all SwaggerHub resources including APIs, domains, integrations, projects, templates, and standardization rulesets. Use it to manage API versio
  name: SwaggerHub Registry API
  slug: swaggerhub-registry-api
- description: The SwaggerHub User Management API enables organizations to automate user provisioning, manage team memberships, and control resource access. It supports adding and removing organization members, chan
  name: SwaggerHub User Management API
  slug: swaggerhub-user-management-api
capabilities:
- description: 'Workflow capability for managing the full API lifecycle in SwaggerHub: discovering APIs, creating and updating definitions, managing versions, controlling lifecycle settings (publish/unpublish), runni'
  name: SwaggerHub API Lifecycle Management
  slug: api-lifecycle-management
common:
- title: ''
  type: Portal
  url: https://swagger.io/tools/swaggerhub/
- title: ''
  type: Sign Up
  url: https://app.swaggerhub.com/signup
- title: ''
  type: Login
  url: https://app.swaggerhub.com/login/
- title: ''
  type: Documentation
  url: https://support.smartbear.com/swaggerhub/docs/
- title: ''
  type: Getting Started
  url: https://support.smartbear.com/swaggerhub/docs/en/get-started.html
- title: ''
  type: Pricing
  url: https://swagger.io/product/pricing/
- title: ''
  type: Blog
  url: https://swagger.io/blog/
- title: ''
  type: Status
  url: https://status.swaggerhub.com/
- title: ''
  type: Support
  url: https://support.smartbear.com/swaggerhub/
- title: ''
  type: Terms of Service
  url: https://app.swaggerhub.com/terms-of-service
- title: ''
  type: Privacy Policy
  url: https://app.swaggerhub.com/eula
- title: ''
  type: CLI
  url: https://github.com/SmartBear/swaggerhub-cli
- title: ''
  type: GitHub Organization
  url: https://github.com/swagger-api
- title: ''
  type: OpenAPI Specification
  url: https://swagger.io/specification/
- title: ''
  type: About
  url: https://swagger.io/about/
- title: ''
  type: License
  url: https://swagger.io/license/
created: '2026-03-03'
description: SwaggerHub is SmartBear's enterprise collaborative API design and documentation platform built around the OpenAPI specification. It provides tools for designing, building, documenting, and consuming RESTful APIs with support for OpenAPI 2.0, OpenAPI 3.0, OpenAPI 3.1, and AsyncAPI specifications. The platform offers automated validation, team collaboration, lifecycle management, integrations with CI/CD pipelines, and an organizational API registry.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Swaggerhub Context
  property_count: 25
  slug: swaggerhub-context
layout: provider
modified: '2026-05-02'
name: SwaggerHub
rules:
- name: SwaggerHub API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 5
  slug: swaggerhub-rules
skills: []
slug: swaggerhub
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: swaggerhub\nname: SwaggerHub\ndescription: >-\n  SwaggerHub is SmartBear's enterprise collaborative API design and documentation\n  platform built around the OpenAPI specification. It provides tools for designing,\n  building, documenting, and consuming RESTful APIs with support for OpenAPI 2.0,\n  OpenAPI 3.0, OpenAPI 3.1, and AsyncAPI specifications. The platform offers\n  automated validation, team collaboration, lifecycle management, integrations\n  with CI/CD pipelines, and an organizational API registry.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Design\n  - API Management\n  - API Registry\n  - Documentation\n  - OpenAPI\n  - SmartBear\nurl: https://raw.githubusercontent.com/api-evangelist/swaggerhub/refs/heads/main/apis.yml\ncreated: '2026-03-03'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: swaggerhub:swaggerhub-registry-api\n    name: SwaggerHub Registry API\n    description:\
  \ >-\n      The SwaggerHub Registry API allows programmatic access to all SwaggerHub\n      resources including APIs, domains, integrations, projects, templates, and\n      standardization rulesets. Use it to manage API versions, publish/unpublish\n      APIs, run integrations, manage project memberships, and retrieve OpenAPI\n      definitions in JSON or YAML format.\n    humanURL: https://support.smartbear.com/swaggerhub/docs/en/swaggerhub-apis.html\n    baseURL: https://api.swaggerhub.com\n    tags:\n      - API Management\n      - API Registry\n      - Documentation\n      - Integrations\n      - OpenAPI\n      - Projects\n    properties:\n      - type: Documentation\n        url: https://support.smartbear.com/swaggerhub/docs/en/swaggerhub-apis.html\n      - type: API Reference\n        url: https://api.swaggerhub.com/apis/swagger-hub/registry-api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/swaggerhub/refs/heads/main/openapi/swaggerhub-registry-api-openapi.yml\n\
  \      - type: Postman Collection\n        url: https://www.postman.com/api-evangelist/swaggerhub/documentation/1lsm5uz/swaggerhub-registry-api\n\n  - aid: swaggerhub:swaggerhub-user-management-api\n    name: SwaggerHub User Management API\n    description: >-\n      The SwaggerHub User Management API enables organizations to automate user\n      provisioning, manage team memberships, and control resource access. It supports\n      adding and removing organization members, changing user roles (Owner, Designer,\n      Consumer), and managing resource access permissions for users and teams.\n    humanURL: https://support.smartbear.com/swaggerhub/docs/en/swaggerhub-apis/user-management-api.html\n    baseURL: https://api.swaggerhub.com\n    tags:\n      - Access Control\n      - Organizations\n      - Teams\n      - User Management\n      - Users\n    properties:\n      - type: Documentation\n        url: https://support.smartbear.com/swaggerhub/docs/en/swaggerhub-apis/user-management-api.html\n\
  \      - type: API Reference\n        url: https://app.swaggerhub.com/apis-docs/swagger-hub/user-management-api/v1\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/swaggerhub/refs/heads/main/openapi/swaggerhub-user-management-openapi.yml\n\ncommon:\n  - type: Portal\n    url: https://swagger.io/tools/swaggerhub/\n  - type: Sign Up\n    url: https://app.swaggerhub.com/signup\n  - type: Login\n    url: https://app.swaggerhub.com/login/\n  - type: Documentation\n    url: https://support.smartbear.com/swaggerhub/docs/\n  - type: Getting Started\n    url: https://support.smartbear.com/swaggerhub/docs/en/get-started.html\n  - type: Pricing\n    url: https://swagger.io/product/pricing/\n  - type: Blog\n    url: https://swagger.io/blog/\n  - type: Status\n    url: https://status.swaggerhub.com/\n  - type: Support\n    url: https://support.smartbear.com/swaggerhub/\n  - type: Terms of Service\n    url: https://app.swaggerhub.com/terms-of-service\n  - type: Privacy\
  \ Policy\n    url: https://app.swaggerhub.com/eula\n  - type: Integrations\n    url: https://swagger.io/tools/swaggerhub/integrations/\n  - type: CLI\n    url: https://github.com/SmartBear/swaggerhub-cli\n  - type: GitHub Organization\n    url: https://github.com/swagger-api\n  - type: OpenAPI Specification\n    url: https://swagger.io/specification/\n  - type: About\n    url: https://swagger.io/about/\n  - type: License\n    url: https://swagger.io/license/\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/swaggerhub/refs/heads/main/apis.yml
tags:
- API Design
- API Management
- API Registry
- Documentation
- OpenAPI
- SmartBear
url: https://raw.githubusercontent.com/api-evangelist/swaggerhub/refs/heads/main/apis.yml
use_cases: []
---
