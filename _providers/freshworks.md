---
api_count: 8
api_specs:
- filename: freshworks-freshdesk-api-openapi.yml
  format: yaml
  label: Freshworks Freshdesk API
  slug: freshdesk-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/openapi/freshworks-freshdesk-api-openapi.yml
- filename: freshworks-freshservice-api-openapi.yml
  format: yaml
  label: Freshworks Freshservice API
  slug: freshservice-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/openapi/freshworks-freshservice-api-openapi.yml
- filename: freshworks-freshsales-api-openapi.yml
  format: yaml
  label: Freshworks Freshsales API
  slug: freshsales-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/openapi/freshworks-freshsales-api-openapi.yml
- filename: freshworks-freshchat-api-openapi.yml
  format: yaml
  label: Freshworks Freshchat API
  slug: freshchat-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/openapi/freshworks-freshchat-api-openapi.yml
- filename: freshworks-freshcaller-api-openapi.yml
  format: yaml
  label: Freshworks Freshcaller API
  slug: freshcaller-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/openapi/freshworks-freshcaller-api-openapi.yml
- filename: freshworks-freshteam-api-openapi.yml
  format: yaml
  label: Freshworks Freshteam API
  slug: freshteam-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/openapi/freshworks-freshteam-api-openapi.yml
apis:
- description: The Freshdesk API v2 is a RESTful API that provides programmatic access to Freshdesk helpdesk functionality. It allows developers to manage tickets, contacts, companies, agents, groups, and other help
  name: Freshworks Freshdesk API
  slug: freshdesk-api
- description: The Freshservice API v2 is a RESTful API for managing IT service desk operations programmatically. It provides endpoints for tickets, problems, changes, releases, assets, requesters, agents, and other
  name: Freshworks Freshservice API
  slug: freshservice-api
- description: The Freshsales API is a RESTful API that enables developers to access and manage CRM data within Freshsales. It supports operations for contacts, accounts, deals, leads, tasks, appointments, notes, an
  name: Freshworks Freshsales API
  slug: freshsales-api
- description: The Freshchat API provides programmatic access to the Freshchat messaging platform for managing customer conversations and engagement. It supports operations for conversations, messages, agents, chann
  name: Freshworks Freshchat API
  slug: freshchat-api
- description: The Freshcaller API provides access to cloud-based phone system functionality for contact center operations. It allows developers to export call data, call recordings, user information, and agent team
  name: Freshworks Freshcaller API
  slug: freshcaller-api
- description: The Freshteam API provides programmatic access to HR and recruiting functionality within the Freshteam platform. It supports operations for managing employees, job postings, candidates, branches, depa
  name: Freshworks Freshteam API
  slug: freshteam-api
- description: 'The Freshmarketer API provides developer access to marketing automation capabilities within the Freshmarketer platform. It enables programmatic management of marketing campaigns, contact lists, email '
  name: Freshworks Freshmarketer API
  slug: freshmarketer-api
- description: The Freshworks App SDK enables developers to build custom applications and extensions that run within the Freshworks product ecosystem. It provides tools for creating apps for Freshdesk, Freshservice,
  name: Freshworks App SDK
  slug: freshworks-app-sdk
asyncapis:
- description: Freshworks products support webhook callbacks that notify external applications when specific events occur within the helpdesk, service desk, CRM, and messaging platforms. Webhooks are configured thro
  name: Freshworks Webhook Events
  slug: freshworks-webhooks-asyncapi
common:
- title: ''
  type: AsyncAPI
  url: asyncapi/freshworks-webhooks-asyncapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/freshworks-ticket-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/freshworks-contact-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/freshworks-context.jsonld
created: ''
description: Freshworks is a software company that develops cloud-based business software including customer support, IT service management, sales force automation, marketing automation, and HR applications.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Freshworks Context
  property_count: 9
  slug: freshworks-context
