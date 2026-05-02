---
api_count: 3
apis:
- description: 'The Online Detainee Locator System is a public-facing search tool that allows the public to locate detainees currently in ICE custody by A-Number and country of birth, or by biographical information. '
  name: ICE Online Detainee Locator System (ODLS)
  slug: ice-online-detainee-locator-system
- description: Enforcement and Removal Operations (ERO) publishes custody arrest, enforcement, and removal statistics in machine-readable formats (CSV/Excel) at regular reporting cadence. These datasets are publishe
  name: ICE ERO Custody and Enforcement Statistics
  slug: ice-ero-statistics
- description: ICE's Freedom of Information Act (FOIA) program provides a public reading room and electronic FOIA library with frequently requested records, policy directives, and data releases. Records are released
  name: ICE FOIA Library
  slug: ice-foia
common:
- title: ''
  type: Website
  url: https://www.ice.gov/
- title: ''
  type: News
  url: https://www.ice.gov/news/all
- title: ''
  type: Statistics
  url: https://www.ice.gov/statistics
- title: ''
  type: FOIA
  url: https://www.ice.gov/foia
- title: ''
  type: Detainee Locator
  url: https://locator.ice.gov/
- title: ''
  type: Contact
  url: https://www.ice.gov/contact
- title: ''
  type: Privacy Policy
  url: https://www.ice.gov/about/privacy
- title: ''
  type: Open Data
  url: https://www.dhs.gov/data
created: '2025-03-01'
description: U.S. Immigration and Customs Enforcement (ICE) is a federal law enforcement agency under the U.S. Department of Homeland Security responsible for enforcing federal immigration and customs laws. ICE does not publish a general-purpose developer API portal, but provides public-facing systems, open data, statistics, and FOIA resources used by researchers, attorneys, journalists, and the public.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: U.S. Immigration and Customs Enforcement (ICE)
skills: []
slug: ice
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ice\nname: U.S. Immigration and Customs Enforcement (ICE)\ndescription: >-\n  U.S. Immigration and Customs Enforcement (ICE) is a federal law enforcement\n  agency under the U.S. Department of Homeland Security responsible for\n  enforcing federal immigration and customs laws. ICE does not publish a\n  general-purpose developer API portal, but provides public-facing systems,\n  open data, statistics, and FOIA resources used by researchers, attorneys,\n  journalists, and the public.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Customs Enforcement\n  - DHS\n  - Federal Government\n  - Government\n  - Immigration\n  - Law Enforcement\n  - Open Data\nurl: https://raw.githubusercontent.com/api-evangelist/ice/refs/heads/main/apis.yml\ncreated: '2025-03-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: ice:ice-online-detainee-locator-system\n    name: ICE Online Detainee Locator System (ODLS)\n\
  \    description: >-\n      The Online Detainee Locator System is a public-facing search tool that\n      allows the public to locate detainees currently in ICE custody by\n      A-Number and country of birth, or by biographical information. The\n      system is provided as a web search interface; no public developer API\n      is published.\n    humanURL: https://locator.ice.gov/\n    tags:\n      - Custody\n      - Detainee Locator\n      - Search\n    properties:\n      - type: Website\n        url: https://locator.ice.gov/\n      - type: Documentation\n        url: https://www.ice.gov/detain/detention-management\n  - aid: ice:ice-ero-statistics\n    name: ICE ERO Custody and Enforcement Statistics\n    description: >-\n      Enforcement and Removal Operations (ERO) publishes custody arrest,\n      enforcement, and removal statistics in machine-readable formats\n      (CSV/Excel) at regular reporting cadence. These datasets are published\n      as downloadable files rather than through\
  \ a versioned developer API.\n    humanURL: https://www.ice.gov/statistics\n    tags:\n      - Enforcement\n      - Removals\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://www.ice.gov/statistics\n      - type: Reports\n        url: https://www.ice.gov/spotlight/statistics\n  - aid: ice:ice-foia\n    name: ICE FOIA Library\n    description: >-\n      ICE's Freedom of Information Act (FOIA) program provides a public\n      reading room and electronic FOIA library with frequently requested\n      records, policy directives, and data releases. Records are released\n      as documents and bulk data files rather than through a programmatic\n      API.\n    humanURL: https://www.ice.gov/foia\n    tags:\n      - FOIA\n      - Public Records\n      - Transparency\n    properties:\n      - type: Documentation\n        url: https://www.ice.gov/foia\n      - type: Library\n        url: https://www.ice.gov/foia/library\n      - type: Submit Request\n       \
  \ url: https://www.ice.gov/foia/submit-request\ncommon:\n  - type: Website\n    url: https://www.ice.gov/\n  - type: News\n    url: https://www.ice.gov/news/all\n  - type: Statistics\n    url: https://www.ice.gov/statistics\n  - type: FOIA\n    url: https://www.ice.gov/foia\n  - type: Detainee Locator\n    url: https://locator.ice.gov/\n  - type: Contact\n    url: https://www.ice.gov/contact\n  - type: Privacy Policy\n    url: https://www.ice.gov/about/privacy\n  - type: Open Data\n    url: https://www.dhs.gov/data\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ice/refs/heads/main/apis.yml
tags:
- Customs Enforcement
- DHS
- Federal Government
- Government
- Immigration
- Law Enforcement
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/ice/refs/heads/main/apis.yml
use_cases: []
---
