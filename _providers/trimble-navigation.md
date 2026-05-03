---
api_count: 2
api_specs:
- filename: trimble-mobile-manager-openapi.yml
  format: yaml
  label: Trimble Mobile Manager API
  slug: trimble-mobile-manager
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trimble-navigation/refs/heads/main/openapi/trimble-mobile-manager-openapi.yml
apis:
- description: 'The Trimble Mobile Manager (TMM) API provides developer interfaces for integrating high-accuracy GNSS positioning from connected Trimble receivers into custom mobile applications. Offers a local REST '
  name: Trimble Mobile Manager API
  slug: trimble-mobile-manager
- description: The Trimble Advanced Positioning (TAP) Store API is a REST-based eCommerce API for purchasing and managing Trimble positioning service subscriptions including RTX correction services. Enables automate
  name: Trimble Positioning Services API
  slug: trimble-positioning-services
capabilities:
- description: Unified GNSS positioning capability combining Trimble Mobile Manager receiver integration, real-time position streaming, correction service management, and Catalyst license activation. Powers high-acc
  name: Trimble Navigation GNSS Positioning
  slug: gnss-positioning
common:
- title: ''
  type: Website
  url: https://www.trimble.com
- title: ''
  type: DeveloperPortal
  url: https://www.trimble.com/en/developer/docs
- title: ''
  type: Documentation
  url: https://developer.trimble.com/docs/mobile-manager/
- title: ''
  type: GettingStarted
  url: https://developer.trimble.com/docs/mobile-manager/guides/integrate/
created: '2026-05-03'
description: Trimble Navigation Limited (now Trimble Inc.) is a global technology company founded in 1978 that pioneered commercial GPS technology. Trimble develops positioning, navigation, and geospatial solutions spanning construction, agriculture, transportation, and surveying industries. The company rebranded from Trimble Navigation Limited to Trimble Inc. in 2016. Its developer APIs cover GPS/GNSS positioning through Trimble Mobile Manager, high-accuracy survey integration via the Trimble Precision SDK, and geospatial data services. The positioning technology integrates GPS, laser, optical, and inertial technologies to deliver centimeter-level accuracy for professional applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Trimble Navigation Context
  property_count: 25
  slug: trimble-navigation-context
layout: provider
modified: '2026-05-03'
name: Trimble Navigation
rules:
- name: Trimble Navigation API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: trimble-mobile-manager-rules
skills: []
slug: trimble-navigation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trimble-navigation\nname: Trimble Navigation\ndescription: >-\n  Trimble Navigation Limited (now Trimble Inc.) is a global technology company\n  founded in 1978 that pioneered commercial GPS technology. Trimble develops\n  positioning, navigation, and geospatial solutions spanning construction,\n  agriculture, transportation, and surveying industries. The company rebranded\n  from Trimble Navigation Limited to Trimble Inc. in 2016. Its developer APIs\n  cover GPS/GNSS positioning through Trimble Mobile Manager, high-accuracy\n  survey integration via the Trimble Precision SDK, and geospatial data services.\n  The positioning technology integrates GPS, laser, optical, and inertial\n  technologies to deliver centimeter-level accuracy for professional applications.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - GPS\n  - GNSS\n  - Positioning\n  - Navigation\n  - Surveying\n  - Geospatial\n  - Construction\nurl: >-\n\
  \  https://raw.githubusercontent.com/api-evangelist/trimble-navigation/refs/heads/main/apis.yml\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: trimble-navigation:trimble-mobile-manager\n    name: Trimble Mobile Manager API\n    description: >-\n      The Trimble Mobile Manager (TMM) API provides developer interfaces for\n      integrating high-accuracy GNSS positioning from connected Trimble receivers\n      into custom mobile applications. Offers a local REST API for configuration\n      and a WebSocket stream for real-time GNSS position delivery. Supports\n      Trimble Catalyst DA2, R580, R780, R12i, R980, and SP100 receivers.\n      Abstracts receiver hardware to enable forward-compatible precision positioning apps.\n    humanURL: https://developer.trimble.com/docs/mobile-manager/\n    tags:\n      - GPS\n      - GNSS\n      - Positioning\n      - Surveying\n      - Mobile\n      - WebSocket\n    properties:\n      - type: Documentation\n\
  \        url: https://developer.trimble.com/docs/mobile-manager/\n      - type: GettingStarted\n        url: https://developer.trimble.com/docs/mobile-manager/guides/integrate/\n      - type: OpenAPI\n        url: openapi/trimble-mobile-manager-openapi.yml\n\n  - aid: trimble-navigation:trimble-positioning-services\n    name: Trimble Positioning Services API\n    description: >-\n      The Trimble Advanced Positioning (TAP) Store API is a REST-based eCommerce\n      API for purchasing and managing Trimble positioning service subscriptions\n      including RTX correction services. Enables automated provisioning of\n      high-accuracy correction subscriptions for fleet and field deployments.\n    humanURL: https://www.trimble.com/en/developer/docs\n    tags:\n      - GPS\n      - GNSS Corrections\n      - RTX\n      - Positioning Services\n      - Subscriptions\n    properties:\n      - type: Documentation\n        url: https://www.trimble.com/en/developer/docs\n\nfeatures:\n  - Real-time\
  \ GNSS position streaming via WebSocket\n  - Receiver configuration via REST API\n  - High-accuracy RTK and RTX correction delivery\n  - Trimble Catalyst on-demand licensing\n  - GNSS reference frame transformation\n  - Multi-receiver hardware support\n  - Centimeter-level positioning accuracy\n  - Integration with Trimble CenterPoint RTX correction network\nuseCases:\n  - Mobile survey applications requiring high-accuracy GNSS positioning\n  - GIS data collection apps integrating Trimble receivers\n  - Construction layout and as-built documentation with precision GPS\n  - Precision agriculture positioning for guidance and variable-rate systems\n  - Utility and infrastructure asset mapping\n  - Transportation fleet positioning and navigation\nintegrations:\n  - Trimble Catalyst DA2 receiver\n  - Trimble R-series GNSS receivers (R580, R780, R12i, R980)\n  - Spectra Geospatial SP100\n  - Esri ArcGIS integration\n  - CenterPoint RTX correction network\n  - Trimble Mobile Manager iOS and Android\
  \ apps\nsolutions:\n  - Survey companies building custom GNSS data collection apps\n  - GIS professionals developing precision field mapping tools\n  - Agricultural technology companies integrating high-accuracy positioning\n  - Construction technology developers requiring centimeter GPS\ncommon:\n  - type: Website\n    url: https://www.trimble.com\n  - type: DeveloperPortal\n    url: https://www.trimble.com/en/developer/docs\n  - type: Documentation\n    url: https://developer.trimble.com/docs/mobile-manager/\n  - type: GettingStarted\n    url: https://developer.trimble.com/docs/mobile-manager/guides/integrate/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trimble-navigation/refs/heads/main/apis.yml
tags:
- GPS
- GNSS
- Positioning
- Navigation
- Surveying
- Geospatial
- Construction
url: https://raw.githubusercontent.com/api-evangelist/trimble-navigation/refs/heads/main/apis.yml
use_cases: []
---
