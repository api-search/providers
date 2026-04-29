---
api_count: 2
apis:
- description: A portfolio of open source projects governed by the Confidential Computing Consortium covering Trusted Execution Environment runtimes, remote attestation services, trustworthy workload identity, and s
  name: Confidential Computing Consortium Projects
  slug: ccc-projects
- description: A working group and set of Internet Draft specifications under the Confidential Computing Consortium that define how confidential workloads establish, prove, and consume identity using remote attestat
  name: Trustworthy Workload Identity (TWI) Specifications
  slug: trustworthy-workload-identity
common:
- title: ''
  type: Website
  url: https://confidentialcomputing.io/
- title: ''
  type: Documentation
  url: https://confidentialcomputing.io/resources/
- title: ''
  type: Projects
  url: https://confidentialcomputing.io/projects/
- title: ''
  type: GitHub
  url: https://github.com/confidential-computing
- title: ''
  type: Glossary
  url: https://github.com/confidential-computing/glossary
- title: ''
  type: Governance
  url: https://github.com/confidential-computing/governance
- title: ''
  type: Mailing Lists
  url: https://lists.confidentialcomputing.io/
- title: ''
  type: Blog
  url: https://confidentialcomputing.io/news/
- title: ''
  type: Events
  url: https://confidentialcomputing.io/events/
- title: ''
  type: Membership
  url: https://confidentialcomputing.io/membership/
created: '2026-03-16'
description: The Confidential Computing Consortium (CCC) is a Linux Foundation project that brings together hardware vendors, cloud providers, and software developers to accelerate the adoption of confidential computing. CCC defines, advances, and standardizes hardware-based Trusted Execution Environments (TEEs) that protect data and code while in use, complementing existing protections for data at rest and in transit. The consortium governs open source projects and specifications spanning attestation, trustworthy workload identity, and TEE runtimes.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Confidential Computing Consortium
skills: []
slug: confidential-computing-consortium
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: confidential-computing-consortium\nname: Confidential Computing Consortium\ndescription: >-\n  The Confidential Computing Consortium (CCC) is a Linux Foundation project\n  that brings together hardware vendors, cloud providers, and software\n  developers to accelerate the adoption of confidential computing. CCC\n  defines, advances, and standardizes hardware-based Trusted Execution\n  Environments (TEEs) that protect data and code while in use, complementing\n  existing protections for data at rest and in transit. The consortium\n  governs open source projects and specifications spanning attestation,\n  trustworthy workload identity, and TEE runtimes.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/confidential-computing-consortium/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion:\
  \ '0.19'\nx-type: opensource\ntags:\n  - Attestation\n  - Confidential Computing\n  - Hardware\n  - Linux Foundation\n  - Open Source\n  - Privacy\n  - Security\n  - TEE\n  - Trusted Execution Environment\napis:\n  - aid: confidential-computing-consortium:ccc-projects\n    name: Confidential Computing Consortium Projects\n    description: >-\n      A portfolio of open source projects governed by the Confidential Computing\n      Consortium covering Trusted Execution Environment runtimes, remote\n      attestation services, trustworthy workload identity, and shared tooling\n      for confidential computing across CPU, GPU, and accelerator vendors.\n      Projects include hosted SDKs, attestation services, and reference\n      implementations rather than a single REST API.\n    humanURL: https://confidentialcomputing.io/projects/\n    baseURL: https://confidentialcomputing.io/projects/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n   \
  \   - Attestation\n      - Confidential Computing\n      - Open Source\n      - TEE\n    properties:\n      - type: Documentation\n        url: https://confidentialcomputing.io/projects/\n      - type: GitHub\n        url: https://github.com/confidential-computing\n    x-features:\n      - TEE Runtimes\n      - Remote Attestation\n      - Workload Identity\n      - Hardware Security\n      - Open Source Governance\n    x-use-cases:\n      - Protect AI/ML training and inference data in use\n      - Run regulated workloads in untrusted clouds\n      - Establish verifiable identity for cloud workloads\n      - Build privacy-preserving multi-party computation\n      - Standardize cross-vendor TEE attestation flows\n  - aid: confidential-computing-consortium:trustworthy-workload-identity\n    name: Trustworthy Workload Identity (TWI) Specifications\n    description: >-\n      A working group and set of Internet Draft specifications under the\n      Confidential Computing Consortium that define\
  \ how confidential workloads\n      establish, prove, and consume identity using remote attestation evidence.\n      TWI work intersects with the IETF RATS (Remote Attestation Procedures)\n      and WIMSE (Workload Identity in a Multi-System Environment) groups,\n      providing the foundation for attested, portable workload identity.\n    humanURL: https://github.com/confidential-computing/twi\n    baseURL: https://github.com/confidential-computing/twi\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Attestation\n      - IETF\n      - Specifications\n      - Workload Identity\n    properties:\n      - type: Documentation\n        url: https://github.com/confidential-computing/twi\n      - type: GitHub\n        url: https://github.com/confidential-computing/twi\n      - type: Related\n        url: https://github.com/confidential-computing/twi-rats\n      - type: Related\n        url: https://github.com/confidential-computing/twi-wimse\n\
  \    x-features:\n      - Workload Identity Standards\n      - Remote Attestation Mappings\n      - IETF Drafts\n    x-use-cases:\n      - Define identity for confidential workloads\n      - Bind workload identity to hardware attestation\n      - Interoperate across cloud providers and hardware vendors\ncommon:\n  - type: Website\n    url: https://confidentialcomputing.io/\n  - type: Documentation\n    url: https://confidentialcomputing.io/resources/\n  - type: Projects\n    url: https://confidentialcomputing.io/projects/\n  - type: GitHub\n    url: https://github.com/confidential-computing\n  - type: Glossary\n    url: https://github.com/confidential-computing/glossary\n  - type: Governance\n    url: https://github.com/confidential-computing/governance\n  - type: Mailing Lists\n    url: https://lists.confidentialcomputing.io/\n  - type: Blog\n    url: https://confidentialcomputing.io/news/\n  - type: Events\n    url: https://confidentialcomputing.io/events/\n  - type: Membership\n   \
  \ url: https://confidentialcomputing.io/membership/\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/confidential-computing-consortium/refs/heads/main/apis.yml
tags:
- Attestation
- Confidential Computing
- Hardware
- Linux Foundation
- Open Source
- Privacy
- Security
- TEE
- Trusted Execution Environment
url: https://raw.githubusercontent.com/api-evangelist/confidential-computing-consortium/refs/heads/main/apis.yml
use_cases: []
---
