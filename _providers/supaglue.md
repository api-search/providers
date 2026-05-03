---
api_count: 4
api_specs:
- filename: supaglue-management-api-openapi.yml
  format: yaml
  label: Supaglue Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/openapi/supaglue-management-api-openapi.yml
- filename: supaglue-crm-api-openapi.yml
  format: yaml
  label: Supaglue Unified CRM API
  slug: crm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/openapi/supaglue-crm-api-openapi.yml
- filename: supaglue-engagement-api-openapi.yml
  format: yaml
  label: Supaglue Unified Engagement API
  slug: engagement-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/openapi/supaglue-engagement-api-openapi.yml
- filename: supaglue-ticketing-api-openapi.yml
  format: yaml
  label: Supaglue Unified Ticketing API
  slug: ticketing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/openapi/supaglue-ticketing-api-openapi.yml
apis:
- description: 'The Supaglue Management API configures all aspects of the integration platform. Manages customers (the end users of the integrations), their connections to third-party providers, sync configurations, '
  name: Supaglue Management API
  slug: management-api
- description: The Supaglue Unified CRM API provides a single interface for reading and writing CRM data across Salesforce, HubSpot, Pipedrive, and other providers. Supports accounts, contacts, leads, opportunities,
  name: Supaglue Unified CRM API
  slug: crm-api
- description: The Supaglue Unified Engagement API provides a single interface for reading and writing sales engagement data across Outreach, Salesloft, Apollo, and other sales engagement platforms. Supports account
  name: Supaglue Unified Engagement API
  slug: engagement-api
- description: The Supaglue Unified Ticketing API (Preview) provides a single interface for reading ticketing and support data across Zendesk, Linear, and other ticketing platforms. Supports accounts, collections, t
  name: Supaglue Unified Ticketing API
  slug: ticketing-api
capabilities:
- description: Unified workflow capability for building CRM product integrations using Supaglue. Combines the Management API for configuring customer connections and sync settings with the Unified CRM API for readin
  name: Supaglue CRM Integration
  slug: crm-integration
common:
- title: ''
  type: Website
  url: https://www.supaglue.com/
- title: ''
  type: Documentation
  url: https://docs.supaglue.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/supaglue-labs
- title: ''
  type: Getting Started
  url: https://docs.supaglue.com/getting-started
- title: ''
  type: API Introduction
  url: https://docs.supaglue.com/api/introduction
created: '2026-03-27'
description: Supaglue is an open-source unified API platform that enables B2B SaaS developers to build product integrations with CRM, HRIS, sales engagement, ticketing, and other business applications. It provides a unified API layer that abstracts away provider-specific differences, managed OAuth authentication, data syncing to data warehouses (BigQuery, Snowflake, Redshift, Postgres), and a management API for configuring customers, connections, and sync configurations. Supported providers include Salesforce, HubSpot, Pipedrive, Zendesk, Slack, and 15+ others. The platform is available as a managed cloud service (api.supaglue.io) and as a self-hosted open-source deployment. The GitHub organization is github.com/supaglue-labs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Supaglue Context
  property_count: 22
  slug: supaglue-context
layout: provider
modified: '2026-05-02'
name: Supaglue
rules:
- name: Supaglue API Rules
  rule_count: 10
  severity_counts:
    error: 0
    hint: 0
    info: 6
    warn: 4
  slug: supaglue-rules
