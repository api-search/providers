---
api_count: 1
apis:
- description: The CloudStack API provides comprehensive REST endpoints for managing virtual machines, networks, storage volumes, accounts, domains, zones, and all cloud infrastructure resources using a query-parame
  name: Apache CloudStack API
  slug: apache-cloudstack-api
capabilities:
- description: Workflow capability for managing Apache CloudStack infrastructure resources including virtual machine lifecycle, network configuration, storage volumes, and zone administration.
  name: Cloudstack Iaas Management
  slug: cloudstack-iaas-management
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/cloudstack
- title: ''
  type: Documentation
  url: https://docs.cloudstack.apache.org/
- title: ''
  type: GettingStarted
  url: https://docs.cloudstack.apache.org/en/latest/installguide/
- title: ''
  type: Support
  url: https://cloudstack.apache.org/community/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: ''
  type: ChangeLog
  url: https://github.com/apache/cloudstack/releases
- title: ''
  type: SpectralRules
  url: rules/apache-cloudstack-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-cloudstack-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/cloudstack-iaas-management.yaml
created: '2026-03-16'
description: Apache CloudStack is an open-source cloud computing platform developed by the Apache Software Foundation for creating, managing, and deploying infrastructure cloud services. It provides a comprehensive IaaS platform supporting multiple hypervisors (KVM, VMware vSphere, XenServer) and a rich API for programmatic cloud resource management. CloudStack is used by service providers and enterprises to build public, private, and hybrid cloud environments with virtual machine management, networking, storage, and multi-tenancy features.
features:
- description: Full VM lifecycle management including deploy, start, stop, reboot, migrate, and destroy across multiple hypervisors.
  name: Virtual Machine Management
- description: Support for KVM, VMware vSphere, XenServer, and Hyper-V hypervisors within a single CloudStack deployment.
  name: Multi-Hypervisor Support
- description: Advanced networking with isolated networks, shared networks, VLANs, VPNs, and software-defined networking.
  name: Network Management
- description: Primary and secondary storage management with volume snapshots, templates, and ISOs.
  name: Storage Management
- description: Account and domain hierarchy for isolating resources between tenants, departments, and organizations.
  name: Multi-Tenancy
- description: Long-running operations return async job IDs that can be polled for completion status.
  name: Asynchronous API
- description: Stateful firewall rules for controlling inbound and outbound traffic to virtual machines.
  name: Security Groups
- description: Automatic scaling of VM instances in response to load conditions using configurable policies.
  name: Auto Scaling
- description: Comprehensive query-parameter-based REST API with HMAC-SHA1 authentication for programmatic cloud management.
  name: REST API
- description: Web-based management console for administrators and users to manage cloud resources visually.
  name: CloudStack UI
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: KVM hypervisor support for Linux-based compute clusters in CloudStack zones.
  name: KVM
- description: VMware vSphere integration for managing ESXi hosts and vCenter clusters via CloudStack.
  name: VMware vSphere
- description: Integration with Apache Cloudbridge for hybrid cloud connectivity between CloudStack and AWS.
  name: Apache Cloudbridge
- description: Ceph distributed storage integration for primary storage in CloudStack deployments.
  name: Ceph
- description: OpenDaylight SDN controller integration for software-defined networking in CloudStack.
  name: OpenDaylight
- description: HashiCorp Terraform CloudStack provider for infrastructure-as-code provisioning.
  name: Terraform
- description: Ansible CloudStack modules for automating VM provisioning and cloud management tasks.
  name: Ansible
jsonld:
- class_count: 6
  name: Apache Cloudstack Context
  property_count: 21
  slug: apache-cloudstack-context
layout: provider
modified: '2026-04-19'
name: Apache CloudStack
rules:
- name: Apache CloudStack API Rules
  rule_count: 12
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 8
  slug: apache-cloudstack-spectral-rules
