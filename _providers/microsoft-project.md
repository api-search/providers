---
api_count: 4
api_specs:
- filename: microsoft-project-rest-api.yaml
  format: yaml
  label: Microsoft Project Online REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-project/refs/heads/main/openapi/microsoft-project-rest-api.yaml
apis:
- description: REST API for accessing and managing Microsoft Project Online and Project Server data including projects, tasks, resources, assignments, calendars, custom fields, timesheets, lookup tables, and workflo
  name: Microsoft Project Online REST API
  slug: rest-api
- description: 'Client-Side Object Model API for programmatic access to Project Online and Project Server. Provides .NET, Silverlight, Windows Phone, and JavaScript interfaces for CRUD operations on projects, tasks, '
  name: Microsoft Project Online CSOM API
  slug: csom-api
- description: OData-based reporting feed for read-only access to Project Server and Project Online reporting data. Provides access to project, task, resource, assignment, and timesheet reporting tables and views vi
  name: Microsoft Project OData Reporting API
  slug: odata-reporting-api
- description: JavaScript API for building Office Add-ins that extend Microsoft Project desktop client. Enables reading task, resource, and view data from the active project within a task pane add-in.
  name: Microsoft Project JavaScript API
  slug: javascript-api
capabilities:
- description: 'Unified project management workflow combining the Microsoft Project Online REST API for managing projects, tasks, resources, assignments, timesheets, and workflows. Used by project managers, resource '
  name: Microsoft Project Management
  slug: project-management
common:
- title: ''
  type: Portal
  url: https://developer.microsoft.com/en-us/microsoft-365
- title: ''
  type: DeveloperPortal
  url: https://learn.microsoft.com/en-us/office/client-developer/project/project-programming-tasks
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/project-blog/bg-p/ProjectBlog
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/microsoft-365/project/compare-microsoft-project-management-software
- title: ''
  type: Support
  url: https://support.microsoft.com/
- title: ''
  type: GitHubRepository
  url: https://github.com/OfficeDev/Project-Samples
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/ms-project
- title: ''
  type: Training
  url: https://support.microsoft.com/en-us/project
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/office/client-developer/project/getting-started-developing-project-server-workflows
- title: ''
  type: GitHubOrganization
  url: https://github.com/OfficeDev
- title: Project Accelerator
  type: CodeExamples
  url: https://github.com/OfficeDev/Project-Accelerator
- title: Dataverse Plugin Sample
  type: CodeExamples
  url: https://github.com/OfficeDev/Project-Dataverse-Plugin-Sample
- title: ''
  type: SpectralRules
  url: rules/microsoft-project-spectral-rules.yml
- title: Project Management Workflow
  type: NaftikoCapability
  url: capabilities/project-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/microsoft-project-vocabulary.yaml
created: '2024-01-15'
description: Microsoft Project is a project management software product developed by Microsoft. It provides tools for developing plans, assigning resources to tasks, tracking progress, managing budgets, and analyzing workloads. Microsoft Project offers REST APIs via SharePoint/Project Online, a Client-Side Object Model (CSOM), OData reporting feeds, and JavaScript APIs for building add-ins and integrations.
features:
- description: Visual timeline charts for project scheduling with task dependencies, critical path analysis, and milestone tracking.
  name: Gantt Charts
- description: Create, assign, and track tasks with predecessors, successors, constraints, and deadlines.
  name: Task Management
- description: Assign resources to tasks, view workloads, and manage resource availability and capacity.
  name: Resource Management
- description: Manage multiple projects as a portfolio with prioritization, budgeting, and resource allocation across projects.
  name: Portfolio Management
- description: Track project costs, budgets, and earned value metrics for financial project management.
  name: Budgeting and Cost Tracking
- description: Automatic scheduling with task dependencies, resource leveling, and critical path calculation.
  name: Scheduling Engine
