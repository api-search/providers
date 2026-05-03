---
api_count: 12
api_specs:
- filename: opsgenie-alert-openapi.yml
  format: yaml
  label: OpsGenie Alert API
  slug: opsgenie-alert
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-alert-openapi.yml
- filename: opsgenie-incident-openapi.yml
  format: yaml
  label: OpsGenie Incident API
  slug: opsgenie-incident
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-incident-openapi.yml
- filename: opsgenie-user-openapi.yml
  format: yaml
  label: OpsGenie User API
  slug: opsgenie-user
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-user-openapi.yml
- filename: opsgenie-team-openapi.yml
  format: yaml
  label: OpsGenie Team API
  slug: opsgenie-team
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-team-openapi.yml
- filename: opsgenie-schedule-openapi.yml
  format: yaml
  label: OpsGenie Schedule API
  slug: opsgenie-schedule
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-schedule-openapi.yml
- filename: opsgenie-escalation-openapi.yml
  format: yaml
  label: OpsGenie Escalation API
  slug: opsgenie-escalation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-escalation-openapi.yml
- filename: opsgenie-integration-openapi.yml
  format: yaml
  label: OpsGenie Integration API
  slug: opsgenie-integration
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-integration-openapi.yml
- filename: opsgenie-heartbeat-openapi.yml
  format: yaml
  label: OpsGenie Heartbeat API
  slug: opsgenie-heartbeat
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-heartbeat-openapi.yml
- filename: opsgenie-service-openapi.yml
  format: yaml
  label: OpsGenie Service API
  slug: opsgenie-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-service-openapi.yml
- filename: opsgenie-notification-rule-openapi.yml
  format: yaml
  label: OpsGenie Notification Rule API
  slug: opsgenie-notification-rule
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-notification-rule-openapi.yml
- filename: opsgenie-account-openapi.yml
  format: yaml
  label: OpsGenie Account API
  slug: opsgenie-account
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-account-openapi.yml
- filename: opsgenie-maintenance-openapi.yml
  format: yaml
  label: OpsGenie Maintenance API
  slug: opsgenie-maintenance
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/openapi/opsgenie-maintenance-openapi.yml
apis:
- description: Programmatically create, update, close, and manage alerts within the OpsGenie incident management platform. Alert creation, deletion, and action requests are processed asynchronously to provide higher
  name: OpsGenie Alert API
  slug: opsgenie-alert
- description: Create and manage incidents programmatically. Supports defining responders, tags, custom details, priority levels, and impacted services for each incident. Available to Standard and Enterprise plan us
  name: OpsGenie Incident API
  slug: opsgenie-incident
- description: Manage user accounts within the OpsGenie platform. Create, retrieve, update, and delete users, list users, and retrieve escalations associated with specific users. Supports managing user roles, contac
  name: OpsGenie User API
  slug: opsgenie-user
- description: Manage teams within the OpsGenie platform. Create, update, retrieve, and delete teams, manage team members and their roles. Teams are a core organizational unit used to route alerts and assign on-call
  name: OpsGenie Team API
  slug: opsgenie-team
- description: Programmatically manage on-call schedules and rotations. Create, update, and delete schedules, manage rotations and overrides, and query who is currently on call. Enables custom dashboards and integra
  name: OpsGenie Schedule API
  slug: opsgenie-schedule
- description: Manage escalation policies that define how alerts are routed when initial responders do not acknowledge them. Create, update, retrieve, and delete escalation configurations with rules defining sequenc
  name: OpsGenie Escalation API
  slug: opsgenie-escalation
- description: Programmatically manage integrations that connect OpsGenie with third-party monitoring, ticketing, and communication tools. Create, enable, disable, and configure integrations and their associated act
  name: OpsGenie Integration API
  slug: opsgenie-integration
- description: Set up and manage heartbeat monitors that track the health and availability of systems and services. Heartbeats expect periodic pings from monitored systems and generate an alert when a ping is not re
  name: OpsGenie Heartbeat API
  slug: opsgenie-heartbeat
- description: Manage services within the OpsGenie platform. Services represent business-critical applications and components that can be associated with incidents to track impact. Used in conjunction with the Incid
  name: OpsGenie Service API
  slug: opsgenie-service
- description: Manage notification rules that control how and when users receive alert notifications. Create, update, and delete notification rules, including conditions, time restrictions, and notification channels
  name: OpsGenie Notification Rule API
  slug: opsgenie-notification-rule
