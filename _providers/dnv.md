---
api_count: 3
api_specs:
- filename: dnv-class-status-openapi.yml
  format: yaml
  label: DNV Class Status API
  slug: dnv-class-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/openapi/dnv-class-status-openapi.yml
apis:
- description: DNV's Class Status API provides programmatic access to vessel classification data. Authentication uses OAuth 2.0 with Azure AD B2C as the identity provider. Access tokens are obtained from https://log
  name: DNV Class Status API
  slug: dnv-class-status-api
- description: DNV Veracity is an open and secure industry data platform facilitating exchange of datasets, APIs, applications, and insights across maritime, oil and gas, and energy sectors. Veracity APIs enable acc
  name: DNV Veracity Platform API
  slug: dnv-veracity-api
- description: DNV Vessel Register provides access to DNV's public registry of classified vessels including vessel identification, classification status, certificates, and survey history. The register supports fleet
  name: DNV Vessel Register
  slug: dnv-vessel-register-api
common:
- title: ''
  type: Website
  url: https://www.dnv.com/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/openapi/dnv-class-status-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/json-schema/dnv-vessel-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/json-ld/dnv-context.jsonld
- title: ''
  type: Portal
  url: https://www.veracity.com/
- title: ''
  type: Documentation
  url: https://developer.veracity.com/docs/section/api-explorer/api-explorer
- title: ''
  type: Authentication
  url: https://maritime.dnv.com/api/cs-iacs-customer
- title: ''
  type: Support
  url: https://help-center.veracity.com/en/
- title: ''
  type: Support
  url: https://support.veracity.com/
- title: ''
  type: PrivacyPolicy
  url: https://www.dnv.com/privacy/
- title: ''
  type: TermsOfService
  url: https://www.dnv.com/terms/
- title: ''
  type: Status
  url: https://vesselregister.dnv.com/vesselregister
- title: ''
  type: GettingStarted
  url: https://www.dnv.com/maritime/
created: ''
description: DNV is a global classification, certification, and assurance provider for the maritime, energy, and industrial sectors. The API portfolio includes the Class Status API for vessel classification data, the Veracity industry data platform, and the public Vessel Register, supporting fleet management, regulatory compliance, and operational analytics workflows.
features: []
image: ''
integrations: []
jsonld:
- class_count: 1
  name: Dnv Context
  property_count: 22
  slug: dnv-context
layout: provider
modified: '2026-04-28'
name: DNV
skills: []
slug: dnv
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dnv\nurl: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/apis.yml\napis:\n  - aid: dnv:dnv-class-status-api\n    name: DNV Class Status API\n    tags:\n      - Azure AD\n      - Classification\n      - Maritime\n      - OAuth2\n      - Safety\n      - Vessel\n    image: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/image.png\n    humanURL: https://maritime.dnv.com/api/cs-iacs-customer\n    baseURL: https://maritime.dnv.com/api/cs-iacs-customer\n    properties:\n      - url: https://maritime.dnv.com/api/cs-iacs-customer/docs/index.html\n        type: Reference\n      - url: https://maritime.dnv.com/api/cs-iacs-customer\n        type: Documentation\n      - url: https://maritime.dnv.com/api/cs-iacs-customer\n        type: Authentication\n      - url: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/openapi/dnv-class-status-openapi.yml\n        type: OpenAPI\n    description: >-\n      DNV's Class Status API\
  \ provides programmatic access to vessel classification\n      data. Authentication uses OAuth 2.0 with Azure AD B2C as the identity provider.\n      Access tokens are obtained from https://login.microsoftonline.com/dnvglb2cprod.onmicrosoft.com/oauth2/token\n      and are valid for approximately 20 minutes. Access requires a separate API contract\n      with DNV.\n  - aid: dnv:dnv-veracity-api\n    name: DNV Veracity Platform API\n    tags:\n      - Analytics\n      - Data Platform\n      - Energy\n      - IoT\n      - Maritime\n    image: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/image.png\n    humanURL: https://www.veracity.com/\n    baseURL: https://api.veracity.com\n    properties:\n      - url: https://developer.veracity.com/docs/section/api-explorer/api-explorer\n        type: Documentation\n      - url: https://developer.veracity.com/docs/section/datastandards/operationalvesseldata\n        type: Reference\n      - url: https://www.veracity.com/\n    \
  \    type: Portal\n    description: >-\n      DNV Veracity is an open and secure industry data platform facilitating exchange\n      of datasets, APIs, applications, and insights across maritime, oil and gas,\n      and energy sectors. Veracity APIs enable access to operational vessel data,\n      maritime analytics, and fleet management services for over 18,000 companies\n      and 200,000 users.\n  - aid: dnv:dnv-vessel-register-api\n    name: DNV Vessel Register\n    tags:\n      - Classification\n      - Fleet Management\n      - Maritime\n      - Vessel Registry\n    image: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/image.png\n    humanURL: https://vesselregister.dnv.com/vesselregister\n    baseURL: https://vesselregister.dnv.com\n    properties:\n      - url: https://vesselregister.dnv.com/vesselregister\n        type: Documentation\n    description: >-\n      DNV Vessel Register provides access to DNV's public registry of classified vessels\n      including\
  \ vessel identification, classification status, certificates, and survey\n      history. The register supports fleet management and regulatory compliance workflows.\ncommon:\n  - url: https://www.dnv.com/\n    type: Website\n  - url: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/openapi/dnv-class-status-openapi.yml\n    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/json-schema/dnv-vessel-schema.json\n    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/json-ld/dnv-context.jsonld\n    type: JSONLDContext\n  - url: https://www.veracity.com/\n    type: Portal\n  - url: https://developer.veracity.com/docs/section/api-explorer/api-explorer\n    type: Documentation\n  - url: https://maritime.dnv.com/api/cs-iacs-customer\n    type: Authentication\n  - url: https://help-center.veracity.com/en/\n    type: Support\n  - url: https://support.veracity.com/\n    type: Support\n  - url:\
  \ https://www.dnv.com/privacy/\n    type: PrivacyPolicy\n  - url: https://www.dnv.com/terms/\n    type: TermsOfService\n  - url: https://vesselregister.dnv.com/vesselregister\n    type: Status\n  - url: https://www.dnv.com/maritime/\n    type: GettingStarted\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\nmodified: '2026-04-28'\nname: DNV\ntags:\n  - Maritime\n  - Energy\n  - Classification\n  - Vessel\n  - Data Platform\ndescription: >-\n  DNV is a global classification, certification, and assurance provider for the\n  maritime, energy, and industrial sectors. The API portfolio includes the Class\n  Status API for vessel classification data, the Veracity industry data platform,\n  and the public Vessel Register, supporting fleet management, regulatory compliance,\n  and operational analytics workflows.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/apis.yml
tags:
- Maritime
- Energy
- Classification
- Vessel
- Data Platform
url: https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/apis.yml
use_cases: []
---
