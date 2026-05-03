---
api_count: 4
apis:
- description: The TANF Data Portal (TDP) is a secure, web-based data reporting system for state agencies to submit Temporary Assistance for Needy Families (TANF) program data to ACF. It provides data submission wor
  name: TANF Data Portal
  slug: tanf-data-portal
- description: ACF's initiative to develop interoperability standards for human services programs using HL7 FHIR and USCDI+ (United States Core Data for Interoperability Plus). Aims to enable data sharing between so
  name: ACF Human Services Interoperability Initiative
  slug: acf-interoperability
- description: NDACAN is the central repository for datasets related to child abuse, neglect, and child welfare at Cornell University, funded by ACF. Provides access to AFCARS (foster care/adoption), NCANDS (child a
  name: National Data Archive on Child Abuse and Neglect
  slug: ndacan
- description: ACF's primary data and research portal providing access to program data, statistical reports, and research findings across all ACF program offices. Includes TANF caseload data, CCDF data, Head Start p
  name: ACF Data and Research Portal
  slug: acf-data-research
common:
- title: ''
  type: Website
  url: https://www.acf.hhs.gov/
- title: ''
  type: Documentation
  url: https://acf.gov/acf-data-research
- title: ''
  type: Data Portal
  url: https://tanfdata.acf.hhs.gov/
- title: ''
  type: GitHub Organization
  url: https://github.com/HHS
- title: ''
  type: Data Catalog
  url: https://catalog.data.gov/organization/hhs-acf
- title: ''
  type: Interoperability
  url: https://acf.gov/about/interoperability
- title: ''
  type: JSONSchema
  url: json-schema/acf-child-welfare-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/acf-tanf-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/acf-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/acf-vocabulary.yml
created: '2024-11-20T00:00:00.000Z'
description: The Administration for Children and Families (ACF) is a division of the U.S. Department of Health and Human Services dedicated to promoting the economic and social well-being of children, families, and communities. ACF administers programs including TANF (cash assistance), CCDF (child care), Head Start, LIHEAP (energy assistance), child welfare, and refugee assistance. ACF collects administrative data via systems including AFCARS (foster care and adoption), NCANDS (child abuse and neglect), NYTD (youth in transition), TANF data reporting, and CCDF data. ACF is pursuing interoperability standards using HL7 FHIR and USCDI+ for human services data exchange. The TANF Data Portal (tanfdata.acf.hhs.gov) provides state agencies with a data submission and analysis interface.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 7
  name: Acf Context
  property_count: 21
  slug: acf-context
layout: provider
modified: '2026-05-03'
name: The Administration for Children and Families
skills: []
slug: the-administration-for-children-and-families
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: the-administration-for-children-and-families\nname: The Administration for Children and Families\ndescription: >-\n  The Administration for Children and Families (ACF) is a division of the\n  U.S. Department of Health and Human Services dedicated to promoting the\n  economic and social well-being of children, families, and communities.\n  ACF administers programs including TANF (cash assistance), CCDF (child\n  care), Head Start, LIHEAP (energy assistance), child welfare, and\n  refugee assistance. ACF collects administrative data via systems including\n  AFCARS (foster care and adoption), NCANDS (child abuse and neglect),\n  NYTD (youth in transition), TANF data reporting, and CCDF data. ACF is\n  pursuing interoperability standards using HL7 FHIR and USCDI+ for\n  human services data exchange. The TANF Data Portal (tanfdata.acf.hhs.gov)\n  provides state agencies with a data submission and analysis interface.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  tags:\n  - Children\n  - Families\n  - Federal Government\n  - Health And Human Services\n  - Human Services\n  - Social Safety Net\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/the-administration-for-children-and-families/refs/heads/main/apis.yml\ncreated: '2024-11-20T00:00:00.000Z'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: the-administration-for-children-and-families:tanf-data-portal\n    name: TANF Data Portal\n    description: >-\n      The TANF Data Portal (TDP) is a secure, web-based data reporting\n      system for state agencies to submit Temporary Assistance for Needy\n      Families (TANF) program data to ACF. It provides data submission\n      workflows, validation, and reporting capabilities. The system is\n      built on a Django/React stack hosted on Cloud.gov.\n    humanURL: https://tanfdata.acf.hhs.gov/\n    baseURL: https://tanfdata.acf.hhs.gov/\n    tags:\n      - Federal Government\n      - Human Services\n      - TANF\n  \
  \  properties:\n      - type: Documentation\n        url: https://tanfdata.acf.hhs.gov/\n      - type: GitHubRepository\n        url: https://github.com/HHS/TANF-app\n  - aid: the-administration-for-children-and-families:acf-interoperability\n    name: ACF Human Services Interoperability Initiative\n    description: >-\n      ACF's initiative to develop interoperability standards for human\n      services programs using HL7 FHIR and USCDI+ (United States Core\n      Data for Interoperability Plus). Aims to enable data sharing\n      between social services, health, and other human services systems\n      to support integrated care coordination for children and families.\n    humanURL: https://acf.gov/about/interoperability\n    baseURL: https://acf.gov/\n    tags:\n      - FHIR\n      - Federal Government\n      - Human Services\n      - Interoperability\n    properties:\n      - type: Documentation\n        url: https://acf.gov/about/interoperability\n  - aid: the-administration-for-children-and-families:ndacan\n\
  \    name: National Data Archive on Child Abuse and Neglect\n    description: >-\n      NDACAN is the central repository for datasets related to child abuse,\n      neglect, and child welfare at Cornell University, funded by ACF.\n      Provides access to AFCARS (foster care/adoption), NCANDS (child abuse\n      and neglect), and NYTD (youth in transition) datasets for research\n      purposes. Includes data codebooks and user guides.\n    humanURL: https://www.ndacan.acf.hhs.gov/\n    baseURL: https://www.ndacan.acf.hhs.gov/\n    tags:\n      - Child Welfare\n      - Data Archive\n      - Federal Government\n      - Research\n    properties:\n      - type: Documentation\n        url: https://www.ndacan.acf.hhs.gov/\n  - aid: the-administration-for-children-and-families:acf-data-research\n    name: ACF Data and Research Portal\n    description: >-\n      ACF's primary data and research portal providing access to program\n      data, statistical reports, and research findings across all\
  \ ACF\n      program offices. Includes TANF caseload data, CCDF data, Head Start\n      program data, and child welfare statistics.\n    humanURL: https://acf.gov/acf-data-research\n    baseURL: https://acf.gov/\n    tags:\n      - Data\n      - Federal Government\n      - Research\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://acf.gov/acf-data-research\n      - type: Dataset\n        url: https://catalog.data.gov/organization/hhs-acf\ncommon:\n  - type: Website\n    url: https://www.acf.hhs.gov/\n  - type: Documentation\n    url: https://acf.gov/acf-data-research\n  - type: Data Portal\n    url: https://tanfdata.acf.hhs.gov/\n  - type: GitHub Organization\n    url: https://github.com/HHS\n  - type: Data Catalog\n    url: https://catalog.data.gov/organization/hhs-acf\n  - type: Interoperability\n    url: https://acf.gov/about/interoperability\n  - type: JSONSchema\n    url: json-schema/acf-child-welfare-schema.json\n  - type: JSONSchema\n    url:\
  \ json-schema/acf-tanf-schema.json\n  - type: JSON-LD\n    url: json-ld/acf-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/acf-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/the-administration-for-children-and-families/refs/heads/main/apis.yml
tags:
- Children
- Families
- Federal Government
- Health And Human Services
- Human Services
- Social Safety Net
url: https://raw.githubusercontent.com/api-evangelist/the-administration-for-children-and-families/refs/heads/main/apis.yml
use_cases: []
---
