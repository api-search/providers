---
api_count: 2
apis:
- description: The Consolidated Screening List (CSL) API consolidates export screening lists from the Departments of Commerce, State, and Treasury. It includes the Entity List, Denied Persons List, Unverified List (
  name: Consolidated Screening List (CSL) API
  slug: consolidated-screening-list-api
- description: SNAP-R (Simplified Network Application Process Redesign) is the BIS online system for applying for export licenses, classifications, and authorizations under the Export Administration Regulations (EAR
  name: SNAP-R Export License Application System
  slug: snap-r
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
created: '2024-12-25'
description: 'The Bureau of Industry and Security (BIS) is a division of the U.S. Department of Commerce that implements and enforces export control regulations to protect national security and prevent the proliferation of weapons of mass destruction. BIS reviews license applications for the export of sensitive goods and technologies, conducts outreach on compliance with export control laws, and maintains the Consolidated Screening List. Note: this entry is an alias for bureau-of-industry-and-security.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bureau of Industry Security
skills: []
slug: bureau-of-industry-security
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bureau-of-industry-security\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bureau-of-industry-security/refs/heads/main/apis.yml\nname: Bureau of Industry Security\ntags:\n  - Compliance\n  - Export Controls\n  - Federal Government\n  - Industries\n  - National Security\n  - Screening Lists\n  - Security\ntype: Index\nx-type: government\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-25'\nmodified: '2026-04-21'\nposition: Consumer\ndescription: >-\n  The Bureau of Industry and Security (BIS) is a division of the U.S. Department\n  of Commerce that implements and enforces export control regulations to protect\n  national security and prevent the proliferation of weapons of mass destruction.\n  BIS reviews license applications for the export of sensitive goods and\n  technologies, conducts outreach on compliance with export control laws, and\n  maintains the Consolidated Screening List.\
  \ Note: this entry is an alias for\n  bureau-of-industry-and-security.\napis:\n  - aid: bureau-of-industry-security:consolidated-screening-list-api\n    name: Consolidated Screening List (CSL) API\n    tags:\n      - Compliance\n      - Export Controls\n      - Federal Government\n      - Sanctions\n      - Screening\n    humanURL: https://www.trade.gov/consolidated-screening-list\n    baseURL: https://api.trade.gov/gateway/v1/consolidated_screening_list\n    properties:\n      - url: https://www.trade.gov/consolidated-screening-list\n        type: Documentation\n      - url: https://api.trade.gov/gateway/v1/consolidated_screening_list/search\n        type: DataAPI\n    description: >-\n      The Consolidated Screening List (CSL) API consolidates export screening\n      lists from the Departments of Commerce, State, and Treasury. It includes\n      the Entity List, Denied Persons List, Unverified List (BIS), ITAR\n      Debarred List (State), SDN List, and others. Used for trade compliance\n\
  \      and due diligence screening.\n    x-features:\n      - Consolidated view of multiple export control screening lists\n      - Full-text search by name, country, and address\n      - Fuzzy name matching for due diligence\n      - REST API with JSON responses\n      - API key authentication via api.data.gov\n    x-use-cases:\n      - Export compliance screening before transactions\n      - Automated trade partner due diligence\n      - Sanctions and embargo verification\n      - Regulatory compliance workflows\n  - aid: bureau-of-industry-security:snap-r\n    name: SNAP-R Export License Application System\n    tags:\n      - Export Controls\n      - Federal Government\n      - Licensing\n    humanURL: https://snapr.bis.doc.gov/\n    properties:\n      - url: https://www.bis.gov/licensing/how-to-apply-snap-r\n        type: Documentation\n    description: >-\n      SNAP-R (Simplified Network Application Process Redesign) is the BIS\n      online system for applying for export licenses,\
  \ classifications, and\n      authorizations under the Export Administration Regulations (EAR).\ncommon:\n  - type: Website\n    url: https://www.bis.gov\n  - type: Privacy Policy\n    url: https://www.bis.gov/privacy-policy\n  - type: Consolidated Screening List\n    url: https://www.trade.gov/consolidated-screening-list\n  - type: Export Administration Regulations\n    url: https://www.bis.gov/regulations/export-administration-regulations-ear\n  - type: Commerce Control List\n    url: https://www.bis.gov/regulations/commerce-control-list-ccl\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bureau-of-industry-security/refs/heads/main/apis.yml
tags:
- Compliance
- Export Controls
- Federal Government
- Industries
- National Security
- Screening Lists
- Security
url: https://raw.githubusercontent.com/api-evangelist/bureau-of-industry-security/refs/heads/main/apis.yml
use_cases: []
---
