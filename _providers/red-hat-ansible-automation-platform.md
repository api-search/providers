---
api_count: 4
apis:
- description: 'Enterprise REST API for the Red Hat Ansible Automation Controller providing centralized management of automation jobs, workflows, inventories, credentials, and RBAC with enterprise authentication and '
  name: Red Hat Ansible Automation Controller API
  slug: controller-api
- description: REST API for managing a private instance of Ansible Automation Hub, enabling organizations to curate, publish, and distribute certified and custom Ansible content collections within their enterprise.
  name: Red Hat Ansible Private Automation Hub API
  slug: private-hub-api
- description: 'REST API for the Event-Driven Ansible Controller enabling management of event sources, rulebook activations, decision environments, and automated response workflows for infrastructure and application '
  name: Red Hat Event-Driven Ansible Controller API
  slug: eda-controller-api
- description: REST API for the Automation Services Catalog providing a self-service portal where users can order and manage pre-approved automation services with governance controls and approval workflows.
  name: Red Hat Automation Services Catalog API
  slug: services-catalog-api
common:
- title: ''
  type: Portal
  url: https://www.redhat.com/en/technologies/management/ansible
- title: ''
  type: Documentation
  url: https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/
- title: ''
  type: GettingStarted
  url: https://www.redhat.com/en/technologies/management/ansible/trial
- title: ''
  type: Blog
  url: https://www.ansible.com/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/ansible
- title: ''
  type: Support
  url: https://access.redhat.com/support/
- title: ''
  type: TermsOfService
  url: https://www.redhat.com/en/about/agreements
- title: ''
  type: PrivacyPolicy
  url: https://www.redhat.com/en/about/privacy-policy
- title: ''
  type: Training
  url: https://www.redhat.com/en/services/training/do007-ansible-essentials-simplicity-automation-technical-overview
- title: ''
  type: Pricing
  url: https://www.redhat.com/en/technologies/management/ansible/pricing
- title: ''
  type: StatusPage
  url: https://status.redhat.com/
created: '2024-01-01'
description: Red Hat Ansible Automation Platform is an enterprise automation solution that provides a framework for building and operating IT automation at scale. It includes the Automation Controller, Automation Hub, Event-Driven Ansible, and Ansible Lightspeed with IBM watsonx Code Assistant, providing REST APIs for managing automation across hybrid cloud infrastructure.
features:
- description: Centralized management of automation with RBAC, audit logging, and credential management.
  name: Enterprise Automation Controller
- description: Curate and distribute certified and custom Ansible content collections within the enterprise.
  name: Private Automation Hub
- description: Automated response to infrastructure events using rulebook activations and event sources.
  name: Event-Driven Automation
- description: AI-powered automation content generation with IBM watsonx Code Assistant.
  name: Ansible Lightspeed
- description: Containerized automation runtime environments for consistent and portable execution.
  name: Execution Environments
- description: Distributed automation execution architecture for scaling across global infrastructure.
  name: Automation Mesh
image: /assets/icons/red-hat-ansible-automation-platform.png
integrations:
- description: Container platform integration for deploying and managing Ansible on Kubernetes.
  name: Red Hat OpenShift
- description: Content management and patching integration for RHEL infrastructure automation.
  name: Red Hat Satellite
- description: ITSM integration for change management and incident remediation workflows.
  name: ServiceNow
- description: Cloud automation for AWS services with certified content collections.
  name: AWS
- description: Cloud automation for Azure services with certified content collections.
  name: Microsoft Azure
- description: Cloud automation for GCP services with certified content collections.
  name: Google Cloud