- description: Time tracking and approval workflows for resource hours and project progress reporting.
  name: Timesheets
- description: Define enterprise custom fields, lookup tables, and formulas for extended project metadata.
  name: Custom Fields
- description: Pre-built and custom reports with Power BI integration for project, resource, and portfolio analytics.
  name: Reporting and Dashboards
- description: Demand management workflows for project proposals, approvals, and stage-gate governance.
  name: Workflow Automation
- description: SharePoint-based project sites with document libraries, issue tracking, and team communication.
  name: Collaboration
- description: Integration with Power BI, Power Automate, and Power Apps for extended project management scenarios.
  name: Power Platform Integration
image: /assets/icons/microsoft-project.png
integrations:
- description: View and manage project tasks directly within Microsoft Teams channels and tabs.
  name: Microsoft Teams
- description: Connect to Project Online data for interactive dashboards and portfolio analytics.
  name: Power BI
- description: SharePoint-based project sites for document management, collaboration, and task synchronization.
  name: SharePoint
- description: Deep integration with Outlook, Excel, Word, and other Microsoft 365 applications.
  name: Microsoft 365
- description: Automate project workflows, notifications, and approvals using Power Automate flows.
  name: Power Automate
- description: Build custom project management applications using Power Apps with Project data.
  name: Power Apps
- description: Connect project schedules with Azure DevOps work items for software development projects.
  name: Azure DevOps
- description: Integrate lightweight task planning in Planner with enterprise project management in Project.
  name: Microsoft Planner
- description: Project for the web stores data in Microsoft Dataverse, enabling custom integrations and extensions.
  name: Dataverse
- description: Export and import project data to Excel for custom analysis, reporting, and data manipulation.
  name: Excel
jsonld:
- class_count: 11
  name: Microsoft Project Rest Api Context
  property_count: 47
  slug: microsoft-project-rest-api-context
layout: provider
modified: '2026-04-18'
name: Microsoft Project
rules:
- name: Microsoft Project API Rules
  rule_count: 39
  severity_counts:
    error: 23
    hint: 0
    info: 7
    warn: 9
  slug: microsoft-project-spectral-rules
