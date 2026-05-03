---
api_count: 4
api_specs:
- filename: ssa-field-office-openapi.yml
  format: yaml
  label: SSA Field Office Address API
  slug: field-office-address-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/social-security-administration/refs/heads/main/openapi/ssa-field-office-openapi.yml
- filename: ssa-resident-station-openapi.yml
  format: yaml
  label: SSA Resident Station Address API
  slug: resident-station-address-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/social-security-administration/refs/heads/main/openapi/ssa-resident-station-openapi.yml
apis:
- description: Provides location, address, telephone numbers, and office hours for Social Security Administration Field Offices across the United States. Uses the Esri ArcGIS Online platform as a RESTful Feature Ser
  name: SSA Field Office Address API
  slug: field-office-address-api
- description: Provides location, address, telephone numbers, and office hours for Social Security Administration Resident Stations — smaller SSA offices that serve rural communities. Uses the Esri ArcGIS Online pla
  name: SSA Resident Station Address API
  slug: resident-station-address-api
- description: Provides statistics on Old Age, Survivors, and Disability Insurance (OASDI) beneficiaries including counts by state, total population data, and benefit payment statistics. Available through SSA's open
  name: SSA OASDI Open Data API
  slug: oasdi-data-api
- description: The Electronic Consent Based SSN Verification (eCBSV) Service allows financial institutions to verify that a provided Social Security Number, name, and date of birth match SSA records, with consent fr
  name: SSA eCBSV Verification API
  slug: ecbsv-api
common:
- title: ''
  type: Website
  url: https://www.ssa.gov/
- title: ''
  type: Developer Portal
  url: https://www.ssa.gov/developer/
- title: ''
  type: Open Data Portal
  url: https://www.ssa.gov/data/
- title: ''
  type: Open Data Inventory
  url: https://www.ssa.gov/data/Open-Data-Inventory-Information.html
- title: ''
  type: Data.gov Organization
  url: https://catalog.data.gov/organization/ssa-gov
- title: ''
  type: JSON Schema
  url: json-schema/ssa-field-office-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/ssa-resident-station-schema.json
- title: ''
  type: JSON Structure
  url: json-structure/ssa-office-structure.json
- title: ''
  type: JSON-LD Context
  url: json-ld/ssa-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/ssa-vocabulary.yml
- title: ''
  type: Examples
  url: examples/ssa-field-office-query-example.json
created: '2024-12-03'
description: The Social Security Administration (SSA) is a U.S. federal agency that administers Social Security programs including retirement, disability (SSDI), and survivor benefits. SSA's Developer Support portal provides APIs for locating field offices and resident stations, accessing open data on OASDI beneficiary statistics, and verifying Social Security Numbers through the eCBSV program.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: Ssa Context
  property_count: 6
  slug: ssa-context
layout: provider
modified: '2026-05-02'
name: Social Security Administration
rules:
- name: Social Security Administration API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 3
  slug: ssa-rules
