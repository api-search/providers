---
api_count: 1
api_specs:
- filename: m3ter-openapi.yml
  format: yaml
  label: M3ter API
  slug: m3ter
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/m3ter/refs/heads/main/openapi/m3ter-openapi.yml
apis:
- description: The m3ter REST API provides programmatic access to the m3ter usage-based billing and metering platform. It is split into the Ingest API for submitting raw measurement data and the Config API for manag
  name: M3ter API
  slug: m3ter
common:
- title: ''
  type: Website
  url: https://www.m3ter.com/
- title: ''
  type: Documentation
  url: https://docs.m3ter.com/
- title: ''
  type: APIReference
  url: https://docs.m3ter.com/api
created: '2026-03-27'
description: 'm3ter is a usage-based billing and metering engine providing real-time usage data ingestion, pricing logic, and billing automation for API and SaaS products. The m3ter platform exposes two HTTP-based REST APIs returning JSON responses: an Ingest API for submitting raw usage measurements and a Config API for configuration and billing management. Authentication uses OAuth 2.0 Client Credentials with a Service User Access Key id and Api Secret exchanged for a Bearer Token at https://api.m3ter.com/oauth/token.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: M3ter
skills: []
slug: m3ter
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: m3ter\nname: M3ter\ndescription: >-\n  m3ter is a usage-based billing and metering engine providing real-time usage\n  data ingestion, pricing logic, and billing automation for API and SaaS\n  products. The m3ter platform exposes two HTTP-based REST APIs returning JSON\n  responses: an Ingest API for submitting raw usage measurements and a Config\n  API for configuration and billing management. Authentication uses OAuth 2.0\n  Client Credentials with a Service User Access Key id and Api Secret exchanged\n  for a Bearer Token at https://api.m3ter.com/oauth/token.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - FinOps\n  - Usage-Based Billing\n  - Metering\n  - Billing\n  - Pricing\n  - SaaS\nurl: https://raw.githubusercontent.com/api-evangelist/m3ter/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: m3ter:m3ter\n    name: M3ter API\n    description:\
  \ >-\n      The m3ter REST API provides programmatic access to the m3ter usage-based\n      billing and metering platform. It is split into the Ingest API for\n      submitting raw measurement data and the Config API for managing Accounts,\n      Plans, Products, Aggregations, Counters, Meters, Pricing, Bills,\n      Commitments, Contracts, Balances, BillJobs, Charges, Notifications,\n      Events, Integrations, and Data Exports. Authentication uses OAuth 2.0\n      Client Credentials. The base URL is https://api.m3ter.com.\n    humanURL: https://www.m3ter.com/\n    baseURL: https://api.m3ter.com\n    tags:\n      - FinOps\n      - Usage-Based Billing\n      - Metering\n      - Billing\n      - Pricing\n    properties:\n      - type: Documentation\n        url: https://docs.m3ter.com/\n      - type: APIReference\n        url: https://docs.m3ter.com/api\n      - type: Authentication\n        url: https://docs.m3ter.com/api/authentication\n      - type: GettingStarted\n        url: https://www.m3ter.com/docs/guides/m3ter-apis/getting-started-with-api-calls\n\
  \      - type: OpenAPI\n        url: openapi/m3ter-openapi.yml\n      - type: SDK\n        url: https://github.com/m3ter-com/m3ter-sdk-python\n      - type: SDK\n        url: https://github.com/m3ter-com/m3ter-sdk-node\n      - type: SDK\n        url: https://github.com/m3ter-com/m3ter-sdk-java\n      - type: SDK\n        url: https://github.com/m3ter-com/m3ter-sdk-go\n      - type: SDK\n        url: https://github.com/m3ter-com/m3ter-sdk-typescript\n      - type: TerraformProvider\n        url: https://github.com/m3ter-com/terraform-provider-m3ter\ncommon:\n  - type: Website\n    url: https://www.m3ter.com/\n  - type: Documentation\n    url: https://docs.m3ter.com/\n  - type: APIReference\n    url: https://docs.m3ter.com/api\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/m3ter/refs/heads/main/apis.yml
tags:
- FinOps
- Usage-Based Billing
- Metering
- Billing
- Pricing
- SaaS
url: https://raw.githubusercontent.com/api-evangelist/m3ter/refs/heads/main/apis.yml
use_cases: []
---
