---
api_count: 6
api_specs:
- filename: microsoft-planner-openapi.yml
  format: yaml
  label: Microsoft Planner API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-planner/refs/heads/main/openapi/microsoft-planner-openapi.yml
- filename: microsoft-planner-openapi.yml
  format: yaml
  label: Microsoft Graph Plans API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-planner/refs/heads/main/openapi/microsoft-planner-openapi.yml
- filename: microsoft-planner-openapi.yml
  format: yaml
  label: Microsoft Graph Tasks API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-planner/refs/heads/main/openapi/microsoft-planner-openapi.yml
- filename: microsoft-planner-openapi.yml
  format: yaml
  label: Microsoft Graph Buckets API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-planner/refs/heads/main/openapi/microsoft-planner-openapi.yml
apis:
- description: RESTful API for accessing and managing tasks, plans, and buckets in Microsoft Planner through Microsoft Graph.
  name: Microsoft Planner API
  slug: ''
- description: API for creating, reading, updating, and deleting plans in Microsoft Planner through Microsoft Graph. Plans are the containers for tasks and are owned by groups or other containers.
  name: Microsoft Graph Plans API
  slug: ''
- description: API for creating, reading, updating, and deleting tasks in Microsoft Planner through Microsoft Graph. Tasks are contained in plans and can be assigned to buckets and users.
  name: Microsoft Graph Tasks API
  slug: ''
- description: API for creating, reading, updating, and deleting buckets in Microsoft Planner through Microsoft Graph. Buckets represent custom columns for organizing tasks within a plan.
  name: Microsoft Graph Buckets API
  slug: ''
- description: Beta version of the Planner API in Microsoft Graph providing access to preview features including plannerRoster resources, business scenarios integration, and expanded container type support.
  name: Microsoft Graph Planner API (Beta)
  slug: ''
- description: Beta API for integrating external business processes with Microsoft Planner through business scenarios, allowing creation of scenario-controlled Planner tasks and plans.
  name: Microsoft Graph Business Scenarios Planner API (Beta)
  slug: ''
capabilities:
- description: Manage plans, tasks, and buckets in Microsoft Planner for team collaboration and project management. Used by project managers and team leads.
  name: Microsoft Planner Task Management
  slug: task-management
common:
- title: ''
  type: Portal
  url: https://developer.microsoft.com/en-us/graph
- title: ''
  type: TermsOfService
  url: https://docs.microsoft.com/en-us/legal/microsoft-apis/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/graph/planner-concept-overview
- title: ''
  type: Blog
  url: https://developer.microsoft.com/en-us/graph/blogs/
- title: ''
  type: StatusPage
  url: https://developer.microsoft.com/en-us/graph/status
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/graph/api/resources/planner-overview
- title: ''
  type: Login
  url: https://planner.cloud.microsoft
- title: ''
  type: Support
  url: https://support.microsoft.com/en-us/planner
- title: ''
  type: FAQ
  url: https://support.microsoft.com/en-us/office/frequently-asked-questions-about-microsoft-planner-d1a2d4e6-a4d7-408c-a48a-31caaa267de5
- title: ''
  type: GitHubOrganization
  url: https://github.com/microsoftgraph
- title: ''
  type: ChangeLog
  url: https://developer.microsoft.com/en-us/graph/changelog
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/graph/auth/
- title: ''
  type: SDK
  url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview
- title: ''
  type: SignUp
  url: https://developer.microsoft.com/en-us/microsoft-365/dev-program
- title: ''
  type: Sandbox
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- title: ''
  type: RateLimits
  url: https://learn.microsoft.com/en-us/graph/throttling
- title: ''
  type: OpenAPI
  url: openapi/microsoft-planner-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/microsoft-planner-task-schema.json
- title: ''
  type: JSONLD
  url: json-ld/microsoft-planner-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/microsoft-planner-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/microsoft-planner-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/task-management.yaml
