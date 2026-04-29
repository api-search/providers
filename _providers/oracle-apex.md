---
api_count: 11
apis:
- description: RESTful API for Oracle APEX applications enabling data access and manipulation through REST endpoints.
  name: Oracle APEX REST Data Services API
  slug: ''
- description: API for accessing SQL Workshop functionality programmatically.
  name: Oracle APEX SQL Workshop API
  slug: ''
- description: API for managing APEX applications, pages, and components.
  name: Oracle APEX Application API
  slug: ''
- description: REST API framework integrated with APEX for creating RESTful services including modules, templates, handlers, privileges, roles, OAuth clients, and AutoREST-enabled objects.
  name: Oracle REST Data Services (ORDS) API
  slug: ''
- description: REST APIs for provisioning and managing Oracle APEX instances in Oracle Cloud Infrastructure, including workspace and application lifecycle management.
  name: Oracle APEX Cloud REST API
  slug: ''
- description: PL/SQL and REST APIs for exporting and importing APEX applications, workspaces, and components using APEX_EXPORT and related packages.
  name: Oracle APEX Export and Import API
  slug: ''
- description: PL/SQL APIs for managing approvals, human tasks, and workflows in APEX applications using the APEX_APPROVAL and workflow packages.
  name: Oracle APEX Approval and Workflow API
  slug: ''
- description: The APEX_UTIL PL/SQL package provides utility functions for user management, authentication, session management, and other common APEX operations.
  name: Oracle APEX Utility API
  slug: ''
- description: APIs for integrating generative AI capabilities into APEX applications, including chat, text generation, and vector embeddings introduced in APEX 24.2.
  name: Oracle APEX Generative AI API
  slug: ''
- description: REST API for Oracle Database management and monitoring operations through ORDS, including pluggable database management, data export, and performance monitoring.
  name: Oracle ORDS Database API
  slug: ''
- description: REST Administration API enabling APEX instance administrators to perform administrative functions over REST and HTTP protocols for machine-to-machine communication.
  name: Oracle APEX REST Administration API
  slug: ''
common:
- title: ''
  type: Documentation
  url: https://docs.oracle.com/en/database/oracle/apex/
- title: ''
  type: Blog
  url: https://blogs.oracle.com/apex/
- title: ''
  type: GitHubOrganization
  url: https://github.com/oracle/apex
- title: ''
  type: YouTube
  url: https://www.youtube.com/c/OracleAPEX
- title: ''
  type: Pricing
  url: https://www.oracle.com/application-development/apex/pricing/
- title: ''
  type: GettingStarted
  url: https://apex.oracle.com/en/learn/getting-started/
- title: ''
  type: Tutorials
  url: https://apex.oracle.com/en/learn/tutorials/
- title: ''
  type: ReleaseNotes
  url: https://apex.oracle.com/en/learn/documentation/release-notes/
- title: ''
  type: APIReference
  url: https://docs.oracle.com/en/database/oracle/apex/24.2/api-references.html
- title: ''
  type: TermsOfService
  url: https://www.oracle.com/legal/terms/
- title: ''
  type: PrivacyPolicy
  url: https://www.oracle.com/legal/privacy/privacy-policy/
- title: ''
  type: FAQ
  url: https://www.oracle.com/tools/technologies/faq-rest-data-services.html
- title: ''
  type: Support
  url: https://apex.oracle.com/community
- title: ''
  type: SignUp
  url: https://docs.oracle.com/en/cloud/paas/apex/gsadd/sign-up-for-apex-service.html
created: '2024-01-01'
description: Oracle Application Express (APEX) is a low-code development platform that enables you to build scalable, secure enterprise apps with world-class features.
features:
- description: Visual drag-and-drop application builder for creating enterprise web applications without extensive coding.
  name: Low-Code Application Development
- description: Built-in ORDS integration for exposing database objects and custom logic as REST APIs.
  name: RESTful Web Services
