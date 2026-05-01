---
api_count: 15
api_specs:
- filename: gainsight-rest-api-openapi.yml
  format: yaml
  label: Gainsight REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-rest-api-openapi.yml
- filename: gainsight-px-api-openapi.yml
  format: yaml
  label: Gainsight PX API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-px-api-openapi.yml
- filename: gainsight-cs-company-api-openapi.yml
  format: yaml
  label: Gainsight CS Company API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-company-api-openapi.yml
- filename: gainsight-cs-person-api-openapi.yml
  format: yaml
  label: Gainsight CS Person API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-person-api-openapi.yml
- filename: gainsight-cs-custom-object-api-openapi.yml
  format: yaml
  label: Gainsight CS Custom Object API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-custom-object-api-openapi.yml
- filename: gainsight-cs-cta-api-openapi.yml
  format: yaml
  label: Gainsight CS CTA API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-cta-api-openapi.yml
- filename: gainsight-cs-timeline-api-openapi.yml
  format: yaml
  label: Gainsight CS Timeline API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-timeline-api-openapi.yml
- filename: gainsight-cs-success-plan-api-openapi.yml
  format: yaml
  label: Gainsight CS Success Plan API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-success-plan-api-openapi.yml
- filename: gainsight-cs-data-management-api-openapi.yml
  format: yaml
  label: Gainsight CS Data Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-data-management-api-openapi.yml
- filename: gainsight-cs-bulk-api-openapi.yml
  format: yaml
  label: Gainsight CS Bulk API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-bulk-api-openapi.yml
- filename: gainsight-cs-events-api-openapi.yml
  format: yaml
  label: Gainsight CS Events API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-events-api-openapi.yml
- filename: gainsight-cs-user-management-api-openapi.yml
  format: yaml
  label: Gainsight CS User Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-user-management-api-openapi.yml
- filename: gainsight-cs-customer-goals-api-openapi.yml
  format: yaml
  label: Gainsight CS Customer Goals API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-customer-goals-api-openapi.yml
- filename: gainsight-cs-renewal-center-api-openapi.yml
  format: yaml
  label: Gainsight CS Renewal Center API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-renewal-center-api-openapi.yml
- filename: gainsight-cs-task-and-playbook-api-openapi.yml
  format: yaml
  label: Gainsight CS Task and Playbook API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/openapi/gainsight-cs-task-and-playbook-api-openapi.yml
apis:
- description: The Gainsight REST API allows developers to integrate customer success data, automate workflows, and build custom applications on top of the Gainsight platform.
  name: Gainsight REST API
  slug: ''
- description: Product Experience (PX) API for tracking product usage, user behavior, and in-app engagement analytics.
  name: Gainsight PX API
  slug: ''
- description: The Company API enables inserting, updating, reading, and deleting records in the Gainsight Company object, supporting up to 50 records per call for write operations and 5000 records per read call.
  name: Gainsight CS Company API
  slug: ''
- description: The Person API facilitates upserting person records into the Gainsight Person object model, enabling management of customer contacts and stakeholders.
  name: Gainsight CS Person API
  slug: ''
- description: The Custom Object API allows inserting, updating, reading, and deleting records in Gainsight transactional custom objects, supporting flexible data models for customer success workflows.
  name: Gainsight CS Custom Object API
  slug: ''
- description: The Call To Action (CTA) API enables creating and updating CTAs, fetching CTA details, and retrieving CTA configurations through Cockpit REST APIs for managing customer success actions.
  name: Gainsight CS CTA API
  slug: ''
- description: The Timeline API enables creating, updating, reading, and deleting Timeline activities, supporting both single and bulk operations with up to 80MB payloads for bulk requests.
  name: Gainsight CS Timeline API
  slug: ''
- description: The Success Plan API enables creating, updating, and fetching Success Plans and their configurations, supporting structured goal tracking for customer engagements.
  name: Gainsight CS Success Plan API
  slug: ''
- description: The Data Management API provides access to Gainsight object and field metadata, enabling retrieval of schema information for integration and data mapping purposes.
  name: Gainsight CS Data Management API
  slug: ''
- description: The Gainsight Bulk API is an asynchronous connector that automates insert or update of large data volumes from CSV files into Gainsight standard and custom objects, with rate limits of 10 calls per ho
  name: Gainsight CS Bulk API
  slug: ''
- description: The Events API enables external systems to publish events into Gainsight, supporting system asset events for cross-system communication with operations including insert, update, upsert, and delete.
  name: Gainsight CS Events API
  slug: ''
- description: The User Management API provides endpoints for managing Gainsight users, company team records, and includes SCIM support for automated user provisioning and de-provisioning through identity providers.
  name: Gainsight CS User Management API
  slug: ''
