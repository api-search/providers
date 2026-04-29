---
api_count: 1
api_specs:
- filename: ahasend-openapi.yml
  format: yaml
  label: AhaSend
  slug: ahasend
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ahasend/refs/heads/main/openapi/ahasend-openapi.yml
apis:
- description: Send, receive, and track transactional emails with the AhaSend REST API. Supports sending messages, managing domains, webhooks, routes, API keys, suppressions, SMTP credentials, and viewing delivery s
  name: AhaSend
  slug: ahasend
capabilities:
- description: Unified workflow for sending transactional emails, managing domains, configuring webhooks, and monitoring delivery statistics. Used by developers integrating email notifications into applications.
  name: AhaSend Email Operations
  slug: email-operations
common:
- title: ''
  type: Pricing
  url: https://ahasend.com/pricing
- title: ''
  type: Blog
  url: https://ahasend.com/blog
- title: ''
  type: Support
  url: https://ahasend.com/help
- title: ''
  type: PrivacyPolicy
  url: https://ahasend.com/privacy
- title: ''
  type: TermsOfService
  url: https://ahasend.com/terms
- title: ''
  type: SignUp
  url: https://dash.ahasend.com/user/register
- title: ''
  type: Login
  url: https://dash.ahasend.com/user/login
- title: ''
  type: GitHubOrganization
  url: https://github.com/AhaSend
- title: Go SDK
  type: SDK
  url: https://github.com/AhaSend/ahasend-go
- title: ''
  type: CLI
  url: https://github.com/AhaSend/ahasend-cli
- title: Java SDK
  type: SDK
  url: https://github.com/AhaSend/ahasend-java-client
- title: ''
  type: Affiliate
  url: https://ahasend.com/affiliates
- title: ''
  type: SpectralRules
  url: rules/ahasend-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/email-operations.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/ahasend-vocabulary.yaml
created: '2025-02-06'
description: AhaSend is a developer-focused transactional email platform providing fast, reliable email delivery via REST API and SMTP relay. It offers features including email tracking, webhooks, email routing, suppression management, domain management, SMTP credentials, and detailed delivery statistics.
features:
- description: Fast delivery of transactional emails including OTPs and confirmations, targeting sub-2-second delivery to Gmail at 99th percentile.
  name: Transactional Email Delivery
- description: Track email opens and link clicks with real-time analytics.
  name: Email Tracking
- description: Real-time webhook events for delivery, bounces, opens, clicks, and account alerts.
  name: Webhook Notifications
- description: Route incoming emails to HTTP endpoints with automatic parsing of signatures and quoted replies.
  name: Email Routing
- description: Automated handling of bounces, complaints, and unsubscribes with suppression lists.
  name: Suppression Management
- description: Manage sending domains including DNS validation, DKIM rotation, and whitelabeling.
  name: Domain Management
- description: Compatible SMTP relay supporting any programming language or software.
  name: SMTP Relay
- description: Free dedicated IPs for high-volume senders exceeding 300k emails per month.
  name: Dedicated IPs
- description: Archive emails to S3-compatible storage with configurable retention policies.
  name: S3-Compatible Archiving
- description: Enterprise single sign-on via OpenID Connect with granular API credential scoping.
  name: SSO with OIDC
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Node.js integration with code examples and SDK support.
  name: Node.js
- description: Python integration examples for sending emails via API or SMTP.
  name: Python
- description: PHP integration including Symfony Mailer transport support.
  name: PHP / Symfony
- description: Ruby integration with Rails ActionMailer transport.
  name: Ruby on Rails
- description: Official Go SDK for the AhaSend API.
  name: Go
- description: WordPress plugin for routing site emails through AhaSend.
  name: WordPress
- description: Java client generated from OpenAPI spec.
  name: Java
jsonld:
- class_count: 9
  name: Ahasend Api Context
  property_count: 19
  slug: ahasend-api-context
