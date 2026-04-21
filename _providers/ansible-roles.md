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
