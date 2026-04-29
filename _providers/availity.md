---
api_count: 9
apis:
- description: The Availity Eligibility & Benefits API supports the ASC X12N 270 and 271 transactions, enabling real-time verification of member coverage, co-pays, deductibles, and benefits information. REST APIs co
  name: Availity Eligibility & Benefits API
  slug: availity-eligibility-benefits-api
- description: The Availity Claim Status API enables the standard ASC X12N 276 and 277 transactions, allowing providers to find, create, and manage claim status inquiries against payer systems. REST APIs bridge prov
  name: Availity Claim Status API
  slug: availity-claims-status-api
- description: 'The Availity Claim Attachments API enables electronic submission of supporting documentation alongside healthcare claims. REST APIs support structured and unstructured attachment types for additional '
  name: Availity Claim Attachments API
  slug: availity-claim-attachments-api
- description: The Availity Service Reviews API enables the ASC X12N 278 transaction for prior authorization and healthcare service review. REST APIs allow providers to find, create, and manage authorization request
  name: Availity Service Reviews (Prior Authorization) API
  slug: availity-service-reviews-api
- description: The Availity Healthcare HIPAA Transactions API provides a unified interface for standard HIPAA EDI transactions. REST APIs enable healthcare providers and vendors to submit and receive X12 EDI transac
  name: Availity Healthcare HIPAA Transactions API
  slug: availity-hipaa-transactions-api
- description: The Availity Patient Cost Estimator API enables healthcare providers and institutions to estimate service costs before delivery for both institutional and professional services. REST APIs support vers
  name: Availity Patient Cost Estimator API
  slug: availity-patient-cost-estimator-api
- description: The Availity Eligibility & Benefits Value-Add APIs provide supplementary data during eligibility transactions. The Care Reminders API retrieves real-time care gap information from multiple payers. The
  name: Availity Eligibility & Benefits Value-Add APIs
  slug: availity-eb-value-adds-api
- description: The Availity Payer List API (v1.0.4) allows healthcare organizations to query available payers and the transactions they support. Returns payer identifiers, names, and supported transaction types incl
  name: Availity Payer List API
  slug: availity-payer-list-api
- description: The Availity Configurations API (v1.0.0) provides provider details and payer-specific validation requirements. Returns configuration rules for enhanced claim status, prior authorization, and other tra
  name: Availity Configurations API
  slug: availity-configurations-api
capabilities:
- description: Unified workflow for revenue cycle management combining eligibility verification, claim status tracking, and prior authorization. Used by billing departments and revenue cycle teams to streamline pati
  name: Availity Healthcare Revenue Cycle Management
  slug: availity-revenue-cycle-management
common:
- title: ''
  type: Website
  url: https://www.availity.com
- title: ''
  type: Portal
  url: https://developer.availity.com/
- title: ''
  type: Documentation
  url: https://developer.availity.com/partner/documentation
- title: ''
  type: GettingStarted
  url: https://developer.availity.com/partner/gettingstarted
- title: ''
  type: Documentation
  url: https://developer.availity.com/blog/2025/3/25/availity-api-guide
- title: ''
  type: Support
  url: https://developer.availity.com/partner/contact-us
- title: ''
  type: TermsOfService
  url: https://www.availity.com/terms-of-use/
- title: ''
  type: PrivacyPolicy
  url: https://www.availity.com/Privacy-Policy/
- title: ''
  type: GitHubOrganization
  url: https://github.com/availity
- title: ''
  type: SDK
  url: https://availity.github.io/sdk-js/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-eligibility-openapi.yml
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-claim-status-openapi.yml
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-claim-attachments-openapi.yml
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-service-reviews-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-schema/availity-eligibility-schema.json
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-eligibility-context.jsonld
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-claim-context.jsonld
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-service-context.jsonld
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/rules/availity-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/vocabulary/availity-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/capabilities/availity-revenue-cycle-management.yaml
created: ''
description: Availity is a healthcare information network and clearinghouse providing REST APIs for real-time HIPAA EDI transactions. The platform processes over 11 billion annual healthcare transactions connecting providers, health plans, and vendors nationwide. Create your application and subscribe to a plan to make use of Availity APIs for eligibility verification, claims management, prior authorization, and patient cost estimation.
features:
- description: Client credentials grant flow with 5-minute token expiration and HTTPS/TLS encryption for secure API access.
  name: OAuth 2.0 Authentication
