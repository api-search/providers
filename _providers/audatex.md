---
api_count: 3
apis:
- description: The AudaConnect API enables third-party software developers to access, query, and update the Audatex platform including assessments, vehicle reference data, repair orders, and photo management using R
  name: Audatex AudaConnect API
  slug: audatex-audaconnect-api
- description: The Audatex GIC (Global Integration Component) API provides integration capabilities for claims processing and vehicle damage assessment workflows in the insurance and collision repair industries.
  name: Audatex GIC API
  slug: audatex-gic-api
- description: The Solera API Gateway provides access to Audatex and Solera claims processing services including ClaimImage document return and other automotive claims data APIs for North American insurance markets.
  name: Solera API Gateway
  slug: solera-api-gateway
common:
- title: ''
  type: Website
  url: https://www.audatex.com/
- title: ''
  type: Documentation
  url: https://www.audatex.com/solutions/
- title: ''
  type: Privacy Policy
  url: https://www.audatex.com/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://www.audatex.com/terms-and-conditions/
- title: ''
  type: Contact
  url: https://www.audatex.com/contact/
created: '2025-01-01'
description: Audatex (part of Solera Holdings) provides automotive claims and repair solutions with data and technology services for the automotive insurance, collision repair, and fleet management industries. It offers the AudaConnect API platform for third-party integration with claims processing, damage assessment, repair cost estimation, and vehicle data workflows. APIs are RESTful with JSON/XML support and OAuth 2.0 authentication.
features:
- description: Search, download, upload, and amend vehicle damage assessments programmatically via the AudaConnect API.
  name: Claims Assessment API
- description: Access Audatex repair cost estimation data and labor rates for collision repair workflow automation.
  name: Repair Cost Estimation
- description: Upload, retrieve, and manage vehicle damage photos attached to claims via the assessment API.
  name: Photo Management
- description: Create, update, and query repair orders from bodyshop management systems via BMS API integration.
  name: Repair Order Integration
- description: Query vehicle reference data including make, model, trim, and VIN decoding for assessment setup.
  name: Vehicle Reference Data
- description: All AudaConnect APIs are secured with OAuth 2.0 authorization for enterprise-grade access control.
  name: OAuth 2.0 Security
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native integration with major BMS platforms for automated repair order and parts pricing workflows.
  name: Bodyshop Management Systems
- description: Integration with insurance policy and claims management systems for end-to-end claims processing.
  name: Insurance Core Systems
- description: Integration with vehicle history and VIN data providers for complete vehicle information at claims initiation.
  name: Vehicle History Providers
- description: Connection to OEM and aftermarket parts supplier catalogs for parts pricing and availability in repair estimates.
  name: Parts Suppliers
layout: provider
modified: '2026-04-19'
name: Audatex
skills: []
slug: audatex
solutions:
- description: End-to-end automation of auto insurance claims from FNOL through repair authorization and settlement.
  name: Claims Process Automation
- description: Digital workflow management for collision repair shops integrating estimates, parts, labor, and customer communication.
  name: Repair Shop Workflow
