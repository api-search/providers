---
api_count: 2
api_specs:
- filename: congress-gov-api-openapi.yml
  format: yaml
  label: Congress.gov API
  slug: congress-gov-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-house-of-representatives/refs/heads/main/openapi/congress-gov-api-openapi.yml
apis:
- description: The Congress.gov API (v3) provides programmatic access to congressional data maintained by the Library of Congress. It offers machine-readable data covering bills, amendments, congressional records, c
  name: Congress.gov API
  slug: congress-gov-api
- description: ProPublica's Congress API provides access to detailed congressional data including member profiles, voting records, bill sponsorship, and committee activity. This third-party API aggregates and enrich
  name: ProPublica Congress API
  slug: propublica-congress-api
capabilities:
- description: Workflow capability for legislative research and congressional monitoring. Provides access to congressional bills, member information, committee activities, and legislative actions via the Congress.go
  name: US Congressional Legislative Research
  slug: legislative-research
common: []
created: '2024-12-03'
description: The United States House of Representatives is one of the two chambers of the United States Congress, with the other being the Senate. Its main function is to pass federal legislation, which must then be approved by the Senate before it can become law. The House also has the power to impeach government officials, including the President, and to initiate revenue-related bills. Congressional data is made available through the Congress.gov API, a REST API maintained by the Library of Congress that provides access to bills, members, committees, amendments, nominations, and treaties.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 26
  name: Us House Of Representatives Context
  property_count: 5
  slug: us-house-of-representatives-context
layout: provider
modified: '2026-05-03'
name: US House of Representatives
rules:
- name: US House of Representatives API Rules
  rule_count: 11
  severity_counts:
    error: 1
    hint: 0
    info: 4
    warn: 6
  slug: congress-gov-api-rules
skills: []
slug: us-house-of-representatives
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-house-of-representatives\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-house-of-representatives/refs/heads/main/apis.yml\napis:\n  - aid: us-house-of-representatives:congress-gov-api\n    name: Congress.gov API\n    tags:\n      - Legislation\n      - Congress\n      - Federal Government\n      - Legislative Data\n    humanURL: https://www.loc.gov/apis/additional-apis/congress-dot-gov-api/\n    properties:\n      - url: https://www.loc.gov/apis/additional-apis/congress-dot-gov-api/\n        type: Documentation\n      - url: https://github.com/LibraryOfCongress/api.congress.gov\n        type: GitHub\n      - url: https://api.congress.gov/\n        type: BaseURL\n      - url: https://raw.githubusercontent.com/api-evangelist/us-house-of-representatives/refs/heads/main/openapi/congress-gov-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Congress.gov API (v3) provides programmatic access to congressional\n      data maintained by\
  \ the Library of Congress. It offers machine-readable\n      data covering bills, amendments, congressional records, committees,\n      members of Congress, nominations, and treaties. An API key is required\n      and can be obtained from api.data.gov. Responses are available in JSON\n      or XML with a rate limit of 5,000 requests per hour and pagination\n      up to 250 results per request.\n\n  - aid: us-house-of-representatives:propublica-congress-api\n    name: ProPublica Congress API\n    tags:\n      - Legislation\n      - Congress\n      - Voting Records\n      - Campaign Finance\n    humanURL: https://projects.propublica.org/api-docs/congress-api/\n    properties:\n      - url: https://projects.propublica.org/api-docs/congress-api/\n        type: Documentation\n    description: >-\n      ProPublica's Congress API provides access to detailed congressional data\n      including member profiles, voting records, bill sponsorship, and\n      committee activity. This third-party API\
  \ aggregates and enriches\n      congressional data from multiple public sources.\n\nname: US House of Representatives\ntags:\n  - Federal Government\n  - Legislation\n  - Congress\n  - Legislative Data\n  - Bills\n  - Members\n  - Committees\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  The United States House of Representatives is one of the two chambers of the\n  United States Congress, with the other being the Senate. Its main function is\n  to pass federal legislation, which must then be approved by the Senate before\n  it can become law. The House also has the power to impeach government\n  officials, including the President, and to initiate revenue-related bills.\n  Congressional data is made available through the Congress.gov API, a REST\n  API maintained by the Library of Congress that provides access to bills,\n  members,\
  \ committees, amendments, nominations, and treaties.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-house-of-representatives/refs/heads/main/apis.yml
tags:
- Federal Government
- Legislation
- Congress
- Legislative Data
- Bills
- Members
- Committees
url: https://raw.githubusercontent.com/api-evangelist/us-house-of-representatives/refs/heads/main/apis.yml
use_cases: []
---
