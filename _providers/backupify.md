---
api_count: 1
apis:
- description: The Backupify SaaS Protection REST API enables programmatic management of cloud-to-cloud backup for Microsoft 365 and Google Workspace. Covers domain listing, seat enumeration, and bulk seat licensing
  name: Backupify SaaS Protection API
  slug: saas-protection-api
capabilities:
- description: SaaS backup management workflow for Backupify (Datto), covering domain administration and seat licensing for Microsoft 365 and Google Workspace. Serves MSPs and IT administrators managing cloud-to-clo
  name: Backupify SaaS Backup Management
  slug: saas-backup-management
common:
- title: ''
  type: Website
  url: https://www.backupify.com
- title: ''
  type: Documentation
  url: https://saasprotection.datto.com/help/M365/Content/Other_Administrative_Tasks/using-rest-api-saas-protection.htm
- title: ''
  type: Portal
  url: https://portal.dattobackup.com
- title: ''
  type: Pricing
  url: https://www.backupify.com/pricing
- title: ''
  type: Blog
  url: https://www.datto.com/blog/
- title: ''
  type: Support
  url: https://www.datto.com/support/
- title: ''
  type: TermsOfService
  url: https://www.datto.com/legal/terms-and-conditions/
- title: ''
  type: PrivacyPolicy
  url: https://www.datto.com/legal/privacy-policy/
- title: ''
  type: GitHubOrganization
  url: https://github.com/backupify
- title: ''
  type: SpectralRules
  url: rules/backupify-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/backupify-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/saas-backup-management.yaml
created: '2026-03-27'
description: Backupify (by Datto/Kaseya) is a SaaS backup platform providing automated cloud-to-cloud data protection for Google Workspace and Microsoft 365. It offers seat-level backup coverage for users, shared mailboxes, SharePoint sites, team sites, and Microsoft Teams. The SaaS Protection REST API enables MSPs and enterprise IT teams to automate domain administration and seat licensing programmatically.
features:
- description: Automated cloud-to-cloud backup for Exchange, OneDrive, SharePoint, and Teams.
  name: Microsoft 365 Backup
- description: Automated backup for Gmail, Drive, Contacts, and Calendar.
  name: Google Workspace Backup
- description: License, unlicense, or pause backup at the individual user, mailbox, site, or team level.
  name: Seat-Level Control
- description: Manage up to 100 seat changes in a single API call.
  name: Bulk Seat Management
- description: Manage backup across multiple customer domains from a single pane of glass.
  name: MSP Multi-Tenant
- description: Restore data to any point in time with granular item-level recovery.
  name: Point-in-Time Recovery
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native integration with Exchange Online, OneDrive, SharePoint, and Microsoft Teams.
  name: Microsoft 365
- description: Native integration with Gmail, Google Drive, Contacts, and Calendar.
  name: Google Workspace
- description: Integration with Kaseya RMM for MSP workflow automation.
  name: Kaseya VSA
- description: Integration with Datto RMM for endpoint and SaaS backup orchestration.
  name: Datto RMM
jsonld:
- class_count: 8
  name: Backupify Context
  property_count: 16
  slug: backupify-context
layout: provider
modified: '2026-04-21'
name: Backupify
rules:
- name: Backupify API Rules
  rule_count: 12
  severity_counts:
    error: 8
    hint: 0
    info: 0
    warn: 4
  slug: backupify-spectral-rules
skills: []
slug: backupify
solutions: []
tags:
- SaaS Backup
- Data Protection
- Cloud Backup
- Microsoft 365
- Google Workspace
url: https://raw.githubusercontent.com/api-evangelist/backupify/refs/heads/main/apis.yml
use_cases:
- description: Protect Microsoft 365 and Google Workspace data from accidental deletion, ransomware, and insider threats.
  name: SaaS Data Protection
- description: Automate backup seat provisioning and de-provisioning across multiple customer tenants.
  name: MSP Backup Management
- description: Maintain immutable backups for compliance, legal hold, and audit requirements.
  name: Compliance and Archival
- description: Backup source data before and during cloud-to-cloud migrations.
  name: Migration Support
---
