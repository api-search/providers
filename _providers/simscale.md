---
api_count: 1
api_specs:
- filename: simscale-openapi.yml
  format: yaml
  label: SimScale REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/simscale/refs/heads/main/openapi/simscale-openapi.yml
apis:
- description: 'The SimScale REST API provides programmatic access to the SimScale cloud simulation platform. Developers can manage projects, upload CAD geometry, configure meshing operations, set up and run CFD/FEA '
  name: SimScale REST API
  slug: ''
capabilities:
- description: 'Workflow capability for automated engineering simulation using SimScale. Covers the complete simulation pipeline: project setup, CAD geometry upload, mesh generation, simulation configuration, executi'
  name: SimScale Simulation Automation
  slug: simulation-automation
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/SimScaleGmbH
- title: ''
  type: DeveloperPortal
  url: https://www.simscale.com/product/api/
- title: ''
  type: Documentation
  url: https://www.simscale.com/docs/
- title: ''
  type: PythonSDK
  url: https://github.com/SimScaleGmbH/simscale-python-sdk
- title: ''
  type: Pricing
  url: https://www.simscale.com/pricing/
- title: ''
  type: TermsOfService
  url: https://www.simscale.com/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://www.simscale.com/privacy-policy/
created: '2026-05-02'
description: SimScale is a cloud-based computer-aided engineering (CAE) platform offering computational fluid dynamics (CFD), finite element analysis (FEA), and thermal simulation capabilities. The SimScale REST API enables programmatic project management, geometry upload, mesh generation, simulation setup and execution, and results extraction for engineering automation workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 25
  name: Simscale Context
  property_count: 4
  slug: simscale-context
layout: provider
modified: '2026-05-02'
name: SimScale
rules:
- name: SimScale API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 6
  slug: simscale-rules
skills: []
slug: simscale
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SimScale\ndescription: SimScale is a cloud-based computer-aided engineering (CAE) platform offering computational fluid dynamics (CFD), finite element analysis (FEA), and thermal simulation capabilities. The SimScale REST API enables programmatic project management, geometry upload, mesh generation, simulation setup and execution, and results extraction for engineering automation workflows.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/simscale/refs/heads/main/apis.yml\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n- CAE\n- CFD\n- FEA\n- Simulation\n- Engineering\napis:\n- name: SimScale REST API\n  description: The SimScale REST API provides programmatic access to the SimScale cloud simulation platform. Developers can manage projects, upload CAD geometry, configure meshing operations, set up and run CFD/FEA simulations, and retrieve results.\
  \ Available on Enterprise plans. SDKs available for Python and C#.\n  image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://www.simscale.com/docs/platform/api-and-sdk-documentation/\n  baseURL: https://api.simscale.com\n  tags:\n  - CFD\n  - FEA\n  - Simulation\n  - Geometry\n  - Meshing\n  - Projects\n  properties:\n  - type: Documentation\n    url: https://www.simscale.com/docs/platform/api-and-sdk-documentation/\n  - type: SwaggerUI\n    url: https://api.simscale.com/apidoc/swagger/index.html\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/simscale/refs/heads/main/openapi/simscale-openapi.yml\n  - type: PythonSDK\n    url: https://github.com/SimScaleGmbH/simscale-python-sdk\n  - type: GitHubOrganization\n    url: https://github.com/SimScaleGmbH\n  - type: Authentication\n    url: https://www.simscale.com/docs/platform/api-and-sdk-documentation/\n  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/simscale/refs/heads/main/rules/simscale-rules.yml\n\
  \  contact:\n  - FN: SimScale Support\n    url: https://www.simscale.com/support/\ncommon:\n- type: GitHubOrganization\n  url: https://github.com/SimScaleGmbH\n- type: DeveloperPortal\n  url: https://www.simscale.com/product/api/\n- type: Documentation\n  url: https://www.simscale.com/docs/\n- type: PythonSDK\n  url: https://github.com/SimScaleGmbH/simscale-python-sdk\n- type: Pricing\n  url: https://www.simscale.com/pricing/\n- type: TermsOfService\n  url: https://www.simscale.com/terms-of-service/\n- type: PrivacyPolicy\n  url: https://www.simscale.com/privacy-policy/\nmaintainers:\n- FN: API Evangelist\n  url: https://apievangelist.com\n  email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/simscale/refs/heads/main/apis.yml
tags:
- CAE
- CFD
- FEA
- Simulation
- Engineering
url: https://raw.githubusercontent.com/api-evangelist/simscale/refs/heads/main/apis.yml
use_cases: []
---
