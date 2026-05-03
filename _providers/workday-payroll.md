---
api_count: 4
api_specs:
- filename: workday-payroll-payroll-openapi.yml
  format: yaml
  label: Workday Payroll API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/openapi/workday-payroll-payroll-openapi.yml
- filename: workday-payroll-payroll-results-openapi.yml
  format: yaml
  label: Workday Payroll Results API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/openapi/workday-payroll-payroll-results-openapi.yml
- filename: workday-payroll-payroll-input-openapi.yml
  format: yaml
  label: Workday Payroll Input API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/openapi/workday-payroll-payroll-input-openapi.yml
- filename: workday-payroll-tax-openapi.yml
  format: yaml
  label: Workday Tax API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/openapi/workday-payroll-tax-openapi.yml
apis:
- description: Core API for managing payroll processes including payroll calculations, employee pay data, deductions, earnings, and payroll runs.
  name: Workday Payroll API
  slug: ''
- description: API for retrieving payroll calculation results, payment details, and historical payroll data.
  name: Workday Payroll Results API
  slug: ''
- description: API for submitting and managing payroll input data including one-time payments, adjustments, and supplemental earnings.
  name: Workday Payroll Input API
  slug: ''
- description: API for managing payroll tax calculations, tax withholdings, and tax filing information.
  name: Workday Tax API
  slug: ''
capabilities:
- description: Unified capability for end-to-end payroll processing workflows combining the Workday Payroll, Payroll Input, Payroll Results, and Tax APIs. Supports HR administrators and payroll specialists running p
  name: Workday Payroll Processing
  slug: payroll-processing
common:
- title: ''
  type: DeveloperPortal
  url: https://community.workday.com/
- title: ''
  type: GettingStarted
  url: https://doc.workday.com/developer/studio/en-us/getting-started.html
- title: ''
  type: Authentication
  url: https://doc.workday.com/admin-guide/en-us/authentication/authentication.html
- title: ''
  type: TermsOfService
  url: https://www.workday.com/en-us/legal.html
- title: ''
  type: PrivacyPolicy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: StatusPage
  url: https://status.workday.com/
- title: ''
  type: Security
  url: https://www.workday.com/en-us/why-workday/security.html
- title: ''
  type: JSON-LD
  url: json-ld/workday-payroll-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/workday-payroll-pay-run-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/workday-payroll-payslip-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/workday-payroll-pay-run-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/workday-payroll-payslip-structure.json
- title: ''
  type: Example
  url: examples/workday-payroll-pay-run-example.json
- title: ''
  type: Example
  url: examples/workday-payroll-payslip-example.json
- title: ''
  type: SpectralRules
  url: rules/workday-payroll-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/payroll-processing.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/workday-payroll-vocabulary.yml
- title: Report-as-a-Service Python Client
  type: Tools
  url: https://github.com/Workday/raas-python
- title: Workday Everywhere SDK
  type: Tools
  url: https://github.com/Workday/everywhere
- title: Agent System of Record API
  type: Tools
  url: https://github.com/Workday/asor
created: '2024-01-01'
description: Workday Payroll provides comprehensive APIs for managing payroll operations, employee compensation, tax calculations, and payment processing within the Workday platform.
features:
- description: Process payroll across multiple countries with configurable calculation logic, pay components, and statutory rules.
  name: Global Payroll Engine
- description: Create, schedule, and execute payroll runs with full visibility into calculation status and results.
  name: Pay Run Management
- description: Configure and apply earnings, deductions, accumulations, and balances per worker, organization, or pay group.
  name: Earnings and Deductions
- description: Automated tax calculations and withholdings with support for federal, state, local, and international jurisdictions.
  name: Tax Calculation and Withholding
- description: Submit one-time payments, retroactive adjustments, and supplemental earnings outside of scheduled pay runs.
  name: Payroll Input Processing
- description: Produce worker-facing payslips and pay statements with detailed breakdowns of earnings, deductions, and taxes.
  name: Payslip Generation