source_filename: apis.yml
source_yaml: "aid: audatex\nname: Audatex\ndescription: |\n  Audatex (part of Solera Holdings) provides automotive claims and repair solutions with data and technology services for the automotive insurance, collision repair, and fleet management industries. It offers the AudaConnect API platform for third-party integration with claims processing, damage assessment, repair cost estimation, and vehicle data workflows. APIs are RESTful with JSON/XML support and OAuth 2.0 authentication.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Automotive\n- Claims Processing\n- Insurance\n- Repair Management\n- Vehicle Data\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/audatex/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: audatex:audatex-audaconnect-api\n  name: Audatex AudaConnect API\n  description: |\n    The AudaConnect API enables third-party software developers\
  \ to access, query, and update the Audatex platform including assessments, vehicle reference data, repair orders, and photo management using RESTful methods with OAuth 2.0.\n  humanURL: https://audaconnect-demo.ax-aee.co.uk/AudaAPI.Portal/Home/About\n  baseURL: https://audaconnect-demo.ax-aee.co.uk/AudaAPI.Bmsapi\n  tags:\n  - Assessments\n  - Claims\n  - Insurance\n  - Repair\n  properties:\n  - type: Documentation\n    url: https://audaconnect-demo.ax-aee.co.uk/AudaAPI.Portal/Home/About\n  - type: OpenAPI\n    url: https://audaconnect-demo.ax-aee.co.uk/AudaAPI.Bmsapi/\n  - type: Authentication\n    url: https://audaconnect-demo.ax-aee.co.uk/AudaAPI.Portal/Home/About\n- aid: audatex:audatex-gic-api\n  name: Audatex GIC API\n  description: |\n    The Audatex GIC (Global Integration Component) API provides integration capabilities for claims processing and vehicle damage assessment workflows in the insurance and collision repair industries.\n  humanURL: https://api-demo.audatex.com/TestGICapi/docs/index.html\n\
  \  baseURL: https://api-demo.audatex.com/TestGICapi\n  tags:\n  - Claims\n  - GIC\n  - Insurance\n  - Integration\n  properties:\n  - type: Documentation\n    url: https://api-demo.audatex.com/TestGICapi/docs/index.html\n- aid: audatex:solera-api-gateway\n  name: Solera API Gateway\n  description: |\n    The Solera API Gateway provides access to Audatex and Solera claims processing services including ClaimImage document return and other automotive claims data APIs for North American insurance markets.\n  humanURL: https://na.api.solera.com/\n  baseURL: https://na.api.solera.com\n  tags:\n  - Claims\n  - Documents\n  - Insurance\n  - Solera\n  properties:\n  - type: Documentation\n    url: https://na.api.solera.com/\n  - type: Authentication\n    url: https://na.api.solera.com/\ncommon:\n- type: Website\n  url: https://www.audatex.com/\n- type: Documentation\n  url: https://www.audatex.com/solutions/\n- type: Privacy Policy\n  url: https://www.audatex.com/privacy-policy/\n- type: TermsOfService\n\
  \  url: https://www.audatex.com/terms-and-conditions/\n- type: Contact\n  url: https://www.audatex.com/contact/\n- type: Features\n  data:\n  - name: Claims Assessment API\n    description: Search, download, upload, and amend vehicle damage assessments programmatically via the AudaConnect API.\n  - name: Repair Cost Estimation\n    description: Access Audatex repair cost estimation data and labor rates for collision repair workflow automation.\n  - name: Photo Management\n    description: Upload, retrieve, and manage vehicle damage photos attached to claims via the assessment API.\n  - name: Repair Order Integration\n    description: Create, update, and query repair orders from bodyshop management systems via BMS API integration.\n  - name: Vehicle Reference Data\n    description: Query vehicle reference data including make, model, trim, and VIN decoding for assessment setup.\n  - name: OAuth 2.0 Security\n    description: All AudaConnect APIs are secured with OAuth 2.0 authorization for\
  \ enterprise-grade access control.\n- type: UseCases\n  data:\n  - name: Insurance Claims Automation\n    description: Automate first notice of loss, damage assessment, and claims settlement workflows for auto insurers.\n  - name: Bodyshop Management System Integration\n    description: Integrate bodyshop management systems with Audatex for repair order creation, parts pricing, and labor time.\n  - name: Total Loss Determination\n    description: Access vehicle valuation and total loss thresholds to automate total loss claims decisions.\n  - name: Digital Claims Submission\n    description: Enable digital submission of vehicle damage photos and assessment data from mobile apps to the Audatex platform.\n- type: Integrations\n  data:\n  - name: Bodyshop Management Systems\n    description: Native integration with major BMS platforms for automated repair order and parts pricing workflows.\n  - name: Insurance Core Systems\n    description: Integration with insurance policy and claims management\
  \ systems for end-to-end claims processing.\n  - name: Vehicle History Providers\n    description: Integration with vehicle history and VIN data providers for complete vehicle information at claims initiation.\n  - name: Parts Suppliers\n    description: Connection to OEM and aftermarket parts supplier catalogs for parts pricing and availability in repair estimates.\n- type: Solutions\n  data:\n  - name: Claims Process Automation\n    description: End-to-end automation of auto insurance claims from FNOL through repair authorization and settlement.\n  - name: Repair Shop Workflow\n    description: Digital workflow management for collision repair shops integrating estimates, parts, labor, and customer communication.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/audatex/refs/heads/main/apis.yml
tags:
- Automotive
- Claims Processing
- Insurance
- Repair Management
- Vehicle Data
url: https://raw.githubusercontent.com/api-evangelist/audatex/refs/heads/main/apis.yml
use_cases:
- description: Automate first notice of loss, damage assessment, and claims settlement workflows for auto insurers.
  name: Insurance Claims Automation
- description: Integrate bodyshop management systems with Audatex for repair order creation, parts pricing, and labor time.
  name: Bodyshop Management System Integration
- description: Access vehicle valuation and total loss thresholds to automate total loss claims decisions.
  name: Total Loss Determination
- description: Enable digital submission of vehicle damage photos and assessment data from mobile apps to the Audatex platform.
  name: Digital Claims Submission
---
