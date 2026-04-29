---
api_count: 1
api_specs:
- filename: abortion-policy-api-openapi.yml
  format: yaml
  label: Abortion Policy API
  slug: abortion-policy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abortion-policy-api/refs/heads/main/openapi/abortion-policy-api-openapi.yml
apis:
- description: The Abortion Policy API consolidates US state abortion laws into one database for third-party developers to use. Data tables include gestational limits, insurance coverage, minors restrictions, and wa
  name: Abortion Policy API
  slug: abortion-policy-api
capabilities:
- description: Unified workflow for looking up US state abortion policies across gestational limits, insurance coverage, minors restrictions, and waiting periods. Designed for healthcare providers, patient advocates
  name: Abortion Policy Lookup
  slug: abortion-policy-lookup
common:
- title: ''
  type: GettingStarted
  url: https://www.abortionpolicyapi.com/
- title: ''
  type: Authentication
  url: https://www.abortionpolicyapi.com/request-access
- title: ''
  type: APIReference
  url: https://www.abortionpolicyapi.com/field-references
- title: ''
  type: CaseStudies
  url: https://www.abortionpolicyapi.com/case-studies
- title: ''
  type: Support
  url: https://www.abortionpolicyapi.com/contact
- title: ''
  type: TermsOfService
  url: https://www.abortionpolicyapi.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.abortionpolicyapi.com/privacy
- title: ''
  type: RateLimits
  url: ''
- title: ''
  type: SpectralRules
  url: rules/abortion-policy-api-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/abortion-policy-lookup.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/abortion-policy-api.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/abortion-policy-api-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/abortion-policy-api-context.jsonld
created: '2025-01-07'
description: The Abortion Policy API provides up-to-date information on US state abortion policies that can be integrated into online abortion resources. The API consolidates abortion laws into one database across four data tables covering gestational limits, insurance coverage, minors restrictions, and waiting periods. Data is accessible by US state name or zip code. The project is co-led by Patient Forward and is fiscally sponsored by NEO Philanthropy.
features:
- description: State-by-state gestational limit policies including exceptions for life, health, fetal anomaly, and rape/incest.
  name: Gestational Limits Data
- description: Comprehensive insurance coverage restrictions covering Medicaid, private insurance, and ACA exchange plans by state.
  name: Insurance Coverage Data
- description: Parental consent, notification, and judicial bypass requirements for minors seeking abortion by state.
  name: Minors Restrictions Data
- description: State mandatory waiting period hours and counseling visit requirements between counseling and abortion care.
  name: Waiting Periods Data
- description: All policy data accessible by US state name or 5-digit zip code for integration flexibility.
  name: State and Zip Code Lookup
- description: Data collaboratively analyzed by reproductive rights experts from Guttmacher, Planned Parenthood, Power to Decide, CRR, and others.
  name: Expert-Curated Data
- description: API provided free without gatekeeping as a public good resource for reproductive health organizations.
  name: Free Public Good
image: /assets/icons/abortion-policy-api.png
integrations:
- description: Used by Planned Parenthood for patient-facing abortion policy information.
  name: Planned Parenthood
- description: Powers policy data in the Abortion Finder patient resource tool.
  name: Abortion Finder
- description: Integrated into Charley the Chatbot for conversational abortion policy guidance.
  name: Charley the Chatbot
- description: Powers policy data for ineedana.com abortion access resource.
  name: Ineedana.com
- description: Available as an independent publisher connector for Power Apps, Power Automate, Logic Apps, and Copilot Studio.
  name: Microsoft Power Platform
jsonld:
- class_count: 4
  name: Abortion Policy Api Context
  property_count: 33
  slug: abortion-policy-api-context
layout: provider
modified: '2026-04-19'
name: Abortion Policy API
rules:
- name: Abortion Policy API API Rules
  rule_count: 32
  severity_counts:
    error: 16
    hint: 0
    info: 1
    warn: 15
  slug: abortion-policy-api-spectral-rules
