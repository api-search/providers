---
api_count: 3
apis:
- description: 'The SCORM 1.2 Run-Time Environment defines communication between e-learning content and an LMS via a JavaScript API. The API Adapter is an ECMAScript object named "API" accessible through the DOM. It '
  name: SCORM 1.2 Runtime API
  slug: scorm-12
- description: The SCORM 2004 Run-Time Environment extends SCORM 1.2 with improved sequencing and navigation capabilities. The API Adapter is an ECMAScript object named "API_1484_11". It supports 8 core API function
  name: SCORM 2004 Runtime API
  slug: scorm-2004
- description: xAPI (Experience API), also known as Tin Can API, is the modern successor to SCORM developed by ADL. It uses a Learning Record Store (LRS) and defines learning statements in a subject-verb-object form
  name: xAPI (Experience API / Tin Can)
  slug: xapi
common: []
created: '2026-05-02'
description: SCORM (Sharable Content Object Reference Model) is a set of technical standards for e-learning software products. Originally developed by the Advanced Distributed Learning (ADL) Initiative, SCORM defines how online learning content and Learning Management Systems (LMS) communicate with each other, enabling interoperability between authoring tools, content packages, and LMS platforms. Key versions include SCORM 1.2 and SCORM 2004, with xAPI (Tin Can) as a modern successor.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Scorm Context
  property_count: 16
  slug: scorm-context
layout: provider
modified: '2026-05-02'
name: SCORM
skills: []
slug: scorm
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: scorm\nname: SCORM\ndescription: >-\n  SCORM (Sharable Content Object Reference Model) is a set of technical\n  standards for e-learning software products. Originally developed by the\n  Advanced Distributed Learning (ADL) Initiative, SCORM defines how online\n  learning content and Learning Management Systems (LMS) communicate with each\n  other, enabling interoperability between authoring tools, content packages,\n  and LMS platforms. Key versions include SCORM 1.2 and SCORM 2004, with\n  xAPI (Tin Can) as a modern successor.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - E-Learning\n  - LMS\n  - Standards\n  - Education\n  - Interoperability\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/scorm/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: scorm:scorm-12\n    name: SCORM 1.2 Runtime API\n\
  \    description: >-\n      The SCORM 1.2 Run-Time Environment defines communication between e-learning\n      content and an LMS via a JavaScript API. The API Adapter is an ECMAScript\n      object named \"API\" accessible through the DOM. It enables content to\n      initialize sessions, get and set CMI data model values, commit data, and\n      retrieve error information.\n    humanURL: https://scorm.com/scorm-explained/technical-scorm/scorm-12-overview-for-developers/\n    tags:\n      - E-Learning\n      - LMS\n      - Standards\n      - SCORM 1.2\n    properties:\n      - type: Documentation\n        url: https://scorm.com/scorm-explained/technical-scorm/scorm-12-overview-for-developers/\n      - type: Specification\n        url: https://adlnet.gov/projects/scorm/\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/scorm/refs/heads/main/json-schema/scorm-cmi-data-schema.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/scorm/refs/heads/main/json-structure/scorm-package-structure.json\n\
  \      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/scorm/refs/heads/main/json-ld/scorm-context.jsonld\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/scorm/refs/heads/main/vocabulary/scorm-vocabulary.yml\n      - type: Example\n        url: https://raw.githubusercontent.com/api-evangelist/scorm/refs/heads/main/examples/scorm-api-initialize-example.json\n  - aid: scorm:scorm-2004\n    name: SCORM 2004 Runtime API\n    description: >-\n      The SCORM 2004 Run-Time Environment extends SCORM 1.2 with improved\n      sequencing and navigation capabilities. The API Adapter is an ECMAScript\n      object named \"API_1484_11\". It supports 8 core API functions for session\n      management, data model access, and error reporting, plus a richer CMI\n      data model with completion status, success status, score, and interaction\n      tracking.\n    humanURL: https://scorm.com/scorm-explained/technical-scorm/scorm-2004-overview-for-developers/\n\
  \    tags:\n      - E-Learning\n      - LMS\n      - Standards\n      - SCORM 2004\n    properties:\n      - type: Documentation\n        url: https://scorm.com/scorm-explained/technical-scorm/scorm-2004-overview-for-developers/\n      - type: Specification\n        url: https://adlnet.gov/projects/scorm/\n  - aid: scorm:xapi\n    name: xAPI (Experience API / Tin Can)\n    description: >-\n      xAPI (Experience API), also known as Tin Can API, is the modern successor\n      to SCORM developed by ADL. It uses a Learning Record Store (LRS) and\n      defines learning statements in a subject-verb-object format, enabling\n      tracking of a much wider range of learning experiences beyond traditional\n      LMS-hosted content.\n    humanURL: https://xapi.com/\n    tags:\n      - E-Learning\n      - Standards\n      - xAPI\n      - Tin Can\n    properties:\n      - type: Documentation\n        url: https://xapi.com/overview/\n      - type: Specification\n        url: https://github.com/adlnet/xAPI-Spec\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scorm/refs/heads/main/apis.yml
tags:
- E-Learning
- LMS
- Standards
- Education
- Interoperability
url: https://raw.githubusercontent.com/api-evangelist/scorm/refs/heads/main/apis.yml
use_cases: []
---
