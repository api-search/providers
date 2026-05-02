---
api_count: 1
api_specs:
- filename: jupyter-server-rest-api-openapi.yml
  format: yaml
  label: Jupyter Server REST API
  slug: jupyter-server-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyter-server/refs/heads/main/openapi/jupyter-server-rest-api-openapi.yml
apis:
- description: Core REST API for Jupyter Server, providing endpoints for managing kernels, sessions, contents (notebooks and files), terminals, kernel specifications, configuration, and server status.
  name: Jupyter Server REST API
  slug: jupyter-server-rest-api
common:
- title: ''
  type: Website
  url: https://jupyter-server.readthedocs.io/
- title: ''
  type: Documentation
  url: https://jupyter-server.readthedocs.io/en/latest/
- title: ''
  type: GettingStarted
  url: https://jupyter-server.readthedocs.io/en/latest/users/index.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/jupyter-server
- title: ''
  type: Repository
  url: https://github.com/jupyter-server/jupyter_server
- title: ''
  type: Community
  url: https://discourse.jupyter.org/
- title: ''
  type: Security
  url: https://jupyter.org/security
created: '2025-02-06'
description: Jupyter Server is the backend that powers Jupyter Notebook, JupyterLab, and other Jupyter web applications. It provides the core REST API for managing kernels, sessions, contents, terminals, and configuration, and it hosts the WebSocket endpoints used to communicate with kernels via the Jupyter messaging protocol.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Jupyter Server Context
  property_count: 0
  slug: jupyter-server-context
layout: provider
modified: '2026-04-28'
name: Jupyter Server
skills: []
slug: jupyter-server
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: jupyter-server\nname: Jupyter Server\ndescription: >-\n  Jupyter Server is the backend that powers Jupyter Notebook, JupyterLab,\n  and other Jupyter web applications. It provides the core REST API for\n  managing kernels, sessions, contents, terminals, and configuration, and\n  it hosts the WebSocket endpoints used to communicate with kernels via\n  the Jupyter messaging protocol.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Compute\n  - Interactive Computing\n  - Kernels\n  - Notebooks\n  - Portable\n  - Workbooks\nurl: https://raw.githubusercontent.com/api-evangelist/jupyter-server/refs/heads/main/apis.yml\ncreated: '2025-02-06'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: jupyter-server:jupyter-server-rest-api\n    name: Jupyter Server REST API\n    description: >-\n      Core REST API for Jupyter Server, providing endpoints for managing\n      kernels, sessions, contents (notebooks\
  \ and files), terminals, kernel\n      specifications, configuration, and server status.\n    humanURL: https://jupyter-server.readthedocs.io/en/latest/developers/rest-api.html\n    baseURL: http://localhost:8888/api\n    tags:\n      - Contents\n      - Kernels\n      - REST API\n      - Sessions\n      - Terminals\n    properties:\n      - type: Documentation\n        url: https://jupyter-server.readthedocs.io/en/latest/developers/rest-api.html\n      - type: Repository\n        url: https://github.com/jupyter-server/jupyter_server\n      - type: ChangeLog\n        url: https://github.com/jupyter-server/jupyter_server/blob/main/CHANGELOG.md\n      - type: OpenAPI\n        url: openapi/jupyter-server-rest-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/jupyter-server-contents-model.json\n      - type: JSONSchema\n        url: json-schema/jupyter-server-kernel.json\n      - type: JSONSchema\n        url: json-schema/jupyter-server-session.json\n      - type: JSONLDContext\n\
  \        url: json-ld/jupyter-server-context.jsonld\ncommon:\n  - type: Website\n    url: https://jupyter-server.readthedocs.io/\n  - type: Documentation\n    url: https://jupyter-server.readthedocs.io/en/latest/\n  - type: GettingStarted\n    url: https://jupyter-server.readthedocs.io/en/latest/users/index.html\n  - type: GitHubOrganization\n    url: https://github.com/jupyter-server\n  - type: Repository\n    url: https://github.com/jupyter-server/jupyter_server\n  - type: Community\n    url: https://discourse.jupyter.org/\n  - type: Security\n    url: https://jupyter.org/security\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/jupyter-server/refs/heads/main/apis.yml
tags:
- Compute
- Interactive Computing
- Kernels
- Notebooks
- Portable
- Workbooks
url: https://raw.githubusercontent.com/api-evangelist/jupyter-server/refs/heads/main/apis.yml
use_cases: []
---