skills: []
slug: social-security-administration
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: social-security-administration\nname: Social Security Administration\ndescription: >-\n  The Social Security Administration (SSA) is a U.S. federal agency that administers Social Security programs including retirement, disability (SSDI), and survivor benefits. SSA's Developer Support portal provides APIs for locating field offices and resident stations, accessing open data on OASDI beneficiary statistics, and verifying Social Security Numbers through the eCBSV program.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/social-security-administration/refs/heads/main/apis.yml\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-05-02'\nposition: Consuming\ntags:\n  - Federal Government\n  - Social Security\n  - Government API\n  - Open Data\n  - OASDI\n  - Disability Benefits\n  - Retirement Benefits\nspecificationVersion: '0.19'\napis:\n  - aid: social-security-administration:field-office-address-api\n\
  \    name: SSA Field Office Address API\n    description: >-\n      Provides location, address, telephone numbers, and office hours for Social Security Administration Field Offices across the United States. Uses the Esri ArcGIS Online platform as a RESTful Feature Service.\n    humanURL: https://www.ssa.gov/developer/api/FO_Address_Data_AppDevs.htm\n    tags:\n      - Field Offices\n      - Location Services\n      - Government Data\n      - Open Data\n    properties:\n      - type: Documentation\n        url: https://www.ssa.gov/developer/api/FO_Address_Data_AppDevs.htm\n      - type: OpenAPI\n        url: openapi/ssa-field-office-openapi.yml\n      - type: ArcGIS Feature Service\n        url: https://services6.arcgis.com/zFiipv75rloRP5N4/ArcGIS/rest/services/Office_Points/FeatureServer/1\n\n  - aid: social-security-administration:resident-station-address-api\n    name: SSA Resident Station Address API\n    description: >-\n      Provides location, address, telephone numbers, and office\
  \ hours for Social Security Administration Resident Stations — smaller SSA offices that serve rural communities. Uses the Esri ArcGIS Online platform as a RESTful Feature Service.\n    humanURL: https://www.ssa.gov/developer/api/RS_Address_Data_AppDevs.htm\n    tags:\n      - Resident Stations\n      - Location Services\n      - Government Data\n      - Open Data\n    properties:\n      - type: Documentation\n        url: https://www.ssa.gov/developer/api/RS_Address_Data_AppDevs.htm\n      - type: OpenAPI\n        url: openapi/ssa-resident-station-openapi.yml\n      - type: ArcGIS Feature Service\n        url: https://services6.arcgis.com/zFiipv75rloRP5N4/arcgis/rest/services/SSA_Resident_Station_Information/FeatureServer\n\n  - aid: social-security-administration:oasdi-data-api\n    name: SSA OASDI Open Data API\n    description: >-\n      Provides statistics on Old Age, Survivors, and Disability Insurance (OASDI) beneficiaries including counts by state, total population data, and benefit\
  \ payment statistics. Available through SSA's open data portal and Esri Feature Services.\n    humanURL: https://www.ssa.gov/data/OASDIBeneficiariesbyState.htm\n    tags:\n      - OASDI\n      - Beneficiary Statistics\n      - Open Data\n      - Benefits Data\n    properties:\n      - type: Documentation\n        url: https://www.ssa.gov/data/OASDIBeneficiariesbyState.htm\n      - type: Open Data Portal\n        url: https://www.ssa.gov/data/\n\n  - aid: social-security-administration:ecbsv-api\n    name: SSA eCBSV Verification API\n    description: >-\n      The Electronic Consent Based SSN Verification (eCBSV) Service allows financial institutions to verify that a provided Social Security Number, name, and date of birth match SSA records, with consent from the individual. Access is restricted to eligible financial institutions.\n    humanURL: https://www.ssa.gov/dataexchange/eCBSV/\n    tags:\n      - SSN Verification\n      - Identity Verification\n      - Financial Services\n     \
  \ - Consent Based\n    properties:\n      - type: Documentation\n        url: https://www.ssa.gov/dataexchange/eCBSV/technical_information.html\n      - type: CBSV Web Service\n        url: https://www.ssa.gov/cbsv/webservice.html\n\ncommon:\n  - type: Website\n    url: https://www.ssa.gov/\n  - type: Developer Portal\n    url: https://www.ssa.gov/developer/\n  - type: Open Data Portal\n    url: https://www.ssa.gov/data/\n  - type: Open Data Inventory\n    url: https://www.ssa.gov/data/Open-Data-Inventory-Information.html\n  - type: Data.gov Organization\n    url: https://catalog.data.gov/organization/ssa-gov\n  - type: JSON Schema\n    url: json-schema/ssa-field-office-schema.json\n  - type: JSON Schema\n    url: json-schema/ssa-resident-station-schema.json\n  - type: JSON Structure\n    url: json-structure/ssa-office-structure.json\n  - type: JSON-LD Context\n    url: json-ld/ssa-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/ssa-vocabulary.yml\n  - type: Examples\n    url:\
  \ examples/ssa-field-office-query-example.json\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/social-security-administration/refs/heads/main/apis.yml
tags:
- Federal Government
- Social Security
- Government API
- Open Data
- OASDI
- Disability Benefits
- Retirement Benefits
url: https://raw.githubusercontent.com/api-evangelist/social-security-administration/refs/heads/main/apis.yml
use_cases: []
---
