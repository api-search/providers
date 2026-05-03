---
api_count: 2
apis:
- description: OpenDaylight is an open-source SDN controller platform that exposes RESTCONF APIs for managing network devices, topology, flows, and configuration. It provides northbound REST interfaces for network a
  name: OpenDaylight RESTCONF API
  slug: opendaylight-restconf
- description: ONOS (Open Network Operating System) is an open-source SDN controller that provides REST APIs for network management including topology discovery, flow rule management, host tracking, and device manag
  name: ONOS SDN Controller REST API
  slug: onos-rest-api
common:
- title: ''
  type: Website
  url: https://opennetworking.org/
- title: ''
  type: Reference
  url: https://en.wikipedia.org/wiki/Software-defined_networking
- title: ''
  type: Standard
  url: https://datatracker.ietf.org/doc/html/rfc7426
- title: ''
  type: Reference
  url: https://www.ciena.com/insights/articles/5-key-APIs-to-enable-the-concept-of-SDN-based-virtual-networks.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/opendaylight
- title: ''
  type: GitHubOrganization
  url: https://github.com/opennetworkinglab
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/json-ld/software-defined-networking-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/vocabulary/software-defined-networking-vocabulary.yml
created: '2026-05-02'
description: Software-Defined Networking (SDN) is a network architecture approach that decouples the network control plane from the data forwarding plane, enabling dynamic, programmatically efficient network configuration. SDN controllers expose northbound REST APIs for network applications to define routing, load balancing, and security policies, while southbound APIs communicate with switches and routers. Key SDN controllers include OpenDaylight, ONOS, and Floodlight.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Software Defined Networking Context
  property_count: 18
  slug: software-defined-networking-context
layout: provider
modified: '2026-05-02'
name: Software-Defined Networking
skills: []
slug: software-defined-networking
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: software-defined-networking\nname: Software-Defined Networking\ndescription: >-\n  Software-Defined Networking (SDN) is a network architecture approach that\n  decouples the network control plane from the data forwarding plane, enabling\n  dynamic, programmatically efficient network configuration. SDN controllers\n  expose northbound REST APIs for network applications to define routing,\n  load balancing, and security policies, while southbound APIs communicate\n  with switches and routers. Key SDN controllers include OpenDaylight, ONOS,\n  and Floodlight.\nurl: https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/apis.yml\ntags:\n  - Cloud Infrastructure\n  - Network Architecture\n  - Networking\n  - Virtualization\n  - SDN\n  - OpenDaylight\n  - ONOS\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: software-defined-networking:opendaylight-restconf\n    name: OpenDaylight RESTCONF API\n\
  \    description: >-\n      OpenDaylight is an open-source SDN controller platform that exposes\n      RESTCONF APIs for managing network devices, topology, flows, and\n      configuration. It provides northbound REST interfaces for network\n      applications and southbound interfaces for OpenFlow devices.\n    humanURL: https://docs.opendaylight.org/en/latest/\n    baseURL: http://localhost:8181/restconf\n    tags:\n      - SDN\n      - OpenDaylight\n      - RESTCONF\n      - Network Management\n      - Networking\n    properties:\n      - type: Documentation\n        url: https://docs.opendaylight.org/en/latest/user-guide/opendaylight-controller-overview.html\n      - type: Website\n        url: https://www.opendaylight.org/\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/json-schema/sdn-network-topology-schema.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/json-structure/sdn-topology-structure.json\n\
  \n  - aid: software-defined-networking:onos-rest-api\n    name: ONOS SDN Controller REST API\n    description: >-\n      ONOS (Open Network Operating System) is an open-source SDN controller\n      that provides REST APIs for network management including topology\n      discovery, flow rule management, host tracking, and device management.\n    humanURL: https://wiki.onosproject.org/display/ONOS/REST+API\n    baseURL: http://localhost:8181/onos/v1\n    tags:\n      - SDN\n      - ONOS\n      - Network Management\n      - Topology\n      - Flow Rules\n    properties:\n      - type: Documentation\n        url: https://wiki.onosproject.org/display/ONOS/REST+API\n      - type: Website\n        url: https://onosproject.org/\n\ncommon:\n  - type: Website\n    url: https://opennetworking.org/\n  - type: Reference\n    url: https://en.wikipedia.org/wiki/Software-defined_networking\n  - type: Standard\n    url: https://datatracker.ietf.org/doc/html/rfc7426\n  - type: Reference\n    url: https://www.ciena.com/insights/articles/5-key-APIs-to-enable-the-concept-of-SDN-based-virtual-networks.html\n\
  \  - type: GitHubOrganization\n    url: https://github.com/opendaylight\n  - type: GitHubOrganization\n    url: https://github.com/opennetworkinglab\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/json-ld/software-defined-networking-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/vocabulary/software-defined-networking-vocabulary.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/apis.yml
tags:
- Cloud Infrastructure
- Network Architecture
- Networking
- Virtualization
- SDN
- OpenDaylight
- ONOS
url: https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/apis.yml
use_cases: []
---
