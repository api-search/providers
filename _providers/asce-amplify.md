---
api_count: 1
apis:
- description: The ASCE Hazard Tool API provides a simple interface to query locations in the United States for environmental hazard data by geographic location. It provides site-specific hazard values used in struc
  name: ASCE Hazard Tool API
  slug: hazard-tool-api
common:
- title: ASCE Amplify Platform
  type: Portal
  url: https://amplify.asce.org/
- title: ASCE Website
  type: Portal
  url: https://www.asce.org/
created: '2025-02-17'
description: ASCE Amplify is a platform created by the American Society of Civil Engineers (ASCE) that provides civil engineering data and advocacy tools. The platform includes the ASCE Hazard Tool API, which provides a simple interface to query locations in the United States for environmental hazard data by geographic location. The Hazard Tool API covers seismic, wind, snow, ice, flood, and other environmental hazard loads used in structural design per ASCE standards. ASCE Amplify also supports advocacy, connecting civil engineers with elected officials to advocate for infrastructure investment and sustainable practices.
features:
- description: Query any US location by latitude and longitude or address to retrieve site-specific environmental hazard values for structural design, including ASCE 7 seismic, wind, snow, and ice parameters.
  name: Geographic Hazard Lookup
- description: Retrieve seismic design parameters including Ss, S1, SMS, SM1, SDS, SD1, and spectral acceleration values per ASCE 7 for any US location.
  name: ASCE 7 Seismic Parameters
- description: Access design wind speed values for various risk categories and exposure categories per ASCE 7 for structural wind load calculations.
  name: Wind Speed Data
- description: Retrieve ground snow load values and ice storm data for design of roof structures and overhead transmission lines per ASCE 7.
  name: Snow and Ice Load Data
- description: Tools for ASCE members to contact elected officials and advocate for infrastructure funding, engineering standards, and professional issues.
  name: Civil Engineer Advocacy
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: API values directly correspond to ASCE 7 Minimum Design Loads for Buildings and Other Structures, the primary reference standard for US structural engineering.
  name: ASCE 7 Standards
- description: Hazard parameters from the API align with International Building Code requirements that reference ASCE 7 for environmental load design values.
  name: IBC Building Codes
layout: provider
modified: '2026-04-19'
name: ASCE Amplify
skills: []
slug: asce-amplify
solutions: []
source_yaml: "aid: asce-amplify\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/asce-amplify/refs/heads/main/apis.yml\nname: ASCE Amplify\ntags:\n  - Civil Engineering\n  - Hazard Data\n  - Engineering Standards\n  - Infrastructure\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-17'\nmodified: '2026-04-19'\ndescription: >-\n  ASCE Amplify is a platform created by the American Society of Civil Engineers\n  (ASCE) that provides civil engineering data and advocacy tools. The platform\n  includes the ASCE Hazard Tool API, which provides a simple interface to query\n  locations in the United States for environmental hazard data by geographic\n  location. The Hazard Tool API covers seismic, wind, snow, ice, flood, and\n  other environmental hazard loads used in structural design per ASCE standards.\n  ASCE Amplify also supports advocacy, connecting civil engineers with elected\n  officials to advocate\
  \ for infrastructure investment and sustainable practices.\napis:\n  - aid: asce-amplify:hazard-tool-api\n    name: ASCE Hazard Tool API\n    description: >-\n      The ASCE Hazard Tool API provides a simple interface to query locations\n      in the United States for environmental hazard data by geographic location.\n      It provides site-specific hazard values used in structural engineering\n      design including seismic ground motion parameters, wind speeds, snow loads,\n      ice loads, and flood data in accordance with ASCE 7 and related standards.\n      Access requires an ASCE membership or license.\n    humanURL: https://amplify.asce.org/api\n    baseURL: https://amplify.asce.org/api\n    tags:\n      - Civil Engineering\n      - Hazard Data\n      - Seismic\n      - Wind\n      - Snow\n      - Structural Engineering\n    properties:\n      - type: Documentation\n        url: https://amplify.asce.org/api\n      - type: Authentication\n        url: https://amplify.asce.org/api\n\
  common:\n  - type: Portal\n    url: https://amplify.asce.org/\n    title: ASCE Amplify Platform\n  - type: Portal\n    url: https://www.asce.org/\n    title: ASCE Website\n  - type: Features\n    data:\n      - name: Geographic Hazard Lookup\n        description: >-\n          Query any US location by latitude and longitude or address to retrieve\n          site-specific environmental hazard values for structural design,\n          including ASCE 7 seismic, wind, snow, and ice parameters.\n      - name: ASCE 7 Seismic Parameters\n        description: >-\n          Retrieve seismic design parameters including Ss, S1, SMS, SM1, SDS,\n          SD1, and spectral acceleration values per ASCE 7 for any US location.\n      - name: Wind Speed Data\n        description: >-\n          Access design wind speed values for various risk categories and\n          exposure categories per ASCE 7 for structural wind load calculations.\n      - name: Snow and Ice Load Data\n        description: >-\n   \
  \       Retrieve ground snow load values and ice storm data for design of\n          roof structures and overhead transmission lines per ASCE 7.\n      - name: Civil Engineer Advocacy\n        description: >-\n          Tools for ASCE members to contact elected officials and advocate for\n          infrastructure funding, engineering standards, and professional issues.\n  - type: UseCases\n    data:\n      - name: Structural Design\n        description: >-\n          Structural engineers use the ASCE Hazard Tool API to obtain site-specific\n          hazard parameters for building and infrastructure design in compliance\n          with ASCE 7 and building codes.\n      - name: Site Assessment\n        description: >-\n          Civil engineers perform preliminary site assessments for new construction\n          projects by querying multiple locations for hazard comparisons.\n      - name: Software Integration\n        description: >-\n          Structural engineering software vendors integrate\
  \ the ASCE Hazard Tool\n          API to automatically populate design parameters based on project location.\n  - type: Integrations\n    data:\n      - name: ASCE 7 Standards\n        description: >-\n          API values directly correspond to ASCE 7 Minimum Design Loads for\n          Buildings and Other Structures, the primary reference standard for US\n          structural engineering.\n      - name: IBC Building Codes\n        description: >-\n          Hazard parameters from the API align with International Building Code\n          requirements that reference ASCE 7 for environmental load design values.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/asce-amplify/refs/heads/main/apis.yml
tags:
- Civil Engineering
- Hazard Data
- Engineering Standards
- Infrastructure
url: https://raw.githubusercontent.com/api-evangelist/asce-amplify/refs/heads/main/apis.yml
use_cases:
- description: Structural engineers use the ASCE Hazard Tool API to obtain site-specific hazard parameters for building and infrastructure design in compliance with ASCE 7 and building codes.
  name: Structural Design
- description: Civil engineers perform preliminary site assessments for new construction projects by querying multiple locations for hazard comparisons.
  name: Site Assessment
- description: Structural engineering software vendors integrate the ASCE Hazard Tool API to automatically populate design parameters based on project location.
  name: Software Integration
---
