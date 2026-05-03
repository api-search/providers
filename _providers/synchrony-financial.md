---
api_count: 3
api_specs:
- filename: synchrony-financial-credit-authorization-openapi.yml
  format: yaml
  label: Synchrony Credit Authorization API
  slug: credit-authorization
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/synchrony-financial/refs/heads/main/openapi/synchrony-financial-credit-authorization-openapi.yml
- filename: synchrony-financial-quickscreen-apply-openapi.yml
  format: yaml
  label: Synchrony Quickscreen Apply API
  slug: quickscreen-apply
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/synchrony-financial/refs/heads/main/openapi/synchrony-financial-quickscreen-apply-openapi.yml
apis:
- description: The Synchrony Credit Authorization API allows merchants and retailers to perform credit card transactions including purchases, preauthorizations, completions, payments, refunds, and reversals. The API
  name: Synchrony Credit Authorization API
  slug: credit-authorization
- description: Synchrony's Quickscreen API is a preapproval engine that allows merchants to offer instant credit decisions using only a customer's name and address. It runs a soft credit check and returns a real-tim
  name: Synchrony Quickscreen Apply API
  slug: quickscreen-apply
- description: The Synchrony Account Management API provides access to cardholder account information, enabling partners to retrieve account details, balance information, transaction history, and manage account serv
  name: Synchrony Account Management API
  slug: account-management
capabilities:
- description: Unified retail credit capability combining Synchrony's credit authorization and Quickscreen preapproval APIs. Enables merchants to offer instant credit decisions, process purchases on credit, handle p
  name: Synchrony Financial Retail Credit
  slug: retail-credit
common:
- title: ''
  type: Website
  url: https://www.synchrony.com
- title: ''
  type: DeveloperPortal
  url: https://developer.syf.com/
- title: ''
  type: PortalProducts
  url: https://developer.syf.com/our-products
- title: ''
  type: TermsOfService
  url: https://developer.syf.com/terms-of-use
- title: ''
  type: Sandbox
  url: https://developer.syf.com/
- title: ''
  type: JSONLDContext
  url: json-ld/synchrony-financial-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/synchrony-financial-vocabulary.yml
created: '2026-05-03'
description: Synchrony Financial is one of the nation's premier consumer financial services companies, providing a range of credit products through programs established with retailers, manufacturers, and merchants. Synchrony offers APIs enabling partners and retailers to integrate credit applications, authorizations, payments, loyalty, and account management into their digital commerce experiences.
features: []
image: ''
integrations: []
jsonld:
- class_count: 24
  name: Synchrony Financial Context
  property_count: 2
  slug: synchrony-financial-context
layout: provider
modified: '2026-05-03'
name: Synchrony Financial
rules:
- name: Synchrony Financial API Rules
  rule_count: 11
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 7
  slug: synchrony-financial-rules
skills: []
slug: synchrony-financial
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: synchrony-financial\nname: Synchrony Financial\ndescription: >-\n  Synchrony Financial is one of the nation's premier consumer financial services companies,\n  providing a range of credit products through programs established with retailers,\n  manufacturers, and merchants. Synchrony offers APIs enabling partners and retailers\n  to integrate credit applications, authorizations, payments, loyalty, and account\n  management into their digital commerce experiences.\nurl: https://raw.githubusercontent.com/api-evangelist/synchrony-financial/refs/heads/main/apis.yml\ncreated: '2026-05-03'\nmodified: '2026-05-03'\ntags:\n  - Financial Services\n  - Credit\n  - Payments\n  - Consumer Finance\n  - Retail Finance\napis:\n  - aid: synchrony-financial:credit-authorization\n    name: Synchrony Credit Authorization API\n    description: >-\n      The Synchrony Credit Authorization API allows merchants and retailers to perform\n      credit card transactions including purchases, preauthorizations,\
  \ completions,\n      payments, refunds, and reversals. The API supports transactions via payment tokens\n      or full account numbers across web, mobile, and point-of-sale channels.\n    humanURL: https://developer.syf.com/our-products/credit-authorizations\n    baseURL: https://api.syf.com\n    tags:\n      - Credit Authorization\n      - Payments\n      - Purchases\n      - Refunds\n      - Retail Finance\n    properties:\n      - type: Documentation\n        url: https://developer.syf.com/our-products/credit-authorizations\n      - type: OpenAPI\n        url: openapi/synchrony-financial-credit-authorization-openapi.yml\n\n  - aid: synchrony-financial:quickscreen-apply\n    name: Synchrony Quickscreen Apply API\n    description: >-\n      Synchrony's Quickscreen API is a preapproval engine that allows merchants\n      to offer instant credit decisions using only a customer's name and address.\n      It runs a soft credit check and returns a real-time decision, enabling\n      seamless\
  \ credit offering within the shopping experience.\n    humanURL: https://developer.syf.com/our-products/quickscreen-apply\n    baseURL: https://api.syf.com\n    tags:\n      - Credit Application\n      - Preapproval\n      - Quickscreen\n      - Consumer Finance\n    properties:\n      - type: Documentation\n        url: https://developer.syf.com/our-products/quickscreen-apply\n      - type: OpenAPI\n        url: openapi/synchrony-financial-quickscreen-apply-openapi.yml\n\n  - aid: synchrony-financial:account-management\n    name: Synchrony Account Management API\n    description: >-\n      The Synchrony Account Management API provides access to cardholder account\n      information, enabling partners to retrieve account details, balance information,\n      transaction history, and manage account servicing operations on behalf of customers.\n    humanURL: https://developer.syf.com/\n    baseURL: https://api.syf.com\n    tags:\n      - Account Management\n      - Consumer Finance\n    \
  \  - Credit Cards\n    properties:\n      - type: Documentation\n        url: https://developer.syf.com/\n\ncommon:\n  - type: Website\n    url: https://www.synchrony.com\n  - type: DeveloperPortal\n    url: https://developer.syf.com/\n  - type: PortalProducts\n    url: https://developer.syf.com/our-products\n  - type: TermsOfService\n    url: https://developer.syf.com/terms-of-use\n  - type: Sandbox\n    url: https://developer.syf.com/\n  - type: JSONLDContext\n    url: json-ld/synchrony-financial-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/synchrony-financial-vocabulary.yml\nfeatures:\n  - Credit Authorization\n  - Preapproval Engine (Quickscreen)\n  - Mobile Credit Application (mApply)\n  - Account Servicing\n  - Loyalty and Rewards Integration\n  - Payment Tokens Support\n  - Sandbox Environment\nuseCases:\n  - Retail Credit Integration\n  - E-Commerce Credit Offering\n  - Mobile Point-of-Sale Financing\n  - Credit Card Transaction Processing\n  - Consumer Loyalty Programs\n\
  integrations:\n  - type: AdobeCommerce\n    url: https://commercemarketplace.adobe.com/synchrony-digital-buy-magento2-module.html\n  - type: Plaid\n    url: https://plaid.com/institutions/synchrony-bank/\nsolutions:\n  - Buy Now Pay Later\n  - Retail Financing\n  - Consumer Credit Programs\n  - Partner Credit Programs\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/synchrony-financial/refs/heads/main/apis.yml
tags:
- Financial Services
- Credit
- Payments
- Consumer Finance
- Retail Finance
url: https://raw.githubusercontent.com/api-evangelist/synchrony-financial/refs/heads/main/apis.yml
use_cases: []
---
