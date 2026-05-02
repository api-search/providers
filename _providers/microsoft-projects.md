---
api_count: 3
apis:
- description: REST API for managing projects, tasks, resources, and assignments in Microsoft Project for the web.
  name: Microsoft Project for the Web API
  slug: ''
- description: REST API for Microsoft Project Online, providing access to project data, timesheets, and enterprise project management features.
  name: Microsoft Project Online API
  slug: ''
- description: Client-side object model for programmatically interacting with Microsoft Project desktop applications.
  name: Microsoft Project Desktop CSOM API
  slug: ''
common:
- title: ''
  type: X-portal
  url: https://developer.microsoft.com/
- title: ''
  type: X-pricing
  url: https://www.microsoft.com/en-us/microsoft-365/project/compare-microsoft-project-management-software
- title: ''
  type: X-status
  url: https://status.cloud.microsoft/
- title: ''
  type: X-blog
  url: https://techcommunity.microsoft.com/t5/project-blog/bg-p/ProjectBlog
- title: ''
  type: X-terms-of-service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: X-privacy-policy
  url: https://privacy.microsoft.com/en-us/privacystatement
created: '2024-01-15'
description: A collection of APIs for Microsoft Project, enabling project management, task tracking, resource allocation, and collaboration capabilities.
features: []
image: https://www.microsoft.com/en-us/microsoft-365/project/project-management-software
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Project APIs
skills: []
slug: microsoft-projects
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-projects\nname: Microsoft Project APIs\ndescription: >-\n  A collection of APIs for Microsoft Project, enabling project management, task tracking,\n  resource allocation, and collaboration capabilities.\nimage: https://www.microsoft.com/en-us/microsoft-365/project/project-management-software\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-projects/refs/heads/main/apis.yml\napis:\n  - name: Microsoft Project for the Web API\n    description: >-\n      REST API for managing projects, tasks, resources, and assignments in Microsoft\n      Project for the web.\n    image: https://www.microsoft.com/en-us/microsoft-365/project/project-management-software\n    humanUrl: https://docs.microsoft.com/en-us/project/\n    baseUrl: https://graph.microsoft.com/v1.0/\n    tags:\n      - Assignments\n      - Collaboration\n      - Projects\n      - Resources\n      - Tasks\n    properties:\n\
  \      - type: X-documentation\n        url: https://docs.microsoft.com/en-us/graph/api/resources/project-rome-overview\n      - type: X-openapi\n        url: https://developer.microsoft.com/en-us/graph/docs/api-reference/v1.0/resources/project\n      - type: X-authentication\n        url: https://docs.microsoft.com/en-us/graph/auth/\n      - type: X-rate-limits\n        url: https://docs.microsoft.com/en-us/graph/throttling\n    contact:\n      - FN: Microsoft Graph Support\n        email: graphsdksupport@microsoft.com\n        url: https://developer.microsoft.com/en-us/graph/support\n  - name: Microsoft Project Online API\n    description: >-\n      REST API for Microsoft Project Online, providing access to project data, timesheets,\n      and enterprise project management features.\n    image: https://www.microsoft.com/en-us/microsoft-365/project/project-management-software\n    humanUrl: https://docs.microsoft.com/en-us/project/project-online\n    baseUrl: https://{tenant}.sharepoint.com/sites/pwa/_api/ProjectServer/\n\
  \    tags:\n      - Enterprise\n      - Portfolio\n      - Project-Online\n      - Reporting\n      - Timesheets\n    properties:\n      - type: X-documentation\n        url: https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712820(v=office.15)\n      - type: X-openapi\n        url: https://docs.microsoft.com/en-us/openspecs/sharepoint_protocols/ms-pjsoi/\n      - type: X-authentication\n        url: https://docs.microsoft.com/en-us/sharepoint/dev/sp-add-ins/authorization-and-authentication-of-sharepoint-add-ins\n      - type: X-sdk\n        url: https://docs.microsoft.com/en-us/project/api/project-csom-overview\n    contact:\n      - FN: Project Online Support\n        email: support@microsoft.com\n        url: https://support.microsoft.com/project\n  - name: Microsoft Project Desktop CSOM API\n    description: >-\n      Client-side object model for programmatically interacting with Microsoft Project\n      desktop applications.\n    image: https://www.microsoft.com/en-us/microsoft-365/project/project-management-software\n\
  \    humanUrl: https://docs.microsoft.com/en-us/office/client-developer/project/\n    baseUrl: N/A\n    tags:\n      - Add-Ins\n      - Automation\n      - Csom\n      - Desktop\n      - Vba\n    properties:\n      - type: X-documentation\n        url: https://docs.microsoft.com/en-us/office/client-developer/project/project-programming-references\n      - type: X-sdk\n        url: https://docs.microsoft.com/en-us/visualstudio/vsto/office-solutions-development-overview-vsto\n      - type: X-samples\n        url: https://github.com/OfficeDev/Project-Samples\n    contact:\n      - FN: Office Developer Support\n        email: officedevfeedback@microsoft.com\n        url: https://developer.microsoft.com/en-us/office\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Collaboration\n  - Enterprise\n  - Microsoft\n  - Portfolio-Management\n  - Project-Management\n  - Resources\n  - Tasks\ninclude: []\ncommon:\n  - type: X-portal\n    url: https://developer.microsoft.com/\n\
  \  - type: X-pricing\n    url: https://www.microsoft.com/en-us/microsoft-365/project/compare-microsoft-project-management-software\n  - type: X-status\n    url: https://status.cloud.microsoft/\n  - type: X-blog\n    url: https://techcommunity.microsoft.com/t5/project-blog/bg-p/ProjectBlog\n  - type: X-terms-of-service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: X-privacy-policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-projects/refs/heads/main/apis.yml
tags:
- Collaboration
- Enterprise
- Microsoft
- Portfolio-Management
- Project-Management
- Resources
- Tasks
url: https://raw.githubusercontent.com/api-evangelist/microsoft-projects/refs/heads/main/apis.yml
use_cases: []
---
