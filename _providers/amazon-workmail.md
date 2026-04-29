---
api_count: 1
api_specs:
- filename: amazon-workmail-openapi-original.yaml
  format: yaml
  label: Amazon WorkMail API
  slug: amazon-workmail-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-workmail/refs/heads/main/openapi/amazon-workmail-openapi-original.yaml
apis:
- description: The Amazon WorkMail API provides programmatic access to manage organizations, users, groups, aliases, mailboxes, resources, and mobile device access. It enables automation of email infrastructure prov
  name: Amazon WorkMail API
  slug: amazon-workmail-api
capabilities:
- description: Unified workflow for IT administrators and email operations teams to manage Amazon WorkMail organizations, users, groups, and mobile device access. Enables programmatic provisioning, deprovisioning, a
  name: Amazon WorkMail Email Management
  slug: email-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/workmail/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/workmail/latest/adminguide/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/workmail/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: SpectralRules
  url: rules/amazon-workmail-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-workmail-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/email-management.yaml
created: '2026-03-16'
description: Amazon WorkMail is a secure, managed business email and calendar service with support for existing desktop and mobile email client applications. It provides encrypted mailboxes, corporate calendaring, full Outlook compatibility, and enterprise-grade security controls for business communications. WorkMail integrates with Active Directory, supports IMAP and Exchange ActiveSync for mobile devices, and provides 80 API operations for programmatic management.
features:
- description: Native support for Microsoft Outlook on Windows and Mac OS X with free/busy scheduling, delegation, and out-of-office replies.
  name: Outlook Compatibility
- description: Automatic encryption at rest using AWS KMS and SSL encryption in transit with spam and virus protection.
  name: Enterprise-Grade Security
- description: Integration with AWS Directory Service AD Connector and Microsoft Active Directory for seamless enterprise authentication.
  name: Active Directory Integration
- description: Exchange ActiveSync support with remote device encryption, lock, password reset, and wipe capabilities across iOS, Android, and Windows.
  name: Mobile Device Management
- description: Hybrid environments with Microsoft Exchange Server 2010 and 2013 for gradual migration scenarios.
  name: Exchange Interoperability
- description: Programmatic API for managing users, groups, resources, and organizational settings at scale.
  name: Administrative SDK
- description: Configurable email flow rules for filtering and routing messages based on custom organizational policies.
  name: Email Flow Rules
- description: Email journaling capabilities for compliance archiving and e-discovery requirements.
  name: Journaling and Archiving
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: AD Connector and Simple AD for directory integration and single sign-on capabilities.
  name: AWS Directory Service
- description: Key Management Service for managing encryption keys for mailbox data at rest.
  name: AWS KMS
- description: Audit logging of all WorkMail API calls for compliance and security monitoring.
  name: AWS CloudTrail
- description: Lambda integration for email flow rules and custom email processing workflows.
  name: AWS Lambda
- description: Native Outlook MAPI support for Windows and Mac desktops.
  name: Microsoft Outlook
jsonld:
- class_count: 184
  name: Amazon Workmail Context
  property_count: 125
  slug: amazon-workmail-context
layout: provider
modified: '2026-04-19'
name: Amazon WorkMail
rules:
- name: Amazon WorkMail API Rules
  rule_count: 19
  severity_counts:
    error: 8
    hint: 0
    info: 3
    warn: 8
  slug: amazon-workmail-spectral-rules
