---
api_count: 2
apis:
- description: The Ameren Illinois Share My Usage API implements the Green Button Connect My Data program, providing authorized third parties access to up to 24 months of historical electric energy usage data for re
  name: Ameren Share My Usage API
  slug: share-my-usage-api
- description: 'The Ameren Renewables Portal enables generation owners to manage community solar and collectively owned generation facilities, track subscriber accounts, and manage billing usage credits in Illinois. '
  name: Ameren Renewables Portal API
  slug: renewables-portal-api
common:
- title: ''
  type: Website
  url: https://www.ameren.com/
- title: ''
  type: Portal
  url: https://www.ameren.com/partners/account-and-data/share-my-usage
created: '2026-03-23'
description: Ameren Corporation is a regulated electric and natural gas utility serving customers in Missouri and Illinois. The company provides reliable energy delivery, smart grid infrastructure, and renewable energy programs. Ameren Illinois implements the Green Button Connect My Data program (Share My Usage) based on the ESPI standard, enabling authorized third parties to access customer energy usage data. Ameren also operates a Renewables Portal for community solar generation owners and participates in grid modernization initiatives.
features:
- description: Standard-based program (ESPI/NAESB) enabling authorized third parties to access customer electric energy usage data with OAuth customer authorization for energy analysis, billing, and research.
  name: Green Button Connect My Data
- description: Advanced smart meter deployment enabling two-way communication, real-time usage monitoring, and automated data collection for Illinois and Missouri service territories.
  name: Smart Meter Infrastructure
- description: Online portal for community solar and generation owners to manage subscriber accounts and billing usage credits in Illinois.
  name: Community Solar Renewables Portal
- description: Advanced outage detection, automated notification, and faster power restoration capabilities through smart grid infrastructure.
  name: Outage Management and Restoration
- description: Rebates and incentive programs for residential and business customers to reduce energy consumption and improve efficiency.
  name: Energy Efficiency Programs
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Ameren Illinois participates in the national Green Button initiative providing standardized energy data access across utilities.
  name: Green Button Alliance
- description: Aclara serves as Ameren Illinois's authorized data custodian for the Share My Usage Green Button program.
  name: Aclara
- description: Energy Services Provider Interface standard from NAESB for energy usage data exchange in XML format via authenticated API.
  name: ESPI Standard
