---
api_count: 4
apis:
- description: NordVPN's public API provides server listings, recommendations, and user credential retrieval for programmatic VPN configuration, especially useful for WireGuard (NordLynx) configuration generation.
  name: NordVPN API
  slug: nordvpn-api
- description: Tailscale provides a REST API for managing tailnets (private mesh networks), devices, users, access control lists, and network configuration. Built on WireGuard, Tailscale enables zero-configuration V
  name: Tailscale API
  slug: tailscale-api
- description: AWS Site-to-Site VPN and AWS Client VPN provide managed VPN solutions on AWS infrastructure. Managed via the AWS EC2 API and AWS CLI for creating virtual private gateways, customer gateways, and VPN c
  name: AWS VPN API
  slug: aws-vpn
- description: Azure VPN Gateway provides managed site-to-site, point-to-site, and VNet-to-VNet VPN connections. Managed via Azure Resource Manager REST API and Azure CLI.
  name: Azure VPN Gateway API
  slug: azure-vpn
common:
- title: ''
  type: Reference
  url: https://en.wikipedia.org/wiki/Virtual_private_network
- title: ''
  type: Standard
  url: https://www.wireguard.com/
- title: ''
  type: Standard
  url: https://openvpn.net/
- title: ''
  type: Portal
  url: https://tailscale.com/
- title: ''
  type: Website
  url: https://www.nordvpn.com/
- title: ''
  type: Website
  url: https://protonvpn.com/
- title: ''
  type: OpenSource
  url: https://github.com/qdm12/gluetun
created: '2025'
description: A VPN (Virtual Private Network) creates an encrypted tunnel between a user's device and a remote network, protecting data from interception and masking the user's IP address. VPN technology is widely used for secure remote access to corporate networks, protecting privacy on public Wi-Fi, and bypassing geographic content restrictions. This index documents VPN providers, protocols, and APIs relevant to the VPN technology landscape including NordVPN, OpenVPN, WireGuard, Tailscale, and cloud provider VPN services.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Vpn Context
  property_count: 7
  slug: vpn-context
