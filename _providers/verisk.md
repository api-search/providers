---
api_count: 2
api_specs:
- filename: verisk-insurance-analytics-openapi.yml
  format: yaml
  label: Verisk Insurance Analytics API
  slug: insurance-analytics
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/openapi/verisk-insurance-analytics-openapi.yml
apis:
- description: Verisk Insurance Analytics API provides property risk assessments, ISO fire protection classifications, catastrophe peril scores, insurance risk scoring, and claims benchmarking data for P&C insurance
  name: Verisk Insurance Analytics API
  slug: insurance-analytics
- description: Verisk UnderWriting API provides personal and commercial lines insurance underwriting data including homeowner data, motor vehicle reports, A-PLUS auto and property reports, LightSpeed prefill, geocod
  name: Verisk UnderWriting API
  slug: underwriting-api
capabilities:
- description: Unified capability for insurance underwriters to assess property risk, retrieve ISO fire protection classifications, score catastrophe peril exposures, and benchmark claims performance. Combines Veris
  name: Verisk Insurance Underwriting
  slug: insurance-underwriting
common:
- title: ''
  type: Website
  url: https://www.verisk.com
- title: ''
  type: Portal
  url: https://gateway-documentation.verisk.com/
- title: ''
  type: APIReference
  url: https://apicatalog.verisk.com/
- title: ''
  type: Documentation
  url: https://gateway.verisk.com/docs/MainPage.ashx
- title: ''
  type: GettingStarted
  url: https://gateway.verisk.com/docs/Getting-Started.ashx
- title: ''
  type: Authentication
  url: https://gateway.verisk.com/docs/Authentication.ashx
- title: ''
  type: TermsOfService
  url: https://www.verisk.com/terms-of-use/
- title: ''
  type: PrivacyPolicy
  url: https://www.verisk.com/privacy-policy/
- title: ''
  type: Contact
  url: https://www.verisk.com/contact/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/rules/verisk-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/vocabulary/verisk-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/capabilities/insurance-underwriting.yaml
created: '2026-05-03'
description: Verisk (formerly ISO) is a leading data analytics and technology company serving the insurance, energy, and financial services industries. Verisk provides risk scoring, actuarial data, property analytics, catastrophe modeling, claims benchmarking, and underwriting intelligence through RESTful APIs that power insurance pricing, reserving, and exposure management workflows.
features:
- description: Comprehensive property risk scoring including construction, fire protection class, and hazard exposure for fire, wind, hail, flood, and earthquake perils.
  name: Property Risk Assessment
- description: ISO Public Protection Classification (PPC) grading measuring community fire suppression capability on a 1-10 scale.
  name: ISO Fire Protection Classification
- description: Natural hazard exposure scores for hurricane, tornado, hail, wildfire, earthquake, and flood risk used for catastrophe risk management.
  name: Catastrophe Peril Scoring
- description: Risk scores for properties, policies, and portfolios including fire protection class, building code effectiveness grading, flood zone, and earthquake zone scores.
  name: Insurance Risk Scoring
- description: Industry claims benchmarking data for loss frequency, severity, combined ratio, and loss ratio metrics across lines of business and states.
  name: Claims Benchmarking
- description: Address-to-property resolution with geocoding to USGS coordinates and ISO property identification for prefill and underwriting workflows.
  name: Address Geocoding and Lookup
- description: LightSpeed and homeowner data APIs provide instant underwriting intelligence from a business name and address for small commercial and personal lines.
  name: Prefill and Accelerated Underwriting
- description: Benchmark API provides hail, wind, lightning, and hurricane wind analytics for property and auto claims and underwriting decisions.
  name: Weather Analytics Integration
image: ''
integrations:
- description: Integrate risk scores and underwriting data directly into existing policy administration and underwriting workflow systems.
  name: Policy Administration Systems
- description: Embed weather analytics and property data into claims management platforms for faster adjudication.
  name: Claims Management Systems
- description: Feed peril scores and property data into catastrophe modeling platforms like AIR Worldwide and RMS for exposure analysis.
  name: Catastrophe Modeling Platforms
- description: API-enabled GenAI commercial underwriting assistant that integrates into existing policy administration systems.
  name: Generative AI Underwriting Assistant
jsonld:
- class_count: 27
  name: Verisk Context
  property_count: 5
  slug: verisk-context
- class_count: 13
  name: Verisk Insurance Analytics Context
  property_count: 42
  slug: verisk-insurance-analytics-context
