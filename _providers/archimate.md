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
