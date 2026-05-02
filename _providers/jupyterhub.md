---
api_count: 1
api_specs:
- filename: jupyterhub-rest-api-openapi.yml
  format: yaml
  label: JupyterHub REST API
  slug: jupyterhub-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyterhub/refs/heads/main/openapi/jupyterhub-rest-api-openapi.yml
apis:
- description: REST API for managing users, groups, single-user servers, services, tokens, the proxy, and OAuth2 authorization in a JupyterHub deployment. Authenticated via API tokens or OAuth2.
  name: JupyterHub REST API
  slug: jupyterhub-rest-api
common:
- title: ''
  type: Website
  url: https://jupyter.org/hub
- title: ''
  type: Documentation
  url: https://jupyterhub.readthedocs.io/
- title: ''
  type: GettingStarted
  url: https://jupyterhub.readthedocs.io/en/stable/tutorial/quickstart.html
- title: ''
  type: Installation
  url: https://jupyterhub.readthedocs.io/en/stable/installation-guide.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/jupyterhub
- title: ''
  type: Repository
  url: https://github.com/jupyterhub/jupyterhub
- title: ''
  type: Community
  url: https://discourse.jupyter.org/c/jupyterhub
- title: ''
  type: License
  url: https://github.com/jupyterhub/jupyterhub/blob/main/COPYING.md
created: '2024-01-01'
description: JupyterHub is a multi-user server for Jupyter notebooks. It manages authentication, spawns and proxies multiple instances of the single-user Jupyter notebook server, and exposes a REST API for managing users, groups, services, tokens, and the proxy.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 9
  name: Jupyterhub Context
  property_count: 0
  slug: jupyterhub-context
layout: provider
modified: '2026-04-28'
name: JupyterHub
skills: []
slug: jupyterhub
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: jupyterhub\nname: JupyterHub\ndescription: >-\n  JupyterHub is a multi-user server for Jupyter notebooks. It manages\n  authentication, spawns and proxies multiple instances of the\n  single-user Jupyter notebook server, and exposes a REST API for\n  managing users, groups, services, tokens, and the proxy.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Authentication\n  - Data Science\n  - Education\n  - Hub\n  - Multi-User\n  - Notebooks\n  - OAuth2\n  - Python\nurl: https://raw.githubusercontent.com/api-evangelist/jupyterhub/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: jupyterhub:jupyterhub-rest-api\n    name: JupyterHub REST API\n    description: >-\n      REST API for managing users, groups, single-user servers, services,\n      tokens, the proxy, and OAuth2 authorization in a JupyterHub\n      deployment. Authenticated via API tokens\
  \ or OAuth2.\n    humanURL: https://jupyterhub.readthedocs.io/en/stable/reference/rest-api.html\n    baseURL: http://localhost:8000/hub/api\n    tags:\n      - Authentication\n      - Groups\n      - OAuth2\n      - REST API\n      - Servers\n      - Tokens\n      - Users\n    properties:\n      - type: Documentation\n        url: https://jupyterhub.readthedocs.io/en/stable/reference/rest-api.html\n      - type: Repository\n        url: https://github.com/jupyterhub/jupyterhub\n      - type: Authentication\n        url: https://jupyterhub.readthedocs.io/en/stable/rbac/index.html\n      - type: OpenAPI\n        url: openapi/jupyterhub-rest-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/jupyterhub-user.json\n      - type: JSONSchema\n        url: json-schema/jupyterhub-server.json\n      - type: JSONSchema\n        url: json-schema/jupyterhub-group.json\n      - type: JSONLDContext\n        url: json-ld/jupyterhub-context.jsonld\ncommon:\n  - type: Website\n    url:\
  \ https://jupyter.org/hub\n  - type: Documentation\n    url: https://jupyterhub.readthedocs.io/\n  - type: GettingStarted\n    url: https://jupyterhub.readthedocs.io/en/stable/tutorial/quickstart.html\n  - type: Installation\n    url: https://jupyterhub.readthedocs.io/en/stable/installation-guide.html\n  - type: GitHubOrganization\n    url: https://github.com/jupyterhub\n  - type: Repository\n    url: https://github.com/jupyterhub/jupyterhub\n  - type: Community\n    url: https://discourse.jupyter.org/c/jupyterhub\n  - type: License\n    url: https://github.com/jupyterhub/jupyterhub/blob/main/COPYING.md\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/jupyterhub/refs/heads/main/apis.yml
tags:
- Authentication
- Data Science
- Education
- Hub
- Multi-User
- Notebooks
- OAuth2
- Python
url: https://raw.githubusercontent.com/api-evangelist/jupyterhub/refs/heads/main/apis.yml
use_cases: []
---
