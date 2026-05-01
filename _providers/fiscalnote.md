---
api_count: 4
api_specs:
- filename: fiscalnote-policynote-openapi.yml
  format: yaml
  label: FiscalNote PolicyNote API
  slug: policynote-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiscalnote/refs/heads/main/openapi/fiscalnote-policynote-openapi.yml
- filename: fiscalnote-appdata-openapi.yml
  format: yaml
  label: FiscalNote AppData API
  slug: appdata-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiscalnote/refs/heads/main/openapi/fiscalnote-appdata-openapi.yml
- filename: fiscalnote-people-openapi.yml
  format: yaml
  label: FiscalNote People API
  slug: people-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiscalnote/refs/heads/main/openapi/fiscalnote-people-openapi.yml
- filename: fiscalnote-organization-openapi.yml
  format: yaml
  label: FiscalNote Organization API
  slug: organization-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiscalnote/refs/heads/main/openapi/fiscalnote-organization-openapi.yml
apis:
- description: 'The FiscalNote PolicyNote API delivers programmatic access to legislative, regulatory, and stakeholder intelligence datasets spanning Congress, all 50 U.S. states, and more than 100 countries through '
  name: FiscalNote PolicyNote API
  slug: policynote-api
- description: The FiscalNote AppData API provides access to FiscalNote's data on legislation and regulations, both past and present, in the United States and globally. It also exposes organizational data from the F
  name: FiscalNote AppData API
  slug: appdata-api
- description: The FiscalNote People API allows developers to access FiscalNote's data on government officials in the United States and globally. The API provides structured information about legislators, elected of
  name: FiscalNote People API
  slug: people-api
- description: The FiscalNote Organization API provides access to FiscalNote's data on government organizations in the United States and globally. It covers legislative committees, federal agencies, and other govern
  name: FiscalNote Organization API
  slug: organization-api
common:
- title: ''
  type: Website
  url: https://fiscalnote.com/
- title: ''
  type: Portal
  url: https://apidocs.fiscalnote.com/
- title: ''
  type: Documentation
  url: https://apidocs.fiscalnote.com/apis
- title: ''
  type: Blog
  url: https://fiscalnote.com/blog
- title: ''
  type: Privacy Policy
  url: https://fiscalnote.com/privacy
- title: ''
  type: Terms of Service
  url: https://fiscalnote.com/terms
- title: ''
  type: Login
  url: https://app.fiscalnote.com/
- title: ''
  type: JSON-LD
  url: json-ld/fiscalnote-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/fiscalnote-legislation-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fiscalnote-official-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fiscalnote-transcript-schema.json
created: '2026-03-24'
description: FiscalNote is a policy intelligence platform that provides legislative, regulatory, and stakeholder data spanning Congress, all 50 U.S. states, and more than 100 countries. FiscalNote expanded its PolicyNote API to eliminate AI hallucinations in compliance workflows by providing primary-source verified policy data.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Fiscalnote Context
  property_count: 5
  slug: fiscalnote-context
