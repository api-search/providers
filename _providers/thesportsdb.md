---
api_count: 1
api_specs:
- filename: thesportsdb-openapi.yml
  format: yaml
  label: TheSportsDB API
  slug: thesportsdb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thesportsdb/refs/heads/main/openapi/thesportsdb-openapi.yml
apis:
- description: 'An open, crowd-sourced sports database of artwork and metadata with a free sports API in JSON format. Provides data on leagues, teams, players, events, venues, and season standings across hundreds of '
  name: TheSportsDB API
  slug: thesportsdb
capabilities:
- description: Workflow capability for accessing sports data including team information, upcoming events, match results, player profiles, league standings, and sports metadata from TheSportsDB free API.
  name: TheSportsDB Sports Data
  slug: sports-data
common:
- title: ''
  type: Website
  url: https://www.thesportsdb.com/
- title: ''
  type: Documentation
  url: https://www.thesportsdb.com/documentation
- title: ''
  type: Sign Up
  url: https://www.thesportsdb.com/register
- title: ''
  type: Pricing
  url: https://www.thesportsdb.com/patreon
- title: ''
  type: Examples
  url: https://www.thesportsdb.com/docs_api_examples
created: '2025-03-01'
description: An open, crowd-sourced sports database of artwork and metadata with a free sports API in JSON format. TheSportsDB provides data on sports leagues, teams, players, events, venues, and season standings across a wide range of sports worldwide including soccer, basketball, baseball, American football, hockey, tennis, and more.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Thesportsdb Context
  property_count: 4
  slug: thesportsdb-context
layout: provider
modified: '2026-05-03'
name: TheSportsDB
rules:
- name: TheSportsDB API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: thesportsdb-rules
skills: []
slug: thesportsdb
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: thesportsdb\nname: TheSportsDB\ndescription: >-\n  An open, crowd-sourced sports database of artwork and metadata with a free\n  sports API in JSON format. TheSportsDB provides data on sports leagues, teams,\n  players, events, venues, and season standings across a wide range of sports\n  worldwide including soccer, basketball, baseball, American football, hockey,\n  tennis, and more.\ntype: Contract\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Sports\n  - Database\n  - Free\n  - Open Data\n  - Teams\n  - Players\n  - Events\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/thesportsdb/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: thesportsdb:thesportsdb\n    name: TheSportsDB API\n    description: >-\n      An open, crowd-sourced sports database of artwork and metadata with a free\n      sports API\
  \ in JSON format. Provides data on leagues, teams, players, events,\n      venues, and season standings across hundreds of sports worldwide.\n    humanURL: https://www.thesportsdb.com/\n    baseURL: https://www.thesportsdb.com/api/v1/json/3\n    tags:\n      - Sports\n      - Database\n      - Free\n      - Teams\n      - Players\n      - Events\n      - Leagues\n    properties:\n      - type: Documentation\n        url: https://www.thesportsdb.com/documentation\n      - type: Website\n        url: https://www.thesportsdb.com/\n      - url: openapi/thesportsdb-openapi.yml\n        type: OpenAPI\n      - url: json-schema/thesportsdb-team-schema.json\n        type: JSONSchema\n      - url: json-ld/thesportsdb-context.jsonld\n        type: JSONLD\n      - url: json-structure/thesportsdb-structure.json\n        type: JSONStructure\n      - url: rules/thesportsdb-rules.yml\n        type: SpectralRules\n      - url: capabilities/sports-data.yaml\n        type: NaftikoCapabilities\n      - url:\
  \ vocabulary/thesportsdb-vocabulary.yml\n        type: Vocabulary\ncommon:\n  - type: Website\n    url: https://www.thesportsdb.com/\n  - type: Documentation\n    url: https://www.thesportsdb.com/documentation\n  - type: Sign Up\n    url: https://www.thesportsdb.com/register\n  - type: Pricing\n    url: https://www.thesportsdb.com/patreon\n  - type: Examples\n    url: https://www.thesportsdb.com/docs_api_examples\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/thesportsdb/refs/heads/main/apis.yml
tags:
- Sports
- Database
- Free
- Open Data
- Teams
- Players
- Events
url: https://raw.githubusercontent.com/api-evangelist/thesportsdb/refs/heads/main/apis.yml
use_cases: []
---
