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
source_filename: apis.yml
source_yaml: "aid: beyondtrust\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/beyondtrust/refs/heads/main/apis.yml\napis:\n  - aid: beyondtrust:beyondtrust-password-safe-api\n    name: BeyondTrust Password Safe API\n    tags:\n      - Privileged Access Management\n      - Secrets Management\n      - Security\n      - Zero Trust\n      - Credentials\n    humanURL: https://docs.beyondtrust.com/\n    baseURL: https://{host}/BeyondTrust/api/public/v3\n    properties:\n      - url: https://docs.beyondtrust.com/\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/beyondtrust/refs/heads/main/openapi/beyondtrust-password-safe-api.yaml\n        type: OpenAPI\n    description: >-\n      The BeyondTrust Password Safe API provides programmatic access to\n      privileged credential management, secrets management, session management,\n      and access request workflows. It enables organizations to implement\n      just-in-time privileged\
  \ access and integrate credential retrieval into\n      automation pipelines and DevOps workflows.\nname: BeyondTrust\ntags:\n  - Access\n  - Access Management\n  - Compliance\n  - Credentials\n  - Privileged Access\n  - Security\n  - Secrets\n  - Zero Trust\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-17'\nmodified: '2026-04-19'\nposition: Consuming\ndescription: >-\n  BeyondTrust is a cybersecurity company specializing in privileged access\n  management (PAM) and vulnerability management solutions. Their products\n  help organizations prevent data breaches, malware attacks, and insider\n  threats by identifying and controlling the access of privileged users,\n  accounts, and credentials across the enterprise.\ncommon:\n  - type: Portal\n    url: https://docs.beyondtrust.com/\n  - type: GettingStarted\n    url: https://docs.beyondtrust.com/\n  - type: GitHubOrganization\n    url: https://github.com/BeyondTrust\n\
  \  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/beyondtrust/refs/heads/main/rules/beyondtrust-spectral-rules.yml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/beyondtrust/refs/heads/main/vocabulary/beyondtrust-vocabulary.yaml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/beyondtrust/refs/heads/main/capabilities/privileged-access-management.yaml\n  - type: Features\n    data:\n      - name: Privileged Password Management\n        description: Automatically discover, manage, and rotate passwords for privileged accounts across systems.\n      - name: Just-In-Time Privileged Access\n        description: Grant time-limited, approval-based access to privileged accounts minimizing standing privileges.\n      - name: Secrets Safe\n        description: Store, manage, and retrieve application secrets, API keys, and credentials securely.\n      - name: Session\
  \ Management\n        description: Record, monitor, and control privileged remote sessions for audit and compliance.\n      - name: Endpoint Privilege Management\n        description: Remove admin rights from endpoints while allowing approved applications to run.\n      - name: Privileged Remote Access\n        description: Provide secure remote access to privileged systems without VPN or exposed credentials.\n      - name: Vulnerability Management\n        description: Identify and prioritize vulnerabilities across the attack surface.\n      - name: AD Bridge\n        description: Extend Active Directory authentication and group policies to Unix and Linux systems.\n  - type: UseCases\n    data:\n      - name: Zero Standing Privileges\n        description: Eliminate persistent privileged access by granting just-in-time credentials on demand.\n      - name: DevOps Secrets Management\n        description: Retrieve credentials and secrets programmatically in CI/CD pipelines without hardcoded\
  \ credentials.\n      - name: Privileged Account Discovery\n        description: Automatically discover and on-board all privileged accounts across hybrid environments.\n      - name: Compliance Reporting\n        description: Generate audit trails for all privileged access to meet SOX, PCI-DSS, and HIPAA requirements.\n      - name: Ransomware Prevention\n        description: Prevent lateral movement by removing local admin rights and controlling privileged access.\n      - name: Third-Party Vendor Access\n        description: Grant temporary, monitored access to vendors and contractors without sharing credentials.\n  - type: Integrations\n    data:\n      - name: ServiceNow\n        description: Integrate access requests with ServiceNow ITSM workflows for approval management.\n      - name: Active Directory\n        description: Sync users, groups, and managed accounts from Active Directory.\n      - name: AWS\n        description: Manage privileged access to AWS IAM roles and EC2 instances.\n\
  \      - name: Azure\n        description: Integrate with Azure Active Directory and manage Azure privileged identities.\n      - name: HashiCorp Vault\n        description: Bridge BeyondTrust and HashiCorp Vault for secrets management.\n      - name: Splunk\n        description: Forward audit logs and session recordings to Splunk for SIEM analysis.\n      - name: Terraform\n        description: Manage BeyondTrust Password Safe resources as infrastructure as code.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/beyondtrust/refs/heads/main/apis.yml
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
