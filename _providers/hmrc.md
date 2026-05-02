---
api_count: 5
api_specs:
- filename: hmrc-vat-mtd-openapi.yml
  format: yaml
  label: HMRC VAT (Making Tax Digital) API
  slug: hmrc-vat-mtd-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/openapi/hmrc-vat-mtd-openapi.yml
apis:
- description: 'The HMRC VAT (Making Tax Digital) API enables software to submit VAT returns, retrieve VAT obligations, liabilities, payments, penalties, and customer details in compliance with UK Making Tax Digital '
  name: HMRC VAT (Making Tax Digital) API
  slug: hmrc-vat-mtd-api
- description: The HMRC Self Assessment APIs enable software to submit and manage self assessment tax returns, income sources, and tax calculations for individuals and sole traders under Making Tax Digital for Incom
  name: HMRC Self Assessment API
  slug: hmrc-self-assessment-api
- description: The HMRC PAYE APIs enable payroll software to submit employer payroll data, retrieve tax codes and employee records, and manage PAYE submissions for Real Time Information (RTI) reporting.
  name: HMRC PAYE (Pay As You Earn) API
  slug: hmrc-paye-api
- description: The HMRC Customs Declarations APIs enable customs software to submit import and export declarations, manage authorizations, and integrate with the UK Customs Declaration Service (CDS) for trade compli
  name: HMRC Customs Declarations API
  slug: hmrc-customs-declarations-api
- description: The HMRC Corporation Tax APIs enable accounting software to submit corporation tax returns, retrieve liabilities, manage payments, and access tax calculation data for UK businesses.
  name: HMRC Corporation Tax API
  slug: hmrc-corporation-tax-api
common:
- title: ''
  type: Portal
  url: https://developer.service.hmrc.gov.uk/
- title: ''
  type: Documentation
  url: https://developer.service.hmrc.gov.uk/api-documentation/docs/api
- title: ''
  type: Authentication
  url: https://developer.service.hmrc.gov.uk/api-documentation/docs/authorisation
- title: ''
  type: Getting Started
  url: https://developer.service.hmrc.gov.uk/api-documentation/docs/using-the-hub
- title: ''
  type: Terms of Service
  url: https://www.gov.uk/api-documentation/docs/terms-of-use
- title: ''
  type: Status
  url: https://api-platform-status.production.tax.service.gov.uk/
- title: ''
  type: Support
  url: https://developer.service.hmrc.gov.uk/
- title: ''
  type: Website
  url: https://www.gov.uk/government/organisations/hm-revenue-customs
- title: ''
  type: OpenAPI
  url: openapi/hmrc-vat-mtd-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/hmrc-vat-return-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/hmrc-context.jsonld
created: '2025'
description: HM Revenue and Customs (HMRC) provides over 115 APIs through the HMRC Developer Hub for UK tax compliance including Making Tax Digital for VAT and Income Tax, PAYE, customs declarations, corporation tax, and construction industry scheme. APIs use OAuth 2.0 and support both REST and XML protocols with a sandbox testing environment.
features: []
image: https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/image.png
integrations: []
jsonld:
- class_count: 4
  name: Hmrc Context
  property_count: 21
  slug: hmrc-context
