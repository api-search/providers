---
api_count: 2
api_specs:
- filename: argus-enterprise-core-openapi.yml
  format: yaml
  label: ARGUS Enterprise Core API
  slug: argus-enterprise-core
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argus-enterprise/refs/heads/main/openapi/argus-enterprise-core-openapi.yml
- filename: argus-enterprise-webhooks-openapi.yml
  format: yaml
  label: ARGUS Enterprise Webhook API
  slug: argus-enterprise-webhooks
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argus-enterprise/refs/heads/main/openapi/argus-enterprise-webhooks-openapi.yml
apis:
- description: Core REST API for the ARGUS Enterprise platform providing programmatic access to commercial real estate investment management capabilities including property data, portfolio management, cash flow proj
  name: ARGUS Enterprise Core API
  slug: argus-enterprise-core
- description: Webhook service for the ARGUS Enterprise platform enabling real-time event notifications for property changes, valuation updates, lease events, portfolio modifications, and report completions.
  name: ARGUS Enterprise Webhook API
  slug: argus-enterprise-webhooks
capabilities:
- description: Unified capability for commercial real estate investment management using ARGUS Enterprise. Combines property valuation, cash flow modeling, lease management, portfolio analytics, and reporting for As
  name: ARGUS Enterprise CRE Investment Management
  slug: cre-investment-management
common:
- title: ''
  type: Website
  url: https://www.altusgroup.com/solutions/argus-enterprise/
- title: ''
  type: Documentation
  url: https://www.altusgroup.com/argus/downloads/argus-enterprise/
- title: ''
  type: GettingStarted
  url: https://www.altusgroup.com/support/start-using-argus-intelligence/
- title: ''
  type: Portal
  url: https://cloud.altusplatform.com/login
- title: ''
  type: Support
  url: https://www.altusgroup.com/support/
- title: ''
  type: TermsOfService
  url: https://www.altusgroup.com/terms-of-use/
- title: ''
  type: PrivacyPolicy
  url: https://www.altusgroup.com/privacy-policy/
- title: ''
  type: Training
  url: https://www.altusgroup.com/argus/training/
- title: ''
  type: Security
  url: https://www.altusgroup.com/security/
- title: ''
  type: JSONLD
  url: json-ld/argus-enterprise-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/argus-enterprise-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/cre-investment-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/argus-enterprise-vocabulary.yaml
created: '2024-01-15'
description: ARGUS Enterprise is the industry-standard commercial property valuation and cash flow forecasting software by Altus Group, now integrated into the ARGUS Intelligence Platform. It provides lease-by-lease cash flow modeling, property valuations using DCF and yield-based methods, budgeting and forecasting, scenario testing, and 40+ industry-standard reports. Trusted by real estate investors, portfolio managers, valuation professionals, and asset managers worldwide and taught at 200+ universities.
features:
- description: Model cash flows at the individual lease level across all property types including office, industrial, retail, and multifamily.
  name: Lease-by-Lease Cash Flow Modeling
- description: Support for DCF, cap rate, hardcore, term and reversion, and initial yield valuation methodologies.
  name: Multiple Valuation Methods
- description: Create property-level budgets with budget-to-actual tracking and prior-year comparison.
  name: Budgeting and Forecasting
- description: Run what-if scenarios to assess best-case and worst-case outcomes for investment decisions.
  name: Scenario Analysis
- description: Stress-test yield rates, growth assumptions, and modeling parameters.
  name: Sensitivity Analysis
- description: 40+ industry-standard asset and portfolio reports for investor and management communication.
  name: Portfolio Reporting
- description: Configure market leasing assumptions for new, vacant, and renewing spaces.
  name: Market Leasing Assumptions
- description: Model leveraged and unleveraged returns with debt tranche configuration.
  name: Debt Modeling
- description: ARGUS Enterprise is ISO/IEC 27001:2022 certified and SOC 2 Type II audited.
  name: ISO 27001 Certified
- description: Integrated with ARGUS Intelligence Platform for portfolio-level dashboards and benchmarking.
  name: ARGUS Intelligence Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native integration with ARGUS Intelligence for portfolio dashboards, analytics, and benchmarking.
  name: ARGUS Intelligence Platform
