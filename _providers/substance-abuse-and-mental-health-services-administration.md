---
api_count: 3
api_specs:
- filename: samhsa-treatment-locator-openapi.yml
  format: yaml
  label: SAMHSA Behavioral Health Treatment Services Locator API
  slug: samhsa-treatment-locator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/substance-abuse-and-mental-health-services-administration/refs/heads/main/openapi/samhsa-treatment-locator-openapi.yml
apis:
- description: The SAMHSA Treatment Services Locator API provides searchable access to over 14,000 behavioral health treatment facilities across the United States. Search by location, service type, payment options (
  name: SAMHSA Behavioral Health Treatment Services Locator API
  slug: samhsa-treatment-locator-api
- description: SAMHSA's data portal provides access to national and state-level behavioral health statistics including the National Survey on Drug Use and Health (NSDUH), Treatment Episode Data Set (TEDS), and Natio
  name: SAMHSA Data Portal
  slug: samhsa-data-portal
- description: Client-Level Data (CLD) from state mental health agencies on clients receiving state-funded mental health services. Provides data on demographics, diagnoses, services received, and outcomes.
  name: SAMHSA Mental Health Client Level Data
  slug: samhsa-mental-health-atlas
common:
- title: ''
  type: Website
  url: https://www.samhsa.gov
- title: ''
  type: Treatment Locator
  url: https://findtreatment.gov
- title: ''
  type: Data Portal
  url: https://www.samhsa.gov/data/
- title: ''
  type: Data Files
  url: https://www.datafiles.samhsa.gov
- title: ''
  type: National Helpline
  url: https://www.samhsa.gov/find-help/national-helpline
- title: ''
  type: 988 Suicide & Crisis Lifeline
  url: https://988lifeline.org
- title: ''
  type: FAQ
  url: https://www.samhsa.gov/about-us/who-we-are/faq
- title: ''
  type: Terms of Use
  url: https://www.samhsa.gov/data/terms-use
- title: ''
  type: Privacy Policy
  url: https://www.samhsa.gov/privacy
- title: ''
  type: GitHub Organization
  url: https://github.com/samhsa
- title: ''
  type: Data.gov Catalog
  url: https://catalog.data.gov/dataset?organization=samhsa-hhs
- title: ''
  type: API Reference
  url: https://api.data.gov/docs/samhsa/
- title: ''
  type: Vocabulary
  url: vocabulary/samhsa-vocabulary.yml
- title: ''
  type: JSON-LD Context
  url: json-ld/samhsa-context.jsonld
- title: ''
  type: JSON Schema
  url: json-schema/samhsa-treatment-facility-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/samhsa-nsduh-data-schema.json
- title: ''
  type: JSON Structure
  url: json-structure/samhsa-treatment-facility-structure.json
- title: ''
  type: Example
  url: examples/samhsa-search-treatment-facilities-example.json
created: '2024-12-03'
description: The Substance Abuse and Mental Health Services Administration (SAMHSA) is a branch of the U.S. Department of Health and Human Services dedicated to improving the quality and availability of prevention, treatment, and recovery support services for individuals struggling with substance abuse and mental health disorders. SAMHSA provides APIs and open data for the behavioral health treatment services locator, national survey data (NSDUH), treatment episode statistics (TEDS), and state mental health data.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 18
  name: Samhsa Context
  property_count: 18
  slug: samhsa-context
layout: provider
modified: '2026-05-02'
name: Substance Abuse and Mental Health Services Administration
skills: []
slug: substance-abuse-and-mental-health-services-administration
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: substance-abuse-and-mental-health-services-administration\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/substance-abuse-and-mental-health-services-administration/refs/heads/main/apis.yml\napis:\n  - aid: substance-abuse-and-mental-health-services-administration:samhsa-treatment-locator-api\n    name: SAMHSA Behavioral Health Treatment Services Locator API\n    tags:\n      - Treatment Facilities\n      - Behavioral Health\n      - Substance Use Disorders\n      - Mental Health\n      - Open Data\n    humanURL: https://findtreatment.gov\n    properties:\n      - url: https://findtreatment.gov\n        type: Documentation\n      - url: https://www.samhsa.gov/find-help/national-helpline\n        type: National Helpline\n      - url: openapi/samhsa-treatment-locator-openapi.yml\n        type: OpenAPI\n    description: >-\n      The SAMHSA Treatment Services Locator API provides searchable access to over 14,000\n      behavioral health treatment facilities across\
  \ the United States. Search by location,\n      service type, payment options (Medicaid, Medicare, sliding fee, free treatment),\n      and population served. Powers the findtreatment.gov website.\n\n  - aid: substance-abuse-and-mental-health-services-administration:samhsa-data-portal\n    name: SAMHSA Data Portal\n    tags:\n      - Open Data\n      - Survey Data\n      - NSDUH\n      - Statistics\n      - Public Health\n    humanURL: https://www.datafiles.samhsa.gov\n    properties:\n      - url: https://www.datafiles.samhsa.gov\n        type: Documentation\n      - url: https://www.samhsa.gov/data/\n        type: Data Portal\n      - url: https://pdas.samhsa.gov/sapt\n        type: State Data\n    description: >-\n      SAMHSA's data portal provides access to national and state-level behavioral health\n      statistics including the National Survey on Drug Use and Health (NSDUH), Treatment\n      Episode Data Set (TEDS), and National Survey of Substance Abuse Treatment Services (N-SSATS).\n\
  \      Data available for download in SAS, SPSS, and Stata formats.\n\n  - aid: substance-abuse-and-mental-health-services-administration:samhsa-mental-health-atlas\n    name: SAMHSA Mental Health Client Level Data\n    tags:\n      - Mental Health\n      - Client Data\n      - Statistics\n      - Open Data\n    humanURL: https://www.samhsa.gov/data/report/2020-mental-health-client-level-data-cld\n    properties:\n      - url: https://www.samhsa.gov/data/report/2020-mental-health-client-level-data-cld\n        type: Documentation\n    description: >-\n      Client-Level Data (CLD) from state mental health agencies on clients receiving\n      state-funded mental health services. Provides data on demographics, diagnoses,\n      services received, and outcomes.\n\nname: Substance Abuse and Mental Health Services Administration\ntags:\n  - Federal Government\n  - Public Health\n  - Behavioral Health\n  - Substance Use Disorders\n  - Mental Health\n  - Open Data\n  - Healthcare\ntype: Contract\n\
  image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-05-02'\nposition: Consuming\ndescription: >-\n  The Substance Abuse and Mental Health Services Administration (SAMHSA) is a branch of the\n  U.S. Department of Health and Human Services dedicated to improving the quality and availability\n  of prevention, treatment, and recovery support services for individuals struggling with substance\n  abuse and mental health disorders. SAMHSA provides APIs and open data for the behavioral health\n  treatment services locator, national survey data (NSDUH), treatment episode statistics (TEDS),\n  and state mental health data.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - url: https://www.samhsa.gov\n    type: Website\n  - url: https://findtreatment.gov\n    type: Treatment Locator\n  - url: https://www.samhsa.gov/data/\n    type: Data Portal\n  - url:\
  \ https://www.datafiles.samhsa.gov\n    type: Data Files\n  - url: https://www.samhsa.gov/find-help/national-helpline\n    type: National Helpline\n  - url: https://988lifeline.org\n    type: 988 Suicide & Crisis Lifeline\n  - url: https://www.samhsa.gov/about-us/who-we-are/faq\n    type: FAQ\n  - url: https://www.samhsa.gov/data/terms-use\n    type: Terms of Use\n  - url: https://www.samhsa.gov/privacy\n    type: Privacy Policy\n  - url: https://github.com/samhsa\n    type: GitHub Organization\n  - url: https://catalog.data.gov/dataset?organization=samhsa-hhs\n    type: Data.gov Catalog\n  - url: https://api.data.gov/docs/samhsa/\n    type: API Reference\n  - url: vocabulary/samhsa-vocabulary.yml\n    type: Vocabulary\n  - url: json-ld/samhsa-context.jsonld\n    type: JSON-LD Context\n  - url: json-schema/samhsa-treatment-facility-schema.json\n    type: JSON Schema\n  - url: json-schema/samhsa-nsduh-data-schema.json\n    type: JSON Schema\n  - url: json-structure/samhsa-treatment-facility-structure.json\n\
  \    type: JSON Structure\n  - url: examples/samhsa-search-treatment-facilities-example.json\n    type: Example\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/substance-abuse-and-mental-health-services-administration/refs/heads/main/apis.yml
tags:
- Federal Government
- Public Health
- Behavioral Health
- Substance Use Disorders
- Mental Health
- Open Data
- Healthcare
url: https://raw.githubusercontent.com/api-evangelist/substance-abuse-and-mental-health-services-administration/refs/heads/main/apis.yml
use_cases: []
---
