---
api_count: 6
api_specs:
- filename: sam-gov-location-services-openapi.yml
  format: yaml
  label: SAM.gov Public Location Services API
  slug: location-services-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sam.gov/refs/heads/main/openapi/sam-gov-location-services-openapi.yml
apis:
- description: The Public Location Services API provides Location Services data (Country, State, City, and ZIP) for validating location data submitted to SAM.gov. Location Services State API supports both United Sta
  name: SAM.gov Public Location Services API
  slug: location-services-api
- description: The Get Opportunities Public API provides all published contract opportunity details based on request parameters. Returns solicitation notices, awards, and pre-solicitations from SAM.gov. Rate limited
  name: SAM.gov Get Opportunities Public API
  slug: get-opportunities-api
- description: 'The Opportunity Management API allows authorized users to programmatically submit, update, and manage contract opportunity notices in SAM.gov. Requires federal government or contractor system account '
  name: SAM.gov Opportunity Management API
  slug: opportunities-management-api
- description: The Entity Management API provides detailed entity (vendor/contractor) information from SAM.gov including registration status, hierarchy, security levels, points of contact, and certifications. Used t
  name: SAM.gov Entity Management API
  slug: entity-management-api
- description: The Federal Hierarchy Public API allows non-federal users to retrieve Federal Organization details down to the office level. Used to look up agency and organizational hierarchy for federal procurement
  name: SAM.gov Federal Hierarchy Public API
  slug: federal-hierarchy-public-api
- description: The Contract Awards API provides access to federal contract award information from SAM.gov, including award details, vendor information, award amounts, and performance period data.
  name: SAM.gov Contract Awards API
  slug: contract-awards-api
capabilities:
- description: Federal procurement workflow for validating vendor registration data against SAM.gov location services. Used by government contractors, procurement officers, and vendor registration systems to validat
  name: SAM.gov Federal Procurement
  slug: federal-procurement
common:
- title: ''
  type: Website
  url: https://sam.gov
- title: ''
  type: Portal
  url: https://open.gsa.gov/api/
- title: ''
  type: Documentation
  url: https://open.gsa.gov/api/
- title: ''
  type: APIKey
  url: https://open.gsa.gov/api/get-opportunities-public-api/#getting-started
- title: ''
  type: GitHub
  url: https://github.com/GSA
- title: ''
  type: DataCatalog
  url: https://catalog.data.gov
- title: ''
  type: Status
  url: https://sam.gov/status
created: '2024-03-29'
description: SAM.gov (System for Award Management) is the official US government system for vendor registration and federal procurement. Operated by the General Services Administration (GSA), SAM.gov consolidates multiple legacy acquisition systems and provides APIs for contract opportunities, entity management, federal hierarchy, and location validation services.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Sam Gov Context
  property_count: 5
  slug: sam-gov-context
layout: provider
modified: '2026-05-02'
name: SAM.gov
rules:
- name: SAM.gov API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 2
    info: 0
    warn: 4
  slug: sam-gov-rules