layout: provider
modified: '2026-05-03'
name: VPN
skills: []
slug: vpn
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vpn\nname: VPN\ndescription: >-\n  A VPN (Virtual Private Network) creates an encrypted tunnel between a user's\n  device and a remote network, protecting data from interception and masking the\n  user's IP address. VPN technology is widely used for secure remote access to\n  corporate networks, protecting privacy on public Wi-Fi, and bypassing geographic\n  content restrictions. This index documents VPN providers, protocols, and APIs\n  relevant to the VPN technology landscape including NordVPN, OpenVPN, WireGuard,\n  Tailscale, and cloud provider VPN services.\ntags:\n  - Encryption\n  - Networking\n  - Privacy\n  - Security\n  - VPN\ntype: Index\nurl: https://en.wikipedia.org/wiki/Virtual_private_network\napis:\n  - aid: vpn:nordvpn-api\n    name: NordVPN API\n    tags:\n      - Encryption\n      - Networking\n      - Privacy\n      - Security\n      - VPN\n    humanURL: https://api.nordvpn.com/\n    baseURL: https://api.nordvpn.com/v1\n    description: >-\n      NordVPN's\
  \ public API provides server listings, recommendations, and user\n      credential retrieval for programmatic VPN configuration, especially useful\n      for WireGuard (NordLynx) configuration generation.\n    properties:\n      - url: https://api.nordvpn.com/v1/servers\n        type: DataFeed\n        description: NordVPN server list endpoint.\n      - url: https://api.nordvpn.com/v1/servers/recommendations\n        type: DataFeed\n        description: NordVPN recommended server endpoint.\n      - url: https://sleeplessbeastie.eu/2019/02/18/how-to-use-public-nordvpn-api/\n        type: Documentation\n        description: Community documentation for the NordVPN public API.\n\n  - aid: vpn:tailscale-api\n    name: Tailscale API\n    tags:\n      - Encryption\n      - Mesh Network\n      - Networking\n      - Privacy\n      - Security\n      - VPN\n      - WireGuard\n      - Zero Trust\n    humanURL: https://tailscale.com/api\n    baseURL: https://api.tailscale.com/api/v2\n    description:\
  \ >-\n      Tailscale provides a REST API for managing tailnets (private mesh networks),\n      devices, users, access control lists, and network configuration. Built on\n      WireGuard, Tailscale enables zero-configuration VPN for teams and organizations.\n    properties:\n      - url: https://tailscale.com/api\n        type: Documentation\n        description: Official Tailscale API documentation.\n      - url: https://api.tailscale.com/api/v2\n        type: BaseURL\n        description: Tailscale API v2 base URL.\n\n  - aid: vpn:aws-vpn\n    name: AWS VPN API\n    tags:\n      - AWS\n      - Cloud\n      - Encryption\n      - Networking\n      - Security\n      - VPN\n    humanURL: https://docs.aws.amazon.com/vpn/\n    baseURL: https://ec2.amazonaws.com/\n    description: >-\n      AWS Site-to-Site VPN and AWS Client VPN provide managed VPN solutions on\n      AWS infrastructure. Managed via the AWS EC2 API and AWS CLI for creating\n      virtual private gateways, customer gateways,\
  \ and VPN connections.\n    properties:\n      - url: https://docs.aws.amazon.com/vpn/latest/s2svpn/VPC_VPN.html\n        type: Documentation\n        description: AWS Site-to-Site VPN documentation.\n      - url: https://docs.aws.amazon.com/vpn/latest/clientvpn-admin/\n        type: Documentation\n        description: AWS Client VPN documentation.\n\n  - aid: vpn:azure-vpn\n    name: Azure VPN Gateway API\n    tags:\n      - Azure\n      - Cloud\n      - Encryption\n      - Networking\n      - Security\n      - VPN\n    humanURL: https://learn.microsoft.com/en-us/azure/vpn-gateway/\n    baseURL: https://management.azure.com/\n    description: >-\n      Azure VPN Gateway provides managed site-to-site, point-to-site, and VNet-to-VNet\n      VPN connections. Managed via Azure Resource Manager REST API and Azure CLI.\n    properties:\n      - url: https://learn.microsoft.com/en-us/azure/vpn-gateway/\n        type: Documentation\n        description: Azure VPN Gateway documentation.\n    \
  \  - url: https://learn.microsoft.com/en-us/rest/api/network/vpn-gateways\n        type: Documentation\n        description: Azure VPN Gateways REST API reference.\n\naccess: 3rd-Party\ncreated: '2025'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ncommon:\n  - url: https://en.wikipedia.org/wiki/Virtual_private_network\n    name: VPN Wikipedia Article\n    type: Reference\n    description: Comprehensive reference on VPN technology and protocols.\n  - url: https://www.wireguard.com/\n    name: WireGuard Protocol\n    type: Standard\n    description: Modern, high-performance VPN protocol standard.\n  - url: https://openvpn.net/\n    name: OpenVPN\n    type: Standard\n    description: Open-source VPN protocol and software suite.\n  - url: https://tailscale.com/\n    name: Tailscale\n    type: Portal\n    description: WireGuard-based mesh VPN for teams with REST management API.\n  - url: https://www.nordvpn.com/\n    name: NordVPN\n    type: Website\n    description: Commercial VPN\
  \ provider with public server API.\n  - url: https://protonvpn.com/\n    name: ProtonVPN\n    type: Website\n    description: Privacy-focused VPN provider by the Proton team.\n  - url: https://github.com/qdm12/gluetun\n    name: Gluetun\n    type: OpenSource\n    description: Docker VPN client supporting multiple providers via OpenVPN and WireGuard.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vpn/refs/heads/main/apis.yml
tags:
- Encryption
- Networking
- Privacy
- Security
- VPN
url: https://en.wikipedia.org/wiki/Virtual_private_network
use_cases: []
---
