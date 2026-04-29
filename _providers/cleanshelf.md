---
api_count: 2
apis:
- description: The Zylo Platform API is the successor to Cleanshelf. It exposes SaaS application discovery, inventory, license, contract, and spend data so enterprises can integrate Zylo with finance, procurement, a
  name: Zylo Platform API (successor)
  slug: zylo-api
- description: Legacy v1.0 endpoints retained from the original Cleanshelf product line. New integrations should use the modern Zylo Platform API.
  name: Zylo Legacy API (Cleanshelf-era)
  slug: zylo-legacy-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://zylo.com/
- title: ''
  type: Acquirer
  url: https://zylo.com/
- title: ''
  type: Acquisition Announcement
  url: https://zylo.com/news/zylo-acquires-cleanshelf/
- title: ''
  type: Application
  url: https://app.zylo.com/
- title: ''
  type: Portal
  url: https://developer.zylo.com/
- title: ''
  type: Privacy Policy
  url: https://zylo.com/privacy-policy/
- title: ''
  type: Terms of Service
  url: https://zylo.com/legal/
- title: ''
  type: Support
  url: https://help.zylo.com/
- title: ''
  type: JSON-LD
  url: json-ld/cleanshelf-context.jsonld
- title: ''
  type: Spectral
  url: rules/cleanshelf-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cleanshelf-capabilities.yml
created: '2026-03-27'
description: Cleanshelf was a SaaS management platform that helped enterprises discover and inventory their SaaS applications, optimize software licenses, track spend, and surface shadow IT. Cleanshelf was acquired by Zylo in 2021 and its capabilities have been folded into the Zylo enterprise SaaS spend optimization platform. The Cleanshelf product brand and standalone API are no longer maintained; equivalent programmatic capabilities are now exposed through the Zylo Developer Hub at developer.zylo.com.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 13
  name: Cleanshelf Context
  property_count: 0
  slug: cleanshelf-context
layout: provider
modified: '2026-04-23'
name: Cleanshelf
rules:
- name: Cleanshelf API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: cleanshelf-rules
skills: []
slug: cleanshelf
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cleanshelf\nname: Cleanshelf\nurl: https://raw.githubusercontent.com/api-evangelist/cleanshelf/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\nstatus: Acquired\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Acquired\n  - License Management\n  - SaaS Management\n  - Shadow IT\n  - SMP\n  - Software Asset Management\n  - Spend Optimization\ndescription: >-\n  Cleanshelf was a SaaS management platform that helped enterprises\n  discover and inventory their SaaS applications, optimize software\n  licenses, track spend, and surface shadow IT. Cleanshelf was acquired\n  by Zylo in 2021 and its capabilities have been folded into the Zylo\n  enterprise SaaS spend optimization platform. The Cleanshelf product\n  brand and standalone API are no longer maintained; equivalent\n  programmatic capabilities are now exposed through\
  \ the Zylo Developer\n  Hub at developer.zylo.com.\napis:\n  - aid: cleanshelf:zylo-api\n    name: Zylo Platform API (successor)\n    tags:\n      - License Management\n      - SaaS Management\n      - Spend\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.zylo.com/\n    properties:\n      - url: https://developer.zylo.com/\n        type: Documentation\n      - url: https://developer.zylo.com/reference\n        type: API Reference\n    description: >-\n      The Zylo Platform API is the successor to Cleanshelf. It exposes\n      SaaS application discovery, inventory, license, contract, and\n      spend data so enterprises can integrate Zylo with finance,\n      procurement, and IT systems. A legacy v1.0 API remains documented\n      for older Cleanshelf-era integrations.\n  - aid: cleanshelf:zylo-legacy-api\n    name: Zylo Legacy API (Cleanshelf-era)\n    tags:\n      - Cleanshelf\n      - Legacy\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://developer.zylo.com/v1.0/reference/zylo-legacy-api\n    properties:\n      - url: https://developer.zylo.com/v1.0/reference/zylo-legacy-api\n        type: Documentation\n    description: >-\n      Legacy v1.0 endpoints retained from the original Cleanshelf\n      product line. New integrations should use the modern Zylo\n      Platform API.\ncommon:\n  - type: Website\n    url: https://zylo.com/\n  - type: Acquirer\n    url: https://zylo.com/\n  - type: Acquisition Announcement\n    url: https://zylo.com/news/zylo-acquires-cleanshelf/\n  - type: Application\n    url: https://app.zylo.com/\n  - type: Portal\n    url: https://developer.zylo.com/\n  - type: Privacy Policy\n    url: https://zylo.com/privacy-policy/\n  - type: Terms of Service\n    url: https://zylo.com/legal/\n  - type: Support\n    url: https://help.zylo.com/\n  - type: JSON-LD\n    url: json-ld/cleanshelf-context.jsonld\n  - type: Spectral\n    url: rules/cleanshelf-rules.yml\n  - type: Naftiko Capabilities\n\
  \    url: capabilities/cleanshelf-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cleanshelf/refs/heads/main/apis.yml
tags:
- Acquired
- License Management
- SaaS Management
- Shadow IT
- SMP
- Software Asset Management
- Spend Optimization
url: https://raw.githubusercontent.com/api-evangelist/cleanshelf/refs/heads/main/apis.yml
use_cases: []
---
