---
api_count: 4
api_specs:
- filename: jupyter-notebook-rest-api-openapi.yml
  format: yaml
  label: Jupyter Notebook REST API
  slug: jupyter-notebook-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/openapi/jupyter-notebook-rest-api-openapi.yml
- filename: jupyter-kernel-gateway-api-openapi.yml
  format: yaml
  label: Jupyter Kernel Gateway API
  slug: jupyter-kernel-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/openapi/jupyter-kernel-gateway-api-openapi.yml
- filename: jupyterhub-rest-api-openapi.yml
  format: yaml
  label: JupyterHub REST API
  slug: jupyterhub-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/openapi/jupyterhub-rest-api-openapi.yml
- filename: jupyter-kernel-messaging-asyncapi.yml
  format: yaml
  label: Jupyter Kernel Messaging Protocol
  slug: jupyter-kernel-messaging
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/asyncapi/jupyter-kernel-messaging-asyncapi.yml
apis:
- description: REST API for managing and interacting with Jupyter Notebook servers, including kernels, sessions, contents (notebooks and files), terminals, and kernel specifications.
  name: Jupyter Notebook REST API
  slug: jupyter-notebook-rest-api
- description: Web server that provides headless access to Jupyter kernels for remote execution of code, with kernel and notebook HTTP modes.
  name: Jupyter Kernel Gateway API
  slug: jupyter-kernel-gateway-api
- description: Multi-user server management API for spawning, managing, and proxying multiple instances of single-user Jupyter notebook servers.
  name: JupyterHub REST API
  slug: jupyterhub-rest-api
- description: WebSocket-based messaging protocol for communication between Jupyter clients and computational kernels. Supports code execution, introspection, completion, and rich output over shell, IOPub, stdin, an
  name: Jupyter Kernel Messaging Protocol
  slug: jupyter-kernel-messaging
asyncapis:
- description: 'The Jupyter Kernel Messaging Protocol defines the WebSocket-based communication between Jupyter clients (notebooks, consoles) and computational kernels. Messages are exchanged over WebSocket channels '
  name: Jupyter Kernel Messaging Protocol
  slug: jupyter-kernel-messaging-asyncapi
common:
- title: ''
  type: Website
  url: https://jupyter.org
- title: ''
  type: Documentation
  url: https://docs.jupyter.org/en/latest/
- title: ''
  type: GettingStarted
  url: https://docs.jupyter.org/en/latest/start/index.html
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
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/jupyter-notebook
created: '2024-01-15'
description: Jupyter Notebook is the original open-source web application for creating and sharing computational documents that contain live code, equations, visualizations, and narrative text. The Jupyter Notebook server exposes a REST API for managing notebooks, files, kernels, sessions, and terminals, and uses the WebSocket-based Jupyter messaging protocol to communicate with kernels.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Jupyter Notebook Context
  property_count: 44
  slug: jupyter-notebook-context