layout: provider
modified: '2026-04-19'
name: Ameren
skills: []
slug: ameren
solutions: []
source_yaml: "aid: ameren\nname: Ameren\ndescription: >-\n  Ameren Corporation is a regulated electric and natural gas utility serving\n  customers in Missouri and Illinois. The company provides reliable energy\n  delivery, smart grid infrastructure, and renewable energy programs. Ameren\n  Illinois implements the Green Button Connect My Data program (Share My Usage)\n  based on the ESPI standard, enabling authorized third parties to access\n  customer energy usage data. Ameren also operates a Renewables Portal for\n  community solar generation owners and participates in grid modernization\n  initiatives.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Utility\n  - Energy\n  - Electric\n  - Natural Gas\n  - Smart Grid\n  - Green Button\n  - Renewable Energy\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ameren/refs/heads/main/apis.yml\ncreated: '2026-03-23'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n\
  \  - aid: ameren:share-my-usage-api\n    name: Ameren Share My Usage API\n    description: >-\n      The Ameren Illinois Share My Usage API implements the Green Button Connect\n      My Data program, providing authorized third parties access to up to 24\n      months of historical electric energy usage data for residential and small\n      commercial customers via the ESPI (Energy Services Provider Interface)\n      standard. Authentication uses OAuth with customer authorization via\n      Ameren Illinois online accounts. Operated by data custodian Aclara.\n    humanURL: https://www.ameren.com/partners/account-and-data/share-my-usage\n    baseURL: https://api.ameren.com\n    tags:\n      - Green Button\n      - Energy Data\n      - ESPI\n      - Smart Meter\n      - Data Sharing\n    properties:\n      - type: Documentation\n        url: https://www.ameren.com/partners/account-and-data/share-my-usage\n      - type: Authentication\n        url: https://www.ameren.com/partners/account-and-data/share-my-usage\n\
  \n  - aid: ameren:renewables-portal-api\n    name: Ameren Renewables Portal API\n    description: >-\n      The Ameren Renewables Portal enables generation owners to manage\n      community solar and collectively owned generation facilities, track\n      subscriber accounts, and manage billing usage credits in Illinois.\n      Supports community renewable energy including solar, wind, hydro-electric,\n      fuel cells, and agricultural energy sources.\n    humanURL: https://www.ameren.com/service/renewables/developers/renewables-portal\n    baseURL: https://anm.ameren.com\n    tags:\n      - Renewable Energy\n      - Community Solar\n      - Generation Management\n      - Illinois\n    properties:\n      - type: Documentation\n        url: https://www.ameren.com/service/renewables/developers/renewables-portal\n      - type: Portal\n        url: https://anm.ameren.com/illinois/registration\n\ncommon:\n  - type: Website\n    url: https://www.ameren.com/\n  - type: Portal\n    url: https://www.ameren.com/partners/account-and-data/share-my-usage\n\
  \  - type: Features\n    data:\n      - name: Green Button Connect My Data\n        description: >-\n          Standard-based program (ESPI/NAESB) enabling authorized third parties\n          to access customer electric energy usage data with OAuth customer\n          authorization for energy analysis, billing, and research.\n      - name: Smart Meter Infrastructure\n        description: >-\n          Advanced smart meter deployment enabling two-way communication,\n          real-time usage monitoring, and automated data collection for\n          Illinois and Missouri service territories.\n      - name: Community Solar Renewables Portal\n        description: >-\n          Online portal for community solar and generation owners to manage\n          subscriber accounts and billing usage credits in Illinois.\n      - name: Outage Management and Restoration\n        description: >-\n          Advanced outage detection, automated notification, and faster power\n          restoration capabilities\
  \ through smart grid infrastructure.\n      - name: Energy Efficiency Programs\n        description: >-\n          Rebates and incentive programs for residential and business customers\n          to reduce energy consumption and improve efficiency.\n  - type: UseCases\n    data:\n      - name: Energy Usage Data Analysis\n        description: >-\n          Authorized third parties access up to 24 months of customer energy\n          usage data for energy efficiency analysis, billing comparisons, and\n          academic research.\n      - name: Community Solar Management\n        description: >-\n          Generation owners manage community solar subscriber accounts and\n          billing credits through the Renewables Portal.\n      - name: Smart Home Integration\n        description: >-\n          Third-party apps and devices integrate with Ameren usage data via\n          Green Button to provide energy management and automation services.\n      - name: Retail Electric Supply Comparison\n\
  \        description: >-\n          Retail electric suppliers and comparison platforms access usage data\n          to provide customers with competitive supply options.\n  - type: Integrations\n    data:\n      - name: Green Button Alliance\n        description: >-\n          Ameren Illinois participates in the national Green Button initiative\n          providing standardized energy data access across utilities.\n      - name: Aclara\n        description: >-\n          Aclara serves as Ameren Illinois's authorized data custodian for the\n          Share My Usage Green Button program.\n      - name: ESPI Standard\n        description: >-\n          Energy Services Provider Interface standard from NAESB for energy\n          usage data exchange in XML format via authenticated API.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ameren/refs/heads/main/apis.yml
tags:
- Utility
- Energy
- Electric
- Natural Gas
- Smart Grid
- Green Button
- Renewable Energy
url: https://raw.githubusercontent.com/api-evangelist/ameren/refs/heads/main/apis.yml
use_cases:
- description: Authorized third parties access up to 24 months of customer energy usage data for energy efficiency analysis, billing comparisons, and academic research.
  name: Energy Usage Data Analysis
- description: Generation owners manage community solar subscriber accounts and billing credits through the Renewables Portal.
  name: Community Solar Management
- description: Third-party apps and devices integrate with Ameren usage data via Green Button to provide energy management and automation services.
  name: Smart Home Integration
- description: Retail electric suppliers and comparison platforms access usage data to provide customers with competitive supply options.
  name: Retail Electric Supply Comparison
---
