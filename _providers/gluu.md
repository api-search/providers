---
api_count: 4
apis:
- description: Gluu Flex is the commercial, self-hosted enterprise distribution of the Linux Foundation Janssen Project. It provides a cloud-native digital identity platform with OAuth 2.0, OpenID Connect, FIDO, SCI
  name: Gluu Flex
  slug: gluu-flex
- description: 'The Janssen Project is the upstream Linux Foundation open-source identity platform that powers Gluu Flex. It implements OAuth 2.0, OpenID Connect, FIDO 2.0, SCIM, UMA, and CIBA, providing a federated '
  name: Janssen Project
  slug: janssen-project
- description: Cedarling is an embeddable Policy Decision Point (PDP) built in Rust that runs anywhere and returns authorization decisions in under 50 microseconds based on declarative Cedar access policies. It vali
  name: Cedarling
  slug: cedarling
- description: Agama Lab is a developer portal for authoring Cedar schema and policies, building authentication workflows using the Agama domain specific language, and managing hosted Gluu infrastructure.
  name: Agama Lab
  slug: agama-lab
common:
- title: ''
  type: Website
  url: https://gluu.org/
- title: ''
  type: Documentation
  url: https://docs.gluu.org/
- title: ''
  type: Blog
  url: https://gluu.org/blog/
- title: ''
  type: Support
  url: https://help.gluu.org/
- title: ''
  type: GitHub Organization
  url: https://github.com/GluuFederation
- title: ''
  type: Pricing
  url: https://gluu.org/pricing/
- title: ''
  type: Contact
  url: https://gluu.org/contact/
- title: ''
  type: Community
  url: https://gluu.org/community/
created: '2025-08-14'
description: Gluu is a technology company that specializes in providing identity and access management solutions for businesses. Their platform allows organizations to centrally manage the authentication and authorization of users across various applications and systems, ensuring secure access to sensitive data and resources.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Gluu
skills: []
slug: gluu
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: gluu\nname: Gluu\ndescription: >-\n  Gluu is a technology company that specializes in providing identity and\n  access management solutions for businesses. Their platform allows\n  organizations to centrally manage the authentication and authorization of\n  users across various applications and systems, ensuring secure access to\n  sensitive data and resources.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-08-14'\nmodified: '2026-04-28'\nposition: Consumer\ntags:\n  - Access Management\n  - Authentication\n  - Authorization\n  - IAM\n  - Identities\n  - OAuth\n  - OpenID Connect\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/gluu/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: gluu:gluu-flex\n    name: Gluu Flex\n    description: >-\n      Gluu Flex is the commercial, self-hosted enterprise distribution of the\n      Linux Foundation Janssen Project.\
  \ It provides a cloud-native digital\n      identity platform with OAuth 2.0, OpenID Connect, FIDO, SCIM, and UMA\n      capabilities, deployable via Helm charts with auto-scaling support.\n    humanURL: https://gluu.org/flex/\n    baseURL: https://docs.gluu.org/\n    tags:\n      - Authentication\n      - Authorization\n      - IAM\n      - OAuth\n      - OpenID Connect\n    properties:\n      - type: Documentation\n        url: https://docs.gluu.org/\n      - type: Getting Started\n        url: https://docs.gluu.org/head/admin-guide/quick-start/\n      - type: GitHubRepository\n        url: https://github.com/GluuFederation/flex\n      - type: Pricing\n        url: https://gluu.org/pricing/\n  - aid: gluu:janssen-project\n    name: Janssen Project\n    description: >-\n      The Janssen Project is the upstream Linux Foundation open-source\n      identity platform that powers Gluu Flex. It implements OAuth 2.0,\n      OpenID Connect, FIDO 2.0, SCIM, UMA, and CIBA, providing a federated\n\
  \      identity provider, authorization server, and FIDO server.\n    humanURL: https://jans.io/\n    baseURL: https://docs.jans.io/\n    tags:\n      - Authentication\n      - Authorization\n      - Linux Foundation\n      - OAuth\n      - Open Source\n      - OpenID Connect\n    properties:\n      - type: Documentation\n        url: https://docs.jans.io/\n      - type: GitHubRepository\n        url: https://github.com/JanssenProject/jans\n      - type: Reference\n        url: https://docs.jans.io/head/admin/reference/\n  - aid: gluu:cedarling\n    name: Cedarling\n    description: >-\n      Cedarling is an embeddable Policy Decision Point (PDP) built in Rust\n      that runs anywhere and returns authorization decisions in under 50\n      microseconds based on declarative Cedar access policies. It validates\n      JWT tokens and applies policies to deliver fine-grained authorization.\n    humanURL: https://gluu.org/cedarling/\n    tags:\n      - Authorization\n      - Cedar\n      - PDP\n\
  \      - Policy\n      - Rust\n    properties:\n      - type: Documentation\n        url: https://docs.jans.io/head/cedarling/cedarling-overview/\n      - type: GitHubRepository\n        url: https://github.com/JanssenProject/jans/tree/main/jans-cedarling\n  - aid: gluu:agama-lab\n    name: Agama Lab\n    description: >-\n      Agama Lab is a developer portal for authoring Cedar schema and\n      policies, building authentication workflows using the Agama domain\n      specific language, and managing hosted Gluu infrastructure.\n    humanURL: https://gluu.org/agama-lab/\n    tags:\n      - Authentication\n      - Developer Portal\n      - DSL\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://docs.gluu.org/agama-lab/\n      - type: Portal\n        url: https://cloud.gluu.org/agama-lab\ncommon:\n  - type: Website\n    url: https://gluu.org/\n  - type: Documentation\n    url: https://docs.gluu.org/\n  - type: Blog\n    url: https://gluu.org/blog/\n  -\
  \ type: Support\n    url: https://help.gluu.org/\n  - type: GitHub Organization\n    url: https://github.com/GluuFederation\n  - type: Pricing\n    url: https://gluu.org/pricing/\n  - type: Contact\n    url: https://gluu.org/contact/\n  - type: Community\n    url: https://gluu.org/community/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/gluu/refs/heads/main/apis.yml
tags:
- Access Management
- Authentication
- Authorization
- IAM
- Identities
- OAuth
- OpenID Connect
url: https://raw.githubusercontent.com/api-evangelist/gluu/refs/heads/main/apis.yml
use_cases: []
---
