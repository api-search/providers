---
api_count: 1
apis:
- description: 'The BetterCloud Platform API provides REST API access for managing SaaS application operations, automated workflows, user lifecycle management, and security policies. It enables IT and security teams '
  name: BetterCloud Platform API
  slug: bettercloud-platform-api
capabilities:
- description: Unified SaaS user lifecycle management workflow combining user management, group management, workflow automation, and audit logging. Used by IT administrators and security teams to manage employee acc
  name: BetterCloud SaaS Lifecycle Management
  slug: saas-lifecycle-management
common:
- title: ''
  type: Portal
  url: https://developer.bettercloud.com/
- title: ''
  type: GettingStarted
  url: https://support.bettercloud.com/s/article/BCCINT4000--BetterCloud-API-Overview-bc33451
- title: ''
  type: Pricing
  url: https://www.bettercloud.com/pricing/
- title: ''
  type: Blog
  url: https://www.bettercloud.com/monitor/
- title: ''
  type: Support
  url: https://support.bettercloud.com/s/
- title: ''
  type: Login
  url: https://support.bettercloud.com/s/login/
- title: ''
  type: SignUp
  url: https://www.bettercloud.com/monitor/sign-up/
- title: ''
  type: GitHubOrganization
  url: https://github.com/BetterCloud
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/bettercloud/refs/heads/main/rules/bettercloud-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/bettercloud/refs/heads/main/vocabulary/bettercloud-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/bettercloud/refs/heads/main/capabilities/saas-lifecycle-management.yaml
created: '2026-03-16'
description: BetterCloud is the end-to-end SaaS management platform that enables IT teams to discover, manage, and secure the growing SaaS environment. The platform provides automated workflows, security policies, and management capabilities for SaaS applications in enterprise environments, handling billions of API calls per day across 100+ SaaS application integrations.
features:
- description: Automate user onboarding and offboarding workflows across all connected SaaS applications.
  name: User Lifecycle Management
- description: Automatically discover all SaaS applications in use across the organization.
  name: SaaS Discovery
- description: Build no-code automation workflows triggered by events, schedules, or manual action.
  name: Automated Workflows
- description: Create and enforce security policies that monitor and remediate violations across SaaS apps.
  name: Security Policy Enforcement
- description: Manage groups and memberships across Google Workspace, Azure AD, and other directory services.
  name: Group Management
- description: Comprehensive audit trail of all actions taken by users and automated workflows.
  name: Audit Logging
- description: Connect and manage 100+ enterprise SaaS applications including Google Workspace, Slack, Salesforce, and more.
  name: SaaS Integrations
- description: Track and optimize SaaS licenses to reduce spend and identify unused seats.
  name: License Management
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Manage Google Workspace users, groups, Drive files, and calendar access.
  name: Google Workspace
- description: Manage Slack workspace users, channels, and app connections.
  name: Slack
- description: Manage Salesforce user provisioning and deprovisioning.
  name: Salesforce
- description: Manage Microsoft 365 users, licenses, and Azure AD groups.
  name: Microsoft 365
- description: Connect BetterCloud workflows with Okta identity management.
  name: Okta
- description: Trigger BetterCloud workflows from ServiceNow ITSM tickets.
  name: ServiceNow
- description: Integrate SaaS management actions with Jira issue workflows.
  name: Jira
jsonld:
- class_count: 28
  name: Bettercloud Context
  property_count: 24
  slug: bettercloud-context
layout: provider
modified: '2026-04-19'
name: BetterCloud
rules:
- name: BetterCloud API Rules
  rule_count: 28
  severity_counts:
    error: 13
    hint: 0
    info: 2
    warn: 13
  slug: bettercloud-spectral-rules
skills: []
slug: bettercloud
solutions: []
tags:
- Automation
- Compliance
- Enterprise
- IT Operations
- SaaS Management
- Security
- Workflows
- User Lifecycle
url: https://raw.githubusercontent.com/api-evangelist/bettercloud/refs/heads/main/apis.yml
use_cases:
- description: Automatically revoke access and deprovision users across all SaaS applications when an employee leaves.
  name: Employee Offboarding
- description: Automatically provision new employees with appropriate SaaS access based on role and department.
  name: Employee Onboarding
- description: Identify underutilized licenses and redundant applications to reduce SaaS spend.
  name: SaaS Spend Optimization
- description: Immediately suspend and deprovision compromised accounts across all SaaS platforms.
  name: Security Incident Response
- description: Generate audit reports showing who has access to what across all connected SaaS applications.
  name: Compliance Auditing
- description: Periodically review and certify user access to ensure least-privilege principles.
  name: Access Reviews
---
