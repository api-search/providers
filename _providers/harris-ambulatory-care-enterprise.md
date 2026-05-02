---
api_count: 4
apis:
- description: The Pulse §170.315(g)(10) ONC Certified FHIR API enables third-party application developers to register, authenticate, and integrate with providers using Harris Pulse EHR software. The documentation d
  name: Pulse FHIR API
  slug: pulse-fhir-api
- description: Amazing Charts is an EHR product within Harris Ambulatory Care Enterprise that exposes a §170.315(g)(10) ONC Certified FHIR API for third-party application developers.
  name: Amazing Charts API
  slug: amazing-charts-api
- description: CareTracker is a Harris Ambulatory Care Enterprise EHR product that provides a §170.315(g)(10) ONC Certified FHIR API for third-party developers.
  name: CareTracker API
  slug: caretracker-api
- description: Picasso is an ambulatory practice management product within Harris Ambulatory Care Enterprise that provides API documentation for third-party integrators.
  name: Picasso API
  slug: picasso-api
common:
- title: ''
  type: Website
  url: https://harrisambulatory.com
- title: ''
  type: Pulse Documentation
  url: https://harrisambulatory.com/pulse-api-documentation/
- title: ''
  type: Amazing Charts Documentation
  url: https://harrisambulatory.com/ac-api-documentation/
- title: ''
  type: CareTracker Documentation
  url: https://harrisambulatory.com/caretracker-api-documentation/
- title: ''
  type: Picasso Documentation
  url: https://harrisambulatory.com/picasso-api-documentation/
- title: ''
  type: Parent Company
  url: https://www.harriscomputer.com
created: '2025-02-24'
description: Harris Ambulatory Care Enterprise (part of Harris Healthcare, a Harris Computer company) provides ambulatory healthcare software solutions including the Pulse electronic health record system. The platform supports a §170.315(g)(10) ONC certified FHIR API for third-party application developers to access patient data, provider information, and clinical resources. Pulse is deployed on-premises, so each provider hosts a separate API instance with its own base URL. Third-party developers must obtain an ONC 2015 Edition Certified API License and register with each provider organization.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Harris Ambulatory Care Enterprise
skills: []
slug: harris-ambulatory-care-enterprise
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: harris-ambulatory-care-enterprise\nname: Harris Ambulatory Care Enterprise\ndescription: >-\n  Harris Ambulatory Care Enterprise (part of Harris Healthcare, a Harris Computer\n  company) provides ambulatory healthcare software solutions including the Pulse\n  electronic health record system. The platform supports a §170.315(g)(10) ONC\n  certified FHIR API for third-party application developers to access patient\n  data, provider information, and clinical resources. Pulse is deployed\n  on-premises, so each provider hosts a separate API instance with its own base\n  URL. Third-party developers must obtain an ONC 2015 Edition Certified API\n  License and register with each provider organization.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Ambulatory Care\n  - Electronic Health Records\n  - FHIR\n  - Health IT\n  - Healthcare\n  - ONC Certified\n  - Pulse\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/harris-ambulatory-care-enterprise/refs/heads/main/apis.yml\n\
  created: '2025-02-24'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: harris-ambulatory-care-enterprise:pulse-fhir-api\n    name: Pulse FHIR API\n    description: >-\n      The Pulse §170.315(g)(10) ONC Certified FHIR API enables third-party\n      application developers to register, authenticate, and integrate with\n      providers using Harris Pulse EHR software. The documentation describes\n      registration, syntax, supported FHIR resources, and error handling.\n      Because Pulse is deployed per provider, each customer hosts a separate\n      API instance with its own base URL.\n    humanURL: https://harrisambulatory.com/pulse-api-documentation/\n    baseURL: https://harrisambulatory.com/pulse-api-documentation/\n    tags:\n      - FHIR\n      - Healthcare\n      - Pulse\n    properties:\n      - type: Documentation\n        url: https://harrisambulatory.com/pulse-api-documentation/\n      - type: FHIR Documentation PDF\n        url: https://harrisambulatory.com/wp-content/uploads/2023/01/Pulse-8.0-API-FHIR-Documentation.pdf\n\
  \      - type: Provider Site\n        url: https://harrisambulatory.com\n  - aid: harris-ambulatory-care-enterprise:amazing-charts-api\n    name: Amazing Charts API\n    description: >-\n      Amazing Charts is an EHR product within Harris Ambulatory Care Enterprise\n      that exposes a §170.315(g)(10) ONC Certified FHIR API for third-party\n      application developers.\n    humanURL: https://harrisambulatory.com/ac-api-documentation/\n    baseURL: https://harrisambulatory.com/ac-api-documentation/\n    tags:\n      - FHIR\n      - Healthcare\n      - Amazing Charts\n    properties:\n      - type: Documentation\n        url: https://harrisambulatory.com/ac-api-documentation/\n  - aid: harris-ambulatory-care-enterprise:caretracker-api\n    name: CareTracker API\n    description: >-\n      CareTracker is a Harris Ambulatory Care Enterprise EHR product that\n      provides a §170.315(g)(10) ONC Certified FHIR API for third-party\n      developers.\n    humanURL: https://harrisambulatory.com/caretracker-api-documentation/\n\
  \    baseURL: https://harrisambulatory.com/caretracker-api-documentation/\n    tags:\n      - FHIR\n      - Healthcare\n      - CareTracker\n    properties:\n      - type: Documentation\n        url: https://harrisambulatory.com/caretracker-api-documentation/\n  - aid: harris-ambulatory-care-enterprise:picasso-api\n    name: Picasso API\n    description: >-\n      Picasso is an ambulatory practice management product within Harris\n      Ambulatory Care Enterprise that provides API documentation for\n      third-party integrators.\n    humanURL: https://harrisambulatory.com/picasso-api-documentation/\n    baseURL: https://harrisambulatory.com/picasso-api-documentation/\n    tags:\n      - Healthcare\n      - Picasso\n    properties:\n      - type: Documentation\n        url: https://harrisambulatory.com/picasso-api-documentation/\ncommon:\n  - type: Website\n    url: https://harrisambulatory.com\n  - type: Pulse Documentation\n    url: https://harrisambulatory.com/pulse-api-documentation/\n\
  \  - type: Amazing Charts Documentation\n    url: https://harrisambulatory.com/ac-api-documentation/\n  - type: CareTracker Documentation\n    url: https://harrisambulatory.com/caretracker-api-documentation/\n  - type: Picasso Documentation\n    url: https://harrisambulatory.com/picasso-api-documentation/\n  - type: Parent Company\n    url: https://www.harriscomputer.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/harris-ambulatory-care-enterprise/refs/heads/main/apis.yml
tags:
- Ambulatory Care
- Electronic Health Records
- FHIR
- Health IT
- Healthcare
- ONC Certified
- Pulse
url: https://raw.githubusercontent.com/api-evangelist/harris-ambulatory-care-enterprise/refs/heads/main/apis.yml
use_cases: []
---