- description: 'Retrieve account-level information and configuration settings. Access details about an OpsGenie account including plan information and account metadata. Foundational API for administrative operations '
  name: OpsGenie Account API
  slug: opsgenie-account
- description: 'Manage maintenance windows that suppress alert notifications during planned maintenance periods. Create, update, list, and delete maintenance windows with configurable time ranges and rules for which '
  name: OpsGenie Maintenance API
  slug: opsgenie-maintenance
asyncapis:
- description: OpsGenie sends webhook notifications for alert actions to configured webhook URLs. When alert events occur such as create, acknowledge, close, or delete, OpsGenie posts a JSON payload to the registere
  name: OpsGenie Webhook Events
  slug: opsgenie-webhook-asyncapi
common:
- title: ''
  type: Portal
  url: https://docs.opsgenie.com/
- title: ''
  type: Documentation
  url: https://docs.opsgenie.com/docs
- title: ''
  type: Website
  url: https://www.atlassian.com/software/opsgenie
- title: ''
  type: PrivacyPolicy
  url: https://www.atlassian.com/legal/privacy-policy
- title: ''
  type: TermsOfService
  url: https://www.atlassian.com/legal/software-license-agreement
- title: ''
  type: Support
  url: https://support.atlassian.com/opsgenie/
- title: ''
  type: Blog
  url: https://www.atlassian.com/blog
- title: ''
  type: Login
  url: https://app.opsgenie.com/auth/login
created: '2025-03-01'
description: OpsGenie is an incident management and alerting platform, now part of Atlassian, that helps operations teams manage on-call schedules, route alerts, and coordinate incident response. The OpsGenie developer platform provides a comprehensive set of REST APIs for programmatically managing alerts, incidents, teams, schedules, escalations, integrations, heartbeats, services, notification rules, accounts, and maintenance windows.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Opsgenie Context
  property_count: 10
  slug: opsgenie-context
