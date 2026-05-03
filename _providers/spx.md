---
api_count: 1
api_specs:
- filename: spx-graphics-control-api-openapi.yml
  format: yaml
  label: SPX Graphics Control API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spx/refs/heads/main/openapi/spx-graphics-control-api-openapi.yml
apis:
- description: The SPX Graphics Control REST API provides external control over the SPX-GC graphics control system. It allows applications and devices such as Stream Deck to trigger graphics playback, control rundow
  name: SPX Graphics Control API
  slug: ''
capabilities:
- description: Unified capability for live video production graphics control using SPX-GC. Enables broadcast operators, stream producers, and automation systems to control graphics rundowns, trigger template playbac
  name: SPX Live Graphics Production
  slug: live-graphics-production
common:
- title: ''
  type: Website
  url: https://spxgraphics.com
- title: ''
  type: GitHub
  url: https://github.com/TuomoKu/SPX-GC
- title: ''
  type: Documentation
  url: https://spxgc.tawk.help/
- title: ''
  type: KnowledgeBase
  url: https://spxgc.tawk.help/
created: '2026-05-02'
description: SPX Graphics is an open-source, browser-based graphics control system for live video productions and live streams. It provides a REST API for external control of graphics templates, rundowns, and playback via integrations with CasparCG, OBS, vMix, and similar broadcast software. SPX enables operators to trigger, control, and update live graphics overlays programmatically or via UI.
features: []
image: https://spxgraphics.com/wp-content/uploads/2021/05/spx-logo.png
integrations: []
jsonld:
- class_count: 20
  name: Spx Context
  property_count: 4
  slug: spx-context
layout: provider
modified: '2026-05-02'
name: SPX Graphics
rules:
- name: SPX Graphics API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 6
  slug: spx-rules
skills: []
slug: spx
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spx\nname: SPX Graphics\ndescription: >-\n  SPX Graphics is an open-source, browser-based graphics control system for live\n  video productions and live streams. It provides a REST API for external control\n  of graphics templates, rundowns, and playback via integrations with CasparCG,\n  OBS, vMix, and similar broadcast software. SPX enables operators to trigger,\n  control, and update live graphics overlays programmatically or via UI.\nimage: https://spxgraphics.com/wp-content/uploads/2021/05/spx-logo.png\nurl: https://spxgraphics.com\ncreated: '2026-05-02'\nmodified: '2026-05-02'\napis:\n  - name: SPX Graphics Control API\n    description: >-\n      The SPX Graphics Control REST API provides external control over the SPX-GC\n      graphics control system. It allows applications and devices such as Stream Deck\n      to trigger graphics playback, control rundowns, manage templates, and interact\n      with SPX extensions. The API runs locally on port 5656 and supports\
  \ optional\n      API key authentication.\n    image: https://spxgraphics.com/wp-content/uploads/2021/05/spx-logo.png\n    humanUrl: https://spxgc.tawk.help/article/help-api\n    baseUrl: http://localhost:5656\n    tags:\n      - Graphics\n      - Live Production\n      - Broadcast\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://spxgc.tawk.help/article/help-api\n      - type: GitHub\n        url: https://github.com/TuomoKu/SPX-GC\n      - type: OpenAPI\n        url: openapi/spx-graphics-control-api-openapi.yml\n      - type: GettingStarted\n        url: https://spxgc.tawk.help/article/help-intro\n      - type: ChangeLog\n        url: https://github.com/TuomoKu/SPX-GC/blob/master/RELEASE_NOTES.md\n      - type: JSONSchema\n        url: json-schema/spx-rundown-item-schema.json\n      - type: JSONStructure\n        url: json-structure/spx-rundown-item-structure.json\n      - type: JSONLD\n        url: json-ld/spx-context.jsonld\n      - type: SpectralRules\n\
  \        url: rules/spx-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/live-graphics-production.yaml\n      - type: Vocabulary\n        url: vocabulary/spx-vocabulary.yml\n    contact:\n      - type: GitHub\n        url: https://github.com/TuomoKu/SPX-GC\ncommon:\n  - type: Website\n    url: https://spxgraphics.com\n  - type: GitHub\n    url: https://github.com/TuomoKu/SPX-GC\n  - type: Documentation\n    url: https://spxgc.tawk.help/\n  - type: KnowledgeBase\n    url: https://spxgc.tawk.help/\nmaintainers:\n  - name: Tuomo Kulomaa\n    url: https://github.com/TuomoKu\ntags:\n  - Broadcast\n  - Graphics\n  - Live Production\n  - Media\n  - Streaming\n  - Video Production\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spx/refs/heads/main/apis.yml
tags:
- Broadcast
- Graphics
- Live Production
- Media
- Streaming
- Video Production
url: https://spxgraphics.com
use_cases: []
---
