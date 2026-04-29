---
api_count: 41
apis:
- description: 'GraphQL is a query language for APIs. You can use it to request the exact data you need, and therefore limit the number of requests you need. GraphQL data is arranged in types, so your client can use '
  name: GitLab GraphQL API
  slug: gitlab-graphql-api
- description: The GitLab Groups API allows you to create, read, update, and delete groups and subgroups. Groups are used to manage access control and organize projects within a GitLab instance, enabling teams to co
  name: GitLab Groups API
  slug: apiv4groups
- description: The GitLab Projects API provides programmatic access to GitLab projects, enabling you to create, list, update, and delete projects. It supports managing project settings, members, forks, stars, and ot
  name: GitLab Projects API
  slug: apiv4projects
- description: The GitLab Admin API provides administrative endpoints for managing a GitLab instance. It includes operations for managing runners, CI/CD variables, Sidekiq queues, and other instance-level administra
  name: GitLab Admin API
  slug: apiv4admin
- description: The GitLab Applications API allows you to manage OAuth applications registered in GitLab. You can create, list, and delete OAuth applications that enable third-party services to access GitLab resource
  name: GitLab Applications API
  slug: apiv4applications
- description: 'The GitLab Avatar API allows you to retrieve avatar images for users and groups. It returns avatar URLs based on user email addresses, enabling applications to display profile images for GitLab users '
  name: GitLab Avatar API
  slug: apiv4avatar
- description: The GitLab Broadcast Messages API allows administrators to create and manage broadcast messages that appear as banners across all GitLab pages. These messages are used to communicate announcements, ma
  name: GitLab Broadcast Messages API
  slug: apiv4broadcast-messages
- description: The GitLab Bulk Imports API enables migration of groups and projects between GitLab instances. It provides endpoints for initiating bulk import operations and tracking their progress, facilitating lar
  name: GitLab Bulk Imports API
  slug: apiv4bulk-imports
- description: The GitLab Application Settings API provides access to instance-wide configuration settings for a GitLab installation. Administrators can retrieve and modify application settings such as sign-up restr
  name: GitLab Application Settings API
  slug: apiv4application
- description: 'The GitLab Metadata API provides information about the GitLab instance, including the version, revision, and other metadata about the running installation. It is useful for verifying connectivity and '
  name: GitLab Metadata API
  slug: apiv4metadata
- description: The GitLab Version API returns version and revision information for the GitLab instance. This endpoint is useful for verifying what version of GitLab is running and for checking compatibility with spe
  name: GitLab Version API
  slug: apiv4version
- description: The GitLab REST API provides programmatic access to GitLab resources, enabling you to build integrations, automate repetitive tasks, and extract data for custom reports. The API supports projects, gro
  name: GitLab REST API
  slug: gitlab-rest-api
- description: 'The GitLab OAuth 2.0 API enables third-party services to access GitLab resources on behalf of users using the OAuth 2.0 protocol. It supports authorization code with PKCE, device authorization grant, '
  name: GitLab OAuth 2.0 API
  slug: gitlab-oauth2-api
- description: GitLab Webhooks allow you to receive real-time HTTP POST notifications when events occur in GitLab projects or groups. Webhooks can be configured to trigger on events such as push events, merge reques
  name: GitLab Webhooks
  slug: gitlab-webhooks
- description: The GitLab Issues API provides programmatic access to manage issues across projects and groups. It supports creating, listing, updating, and deleting issues, as well as managing issue assignments, lab
  name: GitLab Issues API
  slug: apiv4issues
- description: The GitLab Merge Requests API enables programmatic management of merge requests across projects and groups. It supports creating, listing, updating, approving, and merging merge requests, as well as m
  name: GitLab Merge Requests API
  slug: apiv4merge-requests
- description: The GitLab Pipelines API provides programmatic access to CI/CD pipelines in GitLab projects. It supports listing, creating, retrying, and canceling pipelines, as well as retrieving pipeline details an
  name: GitLab Pipelines API
  slug: apiv4pipelines
- description: 'The GitLab Jobs API allows you to interact with CI/CD jobs in GitLab projects. It supports listing, retrieving, canceling, retrying, and erasing jobs, as well as downloading job artifacts and viewing '
  name: GitLab Jobs API
  slug: apiv4jobs
- description: The GitLab Runners API provides endpoints for managing CI/CD runners registered to a GitLab instance. It supports listing, registering, updating, and deleting runners, as well as managing runner confi
  name: GitLab Runners API
  slug: apiv4runners
- description: The GitLab Users API provides programmatic access to manage user accounts on a GitLab instance. It supports listing, creating, updating, and deleting users, managing SSH keys and GPG keys, viewing use
  name: GitLab Users API
  slug: apiv4users
- description: The GitLab Repositories API provides access to Git repository data within GitLab projects. It supports listing repository tree structures, retrieving file contents, comparing branches and tags, downlo
  name: GitLab Repositories API
  slug: apiv4repositories
