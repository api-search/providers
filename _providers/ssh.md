---
api_count: 2
api_specs:
- filename: ssh-key-management-openapi.yml
  format: yaml
  label: OpenSSH Key Management API
  slug: openssh-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/openapi/ssh-key-management-openapi.yml
apis:
- description: OpenSSH is the premier open-source SSH implementation. While SSH itself is a protocol, OpenSSH provides programmatic interfaces for key management, authorized_keys configuration, known_hosts managemen
  name: OpenSSH Key Management API
  slug: openssh-management
- description: 'Teleport is a modern SSH infrastructure access platform providing certificate-based authentication, session recording, audit logging, and role-based access control for SSH, Kubernetes, databases, and '
  name: Teleport Access Management API
  slug: teleport-api
capabilities:
- description: Unified workflow capability for SSH key lifecycle management, certificate authority operations, and access control. Enables security and infrastructure teams to manage SSH keys, sign short-lived certi
  name: SSH Key Management
  slug: key-management
common:
- title: ''
  type: Website
  url: https://www.openssh.com/
- title: ''
  type: Documentation
  url: https://www.openssh.com/manual.html
- title: ''
  type: GitHub Organization
  url: https://github.com/openssh
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/openapi/ssh-key-management-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/json-schema/ssh-key-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/json-structure/ssh-key-structure.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/json-ld/ssh-context.jsonld
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/rules/ssh-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/capabilities/key-management.yaml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/vocabulary/ssh-vocabulary.yml
created: '2025-01-01'
description: SSH (Secure Shell) is a cryptographic network protocol for secure remote login, command execution, and file transfer between computers over unsecured networks. It provides strong encryption, authentication, and data integrity, replacing insecure protocols like Telnet and rlogin. SSH is a fundamental tool for system administration, DevOps, and secure infrastructure access. Multiple vendors provide SSH client libraries, server implementations, and management APIs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 15
  name: Ssh Context
  property_count: 6
  slug: ssh-context
layout: provider
modified: '2026-05-02'
name: SSH
rules:
- name: SSH API Rules
  rule_count: 6
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 3
  slug: ssh-rules
skills: []
slug: ssh
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ssh\nname: SSH\ndescription: >-\n  SSH (Secure Shell) is a cryptographic network protocol for secure remote login,\n  command execution, and file transfer between computers over unsecured networks.\n  It provides strong encryption, authentication, and data integrity, replacing\n  insecure protocols like Telnet and rlogin. SSH is a fundamental tool for\n  system administration, DevOps, and secure infrastructure access. Multiple\n  vendors provide SSH client libraries, server implementations, and management\n  APIs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - SSH\n  - Secure Shell\n  - Remote Access\n  - Cryptography\n  - Network Security\n  - System Administration\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: ssh:openssh-management\n    name: OpenSSH Key Management API\n \
  \   description: >-\n      OpenSSH is the premier open-source SSH implementation. While SSH itself\n      is a protocol, OpenSSH provides programmatic interfaces for key management,\n      authorized_keys configuration, known_hosts management, and integration\n      with PAM and certificate authorities. SSH certificate authorities enable\n      large-scale key management via short-lived certificates.\n    humanURL: https://www.openssh.com/\n    baseURL: https://api.openssh.example.com/v1\n    tags:\n      - SSH\n      - OpenSSH\n      - Key Management\n      - Certificate Authority\n      - Authentication\n    properties:\n      - type: Documentation\n        url: https://www.openssh.com/manual.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/openapi/ssh-key-management-openapi.yml\n  - aid: ssh:teleport-api\n    name: Teleport Access Management API\n    description: >-\n      Teleport is a modern SSH infrastructure\
  \ access platform providing\n      certificate-based authentication, session recording, audit logging,\n      and role-based access control for SSH, Kubernetes, databases, and\n      web applications. Teleport's API enables programmatic management of\n      users, roles, certificates, and access policies.\n    humanURL: https://goteleport.com/\n    baseURL: https://teleport.example.com/v1\n    tags:\n      - SSH\n      - Access Management\n      - Certificate Authority\n      - Zero Trust\n      - Privileged Access\n    properties:\n      - type: Documentation\n        url: https://goteleport.com/docs/\ncommon:\n  - type: Website\n    url: https://www.openssh.com/\n  - type: Documentation\n    url: https://www.openssh.com/manual.html\n  - type: GitHub Organization\n    url: https://github.com/openssh\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/openapi/ssh-key-management-openapi.yml\n  - type: JSONSchema\n    url: >-\n    \
  \  https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/json-schema/ssh-key-schema.json\n  - type: JSONStructure\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/json-structure/ssh-key-structure.json\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/json-ld/ssh-context.jsonld\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/rules/ssh-rules.yml\n  - type: NaftikoCapabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/capabilities/key-management.yaml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/vocabulary/ssh-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/apis.yml
tags:
- SSH
- Secure Shell
- Remote Access
- Cryptography
- Network Security
- System Administration
url: https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/apis.yml
use_cases: []
---
