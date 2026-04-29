---
api_count: 3
apis:
- description: Manage and observe directory synchronization between on-premises directory services and Cisco Webex Control Hub, including sync scheduling, status, and error reporting.
  name: Cisco Directory Connector Sync API
  slug: cisco-directory-connector-sync-api
- description: Administrative API for managing Webex organizations, including users, groups, licenses, and directory-sync settings.
  name: Webex Control Hub API
  slug: webex-control-hub-api
- description: SCIM 2.0 endpoints used by identity providers such as Microsoft Entra (Azure AD) and Okta to provision users and groups into Webex as an alternative to the on-premises Directory Connector.
  name: Webex SCIM 2.0 Provisioning
  slug: webex-scim
common:
- title: ''
  type: Portal
  url: https://developer.webex.com
- title: ''
  type: Admin Console
  url: https://admin.webex.com
- title: ''
  type: Getting Started
  url: https://developer.webex.com/docs/getting-started
- title: ''
  type: Authentication
  url: https://developer.webex.com/docs/integrations
- title: ''
  type: Status
  url: https://status.webex.com
- title: ''
  type: Blog
  url: https://developer.webex.com/blog
- title: ''
  type: Support
  url: https://help.webex.com
- title: ''
  type: Downloads
  url: https://help.webex.com/en-us/article/nivpu1g/Deployment-Guide-for-Cisco-Directory-Connector
- title: ''
  type: Terms of Service
  url: https://www.cisco.com/c/en/us/about/legal/terms-conditions.html
- title: ''
  type: Privacy Policy
  url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html
- title: ''
  type: JSON-LD
  url: json-ld/cisco-directory-connector-context.jsonld
created: '2024-01-01'
description: The Cisco Directory Connector is an on-premises Windows service that synchronizes users and groups from a corporate directory (typically Microsoft Active Directory or LDAP) into Cisco Webex Control Hub. It supports full and incremental sync, attribute mapping, dry-run preview, and scheduled jobs. Programmatic management is via the related Webex People, Groups, and Organizations APIs in Control Hub; modern deployments increasingly use SCIM 2.0 provisioning from identity providers (Azure AD, Okta) as an alternative to the on-premises connector.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 1
  name: Cisco Directory Connector Context
  property_count: 4
  slug: cisco-directory-connector-context
layout: provider
modified: '2026-04-23'
name: Cisco Directory Connector
skills: []
slug: cisco-directory-connector
solutions: []
source_filename: apis.yml
source_yaml: "aid: cisco-directory-connector\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cisco-directory-connector/refs/heads/main/apis.yml\nname: Cisco Directory Connector\ntags:\n  - Active Directory\n  - Directory\n  - Enterprise\n  - Identity Management\n  - LDAP\n  - Provisioning\n  - SCIM\n  - Synchronization\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-01-01'\nmodified: '2026-04-23'\nposition: Consumer\nspecificationVersion: '0.19'\ndescription: >-\n  The Cisco Directory Connector is an on-premises Windows service that\n  synchronizes users and groups from a corporate directory (typically\n  Microsoft Active Directory or LDAP) into Cisco Webex Control Hub. It\n  supports full and incremental sync, attribute mapping, dry-run preview,\n  and scheduled jobs. Programmatic management is via the related Webex\n  People, Groups, and Organizations APIs in Control Hub; modern\n  deployments\
  \ increasingly use SCIM 2.0 provisioning from identity\n  providers (Azure AD, Okta) as an alternative to the on-premises\n  connector.\napis:\n  - aid: cisco-directory-connector:cisco-directory-connector-sync-api\n    name: Cisco Directory Connector Sync API\n    tags:\n      - Directory Sync\n      - Group Management\n      - User Provisioning\n    humanURL: https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/cloudCollaboration/wbxt/directoryconnector/wbx_b_directory-connector-guide.html\n    properties:\n      - url: https://developer.webex.com/docs/api/guides/directory-connector\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/openapi.json\n        type: OpenAPI\n      - url: https://developer.webex.com/docs/integrations\n        type: Authentication\n      - url: https://developer.webex.com/docs/sdks\n        type: SDKs\n      - url: https://developer.webex.com/docs/api/basics#rate-limiting\n        type: Rate Limits\n    description: >-\n      Manage\
  \ and observe directory synchronization between on-premises\n      directory services and Cisco Webex Control Hub, including sync\n      scheduling, status, and error reporting.\n  - aid: cisco-directory-connector:webex-control-hub-api\n    name: Webex Control Hub API\n    tags:\n      - Administration\n      - Licenses\n      - Organizations\n      - Users\n    humanURL: https://admin.webex.com\n    baseURL: https://webexapis.com/v1\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/organizations\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/openapi.json\n        type: OpenAPI\n      - url: https://admin.webex.com\n        type: Console\n    description: >-\n      Administrative API for managing Webex organizations, including\n      users, groups, licenses, and directory-sync settings.\n  - aid: cisco-directory-connector:webex-scim\n    name: Webex SCIM 2.0 Provisioning\n    tags:\n      - Identity\n      - Provisioning\n      -\
  \ SCIM\n      - Standards\n    humanURL: https://developer.webex.com/docs/api/v1/scim2-people\n    baseURL: https://webexapis.com/identity/scim\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/scim2-people\n        type: Documentation\n      - url: https://datatracker.ietf.org/doc/html/rfc7644\n        type: Specification\n    description: >-\n      SCIM 2.0 endpoints used by identity providers such as Microsoft\n      Entra (Azure AD) and Okta to provision users and groups into Webex\n      as an alternative to the on-premises Directory Connector.\ncommon:\n  - type: Portal\n    url: https://developer.webex.com\n  - type: Admin Console\n    url: https://admin.webex.com\n  - type: Getting Started\n    url: https://developer.webex.com/docs/getting-started\n  - type: Authentication\n    url: https://developer.webex.com/docs/integrations\n  - type: Status\n    url: https://status.webex.com\n  - type: Blog\n    url: https://developer.webex.com/blog\n  - type: Support\n\
  \    url: https://help.webex.com\n  - type: Downloads\n    url: https://help.webex.com/en-us/article/nivpu1g/Deployment-Guide-for-Cisco-Directory-Connector\n  - type: Terms of Service\n    url: https://www.cisco.com/c/en/us/about/legal/terms-conditions.html\n  - type: Privacy Policy\n    url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html\n  - type: JSON-LD\n    url: json-ld/cisco-directory-connector-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cisco-directory-connector/refs/heads/main/apis.yml
tags:
- Active Directory
- Directory
- Enterprise
- Identity Management
- LDAP
- Provisioning
- SCIM
- Synchronization
url: https://raw.githubusercontent.com/api-evangelist/cisco-directory-connector/refs/heads/main/apis.yml
use_cases: []
---
