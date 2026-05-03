---
api_count: 10
api_specs:
- filename: openstack-keystone-openapi.yml
  format: yaml
  label: OpenStack Identity (Keystone) API
  slug: keystone
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/openapi/openstack-keystone-openapi.yml
- filename: openstack-nova-openapi.yml
  format: yaml
  label: OpenStack Compute (Nova) API
  slug: nova
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/openapi/openstack-nova-openapi.yml
apis:
- description: Keystone is the OpenStack Identity service that provides authentication, authorization, and a service catalog for an OpenStack cloud. Tokens issued by Keystone are required to call any other OpenStack
  name: OpenStack Identity (Keystone) API
  slug: keystone
- description: Nova is the OpenStack Compute service that manages the lifecycle of compute instances (virtual machines, bare-metal, containers). The API exposes endpoints for servers, flavors, images, key pairs, sec
  name: OpenStack Compute (Nova) API
  slug: nova
- description: Neutron provides networking as a service, exposing endpoints for networks, subnets, ports, routers, floating IPs, security groups, load balancers, firewalls, and VPN-as-a-Service.
  name: OpenStack Networking (Neutron) API
  slug: neutron
- description: Cinder provides persistent block-level storage volumes that can be attached to Nova instances. The v3 API exposes endpoints for volumes, snapshots, backups, volume types, attachments, transfers, and q
  name: OpenStack Block Storage (Cinder) API
  slug: cinder
- description: Swift is the OpenStack object storage service. The API exposes endpoints for accounts, containers, and objects with eventual- consistency replication, large-object support, and configurable access con
  name: OpenStack Object Storage (Swift) API
  slug: swift
- description: Glance manages disk and server images. The v2 API exposes endpoints for images, image members, image tags, image data upload/download, tasks, schemas, and metadata definitions.
  name: OpenStack Image (Glance) API
  slug: glance
- description: Heat is the OpenStack orchestration service that manages infrastructure-as-code deployments via HOT (Heat Orchestration Template) and AWS CloudFormation-compatible templates. The API exposes endpoints
  name: OpenStack Orchestration (Heat) API
  slug: heat
- description: Octavia provides Load Balancing as a Service. The v2 API exposes endpoints for load balancers, listeners, pools, members, health monitors, L7 policies and rules, and TLS containers.
  name: OpenStack Load Balancer (Octavia) API
  slug: octavia
- description: Designate is the OpenStack DNS-as-a-Service. The v2 API exposes endpoints for zones, recordsets, pools, transfers, and TSIG keys.
  name: OpenStack DNS (Designate) API
  slug: designate
- description: Trove is the OpenStack Database-as-a-Service that provisions and manages database instances (MySQL, PostgreSQL, MongoDB, Redis, MariaDB, Cassandra, etc.) on top of OpenStack.
  name: OpenStack Database (Trove) API
  slug: trove
common:
- title: ''
  type: Website
  url: https://www.openstack.org/
- title: ''
  type: Portal
  url: https://docs.openstack.org/
- title: ''
  type: Documentation
  url: https://docs.openstack.org/api-ref/
- title: ''
  type: GettingStarted
  url: https://docs.openstack.org/api-quick-start/
- title: ''
  type: Community
  url: https://www.openstack.org/community/
- title: ''
  type: Blog
  url: https://www.openstack.org/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/openstack
- title: ''
  type: SourceCode
  url: https://opendev.org/openstack
- title: ''
  type: TermsOfService
  url: https://www.openstack.org/legal/
- title: ''
  type: License
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Organization
  url: https://www.openstack.org/foundation/
created: '2025-01-01'
description: Open source cloud computing platform for building and managing public and private clouds, providing infrastructure as a service (IaaS) through a set of interrelated services including Compute (Nova), Object Storage (Swift), Block Storage (Cinder), Networking (Neutron), Identity (Keystone), Image (Glance), Orchestration (Heat), Database (Trove), DNS (Designate), and Load Balancer (Octavia). Each service exposes its own REST API; clients authenticate against Keystone and use the returned service catalog to discover per-region endpoints for the remaining services.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Openstack Context
  property_count: 0
  slug: openstack-context