- description: Native AI capabilities including chat, text generation, and vector embeddings for intelligent applications.
  name: Generative AI Integration
- description: Built-in workflow engine with human task management and approval chains for business process automation.
  name: Workflow and Approvals
- description: Build installable progressive web applications with offline capabilities and native-like user experience.
  name: Progressive Web Apps
- description: Seamless deployment and management on Oracle Cloud Infrastructure with automated provisioning.
  name: Oracle Cloud Integration
image: /assets/icons/oracle-apex.png
integrations:
- description: Native integration with Oracle Database for data access, PL/SQL execution, and database object management.
  name: Oracle Database
- description: Deploy APEX applications on OCI with autonomous database and cloud-native infrastructure services.
  name: Oracle Cloud Infrastructure
- description: ORDS provides the REST API layer for APEX applications and database services.
  name: Oracle REST Data Services
- description: Single sign-on and identity management integration for enterprise authentication.
  name: Oracle Identity Cloud
- description: LDAP-based authentication and user synchronization with Active Directory environments.
  name: Microsoft Active Directory
jsonld:
- class_count: 5
  name: Oracle Apex Context
  property_count: 21
  slug: oracle-apex-context
layout: provider
modified: '2026-04-18'
name: Oracle APEX
skills: []
slug: oracle-apex
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oracle-apex\nname: Oracle APEX\ndescription: >-\n  Oracle Application Express (APEX) is a low-code development platform that\n  enables you to build scalable, secure enterprise apps with world-class features.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-apex/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\nposition: Consumer\naccess: 3rd-Party\ntags:\n  - APEX\n  - Cloud\n  - Database\n  - Development Platform\n  - Enterprise\n  - Generative AI\n  - Low-Code\n  - Oracle\n  - ORDS\n  - PL/SQL\n  - REST API\n  - Web Applications\n  - Workflow\napis:\n  - name: Oracle APEX REST Data Services API\n    description: >-\n      RESTful API for Oracle APEX applications enabling data access and\n      manipulation through REST endpoints.\n    image: https://www.oracle.com/a/ocom/img/apex-logo.png\n    humanURL:\
  \ https://apex.oracle.com/\n    baseURL: https://apex.oracle.com/pls/apex/\n    tags:\n      - Data Services\n      - Database\n      - Low-Code\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/apex/latest/htmdb/\n      - type: Authentication\n        url: https://docs.oracle.com/en/database/oracle/apex/latest/htmdb/authentication.html\n      - type: GettingStarted\n        url: https://apex.oracle.com/en/learn/getting-started/\n    contact:\n      - FN: Oracle APEX Support\n        email: apex-info_us@oracle.com\n        url: https://apex.oracle.com/community\n  - name: Oracle APEX SQL Workshop API\n    description: >-\n      API for accessing SQL Workshop functionality programmatically.\n    image: https://www.oracle.com/a/ocom/img/apex-logo.png\n    humanURL: https://apex.oracle.com/\n    baseURL: https://apex.oracle.com/pls/apex/\n    tags:\n      - Database\n      - Development\n      - SQL\n    properties:\n    \
  \  - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/apex/latest/\n      - type: Tutorials\n        url: https://apex.oracle.com/en/learn/tutorials/\n      - type: APIReference\n        url: https://docs.oracle.com/en/database/oracle/apex/24.2/aeapi/\n    contact:\n      - FN: Oracle APEX Support\n        email: apex-info_us@oracle.com\n        url: https://apex.oracle.com/community\n  - name: Oracle APEX Application API\n    description: >-\n      API for managing APEX applications, pages, and components.\n    image: https://www.oracle.com/a/ocom/img/apex-logo.png\n    humanURL: https://apex.oracle.com/\n    baseURL: https://apex.oracle.com/pls/apex/\n    tags:\n      - Applications\n      - Development\n      - Management\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/apex/latest/aeapi/\n      - type: APIReference\n        url: https://docs.oracle.com/en/database/oracle/apex/latest/aeapi/APEX_APPLICATION.html\n\
  \      - type: GettingStarted\n        url: https://apex.oracle.com/en/learn/getting-started/\n    contact:\n      - FN: Oracle APEX Support\n        email: apex-info_us@oracle.com\n        url: https://apex.oracle.com/community\n  - name: Oracle REST Data Services (ORDS) API\n    description: >-\n      REST API framework integrated with APEX for creating RESTful services\n      including modules, templates, handlers, privileges, roles, OAuth clients,\n      and AutoREST-enabled objects.\n    image: https://www.oracle.com/a/ocom/img/apex-logo.png\n    humanURL: https://www.oracle.com/database/technologies/appdev/rest.html\n    baseURL: https://example.com/ords/_/db-api/stable/\n    tags:\n      - Integration\n      - ORDS\n      - REST\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/\n      - type: APIReference\n        url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/25.2/orrst/index.html\n\
  \      - type: FAQ\n        url: https://www.oracle.com/tools/technologies/faq-rest-data-services.html\n    contact:\n      - FN: Oracle APEX Support\n        email: apex-info_us@oracle.com\n        url: https://apex.oracle.com/community\n  - name: Oracle APEX Cloud REST API\n    description: >-\n      REST APIs for provisioning and managing Oracle APEX instances in Oracle\n      Cloud Infrastructure, including workspace and application lifecycle\n      management.\n    image: https://www.oracle.com/a/ocom/img/apex-logo.png\n    humanURL: https://docs.oracle.com/en/cloud/paas/apex/rest-apis.html\n    baseURL: https://apex.oracle.com/pls/apex/\n    tags:\n      - Administration\n      - Cloud\n      - Oracle Cloud\n      - Provisioning\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/paas/apex/rest-apis.html\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/cloud/paas/apex/gsadd/sign-up-for-apex-service.html\n\
  \    contact:\n      - FN: Oracle APEX Support\n        email: apex-info_us@oracle.com\n        url: https://apex.oracle.com/community\n  - name: Oracle APEX Export and Import API\n    description: >-\n      PL/SQL and REST APIs for exporting and importing APEX applications,\n      workspaces, and components using APEX_EXPORT and related packages.\n    image: https://www.oracle.com/a/ocom/img/apex-logo.png\n    humanURL: https://docs.oracle.com/en/database/oracle/apex/24.2/aeapi/APEX_EXPORT.html\n    baseURL: https://apex.oracle.com/pls/apex/\n    tags:\n      - Applications\n      - Deployment\n      - Export\n      - Import\n      - PL/SQL\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/apex/24.2/aeapi/APEX_EXPORT.html\n      - type: APIReference\n        url: https://docs.oracle.com/en/database/oracle/apex/24.2/aeapi/\n    contact:\n      - FN: Oracle APEX Support\n        email: apex-info_us@oracle.com\n        url: https://apex.oracle.com/community\n\
  \  - name: Oracle APEX Approval and Workflow API\n    description: >-\n      PL/SQL APIs for managing approvals, human tasks, and workflows in APEX\n      applications using the APEX_APPROVAL and workflow packages.\n    image: https://www.oracle.com/a/ocom/img/apex-logo.png\n    humanURL: https://docs.oracle.com/en/database/oracle/apex/24.2/aeapi/\n    baseURL: https://apex.oracle.com/pls/apex/\n    tags:\n      - Approval\n      - Automation\n      - Human Tasks\n      - PL/SQL\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/apex/23.2/aeapi/APEX_APPROVAL.html\n      - type: APIReference\n        url: https://docs.oracle.com/en/database/oracle/apex/24.2/aeapi/\n    contact:\n      - FN: Oracle APEX Support\n        email: apex-info_us@oracle.com\n        url: https://apex.oracle.com/community\n  - name: Oracle APEX Utility API\n    description: >-\n      The APEX_UTIL PL/SQL package provides utility functions for\
  \ user\n      management, authentication, session management, and other common APEX\n      operations.\n    image: https://www.oracle.com/a/ocom/img/apex-logo.png\n    humanURL: https://docs.oracle.com/en/database/oracle/apex/24.2/aeapi/\n    baseURL: https://apex.oracle.com/pls/apex/\n    tags:\n      - Authentication\n      - PL/SQL\n      - Session\n      - User Management\n      - Utility\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/apex/24.2/aeapi/\n      - type: APIReference\n        url: https://docs.oracle.com/en/database/oracle/apex/24.2/aeapi/APEX_UTIL.html\n    contact:\n      - FN: Oracle APEX Support\n        email: apex-info_us@oracle.com\n        url: https://apex.oracle.com/community\n  - name: Oracle APEX Generative AI API\n    description: >-\n      APIs for integrating generative AI capabilities into APEX applications,\n      including chat, text generation, and vector embeddings introduced in APEX\n      24.2.\n\
  \    image: https://www.oracle.com/a/ocom/img/apex-logo.png\n    humanURL: https://apex.oracle.com/en/platform/features/whats-new-242/\n    baseURL: https://apex.oracle.com/pls/apex/\n    tags:\n      - AI\n      - Generative AI\n      - Machine Learning\n      - PL/SQL\n      - Vector Search\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/apex/24.2/aeapi/\n      - type: ReleaseNotes\n        url: https://docs.oracle.com/en/database/oracle/apex/24.2/aeapi/changes-in-this-release.html\n      - type: Features\n        url: https://apex.oracle.com/en/platform/features/whats-new-242/\n    contact:\n      - FN: Oracle APEX Support\n        email: apex-info_us@oracle.com\n        url: https://apex.oracle.com/community\n  - name: Oracle ORDS Database API\n    description: >-\n      REST API for Oracle Database management and monitoring operations through\n      ORDS, including pluggable database management, data export, and performance\n\
  \      monitoring.\n    image: https://www.oracle.com/a/ocom/img/apex-logo.png\n    humanURL: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/25.2/\n    baseURL: https://example.com/ords/\n    tags:\n      - Database\n      - Management\n      - Monitoring\n      - ORDS\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/25.2/\n      - type: APIReference\n        url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/25.2/orrst/toc.htm\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/25.2/\n    contact:\n      - FN: Oracle APEX Support\n        email: apex-info_us@oracle.com\n        url: https://apex.oracle.com/community\n  - name: Oracle APEX REST Administration API\n    description: >-\n      REST Administration API enabling APEX instance administrators to perform\n      administrative functions\
  \ over REST and HTTP protocols for machine-to-machine\n      communication.\n    image: https://www.oracle.com/a/ocom/img/apex-logo.png\n    humanURL: https://docs.oracle.com/database/apex-5.1/AEAPI/Using-REST-Administration-Interface-API.htm\n    baseURL: https://apex.oracle.com/pls/apex/\n    tags:\n      - Administration\n      - Automation\n      - Instance Management\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/database/apex-5.1/AEAPI/Using-REST-Administration-Interface-API.htm\n      - type: APIReference\n        url: https://docs.oracle.com/en/database/oracle/apex/24.2/aeapi/\n    contact:\n      - FN: Oracle APEX Support\n        email: apex-info_us@oracle.com\n        url: https://apex.oracle.com/community\ncommon:\n  - type: Documentation\n    url: https://docs.oracle.com/en/database/oracle/apex/\n  - type: Blog\n    url: https://blogs.oracle.com/apex/\n  - type: GitHubOrganization\n    url: https://github.com/oracle/apex\n\
  \  - type: YouTube\n    url: https://www.youtube.com/c/OracleAPEX\n  - type: Pricing\n    url: https://www.oracle.com/application-development/apex/pricing/\n  - type: GettingStarted\n    url: https://apex.oracle.com/en/learn/getting-started/\n  - type: Tutorials\n    url: https://apex.oracle.com/en/learn/tutorials/\n  - type: ReleaseNotes\n    url: https://apex.oracle.com/en/learn/documentation/release-notes/\n  - type: APIReference\n    url: https://docs.oracle.com/en/database/oracle/apex/24.2/api-references.html\n  - type: TermsOfService\n    url: https://www.oracle.com/legal/terms/\n  - type: PrivacyPolicy\n    url: https://www.oracle.com/legal/privacy/privacy-policy/\n  - type: FAQ\n    url: https://www.oracle.com/tools/technologies/faq-rest-data-services.html\n  - type: Support\n    url: https://apex.oracle.com/community\n  - type: SignUp\n    url: https://docs.oracle.com/en/cloud/paas/apex/gsadd/sign-up-for-apex-service.html\n  - type: Features\n    data:\n      - name: Low-Code\
  \ Application Development\n        description: Visual drag-and-drop application builder for creating enterprise web applications without extensive coding.\n      - name: RESTful Web Services\n        description: Built-in ORDS integration for exposing database objects and custom logic as REST APIs.\n      - name: Generative AI Integration\n        description: Native AI capabilities including chat, text generation, and vector embeddings for intelligent applications.\n      - name: Workflow and Approvals\n        description: Built-in workflow engine with human task management and approval chains for business process automation.\n      - name: Progressive Web Apps\n        description: Build installable progressive web applications with offline capabilities and native-like user experience.\n      - name: Oracle Cloud Integration\n        description: Seamless deployment and management on Oracle Cloud Infrastructure with automated provisioning.\n  - type: UseCases\n    data:\n      - name:\
  \ Enterprise Application Development\n        description: Rapidly build and deploy internal enterprise applications for HR, finance, and operations.\n      - name: Database REST API Creation\n        description: Expose Oracle Database tables and views as RESTful services using ORDS AutoREST.\n      - name: Workflow Automation\n        description: Automate business approval processes and multi-step workflows with the APEX workflow engine.\n      - name: Data Management Portals\n        description: Build self-service data entry and management portals for business users with built-in validation.\n      - name: AI-Enhanced Applications\n        description: Integrate generative AI features into business applications for intelligent data processing and insights.\n  - type: Integrations\n    data:\n      - name: Oracle Database\n        description: Native integration with Oracle Database for data access, PL/SQL execution, and database object management.\n      - name: Oracle Cloud Infrastructure\n\
  \        description: Deploy APEX applications on OCI with autonomous database and cloud-native infrastructure services.\n      - name: Oracle REST Data Services\n        description: ORDS provides the REST API layer for APEX applications and database services.\n      - name: Oracle Identity Cloud\n        description: Single sign-on and identity management integration for enterprise authentication.\n      - name: Microsoft Active Directory\n        description: LDAP-based authentication and user synchronization with Active Directory environments.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-apex/refs/heads/main/apis.yml
tags:
- APEX
- Cloud
- Database
- Development Platform
- Enterprise
- Generative AI
- Low-Code
- Oracle
- ORDS
- PL/SQL
- REST API
- Web Applications
- Workflow
url: https://raw.githubusercontent.com/api-evangelist/oracle-apex/refs/heads/main/apis.yml
use_cases:
- description: Rapidly build and deploy internal enterprise applications for HR, finance, and operations.
  name: Enterprise Application Development
- description: Expose Oracle Database tables and views as RESTful services using ORDS AutoREST.
  name: Database REST API Creation
- description: Automate business approval processes and multi-step workflows with the APEX workflow engine.
  name: Workflow Automation
- description: Build self-service data entry and management portals for business users with built-in validation.
  name: Data Management Portals
- description: Integrate generative AI features into business applications for intelligent data processing and insights.
  name: AI-Enhanced Applications
---
