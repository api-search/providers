---
api_count: 51
apis:
- description: The Box Authorize API initiates the OAuth 2.0 authorization flow by redirecting users to the Box website to grant permission for applications to act on their behalf, providing the first step in authen
  name: Box Authorize API
  slug: box-authorize-api
- description: The Box OAuth2 API manages OAuth 2.0 access tokens, allowing applications to request, refresh, and revoke tokens used for authenticating API calls to the Box Platform.
  name: Box Oauth2 API
  slug: box-oauth2-api
- description: The Box Files API provides endpoints for managing files stored in Box, including copying, getting file information, updating file details, deleting files, and managing file metadata such as thumbnails
  name: Box Files API
  slug: box-files-api
- description: The Box File Requests API allows users to create, retrieve, update, and delete file requests, which enable external users to upload files to a specific Box folder through a personalized URL.
  name: Box File Requests API
  slug: box-file-requests-api
- description: The Box Folders API provides endpoints for managing folders in Box, including creating, copying, listing items, getting folder information, updating, and deleting folders, as well as managing folder c
  name: Box Folders API
  slug: box-folders-api
- description: The Box Folder Locks API provides endpoints for creating, listing, and deleting folder locks, which prevent folders from being moved or deleted by users other than the lock creator.
  name: Box Folder Locks API
  slug: box-folder-locks-api
- description: The Box Metadata Templates API allows creation and management of metadata templates that define the structure and fields of metadata that can be applied to files and folders in Box for custom categori
  name: Box Metadata Templates API
  slug: box-metadata-templates-api
- description: The Box Metadata Cascade Policies API allows configuration of policies that automatically apply metadata templates from a parent folder to all files and subfolders within it, ensuring consistent metad
  name: Box Metadata Cascade Policies API
  slug: box-metadata-cascade-policies-api
- description: The Box Metadata Queries API enables executing structured queries against metadata applied to files and folders, allowing applications to search for and filter content based on custom metadata field v
  name: Box Metadata Queries API
  slug: box-metadata-queries-api
- description: The Box Comments API provides endpoints for creating, retrieving, updating, and deleting comments on files, enabling users to have threaded discussions and collaborate on content stored in Box.
  name: Box Comments API
  slug: box-comments-api
- description: The Box Collaborations API manages sharing permissions for files and folders, allowing applications to invite users, set access levels, accept or reject collaboration invitations, and list existing co
  name: Box Collaborations API
  slug: box-collaborations-api
- description: The Box Search API enables full-text search across content stored in Box, supporting keyword queries, metadata-based filtering, content type restrictions, date range filters, and other advanced search
  name: Box Search API
  slug: box-search-api
- description: The Box Tasks API allows creation and management of tasks on files, enabling assignment of review or approval workflows to content stored in Box.
  name: Box Tasks API
  slug: box-tasks-api
- description: The Box Task Assignments API manages the assignment of tasks to specific users, including creating, retrieving, updating, and deleting task assignments for file review and approval workflows.
  name: Box Task Assignments API
  slug: box-task-assignments-api
- description: The Box Shared Items API allows retrieval of file information for items accessed through shared links, enabling applications to resolve shared link URLs to their underlying file objects.
  name: Box Shared Items API
  slug: box-shared-items-api
- description: The Box Shared Items Folders API manages shared links for folders, allowing applications to create, update, retrieve, and remove shared links that provide external access to folder content.
  name: Box Shared Items#folders API
  slug: box-shared-itemsfolders-api
- description: The Box Web Links API manages web link (bookmark) objects in Box, allowing applications to create, retrieve, update, and delete URL bookmarks stored alongside files and folders.
  name: Box Web Links API
  slug: box-web-links-api
- description: The Box Shared Items Web Links API manages shared links for web link objects, enabling applications to create, update, retrieve, and remove shared links that provide external access to bookmarked URLs
  name: Box Shared Items#web Links API
  slug: box-shared-itemsweb-links-api
- description: The Box Users API provides endpoints for creating, retrieving, updating, and deleting user accounts, including managed users and app users, as well as listing enterprise users and managing user settin
  name: Box Users API
  slug: box-users-api
- description: The Box Invites API allows inviting existing Box users to join an enterprise, managing the process of adding users to organizational accounts.
  name: Box Invites API
  slug: box-invites-api
- description: The Box Groups API provides endpoints for creating, listing, retrieving, updating, and deleting groups within an enterprise, enabling organized management of user permissions and collaboration access.
  name: Box Groups API
  slug: box-groups-api
