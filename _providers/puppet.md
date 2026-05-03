---
api_count: 9
apis:
- description: The Orchestrator API enables you to gather details about orchestrator jobs you run and inspect application instances. It powers running tasks and orchestration workflows across PE-managed nodes.
  name: Puppet Enterprise Orchestrator API
  slug: orchestrator
- description: The RBAC Service API manages access to PE, generates authentication tokens, and provides user, role, group, and permission management. v2 adds user retrieval with filters, token revocation, and LDAP a
  name: Puppet Enterprise RBAC Service API
  slug: rbac
- description: The Node Classifier API enables querying node group matches, assigned classes and parameters, and environment assignments. Used to manage how nodes are classified and configured.
  name: Puppet Enterprise Node Classifier Service API
  slug: node-classifier
- description: The Code Manager API supports webhook creation, deployment queueing, and status monitoring for Puppet code, enabling Git-driven control of Puppet environments.
  name: Puppet Enterprise Code Manager API
  slug: code-manager
- description: The Activity Service API queries PE service and user events logged by the activity service, supporting audit and operational visibility.
  name: Puppet Enterprise Activity Service API
  slug: activity
- description: The Status API checks the health status of PE services.
  name: Puppet Enterprise Status API
  slug: status
- description: The Node Inventory API manages inventory service database operations including connection entries and listings.
  name: Puppet Enterprise Node Inventory API
  slug: inventory
- description: The Value API generates automation impact reports on time and cost savings.
  name: Puppet Enterprise Value API
  slug: value
- description: Puppet Forge is the public module repository providing thousands of downloadable Puppet modules.
  name: Puppet Forge
  slug: forge
common:
- title: ''
  type: Website
  url: https://www.puppet.com/
- title: ''
  type: Documentation
  url: https://help.puppet.com/
- title: ''
  type: Blog
  url: https://www.puppet.com/blog
- title: ''
  type: GitHub Organization
  url: https://github.com/puppetlabs
- title: ''
  type: Forge
  url: https://forge.puppet.com/
- title: ''
  type: Status
  url: https://status.puppet.com/
- title: ''
  type: Support
  url: https://support.puppet.com/
- title: ''
  type: Pricing
  url: https://www.puppet.com/pricing
