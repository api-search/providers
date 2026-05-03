---
api_count: 3
api_specs:
- filename: vantiv-cnp-openapi.yml
  format: yaml
  label: Vantiv CNP API
  slug: cnp-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/openapi/vantiv-cnp-openapi.yml
- filename: vantiv-express-openapi.yml
  format: yaml
  label: Vantiv Express API
  slug: express-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/openapi/vantiv-express-openapi.yml
- filename: vantiv-chargeback-openapi.yml
  format: yaml
  label: Vantiv Chargeback API
  slug: chargeback-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/openapi/vantiv-chargeback-openapi.yml
apis:
- description: 'The Vantiv Card Not Present (CNP) API, formerly known as the Litle eCommerce API, enables online and mobile payment processing. Supports authorizations, sales, captures, credits, voids, tokenization, '
  name: Vantiv CNP API
  slug: cnp-api
- description: The Vantiv Integrated Payments Express API provides a REST/XML interface for point-of-sale and in-person payment processing. Supports credit, debit, EBT, gift card, and check transactions with EMV chi
  name: Vantiv Express API
  slug: express-api
- description: The Vantiv Chargeback API provides programmatic access to chargeback and dispute management, allowing merchants to retrieve chargeback details, upload evidence, and respond to disputes.
  name: Vantiv Chargeback API
  slug: chargeback-api
capabilities:
- description: Unified payment processing workflow combining Vantiv's eCommerce CNP API and chargeback management. Designed for merchants processing online card payments, managing refunds, tokenizing card data for r
  name: Vantiv Payment Processing
  slug: payment-processing
common:
- title: ''
  type: Portal
  url: https://developer.vantiv.com/community/ecommerce
- title: ''
  type: SDK
  url: https://developer.vantiv.com/community/ecommerce/pages/sdks
- title: ''
  type: Sandbox
  url: https://developer.vantiv.com/docs/DOC-1347
- title: ''
  type: SDK
  url: https://github.com/Vantiv
- title: ''
  type: SDK
  url: https://github.com/Vantiv/cnp-sdk-for-java
- title: ''
  type: SDK
  url: https://github.com/Vantiv/vantiv-sdk-for-python
- title: ''
  type: SDK
  url: https://github.com/Vantiv/cnp-sdk-for-php
- title: ''
  type: SDK
  url: https://github.com/Vantiv/cnp-sdk-for-dotnet
- title: ''
  type: SDK
  url: https://github.com/Vantiv/cnp-sdk-for-ruby
- title: ''
  type: SDK
  url: https://github.com/Vantiv/cnp-chargeback-sdk-java
- title: ''
  type: Documentation
  url: https://developer.worldpay.com
- title: ''
  type: Website
  url: https://www.vantiv.com
created: '2026-05-03'
description: Vantiv was a leading American payment processing and technology provider that merged with Worldpay in 2018, forming Worldpay from FIS. Vantiv provided integrated payment processing solutions for merchants, financial institutions, and businesses across eCommerce, in-store, and omni-channel payment scenarios. Their cnpAPI (formerly litleAPI) supported credit card authorizations, captures, sales, refunds, voids, tokenization, chargebacks, and recurring billing.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 17
  name: Vantiv Context
  property_count: 13
  slug: vantiv-context
layout: provider
modified: '2026-05-03'
name: Vantiv
rules:
- name: Vantiv API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 1
    warn: 6
  slug: vantiv-rules