- description: The Box Group Memberships API manages the relationship between users and groups, allowing applications to add users to groups, retrieve membership details, update roles, and remove members.
  name: Box Group Memberships API
  slug: box-group-memberships-api
- description: The Box Webhooks API enables applications to receive real-time notifications when events occur on files and folders in Box, such as uploads, downloads, comments, and collaboration changes.
  name: Box Webhooks API
  slug: box-webhooks-api
- description: The Box Skill Invocations API manages Box Skills, which are custom applications that perform machine learning analysis on files uploaded to Box, applying metadata cards with extracted insights such as
  name: Box Skill Invocations API
  slug: box-skill-invocations-api
- description: The Box Events API provides access to user and enterprise event streams, enabling applications to monitor file activity, track audit logs, and receive real-time notifications about actions taken on co
  name: Box Events API
  slug: box-events-api
- description: The Box Collections API manages collections such as Favorites, allowing applications to list available collections and retrieve the items within them for organizing frequently accessed content.
  name: Box Collections API
  slug: box-collections-api
- description: The Box Recent Items API returns a list of files and folders that have been recently accessed by the authenticated user, enabling quick access to frequently used content.
  name: Box Recent Items API
  slug: box-recent-items-api
- description: The Box Retention Policies API allows creating and managing retention policies that enforce how long content must be kept in Box before it can be deleted, supporting regulatory compliance and informat
  name: Box Retention Policies API
  slug: box-retention-policies-api
- description: The Box Retention Policy Assignments API manages the application of retention policies to specific folders, enterprises, or metadata templates, controlling which content is subject to retention rules.
  name: Box Retention Policy Assignments API
  slug: box-retention-policy-assignments-api
- description: The Box Legal Hold Policies API enables creating and managing legal hold policies that prevent content from being modified or deleted during legal proceedings, supporting e-discovery and litigation ho
  name: Box Legal Hold Policies API
  slug: box-legal-hold-policies-api
- description: The Box Legal Hold Policy Assignments API manages the assignment of legal hold policies to specific users, folders, or files, controlling which content is preserved under legal hold.
  name: Box Legal Hold Policy Assignments API
  slug: box-legal-hold-policy-assignments-api
- description: The Box File Version Retentions API provides information about file versions that are under retention, allowing applications to list and retrieve details about retained file versions and their associa
  name: Box File Version Retentions API
  slug: box-file-version-retentions-api
- description: The Box File Version Legal Holds API provides information about file versions currently under legal hold, enabling applications to list and retrieve details about held file versions and their associat
  name: Box File Version Legal Holds API
  slug: box-file-version-legal-holds-api
- description: The Box Shield Information Barriers API creates and manages information barriers that prevent communication and collaboration between specific groups of users within an enterprise, supporting regulato
  name: Box Shield Information Barriers API
  slug: box-shield-information-barriers-api
- description: The Box Shield Information Barrier Reports API generates and retrieves reports about information barrier configurations and violations, providing visibility into barrier effectiveness and compliance s
  name: Box Shield Information Barrier Reports API
  slug: box-shield-information-barrier-reports-api
- description: The Box Shield Information Barrier Segments API manages the user segments that define the boundaries of information barriers, allowing creation, retrieval, updating, and deletion of segments used in b
  name: Box Shield Information Barrier Segments API
  slug: box-shield-information-barrier-segments-api
- description: The Box Shield Information Barrier Segment Members API manages the users assigned to information barrier segments, controlling which users belong to each restricted group within an information barrier
  name: Box Shield Information Barrier Segment Members API
  slug: box-shield-information-barrier-segment-members-api
- description: The Box Shield Information Barrier Segment Restrictions API defines the restriction rules between information barrier segments, specifying which pairs of segments are prevented from collaborating with
  name: Box Shield Information Barrier Segment Restrictions API
  slug: box-shield-information-barrier-segment-restrictions-api
- description: The Box Device Pinners API manages device pinning for enterprise accounts, allowing administrators to view and remove pinned devices that users have associated with their Box accounts for enhanced sec
  name: Box Device Pinners API
  slug: box-device-pinners-api
- description: The Box Enterprises API provides administrative endpoints for managing enterprise-level settings and configurations, including enterprise user management and organizational controls.
  name: Box Enterprises API
  slug: box-enterprises-api
- description: The Box Terms of Services API enables creation and management of custom terms of service agreements that users must accept before accessing content in an enterprise Box account.
  name: Box Terms Of Services API
  slug: box-terms-of-services-api
- description: The Box Terms of Service User Statuses API tracks and manages whether individual users have accepted or rejected specific terms of service agreements within the enterprise.
  name: Box Terms Of Service User Statuses API
  slug: box-terms-of-service-user-statuses-api
