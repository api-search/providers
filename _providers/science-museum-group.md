---
api_count: 1
api_specs:
- filename: science-museum-group-collection-openapi.yml
  format: yaml
  label: Science Museum Group Collection API
  slug: collection-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/science-museum-group/refs/heads/main/openapi/science-museum-group-collection-openapi.yml
apis:
- description: 'A JSONAPI-compliant REST API providing open access to the Science Museum Group''s collection of over 7 million objects, people, and documents across its five UK museums. Search and retrieve data about '
  name: Science Museum Group Collection API
  slug: collection-api
capabilities:
- description: Unified capability for exploring and discovering artifacts, people, and documents in the Science Museum Group's collection across five UK museums. Enables researchers, educators, developers, and cultu
  name: Science Museum Group Collection Discovery
  slug: collection-discovery
common:
- title: ''
  type: GitHub Organization
  url: https://github.com/TheScienceMuseum
- title: ''
  type: Website
  url: https://www.sciencemuseumgroup.org.uk/
- title: ''
  type: Collections Portal
  url: https://collection.sciencemuseumgroup.org.uk
created: '2026-05-02'
description: 'The Science Museum Group operates five UK science and technology museums: the Science Museum (London), the Science and Industry Museum (Manchester), the National Railway Museum (York), the National Science and Media Museum (Bradford), and Locomotion (Shildon). The group provides an open Collection API giving developers programmatic access to over 7 million objects, people, and documents in the museum collections via a JSONAPI-compliant REST interface. The API is free to use and supports searching, filtering, and retrieval of collection items with rich metadata, images, and curatorial notes.'
features: []
image: ''
integrations: []
jsonld:
- class_count: 23
  name: Science Museum Group Context
  property_count: 19
  slug: science-museum-group-context
layout: provider
modified: '2026-05-02'
name: Science Museum Group
rules:
- name: Science Museum Group API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 7
  slug: science-museum-group-rules
skills: []
slug: science-museum-group
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: science-museum-group\nname: Science Museum Group\ndescription: >-\n  The Science Museum Group operates five UK science and technology museums:\n  the Science Museum (London), the Science and Industry Museum (Manchester),\n  the National Railway Museum (York), the National Science and Media Museum\n  (Bradford), and Locomotion (Shildon). The group provides an open Collection\n  API giving developers programmatic access to over 7 million objects, people,\n  and documents in the museum collections via a JSONAPI-compliant REST interface.\n  The API is free to use and supports searching, filtering, and retrieval of\n  collection items with rich metadata, images, and curatorial notes.\nurl: https://raw.githubusercontent.com/api-evangelist/science-museum-group/refs/heads/main/apis.yml\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Museums\n  - Collections\n  - Cultural Heritage\n  - Open Data\n  - Science\n  - Technology\n  - United Kingdom\n\
  apis:\n  - aid: science-museum-group:collection-api\n    name: Science Museum Group Collection API\n    description: >-\n      A JSONAPI-compliant REST API providing open access to the Science Museum\n      Group's collection of over 7 million objects, people, and documents across\n      its five UK museums. Search and retrieve data about scientific instruments,\n      industrial artifacts, railway objects, and cultural items with image access,\n      pagination, and rich filtering by date, place, maker, museum, and category.\n    humanURL: https://www.sciencemuseumgroup.org.uk/our-work/our-collection/using-our-collection-api\n    baseURL: https://collection.sciencemuseumgroup.org.uk\n    tags:\n      - Collections\n      - Museums\n      - Open Data\n      - Cultural Heritage\n      - Science\n      - JSONAPI\n    properties:\n      - type: Documentation\n        url: https://www.sciencemuseumgroup.org.uk/our-work/our-collection/using-our-collection-api\n      - type: OpenAPI\n      \
  \  url: https://raw.githubusercontent.com/api-evangelist/science-museum-group/refs/heads/main/openapi/science-museum-group-collection-openapi.yml\n      - type: GitHub Repository\n        url: https://github.com/TheScienceMuseum/collectionsonline-api\n      - type: SpectralRules\n        url: https://raw.githubusercontent.com/api-evangelist/science-museum-group/refs/heads/main/rules/science-museum-group-rules.yml\n      - type: NaftikoCapabilities\n        url: https://raw.githubusercontent.com/api-evangelist/science-museum-group/refs/heads/main/capabilities/collection-discovery.yaml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/science-museum-group/refs/heads/main/json-schema/science-museum-group-collection-object-schema.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/science-museum-group/refs/heads/main/json-ld/science-museum-group-context.jsonld\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/science-museum-group/refs/heads/main/vocabulary/science-museum-group-vocabulary.yml\n\
  common:\n  - type: GitHub Organization\n    url: https://github.com/TheScienceMuseum\n  - type: Website\n    url: https://www.sciencemuseumgroup.org.uk/\n  - type: Collections Portal\n    url: https://collection.sciencemuseumgroup.org.uk\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/science-museum-group/refs/heads/main/apis.yml
tags:
- Museums
- Collections
- Cultural Heritage
- Open Data
- Science
- Technology
- United Kingdom
url: https://raw.githubusercontent.com/api-evangelist/science-museum-group/refs/heads/main/apis.yml
use_cases: []
---