layout: provider
modified: '2026-04-18'
name: Red Hat Ansible Automation Platform
skills: []
slug: red-hat-ansible-automation-platform
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: red-hat-ansible-automation-platform\nname: Red Hat Ansible Automation Platform\ndescription: >-\n  Red Hat Ansible Automation Platform is an enterprise automation solution that\n  provides a framework for building and operating IT automation at scale. It includes\n  the Automation Controller, Automation Hub, Event-Driven Ansible, and Ansible\n  Lightspeed with IBM watsonx Code Assistant, providing REST APIs for managing\n  automation across hybrid cloud infrastructure.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/red-hat-ansible-automation-platform/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Automation\n  - Configuration Management\n  - DevOps\n  - Enterprise\n  - Red Hat\napis:\n  - aid: red-hat-ansible-automation-platform:controller-api\n    name: Red Hat Ansible Automation Controller API\n\
  \    description: >-\n      Enterprise REST API for the Red Hat Ansible Automation Controller providing\n      centralized management of automation jobs, workflows, inventories, credentials,\n      and RBAC with enterprise authentication and audit logging.\n    humanURL: https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/\n    baseURL: https://controller-host/api/v2/\n    tags:\n      - Automation\n      - Controller\n      - Enterprise\n      - REST\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/\n      - type: APIReference\n        url: https://docs.ansible.com/automation-controller/latest/html/controllerapi/api_ref.html\n      - type: Authentication\n        url: https://docs.ansible.com/automation-controller/latest/html/controllerapi/authentication.html\n  - aid: red-hat-ansible-automation-platform:private-hub-api\n    name: Red Hat Ansible Private Automation\
  \ Hub API\n    description: >-\n      REST API for managing a private instance of Ansible Automation Hub, enabling\n      organizations to curate, publish, and distribute certified and custom Ansible\n      content collections within their enterprise.\n    humanURL: https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/2.4/html/managing_red_hat_certified_and_ansible_galaxy_collections_in_automation_hub/\n    baseURL: https://hub-host/api/galaxy/\n    tags:\n      - Collections\n      - Content Hub\n      - Enterprise\n      - REST\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/2.4/html/managing_red_hat_certified_and_ansible_galaxy_collections_in_automation_hub/\n  - aid: red-hat-ansible-automation-platform:eda-controller-api\n    name: Red Hat Event-Driven Ansible Controller API\n    description: >-\n      REST API for the Event-Driven Ansible Controller enabling management\
  \ of event\n      sources, rulebook activations, decision environments, and automated response\n      workflows for infrastructure and application events.\n    humanURL: https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/2.4/html/event-driven_ansible_controller_user_guide/\n    baseURL: https://eda-host/api/eda/v1/\n    tags:\n      - EDA\n      - Event-Driven\n      - REST\n      - Rulebooks\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/2.4/html/event-driven_ansible_controller_user_guide/\n  - aid: red-hat-ansible-automation-platform:services-catalog-api\n    name: Red Hat Automation Services Catalog API\n    description: >-\n      REST API for the Automation Services Catalog providing a self-service portal\n      where users can order and manage pre-approved automation services with\n      governance controls and approval workflows.\n    humanURL: https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/\n\
  \    baseURL: https://catalog-host/api/v1/\n    tags:\n      - Catalog\n      - Governance\n      - REST\n      - Self-Service\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/\ncommon:\n  - type: Portal\n    url: https://www.redhat.com/en/technologies/management/ansible\n  - type: Documentation\n    url: https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/\n  - type: GettingStarted\n    url: https://www.redhat.com/en/technologies/management/ansible/trial\n  - type: Blog\n    url: https://www.ansible.com/blog\n  - type: GitHubOrganization\n    url: https://github.com/ansible\n  - type: Support\n    url: https://access.redhat.com/support/\n  - type: TermsOfService\n    url: https://www.redhat.com/en/about/agreements\n  - type: PrivacyPolicy\n    url: https://www.redhat.com/en/about/privacy-policy\n  - type: Training\n    url: https://www.redhat.com/en/services/training/do007-ansible-essentials-simplicity-automation-technical-overview\n\
  \  - type: Pricing\n    url: https://www.redhat.com/en/technologies/management/ansible/pricing\n  - type: StatusPage\n    url: https://status.redhat.com/\n  - type: Features\n    data:\n      - name: Enterprise Automation Controller\n        description: Centralized management of automation with RBAC, audit logging, and credential management.\n      - name: Private Automation Hub\n        description: Curate and distribute certified and custom Ansible content collections within the enterprise.\n      - name: Event-Driven Automation\n        description: Automated response to infrastructure events using rulebook activations and event sources.\n      - name: Ansible Lightspeed\n        description: AI-powered automation content generation with IBM watsonx Code Assistant.\n      - name: Execution Environments\n        description: Containerized automation runtime environments for consistent and portable execution.\n      - name: Automation Mesh\n        description: Distributed automation\
  \ execution architecture for scaling across global infrastructure.\n  - type: UseCases\n    data:\n      - name: Enterprise IT Automation\n        description: Standardize and scale IT automation across the enterprise with governance and compliance controls.\n      - name: Hybrid Cloud Management\n        description: Automate infrastructure provisioning and management across on-premises and multi-cloud environments.\n      - name: Security Automation\n        description: Automated security response and compliance enforcement with event-driven remediation.\n      - name: Edge Computing\n        description: Manage and automate edge infrastructure at scale with automation mesh and execution environments.\n      - name: Self-Service IT\n        description: Enable self-service automation ordering through the services catalog with approval workflows.\n  - type: Integrations\n    data:\n      - name: Red Hat OpenShift\n        description: Container platform integration for deploying and\
  \ managing Ansible on Kubernetes.\n      - name: Red Hat Satellite\n        description: Content management and patching integration for RHEL infrastructure automation.\n      - name: ServiceNow\n        description: ITSM integration for change management and incident remediation workflows.\n      - name: AWS\n        description: Cloud automation for AWS services with certified content collections.\n      - name: Microsoft Azure\n        description: Cloud automation for Azure services with certified content collections.\n      - name: Google Cloud\n        description: Cloud automation for GCP services with certified content collections.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/red-hat-ansible-automation-platform/refs/heads/main/apis.yml
tags:
- Automation
- Configuration Management
- DevOps
- Enterprise
- Red Hat
url: https://raw.githubusercontent.com/api-evangelist/red-hat-ansible-automation-platform/refs/heads/main/apis.yml
use_cases:
- description: Standardize and scale IT automation across the enterprise with governance and compliance controls.
  name: Enterprise IT Automation
- description: Automate infrastructure provisioning and management across on-premises and multi-cloud environments.
  name: Hybrid Cloud Management
- description: Automated security response and compliance enforcement with event-driven remediation.
  name: Security Automation
- description: Manage and automate edge infrastructure at scale with automation mesh and execution environments.
  name: Edge Computing
- description: Enable self-service automation ordering through the services catalog with approval workflows.
  name: Self-Service IT
---
