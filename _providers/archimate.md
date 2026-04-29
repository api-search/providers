---
api_count: 2
apis:
- description: API for exchanging ArchiMate models between tools and repositories using the Open Group ArchiMate Model Exchange File Format (AMEFF). Enables interoperability between enterprise architecture tools.
  name: ArchiMate Model Exchange API
  slug: archimate-model-exchange-api
- description: RESTful API for accessing and managing ArchiMate models, elements, relationships, and views stored in a central enterprise architecture repository.
  name: ArchiMate Repository API
  slug: archimate-repository-api
common:
- title: ''
  type: Portal
  url: https://www.opengroup.org/archimate-forum
- title: ''
  type: Documentation
  url: https://pubs.opengroup.org/architecture/archimate32-doc/
- title: ''
  type: GettingStarted
  url: https://www.opengroup.org/archimate-forum/archimate-overview
- title: ''
  type: GitHubOrganization
  url: https://github.com/archimate-org
- title: ''
  type: Support
  url: https://www.opengroup.org/archimate-forum/forums
- title: ''
  type: Blog
  url: https://blog.opengroup.org/tag/archimate/
- title: ''
  type: Training
  url: https://www.opengroup.org/certifications/archimate
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/archimate/refs/heads/main/rules/archimate-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/archimate/refs/heads/main/vocabulary/archimate-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/archimate/refs/heads/main/json-ld/archimate-model-exchange-api-context.jsonld
created: '2024-01-01'
description: ArchiMate is an open and independent enterprise architecture modeling language developed by The Open Group, supporting description, analysis and visualization of architecture within and across business domains in an unambiguous way. The current version is ArchiMate 3.2.
features:
- description: Standardized language for modeling business, application, and technology architecture layers.
  name: Enterprise Architecture Modeling
- description: ArchiMate Model Exchange File Format (AMEFF) for tool interoperability using XML.
  name: Model Exchange Format
- description: Business, Application, and Technology layers for comprehensive EA modeling.
  name: Three Architecture Layers
- description: Strategy and motivation aspect elements for stakeholder and driver modeling.
  name: Motivation and Strategy
- description: Work package and implementation elements for roadmap and migration planning.
  name: Implementation and Migration
- description: Supported by 20+ enterprise architecture tools including Archi, Sparx EA, BiZZdesign, and MEGA.
  name: Tool Ecosystem
- description: Open Group standard freely available for implementation without licensing fees.
  name: Open Standard
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Open source ArchiMate modelling tool with full AMEFF import/export support.
  name: Archi
- description: Commercial EA tool with ArchiMate 3 profile and exchange format support.
  name: Sparx Enterprise Architect
- description: Enterprise architecture platform with native ArchiMate support.
  name: BiZZdesign
- description: Enterprise architecture management platform supporting ArchiMate standard.
  name: MEGA HOPEX
- description: ArchiMate is the recommended modeling language for TOGAF enterprise architecture framework.
  name: TOGAF
jsonld:
- class_count: 9
  name: Archimate Model Exchange Api Context
  property_count: 22
  slug: archimate-model-exchange-api-context
layout: provider
modified: '2026-04-19'
name: ArchiMate
rules:
- name: ArchiMate API Rules
  rule_count: 14
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 3
  slug: archimate-spectral-rules
