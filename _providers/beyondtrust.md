---
api_count: 1
apis:
- description: The BeyondTrust Password Safe API provides programmatic access to privileged credential management, secrets management, session management, and access request workflows. It enables organizations to im
  name: BeyondTrust Password Safe API
  slug: beyondtrust-password-safe-api
capabilities:
- description: Unified privileged access management workflow combining Password Safe credential management, access request workflows, and secrets management. Used by security engineers and DevOps teams to manage jus
  name: BeyondTrust Privileged Access Management
  slug: privileged-access-management
common:
- title: ''
  type: Portal
  url: https://docs.beyondtrust.com/
- title: ''
  type: GettingStarted
  url: https://docs.beyondtrust.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/BeyondTrust
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/beyondtrust/refs/heads/main/rules/beyondtrust-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/beyondtrust/refs/heads/main/vocabulary/beyondtrust-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/beyondtrust/refs/heads/main/capabilities/privileged-access-management.yaml
created: '2025-02-17'
description: BeyondTrust is a cybersecurity company specializing in privileged access management (PAM) and vulnerability management solutions. Their products help organizations prevent data breaches, malware attacks, and insider threats by identifying and controlling the access of privileged users, accounts, and credentials across the enterprise.
features:
- description: Automatically discover, manage, and rotate passwords for privileged accounts across systems.
  name: Privileged Password Management
- description: Grant time-limited, approval-based access to privileged accounts minimizing standing privileges.
  name: Just-In-Time Privileged Access
- description: Store, manage, and retrieve application secrets, API keys, and credentials securely.
  name: Secrets Safe
- description: Record, monitor, and control privileged remote sessions for audit and compliance.
  name: Session Management
- description: Remove admin rights from endpoints while allowing approved applications to run.
  name: Endpoint Privilege Management
- description: Provide secure remote access to privileged systems without VPN or exposed credentials.
  name: Privileged Remote Access
- description: Identify and prioritize vulnerabilities across the attack surface.
  name: Vulnerability Management
- description: Extend Active Directory authentication and group policies to Unix and Linux systems.
  name: AD Bridge
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integrate access requests with ServiceNow ITSM workflows for approval management.
  name: ServiceNow
- description: Sync users, groups, and managed accounts from Active Directory.
  name: Active Directory
- description: Manage privileged access to AWS IAM roles and EC2 instances.
  name: AWS
- description: Integrate with Azure Active Directory and manage Azure privileged identities.
  name: Azure
- description: Bridge BeyondTrust and HashiCorp Vault for secrets management.
  name: HashiCorp Vault
- description: Forward audit logs and session recordings to Splunk for SIEM analysis.
  name: Splunk
- description: Manage BeyondTrust Password Safe resources as infrastructure as code.
  name: Terraform
jsonld:
- class_count: 13
  name: Beyondtrust Context
  property_count: 37
  slug: beyondtrust-context
layout: provider
modified: '2026-04-19'
name: BeyondTrust
rules:
- name: BeyondTrust API Rules
  rule_count: 23
  severity_counts:
    error: 10
    hint: 0
    info: 2
    warn: 11
  slug: beyondtrust-spectral-rules
skills: []
slug: beyondtrust
solutions: []
tags:
- Access
- Access Management
- Compliance
- Credentials
- Privileged Access
- Security
- Secrets
- Zero Trust
url: https://raw.githubusercontent.com/api-evangelist/beyondtrust/refs/heads/main/apis.yml
use_cases:
- description: Eliminate persistent privileged access by granting just-in-time credentials on demand.
  name: Zero Standing Privileges
- description: Retrieve credentials and secrets programmatically in CI/CD pipelines without hardcoded credentials.
  name: DevOps Secrets Management
- description: Automatically discover and on-board all privileged accounts across hybrid environments.
  name: Privileged Account Discovery
- description: Generate audit trails for all privileged access to meet SOX, PCI-DSS, and HIPAA requirements.
  name: Compliance Reporting
- description: Prevent lateral movement by removing local admin rights and controlling privileged access.
  name: Ransomware Prevention
- description: Grant temporary, monitored access to vendors and contractors without sharing credentials.
  name: Third-Party Vendor Access
---