- description: Generate statutory and compliance reports including tax filings, year-end forms, and audit trails.
  name: Compliance Reporting
- description: Surface pay history, payslips, and tax documents to workers via Workday Mobile and the Workday user experience.
  name: Worker Self-Service
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integrated source of worker, organization, compensation, and time tracking data feeding payroll calculations.
  name: Workday Human Capital Management
- description: Posts payroll journal entries and accruals into the Workday general ledger.
  name: Workday Financial Management
- description: Feeds approved time and absence data into payroll calculations.
  name: Workday Time Tracking
- description: Provides benefit elections and deductions consumed by payroll.
  name: Workday Benefits
- description: Visual integration tool for building inbound and outbound payroll integrations.
  name: Workday Studio
- description: Pre-built integrations to third-party payroll providers and tax filing services.
  name: Workday Cloud Connect for Third-Party Payroll
- description: Generates ACH and international payment files for direct deposit and payroll disbursements.
  name: Banking and Payment Networks
jsonld:
- class_count: 0
  name: Workday Payroll Context
  property_count: 12
  slug: workday-payroll-context
- class_count: 23
  name: Workday Payroll Payroll Context
  property_count: 49
  slug: workday-payroll-payroll-context
- class_count: 19
  name: Workday Payroll Payroll Input Context
  property_count: 30
  slug: workday-payroll-payroll-input-context
- class_count: 14
  name: Workday Payroll Payroll Results Context
  property_count: 53
  slug: workday-payroll-payroll-results-context
- class_count: 15
  name: Workday Payroll Tax Context
  property_count: 46
  slug: workday-payroll-tax-context
layout: provider
modified: '2026-05-03'
name: Workday Payroll
rules:
- name: Workday Payroll API Rules
  rule_count: 63
  severity_counts:
    error: 21
    hint: 0
    info: 4
    warn: 38
  slug: workday-payroll-spectral-rules
skills: []
slug: workday-payroll
solutions:
- description: Full-service payroll solution for U.S. employers including federal, state, and local tax calculation and filing support.
  name: Workday Payroll for the U.S.
- description: Payroll solution covering Canadian federal and provincial requirements.
  name: Workday Payroll for Canada
- description: U.K. payroll with HMRC reporting and statutory pay support.
  name: Workday Payroll for the U.K.
- description: French payroll covering DSN reporting and statutory rules.
  name: Workday Payroll for France
