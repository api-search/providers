---
api_count: 5
apis:
- description: Web and mobile API powering the WEC Energy Group customer self-service portal. Enables customers to view account information, pay bills, manage alerts, view energy usage history, and report outages. A
  name: WEC Energy Group Customer Portal API
  slug: ''
- description: 'Green Button is a standardized API for accessing customer energy usage data. Based on the ESPI (Energy Services Provider Interface) standard, it allows customers to authorize third-party applications '
  name: Green Button Energy Usage Data API
  slug: ''
- description: Real-time electricity outage information for We Energies service territory in Wisconsin. Provides geographic outage data, estimated restoration times, and affected customer counts. Powers the public-f
  name: We Energies Outage Map API
  slug: ''
- description: Customer account and billing API for Peoples Gas, serving natural gas customers in the Chicago metropolitan area. Supports account management, bill payment, usage history, and service requests.
  name: Peoples Gas Customer Service API
  slug: ''
- description: 'Financial data and investor relations resources for WEC Energy Group (NYSE: WEC). Provides access to earnings releases, SEC filings, dividend information, stock price data, and annual reports.'
  name: WEC Energy Group Investor Relations API
  slug: ''
common:
- title: ''
  type: Website
  url: https://www.wecenergygroup.com
- title: ''
  type: Customer Portal
  url: https://www.we-energies.com/
- title: ''
  type: Peoples Gas Portal
  url: https://www.peoplesgas.com/
- title: ''
  type: Wisconsin Public Service Portal
  url: https://www.wisconsinpublicservice.com/
- title: ''
  type: Press Room
  url: https://www.wecenergygroup.com/newsroom/
- title: ''
  type: Investor Relations
  url: https://www.wecenergygroup.com/investor-relations/
- title: ''
  type: Careers
  url: https://careers.wecenergygroup.com/
- title: ''
  type: Sustainability
  url: https://www.wecenergygroup.com/sustainability/
- title: ''
  type: Terms of Service
  url: https://www.we-energies.com/help/legal/terms-of-use/
- title: ''
  type: Privacy Policy
  url: https://www.wecenergygroup.com/privacy-policy/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/wec-energy-group
- title: ''
  type: Twitter
  url: https://twitter.com/WECEnergyGroup
- title: ''
  type: Vocabulary
  url: vocabulary/wec-energy-vocabulary.yml
created: '2024'
description: 'WEC Energy Group (NYSE: WEC) is one of the nation''s premier energy companies, serving 4.4 million customers across Wisconsin, Illinois, Michigan, and Minnesota with electricity and natural gas service. The company operates through regional utilities including We Energies, Wisconsin Public Service, Peoples Gas, North Shore Gas, Minnesota Energy Resources, Michigan Gas Utilities, and Upper Michigan Energy Resources. WEC Energy Group offers customer-facing digital services including account management portals, mobile apps, and Green Button energy usage data access.'
features: []
image: https://www.wecenergygroup.com/images/wec-logo.png
integrations: []
jsonld:
- class_count: 0
  name: Wec Energy Context
  property_count: 23
  slug: wec-energy-context