- description: The Customer Goals API enables external systems to create, update, and fetch customer goals programmatically, including template and metrics management for structured goal tracking.
  name: Gainsight CS Customer Goals API
  slug: ''
- description: The Renewal Center API enables creating and updating opportunity records in the Gainsight Opportunity object, supporting renewal, upsell, and downsell booking types within the Matrix Data Architecture
  name: Gainsight CS Renewal Center API
  slug: ''
- description: The Task and Playbook API manages task creation and updates, and retrieves task and playbook details for orchestrating customer success workflows within the Cockpit.
  name: Gainsight CS Task and Playbook API
  slug: ''
common:
- title: ''
  type: portal
  url: https://support.gainsight.com
- title: ''
  type: login
  url: https://app.gainsight.com
- title: ''
  type: terms-of-service
  url: https://www.gainsight.com/terms-of-service/
- title: ''
  type: privacy-policy
  url: https://www.gainsight.com/privacy-policy/
- title: ''
  type: status
  url: https://trust.gainsight.com/
- title: ''
  type: developer-docs
  url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs
- title: ''
  type: authentication
  url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key
- title: ''
  type: oauth
  url: https://support.gainsight.com/gainsight_nxt/01Onboarding_and_Implementation/Onboarding_for_Gainsight_NXT/Login_and_Permissions/OAuth_for_Gainsight_APIs
- title: ''
  type: release-notes
  url: https://support.gainsight.com/gainsight_nxt/Release_Notes
- title: ''
  type: community
  url: https://communities.gainsight.com
- title: ''
  type: blog
  url: https://www.gainsight.com/blog/
- title: ''
  type: education
  url: https://education.gainsight.com
- title: ''
  type: JSON-LD
  url: json-ld/gainsight-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/gainsight-company-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/gainsight-person-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/gainsight-cta-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/gainsight-opportunity-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/gainsight-timeline-activity-schema.json
created: '2024'
description: Gainsight is a customer success platform that helps companies retain and grow their customer base through data-driven insights, automation, and engagement tools.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Gainsight Context
  property_count: 11
  slug: gainsight-context
