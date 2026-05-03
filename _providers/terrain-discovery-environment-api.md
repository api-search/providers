---
api_count: 1
api_specs:
- filename: terrain-openapi.yml
  format: yaml
  label: Terrain API
  slug: terrain-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/terrain-discovery-environment-api/refs/heads/main/openapi/terrain-openapi.yml
apis:
- description: 'The Terrain API is the main entry-point REST service for the CyVerse Discovery Environment. It handles authentication via Keycloak JWT tokens and orchestrates calls to backend services for filesystem '
  name: Terrain API
  slug: terrain-api
capabilities:
- description: 'Unified workflow capability for bioinformatics and data science on the CyVerse Discovery Environment. Enables researchers, bioinformaticians, and data scientists to manage data in iRODS, discover and '
  name: CyVerse Data Science Workflow
  slug: data-science-workflow
common:
- title: ''
  type: Portal
  url: https://cyverse.org/Science-APIs
- title: ''
  type: Documentation
  url: https://docs.cyverse.org
- title: ''
  type: Repository
  url: https://github.com/cyverse-de/terrain
- title: ''
  type: Portal
  url: https://de.cyverse.org
- title: ''
  type: Webinar
  url: https://cyverse.org/webinar_TerrainAPI
- title: ''
  type: Authentication
  url: https://docs.cyverse.org/services/getting_started/
created: '2026-03-16'
description: Terrain is the primary REST API gateway for CyVerse's Discovery Environment (DE), an open-source data science workbench. Terrain validates user authentication via Keycloak/JWT and orchestrates calls to backend microservices covering filesystem operations, application management, data analysis, metadata annotation, notifications, and persistent identifier management.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 29
  name: Terrain Discovery Environment Api Context
  property_count: 0
  slug: terrain-discovery-environment-api-context
layout: provider
modified: '2026-05-03'
name: Terrain Discovery Environment API
rules:
- name: Terrain Discovery Environment API API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 2
    warn: 5
  slug: terrain-rules
skills: []
slug: terrain-discovery-environment-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: terrain-discovery-environment-api\nname: Terrain Discovery Environment API\ndescription: >-\n  Terrain is the primary REST API gateway for CyVerse's Discovery Environment (DE),\n  an open-source data science workbench. Terrain validates user authentication via\n  Keycloak/JWT and orchestrates calls to backend microservices covering filesystem\n  operations, application management, data analysis, metadata annotation, notifications,\n  and persistent identifier management.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Bioinformatics\n  - Data Science\n  - Life Sciences\n  - Filesystem\n  - Cloud Computing\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/terrain-discovery-environment-api/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: terrain-discovery-environment-api:terrain-api\n    name: Terrain API\n    description:\
  \ >-\n      The Terrain API is the main entry-point REST service for the CyVerse\n      Discovery Environment. It handles authentication via Keycloak JWT tokens\n      and orchestrates calls to backend services for filesystem management,\n      app execution, data analysis, metadata, notifications, and more.\n    humanURL: https://cyverse.org/Science-APIs\n    baseURL: https://de.cyverse.org/terrain\n    tags:\n      - Bioinformatics\n      - Filesystem\n      - Data Analysis\n      - Applications\n      - Notifications\n    properties:\n      - url: https://docs.cyverse.org/services/api_overview/\n        type: Documentation\n      - url: https://de.cyverse.org/terrain/docs\n        type: SwaggerUI\n      - url: https://github.com/cyverse-de/terrain\n        type: Repository\n      - url: https://raw.githubusercontent.com/api-evangelist/terrain-discovery-environment-api/refs/heads/main/openapi/terrain-openapi.yml\n        type: OpenAPI\ncommon:\n  - name: CyVerse Developer Portal\n  \
  \  url: https://cyverse.org/Science-APIs\n    type: Portal\n  - name: CyVerse Documentation\n    url: https://docs.cyverse.org\n    type: Documentation\n  - name: Terrain GitHub Repository\n    url: https://github.com/cyverse-de/terrain\n    type: Repository\n  - name: Discovery Environment\n    url: https://de.cyverse.org\n    type: Portal\n  - name: Terrain API Webinar\n    url: https://cyverse.org/webinar_TerrainAPI\n    type: Webinar\n  - name: Keycloak Authentication\n    url: https://docs.cyverse.org/services/getting_started/\n    type: Authentication\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/terrain-discovery-environment-api/refs/heads/main/apis.yml
tags:
- Bioinformatics
- Data Science
- Life Sciences
- Filesystem
- Cloud Computing
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/terrain-discovery-environment-api/refs/heads/main/apis.yml
use_cases: []
---
