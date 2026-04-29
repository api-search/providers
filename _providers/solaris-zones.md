---
api_count: 9
api_specs:
- filename: solaris-zones-management-openapi.yml
  format: yaml
  label: Solaris Zones Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-zones-management-openapi.yml
- filename: solaris-zone-configuration-openapi.yml
  format: yaml
  label: Zone Configuration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-zone-configuration-openapi.yml
- filename: solaris-zone-administration-openapi.yml
  format: yaml
  label: Zone Administration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-zone-administration-openapi.yml
- filename: solaris-zone-monitoring-openapi.yml
  format: yaml
  label: Zone Monitoring API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-zone-monitoring-openapi.yml
- filename: solaris-rad-zonemgr-openapi.yml
  format: yaml
  label: RAD Zone Management REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-rad-zonemgr-openapi.yml
- filename: solaris-zone-stats-openapi.yml
  format: yaml
  label: Zones Monitoring Statistics API (libzonestat)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-zone-stats-openapi.yml
- filename: solaris-kernel-zones-openapi.yml
  format: yaml
  label: Oracle Solaris Kernel Zones API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-kernel-zones-openapi.yml
- filename: solaris-statsstore-openapi.yml
  format: yaml
  label: Oracle Solaris StatsStore and Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-statsstore-openapi.yml
- filename: solaris-unified-archives-openapi.yml
  format: yaml
  label: Oracle Solaris Unified Archives Zones API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-unified-archives-openapi.yml
apis:
- description: Core API for creating, managing, and monitoring Solaris Zones.
  name: Solaris Zones Management API
  slug: ''
- description: API endpoints for zone configuration and resource management.
  name: Zone Configuration API
  slug: ''
- description: API for zone lifecycle management including install, boot, halt, and delete operations.
  name: Zone Administration API
  slug: ''
- description: API for monitoring zone status, resource usage, and performance metrics.
  name: Zone Monitoring API
  slug: ''
- description: 'Remote Administration Daemon REST API for programmatic zone management via the com.oracle.solaris.rad.zonemgr module, supporting zone creation, configuration, migration, and lifecycle operations over '
  name: RAD Zone Management REST API
  slug: ''
- description: The libzonestat.so.1 C library API used to retrieve and compute zone-related resource utilization information including physical memory, virtual memory, and CPU resources with sorting and filtering op
  name: Zones Monitoring Statistics API (libzonestat)
  slug: ''
- description: API for creating and managing Oracle Solaris Kernel Zones, which are non-global zones with their own kernel providing greater independence and enhanced security isolation.
  name: Oracle Solaris Kernel Zones API
  slug: ''
- description: 'REST API and web interface for accessing the Oracle Solaris 11.4 StatsStore, providing consolidated zone resource statistics, system performance data, and historical analytics via CLI, C, Python, and '
  name: Oracle Solaris StatsStore and Analytics API
  slug: ''
- description: API for creating, deploying, and managing Unified Archives for zone system recovery, cloning, and migration across Oracle Solaris systems.
  name: Oracle Solaris Unified Archives Zones API
  slug: ''
capabilities:
- description: Unified zone lifecycle workflow combining zone creation, configuration, administration, monitoring, and migration. Used by system administrators and platform engineers to manage Solaris virtualization
  name: Solaris Zone Lifecycle Management
  slug: zone-lifecycle
common:
- title: ''
  type: TermsOfService
  url: https://www.oracle.com/legal/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.oracle.com/legal/privacy/
- title: ''
  type: Authentication
  url: https://docs.oracle.com/en/cloud/paas/api-platform/authentication.html
- title: ''
  type: Support
  url: https://www.oracle.com/support/
- title: ''
  type: Blog
  url: https://blogs.oracle.com/solaris/
- title: ''
  type: Portal
  url: https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/index.html
- title: Developer Resources
  type: Resources
  url: https://www.oracle.com/solaris/technologies/solarisdeveloper.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/oracle/oraclesolaris-contrib
- title: ''
  type: GettingStarted
  url: https://docs.oracle.com/cd/E37838_01/html/E61038/gitsf.html
