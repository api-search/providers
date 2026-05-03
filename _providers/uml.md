---
api_count: 2
api_specs:
- filename: plantuml-server-openapi.yml
  format: yaml
  label: PlantUML Server API
  slug: plantuml-server
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uml/refs/heads/main/openapi/plantuml-server-openapi.yml
- filename: kroki-openapi.yml
  format: yaml
  label: Kroki Diagram API
  slug: kroki
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uml/refs/heads/main/openapi/kroki-openapi.yml
apis:
- description: 'PlantUML Server provides a public REST API for generating UML diagrams from plain-text descriptions. Diagrams are encoded in the URL path using a deflate + base64 scheme. The server supports multiple '
  name: PlantUML Server API
  slug: plantuml-server
- description: Kroki provides a unified HTTP API for generating diagrams from textual descriptions. It supports over 20 diagram types including PlantUML, Mermaid, GraphViz, BlockDiag, BPMN, C4, Structurizr, Excalidr
  name: Kroki Diagram API
  slug: kroki
common:
- title: ''
  type: GitHub Org
  url: https://github.com/plantuml
- title: ''
  type: GitHub Org
  url: https://github.com/yuzutech
- title: ''
  type: Website
  url: https://www.omg.org/uml/
- title: ''
  type: Standard
  url: https://www.omg.org/spec/UML/
- title: ''
  type: Wikipedia
  url: https://en.wikipedia.org/wiki/Unified_Modeling_Language
- title: ''
  type: GitHub
  url: https://github.com/plantuml/plantuml
- title: ''
  type: GitHub
  url: https://github.com/yuzutech/kroki
- title: ''
  type: Documentation
  url: https://plantuml.com/
- title: ''
  type: Documentation
  url: https://docs.kroki.io/kroki/
- title: ''
  type: JSON-LD
  url: json-ld/uml-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/uml-vocabulary.yml
- title: ''
  type: JSONSchema
  url: json-schema/uml-diagram-schema.json
- title: ''
  type: Spectral Rules
  url: rules/uml-rules.yml
created: '2025-01-01'
description: UML (Unified Modeling Language) is the standard modeling language for software architecture, system design, and technical documentation. Governed by the Object Management Group (OMG), UML defines a set of notation conventions and diagram types — class, sequence, activity, use case, state, component, deployment, and more — used across the software development lifecycle. This collection profiles the ecosystem of tools, APIs, and services that work with UML diagrams programmatically.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Uml Context
  property_count: 10
  slug: uml-context
layout: provider
modified: '2026-05-03'
name: UML
rules:
- name: UML API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: uml-rules
skills: []
slug: uml
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: uml\nname: UML\ndescription: >-\n  UML (Unified Modeling Language) is the standard modeling language for software\n  architecture, system design, and technical documentation. Governed by the Object\n  Management Group (OMG), UML defines a set of notation conventions and diagram\n  types — class, sequence, activity, use case, state, component, deployment, and\n  more — used across the software development lifecycle. This collection profiles\n  the ecosystem of tools, APIs, and services that work with UML diagrams\n  programmatically.\nurl: https://raw.githubusercontent.com/api-evangelist/uml/refs/heads/main/apis.yml\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - UML\n  - Modeling\n  - Diagrams\n  - Software Architecture\n  - Design\n  - Standards\ncreated: '2025-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: uml:plantuml-server\n    name: PlantUML Server API\n    tags:\n      - UML\n\
  \      - Diagrams\n      - PlantUML\n      - Text-To-Diagram\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://www.plantuml.com/plantuml\n    humanURL: https://plantuml.com/\n    properties:\n      - url: https://plantuml.com/\n        type: Documentation\n      - url: https://deepwiki.com/plantuml/plantuml-server/6-api-reference\n        type: Documentation\n      - url: openapi/plantuml-server-openapi.yml\n        type: OpenAPI\n    description: >-\n      PlantUML Server provides a public REST API for generating UML diagrams\n      from plain-text descriptions. Diagrams are encoded in the URL path using\n      a deflate + base64 scheme. The server supports multiple output formats\n      including PNG, SVG, ASCII art, and PDF. Diagram types include class,\n      sequence, activity, component, state, use case, deployment, timing, and\n      more.\n  - aid: uml:kroki\n    name: Kroki Diagram API\n    tags:\n      - UML\n      -\
  \ Diagrams\n      - Multi-Format\n      - Text-To-Diagram\n      - Open Source\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://kroki.io\n    humanURL: https://kroki.io/\n    properties:\n      - url: https://docs.kroki.io/kroki/\n        type: Documentation\n      - url: https://docs.kroki.io/kroki/setup/usage/\n        type: Getting Started\n      - url: openapi/kroki-openapi.yml\n        type: OpenAPI\n    description: >-\n      Kroki provides a unified HTTP API for generating diagrams from textual\n      descriptions. It supports over 20 diagram types including PlantUML,\n      Mermaid, GraphViz, BlockDiag, BPMN, C4, Structurizr, Excalidraw, Vega,\n      and WaveDrom. Requests can be sent as GET (diagram encoded in URL) or\n      POST (diagram in request body). Output formats include SVG, PNG, PDF, and\n      JPEG. Kroki is open source and can be self-hosted.\ncommon:\n  - type: GitHub Org\n    url: https://github.com/plantuml\n\
  \  - type: GitHub Org\n    url: https://github.com/yuzutech\n  - type: Website\n    url: https://www.omg.org/uml/\n  - type: Standard\n    url: https://www.omg.org/spec/UML/\n  - type: Wikipedia\n    url: https://en.wikipedia.org/wiki/Unified_Modeling_Language\n  - type: GitHub\n    url: https://github.com/plantuml/plantuml\n  - type: GitHub\n    url: https://github.com/yuzutech/kroki\n  - type: Documentation\n    url: https://plantuml.com/\n  - type: Documentation\n    url: https://docs.kroki.io/kroki/\n  - type: JSON-LD\n    url: json-ld/uml-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/uml-vocabulary.yml\n  - type: JSONSchema\n    url: json-schema/uml-diagram-schema.json\n  - type: Spectral Rules\n    url: rules/uml-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/uml/refs/heads/main/apis.yml
tags:
- UML
- Modeling
- Diagrams
- Software Architecture
- Design
- Standards
url: https://raw.githubusercontent.com/api-evangelist/uml/refs/heads/main/apis.yml
use_cases: []
---