layout: provider
modified: '2026-04-28'
name: FiscalNote
skills: []
slug: fiscalnote
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: fiscalnote\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/fiscalnote/refs/heads/main/apis.yml\nname: FiscalNote\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Government\n  - Legislation\n  - Policy\n  - Political Intelligence\n  - Regulation\ndescription: >-\n  FiscalNote is a policy intelligence platform that provides legislative, regulatory,\n  and stakeholder data spanning Congress, all 50 U.S. states, and more than 100 countries.\n  FiscalNote expanded its PolicyNote API to eliminate AI hallucinations in compliance\n  workflows by providing primary-source verified policy data.\ncreated: '2026-03-24'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: fiscalnote:policynote-api\n    name: FiscalNote PolicyNote API\n    tags:\n      - AI Agents\n      - Compliance\n      - Legislation\n      - MCP\n      - Policy\n      - Regulation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.fiscalnote.com\n    humanURL: https://fiscalnote.com/products/policynote-api\n    properties:\n      - url: https://fiscalnote.com/products/policynote-api\n        type: Documentation\n      - url: openapi/fiscalnote-policynote-openapi.yml\n        type: OpenAPI\n    description: >-\n      The FiscalNote PolicyNote API delivers programmatic access to legislative, regulatory,\n      and stakeholder intelligence datasets spanning Congress, all 50 U.S. states,\n      and more than 100 countries through a secure, governed architecture designed\n      for machine consumption. The API includes an MCP server enabling MCP-compatible\n      AI agents from platforms such as Anthropic, OpenAI, Google Gemini, and Microsoft\n      to query structured policy data, verified analysis, and real-time monitoring\n      signals.\n  - aid: fiscalnote:appdata-api\n    name: FiscalNote AppData API\n    tags:\n      - Bills\n      - Government Data\n      - Legislation\n      - Regulation\n\
  \    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fiscalnote.com\n    humanURL: https://apidocs.fiscalnote.com/apis\n    properties:\n      - url: https://apidocs.fiscalnote.com/apis\n        type: Documentation\n      - url: openapi/fiscalnote-appdata-openapi.yml\n        type: OpenAPI\n    description: >-\n      The FiscalNote AppData API provides access to FiscalNote's data on\n      legislation and regulations, both past and present, in the United States\n      and globally. It also exposes organizational data from the FiscalNote\n      platform including issues and labels. Developers can use the API to\n      integrate legislative tracking, regulatory monitoring, and policy analysis\n      capabilities into their own applications and workflows.\n  - aid: fiscalnote:people-api\n    name: FiscalNote People API\n    tags:\n      - Government Officials\n      - Legislators\n      - Politicians\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.fiscalnote.com\n    humanURL: https://apidocs.fiscalnote.com/apis\n    properties:\n      - url: https://apidocs.fiscalnote.com/apis\n        type: Documentation\n      - url: openapi/fiscalnote-people-openapi.yml\n        type: OpenAPI\n    description: >-\n      The FiscalNote People API allows developers to access FiscalNote's data on\n      government officials in the United States and globally. The API provides\n      structured information about legislators, elected officials, and other\n      government personnel, enabling applications to look up representatives,\n      track official profiles, and integrate government personnel data into\n      political intelligence and advocacy workflows.\n  - aid: fiscalnote:organization-api\n    name: FiscalNote Organization API\n    tags:\n      - Committees\n      - Federal Agencies\n      - Government Organizations\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL:\
  \ https://api.fiscalnote.com\n    humanURL: https://apidocs.fiscalnote.com/apis\n    properties:\n      - url: https://apidocs.fiscalnote.com/apis\n        type: Documentation\n      - url: openapi/fiscalnote-organization-openapi.yml\n        type: OpenAPI\n    description: >-\n      The FiscalNote Organization API provides access to FiscalNote's data on\n      government organizations in the United States and globally. It covers\n      legislative committees, federal agencies, and other governmental bodies.\n      Developers can use this API to retrieve structured information about\n      government organizations, enabling integration of organizational data into\n      policy tracking, compliance, and government relations applications.\ncommon:\n  - type: Website\n    url: https://fiscalnote.com/\n  - type: Portal\n    url: https://apidocs.fiscalnote.com/\n  - type: Documentation\n    url: https://apidocs.fiscalnote.com/apis\n  - type: Blog\n    url: https://fiscalnote.com/blog\n  - type:\
  \ Privacy Policy\n    url: https://fiscalnote.com/privacy\n  - type: Terms of Service\n    url: https://fiscalnote.com/terms\n  - type: Login\n    url: https://app.fiscalnote.com/\n  - type: JSON-LD\n    url: json-ld/fiscalnote-context.jsonld\n  - type: JSONSchema\n    url: json-schema/fiscalnote-legislation-schema.json\n  - type: JSONSchema\n    url: json-schema/fiscalnote-official-schema.json\n  - type: JSONSchema\n    url: json-schema/fiscalnote-transcript-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fiscalnote/refs/heads/main/apis.yml
tags:
- Government
- Legislation
- Policy
- Political Intelligence
- Regulation
url: https://raw.githubusercontent.com/api-evangelist/fiscalnote/refs/heads/main/apis.yml
use_cases: []
---
