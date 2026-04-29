---
api_count: 16
apis:
- description: PowerShell and WMI-based management APIs for Windows Server administration.
  name: Windows Server Management API
  slug: ''
- description: WS-Management protocol implementation for remote management of Windows servers using SOAP-based web services for configuration and operations.
  name: Windows Remote Management (WinRM)
  slug: ''
- description: LDAP and REST APIs for Active Directory management and authentication.
  name: Active Directory Domain Services API
  slug: ''
- description: APIs for managing Hyper-V virtualization platform including virtual machines, virtual switches, and virtual storage.
  name: Hyper-V Management API
  slug: ''
- description: APIs for managing Windows updates across enterprise environments.
  name: Windows Server Update Services (WSUS) API
  slug: ''
- description: Modern web-based management interface REST API for Windows Server that provides a gateway service for relaying commands and scripts to managed nodes.
  name: Windows Admin Center API
  slug: ''
- description: APIs for managing Windows DNS Server services.
  name: DNS Server Management API
  slug: ''
- description: Infrastructure for management data and operations on Windows-based operating systems providing COM, scripting, and .NET APIs for system administration and monitoring.
  name: Windows Management Instrumentation (WMI) API
  slug: ''
- description: REST API for managing Internet Information Services (IIS) web servers that enables configuration and monitoring from any HTTP client.
  name: IIS Administration API
  slug: ''
- description: Win32 API for managing Remote Desktop Services including session management, virtual channels, user configuration, and the Remote Desktop Protocol.
  name: Remote Desktop Services API
  slug: ''
- description: APIs for defining and managing software and hardware components on failover clusters to increase application scalability and availability.
  name: Failover Clustering API
  slug: ''
- description: APIs and PowerShell cmdlets for managing Dynamic Host Configuration Protocol server services including leases, reservations, and scopes.
  name: DHCP Server Management API
  slug: ''
- description: Server Message Block protocol APIs and WMI management classes for managing file shares, share access, and network file sharing across Windows Server environments.
  name: SMB File Server API
  slug: ''
- description: API for instrumenting, querying, and consuming event logs on Windows Server for diagnostics, monitoring, and auditing.
  name: Windows Event Log API
  slug: ''
- description: APIs and PowerShell management for software-defined storage enabling clustering of servers with internal storage for hyper-converged infrastructure.
  name: Storage Spaces Direct API
  slug: ''
- description: Network Policy Server providing centralized RADIUS authentication, authorization, and accounting for wireless, VPN, and dial-up connections.
  name: Network Policy Server (NPS) RADIUS API
  slug: ''
capabilities:
- description: Unified workflow for IT administrators to manage IIS web sites, applications, and application pools for enterprise web hosting on Windows Server.
  name: Windows Server Web Management
  slug: web-server-management
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://docs.microsoft.com/windows-server/
- title: ''
  type: Support
  url: https://support.microsoft.com/windows-server
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/windows-server/bg-p/WindowsServer
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/licensing/terms/
- title: ''
  type: ReleaseNotes
  url: https://learn.microsoft.com/en-us/windows-server/get-started/whats-new-windows-server-2025
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/privacystatement
- title: ''
  type: GitHubRepository
  url: https://github.com/MicrosoftDocs/windowsserverdocs
- title: ''
  type: Security
  url: https://learn.microsoft.com/en-us/windows-server/security/tls/tls-ssl-schannel-ssp-overview
- title: ''
  type: NaftikoCapability
  url: capabilities/web-server-management.yaml
created: '2024'
description: APIs and integration points for Microsoft Windows Server operating system including management, networking, storage, virtualization, security, and remote administration capabilities for enterprise server infrastructure.
features:
- description: REST API for managing IIS web sites, applications, and application pools with full CRUD operations and configuration management.
  name: Web Server Management
- description: LDAP and API-based management of directory services, user authentication, group policies, and domain controllers.
  name: Active Directory Services
- description: Create, manage, and monitor virtual machines, virtual switches, and storage with PowerShell and WMI APIs.
  name: Hyper-V Virtualization
- description: Manage servers remotely through WinRM, PowerShell Remoting, Windows Admin Center, and Remote Desktop Services.
  name: Remote Server Administration
- description: High availability clustering with automatic failover for critical workloads including SQL Server, Hyper-V, and file servers.
  name: Failover Clustering
- description: Storage Spaces Direct for hyper-converged infrastructure with pool management, tiering, and resilient storage volumes.
  name: Software-Defined Storage
- description: Network infrastructure services with APIs for DNS zone management and DHCP scope configuration.
  name: DNS and DHCP Services