layout: provider
modified: '2026-04-28'
name: OpenStack
skills: []
slug: openstack
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: openstack\nname: OpenStack\ndescription: >-\n  Open source cloud computing platform for building and managing public and\n  private clouds, providing infrastructure as a service (IaaS) through a set\n  of interrelated services including Compute (Nova), Object Storage (Swift),\n  Block Storage (Cinder), Networking (Neutron), Identity (Keystone), Image\n  (Glance), Orchestration (Heat), Database (Trove), DNS (Designate), and\n  Load Balancer (Octavia). Each service exposes its own REST API; clients\n  authenticate against Keystone and use the returned service catalog to\n  discover per-region endpoints for the remaining services.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Platform\n  - Infrastructure as a Service\n  - Open Source\n  - Virtualization\n  - Linux Foundation\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: openstack:keystone\n    name: OpenStack Identity (Keystone) API\n    description: >-\n      Keystone is the OpenStack Identity service that provides\n      authentication, authorization, and a service catalog for an\n      OpenStack cloud. Tokens issued by Keystone are required to call any\n      other OpenStack service API. The v3 API exposes endpoints for\n      tokens, users, groups, projects, domains, roles, role assignments,\n      services, endpoints, and the service catalog.\n    humanURL: https://docs.openstack.org/api-ref/identity/v3/\n    baseURL: https://{keystone-host}:5000/v3\n    tags:\n      - Identity\n      - Authentication\n      - Authorization\n      - Service Catalog\n    properties:\n      - type: Documentation\n        url: https://docs.openstack.org/api-ref/identity/v3/\n      - type: Documentation\n        url: https://docs.openstack.org/keystone/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/openapi/openstack-keystone-openapi.yml\n\
  \      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/json-ld/openstack-context.jsonld\n  - aid: openstack:nova\n    name: OpenStack Compute (Nova) API\n    description: >-\n      Nova is the OpenStack Compute service that manages the lifecycle of\n      compute instances (virtual machines, bare-metal, containers). The\n      API exposes endpoints for servers, flavors, images, key pairs,\n      security groups, attached volumes, and lifecycle actions such as\n      start, stop, reboot, resize, rebuild, and snapshot.\n    humanURL: https://docs.openstack.org/api-ref/compute/\n    baseURL: https://{nova-host}/compute/v2.1\n    tags:\n      - Compute\n      - Virtual Machines\n      - Bare Metal\n    properties:\n      - type: Documentation\n        url: https://docs.openstack.org/api-ref/compute/\n      - type: Documentation\n        url: https://docs.openstack.org/nova/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/openapi/openstack-nova-openapi.yml\n\
  \      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/json-schema/openstack-server-schema.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/json-ld/openstack-context.jsonld\n  - aid: openstack:neutron\n    name: OpenStack Networking (Neutron) API\n    description: >-\n      Neutron provides networking as a service, exposing endpoints for\n      networks, subnets, ports, routers, floating IPs, security groups,\n      load balancers, firewalls, and VPN-as-a-Service.\n    humanURL: https://docs.openstack.org/api-ref/network/\n    baseURL: https://{neutron-host}/networking/v2.0\n    tags:\n      - Networking\n      - SDN\n      - Security Groups\n    properties:\n      - type: Documentation\n        url: https://docs.openstack.org/api-ref/network/\n      - type: Documentation\n        url: https://docs.openstack.org/neutron/\n  - aid: openstack:cinder\n    name:\
  \ OpenStack Block Storage (Cinder) API\n    description: >-\n      Cinder provides persistent block-level storage volumes that can be\n      attached to Nova instances. The v3 API exposes endpoints for\n      volumes, snapshots, backups, volume types, attachments, transfers,\n      and quotas.\n    humanURL: https://docs.openstack.org/api-ref/block-storage/\n    baseURL: https://{cinder-host}/volume/v3\n    tags:\n      - Block Storage\n      - Volumes\n      - Snapshots\n    properties:\n      - type: Documentation\n        url: https://docs.openstack.org/api-ref/block-storage/\n      - type: Documentation\n        url: https://docs.openstack.org/cinder/\n  - aid: openstack:swift\n    name: OpenStack Object Storage (Swift) API\n    description: >-\n      Swift is the OpenStack object storage service. The API exposes\n      endpoints for accounts, containers, and objects with eventual-\n      consistency replication, large-object support, and configurable\n      access controls.\n    humanURL:\
  \ https://docs.openstack.org/api-ref/object-store/\n    baseURL: https://{swift-host}/v1/AUTH_{tenant_id}\n    tags:\n      - Object Storage\n      - Containers\n      - Replication\n    properties:\n      - type: Documentation\n        url: https://docs.openstack.org/api-ref/object-store/\n      - type: Documentation\n        url: https://docs.openstack.org/swift/\n  - aid: openstack:glance\n    name: OpenStack Image (Glance) API\n    description: >-\n      Glance manages disk and server images. The v2 API exposes endpoints\n      for images, image members, image tags, image data upload/download,\n      tasks, schemas, and metadata definitions.\n    humanURL: https://docs.openstack.org/api-ref/image/\n    baseURL: https://{glance-host}/image/v2\n    tags:\n      - Images\n      - Disk Images\n    properties:\n      - type: Documentation\n        url: https://docs.openstack.org/api-ref/image/\n      - type: Documentation\n        url: https://docs.openstack.org/glance/\n  - aid: openstack:heat\n\
  \    name: OpenStack Orchestration (Heat) API\n    description: >-\n      Heat is the OpenStack orchestration service that manages\n      infrastructure-as-code deployments via HOT (Heat Orchestration\n      Template) and AWS CloudFormation-compatible templates. The API\n      exposes endpoints for stacks, resources, events, software configs,\n      and template validation.\n    humanURL: https://docs.openstack.org/api-ref/orchestration/\n    baseURL: https://{heat-host}/heat-api/v1\n    tags:\n      - Orchestration\n      - Infrastructure as Code\n    properties:\n      - type: Documentation\n        url: https://docs.openstack.org/api-ref/orchestration/\n      - type: Documentation\n        url: https://docs.openstack.org/heat/\n  - aid: openstack:octavia\n    name: OpenStack Load Balancer (Octavia) API\n    description: >-\n      Octavia provides Load Balancing as a Service. The v2 API exposes\n      endpoints for load balancers, listeners, pools, members, health\n      monitors, L7\
  \ policies and rules, and TLS containers.\n    humanURL: https://docs.openstack.org/api-ref/load-balancer/\n    baseURL: https://{octavia-host}/load-balancer/v2\n    tags:\n      - Load Balancer\n      - LBaaS\n    properties:\n      - type: Documentation\n        url: https://docs.openstack.org/api-ref/load-balancer/\n      - type: Documentation\n        url: https://docs.openstack.org/octavia/\n  - aid: openstack:designate\n    name: OpenStack DNS (Designate) API\n    description: >-\n      Designate is the OpenStack DNS-as-a-Service. The v2 API exposes\n      endpoints for zones, recordsets, pools, transfers, and TSIG keys.\n    humanURL: https://docs.openstack.org/api-ref/dns/\n    baseURL: https://{designate-host}/dns/v2\n    tags:\n      - DNS\n      - DNSaaS\n    properties:\n      - type: Documentation\n        url: https://docs.openstack.org/api-ref/dns/\n      - type: Documentation\n        url: https://docs.openstack.org/designate/\n  - aid: openstack:trove\n    name: OpenStack\
  \ Database (Trove) API\n    description: >-\n      Trove is the OpenStack Database-as-a-Service that provisions and\n      manages database instances (MySQL, PostgreSQL, MongoDB, Redis,\n      MariaDB, Cassandra, etc.) on top of OpenStack.\n    humanURL: https://docs.openstack.org/api-ref/database/\n    baseURL: https://{trove-host}/database/v1.0\n    tags:\n      - Database\n      - DBaaS\n    properties:\n      - type: Documentation\n        url: https://docs.openstack.org/api-ref/database/\n      - type: Documentation\n        url: https://docs.openstack.org/trove/\ncommon:\n  - url: https://www.openstack.org/\n    name: OpenStack\n    type: Website\n  - url: https://docs.openstack.org/\n    name: Documentation Portal\n    type: Portal\n  - url: https://docs.openstack.org/api-ref/\n    name: API Reference\n    type: Documentation\n  - url: https://docs.openstack.org/api-quick-start/\n    name: API Quick Start\n    type: GettingStarted\n  - url: https://www.openstack.org/community/\n\
  \    name: Community\n    type: Community\n  - url: https://www.openstack.org/blog/\n    name: Blog\n    type: Blog\n  - url: https://github.com/openstack\n    name: GitHub Organization\n    type: GitHubOrganization\n  - url: https://opendev.org/openstack\n    name: OpenDev Source\n    type: SourceCode\n  - url: https://www.openstack.org/legal/\n    name: Legal\n    type: TermsOfService\n  - url: https://www.apache.org/licenses/LICENSE-2.0\n    name: Apache 2.0 License\n    type: License\n  - url: https://www.openstack.org/foundation/\n    name: Open Infrastructure Foundation\n    type: Organization\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/apis.yml
tags:
- Cloud Platform
- Infrastructure as a Service
- Open Source
- Virtualization
- Linux Foundation
url: https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/apis.yml
use_cases: []
---
