---
api_count: 2
apis:
- description: 'The Aflac Enterprise Connect (AEC) API enables benefits administrators, HR platforms, and third-party enrollment systems to integrate with Aflac''s supplemental insurance platform programmatically. It '
  name: Aflac Enterprise Connect API
  slug: enterprise-connect-api
- description: The Aflac Claims API provides programmatic access to supplemental insurance claim submission, status retrieval, and benefit payment tracking. It enables policyholders and administrators to submit clai
  name: Aflac Claims API
  slug: claims-api
capabilities:
- description: Unified workflow capability for Aflac supplemental insurance benefits administration covering enrollment, claims, eligibility, and policy management. Used by HR platform engineers and benefits adminis
  name: Aflac Benefits Administration
  slug: benefits-administration
common:
- title: ''
  type: Portal
  url: https://docs.enterprise-connect.aflac.com
- title: ''
  type: Website
  url: https://www.aflac.com
- title: ''
  type: SignUp
  url: https://www.aflac.com/business/default.aspx
- title: ''
  type: TermsOfService
  url: https://www.aflac.com/about-aflac/legal/terms-and-conditions.aspx
- title: ''
  type: PrivacyPolicy
  url: https://www.aflac.com/about-aflac/legal/privacy-policy.aspx
- title: ''
  type: Support
  url: https://www.aflac.com/contact-aflac/default.aspx
- title: ''
  type: OpenAPI
  url: openapi/aflac-enterprise-connect-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/enterprise-connect-claim-list-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/enterprise-connect-claim-request-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/enterprise-connect-claim-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/enterprise-connect-dependent-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/enterprise-connect-eligibility-request-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/enterprise-connect-eligibility-response-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/enterprise-connect-enrollment-list-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/enterprise-connect-enrollment-request-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/enterprise-connect-enrollment-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/enterprise-connect-group-list-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/enterprise-connect-group-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/enterprise-connect-policy-list-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/enterprise-connect-policy-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/enterprise-connect-claim-list-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/enterprise-connect-claim-request-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/enterprise-connect-claim-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/enterprise-connect-dependent-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/enterprise-connect-eligibility-request-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/enterprise-connect-eligibility-response-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/enterprise-connect-enrollment-list-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/enterprise-connect-enrollment-request-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/enterprise-connect-enrollment-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/enterprise-connect-group-list-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/enterprise-connect-group-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/enterprise-connect-policy-list-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/enterprise-connect-policy-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/aflac-enterprise-context.jsonld
- title: ''
  type: Example
  url: examples/enterprise-connect-claim-example.json
- title: ''
  type: Example
  url: examples/enterprise-connect-claim-list-example.json
- title: ''
  type: Example
  url: examples/enterprise-connect-claim-request-example.json
- title: ''
  type: Example
  url: examples/enterprise-connect-dependent-example.json
- title: ''
  type: Example
  url: examples/enterprise-connect-eligibility-request-example.json
- title: ''
  type: Example
  url: examples/enterprise-connect-eligibility-response-example.json
- title: ''
  type: Example
  url: examples/enterprise-connect-enrollment-example.json
- title: ''
  type: Example
  url: examples/enterprise-connect-enrollment-list-example.json
- title: ''
  type: Example
  url: examples/enterprise-connect-enrollment-request-example.json
- title: ''
  type: Example
  url: examples/enterprise-connect-group-example.json
- title: ''
  type: Example
  url: examples/enterprise-connect-group-list-example.json
- title: ''
  type: Example
  url: examples/enterprise-connect-policy-example.json
- title: ''
  type: Example
  url: examples/enterprise-connect-policy-list-example.json
- title: ''
  type: SpectralRules
  url: rules/aflac-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/aflac-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/benefits-administration.yaml
