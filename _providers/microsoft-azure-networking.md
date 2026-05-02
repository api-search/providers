---
api_count: 18
apis:
- description: Manage Azure Virtual Networks (VNets) including subnets, peering, and network configurations.
  name: Azure Virtual Networks API
  slug: ''
- description: Distribute traffic across multiple virtual machines and services with Azure Load Balancer.
  name: Azure Load Balancer API
  slug: ''
- description: Web traffic load balancer with application-level routing and SSL termination.
  name: Azure Application Gateway API
  slug: ''
- description: Control network traffic to and from Azure resources with security rules.
  name: Azure Network Security Groups API
  slug: ''
- description: Establish secure cross-premises connectivity between Azure and on-premises networks.
  name: Azure VPN Gateway API
  slug: ''
- description: DNS-based traffic load balancer for distributing traffic globally.
  name: Azure Traffic Manager API
  slug: ''
- description: Create private connections between Azure datacenters and on-premises infrastructure.
  name: Azure ExpressRoute API
  slug: ''
- description: Cloud-native network security service with built-in high availability.
  name: Azure Firewall API
  slug: ''
- description: Host DNS zones and manage DNS records using the Azure DNS REST API. Supports creating, updating, and deleting public DNS zones and record sets for domain name resolution within Azure-managed infrastru
  name: Azure DNS API
  slug: ''
- description: Manage private DNS zones for name resolution within Azure virtual networks. Azure Private DNS provides a reliable and secure DNS service to manage and resolve domain names in a virtual network without
  name: Azure Private DNS API
  slug: ''
- description: Global load balancer and application delivery network that provides fast, reliable, and secure access to web applications. Azure Front Door offers layer 7 load balancing, SSL offload, URL-based routin
  name: Azure Front Door API
  slug: ''
- description: Manage DDoS protection plans that provide enhanced DDoS mitigation capabilities for Azure Virtual Network resources. Azure DDoS Protection provides countermeasures against sophisticated DDoS threats w
  name: Azure DDoS Protection API
  slug: ''
- description: Monitor, diagnose, and gain insights into network performance and health in Azure. Network Watcher provides tools for packet capture, connection troubleshooting, NSG flow logs, and network topology vi
  name: Azure Network Watcher API
  slug: ''
- description: Fully managed PaaS service that provides secure and seamless RDP and SSH connectivity to virtual machines directly through the Azure portal over TLS. Azure Bastion is deployed inside a virtual network
  name: Azure Bastion API
  slug: ''
- description: Simplify outbound-only internet connectivity for virtual networks. When configured on a subnet, all outbound connectivity uses specified static public IP addresses. NAT Gateway provides on-demand SNAT
  name: Azure NAT Gateway API
  slug: ''
- description: Access Azure PaaS services and customer-owned services over a private endpoint in your virtual network. Azure Private Link eliminates data exposure to the public internet by keeping traffic on the Mic
  name: Azure Private Link API
  slug: ''
- description: Networking service that provides optimized and automated branch-to-branch connectivity through Azure. Virtual WAN brings together networking, security, and routing functionalities into a single operat
  name: Azure Virtual WAN API
  slug: ''
- description: Cloud-native web application firewall service that provides centralized protection for web applications from common exploits and vulnerabilities. Azure WAF can be deployed with Application Gateway, Fr
  name: Azure Web Application Firewall API
  slug: ''
common:
- title: ''
  type: X-portal
  url: https://portal.azure.com
- title: ''
  type: X-support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: X-status
  url: https://status.azure.com/
- title: ''
  type: X-blog
  url: https://azure.microsoft.com/en-us/blog/topics/networking/
- title: ''
  type: X-terms-of-service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/networking/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/networking/fundamentals/networking-overview
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/azure/developer/
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure
- title: ''
  type: GitHubRepository
  url: https://github.com/Azure/azure-rest-api-specs
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/azure-virtual-network
- title: ''
  type: Change Log
  url: https://azure.microsoft.com/en-us/updates/?query=networking
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/
- title: ''
  type: Sign Up
  url: https://azure.microsoft.com/en-us/free/
