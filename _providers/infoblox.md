---
api_count: 17
api_specs:
- filename: infoblox-wapi-openapi.yml
  format: yaml
  label: Infoblox WAPI (Web API)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/infoblox/refs/heads/main/openapi/infoblox-wapi-openapi.yml
- filename: openapi.yaml
  format: yaml
  label: Infoblox BloxOne API
  slug: ''
  spec_type: OpenAPI
  url: https://csp.infoblox.com/apidoc/
apis:
- description: RESTful API for managing Infoblox NIOS DDI (DNS, DHCP, IPAM) services, network objects, and configuration. The WAPI uses standard HTTP methods for CRUD operations and supports JSON and XML input and o
  name: Infoblox WAPI (Web API)
  slug: ''
- description: 'Cloud-native API for Infoblox BloxOne DDI and Threat Defense services. Provides RESTful web services for interacting with the Infoblox Cloud Service Platform (CSP) to manage and automate DDI services '
  name: Infoblox BloxOne API
  slug: ''
- description: API for configuring DNS settings within the BloxOne platform. Manages DNS server configurations, views, ACLs, forwarding rules, and other DNS infrastructure settings through the Cloud Service Platform
  name: Infoblox BloxOne DNS Configuration API
  slug: ''
- description: API for managing DNS data records within the BloxOne platform. Provides endpoints for creating, reading, updating, and deleting DNS resource records including A, AAAA, CNAME, MX, TXT, and other record
  name: Infoblox BloxOne DNS Data API
  slug: ''
- description: API for IP address management and DHCP protocol features within the BloxOne platform. Provides visibility and provisioning tools to manage networking spaces, monitoring and reporting of IP address inf
  name: Infoblox BloxOne IPAM/DHCP API
  slug: ''
- description: API for managing TSIG and other keys used in DDI operations within the BloxOne platform. Handles creation and management of authentication keys used for securing DNS zone transfers and dynamic updates
  name: Infoblox BloxOne DDI Keys API
  slug: ''
- description: API for managing anycast configurations within the BloxOne platform. Enables high availability configuration of Infoblox applications running on customer premises by managing anycast addressing and ro
  name: Infoblox BloxOne Anycast Configuration API
  slug: ''
- description: API for managing BloxOne Cloud infrastructure components. Provides endpoints for managing on-premises hosts, service configurations, and infrastructure resources within the Infoblox Cloud Service Plat
  name: Infoblox BloxOne Infrastructure Management API
  slug: ''
- description: API for provisioning and activating on-premises hosts within the BloxOne platform. Handles the host activation workflow including zero touch provisioning and bootstrap configuration for on-prem deploy
  name: Infoblox BloxOne Host Activation API
  slug: ''
- description: API for managing DNS Forwarding Proxy (DFP) configurations within BloxOne Threat Defense. Enforces DNS client-based security policies at remote sites by forwarding DNS queries through the Infoblox clo
  name: Infoblox BloxOne DNS Forwarding Proxy API
  slug: ''
- description: API for managing BloxOne Threat Defense Cloud firewall policies and security lists. Provides visibility into infected and compromised devices on the network and allows management of security policies,
  name: Infoblox BloxOne Firewall API
  slug: ''
- description: API for configuring BloxOne Threat Defense Cloud redirect behavior. Allows configuring traffic redirection to the Infoblox server or custom destinations when threats are detected, and manages redirect
  name: Infoblox BloxOne Redirect API
  slug: ''
- description: API for managing software upgrade policies for BloxOne on-premises hosts. Allows scheduling and configuring software and configuration updates for deployed BloxOne infrastructure components.
  name: Infoblox BloxOne Upgrade Policy API
  slug: ''
- description: 'API for threat intelligence, security analytics, and DNS firewall capabilities. Provides programmatic access to BloxOne Threat Defense features including security policy management, threat feeds, and '
  name: Infoblox Threat Defense API
  slug: ''
