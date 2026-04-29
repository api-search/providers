---
api_count: 3
apis:
- description: The Ansible Galaxy v1 and v2 REST API enables searching, discovering, and downloading Ansible roles contributed by the community. Supports searching roles by keyword, author, or tag; retrieving role d
  name: Ansible Galaxy Roles API
  slug: ''
- description: The Ansible Galaxy v3 API provides enhanced support for Ansible collections — the modern packaging format that bundles roles, modules, plugins, and documentation together. Supports listing, searching,
  name: Ansible Galaxy Collections API
  slug: ''
- description: The Red Hat Ansible Automation Hub provides certified and partner-validated Ansible collections and roles for enterprise use. The API enables access to Red Hat-certified content with SLA-backed qualit
  name: Ansible Automation Hub Roles API
  slug: ''
common:
- title: ''
  type: GettingStarted
  url: https://docs.ansible.com/ansible/latest/galaxy/user_guide.html
- title: ''
  type: Authentication
  url: https://galaxy.ansible.com/docs/authentication/
- title: ''
  type: TermsOfService
  url: https://www.redhat.com/en/about/terms-use
- title: ''
  type: PrivacyPolicy
  url: https://www.redhat.com/en/about/privacy-policy
- title: ''
  type: GitHubRepository
  url: https://github.com/ansible/galaxy
- title: ''
  type: GitHubOrganization
  url: https://github.com/ansible
- title: Role Schema
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/json-schema/ansible-roles-role-schema.json
- title: Collection Schema
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/json-schema/ansible-roles-collection-schema.json
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/vocabulary/ansible-roles-vocabulary.yaml
created: '2024-01-01'
description: A curated collection of APIs and resources for discovering, managing, and consuming Ansible roles — the primary unit of reusable automation content in the Ansible ecosystem. Covers the Galaxy and Automation Hub APIs for role discovery, download, and publishing, as well as the Ansible Collections framework that has extended the role model into full-featured content packages.
features:
- description: Search Galaxy for community-contributed roles by keyword, author, namespace, or tag to find reusable automation content.
  name: Role Search and Discovery
- description: Bundle roles, modules, plugins, and documentation into distributable collection packages versioned and published via the Galaxy API.
  name: Collection Packaging
- description: Access specific versions of roles and collections, enabling pinned dependency management in Ansible projects.
  name: Version Management
- description: Access Red Hat-certified and partner-validated Ansible collections with enterprise-grade quality assurance via Automation Hub.
  name: Certified Content
- description: Manage author namespaces on Galaxy to publish and maintain role and collection content under a consistent identity.
  name: Namespace Management
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Use roles discovered via the Galaxy API directly in Ansible playbooks with the roles directive or include_role task.
  name: Ansible Playbooks
- description: Synchronize collections from Galaxy or Automation Hub into Ansible Automation Platform for use in job templates.
  name: Ansible Automation Platform
- description: Define role and collection dependencies in requirements.yml and install them automatically via ansible-galaxy CLI using the API.
  name: Requirements Files
jsonld:
- class_count: 4
  name: Ansible Roles Context
  property_count: 16
  slug: ansible-roles-context
