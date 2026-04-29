---
api_count: 9
apis:
- description: Blue Button 2.0 is a standards-based HL7 FHIR R4 API that delivers Medicare Part A, B, and D claims data for over 60 million beneficiaries to registered third-party applications, authorized by the ben
  name: CMS Blue Button 2.0 API
  slug: cms-blue-button-2
- description: The Beneficiary Claims Data API (BCDA) is a Bulk FHIR API that delivers Medicare Part A, B, and D claims data to Medicare Shared Savings Program ACOs, ACO REACH participants, and other Alternative Pay
  name: CMS Beneficiary Claims Data API (BCDA)
  slug: cms-bcda
- description: Data at the Point of Care is a FHIR Bulk Data API that delivers Original Medicare claims data to fee-for-service providers for the patients currently under their care, enabling clinicians to see a pat
  name: CMS Data at the Point of Care (DPC) API
  slug: cms-dpc
- description: data.cms.gov hosts hundreds of CMS datasets including Medicare Fee-for-Service utilization and payment data, Provider of Services files, Medicare Part B/D Prescriber summaries, Marketplace open enroll
  name: CMS Socrata Open Data API (data.cms.gov)
  slug: cms-socrata-open-data
- description: The Provider Data Catalog API (formerly Hospital Compare) exposes the Medicare.gov Care Compare datasets including Hospital, Nursing Home, Home Health, Hospice, Physician, Long-Term Care Hospital, Inp
  name: CMS Provider Data Catalog API (Care Compare)
  slug: cms-provider-data-catalog
- description: The NPPES NPI Registry API provides free public access to look up active National Provider Identifier records for individual and organizational healthcare providers, supporting FHIR-compatible JSON re
  name: NPPES NPI Registry API
  slug: nppes-npi-registry
- description: The Healthcare.gov Marketplace API and accompanying Open Data Plan Finder exposes Qualified Health Plan (QHP) details, plan attributes, provider networks, and formularies for the Federally-Facilitated
  name: Healthcare.gov Marketplace API
  slug: healthcare-gov-marketplace
- description: The Quality Payment Program Measures Data repository and REST API publish machine-readable specifications of MIPS quality, promoting interoperability, improvement activities, and cost measures for eac
  name: CMS Quality Payment Program (QPP) Measures API
  slug: qpp-measures-api
- description: The Medicare Coverage Database publishes National Coverage Determinations (NCDs), Local Coverage Determinations (LCDs), articles, and coding guidance used to determine Medicare coverage and reimbursem
  name: Medicare Coverage Database (MCD) API
  slug: medicare-coverage-database
common:
- title: ''
  type: Website
  url: https://www.cms.gov/
- title: ''
  type: Developer
  url: https://developer.cms.gov/
- title: ''
  type: OpenData
  url: https://data.cms.gov/
- title: ''
  type: ProviderData
  url: https://data.cms.gov/provider-data/
- title: ''
  type: BlueButton
  url: https://bluebutton.cms.gov/
- title: ''
  type: BCDA
  url: https://bcda.cms.gov/
- title: ''
  type: DPC
  url: https://dpc.cms.gov/
- title: ''
  type: NPPES
  url: https://npiregistry.cms.hhs.gov/
- title: ''
  type: Marketplace
  url: https://www.healthcare.gov/developers/
- title: ''
  type: QPP
  url: https://qpp.cms.gov/
- title: ''
  type: GitHubOrganization
  url: https://github.com/CMSgov
- title: ''
  type: Privacy Policy
  url: https://www.cms.gov/privacy
