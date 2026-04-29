---
api_count: 5
api_specs:
- filename: cisco-voice-portal-call-control-openapi.yml
  format: yaml
  label: Cisco Voice Portal Call Control API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cisco-voice-portal/refs/heads/main/openapi/cisco-voice-portal-call-control-openapi.yml
- filename: cisco-voice-portal-reporting-openapi.yml
  format: yaml
  label: Cisco Voice Portal Reporting API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cisco-voice-portal/refs/heads/main/openapi/cisco-voice-portal-reporting-openapi.yml
- filename: cisco-voice-portal-administration-openapi.yml
  format: yaml
  label: Cisco Voice Portal Administration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cisco-voice-portal/refs/heads/main/openapi/cisco-voice-portal-administration-openapi.yml
- filename: cisco-voice-portal-vxml-services-openapi.yml
  format: yaml
  label: Cisco Voice Portal VXML Services API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cisco-voice-portal/refs/heads/main/openapi/cisco-voice-portal-vxml-services-openapi.yml
- filename: cisco-voice-portal-call-events-asyncapi.yml
  format: yaml
  label: Cisco Voice Portal Call Events API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/cisco-voice-portal/refs/heads/main/asyncapi/cisco-voice-portal-call-events-asyncapi.yml
apis:
- description: Provides programmatic access to call control functions on the CVP Call Server including active call management, call routing, transfers, SIP session monitoring, and health status of the call processin
  name: Cisco Voice Portal Call Control API
  slug: ''
- description: Access to call detail records (CDRs), real-time call statistics, historical reporting data, and report template execution through the CVP Reporting Server.
  name: Cisco Voice Portal Reporting API
  slug: ''
- description: 'The CVP OAMP (Operations, Administration, Maintenance, and Provisioning) REST API for managing devices, applications, dialed number patterns, SIP server groups, system configuration, user management, '
  name: Cisco Voice Portal Administration API
  slug: ''
- description: Management and monitoring of the CVP VXML Server including application deployment, activation, configuration, session monitoring, micro-application management, media file management, and grammar manag
  name: Cisco Voice Portal VXML Services API
  slug: ''
- description: Event-driven interface for consuming real-time CVP call lifecycle events, system alerts, device status changes, and operational notifications via JMS messaging and syslog.
  name: Cisco Voice Portal Call Events API
  slug: ''
asyncapis:
- description: The Cisco Unified Customer Voice Portal (CVP) generates real-time events during call processing that can be consumed for monitoring, analytics, and integration purposes. CVP publishes call lifecycle e
  name: Cisco Voice Portal Call Events API
  slug: cisco-voice-portal-call-events-asyncapi
capabilities:
- description: Unified workflow for contact center operations combining call control, reporting, administration, and VXML services. Used by contact center administrators and operations teams for monitoring, managing
  name: Cisco Voice Portal Contact Center Operations
  slug: contact-center-operations
common:
- title: ''
  type: DeveloperPortal
  url: https://developer.cisco.com/
- title: ''
  type: Authentication
  url: https://developer.cisco.com/docs/voice-portal/#!authentication
- title: ''
  type: StatusPage
  url: https://status.cisco.com/
- title: ''
  type: Support
  url: https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/tsd-products-support-series-home.html
- title: ''
  type: TermsOfService
  url: https://www.cisco.com/c/en/us/about/legal/terms-conditions.html
- title: ''
  type: PrivacyPolicy
  url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html
- title: ''
  type: Documentation
  url: https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/tsd-products-support-series-home.html
- title: ''
  type: GettingStarted
  url: https://developer.cisco.com/site/devnet/
- title: ''
  type: Blog
  url: https://blogs.cisco.com/developer
- title: ''
  type: GitHubOrganization
  url: https://github.com/CiscoDevNet
- title: ''
  type: SignUp
  url: https://developer.cisco.com/join/devnet
- title: ''
  type: ReleaseNotes
  url: https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-release-notes-list.html
- title: ''
  type: JSONSchema
  url: json-schema/cisco-voice-portal-call-detail-record.json
- title: ''
  type: JSONSchema
  url: json-schema/cisco-voice-portal-device.json
- title: ''
  type: JSONSchema
  url: json-schema/cisco-voice-portal-application.json
- title: ''
  type: JSONSchema
  url: json-schema/cisco-voice-portal-dialed-number-pattern.json
created: '2024'
description: Cisco Voice Portal (CVP) is an enterprise-class Voice XML (VXML) browser and call control platform that enables self-service applications for voice, video, and multimodal interactions.
features: []
image: https://www.cisco.com/c/en/us/products/customer-collaboration/unified-contact-center-enterprise/index.html
integrations: []
jsonld:
- class_count: 0
  name: Cisco Voice Portal Administration Context
  property_count: 0
  slug: cisco-voice-portal-administration-context
- class_count: 0
  name: Cisco Voice Portal Call Control Context
  property_count: 0
  slug: cisco-voice-portal-call-control-context
- class_count: 0
  name: Cisco Voice Portal Reporting Context
  property_count: 0
  slug: cisco-voice-portal-reporting-context
- class_count: 0
  name: Cisco Voice Portal Vxml Services Context
  property_count: 0
  slug: cisco-voice-portal-vxml-services-context
