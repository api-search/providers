---
api_count: 3
apis:
- description: 'The integrator.io Platform API is a RESTful JSON API secured by Bearer Tokens. It provides programmatic access to integrations, connections, flows, imports, exports, iClients, and other integrator.io '
  name: Celigo integrator.io Platform API
  slug: celigo-integrator-io-api
- description: Celigo supports OAuth 2.0 and OAuth 1.0 authentication for HTTP connections, configured through iClient resources for reusable OAuth client credentials across integrations.
  name: Celigo OAuth Authentication
  slug: celigo-oauth-api
- description: Celigo API Management allows organizations to build, publish, and govern APIs on top of Celigo-managed integrations and third-party systems with a dedicated API Management console.
  name: Celigo API Management
  slug: celigo-api-management
common:
- title: ''
  type: Website
  url: https://celigo.com/
- title: ''
  type: Portal
  url: https://docs.celigo.com/
- title: ''
  type: Documentation
  url: https://docs.celigo.com/hc/en-us/categories/360001519091-Platform-API
- title: ''
  type: Reference
  url: https://github.com/celigo/integrator-api-docs
- title: ''
  type: GettingStarted
  url: https://docs.celigo.com/hc/en-us/articles/360042281231-Getting-started-with-standard-REST-API
- title: ''
  type: Authentication
  url: https://docs.celigo.com/hc/en-us/articles/360039586072-Set-up-an-OAuth-2-0-HTTP-connection
- title: ''
  type: Privacy Policy
  url: https://celigo.com/privacy-policy/
- title: ''
  type: Terms of Service
  url: https://celigo.com/terms-of-service/
created: '2026-03-16'
description: Celigo is an intelligent automation platform (iPaaS) that enables organizations to integrate applications, automate business processes, and connect data across their technology stack with low-code tooling. Celigo offers a REST-based integrator.io Platform API, an API Management console, OAuth 2.0 and Bearer Token authentication, and more than one thousand pre-built connectors and integration applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Celigo
skills: []
slug: celigo
solutions: []
source_filename: apis.yml
source_yaml: "aid: celigo\nurl: https://raw.githubusercontent.com/api-evangelist/celigo/refs/heads/main/apis.yml\nname: Celigo\ntags:\n  - API Management\n  - Automation\n  - Data Integration\n  - Integration\n  - iPaaS\n  - Workflow\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-16'\nmodified: '2026-04-23'\nposition: Consumer\nspecificationVersion: '0.19'\ndescription: >-\n  Celigo is an intelligent automation platform (iPaaS) that enables organizations\n  to integrate applications, automate business processes, and connect data across\n  their technology stack with low-code tooling. Celigo offers a REST-based\n  integrator.io Platform API, an API Management console, OAuth 2.0 and Bearer\n  Token authentication, and more than one thousand pre-built connectors and\n  integration applications.\napis:\n  - aid: celigo:celigo-integrator-io-api\n    name: Celigo integrator.io Platform API\n    tags:\n      -\
  \ Integration\n      - iPaaS\n      - REST\n      - Platform\n    humanURL: https://docs.celigo.com/hc/en-us/categories/360001519091-Platform-API\n    properties:\n      - url: https://docs.celigo.com/hc/en-us/categories/360001519091-Platform-API\n        type: Documentation\n      - url: https://github.com/celigo/integrator-api-docs\n        type: Reference\n      - url: https://docs.celigo.com/hc/en-us/articles/360042281231-Getting-started-with-standard-REST-API\n        type: GettingStarted\n      - url: https://docs.celigo.com/hc/en-us/articles/360038520652-Set-up-a-connection-to-Celigo-integrator-io\n        type: Connection\n    description: >-\n      The integrator.io Platform API is a RESTful JSON API secured by Bearer\n      Tokens. It provides programmatic access to integrations, connections,\n      flows, imports, exports, iClients, and other integrator.io resources,\n      with rate limiting via a leaky bucket algorithm of 1000 tokens and a fill\n      rate of 300 tokens per\
  \ second.\n  - aid: celigo:celigo-oauth-api\n    name: Celigo OAuth Authentication\n    tags:\n      - Authentication\n      - OAuth 2.0\n      - OAuth 1.0\n      - Security\n    humanURL: https://docs.celigo.com/hc/en-us/articles/360039586072-Set-up-an-OAuth-2-0-HTTP-connection\n    properties:\n      - url: https://docs.celigo.com/hc/en-us/articles/360039586072-Set-up-an-OAuth-2-0-HTTP-connection\n        type: Documentation\n      - url: https://docs.celigo.com/hc/en-us/articles/10552671272219-Set-up-an-OAuth-1-0-HTTP-connection\n        type: OAuth1\n      - url: https://docs.celigo.com/hc/en-us/articles/11933835192859-Create-an-OAuth-2-0-iClient-resource\n        type: iClient\n    description: >-\n      Celigo supports OAuth 2.0 and OAuth 1.0 authentication for HTTP\n      connections, configured through iClient resources for reusable OAuth\n      client credentials across integrations.\n  - aid: celigo:celigo-api-management\n    name: Celigo API Management\n    tags:\n      - API\
  \ Gateway\n      - API Management\n      - Publishing\n    humanURL: https://docs.celigo.com/hc/en-us/articles/21179125401755-The-API-Management-console-Features-and-concepts\n    properties:\n      - url: https://docs.celigo.com/hc/en-us/articles/21179125401755-The-API-Management-console-Features-and-concepts\n        type: Documentation\n      - url: https://www.celigo.com/platform/api-management/\n        type: Overview\n    description: >-\n      Celigo API Management allows organizations to build, publish, and govern\n      APIs on top of Celigo-managed integrations and third-party systems with\n      a dedicated API Management console.\ncommon:\n  - type: Website\n    url: https://celigo.com/\n  - type: Portal\n    url: https://docs.celigo.com/\n  - type: Documentation\n    url: https://docs.celigo.com/hc/en-us/categories/360001519091-Platform-API\n  - type: Reference\n    url: https://github.com/celigo/integrator-api-docs\n  - type: GettingStarted\n    url: https://docs.celigo.com/hc/en-us/articles/360042281231-Getting-started-with-standard-REST-API\n\
  \  - type: Authentication\n    url: https://docs.celigo.com/hc/en-us/articles/360039586072-Set-up-an-OAuth-2-0-HTTP-connection\n  - type: Privacy Policy\n    url: https://celigo.com/privacy-policy/\n  - type: Terms of Service\n    url: https://celigo.com/terms-of-service/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/celigo/refs/heads/main/apis.yml
tags:
- API Management
- Automation
- Data Integration
- Integration
- iPaaS
- Workflow
url: https://raw.githubusercontent.com/api-evangelist/celigo/refs/heads/main/apis.yml
use_cases: []
---
