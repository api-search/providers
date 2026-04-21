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
