---
api_count: 2
api_specs:
- filename: insomnia-mock-server-openapi.yml
  format: yaml
  label: Insomnia Mock Server API
  slug: mock-server-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/insomnia/refs/heads/main/openapi/insomnia-mock-server-openapi.yml
apis:
- description: Insomnia is an open-source, cross-platform API development platform by Kong for designing, debugging, and testing HTTP, REST, GraphQL, gRPC, SOAP, WebSockets, SSE, and Socket.IO APIs. It includes an I
  name: Insomnia
  slug: insomnia
- description: The Insomnia Mock Server API allows developers to create, manage, and interact with mock servers powered by Insomnia (Kong). Mock servers simulate API endpoints by returning predefined responses based
  name: Insomnia Mock Server API
  slug: mock-server-api
common:
- title: ''
  type: Documentation
  url: https://docs.insomnia.rest/
- title: ''
  type: GitHubRepository
  url: https://github.com/Kong/insomnia
- title: ''
  type: Plugins
  url: https://insomnia.rest/plugins
- title: ''
  type: Changelog
  url: https://insomnia.rest/changelog
- title: ''
  type: Blog
  url: https://konghq.com/blog
- title: ''
  type: Pricing
  url: https://insomnia.rest/pricing
- title: ''
  type: CLI
  url: https://docs.insomnia.rest/inso-cli/introduction/
- title: ''
  type: Website
  url: https://konghq.com/products/kong-insomnia
created: '2025-01-08'
description: Insomnia is an open-source, cross-platform API development platform by Kong for designing, debugging, and testing HTTP, REST, GraphQL, gRPC, SOAP, WebSockets, SSE, and Socket.IO APIs. It includes an Inso CLI for CI/CD integration, cloud-hosted and self-hosted mock servers, OpenAPI spec design tools, and collaborative features with cloud sync, local vault, and Git storage options.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 2
  name: Insomnia Context
  property_count: 5
  slug: insomnia-context
layout: provider
modified: '2026-03-16'
name: Insomnia
skills: []
slug: insomnia
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: insomnia\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/insomnia/refs/heads/main/apis.yml\napis:\n  - aid: insomnia:insomnia\n    name: Insomnia\n    tags:\n      - API Clients\n      - API Design\n      - Debugging\n      - Mocking\n      - Testing\n    humanURL: https://insomnia.rest/\n    properties:\n      - url: https://docs.insomnia.rest/\n        type: Documentation\n      - url: https://insomnia.rest/plugins\n        type: Plugins\n      - url: https://docs.insomnia.rest/inso-cli/introduction/\n        type: CLI\n      - url: https://docs.insomnia.rest/inso-cli/cli-command-reference\n        type: CLIReference\n      - url: https://docs.insomnia.rest/insomnia/api-mocking/\n        type: MockServer\n    description: >-\n      Insomnia is an open-source, cross-platform API development platform by\n      Kong for designing, debugging, and testing HTTP, REST, GraphQL, gRPC,\n      SOAP, WebSockets, SSE, and Socket.IO APIs. It includes an Inso CLI for\n\
  \      CI/CD integration, cloud-hosted and self-hosted mock servers, OpenAPI\n      spec design tools, and collaborative features with cloud sync, local\n      vault, and Git storage options.\n  - aid: insomnia:mock-server-api\n    name: Insomnia Mock Server API\n    tags:\n      - API Design\n      - Mocking\n      - Testing\n    humanURL: https://docs.insomnia.rest/insomnia/api-mocking/\n    properties:\n      - url: https://docs.insomnia.rest/insomnia/api-mocking/\n        type: Documentation\n      - url: openapi/insomnia-mock-server-openapi.yml\n        type: OpenAPI\n      - url: json-schema/workspace.json\n        type: JSONSchema\n      - url: json-schema/request.json\n        type: JSONSchema\n      - url: json-schema/environment.json\n        type: JSONSchema\n      - url: json-ld/insomnia-context.jsonld\n        type: JSONLD\n    description: >-\n      The Insomnia Mock Server API allows developers to create, manage, and\n      interact with mock servers powered by Insomnia\
  \ (Kong). Mock servers\n      simulate API endpoints by returning predefined responses based on\n      OpenAPI specifications or custom route configurations, enabling teams\n      to develop and test against realistic API behavior before the actual\n      implementation is complete.\nname: Insomnia\ntags:\n  - API Design\n  - CLI\n  - Clients\n  - Mocking\n  - Platform\n  - Testing\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-08'\nmodified: '2026-03-16'\nposition: Consumer\ndescription: >-\n  Insomnia is an open-source, cross-platform API development platform by Kong\n  for designing, debugging, and testing HTTP, REST, GraphQL, gRPC, SOAP,\n  WebSockets, SSE, and Socket.IO APIs. It includes an Inso CLI for CI/CD\n  integration, cloud-hosted and self-hosted mock servers, OpenAPI spec design\n  tools, and collaborative features with cloud sync, local vault, and Git\n  storage options.\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: Documentation\n    url: https://docs.insomnia.rest/\n    type: Documentation\n  - name: GitHub Repository\n    url: https://github.com/Kong/insomnia\n    type: GitHubRepository\n  - name: Plugins\n    url: https://insomnia.rest/plugins\n    type: Plugins\n  - name: Changelog\n    url: https://insomnia.rest/changelog\n    type: Changelog\n  - name: Blog\n    url: https://konghq.com/blog\n    type: Blog\n  - name: Pricing\n    url: https://insomnia.rest/pricing\n    type: Pricing\n  - name: Inso CLI\n    url: https://docs.insomnia.rest/inso-cli/introduction/\n    type: CLI\n  - name: Kong Inc\n    url: https://konghq.com/products/kong-insomnia\n    type: Website\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/insomnia/refs/heads/main/apis.yml
tags:
- API Design
- CLI
- Clients
- Mocking
- Platform
- Testing
url: https://raw.githubusercontent.com/api-evangelist/insomnia/refs/heads/main/apis.yml
use_cases: []
---