layout: provider
modified: '2026-05-03'
name: WEC Energy Group
skills: []
slug: wec-energy
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wec-energy\nname: WEC Energy Group\ndescription: >-\n  WEC Energy Group (NYSE: WEC) is one of the nation's premier energy companies, serving\n  4.4 million customers across Wisconsin, Illinois, Michigan, and Minnesota with electricity\n  and natural gas service. The company operates through regional utilities including\n  We Energies, Wisconsin Public Service, Peoples Gas, North Shore Gas, Minnesota Energy\n  Resources, Michigan Gas Utilities, and Upper Michigan Energy Resources. WEC Energy Group\n  offers customer-facing digital services including account management portals, mobile apps,\n  and Green Button energy usage data access.\nimage: https://www.wecenergygroup.com/images/wec-logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/wec-energy/refs/heads/main/apis.yml\ncreated: '2024'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - name: WEC Energy Group Customer Portal API\n    description: >-\n      Web and mobile API powering the WEC Energy\
  \ Group customer self-service portal.\n      Enables customers to view account information, pay bills, manage alerts, view\n      energy usage history, and report outages. Accessible via the We Energies and\n      Wisconsin Public Service customer websites and mobile apps.\n    humanUrl: https://www.we-energies.com/\n    tags:\n      - Account Management\n      - Bill Payment\n      - Customer Portal\n      - Energy Usage\n      - Outage Reporting\n    properties:\n      - type: Customer Portal\n        url: https://www.we-energies.com/customer-service/account-management/\n      - type: Mobile App iOS\n        url: https://apps.apple.com/us/app/we-energies/id1475985561\n      - type: Mobile App Android\n        url: https://play.google.com/store/apps/details?id=com.wecenergygroup.we\n\n  - name: Green Button Energy Usage Data API\n    description: >-\n      Green Button is a standardized API for accessing customer energy usage data.\n      Based on the ESPI (Energy Services Provider Interface)\
  \ standard, it allows\n      customers to authorize third-party applications to access their electricity\n      and gas consumption data. WEC Energy Group utilities support the Green Button\n      Connect My Data standard for automated data sharing.\n    humanUrl: https://www.energy.gov/data/green-button\n    tags:\n      - Energy Data\n      - Green Button\n      - ESPI\n      - OAuth2\n      - Smart Meter\n      - Usage Data\n    properties:\n      - type: Documentation\n        url: https://dev.greenbuttonalliance.org/\n      - type: Standard\n        url: https://www.energy.gov/data/green-button\n      - type: Open Energy Info\n        url: https://openei.org/wiki/Green_Button\n\n  - name: We Energies Outage Map API\n    description: >-\n      Real-time electricity outage information for We Energies service territory in\n      Wisconsin. Provides geographic outage data, estimated restoration times, and\n      affected customer counts. Powers the public-facing outage map.\n    humanUrl:\
  \ https://www.we-energies.com/outages-safety/outages/outage-map/\n    tags:\n      - Electricity\n      - GIS\n      - Outage Map\n      - Real-Time\n      - Wisconsin\n    properties:\n      - type: Outage Map\n        url: https://www.we-energies.com/outages-safety/outages/outage-map/\n      - type: Outage Reporting\n        url: https://www.we-energies.com/outages-safety/outages/\n\n  - name: Peoples Gas Customer Service API\n    description: >-\n      Customer account and billing API for Peoples Gas, serving natural gas customers\n      in the Chicago metropolitan area. Supports account management, bill payment,\n      usage history, and service requests.\n    humanUrl: https://www.peoplesgas.com/\n    tags:\n      - Account Management\n      - Bill Payment\n      - Chicago\n      - Illinois\n      - Natural Gas\n    properties:\n      - type: Customer Portal\n        url: https://www.peoplesgas.com/my-account/\n      - type: Website\n        url: https://www.peoplesgas.com/\n\n  -\
  \ name: WEC Energy Group Investor Relations API\n    description: >-\n      Financial data and investor relations resources for WEC Energy Group (NYSE: WEC).\n      Provides access to earnings releases, SEC filings, dividend information,\n      stock price data, and annual reports.\n    humanUrl: https://www.wecenergygroup.com/investor-relations/\n    tags:\n      - Financial Data\n      - Investor Relations\n      - NYSE\n      - SEC Filings\n      - Stock Data\n    properties:\n      - type: Investor Relations\n        url: https://www.wecenergygroup.com/investor-relations/\n      - type: SEC Filings\n        url: https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0000783325\n\ncommon:\n  - type: Website\n    url: https://www.wecenergygroup.com\n  - type: Customer Portal\n    url: https://www.we-energies.com/\n  - type: Peoples Gas Portal\n    url: https://www.peoplesgas.com/\n  - type: Wisconsin Public Service Portal\n    url: https://www.wisconsinpublicservice.com/\n  -\
  \ type: Press Room\n    url: https://www.wecenergygroup.com/newsroom/\n  - type: Investor Relations\n    url: https://www.wecenergygroup.com/investor-relations/\n  - type: Careers\n    url: https://careers.wecenergygroup.com/\n  - type: Sustainability\n    url: https://www.wecenergygroup.com/sustainability/\n  - type: Terms of Service\n    url: https://www.we-energies.com/help/legal/terms-of-use/\n  - type: Privacy Policy\n    url: https://www.wecenergygroup.com/privacy-policy/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/wec-energy-group\n  - type: Twitter\n    url: https://twitter.com/WECEnergyGroup\n  - type: Vocabulary\n    url: vocabulary/wec-energy-vocabulary.yml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\ntags:\n  - Energy\n  - Electric Utility\n  - Fortune 500\n  - Green Button\n  - Illinois\n  - Michigan\n  - Minnesota\n  - Natural Gas\n  - NYSE\n  - Utility\n  - Wisconsin\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wec-energy/refs/heads/main/apis.yml
tags:
- Energy
- Electric Utility
- Fortune 500
- Green Button
- Illinois
- Michigan
- Minnesota
- Natural Gas
- NYSE
- Utility
- Wisconsin
url: https://raw.githubusercontent.com/api-evangelist/wec-energy/refs/heads/main/apis.yml
use_cases: []
---
