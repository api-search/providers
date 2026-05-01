---
api_count: 9
api_specs:
- filename: swagger.json
  format: json
  label: Everbridge Suite API
  slug: ''
  spec_type: OpenAPI
  url: https://api.everbridge.net/rest/swagger.json
apis:
- description: The Everbridge Suite REST API enables developers to integrate Everbridge's critical event management platform into their applications. It provides endpoints for managing contacts, groups, organization
  name: Everbridge Suite API
  slug: ''
- description: The Everbridge Asset Management API allows organizations to manage assets, asset types, asset associations, and related templates. It supports batch operations for bulk asset management and provides l
  name: Everbridge Asset Management API
  slug: ''
- description: The Everbridge Asset Query API provides endpoints for streaming, listing, searching, paginating, and aggregating asset data. It enables organizations to query and retrieve asset information for report
  name: Everbridge Asset Query API
  slug: ''
- description: The Everbridge CEM Alerts API provides GraphQL-based endpoints for querying public alerts and streaming alert data from the Critical Event Management platform. It enables organizations to programmatic
  name: Everbridge CEM Alerts API
  slug: ''
- description: The Everbridge SnapComms API enables targeted internal communications broadcasting through the Everbridge Engage platform. It supports authentication, group and attribute targeting, content templates,
  name: Everbridge SnapComms API
  slug: ''
- description: The Everbridge Digital Apps API provides integration capabilities for mobile, desktop, and web applications from the perspective of an Everbridge contact. It supports receiving and responding to notif
  name: Everbridge Digital Apps API
  slug: ''
- description: The Everbridge Communications API provides endpoints for managing communication templates, categories, reservations, contact builders, message builders, plans, schedules, and variables. It enables org
  name: Everbridge Communications API
  slug: ''
- description: 'The Everbridge iPaaS (Integration Platform as a Service) API enables IT organizations to build integrations with monitoring and service management tools such as APM, NPM, ITOM, SIEM, DevOps, and ITSM '
  name: Everbridge iPaaS API
  slug: ''
- description: The Everbridge Safety Devices API provides event management capabilities for safety devices integrated with the Everbridge platform. It uses OAuth 2.0 client credential grant type authentication and e
  name: Everbridge Safety Devices API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://manager.everbridge.net/
- title: ''
  type: Developer Portal
  url: https://developers.everbridge.net/home
- title: ''
  type: Login
  url: https://manager.everbridge.net/login
- title: ''
  type: Sign Up
  url: https://www.everbridge.com/free-trial/
- title: ''
  type: Blog
  url: https://www.everbridge.com/blog/
- title: ''
  type: Status
  url: https://status.everbridge.com/
- title: ''
  type: Contact
  url: https://www.everbridge.com/contact/
- title: ''
  type: Getting Started
  url: https://developers.everbridge.net/home/docs/ebs-gs-guide
- title: ''
  type: Authentication
  url: https://developers.everbridge.net/home/docs/ebs-gs-guide-authentication-types
- title: ''
  type: Rate Limits
  url: https://developers.everbridge.net/home/docs/ebs-gs-guide-throttling-limits
- title: ''
  type: Change Log
  url: https://developers.everbridge.net/home/changelog
- title: ''
  type: Support
  url: https://www.everbridge.com/support/
- title: ''
  type: Documentation
  url: https://supportcenter.everbridge.com/hc/en-us/categories/18141856301339-Documentation
- title: ''
  type: Terms of Service
  url: https://www.everbridge.com/company-policies/
- title: ''
  type: Privacy Policy
  url: https://www.everbridge.com/about/legal/everbridge-global-privacy-notice/
- title: ''
  type: Website
  url: https://www.everbridge.com
- title: ''
  type: GitHub Organization
  url: https://github.com/everbridge
- title: ''
  type: Community
  url: https://supportcenter.everbridge.com/hc/en-us
- title: ''
  type: OpenAPI
  url: https://api.everbridge.net/
