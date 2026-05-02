---
api_count: 1
api_specs:
- filename: jupyter-hub-openapi.yml
  format: yaml
  label: JupyterHub REST API
  slug: jupyterhub-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyter-hub/refs/heads/main/openapi/jupyter-hub-openapi.yml
apis:
- description: REST API for managing JupyterHub users, groups, services, and single-user notebook servers. Authentication is performed via API tokens.
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
  type: Getting Started
  url: https://jupyterhub.readthedocs.io/en/stable/tutorial/quickstart.html
- title: ''
  type: GitHub Organization
  url: https://github.com/jupyterhub
- title: ''
  type: Community
  url: https://discourse.jupyter.org/c/jupyterhub
- title: ''
  type: JSON-LD
  url: json-ld/jupyter-hub-context.jsonld
created: '2024-01-01'
description: JupyterHub is a multi-user server for Jupyter notebooks. It manages and proxies multiple instances of the single-user Jupyter notebook server, providing authentication and spawning for multiple users.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 12
  name: Jupyter Hub Context
  property_count: 0
  slug: jupyter-hub-context
layout: provider
modified: '2026-04-28'
name: JupyterHub
skills: []
slug: jupyter-hub
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: jupyter-hub\nname: JupyterHub\ndescription: >-\n  JupyterHub is a multi-user server for Jupyter notebooks. It manages and\n  proxies multiple instances of the single-user Jupyter notebook server,\n  providing authentication and spawning for multiple users.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Science\n  - Education\n  - Jupyter\n  - Multi-User\n  - Notebooks\nurl: https://raw.githubusercontent.com/api-evangelist/jupyter-hub/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: jupyter-hub:jupyterhub-rest-api\n    name: JupyterHub REST API\n    description: >-\n      REST API for managing JupyterHub users, groups, services, and single-user\n      notebook servers. Authentication is performed via API tokens.\n    humanURL: https://jupyterhub.readthedocs.io/en/stable/reference/rest-api.html\n    baseURL: https://your-jupyterhub-domain.com/hub/api\n\
  \    tags:\n      - Authentication\n      - REST API\n      - Servers\n      - Users\n    properties:\n      - type: Documentation\n        url: https://jupyterhub.readthedocs.io/en/stable/reference/rest-api.html\n      - type: OpenAPI\n        url: openapi/jupyter-hub-openapi.yml\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/jupyterhub/jupyterhub/main/docs/source/_static/rest-api.yml\n      - type: JSONSchema\n        url: json-schema/jupyter-hub-user.json\n      - type: Authentication\n        url: https://jupyterhub.readthedocs.io/en/stable/reference/rest-api.html#authentication\ncommon:\n  - type: Website\n    url: https://jupyter.org/hub\n  - type: Documentation\n    url: https://jupyterhub.readthedocs.io/\n  - type: Getting Started\n    url: https://jupyterhub.readthedocs.io/en/stable/tutorial/quickstart.html\n  - type: GitHub Organization\n    url: https://github.com/jupyterhub\n  - type: Community\n    url: https://discourse.jupyter.org/c/jupyterhub\n \
  \ - type: JSON-LD\n    url: json-ld/jupyter-hub-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/jupyter-hub/refs/heads/main/apis.yml
tags:
- Data Science
- Education
- Jupyter
- Multi-User
- Notebooks
url: https://raw.githubusercontent.com/api-evangelist/jupyter-hub/refs/heads/main/apis.yml
use_cases: []
---
