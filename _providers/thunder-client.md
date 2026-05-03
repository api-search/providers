---
api_count: 2
apis:
- description: Thunder Client is the flagship VS Code REST API client extension offering a lightweight GUI for sending HTTP requests, managing collections with environment variables, and running scriptless tests. Fe
  name: Thunder Client
  slug: thunder-client
- description: The Thunder Client CLI (@thunderclient/cli) is a Node.js command-line tool for running Thunder Client requests, collections, and cURL commands from the terminal. It supports CI/CD integration, paralle
  name: Thunder Client CLI
  slug: thunder-client-cli
common:
- title: ''
  type: Website
  url: https://www.thunderclient.com
- title: ''
  type: Documentation
  url: https://docs.thunderclient.com/
- title: ''
  type: GitHub
  url: https://github.com/thunderclient/thunder-client-support
- title: ''
  type: VS Code Marketplace
  url: https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client
- title: ''
  type: Pricing
  url: https://www.thunderclient.com/pricing
- title: ''
  type: npm
  url: https://www.npmjs.com/package/@thunderclient/cli
- title: ''
  type: Changelog
  url: https://github.com/thunderclient/thunder-client-support/releases
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/json-schema/thunder-client-collection-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/json-schema/thunder-client-environment-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/json-structure/thunder-client-collection-structure.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/json-ld/thunder-client-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/vocabulary/thunder-client-vocabulary.yml
created: '2026-03-16'
description: Thunder Client is a lightweight REST API client extension for Visual Studio Code created by Ranga Vadhineni, providing a clean interface for sending HTTP requests, managing collections, and testing APIs without leaving the editor. With nearly 7 million installs, it pioneered GUI-based API testing in VS Code with 100% local storage, scriptless testing, Git Sync for team collaboration, GraphQL support, and an advanced CLI for CI/CD integration. Thunder Client supports importing collections from Postman, Insomnia, Hoppscotch, and OpenAPI 3.0, and offers pre/post-request scripting and environment variables.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 14
  name: Thunder Client Context
  property_count: 27
  slug: thunder-client-context
layout: provider
modified: '2026-05-03'
name: Thunder Client
skills: []
slug: thunder-client
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: thunder-client\nname: Thunder Client\ndescription: >-\n  Thunder Client is a lightweight REST API client extension for Visual Studio\n  Code created by Ranga Vadhineni, providing a clean interface for sending HTTP\n  requests, managing collections, and testing APIs without leaving the editor.\n  With nearly 7 million installs, it pioneered GUI-based API testing in VS Code\n  with 100% local storage, scriptless testing, Git Sync for team collaboration,\n  GraphQL support, and an advanced CLI for CI/CD integration. Thunder Client\n  supports importing collections from Postman, Insomnia, Hoppscotch, and\n  OpenAPI 3.0, and offers pre/post-request scripting and environment variables.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Client\n  - API Testing\n  - CI/CD\n  - CLI\n  - Collections\n  - GraphQL\n  - REST Client\n  - VS Code\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/apis.yml\n\
  created: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: thunder-client:thunder-client\n    name: Thunder Client\n    description: >-\n      Thunder Client is the flagship VS Code REST API client extension offering\n      a lightweight GUI for sending HTTP requests, managing collections with\n      environment variables, and running scriptless tests. Features include\n      Git Sync for team collaboration, GraphQL support, pre/post request\n      scripting, collection import from Postman/Insomnia/Hoppscotch/OpenAPI,\n      and an advanced CLI supporting CI/CD pipelines.\n    humanURL: https://www.thunderclient.com\n    baseURL: https://www.thunderclient.com\n    tags:\n      - API Client\n      - API Testing\n      - Collections\n      - GraphQL\n      - REST Client\n      - VS Code\n    properties:\n      - type: Documentation\n        url: https://docs.thunderclient.com/\n      - type: Getting Started\n        url: https://docs.thunderclient.com/get-started\n\
  \      - type: GitHub\n        url: https://github.com/thunderclient/thunder-client-support\n      - type: VS Code Marketplace\n        url: https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client\n      - type: Pricing\n        url: https://www.thunderclient.com/pricing\n      - type: CLI Documentation\n        url: https://docs.thunderclient.com/cli\n      - type: Scripting API Reference\n        url: https://docs.thunderclient.com/scripting/api\n      - type: Changelog\n        url: https://github.com/thunderclient/thunder-client-support/releases\n      - type: npm\n        url: https://www.npmjs.com/package/@thunderclient/cli\n    contact:\n      - FN: Thunder Client Support\n        url: https://github.com/thunderclient/thunder-client-support\n    version: 2.40.10\n\n  - aid: thunder-client:thunder-client-cli\n    name: Thunder Client CLI\n    description: >-\n      The Thunder Client CLI (@thunderclient/cli) is a Node.js command-line\n      tool for running\
  \ Thunder Client requests, collections, and cURL commands\n      from the terminal. It supports CI/CD integration, parallel execution,\n      and multiple report formats (CLI, CSV, HTML, JSON, XML, NUnit).\n      Installed globally via npm (npm i -g @thunderclient/cli).\n    humanURL: https://docs.thunderclient.com/cli\n    baseURL: https://docs.thunderclient.com/cli\n    tags:\n      - API Testing\n      - CI/CD\n      - CLI\n      - Collections\n      - Node.js\n    properties:\n      - type: Documentation\n        url: https://docs.thunderclient.com/cli\n      - type: CLI Install\n        url: https://docs.thunderclient.com/cli/install\n      - type: Run Requests\n        url: https://docs.thunderclient.com/cli/run-requests\n      - type: Run Collection\n        url: https://docs.thunderclient.com/cli/run-collection\n      - type: cURL Commands\n        url: https://docs.thunderclient.com/cli/curl\n      - type: CI/CD Integration\n        url: https://docs.thunderclient.com/cli/ci-cd\n\
  \      - type: List Command\n        url: https://docs.thunderclient.com/cli/list\n      - type: npm\n        url: https://www.npmjs.com/package/@thunderclient/cli\n\ncommon:\n  - type: Website\n    url: https://www.thunderclient.com\n  - type: Documentation\n    url: https://docs.thunderclient.com/\n  - type: GitHub\n    url: https://github.com/thunderclient/thunder-client-support\n  - type: VS Code Marketplace\n    url: https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client\n  - type: Pricing\n    url: https://www.thunderclient.com/pricing\n  - type: npm\n    url: https://www.npmjs.com/package/@thunderclient/cli\n  - type: Changelog\n    url: https://github.com/thunderclient/thunder-client-support/releases\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/json-schema/thunder-client-collection-schema.json\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/json-schema/thunder-client-environment-schema.json\n\
  \  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/json-structure/thunder-client-collection-structure.json\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/json-ld/thunder-client-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/vocabulary/thunder-client-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/apis.yml
tags:
- API Client
- API Testing
- CI/CD
- CLI
- Collections
- GraphQL
- REST Client
- VS Code
url: https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/apis.yml
use_cases: []
---
