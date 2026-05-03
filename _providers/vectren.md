---
api_count: 3
apis:
- description: Web portal for builders and developers in Vectren/CenterPoint Energy service territories in Indiana and Ohio. Provides self-service tools for ordering new gas and electric service, checking order stat
  name: CenterPoint Energy Builder Portal
  slug: ''
- description: Customer self-service portal providing access to account management, bill pay, usage history, and service requests for residential and business customers in the legacy Vectren service territories of I
  name: CenterPoint Energy Customer Account API
  slug: ''
- description: Energy data portal for comparing current and historical energy usage, integrating with ENERGY STAR Portfolio Manager for benchmarking, and accessing customizable energy consumption analytics. Availabl
  name: CenterPoint Energy Data Portal
  slug: ''
common:
- title: ''
  type: Website
  url: https://www.centerpointenergy.com/en-us/corporate/about-us/vectren-merger
- title: ''
  type: Portal
  url: https://vectren.com
- title: ''
  type: BuilderPortal
  url: https://builder.vectren.com/web/builder/login/login.jsp
- title: ''
  type: Login
  url: https://vectren.com/login
- title: ''
  type: MergerInfo
  url: https://investors.centerpointenergy.com/news-releases/news-release-details/centerpoint-energy-and-vectren-complete-merger
created: '2026-03-24'
description: Vectren Corporation was a Fortune 1000 energy holding company headquartered in Evansville (Newburgh), Indiana providing regulated natural gas and electric distribution services to customers in Indiana and Ohio, along with non-regulated infrastructure services and energy efficiency programs. Vectren merged with CenterPoint Energy on February 1, 2019 in a $6 billion transaction, becoming part of the combined company which serves over 7 million metered customers across Arkansas, Indiana, Louisiana, Minnesota, Mississippi, Ohio, Oklahoma, and Texas. Vectren customer-facing portals continue to operate at vectren.com redirecting to CenterPoint Energy services.
features:
- description: Regulated natural gas distribution serving residential and business customers in Indiana and Ohio.
  name: Natural Gas Distribution
- description: Regulated electric transmission and distribution in southwestern Indiana.
  name: Electric Distribution
- description: Self-service portal for new service orders, meter requests, and construction project management.
  name: Builder and Developer Services
- description: Programs and incentives for energy efficiency improvements for residential and commercial customers.
  name: Energy Efficiency Programs
- description: Historical energy usage data and ENERGY STAR Portfolio Manager integration for benchmarking.
  name: Energy Data Portal
- description: Infrastructure services and energy efficiency solutions through Vectren's non-regulated subsidiary.
  name: Non-Regulated Services
image: ''
integrations:
- description: Automated data connection for benchmarking building energy performance.
  name: ENERGY STAR Portfolio Manager
- description: Vectren merged with CenterPoint Energy on February 1, 2019, becoming part of the combined utility.
  name: CenterPoint Energy
