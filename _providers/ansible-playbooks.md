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
source_filename: apis.yml
source_yaml: "name: Ansible Playbooks\ndescription: >-\n  A curated collection of APIs, tools, and platforms for managing and executing\n  Ansible playbooks for IT automation, configuration management, and\n  orchestration. Covers the Ansible Automation Platform, AWX, Galaxy, Automation\n  Hub, Runner, and Semaphore APIs that power modern infrastructure automation\n  workflows.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/apis.yml\ncreated: \"2024-01-15\"\nmodified: \"2026-04-19\"\nspecificationVersion: '0.16'\ntags:\n  - Ansible\n  - Automation\n  - Configuration Management\n  - DevOps\n  - Infrastructure As Code\n  - Orchestration\n  - Playbooks\napis:\n  - name: Ansible Automation Platform API\n    description: >-\n      REST API for Ansible Automation Platform (formerly Ansible Tower/AWX) to\n      manage playbooks, inventories, credentials, job templates, and\
  \ job\n      execution at enterprise scale. Supports RBAC, workflows, schedules,\n      notifications, and survey prompts. Available as a self-hosted deployment\n      or managed via Red Hat's cloud.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.ansible.com/automation-controller/latest/html/controllerapi/\n    baseURL: https://your-aap-instance/api/v2/\n    tags:\n      - Ansible\n      - Automation\n      - Enterprise\n      - Jobs\n      - Orchestration\n      - Playbooks\n      - Red Hat\n    properties:\n      - type: Documentation\n        url: https://docs.ansible.com/automation-controller/latest/html/controllerapi/\n      - type: APIReference\n        url: https://docs.ansible.com/automation-controller/latest/html/controllerapi/api_ref.html\n      - type: Authentication\n        url: https://docs.ansible.com/automation-controller/latest/html/controllerapi/authentication.html\n      - type: Pricing\n        url:\
  \ https://www.ansible.com/products/pricing\n      - type: GettingStarted\n        url: https://docs.ansible.com/automation-controller/latest/html/quickstart/\n    contact:\n      - FN: Red Hat Ansible Support\n        url: https://access.redhat.com/support\n\n  - name: AWX API\n    description: >-\n      AWX is the open-source upstream project for Ansible Automation Platform,\n      providing a web-based UI, REST API, and task engine for Ansible. The AWX\n      API offers programmatic access to job execution, inventory management,\n      credential storage, workflow templates, and scheduling. Self-hosted and\n      free under the Apache 2.0 license.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/ansible/awx\n    baseURL: https://your-awx-instance/api/v2/\n    tags:\n      - Ansible\n      - Automation\n      - AWX\n      - Open Source\n      - Playbooks\n    properties:\n      - type: Documentation\n        url:\
  \ https://ansible.readthedocs.io/projects/awx/en/latest/\n      - type: APIReference\n        url: https://github.com/ansible/awx/blob/devel/docs/rest_api.md\n      - type: GitHubRepository\n        url: https://github.com/ansible/awx\n      - type: GettingStarted\n        url: https://github.com/ansible/awx/blob/devel/INSTALL.md\n    contact:\n      - FN: AWX Community\n        url: https://github.com/ansible/awx/discussions\n\n  - name: Ansible Runner API\n    description: >-\n      Ansible Runner is a Python library and CLI tool that provides a stable\n      and consistent interface for executing Ansible playbooks programmatically\n      from within other applications and tools. Used by AWX, Automation\n      Platform, and CI/CD pipelines to launch Ansible with structured input and\n      output handling.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://ansible-runner.readthedocs.io/\n    baseURL: https://pypi.org/project/ansible-runner/\n\
  \    tags:\n      - Ansible\n      - Automation\n      - Library\n      - Playbooks\n      - Python\n    properties:\n      - type: Documentation\n        url: https://ansible-runner.readthedocs.io/en/stable/\n      - type: APIReference\n        url: https://ansible-runner.readthedocs.io/en/stable/python_interface.html\n      - type: GitHubRepository\n        url: https://github.com/ansible/ansible-runner\n      - type: SDK\n        url: https://pypi.org/project/ansible-runner/\n    contact:\n      - FN: Ansible Community\n        url: https://github.com/ansible/ansible-runner/issues\n\n  - name: Ansible Galaxy API\n    description: >-\n      Ansible Galaxy is the community hub for sharing Ansible roles and\n      collections. The Galaxy REST API enables searching, downloading, and\n      publishing Ansible content. Supports v1 (roles), v2 (mixed), and v3\n      (collections) API versions with namespace management, search, versioning,\n      and download statistics.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://galaxy.ansible.com\n    baseURL: https://galaxy.ansible.com/api/\n    tags:\n      - Ansible\n      - Collections\n      - Community\n      - Galaxy\n      - Roles\n    properties:\n      - type: Documentation\n        url: https://galaxy.ansible.com/docs/\n      - type: APIReference\n        url: https://galaxy.ansible.com/api/v3/\n      - type: GettingStarted\n        url: https://docs.ansible.com/ansible/latest/galaxy/user_guide.html\n    contact:\n      - FN: Ansible Galaxy Team\n        url: https://github.com/ansible/galaxy/issues\n\n  - name: Ansible Automation Hub API\n    description: >-\n      Red Hat Ansible Automation Hub is the enterprise content hub for certified\n      Ansible collections, roles, and execution environments. The API provides\n      access to Red Hat certified and partner-validated Ansible content for\n      use in production Ansible Automation Platform deployments.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://console.redhat.com/ansible/automation-hub\n    baseURL: https://console.redhat.com/api/automation-hub/\n    tags:\n      - Ansible\n      - Certified Content\n      - Collections\n      - Enterprise\n      - Red Hat\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/\n      - type: APIReference\n        url: https://console.redhat.com/api/automation-hub/v3/\n      - type: Portal\n        url: https://console.redhat.com/ansible/automation-hub\n    contact:\n      - FN: Red Hat Support\n        url: https://access.redhat.com/support\n\n  - name: Ansible Semaphore API\n    description: >-\n      Ansible Semaphore is an open-source modern web UI and REST API for\n      running Ansible playbooks. It provides project management, task\n      scheduling, access control, and a clean interface for teams using Ansible\n      without the complexity of Automation Platform. The REST API\
  \ supports\n      full task and project management.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.ansible-semaphore.com/\n    baseURL: https://your-semaphore-instance/api/\n    tags:\n      - Ansible\n      - Open Source\n      - Playbooks\n      - Semaphore\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://docs.ansible-semaphore.com/\n      - type: APIReference\n        url: https://docs.ansible-semaphore.com/api-reference\n      - type: GitHubRepository\n        url: https://github.com/ansible-semaphore/semaphore\n    contact:\n      - FN: Semaphore Community\n        url: https://github.com/ansible-semaphore/semaphore/issues\n\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n    X: apievangelist\n    url: https://apievangelist.com\ncommon:\n  - type: GettingStarted\n    url: https://docs.ansible.com/ansible/latest/getting_started/\n  - type: BestPractices\n    url:\
  \ https://docs.ansible.com/ansible/latest/tips_tricks/ansible_tips_tricks.html\n  - type: Blog\n    url: https://www.ansible.com/blog\n  - type: TermsOfService\n    url: https://www.redhat.com/en/about/terms-use\n  - type: PrivacyPolicy\n    url: https://www.redhat.com/en/about/privacy-policy\n  - type: GitHubOrganization\n    url: https://github.com/ansible\n  - type: Forum\n    url: https://forum.ansible.com/\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/json-schema/ansible-playbooks-playbook-job-schema.json\n    title: Playbook Job Schema\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/json-schema/ansible-playbooks-inventory-schema.json\n    title: Inventory Schema\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/vocabulary/ansible-playbooks-vocabulary.yaml\n  - type: Features\n    data:\n\
  \      - name: Playbook Execution via API\n        description: >-\n          Launch, monitor, and cancel Ansible playbook runs programmatically\n          via REST API with support for extra vars, limits, and tags.\n      - name: Inventory Management\n        description: >-\n          Create and manage dynamic and static inventories with groups,\n          hosts, and host variables through the API.\n      - name: Credential Storage\n        description: >-\n          Securely store SSH keys, cloud credentials, and vault passwords\n          in encrypted credential objects accessible to jobs.\n      - name: Workflow Templates\n        description: >-\n          Chain multiple job templates into orchestrated workflows with\n          conditional success/failure branching.\n      - name: Scheduling\n        description: >-\n          Schedule playbook runs on recurring schedules using rrule-based\n          calendar expressions.\n      - name: Collections and Role Management\n        description:\
  \ >-\n          Discover, download, and manage Ansible collections and roles from\n          Galaxy, Automation Hub, or private repositories.\n  - type: UseCases\n    data:\n      - name: Infrastructure Provisioning\n        description: >-\n          Automate the provisioning of cloud resources, VMs, and\n          bare-metal servers using Ansible playbooks triggered via API.\n      - name: Configuration Management\n        description: >-\n          Enforce consistent configuration state across server fleets by\n          scheduling and executing configuration playbooks via API.\n      - name: CI/CD Pipeline Integration\n        description: >-\n          Trigger Ansible playbook runs as deployment steps within Jenkins,\n          GitLab CI, GitHub Actions, and other CI/CD platforms.\n      - name: Compliance and Remediation\n        description: >-\n          Run compliance playbooks on demand or on schedule to detect and\n          remediate drift from desired security baseline states.\n\
  \      - name: Network Automation\n        description: >-\n          Automate network device configuration, firmware upgrades, and\n          compliance checks using Ansible network collections via the API.\n  - type: Integrations\n    data:\n      - name: Red Hat OpenShift\n        description: >-\n          Deploy and configure OpenShift clusters and workloads using\n          Ansible Automation Platform integrated with OpenShift pipelines.\n      - name: ServiceNow\n        description: >-\n          Trigger Ansible job templates from ServiceNow ITSM workflows for\n          automated ticket remediation and change management.\n      - name: GitHub Actions\n        description: >-\n          Use the Ansible Automation Platform GitHub Action to trigger\n          playbook runs as part of GitHub CI/CD workflows.\n      - name: Terraform\n        description: >-\n          Combine Terraform for infrastructure provisioning with Ansible\n          for post-provisioning configuration management.\n\
  \      - name: Splunk\n        description: >-\n          Use Ansible collections to configure Splunk deployments and\n          automate security alert remediation workflows.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/apis.yml
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
