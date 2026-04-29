---
api_count: 2
apis:
- description: The Apiary API provides programmatic access to manage API projects, documentation, and team collaboration. It allows creating and updating API Blueprint and Swagger/OpenAPI documents, managing team me
  name: Apiary API
  slug: apiary-api
- description: API Blueprint is a high-level API design language created by Apiary for designing and documenting web APIs. It uses a Markdown-based syntax that is human-readable and machine-parseable, enabling teams
  name: API Blueprint
  slug: api-blueprint
common:
- title: ''
  type: Website
  url: https://apiary.io
- title: ''
  type: Documentation
  url: https://help.apiary.io
- title: ''
  type: GitHubOrganization
  url: https://github.com/apiaryio
- title: ''
  type: Blog
  url: https://blog.apiary.io
- title: ''
  type: Pricing
  url: https://apiary.io/plans
- title: ''
  type: Login
  url: https://login.apiary.io
- title: ''
  type: SignUp
  url: https://login.apiary.io/register
- title: ''
  type: Support
  url: https://help.apiary.io
- title: ''
  type: PrivacyPolicy
  url: https://www.oracle.com/legal/privacy/
- title: ''
  type: TermsOfService
  url: https://www.oracle.com/legal/terms.html
created: '2026-03-25'
description: Apiary is an API design and documentation platform, now part of Oracle Cloud Infrastructure. With 486,000+ users and 591,000+ APIs managed, it uses API Blueprint and Swagger/OpenAPI specifications to produce interactive API documentation, mock servers, automated testing, and collaborative API design workflows. Apiary enables teams to design APIs before writing code, generate documentation automatically, and validate implementations against specifications.
features:
- description: Native support for API Blueprint, a high-level Markdown-based API description language for collaborative design.
  name: API Blueprint Support
- description: Import and work with Swagger and OpenAPI specifications alongside API Blueprint documents.
  name: OpenAPI/Swagger Support
- description: Auto-generate interactive documentation from API specs with a built-in API console for live testing.
  name: Interactive API Documentation
- description: Instant mock servers generated from API specs allowing frontend development before backend is ready.
  name: Mock Servers
- description: Run automated tests against API implementations using Dredd, the open-source API testing framework.
  name: Automated API Testing
- description: Team-based API design with version history, commenting, and shared workspaces.
  name: Collaborative Workflows
- description: Apiary CLI for integrating API design and testing workflows into CI/CD pipelines.
  name: CLI Integration
