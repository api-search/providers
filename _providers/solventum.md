---
api_count: 2
apis:
- description: Solventum's Health Information Systems (formerly 3M HIS) provides APIs for clinical documentation, coding and grouping, computer-assisted coding (CAC), revenue cycle management, and healthcare analyti
  name: Solventum Health Information Systems API
  slug: health-information-systems
- description: APIs supporting computer-assisted clinical documentation improvement (CDI) workflows, providing real-time query generation, physician query management, and documentation quality analysis to improve sp
  name: Solventum Clinical Documentation Improvement API
  slug: clinical-documentation-improvement
common:
- title: ''
  type: Website
  url: https://www.solventum.com
- title: ''
  type: Documentation
  url: https://www.solventum.com/en-us/home/health-information-systems/
- title: ''
  type: Blog
  url: https://www.solventum.com/en-us/home/about-solventum/newsroom/
- title: ''
  type: Investors
  url: https://investors.solventum.com/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/solventum/
- title: ''
  type: Support
  url: https://www.solventum.com/en-us/home/contact-us/
- title: ''
  type: PrivacyPolicy
  url: https://www.solventum.com/en-us/home/privacy/
- title: ''
  type: TermsOfService
  url: https://www.solventum.com/en-us/home/terms-of-use/
created: '2026-03-21'
description: Solventum is a Fortune 500 healthcare company spun off from 3M in 2024, focused on healthcare technology including medical-surgical solutions, dental and orthodontic products, health information systems, and purification and filtration technologies. Solventum serves hospitals, clinics, dental practices, and healthcare IT organizations worldwide.
features:
- description: AI-powered ICD-10, CPT, and DRG coding from clinical documentation.
  name: Computer-Assisted Coding
- description: Real-time CDI queries and documentation quality analysis.
  name: Clinical Documentation Improvement
- description: Diagnosis-related group calculation for inpatient reimbursement.
  name: DRG Grouping
- description: End-to-end revenue cycle analytics and workflow tools.
  name: Revenue Cycle Management
- description: Native integration with Epic, Cerner, Oracle Health, and other EHR systems.
  name: EHR Integration
- description: Clinical and financial analytics for quality and performance reporting.
  name: Healthcare Analytics
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native integration with Epic EHR for embedded coding workflows.
  name: Epic
- description: Integration with Cerner/Oracle Health for clinical documentation.
  name: Oracle Health (Cerner)
- description: Integration with MEDITECH EHR platform.
  name: MEDITECH
- description: FHIR-based data exchange for interoperability.
  name: HL7 FHIR
- description: ICD-10-CM/PCS coding standard support.
  name: ICD-10
- description: Current Procedural Terminology coding support.
  name: CPT
jsonld:
- class_count: 1
  name: Solventum Context
  property_count: 6
  slug: solventum-context
