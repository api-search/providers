---
api_count: 1
apis:
- description: The AOC Data API provides access to public information about Capitol campus buildings, art collections, historic preservation projects, and congressional facilities management.
  name: Architect of the Capitol Data API
  slug: aoc-data-api
common:
- title: ''
  type: Portal
  url: https://www.aoc.gov/
- title: ''
  type: Documentation
  url: https://www.aoc.gov/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/architect-of-the-capitol/refs/heads/main/rules/aoc-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/architect-of-the-capitol/refs/heads/main/vocabulary/aoc-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/architect-of-the-capitol/refs/heads/main/json-ld/aoc-data-api-context.jsonld
created: '2024-11-21'
description: The Architect of the Capitol (AOC) serves Congress and the Supreme Court as builder and steward of Capitol Hill's landmark buildings and grounds, preserving historic structures, monuments, art, and gardens across the Capitol campus.
features:
- description: Information about the US Capitol, House and Senate office buildings, Library of Congress, and Supreme Court.
  name: Capitol Campus Buildings
- description: Access to the Capitol art collection catalog including paintings, sculptures, and historic artifacts.
  name: Art Collections
- description: Data on preservation and restoration projects across the Capitol campus.
  name: Historic Preservation Projects
- description: Accessibility features and visitor accommodations across Capitol campus facilities.
  name: Accessibility Information
- description: Management of congressional office space, hearing rooms, and support facilities.
  name: Congressional Facilities
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 9
  name: Aoc Data Api Context
  property_count: 0
  slug: aoc-data-api-context
layout: provider
modified: '2026-04-19'
name: Architect of the Capitol
rules:
- name: Architect of the Capitol API Rules
  rule_count: 13
  severity_counts:
    error: 8
    hint: 0
    info: 0
    warn: 5
  slug: aoc-spectral-rules
skills: []
slug: architect-of-the-capitol
solutions: []
source_yaml: "aid: architect-of-the-capitol\nname: Architect of the Capitol\ndescription: The Architect of the Capitol (AOC) serves Congress and the Supreme Court as builder and steward of Capitol Hill's landmark buildings and grounds, preserving historic structures, \n  monuments, art, and gardens across the Capitol campus.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Federal Government\n- Capitol Hill\n- Congress\n- Historic Preservation\n- Government Services\nurl: https://raw.githubusercontent.com/api-evangelist/architect-of-the-capitol/refs/heads/main/apis.yml\ncreated: '2024-11-21'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: architect-of-the-capitol:aoc-data-api\n  name: Architect of the Capitol Data API\n  description: The AOC Data API provides access to public information about Capitol campus buildings, art collections, historic preservation projects, and congressional facilities management.\n  humanURL:\
  \ https://www.aoc.gov/\n  tags:\n  - Capitol Campus\n  - Buildings\n  - Art Collections\n  - Historic Preservation\n  - Facilities\n  properties:\n  - type: Documentation\n    url: https://www.aoc.gov/\n  - type: GettingStarted\n    url: https://www.aoc.gov/about-us\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/architect-of-the-capitol/refs/heads/main/openapi/aoc-data-api.yaml\ncommon:\n- type: Portal\n  url: https://www.aoc.gov/\n- type: Documentation\n  url: https://www.aoc.gov/\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/architect-of-the-capitol/refs/heads/main/rules/aoc-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/architect-of-the-capitol/refs/heads/main/vocabulary/aoc-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/architect-of-the-capitol/refs/heads/main/json-ld/aoc-data-api-context.jsonld\n- type: Features\n  data:\n  - name:\
  \ Capitol Campus Buildings\n    description: Information about the US Capitol, House and Senate office buildings, Library of Congress, and Supreme Court.\n  - name: Art Collections\n    description: Access to the Capitol art collection catalog including paintings, sculptures, and historic artifacts.\n  - name: Historic Preservation Projects\n    description: Data on preservation and restoration projects across the Capitol campus.\n  - name: Accessibility Information\n    description: Accessibility features and visitor accommodations across Capitol campus facilities.\n  - name: Congressional Facilities\n    description: Management of congressional office space, hearing rooms, and support facilities.\n- type: UseCases\n  data:\n  - name: Visitor Information\n    description: Provide Capitol campus visitor information including building access, tours, and facilities.\n  - name: Art Research\n    description: Research the Capitol art collection for educational and historical purposes.\n  -\
  \ name: Historic Preservation\n    description: Track preservation project status and outcomes for historic Capitol structures.\n  - name: Congressional Services\n    description: Support congressional staff with facilities management and space planning information.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/architect-of-the-capitol/refs/heads/main/apis.yml
tags:
- Federal Government
- Capitol Hill
- Congress
- Historic Preservation
- Government Services
url: https://raw.githubusercontent.com/api-evangelist/architect-of-the-capitol/refs/heads/main/apis.yml
use_cases:
- description: Provide Capitol campus visitor information including building access, tours, and facilities.
  name: Visitor Information
- description: Research the Capitol art collection for educational and historical purposes.
  name: Art Research
- description: Track preservation project status and outcomes for historic Capitol structures.
  name: Historic Preservation
- description: Support congressional staff with facilities management and space planning information.
  name: Congressional Services
---