- description: Maintains Dredd (testing), Gavel (validation), and API Blueprint as open-source projects.
  name: Open Source Tooling
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-19'
name: Apiary
skills: []
slug: apiary
solutions: []
source_yaml: "aid: apiary\nname: Apiary\ndescription: >-\n  Apiary is an API design and documentation platform, now part of Oracle Cloud\n  Infrastructure. With 486,000+ users and 591,000+ APIs managed, it uses API\n  Blueprint and Swagger/OpenAPI specifications to produce interactive API\n  documentation, mock servers, automated testing, and collaborative API design\n  workflows. Apiary enables teams to design APIs before writing code, generate\n  documentation automatically, and validate implementations against specifications.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Blueprint\n  - API Design\n  - API Testing\n  - Collaboration\n  - Design First\n  - Documentation\n  - Mock Servers\n  - Oracle\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apiary/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apiary:apiary-api\n    name: Apiary API\n\
  \    description: >-\n      The Apiary API provides programmatic access to manage API projects,\n      documentation, and team collaboration. It allows creating and updating\n      API Blueprint and Swagger/OpenAPI documents, managing team members,\n      and integrating Apiary workflows into CI/CD pipelines.\n    humanURL: https://apiary.io\n    tags:\n      - API Blueprint\n      - API Design\n      - Collaboration\n      - Documentation\n      - Mock Servers\n    properties:\n      - type: Documentation\n        url: https://help.apiary.io\n      - type: GettingStarted\n        url: https://help.apiary.io/tools/apiary-cli/\n  - aid: apiary:api-blueprint\n    name: API Blueprint\n    description: >-\n      API Blueprint is a high-level API design language created by Apiary for\n      designing and documenting web APIs. It uses a Markdown-based syntax\n      that is human-readable and machine-parseable, enabling teams to design\n      APIs collaboratively and generate documentation, mock\
  \ servers, and\n      tests from a single source of truth.\n    humanURL: https://apiblueprint.org\n    tags:\n      - API Blueprint\n      - API Design\n      - Documentation\n      - Open Source\n      - Specification\n    properties:\n      - type: Documentation\n        url: https://apiblueprint.org/documentation/\n      - type: GitHubRepository\n        url: https://github.com/apiaryio/api-blueprint\n      - type: Specification\n        url: https://apiblueprint.org/documentation/specification.html\ncommon:\n  - type: Website\n    url: https://apiary.io\n  - type: Documentation\n    url: https://help.apiary.io\n  - type: GitHubOrganization\n    url: https://github.com/apiaryio\n  - type: Blog\n    url: https://blog.apiary.io\n  - type: Pricing\n    url: https://apiary.io/plans\n  - type: Login\n    url: https://login.apiary.io\n  - type: SignUp\n    url: https://login.apiary.io/register\n  - type: Support\n    url: https://help.apiary.io\n  - type: PrivacyPolicy\n    url: https://www.oracle.com/legal/privacy/\n\
  \  - type: TermsOfService\n    url: https://www.oracle.com/legal/terms.html\n  - type: Features\n    data:\n      - name: API Blueprint Support\n        description: Native support for API Blueprint, a high-level Markdown-based API description language for collaborative design.\n      - name: OpenAPI/Swagger Support\n        description: Import and work with Swagger and OpenAPI specifications alongside API Blueprint documents.\n      - name: Interactive API Documentation\n        description: Auto-generate interactive documentation from API specs with a built-in API console for live testing.\n      - name: Mock Servers\n        description: Instant mock servers generated from API specs allowing frontend development before backend is ready.\n      - name: Automated API Testing\n        description: Run automated tests against API implementations using Dredd, the open-source API testing framework.\n      - name: Collaborative Workflows\n        description: Team-based API design with version\
  \ history, commenting, and shared workspaces.\n      - name: CLI Integration\n        description: Apiary CLI for integrating API design and testing workflows into CI/CD pipelines.\n      - name: Open Source Tooling\n        description: Maintains Dredd (testing), Gavel (validation), and API Blueprint as open-source projects.\n  - type: UseCases\n    data:\n      - name: Design-First API Development\n        description: Design APIs in API Blueprint or OpenAPI before writing code, enabling parallel frontend and backend development.\n      - name: API Documentation Generation\n        description: Automatically generate interactive API documentation from API specifications for developer consumption.\n      - name: Mock Server Prototyping\n        description: Generate instant mock servers from specs to enable frontend development without a live backend.\n      - name: Contract Testing\n        description: Validate API implementations against their specifications using Dredd to catch regressions.\n\
  \      - name: Team API Governance\n        description: Collaborate on API design standards and review API changes in a shared workspace.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apiary/refs/heads/main/apis.yml
tags:
- API Blueprint
- API Design
- API Testing
- Collaboration
- Design First
- Documentation
- Mock Servers
- Oracle
url: https://raw.githubusercontent.com/api-evangelist/apiary/refs/heads/main/apis.yml
use_cases:
- description: Design APIs in API Blueprint or OpenAPI before writing code, enabling parallel frontend and backend development.
  name: Design-First API Development
- description: Automatically generate interactive API documentation from API specifications for developer consumption.
  name: API Documentation Generation
- description: Generate instant mock servers from specs to enable frontend development without a live backend.
  name: Mock Server Prototyping
- description: Validate API implementations against their specifications using Dredd to catch regressions.
  name: Contract Testing
- description: Collaborate on API design standards and review API changes in a shared workspace.
  name: Team API Governance
---
