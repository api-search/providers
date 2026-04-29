---
api_count: 5
apis:
- description: The main REST API for Red Hat Satellite 6.x, providing programmatic access to all Satellite functions including host management, content management, provisioning, and configuration.
  name: Red Hat Satellite REST API
  slug: ''
- description: Command-line interface tool for Red Hat Satellite that provides scriptable access to Satellite functions including host management, content views, and provisioning.
  name: Red Hat Satellite Hammer CLI
  slug: ''
- description: Core Foreman API integrated into Red Hat Satellite for host lifecycle management, provisioning, and configuration management. This is the upstream project API that powers Satellite's core functionalit
  name: Red Hat Satellite Foreman API
  slug: ''
- description: Content management API for Red Hat Satellite handling repositories, content views, lifecycle environments, subscriptions, and errata. Katello is the upstream plugin that provides Satellite's content a
  name: Red Hat Satellite Katello API
  slug: ''
- description: The redhat.satellite Ansible collection provides modules, roles, and plugins for automating Red Hat Satellite configuration and management through the Satellite API. Based on the theforeman.foreman co
  name: Red Hat Satellite Ansible Collection
  slug: ''
capabilities:
- description: Unified workflow for managing the complete lifecycle of physical, virtual, and cloud hosts including provisioning, content management, patching, and subscription management. Used by system administrat
  name: Red Hat Satellite Systems Lifecycle Management
  slug: systems-lifecycle-management
common:
- title: ''
  type: Portal
  url: https://access.redhat.com/
- title: ''
  type: Documentation
  url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.16
- title: ''
  type: Support
  url: https://access.redhat.com/support/
- title: ''
  type: StatusPage
  url: https://status.redhat.com/
- title: ''
  type: Blog
  url: https://www.redhat.com/en/blog/channel/red-hat-satellite
- title: ''
  type: GitHubOrganization
  url: https://github.com/theforeman
- title: ''
  type: KnowledgeCenter
  url: https://access.redhat.com/solutions/
- title: Community
  type: Support
  url: https://access.redhat.com/community/
- title: Foreman Community
  type: Support
  url: https://community.theforeman.org/
- title: ''
  type: ReleaseNotes
  url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.18/html-single/release_notes/index
- title: Product Lifecycle
  type: Documentation
  url: https://access.redhat.com/support/policy/updates/satellite
- title: Release Dates
  type: Documentation
  url: https://access.redhat.com/articles/1365633
- title: Provisioning Guide
  type: Documentation
  url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html/provisioning_hosts/index
- title: Managing Hosts Guide
  type: Documentation
  url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/managing_content/index
- title: ''
  type: APIReference
  url: https://apidocs.theforeman.org/
- title: Hammer CLI
  type: CLI
  url: https://github.com/theforeman/hammer-cli-foreman
- title: Ansible Modules
  type: GitHubRepository
  url: https://github.com/theforeman/foreman-ansible-modules
- title: ''
  type: SpectralRules
  url: rules/red-hat-satellite-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/red-hat-satellite-vocabulary.yaml
- title: Satellite API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/satellite-api.yaml
- title: Systems Lifecycle Management Workflow
  type: NaftikoCapability
  url: capabilities/systems-lifecycle-management.yaml
created: '2024-01-01'
description: Red Hat Satellite is a systems management product that helps deploy, configure, and maintain systems across physical, virtual, and cloud environments.
features:
- description: Manage physical, virtual, and cloud hosts across the entire lifecycle from provisioning to decommissioning.
  name: Host Management
- description: Curate and distribute RPM packages, errata, and container images through content views and lifecycle environments.
  name: Content Management
- description: Apply security patches and errata across managed systems with controlled rollouts through lifecycle stages.
  name: Patch Management
- description: Track and manage Red Hat subscriptions and entitlements across organizations and hosts.
  name: Subscription Management
- description: Automate bare-metal and virtual machine provisioning with kickstart templates, PXE boot, and compute resources.
  name: Provisioning