- description: The GitLab Commits API provides programmatic access to Git commits within GitLab projects. It supports listing, creating, and retrieving commits, viewing commit diffs and comments, cherry-picking comm
  name: GitLab Commits API
  slug: apiv4commits
- description: The GitLab Branches API enables programmatic management of Git branches within GitLab projects. It supports listing, creating, and deleting branches, as well as retrieving branch details including the
  name: GitLab Branches API
  slug: apiv4branches
- description: The GitLab Tags API provides programmatic access to manage Git tags within GitLab projects. It supports listing, creating, and deleting tags, as well as retrieving tag details for version management a
  name: GitLab Tags API
  slug: apiv4tags
- description: The GitLab Releases API enables programmatic management of project releases. It supports creating, listing, updating, and deleting releases, as well as managing release assets and links for distributi
  name: GitLab Releases API
  slug: apiv4releases
- description: 'The GitLab Environments API provides programmatic access to manage deployment environments within GitLab projects. It supports creating, listing, updating, stopping, and deleting environments used to '
  name: GitLab Environments API
  slug: apiv4environments
- description: The GitLab Deployments API enables programmatic access to deployment records in GitLab projects. It supports listing, creating, and updating deployments, as well as retrieving deployment details and m
  name: GitLab Deployments API
  slug: apiv4deployments
- description: The GitLab Pipeline Schedules API provides programmatic access to manage scheduled CI/CD pipelines. It supports creating, listing, updating, and deleting pipeline schedules, as well as managing schedu
  name: GitLab Pipeline Schedules API
  slug: apiv4pipeline-schedules
- description: 'The GitLab Labels API provides programmatic access to manage project labels. It supports creating, listing, updating, deleting, and subscribing to labels used for categorizing issues, merge requests, '
  name: GitLab Labels API
  slug: apiv4labels
- description: The GitLab Milestones API provides programmatic access to manage project milestones. It supports creating, listing, updating, and deleting milestones, as well as retrieving issues and merge requests a
  name: GitLab Milestones API
  slug: apiv4milestones
- description: The GitLab Notes API provides programmatic access to manage comments and system notes on issues, merge requests, epics, and snippets. It supports creating, listing, updating, and deleting notes for co
  name: GitLab Notes API
  slug: apiv4notes
- description: The GitLab Snippets API provides programmatic access to manage code snippets. It supports creating, listing, updating, and deleting both personal and project snippets, enabling sharing of code fragmen
  name: GitLab Snippets API
  slug: apiv4snippets
- description: The GitLab Packages API provides programmatic access to the GitLab Package Registry. It supports listing, retrieving, and deleting packages across projects and groups, with support for multiple packag
  name: GitLab Packages API
  slug: apiv4packages
- description: The GitLab Container Registry API provides programmatic access to manage container images stored in the GitLab Container Registry. It supports listing repositories and tags, deleting images, and manag
  name: GitLab Container Registry API
  slug: apiv4container-registry
- description: The GitLab Vulnerabilities API provides programmatic access to manage security vulnerabilities detected in GitLab projects. It supports retrieving, confirming, resolving, and dismissing vulnerabilitie
  name: GitLab Vulnerabilities API
  slug: apiv4vulnerabilities
- description: The GitLab Deploy Keys API provides programmatic access to manage deploy keys for GitLab projects. It supports listing, creating, updating, and deleting SSH deploy keys that grant read-only or read-wr
  name: GitLab Deploy Keys API
  slug: apiv4deploy-keys
- description: The GitLab Protected Branches API provides programmatic access to manage branch protection rules. It supports listing, creating, updating, and removing protection settings that control who can push, m
  name: GitLab Protected Branches API
  slug: apiv4protected-branches
- description: The GitLab Wikis API provides programmatic access to manage project wiki pages. It supports listing, creating, updating, and deleting wiki pages, as well as uploading attachments, enabling teams to ma
  name: GitLab Wikis API
  slug: apiv4wikis
- description: The GitLab Events API provides programmatic access to review event activity across GitLab. It supports listing all events, retrieving user contribution events, and viewing project-specific events such
  name: GitLab Events API
  slug: apiv4events
- description: 'The GitLab Search API enables programmatic search across a GitLab instance, group, or project. It supports searching for projects, issues, merge requests, milestones, code blobs, commits, notes, wiki '
  name: GitLab Search API
  slug: apiv4search
- description: The GitLab Namespaces API provides programmatic access to manage namespaces in GitLab. It supports listing namespaces, retrieving namespace details, and verifying namespace existence, which is essenti
  name: GitLab Namespaces API
  slug: apiv4namespaces
