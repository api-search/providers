---
api_count: 1
api_specs:
- filename: rescuegroups-org-openapi.yml
  format: yaml
  label: RescueGroups.org API
  slug: rescuegroups-org
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/openapi/rescuegroups-org-openapi.yml
apis:
- description: 'The RescueGroups.org REST API v5 provides access to adoptable pet data including animals, organizations, breeds, species, colors, and patterns. It supports advanced search with geodistance filtering, '
  name: RescueGroups.org API
  slug: rescuegroups-org
capabilities:
- description: Workflow capability for searching and discovering adoptable pets and rescue organizations. Enables geographic search, breed/species filtering, and organization lookup for pet adoption platforms, rescu
  name: RescueGroups.org Pet Adoption Search
  slug: pet-adoption-search
common:
- title: ''
  type: Website
  url: https://rescuegroups.org/
- title: ''
  type: Documentation
  url: https://userguide.rescuegroups.org/spaces/APIDG/pages/8192120/API+Developers+Guide+Home
- title: ''
  type: PostmanCollection
  url: https://documenter.getpostman.com/view/60615/SWT5j1e4
- title: ''
  type: CommunityForum
  url: https://groups.google.com/a/rescuegroups.org/g/apidev
- title: ''
  type: Authentication
  url: https://userguide.rescuegroups.org/spaces/APIDG/pages/24053254/v5
- title: ''
  type: About
  url: https://rescuegroups.org/about/
created: '2025-01-07'
description: RescueGroups.org provides the only updatable HTTP/JSON API for adoptable pet data, offering comprehensive search across animals, organizations, breeds, species, colors, and patterns with geodistance filtering. The API supports both public read-only access via API key and authenticated write access via bearer token, enabling rescue organizations to manage and share pet adoption data in real time.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 15
  name: Rescuegroups Org Context
  property_count: 0
  slug: rescuegroups-org-context
layout: provider
modified: '2026-05-02'
name: RescueGroups.org
rules:
- name: RescueGroups.org API Rules
  rule_count: 11
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 7
  slug: rescuegroups-org-rules
skills: []
slug: rescuegroups-org
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rescuegroups-org\nname: RescueGroups.org\ndescription: >-\n  RescueGroups.org provides the only updatable HTTP/JSON API for adoptable pet\n  data, offering comprehensive search across animals, organizations, breeds,\n  species, colors, and patterns with geodistance filtering. The API supports\n  both public read-only access via API key and authenticated write access via\n  bearer token, enabling rescue organizations to manage and share pet adoption\n  data in real time.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Animals\n  - Pet Adoption\n  - Rescue\n  - Animal Welfare\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/apis.yml\ncreated: '2025-01-07'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rescuegroups-org:rescuegroups-org\n    name: RescueGroups.org API\n    description: >-\n      The RescueGroups.org REST API v5 provides access to\
  \ adoptable pet data\n      including animals, organizations, breeds, species, colors, and patterns.\n      It supports advanced search with geodistance filtering, pagination, and\n      relationship inclusion. API key authorization is used for public data\n      access; bearer token authorization is used for private/write operations.\n    humanURL: https://rescuegroups.org/services/adoptable-pet-data-api/\n    baseURL: https://api.rescuegroups.org/v5\n    tags:\n      - Animals\n      - Pet Adoption\n      - Rescue\n      - Organizations\n      - Animal Welfare\n      - Breeds\n      - Species\n    properties:\n      - type: Documentation\n        url: https://userguide.rescuegroups.org/spaces/APIDG/pages/24053254/v5\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/openapi/rescuegroups-org-openapi.yml\n      - type: PostmanCollection\n        url: https://documenter.getpostman.com/view/60615/SWT5j1e4\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/json-schema/rescuegroups-org-animal-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/json-schema/rescuegroups-org-organization-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/json-structure/rescuegroups-org-animal-structure.json\n      - type: JSONLDContext\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/json-ld/rescuegroups-org-context.jsonld\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/rules/rescuegroups-org-rules.yml\n      - type: NaftikoCapabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/capabilities/pet-adoption-search.yaml\n\
  \      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/vocabulary/rescuegroups-org-vocabulary.yml\n    contact:\n      - FN: RescueGroups.org Developer Community\n        url: https://groups.google.com/a/rescuegroups.org/g/apidev\ncommon:\n  - type: Website\n    url: https://rescuegroups.org/\n  - type: Documentation\n    url: https://userguide.rescuegroups.org/spaces/APIDG/pages/8192120/API+Developers+Guide+Home\n  - type: PostmanCollection\n    url: https://documenter.getpostman.com/view/60615/SWT5j1e4\n  - type: CommunityForum\n    url: https://groups.google.com/a/rescuegroups.org/g/apidev\n  - type: Authentication\n    url: https://userguide.rescuegroups.org/spaces/APIDG/pages/24053254/v5\n  - type: About\n    url: https://rescuegroups.org/about/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/apis.yml
tags:
- Animals
- Pet Adoption
- Rescue
- Animal Welfare
url: https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/apis.yml
use_cases: []
---
