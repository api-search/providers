---
api_count: 2
api_specs:
- filename: jupyterlab-server-rest-api-openapi.yml
  format: yaml
  label: JupyterLab Server REST API
  slug: jupyterlab-server-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyterlab/refs/heads/main/openapi/jupyterlab-server-rest-api-openapi.yml
apis:
- description: REST API exposed by JupyterLab Server, the set of REST API services that JupyterLab depends on. Provides endpoints for user settings, workspaces, themes, translations, third-party license reports, and
  name: JupyterLab Server REST API
  slug: jupyterlab-server-rest-api
- description: JavaScript and TypeScript API used to build JupyterLab extensions and plugins. JupyterLab is composed of plugins that consume and provide services on the front-end application object.
  name: JupyterLab Extension API
  slug: jupyterlab-extension-api
common:
- title: ''
  type: Website
  url: https://jupyter.org
- title: ''
  type: Documentation
  url: https://jupyterlab.readthedocs.io/en/stable/
- title: ''
  type: GettingStarted
  url: https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html
- title: ''
  type: Installation
  url: https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html
- title: ''
  type: UserGuide
  url: https://jupyterlab.readthedocs.io/en/stable/user/index.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/jupyterlab
- title: ''
  type: Repository
  url: https://github.com/jupyterlab/jupyterlab
- title: ''
  type: Blog
  url: https://blog.jupyter.org/
- title: ''
  type: Community
  url: https://jupyter.org/community
- title: ''
  type: CodeOfConduct
  url: https://jupyter.org/governance/conduct/code_of_conduct.html
created: '2024-01-01'
description: JupyterLab is the next-generation web-based interactive development environment for notebooks, code, and data. It is served by Jupyter Server and ships with JupyterLab Server, which provides REST APIs for user-defined settings, workspaces, themes, translations, and license reports, alongside the JavaScript and TypeScript extension API used to build JupyterLab plugins.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Jupyterlab Context
  property_count: 0
  slug: jupyterlab-context
layout: provider
modified: '2026-04-28'
name: JupyterLab
skills: []
slug: jupyterlab
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: jupyterlab\nname: JupyterLab\ndescription: >-\n  JupyterLab is the next-generation web-based interactive development\n  environment for notebooks, code, and data. It is served by Jupyter\n  Server and ships with JupyterLab Server, which provides REST APIs for\n  user-defined settings, workspaces, themes, translations, and license\n  reports, alongside the JavaScript and TypeScript extension API used\n  to build JupyterLab plugins.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Science\n  - Extensions\n  - IDE\n  - Interactive Computing\n  - Notebooks\n  - Python\nurl: https://raw.githubusercontent.com/api-evangelist/jupyterlab/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: jupyterlab:jupyterlab-server-rest-api\n    name: JupyterLab Server REST API\n    description: >-\n      REST API exposed by JupyterLab Server, the set of REST API services\n\
  \      that JupyterLab depends on. Provides endpoints for user settings,\n      workspaces, themes, translations, third-party license reports, and\n      extension manager listings.\n    humanURL: https://jupyterlab-server.readthedocs.io/en/stable/api/rest.html\n    baseURL: http://localhost:8888/lab/api\n    tags:\n      - Licenses\n      - REST API\n      - Settings\n      - Themes\n      - Translations\n      - Workspaces\n    properties:\n      - type: Documentation\n        url: https://jupyterlab-server.readthedocs.io/en/stable/api/rest.html\n      - type: Repository\n        url: https://github.com/jupyterlab/jupyterlab_server\n      - type: OpenAPI\n        url: openapi/jupyterlab-server-rest-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/jupyterlab-workspace.json\n      - type: JSONSchema\n        url: json-schema/jupyterlab-setting.json\n      - type: JSONLDContext\n        url: json-ld/jupyterlab-context.jsonld\n  - aid: jupyterlab:jupyterlab-extension-api\n\
  \    name: JupyterLab Extension API\n    description: >-\n      JavaScript and TypeScript API used to build JupyterLab extensions\n      and plugins. JupyterLab is composed of plugins that consume and\n      provide services on the front-end application object.\n    humanURL: https://jupyterlab.readthedocs.io/en/stable/extension/extension_dev.html\n    tags:\n      - Extensions\n      - Frontend\n      - JavaScript\n      - Plugins\n      - TypeScript\n    properties:\n      - type: Documentation\n        url: https://jupyterlab.readthedocs.io/en/stable/extension/extension_dev.html\n      - type: Reference\n        url: https://jupyterlab.readthedocs.io/en/stable/api/modules.html\n      - type: Repository\n        url: https://github.com/jupyterlab/jupyterlab\ncommon:\n  - type: Website\n    url: https://jupyter.org\n  - type: Documentation\n    url: https://jupyterlab.readthedocs.io/en/stable/\n  - type: GettingStarted\n    url: https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html\n\
  \  - type: Installation\n    url: https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html\n  - type: UserGuide\n    url: https://jupyterlab.readthedocs.io/en/stable/user/index.html\n  - type: GitHubOrganization\n    url: https://github.com/jupyterlab\n  - type: Repository\n    url: https://github.com/jupyterlab/jupyterlab\n  - type: Blog\n    url: https://blog.jupyter.org/\n  - type: Community\n    url: https://jupyter.org/community\n  - type: CodeOfConduct\n    url: https://jupyter.org/governance/conduct/code_of_conduct.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/jupyterlab/refs/heads/main/apis.yml
tags:
- Data Science
- Extensions
- IDE
- Interactive Computing
- Notebooks
- Python
url: https://raw.githubusercontent.com/api-evangelist/jupyterlab/refs/heads/main/apis.yml
use_cases: []
---
