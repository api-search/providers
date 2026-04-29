---
api_count: 1
apis:
- description: API Blueprint is a high-level API description language using Markdown-based syntax for designing, documenting, and prototyping APIs. Files use the .apib extension with media type text/vnd.apiblueprint
  name: API Blueprint
  slug: api-blueprint
common:
- title: ''
  type: Website
  url: https://apiblueprint.org
- title: ''
  type: Documentation
  url: https://apiblueprint.org/documentation/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apiaryio
- title: ''
  type: TermsOfService
  url: https://github.com/apiaryio/api-blueprint/blob/master/LICENSE
created: '2026-03-25'
description: API Blueprint is a high-level API description language using Markdown-based syntax for designing, documenting, and prototyping web APIs. Created by Apiary and released under the MIT License, API Blueprint uses .apib files with a concise Markdown format that makes APIs accessible to both technical and non-technical stakeholders. The project is no longer actively maintained (all apiaryio GitHub repos are archived as of 2024) but remains a notable specification in API design history, influencing later formats like OpenAPI.
features:
- description: API Blueprint uses concise Markdown syntax making API descriptions readable by both developers and non-technical stakeholders. Files use the .apib extension with media type text/vnd.apiblueprint.
  name: Markdown-Based Syntax
- description: Supports reusable data structure definitions using MSON (Markdown Syntax for Object Notation) for describing complex request and response schemas.
  name: Data Structure Modeling
- description: API Blueprint documents can drive mock server generation for rapid prototyping and front-end development before backend implementation.
  name: Mock Server Generation
- description: The Dredd HTTP testing tool uses API Blueprint specs to run contract tests validating that API implementations match their documented contracts.
  name: Testing with Dredd
- description: API Blueprint evolution was governed through an RFC process similar to Rust and Django, with proposals submitted to the api-blueprint-rfcs repository.
  name: RFC-Driven Governance
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: API Blueprint was the native specification format of the Apiary platform (acquired by Oracle), which provided hosted documentation, mock servers, and testing.
  name: Apiary
- description: The canonical API Blueprint parser written in C++ with bindings for Node.js (drafter.js, drafter-npm) and other languages.
  name: Drafter Parser
- description: Language-agnostic HTTP API testing tool that validates live API implementations against API Blueprint or Swagger/OpenAPI specs.
  name: Dredd Testing Framework
- description: The swagger2blueprint tool converted Swagger API descriptions into API Blueprint format for migration workflows.
  name: Swagger Conversion
layout: provider
modified: '2026-04-19'
name: API Blueprint
skills: []
slug: api-blueprint
solutions: []
source_filename: apis.yml
source_yaml: "aid: api-blueprint\nname: API Blueprint\ndescription: >-\n  API Blueprint is a high-level API description language using Markdown-based\n  syntax for designing, documenting, and prototyping web APIs. Created by\n  Apiary and released under the MIT License, API Blueprint uses .apib files\n  with a concise Markdown format that makes APIs accessible to both technical\n  and non-technical stakeholders. The project is no longer actively maintained\n  (all apiaryio GitHub repos are archived as of 2024) but remains a notable\n  specification in API design history, influencing later formats like OpenAPI.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Design\n  - Specification Language\n  - Markdown\n  - Documentation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/api-blueprint/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: api-blueprint:api-blueprint\n\
  \    name: API Blueprint\n    description: >-\n      API Blueprint is a high-level API description language using Markdown-based\n      syntax for designing, documenting, and prototyping APIs. Files use the\n      .apib extension with media type text/vnd.apiblueprint. The project was\n      archived in 2024 after being developed by Apiary (acquired by Oracle).\n    humanURL: https://apiblueprint.org\n    tags:\n      - API Design\n      - Specification Language\n      - Markdown\n    properties:\n      - type: Documentation\n        url: https://apiblueprint.org/documentation/\n      - type: GitHubRepository\n        url: https://github.com/apiaryio/api-blueprint\n      - type: Specification\n        url: https://github.com/apiaryio/api-blueprint/blob/master/API%20Blueprint%20Specification.md\n      - type: GettingStarted\n        url: https://apiblueprint.org/documentation/tutorial.html\ncommon:\n  - type: Website\n    url: https://apiblueprint.org\n  - type: Documentation\n    url: https://apiblueprint.org/documentation/\n\
  \  - type: GitHubOrganization\n    url: https://github.com/apiaryio\n  - type: TermsOfService\n    url: https://github.com/apiaryio/api-blueprint/blob/master/LICENSE\n  - type: Features\n    data:\n      - name: Markdown-Based Syntax\n        description: >-\n          API Blueprint uses concise Markdown syntax making API descriptions\n          readable by both developers and non-technical stakeholders. Files\n          use the .apib extension with media type text/vnd.apiblueprint.\n      - name: Data Structure Modeling\n        description: >-\n          Supports reusable data structure definitions using MSON (Markdown\n          Syntax for Object Notation) for describing complex request and\n          response schemas.\n      - name: Mock Server Generation\n        description: >-\n          API Blueprint documents can drive mock server generation for rapid\n          prototyping and front-end development before backend implementation.\n      - name: Testing with Dredd\n        description:\
  \ >-\n          The Dredd HTTP testing tool uses API Blueprint specs to run\n          contract tests validating that API implementations match their\n          documented contracts.\n      - name: RFC-Driven Governance\n        description: >-\n          API Blueprint evolution was governed through an RFC process similar\n          to Rust and Django, with proposals submitted to the api-blueprint-rfcs\n          repository.\n  - type: UseCases\n    data:\n      - name: API Documentation\n        description: >-\n          Write human-readable API documentation in Markdown that doubles as\n          a machine-parseable specification for tooling.\n      - name: Contract Testing\n        description: >-\n          Use API Blueprint specs with Dredd to verify that API implementations\n          conform to their documented contracts in CI pipelines.\n      - name: API Prototyping\n        description: >-\n          Rapidly prototype APIs by writing Blueprint specs first, then\n          generating\
  \ mock servers from the specification.\n  - type: Integrations\n    data:\n      - name: Apiary\n        description: >-\n          API Blueprint was the native specification format of the Apiary\n          platform (acquired by Oracle), which provided hosted documentation,\n          mock servers, and testing.\n      - name: Drafter Parser\n        description: >-\n          The canonical API Blueprint parser written in C++ with bindings\n          for Node.js (drafter.js, drafter-npm) and other languages.\n      - name: Dredd Testing Framework\n        description: >-\n          Language-agnostic HTTP API testing tool that validates live API\n          implementations against API Blueprint or Swagger/OpenAPI specs.\n      - name: Swagger Conversion\n        description: >-\n          The swagger2blueprint tool converted Swagger API descriptions into\n          API Blueprint format for migration workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/api-blueprint/refs/heads/main/apis.yml
tags:
- API Design
- Specification Language
- Markdown
- Documentation
url: https://raw.githubusercontent.com/api-evangelist/api-blueprint/refs/heads/main/apis.yml
use_cases:
- description: Write human-readable API documentation in Markdown that doubles as a machine-parseable specification for tooling.
  name: API Documentation
- description: Use API Blueprint specs with Dredd to verify that API implementations conform to their documented contracts in CI pipelines.
  name: Contract Testing
- description: Rapidly prototype APIs by writing Blueprint specs first, then generating mock servers from the specification.
  name: API Prototyping
---
