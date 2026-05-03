---
api_count: 6
api_specs:
- filename: Authentication_OpenAPI.json
  format: json
  label: Workday Authentication API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Authentication_OpenAPI.json
- filename: Identity_Management_OpenAPI.json
  format: json
  label: Workday Identity Management API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Identity_Management_OpenAPI.json
- filename: Security_Groups_OpenAPI.json
  format: json
  label: Workday Security Groups API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Security_Groups_OpenAPI.json
- filename: Audit_OpenAPI.json
  format: json
  label: Workday Audit and Compliance API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Audit_OpenAPI.json
- filename: Privacy_OpenAPI.json
  format: json
  label: Workday Privacy API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Privacy_OpenAPI.json
apis:
- description: Manage authentication methods, SSO configuration, and session management. Supports WS-Security authentication with Integration System Users and OAuth 2.0 token-based authentication for REST API access
  name: Workday Authentication API
  slug: ''
- description: Manage user identities, roles, and access permissions within Workday. Provides operations for tracking Workday account signons and identifying unauthorized authentication attempts, including Get_Workd
  name: Workday Identity Management API
  slug: ''
- description: Manage security groups, domain security policies, and security group memberships. Controls access to securable items within Workday domains and business processes through Integration System Security G
  name: Workday Security Groups API
  slug: ''
- description: Access audit logs, security reports, and compliance data. Provides programmatic access to audit trail information for security monitoring, regulatory compliance, and governance reporting within Workda
  name: Workday Audit and Compliance API
  slug: ''
- description: Manage data privacy settings, consent, and data subject requests. Supports GDPR and other data protection regulation compliance through programmatic access to privacy controls and data governance work
  name: Workday Privacy API
  slug: ''
- description: 'REST API for retrieving user activity logs and signon data from a Workday tenant. Returns detailed JSON records of user actions including task information, timestamps, IP addresses, activity actions, '
  name: Workday User Activity Logging API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://community.workday.com
- title: ''
  type: Getting Started
  url: https://community.workday.com/articles/1317963
- title: ''
  type: Authentication Guide
  url: https://community.workday.com/articles/1311418
- title: ''
  type: Authentication
  url: https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-authentication.html
- title: ''
  type: Best Practices
  url: https://community.workday.com/articles/security-best-practices
- title: ''
  type: Documentation
  url: https://community.workday.com/api
- title: ''
  type: Reference
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html
- title: ''
  type: Rate Limits
  url: https://community.workday.com/articles/api-rate-limits
- title: ''
  type: Status
  url: https://status.workday.com
- title: ''
  type: Support
  url: https://www.workday.com/en-us/customer-experience/support.html
- title: ''
  type: Website
  url: https://www.workday.com
- title: ''
  type: Terms of Service
  url: https://www.workday.com/en-us/legal.html
- title: ''
  type: Privacy Policy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: Security
  url: https://www.workday.com/en-us/why-workday/trust/security.html
- title: ''
  type: Compliance
  url: https://www.workday.com/en-us/why-workday/trust/compliance.html
- title: ''
  type: Blog
  url: https://blog.workday.com/en-us/application-development.html
- title: ''
  type: GitHub Organization
  url: https://github.com/workday
- title: ''
  type: Sign Up
  url: https://resourcecenter.workday.com/
- title: ''
  type: Login
  url: https://www.myworkday.com