- description: 'Threat Intelligence Data Exchange (TIDE) API for submitting and retrieving threat indicators. Provides access to indicators of compromise in the TIDE database in multiple formats including JSON, XML, '
  name: Infoblox TIDE API
  slug: ''
- description: Threat research API that provides contextual information from multiple sources simultaneously for a given indicator. Supports lookups on IPs, URLs, domains, hostnames, email addresses, and file hashes
  name: Infoblox Dossier API
  slug: ''
- description: RESTful API for the Infoblox NetMRI network change and configuration management platform. Enables automation of network device provisioning, security compliance checks, configuration management, and n
  name: Infoblox NetMRI API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://www.infoblox.com/developer-portal/
- title: ''
  type: Getting Started
  url: https://www.infoblox.com/developer-portal/getting-started/
- title: ''
  type: Documentation
  url: https://docs.infoblox.com/
- title: ''
  type: Blog
  url: https://blogs.infoblox.com/
- title: ''
  type: Community
  url: https://community.infoblox.com/
- title: ''
  type: Status
  url: https://status.infoblox.com/
- title: ''
  type: Support
  url: https://www.infoblox.com/support/
- title: ''
  type: Website
  url: https://www.infoblox.com/
- title: ''
  type: Privacy Policy
  url: https://www.infoblox.com/company/legal/privacy-policy/
- title: ''
  type: Terms of Service
  url: https://www.infoblox.com/company/legal/website-terms-and-conditions/
- title: ''
  type: GitHub Organization
  url: https://github.com/infobloxopen
- title: ''
  type: Change Log
  url: https://docs.infoblox.com/space/BloxOneInfrastructure/332366018/BloxOne+Release+Notes
- title: ''
  type: Console
  url: https://csp.infoblox.com/