skills: []
slug: sam.gov
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sam.gov\nurl: https://raw.githubusercontent.com/api-evangelist/sam.gov/refs/heads/main/apis.yml\nname: SAM.gov\ndescription: >-\n  SAM.gov (System for Award Management) is the official US government system for\n  vendor registration and federal procurement. Operated by the General Services\n  Administration (GSA), SAM.gov consolidates multiple legacy acquisition systems and\n  provides APIs for contract opportunities, entity management, federal hierarchy,\n  and location validation services.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Federal Government\n  - Procurement\n  - Contracts\n  - Entity Management\n  - Location Services\n  - GSA\naccess: Public\ncreated: '2024-03-29'\nmodified: '2026-05-02'\nx-profiled: '2026-05'\nspecificationVersion: '0.19'\napis:\n  - aid: sam.gov:location-services-api\n    name: SAM.gov Public Location Services API\n    description: >-\n      The Public Location Services API provides\
  \ Location Services data (Country,\n      State, City, and ZIP) for validating location data submitted to SAM.gov.\n      Location Services State API supports both United States and Foreign Countries.\n      Requires a valid SAM.gov System Account API key.\n    humanURL: https://open.gsa.gov/api/location-public-api/\n    tags:\n      - Location Services\n      - Validation\n      - Government\n      - GSA\n    properties:\n      - type: Documentation\n        url: https://open.gsa.gov/api/location-public-api/\n      - type: OpenAPI\n        url: openapi/sam-gov-location-services-openapi.yml\n\n  - aid: sam.gov:get-opportunities-api\n    name: SAM.gov Get Opportunities Public API\n    description: >-\n      The Get Opportunities Public API provides all published contract opportunity\n      details based on request parameters. Returns solicitation notices, awards,\n      and pre-solicitations from SAM.gov. Rate limited to 1000 requests/day.\n      Requires a SAM.gov API key.\n    humanURL:\
  \ https://open.gsa.gov/api/get-opportunities-public-api/\n    tags:\n      - Contract Opportunities\n      - Procurement\n      - Federal Contracts\n      - Government\n    properties:\n      - type: Documentation\n        url: https://open.gsa.gov/api/get-opportunities-public-api/\n      - type: BaseURL\n        url: https://api.sam.gov/prod/opportunities/v2/search\n\n  - aid: sam.gov:opportunities-management-api\n    name: SAM.gov Opportunity Management API\n    description: >-\n      The Opportunity Management API allows authorized users to programmatically\n      submit, update, and manage contract opportunity notices in SAM.gov. Requires\n      federal government or contractor system account authorization.\n    humanURL: https://open.gsa.gov/api/opportunities-api/\n    tags:\n      - Contract Management\n      - Procurement\n      - Federal Contracts\n      - Government\n    properties:\n      - type: Documentation\n        url: https://open.gsa.gov/api/opportunities-api/\n\n  - aid:\
  \ sam.gov:entity-management-api\n    name: SAM.gov Entity Management API\n    description: >-\n      The Entity Management API provides detailed entity (vendor/contractor) information\n      from SAM.gov including registration status, hierarchy, security levels, points of\n      contact, and certifications. Used to verify vendors eligible for federal contracts.\n    humanURL: https://open.gsa.gov/api/entity-api/\n    tags:\n      - Entity Management\n      - Vendor Registration\n      - Federal Procurement\n      - Government\n    properties:\n      - type: Documentation\n        url: https://open.gsa.gov/api/entity-api/\n\n  - aid: sam.gov:federal-hierarchy-public-api\n    name: SAM.gov Federal Hierarchy Public API\n    description: >-\n      The Federal Hierarchy Public API allows non-federal users to retrieve Federal\n      Organization details down to the office level. Used to look up agency and\n      organizational hierarchy for federal procurement purposes.\n    humanURL: https://open.gsa.gov/api/fh-public-api/\n\
  \    tags:\n      - Federal Hierarchy\n      - Government Organization\n      - Government\n    properties:\n      - type: Documentation\n        url: https://open.gsa.gov/api/fh-public-api/\n\n  - aid: sam.gov:contract-awards-api\n    name: SAM.gov Contract Awards API\n    description: >-\n      The Contract Awards API provides access to federal contract award information\n      from SAM.gov, including award details, vendor information, award amounts,\n      and performance period data.\n    humanURL: https://open.gsa.gov/api/contract-awards/\n    tags:\n      - Contract Awards\n      - Federal Spending\n      - Procurement\n      - Government\n    properties:\n      - type: Documentation\n        url: https://open.gsa.gov/api/contract-awards/\n\ncommon:\n  - type: Website\n    url: https://sam.gov\n  - type: Portal\n    url: https://open.gsa.gov/api/\n  - type: Documentation\n    url: https://open.gsa.gov/api/\n  - type: APIKey\n    url: https://open.gsa.gov/api/get-opportunities-public-api/#getting-started\n\
  \  - type: GitHub\n    url: https://github.com/GSA\n  - type: DataCatalog\n    url: https://catalog.data.gov\n  - type: Status\n    url: https://sam.gov/status\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sam.gov/refs/heads/main/apis.yml
tags:
- Federal Government
- Procurement
- Contracts
- Entity Management
- Location Services
- GSA
url: https://raw.githubusercontent.com/api-evangelist/sam.gov/refs/heads/main/apis.yml
use_cases: []
---
