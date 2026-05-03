---
api_count: 1
api_specs:
- filename: us-senate-lda-openapi.yml
  format: yaml
  label: Senate Lobbying Disclosure Act (LDA) API
  slug: lda-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-senate/refs/heads/main/openapi/us-senate-lda-openapi.yml
apis:
- description: The Senate Lobbying Disclosure Act (LDA) REST API provides public access to lobbying disclosure filings, registrations, quarterly activity reports (LD-2), and semi-annual contribution reports (LD-203)
  name: Senate Lobbying Disclosure Act (LDA) API
  slug: lda-api
capabilities:
- description: Unified capability for lobbying disclosure research and transparency, combining access to LDA filings, registrant profiles, client information, and lobbyist records. Supports investigative journalists
  name: US Senate Lobbying Transparency
  slug: lobbying-transparency
common: []
created: '2024-12-03'
description: The United States Senate is one of the two chambers of Congress, responsible for representing the interests of the individual states and ensuring that federal legislation is passed in a fair and representative manner. The Senate plays a crucial role in the legislative process, with its members debating and voting on bills and resolutions that affect the country as a whole. The Senate also administers the Lobbying Disclosure Act (LDA) reporting system, which requires lobbyists and lobbying firms to register and report their activities, clients, and campaign contributions for public transparency.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Us Senate Context
  property_count: 19
  slug: us-senate-context
layout: provider
modified: '2026-05-03'
name: US Senate
rules:
- name: US Senate API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 3
  slug: us-senate-rules
skills: []
slug: us-senate
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-senate\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-senate/refs/heads/main/apis.yml\napis:\n  - aid: us-senate:lda-api\n    name: Senate Lobbying Disclosure Act (LDA) API\n    tags:\n      - Lobbying\n      - Government Transparency\n      - Federal Government\n      - Open Data\n      - Campaign Finance\n    humanURL: https://lda.senate.gov/api/\n    properties:\n      - url: https://lda.senate.gov/api/\n        type: Documentation\n      - url: https://lda.senate.gov/api/redoc/v1/\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-senate/refs/heads/main/openapi/us-senate-lda-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Senate Lobbying Disclosure Act (LDA) REST API provides public access\n      to lobbying disclosure filings, registrations, quarterly activity reports\n      (LD-2), and semi-annual contribution reports (LD-203) submitted under the\n      Lobbying Disclosure\
  \ Act. Includes data on registrants, clients, lobbyists,\n      and lobbying activities. An API key increases rate limits from 15 to 120\n      requests per minute.\nname: US Senate\ntags:\n  - Federal Government\n  - Lobbying\n  - Government Transparency\n  - Campaign Finance\n  - Open Data\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  The United States Senate is one of the two chambers of Congress, responsible\n  for representing the interests of the individual states and ensuring that\n  federal legislation is passed in a fair and representative manner. The Senate\n  plays a crucial role in the legislative process, with its members debating and\n  voting on bills and resolutions that affect the country as a whole. The Senate\n  also administers the Lobbying Disclosure Act (LDA) reporting system, which\n  requires lobbyists and\
  \ lobbying firms to register and report their activities,\n  clients, and campaign contributions for public transparency.\nfeatures:\n  - Lobbying Filing Search and Retrieval\n  - Registrant Information\n  - Client Information\n  - Lobbyist Profiles\n  - Campaign Contribution Reports\n  - Reference Data (Issue Codes, Government Entities)\nuseCases:\n  - Government transparency research\n  - Lobbying activity monitoring and analysis\n  - Campaign finance research\n  - Policy influence tracking\n  - Compliance verification for lobbyists\n  - Investigative journalism\nintegrations:\n  - data.gov\nsolutions:\n  - Government Transparency\n  - Lobbying Compliance\n  - Policy Research\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-senate/refs/heads/main/apis.yml
tags:
- Federal Government
- Lobbying
- Government Transparency
- Campaign Finance
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/us-senate/refs/heads/main/apis.yml
use_cases: []
---