layout: provider
modified: '2026-04-28'
name: Gainsight
skills: []
slug: gainsight
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Gainsight\ndescription: Gainsight is a customer success platform that helps companies retain and grow their customer base through data-driven insights, automation, and engagement tools.\nurl: https://www.gainsight.com\ncreated: '2024'\nmodified: '2026-04-28'\napis:\n  - name: Gainsight REST API\n    description: The Gainsight REST API allows developers to integrate customer success data, automate workflows, and build custom applications on top of the Gainsight platform.\n    humanURL: https://support.gainsight.com/PX/API_for_Developers/02About/Work_with_the_Gainsight_API\n    baseURL: https://api.gainsight.com\n    tags:\n      - Analytics\n      - CRM\n      - Customer Success\n      - SaaS\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/PX/API_for_Developers\n      - type: authentication\n        url: https://support.gainsight.com/PX/API_for_Developers/02About/Authentication\n      - type: swagger\n        url: https://api.gainsight.com/swagger\n\
  \      - type: OpenAPI\n        url: openapi/gainsight-rest-api-openapi.yml\n    contact:\n      - name: Gainsight Support\n        url: https://support.gainsight.com\n        email: support@gainsight.com\n  - name: Gainsight PX API\n    description: Product Experience (PX) API for tracking product usage, user behavior, and in-app engagement analytics.\n    humanURL: https://support.gainsight.com/PX/API_for_Developers\n    baseURL: https://api.aptrinsic.com/v1\n    tags:\n      - Product Analytics\n      - Product Experience\n      - User Engagement\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/PX/API_for_Developers/APIs_for_Developers/PX_API\n      - type: api-key\n        url: https://support.gainsight.com/PX/API_for_Developers/02About/API_Keys\n      - type: documentation\n        url: https://gainsightpx.docs.apiary.io/\n      - type: OpenAPI\n        url: openapi/gainsight-px-api-openapi.yml\n  - name: Gainsight CS Company API\n    description:\
  \ The Company API enables inserting, updating, reading, and deleting records in the Gainsight Company object, supporting up to 50 records per call for write operations and 5000 records per read call.\n    humanURL: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Company_and_Relationship_API/Company_API_Documentation\n    baseURL: https://companyapi.gainsightcloud.com\n    tags:\n      - Accounts\n      - Companies\n      - Customer Success\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Company_and_Relationship_API/Company_API_Documentation\n      - type: authentication\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key\n      - type: OpenAPI\n        url: openapi/gainsight-cs-company-api-openapi.yml\n  - name: Gainsight CS Person API\n    description: The Person API facilitates upserting person records into the Gainsight\
  \ Person object model, enabling management of customer contacts and stakeholders.\n    humanURL: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Person_API/People_API_Documentation\n    baseURL: https://personapi.gainsightcloud.com\n    tags:\n      - Contacts\n      - Customer Success\n      - People\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Person_API/People_API_Documentation\n      - type: authentication\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key\n      - type: OpenAPI\n        url: openapi/gainsight-cs-person-api-openapi.yml\n  - name: Gainsight CS Custom Object API\n    description: The Custom Object API allows inserting, updating, reading, and deleting records in Gainsight transactional custom objects, supporting flexible data models for customer success workflows.\n    humanURL: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Custom_Object_API/Gainsight_Custom_Object_API_Documentation\n\
  \    baseURL: https://customobjectapi.gainsightcloud.com\n    tags:\n      - Custom Objects\n      - Customer Success\n      - Data Management\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Custom_Object_API/Gainsight_Custom_Object_API_Documentation\n      - type: authentication\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key\n      - type: OpenAPI\n        url: openapi/gainsight-cs-custom-object-api-openapi.yml\n  - name: Gainsight CS CTA API\n    description: The Call To Action (CTA) API enables creating and updating CTAs, fetching CTA details, and retrieving CTA configurations through Cockpit REST APIs for managing customer success actions.\n    humanURL: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Cockpit_API/Call_To_Action_(CTA)_API_Documentation\n    baseURL: https://cta.gainsightcloud.com\n    tags:\n    \
  \  - Calls to Action\n      - Cockpit\n      - Customer Success\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Cockpit_API/Call_To_Action_(CTA)_API_Documentation\n      - type: authentication\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key\n      - type: OpenAPI\n        url: openapi/gainsight-cs-cta-api-openapi.yml\n  - name: Gainsight CS Timeline API\n    description: The Timeline API enables creating, updating, reading, and deleting Timeline activities, supporting both single and bulk operations with up to 80MB payloads for bulk requests.\n    humanURL: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Timeline_API/Timeline_APIs\n    baseURL: https://timeline.gainsightcloud.com\n    tags:\n      - Activities\n      - Customer Success\n      - Timeline\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Timeline_API/Timeline_APIs\n\
  \      - type: authentication\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key\n      - type: OpenAPI\n        url: openapi/gainsight-cs-timeline-api-openapi.yml\n  - name: Gainsight CS Success Plan API\n    description: The Success Plan API enables creating, updating, and fetching Success Plans and their configurations, supporting structured goal tracking for customer engagements.\n    humanURL: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Success_Plan_APIs/Success_Plan_APIs\n    baseURL: https://successplan.gainsightcloud.com\n    tags:\n      - Customer Success\n      - Goal Tracking\n      - Success Plans\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Success_Plan_APIs/Success_Plan_APIs\n      - type: authentication\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key\n\
  \      - type: OpenAPI\n        url: openapi/gainsight-cs-success-plan-api-openapi.yml\n  - name: Gainsight CS Data Management API\n    description: The Data Management API provides access to Gainsight object and field metadata, enabling retrieval of schema information for integration and data mapping purposes.\n    humanURL: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Data_Management_APIs/Data_Management_APIs\n    baseURL: https://data.gainsightcloud.com\n    tags:\n      - Customer Success\n      - Data Management\n      - Metadata\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Data_Management_APIs/Data_Management_APIs\n      - type: authentication\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key\n      - type: OpenAPI\n        url: openapi/gainsight-cs-data-management-api-openapi.yml\n  - name: Gainsight CS Bulk\
  \ API\n    description: The Gainsight Bulk API is an asynchronous connector that automates insert or update of large data volumes from CSV files into Gainsight standard and custom objects, with rate limits of 10 calls per hour and 100 per day.\n    humanURL: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Bulk_API/Gainsight_Bulk_REST_APIs\n    baseURL: https://bulk.gainsightcloud.com\n    tags:\n      - Bulk Data\n      - Customer Success\n      - Data Import\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Bulk_API/Gainsight_Bulk_REST_APIs\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Bulk_API/Gainsight_Bulk_API\n      - type: authentication\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key\n      - type: OpenAPI\n        url: openapi/gainsight-cs-bulk-api-openapi.yml\n\
  \  - name: Gainsight CS Events API\n    description: The Events API enables external systems to publish events into Gainsight, supporting system asset events for cross-system communication with operations including insert, update, upsert, and delete.\n    humanURL: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Events_API/Events_API\n    baseURL: https://events.gainsightcloud.com\n    tags:\n      - Customer Success\n      - Events\n      - Webhooks\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Events_API/Events_API\n      - type: authentication\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key\n      - type: OpenAPI\n        url: openapi/gainsight-cs-events-api-openapi.yml\n  - name: Gainsight CS User Management API\n    description: The User Management API provides endpoints for managing Gainsight users, company team\
  \ records, and includes SCIM support for automated user provisioning and de-provisioning through identity providers.\n    humanURL: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/User_Management_APIs/User_Management_APIs\n    baseURL: https://usermanagement.gainsightcloud.com\n    tags:\n      - Customer Success\n      - Provisioning\n      - SCIM\n      - User Management\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/User_Management_APIs/User_Management_APIs\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/User_Management_APIs/SCIM_API\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/User_Management_APIs/API_for_Company_Team_Record\n      - type: authentication\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key\n\
  \      - type: OpenAPI\n        url: openapi/gainsight-cs-user-management-api-openapi.yml\n  - name: Gainsight CS Customer Goals API\n    description: The Customer Goals API enables external systems to create, update, and fetch customer goals programmatically, including template and metrics management for structured goal tracking.\n    humanURL: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Customer_Goals_API/Customer_Goals_APIs\n    baseURL: https://goals.gainsightcloud.com\n    tags:\n      - Customer Success\n      - Goals\n      - Outcomes\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Customer_Goals_API/Customer_Goals_APIs\n      - type: authentication\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key\n      - type: OpenAPI\n        url: openapi/gainsight-cs-customer-goals-api-openapi.yml\n  - name: Gainsight CS\
  \ Renewal Center API\n    description: The Renewal Center API enables creating and updating opportunity records in the Gainsight Opportunity object, supporting renewal, upsell, and downsell booking types within the Matrix Data Architecture.\n    humanURL: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Renewal_Center_API/Renewal_Center_API\n    baseURL: https://renewals.gainsightcloud.com\n    tags:\n      - Customer Success\n      - Opportunities\n      - Renewals\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Renewal_Center_API/Renewal_Center_API\n      - type: authentication\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key\n      - type: OpenAPI\n        url: openapi/gainsight-cs-renewal-center-api-openapi.yml\n  - name: Gainsight CS Task and Playbook API\n    description: The Task and Playbook API manages task creation\
  \ and updates, and retrieves task and playbook details for orchestrating customer success workflows within the Cockpit.\n    humanURL: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Cockpit_API/Task_APIs\n    baseURL: https://task.gainsightcloud.com\n    tags:\n      - Cockpit\n      - Customer Success\n      - Playbooks\n      - Tasks\n    properties:\n      - type: documentation\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Cockpit_API/Task_APIs\n      - type: authentication\n        url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key\n      - type: OpenAPI\n        url: openapi/gainsight-cs-task-and-playbook-api-openapi.yml\ncommon:\n  - type: portal\n    url: https://support.gainsight.com\n  - type: login\n    url: https://app.gainsight.com\n  - type: terms-of-service\n    url: https://www.gainsight.com/terms-of-service/\n  - type: privacy-policy\n    url: https://www.gainsight.com/privacy-policy/\n\
  \  - type: status\n    url: https://trust.gainsight.com/\n  - type: developer-docs\n    url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs\n  - type: authentication\n    url: https://support.gainsight.com/gainsight_nxt/API_and_Developer_Docs/Generate_REST_API/Generate_REST_API_Key\n  - type: oauth\n    url: https://support.gainsight.com/gainsight_nxt/01Onboarding_and_Implementation/Onboarding_for_Gainsight_NXT/Login_and_Permissions/OAuth_for_Gainsight_APIs\n  - type: release-notes\n    url: https://support.gainsight.com/gainsight_nxt/Release_Notes\n  - type: community\n    url: https://communities.gainsight.com\n  - type: blog\n    url: https://www.gainsight.com/blog/\n  - type: education\n    url: https://education.gainsight.com\n  - type: JSON-LD\n    url: json-ld/gainsight-context.jsonld\n  - type: JSONSchema\n    url: json-schema/gainsight-company-schema.json\n  - type: JSONSchema\n    url: json-schema/gainsight-person-schema.json\n  - type: JSONSchema\n    url:\
  \ json-schema/gainsight-cta-schema.json\n  - type: JSONSchema\n    url: json-schema/gainsight-opportunity-schema.json\n  - type: JSONSchema\n    url: json-schema/gainsight-timeline-activity-schema.json\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://www.gainsight.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/gainsight/refs/heads/main/apis.yml
tags: []
url: https://www.gainsight.com
use_cases: []
---