skills: []
slug: microsoft-project
solutions: []
source_filename: apis.yml
source_yaml: "aid: microsoft-project\nname: Microsoft Project\ndescription: >-\n  Microsoft Project is a project management software product developed by\n  Microsoft. It provides tools for developing plans, assigning resources to\n  tasks, tracking progress, managing budgets, and analyzing workloads. Microsoft\n  Project offers REST APIs via SharePoint/Project Online, a Client-Side Object\n  Model (CSOM), OData reporting feeds, and JavaScript APIs for building add-ins\n  and integrations.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Budgeting\n  - Gantt Charts\n  - Microsoft\n  - Portfolio Management\n  - Project Management\n  - Resource Management\n  - Scheduling\n  - Task Management\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-project/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - aid: microsoft-project:rest-api\n    name: Microsoft Project\
  \ Online REST API\n    description: >-\n      REST API for accessing and managing Microsoft Project Online and Project\n      Server data including projects, tasks, resources, assignments, calendars,\n      custom fields, timesheets, lookup tables, and workflow activities. Uses\n      SharePoint-based REST endpoints via the ProjectServer service.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/office/client-developer/project/client-side-object-model-csom-for-project-2013\n    baseURL: https://{tenant}.sharepoint.com/sites/pwa/_api/ProjectServer\n    tags:\n      - Assignments\n      - Calendars\n      - Custom Fields\n      - Projects\n      - Resources\n      - REST\n      - Tasks\n      - Timesheets\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/client-developer/project/client-side-object-model-csom-for-project-2013\n      - type: APIReference\n\
  \        url: https://learn.microsoft.com/en-us/office/client-developer/project/javascript-library-and-rest-reference-for-project-server-2013\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/authorization-and-authentication-of-sharepoint-add-ins\n      - type: CodeExamples\n        url: https://github.com/OfficeDev/Project-Samples/tree/main/O365-Project-Online-REST-Samples\n      - type: CodeExamples\n        url: https://github.com/OfficeDev/Project-Add-in-REST-BasicDataOperations\n        title: REST CRUD Operations Sample\n      - type: OpenAPI\n        url: openapi/microsoft-project-rest-api.yaml\n      - type: JSONSchema\n        url: json-schema/rest-api-project-schema.json\n        title: Project Schema\n      - type: JSONSchema\n        url: json-schema/rest-api-task-schema.json\n        title: Task Schema\n      - type: JSONSchema\n        url: json-schema/rest-api-enterprise-resource-schema.json\n        title: Enterprise\
  \ Resource Schema\n      - type: JSONSchema\n        url: json-schema/rest-api-assignment-schema.json\n        title: Assignment Schema\n      - type: JSONSchema\n        url: json-schema/rest-api-calendar-schema.json\n        title: Calendar Schema\n      - type: JSONSchema\n        url: json-schema/rest-api-custom-field-schema.json\n        title: Custom Field Schema\n      - type: JSONSchema\n        url: json-schema/rest-api-time-sheet-schema.json\n        title: TimeSheet Schema\n      - type: JSONStructure\n        url: json-structure/rest-api-project-structure.json\n        title: Project Structure\n      - type: JSONStructure\n        url: json-structure/rest-api-task-structure.json\n        title: Task Structure\n      - type: JSONStructure\n        url: json-structure/rest-api-enterprise-resource-structure.json\n        title: Enterprise Resource Structure\n      - type: JSONStructure\n        url: json-structure/rest-api-assignment-structure.json\n        title: Assignment Structure\n\
  \      - type: JSONStructure\n        url: json-structure/rest-api-calendar-structure.json\n        title: Calendar Structure\n      - type: JSONStructure\n        url: json-structure/rest-api-custom-field-structure.json\n        title: Custom Field Structure\n      - type: JSONStructure\n        url: json-structure/rest-api-time-sheet-structure.json\n        title: TimeSheet Structure\n      - type: JSONLD\n        url: json-ld/microsoft-project-rest-api-context.jsonld\n      - type: Example\n        url: examples/rest-api-project-example.json\n        title: Project Example\n      - type: Example\n        url: examples/rest-api-task-example.json\n        title: Task Example\n      - type: Example\n        url: examples/rest-api-enterprise-resource-example.json\n        title: Enterprise Resource Example\n      - type: Example\n        url: examples/rest-api-assignment-example.json\n        title: Assignment Example\n      - type: Example\n        url: examples/rest-api-calendar-example.json\n\
  \        title: Calendar Example\n      - type: Example\n        url: examples/rest-api-custom-field-example.json\n        title: Custom Field Example\n      - type: Example\n        url: examples/rest-api-time-sheet-example.json\n        title: TimeSheet Example\n  - aid: microsoft-project:csom-api\n    name: Microsoft Project Online CSOM API\n    description: >-\n      Client-Side Object Model API for programmatic access to Project Online and\n      Project Server. Provides .NET, Silverlight, Windows Phone, and JavaScript\n      interfaces for CRUD operations on projects, tasks, resources, assignments,\n      custom fields, lookup tables, and enterprise project types.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/office/client-developer/project/client-side-object-model-csom-for-project-2013\n    baseURL: https://{tenant}.sharepoint.com/sites/pwa/_api/ProjectServer\n    tags:\n      - .NET\n     \
  \ - Client Library\n      - CSOM\n      - JavaScript\n      - Projects\n      - Resources\n      - Tasks\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/client-developer/project/client-side-object-model-csom-for-project-2013\n      - type: SDK\n        url: https://www.nuget.org/packages/Microsoft.SharePointOnline.CSOM/\n        title: .NET SDK\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/office/client-developer/project/getting-started-with-the-project-server-csom-and-.net\n  - aid: microsoft-project:odata-reporting-api\n    name: Microsoft Project OData Reporting API\n    description: >-\n      OData-based reporting feed for read-only access to Project Server and\n      Project Online reporting data. Provides access to project, task, resource,\n      assignment, and timesheet reporting tables and views via the ProjectData\n      service endpoint.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://learn.microsoft.com/en-us/office/client-developer/project/project-server-2013-architecture\n    baseURL: https://{tenant}.sharepoint.com/sites/pwa/_api/ProjectData\n    tags:\n      - OData\n      - Projects\n      - Reporting\n      - Resources\n      - Tasks\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/client-developer/project/project-server-2013-architecture\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/authorization-and-authentication-of-sharepoint-add-ins\n  - aid: microsoft-project:javascript-api\n    name: Microsoft Project JavaScript API\n    description: >-\n      JavaScript API for building Office Add-ins that extend Microsoft Project\n      desktop client. Enables reading task, resource, and view data from the\n      active project within a task pane add-in.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://learn.microsoft.com/en-us/office/dev/add-ins/project/project-add-ins\n    baseURL: https://appsforoffice.microsoft.com/lib/1/hosted/office.js\n    tags:\n      - Add-Ins\n      - JavaScript\n      - Office\n      - Task Pane\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/project/project-add-ins\n      - type: Quickstart\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/project-quickstart\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/javascript/api/office/office.context\n      - type: CodeExamples\n        url: https://developer.microsoft.com/en-us/microsoft-365/gallery/?filterBy=Project,Samples\ncommon:\n  - type: Portal\n    url: https://developer.microsoft.com/en-us/microsoft-365\n  - type: DeveloperPortal\n    url: https://learn.microsoft.com/en-us/office/client-developer/project/project-programming-tasks\n  - type: Blog\n    url: https://techcommunity.microsoft.com/t5/project-blog/bg-p/ProjectBlog\n\
  \  - type: TermsOfService\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Pricing\n    url: https://www.microsoft.com/en-us/microsoft-365/project/compare-microsoft-project-management-software\n  - type: Support\n    url: https://support.microsoft.com/\n  - type: GitHubRepository\n    url: https://github.com/OfficeDev/Project-Samples\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/ms-project\n  - type: Training\n    url: https://support.microsoft.com/en-us/project\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/office/client-developer/project/getting-started-developing-project-server-workflows\n  - type: GitHubOrganization\n    url: https://github.com/OfficeDev\n  - type: CodeExamples\n    url: https://github.com/OfficeDev/Project-Accelerator\n    title: Project Accelerator\n  - type: CodeExamples\n    url: https://github.com/OfficeDev/Project-Dataverse-Plugin-Sample\n\
  \    title: Dataverse Plugin Sample\n  - type: SpectralRules\n    url: rules/microsoft-project-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/project-management.yaml\n    title: Project Management Workflow\n  - type: Vocabulary\n    url: vocabulary/microsoft-project-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Gantt Charts\n        description: Visual timeline charts for project scheduling with task dependencies, critical path analysis, and milestone tracking.\n      - name: Task Management\n        description: Create, assign, and track tasks with predecessors, successors, constraints, and deadlines.\n      - name: Resource Management\n        description: Assign resources to tasks, view workloads, and manage resource availability and capacity.\n      - name: Portfolio Management\n        description: Manage multiple projects as a portfolio with prioritization, budgeting, and resource allocation across projects.\n      - name: Budgeting and Cost\
  \ Tracking\n        description: Track project costs, budgets, and earned value metrics for financial project management.\n      - name: Scheduling Engine\n        description: Automatic scheduling with task dependencies, resource leveling, and critical path calculation.\n      - name: Timesheets\n        description: Time tracking and approval workflows for resource hours and project progress reporting.\n      - name: Custom Fields\n        description: Define enterprise custom fields, lookup tables, and formulas for extended project metadata.\n      - name: Reporting and Dashboards\n        description: Pre-built and custom reports with Power BI integration for project, resource, and portfolio analytics.\n      - name: Workflow Automation\n        description: Demand management workflows for project proposals, approvals, and stage-gate governance.\n      - name: Collaboration\n        description: SharePoint-based project sites with document libraries, issue tracking, and team communication.\n\
  \      - name: Power Platform Integration\n        description: Integration with Power BI, Power Automate, and Power Apps for extended project management scenarios.\n  - type: UseCases\n    data:\n      - name: IT Project Management\n        description: Plan and track IT infrastructure, software development, and digital transformation projects.\n      - name: Construction Project Planning\n        description: Schedule construction phases, manage subcontractors, and track material costs.\n      - name: Product Development\n        description: Coordinate product development timelines, milestones, and cross-functional team resources.\n      - name: Portfolio Optimization\n        description: Evaluate and prioritize project portfolios based on strategic alignment, ROI, and resource constraints.\n      - name: Resource Capacity Planning\n        description: Forecast resource demand, identify bottlenecks, and optimize resource allocation across projects.\n      - name: Program Management\n\
  \        description: Manage interdependent projects as programs with shared resources and coordinated timelines.\n      - name: Agile Project Tracking\n        description: Track agile sprints, backlogs, and team velocity alongside traditional waterfall schedules.\n      - name: Compliance Reporting\n        description: Generate audit trails and compliance reports for project governance and regulatory requirements.\n  - type: Integrations\n    data:\n      - name: Microsoft Teams\n        description: View and manage project tasks directly within Microsoft Teams channels and tabs.\n      - name: Power BI\n        description: Connect to Project Online data for interactive dashboards and portfolio analytics.\n      - name: SharePoint\n        description: SharePoint-based project sites for document management, collaboration, and task synchronization.\n      - name: Microsoft 365\n        description: Deep integration with Outlook, Excel, Word, and other Microsoft 365 applications.\n \
  \     - name: Power Automate\n        description: Automate project workflows, notifications, and approvals using Power Automate flows.\n      - name: Power Apps\n        description: Build custom project management applications using Power Apps with Project data.\n      - name: Azure DevOps\n        description: Connect project schedules with Azure DevOps work items for software development projects.\n      - name: Microsoft Planner\n        description: Integrate lightweight task planning in Planner with enterprise project management in Project.\n      - name: Dataverse\n        description: Project for the web stores data in Microsoft Dataverse, enabling custom integrations and extensions.\n      - name: Excel\n        description: Export and import project data to Excel for custom analysis, reporting, and data manipulation.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-project/refs/heads/main/apis.yml
tags:
- Budgeting
- Gantt Charts
- Microsoft
- Portfolio Management
- Project Management
- Resource Management
- Scheduling
- Task Management
url: https://raw.githubusercontent.com/api-evangelist/microsoft-project/refs/heads/main/apis.yml
use_cases:
- description: Plan and track IT infrastructure, software development, and digital transformation projects.
  name: IT Project Management
- description: Schedule construction phases, manage subcontractors, and track material costs.
  name: Construction Project Planning
- description: Coordinate product development timelines, milestones, and cross-functional team resources.
  name: Product Development
- description: Evaluate and prioritize project portfolios based on strategic alignment, ROI, and resource constraints.
  name: Portfolio Optimization
- description: Forecast resource demand, identify bottlenecks, and optimize resource allocation across projects.
  name: Resource Capacity Planning
- description: Manage interdependent projects as programs with shared resources and coordinated timelines.
  name: Program Management
- description: Track agile sprints, backlogs, and team velocity alongside traditional waterfall schedules.
  name: Agile Project Tracking
- description: Generate audit trails and compliance reports for project governance and regulatory requirements.
  name: Compliance Reporting
---