- title: Virtual Environments Overview
  type: Documentation
  url: https://docs.oracle.com/cd/E37838_01/html/E61037/zonesoverview.html
- title: Zones Configuration Resources
  type: Documentation
  url: https://docs.oracle.com/cd/E37838_01/html/E61040/
- title: RAD Client Guide
  type: Documentation
  url: https://docs.oracle.com/cd/E37838_01/html/E68270/gpzpd.html
- title: ''
  type: JSONLD
  url: json-ld/solaris-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/solaris-zone-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/solaris-zone-resource-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/solaris-zone-stats-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/solaris-zone-migration-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/solaris-zone-evacuation-schema.json
created: '2024'
description: API for managing Solaris Zones (containers) and virtualization on Oracle Solaris systems.
features:
- description: Hardware-enforced isolation between zones providing secure multi-tenant environments on a single physical system.
  name: Zone Isolation
- description: Move running zones between physical systems without downtime using live migration capabilities.
  name: Live Migration
- description: Non-global zones with their own independent kernel for enhanced security isolation and OS independence.
  name: Kernel Zones
- description: Create portable system archives for zone cloning, recovery, and migration across Solaris systems.
  name: Unified Archives
- description: Consolidated resource statistics and historical analytics for monitoring zone performance and capacity planning.
  name: StatsStore Analytics
- description: RESTful remote administration daemon enabling programmatic zone management over HTTP/JSON.
  name: RAD Remote Administration
- description: Fine-grained CPU, memory, and swap resource controls with configurable caps per zone.
  name: Resource Capping
image: https://www.oracle.com/a/ocom/img/cb71-solaris.jpg
integrations:
- description: Manage Solaris Zones through Oracle Enterprise Manager for centralized infrastructure monitoring and control.
  name: Oracle Enterprise Manager
- description: Automate zone provisioning and configuration management using Ansible playbooks with Oracle Solaris modules.
  name: Ansible
- description: Configure and manage Solaris Zones infrastructure as code using Puppet modules for Oracle Solaris.
  name: Puppet
jsonld:
- class_count: 0
  name: Solaris Context
  property_count: 12
  slug: solaris-context
- class_count: 0
  name: Solaris Kernel Zones Context
  property_count: 0
  slug: solaris-kernel-zones-context
- class_count: 0
  name: Solaris Rad Zonemgr Context
  property_count: 0
  slug: solaris-rad-zonemgr-context
- class_count: 0
  name: Solaris Statsstore Context
  property_count: 0
  slug: solaris-statsstore-context
- class_count: 0
  name: Solaris Unified Archives Context
  property_count: 0
  slug: solaris-unified-archives-context
- class_count: 0
  name: Solaris Zone Administration Context
  property_count: 0
  slug: solaris-zone-administration-context
- class_count: 0
  name: Solaris Zone Configuration Context
  property_count: 0
  slug: solaris-zone-configuration-context
- class_count: 0
  name: Solaris Zone Monitoring Context
  property_count: 0
  slug: solaris-zone-monitoring-context
- class_count: 0
  name: Solaris Zone Stats Context
  property_count: 0
  slug: solaris-zone-stats-context
- class_count: 0
  name: Solaris Zones Context
  property_count: 15
  slug: solaris-zones-context
- class_count: 0
  name: Solaris Zones Management Context
  property_count: 0
  slug: solaris-zones-management-context