layout: provider
modified: '2026-04-19'
name: Cisco Voice Portal
rules:
- name: Cisco Voice Portal API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: cisco-voice-portal-spectral-rules
skills: []
slug: cisco-voice-portal
solutions: []
source_filename: apis.yml
source_yaml: "name: Cisco Voice Portal\ndescription: Cisco Voice Portal (CVP) is an enterprise-class Voice XML (VXML) browser and call control platform that enables self-service applications for voice, video, and multimodal interactions.\nimage: https://www.cisco.com/c/en/us/products/customer-collaboration/unified-contact-center-enterprise/index.html\ntags:\n  - Contact Center\n  - IVR\n  - Telephony\n  - Voice\n  - VXML\ncreated: '2024'\nmodified: '2026-04-19'\nspecificationVersion: '0.18'\nurl: https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html\napis:\n  - name: Cisco Voice Portal Call Control API\n    description: Provides programmatic access to call control functions on the CVP Call Server including active call management, call routing, transfers, SIP session monitoring, and health status of the call processing component.\n    image: https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html\n    humanURL: https://developer.cisco.com/docs/voice-portal/\n\
  \    baseURL: https://cvp-callserver.example.com:8000/cvp/rest\n    tags:\n      - Call Control\n      - Routing\n      - Session Management\n      - SIP\n    properties:\n      - type: Documentation\n        url: https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html\n      - type: OpenAPI\n        url: openapi/cisco-voice-portal-call-control-openapi.yml\n  - name: Cisco Voice Portal Reporting API\n    description: Access to call detail records (CDRs), real-time call statistics, historical reporting data, and report template execution through the CVP Reporting Server.\n    image: https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html\n    humanURL: https://developer.cisco.com/docs/voice-portal/\n    baseURL: https://cvp-reporting.example.com:8111/cvp-reporting/rest\n    tags:\n      - Analytics\n      - CDR\n      - Reporting\n      - Statistics\n    properties:\n      - type: Documentation\n\
  \        url: https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html\n      - type: OpenAPI\n        url: openapi/cisco-voice-portal-reporting-openapi.yml\n  - name: Cisco Voice Portal Administration API\n    description: The CVP OAMP (Operations, Administration, Maintenance, and Provisioning) REST API for managing devices, applications, dialed number patterns, SIP server groups, system configuration, user management, and deployment operations.\n    image: https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html\n    humanURL: https://developer.cisco.com/docs/voice-portal/\n    baseURL: https://cvp-oamp.example.com:9443/oamp/rest\n    tags:\n      - Administration\n      - Configuration\n      - Management\n      - OAMP\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html\n\
  \      - type: OpenAPI\n        url: openapi/cisco-voice-portal-administration-openapi.yml\n  - name: Cisco Voice Portal VXML Services API\n    description: Management and monitoring of the CVP VXML Server including application deployment, activation, configuration, session monitoring, micro-application management, media file management, and grammar management.\n    image: https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html\n    humanURL: https://developer.cisco.com/docs/voice-portal/\n    baseURL: https://cvp-vxmlserver.example.com:7443/CVP/rest\n    tags:\n      - Call Studio\n      - IVR\n      - Micro-Applications\n      - Voice Applications\n      - VXML\n    properties:\n      - type: Documentation\n        url: https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html\n      - type: OpenAPI\n        url: openapi/cisco-voice-portal-vxml-services-openapi.yml\n  - name: Cisco Voice Portal\
  \ Call Events API\n    description: Event-driven interface for consuming real-time CVP call lifecycle events, system alerts, device status changes, and operational notifications via JMS messaging and syslog.\n    image: https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html\n    humanURL: https://developer.cisco.com/docs/voice-portal/\n    baseURL: tcp://cvp-callserver.example.com:61616\n    tags:\n      - Call Lifecycle\n      - Events\n      - JMS\n      - Monitoring\n      - Notifications\n    properties:\n      - type: Documentation\n        url: https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html\n      - type: AsyncAPI\n        url: asyncapi/cisco-voice-portal-call-events-asyncapi.yml\ncommon:\n  - type: DeveloperPortal\n    url: https://developer.cisco.com/\n  - type: Authentication\n    url: https://developer.cisco.com/docs/voice-portal/#!authentication\n  - type: StatusPage\n \
  \   url: https://status.cisco.com/\n  - type: Support\n    url: https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/tsd-products-support-series-home.html\n  - type: TermsOfService\n    url: https://www.cisco.com/c/en/us/about/legal/terms-conditions.html\n  - type: PrivacyPolicy\n    url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html\n  - type: Documentation\n    url: https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/tsd-products-support-series-home.html\n  - type: GettingStarted\n    url: https://developer.cisco.com/site/devnet/\n  - type: Blog\n    url: https://blogs.cisco.com/developer\n  - type: GitHubOrganization\n    url: https://github.com/CiscoDevNet\n  - type: SignUp\n    url: https://developer.cisco.com/join/devnet\n  - type: ReleaseNotes\n    url: https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-release-notes-list.html\n  - type: JSONSchema\n    url: json-schema/cisco-voice-portal-call-detail-record.json\n\
  \  - type: JSONSchema\n    url: json-schema/cisco-voice-portal-device.json\n  - type: JSONSchema\n    url: json-schema/cisco-voice-portal-application.json\n  - type: JSONSchema\n    url: json-schema/cisco-voice-portal-dialed-number-pattern.json\n  - type: Features\n    url: https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html\n  - type: UseCases\n    url: https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html\n  - type: Integrations\n    url: https://developer.cisco.com/ecosystem/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cisco-voice-portal/refs/heads/main/apis.yml
tags:
- Contact Center
- IVR
- Telephony
- Voice
- VXML
url: https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html
use_cases: []
---