asyncapis:
- description: GitLab Webhooks deliver HTTP POST payloads to a configured URL whenever specified events occur in a GitLab project or group, such as pushes, merge requests, issues, pipeline status changes, and deploy
  name: GitLab Webhooks
  slug: gitlab-webhooks-asyncapi
capabilities:
- description: Unified capability for GitLab OAuth 2.0 authentication flows and user identity. Enables developers and platform administrators to manage OAuth application authorization, token lifecycle, and authentic
  name: GitLab Authentication And Identity
  slug: authentication-and-identity
- description: Unified capability for managing GitLab project webhooks, including CRUD operations, custom header and URL variable configuration, delivery event history, and testing. Used by DevOps engineers and plat
  name: GitLab Webhook Management
  slug: webhook-management
common:
- title: ''
  type: Website
  url: https://about.gitlab.com/
- title: ''
  type: Portal
  url: https://docs.gitlab.com/api/
- title: ''
  type: Documentation
  url: https://docs.gitlab.com/
- title: ''
  type: Authentication
  url: https://docs.gitlab.com/api/rest/authentication/
- title: ''
  type: GitHubOrganization
  url: https://github.com/gitlabhq
- title: ''
  type: Blog
  url: https://about.gitlab.com/blog/
- title: ''
  type: StatusPage
  url: https://status.gitlab.com/
- title: ''
  type: Pricing
  url: https://about.gitlab.com/pricing/
- title: ''
  type: TermsOfService
  url: https://about.gitlab.com/terms/
- title: ''
  type: PrivacyPolicy
  url: https://about.gitlab.com/privacy/
- title: ''
  type: Support
  url: https://about.gitlab.com/company/contact/
- title: ''
  type: IDESupport
  url: https://docs.gitlab.com/ee/editor_extensions/
- title: ''
  type: ReleaseNotes
  url: https://about.gitlab.com/releases/categories/releases/
- title: ''
  type: Portal
  url: https://developer.gitlab.com/
- title: ''
  type: Documentation
  url: https://docs.gitlab.com/
- title: ''
  type: GettingStarted
  url: https://about.gitlab.com/get-started/
- title: ''
  type: StatusPage
  url: https://status.gitlab.com/
- title: ''
  type: SignUp
  url: https://gitlab.com/users/sign_up
- title: ''
  type: Blog
  url: https://about.gitlab.com/blog/
- title: ''
  type: Support
  url: https://about.gitlab.com/support/
- title: ''
  type: ChangeLog
  url: https://gitlab.com/gitlab-org/gitlab/blob/master/CHANGELOG.md
- title: ''
  type: Authentication
  url: https://docs.gitlab.com/api/rest/authentication/
- title: ''
  type: SDK
  url: https://docs.gitlab.com/api/rest/third_party_clients/
- title: ''
  type: Support
  url: https://forum.gitlab.com/
- title: ''
  type: RateLimits
  url: https://docs.gitlab.com/security/rate_limits/
- title: ''
  type: JSONLD
  url: json-ld/gitlab-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/gitlab-project-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/gitlab-merge-request-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/gitlab-issue-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/gitlab-pipeline-schema.json
- title: ''
  type: Pricing
  url: https://about.gitlab.com/pricing/
- title: ''
  type: Security
  url: https://about.gitlab.com/security/
- title: ''
  type: Security
  url: https://about.gitlab.com/security/disclosure/
- title: ''
  type: Documentation
  url: https://about.gitlab.com/direction/
- title: ''
  type: Partners
  url: https://about.gitlab.com/partners/technology-partners/
- title: ''
  type: Documentation
  url: https://about.gitlab.com/solutions/open-source/
- title: ''
  type: Marketplace
  url: https://marketplace.gitlab.com/
- title: ''
  type: Tools
  url: https://docs.gitlab.com/api/openapi/openapi_interactive/
- title: ''
  type: GitHubRepository
  url: https://gitlab.com/gitlab-org/gitlab
created: 2023/11/10
description: GitLab Inc. is an open-core company that develops GitLab, a DevOps software platform for building, securing, and managing applications. Created by Ukrainian developer Dmytro Zaporozhets and Dutch developer Sytse Sijbrandij, GitLab became the first partly-Ukrainian unicorn in 2018. Known for promoting remote work, it is one of the largest all-remote companies globally. GitLab has approximately 30 million registered users, including 1 million active licensed users.
features:
- description: Comprehensive REST API for managing projects, groups, users, issues, merge requests, pipelines, and all GitLab resources.
  name: REST API v4
- description: Flexible query language API for requesting exactly the data you need with a versionless, non-breaking schema.
  name: GraphQL API
- description: Programmatically manage pipelines, jobs, runners, and deployment workflows.
  name: CI/CD Pipelines
- description: Manage container images and repositories for Docker image lifecycle management.
  name: Container Registry
- description: Publish and manage packages across npm, Maven, PyPI, NuGet, Conan, and other formats.
  name: Package Registry