layout: provider
modified: '2026-04-19'
name: Ansible Roles
skills: []
slug: ansible-roles
solutions: []
source_filename: apis.yml
source_yaml: "name: Ansible Roles\ndescription: >-\n  A curated collection of APIs and resources for discovering, managing, and\n  consuming Ansible roles — the primary unit of reusable automation content in\n  the Ansible ecosystem. Covers the Galaxy and Automation Hub APIs for role\n  discovery, download, and publishing, as well as the Ansible Collections\n  framework that has extended the role model into full-featured content packages.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncreated: \"2024-01-01\"\nmodified: \"2026-04-19\"\nspecificationVersion: '0.16'\nurl: https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/apis.yml\ntags:\n  - Ansible\n  - Automation\n  - Collections\n  - Configuration Management\n  - DevOps\n  - Infrastructure As Code\n  - Roles\napis:\n  - name: Ansible Galaxy Roles API\n    description: >-\n      The Ansible Galaxy v1 and v2 REST API enables searching, discovering, and\n      downloading Ansible\
  \ roles contributed by the community. Supports searching\n      roles by keyword, author, or tag; retrieving role details and version\n      history; and downloading specific role versions for use in playbooks.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://galaxy.ansible.com\n    baseURL: https://galaxy.ansible.com/api/v1/\n    tags:\n      - Ansible\n      - Community\n      - Galaxy\n      - Roles\n    properties:\n      - type: Documentation\n        url: https://galaxy.ansible.com/docs/\n      - type: APIReference\n        url: https://galaxy.ansible.com/api/v1/\n      - type: GettingStarted\n        url: https://docs.ansible.com/ansible/latest/galaxy/user_guide.html\n    contact:\n      - FN: Ansible Galaxy Team\n        url: https://github.com/ansible/galaxy/issues\n\n  - name: Ansible Galaxy Collections API\n    description: >-\n      The Ansible Galaxy v3 API provides enhanced support for Ansible\n      collections\
  \ — the modern packaging format that bundles roles, modules,\n      plugins, and documentation together. Supports listing, searching,\n      downloading, and versioning of published collections from the community\n      namespace on Galaxy.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://galaxy.ansible.com\n    baseURL: https://galaxy.ansible.com/api/v3/\n    tags:\n      - Ansible\n      - Collections\n      - Community\n      - Galaxy\n    properties:\n      - type: Documentation\n        url: https://galaxy.ansible.com/docs/\n      - type: APIReference\n        url: https://galaxy.ansible.com/api/v3/\n      - type: GettingStarted\n        url: https://docs.ansible.com/ansible/latest/collections/index.html\n    contact:\n      - FN: Ansible Galaxy Team\n        url: https://github.com/ansible/galaxy/issues\n\n  - name: Ansible Automation Hub Roles API\n    description: >-\n      The Red Hat Ansible Automation Hub provides\
  \ certified and partner-validated\n      Ansible collections and roles for enterprise use. The API enables access to\n      Red Hat-certified content with SLA-backed quality, partner-certified\n      content, and community content synced from Galaxy in supported namespaces.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://console.redhat.com/ansible/automation-hub\n    baseURL: https://console.redhat.com/api/automation-hub/v3/\n    tags:\n      - Ansible\n      - Certified Content\n      - Collections\n      - Enterprise\n      - Red Hat\n      - Roles\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/\n      - type: APIReference\n        url: https://console.redhat.com/api/automation-hub/v3/\n      - type: Portal\n        url: https://console.redhat.com/ansible/automation-hub\n    contact:\n      - FN: Red Hat Support\n        url: https://access.redhat.com/support\n\
  \nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n    X: apievangelist\n    url: https://apievangelist.com\ncommon:\n  - type: GettingStarted\n    url: https://docs.ansible.com/ansible/latest/galaxy/user_guide.html\n  - type: Authentication\n    url: https://galaxy.ansible.com/docs/authentication/\n  - type: TermsOfService\n    url: https://www.redhat.com/en/about/terms-use\n  - type: PrivacyPolicy\n    url: https://www.redhat.com/en/about/privacy-policy\n  - type: GitHubRepository\n    url: https://github.com/ansible/galaxy\n  - type: GitHubOrganization\n    url: https://github.com/ansible\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/json-schema/ansible-roles-role-schema.json\n    title: Role Schema\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/json-schema/ansible-roles-collection-schema.json\n    title: Collection Schema\n  - type: Vocabulary\n\
  \    url: https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/vocabulary/ansible-roles-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Role Search and Discovery\n        description: >-\n          Search Galaxy for community-contributed roles by keyword, author,\n          namespace, or tag to find reusable automation content.\n      - name: Collection Packaging\n        description: >-\n          Bundle roles, modules, plugins, and documentation into distributable\n          collection packages versioned and published via the Galaxy API.\n      - name: Version Management\n        description: >-\n          Access specific versions of roles and collections, enabling\n          pinned dependency management in Ansible projects.\n      - name: Certified Content\n        description: >-\n          Access Red Hat-certified and partner-validated Ansible collections\n          with enterprise-grade quality assurance via Automation Hub.\n      - name: Namespace\
  \ Management\n        description: >-\n          Manage author namespaces on Galaxy to publish and maintain role\n          and collection content under a consistent identity.\n  - type: UseCases\n    data:\n      - name: Role Reuse Across Projects\n        description: >-\n          Discover and install community roles from Galaxy to avoid\n          reinventing automation logic for common tasks like nginx, MySQL,\n          or Kubernetes setup.\n      - name: Certified Enterprise Automation\n        description: >-\n          Use Red Hat-certified collections from Automation Hub in production\n          environments where quality assurance and support are required.\n      - name: Private Content Distribution\n        description: >-\n          Publish internal roles and collections to a private Automation Hub\n          instance for controlled distribution within an organization.\n      - name: Dependency Management\n        description: >-\n          Pin role and collection versions\
  \ in requirements.yml files and\n          install them via the Galaxy API in CI/CD pipelines.\n  - type: Integrations\n    data:\n      - name: Ansible Playbooks\n        description: >-\n          Use roles discovered via the Galaxy API directly in Ansible playbooks\n          with the roles directive or include_role task.\n      - name: Ansible Automation Platform\n        description: >-\n          Synchronize collections from Galaxy or Automation Hub into\n          Ansible Automation Platform for use in job templates.\n      - name: Requirements Files\n        description: >-\n          Define role and collection dependencies in requirements.yml and\n          install them automatically via ansible-galaxy CLI using the API.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/apis.yml
tags:
- Ansible
- Automation
- Collections
- Configuration Management
- DevOps
- Infrastructure As Code
- Roles
url: https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/apis.yml
use_cases:
- description: Discover and install community roles from Galaxy to avoid reinventing automation logic for common tasks like nginx, MySQL, or Kubernetes setup.
  name: Role Reuse Across Projects
- description: Use Red Hat-certified collections from Automation Hub in production environments where quality assurance and support are required.
  name: Certified Enterprise Automation
- description: Publish internal roles and collections to a private Automation Hub instance for controlled distribution within an organization.
  name: Private Content Distribution
- description: Pin role and collection versions in requirements.yml files and install them via the Galaxy API in CI/CD pipelines.
  name: Dependency Management
---
