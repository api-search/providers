---
api_count: 4
api_specs:
- filename: cyberark-conjur-openapi.yml
  format: yaml
  label: CyberArk Conjur Secrets Manager API
  slug: conjur
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cyberark/refs/heads/main/openapi/cyberark-conjur-openapi.yml
apis:
- description: Conjur is CyberArk's secrets management platform for machine identities and DevOps workloads, delivered as Conjur Open Source, Conjur Enterprise (Self-Hosted), and Conjur Cloud (SaaS). The REST API su
  name: CyberArk Conjur Secrets Manager API
  slug: conjur
- description: The Privileged Access Manager Self-Hosted REST API exposes the Vault for managing accounts, safes, platforms, users, sessions, and applications. Authentication uses the Logon endpoint at /PasswordVaul
  name: CyberArk PAM Self-Hosted REST API
  slug: pam-self-hosted
- description: The Privilege Cloud Shared Services REST API mirrors the PAM Self-Hosted surface for accounts, safes, platforms, and users while running as a SaaS on the CyberArk Identity Security Platform. Identitie
  name: CyberArk Privilege Cloud REST API
  slug: privilege-cloud
- description: The CyberArk Identity REST API enables programmatic management of users, roles, applications, MFA policies, SSO, and SCIM-based provisioning across the workforce identity tenant. Tenants are addressed
  name: CyberArk Identity REST API
  slug: identity
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.cyberark.com
- title: ''
  type: Products
  url: https://www.cyberark.com/products/
- title: ''
  type: Documentation
  url: https://docs.cyberark.com
- title: ''
  type: DeveloperPortal
  url: https://developer.cyberark.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/cyberark
- title: ''
  type: ConjurOpenAPISpec
  url: https://github.com/cyberark/conjur-openapi-spec
- title: ''
  type: Marketplace
  url: https://marketplace.cyberark.com/
- title: ''
  type: Trust
  url: https://www.cyberark.com/trust/
- title: ''
  type: TermsOfService
  url: https://www.cyberark.com/legal-terms-of-use/
- title: ''
  type: PrivacyPolicy
  url: https://www.cyberark.com/privacy-policy/
- title: ''
  type: JSON-LD
  url: json-ld/cyberark-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cyberark-conjur-resource-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cyberark-privileged-account-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/cyberark-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/cyberark-conjur-capabilities.yml
- title: ''
  type: Rules
  url: rules/cyberark-conjur-rules.yml
created: '2026-03-25'
description: CyberArk is the global leader in identity security, providing a unified Identity Security Platform that protects human, machine, and application identities across hybrid and multi-cloud environments. Core product lines include Privileged Access Manager (PAM Self-Hosted) and Privilege Cloud for credential vaulting and session management; Conjur Secrets Manager (Open Source, Enterprise, and Cloud) for machine-identity and DevOps secrets; CyberArk Identity for workforce SSO, MFA, and lifecycle; Endpoint Privilege Manager for least-privilege enforcement on Windows / macOS / Linux endpoints; Secure Cloud Access for just-in-time cloud entitlements; and Customer Identity for B2B / B2C identity. CyberArk publishes a canonical OpenAPI 3.1 specification for Conjur Secrets Manager at github.com/cyberark/conjur-openapi-spec, and REST APIs for PAM Self-Hosted, Privilege Cloud, and CyberArk Identity are documented on docs.cyberark.com and developer.cyberark.com.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 29
  name: Cyberark Context
  property_count: 0
  slug: cyberark-context
layout: provider
modified: '2026-04-28'
name: CyberArk
rules:
- name: CyberArk API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 4
  slug: cyberark-conjur-rules
