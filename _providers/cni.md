---
api_count: 2
apis:
- description: The CNI specification defines the interface between container runtimes and network plugins. It specifies how runtimes invoke plugins via environment variables (CNI_COMMAND, CNI_CONTAINERID, CNI_NETNS,
  name: CNI Specification
  slug: cni-spec
- description: A collection of reference and example networking plugins maintained by the containernetworking team that implement the CNI specification. Includes main plugins such as bridge, ipvlan, macvlan, ptp, ho
  name: CNI Reference Plugins
  slug: cni-plugins
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.cni.dev/
- title: ''
  type: Documentation
  url: https://www.cni.dev/docs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/containernetworking
- title: ''
  type: GitHubRepository
  url: https://github.com/containernetworking/cni
- title: ''
  type: GitHubRepository
  url: https://github.com/containernetworking/plugins
- title: ''
  type: JSONLDContext
  url: json-ld/cni-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cni-network-config-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cni-result-schema.json
- title: ''
  type: NaftikoCapabilities
  url: capabilities/cni-spec-capabilities.yml
created: '2026-03-16'
description: CNI (Container Network Interface) is a CNCF-incubating project that defines a specification and libraries for configuring network interfaces in Linux containers. It provides a simple exec/stdin interface between the container runtime and network implementation plugins, enabling pluggable networking for Kubernetes and other container orchestrators. The CNI spec defines four operations (ADD, DEL, CHECK, VERSION), a network configuration document format, and a plugin Result document. CNI also publishes a collection of reference plugins (bridge, ipvlan, macvlan, host-device, ptp, loopback) and meta-plugins (portmap, bandwidth, firewall, sbr).
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cni Context
  property_count: 11
  slug: cni-context
layout: provider
modified: '2026-04-23'
name: Container Network Interface (CNI)
skills: []
slug: cni
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cni\nname: Container Network Interface (CNI)\nx-type: opensource\ndescription: >-\n  CNI (Container Network Interface) is a CNCF-incubating project that defines a\n  specification and libraries for configuring network interfaces in Linux\n  containers. It provides a simple exec/stdin interface between the container\n  runtime and network implementation plugins, enabling pluggable networking for\n  Kubernetes and other container orchestrators. The CNI spec defines four\n  operations (ADD, DEL, CHECK, VERSION), a network configuration document\n  format, and a plugin Result document. CNI also publishes a collection of\n  reference plugins (bridge, ipvlan, macvlan, host-device, ptp, loopback) and\n  meta-plugins (portmap, bandwidth, firewall, sbr).\nurl: https://www.cni.dev\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Containers\n  - Incubating\n  - Kubernetes\n  - Networking\n  - Plugins\ncreated: '2026-03-16'\n\
  modified: '2026-04-23'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: cni:cni-spec\n    name: CNI Specification\n    description: >-\n      The CNI specification defines the interface between container runtimes\n      and network plugins. It specifies how runtimes invoke plugins via\n      environment variables (CNI_COMMAND, CNI_CONTAINERID, CNI_NETNS,\n      CNI_IFNAME, CNI_PATH, CNI_ARGS) and stdin configuration, and how plugins\n      respond on stdout with network interface details. The spec covers ADD,\n      DEL, CHECK, and VERSION operations for managing container network\n      attachments, and defines the plugin chaining model used by meta-plugins.\n    humanURL: https://www.cni.dev/docs/spec/\n    properties:\n      - type: Documentation\n        url: https://www.cni.dev/docs/spec/\n      - type: GitHubRepository\n        url: https://github.com/containernetworking/cni\n      - type: JSONSchema\n        url: json-schema/cni-network-config-schema.json\n      - type:\
  \ JSONSchema\n        url: json-schema/cni-result-schema.json\n      - type: JSONLDContext\n        url: json-ld/cni-context.jsonld\n      - type: NaftikoCapabilities\n        url: capabilities/cni-spec-capabilities.yml\n    tags:\n      - Network Plugins\n      - Specification\n    x-features:\n      - name: ADD operation\n        description: Attach a container to a network and return a Result document with assigned interfaces, IPs, routes, and DNS.\n      - name: DEL operation\n        description: Detach a container from a network and tear down allocated resources.\n      - name: CHECK operation\n        description: Verify the container's current attachment matches the prior ADD result.\n      - name: VERSION operation\n        description: Report the CNI spec versions a plugin supports.\n      - name: Plugin Chaining\n        description: Meta-plugin chaining model where a chain shares previous Result via prevResult.\n      - name: Network Config Schema\n        description: Schema\
  \ for the JSON document that describes a network and its plugin chain.\n      - name: Result Schema\n        description: Schema for the Result document that plugins emit on stdout.\n    x-useCases:\n      - name: Kubernetes CNI Plugin\n        description: Implement a CNI plugin that integrates with Kubernetes / containerd / CRI-O.\n      - name: Network Validation\n        description: Validate network configurations and plugin Result documents against the spec.\n      - name: Custom SDN\n        description: Build custom software-defined networks for containers using a portable plugin contract.\n  - aid: cni:cni-plugins\n    name: CNI Reference Plugins\n    description: >-\n      A collection of reference and example networking plugins maintained by\n      the containernetworking team that implement the CNI specification.\n      Includes main plugins such as bridge, ipvlan, macvlan, ptp, host-device,\n      and loopback, as well as meta plugins such as portmap, bandwidth,\n      firewall,\
  \ sbr, and tuning for additional networking functionality.\n    humanURL: https://www.cni.dev/plugins/current/\n    properties:\n      - type: Documentation\n        url: https://www.cni.dev/plugins/current/\n      - type: GitHubRepository\n        url: https://github.com/containernetworking/plugins\n      - type: NaftikoCapabilities\n        url: capabilities/cni-spec-capabilities.yml\n    tags:\n      - Containers\n      - Kubernetes\n      - Linux\n      - Network Plugins\n      - Networking\n    x-features:\n      - name: bridge\n        description: Linux-bridge plugin attaching container veth pairs to a bridge.\n      - name: ipvlan\n        description: IPVLAN plugin for L2/L3 IPVLAN attachments.\n      - name: macvlan\n        description: MACVLAN plugin for MACVLAN attachments.\n      - name: host-device\n        description: Plugin that moves an existing host device into a container netns.\n      - name: ptp\n        description: Point-to-point veth-pair plugin.\n      - name:\
  \ loopback\n        description: Loopback interface configuration.\n      - name: portmap\n        description: Meta-plugin that publishes container ports to the host via NAT.\n      - name: bandwidth\n        description: Meta-plugin that applies ingress/egress traffic shaping with tc.\n      - name: firewall\n        description: Meta-plugin that applies iptables/nftables rules for a container.\n      - name: sbr\n        description: Source-based routing meta-plugin.\n    x-useCases:\n      - name: Kubernetes Pod Networking\n        description: Use bridge + portmap as a minimal Kubernetes pod networking stack.\n      - name: Multi-Network Pods\n        description: Combine reference plugins via Multus or chains for multi-NIC pods.\ncommon:\n  - type: Website\n    url: https://www.cni.dev/\n  - type: Documentation\n    url: https://www.cni.dev/docs/\n  - type: GitHubOrganization\n    url: https://github.com/containernetworking\n  - type: GitHubRepository\n    url: https://github.com/containernetworking/cni\n\
  \  - type: GitHubRepository\n    url: https://github.com/containernetworking/plugins\n  - type: JSONLDContext\n    url: json-ld/cni-context.jsonld\n  - type: JSONSchema\n    url: json-schema/cni-network-config-schema.json\n  - type: JSONSchema\n    url: json-schema/cni-result-schema.json\n  - type: NaftikoCapabilities\n    url: capabilities/cni-spec-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cni/refs/heads/main/apis.yml
tags:
- Cloud Native
- Containers
- Incubating
- Kubernetes
- Networking
- Plugins
url: https://www.cni.dev
use_cases: []
---