layout: provider
modified: '2026-05-02'
name: Solventum
skills: []
slug: solventum
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: solventum\nname: Solventum\ndescription: >-\n  Solventum is a Fortune 500 healthcare company spun off from 3M in 2024,\n  focused on healthcare technology including medical-surgical solutions,\n  dental and orthodontic products, health information systems, and purification\n  and filtration technologies. Solventum serves hospitals, clinics, dental\n  practices, and healthcare IT organizations worldwide.\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Dental\n  - EHR\n  - Electronic Health Records\n  - Healthcare\n  - Healthcare IT\n  - Health Information Systems\n  - Medical Devices\n  - Medical Technology\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/solventum/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: solventum:health-information-systems\n    name: Solventum Health Information Systems API\n    description: >-\n     \
  \ Solventum's Health Information Systems (formerly 3M HIS) provides APIs\n      for clinical documentation, coding and grouping, computer-assisted coding\n      (CAC), revenue cycle management, and healthcare analytics. These APIs\n      integrate with EHR systems such as Epic, Cerner, and Oracle Health to\n      support clinical coding, DRG grouping, and quality reporting.\n    humanURL: https://www.solventum.com/en-us/home/health-information-systems/\n    tags:\n      - CAC\n      - Clinical Coding\n      - DRG Grouping\n      - EHR Integration\n      - Health Information Systems\n      - Healthcare Analytics\n      - ICD-10\n      - Revenue Cycle\n    properties:\n      - type: Documentation\n        url: https://www.solventum.com/en-us/home/health-information-systems/\n      - type: APIReference\n        url: https://developer.solventum.com/\n\n  - aid: solventum:clinical-documentation-improvement\n    name: Solventum Clinical Documentation Improvement API\n    description: >-\n  \
  \    APIs supporting computer-assisted clinical documentation improvement\n      (CDI) workflows, providing real-time query generation, physician\n      query management, and documentation quality analysis to improve\n      specificity, accuracy, and completeness of clinical documentation.\n    humanURL: https://www.solventum.com/en-us/home/health-information-systems/clinical-documentation-integrity/\n    tags:\n      - CDI\n      - Clinical Documentation\n      - Clinical Documentation Improvement\n      - Healthcare IT\n      - Physician Query\n    properties:\n      - type: Documentation\n        url: https://www.solventum.com/en-us/home/health-information-systems/clinical-documentation-integrity/\n\ncommon:\n  - type: Website\n    url: https://www.solventum.com\n  - type: Documentation\n    url: https://www.solventum.com/en-us/home/health-information-systems/\n  - type: Blog\n    url: https://www.solventum.com/en-us/home/about-solventum/newsroom/\n  - type: Investors\n    url: https://investors.solventum.com/\n\
  \  - type: LinkedIn\n    url: https://www.linkedin.com/company/solventum/\n  - type: Support\n    url: https://www.solventum.com/en-us/home/contact-us/\n  - type: PrivacyPolicy\n    url: https://www.solventum.com/en-us/home/privacy/\n  - type: TermsOfService\n    url: https://www.solventum.com/en-us/home/terms-of-use/\n  - type: Features\n    data:\n      - name: Computer-Assisted Coding\n        description: AI-powered ICD-10, CPT, and DRG coding from clinical documentation.\n      - name: Clinical Documentation Improvement\n        description: Real-time CDI queries and documentation quality analysis.\n      - name: DRG Grouping\n        description: Diagnosis-related group calculation for inpatient reimbursement.\n      - name: Revenue Cycle Management\n        description: End-to-end revenue cycle analytics and workflow tools.\n      - name: EHR Integration\n        description: Native integration with Epic, Cerner, Oracle Health, and other EHR systems.\n      - name: Healthcare Analytics\n\
  \        description: Clinical and financial analytics for quality and performance reporting.\n  - type: UseCases\n    data:\n      - name: Inpatient Coding\n        description: Automate ICD-10-CM/PCS coding for inpatient encounters.\n      - name: Outpatient Coding\n        description: Automate CPT and ICD-10-CM coding for outpatient and ambulatory encounters.\n      - name: Quality Reporting\n        description: Generate CMS quality measure data for value-based care programs.\n      - name: Revenue Optimization\n        description: Identify missed revenue opportunities through coding accuracy analysis.\n      - name: Clinical Documentation\n        description: Improve physician documentation specificity for accurate reimbursement.\n  - type: Integrations\n    data:\n      - name: Epic\n        description: Native integration with Epic EHR for embedded coding workflows.\n      - name: Oracle Health (Cerner)\n        description: Integration with Cerner/Oracle Health for clinical\
  \ documentation.\n      - name: MEDITECH\n        description: Integration with MEDITECH EHR platform.\n      - name: HL7 FHIR\n        description: FHIR-based data exchange for interoperability.\n      - name: ICD-10\n        description: ICD-10-CM/PCS coding standard support.\n      - name: CPT\n        description: Current Procedural Terminology coding support.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/solventum/refs/heads/main/apis.yml
tags:
- Dental
- EHR
- Electronic Health Records
- Healthcare
- Healthcare IT
- Health Information Systems
- Medical Devices
- Medical Technology
url: https://raw.githubusercontent.com/api-evangelist/solventum/refs/heads/main/apis.yml
use_cases:
- description: Automate ICD-10-CM/PCS coding for inpatient encounters.
  name: Inpatient Coding
- description: Automate CPT and ICD-10-CM coding for outpatient and ambulatory encounters.
  name: Outpatient Coding
- description: Generate CMS quality measure data for value-based care programs.
  name: Quality Reporting
- description: Identify missed revenue opportunities through coding accuracy analysis.
  name: Revenue Optimization
- description: Improve physician documentation specificity for accurate reimbursement.
  name: Clinical Documentation
---
