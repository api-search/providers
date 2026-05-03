---
api_count: 2
api_specs:
- filename: pointclickcare-ehr-openapi.yml
  format: yaml
  label: PointClickCare Long-Term Care EHR API
  slug: pointclickcare-ehr-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pointclickcare/refs/heads/main/openapi/pointclickcare-ehr-openapi.yml
apis:
- description: PointClickCare provides EHR and care coordination APIs for long-term and post-acute care facilities. APIs enable access to resident records, medication administration, clinical assessments, and care p
  name: PointClickCare Long-Term Care EHR API
  slug: pointclickcare-ehr-api
- description: PointClickCare FHIR API provides HL7 FHIR-compliant access to resident clinical data for post-acute and long-term care settings, supporting interoperability with other healthcare systems and care coor
  name: PointClickCare FHIR API
  slug: pointclickcare-fhir-api
common:
- title: ''
  type: Portal
  url: https://developer.pointclickcare.com/spa
- title: ''
  type: Documentation
  url: https://developer.pointclickcare.com/spa
- title: ''
  type: Website
  url: https://www.pointclickcare.com/
- title: ''
  type: Support
  url: https://pointclickcare.com/customer-support/
- title: ''
  type: Blog
  url: https://pointclickcare.com/blog/
- title: ''
  type: PrivacyPolicy
  url: https://pointclickcare.com/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://pointclickcare.com/legal/terms-conditions/
- title: ''
  type: Status
  url: https://status.pointclickcare.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/PointClickCare
created: '2026-03-18'
description: PointClickCare is the leading cloud-based software platform for the senior care and post-acute care industry, providing electronic health records (EHR), care coordination, financial management, and clinical decision support to skilled nursing facilities, senior living communities, and home health agencies. PointClickCare publishes both a partner EHR API and a HL7 FHIR API for clinical interoperability across the long-term and post-acute care (LTPAC) ecosystem.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Pointclickcare Context
  property_count: 33
  slug: pointclickcare-context
layout: provider
modified: '2026-04-28'
name: PointClickCare
skills: []
slug: pointclickcare
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: pointclickcare\nname: PointClickCare\ndescription: >-\n  PointClickCare is the leading cloud-based software platform for the senior\n  care and post-acute care industry, providing electronic health records (EHR),\n  care coordination, financial management, and clinical decision support to\n  skilled nursing facilities, senior living communities, and home health\n  agencies. PointClickCare publishes both a partner EHR API and a HL7 FHIR API\n  for clinical interoperability across the long-term and post-acute care (LTPAC)\n  ecosystem.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Healthcare\n  - Long-Term Care\n  - Post-Acute Care\n  - EHR\n  - FHIR\n  - Senior Care\n  - Interoperability\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/pointclickcare/refs/heads/main/apis.yml\ncreated: '2026-03-18'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n\
  \  - aid: pointclickcare:pointclickcare-ehr-api\n    name: PointClickCare Long-Term Care EHR API\n    description: >-\n      PointClickCare provides EHR and care coordination APIs for long-term and\n      post-acute care facilities. APIs enable access to resident records,\n      medication administration, clinical assessments, and care plan data for\n      skilled nursing facilities and senior living communities.\n    humanURL: https://developer.pointclickcare.com/spa\n    baseURL: https://api.pointclickcare.com/v2\n    tags:\n      - Healthcare\n      - Long-Term Care\n      - EHR\n      - Senior Care\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.pointclickcare.com/spa\n      - type: Portal\n        url: https://developer.pointclickcare.com/spa\n      - type: OpenAPI\n        url: openapi/pointclickcare-ehr-openapi.yml\n      - type: JSONSchema\n        url: json-schema/pointclickcare-patient-schema.json\n      - type: JSONLDContext\n    \
  \    url: json-ld/pointclickcare-context.jsonld\n  - aid: pointclickcare:pointclickcare-fhir-api\n    name: PointClickCare FHIR API\n    description: >-\n      PointClickCare FHIR API provides HL7 FHIR-compliant access to resident\n      clinical data for post-acute and long-term care settings, supporting\n      interoperability with other healthcare systems and care coordination\n      platforms.\n    humanURL: https://developer.pointclickcare.com/spa\n    tags:\n      - Healthcare\n      - Long-Term Care\n      - FHIR\n      - HL7\n      - Interoperability\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.pointclickcare.com/spa\ncommon:\n  - type: Portal\n    url: https://developer.pointclickcare.com/spa\n  - type: Documentation\n    url: https://developer.pointclickcare.com/spa\n  - type: Website\n    url: https://www.pointclickcare.com/\n  - type: Support\n    url: https://pointclickcare.com/customer-support/\n  - type: Blog\n    url: https://pointclickcare.com/blog/\n\
  \  - type: PrivacyPolicy\n    url: https://pointclickcare.com/privacy-policy/\n  - type: TermsOfService\n    url: https://pointclickcare.com/legal/terms-conditions/\n  - type: Status\n    url: https://status.pointclickcare.com/\n  - type: GitHubOrganization\n    url: https://github.com/PointClickCare\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/pointclickcare/refs/heads/main/apis.yml
tags:
- Healthcare
- Long-Term Care
- Post-Acute Care
- EHR
- FHIR
- Senior Care
- Interoperability
url: https://raw.githubusercontent.com/api-evangelist/pointclickcare/refs/heads/main/apis.yml
use_cases: []
---
