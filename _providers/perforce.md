---
api_count: 10
api_specs:
- filename: perforce-helix-swarm-openapi.yml
  format: yaml
  label: Perforce Helix Swarm API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/perforce/refs/heads/main/openapi/perforce-helix-swarm-openapi.yml
apis:
- description: REST API for Helix Core version control system, providing programmatic access to repository operations, file management, and versioning capabilities.
  name: Perforce Helix Core API
  slug: ''
- description: Technology Preview REST API introduced with P4 Server 2025.2, providing a new way to automate workflows and integrate P4 with other tools via standard HTTP endpoints for server info, depots, files, an
  name: Perforce P4 REST API
  slug: ''
- description: REST API for Helix Swarm code review and collaboration platform, enabling automated code review workflows and team collaboration.
  name: Perforce Helix Swarm API
  slug: ''
- description: API for Hansoft agile project management, providing access to project planning, tracking, and reporting capabilities.
  name: Perforce Hansoft API
  slug: ''
- description: GraphQL and REST API for P4 Plan (formerly Hansoft) agile project management, supporting queries, mutations, and real-time subscriptions for planning views, sprints, tasks, and user management.
  name: Perforce P4 Plan API
  slug: ''
- description: REST API for Helix ALM application lifecycle management platform, enabling automation of tasks and development of integrations for requirements management, issue tracking, and test case management.
  name: Perforce Helix ALM REST API
  slug: ''
- description: 'REST API for Helix TeamHub source code repository management platform, providing access to repositories, projects, users, and company resources across Git, Mercurial, Subversion, and other repository '
  name: Perforce Helix TeamHub API
  slug: ''
- description: REST API for P4 DAM (Digital Asset Management), enabling integration with digital asset workflows for finding, reviewing, sharing, and managing versioned assets stored in Helix Core.
  name: Perforce P4 DAM REST API
  slug: ''
- description: REST API for P4 Search, providing indexing and search capabilities across Helix Core servers to support code review, file content search, and changelist description search.
  name: Perforce P4 Search API
  slug: ''
- description: REST API for the Helix Authentication Service, a Node.js based authentication protocol integration service supporting OpenID Connect and SAML 2.0 for authenticating users across Perforce products.
  name: Perforce Helix Authentication Service API
  slug: ''
capabilities:
- description: Unified workflow for code review, commenting, and project management using Helix Swarm. Designed for development teams managing code review workflows integrated with Helix Core version control.
  name: Perforce Code Review and Collaboration
  slug: code-review-collaboration
common:
- title: ''
  type: Portal
  url: https://www.perforce.com/support/developers
- title: ''
  type: GettingStarted
  url: https://www.perforce.com/support/self-service-resources
- title: ''
  type: Documentation
  url: https://www.perforce.com/support/self-service-resources/documentation
- title: ''
  type: Blog
  url: https://www.perforce.com/blog
- title: ''
  type: Support
  url: https://www.perforce.com/support
- title: ''
  type: StatusPage
  url: https://status.perforce.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/perforce
- title: ''
  type: TermsOfService
  url: https://www.perforce.com/terms-use
- title: ''
  type: PrivacyPolicy
  url: https://www.perforce.com/privacy-policy
- title: ''
  type: Contact
  url: https://www.perforce.com/contact-us
created: '2024-01-01'
description: Perforce Software provides enterprise-scale development tools, including version control, application lifecycle management, agile planning, and static analysis solutions for development teams.
features:
- description: Collaborative code review workflows with Helix Swarm supporting inline comments, voting, tasks, and approval gates.
  name: Code Review
- description: Enterprise-scale version control with Helix Core supporting large binary files, distributed development, and atomic changelists.
  name: Version Control
- description: Versioned digital asset workflows with P4 DAM for reviewing, sharing, and managing creative assets stored in Helix Core.
  name: Digital Asset Management
- description: End-to-end ALM with Helix ALM for requirements traceability, issue tracking, and test case management.
  name: Application Lifecycle Management
- description: Agile project management with P4 Plan supporting sprints, backlogs, Gantt charts, and resource planning.
  name: Agile Planning
- description: Single sign-on across Perforce products with Helix Authentication Service supporting OpenID Connect and SAML 2.0.
  name: Authentication Services
