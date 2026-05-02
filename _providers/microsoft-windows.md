---
api_count: 8
api_specs:
- filename: openapi.json
  format: json
  label: Windows Runtime (WinRT) API
  slug: ''
  spec_type: OpenAPI
  url: https://api.windows.com/openapi.json
apis:
- description: Modern API for building Windows applications with support for multiple programming languages.
  name: Windows Runtime (WinRT) API
  slug: ''
- description: Traditional Windows API for native application development with full system access.
  name: Win32 API
  slug: ''
- description: Infrastructure for management data and operations on Windows systems.
  name: Windows Management Instrumentation (WMI)
  slug: ''
- description: Task automation and configuration management framework from Microsoft.
  name: Windows PowerShell API
  slug: ''
- description: API for accessing and manipulating the Windows Registry database.
  name: Windows Registry API
  slug: ''
- description: APIs for interacting with Windows Shell features and user interface elements.
  name: Windows Shell API
  slug: ''
- description: Collection of APIs for handling tasks related to multimedia and game programming.
  name: DirectX Graphics API
  slug: ''
- description: API for creating and managing Windows notifications and toast messages.
  name: Windows Notification API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developer.microsoft.com/windows
- title: ''
  type: Blog
  url: https://blogs.windows.com/windowsdeveloper/
- title: ''
  type: Support
  url: https://support.microsoft.com/windows
- title: ''
  type: GitHub Organization
  url: https://github.com/microsoft
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/
- title: ''
  type: SDK Downloads
  url: https://developer.microsoft.com/windows/downloads/
created: '2024'
description: A collection of APIs and developer resources for Microsoft Windows operating system.
features: []
image: https://www.microsoft.com/windows/windows-11-logo.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Windows
skills: []
slug: microsoft-windows
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-windows\nname: Microsoft Windows\ndescription: >-\n  A collection of APIs and developer resources for Microsoft Windows operating system.\nimage: https://www.microsoft.com/windows/windows-11-logo.png\nurl: https://developer.microsoft.com/windows\ncreated: '2024'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - name: Windows Runtime (WinRT) API\n    description: >-\n      Modern API for building Windows applications with support for multiple programming\n      languages.\n    image: https://docs.microsoft.com/windows/images/winrt-logo.png\n    humanUrl: https://docs.microsoft.com/windows/uwp/\n    baseUrl: https://api.windows.com\n    tags:\n      - Applications\n      - UWP\n      - Windows\n      - WinRT\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/windows/uwp/api/\n      - type: OpenAPI\n        url: https://api.windows.com/openapi.json\n      - type: Getting Started\n        url: https://docs.microsoft.com/windows/uwp/get-started/\n\
  \  - name: Win32 API\n    description: >-\n      Traditional Windows API for native application development with full system\n      access.\n    image: https://docs.microsoft.com/windows/images/win32-logo.png\n    humanUrl: https://docs.microsoft.com/windows/win32/\n    baseUrl: https://api.windows.com/win32\n    tags:\n      - C++\n      - Native\n      - Win32\n      - Windows\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/windows/win32/apiindex/windows-api-list\n      - type: Reference\n        url: https://docs.microsoft.com/windows/win32/api/\n      - type: Code Samples\n        url: https://github.com/microsoft/Windows-classic-samples\n  - name: Windows Management Instrumentation (WMI)\n    description: >-\n      Infrastructure for management data and operations on Windows systems.\n    humanUrl: https://docs.microsoft.com/windows/win32/wmisdk/\n    baseUrl: https://api.windows.com/wmi\n    tags:\n      - Management\n      - System Administration\n\
  \      - Windows\n      - WMI\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/windows/win32/wmisdk/wmi-reference\n      - type: PowerShell Integration\n        url: https://docs.microsoft.com/powershell/module/microsoft.powershell.management/\n  - name: Windows PowerShell API\n    description: >-\n      Task automation and configuration management framework from Microsoft.\n    humanUrl: https://docs.microsoft.com/powershell/\n    baseUrl: https://api.windows.com/powershell\n    tags:\n      - Automation\n      - PowerShell\n      - Scripting\n      - Windows\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/powershell/scripting/overview\n      - type: Module Reference\n        url: https://docs.microsoft.com/powershell/module/\n      - type: GitHub Repository\n        url: https://github.com/PowerShell/PowerShell\n  - name: Windows Registry API\n    description: >-\n      API for accessing and manipulating the\
  \ Windows Registry database.\n    humanUrl: https://docs.microsoft.com/windows/win32/sysinfo/registry\n    baseUrl: https://api.windows.com/registry\n    tags:\n      - Configuration\n      - Registry\n      - System\n      - Windows\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/windows/win32/sysinfo/registry-functions\n      - type: Reference\n        url: https://docs.microsoft.com/windows/win32/sysinfo/registry-reference\n  - name: Windows Shell API\n    description: >-\n      APIs for interacting with Windows Shell features and user interface elements.\n    humanUrl: https://docs.microsoft.com/windows/win32/shell/\n    baseUrl: https://api.windows.com/shell\n    tags:\n      - Explorer\n      - Shell\n      - UI\n      - Windows\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/windows/win32/shell/shell-reference\n      - type: Samples\n        url: https://github.com/microsoft/Windows-classic-samples/tree/main/Samples/Win7Samples/winui/shell\n\
  \  - name: DirectX Graphics API\n    description: >-\n      Collection of APIs for handling tasks related to multimedia and game programming.\n    humanUrl: https://docs.microsoft.com/windows/win32/directx\n    baseUrl: https://api.windows.com/directx\n    tags:\n      - DirectX\n      - Gaming\n      - Graphics\n      - Windows\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/windows/win32/directx\n      - type: Direct3D Reference\n        url: https://docs.microsoft.com/windows/win32/direct3d12/\n      - type: Samples\n        url: https://github.com/microsoft/DirectX-Graphics-Samples\n  - name: Windows Notification API\n    description: >-\n      API for creating and managing Windows notifications and toast messages.\n    humanUrl: https://docs.microsoft.com/windows/apps/design/shell/tiles-and-notifications/\n    baseUrl: https://api.windows.com/notifications\n    tags:\n      - Notifications\n      - Toast\n      - User Interface\n      - Windows\n\
  \    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/windows/apps/design/shell/tiles-and-notifications/windows-push-notification-services--wns--overview\n      - type: Code Samples\n        url: https://docs.microsoft.com/windows/apps/design/shell/tiles-and-notifications/adaptive-interactive-toasts\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://developer.microsoft.com/windows\n  - type: Blog\n    url: https://blogs.windows.com/windowsdeveloper/\n  - type: Support\n    url: https://support.microsoft.com/windows\n  - type: GitHub Organization\n    url: https://github.com/microsoft\n  - type: Terms of Service\n    url: https://www.microsoft.com/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/\n  - type: SDK Downloads\n    url: https://developer.microsoft.com/windows/downloads/\ntags:\n  - Desktop\n  - Development\n  - Microsoft\n  - Operating System\n  - Windows\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-windows/refs/heads/main/apis.yml
tags:
- Desktop
- Development
- Microsoft
- Operating System
- Windows
url: https://developer.microsoft.com/windows
use_cases: []
---
