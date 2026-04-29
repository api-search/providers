---
api_count: 5
apis:
- description: The Advance Passenger Information System (APIS) collects pre-arrival and pre-departure manifest data on all passengers and crew members flown or sailed into and out of the United States. The eAPIS web
  name: APIS / eAPIS
  slug: apis-eapis
- description: ACE is the U.S. Single Window through which the trade community reports imports and exports and CBP and Partner Government Agencies determine admissibility. Trade users access ACE via the ACE Secure D
  name: Automated Commercial Environment (ACE)
  slug: ace
- description: AES is the system through which exporters file Electronic Export Information (EEI) for goods leaving the United States. AES is integrated with ACE and supports both EDI filings and the AESDirect web f
  name: Automated Export System (AES)
  slug: aes
- description: The AESDirect WebLink Inquiry API allows authorized partners to programmatically query AESDirect filings. CBP provides separate certification (test) and production environments for the API. This is on
  name: AESDirect WebLink Inquiry API
  slug: aesdirect-weblink-inquiry-api
- description: ACAS requires inbound air carriers and other eligible parties to submit advance air cargo data to CBP for security risk-based screening prior to loading on aircraft destined for the United States. ACA
  name: Air Cargo Advance Screening (ACAS)
  slug: acas
common:
- title: ''
  type: Website
  url: https://www.cbp.gov/
- title: ''
  type: TradeAutomation
  url: https://www.cbp.gov/trade/automated
- title: ''
  type: TradeOutreach
  url: https://www.cbp.gov/trade/stakeholder-engagement
- title: ''
  type: ACEServiceDesk
  url: https://www.cbp.gov/contact/automated-broker-interface-service-desk
- title: ''
  type: HelpCenter
  url: https://www.help.cbp.gov/
- title: ''
  type: Newsroom
  url: https://www.cbp.gov/newsroom
- title: ''
  type: FOIA
  url: https://www.cbp.gov/site-policy-notices/foia
- title: ''
  type: PrivacyPolicy
  url: https://www.cbp.gov/site-policy-notices/privacy-policy
