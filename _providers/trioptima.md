---
api_count: 2
api_specs:
- filename: trioptima-trireduce-api-openapi.yml
  format: yaml
  label: Trioptima triReduce API
  slug: trireduce-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trioptima/refs/heads/main/openapi/trioptima-trireduce-api-openapi.yml
apis:
- description: The triReduce API provides machine-to-machine access to TriOptima's portfolio compression cycles for OTC derivatives. The API allows cycle participants to automate participation in compression cycles,
  name: Trioptima triReduce API
  slug: trireduce-api
- description: Trioptima triResolve is a web-based portfolio reconciliation service for OTC derivatives. It normalizes trade data, reconciles all fields using an algorithmic match engine, and provides break workflow
  name: Trioptima triResolve Portfolio Reconciliation
  slug: triresolve
capabilities:
- description: Workflow capability for automating OTC derivatives portfolio compression cycles via the triReduce API. Designed for derivatives operations teams, risk managers, and treasury systems that need to parti
  name: Trioptima Portfolio Compression
  slug: portfolio-compression
common:
- title: ''
  type: Website
  url: https://osttra.com
- title: ''
  type: Website
  url: https://osttra.com/login/trioptima-logins/
- title: ''
  type: Documentation
  url: https://www.cmegroup.com/education/brochures-and-handbooks/trireduce-api
- title: ''
  type: Documentation
  url: https://osttra.com/services/optimisation/portfolio-compression/
- title: ''
  type: Documentation
  url: https://osttra.com/services/trade-lifecycle-services/portfolio-reconciliation/
- title: ''
  type: GitHub
  url: https://github.com/TriOptima
- title: ''
  type: GitHub
  url: https://github.com/osttra
- title: ''
  type: JSONLDContext
  url: json-ld/trioptima-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/trioptima-compression-cycle-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/trioptima-trade-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/trioptima-vocabulary.yml
created: '2026-05-03'
description: Trioptima provides post-trade infrastructure services for the OTC derivatives market, including portfolio compression (triReduce), portfolio reconciliation (triResolve), and risk mitigation services. Originally founded in 2000, Trioptima became part of OSTTRA in 2021 — a joint venture combining MarkitServ, Traiana, TriOptima, and Reset to form a comprehensive post-trade services platform. Trioptima's services help financial institutions reduce counterparty risk, optimize capital requirements, and meet regulatory obligations across interest rate, credit, FX, and equity derivatives.
features:
- name: Portfolio Compression (triReduce)
- name: Portfolio Reconciliation (triResolve)
- name: Collateral Management (triResolve Margin)
- name: Risk Mitigation
- name: Multilateral Compression
- name: Bilateral Compression
- name: Cleared IRS Compression
- name: Credit Default Swap Compression
- name: FX Forward Compression
- name: Break Workflow Management
- name: Dispute Resolution
- name: SWIFT Integration
- name: SFTP Data Transfer
- name: OAuth 2.0 Authentication
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: SWIFT
- name: CLS (FX compression)
- name: LCH
- name: CME Clearing
- name: Eurex
- name: Bloomberg
- name: Traiana
- name: MarkitServ
jsonld:
- class_count: 16
  name: Trioptima Context
  property_count: 17
  slug: trioptima-context
layout: provider
modified: '2026-05-03'
name: Trioptima
rules:
- name: Trioptima API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 5
  slug: trioptima-rules