skills: []
slug: amazon-workmail
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-workmail\nname: Amazon WorkMail\ndescription: >-\n  Amazon WorkMail is a secure, managed business email and calendar service with\n  support for existing desktop and mobile email client applications. It provides\n  encrypted mailboxes, corporate calendaring, full Outlook compatibility, and\n  enterprise-grade security controls for business communications. WorkMail\n  integrates with Active Directory, supports IMAP and Exchange ActiveSync for\n  mobile devices, and provides 80 API operations for programmatic management.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Business Communication\n  - Calendar\n  - Email\n  - Exchange\n  - Enterprise\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-workmail/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-workmail:amazon-workmail-api\n    name: Amazon WorkMail\
  \ API\n    description: >-\n      The Amazon WorkMail API provides programmatic access to manage\n      organizations, users, groups, aliases, mailboxes, resources, and mobile\n      device access. It enables automation of email infrastructure provisioning\n      and management for enterprise deployments with 80 operations.\n    humanURL: https://aws.amazon.com/workmail/\n    baseURL: https://workmail.amazonaws.com\n    tags:\n      - AWS\n      - Calendar\n      - Email\n      - Enterprise\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/workmail/latest/adminguide/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/workmail/latest/APIReference/\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/workmail/latest/adminguide/getting_started.html\n      - type: Pricing\n        url: https://aws.amazon.com/workmail/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/workmail/faqs/\n      - type: OpenAPI\n\
  \        url: openapi/amazon-workmail-openapi-original.yaml\n      - type: JSONSchema\n        url: json-schema/workmail-organization-schema.json\n      - type: JSONLD\n        url: json-ld/amazon-workmail-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/\n  - type: Website\n    url: https://aws.amazon.com/workmail/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/workmail/latest/adminguide/\n  - type: Console\n    url: https://console.aws.amazon.com/workmail/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: SignUp\n    url: https://signin.aws.amazon.com/signup?request_type=register\n  - type: Login\n    url: https://aws.amazon.com/console/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: GitHubOrganization\n    url: https://github.com/aws\n\
  \  - type: SpectralRules\n    url: rules/amazon-workmail-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-workmail-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/email-management.yaml\n  - type: Features\n    data:\n      - name: Outlook Compatibility\n        description: >-\n          Native support for Microsoft Outlook on Windows and Mac OS X with\n          free/busy scheduling, delegation, and out-of-office replies.\n      - name: Enterprise-Grade Security\n        description: >-\n          Automatic encryption at rest using AWS KMS and SSL encryption in\n          transit with spam and virus protection.\n      - name: Active Directory Integration\n        description: >-\n          Integration with AWS Directory Service AD Connector and Microsoft\n          Active Directory for seamless enterprise authentication.\n      - name: Mobile Device Management\n        description: >-\n          Exchange ActiveSync support with remote device encryption,\
  \ lock,\n          password reset, and wipe capabilities across iOS, Android, and Windows.\n      - name: Exchange Interoperability\n        description: >-\n          Hybrid environments with Microsoft Exchange Server 2010 and 2013\n          for gradual migration scenarios.\n      - name: Administrative SDK\n        description: >-\n          Programmatic API for managing users, groups, resources, and\n          organizational settings at scale.\n      - name: Email Flow Rules\n        description: >-\n          Configurable email flow rules for filtering and routing messages\n          based on custom organizational policies.\n      - name: Journaling and Archiving\n        description: >-\n          Email journaling capabilities for compliance archiving and\n          e-discovery requirements.\n  - type: UseCases\n    data:\n      - name: Exchange Migration\n        description: >-\n          Migrate from Microsoft Exchange to Amazon WorkMail with minimal\n          disruption using\
  \ hybrid environment support.\n      - name: Enterprise Email Provisioning\n        description: >-\n          Automate user and mailbox provisioning via API for large-scale\n          enterprise deployments.\n      - name: Compliance Email Archiving\n        description: >-\n          Use journaling and encryption for HIPAA-compliant and regulatory\n          email archiving programs.\n      - name: Mobile Workforce Enablement\n        description: >-\n          Provide secure mobile email access with ActiveSync and mobile\n          device management policies.\n      - name: Hybrid Cloud Email\n        description: >-\n          Run WorkMail alongside existing Exchange infrastructure for\n          gradual cloud migration.\n  - type: Integrations\n    data:\n      - name: AWS Directory Service\n        description: >-\n          AD Connector and Simple AD for directory integration and\n          single sign-on capabilities.\n      - name: AWS KMS\n        description: >-\n          Key\
  \ Management Service for managing encryption keys for\n          mailbox data at rest.\n      - name: AWS CloudTrail\n        description: >-\n          Audit logging of all WorkMail API calls for compliance and\n          security monitoring.\n      - name: AWS Lambda\n        description: >-\n          Lambda integration for email flow rules and custom email\n          processing workflows.\n      - name: Microsoft Outlook\n        description: >-\n          Native Outlook MAPI support for Windows and Mac desktops.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-workmail/refs/heads/main/apis.yml
tags:
- AWS
- Business Communication
- Calendar
- Email
- Exchange
- Enterprise
url: https://raw.githubusercontent.com/api-evangelist/amazon-workmail/refs/heads/main/apis.yml
use_cases:
- description: Migrate from Microsoft Exchange to Amazon WorkMail with minimal disruption using hybrid environment support.
  name: Exchange Migration
- description: Automate user and mailbox provisioning via API for large-scale enterprise deployments.
  name: Enterprise Email Provisioning
- description: Use journaling and encryption for HIPAA-compliant and regulatory email archiving programs.
  name: Compliance Email Archiving
- description: Provide secure mobile email access with ActiveSync and mobile device management policies.
  name: Mobile Workforce Enablement
- description: Run WorkMail alongside existing Exchange infrastructure for gradual cloud migration.
  name: Hybrid Cloud Email
---
