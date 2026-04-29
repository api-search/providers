---
api_count: 2
apis:
- description: The ECS Management REST API provides programmatic access to manage Dell EMC Elastic Cloud Storage (ECS) object storage platform. It supports namespace management, user management, storage pool configu
  name: EMC ECS Management REST API
  slug: ecs-management-api
- description: The Unisphere Management REST API provides programmatic access to manage Dell EMC Unity and PowerStore storage arrays. It supports storage resource provisioning, performance monitoring, alert manageme
  name: EMC Unisphere REST API
  slug: unisphere-api
capabilities: []
common:
- title: ''
  type: Documentation
  url: https://www.dell.com/support/kbdoc/en-us/000020064/ecs-api-documentation
- title: ''
  type: Support
  url: https://www.dell.com/support/home/en-us
- title: ''
  type: DeveloperPortal
  url: https://developer.dell.com/
created: '2026-03-24'
description: EMC Corporation (now Dell EMC, a division of Dell Technologies) provides enterprise storage, data management, and cloud infrastructure solutions. EMC products include VMAX, VNX, Isilon, and ECS storage platforms, as well as data protection and information management solutions. EMC was acquired by Dell Technologies in 2016.
features:
- Enterprise-grade object and block storage
- Multi-protocol support (S3, Swift, Atmos, HDFS)
- Geo-distributed replication
- Namespace and tenant management
- Role-based access control
- Performance monitoring and alerting
- Storage pool and provisioning management
image: /assets/icons/emc.png
integrations:
- VMware vSphere
- Microsoft Hyper-V
- Amazon S3
- OpenStack Swift
- Hadoop HDFS
- Kubernetes CSI
- Ansible
layout: provider
modified: '2026-04-18'
name: EMC
skills: []
slug: emc
solutions: []
source_filename: apis.yml
source_yaml: "aid: emc\nname: EMC\ndescription: >-\n  EMC Corporation (now Dell EMC, a division of Dell Technologies) provides\n  enterprise storage, data management, and cloud infrastructure solutions. EMC\n  products include VMAX, VNX, Isilon, and ECS storage platforms, as well as\n  data protection and information management solutions. EMC was acquired by\n  Dell Technologies in 2016.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/emc/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Cloud Infrastructure\n  - Data Management\n  - Data Protection\n  - Enterprise Storage\n  - Storage\napis:\n  - aid: emc:ecs-management-api\n    name: EMC ECS Management REST API\n    description: >-\n      The ECS Management REST API provides programmatic access to manage Dell EMC\n      Elastic Cloud Storage (ECS) object storage platform.\
  \ It supports namespace\n      management, user management, storage pool configuration, replication groups,\n      bucket management, and monitoring operations.\n    humanURL: https://www.dell.com/support/kbdoc/en-us/000020064/ecs-api-documentation\n    baseURL: https://ecs.example.com:4443\n    tags:\n      - Buckets\n      - Cloud Storage\n      - Namespaces\n      - Object Storage\n    properties:\n      - type: Documentation\n        url: https://www.dell.com/support/kbdoc/en-us/000020064/ecs-api-documentation\n    contact:\n      - type: Support\n        url: https://www.dell.com/support/home/en-us\n  - aid: emc:unisphere-api\n    name: EMC Unisphere REST API\n    description: >-\n      The Unisphere Management REST API provides programmatic access to manage\n      Dell EMC Unity and PowerStore storage arrays. It supports storage resource\n      provisioning, performance monitoring, alert management, and system\n      configuration operations.\n    humanURL: https://www.dell.com/support/kbdoc/en-us/000020064/ecs-api-documentation\n\
  \    baseURL: https://unity.example.com/api\n    tags:\n      - Enterprise Storage\n      - Management\n      - Monitoring\n      - Storage Arrays\n    properties:\n      - type: Documentation\n        url: https://www.dell.com/support/kbdoc/en-us/000020064/ecs-api-documentation\n    contact:\n      - type: Support\n        url: https://www.dell.com/support/home/en-us\ncommon:\n  - type: Documentation\n    url: https://www.dell.com/support/kbdoc/en-us/000020064/ecs-api-documentation\n  - type: Support\n    url: https://www.dell.com/support/home/en-us\n  - type: DeveloperPortal\n    url: https://developer.dell.com/\n  - type: Features\n    data:\n      - Enterprise-grade object and block storage\n      - Multi-protocol support (S3, Swift, Atmos, HDFS)\n      - Geo-distributed replication\n      - Namespace and tenant management\n      - Role-based access control\n      - Performance monitoring and alerting\n      - Storage pool and provisioning management\n  - type: UseCases\n    data:\n\
  \      - Managing enterprise storage infrastructure programmatically\n      - Automating storage provisioning for cloud workloads\n      - Monitoring storage array health and performance\n      - Configuring data protection and replication policies\n      - Managing multi-tenant storage environments\n  - type: Integrations\n    data:\n      - VMware vSphere\n      - Microsoft Hyper-V\n      - Amazon S3\n      - OpenStack Swift\n      - Hadoop HDFS\n      - Kubernetes CSI\n      - Ansible\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/emc/refs/heads/main/apis.yml
tags:
- Cloud Infrastructure
- Data Management
- Data Protection
- Enterprise Storage
- Storage
url: https://raw.githubusercontent.com/api-evangelist/emc/refs/heads/main/apis.yml
use_cases:
- Managing enterprise storage infrastructure programmatically
- Automating storage provisioning for cloud workloads
- Monitoring storage array health and performance
- Configuring data protection and replication policies
- Managing multi-tenant storage environments
---