layout: provider
modified: '2026-05-03'
name: Vectren (CenterPoint Energy)
skills: []
slug: vectren
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vectren\nname: Vectren (CenterPoint Energy)\ndescription: >-\n  Vectren Corporation was a Fortune 1000 energy holding company headquartered in\n  Evansville (Newburgh), Indiana providing regulated natural gas and electric\n  distribution services to customers in Indiana and Ohio, along with non-regulated\n  infrastructure services and energy efficiency programs. Vectren merged with\n  CenterPoint Energy on February 1, 2019 in a $6 billion transaction, becoming\n  part of the combined company which serves over 7 million metered customers across\n  Arkansas, Indiana, Louisiana, Minnesota, Mississippi, Ohio, Oklahoma, and Texas.\n  Vectren customer-facing portals continue to operate at vectren.com redirecting to\n  CenterPoint Energy services.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vectren/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-05-03'\ntags:\n  - Electric Utility\n  - Energy\n  - Natural Gas\n  - Regulated Utility\n  - Utility\n\
  apis:\n  - name: CenterPoint Energy Builder Portal\n    description: >-\n      Web portal for builders and developers in Vectren/CenterPoint Energy service\n      territories in Indiana and Ohio. Provides self-service tools for ordering new\n      gas and electric service, checking order status, requesting meters, and\n      managing construction projects. Accessible at builder.vectren.com for legacy\n      Vectren territory customers.\n    humanURL: https://builder.vectren.com/web/builder/login/login.jsp\n    tags:\n      - Builder Services\n      - Construction\n      - Service Orders\n    properties:\n      - type: Documentation\n        url: https://builder.vectren.com/site-guide\n  - name: CenterPoint Energy Customer Account API\n    description: >-\n      Customer self-service portal providing access to account management, bill pay,\n      usage history, and service requests for residential and business customers in\n      the legacy Vectren service territories of Indiana and Ohio.\
  \ The portal supports\n      energy usage tracking, benchmarking with ENERGY STAR Portfolio Manager, and\n      automated alerts for usage anomalies.\n    humanURL: https://midwest.centerpointenergy.com/web/builder/login/login.jsp\n    tags:\n      - Account Management\n      - Bill Pay\n      - Customer Portal\n      - Energy Usage\n    properties:\n      - type: Documentation\n        url: https://energydataportal.centerpointenergy.com/\n  - name: CenterPoint Energy Data Portal\n    description: >-\n      Energy data portal for comparing current and historical energy usage,\n      integrating with ENERGY STAR Portfolio Manager for benchmarking, and\n      accessing customizable energy consumption analytics. Available to residential\n      and business customers in legacy Vectren service territories.\n    humanURL: https://energydataportal.centerpointenergy.com/\n    tags:\n      - Analytics\n      - Data\n      - Energy Efficiency\n      - Energy Usage\n    properties:\n      - type:\
  \ Documentation\n        url: https://energydataportal.centerpointenergy.com/\ncommon:\n  - type: Website\n    url: https://www.centerpointenergy.com/en-us/corporate/about-us/vectren-merger\n  - type: Portal\n    url: https://vectren.com\n  - type: BuilderPortal\n    url: https://builder.vectren.com/web/builder/login/login.jsp\n  - type: Login\n    url: https://vectren.com/login\n  - type: MergerInfo\n    url: https://investors.centerpointenergy.com/news-releases/news-release-details/centerpoint-energy-and-vectren-complete-merger\n  - type: Features\n    data:\n      - name: Natural Gas Distribution\n        description: Regulated natural gas distribution serving residential and business customers in Indiana and Ohio.\n      - name: Electric Distribution\n        description: Regulated electric transmission and distribution in southwestern Indiana.\n      - name: Builder and Developer Services\n        description: Self-service portal for new service orders, meter requests, and construction\
  \ project management.\n      - name: Energy Efficiency Programs\n        description: Programs and incentives for energy efficiency improvements for residential and commercial customers.\n      - name: Energy Data Portal\n        description: Historical energy usage data and ENERGY STAR Portfolio Manager integration for benchmarking.\n      - name: Non-Regulated Services\n        description: Infrastructure services and energy efficiency solutions through Vectren's non-regulated subsidiary.\n  - type: UseCases\n    data:\n      - name: New Construction Service\n        description: Builders and developers order new gas and electric service connections for residential and commercial construction.\n      - name: Account Self-Service\n        description: Customers manage accounts, pay bills, track usage, and request service changes online.\n      - name: Energy Benchmarking\n        description: Commercial building managers benchmark energy performance against ENERGY STAR standards.\n  \
  \    - name: Usage Monitoring\n        description: Monitor energy consumption trends to identify efficiency opportunities and anomalies.\n  - type: Integrations\n    data:\n      - name: ENERGY STAR Portfolio Manager\n        description: Automated data connection for benchmarking building energy performance.\n      - name: CenterPoint Energy\n        description: Vectren merged with CenterPoint Energy on February 1, 2019, becoming part of the combined utility.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vectren/refs/heads/main/apis.yml
tags:
- Electric Utility
- Energy
- Natural Gas
- Regulated Utility
- Utility
url: https://raw.githubusercontent.com/api-evangelist/vectren/refs/heads/main/apis.yml
use_cases:
- description: Builders and developers order new gas and electric service connections for residential and commercial construction.
  name: New Construction Service
- description: Customers manage accounts, pay bills, track usage, and request service changes online.
  name: Account Self-Service
- description: Commercial building managers benchmark energy performance against ENERGY STAR standards.
  name: Energy Benchmarking
- description: Monitor energy consumption trends to identify efficiency opportunities and anomalies.
  name: Usage Monitoring
---
