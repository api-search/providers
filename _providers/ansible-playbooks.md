---
api_count: 6
apis:
- description: REST API for Ansible Automation Platform (formerly Ansible Tower/AWX) to manage playbooks, inventories, credentials, job templates, and job execution at enterprise scale. Supports RBAC, workflows, sch
  name: Ansible Automation Platform API
  slug: ''
- description: AWX is the open-source upstream project for Ansible Automation Platform, providing a web-based UI, REST API, and task engine for Ansible. The AWX API offers programmatic access to job execution, inven
  name: AWX API
  slug: ''
- description: 'Ansible Runner is a Python library and CLI tool that provides a stable and consistent interface for executing Ansible playbooks programmatically from within other applications and tools. Used by AWX, '
  name: Ansible Runner API
  slug: ''
- description: 'Ansible Galaxy is the community hub for sharing Ansible roles and collections. The Galaxy REST API enables searching, downloading, and publishing Ansible content. Supports v1 (roles), v2 (mixed), and '
  name: Ansible Galaxy API
  slug: ''
- description: Red Hat Ansible Automation Hub is the enterprise content hub for certified Ansible collections, roles, and execution environments. The API provides access to Red Hat certified and partner-validated An
  name: Ansible Automation Hub API
  slug: ''
- description: Ansible Semaphore is an open-source modern web UI and REST API for running Ansible playbooks. It provides project management, task scheduling, access control, and a clean interface for teams using Ans
  name: Ansible Semaphore API
  slug: ''
common:
- title: ''
  type: GettingStarted
  url: https://docs.ansible.com/ansible/latest/getting_started/
- title: ''
  type: BestPractices
  url: https://docs.ansible.com/ansible/latest/tips_tricks/ansible_tips_tricks.html
- title: ''
  type: Blog
  url: https://www.ansible.com/blog
- title: ''
  type: TermsOfService
  url: https://www.redhat.com/en/about/terms-use
- title: ''
  type: PrivacyPolicy
  url: https://www.redhat.com/en/about/privacy-policy
- title: ''
  type: GitHubOrganization
  url: https://github.com/ansible
- title: ''
  type: Forum
  url: https://forum.ansible.com/
- title: Playbook Job Schema
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/json-schema/ansible-playbooks-playbook-job-schema.json
- title: Inventory Schema
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/json-schema/ansible-playbooks-inventory-schema.json
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/vocabulary/ansible-playbooks-vocabulary.yaml
created: '2024-01-15'
description: A curated collection of APIs, tools, and platforms for managing and executing Ansible playbooks for IT automation, configuration management, and orchestration. Covers the Ansible Automation Platform, AWX, Galaxy, Automation Hub, Runner, and Semaphore APIs that power modern infrastructure automation workflows.
features:
- description: Launch, monitor, and cancel Ansible playbook runs programmatically via REST API with support for extra vars, limits, and tags.
  name: Playbook Execution via API
- description: Create and manage dynamic and static inventories with groups, hosts, and host variables through the API.
  name: Inventory Management
- description: Securely store SSH keys, cloud credentials, and vault passwords in encrypted credential objects accessible to jobs.
  name: Credential Storage
- description: Chain multiple job templates into orchestrated workflows with conditional success/failure branching.
  name: Workflow Templates
- description: Schedule playbook runs on recurring schedules using rrule-based calendar expressions.
  name: Scheduling
- description: Discover, download, and manage Ansible collections and roles from Galaxy, Automation Hub, or private repositories.
  name: Collections and Role Management
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Deploy and configure OpenShift clusters and workloads using Ansible Automation Platform integrated with OpenShift pipelines.
  name: Red Hat OpenShift
- description: Trigger Ansible job templates from ServiceNow ITSM workflows for automated ticket remediation and change management.
  name: ServiceNow
- description: Use the Ansible Automation Platform GitHub Action to trigger playbook runs as part of GitHub CI/CD workflows.
  name: GitHub Actions
- description: Combine Terraform for infrastructure provisioning with Ansible for post-provisioning configuration management.
  name: Terraform
- description: Use Ansible collections to configure Splunk deployments and automate security alert remediation workflows.
  name: Splunk
jsonld:
- class_count: 4
  name: Ansible Playbooks Context
  property_count: 20
  slug: ansible-playbooks-context
layout: provider
modified: '2026-04-19'
name: Ansible Playbooks
skills: []
slug: ansible-playbooks
solutions: []
tags:
- Ansible
- Automation
- Configuration Management
- DevOps
- Infrastructure As Code
- Orchestration
- Playbooks
url: https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/apis.yml
use_cases:
- description: Automate the provisioning of cloud resources, VMs, and bare-metal servers using Ansible playbooks triggered via API.
  name: Infrastructure Provisioning
- description: Enforce consistent configuration state across server fleets by scheduling and executing configuration playbooks via API.
  name: Configuration Management
- description: Trigger Ansible playbook runs as deployment steps within Jenkins, GitLab CI, GitHub Actions, and other CI/CD platforms.
  name: CI/CD Pipeline Integration
- description: Run compliance playbooks on demand or on schedule to detect and remediate drift from desired security baseline states.
  name: Compliance and Remediation
- description: Automate network device configuration, firmware upgrades, and compliance checks using Ansible network collections via the API.
  name: Network Automation
---
