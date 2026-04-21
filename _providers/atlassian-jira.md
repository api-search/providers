---
api_count: 3
apis:
- description: The Jira Cloud platform REST API enables developers to interact with Jira issues, projects, workflows, users, and more.
  name: Jira Cloud Platform REST API
  slug: jira-cloud-platform-rest-api
- description: REST API for Jira Software Cloud specific features including boards, sprints, and backlog management.
  name: Jira Software Cloud REST API
  slug: jira-software-cloud-rest-api
- description: REST API for Jira Service Management features including request types, service desk queues, and customer portals.
  name: Jira Service Management REST API
  slug: jira-service-management-rest-api
common:
- title: ''
  type: Website
  url: https://www.atlassian.com/software/jira
- title: ''
  type: Documentation
  url: https://developer.atlassian.com/cloud/jira/platform/
- title: ''
  type: Getting Started
  url: https://developer.atlassian.com/cloud/jira/platform/getting-started/
- title: ''
  type: Authentication
  url: https://developer.atlassian.com/cloud/jira/platform/oauth-2-3lo-apps/
- title: ''
  type: Pricing
  url: https://www.atlassian.com/software/jira/pricing
- title: ''
  type: Status
  url: https://status.atlassian.com/
- title: ''
  type: Support
  url: https://support.atlassian.com/
- title: ''
  type: Community
  url: https://community.developer.atlassian.com/
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
  type: Blog
  url: https://developer.atlassian.com/blog/
- title: ''
  type: RateLimits
  url: https://developer.atlassian.com/cloud/jira/platform/rate-limiting/
created: '2024-01-01'
description: Jira is a leading issue tracking and project management platform developed by Atlassian. It provides REST APIs for Jira Cloud Platform, Jira Software, and Jira Service Management enabling programmatic management of issues, projects, workflows, boards, sprints, users, and service desk requests with OAuth 2.0 authentication.
features:
- description: Create, update, transition, and delete Jira issues with full support for custom fields, attachments, comments, and workflow transitions.
  name: Issue Management
- description: Manage Jira projects including project categories, components, versions, and project-level configurations.
  name: Project Management
- description: Create and manage Scrum boards, sprints, and Kanban boards for agile project planning and execution.
  name: Board and Sprint Management
- description: Manage service desk projects, request types, queues, and SLA data for IT service management workflows.
  name: Service Desk
- description: Programmatically configure Jira workflows, statuses, transitions, and screen configurations.
  name: Workflow Configuration
- description: Build Jira apps using the Atlassian Forge platform with serverless functions and UI modules.
  name: Forge App Development
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Link Jira projects and issues to Confluence spaces and pages for integrated project documentation.
  name: Confluence
- description: Connect Bitbucket repositories to Jira for branch, commit, and pull request linking.
  name: Bitbucket
- description: Integrate GitHub with Jira via the GitHub for Jira app for development activity tracking.
  name: GitHub
- description: Receive Jira issue notifications and create issues directly from Slack using the Jira for Slack app.
  name: Slack
- description: Connect Jenkins build and deployment events to Jira issues via the Atlassian Jenkins plugin.
  name: Jenkins
- description: Create Jira issues automatically from PagerDuty incidents for integrated incident management.
  name: PagerDuty
layout: provider
modified: '2026-04-19'
name: Atlassian Jira
skills: []
slug: atlassian-jira
solutions:
- description: Manage software development with Scrum and Kanban boards, sprint planning, and backlog management.
  name: Agile Project Management
- description: Provide enterprise ITSM with service catalogs, SLAs, queues, and approval workflows via Jira Service Management.
  name: IT Service Management
- description: Track any business process or workflow using customizable Jira projects and issue types for non-software teams.
  name: Business Process Tracking
tags:
- Agile
- Atlassian
- Bug Tracking
- Issue Tracking
- ITSM
- Kanban
- Project Management
- Scrum
- Service Desk
url: https://raw.githubusercontent.com/api-evangelist/atlassian-jira/refs/heads/main/apis.yml
use_cases:
- description: Automate issue creation, assignment, and transitions from CI/CD pipelines, monitoring alerts, and external systems.
  name: Issue Automation
- description: Extract issue data, sprint velocity, and project metrics for custom reporting and analytics dashboards.
  name: Project Reporting
- description: Integrate Jira Service Management with external monitoring, CMDB, and ITSM tools for incident and change management.
  name: ITSM Integration
- description: Link Jira issues to commits, branches, builds, and deployments from GitHub, Bitbucket, and Jenkins.
  name: DevOps Pipeline Integration
- description: Synchronize custom field data between Jira and external systems for portfolio tracking and compliance reporting.
  name: Custom Field Automation
---