created: '2024-01-15'
description: Collection of Workday Security APIs for managing authentication, authorization, and security configurations including identity management, security groups, audit logging, privacy, and user activity monitoring.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-16'
name: Workday Security
skills: []
slug: workday-security
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: workday-security\nspecificationVersion: '0.19'\nname: Workday Security\ndescription: >-\n  Collection of Workday Security APIs for managing authentication, authorization,\n  and security configurations including identity management, security groups,\n  audit logging, privacy, and user activity monitoring.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/workday-security/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-03-16'\napis:\n  - name: Workday Authentication API\n    description: >-\n      Manage authentication methods, SSO configuration, and session management.\n      Supports WS-Security authentication with Integration System Users and\n      OAuth 2.0 token-based authentication for REST API access.\n    image: https://www.workday.com/content/dam/web/images/icons/wd-icon.png\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Authentication.html\n\
  \    baseURL: https://wd2-impl-services1.workday.com/ccx/service/\n    tags:\n      - Authentication\n      - OAuth\n      - SAML\n      - Security\n      - SSO\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Authentication.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Authentication_OpenAPI.json\n      - type: WSDL\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Authentication.wsdl\n      - type: Authentication\n        url: https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-authentication.html\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\n        url: https://community.workday.com\n  - name: Workday Identity Management API\n    description: >-\n      Manage user identities, roles,\
  \ and access permissions within Workday.\n      Provides operations for tracking Workday account signons and identifying\n      unauthorized authentication attempts, including Get_Workday_Account_Signons\n      and Get_Unidentified_Signons operations.\n    image: https://www.workday.com/content/dam/web/images/icons/wd-icon.png\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/productionapi/Identity_Management/v45.2/Identity_Management.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/service/\n    tags:\n      - Access Management\n      - Identity\n      - Security\n      - Signons\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Identity_Management.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Identity_Management_OpenAPI.json\n      - type: WSDL\n        url:\
  \ https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Identity_Management.wsdl\n      - type: Reference\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Identity_Management/v45.2/Identity_Management.html\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\n        url: https://community.workday.com\n  - name: Workday Security Groups API\n    description: >-\n      Manage security groups, domain security policies, and security group\n      memberships. Controls access to securable items within Workday domains\n      and business processes through Integration System Security Groups and\n      role-based permission assignments.\n    image: https://www.workday.com/content/dam/web/images/icons/wd-icon.png\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Security_Groups.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/service/\n\
  \    tags:\n      - Domain Security\n      - Groups\n      - Permissions\n      - Security\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Security_Groups.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Security_Groups_OpenAPI.json\n      - type: WSDL\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Security_Groups.wsdl\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\n        url: https://community.workday.com\n  - name: Workday Audit and Compliance API\n    description: >-\n      Access audit logs, security reports, and compliance data. Provides\n      programmatic access to audit trail information for security monitoring,\n      regulatory compliance, and governance reporting within Workday.\n    image: https://www.workday.com/content/dam/web/images/icons/wd-icon.png\n\
  \    humanURL: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Audit.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/service/\n    tags:\n      - Audit\n      - Compliance\n      - Logging\n      - Security\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Audit.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Audit_OpenAPI.json\n      - type: WSDL\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Audit.wsdl\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\n        url: https://community.workday.com\n  - name: Workday Privacy API\n    description: >-\n      Manage data privacy settings, consent, and data subject requests. Supports\n      GDPR and other data protection\
  \ regulation compliance through programmatic\n      access to privacy controls and data governance workflows.\n    image: https://www.workday.com/content/dam/web/images/icons/wd-icon.png\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Privacy.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/service/\n    tags:\n      - Data Protection\n      - GDPR\n      - Privacy\n      - Security\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Privacy.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Privacy_OpenAPI.json\n      - type: WSDL\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Privacy.wsdl\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\n       \
  \ url: https://community.workday.com\n  - name: Workday User Activity Logging API\n    description: >-\n      REST API for retrieving user activity logs and signon data from a Workday\n      tenant. Returns detailed JSON records of user actions including task\n      information, timestamps, IP addresses, activity actions, system accounts,\n      and session identifiers. Used by SIEM platforms for security monitoring.\n    image: https://www.workday.com/content/dam/web/images/icons/wd-icon.png\n    humanURL: https://doc.workday.com/admin-guide/en-us/integrations/workday-rest-api/rest-api-guides/user-activity-logging-rest-api/mhr1626995534900.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/privacy/v1/\n    tags:\n      - Activity Logging\n      - Audit\n      - Security\n      - SIEM\n      - Signons\n    properties:\n      - type: Documentation\n        url: https://doc.workday.com/admin-guide/en-us/integrations/workday-rest-api/rest-api-guides/user-activity-logging-rest-api/mhr1626995534900.html\n\
  \      - type: Authentication\n        url: https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-authentication.html\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\n        url: https://community.workday.com\ncommon:\n  - type: Portal\n    url: https://community.workday.com\n  - type: Getting Started\n    url: https://community.workday.com/articles/1317963\n  - type: Authentication Guide\n    url: https://community.workday.com/articles/1311418\n  - type: Authentication\n    url: https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-authentication.html\n  - type: Best Practices\n    url: https://community.workday.com/articles/security-best-practices\n  - type: Documentation\n    url: https://community.workday.com/api\n  - type: Reference\n    url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n  - type: Rate Limits\n    url: https://community.workday.com/articles/api-rate-limits\n\
  \  - type: Status\n    url: https://status.workday.com\n  - type: Support\n    url: https://www.workday.com/en-us/customer-experience/support.html\n  - type: Website\n    url: https://www.workday.com\n  - type: Terms of Service\n    url: https://www.workday.com/en-us/legal.html\n  - type: Privacy Policy\n    url: https://www.workday.com/en-us/privacy.html\n  - type: Security\n    url: https://www.workday.com/en-us/why-workday/trust/security.html\n  - type: Compliance\n    url: https://www.workday.com/en-us/why-workday/trust/compliance.html\n  - type: Blog\n    url: https://blog.workday.com/en-us/application-development.html\n  - type: GitHub Organization\n    url: https://github.com/workday\n  - type: Sign Up\n    url: https://resourcecenter.workday.com/\n  - type: Login\n    url: https://www.myworkday.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Access Control\n  - Audit\n  - Authentication\n  - Compliance\n  - Enterprise\n\
  \  - Identity Management\n  - Privacy\n  - SAML\n  - Security\n  - SSO\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday-security/refs/heads/main/apis.yml
tags:
- Access Control
- Audit
- Authentication
- Compliance
- Enterprise
- Identity Management
- Privacy
- SAML
- Security
- SSO
url: https://raw.githubusercontent.com/api-evangelist/workday-security/refs/heads/main/apis.yml
use_cases: []
---
