---
api_count: 2
api_specs:
- filename: ocelot-administration-openapi.yml
  format: yaml
  label: Ocelot Administration API
  slug: ocelot-administration-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ocelot/refs/heads/main/openapi/ocelot-administration-openapi.yml
apis:
- description: Ocelot is an open-source .NET API Gateway that provides routing, authentication, authorization, rate limiting, load balancing, caching, and service discovery for microservices architectures. It is con
  name: Ocelot API Gateway
  slug: ocelot-gateway
- description: 'The Ocelot Administration API allows runtime changes to gateway configuration via an authenticated HTTP API. It supports updating routes and clearing cache regions without restarting the gateway, and '
  name: Ocelot Administration API
  slug: ocelot-administration-api
common:
- title: ''
  type: Website
  url: https://ocelot.readthedocs.io/
- title: ''
  type: Documentation
  url: https://ocelot.readthedocs.io/en/latest/
- title: ''
  type: Getting Started
  url: https://ocelot.readthedocs.io/en/latest/introduction/gettingstarted.html
- title: ''
  type: Change Log
  url: https://github.com/ThreeMammals/Ocelot/releases
- title: ''
  type: GitHub Organization
  url: https://github.com/ThreeMammals/Ocelot
- title: ''
  type: GitHubRepository
  url: https://github.com/ThreeMammals/Ocelot
- title: ''
  type: Community
  url: https://github.com/ThreeMammals/Ocelot/discussions
- title: ''
  type: Issue Tracker
  url: https://github.com/ThreeMammals/Ocelot/issues
- title: ''
  type: SDKs
  url: https://www.nuget.org/packages/Ocelot
created: '2026-03-16'
description: Ocelot is an open-source API Gateway built with .NET for microservices architectures. It provides routing, authentication, rate limiting, load balancing, and service discovery features for managing and securing APIs in .NET ecosystems.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Ocelot
skills: []
slug: ocelot
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ocelot\nname: Ocelot\ndescription: >-\n  Ocelot is an open-source API Gateway built with .NET for microservices\n  architectures. It provides routing, authentication, rate limiting, load\n  balancing, and service discovery features for managing and securing APIs\n  in .NET ecosystems.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - .NET\n  - API Gateway\n  - Microservices\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ocelot/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: ocelot:ocelot-gateway\n    name: Ocelot API Gateway\n    description: >-\n      Ocelot is an open-source .NET API Gateway that provides routing,\n      authentication, authorization, rate limiting, load balancing, caching,\n      and service discovery for microservices architectures. It is configured\n      via JSON files and integrates with ASP.NET\
  \ Core middleware pipelines.\n    humanURL: https://ocelot.readthedocs.io/en/latest/\n    baseURL: https://ocelot.readthedocs.io/\n    tags:\n      - .NET\n      - API Gateway\n      - Microservices\n      - Routing\n    properties:\n      - type: Documentation\n        url: https://ocelot.readthedocs.io/en/latest/\n      - type: Getting Started\n        url: https://ocelot.readthedocs.io/en/latest/introduction/gettingstarted.html\n      - type: Reference\n        url: https://ocelot.readthedocs.io/en/latest/features/configuration.html\n      - type: Authentication\n        url: https://ocelot.readthedocs.io/en/latest/features/authentication.html\n      - type: GitHubRepository\n        url: https://github.com/ThreeMammals/Ocelot\n  - aid: ocelot:ocelot-administration-api\n    name: Ocelot Administration API\n    description: >-\n      The Ocelot Administration API allows runtime changes to gateway\n      configuration via an authenticated HTTP API. It supports updating\n      routes and\
  \ clearing cache regions without restarting the gateway,\n      and is authenticated using Bearer tokens issued by Ocelot's built-in\n      IdentityServer or an external identity provider.\n    humanURL: https://ocelot.readthedocs.io/en/latest/features/administration.html\n    baseURL: https://ocelot.readthedocs.io/\n    tags:\n      - .NET\n      - Administration\n      - Configuration\n      - Management\n    properties:\n      - type: Documentation\n        url: https://ocelot.readthedocs.io/en/latest/features/administration.html\n      - type: Authentication\n        url: https://ocelot.readthedocs.io/en/latest/features/authentication.html\n      - type: GitHubRepository\n        url: https://github.com/ThreeMammals/Ocelot\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/ocelot/refs/heads/main/openapi/ocelot-administration-openapi.yml\ncommon:\n  - type: Website\n    url: https://ocelot.readthedocs.io/\n  - type: Documentation\n    url: https://ocelot.readthedocs.io/en/latest/\n\
  \  - type: Getting Started\n    url: https://ocelot.readthedocs.io/en/latest/introduction/gettingstarted.html\n  - type: Change Log\n    url: https://github.com/ThreeMammals/Ocelot/releases\n  - type: GitHub Organization\n    url: https://github.com/ThreeMammals/Ocelot\n  - type: GitHubRepository\n    url: https://github.com/ThreeMammals/Ocelot\n  - type: Community\n    url: https://github.com/ThreeMammals/Ocelot/discussions\n  - type: Issue Tracker\n    url: https://github.com/ThreeMammals/Ocelot/issues\n  - type: SDKs\n    url: https://www.nuget.org/packages/Ocelot\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ocelot/refs/heads/main/apis.yml
tags:
- .NET
- API Gateway
- Microservices
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/ocelot/refs/heads/main/apis.yml
use_cases: []
---