layout: provider
modified: '2026-04-28'
name: freshworks
skills: []
slug: freshworks
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: freshworks\nurl: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/apis.yml\nmodified: '2026-04-28'\napis:\n  - aid: freshworks:freshdesk-api\n    name: Freshworks Freshdesk API\n    tags:\n      - Agents\n      - Contacts\n      - Customer Support\n      - Helpdesk\n      - Ticketing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://domain.freshdesk.com/api/v2\n    humanURL: https://developers.freshdesk.com/api/\n    properties:\n      - url: https://developers.freshdesk.com/api/\n        type: Documentation\n      - url: openapi/freshworks-freshdesk-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Freshdesk API v2 is a RESTful API that provides programmatic access to\n      Freshdesk helpdesk functionality. It allows developers to manage tickets,\n      contacts, companies, agents, groups, and other helpdesk resources through\n      standard CRUD operations. The\
  \ API uses JSON for data exchange, supports\n      API key authentication, and enables integration of Freshdesk customer\n      support workflows into third-party applications and automation pipelines.\n  - aid: freshworks:freshservice-api\n    name: Freshworks Freshservice API\n    tags:\n      - Asset Management\n      - IT Service Management\n      - ITSM\n      - Service Desk\n      - Ticketing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://domain.freshservice.com/api/v2\n    humanURL: https://api.freshservice.com/\n    properties:\n      - url: https://api.freshservice.com/\n        type: Documentation\n      - url: openapi/freshworks-freshservice-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Freshservice API v2 is a RESTful API for managing IT service desk\n      operations programmatically. It provides endpoints for tickets, problems,\n      changes, releases, assets, requesters, agents, and other\
  \ ITSM resources.\n      The API supports Cross-Origin Resource Sharing (CORS) for web-based\n      applications, uses API key authentication via Base64-encoded authorization\n      headers, and allows organizations to automate IT service management\n      workflows and integrate Freshservice with other enterprise tools.\n  - aid: freshworks:freshsales-api\n    name: Freshworks Freshsales API\n    tags:\n      - Contacts\n      - CRM\n      - Deals\n      - Leads\n      - Sales\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://domain.myfreshworks.com/crm/sales/api\n    humanURL: https://developers.freshworks.com/crm/api/\n    properties:\n      - url: https://developers.freshworks.com/crm/api/\n        type: Documentation\n      - url: openapi/freshworks-freshsales-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Freshsales API is a RESTful API that enables developers to access and\n      manage CRM data within\
  \ Freshsales. It supports operations for contacts,\n      accounts, deals, leads, tasks, appointments, notes, and sales activities.\n      The API uses token-based authentication and allows developers to read,\n      modify, add, or delete CRM data, making it possible to build custom\n      integrations, automate sales workflows, and synchronize Freshsales data\n      with other business applications.\n  - aid: freshworks:freshchat-api\n    name: Freshworks Freshchat API\n    tags:\n      - Chat\n      - Conversations\n      - Customer Engagement\n      - Live Chat\n      - Messaging\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.freshchat.com/v2\n    humanURL: https://developers.freshchat.com/api/\n    properties:\n      - url: https://developers.freshchat.com/api/\n        type: Documentation\n      - url: openapi/freshworks-freshchat-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Freshchat API\
  \ provides programmatic access to the Freshchat messaging\n      platform for managing customer conversations and engagement. It supports\n      operations for conversations, messages, agents, channels, and users. The\n      API enables developers to automate customer communication workflows,\n      integrate Freshchat with external systems, and build custom messaging\n      solutions on top of the Freshchat platform. Authentication is handled via\n      API tokens obtained from the Freshchat admin panel.\n  - aid: freshworks:freshcaller-api\n    name: Freshworks Freshcaller API\n    tags:\n      - Call Center\n      - Contact Center\n      - Phone\n      - Telephony\n      - Voice\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://domain.freshcaller.com/api/v1\n    humanURL: https://developers.freshcaller.com/api/\n    properties:\n      - url: https://developers.freshcaller.com/api/\n        type: Documentation\n      - url: openapi/freshworks-freshcaller-api-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The Freshcaller API provides access to cloud-based phone system\n      functionality for contact center operations. It allows developers to\n      export call data, call recordings, user information, and agent team\n      details stored in the Freshcaller system. The API supports integration\n      of voice and telephony workflows into broader business applications,\n      enabling organizations to automate call center reporting, synchronize\n      agent data, and build custom dashboards around their phone operations.\n  - aid: freshworks:freshteam-api\n    name: Freshworks Freshteam API\n    tags:\n      - Applicant Tracking\n      - Employees\n      - HR\n      - Human Resources\n      - Recruiting\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://domain.freshteam.com/api\n    humanURL: https://developers.freshworks.com/api-sdk/freshteam/\n    properties:\n      - url: https://developers.freshworks.com/api-sdk/freshteam/\n\
  \        type: Documentation\n      - url: openapi/freshworks-freshteam-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Freshteam API provides programmatic access to HR and recruiting functionality\n      within the Freshteam platform. It supports operations for managing employees,\n      job postings, candidates, branches, departments, and other HR resources.\n  - aid: freshworks:freshmarketer-api\n    name: Freshworks Freshmarketer API\n    tags:\n      - Analytics\n      - Campaigns\n      - Email Marketing\n      - Marketing\n      - Marketing Automation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.freshmarketer.com/\n    properties:\n      - url: https://developer.freshmarketer.com/\n        type: Documentation\n    description: >-\n      The Freshmarketer API provides developer access to marketing automation\n      capabilities within the Freshmarketer\
  \ platform. It enables programmatic\n      management of marketing campaigns, contact lists, email sequences, and\n      conversion optimization workflows. Developers can use the API to\n      integrate Freshmarketer with other marketing tools, automate campaign\n      management, and synchronize marketing data across their technology stack\n      for unified customer engagement analytics.\n  - aid: freshworks:freshworks-app-sdk\n    name: Freshworks App SDK\n    tags:\n      - App Development\n      - Extensions\n      - Integrations\n      - Platform\n      - SDK\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developers.freshworks.com/docs/\n    properties:\n      - url: https://developers.freshworks.com/docs/\n        type: Documentation\n    description: >-\n      The Freshworks App SDK enables developers to build custom applications and extensions\n      that run within the Freshworks\
  \ product ecosystem. It provides tools for creating\n      apps for Freshdesk, Freshservice, Freshsales, and other Freshworks products\n      using a unified development framework.\ncommon:\n  - type: AsyncAPI\n    url: asyncapi/freshworks-webhooks-asyncapi.yml\n  - type: JSONSchema\n    url: json-schema/freshworks-ticket-schema.json\n  - type: JSONSchema\n    url: json-schema/freshworks-contact-schema.json\n  - type: JSON-LD\n    url: json-ld/freshworks-context.jsonld\ndescription: >-\n  Freshworks is a software company that develops cloud-based business software including\n  customer support, IT service management, sales force automation, marketing automation,\n  and HR applications.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/apis.yml
use_cases: []
---