skills: []
slug: apache-cloudstack
solutions: []
source_yaml: "aid: apache-cloudstack\nname: Apache CloudStack\ndescription: >-\n  Apache CloudStack is an open-source cloud computing platform developed by the Apache Software Foundation for creating, managing, and deploying infrastructure cloud services. It provides a comprehensive IaaS platform supporting multiple hypervisors (KVM, VMware vSphere, XenServer) and a rich API for programmatic cloud resource management. CloudStack is used by service providers and enterprises to build public, private, and hybrid cloud environments with virtual machine management, networking, storage, and multi-tenancy features.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache\n  - Cloud\n  - IaaS\n  - Infrastructure\n  - Open Source\n  - Virtualization\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-cloudstack/refs/heads/main/apis.yml\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: apache-cloudstack:apache-cloudstack-api\n    name: Apache CloudStack API\n    description: >-\n      The CloudStack API provides comprehensive REST endpoints for managing virtual machines, networks, storage volumes, accounts, domains, zones, and all cloud infrastructure resources using a query-parameter-based command dispatch pattern with HMAC-SHA1 authentication and asynchronous job support.\n    humanURL: https://cloudstack.apache.org/api/\n    baseURL: http://localhost:8080/client/api\n    tags:\n      - Cloud\n      - IaaS\n      - REST\n      - Virtual Machines\n    properties:\n      - type: Documentation\n        url: https://cloudstack.apache.org/api/\n      - type: OpenAPI\n        url: openapi/apache-cloudstack-api-openapi.yaml\n      - type: GettingStarted\n        url: https://docs.cloudstack.apache.org/en/latest/installguide/\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/cloudstack\n\
  \  - type: Documentation\n    url: https://docs.cloudstack.apache.org/\n  - type: GettingStarted\n    url: https://docs.cloudstack.apache.org/en/latest/installguide/\n  - type: Support\n    url: https://cloudstack.apache.org/community/\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: ChangeLog\n    url: https://github.com/apache/cloudstack/releases\n  - type: SpectralRules\n    url: rules/apache-cloudstack-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-cloudstack-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/cloudstack-iaas-management.yaml\n  - type: Features\n    data:\n      - name: Virtual Machine Management\n        description: Full VM lifecycle management including deploy, start, stop, reboot, migrate, and destroy across multiple hypervisors.\n      - name: Multi-Hypervisor Support\n        description: Support for KVM, VMware vSphere, XenServer, and Hyper-V hypervisors within a single CloudStack deployment.\n\
  \      - name: Network Management\n        description: Advanced networking with isolated networks, shared networks, VLANs, VPNs, and software-defined networking.\n      - name: Storage Management\n        description: Primary and secondary storage management with volume snapshots, templates, and ISOs.\n      - name: Multi-Tenancy\n        description: Account and domain hierarchy for isolating resources between tenants, departments, and organizations.\n      - name: Asynchronous API\n        description: Long-running operations return async job IDs that can be polled for completion status.\n      - name: Security Groups\n        description: Stateful firewall rules for controlling inbound and outbound traffic to virtual machines.\n      - name: Auto Scaling\n        description: Automatic scaling of VM instances in response to load conditions using configurable policies.\n      - name: REST API\n        description: Comprehensive query-parameter-based REST API with HMAC-SHA1 authentication\
  \ for programmatic cloud management.\n      - name: CloudStack UI\n        description: Web-based management console for administrators and users to manage cloud resources visually.\n  - type: UseCases\n    data:\n      - name: Public Cloud Infrastructure\n        description: Build and operate public IaaS clouds for service providers offering compute, storage, and networking.\n      - name: Private Enterprise Cloud\n        description: Deploy private clouds for enterprise organizations needing isolated, on-premises infrastructure.\n      - name: Hybrid Cloud Orchestration\n        description: Extend on-premises CloudStack clouds to public cloud providers for burst capacity and disaster recovery.\n      - name: Managed Service Provider Hosting\n        description: Host multi-tenant virtual server environments for managed service providers and resellers.\n      - name: Development and Test Environments\n        description: Provision self-service development and testing environments\
  \ on demand for engineering teams.\n  - type: Integrations\n    data:\n      - name: KVM\n        description: KVM hypervisor support for Linux-based compute clusters in CloudStack zones.\n      - name: VMware vSphere\n        description: VMware vSphere integration for managing ESXi hosts and vCenter clusters via CloudStack.\n      - name: Apache Cloudbridge\n        description: Integration with Apache Cloudbridge for hybrid cloud connectivity between CloudStack and AWS.\n      - name: Ceph\n        description: Ceph distributed storage integration for primary storage in CloudStack deployments.\n      - name: OpenDaylight\n        description: OpenDaylight SDN controller integration for software-defined networking in CloudStack.\n      - name: Terraform\n        description: HashiCorp Terraform CloudStack provider for infrastructure-as-code provisioning.\n      - name: Ansible\n        description: Ansible CloudStack modules for automating VM provisioning and cloud management tasks.\n\
  maintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-cloudstack/refs/heads/main/apis.yml
tags:
- Apache
- Cloud
- IaaS
- Infrastructure
- Open Source
- Virtualization
url: https://raw.githubusercontent.com/api-evangelist/apache-cloudstack/refs/heads/main/apis.yml
use_cases:
- description: Build and operate public IaaS clouds for service providers offering compute, storage, and networking.
  name: Public Cloud Infrastructure
- description: Deploy private clouds for enterprise organizations needing isolated, on-premises infrastructure.
  name: Private Enterprise Cloud
- description: Extend on-premises CloudStack clouds to public cloud providers for burst capacity and disaster recovery.
  name: Hybrid Cloud Orchestration
- description: Host multi-tenant virtual server environments for managed service providers and resellers.
  name: Managed Service Provider Hosting
- description: Provision self-service development and testing environments on demand for engineering teams.
  name: Development and Test Environments
---
