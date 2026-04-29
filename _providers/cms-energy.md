---
api_count: 1
apis:
- description: The Consumers Energy Green Button Connect My Data API exposes customer-authorized electric and natural-gas usage data to registered third parties using the NAESB ESPI / Green Button standard. Authoriz
  name: Consumers Energy Green Button Connect My Data API
  slug: consumers-green-button-api
common:
- title: ''
  type: Website
  url: https://www.cmsenergy.com
- title: ''
  type: Website
  url: https://www.consumersenergy.com
- title: ''
  type: Documentation
  url: https://utilityapi.com/docs/utilities/consumersenergy
- title: ''
  type: About
  url: https://www.cmsenergy.com/about-cms-energy/consumers-energy/
- title: ''
  type: Support
  url: https://www.cmsenergy.com/contact-us/default.aspx
- title: ''
  type: PrivacyPolicy
  url: https://www.cmsenergy.com/privacy-statement/default.aspx
- title: ''
  type: X
  url: https://twitter.com/CMSEnergy
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/cms-energy/
created: '2026-03-21'
description: CMS Energy is an energy holding company whose primary subsidiary is Consumers Energy, an electric and natural gas utility serving customers in Michigan. Consumers Energy participates in the Green Button Connect My Data (GBCMD) program, exposing customer-authorized energy usage data to third parties via OAuth 2.0 - typically brokered through UtilityAPI - for use in energy management, demand response, EV charging, solar, and sustainability applications.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: CMS Energy
skills: []
slug: cms-energy
solutions: []
source_filename: apis.yml
source_yaml: "aid: cms-energy\nurl: https://raw.githubusercontent.com/api-evangelist/cms-energy/refs/heads/main/apis.yml\nname: CMS Energy\nx-type: company\ntags:\n  - Electric\n  - Energy\n  - Green Button\n  - Michigan\n  - Natural Gas\n  - Utility\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-21'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\ndescription: >-\n  CMS Energy is an energy holding company whose primary subsidiary is Consumers\n  Energy, an electric and natural gas utility serving customers in Michigan.\n  Consumers Energy participates in the Green Button Connect My Data (GBCMD)\n  program, exposing customer-authorized energy usage data to third parties via\n  OAuth 2.0 - typically brokered through UtilityAPI - for use in energy\n  management, demand response, EV charging, solar, and sustainability\n  applications.\napis:\n  - aid: cms-energy:consumers-green-button-api\n    name:\
  \ Consumers Energy Green Button Connect My Data API\n    tags:\n      - Energy Usage\n      - Green Button\n      - OAuth2\n      - Smart Meter\n      - Utility\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://utilityapi.com/docs/utilities/consumersenergy\n    properties:\n      - url: https://utilityapi.com/docs/utilities/consumersenergy\n        type: Documentation\n      - url: https://utilityapi.com/\n        type: Portal\n    description: >-\n      The Consumers Energy Green Button Connect My Data API exposes\n      customer-authorized electric and natural-gas usage data to registered\n      third parties using the NAESB ESPI / Green Button standard. Authorization\n      uses OAuth 2.0 with single sign-on or test-account scopes; data is\n      delivered as Green Button XML or JSON via UtilityAPI's standardized\n      endpoints (Meters, Bills, Intervals, Billing Summaries). Third parties\n      register with Consumers Energy,\
  \ are issued a client_id, and start in\n      sandbox mode before being approved for live data.\n    x-features:\n      - name: Green Button Standard\n        description: NAESB ESPI / Green Button XML for usage point and interval data.\n      - name: Meters Endpoint\n        description: Retrieve individual meter information for an authorized customer.\n      - name: Bills Endpoint\n        description: Retrieve bill history and charges.\n      - name: Intervals Endpoint\n        description: Retrieve granular interval-usage time series.\n      - name: Billing Summaries\n        description: Retrieve account-level summary data.\n      - name: OAuth 2.0\n        description: Customer authorization via OAuth 2.0 with SSO or test scopes.\n      - name: Sandbox Test Accounts\n        description: Built-in test residential and commercial scenarios for development.\n    x-useCases:\n      - name: Energy Efficiency\n        description: Pull usage data into energy efficiency and benchmarking\
  \ apps.\n      - name: Demand Response\n        description: Power demand-response and load-management programs.\n      - name: Solar and EV\n        description: Inform solar sizing and EV-charging optimization with real usage.\n      - name: Sustainability Reporting\n        description: Aggregate usage into Scope 2 emissions and ESG reporting.\ncommon:\n  - url: https://www.cmsenergy.com\n    type: Website\n  - url: https://www.consumersenergy.com\n    name: Consumers Energy\n    type: Website\n  - url: https://utilityapi.com/docs/utilities/consumersenergy\n    name: Consumers Energy on UtilityAPI\n    type: Documentation\n  - url: https://www.cmsenergy.com/about-cms-energy/consumers-energy/\n    name: About Consumers Energy\n    type: About\n  - url: https://www.cmsenergy.com/contact-us/default.aspx\n    name: Contact Us\n    type: Support\n  - url: https://www.cmsenergy.com/privacy-statement/default.aspx\n    name: Privacy Statement\n    type: PrivacyPolicy\n  - url: https://twitter.com/CMSEnergy\n\
  \    name: CMS Energy on X\n    type: X\n  - url: https://www.linkedin.com/company/cms-energy/\n    name: CMS Energy on LinkedIn\n    type: LinkedIn\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cms-energy/refs/heads/main/apis.yml
tags:
- Electric
- Energy
- Green Button
- Michigan
- Natural Gas
- Utility
url: https://raw.githubusercontent.com/api-evangelist/cms-energy/refs/heads/main/apis.yml
use_cases: []
---