skills: []
slug: abortion-policy-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: abortion-policy-api\nurl: https://raw.githubusercontent.com/api-evangelist/abortion-policy-api/refs/heads/main/apis.yml\nname: Abortion Policy API\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Abortion\n  - Policies\n  - Healthcare\n  - Government\ndescription: >-\n  The Abortion Policy API provides up-to-date information on US state abortion\n  policies that can be integrated into online abortion resources. The API consolidates\n  abortion laws into one database across four data tables covering gestational limits,\n  insurance coverage, minors restrictions, and waiting periods. Data is accessible by\n  US state name or zip code. The project is co-led by Patient Forward and is fiscally\n  sponsored by NEO Philanthropy.\ncreated: '2025-01-07'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: abortion-policy-api:abortion-policy-api\n    name: Abortion Policy API\n    tags:\n      - Abortion\n\
  \      - Policies\n      - Healthcare\n    humanURL: https://www.abortionpolicyapi.com/\n    properties:\n      - type: Documentation\n        url: https://www.abortionpolicyapi.com/\n      - type: Authentication\n        url: https://www.abortionpolicyapi.com/request-access\n      - type: APIReference\n        url: https://www.abortionpolicyapi.com/field-references\n      - type: OpenAPI\n        url: openapi/abortion-policy-api-openapi.yml\n      - type: CodeExamples\n        url: https://github.com/alexanian/abortion-policy-api-examples\n        title: Python/JavaScript Examples\n      - type: JSONSchema\n        url: json-schema/gestational-limits-schema.json\n        title: Gestational Limits Schema\n      - type: JSONSchema\n        url: json-schema/insurance-coverage-schema.json\n        title: Insurance Coverage Schema\n      - type: JSONSchema\n        url: json-schema/minors-restrictions-schema.json\n        title: Minors Restrictions Schema\n      - type: JSONSchema\n      \
  \  url: json-schema/waiting-periods-schema.json\n        title: Waiting Periods Schema\n    description: >-\n      The Abortion Policy API consolidates US state abortion laws into one database\n      for third-party developers to use. Data tables include gestational limits,\n      insurance coverage, minors restrictions, and waiting periods. Access requires\n      requesting an API key. Rate limit is 100 calls per 60 seconds.\ncommon:\n  - type: GettingStarted\n    url: https://www.abortionpolicyapi.com/\n  - type: Authentication\n    url: https://www.abortionpolicyapi.com/request-access\n  - type: APIReference\n    url: https://www.abortionpolicyapi.com/field-references\n  - type: CaseStudies\n    url: https://www.abortionpolicyapi.com/case-studies\n  - type: Support\n    url: https://www.abortionpolicyapi.com/contact\n  - type: TermsOfService\n    url: https://www.abortionpolicyapi.com/terms\n  - type: PrivacyPolicy\n    url: https://www.abortionpolicyapi.com/privacy\n  - type: RateLimits\n\
  \    data:\n      - name: API Calls Per Connection\n        description: 100 calls per 60 seconds per connection\n  - type: Features\n    data:\n      - name: Gestational Limits Data\n        description: State-by-state gestational limit policies including exceptions for life, health, fetal anomaly, and rape/incest.\n      - name: Insurance Coverage Data\n        description: Comprehensive insurance coverage restrictions covering Medicaid, private insurance, and ACA exchange plans by state.\n      - name: Minors Restrictions Data\n        description: Parental consent, notification, and judicial bypass requirements for minors seeking abortion by state.\n      - name: Waiting Periods Data\n        description: State mandatory waiting period hours and counseling visit requirements between counseling and abortion care.\n      - name: State and Zip Code Lookup\n        description: All policy data accessible by US state name or 5-digit zip code for integration flexibility.\n      - name: Expert-Curated\
  \ Data\n        description: Data collaboratively analyzed by reproductive rights experts from Guttmacher, Planned Parenthood, Power to Decide, CRR, and others.\n      - name: Free Public Good\n        description: API provided free without gatekeeping as a public good resource for reproductive health organizations.\n  - type: UseCases\n    data:\n      - name: Abortion Finder Applications\n        description: Integrate state abortion policy data into patient-facing tools that help people find abortion services.\n      - name: Healthcare Provider Tools\n        description: Embed policy data into clinical tools to help providers advise patients on state-specific access restrictions.\n      - name: Journalism and Research\n        description: Access structured policy data for data journalism, academic research, and policy analysis.\n      - name: Advocacy and Education\n        description: Power public education tools and advocacy platforms with accurate, up-to-date abortion policy information.\n\
  \      - name: Chatbot Integration\n        description: Provide abortion policy answers in conversational tools like Charley the Chatbot.\n      - name: Legal Aid Resources\n        description: Support legal aid organizations with accurate state law data for advising clients on abortion access.\n  - type: Integrations\n    data:\n      - name: Planned Parenthood\n        description: Used by Planned Parenthood for patient-facing abortion policy information.\n      - name: Abortion Finder\n        description: Powers policy data in the Abortion Finder patient resource tool.\n      - name: Charley the Chatbot\n        description: Integrated into Charley the Chatbot for conversational abortion policy guidance.\n      - name: Ineedana.com\n        description: Powers policy data for ineedana.com abortion access resource.\n      - name: Microsoft Power Platform\n        description: Available as an independent publisher connector for Power Apps, Power Automate, Logic Apps, and Copilot Studio.\n\
  \  - type: SpectralRules\n    url: rules/abortion-policy-api-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/abortion-policy-lookup.yaml\n  - type: NaftikoCapability\n    url: capabilities/shared/abortion-policy-api.yaml\n  - type: Vocabulary\n    url: vocabulary/abortion-policy-api-vocabulary.yaml\n  - type: JSONLD\n    url: json-ld/abortion-policy-api-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/abortion-policy-api/refs/heads/main/apis.yml
tags:
- Abortion
- Policies
- Healthcare
- Government
url: https://raw.githubusercontent.com/api-evangelist/abortion-policy-api/refs/heads/main/apis.yml
use_cases:
- description: Integrate state abortion policy data into patient-facing tools that help people find abortion services.
  name: Abortion Finder Applications
- description: Embed policy data into clinical tools to help providers advise patients on state-specific access restrictions.
  name: Healthcare Provider Tools
- description: Access structured policy data for data journalism, academic research, and policy analysis.
  name: Journalism and Research
- description: Power public education tools and advocacy platforms with accurate, up-to-date abortion policy information.
  name: Advocacy and Education
- description: Provide abortion policy answers in conversational tools like Charley the Chatbot.
  name: Chatbot Integration
- description: Support legal aid organizations with accurate state law data for advising clients on abortion access.
  name: Legal Aid Resources
---