- title: ''
  type: Login
  url: https://portal.azure.com/#home
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow
created: '2024-01-15'
description: A collection of Azure Networking APIs for managing virtual networks, load balancers, application gateways, and network security.
features: []
image: https://azure.microsoft.com/svghandler/azure-networking.svg
integrations: []
layout: provider
modified: '2026-04-28'
name: Azure Networking
skills: []
slug: microsoft-azure-networking
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Networking\ndescription: >-\n  A collection of Azure Networking APIs for managing virtual networks, load balancers,\n  application gateways, and network security.\nimage: https://azure.microsoft.com/svghandler/azure-networking.svg\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\ntags:\n  - Azure\n  - Cloud\n  - Infrastructure\n  - Microsoft\n  - Networking\napis:\n  - name: Azure Virtual Networks API\n    description: >-\n      Manage Azure Virtual Networks (VNets) including subnets, peering, and network\n      configurations.\n    image: https://azure.microsoft.com/svghandler/virtual-network.svg\n    humanURL: https://azure.microsoft.com/en-us/services/virtual-network/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks\n    tags:\n      - Peering\n      - Subnets\n      - Virtual Networks\n      - Vnet\n    properties:\n      - type:\
  \ X-documentation\n        url: https://docs.microsoft.com/en-us/rest/api/virtualnetwork/\n      - type: X-openapi\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/network/resource-manager/Microsoft.Network/stable/2023-05-01/virtualNetwork.json\n      - type: X-pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/virtual-network/\n      - type: X-authentication\n        url: https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/virtualnetwork/\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/virtual-network/quickstart-create-virtual-network\n  - name: Azure Load Balancer API\n    description: >-\n      Distribute traffic across multiple virtual machines and services with Azure\n      Load Balancer.\n    image: https://azure.microsoft.com/svghandler/load-balancer.svg\n\
  \    humanURL: https://azure.microsoft.com/en-us/services/load-balancer/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/loadBalancers\n    tags:\n      - High Availability\n      - Load Balancer\n      - Traffic Distribution\n    properties:\n      - type: X-documentation\n        url: https://docs.microsoft.com/en-us/rest/api/load-balancer/\n      - type: X-openapi\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/network/resource-manager/Microsoft.Network/stable/2023-05-01/loadBalancer.json\n      - type: X-pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/load-balancer/\n      - type: X-authentication\n        url: https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/load-balancer/\n  - name: Azure Application\
  \ Gateway API\n    description: >-\n      Web traffic load balancer with application-level routing and SSL termination.\n    image: https://azure.microsoft.com/svghandler/application-gateway.svg\n    humanURL: https://azure.microsoft.com/en-us/services/application-gateway/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/applicationGateways\n    tags:\n      - Application Gateway\n      - Layer 7 Load Balancing\n      - Ssl Termination\n      - Web Application Firewall\n    properties:\n      - type: X-documentation\n        url: https://docs.microsoft.com/en-us/rest/api/application-gateway/\n      - type: X-openapi\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/network/resource-manager/Microsoft.Network/stable/2023-05-01/applicationGateway.json\n      - type: X-pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/application-gateway/\n\
  \      - type: X-authentication\n        url: https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/application-gateway/\n  - name: Azure Network Security Groups API\n    description: >-\n      Control network traffic to and from Azure resources with security rules.\n    image: https://azure.microsoft.com/svghandler/network-security-groups.svg\n    humanURL: https://azure.microsoft.com/en-us/services/network-security-groups/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups\n    tags:\n      - Firewall\n      - Network Security Groups\n      - Nsg\n      - Security\n    properties:\n      - type: X-documentation\n        url: https://docs.microsoft.com/en-us/rest/api/virtualnetwork/networksecuritygroups\n      - type: X-openapi\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/network/resource-manager/Microsoft.Network/stable/2023-05-01/networkSecurityGroup.json\n\
  \      - type: X-pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/virtual-network/\n      - type: X-authentication\n        url: https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/virtualnetwork/networksecuritygroups\n  - name: Azure VPN Gateway API\n    description: >-\n      Establish secure cross-premises connectivity between Azure and on-premises networks.\n    image: https://azure.microsoft.com/svghandler/vpn-gateway.svg\n    humanURL: https://azure.microsoft.com/en-us/services/vpn-gateway/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways\n    tags:\n      - Gateway\n      - Hybrid Connectivity\n      - Site-To-Site\n      - Vpn\n    properties:\n      - type: X-documentation\n        url: https://docs.microsoft.com/en-us/rest/api/network-gateway/\n\
  \      - type: X-openapi\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/network/resource-manager/Microsoft.Network/stable/2023-05-01/virtualNetworkGateway.json\n      - type: X-pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/vpn-gateway/\n      - type: X-authentication\n        url: https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/network-gateway/\n  - name: Azure Traffic Manager API\n    description: >-\n      DNS-based traffic load balancer for distributing traffic globally.\n    image: https://azure.microsoft.com/svghandler/traffic-manager.svg\n    humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficManagerProfiles\n    tags:\n  \
  \    - Dns\n      - Failover\n      - Global Load Balancing\n      - Traffic Manager\n    properties:\n      - type: X-documentation\n        url: https://docs.microsoft.com/en-us/rest/api/trafficmanager/\n      - type: X-openapi\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/trafficmanager/resource-manager/Microsoft.Network/stable/2022-04-01/trafficmanager.json\n      - type: X-pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/traffic-manager/\n      - type: X-authentication\n        url: https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/trafficmanager/\n  - name: Azure ExpressRoute API\n    description: >-\n      Create private connections between Azure datacenters and on-premises infrastructure.\n    image: https://azure.microsoft.com/svghandler/expressroute.svg\n    humanURL: https://azure.microsoft.com/en-us/services/expressroute/\n\
  \    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits\n    tags:\n      - Dedicated Connection\n      - Expressroute\n      - Hybrid\n      - Private Connectivity\n    properties:\n      - type: X-documentation\n        url: https://docs.microsoft.com/en-us/rest/api/expressroute/\n      - type: X-openapi\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/network/resource-manager/Microsoft.Network/stable/2023-05-01/expressRouteCircuit.json\n      - type: X-pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/expressroute/\n      - type: X-authentication\n        url: https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/expressroute/\n  - name: Azure Firewall API\n    description: >-\n      Cloud-native network\
  \ security service with built-in high availability.\n    image: https://azure.microsoft.com/svghandler/azure-firewall.svg\n    humanURL: https://azure.microsoft.com/en-us/services/azure-firewall/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/azureFirewalls\n    tags:\n      - Firewall\n      - Network Security\n      - Security\n      - Threat Protection\n    properties:\n      - type: X-documentation\n        url: https://docs.microsoft.com/en-us/rest/api/firewall/\n      - type: X-openapi\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/network/resource-manager/Microsoft.Network/stable/2023-05-01/azureFirewall.json\n      - type: X-pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/azure-firewall/\n      - type: X-authentication\n        url: https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n\
  \      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/firewall/\n  - name: Azure DNS API\n    description: >-\n      Host DNS zones and manage DNS records using the Azure DNS REST API. Supports\n      creating, updating, and deleting public DNS zones and record sets for domain\n      name resolution within Azure-managed infrastructure.\n    image: https://azure.microsoft.com/svghandler/azure-networking.svg\n    humanURL: https://learn.microsoft.com/en-us/azure/dns/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/dnsZones\n    tags:\n      - DNS\n      - Domain Name System\n      - Records\n      - Zones\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/dns/\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/dns/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n\
  \  - name: Azure Private DNS API\n    description: >-\n      Manage private DNS zones for name resolution within Azure virtual networks.\n      Azure Private DNS provides a reliable and secure DNS service to manage and\n      resolve domain names in a virtual network without needing a custom DNS solution.\n    image: https://azure.microsoft.com/svghandler/azure-networking.svg\n    humanURL: https://learn.microsoft.com/en-us/azure/dns/private-dns-overview\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/privateDnsZones\n    tags:\n      - DNS\n      - Name Resolution\n      - Private DNS\n      - Virtual Networks\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/dns/privatedns/private-zones\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n  - name: Azure Front Door\
  \ API\n    description: >-\n      Global load balancer and application delivery network that provides fast,\n      reliable, and secure access to web applications. Azure Front Door offers\n      layer 7 load balancing, SSL offload, URL-based routing, and Web Application\n      Firewall integration.\n    image: https://azure.microsoft.com/svghandler/azure-networking.svg\n    humanURL: https://learn.microsoft.com/en-us/azure/frontdoor/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/frontDoors\n    tags:\n      - CDN\n      - Front Door\n      - Global Load Balancing\n      - Web Application Firewall\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/frontdoor/\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/frontdoor/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n\
  \  - name: Azure DDoS Protection API\n    description: >-\n      Manage DDoS protection plans that provide enhanced DDoS mitigation\n      capabilities for Azure Virtual Network resources. Azure DDoS Protection\n      provides countermeasures against sophisticated DDoS threats with adaptive\n      tuning, attack analytics, and alerting.\n    image: https://azure.microsoft.com/svghandler/azure-networking.svg\n    humanURL: https://learn.microsoft.com/en-us/azure/ddos-protection/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/ddosProtectionPlans\n    tags:\n      - DDoS Protection\n      - Network Security\n      - Security\n      - Threat Mitigation\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/virtualnetwork/ddos-protection-plans\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/ddos-protection/\n      -\
  \ type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n  - name: Azure Network Watcher API\n    description: >-\n      Monitor, diagnose, and gain insights into network performance and health in\n      Azure. Network Watcher provides tools for packet capture, connection\n      troubleshooting, NSG flow logs, and network topology visualization.\n    image: https://azure.microsoft.com/svghandler/azure-networking.svg\n    humanURL: https://learn.microsoft.com/en-us/azure/network-watcher/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers\n    tags:\n      - Diagnostics\n      - Flow Logs\n      - Network Monitoring\n      - Packet Capture\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/network-watcher/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n\
  \  - name: Azure Bastion API\n    description: >-\n      Fully managed PaaS service that provides secure and seamless RDP and SSH\n      connectivity to virtual machines directly through the Azure portal over TLS.\n      Azure Bastion is deployed inside a virtual network and does not require a\n      public IP on the target VM.\n    image: https://azure.microsoft.com/svghandler/azure-networking.svg\n    humanURL: https://learn.microsoft.com/en-us/azure/bastion/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/bastionHosts\n    tags:\n      - Bastion\n      - RDP\n      - Remote Access\n      - Secure Connectivity\n      - SSH\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/virtualnetwork/bastion-hosts\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/azure-bastion/\n      - type: Authentication\n        url:\
  \ https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n  - name: Azure NAT Gateway API\n    description: >-\n      Simplify outbound-only internet connectivity for virtual networks. When\n      configured on a subnet, all outbound connectivity uses specified static\n      public IP addresses. NAT Gateway provides on-demand SNAT port allocation\n      without the need for a load balancer or directly attached public IPs.\n    image: https://azure.microsoft.com/svghandler/azure-networking.svg\n    humanURL: https://learn.microsoft.com/en-us/azure/nat-gateway/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/natGateways\n    tags:\n      - IP Address Management\n      - NAT Gateway\n      - Outbound Connectivity\n      - SNAT\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/virtualnetwork/nat-gateways\n      - type:\
  \ Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/azure-nat-gateway/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n  - name: Azure Private Link API\n    description: >-\n      Access Azure PaaS services and customer-owned services over a private\n      endpoint in your virtual network. Azure Private Link eliminates data\n      exposure to the public internet by keeping traffic on the Microsoft\n      global network.\n    image: https://azure.microsoft.com/svghandler/azure-networking.svg\n    humanURL: https://learn.microsoft.com/en-us/azure/private-link/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/privateLinkServices\n    tags:\n      - Network Isolation\n      - Private Endpoint\n      - Private Link\n      - Security\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/virtualnetwork/private-link-services\n\
  \      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/private-link/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n  - name: Azure Virtual WAN API\n    description: >-\n      Networking service that provides optimized and automated branch-to-branch\n      connectivity through Azure. Virtual WAN brings together networking,\n      security, and routing functionalities into a single operational interface\n      including VPN, ExpressRoute, and point-to-site connectivity.\n    image: https://azure.microsoft.com/svghandler/azure-networking.svg\n    humanURL: https://learn.microsoft.com/en-us/azure/virtual-wan/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualWans\n    tags:\n      - Branch Connectivity\n      - Hybrid Networking\n      - SD-WAN\n      - Virtual WAN\n    properties:\n\
  \      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/virtualwan/\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/virtual-wan/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n  - name: Azure Web Application Firewall API\n    description: >-\n      Cloud-native web application firewall service that provides centralized\n      protection for web applications from common exploits and vulnerabilities.\n      Azure WAF can be deployed with Application Gateway, Front Door, and CDN\n      for layer 7 protection.\n    image: https://azure.microsoft.com/svghandler/azure-networking.svg\n    humanURL: https://learn.microsoft.com/en-us/azure/web-application-firewall/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/ApplicationGatewayWebApplicationFirewallPolicies\n\
  \    tags:\n      - Application Protection\n      - Security\n      - WAF\n      - Web Application Firewall\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/application-gateway/web-application-firewall-policies\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/web-application-firewall/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\ncommon:\n  - type: X-portal\n    url: https://portal.azure.com\n  - type: X-support\n    url: https://azure.microsoft.com/en-us/support/\n  - type: X-status\n    url: https://status.azure.com/\n  - type: X-blog\n    url: https://azure.microsoft.com/en-us/blog/topics/networking/\n  - type: X-terms-of-service\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: Portal\n    url: https://portal.azure.com\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/networking/\n\
  \  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/networking/fundamentals/networking-overview\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: SDKs\n    url: https://learn.microsoft.com/en-us/azure/developer/\n  - type: GitHub Organization\n    url: https://github.com/Azure\n  - type: GitHubRepository\n    url: https://github.com/Azure/azure-rest-api-specs\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/azure-virtual-network\n  - type: Change Log\n    url: https://azure.microsoft.com/en-us/updates/?query=networking\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/\n  - type: Sign Up\n    url: https://azure.microsoft.com/en-us/free/\n  - type: Login\n    url: https://portal.azure.com/#home\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\
  \    url: https://azure.microsoft.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-networking/refs/heads/main/apis.yml
tags:
- Azure
- Cloud
- Infrastructure
- Microsoft
- Networking
url: ''
use_cases: []
---