created: '2024-01-15'
description: Infoblox is a networking and cybersecurity company providing DDI (DNS, DHCP, and IPAM) solutions and protective DNS-layer security services. Its product portfolio spans the Universal DDI suite for unified hybrid and multi-cloud network services, NIOS DDI for on-premises deployments, NIOS-X as a Service, Threat Defense for DNS-layer security, threat intelligence (TIDE) and research (Dossier), and NetMRI for network change and configuration management.
features: []
image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg
integrations: []
layout: provider
modified: '2026-04-28'
name: Infoblox
skills: []
slug: infoblox
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: infoblox\nname: Infoblox\ndescription: >-\n  Infoblox is a networking and cybersecurity company providing DDI (DNS, DHCP,\n  and IPAM) solutions and protective DNS-layer security services. Its product\n  portfolio spans the Universal DDI suite for unified hybrid and multi-cloud\n  network services, NIOS DDI for on-premises deployments, NIOS-X as a Service,\n  Threat Defense for DNS-layer security, threat intelligence (TIDE) and\n  research (Dossier), and NetMRI for network change and configuration\n  management.\nimage: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/infoblox/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\napis:\n  - name: Infoblox WAPI (Web API)\n    description: >-\n      RESTful API for managing Infoblox NIOS DDI (DNS, DHCP, IPAM) services,\n      network objects, and\
  \ configuration. The WAPI uses standard HTTP methods\n      for CRUD operations and supports JSON and XML input and output formats.\n    image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://www.infoblox.com/products/ddi/\n    baseURL: https://{grid-master}/wapi/v2.12\n    tags:\n      - DDI\n      - DHCP\n      - DNS\n      - IPAM\n      - Network Management\n    properties:\n      - type: Documentation\n        url: https://docs.infoblox.com/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/infoblox/refs/heads/main/openapi/infoblox-wapi-openapi.yml\n      - type: Reference\n        url: https://docs.infoblox.com/space/niosapi/\n      - type: Authentication\n        url: https://docs.infoblox.com/space/niosapi/22644231/WAPI+Authentication\n      - type: Swagger\n        url: https://{grid-master}/wapidoc/\n      - type: Reference\n        url: https://docs.infoblox.com/space/nios90/156664532/Using+NIOS+APIs\n\
  \      - type: Change Log\n        url: https://docs.infoblox.com/space/nios90/318210347/What's+New\n      - type: Client Libraries\n        url: https://github.com/infobloxopen/infoblox-go-client\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox BloxOne API\n    description: >-\n      Cloud-native API for Infoblox BloxOne DDI and Threat Defense services.\n      Provides RESTful web services for interacting with the Infoblox Cloud\n      Service Platform (CSP) to manage and automate DDI services in the cloud.\n    image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://www.infoblox.com/products/bloxone-ddi/\n    baseURL: https://csp.infoblox.com/api\n    tags:\n      - Cloud\n      - DHCP\n      - DNS\n      - IPAM\n      - Security\n      - Threat Defense\n    properties:\n      - type: Documentation\n        url: https://docs.infoblox.com/space/BloxOneDDI/\n\
  \      - type: OpenAPI\n        url: https://csp.infoblox.com/apidoc/\n      - type: API Portal\n        url: https://csp.infoblox.com/\n      - type: Authentication\n        url: https://docs.infoblox.com/space/BloxOneDDI/35430405/Authentication\n      - type: Getting Started\n        url: https://www.infoblox.com/developer-portal/getting-started/\n      - type: Reference\n        url: https://docs.infoblox.com/space/BloxOneDDI/186745633/Universal+DDI+API+Guide\n      - type: Change Log\n        url: https://docs.infoblox.com/space/BloxOneInfrastructure/332366018/BloxOne+Release+Notes\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox BloxOne DNS Configuration API\n    description: >-\n      API for configuring DNS settings within the BloxOne platform. Manages DNS\n      server configurations, views, ACLs, forwarding rules, and other DNS\n      infrastructure settings through the Cloud Service\
  \ Platform.\n    image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://csp.infoblox.com/apidoc/?url=https%3A%2F%2Fcsp.infoblox.com%2Fapidoc%2Fdocs%2FDnsConfig\n    baseURL: https://csp.infoblox.com/api/ddi/v1\n    tags:\n      - Cloud\n      - Configuration\n      - DNS\n    properties:\n      - type: Documentation\n        url: https://csp.infoblox.com/apidoc/?url=https%3A%2F%2Fcsp.infoblox.com%2Fapidoc%2Fdocs%2FDnsConfig\n      - type: Authentication\n        url: https://docs.infoblox.com/space/BloxOneDDI/35430405/Authentication\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox BloxOne DNS Data API\n    description: >-\n      API for managing DNS data records within the BloxOne platform. Provides\n      endpoints for creating, reading, updating, and deleting DNS resource\n      records including A, AAAA, CNAME, MX, TXT, and other record types.\n  \
  \  image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://csp.infoblox.com/apidoc/?url=https%3A%2F%2Fcsp.infoblox.com%2Fapidoc%2Fdocs%2FDnsData\n    baseURL: https://csp.infoblox.com/api/ddi/v1\n    tags:\n      - Cloud\n      - DNS\n      - Records\n    properties:\n      - type: Documentation\n        url: https://csp.infoblox.com/apidoc/?url=https%3A%2F%2Fcsp.infoblox.com%2Fapidoc%2Fdocs%2FDnsData\n      - type: Authentication\n        url: https://docs.infoblox.com/space/BloxOneDDI/35430405/Authentication\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox BloxOne IPAM/DHCP API\n    description: >-\n      API for IP address management and DHCP protocol features within the\n      BloxOne platform. Provides visibility and provisioning tools to manage\n      networking spaces, monitoring and reporting of IP address infrastructures,\n      and integration\
  \ with DNS and DHCP protocols.\n    image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://csp.infoblox.com/apidoc/?url=https%3A%2F%2Fcsp.infoblox.com%2Fapidoc%2Fdocs%2FIpamDhcp\n    baseURL: https://csp.infoblox.com/api/ddi/v1\n    tags:\n      - Cloud\n      - DHCP\n      - IPAM\n      - Network Management\n    properties:\n      - type: Documentation\n        url: https://csp.infoblox.com/apidoc/?url=https%3A%2F%2Fcsp.infoblox.com%2Fapidoc%2Fdocs%2FIpamDhcp\n      - type: Reference\n        url: https://docs.infoblox.com/space/BloxOneDDI/186843385\n      - type: Authentication\n        url: https://docs.infoblox.com/space/BloxOneDDI/35430405/Authentication\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox BloxOne DDI Keys API\n    description: >-\n      API for managing TSIG and other keys used in DDI operations within the\n      BloxOne platform. Handles\
  \ creation and management of authentication keys\n      used for securing DNS zone transfers and dynamic updates.\n    image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://csp.infoblox.com/apidoc/?url=https%3A%2F%2Fcsp.infoblox.com%2Fapidoc%2Fdocs%2FDDIKeys\n    baseURL: https://csp.infoblox.com/api/ddi/v1\n    tags:\n      - Authentication\n      - DNS Security\n      - Keys\n    properties:\n      - type: Documentation\n        url: https://csp.infoblox.com/apidoc/?url=https%3A%2F%2Fcsp.infoblox.com%2Fapidoc%2Fdocs%2FDDIKeys\n      - type: Authentication\n        url: https://docs.infoblox.com/space/BloxOneDDI/35430405/Authentication\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox BloxOne Anycast Configuration API\n    description: >-\n      API for managing anycast configurations within the BloxOne platform.\n      Enables high availability configuration\
  \ of Infoblox applications running\n      on customer premises by managing anycast addressing and routing.\n    image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://docs.infoblox.com/space/BloxOneDDI/186466502\n    baseURL: https://csp.infoblox.com/api/anycast/v1\n    tags:\n      - Anycast\n      - High Availability\n      - Network Management\n    properties:\n      - type: Documentation\n        url: https://docs.infoblox.com/space/BloxOneDDI/186466502\n      - type: Reference\n        url: https://docs.infoblox.com/space/BloxOneDDI/186745670\n      - type: Authentication\n        url: https://docs.infoblox.com/space/BloxOneDDI/35430405/Authentication\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox BloxOne Infrastructure Management API\n    description: >-\n      API for managing BloxOne Cloud infrastructure components. Provides\n      endpoints\
  \ for managing on-premises hosts, service configurations,\n      and infrastructure resources within the Infoblox Cloud Service Platform.\n    image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://csp.infoblox.com/apidoc/\n    baseURL: https://csp.infoblox.com/api/infra/v1\n    tags:\n      - Cloud\n      - Infrastructure\n      - Management\n    properties:\n      - type: Documentation\n        url: https://docs.infoblox.com/space/BloxOneInfrastructure/\n      - type: Authentication\n        url: https://docs.infoblox.com/space/BloxOneDDI/35430405/Authentication\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox BloxOne Host Activation API\n    description: >-\n      API for provisioning and activating on-premises hosts within the BloxOne\n      platform. Handles the host activation workflow including zero touch\n      provisioning and bootstrap configuration\
  \ for on-prem deployments.\n    image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://csp.infoblox.com/apidoc/\n    baseURL: https://csp.infoblox.com/api/host_app/v1\n    tags:\n      - Host Activation\n      - Infrastructure\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://docs.infoblox.com/space/BloxOneInfrastructure/\n      - type: Authentication\n        url: https://docs.infoblox.com/space/BloxOneDDI/35430405/Authentication\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox BloxOne DNS Forwarding Proxy API\n    description: >-\n      API for managing DNS Forwarding Proxy (DFP) configurations within\n      BloxOne Threat Defense. Enforces DNS client-based security policies\n      at remote sites by forwarding DNS queries through the Infoblox cloud\n      for threat inspection and policy enforcement.\n    image:\
  \ https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://csp.infoblox.com/apidoc/\n    baseURL: https://csp.infoblox.com/api/atcdfp/v1\n    tags:\n      - DNS\n      - Forwarding Proxy\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.infoblox.com/space/BloxOneThreatDefense/\n      - type: Authentication\n        url: https://docs.infoblox.com/space/BloxOneDDI/35430405/Authentication\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox BloxOne Firewall API\n    description: >-\n      API for managing BloxOne Threat Defense Cloud firewall policies and\n      security lists. Provides visibility into infected and compromised\n      devices on the network and allows management of security policies,\n      custom lists, and named lists for DNS-based threat defense.\n    image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n\
  \    humanURL: https://csp.infoblox.com/apidoc/\n    baseURL: https://csp.infoblox.com/api/atcfw/v1\n    tags:\n      - Firewall\n      - Security\n      - Threat Defense\n    properties:\n      - type: Documentation\n        url: https://docs.infoblox.com/space/BloxOneThreatDefense/\n      - type: Reference\n        url: https://docs.infoblox.com/space/BloxOneThreatDefense/35406336\n      - type: Authentication\n        url: https://docs.infoblox.com/space/BloxOneDDI/35430405/Authentication\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox BloxOne Redirect API\n    description: >-\n      API for configuring BloxOne Threat Defense Cloud redirect behavior.\n      Allows configuring traffic redirection to the Infoblox server or\n      custom destinations when threats are detected, and manages redirect\n      pages and custom URL filtering rules.\n    image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n\
  \    humanURL: https://csp.infoblox.com/apidoc/docs/Redirect\n    baseURL: https://csp.infoblox.com/api/atcfw/v1\n    tags:\n      - Redirect\n      - Security\n      - Threat Defense\n    properties:\n      - type: Documentation\n        url: https://csp.infoblox.com/apidoc/docs/Redirect\n      - type: Authentication\n        url: https://docs.infoblox.com/space/BloxOneDDI/35430405/Authentication\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox BloxOne Upgrade Policy API\n    description: >-\n      API for managing software upgrade policies for BloxOne on-premises\n      hosts. Allows scheduling and configuring software and configuration\n      updates for deployed BloxOne infrastructure components.\n    image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://csp.infoblox.com/apidoc/\n    baseURL: https://csp.infoblox.com/api/upgrade_policy/v1\n    tags:\n\
  \      - Infrastructure\n      - Policy\n      - Upgrade\n    properties:\n      - type: Documentation\n        url: https://docs.infoblox.com/space/BloxOneInfrastructure/\n      - type: Authentication\n        url: https://docs.infoblox.com/space/BloxOneDDI/35430405/Authentication\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox Threat Defense API\n    description: >-\n      API for threat intelligence, security analytics, and DNS firewall\n      capabilities. Provides programmatic access to BloxOne Threat Defense\n      features including security policy management, threat feeds, and\n      DNS-layer security controls.\n    image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://www.infoblox.com/products/threat-defense/\n    baseURL: https://csp.infoblox.com/tide/api\n    tags:\n      - DNS Security\n      - Firewall\n      - Security\n      - Threat\
  \ Intelligence\n    properties:\n      - type: Documentation\n        url: https://docs.infoblox.com/space/BloxOneThreatDefense/\n      - type: API Reference\n        url: https://docs.infoblox.com/space/BloxOneThreatDefense/35389219/Threat+Defense+API\n      - type: Getting Started\n        url: https://docs.infoblox.com/space/BloxOneThreatDefense/35369274\n      - type: Change Log\n        url: https://docs.infoblox.com/display/BloxOneThreatDefense/What's+New+in+Infoblox+Threat+Defense\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox TIDE API\n    description: >-\n      Threat Intelligence Data Exchange (TIDE) API for submitting and\n      retrieving threat indicators. Provides access to indicators of\n      compromise in the TIDE database in multiple formats including JSON,\n      XML, STIX, CEF, and CSV. Used for threat intelligence sharing and\n      enrichment workflows.\n    image:\
  \ https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://docs.infoblox.com/space/BloxOneThreatDefense/230394127\n    baseURL: https://csp.infoblox.com/tide/api\n    tags:\n      - Indicators\n      - Security\n      - Threat Intelligence\n      - TIDE\n    properties:\n      - type: Documentation\n        url: https://csp.infoblox.com/apidoc/?url=https%3A%2F%2Fcsp.infoblox.com%2Fapidoc%2Fdocs%2FTIDEData\n      - type: Getting Started\n        url: https://docs.infoblox.com/display/BloxOneThreatDefense/Infoblox+Quick+Start+Guide+for++Dossier+and+TIDE\n      - type: Reference\n        url: https://docs.infoblox.com/space/BloxOneThreatDefense/230394127/Infoblox+TIDE+API+FAQs+Guide\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox Dossier API\n    description: >-\n      Threat research API that provides contextual information from multiple\n      sources simultaneously\
  \ for a given indicator. Supports lookups on IPs,\n      URLs, domains, hostnames, email addresses, and file hashes (MD5, SHA1,\n      SHA256) to enrich SIEM and security tool data.\n    image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://docs.infoblox.com/display/BloxOneThreatDefense/Dossier+Threat+Research+Portal\n    baseURL: https://csp.infoblox.com/tide/api\n    tags:\n      - Dossier\n      - Research\n      - Security\n      - Threat Intelligence\n    properties:\n      - type: Documentation\n        url: https://docs.infoblox.com/display/BloxOneThreatDefense/Infoblox+Dossier+User+Guide\n      - type: Getting Started\n        url: https://docs.infoblox.com/display/BloxOneThreatDefense/Infoblox+Quick+Start+Guide+for++Dossier+and+TIDE\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\n  - name: Infoblox NetMRI API\n    description: >-\n      RESTful API for the Infoblox\
  \ NetMRI network change and configuration\n      management platform. Enables automation of network device provisioning,\n      security compliance checks, configuration management, and network\n      discovery workflows.\n    image: https://www.infoblox.com/wp-content/uploads/infoblox-logo.svg\n    humanURL: https://www.infoblox.com/products/netmri/\n    baseURL: https://{netmri-server}/api\n    tags:\n      - Compliance\n      - Configuration Management\n      - Network Automation\n    properties:\n      - type: Documentation\n        url: https://docs.infoblox.com/space/APIDeveloperGuide/43025615/\n      - type: Client Libraries\n        url: https://github.com/infobloxopen/infoblox-netmri\n    contact:\n      - FN: Infoblox Support\n        email: support@infoblox.com\n        url: https://www.infoblox.com/support/\ncommon:\n  - type: Portal\n    url: https://www.infoblox.com/developer-portal/\n  - type: Getting Started\n    url: https://www.infoblox.com/developer-portal/getting-started/\n\
  \  - type: Documentation\n    url: https://docs.infoblox.com/\n  - type: Blog\n    url: https://blogs.infoblox.com/\n  - type: Community\n    url: https://community.infoblox.com/\n  - type: Status\n    url: https://status.infoblox.com/\n  - type: Support\n    url: https://www.infoblox.com/support/\n  - type: Website\n    url: https://www.infoblox.com/\n  - type: Privacy Policy\n    url: https://www.infoblox.com/company/legal/privacy-policy/\n  - type: Terms of Service\n    url: https://www.infoblox.com/company/legal/website-terms-and-conditions/\n  - type: GitHub Organization\n    url: https://github.com/infobloxopen\n  - type: Change Log\n    url: https://docs.infoblox.com/space/BloxOneInfrastructure/332366018/BloxOne+Release+Notes\n  - type: Console\n    url: https://csp.infoblox.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Cloud\n  - DDI\n  - DHCP\n  - DNS\n  - IPAM\n  - Network Management\n  - Security\n  - Threat Intelligence\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/infoblox/refs/heads/main/apis.yml
tags:
- Cloud
- DDI
- DHCP
- DNS
- IPAM
- Network Management
- Security
- Threat Intelligence
url: https://raw.githubusercontent.com/api-evangelist/infoblox/refs/heads/main/apis.yml
use_cases: []
---
