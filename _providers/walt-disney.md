---
api_count: 1
api_specs:
- filename: walt-disney-disney-api-openapi.yml
  format: yaml
  label: Disney Characters API
  slug: disney-characters-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/walt-disney/refs/heads/main/openapi/walt-disney-disney-api-openapi.yml
apis:
- description: The Disney Characters API provides REST and GraphQL interfaces to a comprehensive database of 9,820+ Disney characters across all Disney brands including Walt Disney Animation, Pixar, Marvel, Star War
  name: Disney Characters API
  slug: disney-characters-api
capabilities:
- description: Workflow for discovering Disney characters and content metadata across films, TV shows, video games, and park attractions. Enables content applications, fans, and media platforms to explore Disney's c
  name: Disney Content Discovery
  slug: disney-content-discovery
common:
- title: ''
  type: Website
  url: https://www.disney.com/
- title: ''
  type: Portal
  url: https://disneyapi.dev/
- title: ''
  type: Documentation
  url: https://disneyapi.dev/docs/
- title: ''
  type: GitHubOrganization
  url: https://disney.github.io/
- title: ''
  type: GitHubOrganization
  url: https://github.com/disney
- title: ''
  type: GitHubOrganization
  url: https://github.com/disneystreaming
- title: ''
  type: Blog
  url: https://medium.com/disney-streaming
- title: ''
  type: Portal
  url: https://developer.disney.com/
created: '2026-03-21'
description: The Walt Disney Company is a leading diversified international family entertainment and media enterprise with operations across media networks, parks and resorts, studio entertainment, and direct-to-consumer streaming. Disney's developer APIs and open source projects enable partners and developers to integrate Disney content, characters, and experiences into their applications.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Walt Disney Context
  property_count: 11
  slug: walt-disney-context
layout: provider
modified: '2026-05-03'
name: Walt Disney
rules:
- name: Walt Disney API Rules
  rule_count: 9
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 4
  slug: walt-disney-rules
skills: []
slug: walt-disney
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: walt-disney\nurl: https://raw.githubusercontent.com/api-evangelist/walt-disney/refs/heads/main/apis.yml\nmodified: '2026-05-03'\ncreated: '2026-03-21'\nname: Walt Disney\ntags:\n  - Entertainment\n  - Media\n  - Streaming\n  - Parks\n  - Content\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nposition: Consumer\ndescription: >-\n  The Walt Disney Company is a leading diversified international family\n  entertainment and media enterprise with operations across media networks,\n  parks and resorts, studio entertainment, and direct-to-consumer streaming.\n  Disney's developer APIs and open source projects enable partners and developers\n  to integrate Disney content, characters, and experiences into their applications.\napis:\n  - aid: walt-disney:disney-characters-api\n    name: Disney Characters API\n    tags:\n      - Characters\n      - Content\n      - Entertainment\n      - Films\n      - Parks\n  \
  \    - Television\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.disneyapi.dev\n    humanURL: https://disneyapi.dev/\n    properties:\n      - url: https://disneyapi.dev/docs/\n        type: Documentation\n      - url: openapi/walt-disney-disney-api-openapi.yml\n        type: OpenAPI\n      - url: rules/walt-disney-rules.yml\n        type: SpectralRules\n      - url: capabilities/disney-content-discovery.yaml\n        type: NaftikoCapabilities\n      - url: json-schema/walt-disney-character-schema.json\n        type: JSONSchema\n      - url: json-ld/walt-disney-context.jsonld\n        type: JSONLDContext\n      - url: vocabulary/walt-disney-vocabulary.yml\n        type: Vocabulary\n    description: >-\n      The Disney Characters API provides REST and GraphQL interfaces to a\n      comprehensive database of 9,820+ Disney characters across all Disney brands\n      including Walt Disney Animation, Pixar, Marvel, Star Wars,\
  \ and National\n      Geographic. Each character includes associated films, short films, TV shows,\n      video games, park attractions, and character relationships. The API requires\n      no authentication and is freely accessible.\ncommon:\n  - url: https://www.disney.com/\n    name: Walt Disney Company\n    type: Website\n  - url: https://disneyapi.dev/\n    name: Disney Characters API\n    type: Portal\n  - url: https://disneyapi.dev/docs/\n    name: Disney API Documentation\n    type: Documentation\n  - url: https://disney.github.io/\n    name: Disney Open Source\n    type: GitHubOrganization\n  - url: https://github.com/disney\n    name: Disney GitHub Organization\n    type: GitHubOrganization\n  - url: https://github.com/disneystreaming\n    name: Disney Streaming GitHub Organization\n    type: GitHubOrganization\n  - url: https://medium.com/disney-streaming\n    name: Disney Streaming Engineering Blog\n    type: Blog\n  - url: https://developer.disney.com/\n    name: Disney Developer\
  \ Portal\n    type: Portal\nfeatures:\n  - Disney Character Database (9,820+ characters)\n  - REST API (no authentication required)\n  - GraphQL API\n  - Character-to-media cross-references (films, TV, games, parks)\n  - Character relationship mapping (allies, enemies)\n  - Pagination support\n  - Disney Parks Attraction Data\nopenSource:\n  - name: Quanta\n    description: Roaring bitmap-based HTAP database engine\n    url: https://github.com/disney/quanta\n  - name: Automated Cloud Advisor\n    description: AWS cost optimization tool\n    url: https://github.com/disneystreaming/automated-cloud-advisor\n  - name: Groovity\n    description: Modular scripting language for REST APIs\n    url: https://github.com/disney/groovity\n  - name: MaterialX\n    description: Open standard for material and look-development content\n    url: https://github.com/materialx/MaterialX\n  - name: Universal Scene Description (USD)\n    description: Software for robust 3D scene interchange\n    url: https://github.com/PixarAnimationStudios/USD\n\
  \  - name: OpenSubdiv\n    description: High-performance subdivision surface evaluation\n    url: https://github.com/PixarAnimationStudios/OpenSubdiv\n  - name: OpenEXR\n    description: High dynamic-range image file format\n    url: https://github.com/openexr/openexr\n  - name: weaver-test\n    description: Scala test framework for Cats-Effect\n    url: https://github.com/disneystreaming/weaver-test\nsolutions:\n  - Entertainment Content APIs\n  - Character Data\n  - Media Metadata\n  - Open Source Graphics Standards\n  - Cloud Infrastructure Tools\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/walt-disney/refs/heads/main/apis.yml
tags:
- Entertainment
- Media
- Streaming
- Parks
- Content
url: https://raw.githubusercontent.com/api-evangelist/walt-disney/refs/heads/main/apis.yml
use_cases: []
---