- title: ''
  type: Twitter
  url: https://twitter.com/CBP
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/u-s-customs-and-border-protection/
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/CustomsBorderProtect
created: '2024-12-03'
description: U.S. Customs and Border Protection (CBP) is the federal law enforcement agency within the Department of Homeland Security responsible for apprehending individuals attempting to enter the United States illegally, stemming the flow of illegal drugs and contraband, protecting agricultural and economic interests from harmful pests and diseases, protecting intellectual property, and regulating and facilitating international trade, collecting import duties, and enforcing U.S. trade laws. CBP's primary trade automation systems are the Automated Commercial Environment (ACE), the Automated Export System (AES), AESDirect, the Advance Passenger Information System (APIS / eAPIS), and the Air Cargo Advance Screening (ACAS) program. Trade integrations are predominantly delivered through Electronic Data Interchange (EDI) messaging via ACE, with a small set of CBP web services (e.g., the AESDirect WebLink Inquiry API) exposed for programmatic use.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Customs and Border Protection
skills: []
slug: customs-and-border-protection
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: customs-and-border-protection\nname: Customs and Border Protection\nx-type: government\ndescription: >-\n  U.S. Customs and Border Protection (CBP) is the federal law enforcement\n  agency within the Department of Homeland Security responsible for\n  apprehending individuals attempting to enter the United States illegally,\n  stemming the flow of illegal drugs and contraband, protecting agricultural\n  and economic interests from harmful pests and diseases, protecting\n  intellectual property, and regulating and facilitating international trade,\n  collecting import duties, and enforcing U.S. trade laws. CBP's primary\n  trade automation systems are the Automated Commercial Environment (ACE),\n  the Automated Export System (AES), AESDirect, the Advance Passenger\n  Information System (APIS / eAPIS), and the Air Cargo Advance Screening\n  (ACAS) program. Trade integrations are predominantly delivered through\n  Electronic Data Interchange (EDI) messaging via ACE, with a\
  \ small set of\n  CBP web services (e.g., the AESDirect WebLink Inquiry API) exposed for\n  programmatic use.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/customs-and-border-protection/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\naccess: Public\nposition: Consuming\ncreated: '2024-12-03'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntags:\n  - ACE\n  - ACAS\n  - AES\n  - AESDirect\n  - APIS\n  - Borders\n  - Cargo\n  - CBP\n  - Customs\n  - Department of Homeland Security\n  - DHS\n  - EDI\n  - Exports\n  - Federal Government\n  - Imports\n  - International Trade\n  - Manifests\n  - Single Window\n  - Trade Compliance\napis:\n  - aid: customs-and-border-protection:apis-eapis\n    name: APIS / eAPIS\n    description: >-\n      The Advance Passenger Information System (APIS) collects pre-arrival\n      and pre-departure manifest data on all passengers and crew members\n      flown or sailed\
  \ into and out of the United States. The eAPIS web\n      portal allows commercial operators and private aircraft and vessel\n      operators to create, manage, and submit APIS manifests. Bulk and\n      partner integrations use UN/EDIFACT PAXLST and CUSRES messages over\n      CBP-approved transmission methods.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cbp.gov/travel/travel-industry-personnel/advance-passenger-information-system\n    baseURL: https://eapis.cbp.dhs.gov/\n    tags:\n      - APIS\n      - Border Security\n      - Crew\n      - eAPIS\n      - Manifests\n      - Passengers\n    properties:\n      - type: Documentation\n        url: https://www.cbp.gov/travel/travel-industry-personnel/advance-passenger-information-system\n      - type: Portal\n        url: https://eapis.cbp.dhs.gov/\n      - type: FactSheet\n        url: https://www.cbp.gov/sites/default/files/assets/documents/2019-Sep/APIS-Fact-Sheet-2019.pdf\n\
  \  - aid: customs-and-border-protection:ace\n    name: Automated Commercial Environment (ACE)\n    description: >-\n      ACE is the U.S. Single Window through which the trade community\n      reports imports and exports and CBP and Partner Government Agencies\n      determine admissibility. Trade users access ACE via the ACE Secure\n      Data Portal (a free web-based interface) and via ACE Electronic Data\n      Interchange (EDI), which uses CBP-approved CAMIR/AESTIR messaging\n      standards. The ACE Portal modernization program completed user\n      access management migration in February 2025.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cbp.gov/trade/automated\n    baseURL: https://ace.cbp.dhs.gov/\n    tags:\n      - ACE\n      - Admissibility\n      - Cargo\n      - EDI\n      - Imports\n      - PGA\n      - Single Window\n    properties:\n      - type: Documentation\n        url: https://www.cbp.gov/trade/automated\n\
  \      - type: GettingStarted\n        url: https://www.cbp.gov/trade/automated/how-to-use-ace\n      - type: Portal\n        url: https://ace.cbp.dhs.gov/\n      - type: Modernization\n        url: https://www.cbp.gov/trade/automated/ace-deployments/ace-portal-modernization\n      - type: Deployments\n        url: https://www.cbp.gov/trade/automated/ace-deployments\n  - aid: customs-and-border-protection:aes\n    name: Automated Export System (AES)\n    description: >-\n      AES is the system through which exporters file Electronic Export\n      Information (EEI) for goods leaving the United States. AES is\n      integrated with ACE and supports both EDI filings and the AESDirect\n      web filing tool. AESDirect is the free web-based filing application\n      offered by CBP to file EEI directly into AES.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cbp.gov/trade/aes\n    baseURL: https://ace.cbp.dhs.gov/\n    tags:\n\
  \      - AES\n      - AESDirect\n      - EEI\n      - Exports\n      - Filings\n    properties:\n      - type: Documentation\n        url: https://www.cbp.gov/trade/aes\n      - type: AESDirect\n        url: https://www.cbp.gov/trade/aes/aesdirect\n  - aid: customs-and-border-protection:aesdirect-weblink-inquiry-api\n    name: AESDirect WebLink Inquiry API\n    description: >-\n      The AESDirect WebLink Inquiry API allows authorized partners to\n      programmatically query AESDirect filings. CBP provides separate\n      certification (test) and production environments for the API. This\n      is one of the few directly exposed web APIs in CBP's trade portfolio.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cbp.gov/trade/automated/aesdirect-weblink-inquiry-api\n    baseURL: https://ace.cbp.dhs.gov/\n    tags:\n      - AES\n      - AESDirect\n      - Filings\n      - Inquiry\n      - WebLink\n    properties:\n      -\
  \ type: Documentation\n        url: https://www.cbp.gov/trade/automated/aesdirect-weblink-inquiry-api\n  - aid: customs-and-border-protection:acas\n    name: Air Cargo Advance Screening (ACAS)\n    description: >-\n      ACAS requires inbound air carriers and other eligible parties to\n      submit advance air cargo data to CBP for security risk-based\n      screening prior to loading on aircraft destined for the United\n      States. ACAS data is transmitted via CBP-approved EDI messages.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cbp.gov/border-security/ports-entry/cargo-security/acas\n    baseURL: https://ace.cbp.dhs.gov/\n    tags:\n      - ACAS\n      - Advance Data\n      - Air Cargo\n      - Pre-loading\n      - Security\n    properties:\n      - type: Documentation\n        url: https://www.cbp.gov/border-security/ports-entry/cargo-security/acas\ncommon:\n  - type: Website\n    url: https://www.cbp.gov/\n  -\
  \ type: TradeAutomation\n    url: https://www.cbp.gov/trade/automated\n  - type: TradeOutreach\n    url: https://www.cbp.gov/trade/stakeholder-engagement\n  - type: ACEServiceDesk\n    url: https://www.cbp.gov/contact/automated-broker-interface-service-desk\n  - type: HelpCenter\n    url: https://www.help.cbp.gov/\n  - type: Newsroom\n    url: https://www.cbp.gov/newsroom\n  - type: FOIA\n    url: https://www.cbp.gov/site-policy-notices/foia\n  - type: PrivacyPolicy\n    url: https://www.cbp.gov/site-policy-notices/privacy-policy\n  - type: Twitter\n    url: https://twitter.com/CBP\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/u-s-customs-and-border-protection/\n  - type: YouTube\n    url: https://www.youtube.com/user/CustomsBorderProtect\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/customs-and-border-protection/refs/heads/main/apis.yml
tags:
- ACE
- ACAS
- AES
- AESDirect
- APIS
- Borders
- Cargo
- CBP
- Customs
- Department of Homeland Security
- DHS
- EDI
- Exports
- Federal Government
- Imports
- International Trade
- Manifests
- Single Window
- Trade Compliance
url: https://raw.githubusercontent.com/api-evangelist/customs-and-border-protection/refs/heads/main/apis.yml
use_cases: []
---