created: ''
description: Aflac is America's leading provider of supplemental insurance, offering products that pay benefits when a policyholder experiences an accident, illness, or injury. Aflac provides REST APIs through its Enterprise Connect (AEC) platform enabling benefits technology companies, HR platforms, and benefits administrators to integrate supplemental insurance enrollment, policy management, and claims capabilities into their workflows.
features:
- description: Replace EDI 834 file-based enrollment with real-time API-driven enrollment workflows for supplemental insurance products.
  name: Electronic Benefits Enrollment
- description: Manage group and individual supplemental insurance policies including enrollments, terminations, and coverage changes.
  name: Policy Administration
- description: Enable digital claim filing for supplemental insurance products including accident, critical illness, cancer, and disability coverage.
  name: Claims Submission
- description: Verify employee eligibility for Aflac supplemental insurance products in real time during enrollment.
  name: Eligibility Verification
- description: Connect benefits administration platforms with Aflac's enrollment and policy systems via standardized REST APIs.
  name: Benefits Administration Integration
- description: Receive immediate enrollment confirmation and policy numbers upon successful enrollment submission.
  name: Real-Time Enrollment Confirmation
image: ''
integrations:
- description: Aflac connects with Employee Navigator benefits administration platform for automated enrollment data exchange.
  name: Employee Navigator
- description: Integration with Benefitfocus benefits marketplace for supplemental insurance enrollment.
  name: Benefitfocus
- description: Payroll and HR integration with ADP for Aflac premium deduction and enrollment synchronization.
  name: ADP
- description: Enterprise HR platform integration for benefits enrollment and Aflac policy administration.
  name: Workday
- description: Benefits administration platform integration for Aflac group enrollment.
  name: bswift
jsonld:
- class_count: 17
  name: Aflac Enterprise Context
  property_count: 30
  slug: aflac-enterprise-context
layout: provider
modified: '2026-04-19'
name: aflac
rules:
- name: aflac API Rules
  rule_count: 24
  severity_counts:
    error: 14
    hint: 0
    info: 0
    warn: 10
  slug: aflac-spectral-rules