skills: []
slug: archimate
solutions: []
source_filename: apis.yml
source_yaml: "aid: archimate\nname: ArchiMate\ndescription: ArchiMate is an open and independent enterprise architecture modeling language developed by The Open Group, supporting description, analysis and visualization of architecture within and \n  across business domains in an unambiguous way. The current version is ArchiMate 3.2.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Enterprise Architecture\n- Architecture Framework\n- Modeling Language\n- Business Architecture\n- Technology Architecture\n- Standard\n- Open Group\nurl: https://raw.githubusercontent.com/api-evangelist/archimate/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: archimate:archimate-model-exchange-api\n  name: ArchiMate Model Exchange API\n  description: API for exchanging ArchiMate models between tools and repositories using the Open Group ArchiMate Model Exchange File Format (AMEFF). Enables\
  \ interoperability between enterprise \n    architecture tools.\n  humanURL: https://www.opengroup.org/archimate-forum/archimate-overview\n  tags:\n  - Enterprise Architecture\n  - Model Exchange\n  - Interoperability\n  - XML Schema\n  properties:\n  - type: Documentation\n    url: https://pubs.opengroup.org/architecture/archimate3-doc/\n  - type: GettingStarted\n    url: https://www.opengroup.org/archimate-forum/archimate-overview\n  - type: APIReference\n    url: https://pubs.opengroup.org/architecture/archimate3-doc/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/archimate/refs/heads/main/openapi/archimate-model-exchange-api.yaml\n- aid: archimate:archimate-repository-api\n  name: ArchiMate Repository API\n  description: RESTful API for accessing and managing ArchiMate models, elements, relationships, and views stored in a central enterprise architecture repository.\n  humanURL: https://www.opengroup.org/archimate-forum\n  tags:\n  - Repository Management\n\
  \  - Model Management\n  - REST API\n  - Enterprise Architecture\n  properties:\n  - type: Documentation\n    url: https://pubs.opengroup.org/architecture/archimate3-doc/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/archimate/refs/heads/main/openapi/archimate-repository-api.yaml\ncommon:\n- type: Portal\n  url: https://www.opengroup.org/archimate-forum\n- type: Documentation\n  url: https://pubs.opengroup.org/architecture/archimate32-doc/\n- type: GettingStarted\n  url: https://www.opengroup.org/archimate-forum/archimate-overview\n- type: GitHubOrganization\n  url: https://github.com/archimate-org\n- type: Support\n  url: https://www.opengroup.org/archimate-forum/forums\n- type: Blog\n  url: https://blog.opengroup.org/tag/archimate/\n- type: Training\n  url: https://www.opengroup.org/certifications/archimate\n- type: Features\n  data:\n  - name: Enterprise Architecture Modeling\n    description: Standardized language for modeling business, application,\
  \ and technology architecture layers.\n  - name: Model Exchange Format\n    description: ArchiMate Model Exchange File Format (AMEFF) for tool interoperability using XML.\n  - name: Three Architecture Layers\n    description: Business, Application, and Technology layers for comprehensive EA modeling.\n  - name: Motivation and Strategy\n    description: Strategy and motivation aspect elements for stakeholder and driver modeling.\n  - name: Implementation and Migration\n    description: Work package and implementation elements for roadmap and migration planning.\n  - name: Tool Ecosystem\n    description: Supported by 20+ enterprise architecture tools including Archi, Sparx EA, BiZZdesign, and MEGA.\n  - name: Open Standard\n    description: Open Group standard freely available for implementation without licensing fees.\n- type: UseCases\n  data:\n  - name: Enterprise Architecture Documentation\n    description: Document and communicate enterprise architecture across business, application,\
  \ and technology layers.\n  - name: Architecture Analysis\n    description: Analyze dependencies, impacts, and gaps in enterprise architecture using standardized notation.\n  - name: Tool Migration\n    description: Migrate ArchiMate models between EA tools using the standardized exchange format.\n  - name: Architecture Governance\n    description: Establish governance controls and compliance checking for enterprise architecture standards.\n  - name: IT Portfolio Management\n    description: Manage IT application portfolios and rationalize technology investments using ArchiMate models.\n- type: Integrations\n  data:\n  - name: Archi\n    description: Open source ArchiMate modelling tool with full AMEFF import/export support.\n  - name: Sparx Enterprise Architect\n    description: Commercial EA tool with ArchiMate 3 profile and exchange format support.\n  - name: BiZZdesign\n    description: Enterprise architecture platform with native ArchiMate support.\n  - name: MEGA HOPEX\n    description:\
  \ Enterprise architecture management platform supporting ArchiMate standard.\n  - name: TOGAF\n    description: ArchiMate is the recommended modeling language for TOGAF enterprise architecture framework.\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/archimate/refs/heads/main/rules/archimate-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/archimate/refs/heads/main/vocabulary/archimate-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/archimate/refs/heads/main/json-ld/archimate-model-exchange-api-context.jsonld\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/archimate/refs/heads/main/apis.yml
tags:
- Enterprise Architecture
- Architecture Framework
- Modeling Language
- Business Architecture
- Technology Architecture
- Standard
- Open Group
url: https://raw.githubusercontent.com/api-evangelist/archimate/refs/heads/main/apis.yml
use_cases:
- description: Document and communicate enterprise architecture across business, application, and technology layers.
  name: Enterprise Architecture Documentation
- description: Analyze dependencies, impacts, and gaps in enterprise architecture using standardized notation.
  name: Architecture Analysis
- description: Migrate ArchiMate models between EA tools using the standardized exchange format.
  name: Tool Migration
- description: Establish governance controls and compliance checking for enterprise architecture standards.
  name: Architecture Governance
- description: Manage IT application portfolios and rationalize technology investments using ArchiMate models.
  name: IT Portfolio Management
---