- description: Receive real-time notifications for events across projects, groups, and system-level actions.
  name: Webhooks
- description: Standards-based OAuth 2.0 and OpenID Connect authentication for third-party applications.
  name: OAuth 2.0 Authentication
- description: Access SAST, DAST, dependency scanning, and container scanning results through APIs.
  name: Security Scanning
- description: Full lifecycle management of merge requests including creation, review, approval, and merge.
  name: Merge Request Management
- description: Create, manage, and query issues with labels, milestones, weights, and custom fields.
  name: Issue Tracking
- description: Manage repository files, branches, tags, commits, and merge operations.
  name: Repository Management
- description: Create and configure groups, subgroups, and projects with membership and permissions.
  name: Group and Project Management
image: /assets/icons/gitlab.png
integrations: []
jsonld:
- class_count: 38
  name: Gitlab Context
  property_count: 268
  slug: gitlab-context
layout: provider
modified: '2026-04-17'
name: GitLab
rules:
- name: GitLab API Rules
  rule_count: 24
  severity_counts:
    error: 15
    hint: 0
    info: 3
    warn: 6
  slug: gitlab-spectral-rules
skills: []
slug: gitlab
solutions:
- description: Core DevOps platform with unlimited repositories, CI/CD, issue tracking, and API access.
  name: GitLab Free
- description: Advanced DevOps with merge request approvals, code owners, and priority support.
  name: GitLab Premium
- description: Enterprise DevOps with security scanning, compliance, and advanced API features.
  name: GitLab Ultimate
- description: Single-tenant SaaS deployment with dedicated infrastructure and enhanced security.
  name: GitLab Dedicated
