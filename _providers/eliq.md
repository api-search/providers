---
api_count: 4
apis:
- description: The Eliq Auth API authenticates client applications and issues access tokens used to call the Insights, Data Management, and Intelligence APIs. It supports the credential flows required for utility-si
  name: Eliq Auth API
  slug: auth
- description: The Eliq Data Management API ingests and manages customer, location, and meter data inside the Eliq system. Clients use it to provision users and locations, post energy consumption readings, attach me
  name: Eliq Data Management API
  slug: data-management
- description: The Eliq Insights API delivers analytics and presentation-ready data for end-user energy applications. It exposes consumption aggregates by day, week, month, and year, trends, cost, CO2 footprint, day
  name: Eliq Insights API
  slug: insights
- description: The Eliq Intelligence API provides customer-level analytics designed for utility service, operations, and growth teams. It supports customer segmentation, behavioral classification, and personalized r
  name: Eliq Intelligence API
  slug: intelligence
common:
- title: ''
  type: Website
  url: https://eliq.com
- title: ''
  type: DeveloperPortal
  url: https://developer.eliq.com
- title: ''
  type: Documentation
  url: https://developer.eliq.com/docs
- title: ''
  type: Documentation
  url: https://eliq.com/api/
created: '2025-05-02'
description: Eliq provides energy data and analytics APIs for utilities and energy app developers. The platform combines a decade of analytics and machine learning trained on millions of homes to deliver consumption insights, disaggregation, forecasting, peak detection, tariff comparison, and customer segmentation.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Eliq
skills: []
slug: eliq
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: eliq\nname: Eliq\ndescription: >-\n  Eliq provides energy data and analytics APIs for utilities and energy app\n  developers. The platform combines a decade of analytics and machine learning\n  trained on millions of homes to deliver consumption insights, disaggregation,\n  forecasting, peak detection, tariff comparison, and customer segmentation.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Energy\n  - Utilities\n  - Analytics\n  - Sustainability\ncreated: '2025-05-02'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/eliq/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: eliq:auth\n    name: Eliq Auth API\n    description: >-\n      The Eliq Auth API authenticates client applications and issues access\n      tokens used to call the Insights, Data Management, and Intelligence APIs.\n      It supports the credential flows\
  \ required for utility-side integrations.\n    humanURL: https://developer.eliq.com/api-reference\n    tags:\n      - Authentication\n      - Energy\n    properties:\n      - type: Documentation\n        url: https://developer.eliq.com/api-reference\n      - type: DeveloperPortal\n        url: https://developer.eliq.com\n  - aid: eliq:data-management\n    name: Eliq Data Management API\n    description: >-\n      The Eliq Data Management API ingests and manages customer, location, and\n      meter data inside the Eliq system. Clients use it to provision users and\n      locations, post energy consumption readings, attach metadata such as\n      tariffs and dwelling information, and keep the dataset that powers the\n      Insights API up to date.\n    humanURL: https://developer.eliq.com/doc/eliq-apis\n    tags:\n      - Data Management\n      - Energy\n      - Utilities\n    properties:\n      - type: Documentation\n        url: https://developer.eliq.com/doc/eliq-apis\n  - aid: eliq:insights\n\
  \    name: Eliq Insights API\n    description: >-\n      The Eliq Insights API delivers analytics and presentation-ready data for\n      end-user energy applications. It exposes consumption aggregates by day,\n      week, month, and year, trends, cost, CO2 footprint, day-ahead pricing,\n      weather, peak power, tariff comparisons, PV disaggregation, forecasting,\n      anomalies, and budget or goal tracking. Device-specific energy insights\n      use NILM disaggregation to attribute consumption to appliances.\n    humanURL: https://developer.eliq.com/doc/energy-insights-for-businesses\n    tags:\n      - Insights\n      - Analytics\n      - Energy\n      - Utilities\n      - Disaggregation\n    properties:\n      - type: Documentation\n        url: https://developer.eliq.com/doc/energy-insights-for-businesses\n      - type: Documentation\n        url: https://developer.eliq.com/doc/device-specific-energy-insights\n  - aid: eliq:intelligence\n    name: Eliq Intelligence API\n    description:\
  \ >-\n      The Eliq Intelligence API provides customer-level analytics designed for\n      utility service, operations, and growth teams. It supports customer\n      segmentation, behavioral classification, and personalized recommendations\n      derived from consumption history, weather, tariffs, and disaggregation\n      models. Access to the Intelligence API is granted on request.\n    humanURL: https://developer.eliq.com/api-reference\n    tags:\n      - Intelligence\n      - Segmentation\n      - Energy\n      - Utilities\n    properties:\n      - type: Documentation\n        url: https://developer.eliq.com/api-reference\ncommon:\n  - type: Website\n    url: https://eliq.com\n  - type: DeveloperPortal\n    url: https://developer.eliq.com\n  - type: Documentation\n    url: https://developer.eliq.com/docs\n  - type: Documentation\n    url: https://eliq.com/api/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/eliq/refs/heads/main/apis.yml
tags:
- Energy
- Utilities
- Analytics
- Sustainability
url: https://raw.githubusercontent.com/api-evangelist/eliq/refs/heads/main/apis.yml
use_cases: []
---
