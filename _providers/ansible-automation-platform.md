---
api_count: 4
apis:
- description: RESTful API for the Ansible Automation Controller (formerly Ansible Tower) providing programmatic access to job templates, workflows, inventories, credentials, projects, and job execution. Supports CR
  name: Ansible Automation Controller API
  slug: controller-api
- description: REST API for Ansible Automation Hub providing access to certified and validated Ansible content collections, roles, and execution environments. Supports searching, downloading, and publishing automati
  name: Ansible Automation Hub API
  slug: hub-api
- description: API for Event-Driven Ansible (EDA) Controller enabling management of rulebooks, activations, and event sources for automated response to infrastructure and application events.
  name: Ansible Event-Driven Automation API
  slug: event-driven-api
- description: REST API for Ansible Galaxy, the community hub for sharing Ansible roles and collections. Supports searching, downloading, and rating community automation content.
  name: Ansible Galaxy API
  slug: galaxy-api
common:
- title: ''
  type: Portal
  url: https://docs.ansible.com/
- title: ''
  type: Documentation
  url: https://docs.ansible.com/automation-controller/
- title: ''
  type: GettingStarted
  url: https://docs.ansible.com/ansible/latest/getting_started/
- title: ''
  type: Blog
  url: https://www.ansible.com/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/ansible
- title: ''
  type: Support
  url: https://access.redhat.com/products/ansible-automation-platform
- title: ''
  type: TermsOfService
  url: https://www.redhat.com/en/about/agreements
- title: ''
  type: PrivacyPolicy
  url: https://www.redhat.com/en/about/privacy-policy
- title: ''
  type: Training
  url: https://www.ansible.com/products/training-certification
- title: ''
  type: YouTube
  url: https://www.youtube.com/ansibleautomation
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/ansible
- title: ''
  type: Pricing
  url: https://www.redhat.com/en/technologies/management/ansible/pricing
created: '2024-01-01'
description: Ansible Automation Platform (formerly Ansible Tower) provides a REST API for managing automation workflows, job templates, inventories, credentials, and projects. The API enables programmatic access to the automation controller for launching jobs, managing infrastructure inventory, and orchestrating complex multi-tier deployments across hybrid cloud environments.
features:
- description: Define and manage reusable automation job templates with variables, credentials, and inventory assignments.
  name: Job Template Management
- description: Build multi-step automation workflows with conditional logic, error handling, and approval gates.
  name: Workflow Orchestration
- description: Manage dynamic and static inventories of infrastructure hosts with grouping and variable assignment.
  name: Inventory Management
- description: Fine-grained access control for automation resources with teams, users, and permission assignments.
  name: Role-Based Access Control
- description: Automatically respond to infrastructure events with rulebook-driven automation triggers.
  name: Event-Driven Automation
- description: Discover, install, and manage certified Ansible content collections from Automation Hub.
  name: Content Collections
image: /assets/icons/ansible-automation-platform.png
integrations:
- description: Integration with Red Hat Satellite for content management and patch automation.
  name: Red Hat Satellite
- description: ITSM integration for change management approval workflows and incident remediation.
  name: ServiceNow
- description: Cloud automation modules for AWS services including EC2, S3, RDS, and CloudFormation.
  name: AWS
- description: Cloud automation modules for Azure services including VMs, AKS, and Azure Resource Manager.
  name: Azure
- description: Infrastructure as code integration for provisioning with Terraform and configuring with Ansible.
  name: Terraform
- description: CI/CD pipeline integration for automated deployment workflows triggered by Jenkins.
  name: Jenkins
jsonld:
- class_count: 3
  name: Ansible Automation Platform Context
  property_count: 9
  slug: ansible-automation-platform-context