layout: provider
modified: '2026-05-03'
name: Verisk
rules:
- name: Verisk API Rules
  rule_count: 36
  severity_counts:
    error: 18
    hint: 0
    info: 1
    warn: 17
  slug: verisk-spectral-rules
skills: []
slug: verisk
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: verisk\nname: Verisk\ndescription: >-\n  Verisk (formerly ISO) is a leading data analytics and technology company serving\n  the insurance, energy, and financial services industries. Verisk provides risk\n  scoring, actuarial data, property analytics, catastrophe modeling, claims\n  benchmarking, and underwriting intelligence through RESTful APIs that power\n  insurance pricing, reserving, and exposure management workflows.\nurl: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/apis.yml\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - Insurance\n  - Analytics\n  - Risk Management\n  - Property Data\n  - Catastrophe Modeling\n  - Underwriting\n  - Claims\napis:\n  - aid: verisk:insurance-analytics\n    name: Verisk Insurance Analytics API\n    description: >-\n      Verisk Insurance Analytics API provides property risk assessments, ISO fire\n      protection classifications, catastrophe peril scores, insurance\
  \ risk scoring,\n      and claims benchmarking data for P&C insurance carriers. Delivers loss cost data,\n      risk classification, and underwriting data services for insurance pricing,\n      reserving, and exposure management.\n    humanURL: https://gateway.verisk.com/docs/MainPage.ashx\n    tags:\n      - Insurance\n      - Analytics\n      - Risk Management\n      - Property Data\n      - Catastrophe Modeling\n      - Underwriting\n      - Claims\n    properties:\n      - type: Documentation\n        url: https://gateway.verisk.com/docs/MainPage.ashx\n      - type: GettingStarted\n        url: https://gateway.verisk.com/docs/Getting-Started.ashx\n      - type: Authentication\n        url: https://gateway.verisk.com/docs/Authentication.ashx\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/openapi/verisk-insurance-analytics-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-schema/insurance-analytics-property-risk-schema.json\n\
  \      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-schema/insurance-analytics-construction-data-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-schema/insurance-analytics-fire-protection-class-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-schema/insurance-analytics-address-lookup-request-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-schema/insurance-analytics-property-lookup-response-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-schema/insurance-analytics-risk-score-request-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-schema/insurance-analytics-risk-score-response-schema.json\n\
  \      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-schema/insurance-analytics-peril-score-request-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-schema/insurance-analytics-peril-score-response-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-schema/insurance-analytics-claims-benchmarks-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-schema/insurance-analytics-address-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-schema/insurance-analytics-coordinates-schema.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-structure/insurance-analytics-property-risk-structure.json\n\
  \      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-structure/insurance-analytics-construction-data-structure.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-structure/insurance-analytics-fire-protection-class-structure.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-structure/insurance-analytics-claims-benchmarks-structure.json\n      - type: JSON-LD\n        url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/json-ld/verisk-insurance-analytics-context.jsonld\n  - aid: verisk:underwriting-api\n    name: Verisk UnderWriting API\n    description: >-\n      Verisk UnderWriting API provides personal and commercial lines insurance\n      underwriting data including homeowner data, motor vehicle reports, A-PLUS\n      auto and property reports, LightSpeed\
  \ prefill, geocoding, ISO fire protection\n      class, and coverage verification for P&C insurance carriers. Supports both\n      JSON and XML response formats.\n    humanURL: https://gateway.verisk.com/docs/MainPage.ashx\n    tags:\n      - Underwriting\n      - Insurance\n      - Personal Lines\n      - Commercial Lines\n      - Motor Vehicle\n      - Property Data\n    properties:\n      - type: Documentation\n        url: https://gateway.verisk.com/docs/MainPage.ashx\n      - type: GettingStarted\n        url: https://gateway.verisk.com/docs/Getting-Started.ashx\n      - type: Authentication\n        url: https://gateway.verisk.com/docs/Authentication.ashx\ncommon:\n  - type: Website\n    url: https://www.verisk.com\n  - type: Portal\n    url: https://gateway-documentation.verisk.com/\n  - type: APIReference\n    url: https://apicatalog.verisk.com/\n  - type: Documentation\n    url: https://gateway.verisk.com/docs/MainPage.ashx\n  - type: GettingStarted\n    url: https://gateway.verisk.com/docs/Getting-Started.ashx\n\
  \  - type: Authentication\n    url: https://gateway.verisk.com/docs/Authentication.ashx\n  - type: TermsOfService\n    url: https://www.verisk.com/terms-of-use/\n  - type: PrivacyPolicy\n    url: https://www.verisk.com/privacy-policy/\n  - type: Contact\n    url: https://www.verisk.com/contact/\n  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/rules/verisk-spectral-rules.yml\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/vocabulary/verisk-vocabulary.yaml\n  - type: NaftikoCapability\n    url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/capabilities/insurance-underwriting.yaml\n  - type: Features\n    data:\n      - name: Property Risk Assessment\n        description: Comprehensive property risk scoring including construction, fire protection class, and hazard exposure for fire, wind, hail, flood, and earthquake perils.\n      - name: ISO Fire Protection\
  \ Classification\n        description: ISO Public Protection Classification (PPC) grading measuring community fire suppression capability on a 1-10 scale.\n      - name: Catastrophe Peril Scoring\n        description: Natural hazard exposure scores for hurricane, tornado, hail, wildfire, earthquake, and flood risk used for catastrophe risk management.\n      - name: Insurance Risk Scoring\n        description: Risk scores for properties, policies, and portfolios including fire protection class, building code effectiveness grading, flood zone, and earthquake zone scores.\n      - name: Claims Benchmarking\n        description: Industry claims benchmarking data for loss frequency, severity, combined ratio, and loss ratio metrics across lines of business and states.\n      - name: Address Geocoding and Lookup\n        description: Address-to-property resolution with geocoding to USGS coordinates and ISO property identification for prefill and underwriting workflows.\n      - name: Prefill\
  \ and Accelerated Underwriting\n        description: LightSpeed and homeowner data APIs provide instant underwriting intelligence from a business name and address for small commercial and personal lines.\n      - name: Weather Analytics Integration\n        description: Benchmark API provides hail, wind, lightning, and hurricane wind analytics for property and auto claims and underwriting decisions.\n  - type: UseCases\n    data:\n      - name: Insurance Pricing and Rating\n        description: Use risk scores and property data to accurately price insurance policies for homeowners, auto, and commercial lines of business.\n      - name: Catastrophe Risk Management\n        description: Assess portfolio exposure to natural hazard perils and estimate probable maximum loss (PML) for catastrophe reinsurance programs.\n      - name: Claims Adjudication\n        description: Integrate weather analytics and property data to streamline field adjustments, reduce inspection costs, and accelerate\
  \ claim cycle times.\n      - name: Underwriting Automation\n        description: Automate underwriting decisions by integrating prefill data, motor vehicle reports, and coverage verification into policy administration systems.\n      - name: Portfolio Risk Monitoring\n        description: Monitor geographic concentration and peril exposure across insurance portfolios for risk management and regulatory reporting.\n  - type: Integrations\n    data:\n      - name: Policy Administration Systems\n        description: Integrate risk scores and underwriting data directly into existing policy administration and underwriting workflow systems.\n      - name: Claims Management Systems\n        description: Embed weather analytics and property data into claims management platforms for faster adjudication.\n      - name: Catastrophe Modeling Platforms\n        description: Feed peril scores and property data into catastrophe modeling platforms like AIR Worldwide and RMS for exposure analysis.\n  \
  \    - name: Generative AI Underwriting Assistant\n        description: API-enabled GenAI commercial underwriting assistant that integrates into existing policy administration systems.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/apis.yml
tags:
- Insurance
- Analytics
- Risk Management
- Property Data
- Catastrophe Modeling
- Underwriting
- Claims
url: https://raw.githubusercontent.com/api-evangelist/verisk/refs/heads/main/apis.yml
use_cases:
- description: Use risk scores and property data to accurately price insurance policies for homeowners, auto, and commercial lines of business.
  name: Insurance Pricing and Rating
- description: Assess portfolio exposure to natural hazard perils and estimate probable maximum loss (PML) for catastrophe reinsurance programs.
  name: Catastrophe Risk Management
- description: Integrate weather analytics and property data to streamline field adjustments, reduce inspection costs, and accelerate claim cycle times.
  name: Claims Adjudication
- description: Automate underwriting decisions by integrating prefill data, motor vehicle reports, and coverage verification into policy administration systems.
  name: Underwriting Automation
- description: Monitor geographic concentration and peril exposure across insurance portfolios for risk management and regulatory reporting.
  name: Portfolio Risk Monitoring
---
