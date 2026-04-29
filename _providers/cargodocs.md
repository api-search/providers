---
api_count: 3
api_specs:
- filename: cargodocs-partner-openapi.yml
  format: yaml
  label: CargoDocs Partner API
  slug: partner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/openapi/cargodocs-partner-openapi.yml
- filename: cargodocs-issuer-openapi.yml
  format: yaml
  label: CargoDocs Issuer API
  slug: issuer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/openapi/cargodocs-issuer-openapi.yml
- filename: cargodocs-customer-openapi.yml
  format: yaml
  label: CargoDocs Customer Data/Docs API
  slug: customer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/openapi/cargodocs-customer-openapi.yml
apis:
- description: The CargoDocs Partner API enables platform providers and trade finance/trade management platforms to embed CargoDocs DocEx functionality, including original electronic bills of lading (eBoL) and wareh
  name: CargoDocs Partner API
  slug: partner-api
- description: The CargoDocs Issuer API enables container lines, NVOCCs, and bulk/tanker carriers to manage electronic straight and negotiable bills of lading and sea waybills at origin or destination from within th
  name: CargoDocs Issuer API
  slug: issuer-api
- description: 'The CargoDocs Customer Data/Docs API enables exporters and commodity shippers to draft trade and shipping documents, including tanker, bulker, or barge bills of lading, from data imported out of ERP, '
  name: CargoDocs Customer Data/Docs API
  slug: customer-api
common:
- title: ''
  type: Website
  url: https://www.essdocs.com/
- title: ''
  type: Product
  url: https://www.essdocs.com/cargodocs
- title: ''
  type: JSONLDContext
  url: json-ld/cargodocs-context.jsonld
- title: ''
  type: Partner Docs
  url: https://cargodocs-partner.readme.io/
- title: ''
  type: Issuer Docs
  url: https://cargodocs-issuer.readme.io/
- title: ''
  type: Customer Docs
  url: https://cargodocs-customer.readme.io/
- title: ''
  type: Blog
  url: https://www.essdocs.com/blog
- title: ''
  type: Contact
  url: https://www.essdocs.com/contact
- title: ''
  type: Terms of Service
  url: https://www.essdocs.com/terms
- title: ''
  type: Privacy Policy
  url: https://www.essdocs.com/privacy
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/essdocs
created: '2025-01-08'
description: CargoDocs, operated by EssDocs, is a digital trade documentation platform that eliminates paper-based shipping documents by letting carriers, shippers, banks, and partner platforms issue, sign, transfer, and surrender original electronic bills of lading (eBoL), sea waybills (SWB), warehouse warrants (eWW), and supporting trade documents. CargoDocs DocEx is used by container lines, NVOCCs, bulk/tanker carriers, commodity shippers, and trade finance banks to move documents in minutes rather than days while retaining negotiability and legal effect. Developers interact with CargoDocs through three OpenAPI-described REST APIs hosted on ReadMe - the Partner API (embed DocEx in third-party platforms), the Issuer API (carrier/NVOCC issuance and amendments), and the Customer Data/Docs API (exporter drafting and back-office integration).
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cargodocs Context
  property_count: 5
  slug: cargodocs-context