layout: provider
modified: '2026-04-18'
name: Ansible Automation Platform
rules:
- name: Ansible Automation Platform API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: ansible-automation-platform-spectral-rules
skills: []
slug: ansible-automation-platform
solutions: []
source_yaml: "aid: ansible-automation-platform\nname: Ansible Automation Platform\ndescription: >-\n  Ansible Automation Platform (formerly Ansible Tower) provides a REST API for\n  managing automation workflows, job templates, inventories, credentials, and\n  projects. The API enables programmatic access to the automation controller for\n  launching jobs, managing infrastructure inventory, and orchestrating complex\n  multi-tier deployments across hybrid cloud environments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ansible-automation-platform/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Automation\n  - Configuration Management\n  - DevOps\n  - Infrastructure as Code\n  - Orchestration\napis:\n  - aid: ansible-automation-platform:controller-api\n    name: Ansible Automation Controller API\n    description: >-\n\
  \      RESTful API for the Ansible Automation Controller (formerly Ansible Tower)\n      providing programmatic access to job templates, workflows, inventories,\n      credentials, projects, and job execution. Supports CRUD operations on all\n      controller resources with token-based and session authentication.\n    humanURL: https://docs.ansible.com/automation-controller/latest/html/controllerapi/\n    baseURL: https://controller-host/api/v2/\n    tags:\n      - Automation\n      - Controller\n      - Jobs\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.ansible.com/automation-controller/latest/html/controllerapi/\n      - type: APIReference\n        url: https://docs.ansible.com/automation-controller/latest/html/controllerapi/api_ref.html\n      - type: Authentication\n        url: https://docs.ansible.com/automation-controller/latest/html/controllerapi/authentication.html\n      - type: GettingStarted\n        url: https://docs.ansible.com/automation-controller/latest/html/controllerapi/intro.html\n\
  \  - aid: ansible-automation-platform:hub-api\n    name: Ansible Automation Hub API\n    description: >-\n      REST API for Ansible Automation Hub providing access to certified and validated\n      Ansible content collections, roles, and execution environments. Supports\n      searching, downloading, and publishing automation content.\n    humanURL: https://docs.ansible.com/automation-hub/\n    baseURL: https://hub-host/api/galaxy/\n    tags:\n      - Collections\n      - Content Hub\n      - REST\n      - Roles\n    properties:\n      - type: Documentation\n        url: https://docs.ansible.com/automation-hub/\n  - aid: ansible-automation-platform:event-driven-api\n    name: Ansible Event-Driven Automation API\n    description: >-\n      API for Event-Driven Ansible (EDA) Controller enabling management of\n      rulebooks, activations, and event sources for automated response to\n      infrastructure and application events.\n    humanURL: https://docs.ansible.com/automation-controller/latest/html/userguide/eda.html\n\
  \    baseURL: https://eda-host/api/eda/v1/\n    tags:\n      - EDA\n      - Event-Driven\n      - REST\n      - Rulebooks\n    properties:\n      - type: Documentation\n        url: https://docs.ansible.com/automation-controller/latest/html/userguide/eda.html\n  - aid: ansible-automation-platform:galaxy-api\n    name: Ansible Galaxy API\n    description: >-\n      REST API for Ansible Galaxy, the community hub for sharing Ansible roles\n      and collections. Supports searching, downloading, and rating community\n      automation content.\n    humanURL: https://galaxy.ansible.com/docs/\n    baseURL: https://galaxy.ansible.com/api/v3/\n    tags:\n      - Collections\n      - Community\n      - Galaxy\n      - REST\n      - Roles\n    properties:\n      - type: Documentation\n        url: https://galaxy.ansible.com/docs/\n      - type: APIReference\n        url: https://galaxy.ansible.com/api/\ncommon:\n  - type: Portal\n    url: https://docs.ansible.com/\n  - type: Documentation\n    url:\
  \ https://docs.ansible.com/automation-controller/\n  - type: GettingStarted\n    url: https://docs.ansible.com/ansible/latest/getting_started/\n  - type: Blog\n    url: https://www.ansible.com/blog\n  - type: GitHubOrganization\n    url: https://github.com/ansible\n  - type: Support\n    url: https://access.redhat.com/products/ansible-automation-platform\n  - type: TermsOfService\n    url: https://www.redhat.com/en/about/agreements\n  - type: PrivacyPolicy\n    url: https://www.redhat.com/en/about/privacy-policy\n  - type: Training\n    url: https://www.ansible.com/products/training-certification\n  - type: YouTube\n    url: https://www.youtube.com/ansibleautomation\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/ansible\n  - type: Pricing\n    url: https://www.redhat.com/en/technologies/management/ansible/pricing\n  - type: Features\n    data:\n      - name: Job Template Management\n        description: Define and manage reusable automation job templates\
  \ with variables, credentials, and inventory assignments.\n      - name: Workflow Orchestration\n        description: Build multi-step automation workflows with conditional logic, error handling, and approval gates.\n      - name: Inventory Management\n        description: Manage dynamic and static inventories of infrastructure hosts with grouping and variable assignment.\n      - name: Role-Based Access Control\n        description: Fine-grained access control for automation resources with teams, users, and permission assignments.\n      - name: Event-Driven Automation\n        description: Automatically respond to infrastructure events with rulebook-driven automation triggers.\n      - name: Content Collections\n        description: Discover, install, and manage certified Ansible content collections from Automation Hub.\n  - type: UseCases\n    data:\n      - name: Infrastructure Provisioning\n        description: Automate provisioning of servers, networks, and cloud resources across\
  \ hybrid environments.\n      - name: Configuration Management\n        description: Maintain consistent configuration across thousands of servers with idempotent automation.\n      - name: Application Deployment\n        description: Automate application deployment pipelines with rolling updates and rollback capabilities.\n      - name: Security Compliance\n        description: Enforce security policies and compliance standards through automated remediation workflows.\n      - name: Network Automation\n        description: Automate network device configuration and management across multi-vendor environments.\n  - type: Integrations\n    data:\n      - name: Red Hat Satellite\n        description: Integration with Red Hat Satellite for content management and patch automation.\n      - name: ServiceNow\n        description: ITSM integration for change management approval workflows and incident remediation.\n      - name: AWS\n        description: Cloud automation modules for AWS services\
  \ including EC2, S3, RDS, and CloudFormation.\n      - name: Azure\n        description: Cloud automation modules for Azure services including VMs, AKS, and Azure Resource Manager.\n      - name: Terraform\n        description: Infrastructure as code integration for provisioning with Terraform and configuring with Ansible.\n      - name: Jenkins\n        description: CI/CD pipeline integration for automated deployment workflows triggered by Jenkins.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ansible-automation-platform/refs/heads/main/apis.yml
tags:
- Automation
- Configuration Management
- DevOps
- Infrastructure as Code
- Orchestration
url: https://raw.githubusercontent.com/api-evangelist/ansible-automation-platform/refs/heads/main/apis.yml
use_cases:
- description: Automate provisioning of servers, networks, and cloud resources across hybrid environments.
  name: Infrastructure Provisioning
- description: Maintain consistent configuration across thousands of servers with idempotent automation.
  name: Configuration Management
- description: Automate application deployment pipelines with rolling updates and rollback capabilities.
  name: Application Deployment
- description: Enforce security policies and compliance standards through automated remediation workflows.
  name: Security Compliance
- description: Automate network device configuration and management across multi-vendor environments.
  name: Network Automation
---
