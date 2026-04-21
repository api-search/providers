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