layout: provider
modified: '2026-04-23'
name: CargoDocs
skills: []
slug: cargodocs
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cargodocs\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/apis.yml\nname: CargoDocs\ndescription: >-\n  CargoDocs, operated by EssDocs, is a digital trade documentation\n  platform that eliminates paper-based shipping documents by letting\n  carriers, shippers, banks, and partner platforms issue, sign,\n  transfer, and surrender original electronic bills of lading (eBoL),\n  sea waybills (SWB), warehouse warrants (eWW), and supporting trade\n  documents. CargoDocs DocEx is used by container lines, NVOCCs,\n  bulk/tanker carriers, commodity shippers, and trade finance banks\n  to move documents in minutes rather than days while retaining\n  negotiability and legal effect. Developers interact with CargoDocs\n  through three OpenAPI-described REST APIs hosted on ReadMe - the\n  Partner API (embed DocEx in third-party platforms), the Issuer API\n  (carrier/NVOCC issuance and amendments), and the Customer Data/Docs\n  API (exporter drafting\
  \ and back-office integration).\ntype: Index\nx-type: company\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Bills of Lading\n  - Documentation\n  - eBoL\n  - EssDocs\n  - MLETR\n  - Shipping\n  - Supply Chain\n  - Trade\n  - Trade Finance\n  - Warehouse Warrants\ncreated: '2025-01-08'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: cargodocs:partner-api\n    name: CargoDocs Partner API\n    description: >-\n      The CargoDocs Partner API enables platform providers and trade\n      finance/trade management platforms to embed CargoDocs DocEx\n      functionality, including original electronic bills of lading\n      (eBoL) and warehouse warrants (eWW). The API exposes Partner\n      Exchange endpoints to retrieve customer, counterparty, document,\n      and transaction data using conditions and filters, and Action\n      endpoints to perform operations over transactions such as\
  \ signing,\n      transferring, and surrendering documents.\n    humanURL: https://cargodocs-partner.readme.io/\n    baseURL: https://api.essdocs.com\n    tags:\n      - Bills of Lading\n      - Shipping\n      - Trade\n    properties:\n      - url: https://cargodocs-partner.readme.io/\n        type: Documentation\n      - url: https://cargodocs-partner.readme.io/docs/api-environments\n        type: GettingStarted\n      - url: openapi/cargodocs-partner-openapi.yml\n        type: OpenAPI\n      - url: json-schema/cargodocs-customer.json\n        type: JSONSchema\n      - url: json-schema/cargodocs-counterparty.json\n        type: JSONSchema\n    x-features:\n      - Retrieve customer, counterparty, and transaction data with filters\n      - Perform signing, transferring, and surrendering actions\n      - Embed DocEx workflows in partner platforms\n      - Sandbox and production API environments\n      - JSON document retrieval plus PDF rendering\n      - Partner-scoped authentication and\
  \ audit trail\n    x-use-cases:\n      - Trade finance platforms embedding eBoL workflows\n      - TMS/CTRM providers offering native digital docs\n      - Freight forwarder portals with integrated surrender flows\n      - Bank-held eBoL custody during letter-of-credit settlement\n  - aid: cargodocs:issuer-api\n    name: CargoDocs Issuer API\n    description: >-\n      The CargoDocs Issuer API enables container lines, NVOCCs, and\n      bulk/tanker carriers to manage electronic straight and negotiable\n      bills of lading and sea waybills at origin or destination from\n      within their TMS. It supports sharing draft eBoL/SWB for shipper\n      approval, signing and issuing original eBoL/SWB, receiving\n      surrendered original electronic bills of lading, and managing\n      amendment requests or splits of an eBoL.\n    humanURL: https://cargodocs-issuer.readme.io/\n    baseURL: https://api.essdocs.com\n    tags:\n      - Bills of Lading\n      - Issuance\n      - Shipping\n    properties:\n\
  \      - url: https://cargodocs-issuer.readme.io/\n        type: Documentation\n      - url: https://cargodocs-issuer.readme.io/docs/first-api-call\n        type: GettingStarted\n      - url: openapi/cargodocs-issuer-openapi.yml\n        type: OpenAPI\n      - url: json-schema/cargodocs-bill-of-lading.json\n        type: JSONSchema\n    x-features:\n      - Draft, sign, and issue original eBoL / SWB\n      - Shipper approval workflow for drafts\n      - Receive surrendered original eBoL at destination\n      - Amendment requests and eBoL split handling\n      - Straight and negotiable bill of lading support\n      - Carrier-side legal audit trail\n    x-use-cases:\n      - Container line TMS integration\n      - NVOCC issuance automation\n      - Bulk/tanker carrier documentation\n      - Origin/destination eBoL surrender workflows\n  - aid: cargodocs:customer-api\n    name: CargoDocs Customer Data/Docs API\n    description: >-\n      The CargoDocs Customer Data/Docs API enables exporters\
  \ and\n      commodity shippers to draft trade and shipping documents,\n      including tanker, bulker, or barge bills of lading, from data\n      imported out of ERP, CTRM, TMS, or WMS systems. It also enables\n      any party using CargoDocs to download copy documents and\n      structured transaction data to automate back-office steps such\n      as invoicing, reconciliation, and reporting.\n    humanURL: https://cargodocs-customer.readme.io/\n    baseURL: https://api.essdocs.com\n    tags:\n      - Documents\n      - Shipping\n      - Trade\n    properties:\n      - url: https://cargodocs-customer.readme.io/\n        type: Documentation\n      - url: openapi/cargodocs-customer-openapi.yml\n        type: OpenAPI\n      - url: json-schema/cargodocs-transaction.json\n        type: JSONSchema\n      - url: json-schema/cargodocs-document.json\n        type: JSONSchema\n    x-features:\n      - Drafting of tanker, bulker, and barge bills of lading\n      - ERP/CTRM/TMS/WMS data import\n\
  \      - Copy document and structured data download\n      - Transaction metadata for back-office automation\n      - Exporter-friendly document templates\n    x-use-cases:\n      - Commodity shipper documentation automation\n      - ERP-driven eBoL drafting\n      - Back-office reconciliation of shipping documents\n      - Data feeds into trade finance and invoicing systems\ncommon:\n  - type: Website\n    url: https://www.essdocs.com/\n  - type: Product\n    url: https://www.essdocs.com/cargodocs\n  - url: json-ld/cargodocs-context.jsonld\n    name: CargoDocs JSON-LD Context\n    type: JSONLDContext\n    description: JSON-LD context document for CargoDocs domain entities.\n  - type: Partner Docs\n    url: https://cargodocs-partner.readme.io/\n  - type: Issuer Docs\n    url: https://cargodocs-issuer.readme.io/\n  - type: Customer Docs\n    url: https://cargodocs-customer.readme.io/\n  - type: Blog\n    url: https://www.essdocs.com/blog\n  - type: Contact\n    url: https://www.essdocs.com/contact\n\
  \  - type: Terms of Service\n    url: https://www.essdocs.com/terms\n  - type: Privacy Policy\n    url: https://www.essdocs.com/privacy\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/essdocs\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/apis.yml
tags:
- Bills of Lading
- Documentation
- eBoL
- EssDocs
- MLETR
- Shipping
- Supply Chain
- Trade
- Trade Finance
- Warehouse Warrants
url: https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/apis.yml
use_cases: []
---
