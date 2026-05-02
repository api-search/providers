---
api_count: 1
api_specs:
- filename: jupyter-notebooks-openapi.yml
  format: yaml
  label: Jupyter Notebook Server REST API
  slug: notebook-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebooks/refs/heads/main/openapi/jupyter-notebooks-openapi.yml
apis:
- description: REST API for the Jupyter Notebook server, providing access to notebook contents, kernels, kernel specs, sessions, and terminals.
  name: Jupyter Notebook Server REST API
  slug: notebook-rest-api
common:
- title: ''
  type: Website
  url: https://jupyter.org
- title: ''
  type: Documentation
  url: https://jupyter-notebook.readthedocs.io/en/stable/
- title: ''
  type: GitHub Organization
  url: https://github.com/jupyter
- title: ''
  type: Community
  url: https://discourse.jupyter.org/
- title: ''
  type: JSON-LD
  url: json-ld/jupyter-notebooks-context.jsonld
created: '2024-01-15'
description: Jupyter Notebooks is the original web application for creating and sharing computational documents. APIs cover the notebook server, kernels, sessions, contents, and terminal management.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 13
  name: Jupyter Notebooks Context
  property_count: 0
  slug: jupyter-notebooks-context
layout: provider
modified: '2026-04-28'
name: Jupyter Notebooks
skills: []
slug: jupyter-notebooks
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: jupyter-notebooks\nname: Jupyter Notebooks\ndescription: >-\n  Jupyter Notebooks is the original web application for creating and sharing\n  computational documents. APIs cover the notebook server, kernels, sessions,\n  contents, and terminal management.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Science\n  - Interactive Computing\n  - Jupyter\n  - Notebooks\n  - Python\nurl: https://raw.githubusercontent.com/api-evangelist/jupyter-notebooks/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: jupyter-notebooks:notebook-rest-api\n    name: Jupyter Notebook Server REST API\n    description: >-\n      REST API for the Jupyter Notebook server, providing access to notebook\n      contents, kernels, kernel specs, sessions, and terminals.\n    humanURL: https://jupyter-server.readthedocs.io/en/latest/developers/rest-api.html\n    baseURL: http://localhost:8888/api\n\
  \    tags:\n      - Contents\n      - Kernels\n      - Notebooks\n      - Sessions\n      - Terminals\n    properties:\n      - type: Documentation\n        url: https://jupyter-server.readthedocs.io/en/latest/developers/rest-api.html\n      - type: OpenAPI\n        url: openapi/jupyter-notebooks-openapi.yml\n      - type: JSONSchema\n        url: json-schema/jupyter-notebook-format-schema.json\ncommon:\n  - type: Website\n    url: https://jupyter.org\n  - type: Documentation\n    url: https://jupyter-notebook.readthedocs.io/en/stable/\n  - type: GitHub Organization\n    url: https://github.com/jupyter\n  - type: Community\n    url: https://discourse.jupyter.org/\n  - type: JSON-LD\n    url: json-ld/jupyter-notebooks-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebooks/refs/heads/main/apis.yml
tags:
- Data Science
- Interactive Computing
- Jupyter
- Notebooks
- Python
url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebooks/refs/heads/main/apis.yml
use_cases: []
---
