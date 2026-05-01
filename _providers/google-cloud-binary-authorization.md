---
api_count: 1
api_specs:
- filename: binary-authorization-api-openapi.yml
  format: yaml
  label: Binary Authorization API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-binary-authorization/refs/heads/main/openapi/binary-authorization-api-openapi.yml
apis:
- description: The Binary Authorization API provides programmatic access to manage deploy-time security policies for container images. Developers can use the API to create and manage attestors, attestations, and pol
  name: Binary Authorization API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://cloud.google.com/binary-authorization
- title: ''
  type: Getting Started
  url: https://cloud.google.com/binary-authorization/docs/getting-started-cli
- title: ''
  type: Documentation
  url: https://cloud.google.com/binary-authorization/docs
- title: ''
  type: Authentication
  url: https://cloud.google.com/binary-authorization/docs/reference/rest#authentication
- title: ''
  type: Pricing
  url: https://cloud.google.com/binary-authorization/pricing
- title: ''
  type: Terms of Service
  url: https://cloud.google.com/terms
- title: ''
  type: Privacy Policy
  url: https://policies.google.com/privacy
- title: ''
  type: Status
  url: https://status.cloud.google.com
- title: ''
  type: Support
  url: https://cloud.google.com/binary-authorization/docs/support
- title: ''
  type: JSON-LD
  url: json-ld/google-cloud-binary-authorization-context.jsonld
created: '2026-03-13'
description: Google Cloud Binary Authorization is a deploy-time security control that ensures only trusted container images are deployed on Google Kubernetes Engine (GKE), Cloud Run, and Anthos clusters. It uses attestation-based policies to validate that container images have been signed by trusted authorities before allowing deployment, helping enforce software supply chain security.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Google Cloud Binary Authorization Context
  property_count: 3
  slug: google-cloud-binary-authorization-context
layout: provider
modified: '2026-04-28'
name: Google Cloud Binary Authorization
skills: []
slug: google-cloud-binary-authorization
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-cloud-binary-authorization\nname: Google Cloud Binary Authorization\ndescription: >-\n  Google Cloud Binary Authorization is a deploy-time security control that\n  ensures only trusted container images are deployed on Google Kubernetes Engine\n  (GKE), Cloud Run, and Anthos clusters. It uses attestation-based policies to\n  validate that container images have been signed by trusted authorities before\n  allowing deployment, helping enforce software supply chain security.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/google-cloud-binary-authorization/refs/heads/main/apis.yml\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Attestation\n  - Container Security\n  - DevSecOps\n  - Kubernetes\n  - Policy Enforcement\n  - Supply Chain Security\napis:\n  - name: Binary Authorization API\n    description: >-\n      The Binary Authorization\
  \ API provides programmatic access to manage\n      deploy-time security policies for container images. Developers can use the\n      API to create and manage attestors, attestations, and policies that control\n      which container images are allowed to be deployed. The API integrates with\n      GKE, Cloud Run, and Anthos to enforce that only verified and trusted\n      container images are deployed to production environments.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloud.google.com/binary-authorization/docs\n    baseURL: https://binaryauthorization.googleapis.com\n    tags:\n      - Attestations\n      - Attestors\n      - Container Images\n      - Policies\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/binary-authorization/docs/reference/rest\n      - type: OpenAPI\n        url: openapi/binary-authorization-api-openapi.yml\n      - type: Authentication\n        url: https://cloud.google.com/binary-authorization/docs/reference/rest#authentication\n\
  \      - type: JSONSchema\n        url: json-schema/google-cloud-binary-authorization-policy-schema.json\ncommon:\n  - type: Portal\n    url: https://cloud.google.com/binary-authorization\n  - type: Getting Started\n    url: https://cloud.google.com/binary-authorization/docs/getting-started-cli\n  - type: Documentation\n    url: https://cloud.google.com/binary-authorization/docs\n  - type: Authentication\n    url: https://cloud.google.com/binary-authorization/docs/reference/rest#authentication\n  - type: Pricing\n    url: https://cloud.google.com/binary-authorization/pricing\n  - type: Terms of Service\n    url: https://cloud.google.com/terms\n  - type: Privacy Policy\n    url: https://policies.google.com/privacy\n  - type: Status\n    url: https://status.cloud.google.com\n  - type: Support\n    url: https://cloud.google.com/binary-authorization/docs/support\n  - type: JSON-LD\n    url: json-ld/google-cloud-binary-authorization-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email:\
  \ kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-binary-authorization/refs/heads/main/apis.yml
tags:
- Attestation
- Container Security
- DevSecOps
- Kubernetes
- Policy Enforcement
- Supply Chain Security
url: https://raw.githubusercontent.com/api-evangelist/google-cloud-binary-authorization/refs/heads/main/apis.yml
use_cases: []
---
