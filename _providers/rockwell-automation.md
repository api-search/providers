---
api_count: 5
apis:
- description: Plex by Rockwell Automation provides a Smart Manufacturing Platform ERP API with REST/JSON endpoints for customer orders, shipping, production, quality, and just-in-sequence parts delivery. Enables in
  name: Rockwell Automation Plex ERP API
  slug: plex-erp-api
- description: FactoryTalk DataMosaix is an Industrial DataOps solution that provides REST API access for industrial data management, contextualization, and analytics. Supports machine-to-machine (M2M) communication
  name: Rockwell Automation FactoryTalk DataMosaix API
  slug: factorytalk-datamosaix-api
- description: FactoryTalk Remote Access (FTRA) Web API provides RESTful HTTP interface for remote access management, enabling developers to integrate industrial device remote access capabilities into third-party ap
  name: Rockwell Automation FactoryTalk Remote Access Web API
  slug: factorytalk-remote-access-api
- description: The Studio 5000 Logix Designer Software Development Kit (LDSDK) provides programmatic access to Logix controller programming for CI/CD pipeline automation, version control integration, and export of L
  name: Rockwell Automation Logix Designer SDK
  slug: logix-designer-api
- description: Emulate3D Core API provides programmatic access to 3D simulation and digital twin capabilities for factory automation. Enables integration with Nvidia Omniverse and custom automation workflows via scr
  name: Rockwell Automation Emulate3D API
  slug: emulate3d-api
common:
- title: ''
  type: Website
  url: https://www.rockwellautomation.com
- title: ''
  type: Documentation
  url: https://www.rockwellautomation.com/en-us/support/documentation.html
- title: ''
  type: Portal
  url: https://developers.plex.com/docs
- title: ''
  type: GitHubOrganization
  url: https://github.com/RockwellAutomation
- title: ''
  type: Support
  url: https://www.rockwellautomation.com/en-us/support/
- title: ''
  type: PrivacyPolicy
  url: https://www.rockwellautomation.com/en-us/company/about-us/legal-notices/privacy-and-cookies-policy.html
- title: ''
  type: Blog
  url: https://www.rockwellautomation.com/en-us/company/news/blogs/
- title: ''
  type: JSONSchema
  url: json-schema/rockwell-automation-plex-order-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/rockwell-automation-plex-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/rockwell-automation-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/rockwell-automation-vocabulary.yml
created: '2026-03-21'
description: Rockwell Automation is a global provider of industrial automation and digital transformation solutions, helping manufacturers boost productivity, sustainability, and agility. The company offers a portfolio of hardware, software, and services including programmable logic controllers (PLCs), industrial networking, motor control, safety systems, and the FactoryTalk software suite for MES, SCADA, historian, remote access, and industrial data management.
features: []
image: ''
integrations: []
jsonld:
- class_count: 7
  name: Rockwell Automation Context
  property_count: 15
  slug: rockwell-automation-context
