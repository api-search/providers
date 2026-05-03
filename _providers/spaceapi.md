---
api_count: 1
api_specs:
- filename: openapi.json
  format: json
  label: SpaceAPI Collector
  slug: spaceapi-collector
  spec_type: OpenAPI
  url: https://api.spaceapi.io/openapi.json
apis:
- description: The SpaceAPI Collector is a central directory API that aggregates endpoints from hackerspaces and makerspaces around the world that implement the SpaceAPI standard. It returns a list of all registered
  name: SpaceAPI Collector
  slug: spaceapi-collector
capabilities:
- description: Workflow capability for discovering and browsing hackerspaces, makerspaces, fablabs, and community spaces worldwide using the SpaceAPI directory. Useful for applications that want to help users find n
  name: SpaceAPI Space Discovery
  slug: space-discovery
common:
- title: ''
  type: Website
  url: https://spaceapi.io
- title: ''
  type: Documentation
  url: https://spaceapi.io/how-to-use/
- title: ''
  type: GitHub
  url: https://github.com/SpaceApi
- title: ''
  type: Directory
  url: https://directory.spaceapi.io/
created: '2024-11-07'
description: SpaceAPI is an open standard for hackerspaces, makerspaces, fablabs, and similar community spaces to publish real-time information about their spaces in a machine-readable JSON format. It provides a central directory (collector) that aggregates endpoints from participating spaces around the world, enabling applications to discover and display space status, location, contact, and operational information.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 8
  name: Spaceapi Context
  property_count: 7
  slug: spaceapi-context
layout: provider
modified: '2026-05-02'
name: SpaceAPI
rules:
- name: SpaceAPI API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 1
    warn: 6
  slug: spaceapi-rules
skills: []
slug: spaceapi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spaceapi\nurl: https://raw.githubusercontent.com/api-evangelist/spaceapi/refs/heads/main/apis.yml\nname: SpaceAPI\ndescription: >-\n  SpaceAPI is an open standard for hackerspaces, makerspaces, fablabs, and similar\n  community spaces to publish real-time information about their spaces in a machine-readable\n  JSON format. It provides a central directory (collector) that aggregates endpoints from\n  participating spaces around the world, enabling applications to discover and display space\n  status, location, contact, and operational information.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Co-Working\n  - Event Spaces\n  - Maker Spaces\n  - Hackerspaces\n  - Community\n  - Open Standard\ncreated: '2024-11-07'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: spaceapi:spaceapi-collector\n    name: SpaceAPI Collector\n    description: >-\n      The SpaceAPI Collector is a central directory\
  \ API that aggregates endpoints from\n      hackerspaces and makerspaces around the world that implement the SpaceAPI standard.\n      It returns a list of all registered spaces with their status endpoint URLs, validity,\n      names, and last-seen timestamps.\n    humanURL: https://spaceapi.io\n    baseURL: https://collector.spaceapi.io\n    tags:\n      - Co-Working\n      - Maker Spaces\n      - Hackerspaces\n      - Directory\n    properties:\n      - url: https://spaceapi.io\n        type: Documentation\n      - url: https://spaceapi.io/how-to-use/\n        type: Getting Started\n      - url: https://api.spaceapi.io/openapi.json\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/spaceapi/refs/heads/main/openapi/spaceapi-collector-openapi.yml\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/spaceapi/refs/heads/main/rules/spaceapi-rules.yml\n        type: SpectralRules\n      - url: https://raw.githubusercontent.com/api-evangelist/spaceapi/refs/heads/main/json-schema/spaceapi-directory-entry-schema.json\n\
  \        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/spaceapi/refs/heads/main/json-structure/spaceapi-directory-entry-structure.json\n        type: JSONStructure\n      - url: https://raw.githubusercontent.com/api-evangelist/spaceapi/refs/heads/main/json-ld/spaceapi-context.jsonld\n        type: JSONLDContext\n      - url: https://raw.githubusercontent.com/api-evangelist/spaceapi/refs/heads/main/vocabulary/spaceapi-vocabulary.yml\n        type: Vocabulary\ncommon:\n  - type: Website\n    url: https://spaceapi.io\n  - type: Documentation\n    url: https://spaceapi.io/how-to-use/\n  - type: GitHub\n    url: https://github.com/SpaceApi\n  - type: Directory\n    url: https://directory.spaceapi.io/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spaceapi/refs/heads/main/apis.yml
tags:
- Co-Working
- Event Spaces
- Maker Spaces
- Hackerspaces
- Community
- Open Standard
url: https://raw.githubusercontent.com/api-evangelist/spaceapi/refs/heads/main/apis.yml
use_cases: []
---