source_yaml: "aid: gitlab\nurl: https://raw.githubusercontent.com/api-search/code/main/_apis/gitlab/apis.md\napis:\n  - aid: gitlab:gitlab-graphql-api\n    name: GitLab GraphQL API\n    tags:\n      - Data\n      - GraphQL\n      - Query Language\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/graphql\n    humanURL: https://docs.gitlab.com/ee/api/graphql/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/ee/api/graphql/\n        type: Documentation\n      - url: >-\n          https://docs.gitlab.com/ee/api/graphql/#deprecation-and-removal-process\n        type: Deprecation\n      - url: >-\n          https://docs.gitlab.com/ee/api/graphql/#deprecation-and-removal-process\n        type: Documentation\n      - url: https://docs.gitlab.com/ee/api/graphql/#limits\n        type: RateLimits\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n      - url:\
  \ https://docs.gitlab.com/api/graphql/reference/\n        type: APIReference\n      - url: https://docs.gitlab.com/api/graphql/getting_started/\n        type: GettingStarted\n    description: >-\n      GraphQL is a query language for APIs. You can use it to request the exact data\n      you need, and therefore limit the number of requests you need. GraphQL data\n      is arranged in types, so your client can use client-side GraphQL libraries to\n      consume the API and avoid manual parsing. There are no fixed endpoints and no\n      data model, so you can add to the API without creating breaking changes. This\n      enables us to have a versionless API.\n  - aid: gitlab:apiv4groups\n    name: GitLab Groups API\n    tags:\n      - Access Control\n      - Groups\n      - Organizations\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/groups/\n    overlays:\n      - url:\
  \ overlays/gitlab-api-v4-groups-openapi-search.yml\n        type: OpenAPI\n    properties:\n      - url: openapi/gitlab-api-v4-groups-openapi-original.yml\n        type: OpenAPI\n      - url: https://docs.gitlab.com/api/groups/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Groups API allows you to create, read, update, and delete\n      groups and subgroups. Groups are used to manage access control and organize\n      projects within a GitLab instance, enabling teams to collaborate with\n      shared access permissions and settings.\n  - aid: gitlab:apiv4projects\n    name: GitLab Projects API\n    tags:\n      - Projects\n      - Repositories\n      - Source Control\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/projects/\n    overlays:\n      - url:\
  \ overlays/gitlab-api-v4-projects-openapi-search.yml\n        type: OpenAPI\n    properties:\n      - url: openapi/gitlab-api-v4-projects-openapi-original.yml\n        type: OpenAPI\n      - url: https://docs.gitlab.com/api/projects/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Projects API provides programmatic access to GitLab projects,\n      enabling you to create, list, update, and delete projects. It supports\n      managing project settings, members, forks, stars, and other project-level\n      resources across GitLab.com and self-managed instances.\n  - aid: gitlab:apiv4admin\n    name: GitLab Admin API\n    tags:\n      - Admin\n      - Administration\n      - Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/admin/\n    overlays:\n \
  \     - url: overlays/gitlab-api-v4-admin-openapi-search.yml\n        type: OpenAPI\n    properties:\n      - url: openapi/gitlab-api-v4-admin-openapi-original.yml\n        type: OpenAPI\n      - url: https://docs.gitlab.com/api/admin/\n        type: Documentation\n    description: >-\n      The GitLab Admin API provides administrative endpoints for managing a\n      GitLab instance. It includes operations for managing runners, CI/CD\n      variables, Sidekiq queues, and other instance-level administrative tasks\n      that require administrator privileges.\n  - aid: gitlab:apiv4applications\n    name: GitLab Applications API\n    tags:\n      - Applications\n      - Authentication\n      - OAuth\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/applications/\n    overlays:\n      - url: overlays/gitlab-api-v4-applications-openapi-search.yml\n        type: OpenAPI\n \
  \   properties:\n      - url: openapi/gitlab-api-v4-applications-openapi-original.yml\n        type: OpenAPI\n      - url: https://docs.gitlab.com/api/applications/\n        type: Documentation\n    description: >-\n      The GitLab Applications API allows you to manage OAuth applications\n      registered in GitLab. You can create, list, and delete OAuth applications\n      that enable third-party services to access GitLab resources on behalf of\n      users using the OAuth 2.0 protocol.\n  - aid: gitlab:apiv4avatar\n    name: GitLab Avatar API\n    tags:\n      - Avatars\n      - Profile\n      - Users\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/avatar/\n    overlays:\n      - url: overlays/gitlab-api-v4-avatar-openapi-search.yml\n        type: OpenAPI\n    properties:\n      - url: openapi/gitlab-api-v4-avatar-openapi-original.yml\n        type: OpenAPI\n   \
  \   - url: https://docs.gitlab.com/api/avatar/\n        type: Documentation\n    description: >-\n      The GitLab Avatar API allows you to retrieve avatar images for users and\n      groups. It returns avatar URLs based on user email addresses, enabling\n      applications to display profile images for GitLab users without requiring\n      authentication.\n  - aid: gitlab:apiv4broadcast-messages\n    name: GitLab Broadcast Messages API\n    tags:\n      - Administration\n      - Broadcast Messages\n      - Notifications\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/broadcast_messages/\n    overlays:\n      - url: overlays/gitlab-api-v4-broadcast-messages-openapi-search.yml\n        type: OpenAPI\n    properties:\n      - url: openapi/gitlab-api-v4-broadcast-messages-openapi-original.yml\n        type: OpenAPI\n      - url: https://docs.gitlab.com/api/broadcast_messages/\n\
  \        type: Documentation\n    description: >-\n      The GitLab Broadcast Messages API allows administrators to create and\n      manage broadcast messages that appear as banners across all GitLab pages.\n      These messages are used to communicate announcements, maintenance notices,\n      and other important information to all users of a GitLab instance.\n  - aid: gitlab:apiv4bulk-imports\n    name: GitLab Bulk Imports API\n    tags:\n      - Bulk Imports\n      - Data Transfer\n      - Migration\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/bulk_imports/\n    overlays:\n      - url: overlays/gitlab-api-v4-bulk-imports-openapi-search.yml\n        type: OpenAPI\n    properties:\n      - url: openapi/gitlab-api-v4-bulk-imports-openapi-original.yml\n        type: OpenAPI\n      - url: https://docs.gitlab.com/api/bulk_imports/\n        type: Documentation\n   \
  \ description: >-\n      The GitLab Bulk Imports API enables migration of groups and projects\n      between GitLab instances. It provides endpoints for initiating bulk import\n      operations and tracking their progress, facilitating large-scale data\n      migrations between GitLab environments.\n  - aid: gitlab:apiv4application\n    name: GitLab Application Settings API\n    tags:\n      - Administration\n      - Application Settings\n      - Configuration\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/settings/\n    overlays:\n      - url: overlays/gitlab-api-v4-application-openapi-search.yml\n        type: OpenAPI\n    properties:\n      - url: openapi/gitlab-api-v4-application-openapi-original.yml\n        type: OpenAPI\n      - url: https://docs.gitlab.com/api/settings/\n        type: Documentation\n    description: >-\n      The GitLab Application Settings\
  \ API provides access to instance-wide\n      configuration settings for a GitLab installation. Administrators can\n      retrieve and modify application settings such as sign-up restrictions,\n      default project visibility, and other instance-level preferences.\n  - aid: gitlab:apiv4metadata\n    name: GitLab Metadata API\n    tags:\n      - Instance Information\n      - Metadata\n      - System\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/metadata/\n    overlays:\n      - url: overlays/gitlab-api-v4-metadata-openapi-search.yml\n        type: OpenAPI\n    properties:\n      - url: openapi/gitlab-api-v4-metadata-openapi-original.yml\n        type: OpenAPI\n      - url: https://docs.gitlab.com/api/metadata/\n        type: Documentation\n    description: >-\n      The GitLab Metadata API provides information about the GitLab instance,\n      including the version,\
  \ revision, and other metadata about the running\n      installation. It is useful for verifying connectivity and identifying the\n      version of a GitLab instance programmatically.\n  - aid: gitlab:apiv4version\n    name: GitLab Version API\n    tags:\n      - Instance Information\n      - System\n      - Version\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/version/\n    overlays:\n      - url: overlays/gitlab-api-v4-version-openapi-search.yml\n        type: OpenAPI\n    properties:\n      - url: openapi/gitlab-api-v4-version-openapi-original.yml\n        type: OpenAPI\n      - url: https://docs.gitlab.com/api/version/\n        type: Documentation\n    description: >-\n      The GitLab Version API returns version and revision information for the\n      GitLab instance. This endpoint is useful for verifying what version of\n      GitLab is running and for checking\
  \ compatibility with specific API\n      features before making requests.\n  - aid: gitlab:gitlab-rest-api\n    name: GitLab REST API\n    tags:\n      - DevOps\n      - Integration\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/rest/\n    overlays: []\n    properties:\n      - url: openapi/gitlab-openapi-original.yml\n        type: OpenAPI\n      - url: https://docs.gitlab.com/api/rest/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n      - url: https://docs.gitlab.com/api/rest/third_party_clients/\n        type: SDK\n      - url: https://docs.gitlab.com/api/api_resources/\n        type: APIReference\n      - url: https://docs.gitlab.com/security/rate_limits/\n        type: RateLimits\n      - url: https://docs.gitlab.com/api/openapi/openapi_interactive/\n        type: Interactive\
  \ Documentation\n    description: >-\n      The GitLab REST API provides programmatic access to GitLab resources,\n      enabling you to build integrations, automate repetitive tasks, and extract\n      data for custom reports. The API supports projects, groups, issues, merge\n      requests, CI/CD pipelines, and many other GitLab features through standard\n      HTTP methods and JSON responses.\n  - aid: gitlab:gitlab-oauth2-api\n    name: GitLab OAuth 2.0 API\n    tags:\n      - Authentication\n      - Authorization\n      - OAuth\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com\n    humanURL: https://docs.gitlab.com/api/oauth2/\n    overlays: []\n    properties:\n      - url: openapi/gitlab-oauth2-openapi.yml\n        type: OpenAPI\n      - url: https://docs.gitlab.com/api/oauth2/\n        type: Documentation\n      - url: https://docs.gitlab.com/integration/oauth_provider/\n        type: Authentication\n    description:\
  \ >-\n      The GitLab OAuth 2.0 API enables third-party services to access GitLab\n      resources on behalf of users using the OAuth 2.0 protocol. It supports\n      authorization code with PKCE, device authorization grant, and resource\n      owner password credentials flows, allowing secure delegation of access to\n      GitLab resources.\n  - aid: gitlab:gitlab-webhooks\n    name: GitLab Webhooks\n    tags:\n      - Events\n      - Integrations\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/user/project/integrations/webhooks.html\n    overlays: []\n    properties:\n      - url: openapi/gitlab-webhooks-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/gitlab-webhooks-asyncapi.yml\n        type: AsyncAPI\n      - url: https://docs.gitlab.com/user/project/integrations/webhooks.html\n        type: Documentation\n      - url: https://docs.gitlab.com/api/project_webhooks/\n\
  \        type: APIReference\n    description: >-\n      GitLab Webhooks allow you to receive real-time HTTP POST notifications\n      when events occur in GitLab projects or groups. Webhooks can be configured\n      to trigger on events such as push events, merge requests, issues, comments,\n      and pipeline status changes, enabling integrations with external systems.\n  - aid: gitlab:apiv4issues\n    name: GitLab Issues API\n    tags:\n      - Bug Tracking\n      - Issues\n      - Project Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/issues/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/issues/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Issues API provides programmatic access to manage issues across\n  \
  \    projects and groups. It supports creating, listing, updating, and deleting\n      issues, as well as managing issue assignments, labels, milestones, and\n      related metadata for tracking work in GitLab.\n  - aid: gitlab:apiv4merge-requests\n    name: GitLab Merge Requests API\n    tags:\n      - Code Review\n      - Collaboration\n      - Merge Requests\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/merge_requests/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/merge_requests/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Merge Requests API enables programmatic management of merge\n      requests across projects and groups. It supports creating, listing,\n      updating, approving, and merging merge requests, as well\
  \ as managing\n      reviewers, assignees, and merge request metadata for code review workflows.\n  - aid: gitlab:apiv4pipelines\n    name: GitLab Pipelines API\n    tags:\n      - CI/CD\n      - Continuous Integration\n      - Pipelines\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/pipelines/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/pipelines/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Pipelines API provides programmatic access to CI/CD pipelines\n      in GitLab projects. It supports listing, creating, retrying, and canceling\n      pipelines, as well as retrieving pipeline details and variables for\n      automating continuous integration and delivery workflows.\n  - aid: gitlab:apiv4jobs\n    name: GitLab Jobs\
  \ API\n    tags:\n      - Build\n      - CI/CD\n      - Jobs\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/jobs/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/jobs/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Jobs API allows you to interact with CI/CD jobs in GitLab\n      projects. It supports listing, retrieving, canceling, retrying, and\n      erasing jobs, as well as downloading job artifacts and viewing job logs\n      for build and deployment automation.\n  - aid: gitlab:apiv4runners\n    name: GitLab Runners API\n    tags:\n      - CI/CD\n      - Infrastructure\n      - Runners\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL:\
  \ https://docs.gitlab.com/api/runners/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/runners/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Runners API provides endpoints for managing CI/CD runners\n      registered to a GitLab instance. It supports listing, registering,\n      updating, and deleting runners, as well as managing runner configurations\n      and viewing jobs assigned to specific runners.\n  - aid: gitlab:apiv4users\n    name: GitLab Users API\n    tags:\n      - Access Management\n      - Identity\n      - Users\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/users/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/users/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n\
  \        type: Authentication\n    description: >-\n      The GitLab Users API provides programmatic access to manage user accounts\n      on a GitLab instance. It supports listing, creating, updating, and\n      deleting users, managing SSH keys and GPG keys, viewing user activity, and\n      administering user-level settings and permissions.\n  - aid: gitlab:apiv4repositories\n    name: GitLab Repositories API\n    tags:\n      - Git\n      - Repositories\n      - Source Control\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/repositories/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/repositories/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Repositories API provides access to Git repository data within\n      GitLab projects.\
  \ It supports listing repository tree structures, retrieving\n      file contents, comparing branches and tags, downloading archives, and\n      accessing contributor statistics.\n  - aid: gitlab:apiv4commits\n    name: GitLab Commits API\n    tags:\n      - Commits\n      - Git\n      - Source Control\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/commits/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/commits/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Commits API provides programmatic access to Git commits within\n      GitLab projects. It supports listing, creating, and retrieving commits,\n      viewing commit diffs and comments, cherry-picking commits, and accessing\n      commit status information for CI/CD integration.\n\
  \  - aid: gitlab:apiv4branches\n    name: GitLab Branches API\n    tags:\n      - Branches\n      - Git\n      - Source Control\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/branches/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/branches/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Branches API enables programmatic management of Git branches\n      within GitLab projects. It supports listing, creating, and deleting\n      branches, as well as retrieving branch details including the latest commit\n      and protection status.\n  - aid: gitlab:apiv4tags\n    name: GitLab Tags API\n    tags:\n      - Git\n      - Source Control\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL:\
  \ https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/tags/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/tags/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Tags API provides programmatic access to manage Git tags within\n      GitLab projects. It supports listing, creating, and deleting tags, as well\n      as retrieving tag details for version management and release workflows.\n  - aid: gitlab:apiv4releases\n    name: GitLab Releases API\n    tags:\n      - Distribution\n      - Releases\n      - Versioning\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/releases/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/releases/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n\
  \        type: Authentication\n    description: >-\n      The GitLab Releases API enables programmatic management of project\n      releases. It supports creating, listing, updating, and deleting releases,\n      as well as managing release assets and links for distributing software\n      versions and release notes.\n  - aid: gitlab:apiv4environments\n    name: GitLab Environments API\n    tags:\n      - CI/CD\n      - Deployments\n      - Environments\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/environments/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/environments/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Environments API provides programmatic access to manage\n      deployment environments within GitLab projects.\
  \ It supports creating,\n      listing, updating, stopping, and deleting environments used to track\n      deployments across different stages such as staging and production.\n  - aid: gitlab:apiv4deployments\n    name: GitLab Deployments API\n    tags:\n      - CI/CD\n      - Deployments\n      - Release Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/deployments/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/deployments/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Deployments API enables programmatic access to deployment\n      records in GitLab projects. It supports listing, creating, and updating\n      deployments, as well as retrieving deployment details and merge requests\n      associated with specific\
  \ deployments.\n  - aid: gitlab:apiv4pipeline-schedules\n    name: GitLab Pipeline Schedules API\n    tags:\n      - Automation\n      - CI/CD\n      - Pipeline Schedules\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/pipeline_schedules/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/pipeline_schedules/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Pipeline Schedules API provides programmatic access to manage\n      scheduled CI/CD pipelines. It supports creating, listing, updating, and\n      deleting pipeline schedules, as well as managing schedule variables and\n      triggering scheduled pipeline runs.\n  - aid: gitlab:apiv4labels\n    name: GitLab Labels API\n    tags:\n      - Labels\n      - Organization\n      - Project\
  \ Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/labels/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/labels/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Labels API provides programmatic access to manage project\n      labels. It supports creating, listing, updating, deleting, and subscribing\n      to labels used for categorizing issues, merge requests, and other project\n      resources.\n  - aid: gitlab:apiv4milestones\n    name: GitLab Milestones API\n    tags:\n      - Milestones\n      - Planning\n      - Project Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/milestones/\n\
  \    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/milestones/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Milestones API provides programmatic access to manage project\n      milestones. It supports creating, listing, updating, and deleting\n      milestones, as well as retrieving issues and merge requests associated\n      with specific milestones for sprint and release planning.\n  - aid: gitlab:apiv4notes\n    name: GitLab Notes API\n    tags:\n      - Collaboration\n      - Comments\n      - Notes\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/notes/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/notes/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n\
  \        type: Authentication\n    description: >-\n      The GitLab Notes API provides programmatic access to manage comments and\n      system notes on issues, merge requests, epics, and snippets. It supports\n      creating, listing, updating, and deleting notes for collaboration and\n      discussion within GitLab resources.\n  - aid: gitlab:apiv4snippets\n    name: GitLab Snippets API\n    tags:\n      - Code Sharing\n      - Collaboration\n      - Snippets\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/snippets/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/snippets/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Snippets API provides programmatic access to manage code\n      snippets. It supports creating, listing,\
  \ updating, and deleting both\n      personal and project snippets, enabling sharing of code fragments and\n      configuration examples across teams and projects.\n  - aid: gitlab:apiv4packages\n    name: GitLab Packages API\n    tags:\n      - Artifacts\n      - Package Registry\n      - Packages\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/packages/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/packages/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Packages API provides programmatic access to the GitLab Package\n      Registry. It supports listing, retrieving, and deleting packages across\n      projects and groups, with support for multiple package formats including\n      NPM, Maven, PyPI, NuGet, Conan, Helm, and\
  \ more.\n  - aid: gitlab:apiv4container-registry\n    name: GitLab Container Registry API\n    tags:\n      - Container Registry\n      - Containers\n      - Docker\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/container_registry/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/container_registry/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Container Registry API provides programmatic access to manage\n      container images stored in the GitLab Container Registry. It supports\n      listing repositories and tags, deleting images, and managing registry\n      visibility settings for containerized application deployments.\n  - aid: gitlab:apiv4vulnerabilities\n    name: GitLab Vulnerabilities API\n    tags:\n      - DevSecOps\n\
  \      - Security\n      - Vulnerabilities\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/vulnerabilities/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/vulnerabilities/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Vulnerabilities API provides programmatic access to manage\n      security vulnerabilities detected in GitLab projects. It supports\n      retrieving, confirming, resolving, and dismissing vulnerabilities found\n      by SAST, DAST, container scanning, and dependency scanning tools.\n  - aid: gitlab:apiv4deploy-keys\n    name: GitLab Deploy Keys API\n    tags:\n      - Deploy Keys\n      - Security\n      - SSH\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL:\
  \ https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/deploy_keys/\n    overlays: []\n    properties:\n      - url: https://docs.gitlab.com/api/deploy_keys/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Deploy Keys API provides programmatic access to manage deploy\n      keys for GitLab projects. It supports listing, creating, updating, and\n      deleting SSH deploy keys that grant read-only or read-write access to\n      repositories for automated deployment workflows.\n  - aid: gitlab:apiv4protected-branches\n    name: GitLab Protected Branches API\n    tags:\n      - Access Control\n      - Protected Branches\n      - Source Control\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gitlab.com/api/v4\n    humanURL: https://docs.gitlab.com/api/protected_branches/\n    overlays: []\n    properties:\n\
  \      - url: https://docs.gitlab.com/api/protected_branches/\n        type: Documentation\n      - url: https://docs.gitlab.com/api/rest/authentication/\n        type: Authentication\n    description: >-\n      The GitLab Protected Branches API provides programmatic access to manage\n      branch protection rules. It supports listing, creating, updating, and\n      removing protection settings that control who can push, merg\n\n# --- truncated at 32 KB (41 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/apis.yml
tags:
- Code
- Platform
- Software Development
- Source Control
url: https://raw.githubusercontent.com/api-search/code/main/_apis/gitlab/apis.md
use_cases:
- description: Automate CI/CD pipeline creation, runner management, and deployment workflows.
  name: DevOps Automation
- description: Programmatically manage issues, milestones, boards, and merge requests.
  name: Project Management
- description: Manage GitLab configuration, groups, projects, and settings through APIs.
  name: Infrastructure as Code
- description: Access vulnerability reports, security scan results, and compliance data.
  name: Security and Compliance
- description: Bulk import projects, users, and data from other platforms.
  name: Migration and Integration
- description: Build custom developer tools, dashboards, and bots for GitLab workflows.
  name: Custom Tooling
- description: Manage Docker images, Kubernetes clusters, and container deployments.
  name: Container Management
- description: Extract project analytics, contribution data, and productivity metrics.
  name: Analytics and Reporting
---
