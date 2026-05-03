---
api_count: 11
api_specs:
- filename: scout-rfp-events-openapi.yml
  format: yaml
  label: Workday Strategic Sourcing API
  slug: workday-strategic-sourcing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/openapi/scout-rfp-events-openapi.yml
apis:
- description: 'The Workday Strategic Sourcing API (formerly Scout RFP API) provides programmatic access to sourcing and procurement workflows. API services cover events (RFPs, RFIs, auctions), suppliers, contracts, '
  name: Workday Strategic Sourcing API
  slug: workday-strategic-sourcing
- description: Manage sourcing events including RFPs, RFIs, and reverse auctions. Supports creating events from templates, updating event details, managing supplier invitations, worksheets, line items, and bid colle
  name: Events API
  slug: events-api
- description: Manage supplier companies and contacts in the Workday Strategic Sourcing platform. Supports creating, updating, and querying supplier records with version 1.1 of the API.
  name: Suppliers API
  slug: suppliers-api
- description: Manage contracts within the strategic sourcing platform, including creation, retrieval, and updates. Version 1.1 of the API.
  name: Contracts API
  slug: contracts-api
- description: Manage sourcing award decisions for completed events, tracking supplier selection outcomes and award values. Version 1.1.
  name: Awards API
  slug: awards-api
- description: Upload and manage file attachments associated with sourcing events, contracts, and other procurement objects. Version 1.0.
  name: Attachments API
  slug: attachments-api
- description: Manage payment records associated with procurement transactions and contract fulfillment. Version 1.0.
  name: Payments API
  slug: payments-api
- description: Manage procurement projects that organize and group related sourcing events and activities. Version 1.0.
  name: Projects API
  slug: projects-api
- description: Access procurement analytics and reporting data from the Workday Strategic Sourcing platform. Version 1.0.
  name: Reports API
  slug: reports-api
- description: Manage users in the Workday Strategic Sourcing platform using the SCIM 2.0 standard, enabling integration with identity providers for automated user provisioning and deprovisioning.
  name: SCIM Users API
  slug: scim-api
- description: Manage spend category taxonomies used to classify procurement spending within the Workday Strategic Sourcing platform. Version 1.0.
  name: Spend Categories API
  slug: spend-categories-api
capabilities:
- description: Unified capability for strategic sourcing and procurement workflows using the Workday Strategic Sourcing (Scout RFP) API. Enables procurement teams to manage the full sourcing lifecycle — from creatin
  name: Strategic Sourcing and Procurement
  slug: strategic-sourcing
common: []
created: '2026-05-02'
description: Scout RFP is a cloud-based strategic sourcing and procurement platform that streamlines the RFP (Request for Proposal) process for procurement teams. Founded in 2014 and acquired by Workday, Scout RFP is now known as Workday Strategic Sourcing. The platform provides REST APIs for managing sourcing events, suppliers, contracts, awards, attachments, and spend categories, enabling integrations with ERP, CRM, and procurement systems.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 2
  name: Scout Rfp Context
  property_count: 16
  slug: scout-rfp-context
layout: provider
modified: '2026-05-02'
name: Scout RFP
rules:
- name: Scout RFP API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 3
    warn: 5
  slug: scout-rfp-rules
