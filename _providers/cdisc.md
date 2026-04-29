---
api_count: 2
apis:
- description: The CDISC Library API is a REST API that delivers CDISC standards metadata to software applications that automate standards-based processes. It uses linked data to provide access to SDTM, ADaM, and ot
  name: CDISC Library API
  slug: cdisc-library-api
- description: CDISC CORE (Checks and Rules Engine) is an open-source rules engine for validating clinical data against CDISC conformance rules. It enables automated validation of SDTM, ADaM, and other study data ar
  name: CDISC CORE (Checks and Rules Engine) API
  slug: cdisc-core-api
common:
- title: ''
  type: Website
  url: https://www.cdisc.org/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cdisc/refs/heads/main/openapi/cdisc-library-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/cdisc/refs/heads/main/json-schema/cdisc-dataset-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/cdisc/refs/heads/main/json-ld/cdisc-context.jsonld
- title: ''
  type: Portal
  url: https://www.cdisc.org/cdisc-library
- title: ''
  type: GettingStarted
  url: https://www.cdisc.org/cdisc-library/getting-started
- title: ''
  type: Documentation
  url: https://www.cdisc.org/cdisc-library/api-documentation
- title: ''
  type: Authentication
  url: https://api.developer.library.cdisc.org/
- title: ''
  type: Support
  url: https://jira.cdisc.org/servicedesk/customer/portal/2
- title: ''
  type: ChangeLog
  url: https://wiki.cdisc.org/display/LIBSUPRT/Release+Notes
- title: ''
  type: SignUp
  url: https://www.cdisc.org/cdisc-library/api-account-request
created: ''
description: CDISC Library uses linked data and a REST API to deliver CDISC standards metadata to software applications that automate standards-based processes. CDISC Library provides access to new relationships between standards as well as a substantially increased number of versioned CDISC standards and controlled terminology packages.
features: []
image: ''
integrations: []
jsonld:
- class_count: 6
  name: Cdisc Context
  property_count: 16
  slug: cdisc-context
layout: provider
modified: '2026-03-18'
name: cdisc
skills: []
slug: cdisc
solutions: []
source_filename: apis.yml
source_yaml: "aid: cdisc\nurl: https://raw.githubusercontent.com/api-evangelist/cdisc/refs/heads/main/apis.yml\napis:\n  - aid: cdisc:cdisc-library-api\n    name: CDISC Library API\n    tags:\n      - ADaM\n      - Clinical Trials\n      - Metadata\n      - ODM\n      - Pharma\n      - SDTM\n      - Standards\n    image: https://raw.githubusercontent.com/api-evangelist/cdisc/refs/heads/main/image.png\n    humanURL: https://www.cdisc.org/cdisc-library\n    baseURL: https://library.cdisc.org/api\n    properties:\n      - url: https://www.cdisc.org/cdisc-library/api-documentation\n        type: Documentation\n      - url: https://api.developer.library.cdisc.org/api-details\n        type: Reference\n      - url: https://www.cdisc.org/cdisc-library/getting-started\n        type: GettingStarted\n      - url: https://api.developer.library.cdisc.org/\n        type: Portal\n      - url: https://wiki.cdisc.org/display/LIBSUPRT/How-to+articles\n        type: KnowledgeBase\n      - url: https://wiki.cdisc.org/display/LIBSUPRT/Release+Notes\n\
  \        type: ChangeLog\n      - url: https://jira.cdisc.org/servicedesk/customer/portal/2\n        type: Support\n      - url: https://library.cdisc.org/browser\n        type: Explorer\n      - url: https://raw.githubusercontent.com/api-evangelist/cdisc/refs/heads/main/openapi/cdisc-library-openapi.yml\n        type: OpenAPI\n    description: >-\n      The CDISC Library API is a REST API that delivers CDISC standards metadata to\n      software applications that automate standards-based processes. It uses linked\n      data to provide access to SDTM, ADaM, and other clinical data standards. Responses\n      are available in JSON, XML, ODM, CSV, and Excel formats. Access requires a CDISC\n      Library account and an API key obtained from the CDISC Library API Management\n      (APIM) Developer Portal.\n  - aid: cdisc:cdisc-core-api\n    name: CDISC CORE (Checks and Rules Engine) API\n    tags:\n      - Clinical Trials\n      - Conformance\n      - Pharma\n      - Rules\n      - Validation\n\
  \    image: https://raw.githubusercontent.com/api-evangelist/cdisc/refs/heads/main/image.png\n    humanURL: https://www.cdisc.org/core\n    baseURL: https://library.cdisc.org/api\n    properties:\n      - url: https://www.cdisc.org/core\n        type: Documentation\n    description: >-\n      CDISC CORE (Checks and Rules Engine) is an open-source rules engine for validating\n      clinical data against CDISC conformance rules. It enables automated validation\n      of SDTM, ADaM, and other study data artifacts against published CDISC standards.\ncommon:\n  - url: https://www.cdisc.org/\n    type: Website\n  - url: https://raw.githubusercontent.com/api-evangelist/cdisc/refs/heads/main/openapi/cdisc-library-openapi.yml\n    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/cdisc/refs/heads/main/json-schema/cdisc-dataset-schema.json\n    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/cdisc/refs/heads/main/json-ld/cdisc-context.jsonld\n \
  \   type: JSONLDContext\n  - url: https://www.cdisc.org/cdisc-library\n    type: Portal\n  - url: https://www.cdisc.org/cdisc-library/getting-started\n    type: GettingStarted\n  - url: https://www.cdisc.org/cdisc-library/api-documentation\n    type: Documentation\n  - url: https://api.developer.library.cdisc.org/\n    type: Authentication\n  - url: https://jira.cdisc.org/servicedesk/customer/portal/2\n    type: Support\n  - url: https://wiki.cdisc.org/display/LIBSUPRT/Release+Notes\n    type: ChangeLog\n  - url: https://www.cdisc.org/cdisc-library/api-account-request\n    type: SignUp\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\nmodified: '2026-03-18'\ndescription: >-\n  CDISC Library uses linked data and a REST API to deliver CDISC standards metadata\n  to software applications that automate standards-based processes. CDISC Library\n  provides access to new relationships between standards as well as a substantially\n  increased number of versioned CDISC standards\
  \ and controlled terminology packages.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cdisc/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/cdisc/refs/heads/main/apis.yml
use_cases: []
---
