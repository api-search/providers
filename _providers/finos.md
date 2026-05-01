---
api_count: 5
api_specs:
- filename: finos-symphony-pod-api-openapi.yml
  format: yaml
  label: Symphony API Spec
  slug: symphony-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/finos/refs/heads/main/openapi/finos-symphony-pod-api-openapi.yml
apis:
- description: FDC3 is an open standard for financial desktop interoperability, defining how applications launch, share context, and resolve intents across the financial desktop. The standard includes a Desktop Agen
  name: FDC3
  slug: fdc3
- description: The Common Domain Model (CDM) is a standardized, machine-readable, and machine-executable model that represents financial products, trades in those products, and the lifecycle events of those trades.
  name: Common Domain Model
  slug: common-domain-model
- description: FINOS Common Cloud Controls is an open standard project that describes consistent controls for compliant public cloud deployments in the financial services sector.
  name: Common Cloud Controls
  slug: common-cloud-controls
- description: Morphir is a universal language for business and technology that captures business logic in a portable, technology-agnostic intermediate representation that can be compiled to multiple target language
  name: Morphir
  slug: morphir
- description: 'The Symphony API Spec project hosted at FINOS publishes the OpenAPI definitions for the Symphony platform, including the Pod API, Agent API, and Authenticator API used to send messages, manage users, '
  name: Symphony API Spec
  slug: symphony-api
common:
- title: ''
  type: Website
  url: https://www.finos.org/
- title: ''
  type: Documentation
  url: https://www.finos.org/about
- title: ''
  type: GitHubOrg
  url: https://github.com/finos
- title: ''
  type: Landscape
  url: https://landscape.finos.org/
- title: ''
  type: Community
  url: https://www.finos.org/community
created: '2026-03-16'
description: The Fintech Open Source Foundation (FINOS) is a Linux Foundation project dedicated to open source innovation in the financial services industry. It fosters collaboration between banks, fintech companies, and technology firms on standards and projects spanning desktop interoperability (FDC3), financial product modeling (Common Domain Model), cloud compliance (Common Cloud Controls), business and technology modeling (Morphir), and messaging APIs (Symphony API Spec), among others.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: FINOS
skills: []
slug: finos
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: finos\nname: FINOS\ndescription: >-\n  The Fintech Open Source Foundation (FINOS) is a Linux Foundation project\n  dedicated to open source innovation in the financial services industry. It\n  fosters collaboration between banks, fintech companies, and technology firms\n  on standards and projects spanning desktop interoperability (FDC3),\n  financial product modeling (Common Domain Model), cloud compliance (Common\n  Cloud Controls), business and technology modeling (Morphir), and messaging\n  APIs (Symphony API Spec), among others.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Financial Services\n  - Fintech\n  - Linux Foundation\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/finos/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: finos:fdc3\n    name: FDC3\n    description:\
  \ >-\n      FDC3 is an open standard for financial desktop interoperability,\n      defining how applications launch, share context, and resolve intents\n      across the financial desktop. The standard includes a Desktop Agent API\n      and an App Directory specification.\n    humanURL: https://fdc3.finos.org/\n    tags:\n      - Desktop Interoperability\n      - FDC3\n      - Financial Services\n      - Open Standard\n    properties:\n      - type: Documentation\n        url: https://fdc3.finos.org/docs/fdc3-intro\n      - type: GitHubRepository\n        url: https://github.com/finos/FDC3\n      - type: Reference\n        url: https://fdc3.finos.org/docs/app-directory/overview\n  - aid: finos:common-domain-model\n    name: Common Domain Model\n    description: >-\n      The Common Domain Model (CDM) is a standardized, machine-readable, and\n      machine-executable model that represents financial products, trades in\n      those products, and the lifecycle events of those trades.\n\
  \    humanURL: https://www.finos.org/common-domain-model\n    tags:\n      - Common Domain Model\n      - Financial Products\n      - Open Standard\n      - Trade Lifecycle\n    properties:\n      - type: Documentation\n        url: https://cdm.finos.org/\n      - type: GitHubRepository\n        url: https://github.com/finos/common-domain-model\n  - aid: finos:common-cloud-controls\n    name: Common Cloud Controls\n    description: >-\n      FINOS Common Cloud Controls is an open standard project that describes\n      consistent controls for compliant public cloud deployments in the\n      financial services sector.\n    humanURL: https://www.finos.org/common-cloud-controls-project\n    tags:\n      - Cloud\n      - Compliance\n      - Financial Services\n      - Open Standard\n    properties:\n      - type: Documentation\n        url: https://www.finos.org/common-cloud-controls-project\n      - type: GitHubRepository\n        url: https://github.com/finos/common-cloud-controls\n  - aid:\
  \ finos:morphir\n    name: Morphir\n    description: >-\n      Morphir is a universal language for business and technology that\n      captures business logic in a portable, technology-agnostic intermediate\n      representation that can be compiled to multiple target languages and\n      runtimes.\n    humanURL: https://morphir.finos.org/\n    tags:\n      - Business Modeling\n      - Domain Modeling\n      - Morphir\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://morphir.finos.org/\n      - type: GitHubRepository\n        url: https://github.com/finos/morphir\n  - aid: finos:symphony-api\n    name: Symphony API Spec\n    description: >-\n      The Symphony API Spec project hosted at FINOS publishes the OpenAPI\n      definitions for the Symphony platform, including the Pod API, Agent API,\n      and Authenticator API used to send messages, manage users, and\n      authenticate bots and integrations.\n    humanURL: https://github.com/finos/symphony-api-spec\n\
  \    tags:\n      - Authentication\n      - Messaging\n      - OpenAPI\n      - Symphony\n    properties:\n      - type: Documentation\n        url: https://github.com/finos/symphony-api-spec\n      - type: GitHubRepository\n        url: https://github.com/finos/symphony-api-spec\n      - type: OpenAPI\n        url: openapi/finos-symphony-pod-api-openapi.yml\n      - type: OpenAPI\n        url: openapi/finos-symphony-agent-api-openapi.yml\n      - type: OpenAPI\n        url: openapi/finos-symphony-authenticator-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.finos.org/\n  - type: Documentation\n    url: https://www.finos.org/about\n  - type: GitHubOrg\n    url: https://github.com/finos\n  - type: Landscape\n    url: https://landscape.finos.org/\n  - type: Community\n    url: https://www.finos.org/community\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/finos/refs/heads/main/apis.yml
tags:
- Financial Services
- Fintech
- Linux Foundation
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/finos/refs/heads/main/apis.yml
use_cases: []
---