skills: []
slug: cyberark
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cyberark\nname: CyberArk\nx-type: company\ndescription: >-\n  CyberArk is the global leader in identity security, providing a\n  unified Identity Security Platform that protects human, machine, and\n  application identities across hybrid and multi-cloud environments.\n  Core product lines include Privileged Access Manager (PAM\n  Self-Hosted) and Privilege Cloud for credential vaulting and session\n  management; Conjur Secrets Manager (Open Source, Enterprise, and\n  Cloud) for machine-identity and DevOps secrets; CyberArk Identity\n  for workforce SSO, MFA, and lifecycle; Endpoint Privilege Manager\n  for least-privilege enforcement on Windows / macOS / Linux endpoints;\n  Secure Cloud Access for just-in-time cloud entitlements; and\n  Customer Identity for B2B / B2C identity. CyberArk publishes a\n  canonical OpenAPI 3.1 specification for Conjur Secrets Manager at\n  github.com/cyberark/conjur-openapi-spec, and REST APIs for PAM\n  Self-Hosted, Privilege Cloud, and CyberArk\
  \ Identity are documented\n  on docs.cyberark.com and developer.cyberark.com.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cyberark/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\naccess: 3rd-Party\nposition: Consuming\ncreated: '2026-03-25'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntags:\n  - Authentication\n  - Cloud Security\n  - Conjur\n  - Credential Vault\n  - DevOps Secrets\n  - Endpoint Privilege Management\n  - Identity Security\n  - Machine Identity\n  - MFA\n  - OpenAPI\n  - PAM\n  - Privileged Access\n  - Privileged Access Management\n  - Secrets Management\n  - Session Management\n  - SSO\n  - Vault\n  - Zero Trust\napis:\n  - aid: cyberark:conjur\n    name: CyberArk Conjur Secrets Manager API\n    description: >-\n      Conjur is CyberArk's secrets management platform for machine\n      identities and DevOps workloads, delivered as Conjur Open Source,\n      Conjur Enterprise\
  \ (Self-Hosted), and Conjur Cloud (SaaS). The\n      REST API supports authenticating hosts and users, loading and\n      replacing policy YAML, storing and retrieving versioned secrets,\n      managing resources and roles, and retrieving public keys. The\n      canonical OpenAPI 3.1 spec is open-sourced at\n      github.com/cyberark/conjur-openapi-spec.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.cyberark.com/conjur-cloud/latest/en/content/developer/conjur-api-openapi.html\n    baseURL: https://conjur.example.com\n    tags:\n      - Authentication\n      - Conjur\n      - DevOps Secrets\n      - Machine Identity\n      - Policies\n      - Resources\n      - Roles\n      - Secrets\n      - Vault\n    properties:\n      - type: Documentation\n        url: https://docs.cyberark.com/conjur-cloud/latest/en/content/developer/conjur-api-openapi.html\n      - type: OpenAPI\n        url: openapi/cyberark-conjur-openapi.yml\n\
  \      - type: CanonicalOpenAPI\n        url: https://github.com/cyberark/conjur-openapi-spec\n      - type: Capabilities\n        url: capabilities/cyberark-conjur-capabilities.yml\n      - type: Rules\n        url: rules/cyberark-conjur-rules.yml\n      - type: GitHubRepository\n        url: https://github.com/cyberark/conjur\n      - type: Blog\n        url: https://developer.cyberark.com/blog/introducing-the-conjur-openapi-description/\n  - aid: cyberark:pam-self-hosted\n    name: CyberArk PAM Self-Hosted REST API\n    description: >-\n      The Privileged Access Manager Self-Hosted REST API exposes the\n      Vault for managing accounts, safes, platforms, users, sessions,\n      and applications. Authentication uses the Logon endpoint at\n      /PasswordVault/API/Auth/{provider}/Logon to obtain a session\n      token used in the Authorization header for subsequent calls.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.cyberark.com/pam-self-hosted/latest/en/content/webservices/implementing%20privileged%20account%20security%20web%20services%20.htm\n\
  \    tags:\n      - Accounts\n      - PAM\n      - Privileged Access\n      - REST\n      - Safes\n      - Sessions\n      - Vault\n    properties:\n      - type: Documentation\n        url: https://docs.cyberark.com/pam-self-hosted/latest/en/content/webservices/implementing%20privileged%20account%20security%20web%20services%20.htm\n      - type: SampleScripts\n        url: https://github.com/cyberark/epv-api-scripts\n      - type: PowerShellModule\n        url: https://github.com/pspete/psPAS\n  - aid: cyberark:privilege-cloud\n    name: CyberArk Privilege Cloud REST API\n    description: >-\n      The Privilege Cloud Shared Services REST API mirrors the PAM\n      Self-Hosted surface for accounts, safes, platforms, and users\n      while running as a SaaS on the CyberArk Identity Security\n      Platform. Identities and groups reference the tenant's CyberArk\n      Identity directory.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL:\
  \ https://docs.cyberark.com/privilege-cloud-shared-services/latest/en/content/sdk/sdk-overview.htm\n    tags:\n      - Accounts\n      - PAM\n      - Privilege Cloud\n      - Safes\n      - SaaS\n      - Vault\n    properties:\n      - type: Documentation\n        url: https://docs.cyberark.com/privilege-cloud-shared-services/latest/en/content/sdk/sdk-overview.htm\n      - type: WhatsNew\n        url: https://docs.cyberark.com/privilege-cloud-shared-services/latest/en/content/privilege%20cloud/privcloud-whatsnew-v12.2.htm\n  - aid: cyberark:identity\n    name: CyberArk Identity REST API\n    description: >-\n      The CyberArk Identity REST API enables programmatic management\n      of users, roles, applications, MFA policies, SSO, and SCIM-based\n      provisioning across the workforce identity tenant. Tenants are\n      addressed at {tenant}.id.cyberark.cloud and authentication uses\n      OAuth2.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://docs.cyberark.com/identity/Latest/en/Content/Developer/Developer.htm\n    tags:\n      - Identity\n      - MFA\n      - OAuth2\n      - SCIM\n      - SSO\n      - Workforce Identity\n    properties:\n      - type: Documentation\n        url: https://docs.cyberark.com/identity/Latest/en/Content/Developer/Developer.htm\n      - type: SCIM\n        url: https://docs.cyberark.com/identity/latest/en/content/developer/scim-management/scim-overview.htm\n      - type: DeveloperPortal\n        url: https://developer.cyberark.com/\ncommon:\n  - type: Website\n    url: https://www.cyberark.com\n  - type: Products\n    url: https://www.cyberark.com/products/\n  - type: Documentation\n    url: https://docs.cyberark.com\n  - type: DeveloperPortal\n    url: https://developer.cyberark.com/\n  - type: GitHubOrganization\n    url: https://github.com/cyberark\n  - type: ConjurOpenAPISpec\n    url: https://github.com/cyberark/conjur-openapi-spec\n  - type: Marketplace\n    url: https://marketplace.cyberark.com/\n\
  \  - type: Trust\n    url: https://www.cyberark.com/trust/\n  - type: TermsOfService\n    url: https://www.cyberark.com/legal-terms-of-use/\n  - type: PrivacyPolicy\n    url: https://www.cyberark.com/privacy-policy/\n  - type: JSON-LD\n    url: json-ld/cyberark-context.jsonld\n  - type: JSONSchema\n    url: json-schema/cyberark-conjur-resource-schema.json\n  - type: JSONSchema\n    url: json-schema/cyberark-privileged-account-schema.json\n  - type: Vocabulary\n    url: vocabulary/cyberark-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/cyberark-conjur-capabilities.yml\n  - type: Rules\n    url: rules/cyberark-conjur-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cyberark/refs/heads/main/apis.yml
tags:
- Authentication
- Cloud Security
- Conjur
- Credential Vault
- DevOps Secrets
- Endpoint Privilege Management
- Identity Security
- Machine Identity
- MFA
- OpenAPI
- PAM
- Privileged Access
- Privileged Access Management
- Secrets Management
- Session Management
- SSO
- Vault
- Zero Trust
url: https://raw.githubusercontent.com/api-evangelist/cyberark/refs/heads/main/apis.yml
use_cases: []
---
