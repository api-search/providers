---
api_count: 3
apis:
- description: The primary REST API for Confluence Cloud, providing access to content, spaces, users, and more.
  name: Confluence Cloud REST API
  slug: confluence-cloud-rest-api
- description: The next generation REST API for Confluence Cloud with improved performance and new capabilities.
  name: Confluence Cloud REST API V2
  slug: confluence-cloud-rest-api-v2
- description: The Confluence Cloud GraphQL API provides flexible querying and mutation capabilities for Confluence content, spaces, pages, and user data using OAuth 2.0 authentication.
  name: Confluence Cloud GraphQL API
  slug: confluence-cloud-graphql-api
common:
- title: ''
  type: Website
  url: https://www.atlassian.com/software/confluence
- title: ''
  type: Documentation
  url: https://developer.atlassian.com/cloud/confluence/
- title: ''
  type: Getting Started
  url: https://developer.atlassian.com/cloud/confluence/getting-started/
- title: ''
  type: Authentication
  url: https://developer.atlassian.com/cloud/confluence/oauth-2-3lo-apps/
- title: ''
  type: Change Log
  url: https://developer.atlassian.com/cloud/confluence/changelog/
- title: ''
  type: Status
  url: https://status.atlassian.com/
- title: ''
  type: Support
  url: https://support.atlassian.com/
- title: ''
  type: Community
  url: https://community.atlassian.com/
- title: ''
  type: Terms of Service
  url: https://www.atlassian.com/legal/cloud-terms-of-service
- title: ''
  type: Privacy Policy
  url: https://www.atlassian.com/legal/privacy-policy
- title: ''
  type: GitHub Organization
  url: https://github.com/atlassian
- title: ''
  type: RateLimits
  url: https://developer.atlassian.com/cloud/confluence/rate-limiting/
- title: ''
  type: Blog
  url: https://developer.atlassian.com/blog/
- title: ''
  type: Pricing
  url: https://www.atlassian.com/software/confluence/pricing
- title: ''
  type: SignUp
  url: https://www.atlassian.com/software/confluence
- title: ''
  type: SDK
  url: https://developer.atlassian.com/platform/forge/
created: '2024-01-15'
description: Atlassian Confluence is a team collaboration and wiki platform for creating, organizing, and discussing work with your team. It provides REST APIs (v1 and v2) and a GraphQL API for managing content, spaces, pages, users, labels, and search across Confluence Cloud deployments, enabling automation, app development, and integration with enterprise workflows.
features:
- description: Create, read, update, and delete Confluence pages, blog posts, and spaces programmatically via REST or GraphQL.
  name: Content Management API
- description: Execute powerful content searches using Confluence Query Language (CQL) to find pages, users, and spaces.
  name: CQL Search
- description: Manage Confluence users, groups, and permissions programmatically using the REST API.
  name: User and Group Management
- description: Build Confluence apps with the Atlassian Forge platform using serverless functions and UI extensions.
  name: Forge App Development
- description: Subscribe to Confluence events via webhooks to trigger workflows on content creation, update, and deletion.
  name: Webhook Support
- description: Secure API access via OAuth 2.0 three-legged authorization for user-facing integrations.
  name: OAuth 2.0 Authentication
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Deep native integration linking Confluence pages to Jira issues, projects, and sprints for unified project documentation.
  name: Jira
- description: Confluence Slack integration for notifications, page previews, and content sharing within Slack channels.
  name: Slack
- description: Share and preview Confluence pages within Microsoft Teams with native connector support.
  name: Microsoft Teams
- description: Link Trello boards to Confluence spaces for project documentation aligned with Kanban workflows.
  name: Trello
- description: Embed Bitbucket code snippets and repository information in Confluence pages using Smart Links.
  name: Bitbucket
layout: provider
modified: '2026-04-19'
name: Atlassian Confluence
skills: []
slug: atlassian-confluence
solutions:
- description: Create a structured team knowledge base with organized spaces, nested pages, and templates for documentation.
  name: Team Knowledge Base