- description: Enforce desired-state configuration using Puppet classes and Ansible roles across managed hosts.
  name: Configuration Management
- description: Organize hosts, content, and subscriptions into isolated organizations and locations.
  name: Multi-Tenancy
image: https://www.redhat.com/profiles/rh/themes/redhatdotcom/img/logo.png
integrations:
- description: Automate Satellite operations and host configuration using the redhat.satellite Ansible collection.
  name: Ansible
- description: Proactive risk analysis and remediation recommendations for managed hosts.
  name: Red Hat Insights
- description: Apply and enforce configuration management policies using Puppet modules and classes.
  name: Puppet
- description: Security compliance scanning and reporting using SCAP content and policies.
  name: OpenSCAP
- description: Provision and manage virtual machines on VMware infrastructure as compute resources.
  name: VMware vSphere
- description: Provision and manage instances on OpenStack as compute resources.
  name: Red Hat OpenStack
- description: Provision and manage cloud instances on AWS as compute resources.
  name: Amazon EC2
- description: Provision and manage cloud instances on Google Cloud as compute resources.
  name: Google GCE
jsonld:
- class_count: 0
  name: Red Hat Satellite Context
  property_count: 0
  slug: red-hat-satellite-context
layout: provider
modified: '2026-04-18'
name: Red Hat Satellite
rules:
- name: Red Hat Satellite API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: red-hat-satellite-spectral-rules
skills: []
slug: red-hat-satellite
solutions: []
source_yaml: "aid: red-hat-satellite\nname: Red Hat Satellite\ndescription: Red Hat Satellite is a systems management product that helps deploy, configure, and maintain systems across physical, virtual, and cloud environments.\ntype: Index\nimage: https://www.redhat.com/profiles/rh/themes/redhatdotcom/img/logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/red-hat-satellite/refs/heads/main/apis.yml\ntags:\n  - Configuration Management\n  - Lifecycle Management\n  - Patch Management\n  - Subscription Management\n  - Systems Management\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - name: Red Hat Satellite REST API\n    description: The main REST API for Red Hat Satellite 6.x, providing programmatic access to all Satellite functions including host management, content management, provisioning, and configuration.\n    image: https://www.redhat.com/profiles/rh/themes/redhatdotcom/img/logo.png\n    baseURL: https://satellite.example.com/api/v2\n\
  \    humanURL: https://access.redhat.com/documentation/en-us/red_hat_satellite/\n    tags:\n      - Automation\n      - REST API\n      - Systems Management\n    properties:\n      - type: Documentation\n        url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/using_the_satellite_rest_api/index\n      - type: OpenAPI\n        url: https://satellite.example.com/apidoc/v2.json\n      - type: OpenAPI\n        url: openapi/red-hat-satellite-api.yml\n      - type: JSONSchema\n        url: json-schema/red-hat-satellite-host-schema.json\n      - type: JSONSchema\n        url: json-schema/red-hat-satellite-host-create-schema.json\n      - type: JSONSchema\n        url: json-schema/red-hat-satellite-host-update-schema.json\n      - type: JSONSchema\n        url: json-schema/red-hat-satellite-host-interface-schema.json\n      - type: JSONSchema\n        url: json-schema/red-hat-satellite-host-interface-create-schema.json\n      - type: JSONSchema\n        url: json-schema/red-hat-satellite-content-view-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/red-hat-satellite-content-view-create-schema.json\n      - type: JSONSchema\n        url: json-schema/red-hat-satellite-content-view-update-schema.json\n      - type: JSONSchema\n        url: json-schema/red-hat-satellite-subscription-schema.json\n      - type: JSONSchema\n        url: json-schema/red-hat-satellite-lifecycle-environment-schema.json\n      - type: JSONSchema\n        url: json-schema/red-hat-satellite-organization-schema.json\n      - type: JSONSchema\n        url: json-schema/red-hat-satellite-foreman-task-schema.json\n      - type: JSONStructure\n        url: json-structure/red-hat-satellite-host-structure.json\n      - type: JSONStructure\n        url: json-structure/red-hat-satellite-host-create-structure.json\n      - type: JSONStructure\n        url: json-structure/red-hat-satellite-host-update-structure.json\n      - type: JSONStructure\n        url: json-structure/red-hat-satellite-host-interface-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/red-hat-satellite-host-interface-create-structure.json\n      - type: JSONStructure\n        url: json-structure/red-hat-satellite-content-view-structure.json\n      - type: JSONStructure\n        url: json-structure/red-hat-satellite-content-view-create-structure.json\n      - type: JSONStructure\n        url: json-structure/red-hat-satellite-content-view-update-structure.json\n      - type: JSONStructure\n        url: json-structure/red-hat-satellite-subscription-structure.json\n      - type: JSONStructure\n        url: json-structure/red-hat-satellite-lifecycle-environment-structure.json\n      - type: JSONStructure\n        url: json-structure/red-hat-satellite-organization-structure.json\n      - type: JSONStructure\n        url: json-structure/red-hat-satellite-foreman-task-structure.json\n      - type: Example\n        url: examples/red-hat-satellite-host-example.json\n      - type: Example\n        url: examples/red-hat-satellite-host-create-example.json\n\
  \      - type: Example\n        url: examples/red-hat-satellite-host-update-example.json\n      - type: Example\n        url: examples/red-hat-satellite-host-interface-example.json\n      - type: Example\n        url: examples/red-hat-satellite-host-interface-create-example.json\n      - type: Example\n        url: examples/red-hat-satellite-content-view-example.json\n      - type: Example\n        url: examples/red-hat-satellite-content-view-create-example.json\n      - type: Example\n        url: examples/red-hat-satellite-content-view-update-example.json\n      - type: Example\n        url: examples/red-hat-satellite-subscription-example.json\n      - type: Example\n        url: examples/red-hat-satellite-lifecycle-environment-example.json\n      - type: Example\n        url: examples/red-hat-satellite-organization-example.json\n      - type: Example\n        url: examples/red-hat-satellite-foreman-task-example.json\n      - type: JSONLD\n        url: json-ld/red-hat-satellite-context.jsonld\n\
  \      - type: Authentication\n        url: https://access.redhat.com/documentation/en-us/red_hat_satellite/6.14/html/api_guide/chap-api_guide-authentication\n      - type: GettingStarted\n        url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.18/html/using_the_satellite_rest_api/introduction-to-satellite-api\n      - type: APIReference\n        url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.18/html/using_the_satellite_rest_api/index\n    contact:\n      - type: Support\n        url: https://access.redhat.com/support\n  - name: Red Hat Satellite Hammer CLI\n    description: Command-line interface tool for Red Hat Satellite that provides scriptable access to Satellite functions including host management, content views, and provisioning.\n    image: https://www.redhat.com/profiles/rh/themes/redhatdotcom/img/logo.png\n    humanURL: https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/using_the_hammer_cli_tool/index\n    tags:\n\
  \      - Automation\n      - CLI\n      - Command Line\n    properties:\n      - type: Documentation\n        url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/using_the_hammer_cli_tool/index\n      - type: CodeExamples\n        url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html/using_the_hammer_cli_tool/hammer-cheat-sheet\n      - type: Authentication\n        url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html/using_the_hammer_cli_tool/hammer-authentication\n    contact:\n      - type: Support\n        url: https://access.redhat.com/support\n  - name: Red Hat Satellite Foreman API\n    description: Core Foreman API integrated into Red Hat Satellite for host lifecycle management, provisioning, and configuration management. This is the upstream project API that powers Satellite's core functionality including the web UI, users, organizations, and security.\n    image: https://www.redhat.com/profiles/rh/themes/redhatdotcom/img/logo.png\n\
  \    baseURL: https://satellite.example.com/api\n    humanURL: https://theforeman.org/api.html\n    tags:\n      - Foreman\n      - Host Management\n      - Provisioning\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://apidocs.theforeman.org/\n      - type: APIReference\n        url: https://apidocs.theforeman.org/foreman/latest/apidoc/v2.html\n      - type: GitHubOrganization\n        url: https://github.com/theforeman\n      - type: GitHubRepository\n        url: https://github.com/theforeman/foreman\n      - type: GitHubRepository\n        url: https://github.com/theforeman/apidocs\n        title: API Docs Repository\n    contact:\n      - type: Support\n        url: https://access.redhat.com/support\n      - type: Support\n        url: https://community.theforeman.org/\n  - name: Red Hat Satellite Katello API\n    description: Content management API for Red Hat Satellite handling repositories, content views, lifecycle environments, subscriptions,\
  \ and errata. Katello is the upstream plugin that provides Satellite's content and subscription management capabilities.\n    image: https://www.redhat.com/profiles/rh/themes/redhatdotcom/img/logo.png\n    baseURL: https://satellite.example.com/katello/api\n    humanURL: https://theforeman.org/plugins/katello/\n    tags:\n      - Content Management\n      - Lifecycle Environments\n      - Repositories\n      - REST API\n      - Subscriptions\n    properties:\n      - type: Documentation\n        url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/using_the_satellite_rest_api/index\n      - type: APIReference\n        url: https://apidocs.theforeman.org/katello/latest/apidoc/v2.html\n      - type: Documentation\n        url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/managing_content/index\n        title: Content Management Guide\n      - type: GitHubRepository\n        url: https://github.com/Katello/katello\n      - type: GitHubOrganization\n\
  \        url: https://github.com/Katello\n    contact:\n      - type: Support\n        url: https://access.redhat.com/support\n  - name: Red Hat Satellite Ansible Collection\n    description: The redhat.satellite Ansible collection provides modules, roles, and plugins for automating Red Hat Satellite configuration and management through the Satellite API. Based on the theforeman.foreman community collection.\n    image: https://www.redhat.com/profiles/rh/themes/redhatdotcom/img/logo.png\n    humanURL: https://catalog.redhat.com/en/software/collection/redhat/satellite\n    tags:\n      - Ansible\n      - Automation\n      - Configuration Management\n      - Infrastructure as Code\n    properties:\n      - type: Documentation\n        url: https://redhatsatellite.github.io/satellite-ansible-collection/develop/README.html\n      - type: GitHubRepository\n        url: https://github.com/RedHatSatellite/satellite-ansible-collection\n      - type: Marketplace\n        url: https://catalog.redhat.com/en/software/collection/redhat/satellite\n\
  \      - type: GitHubRepository\n        url: https://github.com/theforeman/foreman-ansible-modules\n        title: Community Upstream\n      - type: Blog\n        url: https://www.redhat.com/en/blog/automating-red-hat-satellite-with-ansible\n    contact:\n      - type: Support\n        url: https://access.redhat.com/support\ncommon:\n  - type: Portal\n    url: https://access.redhat.com/\n  - type: Documentation\n    url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.16\n  - type: Support\n    url: https://access.redhat.com/support/\n  - type: StatusPage\n    url: https://status.redhat.com/\n  - type: Blog\n    url: https://www.redhat.com/en/blog/channel/red-hat-satellite\n  - type: GitHubOrganization\n    url: https://github.com/theforeman\n  - type: KnowledgeCenter\n    url: https://access.redhat.com/solutions/\n  - type: Support\n    url: https://access.redhat.com/community/\n    title: Community\n  - type: Support\n    url: https://community.theforeman.org/\n    title:\
  \ Foreman Community\n  - type: ReleaseNotes\n    url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.18/html-single/release_notes/index\n  - type: Documentation\n    url: https://access.redhat.com/support/policy/updates/satellite\n    title: Product Lifecycle\n  - type: Documentation\n    url: https://access.redhat.com/articles/1365633\n    title: Release Dates\n  - type: Documentation\n    url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html/provisioning_hosts/index\n    title: Provisioning Guide\n  - type: Documentation\n    url: https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/managing_content/index\n    title: Managing Hosts Guide\n  - type: APIReference\n    url: https://apidocs.theforeman.org/\n  - type: CLI\n    url: https://github.com/theforeman/hammer-cli-foreman\n    title: Hammer CLI\n  - type: GitHubRepository\n    url: https://github.com/theforeman/foreman-ansible-modules\n    title: Ansible Modules\n  - type: SpectralRules\n\
  \    url: rules/red-hat-satellite-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/red-hat-satellite-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/shared/satellite-api.yaml\n    title: Satellite API Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/systems-lifecycle-management.yaml\n    title: Systems Lifecycle Management Workflow\n  - type: Features\n    data:\n      - name: Host Management\n        description: Manage physical, virtual, and cloud hosts across the entire lifecycle from provisioning to decommissioning.\n      - name: Content Management\n        description: Curate and distribute RPM packages, errata, and container images through content views and lifecycle environments.\n      - name: Patch Management\n        description: Apply security patches and errata across managed systems with controlled rollouts through lifecycle stages.\n      - name: Subscription Management\n        description: Track and manage Red Hat subscriptions\
  \ and entitlements across organizations and hosts.\n      - name: Provisioning\n        description: Automate bare-metal and virtual machine provisioning with kickstart templates, PXE boot, and compute resources.\n      - name: Configuration Management\n        description: Enforce desired-state configuration using Puppet classes and Ansible roles across managed hosts.\n      - name: Multi-Tenancy\n        description: Organize hosts, content, and subscriptions into isolated organizations and locations.\n  - type: UseCases\n    data:\n      - name: Automated Server Provisioning\n        description: Provision new servers automatically using compute resources, host groups, and kickstart templates.\n      - name: Security Patching at Scale\n        description: Identify, test, and deploy security errata across thousands of hosts using content views and promotion workflows.\n      - name: Hybrid Cloud Management\n        description: Manage hosts across on-premises data centers and cloud\
  \ providers from a single console.\n      - name: Compliance Reporting\n        description: Generate compliance reports using OpenSCAP integration to verify hosts meet security baselines.\n      - name: Air-Gapped Environment Management\n        description: Manage systems in disconnected environments using content synchronization and inter-satellite sync.\n  - type: Integrations\n    data:\n      - name: Ansible\n        description: Automate Satellite operations and host configuration using the redhat.satellite Ansible collection.\n      - name: Red Hat Insights\n        description: Proactive risk analysis and remediation recommendations for managed hosts.\n      - name: Puppet\n        description: Apply and enforce configuration management policies using Puppet modules and classes.\n      - name: OpenSCAP\n        description: Security compliance scanning and reporting using SCAP content and policies.\n      - name: VMware vSphere\n        description: Provision and manage virtual\
  \ machines on VMware infrastructure as compute resources.\n      - name: Red Hat OpenStack\n        description: Provision and manage instances on OpenStack as compute resources.\n      - name: Amazon EC2\n        description: Provision and manage cloud instances on AWS as compute resources.\n      - name: Google GCE\n        description: Provision and manage cloud instances on Google Cloud as compute resources.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/red-hat-satellite/refs/heads/main/apis.yml
tags:
- Configuration Management
- Lifecycle Management
- Patch Management
- Subscription Management
- Systems Management
url: https://raw.githubusercontent.com/api-evangelist/red-hat-satellite/refs/heads/main/apis.yml
use_cases:
- description: Provision new servers automatically using compute resources, host groups, and kickstart templates.
  name: Automated Server Provisioning
- description: Identify, test, and deploy security errata across thousands of hosts using content views and promotion workflows.
  name: Security Patching at Scale
- description: Manage hosts across on-premises data centers and cloud providers from a single console.
  name: Hybrid Cloud Management
- description: Generate compliance reports using OpenSCAP integration to verify hosts meet security baselines.
  name: Compliance Reporting
- description: Manage systems in disconnected environments using content synchronization and inter-satellite sync.
  name: Air-Gapped Environment Management
---
