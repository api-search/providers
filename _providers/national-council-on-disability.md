---
api_count: 3
apis:
- description: FOIA-accessible data from the National Council on Disability including performance and results act reports, congressional budget justification reports, financial audit reports, strategic plans, bylaws
  name: National Council on Disability FOIA Data
  slug: ncd-foia-data
- description: Comprehensive archive of NCD policy reports dating back to 1984 covering disability civil rights, healthcare, transportation, employment, housing, financial assistance, and emergency management. Repor
  name: National Council on Disability Policy Reports
  slug: ncd-policy-reports
- description: 'Performance, accountability, and budget data from the National Council on Disability. Includes Annual Performance Reports, Congressional Budget Justification Reports, financial audits, and EEO policy '
  name: National Council on Disability Accountability Reports
  slug: ncd-accountability-data
common:
- title: ''
  type: Vocabulary
  url: vocabulary/ncd-vocabulary.yaml
- title: ''
  type: JSONSchema
  url: json-schema/ncd-policy-report-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/ncd-foia-record-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/ncd-accountability-report-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/ncd-testimony-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/ncd-stakeholder-letter-schema.json
- title: ''
  type: Website
  url: https://www.ncd.gov
- title: ''
  type: Documentation
  url: https://www.ncd.gov/reports/
- title: ''
  type: DataAPI
  url: https://www.ncd.gov/foia/
- title: ''
  type: Contact
  url: https://www.ncd.gov/contact/
- title: ''
  type: PrivacyPolicy
  url: https://www.ncd.gov/privacy-policy/
- title: ''
  type: Newsroom
  url: https://www.ncd.gov/newsroom/
- title: ''
  type: JSONLD
  url: json-ld/ncd-context.jsonld
- title: ''
  type: JSONStructure
  url: json-structure/ncd-policy-report-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/ncd-foia-record-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/ncd-accountability-report-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/ncd-testimony-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/ncd-stakeholder-letter-structure.json
- title: ''
  type: Example
  url: examples/ncd-policy-report-example.json
- title: ''
  type: Example
  url: examples/ncd-foia-record-example.json
- title: ''
  type: Example
  url: examples/ncd-accountability-report-example.json
- title: ''
  type: Example
  url: examples/ncd-testimony-example.json
- title: ''
  type: Example
  url: examples/ncd-stakeholder-letter-example.json
created: '2024-12-03'
description: The National Council on Disability (NCD) is an independent federal agency that advises the President, Congress, and other federal agencies on disability policy and programs. Established in 1978, the NCD promotes equal opportunity, economic self-sufficiency, independent living, and full participation in all areas of society for individuals with disabilities. The agency conducts research, gathers information, and provides recommendations to improve policies, programs, and services. NCD publishes policy reports spanning civil rights, healthcare, transportation, employment, housing, and emergency management for people with disabilities.
features:
- description: Comprehensive archive of NCD policy reports dating back to 1984 covering all areas of disability policy including civil rights, healthcare, employment, housing, and transportation.
  name: Policy Reports Archive
- description: Proactively published collection of NCD documents including bylaws, performance reports, budget justifications, financial audits, and strategic plans available for public download.
  name: FOIA e-Library
- description: Archive of NCD testimony before Congress on disability policy issues, providing insight into legislative advocacy and policy recommendations over time.
  name: Congressional Testimony Archive
- description: Practical toolkits and fact sheets on disability rights and policy topics to help individuals, advocates, and policymakers understand and implement disability-inclusive practices.
  name: Disability Policy Toolkits
- description: Press releases, newsroom updates, and letters to federal agency stakeholders documenting NCD's ongoing policy engagement and recommendations.
  name: Newsroom and Stakeholder Letters
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: NCD's work intersects with the Americans with Disabilities Act guidance provided through ADA.gov maintained by the Department of Justice.
  name: ADA.gov
- description: NCD recommendations inform resources available through federal disability information portals providing access to government benefits and services.
  name: Disability.gov
- description: Federal government open data portal where related disability datasets from agencies like SSA, HHS, and DOL are cataloged and made available for download.
  name: data.gov
- description: NCD federal spending data is publicly accessible through USASpending.gov as part of federal transparency requirements.
  name: USASpending.gov
jsonld:
- class_count: 3
  name: Ncd Context
  property_count: 6
  slug: ncd-context
layout: provider
modified: '2026-04-19'
name: National Council on Disability
skills: []
slug: national-council-on-disability
solutions:
- description: NCD provides independent policy analysis and recommendations to the three branches of government on all matters affecting people with disabilities.
  name: Disability Policy Leadership
- description: NCD monitors federal agency compliance with disability rights laws and makes recommendations for program improvements and new legislation.
  name: Federal Agency Accountability
