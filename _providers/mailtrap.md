---
api_count: 2
api_specs:
- filename: mailtrap-email-api-openapi.yml
  format: yaml
  label: Mailtrap Email Sending API
  slug: mailtrap-email-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mailtrap/refs/heads/main/openapi/mailtrap-email-api-openapi.yml
- filename: mailtrap-email-sandbox-openapi.yml
  format: yaml
  label: Mailtrap Email Sandbox API
  slug: mailtrap-email-sandbox
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mailtrap/refs/heads/main/openapi/mailtrap-email-sandbox-openapi.yml
apis:
- description: The Mailtrap Email Sending API allows sending transactional and bulk emails with high deliverability. It follows REST principles and supports authentication via API tokens, with all requests sent over
  name: Mailtrap Email Sending API
  slug: mailtrap-email-api
- description: The Mailtrap Email Sandbox API provides a safe email testing environment to inspect and debug emails before sending to real recipients. Supports switching between sandbox and production modes in offic
  name: Mailtrap Email Sandbox API
  slug: mailtrap-email-sandbox
common:
- title: ''
  type: Portal
  url: https://mailtrap.io/
- title: ''
  type: Documentation
  url: https://docs.mailtrap.io/
- title: ''
  type: Sign Up
  url: https://mailtrap.io/register/signup
- title: ''
  type: Login
  url: https://mailtrap.io/users/sign_in
- title: ''
  type: Pricing
  url: https://mailtrap.io/pricing/
- title: ''
  type: Status
  url: https://status.mailtrap.io/
- title: ''
  type: Support
  url: https://help.mailtrap.io/
- title: ''
  type: Terms of Service
  url: https://mailtrap.io/terms-of-use/
- title: ''
  type: Privacy Policy
  url: https://mailtrap.io/privacy-policy/
created: '2025-02-06'
description: Mailtrap provides a RESTful email infrastructure API with high deliverability rates, an email sandbox for safe testing, and actionable analytics. It offers SDKs for smooth integration and supports both transactional sending and bulk email delivery.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Mailtrap
skills: []
slug: mailtrap
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: mailtrap\nname: Mailtrap\ndescription: >-\n  Mailtrap provides a RESTful email infrastructure API with high deliverability\n  rates, an email sandbox for safe testing, and actionable analytics. It offers\n  SDKs for smooth integration and supports both transactional sending and bulk\n  email delivery.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Email\n  - Email Delivery\n  - Email Sandbox\n  - Email Testing\n  - Transactional Email\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/mailtrap/refs/heads/main/apis.yml\ncreated: '2025-02-06'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: mailtrap:mailtrap-email-api\n    name: Mailtrap Email Sending API\n    description: >-\n      The Mailtrap Email Sending API allows sending transactional and bulk\n      emails with high deliverability. It follows REST principles and supports\n      authentication via API tokens, with all requests\
  \ sent over HTTPS.\n    humanURL: https://mailtrap.io/email-api/\n    baseURL: https://send.api.mailtrap.io\n    tags:\n      - Email\n      - REST API\n      - Transactional Email\n    properties:\n      - type: Documentation\n        url: https://docs.mailtrap.io/developers\n      - type: Reference\n        url: https://api-docs.mailtrap.io/\n      - type: Getting Started\n        url: https://docs.mailtrap.io/docs/sending-emails-overview\n      - type: OpenAPI\n        url: openapi/mailtrap-email-api-openapi.yml\n  - aid: mailtrap:mailtrap-email-sandbox\n    name: Mailtrap Email Sandbox API\n    description: >-\n      The Mailtrap Email Sandbox API provides a safe email testing environment\n      to inspect and debug emails before sending to real recipients. Supports\n      switching between sandbox and production modes in official SDKs.\n    humanURL: https://mailtrap.io/automated-email-testing/\n    baseURL: https://sandbox.api.mailtrap.io\n    tags:\n      - Email Testing\n     \
  \ - QA\n      - Sandbox\n    properties:\n      - type: Documentation\n        url: https://docs.mailtrap.io/docs/email-sandbox-overview\n      - type: OpenAPI\n        url: openapi/mailtrap-email-sandbox-openapi.yml\ncommon:\n  - type: Portal\n    url: https://mailtrap.io/\n  - type: Documentation\n    url: https://docs.mailtrap.io/\n  - type: Sign Up\n    url: https://mailtrap.io/register/signup\n  - type: Login\n    url: https://mailtrap.io/users/sign_in\n  - type: Pricing\n    url: https://mailtrap.io/pricing/\n  - type: Status\n    url: https://status.mailtrap.io/\n  - type: Support\n    url: https://help.mailtrap.io/\n  - type: Terms of Service\n    url: https://mailtrap.io/terms-of-use/\n  - type: Privacy Policy\n    url: https://mailtrap.io/privacy-policy/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/mailtrap/refs/heads/main/apis.yml
tags:
- Email
- Email Delivery
- Email Sandbox
- Email Testing
- Transactional Email
url: https://raw.githubusercontent.com/api-evangelist/mailtrap/refs/heads/main/apis.yml
use_cases: []
---
