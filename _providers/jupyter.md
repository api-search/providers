---
api_count: 4
apis:
- description: Original Jupyter web application and REST API for creating, editing, and running notebooks. Includes the kernel messaging protocol and supporting OpenAPI, JSON Schema, and AsyncAPI artifacts.
  name: Jupyter Notebook
  slug: jupyter-notebook
- description: Backend that powers Jupyter Notebook, JupyterLab, and other Jupyter web applications. Exposes the core REST API and the WebSocket messaging endpoints used to communicate with kernels.
  name: Jupyter Server
  slug: jupyter-server
- description: Multi-user server for Jupyter notebooks. Manages authentication, spawns and proxies multiple instances of the single-user Jupyter notebook server, and exposes a REST API for users, groups, services, t
  name: JupyterHub
  slug: jupyterhub
- description: Next-generation web-based interactive development environment for notebooks, code, and data, with a JupyterLab Server REST API for settings, workspaces, themes, translations, and licenses.
  name: JupyterLab
  slug: jupyterlab
common:
- title: ''
  type: Website
  url: https://jupyter.org
- title: ''
  type: Documentation
  url: https://docs.jupyter.org/
- title: ''
  type: Blog
  url: https://blog.jupyter.org/
- title: ''
  type: GitHubOrganization
  url: https://github.com/jupyter
- title: ''
  type: Community
  url: https://jupyter.org/community
- title: ''
  type: Support
  url: https://discourse.jupyter.org/
- title: ''
  type: Security
  url: https://jupyter.org/security
- title: ''
  type: YouTube
  url: https://www.youtube.com/@ProjectJupyter
created: '2024-01-01'
description: Project Jupyter is an open-source initiative that develops the software, open standards, and services for interactive computing across dozens of programming languages. The Jupyter ecosystem includes Jupyter Notebook, JupyterLab, Jupyter Server, JupyterHub, the Jupyter messaging protocol, and supporting client libraries.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Jupyter
skills: []
slug: jupyter
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: jupyter\nname: Jupyter\ndescription: >-\n  Project Jupyter is an open-source initiative that develops the software,\n  open standards, and services for interactive computing across dozens of\n  programming languages. The Jupyter ecosystem includes Jupyter Notebook,\n  JupyterLab, Jupyter Server, JupyterHub, the Jupyter messaging protocol,\n  and supporting client libraries.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Science\n  - Education\n  - Interactive Computing\n  - Notebooks\n  - Python\n  - Scientific Computing\nurl: https://raw.githubusercontent.com/api-evangelist/jupyter/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: jupyter:jupyter-notebook\n    name: Jupyter Notebook\n    description: >-\n      Original Jupyter web application and REST API for creating, editing,\n      and running notebooks. Includes the kernel messaging\
  \ protocol and\n      supporting OpenAPI, JSON Schema, and AsyncAPI artifacts.\n    humanURL: https://jupyter-notebook.readthedocs.io/\n    baseURL: http://localhost:8888\n    tags:\n      - Interactive Computing\n      - Kernels\n      - Notebooks\n      - REST API\n    properties:\n      - type: APIsYAML\n        url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/apis.yml\n      - type: Documentation\n        url: https://jupyter-notebook.readthedocs.io/en/stable/rest_api.html\n      - type: Repository\n        url: https://github.com/jupyter/notebook\n  - aid: jupyter:jupyter-server\n    name: Jupyter Server\n    description: >-\n      Backend that powers Jupyter Notebook, JupyterLab, and other Jupyter\n      web applications. Exposes the core REST API and the WebSocket\n      messaging endpoints used to communicate with kernels.\n    humanURL: https://jupyter-server.readthedocs.io/en/latest/developers/index.html\n    baseURL: http://localhost:8888/api\n\
  \    tags:\n      - Compute\n      - Kernels\n      - REST API\n      - Sessions\n    properties:\n      - type: APIsYAML\n        url: https://raw.githubusercontent.com/api-evangelist/jupyter-server/refs/heads/main/apis.yml\n      - type: Documentation\n        url: https://jupyter-server.readthedocs.io/en/latest/developers/rest-api.html\n      - type: Repository\n        url: https://github.com/jupyter-server/jupyter_server\n  - aid: jupyter:jupyterhub\n    name: JupyterHub\n    description: >-\n      Multi-user server for Jupyter notebooks. Manages authentication,\n      spawns and proxies multiple instances of the single-user Jupyter\n      notebook server, and exposes a REST API for users, groups, services,\n      tokens, and OAuth2.\n    humanURL: https://jupyterhub.readthedocs.io/\n    baseURL: http://localhost:8000/hub/api\n    tags:\n      - Authentication\n      - Hub\n      - Multi-User\n      - OAuth2\n    properties:\n      - type: APIsYAML\n        url: https://raw.githubusercontent.com/api-evangelist/jupyterhub/refs/heads/main/apis.yml\n\
  \      - type: Documentation\n        url: https://jupyterhub.readthedocs.io/en/stable/reference/rest-api.html\n      - type: Repository\n        url: https://github.com/jupyterhub/jupyterhub\n  - aid: jupyter:jupyterlab\n    name: JupyterLab\n    description: >-\n      Next-generation web-based interactive development environment for\n      notebooks, code, and data, with a JupyterLab Server REST API for\n      settings, workspaces, themes, translations, and licenses.\n    humanURL: https://jupyterlab.readthedocs.io/\n    baseURL: http://localhost:8888/lab/api\n    tags:\n      - Extensions\n      - IDE\n      - Interactive Computing\n      - Notebooks\n    properties:\n      - type: APIsYAML\n        url: https://raw.githubusercontent.com/api-evangelist/jupyterlab/refs/heads/main/apis.yml\n      - type: Documentation\n        url: https://jupyterlab.readthedocs.io/en/stable/\n      - type: Repository\n        url: https://github.com/jupyterlab/jupyterlab\ncommon:\n  - type: Website\n\
  \    url: https://jupyter.org\n  - type: Documentation\n    url: https://docs.jupyter.org/\n  - type: Blog\n    url: https://blog.jupyter.org/\n  - type: GitHubOrganization\n    url: https://github.com/jupyter\n  - type: Community\n    url: https://jupyter.org/community\n  - type: Support\n    url: https://discourse.jupyter.org/\n  - type: Security\n    url: https://jupyter.org/security\n  - type: YouTube\n    url: https://www.youtube.com/@ProjectJupyter\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/jupyter/refs/heads/main/apis.yml
tags:
- Data Science
- Education
- Interactive Computing
- Notebooks
- Python
- Scientific Computing
url: https://raw.githubusercontent.com/api-evangelist/jupyter/refs/heads/main/apis.yml
use_cases: []
---
