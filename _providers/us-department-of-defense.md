---
api_count: 4
api_specs:
- filename: usace-cwms-data-api-openapi.yml
  format: yaml
  label: USACE Corps Water Management System Data API
  slug: cwms-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-department-of-defense/refs/heads/main/openapi/usace-cwms-data-api-openapi.yml
apis:
- description: The USACE Corps Water Management System Data API (CDA) is a REST service providing programmatic access to USACE water management data including time series measurements, monitoring locations, rating c
  name: USACE Corps Water Management System Data API
  slug: cwms-data-api
- description: The USACE Lock Performance Monitoring System (LPMS) API provides data on inland waterway lock operations across the US Army Corps of Engineers lock system. Endpoints return XML data for lock queue rep
  name: USACE Lock Performance Monitoring System API
  slug: lpms-api
- description: The Department of Defense Data Portal features APIs enabling access to DoD open data across military branches, agencies, and programs. The portal surfaces selected APIs from the DoD's data strategy in
  name: DoD Data Portal
  slug: defense-data-gov
- description: The Department of Defense Open Data Platform (data.mil) provides access to unclassified DoD datasets and data services supporting defense research, policy analysis, and public accountability.
  name: DoD Open Data Platform
  slug: dod-open-data
capabilities:
- description: Workflow capability for USACE water management operations including reservoir monitoring, flood control, navigation, and water quality. Combines CWMS time series data, location metadata, reservoir poo
  name: USACE Water Management
  slug: water-management
common: []
created: '2024-12-03'
description: The US Department of Defense is responsible for providing the military forces needed to deter war and protect the security of the United States. This includes overseeing the Army, Navy, Marine Corps, and Air Force, as well as coordinating with other defense agencies and organizations. The Department of Defense also plays a critical role in developing military strategies, acquiring and maintaining weapons and equipment, and ensuring the readiness and effectiveness of the armed forces. The DoD's data strategy initiatives have led to the publication of multiple public APIs including the USACE Corps Water Management System API, Lock Performance Monitoring System, and the DoD open data portal.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 22
  name: Us Department Of Defense Context
  property_count: 2
  slug: us-department-of-defense-context
layout: provider
modified: '2026-05-03'
name: US Department of Defense
rules:
- name: US Department of Defense API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 6
  slug: usace-cwms-data-api-rules
skills: []
slug: us-department-of-defense
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-department-of-defense\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-department-of-defense/refs/heads/main/apis.yml\napis:\n  - aid: us-department-of-defense:cwms-data-api\n    name: USACE Corps Water Management System Data API\n    tags:\n      - Water Management\n      - Hydrology\n      - Army Corps of Engineers\n      - Federal Government\n    humanURL: https://cwms-data.usace.army.mil/cwms-data/\n    properties:\n      - url: https://cwms-data.usace.army.mil/cwms-data/\n        type: Documentation\n      - url: https://cwms-data.usace.army.mil/cwms-data/swagger-ui.html\n        type: SwaggerUI\n      - url: https://cwms-data-api.readthedocs.io/latest/\n        type: Documentation\n      - url: https://github.com/USACE/cwms-data-api\n        type: GitHub\n      - url: https://raw.githubusercontent.com/api-evangelist/us-department-of-defense/refs/heads/main/openapi/usace-cwms-data-api-openapi.yml\n        type: OpenAPI\n    description: >-\n    \
  \  The USACE Corps Water Management System Data API (CDA) is a REST service\n      providing programmatic access to USACE water management data including\n      time series measurements, monitoring locations, rating curves, reservoir\n      levels, and operational data across Army Corps of Engineers projects.\n      Supports both public read access and authenticated write operations.\n\n  - aid: us-department-of-defense:lpms-api\n    name: USACE Lock Performance Monitoring System API\n    tags:\n      - Waterways\n      - Navigation\n      - Locks\n      - Federal Government\n    humanURL: https://corpslocks.usace.army.mil/lpwb/f\n    properties:\n      - url: https://corpslocks.usace.army.mil/lpwb/f\n        type: Documentation\n      - url: https://catalog.data.gov/dataset/corps-locks\n        type: DataCatalog\n    description: >-\n      The USACE Lock Performance Monitoring System (LPMS) API provides data\n      on inland waterway lock operations across the US Army Corps of Engineers\n\
  \      lock system. Endpoints return XML data for lock queue reports (past 24\n      hours), tonnage reports, and traffic reports (past 30 days). Tracks\n      vessel traffic through 192 commercially active locks on US inland\n      waterways.\n\n  - aid: us-department-of-defense:defense-data-gov\n    name: DoD Data Portal\n    tags:\n      - Open Data\n      - Defense\n      - Federal Government\n    humanURL: https://data.defense.gov/Featured-API/\n    properties:\n      - url: https://data.defense.gov/Featured-API/\n        type: Documentation\n      - url: https://data.defense.gov/\n        type: Portal\n    description: >-\n      The Department of Defense Data Portal features APIs enabling access to\n      DoD open data across military branches, agencies, and programs. The\n      portal surfaces selected APIs from the DoD's data strategy initiative\n      to make defense data more accessible through reusable APIs.\n\n  - aid: us-department-of-defense:dod-open-data\n    name: DoD Open\
  \ Data Platform\n    tags:\n      - Open Data\n      - Defense\n      - Datasets\n      - Federal Government\n    humanURL: https://www.data.mil/\n    properties:\n      - url: https://www.data.mil/\n        type: Portal\n    description: >-\n      The Department of Defense Open Data Platform (data.mil) provides\n      access to unclassified DoD datasets and data services supporting\n      defense research, policy analysis, and public accountability.\n\nname: US Department of Defense\ntags:\n  - Federal Government\n  - Defense\n  - Military\n  - Water Management\n  - Waterways\n  - Open Data\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  The US Department of Defense is responsible for providing the military forces\n  needed to deter war and protect the security of the United States. This\n  includes overseeing the Army, Navy, Marine\
  \ Corps, and Air Force, as well as\n  coordinating with other defense agencies and organizations. The Department of\n  Defense also plays a critical role in developing military strategies, acquiring\n  and maintaining weapons and equipment, and ensuring the readiness and\n  effectiveness of the armed forces. The DoD's data strategy initiatives have\n  led to the publication of multiple public APIs including the USACE Corps Water\n  Management System API, Lock Performance Monitoring System, and the DoD open\n  data portal.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-department-of-defense/refs/heads/main/apis.yml
tags:
- Federal Government
- Defense
- Military
- Water Management
- Waterways
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/us-department-of-defense/refs/heads/main/apis.yml
use_cases: []
---
