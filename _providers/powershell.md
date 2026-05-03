---
api_count: 3
apis:
- description: The PowerShell Gallery is the central repository for PowerShell modules, scripts, and DSC resources. It exposes a public OData v2 API for searching, retrieving, and downloading packages programmatical
  name: PowerShell Gallery API
  slug: powershell-gallery-api
- description: .NET APIs for creating, configuring, and managing PowerShell runspaces from host applications. Enables embedding PowerShell execution inside .NET programs.
  name: PowerShell Runspace API
  slug: powershell-runspace-api
- description: APIs and protocols for remote PowerShell execution over WS-Management (WinRM) and SSH. Enables one-to-one and one-to-many remote command and session management.
  name: PowerShell Remoting API
  slug: powershell-remoting-api
common:
- title: ''
  type: Website
  url: https://microsoft.com/powershell
- title: ''
  type: GitHub
  url: https://github.com/PowerShell/PowerShell
- title: ''
  type: Documentation
  url: https://docs.microsoft.com/en-us/powershell/
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/powershell/
- title: ''
  type: Community
  url: https://github.com/PowerShell/PowerShell/blob/master/docs/community/README.md
- title: ''
  type: GettingStarted
  url: https://docs.microsoft.com/en-us/powershell/scripting/learn/ps101/01-getting-started
- title: ''
  type: License
  url: https://github.com/PowerShell/PowerShell/blob/master/LICENSE.txt
- title: ''
  type: Releases
  url: https://github.com/PowerShell/PowerShell/releases
- title: ''
  type: Roadmap
  url: https://github.com/PowerShell/PowerShell/projects
- title: ''
  type: Security
  url: https://github.com/PowerShell/PowerShell/security/policy
- title: ''
  type: Contributing
  url: https://github.com/PowerShell/PowerShell/blob/master/.github/CONTRIBUTING.md
created: '2024-01-15'
description: PowerShell is a cross-platform task automation solution made up of a command-line shell, a scripting language, and a configuration management framework. The PowerShell ecosystem exposes APIs through the PowerShell Gallery (an OData-based package repository), the Runspace .NET hosting APIs, and PowerShell Remoting protocols (WS-Management and SSH).
features: []
image: https://raw.githubusercontent.com/PowerShell/PowerShell/master/assets/ps_black_64.svg
integrations: []
layout: provider
modified: '2026-04-28'
name: PowerShell
skills: []
slug: powershell
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: powershell\nname: PowerShell\ndescription: >-\n  PowerShell is a cross-platform task automation solution made up of a\n  command-line shell, a scripting language, and a configuration\n  management framework. The PowerShell ecosystem exposes APIs through\n  the PowerShell Gallery (an OData-based package repository), the\n  Runspace .NET hosting APIs, and PowerShell Remoting protocols\n  (WS-Management and SSH).\ntype: Index\nimage: https://raw.githubusercontent.com/PowerShell/PowerShell/master/assets/ps_black_64.svg\ntags:\n  - Automation\n  - Command-Line\n  - Cross-Platform\n  - Scripting\n  - Shell\n  - Windows\n  - DevOps\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/powershell/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: powershell:powershell-gallery-api\n    name: PowerShell Gallery API\n    description: >-\n      The PowerShell Gallery is the central repository for PowerShell\n\
  \      modules, scripts, and DSC resources. It exposes a public OData v2\n      API for searching, retrieving, and downloading packages\n      programmatically.\n    image: https://www.powershellgallery.com/Content/Images/Branding/psgallerylogo.svg\n    humanURL: https://www.powershellgallery.com/\n    baseURL: https://www.powershellgallery.com/api/v2\n    tags:\n      - Modules\n      - NuGet\n      - Packages\n      - Repository\n      - OData\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/powershell/gallery/overview\n      - type: Metadata\n        url: https://www.powershellgallery.com/api/v2/$metadata\n    contact:\n      - FN: PowerShell Gallery Support\n        url: https://github.com/PowerShell/PowerShellGallery/issues\n  - aid: powershell:powershell-runspace-api\n    name: PowerShell Runspace API\n    description: >-\n      .NET APIs for creating, configuring, and managing PowerShell\n      runspaces from host applications. Enables\
  \ embedding PowerShell\n      execution inside .NET programs.\n    humanURL: https://docs.microsoft.com/en-us/dotnet/api/system.management.automation.runspaces\n    tags:\n      - Automation\n      - .NET\n      - Runspace\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/powershell/scripting/developer/hosting/creating-runspaces\n      - type: SDK\n        url: https://www.nuget.org/packages/System.Management.Automation/\n      - type: Examples\n        url: https://github.com/PowerShell/PowerShell/tree/master/test/hosting\n  - aid: powershell:powershell-remoting-api\n    name: PowerShell Remoting API\n    description: >-\n      APIs and protocols for remote PowerShell execution over\n      WS-Management (WinRM) and SSH. Enables one-to-one and one-to-many\n      remote command and session management.\n    humanURL: https://docs.microsoft.com/en-us/powershell/scripting/learn/remoting/running-remote-commands\n    tags:\n      - Remoting\n\
  \      - SSH\n      - WinRM\n      - WS-Management\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/powershell/scripting/learn/remoting/powershell-remoting-faq\n      - type: ProtocolSpecification\n        url: https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-psrp/\ncommon:\n  - type: Website\n    url: https://microsoft.com/powershell\n  - type: GitHub\n    url: https://github.com/PowerShell/PowerShell\n  - type: Documentation\n    url: https://docs.microsoft.com/en-us/powershell/\n  - type: Blog\n    url: https://devblogs.microsoft.com/powershell/\n  - type: Community\n    url: https://github.com/PowerShell/PowerShell/blob/master/docs/community/README.md\n  - type: GettingStarted\n    url: https://docs.microsoft.com/en-us/powershell/scripting/learn/ps101/01-getting-started\n  - type: License\n    url: https://github.com/PowerShell/PowerShell/blob/master/LICENSE.txt\n  - type: Releases\n    url: https://github.com/PowerShell/PowerShell/releases\n\
  \  - type: Roadmap\n    url: https://github.com/PowerShell/PowerShell/projects\n  - type: Security\n    url: https://github.com/PowerShell/PowerShell/security/policy\n  - type: Contributing\n    url: https://github.com/PowerShell/PowerShell/blob/master/.github/CONTRIBUTING.md\nmaintainers:\n  - FN: Microsoft\n    email: powershell@microsoft.com\n    url: https://github.com/PowerShell\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/powershell/refs/heads/main/apis.yml
tags:
- Automation
- Command-Line
- Cross-Platform
- Scripting
- Shell
- Windows
- DevOps
url: https://raw.githubusercontent.com/api-evangelist/powershell/refs/heads/main/apis.yml
use_cases: []
---