layout: provider
modified: '2026-04-18'
name: Solaris Zones
rules:
- name: Solaris Zones API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: solaris-zones-spectral-rules
skills: []
slug: solaris-zones
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Solaris Zones\ndescription: >-\n  API for managing Solaris Zones (containers) and virtualization on Oracle Solaris\n  systems.\nimage: https://www.oracle.com/a/ocom/img/cb71-solaris.jpg\ncreated: '2024'\nmodified: '2026-04-18'\nurl: https://docs.oracle.com/en/operating-systems/solaris.html\nspecificationVersion: '0.18'\napis:\n  - name: Solaris Zones Management API\n    description: >-\n      Core API for creating, managing, and monitoring Solaris Zones.\n    image: https://www.oracle.com/a/ocom/img/cb71-solaris.jpg\n    humanURL: https://docs.oracle.com/cd/E88353_01/html/E37839/zones.html\n    baseURL: https://solaris-host.example.com/api/v1\n    tags:\n      - Containers\n      - Oracle\n      - Solaris\n      - Virtualization\n      - Zones\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E88353_01/html/E37839/zones.html\n      - type: OpenAPI\n        url: openapi/solaris-zones-management-openapi.yml\n    contact:\n      - FN:\
  \ Oracle Solaris Support\n        email: solaris-support@oracle.com\n        url: https://www.oracle.com/solaris/support/\n  - name: Zone Configuration API\n    description: >-\n      API endpoints for zone configuration and resource management.\n    humanURL: https://docs.oracle.com/cd/E88353_01/html/E37839/zonecfg-1m.html\n    baseURL: https://solaris-host.example.com/api/v1/zones\n    tags:\n      - Configuration\n      - Networking\n      - Resources\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E88353_01/html/E37839/zonecfg-1m.html\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E37838_01/html/E61040/\n      - type: OpenAPI\n        url: openapi/solaris-zone-configuration-openapi.yml\n    contact:\n      - FN: Oracle Solaris Support\n        email: solaris-support@oracle.com\n        url: https://www.oracle.com/solaris/support/\n  - name: Zone Administration API\n    description: >-\n      API for zone lifecycle management\
  \ including install, boot, halt, and delete\n      operations.\n    humanURL: https://docs.oracle.com/cd/E88353_01/html/E37839/zoneadm-1m.html\n    baseURL: https://solaris-host.example.com/api/v1/zones/admin\n    tags:\n      - Administration\n      - Lifecycle\n      - Management\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E88353_01/html/E37839/zoneadm-1m.html\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E37838_01/html/E61038/gqhar.html\n      - type: OpenAPI\n        url: openapi/solaris-zone-administration-openapi.yml\n    contact:\n      - FN: Oracle Solaris Support\n        email: solaris-support@oracle.com\n        url: https://www.oracle.com/solaris/support/\n  - name: Zone Monitoring API\n    description: >-\n      API for monitoring zone status, resource usage, and performance metrics.\n    humanURL: https://docs.oracle.com/cd/E88353_01/html/E37839/zonestat-1.html\n    baseURL: https://solaris-host.example.com/api/v1/zones/monitoring\n\
  \    tags:\n      - Metrics\n      - Monitoring\n      - Performance\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E88353_01/html/E37839/zonestat-1.html\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E37838_01/html/E61043/gklfb.html\n      - type: OpenAPI\n        url: openapi/solaris-zone-monitoring-openapi.yml\n    contact:\n      - FN: Oracle Solaris Support\n        email: solaris-support@oracle.com\n        url: https://www.oracle.com/solaris/support/\n  - name: RAD Zone Management REST API\n    description: >-\n      Remote Administration Daemon REST API for programmatic zone management via the\n      com.oracle.solaris.rad.zonemgr module, supporting zone creation, configuration,\n      migration, and lifecycle operations over HTTP/JSON.\n    humanURL: https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/rad-client/rest-api-reference.html\n    baseURL: https://solaris-host.example.com/api/com.oracle.solaris.rad.zonemgr\n\
  \    tags:\n      - Management\n      - RAD\n      - Remote Administration\n      - REST API\n      - Zones\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/rad-client/rest-api-reference.html\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E37838_01/html/E68270/gpzpd.html\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E37838_01/html/E68270/gpzpv.html\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E88353_01/html/E76189/zonemgr-1-3rad.html\n      - type: OpenAPI\n        url: openapi/solaris-rad-zonemgr-openapi.yml\n    contact:\n      - FN: Oracle Solaris Support\n        email: solaris-support@oracle.com\n        url: https://www.oracle.com/solaris/support/\n  - name: Zones Monitoring Statistics API (libzonestat)\n    description: >-\n      The libzonestat.so.1 C library API used to retrieve and compute zone-related\n      resource utilization\
  \ information including physical memory, virtual memory,\n      and CPU resources with sorting and filtering options.\n    humanURL: https://docs.oracle.com/cd/E37838_01/html/E61043/\n    baseURL: https://solaris-host.example.com/api/v1/zones/stats\n    tags:\n      - CPU\n      - Libzonestat\n      - Memory\n      - Monitoring\n      - Resource Utilization\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E37838_01/html/E61043/\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E37838_01/html/E61043/gklfn.html\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E23824_01/html/821-1499/gloag.html\n      - type: OpenAPI\n        url: openapi/solaris-zone-stats-openapi.yml\n    contact:\n      - FN: Oracle Solaris Support\n        email: solaris-support@oracle.com\n        url: https://www.oracle.com/solaris/support/\n  - name: Oracle Solaris Kernel Zones API\n    description: >-\n      API for\
  \ creating and managing Oracle Solaris Kernel Zones, which are non-global\n      zones with their own kernel providing greater independence and enhanced security\n      isolation.\n    humanURL: https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/kernel-zones/oracle-solaris-kernel-zones.html\n    baseURL: https://solaris-host.example.com/api/v1/zones/kernel\n    tags:\n      - Isolation\n      - Kernel Zones\n      - Security\n      - Virtualization\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/kernel-zones/oracle-solaris-kernel-zones.html\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E37838_01/html/E61041/gnzfn.html\n      - type: OpenAPI\n        url: openapi/solaris-kernel-zones-openapi.yml\n    contact:\n      - FN: Oracle Solaris Support\n        email: solaris-support@oracle.com\n        url: https://www.oracle.com/solaris/support/\n  - name: Oracle\
  \ Solaris StatsStore and Analytics API\n    description: >-\n      REST API and web interface for accessing the Oracle Solaris 11.4 StatsStore,\n      providing consolidated zone resource statistics, system performance data, and\n      historical analytics via CLI, C, Python, and RAD interfaces.\n    humanURL: https://docs.oracle.com/cd/E37838_01/html/E56520/index.html\n    baseURL: https://solaris-host.example.com/api/v1/statsstore\n    tags:\n      - Analytics\n      - Monitoring\n      - Performance\n      - REST API\n      - StatsStore\n      - Web Interface\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E37838_01/html/E56520/index.html\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E37838_01/html/E56520/sstoreintro.html\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E37838_01/html/E56520/ssids.html\n      - type: OpenAPI\n        url: openapi/solaris-statsstore-openapi.yml\n    contact:\n      -\
  \ FN: Oracle Solaris Support\n        email: solaris-support@oracle.com\n        url: https://www.oracle.com/solaris/support/\n  - name: Oracle Solaris Unified Archives Zones API\n    description: >-\n      API for creating, deploying, and managing Unified Archives for zone system recovery,\n      cloning, and migration across Oracle Solaris systems.\n    humanURL: https://docs.oracle.com/cd/E37838_01/html/E60984/gmrlo.html\n    baseURL: https://solaris-host.example.com/api/v1/zones/archives\n    tags:\n      - Backup\n      - Cloning\n      - Migration\n      - Recovery\n      - Unified Archives\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E37838_01/html/E60984/gmrlo.html\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E37838_01/html/E60984/gmwen.html\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E37838_01/html/E61039/gpoiu.html\n      - type: OpenAPI\n        url: openapi/solaris-unified-archives-openapi.yml\n\
  \    contact:\n      - FN: Oracle Solaris Support\n        email: solaris-support@oracle.com\n        url: https://www.oracle.com/solaris/support/\ncommon:\n  - type: TermsOfService\n    url: https://www.oracle.com/legal/terms.html\n  - type: PrivacyPolicy\n    url: https://www.oracle.com/legal/privacy/\n  - type: Authentication\n    url: https://docs.oracle.com/en/cloud/paas/api-platform/authentication.html\n  - type: Support\n    url: https://www.oracle.com/support/\n  - type: Blog\n    url: https://blogs.oracle.com/solaris/\n  - type: Portal\n    url: https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/index.html\n  - type: Resources\n    url: https://www.oracle.com/solaris/technologies/solarisdeveloper.html\n    title: Developer Resources\n  - type: GitHubOrganization\n    url: https://github.com/oracle/oraclesolaris-contrib\n  - type: GettingStarted\n    url: https://docs.oracle.com/cd/E37838_01/html/E61038/gitsf.html\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E37838_01/html/E61037/zonesoverview.html\n\
  \    title: Virtual Environments Overview\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E37838_01/html/E61040/\n    title: Zones Configuration Resources\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E37838_01/html/E68270/gpzpd.html\n    title: RAD Client Guide\n  - type: JSONLD\n    url: json-ld/solaris-context.jsonld\n  - type: JSONSchema\n    url: json-schema/solaris-zone-schema.json\n  - type: JSONSchema\n    url: json-schema/solaris-zone-resource-schema.json\n  - type: JSONSchema\n    url: json-schema/solaris-zone-stats-schema.json\n  - type: JSONSchema\n    url: json-schema/solaris-zone-migration-schema.json\n  - type: JSONSchema\n    url: json-schema/solaris-zone-evacuation-schema.json\n  - type: Features\n    data:\n      - name: Zone Isolation\n        description: Hardware-enforced isolation between zones providing secure multi-tenant environments on a single physical system.\n      - name: Live Migration\n        description: Move running zones\
  \ between physical systems without downtime using live migration capabilities.\n      - name: Kernel Zones\n        description: Non-global zones with their own independent kernel for enhanced security isolation and OS independence.\n      - name: Unified Archives\n        description: Create portable system archives for zone cloning, recovery, and migration across Solaris systems.\n      - name: StatsStore Analytics\n        description: Consolidated resource statistics and historical analytics for monitoring zone performance and capacity planning.\n      - name: RAD Remote Administration\n        description: RESTful remote administration daemon enabling programmatic zone management over HTTP/JSON.\n      - name: Resource Capping\n        description: Fine-grained CPU, memory, and swap resource controls with configurable caps per zone.\n  - type: UseCases\n    data:\n      - name: Server Consolidation\n        description: Consolidate multiple workloads onto a single physical system\
  \ using zones for resource isolation and management.\n      - name: Development and Testing\n        description: Create isolated development and testing environments that mirror production without dedicated hardware.\n      - name: Disaster Recovery\n        description: Use Unified Archives and zone migration to implement disaster recovery workflows across Solaris systems.\n      - name: Performance Monitoring\n        description: Monitor zone resource utilization and system performance using StatsStore and zonestat APIs.\n      - name: Automated Provisioning\n        description: Programmatically create, configure, and deploy zones using RAD REST APIs for automated infrastructure provisioning.\n  - type: Integrations\n    data:\n      - name: Oracle Enterprise Manager\n        description: Manage Solaris Zones through Oracle Enterprise Manager for centralized infrastructure monitoring and control.\n      - name: Ansible\n        description: Automate zone provisioning and configuration\
  \ management using Ansible playbooks with Oracle Solaris modules.\n      - name: Puppet\n        description: Configure and manage Solaris Zones infrastructure as code using Puppet modules for Oracle Solaris.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n  - FN: Oracle Corporation\n    email: solaris-feedback@oracle.com\n    url: https://www.oracle.com/solaris/\ntags:\n  - Containers\n  - Kernel Zones\n  - Operating Systems\n  - Oracle\n  - RAD\n  - Resource Management\n  - Solaris\n  - StatsStore\n  - Virtualization\n  - Zones\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/apis.yml
tags:
- Containers
- Kernel Zones
- Operating Systems
- Oracle
- RAD
- Resource Management
- Solaris
- StatsStore
- Virtualization
- Zones
url: https://docs.oracle.com/en/operating-systems/solaris.html
use_cases:
- description: Consolidate multiple workloads onto a single physical system using zones for resource isolation and management.
  name: Server Consolidation
- description: Create isolated development and testing environments that mirror production without dedicated hardware.
  name: Development and Testing
- description: Use Unified Archives and zone migration to implement disaster recovery workflows across Solaris systems.
  name: Disaster Recovery
- description: Monitor zone resource utilization and system performance using StatsStore and zonestat APIs.
  name: Performance Monitoring
- description: Programmatically create, configure, and deploy zones using RAD REST APIs for automated infrastructure provisioning.
  name: Automated Provisioning
---