- description: Connectors and data feeds for customers running payroll on a third-party provider while using Workday HCM.
  name: Workday Cloud Connect for Third-Party Payroll
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: workday-payroll\nname: Workday Payroll\ndescription: Workday Payroll provides comprehensive APIs for managing payroll operations, employee compensation, tax calculations, and payment processing within the Workday platform.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - name: Workday Payroll API\n    description: Core API for managing payroll processes including payroll calculations, employee pay data, deductions, earnings, and payroll runs.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanURL: https://www.workday.com/en-us/products/payroll-management.html\n    baseURL: https://api.workday.com/payroll/v1\n    tags:\n      - Compensation\n      - Deductions\n      - Earnings\n      - Pay-Runs\n      -\
  \ Payroll\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n      - type: OpenAPI\n        url: openapi/workday-payroll-payroll-openapi.yml\n      - type: Authentication\n        url: https://doc.workday.com/admin-guide/en-us/authentication/authentication.html\n      - type: APIConsole\n        url: https://community.workday.com/api-console\n      - type: RateLimits\n        url: https://doc.workday.com/admin-guide/en-us/api-reference/api-rate-limiting.html\n      - type: JSON-LD\n        url: json-ld/workday-payroll-payroll-context.jsonld\n      - type: JSONSchema\n        url: json-schema/payroll-calculation-status-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-create-pay-run-request-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-deduction-code-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-deduction-code-ref-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/payroll-deduction-code-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-deduction-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-deduction-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-earning-code-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-earning-code-ref-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-earning-code-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-earning-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-earning-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-pay-group-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-pay-group-ref-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-pay-group-schema.json\n      - type: JSONSchema\n        url:\
  \ json-schema/payroll-pay-period-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-pay-run-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-pay-run-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-update-pay-run-request-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-worker-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-worker-payroll-details-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-worker-ref-schema.json\n      - type: JSONStructure\n        url: json-structure/payroll-calculation-status-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-create-pay-run-request-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-deduction-code-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-deduction-code-ref-structure.json\n      - type:\
  \ JSONStructure\n        url: json-structure/payroll-deduction-code-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-deduction-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-deduction-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-earning-code-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-earning-code-ref-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-earning-code-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-earning-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-earning-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-pay-group-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-pay-group-ref-structure.json\n      - type: JSONStructure\n        url:\
  \ json-structure/payroll-pay-group-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-pay-period-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-pay-run-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-pay-run-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-update-pay-run-request-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-worker-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-worker-payroll-details-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-worker-ref-structure.json\n      - type: Example\n        url: examples/payroll-calculation-status-example.json\n      - type: Example\n        url: examples/payroll-create-pay-run-request-example.json\n      - type: Example\n        url: examples/payroll-deduction-code-collection-example.json\n\
  \      - type: Example\n        url: examples/payroll-deduction-code-example.json\n      - type: Example\n        url: examples/payroll-deduction-code-ref-example.json\n      - type: Example\n        url: examples/payroll-deduction-collection-example.json\n      - type: Example\n        url: examples/payroll-deduction-example.json\n      - type: Example\n        url: examples/payroll-earning-code-collection-example.json\n      - type: Example\n        url: examples/payroll-earning-code-example.json\n      - type: Example\n        url: examples/payroll-earning-code-ref-example.json\n      - type: Example\n        url: examples/payroll-earning-collection-example.json\n      - type: Example\n        url: examples/payroll-earning-example.json\n      - type: Example\n        url: examples/payroll-pay-group-collection-example.json\n      - type: Example\n        url: examples/payroll-pay-group-example.json\n      - type: Example\n        url: examples/payroll-pay-group-ref-example.json\n   \
  \   - type: Example\n        url: examples/payroll-pay-period-example.json\n      - type: Example\n        url: examples/payroll-pay-run-collection-example.json\n      - type: Example\n        url: examples/payroll-pay-run-example.json\n      - type: Example\n        url: examples/payroll-update-pay-run-request-example.json\n      - type: Example\n        url: examples/payroll-worker-collection-example.json\n      - type: Example\n        url: examples/payroll-worker-payroll-details-example.json\n      - type: Example\n        url: examples/payroll-worker-ref-example.json\n      - type: Example\n        url: examples/workday-payroll-list-pay-runs-example.json\n      - type: NaftikoCapability\n        url: capabilities/shared/payroll.yaml\n    contact:\n      - type: support\n        url: https://www.workday.com/en-us/company/customer-support.html\n      - type: email\n        url: support@workday.com\n  - name: Workday Payroll Results API\n    description: API for retrieving payroll calculation\
  \ results, payment details, and historical payroll data.\n    humanURL: https://www.workday.com/en-us/products/payroll-management.html\n    baseURL: https://api.workday.com/payroll-results/v1\n    tags:\n      - History\n      - Payments\n      - Payroll-Results\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n      - type: OpenAPI\n        url: openapi/workday-payroll-payroll-results-openapi.yml\n      - type: JSON-LD\n        url: json-ld/workday-payroll-payroll-results-context.jsonld\n      - type: JSONSchema\n        url: json-schema/payroll-results-pay-period-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-results-pay-run-result-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-results-payment-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-results-payment-election-collection-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/payroll-results-payment-election-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-results-payment-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-results-payslip-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-results-payslip-deduction-line-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-results-payslip-earning-line-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-results-payslip-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-results-payslip-tax-line-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-results-worker-ref-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-results-worker-result-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-results-worker-result-schema.json\n      - type: JSONStructure\n      \
  \  url: json-structure/payroll-results-pay-period-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-results-pay-run-result-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-results-payment-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-results-payment-election-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-results-payment-election-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-results-payment-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-results-payslip-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-results-payslip-deduction-line-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-results-payslip-earning-line-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-results-payslip-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/payroll-results-payslip-tax-line-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-results-worker-ref-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-results-worker-result-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-results-worker-result-structure.json\n      - type: Example\n        url: examples/payroll-results-pay-period-example.json\n      - type: Example\n        url: examples/payroll-results-pay-run-result-example.json\n      - type: Example\n        url: examples/payroll-results-payment-collection-example.json\n      - type: Example\n        url: examples/payroll-results-payment-election-collection-example.json\n      - type: Example\n        url: examples/payroll-results-payment-election-example.json\n      - type: Example\n        url: examples/payroll-results-payment-example.json\n      - type: Example\n    \
  \    url: examples/payroll-results-payslip-collection-example.json\n      - type: Example\n        url: examples/payroll-results-payslip-deduction-line-example.json\n      - type: Example\n        url: examples/payroll-results-payslip-earning-line-example.json\n      - type: Example\n        url: examples/payroll-results-payslip-example.json\n      - type: Example\n        url: examples/payroll-results-payslip-tax-line-example.json\n      - type: Example\n        url: examples/payroll-results-worker-ref-example.json\n      - type: Example\n        url: examples/payroll-results-worker-result-collection-example.json\n      - type: Example\n        url: examples/payroll-results-worker-result-example.json\n      - type: Example\n        url: examples/workday-payroll-get-worker-payslip-example.json\n      - type: NaftikoCapability\n        url: capabilities/shared/payroll-results.yaml\n  - name: Workday Payroll Input API\n    description: API for submitting and managing payroll input data including\
  \ one-time payments, adjustments, and supplemental earnings.\n    humanURL: https://www.workday.com/en-us/products/payroll-management.html\n    baseURL: https://api.workday.com/payroll-input/v1\n    tags:\n      - Adjustments\n      - One-Time-Payments\n      - Payroll-Input\n      - Supplemental-Earnings\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n      - type: OpenAPI\n        url: openapi/workday-payroll-payroll-input-openapi.yml\n      - type: JSON-LD\n        url: json-ld/workday-payroll-payroll-input-context.jsonld\n      - type: JSONSchema\n        url: json-schema/payroll-input-adjustment-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-adjustment-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-create-adjustment-request-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-create-input-batch-request-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/payroll-input-create-one-time-payment-request-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-create-supplemental-earning-request-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-create-time-off-input-request-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-input-batch-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-input-batch-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-input-record-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-one-time-payment-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-one-time-payment-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-supplemental-earning-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-supplemental-earning-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/payroll-input-time-off-input-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-time-off-input-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-update-one-time-payment-request-schema.json\n      - type: JSONSchema\n        url: json-schema/payroll-input-worker-ref-schema.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-adjustment-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-adjustment-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-create-adjustment-request-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-create-input-batch-request-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-create-one-time-payment-request-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-create-supplemental-earning-request-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/payroll-input-create-time-off-input-request-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-input-batch-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-input-batch-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-input-record-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-one-time-payment-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-one-time-payment-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-supplemental-earning-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-supplemental-earning-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-time-off-input-collection-structure.json\n      - type:\
  \ JSONStructure\n        url: json-structure/payroll-input-time-off-input-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-update-one-time-payment-request-structure.json\n      - type: JSONStructure\n        url: json-structure/payroll-input-worker-ref-structure.json\n      - type: Example\n        url: examples/payroll-input-adjustment-collection-example.json\n      - type: Example\n        url: examples/payroll-input-adjustment-example.json\n      - type: Example\n        url: examples/payroll-input-create-adjustment-request-example.json\n      - type: Example\n        url: examples/payroll-input-create-input-batch-request-example.json\n      - type: Example\n        url: examples/payroll-input-create-one-time-payment-request-example.json\n      - type: Example\n        url: examples/payroll-input-create-supplemental-earning-request-example.json\n      - type: Example\n        url: examples/payroll-input-create-time-off-input-request-example.json\n\
  \      - type: Example\n        url: examples/payroll-input-input-batch-collection-example.json\n      - type: Example\n        url: examples/payroll-input-input-batch-example.json\n      - type: Example\n        url: examples/payroll-input-input-record-example.json\n      - type: Example\n        url: examples/payroll-input-one-time-payment-collection-example.json\n      - type: Example\n        url: examples/payroll-input-one-time-payment-example.json\n      - type: Example\n        url: examples/payroll-input-supplemental-earning-collection-example.json\n      - type: Example\n        url: examples/payroll-input-supplemental-earning-example.json\n      - type: Example\n        url: examples/payroll-input-time-off-input-collection-example.json\n      - type: Example\n        url: examples/payroll-input-time-off-input-example.json\n      - type: Example\n        url: examples/payroll-input-update-one-time-payment-request-example.json\n      - type: Example\n        url: examples/payroll-input-worker-ref-example.json\n\
  \      - type: Example\n        url: examples/workday-payroll-create-one-time-payment-example.json\n      - type: NaftikoCapability\n        url: capabilities/shared/payroll-input.yaml\n  - name: Workday Tax API\n    description: API for managing payroll tax calculations, tax withholdings, and tax filing information.\n    humanURL: https://www.workday.com/en-us/products/payroll-management.html\n    baseURL: https://api.workday.com/tax/v1\n    tags:\n      - Compliance\n      - Tax\n      - Tax-Filing\n      - Withholdings\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n      - type: OpenAPI\n        url: openapi/workday-payroll-tax-openapi.yml\n      - type: JSON-LD\n        url: json-ld/workday-payroll-tax-context.jsonld\n      - type: JSONSchema\n        url: json-schema/tax-create-tax-election-request-schema.json\n      - type: JSONSchema\n        url: json-schema/tax-tax-election-collection-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/tax-tax-election-schema.json\n      - type: JSONSchema\n        url: json-schema/tax-tax-filing-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/tax-tax-filing-schema.json\n      - type: JSONSchema\n        url: json-schema/tax-tax-jurisdiction-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/tax-tax-jurisdiction-ref-schema.json\n      - type: JSONSchema\n        url: json-schema/tax-tax-jurisdiction-schema.json\n      - type: JSONSchema\n        url: json-schema/tax-tax-result-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/tax-tax-result-schema.json\n      - type: JSONSchema\n        url: json-schema/tax-tax-withholding-collection-schema.json\n      - type: JSONSchema\n        url: json-schema/tax-tax-withholding-schema.json\n      - type: JSONSchema\n        url: json-schema/tax-update-tax-withholding-request-schema.json\n      - type: JSONSchema\n     \
  \   url: json-schema/tax-worker-ref-schema.json\n      - type: JSONSchema\n        url: json-schema/tax-worker-tax-summary-schema.json\n      - type: JSONStructure\n        url: json-structure/tax-create-tax-election-request-structure.json\n      - type: JSONStructure\n        url: json-structure/tax-tax-election-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/tax-tax-election-structure.json\n      - type: JSONStructure\n        url: json-structure/tax-tax-filing-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/tax-tax-filing-structure.json\n      - type: JSONStructure\n        url: json-structure/tax-tax-jurisdiction-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/tax-tax-jurisdiction-ref-structure.json\n      - type: JSONStructure\n        url: json-structure/tax-tax-jurisdiction-structure.json\n      - type: JSONStructure\n        url: json-structure/tax-tax-result-collection-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/tax-tax-result-structure.json\n      - type: JSONStructure\n        url: json-structure/tax-tax-withholding-collection-structure.json\n      - type: JSONStructure\n        url: json-structure/tax-tax-withholding-structure.json\n      - type: JSONStructure\n        url: json-structure/tax-update-tax-withholding-request-structure.json\n      - type: JSONStructure\n        url: json-structure/tax-worker-ref-structure.json\n      - type: JSONStructure\n        url: json-structure/tax-worker-tax-summary-structure.json\n      - type: Example\n        url: examples/tax-create-tax-election-request-example.json\n      - type: Example\n        url: examples/tax-tax-election-collection-example.json\n      - type: Example\n        url: examples/tax-tax-election-example.json\n      - type: Example\n        url: examples/tax-tax-filing-collection-example.json\n      - type: Example\n        url: examples/tax-tax-filing-example.json\n      - type:\
  \ Example\n        url: examples/tax-tax-jurisdiction-collection-example.json\n      - type: Example\n        url: examples/tax-tax-jurisdiction-example.json\n      - type: Example\n        url: examples/tax-tax-jurisdiction-ref-example.json\n      - type: Example\n        url: examples/tax-tax-result-collection-example.json\n      - type: Example\n        url: examples/tax-tax-result-example.json\n      - type: Example\n        url: examples/tax-tax-withholding-collection-example.json\n      - type: Example\n        url: examples/tax-tax-withholding-example.json\n      - type: Example\n        url: examples/tax-update-tax-withholding-request-example.json\n      - type: Example\n        url: examples/tax-worker-ref-example.json\n      - type: Example\n        url: examples/tax-worker-tax-summary-example.json\n      - type: NaftikoCapability\n        url: capabilities/shared/payroll-tax.yaml\ncommon:\n  - type: DeveloperPortal\n    url: https://community.workday.com/\n  - type: GettingStarted\n\
  \    url: https://doc.workday.com/developer/studio/en-us/getting-started.html\n  - type: Authentication\n    url: https://doc.workday.com/admin-guide/en-us/authentication/authentication.html\n  - type: TermsOfService\n    url: https://www.workday.com/en-us/legal.html\n  - type: PrivacyPolicy\n    url: https://www.workday.com/en-us/privacy.html\n  - type: StatusPage\n    url: https://status.workday.com/\n  - type: Security\n    url: https://www.workday.com/en-us/why-workday/security.html\n  - type: JSON-LD\n    url: json-ld/workday-payroll-context.jsonld\n  - type: JSONSchema\n    url: json-schema/workday-payroll-pay-run-schema.json\n  - type: JSONSchema\n    url: json-schema/workday-payroll-payslip-schema.json\n  - type: JSONStructure\n    url: json-structure/workday-payroll-pay-run-structure.json\n  - type: JSONStructure\n    url: json-structure/workday-payroll-payslip-structure.json\n  - type: Example\n    url: examples/workday-payroll-pay-run-example.json\n  - type: Example\n    url:\
  \ examples/workday-payroll-payslip-example.json\n  - type: SpectralRules\n    url: rules/workday-payroll-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/payroll-processing.yaml\n  - type: Vocabulary\n    url: vocabulary/workday-payroll-vocabulary.yml\n  - type: Tools\n    url: https://github.com/Workday/raas-python\n    title: Report-as-a-Service Python Client\n  - type: Tools\n    url: https://github.com/Workday/everywhere\n    title: Workday Everywhere SDK\n  - type: Tools\n    url: https://github.com/Workday/asor\n    title: Agent System of Record API\n  - type: Features\n    data:\n      - name: Global Payroll Engine\n        description: Process payroll across multiple countries with configurable calculation logic, pay components, and statutory rules.\n      - name: Pay Run Management\n        description: Create, schedule, and execute payroll runs with full visibility into calculation status and results.\n      - name: Earnings and Deductions\n        description:\
  \ Configure and apply earnings, deductions, accumulations, and balances per worker, organization, or pay group.\n      - name: Tax Calculation and Withholding\n        description: Automated tax calculations and withholdings with support for federal, state, local, and international jurisdictions.\n      - name: Payroll Input Processing\n        description: Submit one-time payments, retroactive adjustments, and supplemental earnings outside of scheduled pay runs.\n      - name: Payslip Generation\n        description: Produce worker-facing payslips and pay statements with detailed breakdowns of earnings, deductions, and taxes.\n      - name: Compliance Reporting\n        description: Generate statutory and compliance reports including tax filings, year-end forms, and audit trails.\n      - name: Worker Self-Service\n        description: Surface pay history, payslips, and tax documents to workers via Workday Mobile and the Workday user experience.\n  - type: UseCases\n    data:\n      -\
  \ name: Multi-Country Payroll Operations\n        description: Run payroll for a global workforce across regions while standardizing on a single platform and data model.\n      - name: Payroll Cycle Automation\n        description: Schedule, execute, and audit recurring payroll runs end-to-end with minimal manual intervention.\n      - name: One-Time Payments and Adjustments\n        description: Submit bonuses, retroactive pay, and corrections programmatically through the Payroll Input API.\n      - name: Tax Filing and Compliance\n        description: Calculate withholdings and produce data feeds for statutory tax filings and year-end reporting.\n      - name: Pay Data Integration\n        description: Sync payroll results into general ledger, banking, benefits, and analytics systems downstream of payroll runs.\n      - name: Worker Pay Transparency\n        description: Provide workers with secure programmatic access to payslips, year-to-date totals, and tax forms.\n  - type: Integrations\n\
  \    data:\n      - name: Workday Human Capital Management\n        description: Integrated source of worker, organization, compensation, and time tracking data feeding payroll calculations.\n      - name: Workday Financial Management\n        description: Posts payroll journal entries and accruals into the Workday general ledger.\n      - name: Workday Time Tracking\n        description: Feeds approved time and absence data into payroll calculations.\n      - name: Workday Benefits\n        description: Provides benefit elections and deductions consumed by payroll.\n      - name: Workday Studio\n        description: Visual integration tool for building inbound and outbound payroll integrations.\n      - name: Workday Cloud Connect for Third-Party Payroll\n        description: Pre-built integrations to third-party payroll providers and tax filing services.\n      - name: Banking and Payment Networks\n        description: Generates ACH and international payment files for direct deposit\
  \ and payroll disbursements.\n  - type: Solutions\n    data:\n      - name: Workday Payroll for the U.S.\n        description: Full-service payroll solution for U.S. employers including federal, state, and local tax calculation and filing support.\n      - name: Workday Payroll for Canada\n        description: Payroll solution covering Canadian federal and provincial requirements.\n      - name: Workday Payroll for the U.K.\n        description: U.K. payroll with HMRC reporting and statutory pay support.\n      - name: Workday Payroll for France\n        description: French payroll covering DSN reporting and statutory rules.\n      - name: Workday Cloud Connect for Third-Party Payroll\n        description: Connectors and data feeds for customers running payroll on a third-party provider while using Workday HCM.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Compensation\n  - Enterprise\n  - Human Resources\n  - Payroll\n  - SaaS\n  - Tax\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/apis.yml
tags:
- Compensation
- Enterprise
- Human Resources
- Payroll
- SaaS
- Tax
url: https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/apis.yml
use_cases:
- description: Run payroll for a global workforce across regions while standardizing on a single platform and data model.
  name: Multi-Country Payroll Operations
- description: Schedule, execute, and audit recurring payroll runs end-to-end with minimal manual intervention.
  name: Payroll Cycle Automation
- description: Submit bonuses, retroactive pay, and corrections programmatically through the Payroll Input API.
  name: One-Time Payments and Adjustments
- description: Calculate withholdings and produce data feeds for statutory tax filings and year-end reporting.
  name: Tax Filing and Compliance
- description: Sync payroll results into general ledger, banking, benefits, and analytics systems downstream of payroll runs.
  name: Pay Data Integration
- description: Provide workers with secure programmatic access to payslips, year-to-date totals, and tax forms.
  name: Worker Pay Transparency
---