- description: NCD publishes toolkits, fact sheets, and reports to educate the public and policymakers about disability rights and best practices for inclusion.
  name: Public Education
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: national-council-on-disability\nname: National Council on Disability\ndescription: >-\n  The National Council on Disability (NCD) is an independent federal agency\n  that advises the President, Congress, and other federal agencies on disability\n  policy and programs. Established in 1978, the NCD promotes equal opportunity,\n  economic self-sufficiency, independent living, and full participation in all\n  areas of society for individuals with disabilities. The agency conducts\n  research, gathers information, and provides recommendations to improve\n  policies, programs, and services. NCD publishes policy reports spanning civil\n  rights, healthcare, transportation, employment, housing, and emergency\n  management for people with disabilities.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Disability\n- Federal Government\n- Policy\n- Civil Rights\n- Healthcare\n- Independent Agency\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/national-council-on-disability/refs/heads/main/apis.yml\n\
  created: '2024-12-03'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: national-council-on-disability:ncd-foia-data\n  name: National Council on Disability FOIA Data\n  description: >-\n    FOIA-accessible data from the National Council on Disability including\n    performance and results act reports, congressional budget justification\n    reports, financial audit reports, strategic plans, bylaws, stakeholder\n    letters, and all NCD policy reports. Data is available in PDF, XML, CSV,\n    and ZIP formats through the NCD FOIA e-Library.\n  humanURL: https://www.ncd.gov/foia/\n  baseURL: https://www.ncd.gov\n  tags:\n  - FOIA\n  - Open Data\n  - Government Reports\n  - Policy\n  properties:\n  - type: Documentation\n    url: https://www.ncd.gov/foia/\n  - type: DataAPI\n    url: https://www.ncd.gov/foia/\n- aid: national-council-on-disability:ncd-policy-reports\n  name: National Council on Disability Policy Reports\n  description: >-\n    Comprehensive archive of NCD\
  \ policy reports dating back to 1984 covering\n    disability civil rights, healthcare, transportation, employment, housing,\n    financial assistance, and emergency management. Reports include\n    recommendations to the President, Congress, and federal policymakers on\n    national disability policy.\n  humanURL: https://www.ncd.gov/reports/\n  baseURL: https://www.ncd.gov\n  tags:\n  - Policy Reports\n  - Civil Rights\n  - Healthcare\n  - Employment\n  - Housing\n  - Transportation\n  properties:\n  - type: Documentation\n    url: https://www.ncd.gov/reports/\n  - type: DataAPI\n    url: https://www.ncd.gov/reports/\n- aid: national-council-on-disability:ncd-accountability-data\n  name: National Council on Disability Accountability Reports\n  description: >-\n    Performance, accountability, and budget data from the National Council on\n    Disability. Includes Annual Performance Reports, Congressional Budget\n    Justification Reports, financial audits, and EEO policy statements\n\
  \    providing transparency into agency operations and resource allocation.\n  humanURL: https://www.ncd.gov/accountability/\n  baseURL: https://www.ncd.gov\n  tags:\n  - Accountability\n  - Budget\n  - Performance\n  - Transparency\n  properties:\n  - type: Documentation\n    url: https://www.ncd.gov/accountability/\n  - type: DataAPI\n    url: https://www.ncd.gov/accountability/congressional-budget-justification-reports/\ncommon:\n- type: Vocabulary\n  url: vocabulary/ncd-vocabulary.yaml\n- type: JSONSchema\n  url: json-schema/ncd-policy-report-schema.json\n- type: JSONSchema\n  url: json-schema/ncd-foia-record-schema.json\n- type: JSONSchema\n  url: json-schema/ncd-accountability-report-schema.json\n- type: JSONSchema\n  url: json-schema/ncd-testimony-schema.json\n- type: JSONSchema\n  url: json-schema/ncd-stakeholder-letter-schema.json\n- type: Website\n  url: https://www.ncd.gov\n- type: Documentation\n  url: https://www.ncd.gov/reports/\n- type: DataAPI\n  url: https://www.ncd.gov/foia/\n\
  - type: Contact\n  url: https://www.ncd.gov/contact/\n- type: PrivacyPolicy\n  url: https://www.ncd.gov/privacy-policy/\n- type: Newsroom\n  url: https://www.ncd.gov/newsroom/\n- type: Features\n  data:\n  - name: Policy Reports Archive\n    description: >-\n      Comprehensive archive of NCD policy reports dating back to 1984\n      covering all areas of disability policy including civil rights,\n      healthcare, employment, housing, and transportation.\n  - name: FOIA e-Library\n    description: >-\n      Proactively published collection of NCD documents including bylaws,\n      performance reports, budget justifications, financial audits, and\n      strategic plans available for public download.\n  - name: Congressional Testimony Archive\n    description: >-\n      Archive of NCD testimony before Congress on disability policy issues,\n      providing insight into legislative advocacy and policy recommendations\n      over time.\n  - name: Disability Policy Toolkits\n    description:\
  \ >-\n      Practical toolkits and fact sheets on disability rights and policy\n      topics to help individuals, advocates, and policymakers understand\n      and implement disability-inclusive practices.\n  - name: Newsroom and Stakeholder Letters\n    description: >-\n      Press releases, newsroom updates, and letters to federal agency\n      stakeholders documenting NCD's ongoing policy engagement and\n      recommendations.\n- type: UseCases\n  data:\n  - name: Disability Policy Research\n    description: >-\n      Access NCD's comprehensive reports to research disability policy\n      history, current recommendations, and policy gaps across federal\n      programs and agencies.\n  - name: FOIA Document Retrieval\n    description: >-\n      Submit FOIA requests or access the FOIA e-Library to retrieve\n      agency financial, performance, and operational documents.\n  - name: Legislative Advocacy\n    description: >-\n      Use NCD testimony archives and policy letters as reference\
  \ material\n      for disability rights advocacy and legislative engagement.\n  - name: Federal Agency Compliance\n    description: >-\n      Access NCD recommendations to understand federal agency obligations\n      under disability rights laws including the ADA, Rehabilitation Act,\n      and other statutes.\n  - name: Academic Research\n    description: >-\n      Download NCD policy reports, progress reports, and data for academic\n      research on disability policy, independent living, and civil rights.\n- type: Integrations\n  data:\n  - name: ADA.gov\n    description: >-\n      NCD's work intersects with the Americans with Disabilities Act\n      guidance provided through ADA.gov maintained by the Department of\n      Justice.\n  - name: Disability.gov\n    description: >-\n      NCD recommendations inform resources available through federal\n      disability information portals providing access to government benefits\n      and services.\n  - name: data.gov\n    description: >-\n\
  \      Federal government open data portal where related disability datasets\n      from agencies like SSA, HHS, and DOL are cataloged and made\n      available for download.\n  - name: USASpending.gov\n    description: >-\n      NCD federal spending data is publicly accessible through\n      USASpending.gov as part of federal transparency requirements.\n- type: Solutions\n  data:\n  - name: Disability Policy Leadership\n    description: >-\n      NCD provides independent policy analysis and recommendations to the\n      three branches of government on all matters affecting people with\n      disabilities.\n  - name: Federal Agency Accountability\n    description: >-\n      NCD monitors federal agency compliance with disability rights laws\n      and makes recommendations for program improvements and new\n      legislation.\n  - name: Public Education\n    description: >-\n      NCD publishes toolkits, fact sheets, and reports to educate the\n      public and policymakers about disability\
  \ rights and best practices\n      for inclusion.\n- type: JSONLD\n  url: json-ld/ncd-context.jsonld\n- type: JSONStructure\n  url: json-structure/ncd-policy-report-structure.json\n- type: JSONStructure\n  url: json-structure/ncd-foia-record-structure.json\n- type: JSONStructure\n  url: json-structure/ncd-accountability-report-structure.json\n- type: JSONStructure\n  url: json-structure/ncd-testimony-structure.json\n- type: JSONStructure\n  url: json-structure/ncd-stakeholder-letter-structure.json\n- type: Example\n  url: examples/ncd-policy-report-example.json\n- type: Example\n  url: examples/ncd-foia-record-example.json\n- type: Example\n  url: examples/ncd-accountability-report-example.json\n- type: Example\n  url: examples/ncd-testimony-example.json\n- type: Example\n  url: examples/ncd-stakeholder-letter-example.json\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/national-council-on-disability/refs/heads/main/apis.yml
tags:
- Disability
- Federal Government
- Policy
- Civil Rights
- Healthcare
- Independent Agency
url: https://raw.githubusercontent.com/api-evangelist/national-council-on-disability/refs/heads/main/apis.yml
use_cases:
- description: Access NCD's comprehensive reports to research disability policy history, current recommendations, and policy gaps across federal programs and agencies.
  name: Disability Policy Research
- description: Submit FOIA requests or access the FOIA e-Library to retrieve agency financial, performance, and operational documents.
  name: FOIA Document Retrieval
- description: Use NCD testimony archives and policy letters as reference material for disability rights advocacy and legislative engagement.
  name: Legislative Advocacy
- description: Access NCD recommendations to understand federal agency obligations under disability rights laws including the ADA, Rehabilitation Act, and other statutes.
  name: Federal Agency Compliance
- description: Download NCD policy reports, progress reports, and data for academic research on disability policy, independent living, and civil rights.
  name: Academic Research
---
