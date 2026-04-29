---
api_count: 1
apis:
- description: The RISE API allows users to query Bureau of Reclamation water resource data programmatically, returning JSON objects. For Geospatial and File Upload datasets, only metadata can be queried. For time s
  name: Reclamation Information Sharing Environment (RISE) API
  slug: reclamation-information-sharing-environment-rise
common:
- title: ''
  type: Website
  url: https://www.usbr.gov
- title: ''
  type: Portal
  url: https://data.usbr.gov/
- title: ''
  type: Privacy Policy
  url: https://www.usbr.gov/privacy.html
- title: ''
  type: Data Portal
  url: https://catalog.data.gov/dataset?organization=usbr-gov
created: '2024-11-30'
description: Established in 1902, the Bureau of Reclamation is best known for the dams, powerplants, and canals it constructed in the 17 western states. These water projects led to homesteading and promoted the economic development of the West. Reclamation has constructed more than 600 dams and reservoirs including Hoover Dam on the Colorado River and Grand Coulee on the Columbia River.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Bureau of Reclamation
skills: []
slug: bureau-of-reclamation
solutions: []
source_filename: apis.yml
source_yaml: "aid: bureau-of-reclamation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bureau-of-reclamation/refs/heads/main/apis.yml\nname: Bureau of Reclamation\ntags:\n  - Energy\n  - Federal Government\n  - Infrastructure\n  - Water\n  - Hydrology\n  - Reservoirs\ntype: Index\nx-type: government\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-30'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  Established in 1902, the Bureau of Reclamation is best known for the dams,\n  powerplants, and canals it constructed in the 17 western states. These water\n  projects led to homesteading and promoted the economic development of the\n  West. Reclamation has constructed more than 600 dams and reservoirs including\n  Hoover Dam on the Colorado River and Grand Coulee on the Columbia River.\napis:\n  - aid: bureau-of-reclamation:reclamation-information-sharing-environment-rise\n    name: Reclamation\
  \ Information Sharing Environment (RISE) API\n    tags:\n      - Federal Government\n      - Water\n      - Hydrology\n      - Time Series\n    humanURL: https://data.usbr.gov/rise/api\n    baseURL: https://data.usbr.gov/rise/api/\n    properties:\n      - url: https://data.usbr.gov/rise/api\n        type: Documentation\n      - url: https://data.usbr.gov/\n        type: Portal\n      - url: https://catalog.data.gov/dataset?organization=usbr-gov\n        type: DataAPI\n    description: >-\n      The RISE API allows users to query Bureau of Reclamation water resource\n      data programmatically, returning JSON objects. For Geospatial and File\n      Upload datasets, only metadata can be queried. For time series datasets,\n      both metadata and data can be queried. Data includes hydrometric\n      measurements, reservoir levels, streamflow, and water quality.\n    features:\n      - Time Series Data\n      - Hydrometric Measurements\n      - Reservoir Level Data\n      - Streamflow Data\n\
  \      - Water Quality Data\n      - Geospatial Metadata\n      - JSON Format\n      - Paginated Results\n    useCases:\n      - Water resource planning\n      - Drought monitoring\n      - Hydroelectric generation analysis\n      - Environmental flow studies\n      - Water rights management\n      - Climate research\n    endpoints:\n      - path: /catalog-item\n        description: Query catalog items\n      - path: /catalog-record\n        description: Query catalog records\n      - path: /location\n        description: Query monitoring locations\n      - path: /parameter\n        description: Query measured parameters\n      - path: /result\n        description: Query time series results\n      - path: /reclamation-region\n        description: Query Reclamation regions\n      - path: /model-run\n        description: Query model run data\ncommon:\n  - type: Website\n    url: https://www.usbr.gov\n  - type: Portal\n    url: https://data.usbr.gov/\n  - type: Privacy Policy\n    url: https://www.usbr.gov/privacy.html\n\
  \  - type: Data Portal\n    url: https://catalog.data.gov/dataset?organization=usbr-gov\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bureau-of-reclamation/refs/heads/main/apis.yml
tags:
- Energy
- Federal Government
- Infrastructure
- Water
- Hydrology
- Reservoirs
url: https://raw.githubusercontent.com/api-evangelist/bureau-of-reclamation/refs/heads/main/apis.yml
use_cases: []
---
