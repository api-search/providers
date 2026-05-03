---
api_count: 1
api_specs:
- filename: warner-music-group-licensing-openapi.yml
  format: yaml
  label: Warner Music Group Licensing API
  slug: wmg-licensing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/warner-music-group/refs/heads/main/openapi/warner-music-group-licensing-openapi.yml
apis:
- description: The Warner Music Group Licensing API enables content creators and developers to request synchronization licenses, mechanical licenses, and other music rights for WMG's catalog of recordings and compos
  name: Warner Music Group Licensing API
  slug: wmg-licensing-api
capabilities:
- description: Unified workflow for Warner Music Group music licensing operations. Enables content creators, developers, and licensing professionals to search the WMG catalog, discover tracks, and submit license req
  name: Warner Music Group Music Licensing
  slug: music-licensing
common:
- title: ''
  type: Website
  url: https://www.wmg.com/
- title: ''
  type: Portal
  url: https://www.wmgmusiclicensing.com/
- title: ''
  type: Website
  url: https://warnerchappell.com/
- title: ''
  type: Documentation
  url: https://warnerchappell.com/music-licensing
- title: ''
  type: Website
  url: https://www.warnerchappellpm.com/
- title: ''
  type: Portal
  url: https://developer.wmg.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/wmg
created: '2026-03-24'
description: Warner Music Group is one of the major record labels in the music industry, with recorded music and music publishing operations spanning a roster of artists, songwriters, and labels around the world. WMG includes Warner Records, Atlantic Records, Elektra Records, and Warner Chappell Music (one of the world's largest music publishing companies). WMG provides music licensing APIs and developer tools for integrating licensed music into applications.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Warner Music Group Context
  property_count: 15
  slug: warner-music-group-context
layout: provider
modified: '2026-05-03'
name: Warner Music Group
rules:
- name: Warner Music Group API Rules
  rule_count: 10
  severity_counts:
    error: 6
    hint: 0
    info: 1
    warn: 3
  slug: warner-music-group-rules
skills: []
slug: warner-music-group
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: warner-music-group\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/warner-music-group/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nname: Warner Music Group\ntags:\n  - Music\n  - Entertainment\n  - Streaming\n  - Licensing\n  - Publishing\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nposition: Consumer\ndescription: >-\n  Warner Music Group is one of the major record labels in the music industry,\n  with recorded music and music publishing operations spanning a roster of\n  artists, songwriters, and labels around the world. WMG includes Warner\n  Records, Atlantic Records, Elektra Records, and Warner Chappell Music\n  (one of the world's largest music publishing companies). WMG provides\n  music licensing APIs and developer tools for integrating licensed music\n  into applications.\napis:\n  - aid: warner-music-group:wmg-licensing-api\n    name: Warner Music Group\
  \ Licensing API\n    tags:\n      - Music Licensing\n      - Sync Licensing\n      - Content Rights\n      - Publishing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.wmg.com\n    humanURL: https://www.wmgmusiclicensing.com/\n    properties:\n      - url: https://www.wmgmusiclicensing.com/\n        type: Documentation\n      - url: openapi/warner-music-group-licensing-openapi.yml\n        type: OpenAPI\n      - url: rules/warner-music-group-rules.yml\n        type: SpectralRules\n      - url: capabilities/music-licensing.yaml\n        type: NaftikoCapabilities\n      - url: json-schema/warner-music-group-license-schema.json\n        type: JSONSchema\n      - url: json-ld/warner-music-group-context.jsonld\n        type: JSONLDContext\n      - url: vocabulary/warner-music-group-vocabulary.yml\n        type: Vocabulary\n    description: >-\n      The Warner Music Group Licensing API enables content creators and\n      developers\
  \ to request synchronization licenses, mechanical licenses,\n      and other music rights for WMG's catalog of recordings and compositions.\n      The API covers tracks from Warner Records, Atlantic Records, Elektra,\n      and Warner Chappell Music publishing.\ncommon:\n  - url: https://www.wmg.com/\n    name: Warner Music Group\n    type: Website\n  - url: https://www.wmgmusiclicensing.com/\n    name: WMG Music Licensing Portal\n    type: Portal\n  - url: https://warnerchappell.com/\n    name: Warner Chappell Music\n    type: Website\n  - url: https://warnerchappell.com/music-licensing\n    name: Warner Chappell Music Licensing\n    type: Documentation\n  - url: https://www.warnerchappellpm.com/\n    name: Warner Chappell Production Music\n    type: Website\n  - url: https://developer.wmg.com/\n    name: WMG Developer Portal\n    type: Portal\n  - url: https://github.com/wmg\n    name: WMG GitHub Organization\n    type: GitHubOrganization\nlabels:\n  - Warner Records\n  - Atlantic Records\n\
  \  - Elektra Records\n  - Reprise Records\n  - Parlophone\n  - Sire Records\npublishers:\n  - Warner Chappell Music\n  - Warner Chappell Production Music\nfeatures:\n  - Sync Licensing (film, TV, advertising, gaming)\n  - Mechanical Licensing\n  - Digital Licensing (streaming, download)\n  - Production Music Library\n  - Artist and Release Catalog Search\n  - License Status Tracking\nuseCases:\n  - License music for film and television productions\n  - Clear music rights for advertising and brand campaigns\n  - Integrate licensed music into apps and digital products\n  - Access production music for video content creation\n  - Discover and license music from major artists\nintegrations:\n  - Adaptr (music licensing SDK)\n  - Feed Media Group\n  - Spotify (content delivery)\n  - Apple Music (content delivery)\n  - YouTube Content ID\nsolutions:\n  - Music Licensing\n  - Sync Licensing\n  - Music Publishing\n  - Artist Management Data\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\
  specificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/warner-music-group/refs/heads/main/apis.yml
tags:
- Music
- Entertainment
- Streaming
- Licensing
- Publishing
url: https://raw.githubusercontent.com/api-evangelist/warner-music-group/refs/heads/main/apis.yml
use_cases: []
---