skills: []
slug: supaglue
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: supaglue\nname: Supaglue\ndescription: >-\n  Supaglue is an open-source unified API platform that enables B2B SaaS\n  developers to build product integrations with CRM, HRIS, sales engagement,\n  ticketing, and other business applications. It provides a unified API layer\n  that abstracts away provider-specific differences, managed OAuth\n  authentication, data syncing to data warehouses (BigQuery, Snowflake,\n  Redshift, Postgres), and a management API for configuring customers,\n  connections, and sync configurations. Supported providers include Salesforce,\n  HubSpot, Pipedrive, Zendesk, Slack, and 15+ others. The platform is available\n  as a managed cloud service (api.supaglue.io) and as a self-hosted open-source\n  deployment. The GitHub organization is github.com/supaglue-labs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CRM\n  - HRIS\n  - Unified API\n  - Open Source\n  - Integrations\n  - Sales Engagement\n\
  url: >-\n  https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: supaglue:management-api\n    name: Supaglue Management API\n    description: >-\n      The Supaglue Management API configures all aspects of the integration\n      platform. Manages customers (the end users of the integrations), their\n      connections to third-party providers, sync configurations, data\n      destinations (BigQuery, Snowflake, Redshift, Postgres), schema and entity\n      mappings, field mappings, providers, sync operations (trigger/pause/resume),\n      sync run history, and magic link generation for OAuth flows. Authentication\n      uses an API key passed via the x-api-key header. Base URL:\n      https://api.supaglue.io/mgmt/v2.\n    humanURL: https://docs.supaglue.com/api/v2/mgmt/management-api\n    tags:\n      - Management\n      - Customers\n      - Connections\n      - Sync\n\
  \      - Destinations\n    properties:\n      - type: Documentation\n        url: https://docs.supaglue.com/api/v2/mgmt/management-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/openapi/supaglue-management-api-openapi.yml\n  - aid: supaglue:crm-api\n    name: Supaglue Unified CRM API\n    description: >-\n      The Supaglue Unified CRM API provides a single interface for reading and\n      writing CRM data across Salesforce, HubSpot, Pipedrive, and other\n      providers. Supports accounts, contacts, leads, opportunities, users,\n      custom objects, standard objects, associations, lists, and metadata\n      (custom object schemas, property definitions). All operations use the\n      x-api-key header plus a customer ID context. Base URL:\n      https://api.supaglue.io/crm/v2.\n    humanURL: https://docs.supaglue.com/api/v2/crm/unified-crm-api\n    tags:\n      - CRM\n      - Contacts\n      - Accounts\n\
  \      - Opportunities\n      - Leads\n      - Salesforce\n      - HubSpot\n    properties:\n      - type: Documentation\n        url: https://docs.supaglue.com/api/v2/crm/unified-crm-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/openapi/supaglue-crm-api-openapi.yml\n  - aid: supaglue:engagement-api\n    name: Supaglue Unified Engagement API\n    description: >-\n      The Supaglue Unified Engagement API provides a single interface for\n      reading and writing sales engagement data across Outreach, Salesloft,\n      Apollo, and other sales engagement platforms. Supports accounts,\n      contacts, sequences, sequence states, mailboxes, users, and metadata\n      for custom objects and standard objects. Base URL:\n      https://api.supaglue.io/engagement/v2.\n    humanURL: https://docs.supaglue.com/api/v2/engagement\n    tags:\n      - Sales Engagement\n      - Outreach\n      - Salesloft\n      - Sequences\n\
  \      - Contacts\n    properties:\n      - type: Documentation\n        url: https://docs.supaglue.com/api/v2/engagement\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/openapi/supaglue-engagement-api-openapi.yml\n  - aid: supaglue:ticketing-api\n    name: Supaglue Unified Ticketing API\n    description: >-\n      The Supaglue Unified Ticketing API (Preview) provides a single interface\n      for reading ticketing and support data across Zendesk, Linear, and other\n      ticketing platforms. Supports accounts, collections, tickets, tags,\n      contacts, users, and attachments. Base URL:\n      https://api.supaglue.io/ticketing/v2.\n    humanURL: https://docs.supaglue.com/api/v2/ticketing\n    tags:\n      - Ticketing\n      - Support\n      - Zendesk\n      - Help Desk\n    properties:\n      - type: Documentation\n        url: https://docs.supaglue.com/api/v2/ticketing\n      - type: OpenAPI\n        url: >-\n\
  \          https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/openapi/supaglue-ticketing-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.supaglue.com/\n  - type: Documentation\n    url: https://docs.supaglue.com/\n  - type: GitHub Organization\n    url: https://github.com/supaglue-labs\n  - type: Getting Started\n    url: https://docs.supaglue.com/getting-started\n  - type: API Introduction\n    url: https://docs.supaglue.com/api/introduction\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/apis.yml
tags:
- CRM
- HRIS
- Unified API
- Open Source
- Integrations
- Sales Engagement
url: https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/apis.yml
use_cases: []
---