layout: provider
modified: '2026-04-28'
name: OpsGenie
skills: []
slug: opsgenie
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: opsgenie\nname: OpsGenie\ndescription: >-\n  OpsGenie is an incident management and alerting platform, now part of\n  Atlassian, that helps operations teams manage on-call schedules, route\n  alerts, and coordinate incident response. The OpsGenie developer platform\n  provides a comprehensive set of REST APIs for programmatically managing\n  alerts, incidents, teams, schedules, escalations, integrations,\n  heartbeats, services, notification rules, accounts, and maintenance\n  windows.\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Alerts\n  - Incident Management\n  - Monitoring\n  - On-Call\n  - Operations\ncreated: '2025-03-01'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: opsgenie:opsgenie-alert\n    name: OpsGenie Alert API\n    description: >-\n\
  \      Programmatically create, update, close, and manage alerts within the\n      OpsGenie incident management platform. Alert creation, deletion, and\n      action requests are processed asynchronously to provide higher\n      availability and scalability. Supports alert priorities, responders,\n      tags, custom details, notes, and acknowledgments.\n    humanURL: https://docs.opsgenie.com/docs/alert-api\n    baseURL: https://api.opsgenie.com\n    tags:\n      - Alerts\n      - Incident Management\n      - Monitoring\n      - Notifications\n    properties:\n      - type: Documentation\n        url: https://docs.opsgenie.com/docs/alert-api\n      - type: OpenAPI\n        url: openapi/opsgenie-alert-openapi.yml\n      - type: JSONSchema\n        url: json-schema/opsgenie-alert-schema.json\n  - aid: opsgenie:opsgenie-incident\n    name: OpsGenie Incident API\n    description: >-\n      Create and manage incidents programmatically. Supports defining\n      responders, tags, custom details,\
  \ priority levels, and impacted\n      services for each incident. Available to Standard and Enterprise\n      plan users with endpoints for creating, updating, closing, and\n      resolving incidents in a structured response workflow.\n    humanURL: https://docs.opsgenie.com/docs/incident-api\n    baseURL: https://api.opsgenie.com\n    tags:\n      - Incidents\n      - Incident Management\n      - Operations\n      - Response\n    properties:\n      - type: Documentation\n        url: https://docs.opsgenie.com/docs/incident-api\n      - type: OpenAPI\n        url: openapi/opsgenie-incident-openapi.yml\n      - type: JSONSchema\n        url: json-schema/opsgenie-incident-schema.json\n  - aid: opsgenie:opsgenie-user\n    name: OpsGenie User API\n    description: >-\n      Manage user accounts within the OpsGenie platform. Create, retrieve,\n      update, and delete users, list users, and retrieve escalations\n      associated with specific users. Supports managing user roles,\n      contact\
  \ methods, and notification preferences.\n    humanURL: https://docs.opsgenie.com/docs/user-api\n    baseURL: https://api.opsgenie.com\n    tags:\n      - Users\n      - Accounts\n      - Identity\n      - Management\n    properties:\n      - type: Documentation\n        url: https://docs.opsgenie.com/docs/user-api\n      - type: OpenAPI\n        url: openapi/opsgenie-user-openapi.yml\n  - aid: opsgenie:opsgenie-team\n    name: OpsGenie Team API\n    description: >-\n      Manage teams within the OpsGenie platform. Create, update, retrieve,\n      and delete teams, manage team members and their roles. Teams are a\n      core organizational unit used to route alerts and assign on-call\n      responsibilities to groups of users.\n    humanURL: https://docs.opsgenie.com/docs/team-api\n    baseURL: https://api.opsgenie.com\n    tags:\n      - Teams\n      - Groups\n      - Collaboration\n      - Management\n    properties:\n      - type: Documentation\n        url: https://docs.opsgenie.com/docs/team-api\n\
  \      - type: OpenAPI\n        url: openapi/opsgenie-team-openapi.yml\n  - aid: opsgenie:opsgenie-schedule\n    name: OpsGenie Schedule API\n    description: >-\n      Programmatically manage on-call schedules and rotations. Create,\n      update, and delete schedules, manage rotations and overrides, and\n      query who is currently on call. Enables custom dashboards and\n      integrations that reflect real-time on-call status.\n    humanURL: https://docs.opsgenie.com/docs/schedule-api\n    baseURL: https://api.opsgenie.com\n    tags:\n      - Schedules\n      - On-Call\n      - Rotations\n      - Planning\n    properties:\n      - type: Documentation\n        url: https://docs.opsgenie.com/docs/schedule-api\n      - type: OpenAPI\n        url: openapi/opsgenie-schedule-openapi.yml\n  - aid: opsgenie:opsgenie-escalation\n    name: OpsGenie Escalation API\n    description: >-\n      Manage escalation policies that define how alerts are routed when\n      initial responders do not acknowledge\
  \ them. Create, update,\n      retrieve, and delete escalation configurations with rules defining\n      sequence of notifications and configurable delay intervals.\n    humanURL: https://docs.opsgenie.com/docs/escalation-api\n    baseURL: https://api.opsgenie.com\n    tags:\n      - Escalations\n      - Routing\n      - Alerts\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://docs.opsgenie.com/docs/escalation-api\n      - type: OpenAPI\n        url: openapi/opsgenie-escalation-openapi.yml\n  - aid: opsgenie:opsgenie-integration\n    name: OpsGenie Integration API\n    description: >-\n      Programmatically manage integrations that connect OpsGenie with\n      third-party monitoring, ticketing, and communication tools. Create,\n      enable, disable, and configure integrations and their associated\n      actions. Note that Zendesk, Slack, and Incoming Call integrations\n      must be configured through the OpsGenie web interface.\n    humanURL: https://docs.opsgenie.com/docs/integration-api\n\
  \    baseURL: https://api.opsgenie.com\n    tags:\n      - Integrations\n      - Connections\n      - Third Party\n      - Automation\n    properties:\n      - type: Documentation\n        url: https://docs.opsgenie.com/docs/integration-api\n      - type: OpenAPI\n        url: openapi/opsgenie-integration-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/opsgenie-webhook-asyncapi.yml\n  - aid: opsgenie:opsgenie-heartbeat\n    name: OpsGenie Heartbeat API\n    description: >-\n      Set up and manage heartbeat monitors that track the health and\n      availability of systems and services. Heartbeats expect periodic\n      pings from monitored systems and generate an alert when a ping is\n      not received within the configured interval.\n    humanURL: https://docs.opsgenie.com/docs/heartbeat-api\n    baseURL: https://api.opsgenie.com\n    tags:\n      - Heartbeat\n      - Health Checks\n      - Monitoring\n      - Uptime\n    properties:\n      - type: Documentation\n        url:\
  \ https://docs.opsgenie.com/docs/heartbeat-api\n      - type: OpenAPI\n        url: openapi/opsgenie-heartbeat-openapi.yml\n      - type: JSONSchema\n        url: json-schema/opsgenie-heartbeat-schema.json\n  - aid: opsgenie:opsgenie-service\n    name: OpsGenie Service API\n    description: >-\n      Manage services within the OpsGenie platform. Services represent\n      business-critical applications and components that can be\n      associated with incidents to track impact. Used in conjunction\n      with the Incident API to identify which services are affected\n      during an outage.\n    humanURL: https://docs.opsgenie.com/docs/service-api\n    baseURL: https://api.opsgenie.com\n    tags:\n      - Services\n      - Service Catalog\n      - Operations\n      - Management\n    properties:\n      - type: Documentation\n        url: https://docs.opsgenie.com/docs/service-api\n      - type: OpenAPI\n        url: openapi/opsgenie-service-openapi.yml\n  - aid: opsgenie:opsgenie-notification-rule\n\
  \    name: OpsGenie Notification Rule API\n    description: >-\n      Manage notification rules that control how and when users receive\n      alert notifications. Create, update, and delete notification rules,\n      including conditions, time restrictions, and notification channels\n      such as email, SMS, push notifications, and voice calls.\n    humanURL: https://docs.opsgenie.com/docs/notification-rule-api\n    baseURL: https://api.opsgenie.com\n    tags:\n      - Notifications\n      - Rules\n      - Alerts\n      - Configuration\n    properties:\n      - type: Documentation\n        url: https://docs.opsgenie.com/docs/notification-rule-api\n      - type: OpenAPI\n        url: openapi/opsgenie-notification-rule-openapi.yml\n  - aid: opsgenie:opsgenie-account\n    name: OpsGenie Account API\n    description: >-\n      Retrieve account-level information and configuration settings.\n      Access details about an OpsGenie account including plan\n      information and account metadata.\
  \ Foundational API for\n      administrative operations and account management.\n    humanURL: https://docs.opsgenie.com/docs/account-api\n    baseURL: https://api.opsgenie.com\n    tags:\n      - Accounts\n      - Administration\n      - Settings\n      - Configuration\n    properties:\n      - type: Documentation\n        url: https://docs.opsgenie.com/docs/account-api\n      - type: OpenAPI\n        url: openapi/opsgenie-account-openapi.yml\n  - aid: opsgenie:opsgenie-maintenance\n    name: OpsGenie Maintenance API\n    description: >-\n      Manage maintenance windows that suppress alert notifications\n      during planned maintenance periods. Create, update, list, and\n      delete maintenance windows with configurable time ranges and\n      rules for which integrations or policies are affected.\n    humanURL: https://docs.opsgenie.com/docs/maintenance-api\n    baseURL: https://api.opsgenie.com\n    tags:\n      - Maintenance\n      - Windows\n      - Scheduling\n      - Operations\n\
  \    properties:\n      - type: Documentation\n        url: https://docs.opsgenie.com/docs/maintenance-api\n      - type: OpenAPI\n        url: openapi/opsgenie-maintenance-openapi.yml\ncommon:\n  - type: Portal\n    name: OpsGenie Documentation Portal\n    url: https://docs.opsgenie.com/\n  - type: Documentation\n    name: OpsGenie Documentation\n    url: https://docs.opsgenie.com/docs\n  - type: Website\n    name: OpsGenie Website\n    url: https://www.atlassian.com/software/opsgenie\n  - type: PrivacyPolicy\n    name: Atlassian Privacy Policy\n    url: https://www.atlassian.com/legal/privacy-policy\n  - type: TermsOfService\n    name: Atlassian Terms of Service\n    url: https://www.atlassian.com/legal/software-license-agreement\n  - type: Support\n    name: Atlassian OpsGenie Support\n    url: https://support.atlassian.com/opsgenie/\n  - type: Blog\n    name: Atlassian Blog\n    url: https://www.atlassian.com/blog\n  - type: Login\n    name: OpsGenie Login\n    url: https://app.opsgenie.com/auth/login\n\
  maintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/apis.yml
tags:
- Alerts
- Incident Management
- Monitoring
- On-Call
- Operations
url: https://raw.githubusercontent.com/api-evangelist/opsgenie/refs/heads/main/apis.yml
use_cases: []
---