- description: Maintain living technical documentation alongside development workflows with API-driven updates.
  name: Technical Documentation
- description: Facilitate project planning, retrospectives, and cross-team collaboration with integrated Jira and Confluence workspaces.
  name: Project Collaboration
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: atlassian-confluence\nname: Atlassian Confluence\ndescription: |\n  Atlassian Confluence is a team collaboration and wiki platform for creating, organizing, and discussing work with your team. It provides REST APIs (v1 and v2) and a GraphQL API for managing content, spaces, pages, users, labels, and search across Confluence Cloud deployments, enabling automation, app development, and integration with enterprise workflows.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Atlassian\n- Collaboration\n- Content Management\n- Documentation\n- Knowledge Management\n- Wiki\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/atlassian-confluence/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: atlassian-confluence:confluence-cloud-rest-api\n  name: Confluence Cloud REST API\n  description: >-\n    The primary REST API for Confluence Cloud, providing\
  \ access to content,\n    spaces, users, and more.\n  humanURL: https://developer.atlassian.com/cloud/confluence/rest/\n  baseURL: https://your-domain.atlassian.net/wiki/rest/api\n  tags:\n  - Content\n  - Pages\n  - REST\n  - Spaces\n  properties:\n  - type: Documentation\n    url: https://developer.atlassian.com/cloud/confluence/rest/v1/intro/\n  - type: OpenAPI\n    url: https://dac-static.atlassian.com/cloud/confluence/swagger.v3.json\n  - type: Authentication\n    url: https://developer.atlassian.com/cloud/confluence/authentication/\n  - type: GettingStarted\n    url: https://developer.atlassian.com/cloud/confluence/getting-started/\n- aid: atlassian-confluence:confluence-cloud-rest-api-v2\n  name: Confluence Cloud REST API V2\n  description: >-\n    The next generation REST API for Confluence Cloud with improved\n    performance and new capabilities.\n  humanURL: https://developer.atlassian.com/cloud/confluence/rest/v2/intro/\n  baseURL: https://your-domain.atlassian.net/wiki/api/v2\n\
  \  tags:\n  - Content\n  - Pages\n  - REST\n  - Spaces\n  properties:\n  - type: Documentation\n    url: https://developer.atlassian.com/cloud/confluence/rest/v2/intro/\n  - type: OpenAPI\n    url: https://dac-static.atlassian.com/cloud/confluence/openapi-v2.v3.json\n- aid: atlassian-confluence:confluence-cloud-graphql-api\n  name: Confluence Cloud GraphQL API\n  description: |\n    The Confluence Cloud GraphQL API provides flexible querying and mutation capabilities for Confluence content, spaces, pages, and user data using OAuth 2.0 authentication.\n  humanURL: https://developer.atlassian.com/cloud/confluence/graphql/\n  baseURL: https://api.atlassian.com/graphql\n  tags:\n  - Content\n  - GraphQL\n  - Pages\n  - Spaces\n  properties:\n  - type: Documentation\n    url: https://developer.atlassian.com/cloud/confluence/graphql/\ncommon:\n- type: Website\n  url: https://www.atlassian.com/software/confluence\n- type: Documentation\n  url: https://developer.atlassian.com/cloud/confluence/\n\
  - type: Getting Started\n  url: https://developer.atlassian.com/cloud/confluence/getting-started/\n- type: Authentication\n  url: https://developer.atlassian.com/cloud/confluence/oauth-2-3lo-apps/\n- type: Change Log\n  url: https://developer.atlassian.com/cloud/confluence/changelog/\n- type: Status\n  url: https://status.atlassian.com/\n- type: Support\n  url: https://support.atlassian.com/\n- type: Community\n  url: https://community.atlassian.com/\n- type: Terms of Service\n  url: https://www.atlassian.com/legal/cloud-terms-of-service\n- type: Privacy Policy\n  url: https://www.atlassian.com/legal/privacy-policy\n- type: GitHub Organization\n  url: https://github.com/atlassian\n- type: RateLimits\n  url: https://developer.atlassian.com/cloud/confluence/rate-limiting/\n- type: Blog\n  url: https://developer.atlassian.com/blog/\n- type: Pricing\n  url: https://www.atlassian.com/software/confluence/pricing\n- type: SignUp\n  url: https://www.atlassian.com/software/confluence\n- type: SDK\n\
  \  url: https://developer.atlassian.com/platform/forge/\n- type: Features\n  data:\n  - name: Content Management API\n    description: Create, read, update, and delete Confluence pages, blog posts, and spaces programmatically via REST or GraphQL.\n  - name: CQL Search\n    description: Execute powerful content searches using Confluence Query Language (CQL) to find pages, users, and spaces.\n  - name: User and Group Management\n    description: Manage Confluence users, groups, and permissions programmatically using the REST API.\n  - name: Forge App Development\n    description: Build Confluence apps with the Atlassian Forge platform using serverless functions and UI extensions.\n  - name: Webhook Support\n    description: Subscribe to Confluence events via webhooks to trigger workflows on content creation, update, and deletion.\n  - name: OAuth 2.0 Authentication\n    description: Secure API access via OAuth 2.0 three-legged authorization for user-facing integrations.\n- type: UseCases\n\
  \  data:\n  - name: Documentation Automation\n    description: Automatically create and update Confluence pages from CI/CD pipelines, JIRA data, or external documentation sources.\n  - name: Content Migration\n    description: Migrate content from other wikis and knowledge bases into Confluence using the REST API bulk import capabilities.\n  - name: Enterprise Search Integration\n    description: Index and search Confluence content from enterprise search platforms using the CQL search API.\n  - name: Custom App Development\n    description: Build custom Confluence apps and macros using Forge to extend the platform with team-specific workflows.\n  - name: Reporting and Analytics\n    description: Extract page views, space statistics, and content metadata for custom analytics and reporting dashboards.\n- type: Integrations\n  data:\n  - name: Jira\n    description: Deep native integration linking Confluence pages to Jira issues, projects, and sprints for unified project documentation.\n\
  \  - name: Slack\n    description: Confluence Slack integration for notifications, page previews, and content sharing within Slack channels.\n  - name: Microsoft Teams\n    description: Share and preview Confluence pages within Microsoft Teams with native connector support.\n  - name: Trello\n    description: Link Trello boards to Confluence spaces for project documentation aligned with Kanban workflows.\n  - name: Bitbucket\n    description: Embed Bitbucket code snippets and repository information in Confluence pages using Smart Links.\n- type: Solutions\n  data:\n  - name: Team Knowledge Base\n    description: Create a structured team knowledge base with organized spaces, nested pages, and templates for documentation.\n  - name: Technical Documentation\n    description: Maintain living technical documentation alongside development workflows with API-driven updates.\n  - name: Project Collaboration\n    description: Facilitate project planning, retrospectives, and cross-team collaboration\
  \ with integrated Jira and Confluence workspaces.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/atlassian-confluence/refs/heads/main/apis.yml
tags:
- Atlassian
- Collaboration
- Content Management
- Documentation
- Knowledge Management
- Wiki
url: https://raw.githubusercontent.com/api-evangelist/atlassian-confluence/refs/heads/main/apis.yml
use_cases:
- description: Automatically create and update Confluence pages from CI/CD pipelines, JIRA data, or external documentation sources.
  name: Documentation Automation
- description: Migrate content from other wikis and knowledge bases into Confluence using the REST API bulk import capabilities.
  name: Content Migration
- description: Index and search Confluence content from enterprise search platforms using the CQL search API.
  name: Enterprise Search Integration
- description: Build custom Confluence apps and macros using Forge to extend the platform with team-specific workflows.
  name: Custom App Development
- description: Extract page views, space statistics, and content metadata for custom analytics and reporting dashboards.
  name: Reporting and Analytics
---