layout: provider
modified: '2026-05-02'
name: Rockwell Automation
skills: []
slug: rockwell-automation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rockwell-automation\nname: Rockwell Automation\ndescription: >-\n  Rockwell Automation is a global provider of industrial automation and digital\n  transformation solutions, helping manufacturers boost productivity, sustainability,\n  and agility. The company offers a portfolio of hardware, software, and services\n  including programmable logic controllers (PLCs), industrial networking, motor\n  control, safety systems, and the FactoryTalk software suite for MES, SCADA,\n  historian, remote access, and industrial data management.\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/rockwell-automation/refs/heads/main/apis.yml\ntags:\n  - Industrial Automation\n  - Manufacturing\n  - PLC\n  - SCADA\n  - IIoT\ncreated: '2026-03-21'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rockwell-automation:plex-erp-api\n    name: Rockwell Automation Plex ERP API\n    description: >-\n      Plex by Rockwell Automation provides a Smart Manufacturing\
  \ Platform ERP\n      API with REST/JSON endpoints for customer orders, shipping, production,\n      quality, and just-in-sequence parts delivery. Enables integration with\n      third-party systems and cloud services through role-based security.\n    tags:\n      - ERP\n      - Manufacturing\n      - Smart Manufacturing\n      - REST\n      - Industrial Automation\n    humanURL: https://plex.rockwellautomation.com/en-us/resources/enterprise-resource-planning-erp-apis.html\n    baseURL: https://api.plex.com\n    properties:\n      - url: https://plex.rockwellautomation.com/en-us/resources/enterprise-resource-planning-erp-apis.html\n        type: Documentation\n      - url: https://developers.plex.com/docs\n        type: Portal\n      - url: https://docs.plex.com/welcome\n        type: Documentation\n\n  - aid: rockwell-automation:factorytalk-datamosaix-api\n    name: Rockwell Automation FactoryTalk DataMosaix API\n    description: >-\n      FactoryTalk DataMosaix is an Industrial DataOps\
  \ solution that provides\n      REST API access for industrial data management, contextualization, and\n      analytics. Supports machine-to-machine (M2M) communication, data ingestion,\n      visualization, and integration with enterprise analytics tools via OpenAPI-specified\n      endpoints accessible through Swagger UI.\n    tags:\n      - Industrial Data\n      - DataOps\n      - Manufacturing\n      - REST\n      - Industrial Automation\n    humanURL: https://www.rockwellautomation.com/en-us/products/software/factorytalk/datamosaix.html\n    baseURL: https://datamosaix-portal.cloud.rockwellautomation.com\n    properties:\n      - url: https://www.rockwellautomation.com/en-us/docs/factorytalk-datamosaix/current/online-help-ditamap/api-reference.html\n        type: Documentation\n      - url: https://www.rockwellautomation.com/en-us/products/software/factorytalk/datamosaix.html\n        type: Website\n\n  - aid: rockwell-automation:factorytalk-remote-access-api\n    name: Rockwell\
  \ Automation FactoryTalk Remote Access Web API\n    description: >-\n      FactoryTalk Remote Access (FTRA) Web API provides RESTful HTTP interface\n      for remote access management, enabling developers to integrate industrial\n      device remote access capabilities into third-party applications and proprietary\n      systems. Supports GET, POST, PUT, PATCH, and DELETE operations for device\n      and session management.\n    tags:\n      - Remote Access\n      - Industrial Automation\n      - REST\n      - Manufacturing\n    humanURL: https://www.rockwellautomation.com/en-us/products/software/factorytalk/remote-access.html\n    baseURL: https://api.rockwellautomation.com\n    properties:\n      - url: https://www.rockwellautomation.com/en-pr/docs/factorytalk-remote-access/ubiquity-ftra-help/ftra-ditamap/web-api.html\n        type: Documentation\n\n  - aid: rockwell-automation:logix-designer-api\n    name: Rockwell Automation Logix Designer SDK\n    description: >-\n      The Studio\
  \ 5000 Logix Designer Software Development Kit (LDSDK) provides\n      programmatic access to Logix controller programming for CI/CD pipeline\n      automation, version control integration, and export of L5X controller files\n      for PLC program management.\n    tags:\n      - PLC\n      - Programming\n      - SDK\n      - Industrial Automation\n      - Manufacturing\n    humanURL: https://github.com/RockwellAutomation/ra-logix-designer-vcs-custom-tools\n    baseURL: https://github.com/RockwellAutomation\n    properties:\n      - url: https://github.com/RockwellAutomation/ra-logix-cicd\n        type: GitHubRepository\n      - url: https://github.com/RockwellAutomation/ra-logix-designer-vcs-custom-tools\n        type: GitHubRepository\n\n  - aid: rockwell-automation:emulate3d-api\n    name: Rockwell Automation Emulate3D API\n    description: >-\n      Emulate3D Core API provides programmatic access to 3D simulation and digital\n      twin capabilities for factory automation. Enables integration\
  \ with Nvidia\n      Omniverse and custom automation workflows via scripting interfaces.\n    tags:\n      - Digital Twin\n      - Simulation\n      - Industrial Automation\n      - Manufacturing\n    humanURL: https://github.com/RockwellAutomation/ra-emulate3d-core-samples\n    baseURL: https://github.com/RockwellAutomation\n    properties:\n      - url: https://github.com/RockwellAutomation/ra-emulate3d-core-samples\n        type: GitHubRepository\n      - url: https://github.com/RockwellAutomation/ra-emulate3d-kit-app-template\n        type: GitHubRepository\n\ncommon:\n  - url: https://www.rockwellautomation.com\n    type: Website\n  - url: https://www.rockwellautomation.com/en-us/support/documentation.html\n    type: Documentation\n  - url: https://developers.plex.com/docs\n    type: Portal\n  - url: https://github.com/RockwellAutomation\n    type: GitHubOrganization\n  - url: https://www.rockwellautomation.com/en-us/support/\n    type: Support\n  - url: https://www.rockwellautomation.com/en-us/company/about-us/legal-notices/privacy-and-cookies-policy.html\n\
  \    type: PrivacyPolicy\n  - url: https://www.rockwellautomation.com/en-us/company/news/blogs/\n    type: Blog\n  - url: json-schema/rockwell-automation-plex-order-schema.json\n    type: JSONSchema\n  - url: json-structure/rockwell-automation-plex-structure.json\n    type: JSONStructure\n  - url: json-ld/rockwell-automation-context.jsonld\n    type: JSONLDContext\n  - url: vocabulary/rockwell-automation-vocabulary.yml\n    type: Vocabulary\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rockwell-automation/refs/heads/main/apis.yml
tags:
- Industrial Automation
- Manufacturing
- PLC
- SCADA
- IIoT
url: https://raw.githubusercontent.com/api-evangelist/rockwell-automation/refs/heads/main/apis.yml
use_cases: []
---