created: '2025-02-24'
description: Puppet provides infrastructure automation and configuration management for hybrid and cloud environments. Puppet Enterprise exposes a collection of service APIs (Orchestrator, RBAC, Node Classifier, Code Manager, Activity, Status, Inventory, Value) that enable programmatic management of nodes, users, classifications, code deployments, and operational events.
features: []
image: https://puppet.com/sites/default/files/2021-09/puppet-logo.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Puppet
skills: []
slug: puppet
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: puppet\nname: Puppet\ndescription: >-\n  Puppet provides infrastructure automation and configuration management for\n  hybrid and cloud environments. Puppet Enterprise exposes a collection of\n  service APIs (Orchestrator, RBAC, Node Classifier, Code Manager, Activity,\n  Status, Inventory, Value) that enable programmatic management of nodes,\n  users, classifications, code deployments, and operational events.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://puppet.com/sites/default/files/2021-09/puppet-logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/puppet/refs/heads/main/apis.yml\ntags:\n  - Automation\n  - Configuration Management\n  - DevOps\n  - Enterprise\n  - Infrastructure as Code\n  - Orchestration\n  - RBAC\ncreated: '2025-02-24'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: puppet:orchestrator\n    name: Puppet Enterprise Orchestrator API\n    description: >-\n      The Orchestrator API enables you\
  \ to gather details about orchestrator\n      jobs you run and inspect application instances. It powers running tasks\n      and orchestration workflows across PE-managed nodes.\n    humanURL: https://help.puppet.com/pe/2025.10/topics/orchestrator_api.htm\n    tags:\n      - Orchestration\n      - Tasks\n    properties:\n      - type: Documentation\n        url: https://help.puppet.com/pe/2025.10/topics/orchestrator_api.htm\n  - aid: puppet:rbac\n    name: Puppet Enterprise RBAC Service API\n    description: >-\n      The RBAC Service API manages access to PE, generates authentication\n      tokens, and provides user, role, group, and permission management.\n      v2 adds user retrieval with filters, token revocation, and LDAP admin.\n    humanURL: https://help.puppet.com/pe/2025.10/topics/rbac_service_api_v1.htm\n    tags:\n      - RBAC\n      - Authentication\n      - Users\n    properties:\n      - type: Documentation\n        url: https://help.puppet.com/pe/2025.10/topics/rbac_service_api_v1.htm\n\
  \      - type: Documentation\n        url: https://help.puppet.com/pe/2025.10/topics/rbac_service_api_v2.htm\n  - aid: puppet:node-classifier\n    name: Puppet Enterprise Node Classifier Service API\n    description: >-\n      The Node Classifier API enables querying node group matches, assigned\n      classes and parameters, and environment assignments. Used to manage how\n      nodes are classified and configured.\n    humanURL: https://help.puppet.com/pe/2025.10/topics/classifier_api.htm\n    tags:\n      - Classification\n      - Nodes\n    properties:\n      - type: Documentation\n        url: https://help.puppet.com/pe/2025.10/topics/classifier_api.htm\n  - aid: puppet:code-manager\n    name: Puppet Enterprise Code Manager API\n    description: >-\n      The Code Manager API supports webhook creation, deployment queueing,\n      and status monitoring for Puppet code, enabling Git-driven control of\n      Puppet environments.\n    humanURL: https://help.puppet.com/pe/2025.10/topics/code_mgr_api.htm\n\
  \    tags:\n      - Code\n      - Deployment\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://help.puppet.com/pe/2025.10/topics/code_mgr_api.htm\n  - aid: puppet:activity\n    name: Puppet Enterprise Activity Service API\n    description: >-\n      The Activity Service API queries PE service and user events logged by\n      the activity service, supporting audit and operational visibility.\n    humanURL: https://help.puppet.com/pe/2025.10/topics/activity_api.htm\n    tags:\n      - Activity\n      - Audit\n    properties:\n      - type: Documentation\n        url: https://help.puppet.com/pe/2025.10/topics/activity_api.htm\n  - aid: puppet:status\n    name: Puppet Enterprise Status API\n    description: >-\n      The Status API checks the health status of PE services.\n    humanURL: https://help.puppet.com/pe/2025.10/topics/status_api.htm\n    tags:\n      - Health\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://help.puppet.com/pe/2025.10/topics/status_api.htm\n\
  \  - aid: puppet:inventory\n    name: Puppet Enterprise Node Inventory API\n    description: >-\n      The Node Inventory API manages inventory service database operations\n      including connection entries and listings.\n    humanURL: https://help.puppet.com/pe/2025.10/topics/inventory_api.htm\n    tags:\n      - Inventory\n      - Nodes\n    properties:\n      - type: Documentation\n        url: https://help.puppet.com/pe/2025.10/topics/inventory_api.htm\n  - aid: puppet:value\n    name: Puppet Enterprise Value API\n    description: >-\n      The Value API generates automation impact reports on time and cost\n      savings.\n    humanURL: https://help.puppet.com/pe/2025.10/topics/value_api.htm\n    tags:\n      - Reports\n      - Analytics\n    properties:\n      - type: Documentation\n        url: https://help.puppet.com/pe/2025.10/topics/value_api.htm\n  - aid: puppet:forge\n    name: Puppet Forge\n    description: >-\n      Puppet Forge is the public module repository providing thousands\
  \ of\n      downloadable Puppet modules.\n    humanURL: https://forge.puppet.com/\n    tags:\n      - Modules\n      - Registry\n    properties:\n      - type: Website\n        url: https://forge.puppet.com/\ncommon:\n  - type: Website\n    url: https://www.puppet.com/\n  - type: Documentation\n    url: https://help.puppet.com/\n  - type: Blog\n    url: https://www.puppet.com/blog\n  - type: GitHub Organization\n    url: https://github.com/puppetlabs\n  - type: Forge\n    url: https://forge.puppet.com/\n  - type: Status\n    url: https://status.puppet.com/\n  - type: Support\n    url: https://support.puppet.com/\n  - type: Pricing\n    url: https://www.puppet.com/pricing\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/puppet/refs/heads/main/apis.yml
tags:
- Automation
- Configuration Management
- DevOps
- Enterprise
- Infrastructure as Code
- Orchestration
- RBAC
url: https://raw.githubusercontent.com/api-evangelist/puppet/refs/heads/main/apis.yml
use_cases: []
---