- description: Processing over 8.8 million daily transactions and 11 billion annual healthcare transactions across all major health plans.
  name: Real-Time EDI Transactions
- description: Access to every major health plan nationwide and over 1 million providers through the Availity clearinghouse.
  name: Nationwide Payer Network
- description: Returns JSON and XML representations including errors using HTTP response codes. Supports CSV, PDF, PNG, and XLS for specific endpoints.
  name: Multi-Format Responses
- description: Collection resources support offset/limit pagination with limit range of 1-50 items per request with link relations.
  name: Cursor-Based Pagination
- description: Demo subscriptions support custom response selection via X-Api-Mock-Scenario-ID and X-Api-Mock-Response headers.
  name: Mock/Sandbox Testing
- description: Standard tier provides 100,000 calls per day and 100 calls per second for HIPAA transaction APIs.
  name: Rate Limiting
- description: Full support for HIPAA EDI version 005010 transactions including 270/271, 276/277, 278, and 835 transaction sets.
  name: ASC X12 EDI Standards
image: ''
integrations:
- description: Integrates with electronic health record systems to embed eligibility and claims workflows into clinical workflows.
  name: EHR Systems
- description: Connects practice management software to payer networks for revenue cycle management and claims processing.
  name: Practice Management Systems
- description: Integrates with RCM platforms to automate eligibility verification, claim submission, and payment reconciliation.
  name: Revenue Cycle Management Platforms
- description: Direct integration with BCBS plans nationwide for eligibility, claims, and prior authorization transactions.
  name: Blue Cross Blue Shield Plans
- description: Integration with Humana for care reminders, eligibility verification, and claims processing.
  name: Humana
- description: Integration with Molina Healthcare for eligibility and benefits verification and care reminders.
  name: Molina Healthcare
- description: Integration with Florida Blue for care reminders and real-time eligibility verification.
  name: Florida Blue
- description: Integration with Healthfirst New York for eligibility and care gap identification.
  name: Healthfirst New York
jsonld:
- class_count: 2
  name: Availity Availity Context
  property_count: 32
  slug: availity-availity-context
- class_count: 9
  name: Availity Claim Context
  property_count: 45
  slug: availity-claim-context
- class_count: 0
  name: Availity Context
  property_count: 5
  slug: availity-context
- class_count: 15
  name: Availity Eligibility Context
  property_count: 58
  slug: availity-eligibility-context
- class_count: 8
  name: Availity Service Context
  property_count: 30
  slug: availity-service-context