- description: The Box Collaboration Whitelist Entries API manages domain restrictions for collaborations, allowing administrators to specify which external domains are allowed to collaborate with enterprise users.
  name: Box Collaboration Whitelist Entries API
  slug: box-collaboration-whitelist-entries-api
- description: Needs a description.
  name: Box Collaboration Whitelist Exempt Targets API
  slug: box-collaboration-whitelist-exempt-targets-api
- description: Needs a description.
  name: Box Storage Policies API
  slug: box-storage-policies-api
- description: Needs a description.
  name: Box Storage Policy Assignments API
  slug: box-storage-policy-assignments-api
- description: Needs a description.
  name: Box Zip Downloads API
  slug: box-zip-downloads-api
- description: Needs a description.
  name: Box Sign Requests API
  slug: box-sign-requests-api
- description: Needs a description.
  name: Box Workflows API
  slug: box-workflows-api
- description: Needs a description.
  name: Box Sign Templates API
  slug: box-sign-templates-api
- description: Needs a description.
  name: Box Integration Mappings API
  slug: box-integration-mappings-api
common:
- title: ''
  type: Blog
  url: https://medium.com/box-developer-blog
- title: ''
  type: Newsletter
  url: https://developer.box.com/newsletter/
- title: ''
  type: Change Log
  url: https://developer.box.com/changelog/
- title: ''
  type: Samples
  url: https://github.com/box/samples
- title: ''
  type: Forum
  url: https://support.box.com/hc/en-us/community/topics/360001932973-Platform-and-Developer-Forum
- title: ''
  type: Status
  url: https://status.box.com/
- title: ''
  type: Feedback
  url: https://pulse.box.com/forums/909778-product-feedback?category_id=330838
- title: ''
  type: Login
  url: https://account.box.com/login
- title: ''
  type: Pricing
  url: https://www.box.com/pricing
- title: ''
  type: Node SDK
  url: https://github.com/box/box-node-sdk
- title: ''
  type: Java SDK
  url: https://github.com/box/box-java-sdk
- title: ''
  type: Python SDK
  url: https://github.com/box/box-python-sdk
- title: ''
  type: .NET SDK
  url: https://github.com/box/box-windows-sdk-v2
- title: ''
  type: iOS Content SDK
  url: https://github.com/box/box-ios-sdk
- title: ''
  type: CLI
  url: https://github.com/box/boxcli
- title: ''
  type: Developer Portal
  url: https://developer.box.com/
- title: ''
  type: Support
  url: https://support.box.com/
- title: ''
  type: Community
  url: https://community.box.com/
- title: ''
  type: Terms of Service
  url: https://www.box.com/legal/termsofservice
- title: ''
  type: Privacy Policy
  url: https://www.box.com/legal/privacypolicy
- title: ''
  type: Sign Up
  url: https://account.box.com/signup
- title: ''
  type: GitHub Organization
  url: https://github.com/box
- title: ''
  type: Postman Collection
  url: https://www.postman.com/box