- description: RADIUS authentication via NPS, TLS/SSL management, Windows Event Log auditing, and security policy enforcement.
  name: Security and Compliance
image: /assets/icons/microsoft-windows-server.png
integrations:
- description: Extend on-premises Windows Server to Azure with Azure Arc, Azure Backup, Azure Site Recovery, and hybrid networking.
  name: Microsoft Azure
- description: Enterprise management with System Center Configuration Manager, Operations Manager, and Virtual Machine Manager.
  name: System Center
- description: Integrated security with Microsoft Defender for Servers, threat detection, and vulnerability management.
  name: Microsoft Defender
- description: Enable single sign-on and federated identity across on-premises and cloud applications with ADFS.
  name: Active Directory Federation Services
- description: Collect and analyze Windows Server performance metrics, logs, and diagnostics in Azure Monitor.
  name: Azure Monitor
jsonld:
- class_count: 0
  name: Iis Administration Context
  property_count: 0
  slug: iis-administration-context
- class_count: 0
  name: Microsoft Windows Server Context
  property_count: 3
  slug: microsoft-windows-server-context
layout: provider
modified: '2026-04-19'
name: Microsoft Windows Server
rules:
- name: Microsoft Windows Server API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: microsoft-windows-server-spectral-rules
skills: []
slug: microsoft-windows-server
solutions: []
source_yaml: "aid: microsoft-windows-server\nname: Microsoft Windows Server\ndescription: APIs and integration points for Microsoft Windows Server operating system including management, networking, storage, virtualization, security, and remote administration capabilities for enterprise server infrastructure.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://www.microsoft.com/windows-server\ntags:\n  - Datacenter\n  - Enterprise\n  - Infrastructure\n  - Microsoft\n  - Operating System\n  - Server Management\n  - Windows Server\n  - Windows Server 2025\ncreated: '2024'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - name: Windows Server Management API\n    description: PowerShell and WMI-based management APIs for Windows Server administration.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://docs.microsoft.com/windows-server/administration/\n    baseURL: https://localhost\n    tags:\n     \
  \ - Administration\n      - Management\n      - PowerShell\n      - WMI\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/powershell/windows/get-started\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n        url: https://support.microsoft.com\n  - name: Windows Remote Management (WinRM)\n    description: WS-Management protocol implementation for remote management of Windows servers using SOAP-based web services for configuration and operations.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://docs.microsoft.com/windows/win32/winrm/portal\n    baseURL: http://localhost:5985\n    tags:\n      - PowerShell Remoting\n      - Remote Management\n      - SOAP\n      - WS-Management\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/windows/win32/winrm/windows-remote-management-portal\n  - name: Active Directory Domain Services API\n    description: LDAP and REST\
  \ APIs for Active Directory management and authentication.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://docs.microsoft.com/windows-server/identity/ad-ds/\n    baseURL: ldap://localhost:389\n    tags:\n      - Active Directory\n      - Authentication\n      - Directory Services\n      - LDAP\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/windows/win32/ad/active-directory-domain-services\n      - type: SDK\n        url: https://docs.microsoft.com/dotnet/api/system.directoryservices\n  - name: Hyper-V Management API\n    description: APIs for managing Hyper-V virtualization platform including virtual machines, virtual switches, and virtual storage.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://docs.microsoft.com/virtualization/hyper-v-on-windows/\n    baseURL: https://localhost\n    tags:\n      - Hyper-V\n      - Virtual Machines\n      - Virtualization\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.microsoft.com/virtualization/api/\n  - name: Windows Server Update Services (WSUS) API\n    description: APIs for managing Windows updates across enterprise environments.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://docs.microsoft.com/windows-server/administration/windows-server-update-services/\n    baseURL: https://localhost:8530\n    tags:\n      - Patch Management\n      - Updates\n      - WSUS\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/previous-versions/windows/desktop/aa354519(v=vs.85)\n      - type: SDK\n        url: https://docs.microsoft.com/dotnet/api/microsoft.updateservices.administration\n  - name: Windows Admin Center API\n    description: Modern web-based management interface REST API for Windows Server that provides a gateway service for relaying commands and scripts to managed nodes.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://docs.microsoft.com/windows-server/manage/windows-admin-center/\n\
  \    baseURL: https://localhost:6516\n    tags:\n      - Admin Center\n      - Gateway\n      - REST API\n      - Web Management\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/windows-server/manage/windows-admin-center/extend/extensibility-overview\n      - type: GitHubRepository\n        url: https://github.com/Microsoft/windows-admin-center-sdk\n  - name: DNS Server Management API\n    description: APIs for managing Windows DNS Server services.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://docs.microsoft.com/windows-server/networking/dns/\n    baseURL: https://localhost\n    tags:\n      - DNS\n      - Name Resolution\n      - Networking\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/powershell/module/dnsserver/\n  - name: Windows Management Instrumentation (WMI) API\n    description: Infrastructure for management data and operations on Windows-based operating systems providing\
  \ COM, scripting, and .NET APIs for system administration and monitoring.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://learn.microsoft.com/en-us/windows/win32/wmisdk/wmi-start-page\n    baseURL: https://localhost\n    tags:\n      - COM\n      - Management\n      - Monitoring\n      - Scripting\n      - WMI\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/windows/win32/wmisdk/wmi-start-page\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/windows/win32/wmisdk/com-api-for-wmi\n  - name: IIS Administration API\n    description: REST API for managing Internet Information Services (IIS) web servers that enables configuration and monitoring from any HTTP client.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://learn.microsoft.com/en-us/iis-administration/\n    baseURL: https://localhost:55539\n    tags:\n      - IIS\n      - REST API\n      - Web Management\n      - Web\
  \ Server\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/iis-administration/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/iis-administration/getting-started\n      - type: GitHubRepository\n        url: https://github.com/microsoft/IIS.Administration\n      - type: OpenAPI\n        url: openapi/iis-administration-api.yml\n  - name: Remote Desktop Services API\n    description: Win32 API for managing Remote Desktop Services including session management, virtual channels, user configuration, and the Remote Desktop Protocol.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://learn.microsoft.com/en-us/windows/win32/termserv/terminal-services-portal\n    baseURL: https://localhost\n    tags:\n      - RDS\n      - Remote Access\n      - Remote Desktop\n      - Terminal Services\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/windows/win32/termserv/terminal-services-portal\n\
  \      - type: APIReference\n        url: https://learn.microsoft.com/en-us/windows/win32/termserv/terminal-services-api-reference\n  - name: Failover Clustering API\n    description: APIs for defining and managing software and hardware components on failover clusters to increase application scalability and availability.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://learn.microsoft.com/en-us/windows-server/failover-clustering/failover-clustering-overview\n    baseURL: https://localhost\n    tags:\n      - Cluster Management\n      - Failover Clustering\n      - High Availability\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/windows-server/failover-clustering/failover-clustering-overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/previous-versions/windows/desktop/mscs/failover-cluster-apis-portal\n  - name: DHCP Server Management API\n    description: APIs and PowerShell cmdlets for\
  \ managing Dynamic Host Configuration Protocol server services including leases, reservations, and scopes.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://learn.microsoft.com/en-us/windows-server/networking/technologies/dhcp/dhcp-deploy-wps\n    baseURL: https://localhost\n    tags:\n      - DHCP\n      - IP Address Management\n      - Networking\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/previous-versions/windows/desktop/dhcp/dhcp-server-management-api\n  - name: SMB File Server API\n    description: Server Message Block protocol APIs and WMI management classes for managing file shares, share access, and network file sharing across Windows Server environments.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://learn.microsoft.com/en-us/windows-server/storage/file-server/file-server-smb-overview\n    baseURL: https://localhost\n    tags:\n      - File Sharing\n      - Network Storage\n   \
  \   - SMB\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/windows-server/storage/file-server/file-server-smb-overview\n  - name: Windows Event Log API\n    description: API for instrumenting, querying, and consuming event logs on Windows Server for diagnostics, monitoring, and auditing.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://learn.microsoft.com/en-us/windows/win32/wes/windows-event-log\n    baseURL: https://localhost\n    tags:\n      - Diagnostics\n      - Event Log\n      - Logging\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/windows/win32/wes/windows-event-log\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/windows/win32/wes/windows-event-log-reference\n  - name: Storage Spaces Direct API\n    description: APIs and PowerShell management for software-defined storage enabling clustering of servers\
  \ with internal storage for hyper-converged infrastructure.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://learn.microsoft.com/en-us/windows-server/storage/storage-spaces/storage-spaces-direct-overview\n    baseURL: https://localhost\n    tags:\n      - Hyper-Converged\n      - Software-Defined Storage\n      - Storage\n      - Storage Spaces Direct\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/windows-server/storage/storage-spaces/storage-spaces-direct-overview\n  - name: Network Policy Server (NPS) RADIUS API\n    description: Network Policy Server providing centralized RADIUS authentication, authorization, and accounting for wireless, VPN, and dial-up connections.\n    image: https://www.microsoft.com/favicon.ico\n    humanURL: https://learn.microsoft.com/en-us/windows-server/networking/technologies/nps/nps-top\n    baseURL: https://localhost\n    tags:\n      - Authentication\n      - Network Access\n      -\
  \ NPS\n      - RADIUS\n      - VPN\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/windows-server/networking/technologies/nps/nps-top\ncommon:\n  - type: Portal\n    url: https://portal.azure.com\n  - type: Documentation\n    url: https://docs.microsoft.com/windows-server/\n  - type: Support\n    url: https://support.microsoft.com/windows-server\n  - type: Blog\n    url: https://techcommunity.microsoft.com/t5/windows-server/bg-p/WindowsServer\n  - type: TermsOfService\n    url: https://www.microsoft.com/licensing/terms/\n  - type: ReleaseNotes\n    url: https://learn.microsoft.com/en-us/windows-server/get-started/whats-new-windows-server-2025\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/privacystatement\n  - type: GitHubRepository\n    url: https://github.com/MicrosoftDocs/windowsserverdocs\n  - type: Security\n    url: https://learn.microsoft.com/en-us/windows-server/security/tls/tls-ssl-schannel-ssp-overview\n  - type:\
  \ Features\n    data:\n      - name: Web Server Management\n        description: REST API for managing IIS web sites, applications, and application pools with full CRUD operations and configuration management.\n      - name: Active Directory Services\n        description: LDAP and API-based management of directory services, user authentication, group policies, and domain controllers.\n      - name: Hyper-V Virtualization\n        description: Create, manage, and monitor virtual machines, virtual switches, and storage with PowerShell and WMI APIs.\n      - name: Remote Server Administration\n        description: Manage servers remotely through WinRM, PowerShell Remoting, Windows Admin Center, and Remote Desktop Services.\n      - name: Failover Clustering\n        description: High availability clustering with automatic failover for critical workloads including SQL Server, Hyper-V, and file servers.\n      - name: Software-Defined Storage\n        description: Storage Spaces Direct for\
  \ hyper-converged infrastructure with pool management, tiering, and resilient storage volumes.\n      - name: DNS and DHCP Services\n        description: Network infrastructure services with APIs for DNS zone management and DHCP scope configuration.\n      - name: Security and Compliance\n        description: RADIUS authentication via NPS, TLS/SSL management, Windows Event Log auditing, and security policy enforcement.\n  - type: UseCases\n    data:\n      - name: Enterprise Web Hosting\n        description: Deploy and manage web applications on IIS with automated site provisioning, SSL certificate management, and application pool isolation.\n      - name: Infrastructure Automation\n        description: Automate server provisioning, configuration management, and patch deployment using PowerShell, WMI, and REST APIs.\n      - name: Hybrid Cloud Management\n        description: Manage on-premises Windows Server infrastructure alongside Azure resources through Windows Admin Center and Azure\
  \ Arc.\n      - name: Virtual Desktop Infrastructure\n        description: Deploy and manage Remote Desktop Services for virtual desktop and application delivery to remote workers.\n      - name: High Availability Deployments\n        description: Configure failover clustering and storage replication for mission-critical applications requiring zero downtime.\n  - type: Integrations\n    data:\n      - name: Microsoft Azure\n        description: Extend on-premises Windows Server to Azure with Azure Arc, Azure Backup, Azure Site Recovery, and hybrid networking.\n      - name: System Center\n        description: Enterprise management with System Center Configuration Manager, Operations Manager, and Virtual Machine Manager.\n      - name: Microsoft Defender\n        description: Integrated security with Microsoft Defender for Servers, threat detection, and vulnerability management.\n      - name: Active Directory Federation Services\n        description: Enable single sign-on and federated\
  \ identity across on-premises and cloud applications with ADFS.\n      - name: Azure Monitor\n        description: Collect and analyze Windows Server performance metrics, logs, and diagnostics in Azure Monitor.\n  - type: NaftikoCapability\n    url: capabilities/web-server-management.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-windows-server/refs/heads/main/apis.yml
tags:
- Datacenter
- Enterprise
- Infrastructure
- Microsoft
- Operating System
- Server Management
- Windows Server
- Windows Server 2025
url: https://www.microsoft.com/windows-server
use_cases:
- description: Deploy and manage web applications on IIS with automated site provisioning, SSL certificate management, and application pool isolation.
  name: Enterprise Web Hosting
- description: Automate server provisioning, configuration management, and patch deployment using PowerShell, WMI, and REST APIs.
  name: Infrastructure Automation
- description: Manage on-premises Windows Server infrastructure alongside Azure resources through Windows Admin Center and Azure Arc.
  name: Hybrid Cloud Management
- description: Deploy and manage Remote Desktop Services for virtual desktop and application delivery to remote workers.
  name: Virtual Desktop Infrastructure
- description: Configure failover clustering and storage replication for mission-critical applications requiring zero downtime.
  name: High Availability Deployments
---