skills: []
slug: trioptima
solutions:
- name: Interest Rate Derivatives Post-Trade
- name: Credit Derivatives Post-Trade
- name: FX Derivatives Post-Trade
- name: Regulatory Compliance (EMIR, Dodd-Frank)
- name: Capital Optimization
- name: Counterparty Risk Reduction
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trioptima\nurl: https://raw.githubusercontent.com/api-evangelist/trioptima/refs/heads/main/apis.yml\nname: Trioptima\ndescription: >-\n  Trioptima provides post-trade infrastructure services for the OTC derivatives market,\n  including portfolio compression (triReduce), portfolio reconciliation (triResolve),\n  and risk mitigation services. Originally founded in 2000, Trioptima became part of\n  OSTTRA in 2021 — a joint venture combining MarkitServ, Traiana, TriOptima, and Reset\n  to form a comprehensive post-trade services platform. Trioptima's services help financial\n  institutions reduce counterparty risk, optimize capital requirements, and meet regulatory\n  obligations across interest rate, credit, FX, and equity derivatives.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CME Group\n  - Derivatives\n  - Financial Services\n  - OSTTRA\n  - Portfolio Compression\n  - Post-Trade Services\n  - Reconciliation\n  - Risk\
  \ Management\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: trioptima:trireduce-api\n    name: Trioptima triReduce API\n    tags:\n      - Compression\n      - Derivatives\n      - Portfolio Optimization\n      - Risk Reduction\n    humanURL: https://osttra.com/services/optimisation/portfolio-compression/\n    baseURL: https://rates.trireduce.com\n    properties:\n      - url: https://www.cmegroup.com/education/brochures-and-handbooks/trireduce-api\n        type: Documentation\n      - url: openapi/trioptima-trireduce-api-openapi.yml\n        type: OpenAPI\n      - url: rules/trioptima-rules.yml\n        type: SpectralRules\n      - url: vocabulary/trioptima-vocabulary.yml\n        type: Vocabulary\n    description: >-\n      The triReduce API provides machine-to-machine access to TriOptima's portfolio\n      compression cycles for OTC derivatives. The API allows cycle participants to automate\n      participation in compression cycles, submit\
  \ trade and risk data, and retrieve cycle\n      results. Available for rates (IRS, OIS) and credit derivatives compression.\n      Authentication uses OAuth 2.0 with read-only access for development and full access\n      for production. Documentation available at https://rates.trireduce.com/api/v1/doc.\n\n  - aid: trioptima:triresolve\n    name: Trioptima triResolve Portfolio Reconciliation\n    tags:\n      - Collateral Management\n      - Derivatives\n      - Disputes\n      - Reconciliation\n      - Risk Management\n    humanURL: https://osttra.com/services/trade-lifecycle-services/portfolio-reconciliation/\n    baseURL: https://triResolve.com\n    properties:\n      - url: https://osttra.com/services/trade-lifecycle-services/portfolio-reconciliation/\n        type: Documentation\n    description: >-\n      Trioptima triResolve is a web-based portfolio reconciliation service for OTC\n      derivatives. It normalizes trade data, reconciles all fields using an algorithmic\n      match\
  \ engine, and provides break workflow for identifying, tracking, investigating,\n      and resolving discrepancies. Over 1,500 firms use triResolve for bilateral and\n      cleared portfolio reconciliation. Data submission via SFTP API file transfer or\n      manual upload (QuickPort).\n\ncommon:\n  - type: Website\n    url: https://osttra.com\n    name: OSTTRA (TriOptima Parent)\n  - type: Website\n    url: https://osttra.com/login/trioptima-logins/\n    name: TriOptima Logins\n  - type: Documentation\n    url: https://www.cmegroup.com/education/brochures-and-handbooks/trireduce-api\n    name: triReduce API Documentation\n  - type: Documentation\n    url: https://osttra.com/services/optimisation/portfolio-compression/\n    name: Portfolio Compression Service\n  - type: Documentation\n    url: https://osttra.com/services/trade-lifecycle-services/portfolio-reconciliation/\n    name: Portfolio Reconciliation Service\n  - type: GitHub\n    url: https://github.com/TriOptima\n    name: TriOptima\
  \ GitHub Organization\n  - type: GitHub\n    url: https://github.com/osttra\n    name: OSTTRA GitHub Organization\n  - url: json-ld/trioptima-context.jsonld\n    name: Trioptima JSON-LD Context\n    type: JSONLDContext\n  - url: json-schema/trioptima-compression-cycle-schema.json\n    name: Compression Cycle JSON Schema\n    type: JSONSchema\n  - url: json-schema/trioptima-trade-schema.json\n    name: Trade JSON Schema\n    type: JSONSchema\n  - url: vocabulary/trioptima-vocabulary.yml\n    name: Trioptima Vocabulary\n    type: Vocabulary\n  - name: Features\n    type: Features\n    data:\n      - name: Portfolio Compression (triReduce)\n      - name: Portfolio Reconciliation (triResolve)\n      - name: Collateral Management (triResolve Margin)\n      - name: Risk Mitigation\n      - name: Multilateral Compression\n      - name: Bilateral Compression\n      - name: Cleared IRS Compression\n      - name: Credit Default Swap Compression\n      - name: FX Forward Compression\n      - name:\
  \ Break Workflow Management\n      - name: Dispute Resolution\n      - name: SWIFT Integration\n      - name: SFTP Data Transfer\n      - name: OAuth 2.0 Authentication\n  - name: Solutions\n    type: Solutions\n    data:\n      - name: Interest Rate Derivatives Post-Trade\n      - name: Credit Derivatives Post-Trade\n      - name: FX Derivatives Post-Trade\n      - name: Regulatory Compliance (EMIR, Dodd-Frank)\n      - name: Capital Optimization\n      - name: Counterparty Risk Reduction\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: SWIFT\n      - name: CLS (FX compression)\n      - name: LCH\n      - name: CME Clearing\n      - name: Eurex\n      - name: Bloomberg\n      - name: Traiana\n      - name: MarkitServ\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trioptima/refs/heads/main/apis.yml
tags:
- CME Group
- Derivatives
- Financial Services
- OSTTRA
- Portfolio Compression
- Post-Trade Services
- Reconciliation
- Risk Management
url: https://raw.githubusercontent.com/api-evangelist/trioptima/refs/heads/main/apis.yml
use_cases: []
---
