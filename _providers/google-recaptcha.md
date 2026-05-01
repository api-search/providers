---
api_count: 2
api_specs:
- filename: recaptcha-enterprise-openapi.yml
  format: yaml
  label: reCAPTCHA Enterprise API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-recaptcha/refs/heads/main/openapi/recaptcha-enterprise-openapi.yml
apis:
- description: The reCAPTCHA Enterprise API provides advanced bot detection and fraud prevention capabilities for websites and applications. It returns risk scores and reason codes for user interactions, supports cr
  name: reCAPTCHA Enterprise API
  slug: ''
- description: The reCAPTCHA Site Verify API is the standard verification endpoint for reCAPTCHA v2 and v3 tokens. After a user completes a reCAPTCHA challenge on the frontend, the backend sends the response token t
  name: reCAPTCHA Site Verify API
  slug: ''
common:
- title: ''
  type: GettingStarted
  url: https://cloud.google.com/recaptcha-enterprise/docs/getting-started
- title: ''
  type: Pricing
  url: https://cloud.google.com/recaptcha-enterprise/pricing
- title: ''
  type: Authentication
  url: https://cloud.google.com/recaptcha-enterprise/docs/authentication
- title: ''
  type: Console
  url: https://console.cloud.google.com/security/recaptcha
- title: ''
  type: SDKs
  url: https://cloud.google.com/recaptcha-enterprise/docs/libraries
- title: ''
  type: Support
  url: https://cloud.google.com/recaptcha-enterprise/docs/support
- title: ''
  type: Status
  url: https://status.cloud.google.com
- title: ''
  type: JSON-LD
  url: json-ld/google-recaptcha-context.jsonld
created: '2026-03-13'
description: Google reCAPTCHA is a security service that protects websites and applications from spam and abuse by verifying that interactions are from real humans rather than bots, offering Enterprise and standard APIs for site verification and risk assessment.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Google Recaptcha Context
  property_count: 3
  slug: google-recaptcha-context
layout: provider
modified: '2026-04-28'
name: Google reCAPTCHA
skills: []
slug: google-recaptcha
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-recaptcha\nname: Google reCAPTCHA\ndescription: Google reCAPTCHA is a security service that protects websites and applications from spam and abuse by verifying that interactions are from real humans rather than bots, offering Enterprise and standard APIs for site verification and risk assessment.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/google-recaptcha/refs/heads/main/apis.yml\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Abuse Prevention\n  - Bot Detection\n  - CAPTCHA\n  - Fraud Prevention\n  - Google Cloud\n  - Security\napis:\n  - name: reCAPTCHA Enterprise API\n    description: >-\n      The reCAPTCHA Enterprise API provides advanced bot detection and fraud\n      prevention capabilities for websites and applications. It returns risk\n      scores and reason codes for user interactions, supports creating and\n\
  \      managing site keys, assessments, and related resources. The API enables\n      creating assessments for tokens, annotating assessments with feedback,\n      and managing firewall policies for automated protection.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloud.google.com/recaptcha-enterprise/docs\n    baseURL: https://recaptchaenterprise.googleapis.com\n    tags:\n      - Bot Detection\n      - Enterprise\n      - Risk Assessment\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/recaptcha-enterprise/docs/reference/rest\n      - type: OpenAPI\n        url: openapi/recaptcha-enterprise-openapi.yml\n      - type: JSONSchema\n        url: json-schema/google-recaptcha-assessment-schema.json\n  - name: reCAPTCHA Site Verify API\n    description: >-\n      The reCAPTCHA Site Verify API is the standard verification endpoint for\n      reCAPTCHA v2 and v3 tokens. After a user completes\
  \ a reCAPTCHA challenge\n      on the frontend, the backend sends the response token to this API to\n      verify the interaction. The API returns whether the verification succeeded,\n      a score (for v3), the action name, and the hostname.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.google.com/recaptcha/docs/verify\n    baseURL: https://www.google.com/recaptcha/api\n    tags:\n      - reCAPTCHA V3\n      - Token Validation\n      - Verification\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/recaptcha/docs/verify\ncommon:\n  - type: GettingStarted\n    url: https://cloud.google.com/recaptcha-enterprise/docs/getting-started\n  - type: Pricing\n    url: https://cloud.google.com/recaptcha-enterprise/pricing\n  - type: Authentication\n    url: https://cloud.google.com/recaptcha-enterprise/docs/authentication\n  - type: Console\n    url: https://console.cloud.google.com/security/recaptcha\n\
  \  - type: SDKs\n    url: https://cloud.google.com/recaptcha-enterprise/docs/libraries\n  - type: Support\n    url: https://cloud.google.com/recaptcha-enterprise/docs/support\n  - type: Status\n    url: https://status.cloud.google.com\n  - type: JSON-LD\n    url: json-ld/google-recaptcha-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-recaptcha/refs/heads/main/apis.yml
tags:
- Abuse Prevention
- Bot Detection
- CAPTCHA
- Fraud Prevention
- Google Cloud
- Security
url: https://raw.githubusercontent.com/api-evangelist/google-recaptcha/refs/heads/main/apis.yml
use_cases: []
---