- class_count: 60
  name: Ahasend Openapi V2 Context
  property_count: 129
  slug: ahasend-openapi-v2-context
layout: provider
modified: '2026-04-19'
name: AhaSend
rules:
- name: AhaSend API Rules
  rule_count: 28
  severity_counts:
    error: 11
    hint: 0
    info: 3
    warn: 14
  slug: ahasend-spectral-rules
skills: []
slug: ahasend
solutions: []
source_filename: apis.yml
source_yaml: "aid: ahasend\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ahasend/refs/heads/main/apis.yml\napis:\n- aid: ahasend:ahasend\n  name: AhaSend\n  tags:\n  - Email\n  - Transactional Email\n  - REST API\n  - SMTP\n  - Webhooks\n  humanURL: 'https://ahasend.com/docs'\n  properties:\n  - url: https://ahasend.com/docs\n    type: Documentation\n  - url: https://ahasend.com/docs/api-reference\n    type: APIReference\n  - url: openapi/ahasend-openapi.yml\n    type: OpenAPI\n    title: AhaSend Email API v1\n  - url: openapi/ahasend-openapi-v2.yaml\n    type: OpenAPI\n    title: AhaSend API v2\n  - url: https://ahasend.com/docs/quickstart\n    type: Quickstart\n  - url: https://ahasend.com/docs/authentication\n    type: Authentication\n  description: >-\n    Send, receive, and track transactional emails with the AhaSend REST API. Supports sending messages, managing domains, webhooks, routes, API keys, suppressions, SMTP credentials, and viewing delivery\n    statistics.\n\
  name: AhaSend\ntags:\n- Email\n- Transactional Email\n- Developer Tools\n- SMTP\n- Webhooks\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-06'\nmodified: '2026-04-19'\nposition: Consumer\ndescription: >-\n  AhaSend is a developer-focused transactional email platform providing fast, reliable email delivery via REST API and SMTP relay. It offers features including email tracking, webhooks, email routing, suppression\n  management, domain management, SMTP credentials, and detailed delivery statistics.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n- name: AhaSend Pricing\n  url: https://ahasend.com/pricing\n  type: Pricing\n  description: Pay-as-you-go email pricing with 1,000 free monthly emails.\n- name: AhaSend Blog\n  url: https://ahasend.com/blog\n  type: Blog\n  description: AhaSend blog with email delivery tips and product updates.\n- name: AhaSend\
  \ Help Center\n  url: https://ahasend.com/help\n  type: Support\n  description: Help center and support documentation.\n- name: AhaSend Privacy Policy\n  url: https://ahasend.com/privacy\n  type: PrivacyPolicy\n  description: Privacy policy for AhaSend services.\n- name: AhaSend Terms of Service\n  url: https://ahasend.com/terms\n  type: TermsOfService\n  description: Terms and conditions for using AhaSend.\n- name: AhaSend Sign Up\n  url: https://dash.ahasend.com/user/register\n  type: SignUp\n  description: Create a free AhaSend account.\n- name: AhaSend Login\n  url: https://dash.ahasend.com/user/login\n  type: Login\n  description: Log in to the AhaSend dashboard.\n- name: AhaSend GitHub Organization\n  url: https://github.com/AhaSend\n  type: GitHubOrganization\n  description: Official AhaSend GitHub organization with SDKs and CLI tools.\n- name: AhaSend Go SDK\n  url: https://github.com/AhaSend/ahasend-go\n  type: SDK\n  title: Go SDK\n  description: Official Go SDK for AhaSend.\n\
  - name: AhaSend CLI\n  url: https://github.com/AhaSend/ahasend-cli\n  type: CLI\n  description: Command-line tool for AhaSend.\n- name: AhaSend WordPress Plugin\n  url: https://github.com/AhaSend/wordpress-plugin\n  type: Integrations\n  description: WordPress plugin for sending emails via AhaSend API.\n- name: AhaSend Java Client\n  url: https://github.com/AhaSend/ahasend-java-client\n  type: SDK\n  title: Java SDK\n  description: Java client for AhaSend APIs generated using Swagger Codegen.\n- name: AhaSend Affiliate Program\n  url: https://ahasend.com/affiliates\n  type: Affiliate\n  description: Earn commissions by referring new users to AhaSend.\n- type: Features\n  data:\n  - name: Transactional Email Delivery\n    description: Fast delivery of transactional emails including OTPs and confirmations, targeting sub-2-second delivery to Gmail at 99th percentile.\n  - name: Email Tracking\n    description: Track email opens and link clicks with real-time analytics.\n  - name: Webhook\
  \ Notifications\n    description: Real-time webhook events for delivery, bounces, opens, clicks, and account alerts.\n  - name: Email Routing\n    description: Route incoming emails to HTTP endpoints with automatic parsing of signatures and quoted replies.\n  - name: Suppression Management\n    description: Automated handling of bounces, complaints, and unsubscribes with suppression lists.\n  - name: Domain Management\n    description: Manage sending domains including DNS validation, DKIM rotation, and whitelabeling.\n  - name: SMTP Relay\n    description: Compatible SMTP relay supporting any programming language or software.\n  - name: Dedicated IPs\n    description: Free dedicated IPs for high-volume senders exceeding 300k emails per month.\n  - name: S3-Compatible Archiving\n    description: Archive emails to S3-compatible storage with configurable retention policies.\n  - name: SSO with OIDC\n    description: Enterprise single sign-on via OpenID Connect with granular API credential\
  \ scoping.\n- type: UseCases\n  data:\n  - name: Password Reset Emails\n    description: Send secure one-time password and password reset links with guaranteed fast delivery.\n  - name: Email Verification\n    description: Deliver account verification emails for new user signups.\n  - name: Order Confirmation Emails\n    description: Transactional order and shipping confirmation emails for e-commerce.\n  - name: System Alerts\n    description: Programmatic email alerts and notifications from applications and infrastructure.\n  - name: Inbound Email Processing\n    description: Route and process incoming emails in applications using email routing.\n- type: Integrations\n  data:\n  - name: Node.js\n    description: Native Node.js integration with code examples and SDK support.\n  - name: Python\n    description: Python integration examples for sending emails via API or SMTP.\n  - name: PHP / Symfony\n    description: PHP integration including Symfony Mailer transport support.\n  - name:\
  \ Ruby on Rails\n    description: Ruby integration with Rails ActionMailer transport.\n  - name: Go\n    description: Official Go SDK for the AhaSend API.\n  - name: WordPress\n    description: WordPress plugin for routing site emails through AhaSend.\n  - name: Java\n    description: Java client generated from OpenAPI spec.\n- name: AhaSend Spectral Rules\n  url: rules/ahasend-spectral-rules.yml\n  type: SpectralRules\n  description: Spectral ruleset enforcing AhaSend API conventions.\n- name: AhaSend Email Operations Capability\n  url: capabilities/email-operations.yaml\n  type: NaftikoCapability\n  description: Naftiko workflow capability for email operations.\n- name: AhaSend Vocabulary\n  url: vocabulary/ahasend-vocabulary.yaml\n  type: Vocabulary\n  description: Taxonomy vocabulary for AhaSend APIs.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ahasend/refs/heads/main/apis.yml
tags:
- Email
- Transactional Email
- Developer Tools
- SMTP
- Webhooks
url: https://raw.githubusercontent.com/api-evangelist/ahasend/refs/heads/main/apis.yml
use_cases:
- description: Send secure one-time password and password reset links with guaranteed fast delivery.
  name: Password Reset Emails
- description: Deliver account verification emails for new user signups.
  name: Email Verification
- description: Transactional order and shipping confirmation emails for e-commerce.
  name: Order Confirmation Emails
- description: Programmatic email alerts and notifications from applications and infrastructure.
  name: System Alerts
- description: Route and process incoming emails in applications using email routing.
  name: Inbound Email Processing
---