created: 2023/11/09
description: Box is a cloud content management and file sharing service for businesses. Box provides a secure platform for storing, managing, and sharing files and content, with features for collaboration, workflow automation, and integration with other business applications.
features: []
image: https://www.box.com/themes/custom/box/logo.svg
integrations: []
layout: provider
modified: '2024-12-22'
name: Box
skills: []
slug: box
solutions: []
source_yaml: "aid: box\nurl: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/box.yml\napis:\n  - aid: box:box-authorize-api\n    name: Box Authorize API\n    tags:\n      - Authentication\n      - Authorization\n      - OAuth\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://account.box.com/api/oauth2\n    humanURL: https://developer.box.com/reference/get-authorize\n    properties:\n      - url: https://developer.box.com/reference/get-authorize\n        type: Documentation\n      - url: openapi/authorize-openapi-original.yml\n        type: OpenAPI\n    description: The Box Authorize API initiates the OAuth 2.0 authorization flow by redirecting users to the Box website to grant permission for applications to act on their behalf, providing the first step in authenticating users with Box.\n  - aid: box:box-oauth2-api\n    name: Box Oauth2 API\n    tags:\n      - Authentication\n      - OAuth\n      - Tokens\n    image:\
  \ https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/oauth2\n    humanURL: https://developer.box.com/reference/post-oauth2-token\n    properties:\n      - url: https://developer.box.com/reference/post-oauth2-token\n        type: Documentation\n      - url: openapi/oauth2-openapi-original.yml\n        type: OpenAPI\n    description: The Box OAuth2 API manages OAuth 2.0 access tokens, allowing applications to request, refresh, and revoke tokens used for authenticating API calls to the Box Platform.\n  - aid: box:box-files-api\n    name: Box Files API\n    tags:\n      - Content\n      - Documents\n      - Files\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-files-id-copy\n    properties:\n      - url: https://developer.box.com/reference/post-files-id-copy\n        type: Documentation\n      - url: openapi/files-openapi-original.yml\n\
  \        type: OpenAPI\n    description: The Box Files API provides endpoints for managing files stored in Box, including copying, getting file information, updating file details, deleting files, and managing file metadata such as thumbnails, collaborations, comments, and tasks.\n  - aid: box:box-file-requests-api\n    name: Box File Requests API\n    tags:\n      - Files\n      - Requests\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-file-requests-id-copy\n    properties:\n      - url: https://developer.box.com/reference/post-file-requests-id-copy\n        type: Documentation\n      - url: openapi/file-requests-openapi-original.yml\n        type: OpenAPI\n    description: The Box File Requests API allows users to create, retrieve, update, and delete file requests, which enable external users to upload files to a specific Box folder through a personalized\
  \ URL.\n  - aid: box:box-folders-api\n    name: Box Folders API\n    tags:\n      - Content\n      - Directories\n      - Folders\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-folders-id-copy\n    properties:\n      - url: https://developer.box.com/reference/post-folders-id-copy\n        type: Documentation\n      - url: openapi/folders-openapi-original.yml\n        type: OpenAPI\n    description: The Box Folders API provides endpoints for managing folders in Box, including creating, copying, listing items, getting folder information, updating, and deleting folders, as well as managing folder collaborations and metadata.\n  - aid: box:box-folder-locks-api\n    name: Box Folder Locks API\n    tags:\n      - Folders\n      - Locks\n      - Security\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n\
  \    humanURL: https://developer.box.com/reference/post-folder-locks\n    properties:\n      - url: https://developer.box.com/reference/post-folder-locks\n        type: Documentation\n      - url: openapi/folder-locks-openapi-original.yml\n        type: OpenAPI\n    description: The Box Folder Locks API provides endpoints for creating, listing, and deleting folder locks, which prevent folders from being moved or deleted by users other than the lock creator.\n  - aid: box:box-metadata-templates-api\n    name: Box Metadata Templates API\n    tags:\n      - Metadata\n      - Schemas\n      - Templates\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-metadata-templates-schema\n    properties:\n      - url: https://developer.box.com/reference/post-metadata-templates-schema\n        type: Documentation\n      - url: openapi/metadata-templates-openapi-original.yml\n\
  \        type: OpenAPI\n    description: The Box Metadata Templates API allows creation and management of metadata templates that define the structure and fields of metadata that can be applied to files and folders in Box for custom categorization and organization.\n  - aid: box:box-metadata-cascade-policies-api\n    name: Box Metadata Cascade Policies API\n    tags:\n      - Cascade\n      - Metadata\n      - Policies\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-metadata-cascade-policies\n    properties:\n      - url: https://developer.box.com/reference/post-metadata-cascade-policies\n        type: Documentation\n      - url: openapi/metadata-cascade-policies-openapi-original.yml\n        type: OpenAPI\n    description: The Box Metadata Cascade Policies API allows configuration of policies that automatically apply metadata templates from a parent folder\
  \ to all files and subfolders within it, ensuring consistent metadata across content hierarchies.\n  - aid: box:box-metadata-queries-api\n    name: Box Metadata Queries API\n    tags:\n      - Metadata\n      - Queries\n      - Search\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-metadata-queries-execute-read\n    properties:\n      - url: https://developer.box.com/reference/post-metadata-queries-execute-read\n        type: Documentation\n      - url: openapi/metadata-queries-openapi-original.yml\n        type: OpenAPI\n    description: The Box Metadata Queries API enables executing structured queries against metadata applied to files and folders, allowing applications to search for and filter content based on custom metadata field values.\n  - aid: box:box-comments-api\n    name: Box Comments API\n    tags:\n      - Collaboration\n      - Comments\n  \
  \  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-comments\n    properties:\n      - url: https://developer.box.com/reference/post-comments\n        type: Documentation\n      - url: openapi/comments-openapi-original.yml\n        type: OpenAPI\n    description: The Box Comments API provides endpoints for creating, retrieving, updating, and deleting comments on files, enabling users to have threaded discussions and collaborate on content stored in Box.\n  - aid: box:box-collaborations-api\n    name: Box Collaborations API\n    tags:\n      - Collaborations\n      - Permissions\n      - Sharing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-collaborations\n    properties:\n      - url: https://developer.box.com/reference/post-collaborations\n\
  \        type: Documentation\n      - url: openapi/collaborations-openapi-original.yml\n        type: OpenAPI\n    description: The Box Collaborations API manages sharing permissions for files and folders, allowing applications to invite users, set access levels, accept or reject collaboration invitations, and list existing collaborations.\n  - aid: box:box-search-api\n    name: Box Search API\n    tags:\n      - Content Discovery\n      - Search\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-metadata-queries-execute-read\n    properties:\n      - url: https://developer.box.com/reference/post-metadata-queries-execute-read\n        type: Documentation\n      - url: openapi/search-openapi-original.yml\n        type: OpenAPI\n    description: The Box Search API enables full-text search across content stored in Box, supporting keyword queries, metadata-based\
  \ filtering, content type restrictions, date range filters, and other advanced search parameters.\n  - aid: box:box-tasks-api\n    name: Box Tasks API\n    tags:\n      - Tasks\n      - Workflow\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-tasks\n    properties:\n      - url: https://developer.box.com/reference/post-tasks\n        type: Documentation\n      - url: openapi/tasks-openapi-original.yml\n        type: OpenAPI\n    description: The Box Tasks API allows creation and management of tasks on files, enabling assignment of review or approval workflows to content stored in Box.\n  - aid: box:box-task-assignments-api\n    name: Box Task Assignments API\n    tags:\n      - Assignments\n      - Tasks\n      - Workflow\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL:\
  \ https://developer.box.com/reference/post-task-assignments\n    properties:\n      - url: https://developer.box.com/reference/post-task-assignments\n        type: Documentation\n      - url: openapi/task-assignments-openapi-original.yml\n        type: OpenAPI\n    description: The Box Task Assignments API manages the assignment of tasks to specific users, including creating, retrieving, updating, and deleting task assignments for file review and approval workflows.\n  - aid: box:box-shared-items-api\n    name: Box Shared Items API\n    tags:\n      - Shared Links\n      - Sharing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/put-files-id--add-shared-link\n    properties:\n      - url: https://developer.box.com/reference/put-files-id--add-shared-link\n        type: Documentation\n      - url: openapi/shared-items-openapi-original.yml\n        type: OpenAPI\n\
  \    description: The Box Shared Items API allows retrieval of file information for items accessed through shared links, enabling applications to resolve shared link URLs to their underlying file objects.\n  - aid: box:box-shared-itemsfolders-api\n    name: Box Shared Items#folders API\n    tags:\n      - Folders\n      - Shared Links\n      - Sharing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/put-folders-id--add-shared-link\n    properties:\n      - url: https://developer.box.com/reference/put-folders-id--add-shared-link\n        type: Documentation\n      - url: openapi/shared-itemsfolders-openapi-original.yml\n        type: OpenAPI\n    description: The Box Shared Items Folders API manages shared links for folders, allowing applications to create, update, retrieve, and remove shared links that provide external access to folder content.\n  - aid: box:box-web-links-api\n\
  \    name: Box Web Links API\n    tags:\n      - Bookmarks\n      - Web Links\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-web-links\n    properties:\n      - url: https://developer.box.com/reference/post-web-links\n        type: Documentation\n      - url: openapi/web-links-openapi-original.yml\n        type: OpenAPI\n    description: The Box Web Links API manages web link (bookmark) objects in Box, allowing applications to create, retrieve, update, and delete URL bookmarks stored alongside files and folders.\n  - aid: box:box-shared-itemsweb-links-api\n    name: Box Shared Items#web Links API\n    tags:\n      - Shared Links\n      - Sharing\n      - Web Links\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/put-web-links-id--add-shared-link\n\
  \    properties:\n      - url: https://developer.box.com/reference/put-web-links-id--add-shared-link\n        type: Documentation\n      - url: openapi/shared-itemsweb-links-openapi-original.yml\n        type: OpenAPI\n    description: The Box Shared Items Web Links API manages shared links for web link objects, enabling applications to create, update, retrieve, and remove shared links that provide external access to bookmarked URLs.\n  - aid: box:box-users-api\n    name: Box Users API\n    tags:\n      - Accounts\n      - Administration\n      - Users\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-users\n    properties:\n      - url: https://developer.box.com/reference/post-users\n        type: Documentation\n      - url: openapi/users-openapi-original.yml\n        type: OpenAPI\n    description: The Box Users API provides endpoints for creating, retrieving,\
  \ updating, and deleting user accounts, including managed users and app users, as well as listing enterprise users and managing user settings.\n  - aid: box:box-invites-api\n    name: Box Invites API\n    tags:\n      - Invites\n      - Users\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-invites\n    properties:\n      - url: https://developer.box.com/reference/post-invites\n        type: Documentation\n      - url: openapi/invites-openapi-original.yml\n        type: OpenAPI\n    description: The Box Invites API allows inviting existing Box users to join an enterprise, managing the process of adding users to organizational accounts.\n  - aid: box:box-groups-api\n    name: Box Groups API\n    tags:\n      - Administration\n      - Groups\n      - Users\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n\
  \    humanURL: https://developer.box.com/reference/post-groups\n    properties:\n      - url: https://developer.box.com/reference/post-groups\n        type: Documentation\n      - url: openapi/groups-openapi-original.yml\n        type: OpenAPI\n    description: The Box Groups API provides endpoints for creating, listing, retrieving, updating, and deleting groups within an enterprise, enabling organized management of user permissions and collaboration access.\n  - aid: box:box-group-memberships-api\n    name: Box Group Memberships API\n    tags:\n      - Groups\n      - Memberships\n      - Users\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-group-memberships\n    properties:\n      - url: https://developer.box.com/reference/post-group-memberships\n        type: Documentation\n      - url: openapi/group-memberships-openapi-original.yml\n        type: OpenAPI\n\
  \    description: The Box Group Memberships API manages the relationship between users and groups, allowing applications to add users to groups, retrieve membership details, update roles, and remove members.\n  - aid: box:box-webhooks-api\n    name: Box Webhooks API\n    tags:\n      - Events\n      - Notifications\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-webhooks\n    properties:\n      - url: https://developer.box.com/reference/post-webhooks\n        type: Documentation\n      - url: openapi/webhooks-openapi-original.yml\n        type: OpenAPI\n    description: The Box Webhooks API enables applications to receive real-time notifications when events occur on files and folders in Box, such as uploads, downloads, comments, and collaboration changes.\n  - aid: box:box-skill-invocations-api\n    name: Box Skill Invocations API\n    tags:\n\
  \      - AI\n      - Machine Learning\n      - Skills\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-files-id-metadata-global-boxSkillsCards\n    properties:\n      - url: https://developer.box.com/reference/post-files-id-metadata-global-boxSkillsCards\n        type: Documentation\n      - url: openapi/skill-invocations-openapi-original.yml\n        type: OpenAPI\n    description: The Box Skill Invocations API manages Box Skills, which are custom applications that perform machine learning analysis on files uploaded to Box, applying metadata cards with extracted insights such as transcripts, topics, and key phrases.\n  - aid: box:box-events-api\n    name: Box Events API\n    tags:\n      - Activity\n      - Audit\n      - Events\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n \
  \   humanURL: https://developer.box.com/reference/options-events\n    properties:\n      - url: https://developer.box.com/reference/options-events\n        type: Documentation\n      - url: openapi/events-openapi-original.yml\n        type: OpenAPI\n    description: The Box Events API provides access to user and enterprise event streams, enabling applications to monitor file activity, track audit logs, and receive real-time notifications about actions taken on content in Box.\n  - aid: box:box-collections-api\n    name: Box Collections API\n    tags:\n      - Collections\n      - Favorites\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/get-collections-id\n    properties:\n      - url: https://developer.box.com/reference/get-collections-id\n        type: Documentation\n      - url: openapi/collections-openapi-original.yml\n        type: OpenAPI\n    description:\
  \ The Box Collections API manages collections such as Favorites, allowing applications to list available collections and retrieve the items within them for organizing frequently accessed content.\n  - aid: box:box-recent-items-api\n    name: Box Recent Items API\n    tags:\n      - Activity\n      - Recent Items\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/get-recent-items\n    properties:\n      - url: https://developer.box.com/reference/get-recent-items\n        type: Documentation\n      - url: openapi/recent-items-openapi-original.yml\n        type: OpenAPI\n    description: The Box Recent Items API returns a list of files and folders that have been recently accessed by the authenticated user, enabling quick access to frequently used content.\n  - aid: box:box-retention-policies-api\n    name: Box Retention Policies API\n    tags:\n      - Governance\n\
  \      - Policies\n      - Retention\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-retention-policies\n    properties:\n      - url: https://developer.box.com/reference/post-retention-policies\n        type: Documentation\n      - url: openapi/retention-policies-openapi-original.yml\n        type: OpenAPI\n    description: The Box Retention Policies API allows creating and managing retention policies that enforce how long content must be kept in Box before it can be deleted, supporting regulatory compliance and information governance requirements.\n  - aid: box:box-retention-policy-assignments-api\n    name: Box Retention Policy Assignments API\n    tags:\n      - Assignments\n      - Governance\n      - Retention\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-retention-policy-assignments\n\
  \    properties:\n      - url: https://developer.box.com/reference/post-retention-policy-assignments\n        type: Documentation\n      - url: openapi/retention-policy-assignments-openapi-original.yml\n        type: OpenAPI\n    description: The Box Retention Policy Assignments API manages the application of retention policies to specific folders, enterprises, or metadata templates, controlling which content is subject to retention rules.\n  - aid: box:box-legal-hold-policies-api\n    name: Box Legal Hold Policies API\n    tags:\n      - Compliance\n      - Legal Hold\n      - Policies\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-legal-hold-policies\n    properties:\n      - url: https://developer.box.com/reference/post-legal-hold-policies\n        type: Documentation\n      - url: openapi/legal-hold-policies-openapi-original.yml\n        type: OpenAPI\n\
  \    description: The Box Legal Hold Policies API enables creating and managing legal hold policies that prevent content from being modified or deleted during legal proceedings, supporting e-discovery and litigation hold requirements.\n  - aid: box:box-legal-hold-policy-assignments-api\n    name: Box Legal Hold Policy Assignments API\n    tags:\n      - Assignments\n      - Compliance\n      - Legal Hold\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-legal-hold-policy-assignments\n    properties:\n      - url: https://developer.box.com/reference/post-legal-hold-policy-assignments\n        type: Documentation\n      - url: openapi/legal-hold-policy-assignments-openapi-original.yml\n        type: OpenAPI\n    description: The Box Legal Hold Policy Assignments API manages the assignment of legal hold policies to specific users, folders, or files, controlling\
  \ which content is preserved under legal hold.\n  - aid: box:box-file-version-retentions-api\n    name: Box File Version Retentions API\n    tags:\n      - File Versions\n      - Governance\n      - Retention\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/get-file-version-retentions-id\n    properties:\n      - url: https://developer.box.com/reference/get-file-version-retentions-id\n        type: Documentation\n      - url: openapi/file-version-retentions-openapi-original.yml\n        type: OpenAPI\n    description: The Box File Version Retentions API provides information about file versions that are under retention, allowing applications to list and retrieve details about retained file versions and their associated policies.\n  - aid: box:box-file-version-legal-holds-api\n    name: Box File Version Legal Holds API\n    tags:\n      - Compliance\n      - File\
  \ Versions\n      - Legal Hold\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/get-file-version-legal-holds-id\n    properties:\n      - url: https://developer.box.com/reference/get-file-version-legal-holds-id\n        type: Documentation\n      - url: openapi/file-version-legal-holds-openapi-original.yml\n        type: OpenAPI\n    description: The Box File Version Legal Holds API provides information about file versions currently under legal hold, enabling applications to list and retrieve details about held file versions and their associated legal hold policies.\n  - aid: box:box-shield-information-barriers-api\n    name: Box Shield Information Barriers API\n    tags:\n      - Information Barriers\n      - Security\n      - Shield\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n \
  \   humanURL: https://developer.box.com/reference/post-shield-information-barriers-change-status\n    properties:\n      - url: https://developer.box.com/reference/post-shield-information-barriers-change-status\n        type: Documentation\n      - url: openapi/shield-information-barriers-openapi-original.yml\n        type: OpenAPI\n    description: The Box Shield Information Barriers API creates and manages information barriers that prevent communication and collaboration between specific groups of users within an enterprise, supporting regulatory compliance for financial services and other regulated industries.\n  - aid: box:box-shield-information-barrier-reports-api\n    name: Box Shield Information Barrier Reports API\n    tags:\n      - Reports\n      - Security\n      - Shield\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-shield-information-barrier-reports\n\
  \    properties:\n      - url: https://developer.box.com/reference/post-shield-information-barrier-reports\n        type: Documentation\n      - url: openapi/shield-information-barrier-reports-openapi-original.yml\n        type: OpenAPI\n    description: The Box Shield Information Barrier Reports API generates and retrieves reports about information barrier configurations and violations, providing visibility into barrier effectiveness and compliance status.\n  - aid: box:box-shield-information-barrier-segments-api\n    name: Box Shield Information Barrier Segments API\n    tags:\n      - Security\n      - Segments\n      - Shield\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-shield-information-barrier-segments\n    properties:\n      - url: https://developer.box.com/reference/post-shield-information-barrier-segments\n        type: Documentation\n      -\
  \ url: openapi/shield-information-barrier-segments-openapi-original.yml\n        type: OpenAPI\n    description: The Box Shield Information Barrier Segments API manages the user segments that define the boundaries of information barriers, allowing creation, retrieval, updating, and deletion of segments used in barrier policies.\n  - aid: box:box-shield-information-barrier-segment-members-api\n    name: Box Shield Information Barrier Segment Members API\n    tags:\n      - Members\n      - Security\n      - Segments\n      - Shield\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-shield-information-barrier-segment-members\n    properties:\n      - url: https://developer.box.com/reference/post-shield-information-barrier-segment-members\n        type: Documentation\n      - url: openapi/shield-information-barrier-segment-members-openapi-original.yml\n       \
  \ type: OpenAPI\n    description: The Box Shield Information Barrier Segment Members API manages the users assigned to information barrier segments, controlling which users belong to each restricted group within an information barrier configuration.\n  - aid: box:box-shield-information-barrier-segment-restrictions-api\n    name: Box Shield Information Barrier Segment Restrictions API\n    tags:\n      - Restrictions\n      - Security\n      - Shield\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-shield-information-barrier-segment-restrictions\n    properties:\n      - url: https://developer.box.com/reference/post-shield-information-barrier-segment-restrictions\n        type: Documentation\n      - url: openapi/shield-information-barrier-segment-restrictions-openapi-original.yml\n        type: OpenAPI\n    description: The Box Shield Information Barrier Segment\
  \ Restrictions API defines the restriction rules between information barrier segments, specifying which pairs of segments are prevented from collaborating with each other.\n  - aid: box:box-device-pinners-api\n    name: Box Device Pinners API\n    tags:\n      - Devices\n      - Pinning\n      - Security\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/get-device-pinners-id\n    properties:\n      - url: https://developer.box.com/reference/get-device-pinners-id\n        type: Documentation\n      - url: openapi/device-pinners-openapi-original.yml\n        type: OpenAPI\n    description: The Box Device Pinners API manages device pinning for enterprise accounts, allowing administrators to view and remove pinned devices that users have associated with their Box accounts for enhanced security.\n  - aid: box:box-enterprises-api\n    name: Box Enterprises API\n    tags:\n\
  \      - Administration\n      - Enterprises\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-users\n    properties:\n      - url: https://developer.box.com/reference/post-users\n        type: Documentation\n      - url: openapi/enterprises-openapi-original.yml\n        type: OpenAPI\n    description: The Box Enterprises API provides administrative endpoints for managing enterprise-level settings and configurations, including enterprise user management and organizational controls.\n  - aid: box:box-terms-of-services-api\n    name: Box Terms Of Services API\n    tags:\n      - Compliance\n      - Terms of Service\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-terms-of-services\n    properties:\n      - url: https://developer.box.com/reference/post-terms-of-services\n\
  \        type: Documentation\n      - url: openapi/terms-of-services-openapi-original.yml\n        type: OpenAPI\n    description: The Box Terms of Services API enables creation and management of custom terms of service agreements that users must accept before accessing content in an enterprise Box account.\n  - aid: box:box-terms-of-service-user-statuses-api\n    name: Box Terms Of Service User Statuses API\n    tags:\n      - Compliance\n      - Terms of Service\n      - Users\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-terms-of-service-user-statuses\n    properties:\n      - url: https://developer.box.com/reference/post-terms-of-service-user-statuses\n        type: Documentation\n      - url: openapi/terms-of-service-user-statuses-openapi-original.yml\n        type: OpenAPI\n    description: The Box Terms of Service User Statuses API tracks and manages\
  \ whether individual users have accepted or rejected specific terms of service agreements within the enterprise.\n  - aid: box:box-collaboration-whitelist-entries-api\n    name: Box Collaboration Whitelist Entries API\n    tags:\n      - Collaboration\n      - Domain Restrictions\n      - Security\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.box.com/2.0\n    humanURL: https://developer.box.com/reference/post-collaboration-whitelist-entries\n    properties:\n      - url: https://developer.box.com/reference/post-collaboration-whitelist-entries\n        type: Documentation\n      - url: openapi/collaboration-whitelist-entries-openapi-original.yml\n        type: OpenAPI\n    description: The Box Collaboration Whitelist Entries API manages domain restrictions for collaborations, allowing administrators to specify which external domains are allowed to collaborate with enterprise users.\n  - aid: box:box-collaboration-whitelist-exempt-targets-api\n\
  \    name: Box Collaboration Whitelist Exempt Targets API\n    tags: []\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-jso\n\n# --- truncated at 32 KB (37 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/box/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/box/refs/heads/main/apis.yml
tags:
- Cloud Storage
- Collaboration
- Content Management
- Documents
- Enterprise
- File Sharing
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/box.yml
use_cases: []
---