created: '2024-01-01'
description: Microsoft Planner is a task management tool that helps teams organize work, assign tasks, share files, and collaborate on projects within Microsoft 365.
features:
- Visual task boards with drag-and-drop organization
- Plan creation tied to Microsoft 365 Groups
- Task assignment with due dates and priorities
- Bucket-based task categorization and organization
- Checklist subtasks within individual tasks
- File attachment and external reference linking
- Progress tracking with charts and status views
- Microsoft Teams integration for collaborative planning
- Category labels for cross-cutting task classification
- Microsoft Graph API for programmatic access
image: https://docs.microsoft.com/en-us/media/logos/logo-ms-social.png
integrations:
- Microsoft Teams for in-chat task management
- Microsoft To Do for personal task sync
- Power Automate for workflow automation
- SharePoint for document-linked tasks
- Outlook for email-to-task conversion
- Excel for data export and reporting
- Power BI for advanced analytics dashboards
- Azure DevOps for development task bridging
jsonld:
- class_count: 0
  name: Microsoft Planner Context
  property_count: 0
  slug: microsoft-planner-context
layout: provider
modified: '2026-04-18'
name: Microsoft Planner
rules:
- name: Microsoft Planner API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: microsoft-planner-spectral-rules
skills: []
slug: microsoft-planner
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-planner\nname: Microsoft Planner\ndescription: >-\n  Microsoft Planner is a task management tool that helps teams organize work,\n  assign tasks, share files, and collaborate on projects within Microsoft 365.\nimage: https://docs.microsoft.com/en-us/media/logos/logo-ms-social.png\ntags:\n  - Collaboration\n  - Microsoft 365\n  - Productivity\n  - Project Management\n  - Task Management\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-planner/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - name: Microsoft Planner API\n    description: >-\n      RESTful API for accessing and managing tasks, plans, and buckets in Microsoft\n      Planner through Microsoft Graph.\n    image: https://docs.microsoft.com/en-us/media/logos/logo-ms-social.png\n    humanURL: https://developer.microsoft.com/en-us/graph/docs/api-reference/v1.0/resources/planner_overview\n    baseURL: https://graph.microsoft.com/v1.0/planner\n\
  \    tags:\n      - Assignments\n      - Buckets\n      - Microsoft Graph\n      - Plans\n      - Tasks\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/planner-overview\n      - type: OpenAPI\n        url: openapi/microsoft-planner-openapi.yml\n      - type: JSONSchema\n        url: json-schema/microsoft-planner-task-schema.json\n      - type: JSONLD\n        url: json-ld/microsoft-planner-context.jsonld\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: Pricing\n        url: https://www.microsoft.com/en-us/microsoft-365/enterprise/microsoft365-plans-and-pricing\n      - type: RateLimits\n        url: https://learn.microsoft.com/en-us/graph/throttling\n      - type: SDK\n        url: https://github.com/microsoftgraph/msgraph-sdk-dotnet\n        title: .NET SDK\n      - type: SDK\n        url: https://github.com/microsoftgraph/msgraph-sdk-javascript\n        title: JavaScript\
  \ SDK\n      - type: SDK\n        url: https://github.com/microsoftgraph/msgraph-sdk-python\n        title: Python SDK\n      - type: SDK\n        url: https://github.com/microsoftgraph/msgraph-sdk-java\n        title: Java SDK\n      - type: SDK\n        url: https://github.com/microsoftgraph/msgraph-sdk-go\n        title: Go SDK\n      - type: SDK\n        url: https://github.com/microsoftgraph/msgraph-sdk-php\n        title: PHP SDK\n      - type: Support\n        url: https://developer.microsoft.com/en-us/graph/support\n      - type: ChangeLog\n        url: https://developer.microsoft.com/en-us/graph/changelog\n      - type: Sandbox\n        url: https://developer.microsoft.com/en-us/graph/graph-explorer\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/planner-concept-overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/planner-overview?view=graph-rest-1.0\n      - type: Quickstart\n        url:\
  \ https://developer.microsoft.com/en-us/graph/quick-start\n    contact:\n      - FN: Microsoft Graph Support\n        url: https://developer.microsoft.com/en-us/graph/support\n        email: graphsdksupport@microsoft.com\n  - name: Microsoft Graph Plans API\n    description: >-\n      API for creating, reading, updating, and deleting plans in Microsoft Planner\n      through Microsoft Graph. Plans are the containers for tasks and are owned by\n      groups or other containers.\n    image: https://docs.microsoft.com/en-us/media/logos/logo-ms-social.png\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/plannerplan?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0/planner/plans\n    tags:\n      - Microsoft Graph\n      - Planner\n      - Plans\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/plannerplan?view=graph-rest-1.0\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/planner-post-plans?view=graph-rest-1.0\n\
  \      - type: OpenAPI\n        url: openapi/microsoft-planner-openapi.yml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/planner-concept-overview\n      - type: Sandbox\n        url: https://developer.microsoft.com/en-us/graph/graph-explorer\n    contact:\n      - FN: Microsoft Graph Support\n        url: https://developer.microsoft.com/en-us/graph/support\n        email: graphsdksupport@microsoft.com\n  - name: Microsoft Graph Tasks API\n    description: >-\n      API for creating, reading, updating, and deleting tasks in Microsoft Planner\n      through Microsoft Graph. Tasks are contained in plans and can be assigned to\n      buckets and users.\n    image: https://docs.microsoft.com/en-us/media/logos/logo-ms-social.png\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/plannertask?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0/planner/tasks\n\
  \    tags:\n      - Assignments\n      - Microsoft Graph\n      - Planner\n      - Tasks\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/plannertask?view=graph-rest-1.0\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/planner-post-tasks?view=graph-rest-1.0\n      - type: OpenAPI\n        url: openapi/microsoft-planner-openapi.yml\n      - type: JSONSchema\n        url: json-schema/microsoft-planner-task-schema.json\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/planner-concept-overview\n      - type: Sandbox\n        url: https://developer.microsoft.com/en-us/graph/graph-explorer\n    contact:\n      - FN: Microsoft Graph Support\n        url: https://developer.microsoft.com/en-us/graph/support\n        email: graphsdksupport@microsoft.com\n  - name: Microsoft\
  \ Graph Buckets API\n    description: >-\n      API for creating, reading, updating, and deleting buckets in Microsoft\n      Planner through Microsoft Graph. Buckets represent custom columns for\n      organizing tasks within a plan.\n    image: https://docs.microsoft.com/en-us/media/logos/logo-ms-social.png\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/plannerbucket?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0/planner/buckets\n    tags:\n      - Buckets\n      - Microsoft Graph\n      - Organization\n      - Planner\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/plannerbucket?view=graph-rest-1.0\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/planner-post-buckets?view=graph-rest-1.0\n      - type: OpenAPI\n        url: openapi/microsoft-planner-openapi.yml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n\
  \      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/planner-concept-overview\n      - type: Sandbox\n        url: https://developer.microsoft.com/en-us/graph/graph-explorer\n    contact:\n      - FN: Microsoft Graph Support\n        url: https://developer.microsoft.com/en-us/graph/support\n        email: graphsdksupport@microsoft.com\n  - name: Microsoft Graph Planner API (Beta)\n    description: >-\n      Beta version of the Planner API in Microsoft Graph providing access to\n      preview features including plannerRoster resources, business scenarios\n      integration, and expanded container type support.\n    image: https://docs.microsoft.com/en-us/media/logos/logo-ms-social.png\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/planner-overview?view=graph-rest-beta\n    baseURL: https://graph.microsoft.com/beta/planner\n    tags:\n      - Beta\n      - Microsoft Graph\n      - Planner\n      - Preview\n      - Rosters\n    properties:\n\
  \      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/planner-overview?view=graph-rest-beta\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/planner-overview?view=graph-rest-beta\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/planner-concept-overview\n      - type: Sandbox\n        url: https://developer.microsoft.com/en-us/graph/graph-explorer\n    contact:\n      - FN: Microsoft Graph Support\n        url: https://developer.microsoft.com/en-us/graph/support\n        email: graphsdksupport@microsoft.com\n  - name: Microsoft Graph Business Scenarios Planner API (Beta)\n    description: >-\n      Beta API for integrating external business processes with Microsoft Planner\n      through business scenarios, allowing creation of scenario-controlled Planner\n      tasks and plans.\n\
  \    image: https://docs.microsoft.com/en-us/media/logos/logo-ms-social.png\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/businessscenario-planner-overview?view=graph-rest-beta\n    baseURL: https://graph.microsoft.com/beta/solutions/businessScenarios\n    tags:\n      - Beta\n      - Business Scenarios\n      - Integration\n      - Microsoft Graph\n      - Planner\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/businessscenario-planner-overview?view=graph-rest-beta\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/businessscenario-overview?view=graph-rest-beta\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: Sandbox\n        url: https://developer.microsoft.com/en-us/graph/graph-explorer\n    contact:\n      - FN: Microsoft Graph Support\n        url: https://developer.microsoft.com/en-us/graph/support\n\
  \        email: graphsdksupport@microsoft.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ncommon:\n  - type: Portal\n    url: https://developer.microsoft.com/en-us/graph\n  - type: TermsOfService\n    url: https://docs.microsoft.com/en-us/legal/microsoft-apis/terms-of-use\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/graph/planner-concept-overview\n  - type: Blog\n    url: https://developer.microsoft.com/en-us/graph/blogs/\n  - type: StatusPage\n    url: https://developer.microsoft.com/en-us/graph/status\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/graph/api/resources/planner-overview\n  - type: Login\n    url: https://planner.cloud.microsoft\n  - type: Support\n    url: https://support.microsoft.com/en-us/planner\n  - type: FAQ\n    url: https://support.microsoft.com/en-us/office/frequently-asked-questions-about-microsoft-planner-d1a2d4e6-a4d7-408c-a48a-31caaa267de5\n\
  \  - type: GitHubOrganization\n    url: https://github.com/microsoftgraph\n  - type: ChangeLog\n    url: https://developer.microsoft.com/en-us/graph/changelog\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/graph/auth/\n  - type: SDK\n    url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n  - type: SignUp\n    url: https://developer.microsoft.com/en-us/microsoft-365/dev-program\n  - type: Sandbox\n    url: https://developer.microsoft.com/en-us/graph/graph-explorer\n  - type: RateLimits\n    url: https://learn.microsoft.com/en-us/graph/throttling\n  - type: OpenAPI\n    url: openapi/microsoft-planner-openapi.yml\n  - type: JSONSchema\n    url: json-schema/microsoft-planner-task-schema.json\n  - type: JSONLD\n    url: json-ld/microsoft-planner-context.jsonld\n  - type: SpectralRules\n    url: rules/microsoft-planner-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/microsoft-planner-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/task-management.yaml\n\
  \  - type: Features\n    data:\n      - Visual task boards with drag-and-drop organization\n      - Plan creation tied to Microsoft 365 Groups\n      - Task assignment with due dates and priorities\n      - Bucket-based task categorization and organization\n      - Checklist subtasks within individual tasks\n      - File attachment and external reference linking\n      - Progress tracking with charts and status views\n      - Microsoft Teams integration for collaborative planning\n      - Category labels for cross-cutting task classification\n      - Microsoft Graph API for programmatic access\n  - type: UseCases\n    data:\n      - Project management for team-based work coordination\n      - Sprint planning and agile task tracking\n      - Onboarding workflows for new employees\n      - Event planning with task delegation and deadlines\n      - Content publishing calendars and editorial workflows\n      - IT helpdesk ticket organization and tracking\n      - Marketing campaign task management\n\
  \      - Cross-functional team collaboration on initiatives\n  - type: Integrations\n    data:\n      - Microsoft Teams for in-chat task management\n      - Microsoft To Do for personal task sync\n      - Power Automate for workflow automation\n      - SharePoint for document-linked tasks\n      - Outlook for email-to-task conversion\n      - Excel for data export and reporting\n      - Power BI for advanced analytics dashboards\n      - Azure DevOps for development task bridging\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-planner/refs/heads/main/apis.yml
tags:
- Collaboration
- Microsoft 365
- Productivity
- Project Management
- Task Management
url: https://raw.githubusercontent.com/api-evangelist/microsoft-planner/refs/heads/main/apis.yml
use_cases:
- Project management for team-based work coordination
- Sprint planning and agile task tracking
- Onboarding workflows for new employees
- Event planning with task delegation and deadlines
- Content publishing calendars and editorial workflows
- IT helpdesk ticket organization and tracking
- Marketing campaign task management
- Cross-functional team collaboration on initiatives
---