layout: provider
modified: '2026-04-28'
name: HMRC UK Tax Authority
skills: []
slug: hmrc
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: hmrc\nname: HMRC UK Tax Authority\ndescription: >-\n  HM Revenue and Customs (HMRC) provides over 115 APIs through the HMRC\n  Developer Hub for UK tax compliance including Making Tax Digital for VAT\n  and Income Tax, PAYE, customs declarations, corporation tax, and\n  construction industry scheme. APIs use OAuth 2.0 and support both REST\n  and XML protocols with a sandbox testing environment.\nurl: https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/apis.yml\ntype: Index\nimage: https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/image.png\ntags:\n  - Government\n  - Making Tax Digital\n  - Regulatory\n  - Tax\n  - UK\ncreated: '2025'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: hmrc:hmrc-vat-mtd-api\n    name: HMRC VAT (Making Tax Digital) API\n    description: >-\n      The HMRC VAT (Making Tax Digital) API enables software to submit VAT\n      returns, retrieve VAT obligations, liabilities, payments, penalties,\n\
  \      and customer details in compliance with UK Making Tax Digital\n      requirements. Uses OAuth 2.0 authentication with fraud prevention\n      headers required.\n    humanURL: https://developer.service.hmrc.gov.uk/api-documentation/docs/api/service/vat-api/1.0\n    baseURL: https://api.service.hmrc.gov.uk\n    image: https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/image.png\n    tags:\n      - Government\n      - Making Tax Digital\n      - REST\n      - Tax\n      - UK\n      - VAT\n    properties:\n      - type: Documentation\n        url: https://developer.service.hmrc.gov.uk/api-documentation/docs/api/service/vat-api/1.0\n      - type: Reference\n        url: https://developer.service.hmrc.gov.uk/api-documentation/docs/api/service/vat-api/1.0/oas/page\n      - type: Authentication\n        url: https://developer.service.hmrc.gov.uk/api-documentation/docs/authorisation\n      - type: OpenAPI\n        url: openapi/hmrc-vat-mtd-openapi.yml\n\n  - aid: hmrc:hmrc-self-assessment-api\n\
  \    name: HMRC Self Assessment API\n    description: >-\n      The HMRC Self Assessment APIs enable software to submit and manage\n      self assessment tax returns, income sources, and tax calculations for\n      individuals and sole traders under Making Tax Digital for Income Tax.\n    humanURL: https://developer.service.hmrc.gov.uk/api-documentation/docs/api\n    baseURL: https://api.service.hmrc.gov.uk\n    image: https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/image.png\n    tags:\n      - Government\n      - Income Tax\n      - REST\n      - Self Assessment\n      - Tax\n      - UK\n    properties:\n      - type: Documentation\n        url: https://developer.service.hmrc.gov.uk/api-documentation/docs/api\n      - type: Authentication\n        url: https://developer.service.hmrc.gov.uk/api-documentation/docs/authorisation\n\n  - aid: hmrc:hmrc-paye-api\n    name: HMRC PAYE (Pay As You Earn) API\n    description: >-\n      The HMRC PAYE APIs enable payroll software\
  \ to submit employer payroll\n      data, retrieve tax codes and employee records, and manage PAYE\n      submissions for Real Time Information (RTI) reporting.\n    humanURL: https://developer.service.hmrc.gov.uk/api-documentation/docs/api\n    baseURL: https://api.service.hmrc.gov.uk\n    image: https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/image.png\n    tags:\n      - Government\n      - PAYE\n      - Payroll\n      - REST\n      - Tax\n      - UK\n    properties:\n      - type: Documentation\n        url: https://developer.service.hmrc.gov.uk/api-documentation/docs/api\n      - type: Authentication\n        url: https://developer.service.hmrc.gov.uk/api-documentation/docs/authorisation\n\n  - aid: hmrc:hmrc-customs-declarations-api\n    name: HMRC Customs Declarations API\n    description: >-\n      The HMRC Customs Declarations APIs enable customs software to submit\n      import and export declarations, manage authorizations, and integrate\n      with the\
  \ UK Customs Declaration Service (CDS) for trade compliance.\n    humanURL: https://developer.service.hmrc.gov.uk/api-documentation/docs/api\n    baseURL: https://api.service.hmrc.gov.uk\n    image: https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/image.png\n    tags:\n      - Customs\n      - Excise\n      - Government\n      - REST\n      - Tax\n      - UK\n      - XML\n    properties:\n      - type: Documentation\n        url: https://developer.service.hmrc.gov.uk/api-documentation/docs/api\n      - type: Authentication\n        url: https://developer.service.hmrc.gov.uk/api-documentation/docs/authorisation\n\n  - aid: hmrc:hmrc-corporation-tax-api\n    name: HMRC Corporation Tax API\n    description: >-\n      The HMRC Corporation Tax APIs enable accounting software to submit\n      corporation tax returns, retrieve liabilities, manage payments, and\n      access tax calculation data for UK businesses.\n    humanURL: https://developer.service.hmrc.gov.uk/api-documentation/docs/api\n\
  \    baseURL: https://api.service.hmrc.gov.uk\n    image: https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/image.png\n    tags:\n      - Business\n      - Corporation Tax\n      - Government\n      - REST\n      - Tax\n      - UK\n    properties:\n      - type: Documentation\n        url: https://developer.service.hmrc.gov.uk/api-documentation/docs/api\n      - type: Authentication\n        url: https://developer.service.hmrc.gov.uk/api-documentation/docs/authorisation\n\ncommon:\n  - type: Portal\n    url: https://developer.service.hmrc.gov.uk/\n  - type: Documentation\n    url: https://developer.service.hmrc.gov.uk/api-documentation/docs/api\n  - type: Authentication\n    url: https://developer.service.hmrc.gov.uk/api-documentation/docs/authorisation\n  - type: Getting Started\n    url: https://developer.service.hmrc.gov.uk/api-documentation/docs/using-the-hub\n  - type: Terms of Service\n    url: https://www.gov.uk/api-documentation/docs/terms-of-use\n  - type:\
  \ Status\n    url: https://api-platform-status.production.tax.service.gov.uk/\n  - type: Support\n    url: https://developer.service.hmrc.gov.uk/\n  - type: Website\n    url: https://www.gov.uk/government/organisations/hm-revenue-customs\n  - type: OpenAPI\n    url: openapi/hmrc-vat-mtd-openapi.yml\n  - type: JSONSchema\n    url: json-schema/hmrc-vat-return-schema.json\n  - type: JSONLDContext\n    url: json-ld/hmrc-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/apis.yml
tags:
- Government
- Making Tax Digital
- Regulatory
- Tax
- UK
url: https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/apis.yml
use_cases: []
---