created: 2024-01-09 00:00:00+00:00
description: Everbridge is a global software company that provides enterprise software applications that automate and accelerate organizations' operational response to critical events in order to keep people safe and businesses running.
features: []
image: https://www.everbridge.com/wp-content/uploads/2021/01/everbridge-logo.svg
integrations: []
layout: provider
modified: '2026-03-16'
name: Everbridge
skills: []
slug: everbridge
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Everbridge\ndescription: Everbridge is a global software company that provides enterprise software applications that automate and accelerate organizations' operational response to critical events in order to keep people safe and businesses running.\nimage: https://www.everbridge.com/wp-content/uploads/2021/01/everbridge-logo.svg\nurl: https://www.everbridge.com\ncreated: 2024-01-09 00:00:00+00:00\nmodified: '2026-03-16'\nspecificationVersion: '0.19'\ntags:\n  - Critical Event Management\n  - Emergency Management\n  - Incident Management\n  - IT Alerting\n  - Mass Notification\napis:\n  - name: Everbridge Suite API\n    description: >-\n      The Everbridge Suite REST API enables developers to integrate Everbridge's\n      critical event management platform into their applications. It provides\n      endpoints for managing contacts, groups, organizations, notifications,\n      incidents, calendars, conference bridges, locations, and more.\n    image: https://www.everbridge.com/wp-content/uploads/2021/01/everbridge-logo.svg\n\
  \    humanURL: https://developers.everbridge.net/home\n    baseURL: https://api.everbridge.net/rest\n    tags:\n      - Contacts\n      - Groups\n      - Incidents\n      - Mass Notification\n      - Notifications\n      - Organizations\n    properties:\n      - type: Documentation\n        url: https://developers.everbridge.net/home/docs/overview\n      - type: OpenAPI\n        url: https://api.everbridge.net/rest/swagger.json\n      - type: Reference\n        url: https://api.everbridge.net/\n      - type: Authentication\n        url: https://developers.everbridge.net/home/docs/ebs-gs-guide-authentication-types\n      - type: Getting Started\n        url: https://developers.everbridge.net/home/docs/ebs-gs-guide\n      - type: Rate Limits\n        url: https://developers.everbridge.net/home/docs/ebs-gs-guide-throttling-limits\n      - type: Change Log\n        url: https://developers.everbridge.net/home/changelog\n  - name: Everbridge Asset Management API\n    description: >-\n      The\
  \ Everbridge Asset Management API allows organizations to manage assets,\n      asset types, asset associations, and related templates. It supports batch\n      operations for bulk asset management and provides license limit statistics\n      for asset tracking within the Everbridge platform.\n    image: https://www.everbridge.com/wp-content/uploads/2021/01/everbridge-logo.svg\n    humanURL: https://developers.everbridge.net/home\n    baseURL: https://api.everbridge.net/rest\n    tags:\n      - Asset Management\n      - Assets\n      - Critical Events\n    properties:\n      - type: Documentation\n        url: https://developers.everbridge.net/home\n      - type: Reference\n        url: https://api.everbridge.net/\n  - name: Everbridge Asset Query API\n    description: >-\n      The Everbridge Asset Query API provides endpoints for streaming, listing,\n      searching, paginating, and aggregating asset data. It enables organizations\n      to query and retrieve asset information for reporting\
  \ and analysis purposes.\n    image: https://www.everbridge.com/wp-content/uploads/2021/01/everbridge-logo.svg\n    humanURL: https://developers.everbridge.net/home\n    baseURL: https://api.everbridge.net/rest\n    tags:\n      - Assets\n      - Queries\n      - Search\n    properties:\n      - type: Documentation\n        url: https://developers.everbridge.net/home\n      - type: Reference\n        url: https://api.everbridge.net/\n  - name: Everbridge CEM Alerts API\n    description: >-\n      The Everbridge CEM Alerts API provides GraphQL-based endpoints for querying\n      public alerts and streaming alert data from the Critical Event Management\n      platform. It enables organizations to programmatically access risk event\n      and alert information for situational awareness and response automation.\n    image: https://www.everbridge.com/wp-content/uploads/2021/01/everbridge-logo.svg\n    humanURL: https://developers.everbridge.net/home\n    baseURL: https://api.everbridge.net\n\
  \    tags:\n      - Alerts\n      - Critical Events\n      - GraphQL\n      - Risk Intelligence\n    properties:\n      - type: Documentation\n        url: https://developers.everbridge.net/home\n      - type: Reference\n        url: https://api.everbridge.net/\n  - name: Everbridge SnapComms API\n    description: >-\n      The Everbridge SnapComms API enables targeted internal communications\n      broadcasting through the Everbridge Engage platform. It supports\n      authentication, group and attribute targeting, content templates, user\n      management, and reporting for delivering desktop alerts, tickers, and\n      other employee communications.\n    image: https://www.everbridge.com/wp-content/uploads/2021/01/everbridge-logo.svg\n    humanURL: https://developers.everbridge.net/home\n    baseURL: https://api.snapcomms.com\n    tags:\n      - Desktop Alerts\n      - Employee Communications\n      - Internal Communications\n    properties:\n      - type: Documentation\n        url:\
  \ https://developers.everbridge.net/home\n      - type: Reference\n        url: https://api.everbridge.net/\n      - type: Getting Started\n        url: https://support.snapcomms.com/hc/en-us/articles/19361020051867-Integration-Through-API-Overview\n  - name: Everbridge Digital Apps API\n    description: >-\n      The Everbridge Digital Apps API provides integration capabilities for\n      mobile, desktop, and web applications from the perspective of an Everbridge\n      contact. It supports receiving and responding to notifications, device\n      registration for push notifications, contact management, incident access,\n      scheduling, and single sign-on for third-party applications.\n    image: https://www.everbridge.com/wp-content/uploads/2021/01/everbridge-logo.svg\n    humanURL: https://developers.everbridge.net/home/docs/overview\n    baseURL: https://api.everbridge.net\n    tags:\n      - Contacts\n      - Digital Apps\n      - Mobile\n      - Push Notifications\n    properties:\n\
  \      - type: Documentation\n        url: https://developers.everbridge.net/home/docs/overview\n      - type: Reference\n        url: https://api.everbridge.net/\n      - type: Getting Started\n        url: https://developers.everbridge.net/home/docs/notifications\n  - name: Everbridge Communications API\n    description: >-\n      The Everbridge Communications API provides endpoints for managing\n      communication templates, categories, reservations, contact builders,\n      message builders, plans, schedules, and variables. It enables\n      organizations to programmatically create and manage multi-channel\n      communications within the Everbridge platform.\n    image: https://www.everbridge.com/wp-content/uploads/2021/01/everbridge-logo.svg\n    humanURL: https://developers.everbridge.net/home\n    baseURL: https://api.everbridge.net\n    tags:\n      - Communications\n      - Messaging\n      - Templates\n    properties:\n      - type: Documentation\n        url: https://developers.everbridge.net/home\n\
  \      - type: Reference\n        url: https://api.everbridge.net/\n  - name: Everbridge iPaaS API\n    description: >-\n      The Everbridge iPaaS (Integration Platform as a Service) API enables\n      IT organizations to build integrations with monitoring and service\n      management tools such as APM, NPM, ITOM, SIEM, DevOps, and ITSM\n      systems. It provides a no-code to low-code approach for automatically\n      mapping technology integrations to existing workflows and triggering\n      Everbridge IT Alerting notifications.\n    image: https://www.everbridge.com/wp-content/uploads/2021/01/everbridge-logo.svg\n    humanURL: https://www.everbridge.com/products/it-alerting/integrations/ipaas-self-service-integration-guide/\n    baseURL: https://ipaas-ingestion.everbridge.net\n    tags:\n      - Integration\n      - iPaaS\n      - IT Alerting\n      - ITSM\n    properties:\n      - type: Documentation\n        url: https://www.everbridge.com/products/it-alerting/integrations/ipaas-self-service-integration-guide/\n\
  \      - type: Reference\n        url: https://developers.everbridge.net/home\n  - name: Everbridge Safety Devices API\n    description: >-\n      The Everbridge Safety Devices API provides event management capabilities\n      for safety devices integrated with the Everbridge platform. It uses\n      OAuth 2.0 client credential grant type authentication and enables\n      organizations to manage safety device events programmatically.\n    image: https://www.everbridge.com/wp-content/uploads/2021/01/everbridge-logo.svg\n    humanURL: https://developers.everbridge.net/home\n    baseURL: https://api.everbridge.net\n    tags:\n      - Devices\n      - IoT\n      - Safety\n    properties:\n      - type: Documentation\n        url: https://developers.everbridge.net/home\n      - type: Reference\n        url: https://api.everbridge.net/\ncommon:\n  - type: Portal\n    url: https://manager.everbridge.net/\n  - type: Developer Portal\n    url: https://developers.everbridge.net/home\n  - type: Login\n\
  \    url: https://manager.everbridge.net/login\n  - type: Sign Up\n    url: https://www.everbridge.com/free-trial/\n  - type: Blog\n    url: https://www.everbridge.com/blog/\n  - type: Status\n    url: https://status.everbridge.com/\n  - type: Contact\n    url: https://www.everbridge.com/contact/\n  - type: Getting Started\n    url: https://developers.everbridge.net/home/docs/ebs-gs-guide\n  - type: Authentication\n    url: https://developers.everbridge.net/home/docs/ebs-gs-guide-authentication-types\n  - type: Rate Limits\n    url: https://developers.everbridge.net/home/docs/ebs-gs-guide-throttling-limits\n  - type: Change Log\n    url: https://developers.everbridge.net/home/changelog\n  - type: Support\n    url: https://www.everbridge.com/support/\n  - type: Documentation\n    url: https://supportcenter.everbridge.com/hc/en-us/categories/18141856301339-Documentation\n  - type: Terms of Service\n    url: https://www.everbridge.com/company-policies/\n  - type: Privacy Policy\n    url:\
  \ https://www.everbridge.com/about/legal/everbridge-global-privacy-notice/\n  - type: Website\n    url: https://www.everbridge.com\n  - type: GitHub Organization\n    url: https://github.com/everbridge\n  - type: Community\n    url: https://supportcenter.everbridge.com/hc/en-us\n  - type: OpenAPI\n    url: https://api.everbridge.net/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/everbridge/refs/heads/main/apis.yml
tags:
- Critical Event Management
- Emergency Management
- Incident Management
- IT Alerting
- Mass Notification
url: https://www.everbridge.com
use_cases: []
---