layout: provider
modified: '2026-04-19'
name: availity
skills: []
slug: availity
solutions: []
source_yaml: "aid: availity\nurl: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/apis.yml\napis:\n  - aid: availity:availity-eligibility-benefits-api\n    name: Availity Eligibility & Benefits API\n    tags:\n      - Benefits\n      - EDI\n      - Eligibility\n      - Healthcare\n      - X12 270/271\n    image: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/image.png\n    humanURL: https://developer.availity.com/\n    baseURL: https://api.availity.com\n    properties:\n      - url: https://developer.availity.com/partner/documentation\n        type: Documentation\n      - url: https://developer.availity.com/partner/gettingstarted\n        type: GettingStarted\n      - url: https://developer.availity.com/blog/2025/3/4/ebvalue-add-api\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-eligibility-openapi.yml\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-schema/availity-eligibility-schema.json\n\
  \        type: JSONSchema\n    description: >-\n      The Availity Eligibility & Benefits API supports the ASC X12N 270 and 271 transactions,\n      enabling real-time verification of member coverage, co-pays, deductibles, and\n      benefits information. REST APIs connect provider systems to every major health\n      plan nationwide for eligibility checks.\n\n  - aid: availity:availity-claims-status-api\n    name: Availity Claim Status API\n    tags:\n      - Claims\n      - Clearinghouse\n      - EDI\n      - Healthcare\n      - X12 276/277\n    image: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/image.png\n    humanURL: https://developer.availity.com/\n    baseURL: https://api.availity.com\n    properties:\n      - url: https://developer.availity.com/partner/documentation\n        type: Documentation\n      - url: https://developer.availity.com/blog/2025/3/25/enhanced-claim-status\n        type: Documentation\n      - url: https://developer.availity.com/partner/gettingstarted\n\
  \        type: GettingStarted\n      - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-claim-status-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Availity Claim Status API enables the standard ASC X12N 276 and 277 transactions,\n      allowing providers to find, create, and manage claim status inquiries against\n      payer systems. REST APIs bridge provider billing systems and payers through\n      the Availity clearinghouse network. Supports both standard 276/277 workflows\n      and enhanced claim status with summary and detail search.\n\n  - aid: availity:availity-claim-attachments-api\n    name: Availity Claim Attachments API\n    tags:\n      - Attachments\n      - Claims\n      - Clearinghouse\n      - EDI\n      - Healthcare\n    image: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/image.png\n    humanURL: https://developer.availity.com/\n    baseURL: https://api.availity.com\n    properties:\n\
  \      - url: https://developer.availity.com/blog/2025/2/28/claim-attachment-api\n        type: Documentation\n      - url: https://developer.availity.com/partner/gettingstarted\n        type: GettingStarted\n      - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-claim-attachments-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Availity Claim Attachments API enables electronic submission of supporting\n      documentation alongside healthcare claims. REST APIs support structured and\n      unstructured attachment types for additional clinical information required by\n      payers during claims adjudication.\n\n  - aid: availity:availity-service-reviews-api\n    name: Availity Service Reviews (Prior Authorization) API\n    tags:\n      - EDI\n      - Healthcare\n      - Prior Authorization\n      - Service Reviews\n      - X12 278\n    image: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/image.png\n\
  \    humanURL: https://developer.availity.com/\n    baseURL: https://api.availity.com\n    properties:\n      - url: https://developer.availity.com/blog/2025/3/4/service-reviews\n        type: Documentation\n      - url: https://developer.availity.com/partner/gettingstarted\n        type: GettingStarted\n      - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-service-reviews-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Availity Service Reviews API enables the ASC X12N 278 transaction for prior\n      authorization and healthcare service review. REST APIs allow providers to find,\n      create, and manage authorization requests and responses with health plan payers\n      through the Availity clearinghouse. Includes IsAuthRequired and Attachments add-on APIs.\n\n  - aid: availity:availity-hipaa-transactions-api\n    name: Availity Healthcare HIPAA Transactions API\n    tags:\n      - Clearinghouse\n      - EDI\n     \
  \ - Healthcare\n      - HIPAA\n    image: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/image.png\n    humanURL: https://developer.availity.com/portal/catalogue-products/healthcare-hipaa-transactions-1\n    baseURL: https://api.availity.com\n    properties:\n      - url: https://developer.availity.com/portal/catalogue-products/healthcare-hipaa-transactions-1\n        type: Documentation\n      - url: https://developer.availity.com/blog/2025/3/25/hipaa-transactions\n        type: Documentation\n      - url: https://developer.availity.com/partner/gettingstarted\n        type: GettingStarted\n    description: >-\n      The Availity Healthcare HIPAA Transactions API provides a unified interface\n      for standard HIPAA EDI transactions. REST APIs enable healthcare providers and\n      vendors to submit and receive X12 EDI transactions across payers including eligibility,\n      claims, remittance, authorizations, and referrals. Quota: 100,000 calls per day,\n \
  \     100 calls per second rate limit.\n\n  - aid: availity:availity-patient-cost-estimator-api\n    name: Availity Patient Cost Estimator API\n    tags:\n      - Cost Estimation\n      - Healthcare\n      - Patient Financial Responsibility\n      - Price Transparency\n    image: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/image.png\n    humanURL: https://developer.availity.com/\n    baseURL: https://api.availity.com\n    properties:\n      - url: https://developer.availity.com/partner/documentation\n        type: Documentation\n      - url: https://developer.availity.com/partner/gettingstarted\n        type: GettingStarted\n    description: >-\n      The Availity Patient Cost Estimator API enables healthcare providers and institutions\n      to estimate service costs before delivery for both institutional and professional\n      services. REST APIs support version 1.0.0 and 2.0.0 and include predetermination\n      requests across all major health plan payers,\
  \ helping meet price transparency requirements.\n\n  - aid: availity:availity-eb-value-adds-api\n    name: Availity Eligibility & Benefits Value-Add APIs\n    tags:\n      - Care Reminders\n      - EDI\n      - Eligibility\n      - Healthcare\n      - Member ID Card\n    image: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/image.png\n    humanURL: https://developer.availity.com/\n    baseURL: https://api.availity.com\n    properties:\n      - url: https://developer.availity.com/blog/2025/3/4/ebvalue-add-api\n        type: Documentation\n      - url: https://developer.availity.com/partner/gettingstarted\n        type: GettingStarted\n    description: >-\n      The Availity Eligibility & Benefits Value-Add APIs provide supplementary data\n      during eligibility transactions. The Care Reminders API retrieves real-time care\n      gap information from multiple payers. The Member ID Card API retrieves digital\n      member ID cards in PDF or PNG format during eligibility\
  \ verification workflows.\n\n  - aid: availity:availity-payer-list-api\n    name: Availity Payer List API\n    tags:\n      - Clearinghouse\n      - Healthcare\n      - Payer Network\n      - Reference Data\n    image: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/image.png\n    humanURL: https://developer.availity.com/\n    baseURL: https://api.availity.com\n    properties:\n      - url: https://developer.availity.com/partner/documentation\n        type: Documentation\n      - url: https://developer.availity.com/partner/gettingstarted\n        type: GettingStarted\n    description: >-\n      The Availity Payer List API (v1.0.4) allows healthcare organizations to query\n      available payers and the transactions they support. Returns payer identifiers,\n      names, and supported transaction types including eligibility, claim status,\n      prior authorization, and remittance across the nationwide Availity clearinghouse network.\n\n  - aid: availity:availity-configurations-api\n\
  \    name: Availity Configurations API\n    tags:\n      - Configuration\n      - Healthcare\n      - Payer Requirements\n      - Provider Validation\n    image: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/image.png\n    humanURL: https://developer.availity.com/\n    baseURL: https://api.availity.com\n    properties:\n      - url: https://developer.availity.com/partner/documentation\n        type: Documentation\n      - url: https://developer.availity.com/partner/gettingstarted\n        type: GettingStarted\n    description: >-\n      The Availity Configurations API (v1.0.0) provides provider details and payer-specific\n      validation requirements. Returns configuration rules for enhanced claim status, prior\n      authorization, and other transaction types so provider systems can validate submissions\n      before sending to payers.\n\ncommon:\n  - url: https://www.availity.com\n    type: Website\n  - url: https://developer.availity.com/\n    type: Portal\n\
  \  - url: https://developer.availity.com/partner/documentation\n    type: Documentation\n  - url: https://developer.availity.com/partner/gettingstarted\n    type: GettingStarted\n  - url: https://developer.availity.com/blog/2025/3/25/availity-api-guide\n    type: Documentation\n  - url: https://developer.availity.com/partner/contact-us\n    type: Support\n  - url: https://www.availity.com/terms-of-use/\n    type: TermsOfService\n  - url: https://www.availity.com/Privacy-Policy/\n    type: PrivacyPolicy\n  - url: https://github.com/availity\n    type: GitHubOrganization\n  - url: https://availity.github.io/sdk-js/\n    type: SDK\n  - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-eligibility-openapi.yml\n    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-claim-status-openapi.yml\n    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-claim-attachments-openapi.yml\n\
  \    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/openapi/availity-service-reviews-openapi.yml\n    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-schema/availity-eligibility-schema.json\n    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-eligibility-context.jsonld\n    type: JSONLD\n  - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-claim-context.jsonld\n    type: JSONLD\n  - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-service-context.jsonld\n    type: JSONLD\n  - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/rules/availity-spectral-rules.yml\n    type: SpectralRules\n  - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/vocabulary/availity-vocabulary.yaml\n\
  \    type: Vocabulary\n  - url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/capabilities/availity-revenue-cycle-management.yaml\n    type: NaftikoCapability\n  - type: Features\n    data:\n      - name: OAuth 2.0 Authentication\n        description: Client credentials grant flow with 5-minute token expiration and HTTPS/TLS encryption for secure API access.\n      - name: Real-Time EDI Transactions\n        description: Processing over 8.8 million daily transactions and 11 billion annual healthcare transactions across all major health plans.\n      - name: Nationwide Payer Network\n        description: Access to every major health plan nationwide and over 1 million providers through the Availity clearinghouse.\n      - name: Multi-Format Responses\n        description: Returns JSON and XML representations including errors using HTTP response codes. Supports CSV, PDF, PNG, and XLS for specific endpoints.\n      - name: Cursor-Based Pagination\n        description:\
  \ Collection resources support offset/limit pagination with limit range of 1-50 items per request with link relations.\n      - name: Mock/Sandbox Testing\n        description: Demo subscriptions support custom response selection via X-Api-Mock-Scenario-ID and X-Api-Mock-Response headers.\n      - name: Rate Limiting\n        description: Standard tier provides 100,000 calls per day and 100 calls per second for HIPAA transaction APIs.\n      - name: ASC X12 EDI Standards\n        description: Full support for HIPAA EDI version 005010 transactions including 270/271, 276/277, 278, and 835 transaction sets.\n  - type: UseCases\n    data:\n      - name: Real-Time Eligibility Verification\n        description: Verify patient insurance coverage, co-pays, deductibles, and benefits in real time before scheduling or rendering services.\n      - name: Claim Status Tracking\n        description: Track submitted claims through adjudication, checking ACKNOWLEDGED, PENDING, PAID, DENIED, and ADJUSTED\
  \ statuses.\n      - name: Prior Authorization Management\n        description: Submit and track prior authorization requests using X12 278 transactions to check if authorization is required before service delivery.\n      - name: Patient Cost Estimation\n        description: Estimate patient out-of-pocket costs before services are rendered to meet price transparency requirements and inform patients.\n      - name: Electronic Claim Attachments\n        description: Electronically attach clinical documentation to claims and authorizations, reducing manual faxing and accelerating adjudication.\n      - name: Care Gap Identification\n        description: Retrieve real-time care reminders during eligibility checks to identify preventive care gaps and coordinate outreach.\n      - name: Digital Member ID Cards\n        description: Retrieve member ID cards digitally during eligibility verification, reducing administrative burden and improving patient experience.\n      - name: Multi-Payer Data\
  \ Consolidation\n        description: Connect to all major payers through a single clearinghouse API rather than managing individual payer connections.\n  - type: Integrations\n    data:\n      - name: EHR Systems\n        description: Integrates with electronic health record systems to embed eligibility and claims workflows into clinical workflows.\n      - name: Practice Management Systems\n        description: Connects practice management software to payer networks for revenue cycle management and claims processing.\n      - name: Revenue Cycle Management Platforms\n        description: Integrates with RCM platforms to automate eligibility verification, claim submission, and payment reconciliation.\n      - name: Blue Cross Blue Shield Plans\n        description: Direct integration with BCBS plans nationwide for eligibility, claims, and prior authorization transactions.\n      - name: Humana\n        description: Integration with Humana for care reminders, eligibility verification,\
  \ and claims processing.\n      - name: Molina Healthcare\n        description: Integration with Molina Healthcare for eligibility and benefits verification and care reminders.\n      - name: Florida Blue\n        description: Integration with Florida Blue for care reminders and real-time eligibility verification.\n      - name: Healthfirst New York\n        description: Integration with Healthfirst New York for eligibility and care gap identification.\n\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n\nmodified: '2026-04-19'\ndescription: >-\n  Availity is a healthcare information network and clearinghouse providing REST APIs\n  for real-time HIPAA EDI transactions. The platform processes over 11 billion annual\n  healthcare transactions connecting providers, health plans, and vendors nationwide.\n  Create your application and subscribe to a plan to make use of Availity APIs for\n  eligibility verification, claims management, prior authorization, and patient cost\
  \ estimation.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/apis.yml
use_cases:
- description: Verify patient insurance coverage, co-pays, deductibles, and benefits in real time before scheduling or rendering services.
  name: Real-Time Eligibility Verification
- description: Track submitted claims through adjudication, checking ACKNOWLEDGED, PENDING, PAID, DENIED, and ADJUSTED statuses.
  name: Claim Status Tracking
- description: Submit and track prior authorization requests using X12 278 transactions to check if authorization is required before service delivery.
  name: Prior Authorization Management
- description: Estimate patient out-of-pocket costs before services are rendered to meet price transparency requirements and inform patients.
  name: Patient Cost Estimation
- description: Electronically attach clinical documentation to claims and authorizations, reducing manual faxing and accelerating adjudication.
  name: Electronic Claim Attachments
- description: Retrieve real-time care reminders during eligibility checks to identify preventive care gaps and coordinate outreach.
  name: Care Gap Identification
- description: Retrieve member ID cards digitally during eligibility verification, reducing administrative burden and improving patient experience.
  name: Digital Member ID Cards
- description: Connect to all major payers through a single clearinghouse API rather than managing individual payer connections.
  name: Multi-Payer Data Consolidation
---