created: '2024-12-03'
description: The Centers for Medicare and Medicaid Services (CMS) is the federal agency that provides health coverage to more than 160 million Americans through Medicare, Medicaid, the Children's Health Insurance Program (CHIP), and the Health Insurance Marketplace. CMS operates one of the largest public API programs in the U.S. government, including the FHIR-based Blue Button 2.0, Beneficiary Claims Data API (BCDA), and Data at the Point of Care (DPC); the data.cms.gov Socrata Open Data API covering Medicare claims, provider, and enrollment datasets; the Medicare Provider Data Catalog (Hospital Compare, Nursing Home Compare); the Healthcare.gov Marketplace API; NPPES and NPI Registry APIs; the QPP Measures API; and Medicaid Transformed Medicaid Statistical Information System (T-MSIS) resources.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Centers for Medicare and Medicaid Services
skills: []
slug: centers-for-medicare-and-medicaid-services
solutions: []
source_yaml: "aid: centers-for-medicare-and-medicaid-services\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/centers-for-medicare-and-medicaid-services/refs/heads/main/apis.yml\nname: Centers for Medicare and Medicaid Services\ntags:\n  - BCDA\n  - Blue Button\n  - CMS\n  - Claims\n  - DPC\n  - FHIR\n  - Federal Government\n  - Healthcare\n  - Interoperability\n  - Marketplace\n  - Medicaid\n  - Medicare\n  - Open Data\n  - Provider Data\n  - Socrata\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-04-23'\nposition: Consumer\nspecificationVersion: '0.19'\ndescription: >-\n  The Centers for Medicare and Medicaid Services (CMS) is the federal agency\n  that provides health coverage to more than 160 million Americans through\n  Medicare, Medicaid, the Children's Health Insurance Program (CHIP), and\n  the Health Insurance Marketplace. CMS operates one of the largest public\n\
  \  API programs in the U.S. government, including the FHIR-based Blue Button\n  2.0, Beneficiary Claims Data API (BCDA), and Data at the Point of Care\n  (DPC); the data.cms.gov Socrata Open Data API covering Medicare claims,\n  provider, and enrollment datasets; the Medicare Provider Data Catalog\n  (Hospital Compare, Nursing Home Compare); the Healthcare.gov Marketplace\n  API; NPPES and NPI Registry APIs; the QPP Measures API; and Medicaid\n  Transformed Medicaid Statistical Information System (T-MSIS) resources.\napis:\n  - aid: centers-for-medicare-and-medicaid-services:cms-blue-button-2\n    name: CMS Blue Button 2.0 API\n    tags:\n      - Blue Button\n      - Claims\n      - FHIR\n      - Medicare\n      - OAuth 2.0\n      - Patient Access\n    humanURL: https://bluebutton.cms.gov/\n    baseURL: https://api.bluebutton.cms.gov/v2/fhir/\n    properties:\n      - url: https://bluebutton.cms.gov/\n        type: Website\n      - url: https://bluebutton.cms.gov/developers/\n        type:\
  \ Developer\n      - url: https://bluebutton.cms.gov/api-documentation/\n        type: Documentation\n      - url: https://sandbox.bluebutton.cms.gov/\n        type: Sandbox\n      - url: https://bluebutton.cms.gov/resources/\n        type: Resources\n    description: >-\n      Blue Button 2.0 is a standards-based HL7 FHIR R4 API that delivers\n      Medicare Part A, B, and D claims data for over 60 million beneficiaries\n      to registered third-party applications, authorized by the beneficiary\n      through OAuth 2.0. It anchors CMS's Patient Access API program under\n      the 21st Century Cures Act.\n  - aid: centers-for-medicare-and-medicaid-services:cms-bcda\n    name: CMS Beneficiary Claims Data API (BCDA)\n    tags:\n      - ACO\n      - BCDA\n      - Bulk FHIR\n      - Claims\n      - Medicare\n      - Shared Savings\n    humanURL: https://bcda.cms.gov/\n    baseURL: https://api.bcda.cms.gov/api/v2/\n    properties:\n      - url: https://bcda.cms.gov/\n        type: Website\n\
  \      - url: https://bcda.cms.gov/guide.html\n        type: Documentation\n      - url: https://sandbox.bcda.cms.gov/\n        type: Sandbox\n    description: >-\n      The Beneficiary Claims Data API (BCDA) is a Bulk FHIR API that delivers\n      Medicare Part A, B, and D claims data to Medicare Shared Savings\n      Program ACOs, ACO REACH participants, and other Alternative Payment\n      Model participants for their attributed and assignable beneficiaries.\n  - aid: centers-for-medicare-and-medicaid-services:cms-dpc\n    name: CMS Data at the Point of Care (DPC) API\n    tags:\n      - Bulk FHIR\n      - Claims\n      - FFS\n      - Point of Care\n      - Providers\n    humanURL: https://dpc.cms.gov/\n    baseURL: https://api.dpc.cms.gov/api/v1/\n    properties:\n      - url: https://dpc.cms.gov/\n        type: Website\n      - url: https://dpc.cms.gov/docs\n        type: Documentation\n      - url: https://sandbox.dpc.cms.gov/\n        type: Sandbox\n      - url: https://dpc.cms.gov/faq\n\
  \        type: FAQ\n    description: >-\n      Data at the Point of Care is a FHIR Bulk Data API that delivers\n      Original Medicare claims data to fee-for-service providers for the\n      patients currently under their care, enabling clinicians to see a\n      patient's full Medicare history at the point of care.\n  - aid: centers-for-medicare-and-medicaid-services:cms-socrata-open-data\n    name: CMS Socrata Open Data API (data.cms.gov)\n    tags:\n      - Datasets\n      - Medicare\n      - Open Data\n      - Provider Data\n      - SODA\n      - Socrata\n    humanURL: https://data.cms.gov/\n    baseURL: https://data.cms.gov/data.json\n    properties:\n      - url: https://data.cms.gov/\n        type: Website\n      - url: https://data.cms.gov/provider-data/docs\n        type: Documentation\n      - url: https://developer.cms.gov/data-cms/\n        type: Developer\n      - url: https://data.cms.gov/data-api\n        type: DataAPI\n    description: >-\n      data.cms.gov hosts hundreds\
  \ of CMS datasets including Medicare\n      Fee-for-Service utilization and payment data, Provider of Services\n      files, Medicare Part B/D Prescriber summaries, Marketplace open\n      enrollment data, and COVID-19 nursing home data, available via the\n      data.cms.gov Data API (JSON) and the CMS Provider Data Catalog\n      Socrata-compatible endpoints.\n  - aid: centers-for-medicare-and-medicaid-services:cms-provider-data-catalog\n    name: CMS Provider Data Catalog API (Care Compare)\n    tags:\n      - Care Compare\n      - Dialysis Compare\n      - Hospital Compare\n      - Nursing Home Compare\n      - Provider Data\n      - Quality\n    humanURL: https://data.cms.gov/provider-data/\n    baseURL: https://data.cms.gov/provider-data/api/1/\n    properties:\n      - url: https://data.cms.gov/provider-data/\n        type: Website\n      - url: https://data.cms.gov/provider-data/docs\n        type: Documentation\n      - url: https://data.cms.gov/provider-data/api/1/metastore/schemas/dataset/items\n\
  \        type: Metastore\n    description: >-\n      The Provider Data Catalog API (formerly Hospital Compare) exposes the\n      Medicare.gov Care Compare datasets including Hospital, Nursing Home,\n      Home Health, Hospice, Physician, Long-Term Care Hospital, Inpatient\n      Rehab, and Dialysis Facility quality measures as DCAT-based datasets\n      with Datastore query endpoints.\n  - aid: centers-for-medicare-and-medicaid-services:nppes-npi-registry\n    name: NPPES NPI Registry API\n    tags:\n      - Credentialing\n      - NPI\n      - NPPES\n      - Provider Identifier\n      - Provider Registry\n    humanURL: https://npiregistry.cms.hhs.gov/\n    baseURL: https://npiregistry.cms.hhs.gov/api/\n    properties:\n      - url: https://npiregistry.cms.hhs.gov/\n        type: Website\n      - url: https://npiregistry.cms.hhs.gov/api-page\n        type: Documentation\n      - url: https://npiregistry.cms.hhs.gov/help-api/\n        type: Help\n    description: >-\n      The NPPES NPI\
  \ Registry API provides free public access to look up\n      active National Provider Identifier records for individual and\n      organizational healthcare providers, supporting FHIR-compatible\n      JSON responses used widely in credentialing, directory, and claims\n      validation workflows.\n  - aid: centers-for-medicare-and-medicaid-services:healthcare-gov-marketplace\n    name: Healthcare.gov Marketplace API\n    tags:\n      - ACA\n      - Exchange\n      - Marketplace\n      - Plan Finder\n      - QHP\n    humanURL: https://www.healthcare.gov/developers/\n    baseURL: https://marketplace.api.healthcare.gov/api/v1/\n    properties:\n      - url: https://www.healthcare.gov/developers/\n        type: Developer\n      - url: https://github.com/CMSgov/marketplace-api-examples\n        type: Examples\n      - url: https://data.healthcare.gov/\n        type: OpenData\n    description: >-\n      The Healthcare.gov Marketplace API and accompanying Open Data Plan\n      Finder exposes\
  \ Qualified Health Plan (QHP) details, plan attributes,\n      provider networks, and formularies for the Federally-Facilitated\n      Marketplace states, enabling third-party plan comparison and\n      enrollment experiences.\n  - aid: centers-for-medicare-and-medicaid-services:qpp-measures-api\n    name: CMS Quality Payment Program (QPP) Measures API\n    tags:\n      - MIPS\n      - Measures\n      - Quality\n      - QPP\n      - Value-Based\n    humanURL: https://qpp.cms.gov/\n    properties:\n      - url: https://qpp.cms.gov/\n        type: Website\n      - url: https://cmsgov.github.io/qpp-measures-data/\n        type: Documentation\n      - url: https://github.com/CMSgov/qpp-measures-data\n        type: SourceCode\n    description: >-\n      The Quality Payment Program Measures Data repository and REST API\n      publish machine-readable specifications of MIPS quality, promoting\n      interoperability, improvement activities, and cost measures for each\n      performance year,\
  \ supporting vendor QPP submissions and analytics.\n  - aid: centers-for-medicare-and-medicaid-services:medicare-coverage-database\n    name: Medicare Coverage Database (MCD) API\n    tags:\n      - Coverage\n      - LCD\n      - MAC\n      - NCD\n      - Policy\n    humanURL: https://www.cms.gov/medicare-coverage-database/\n    properties:\n      - url: https://www.cms.gov/medicare-coverage-database/\n        type: Website\n      - url: https://www.cms.gov/medicare-coverage-database/downloads/downloads.aspx\n        type: Downloads\n    description: >-\n      The Medicare Coverage Database publishes National Coverage\n      Determinations (NCDs), Local Coverage Determinations (LCDs),\n      articles, and coding guidance used to determine Medicare coverage\n      and reimbursement policies, distributed via downloadable datasets\n      and JSON/CSV query endpoints.\ncommon:\n  - type: Website\n    url: https://www.cms.gov/\n  - type: Developer\n    url: https://developer.cms.gov/\n  - type:\
  \ OpenData\n    url: https://data.cms.gov/\n  - type: ProviderData\n    url: https://data.cms.gov/provider-data/\n  - type: BlueButton\n    url: https://bluebutton.cms.gov/\n  - type: BCDA\n    url: https://bcda.cms.gov/\n  - type: DPC\n    url: https://dpc.cms.gov/\n  - type: NPPES\n    url: https://npiregistry.cms.hhs.gov/\n  - type: Marketplace\n    url: https://www.healthcare.gov/developers/\n  - type: QPP\n    url: https://qpp.cms.gov/\n  - type: GitHubOrganization\n    url: https://github.com/CMSgov\n  - type: Privacy Policy\n    url: https://www.cms.gov/privacy\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/centers-for-medicare-and-medicaid-services/refs/heads/main/apis.yml
tags:
- BCDA
- Blue Button
- CMS
- Claims
- DPC
- FHIR
- Federal Government
- Healthcare
- Interoperability
- Marketplace
- Medicaid
- Medicare
- Open Data
- Provider Data
- Socrata
url: https://raw.githubusercontent.com/api-evangelist/centers-for-medicare-and-medicaid-services/refs/heads/main/apis.yml
use_cases: []
---
