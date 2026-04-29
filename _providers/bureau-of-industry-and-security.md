---
api_count: 3
apis:
- description: The Consolidated Screening List (CSL) API consolidates export screening lists from the Departments of Commerce, State, and Treasury. It includes the Entity List, Denied Persons List, Unverified List (
  name: Consolidated Screening List (CSL) API
  slug: consolidated-screening-list-api
- description: SNAP-R (Simplified Network Application Process Redesign) is the BIS online system for applying for export licenses, classifications, and authorizations under the Export Administration Regulations (EAR
  name: SNAP-R Export License Application System
  slug: snap-r
- description: STELA (System for Tracking Export License Applications) allows applicants to check the status of export license applications submitted to BIS.
  name: STELA Export License Tracking
  slug: stela
common:
- title: ''
  type: Website
  url: https://www.bis.gov
- title: ''
  type: Privacy Policy
  url: https://www.bis.gov/privacy-policy
- title: ''
  type: Consolidated Screening List
  url: https://www.trade.gov/consolidated-screening-list
- title: ''
  type: Export Administration Regulations
  url: https://www.bis.gov/regulations/export-administration-regulations-ear
- title: ''
  type: Commerce Control List
  url: https://www.bis.gov/regulations/commerce-control-list-ccl
created: '2024-11-25'
description: The Bureau of Industry and Security (BIS), a division of the U.S. Department of Commerce, advances U.S. national security, foreign policy, and economic objectives by administering an effective export control and treaty compliance system. BIS maintains the Commerce Control List (CCL), administers the Consolidated Screening List (CSL), and operates the SNAP-R licensing system.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bureau of Industry and Security
skills: []
slug: bureau-of-industry-and-security
solutions: []
source_filename: apis.yml
source_yaml: "aid: bureau-of-industry-and-security\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bureau-of-industry-and-security/refs/heads/main/apis.yml\nname: Bureau of Industry and Security\ntags:\n  - Compliance\n  - Export Controls\n  - Federal Government\n  - Industries\n  - National Security\n  - Screening Lists\n  - Security\ntype: Index\nx-type: government\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-25'\nmodified: '2026-04-21'\nposition: Consumer\ndescription: >-\n  The Bureau of Industry and Security (BIS), a division of the U.S. Department\n  of Commerce, advances U.S. national security, foreign policy, and economic\n  objectives by administering an effective export control and treaty compliance\n  system. BIS maintains the Commerce Control List (CCL), administers the\n  Consolidated Screening List (CSL), and operates the SNAP-R licensing system.\napis:\n  - aid: bureau-of-industry-and-security:consolidated-screening-list-api\n\
  \    name: Consolidated Screening List (CSL) API\n    tags:\n      - Compliance\n      - Export Controls\n      - Federal Government\n      - Sanctions\n      - Screening\n    humanURL: https://www.trade.gov/consolidated-screening-list\n    baseURL: https://api.trade.gov/gateway/v1/consolidated_screening_list\n    properties:\n      - url: https://www.trade.gov/consolidated-screening-list\n        type: Documentation\n      - url: https://api.trade.gov/gateway/v1/consolidated_screening_list/search\n        type: DataAPI\n    description: >-\n      The Consolidated Screening List (CSL) API consolidates export screening\n      lists from the Departments of Commerce, State, and Treasury. It includes\n      the Entity List, Denied Persons List, Unverified List (BIS), ITAR\n      Debarred List (State), SDN List, and others. Used for trade compliance\n      and due diligence screening.\n    x-features:\n      - Consolidated view of multiple export control screening lists\n      - Full-text search\
  \ by name, country, and address\n      - Fuzzy name matching for due diligence\n      - REST API with JSON responses\n      - API key authentication via api.data.gov\n    x-use-cases:\n      - Export compliance screening before transactions\n      - Automated trade partner due diligence\n      - Sanctions and embargo verification\n      - Regulatory compliance workflows\n  - aid: bureau-of-industry-and-security:snap-r\n    name: SNAP-R Export License Application System\n    tags:\n      - Export Controls\n      - Federal Government\n      - Licensing\n    humanURL: https://snapr.bis.doc.gov/\n    properties:\n      - url: https://www.bis.gov/licensing/how-to-apply-snap-r\n        type: Documentation\n    description: >-\n      SNAP-R (Simplified Network Application Process Redesign) is the BIS\n      online system for applying for export licenses, classifications, and\n      authorizations under the Export Administration Regulations (EAR).\n  - aid: bureau-of-industry-and-security:stela\n\
  \    name: STELA Export License Tracking\n    tags:\n      - Export Controls\n      - Federal Government\n      - Licensing\n      - Tracking\n    humanURL: https://www.bis.gov/licensing/stela\n    properties:\n      - url: https://www.bis.gov/licensing/stela\n        type: Documentation\n    description: >-\n      STELA (System for Tracking Export License Applications) allows applicants\n      to check the status of export license applications submitted to BIS.\ncommon:\n  - type: Website\n    url: https://www.bis.gov\n  - type: Privacy Policy\n    url: https://www.bis.gov/privacy-policy\n  - type: Consolidated Screening List\n    url: https://www.trade.gov/consolidated-screening-list\n  - type: Export Administration Regulations\n    url: https://www.bis.gov/regulations/export-administration-regulations-ear\n  - type: Commerce Control List\n    url: https://www.bis.gov/regulations/commerce-control-list-ccl\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion:\
  \ '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bureau-of-industry-and-security/refs/heads/main/apis.yml
tags:
- Compliance
- Export Controls
- Federal Government
- Industries
- National Security
- Screening Lists
- Security
url: https://raw.githubusercontent.com/api-evangelist/bureau-of-industry-and-security/refs/heads/main/apis.yml
use_cases: []
---