skills: []
slug: aflac
solutions: []
source_yaml: "aid: aflac\nurl: https://raw.githubusercontent.com/api-evangelist/aflac/refs/heads/main/apis.yml\nmodified: '2026-04-19'\napis:\n- aid: aflac:enterprise-connect-api\n  name: Aflac Enterprise Connect API\n  tags:\n  - Benefits\n  - Enrollment\n  - Insurance\n  - Supplemental Insurance\n  - Workforce\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.enterprise-connect.aflac.com\n  humanURL: https://docs.enterprise-connect.aflac.com\n  properties:\n  - url: https://docs.enterprise-connect.aflac.com\n    type: Documentation\n  - url: https://docs.enterprise-connect.aflac.com/docs/getting-started\n    type: GettingStarted\n  - type: OpenAPI\n    url: openapi/aflac-enterprise-connect-openapi.yml\n  description: >-\n    The Aflac Enterprise Connect (AEC) API enables benefits administrators, HR platforms,\n    and third-party enrollment systems to integrate with Aflac's supplemental insurance\n    platform programmatically.\
  \ It provides REST API access to benefits enrollment, policy\n    management, claims status, and eligibility verification for group and individual\n    supplemental insurance products. The API supports electronic benefits enrollment\n    workflows replacing traditional EDI 834 file exchanges, enabling real-time enrollment\n    confirmation and policy administration for employers and their benefits technology\n    partners.\n\n- aid: aflac:claims-api\n  name: Aflac Claims API\n  tags:\n  - Claims\n  - Insurance\n  - Payments\n  - Supplemental Insurance\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.enterprise-connect.aflac.com\n  humanURL: https://docs.enterprise-connect.aflac.com\n  properties:\n  - url: https://docs.enterprise-connect.aflac.com\n    type: Documentation\n  description: >-\n    The Aflac Claims API provides programmatic access to supplemental insurance claim\n    submission, status retrieval, and benefit payment\
  \ tracking. It enables policyholders\n    and administrators to submit claims digitally, track claim processing status, and\n    receive benefit payment notifications. The API supports claims for Aflac's portfolio\n    of supplemental products including accident, critical illness, cancer, hospital\n    indemnity, and short-term disability insurance.\n\ncommon:\n- type: Portal\n  url: https://docs.enterprise-connect.aflac.com\n- type: Website\n  url: https://www.aflac.com\n- type: SignUp\n  url: https://www.aflac.com/business/default.aspx\n- type: TermsOfService\n  url: https://www.aflac.com/about-aflac/legal/terms-and-conditions.aspx\n- type: PrivacyPolicy\n  url: https://www.aflac.com/about-aflac/legal/privacy-policy.aspx\n- type: Support\n  url: https://www.aflac.com/contact-aflac/default.aspx\n- type: Features\n  data:\n  - name: Electronic Benefits Enrollment\n    description: Replace EDI 834 file-based enrollment with real-time API-driven enrollment workflows for supplemental insurance\
  \ products.\n  - name: Policy Administration\n    description: Manage group and individual supplemental insurance policies including enrollments, terminations, and coverage changes.\n  - name: Claims Submission\n    description: Enable digital claim filing for supplemental insurance products including accident, critical illness, cancer, and disability coverage.\n  - name: Eligibility Verification\n    description: Verify employee eligibility for Aflac supplemental insurance products in real time during enrollment.\n  - name: Benefits Administration Integration\n    description: Connect benefits administration platforms with Aflac's enrollment and policy systems via standardized REST APIs.\n  - name: Real-Time Enrollment Confirmation\n    description: Receive immediate enrollment confirmation and policy numbers upon successful enrollment submission.\n- type: UseCases\n  data:\n  - name: HR Platform Integration\n    description: HR and benefits administration platforms integrate with Aflac's\
  \ API to offer supplemental insurance enrollment within their existing benefits workflows.\n  - name: Employer Self-Service Enrollment\n    description: Employers manage supplemental insurance enrollments for employees during open enrollment periods via connected benefits platforms.\n  - name: Claims Tracking\n    description: Employees and HR teams track the status of Aflac supplemental insurance claims submitted after a qualifying health event.\n  - name: Benefits Broker Workflow\n    description: Benefits brokers manage group policy setup, employee enrollment, and plan changes for employer clients through integrated tools.\n- type: Integrations\n  data:\n  - name: Employee Navigator\n    description: Aflac connects with Employee Navigator benefits administration platform for automated enrollment data exchange.\n  - name: Benefitfocus\n    description: Integration with Benefitfocus benefits marketplace for supplemental insurance enrollment.\n  - name: ADP\n    description: Payroll and\
  \ HR integration with ADP for Aflac premium deduction and enrollment synchronization.\n  - name: Workday\n    description: Enterprise HR platform integration for benefits enrollment and Aflac policy administration.\n  - name: bswift\n    description: Benefits administration platform integration for Aflac group enrollment.\n- type: OpenAPI\n  url: openapi/aflac-enterprise-connect-openapi.yml\n- type: JSONSchema\n  url: json-schema/enterprise-connect-claim-list-schema.json\n- type: JSONSchema\n  url: json-schema/enterprise-connect-claim-request-schema.json\n- type: JSONSchema\n  url: json-schema/enterprise-connect-claim-schema.json\n- type: JSONSchema\n  url: json-schema/enterprise-connect-dependent-schema.json\n- type: JSONSchema\n  url: json-schema/enterprise-connect-eligibility-request-schema.json\n- type: JSONSchema\n  url: json-schema/enterprise-connect-eligibility-response-schema.json\n- type: JSONSchema\n  url: json-schema/enterprise-connect-enrollment-list-schema.json\n- type: JSONSchema\n\
  \  url: json-schema/enterprise-connect-enrollment-request-schema.json\n- type: JSONSchema\n  url: json-schema/enterprise-connect-enrollment-schema.json\n- type: JSONSchema\n  url: json-schema/enterprise-connect-group-list-schema.json\n- type: JSONSchema\n  url: json-schema/enterprise-connect-group-schema.json\n- type: JSONSchema\n  url: json-schema/enterprise-connect-policy-list-schema.json\n- type: JSONSchema\n  url: json-schema/enterprise-connect-policy-schema.json\n- type: JSONStructure\n  url: json-structure/enterprise-connect-claim-list-structure.json\n- type: JSONStructure\n  url: json-structure/enterprise-connect-claim-request-structure.json\n- type: JSONStructure\n  url: json-structure/enterprise-connect-claim-structure.json\n- type: JSONStructure\n  url: json-structure/enterprise-connect-dependent-structure.json\n- type: JSONStructure\n  url: json-structure/enterprise-connect-eligibility-request-structure.json\n- type: JSONStructure\n  url: json-structure/enterprise-connect-eligibility-response-structure.json\n\
  - type: JSONStructure\n  url: json-structure/enterprise-connect-enrollment-list-structure.json\n- type: JSONStructure\n  url: json-structure/enterprise-connect-enrollment-request-structure.json\n- type: JSONStructure\n  url: json-structure/enterprise-connect-enrollment-structure.json\n- type: JSONStructure\n  url: json-structure/enterprise-connect-group-list-structure.json\n- type: JSONStructure\n  url: json-structure/enterprise-connect-group-structure.json\n- type: JSONStructure\n  url: json-structure/enterprise-connect-policy-list-structure.json\n- type: JSONStructure\n  url: json-structure/enterprise-connect-policy-structure.json\n- type: JSON-LD\n  url: json-ld/aflac-enterprise-context.jsonld\n- type: Example\n  url: examples/enterprise-connect-claim-example.json\n- type: Example\n  url: examples/enterprise-connect-claim-list-example.json\n- type: Example\n  url: examples/enterprise-connect-claim-request-example.json\n- type: Example\n  url: examples/enterprise-connect-dependent-example.json\n\
  - type: Example\n  url: examples/enterprise-connect-eligibility-request-example.json\n- type: Example\n  url: examples/enterprise-connect-eligibility-response-example.json\n- type: Example\n  url: examples/enterprise-connect-enrollment-example.json\n- type: Example\n  url: examples/enterprise-connect-enrollment-list-example.json\n- type: Example\n  url: examples/enterprise-connect-enrollment-request-example.json\n- type: Example\n  url: examples/enterprise-connect-group-example.json\n- type: Example\n  url: examples/enterprise-connect-group-list-example.json\n- type: Example\n  url: examples/enterprise-connect-policy-example.json\n- type: Example\n  url: examples/enterprise-connect-policy-list-example.json\n- type: SpectralRules\n  url: rules/aflac-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/aflac-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/benefits-administration.yaml\ndescription: >-\n  Aflac is America's leading provider of supplemental insurance, offering\
  \ products\n  that pay benefits when a policyholder experiences an accident, illness, or injury.\n  Aflac provides REST APIs through its Enterprise Connect (AEC) platform enabling\n  benefits technology companies, HR platforms, and benefits administrators to integrate\n  supplemental insurance enrollment, policy management, and claims capabilities into\n  their workflows.\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aflac/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/aflac/refs/heads/main/apis.yml
use_cases:
- description: HR and benefits administration platforms integrate with Aflac's API to offer supplemental insurance enrollment within their existing benefits workflows.
  name: HR Platform Integration
- description: Employers manage supplemental insurance enrollments for employees during open enrollment periods via connected benefits platforms.
  name: Employer Self-Service Enrollment
- description: Employees and HR teams track the status of Aflac supplemental insurance claims submitted after a qualifying health event.
  name: Claims Tracking
- description: Benefits brokers manage group policy setup, employee enrollment, and plan changes for employer clients through integrated tools.
  name: Benefits Broker Workflow
---