skills: []
slug: vantiv
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vantiv\nurl: https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/apis.yml\nname: Vantiv\ntags:\n  - Payments\n  - Payment Processing\n  - eCommerce\n  - Finance\n  - FinTech\ntype: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-05-03'\nmodified: '2026-05-03'\ndescription: >-\n  Vantiv was a leading American payment processing and technology provider that merged\n  with Worldpay in 2018, forming Worldpay from FIS. Vantiv provided integrated payment\n  processing solutions for merchants, financial institutions, and businesses across\n  eCommerce, in-store, and omni-channel payment scenarios. Their cnpAPI (formerly litleAPI)\n  supported credit card authorizations, captures, sales, refunds, voids, tokenization,\n  chargebacks, and recurring billing.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\napis:\n  - aid: vantiv:cnp-api\n\
  \    name: Vantiv CNP API\n    tags:\n      - Payments\n      - Payment Processing\n      - eCommerce\n      - Finance\n      - Card-Not-Present\n    humanURL: https://developer.vantiv.com/community/ecommerce\n    baseURL: https://payments.vantivprelive.com/vap/communicator/online\n    properties:\n      - url: https://developer.vantiv.com/community/ecommerce/pages/sdks\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/openapi/vantiv-cnp-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Vantiv Card Not Present (CNP) API, formerly known as the Litle eCommerce API,\n      enables online and mobile payment processing. Supports authorizations, sales, captures,\n      credits, voids, tokenization, chargebacks, and recurring billing through XML-based\n      HTTPS POST requests.\n\n  - aid: vantiv:express-api\n    name: Vantiv Express API\n    tags:\n      - Payments\n      - Payment Processing\n      - Point Of\
  \ Sale\n      - Finance\n    humanURL: https://developer.vantiv.com/community/point-of-sale/pages/documentation\n    baseURL: https://api.vantivintegrationtest.com/express/v1\n    properties:\n      - url: https://developer.vantiv.com/community/point-of-sale/pages/documentation\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/openapi/vantiv-express-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Vantiv Integrated Payments Express API provides a REST/XML interface for\n      point-of-sale and in-person payment processing. Supports credit, debit, EBT,\n      gift card, and check transactions with EMV chip support.\n\n  - aid: vantiv:chargeback-api\n    name: Vantiv Chargeback API\n    tags:\n      - Payments\n      - Chargebacks\n      - Finance\n      - Dispute Management\n    humanURL: https://developer.vantiv.com/community/ecommerce\n    baseURL: https://services.vantivprelive.com/services/chargebacks\n\
  \    properties:\n      - url: https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/openapi/vantiv-chargeback-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Vantiv Chargeback API provides programmatic access to chargeback and dispute\n      management, allowing merchants to retrieve chargeback details, upload evidence,\n      and respond to disputes.\n\ncommon:\n  - name: Developer Community\n    url: https://developer.vantiv.com/community/ecommerce\n    type: Portal\n  - name: eCommerce SDKs\n    url: https://developer.vantiv.com/community/ecommerce/pages/sdks\n    type: SDK\n  - name: Sandbox Documentation\n    url: https://developer.vantiv.com/docs/DOC-1347\n    type: Sandbox\n  - name: GitHub Organization\n    url: https://github.com/Vantiv\n    type: SDK\n  - name: Java SDK\n    url: https://github.com/Vantiv/cnp-sdk-for-java\n    type: SDK\n  - name: Python SDK\n    url: https://github.com/Vantiv/vantiv-sdk-for-python\n    type: SDK\n  - name:\
  \ PHP SDK\n    url: https://github.com/Vantiv/cnp-sdk-for-php\n    type: SDK\n  - name: .NET SDK\n    url: https://github.com/Vantiv/cnp-sdk-for-dotnet\n    type: SDK\n  - name: Ruby SDK\n    url: https://github.com/Vantiv/cnp-sdk-for-ruby\n    type: SDK\n  - name: Chargeback SDK Java\n    url: https://github.com/Vantiv/cnp-chargeback-sdk-java\n    type: SDK\n  - name: Worldpay Developer Hub\n    url: https://developer.worldpay.com\n    type: Documentation\n  - name: Website\n    url: https://www.vantiv.com\n    type: Website\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/apis.yml
tags:
- Payments
- Payment Processing
- eCommerce
- Finance
- FinTech
url: https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/apis.yml
use_cases: []
---