skills: []
slug: scout-rfp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: scout-rfp\nname: Scout RFP\ndescription: >-\n  Scout RFP is a cloud-based strategic sourcing and procurement platform that\n  streamlines the RFP (Request for Proposal) process for procurement teams.\n  Founded in 2014 and acquired by Workday, Scout RFP is now known as Workday\n  Strategic Sourcing. The platform provides REST APIs for managing sourcing\n  events, suppliers, contracts, awards, attachments, and spend categories,\n  enabling integrations with ERP, CRM, and procurement systems.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Procurement\n  - Sourcing\n  - RFP\n  - Supply Chain\n  - Workday\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: scout-rfp:workday-strategic-sourcing\n    name: Workday Strategic Sourcing API\n    description:\
  \ >-\n      The Workday Strategic Sourcing API (formerly Scout RFP API) provides\n      programmatic access to sourcing and procurement workflows. API services\n      cover events (RFPs, RFIs, auctions), suppliers, contracts, awards,\n      attachments, payments, projects, reports, spend categories, and user\n      management via SCIM. Authentication uses API key and user token headers.\n    humanURL: https://apidocs.workdayspend.com/\n    tags:\n      - Procurement\n      - Sourcing\n      - RFP\n      - Workday\n      - Events\n    properties:\n      - type: Documentation\n        url: https://apidocs.workdayspend.com/\n      - type: GettingStarted\n        url: https://apidocs.workdayspend.com/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/openapi/scout-rfp-events-openapi.yml\n      - type: SpectralRules\n        url: https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/rules/scout-rfp-rules.yml\n\
  \      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/json-schema/scout-rfp-event-schema.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/json-ld/scout-rfp-context.jsonld\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/json-structure/scout-rfp-event-structure.json\n      - type: Example\n        url: https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/examples/scout-rfp-list-events-example.json\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/vocabulary/scout-rfp-vocabulary.yml\n      - type: NaftikoCapabilities\n        url: https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/capabilities/strategic-sourcing.yaml\n  - aid: scout-rfp:events-api\n    name: Events API\n    description:\
  \ >-\n      Manage sourcing events including RFPs, RFIs, and reverse auctions.\n      Supports creating events from templates, updating event details, managing\n      supplier invitations, worksheets, line items, and bid collection.\n      Version 1.3 is the latest stable release.\n    humanURL: https://apidocs.workdayspend.com/services/events/v1.html\n    tags:\n      - Events\n      - RFP\n      - Procurement\n      - Sourcing\n    properties:\n      - type: Documentation\n        url: https://apidocs.workdayspend.com/services/events/v1.html\n  - aid: scout-rfp:suppliers-api\n    name: Suppliers API\n    description: >-\n      Manage supplier companies and contacts in the Workday Strategic Sourcing\n      platform. Supports creating, updating, and querying supplier records with\n      version 1.1 of the API.\n    humanURL: https://apidocs.workdayspend.com/services/suppliers/v1.html\n    tags:\n      - Suppliers\n      - Procurement\n      - Vendor Management\n    properties:\n      -\
  \ type: Documentation\n        url: https://apidocs.workdayspend.com/services/suppliers/v1.html\n  - aid: scout-rfp:contracts-api\n    name: Contracts API\n    description: >-\n      Manage contracts within the strategic sourcing platform, including\n      creation, retrieval, and updates. Version 1.1 of the API.\n    humanURL: https://apidocs.workdayspend.com/services/contracts/v1.html\n    tags:\n      - Contracts\n      - Procurement\n      - Legal\n    properties:\n      - type: Documentation\n        url: https://apidocs.workdayspend.com/services/contracts/v1.html\n  - aid: scout-rfp:awards-api\n    name: Awards API\n    description: >-\n      Manage sourcing award decisions for completed events, tracking supplier\n      selection outcomes and award values. Version 1.1.\n    humanURL: https://apidocs.workdayspend.com/services/awards/v1.html\n    tags:\n      - Awards\n      - Procurement\n      - Sourcing\n    properties:\n      - type: Documentation\n        url: https://apidocs.workdayspend.com/services/awards/v1.html\n\
  \  - aid: scout-rfp:attachments-api\n    name: Attachments API\n    description: >-\n      Upload and manage file attachments associated with sourcing events,\n      contracts, and other procurement objects. Version 1.0.\n    humanURL: https://apidocs.workdayspend.com/services/attachments/v1.html\n    tags:\n      - Attachments\n      - Files\n      - Procurement\n    properties:\n      - type: Documentation\n        url: https://apidocs.workdayspend.com/services/attachments/v1.html\n  - aid: scout-rfp:payments-api\n    name: Payments API\n    description: >-\n      Manage payment records associated with procurement transactions and\n      contract fulfillment. Version 1.0.\n    humanURL: https://apidocs.workdayspend.com/services/payments/v1.html\n    tags:\n      - Payments\n      - Procurement\n      - Finance\n    properties:\n      - type: Documentation\n        url: https://apidocs.workdayspend.com/services/payments/v1.html\n  - aid: scout-rfp:projects-api\n    name: Projects API\n\
  \    description: >-\n      Manage procurement projects that organize and group related sourcing\n      events and activities. Version 1.0.\n    humanURL: https://apidocs.workdayspend.com/services/projects/v1.html\n    tags:\n      - Projects\n      - Procurement\n      - Organization\n    properties:\n      - type: Documentation\n        url: https://apidocs.workdayspend.com/services/projects/v1.html\n  - aid: scout-rfp:reports-api\n    name: Reports API\n    description: >-\n      Access procurement analytics and reporting data from the Workday\n      Strategic Sourcing platform. Version 1.0.\n    humanURL: https://apidocs.workdayspend.com/services/reports/v1.html\n    tags:\n      - Reports\n      - Analytics\n      - Procurement\n    properties:\n      - type: Documentation\n        url: https://apidocs.workdayspend.com/services/reports/v1.html\n  - aid: scout-rfp:scim-api\n    name: SCIM Users API\n    description: >-\n      Manage users in the Workday Strategic Sourcing platform\
  \ using the\n      SCIM 2.0 standard, enabling integration with identity providers for\n      automated user provisioning and deprovisioning.\n    humanURL: https://apidocs.workdayspend.com/services/scim/v2.html\n    tags:\n      - SCIM\n      - User Management\n      - Identity\n      - SSO\n    properties:\n      - type: Documentation\n        url: https://apidocs.workdayspend.com/services/scim/v2.html\n  - aid: scout-rfp:spend-categories-api\n    name: Spend Categories API\n    description: >-\n      Manage spend category taxonomies used to classify procurement spending\n      within the Workday Strategic Sourcing platform. Version 1.0.\n    humanURL: https://apidocs.workdayspend.com/services/spend_categories/v1.html\n    tags:\n      - Spend Categories\n      - Procurement\n      - Classification\n    properties:\n      - type: Documentation\n        url: https://apidocs.workdayspend.com/services/spend_categories/v1.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/apis.yml
tags:
- Procurement
- Sourcing
- RFP
- Supply Chain
- Workday
url: https://raw.githubusercontent.com/api-evangelist/scout-rfp/refs/heads/main/apis.yml
use_cases: []
---
