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