- description: Integration with ARGUS Developer for development-to-stabilization lifecycle management.
  name: ARGUS Developer
- description: Import property management and lease data from Yardi into ARGUS Enterprise models.
  name: Yardi
- description: Integrate MRI property management data into cash flow models.
  name: MRI Software
- description: JLL uses ARGUS Enterprise for asset management and portfolio analytics globally.
  name: JLL
- description: CBRE uses ARGUS Enterprise for valuation and investment analysis services.
  name: CBRE
jsonld:
- class_count: 0
  name: Argus Enterprise Context
  property_count: 8
  slug: argus-enterprise-context
layout: provider
modified: '2026-04-19'
name: ARGUS Enterprise
rules:
- name: ARGUS Enterprise API Rules
  rule_count: 14
  severity_counts:
    error: 5
    hint: 0
    info: 2
    warn: 7
  slug: argus-enterprise-spectral-rules
skills: []
slug: argus-enterprise
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: argus-enterprise\nname: ARGUS Enterprise\ndescription: >-\n  ARGUS Enterprise is the industry-standard commercial property valuation and cash flow\n  forecasting software by Altus Group, now integrated into the ARGUS Intelligence Platform.\n  It provides lease-by-lease cash flow modeling, property valuations using DCF and yield-based\n  methods, budgeting and forecasting, scenario testing, and 40+ industry-standard reports.\n  Trusted by real estate investors, portfolio managers, valuation professionals, and asset\n  managers worldwide and taught at 200+ universities.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Altus Group\n  - Asset Management\n  - Cash Flow Modeling\n  - Commercial Real Estate\n  - Portfolio Management\n  - Valuation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/argus-enterprise/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\n\
  apis:\n  - aid: argus-enterprise:argus-enterprise-core\n    name: ARGUS Enterprise Core API\n    description: >-\n      Core REST API for the ARGUS Enterprise platform providing programmatic access to\n      commercial real estate investment management capabilities including property data,\n      portfolio management, cash flow projections, valuations, tenants, leases, and reporting.\n      Authentication via bearer token.\n    humanURL: https://www.altusgroup.com/solutions/argus-enterprise/\n    baseURL: https://api.argusenterprise.com/v1\n    tags:\n      - Analytics\n      - Cash Flow\n      - Leases\n      - Portfolio Management\n      - Properties\n      - Reporting\n      - Valuations\n    properties:\n      - type: Documentation\n        url: https://www.altusgroup.com/argus/downloads/argus-enterprise/\n      - type: OpenAPI\n        url: openapi/argus-enterprise-core-openapi.yml\n      - type: Authentication\n        url: https://www.altusgroup.com/support/start-using-argus-intelligence/\n\
  \  - aid: argus-enterprise:argus-enterprise-webhooks\n    name: ARGUS Enterprise Webhook API\n    description: >-\n      Webhook service for the ARGUS Enterprise platform enabling real-time event notifications\n      for property changes, valuation updates, lease events, portfolio modifications, and\n      report completions.\n    humanURL: https://www.altusgroup.com/solutions/argus-enterprise/\n    tags:\n      - Events\n      - Real-Time\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://www.altusgroup.com/argus/downloads/argus-enterprise/\n      - type: OpenAPI\n        url: openapi/argus-enterprise-webhooks-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.altusgroup.com/solutions/argus-enterprise/\n  - type: Documentation\n    url: https://www.altusgroup.com/argus/downloads/argus-enterprise/\n  - type: GettingStarted\n    url: https://www.altusgroup.com/support/start-using-argus-intelligence/\n  - type: Portal\n    url: https://cloud.altusplatform.com/login\n\
  \  - type: Support\n    url: https://www.altusgroup.com/support/\n  - type: TermsOfService\n    url: https://www.altusgroup.com/terms-of-use/\n  - type: PrivacyPolicy\n    url: https://www.altusgroup.com/privacy-policy/\n  - type: Training\n    url: https://www.altusgroup.com/argus/training/\n  - type: Security\n    url: https://www.altusgroup.com/security/\n  - type: JSONLD\n    url: json-ld/argus-enterprise-context.jsonld\n  - type: SpectralRules\n    url: rules/argus-enterprise-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/cre-investment-management.yaml\n  - type: Vocabulary\n    url: vocabulary/argus-enterprise-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Lease-by-Lease Cash Flow Modeling\n        description: Model cash flows at the individual lease level across all property types including office, industrial, retail, and multifamily.\n      - name: Multiple Valuation Methods\n        description: Support for DCF, cap rate, hardcore, term\
  \ and reversion, and initial yield valuation methodologies.\n      - name: Budgeting and Forecasting\n        description: Create property-level budgets with budget-to-actual tracking and prior-year comparison.\n      - name: Scenario Analysis\n        description: Run what-if scenarios to assess best-case and worst-case outcomes for investment decisions.\n      - name: Sensitivity Analysis\n        description: Stress-test yield rates, growth assumptions, and modeling parameters.\n      - name: Portfolio Reporting\n        description: 40+ industry-standard asset and portfolio reports for investor and management communication.\n      - name: Market Leasing Assumptions\n        description: Configure market leasing assumptions for new, vacant, and renewing spaces.\n      - name: Debt Modeling\n        description: Model leveraged and unleveraged returns with debt tranche configuration.\n      - name: ISO 27001 Certified\n        description: ARGUS Enterprise is ISO/IEC 27001:2022 certified\
  \ and SOC 2 Type II audited.\n      - name: ARGUS Intelligence Integration\n        description: Integrated with ARGUS Intelligence Platform for portfolio-level dashboards and benchmarking.\n  - type: UseCases\n    data:\n      - name: Asset Valuation\n        description: Produce DCF and yield-based valuations for commercial real estate appraisals and acquisitions.\n      - name: Portfolio Performance Monitoring\n        description: Monitor portfolio-level performance against budgets and prior periods with dashboards.\n      - name: Acquisition Underwriting\n        description: Underwrite new property acquisitions with detailed cash flow and return analysis.\n      - name: Asset Management Budgeting\n        description: Create and track property-level budgets against actual performance for active assets.\n      - name: Investor Reporting\n        description: Generate standardized reports for investors, lenders, and boards on asset and portfolio performance.\n      - name: Disposition\
  \ Analysis\n        description: Model disposition scenarios and exit valuations for hold/sell decisions.\n  - type: Integrations\n    data:\n      - name: ARGUS Intelligence Platform\n        description: Native integration with ARGUS Intelligence for portfolio dashboards, analytics, and benchmarking.\n      - name: ARGUS Developer\n        description: Integration with ARGUS Developer for development-to-stabilization lifecycle management.\n      - name: Yardi\n        description: Import property management and lease data from Yardi into ARGUS Enterprise models.\n      - name: MRI Software\n        description: Integrate MRI property management data into cash flow models.\n      - name: JLL\n        description: JLL uses ARGUS Enterprise for asset management and portfolio analytics globally.\n      - name: CBRE\n        description: CBRE uses ARGUS Enterprise for valuation and investment analysis services.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/argus-enterprise/refs/heads/main/apis.yml
tags:
- Altus Group
- Asset Management
- Cash Flow Modeling
- Commercial Real Estate
- Portfolio Management
- Valuation
url: https://raw.githubusercontent.com/api-evangelist/argus-enterprise/refs/heads/main/apis.yml
use_cases:
- description: Produce DCF and yield-based valuations for commercial real estate appraisals and acquisitions.
  name: Asset Valuation
- description: Monitor portfolio-level performance against budgets and prior periods with dashboards.
  name: Portfolio Performance Monitoring
- description: Underwrite new property acquisitions with detailed cash flow and return analysis.
  name: Acquisition Underwriting
- description: Create and track property-level budgets against actual performance for active assets.
  name: Asset Management Budgeting
- description: Generate standardized reports for investors, lenders, and boards on asset and portfolio performance.
  name: Investor Reporting
- description: Model disposition scenarios and exit valuations for hold/sell decisions.
  name: Disposition Analysis
---