layout: provider
modified: '2026-04-28'
name: Jupyter Notebook
skills: []
slug: jupyter-notebook
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: jupyter-notebook\nname: Jupyter Notebook\ndescription: >-\n  Jupyter Notebook is the original open-source web application for creating\n  and sharing computational documents that contain live code, equations,\n  visualizations, and narrative text. The Jupyter Notebook server exposes\n  a REST API for managing notebooks, files, kernels, sessions, and\n  terminals, and uses the WebSocket-based Jupyter messaging protocol to\n  communicate with kernels.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Science\n  - Interactive Computing\n  - Jupyter\n  - Machine Learning\n  - Notebooks\n  - Python\nurl: https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: jupyter-notebook:jupyter-notebook-rest-api\n    name: Jupyter Notebook REST API\n    description: >-\n      REST API for managing\
  \ and interacting with Jupyter Notebook servers,\n      including kernels, sessions, contents (notebooks and files),\n      terminals, and kernel specifications.\n    humanURL: https://jupyter-notebook.readthedocs.io/\n    baseURL: http://localhost:8888/api\n    tags:\n      - Contents\n      - Files\n      - Kernels\n      - Notebooks\n      - REST API\n      - Sessions\n    properties:\n      - type: Documentation\n        url: https://jupyter-notebook.readthedocs.io/en/stable/rest_api.html\n      - type: Repository\n        url: https://github.com/jupyter/notebook\n      - type: OpenAPI\n        url: openapi/jupyter-notebook-rest-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/jupyter-notebook-document.json\n      - type: JSONSchema\n        url: json-schema/jupyter-contents-model.json\n      - type: JSONSchema\n        url: json-schema/jupyter-kernel-spec.json\n      - type: JSONLDContext\n        url: json-ld/jupyter-notebook-context.jsonld\n  - aid: jupyter-notebook:jupyter-kernel-gateway-api\n\
  \    name: Jupyter Kernel Gateway API\n    description: >-\n      Web server that provides headless access to Jupyter kernels for\n      remote execution of code, with kernel and notebook HTTP modes.\n    humanURL: https://jupyter-kernel-gateway.readthedocs.io/\n    baseURL: http://localhost:8888\n    tags:\n      - Execution\n      - Gateway\n      - Headless\n      - Kernels\n    properties:\n      - type: Documentation\n        url: https://jupyter-kernel-gateway.readthedocs.io/en/latest/\n      - type: Repository\n        url: https://github.com/jupyter-server/kernel_gateway\n      - type: OpenAPI\n        url: openapi/jupyter-kernel-gateway-api-openapi.yml\n  - aid: jupyter-notebook:jupyterhub-rest-api\n    name: JupyterHub REST API\n    description: >-\n      Multi-user server management API for spawning, managing, and\n      proxying multiple instances of single-user Jupyter notebook servers.\n    humanURL: https://jupyterhub.readthedocs.io/\n    baseURL: http://localhost:8000/hub/api\n\
  \    tags:\n      - Authentication\n      - Hub\n      - Multi-User\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://jupyterhub.readthedocs.io/en/stable/reference/rest-api.html\n      - type: Repository\n        url: https://github.com/jupyterhub/jupyterhub\n      - type: OpenAPI\n        url: openapi/jupyterhub-rest-api-openapi.yml\n  - aid: jupyter-notebook:jupyter-kernel-messaging\n    name: Jupyter Kernel Messaging Protocol\n    description: >-\n      WebSocket-based messaging protocol for communication between\n      Jupyter clients and computational kernels. Supports code execution,\n      introspection, completion, and rich output over shell, IOPub, stdin,\n      and control channels.\n    humanURL: https://jupyter-client.readthedocs.io/en/stable/messaging.html\n    baseURL: ws://localhost:8888\n    tags:\n      - Kernels\n      - Messaging\n      - Real-Time\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://jupyter-client.readthedocs.io/en/stable/messaging.html\n\
  \      - type: Repository\n        url: https://github.com/jupyter/jupyter_client\n      - type: AsyncAPI\n        url: asyncapi/jupyter-kernel-messaging-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/jupyter-kernel-message.json\n      - type: JSONLDContext\n        url: json-ld/jupyter-notebook-context.jsonld\ncommon:\n  - type: Website\n    url: https://jupyter.org\n  - type: Documentation\n    url: https://docs.jupyter.org/en/latest/\n  - type: GettingStarted\n    url: https://docs.jupyter.org/en/latest/start/index.html\n  - type: Blog\n    url: https://blog.jupyter.org/\n  - type: GitHubOrganization\n    url: https://github.com/jupyter\n  - type: Community\n    url: https://jupyter.org/community\n  - type: Support\n    url: https://discourse.jupyter.org/\n  - type: Security\n    url: https://jupyter.org/security\n  - type: YouTube\n    url: https://www.youtube.com/@ProjectJupyter\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/jupyter-notebook\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/apis.yml
tags:
- Data Science
- Interactive Computing
- Jupyter
- Machine Learning
- Notebooks
- Python
url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/apis.yml
use_cases: []
---
