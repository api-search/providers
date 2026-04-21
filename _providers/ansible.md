---
api_count: 4
apis:
- description: RESTful API for Ansible Automation Platform (formerly Ansible Tower) that provides programmatic access to job templates, inventories, credentials, workflow templates, schedules, notifications, and job
  name: Ansible Automation Platform API
  slug: ''
- description: AWX is the open-source upstream project for Ansible Automation Platform, providing a web-based UI, REST API, and task engine for Ansible under the Apache 2.0 license. The AWX API mirrors the AAP API s
  name: AWX API
  slug: ''
- description: REST API for Ansible Galaxy — the community hub for sharing and downloading Ansible roles and collections. The v1 API covers roles and the v3 API covers collections with namespace management, versioni
  name: Ansible Galaxy API
  slug: ''
- description: The Red Hat Ansible Automation Hub API provides access to certified Ansible collections and roles curated by Red Hat and partners. Available through console.redhat.com, it serves certified content for
  name: Ansible Automation Hub API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://www.ansible.com
- title: ''
  type: GettingStarted
  url: https://docs.ansible.com/ansible/latest/getting_started/
- title: ''
  type: Documentation
  url: https://docs.ansible.com/
- title: ''
  type: Blog
  url: https://www.ansible.com/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/ansible
- title: ''
  type: Forum
  url: https://forum.ansible.com/
- title: ''
  type: Support
  url: https://access.redhat.com/products/red-hat-ansible-automation-platform/
- title: ''
  type: Training
  url: https://www.ansible.com/products/training-certification
- title: ''
  type: TermsOfService
  url: https://www.redhat.com/en/about/terms-use
- title: ''
  type: PrivacyPolicy
  url: https://www.redhat.com/en/about/privacy-policy
- title: Ansible Python Package
  type: SDK
  url: https://pypi.org/project/ansible/
- title: Ansible Runner Python Package
  type: SDK
  url: https://pypi.org/project/ansible-runner/
- title: Playbook Schema
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/ansible/refs/heads/main/json-schema/ansible-playbook-schema.json
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/ansible/refs/heads/main/vocabulary/ansible-vocabulary.yaml
created: '2024-01-01'
description: Ansible is an open-source IT automation platform developed by Red Hat that provides agentless configuration management, application deployment, cloud provisioning, and orchestration. Using YAML-based playbooks and an SSH-native architecture, Ansible automates infrastructure at scale without requiring agents or custom security infrastructure on managed nodes.
features:
- description: Ansible connects to managed nodes via SSH or WinRM without requiring any agent software, simplifying deployment and reducing attack surface.
  name: Agentless Architecture
- description: Automation is defined in human-readable YAML playbooks that describe the desired state of managed systems without complex programming.
  name: YAML Playbooks
- description: Ansible tasks are idempotent — running the same playbook multiple times produces the same result, making deployments safe to rerun.
  name: Idempotent Execution
- description: Over 3,000 built-in modules covering cloud providers, network devices, databases, containers, storage, and operating system tasks.
  name: Module Ecosystem
- description: The Ansible Collections packaging format bundles related modules, roles, plugins, and documentation for modular content distribution.
  name: Collection System
- description: Query cloud providers, CMDBs, and external systems dynamically to build host inventories at execution time rather than static files.
  name: Dynamic Inventory
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Ansible is the primary configuration management tool for Red Hat Enterprise Linux systems with deep integration into the RHEL platform.
  name: Red Hat Enterprise Linux
- description: Manage Kubernetes clusters, namespaces, deployments, and OpenShift workloads using the kubernetes.core collection.
  name: Kubernetes / OpenShift
- description: Combine Terraform for cloud resource provisioning with Ansible for post-provisioning OS and application configuration.
  name: Terraform
- description: Integrate Ansible playbook execution into CI/CD pipelines using the AAP Action for GitHub or Ansible Tower Plugin for Jenkins.
  name: Jenkins / GitHub Actions
- description: Trigger Ansible automation from ServiceNow ITSM workflows using the ServiceNow ITX collection for change management automation.
  name: ServiceNow
jsonld:
- class_count: 4
  name: Ansible Context
  property_count: 10
  slug: ansible-context
layout: provider
modified: '2026-04-19'
name: Ansible
skills: []
slug: ansible
solutions: []
tags:
- Ansible
- Automation
- Configuration Management
- DevOps
- Infrastructure As Code
- Open Source
- Orchestration
- Red Hat
url: https://raw.githubusercontent.com/api-evangelist/ansible/refs/heads/main/apis.yml
use_cases:
- description: Ensure servers and services remain in a consistent desired state by applying configuration playbooks across fleets of hosts.
  name: Configuration Management
- description: Deploy and update applications across development, staging, and production environments with zero-downtime rolling strategies.
  name: Application Deployment
- description: Provision cloud resources on AWS, Azure, GCP, and other providers using cloud-specific Ansible modules and dynamic inventory.
  name: Cloud Provisioning
- description: Configure routers, switches, and firewalls from Cisco, Juniper, Arista, and Palo Alto using vendor-specific Ansible collections.
  name: Network Automation
- description: Enforce security baselines, CIS benchmarks, and STIG compliance across infrastructure using Ansible hardening playbooks.
  name: Security and Compliance
---