image: https://www.perforce.com/sites/default/files/perforce-logo.png
integrations:
- description: Trigger builds and report results through Helix Core and Swarm integration plugins for Jenkins CI/CD.
  name: Jenkins
- description: Native Visual Studio integration with P4VS plugin for source control operations from within the IDE.
  name: Visual Studio
- description: Helix Core plugin for Unity game engine enabling version control of game projects directly within the editor.
  name: Unity
- description: Native Helix Core integration with Unreal Engine for versioning game assets and source code.
  name: Unreal Engine
jsonld:
- class_count: 0
  name: Perforce Context
  property_count: 9
  slug: perforce-context
- class_count: 0
  name: Perforce Helix Swarm Context
  property_count: 0
  slug: perforce-helix-swarm-context
layout: provider
modified: '2026-04-18'
name: Perforce
rules:
- name: Perforce API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: perforce-spectral-rules
skills: []
slug: perforce
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: perforce\nname: Perforce\ndescription: Perforce Software provides enterprise-scale development tools, including version control, application lifecycle management, agile planning, and static analysis solutions for development teams.\nimage: https://www.perforce.com/sites/default/files/perforce-logo.png\nurl: https://www.perforce.com\ntype: Index\nposition: Consumer\naccess: 3rd-Party\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - name: Perforce Helix Core API\n    description: REST API for Helix Core version control system, providing programmatic access to repository operations, file management, and versioning capabilities.\n    image: https://www.perforce.com/sites/default/files/helix-core-icon.png\n    humanURL: https://www.perforce.com/products/helix-core\n    baseURL: https://api.perforce.com/helix-core/v1\n    tags:\n      - DevOps\n      - SCM\n      - Source Control\n      - Version Control\n    properties:\n      - type:\
  \ Documentation\n        url: https://www.perforce.com/manuals/p4api/\n      - type: OpenAPI\n        url: https://api.perforce.com/helix-core/openapi.json\n      - type: Authentication\n        url: https://www.perforce.com/manuals/p4api/Content/P4API/authentication.html\n      - type: GettingStarted\n        url: https://www.perforce.com/products/helix-core/learning-resources\n  - name: Perforce P4 REST API\n    description: Technology Preview REST API introduced with P4 Server 2025.2, providing a new way to automate workflows and integrate P4 with other tools via standard HTTP endpoints for server info, depots, files, and changelists.\n    image: https://www.perforce.com/sites/default/files/helix-core-icon.png\n    humanURL: https://help.perforce.com/helix-core/server-apps/p4sag/current/Content/P4SAG/p4-rest-api.html\n    baseURL: https://p4server.example.com/api/v0\n    tags:\n      - Automation\n      - DevOps\n      - REST API\n      - Version Control\n    properties:\n      - type:\
  \ Documentation\n        url: https://help.perforce.com/helix-core/server-apps/p4sag/current/Content/P4SAG/p4-rest-api.html\n      - type: ChangeLog\n        url: https://help.perforce.com/helix-core/server-apps/cmdref/2025.2/Content/CmdRef/whats-new-2025-2.html\n  - name: Perforce Helix Swarm API\n    description: REST API for Helix Swarm code review and collaboration platform, enabling automated code review workflows and team collaboration.\n    image: https://www.perforce.com/sites/default/files/helix-swarm-icon.png\n    humanURL: https://www.perforce.com/products/helix-swarm\n    baseURL: https://swarm.example.com/api/v10\n    tags:\n      - Code Review\n      - Collaboration\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://www.perforce.com/manuals/swarm/Content/Swarm/swarm-apidoc.html\n      - type: APIReference\n        url: https://www.perforce.com/manuals/swarm/api/index.html\n      - type: Authentication\n        url: https://www.perforce.com/manuals/swarm/Content/Swarm/swarm-apidoc_endpoints.html\n\
  \      - type: OpenAPI\n        url: openapi/perforce-helix-swarm-openapi.yml\n      - type: JSONSchema\n        url: json-schema/perforce-review-schema.json\n      - type: JSONLD\n        url: json-ld/perforce-context.jsonld\n  - name: Perforce Hansoft API\n    description: API for Hansoft agile project management, providing access to project planning, tracking, and reporting capabilities.\n    image: https://www.perforce.com/sites/default/files/hansoft-icon.png\n    humanURL: https://www.perforce.com/products/hansoft\n    baseURL: https://hansoft.example.com/api\n    tags:\n      - Agile\n      - Planning\n      - Project Management\n    properties:\n      - type: Documentation\n        url: https://www.perforce.com/manuals/hansoft-sdk/\n      - type: SDK\n        url: https://www.perforce.com/downloads/hansoft-sdk\n  - name: Perforce P4 Plan API\n    description: GraphQL and REST API for P4 Plan (formerly Hansoft) agile project management, supporting queries, mutations, and real-time\
  \ subscriptions for planning views, sprints, tasks, and user management.\n    image: https://www.perforce.com/sites/default/files/hansoft-icon.png\n    humanURL: https://www.perforce.com/products/hansoft\n    baseURL: https://p4plan.example.com/api\n    tags:\n      - Agile\n      - GraphQL\n      - Planning\n      - Project Management\n    properties:\n      - type: Documentation\n        url: https://help.perforce.com/hansoft/current/Content/hansoftapi/index.html\n      - type: SDK\n        url: https://www.perforce.com/downloads/helix-plan-sdk\n      - type: ReleaseNotes\n        url: https://cache.hansoft.com/releasenotes/helix-plan-api.html\n  - name: Perforce Helix ALM REST API\n    description: REST API for Helix ALM application lifecycle management platform, enabling automation of tasks and development of integrations for requirements management, issue tracking, and test case management.\n    image: https://www.perforce.com/sites/default/files/helix-alm-icon.png\n    humanURL:\
  \ https://www.perforce.com/products/helix-alm\n    baseURL: https://helixalm.example.com/helix-alm/api/v0\n    tags:\n      - Application Lifecycle Management\n      - Issue Tracking\n      - Requirements Management\n      - Test Management\n    properties:\n      - type: Documentation\n        url: https://help.perforce.com/helix-alm/helixalm/current/restapi/Default.htm\n      - type: APIReference\n        url: https://help.perforce.com/helix-alm/helixalm/current/rest-api/index.html\n      - type: GettingStarted\n        url: https://help.perforce.com/helix-alm/helixalm/2019.3.0/restapi/Content/RESTAPI/GettingStarted.htm\n  - name: Perforce Helix TeamHub API\n    description: REST API for Helix TeamHub source code repository management platform, providing access to repositories, projects, users, and company resources across Git, Mercurial, Subversion, and other repository types.\n    image: https://www.perforce.com/sites/default/files/helix-teamhub-icon.png\n    humanURL: https://www.perforce.com/products/helix-teamhub\n\
  \    baseURL: https://teamhub.example.com/api/v1\n    tags:\n      - Collaboration\n      - Git\n      - Repositories\n      - Source Code Management\n    properties:\n      - type: Documentation\n        url: https://help.perforce.com/helix-core/helix-teamhub/current/Content/HTH-API/api-v1.html\n      - type: GettingStarted\n        url: https://help.perforce.com/helix-core/helix-teamhub/2025.5.0/Content/HTH-API/getting-started.html\n  - name: Perforce P4 DAM REST API\n    description: REST API for P4 DAM (Digital Asset Management), enabling integration with digital asset workflows for finding, reviewing, sharing, and managing versioned assets stored in Helix Core.\n    image: https://www.perforce.com/sites/default/files/helix-dam-icon.png\n    humanURL: https://www.perforce.com/products/helix-dam\n    baseURL: https://dam.example.com/api\n    tags:\n      - Asset Management\n      - Digital Asset Management\n      - Media\n      - Version Control\n    properties:\n      - type: Documentation\n\
  \        url: https://help.perforce.com/helix-core/helix-dam/current/api/\n  - name: Perforce P4 Search API\n    description: REST API for P4 Search, providing indexing and search capabilities across Helix Core servers to support code review, file content search, and changelist description search.\n    image: https://www.perforce.com/sites/default/files/helix-core-icon.png\n    humanURL: https://help.perforce.com/helix-core/integrations-plugins/p4search/current/Content/P4Search/overview.html\n    baseURL: https://p4search.example.com/api\n    tags:\n      - Code Search\n      - Indexing\n      - Search\n    properties:\n      - type: Documentation\n        url: https://help.perforce.com/helix-core/integrations-plugins/p4search/current/Content/P4Search/api-endpoints.html\n      - type: Authentication\n        url: https://help.perforce.com/helix-core/integrations-plugins/p4search/current/Content/P4Search/api-authentication.html\n  - name: Perforce Helix Authentication Service API\n    description:\
  \ REST API for the Helix Authentication Service, a Node.js based authentication protocol integration service supporting OpenID Connect and SAML 2.0 for authenticating users across Perforce products.\n    image: https://www.perforce.com/sites/default/files/helix-core-icon.png\n    humanURL: https://help.perforce.com/helix-core/integrations-plugins/helix-auth-svc/current/\n    baseURL: https://auth.example.com\n    tags:\n      - Authentication\n      - Identity\n      - OpenID Connect\n      - SAML\n      - SSO\n    properties:\n      - type: Documentation\n        url: https://help.perforce.com/helix-core/integrations-plugins/helix-auth-svc/current/\n      - type: APIReference\n        url: https://github.com/perforce/helix-authentication-service/blob/main/docs/REST_API.md\n      - type: GitHubRepository\n        url: https://github.com/perforce/helix-authentication-service\ncommon:\n  - type: Portal\n    url: https://www.perforce.com/support/developers\n  - type: GettingStarted\n    url:\
  \ https://www.perforce.com/support/self-service-resources\n  - type: Documentation\n    url: https://www.perforce.com/support/self-service-resources/documentation\n  - type: Blog\n    url: https://www.perforce.com/blog\n  - type: Support\n    url: https://www.perforce.com/support\n  - type: StatusPage\n    url: https://status.perforce.com\n  - type: Integrations\n    url: https://www.perforce.com/plugins-integrations\n  - type: GitHubOrganization\n    url: https://github.com/perforce\n  - type: TermsOfService\n    url: https://www.perforce.com/terms-use\n  - type: PrivacyPolicy\n    url: https://www.perforce.com/privacy-policy\n  - type: Contact\n    url: https://www.perforce.com/contact-us\n  - type: Features\n    data:\n      - name: Code Review\n        description: Collaborative code review workflows with Helix Swarm supporting inline comments, voting, tasks, and approval gates.\n      - name: Version Control\n        description: Enterprise-scale version control with Helix Core supporting\
  \ large binary files, distributed development, and atomic changelists.\n      - name: Digital Asset Management\n        description: Versioned digital asset workflows with P4 DAM for reviewing, sharing, and managing creative assets stored in Helix Core.\n      - name: Application Lifecycle Management\n        description: End-to-end ALM with Helix ALM for requirements traceability, issue tracking, and test case management.\n      - name: Agile Planning\n        description: Agile project management with P4 Plan supporting sprints, backlogs, Gantt charts, and resource planning.\n      - name: Authentication Services\n        description: Single sign-on across Perforce products with Helix Authentication Service supporting OpenID Connect and SAML 2.0.\n  - type: UseCases\n    data:\n      - name: Game Development\n        description: Manage large game assets and source code with Helix Core providing fast file transfers and atomic changelists for game studios.\n      - name: Semiconductor\
  \ Design\n        description: Version control for chip design files with support for large binary IP blocks and strict access controls.\n      - name: Automotive Software\n        description: Manage safety-critical automotive software with full traceability from requirements through testing using Helix ALM.\n      - name: DevOps Automation\n        description: Automate CI/CD pipelines with Helix Core triggers, Swarm review gates, and REST API integrations.\n  - type: Integrations\n    data:\n      - name: Jenkins\n        description: Trigger builds and report results through Helix Core and Swarm integration plugins for Jenkins CI/CD.\n      - name: Visual Studio\n        description: Native Visual Studio integration with P4VS plugin for source control operations from within the IDE.\n      - name: Unity\n        description: Helix Core plugin for Unity game engine enabling version control of game projects directly within the editor.\n      - name: Unreal Engine\n        description:\
  \ Native Helix Core integration with Unreal Engine for versioning game assets and source code.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/perforce/refs/heads/main/apis.yml
tags: []
url: https://www.perforce.com
use_cases:
- description: Manage large game assets and source code with Helix Core providing fast file transfers and atomic changelists for game studios.
  name: Game Development
- description: Version control for chip design files with support for large binary IP blocks and strict access controls.
  name: Semiconductor Design
- description: Manage safety-critical automotive software with full traceability from requirements through testing using Helix ALM.
  name: Automotive Software
- description: Automate CI/CD pipelines with Helix Core triggers, Swarm review gates, and REST API integrations.
  name: DevOps Automation
---
