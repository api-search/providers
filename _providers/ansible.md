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
source_filename: apis.yml
source_yaml: "name: Ansible\ndescription: >-\n  Ansible is an open-source IT automation platform developed by Red Hat that\n  provides agentless configuration management, application deployment, cloud\n  provisioning, and orchestration. Using YAML-based playbooks and an\n  SSH-native architecture, Ansible automates infrastructure at scale without\n  requiring agents or custom security infrastructure on managed nodes.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Ansible\n  - Automation\n  - Configuration Management\n  - DevOps\n  - Infrastructure As Code\n  - Open Source\n  - Orchestration\n  - Red Hat\ncreated: \"2024-01-01\"\nmodified: \"2026-04-19\"\nurl: https://raw.githubusercontent.com/api-evangelist/ansible/refs/heads/main/apis.yml\nspecificationVersion: '0.16'\napis:\n  - name: Ansible Automation Platform API\n    description: >-\n      RESTful API for Ansible Automation Platform (formerly Ansible Tower) that\n      provides programmatic\
  \ access to job templates, inventories, credentials,\n      workflow templates, schedules, notifications, and job execution. Supports\n      OAuth2 authentication and delivers a comprehensive management interface\n      for enterprise-scale Ansible deployments.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.ansible.com/automation-controller/latest/html/controllerapi/\n    baseURL: https://your-controller-host/api/v2/\n    tags:\n      - Ansible\n      - Automation\n      - Enterprise\n      - Inventories\n      - Jobs\n      - Red Hat\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://docs.ansible.com/automation-controller/latest/html/controllerapi/\n      - type: APIReference\n        url: https://docs.ansible.com/automation-controller/latest/html/controllerapi/api_ref.html\n      - type: Authentication\n        url: https://docs.ansible.com/automation-controller/latest/html/controllerapi/authentication.html\n\
  \      - type: GettingStarted\n        url: https://docs.ansible.com/automation-controller/latest/html/quickstart/\n    contact:\n      - FN: Ansible Support\n        url: https://access.redhat.com/support\n\n  - name: AWX API\n    description: >-\n      AWX is the open-source upstream project for Ansible Automation Platform,\n      providing a web-based UI, REST API, and task engine for Ansible under the\n      Apache 2.0 license. The AWX API mirrors the AAP API surface for job\n      management, inventory, credentials, workflow templates, and scheduling.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/ansible/awx\n    baseURL: https://your-awx-host/api/v2/\n    tags:\n      - Ansible\n      - Automation\n      - AWX\n      - Jobs\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://ansible.readthedocs.io/projects/awx/en/latest/\n      - type: APIReference\n        url: https://github.com/ansible/awx/blob/devel/docs/rest_api.md\n\
  \      - type: GitHubRepository\n        url: https://github.com/ansible/awx\n      - type: GettingStarted\n        url: https://github.com/ansible/awx/blob/devel/INSTALL.md\n    contact:\n      - FN: AWX Community\n        url: https://github.com/ansible/awx/discussions\n\n  - name: Ansible Galaxy API\n    description: >-\n      REST API for Ansible Galaxy — the community hub for sharing and\n      downloading Ansible roles and collections. The v1 API covers roles and\n      the v3 API covers collections with namespace management, versioning,\n      search, and content download capabilities.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://galaxy.ansible.com/\n    baseURL: https://galaxy.ansible.com/api/\n    tags:\n      - Ansible\n      - Collections\n      - Community\n      - Galaxy\n      - Roles\n    properties:\n      - type: Documentation\n        url: https://galaxy.ansible.com/docs/\n      - type: APIReference\n  \
  \      url: https://galaxy.ansible.com/api/v3/\n      - type: GitHubRepository\n        url: https://github.com/ansible/galaxy\n    contact:\n      - FN: Ansible Galaxy Team\n        url: https://github.com/ansible/galaxy/issues\n\n  - name: Ansible Automation Hub API\n    description: >-\n      The Red Hat Ansible Automation Hub API provides access to certified\n      Ansible collections and roles curated by Red Hat and partners. Available\n      through console.redhat.com, it serves certified content for enterprise\n      Ansible Automation Platform deployments.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://console.redhat.com/ansible/automation-hub\n    baseURL: https://console.redhat.com/api/automation-hub/v3/\n    tags:\n      - Ansible\n      - Certified Content\n      - Collections\n      - Enterprise\n      - Red Hat\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/\n\
  \      - type: APIReference\n        url: https://console.redhat.com/api/automation-hub/v3/\n      - type: Portal\n        url: https://console.redhat.com/ansible/automation-hub\n    contact:\n      - FN: Red Hat Support\n        url: https://access.redhat.com/support\n\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n    X: apievangelist\n    url: https://apievangelist.com\ncommon:\n  - type: Portal\n    url: https://www.ansible.com\n  - type: GettingStarted\n    url: https://docs.ansible.com/ansible/latest/getting_started/\n  - type: Documentation\n    url: https://docs.ansible.com/\n  - type: Blog\n    url: https://www.ansible.com/blog\n  - type: GitHubOrganization\n    url: https://github.com/ansible\n  - type: Forum\n    url: https://forum.ansible.com/\n  - type: Support\n    url: https://access.redhat.com/products/red-hat-ansible-automation-platform/\n  - type: Training\n    url: https://www.ansible.com/products/training-certification\n  - type: TermsOfService\n\
  \    url: https://www.redhat.com/en/about/terms-use\n  - type: PrivacyPolicy\n    url: https://www.redhat.com/en/about/privacy-policy\n  - type: SDK\n    url: https://pypi.org/project/ansible/\n    title: Ansible Python Package\n  - type: SDK\n    url: https://pypi.org/project/ansible-runner/\n    title: Ansible Runner Python Package\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/ansible/refs/heads/main/json-schema/ansible-playbook-schema.json\n    title: Playbook Schema\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/ansible/refs/heads/main/vocabulary/ansible-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Agentless Architecture\n        description: >-\n          Ansible connects to managed nodes via SSH or WinRM without requiring\n          any agent software, simplifying deployment and reducing attack surface.\n      - name: YAML Playbooks\n        description: >-\n          Automation is defined in human-readable\
  \ YAML playbooks that describe\n          the desired state of managed systems without complex programming.\n      - name: Idempotent Execution\n        description: >-\n          Ansible tasks are idempotent — running the same playbook multiple\n          times produces the same result, making deployments safe to rerun.\n      - name: Module Ecosystem\n        description: >-\n          Over 3,000 built-in modules covering cloud providers, network\n          devices, databases, containers, storage, and operating system tasks.\n      - name: Collection System\n        description: >-\n          The Ansible Collections packaging format bundles related modules,\n          roles, plugins, and documentation for modular content distribution.\n      - name: Dynamic Inventory\n        description: >-\n          Query cloud providers, CMDBs, and external systems dynamically to\n          build host inventories at execution time rather than static files.\n  - type: UseCases\n    data:\n      -\
  \ name: Configuration Management\n        description: >-\n          Ensure servers and services remain in a consistent desired state\n          by applying configuration playbooks across fleets of hosts.\n      - name: Application Deployment\n        description: >-\n          Deploy and update applications across development, staging, and\n          production environments with zero-downtime rolling strategies.\n      - name: Cloud Provisioning\n        description: >-\n          Provision cloud resources on AWS, Azure, GCP, and other providers\n          using cloud-specific Ansible modules and dynamic inventory.\n      - name: Network Automation\n        description: >-\n          Configure routers, switches, and firewalls from Cisco, Juniper,\n          Arista, and Palo Alto using vendor-specific Ansible collections.\n      - name: Security and Compliance\n        description: >-\n          Enforce security baselines, CIS benchmarks, and STIG compliance\n          across infrastructure\
  \ using Ansible hardening playbooks.\n  - type: Integrations\n    data:\n      - name: Red Hat Enterprise Linux\n        description: >-\n          Ansible is the primary configuration management tool for Red Hat\n          Enterprise Linux systems with deep integration into the RHEL platform.\n      - name: Kubernetes / OpenShift\n        description: >-\n          Manage Kubernetes clusters, namespaces, deployments, and OpenShift\n          workloads using the kubernetes.core collection.\n      - name: Terraform\n        description: >-\n          Combine Terraform for cloud resource provisioning with Ansible for\n          post-provisioning OS and application configuration.\n      - name: Jenkins / GitHub Actions\n        description: >-\n          Integrate Ansible playbook execution into CI/CD pipelines using\n          the AAP Action for GitHub or Ansible Tower Plugin for Jenkins.\n      - name: ServiceNow\n        description: >-\n          Trigger Ansible automation from ServiceNow\
  \ ITSM workflows using\n          the ServiceNow ITX collection for change management automation.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ansible/refs/heads/main/apis.yml
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
