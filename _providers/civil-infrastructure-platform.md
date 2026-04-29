---
api_count: 5
apis:
- description: 'The CIP Kernel is a Super Long-Term Support (SLTS) Linux kernel branch maintained for ten or more years, providing a stable base for industrial systems that must remain in service across multi-decade '
  name: CIP SLTS Kernel
  slug: cip-kernel
- description: CIP Core provides a curated set of Debian-derived user-space packages aligned with the SLTS kernel to deliver a complete reference platform for civil infrastructure devices.
  name: CIP Core Packages
  slug: cip-core
- description: The CIP Software Update working group maintains tooling such as SWUpdate and hawkBit-based servers used to deliver secure over-the-air updates across long-lived industrial deployments.
  name: CIP Software Update
  slug: cip-software-update
- description: The CIP Security working group aligns the CIP base layer with IEC 62443-4-1 and 62443-4-2 industrial cybersecurity requirements and tracks CVE handling across the SLTS kernel and user-space.
  name: CIP Security
  slug: cip-security
- description: The CIP Testing working group runs continuous-integration and hardware-in-the-loop testing on member-supplied boards to validate kernel and core packages against the SLTS branch.
  name: CIP Testing
  slug: cip-testing
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.cip-project.org/
- title: ''
  type: Wiki
  url: https://wiki.linuxfoundation.org/civilinfrastructureplatform
- title: ''
  type: GitLab
  url: https://gitlab.com/cip-project
- title: ''
  type: GitHub
  url: https://github.com/cip-project
- title: ''
  type: Mailing List
  url: https://lists.cip-project.org/g/cip-dev
- title: ''
  type: Foundation
  url: https://www.linuxfoundation.org/projects/civil-infrastructure-platform/
- title: ''
  type: JSON-LD
  url: json-ld/civil-infrastructure-platform-context.jsonld
- title: ''
  type: Spectral
  url: rules/civil-infrastructure-platform-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/civil-infrastructure-platform-capabilities.yml
created: '2026-03-16'
description: The Civil Infrastructure Platform (CIP) is a Linux Foundation collaborative project that builds an industrial-grade open source base layer for civil infrastructure systems such as transportation, power generation and distribution, building and city management, industrial control, and healthcare equipment. CIP curates a Super Long-Term Support (SLTS) kernel and core user-space packages that can be maintained for more than ten years, plus working groups for security (IEC 62443 alignment), software update, real-time, and testing. CIP does not publish a public REST API surface; its programmable interface is the source code, kernel, and tooling published through GitLab and Debian-derived package archives.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 13
  name: Civil Infrastructure Platform Context
  property_count: 0
  slug: civil-infrastructure-platform-context
layout: provider
modified: '2026-04-23'
name: Civil Infrastructure Platform
rules:
- name: Civil Infrastructure Platform API Rules
  rule_count: 5
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 3
  slug: civil-infrastructure-platform-rules
skills: []
slug: civil-infrastructure-platform
solutions: []
source_yaml: "aid: civil-infrastructure-platform\nname: Civil Infrastructure Platform\nurl: https://raw.githubusercontent.com/api-evangelist/civil-infrastructure-platform/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Embedded\n  - Industrial\n  - Infrastructure\n  - Linux\n  - Linux Foundation\n  - Long-Term Support\n  - Open Source\ndescription: >-\n  The Civil Infrastructure Platform (CIP) is a Linux Foundation\n  collaborative project that builds an industrial-grade open source base\n  layer for civil infrastructure systems such as transportation, power\n  generation and distribution, building and city management, industrial\n  control, and healthcare equipment. CIP curates a Super Long-Term\n  Support (SLTS) kernel and core user-space packages that can be\n  maintained for more than ten\
  \ years, plus working groups for security\n  (IEC 62443 alignment), software update, real-time, and testing. CIP\n  does not publish a public REST API surface; its programmable interface\n  is the source code, kernel, and tooling published through GitLab and\n  Debian-derived package archives.\napis:\n  - aid: civil-infrastructure-platform:cip-kernel\n    name: CIP SLTS Kernel\n    tags:\n      - Embedded\n      - Kernel\n      - Linux\n      - SLTS\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://wiki.linuxfoundation.org/civilinfrastructureplatform/cipkernelmaintenance\n    properties:\n      - url: https://wiki.linuxfoundation.org/civilinfrastructureplatform/cipkernelmaintenance\n        type: Documentation\n      - url: https://gitlab.com/cip-project/cip-kernel\n        type: Source Code\n    description: >-\n      The CIP Kernel is a Super Long-Term Support (SLTS) Linux kernel\n      branch maintained for ten or more years,\
  \ providing a stable base\n      for industrial systems that must remain in service across\n      multi-decade lifecycles.\n  - aid: civil-infrastructure-platform:cip-core\n    name: CIP Core Packages\n    tags:\n      - Debian\n      - Packages\n      - Userspace\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://wiki.linuxfoundation.org/civilinfrastructureplatform/cipcore\n    properties:\n      - url: https://wiki.linuxfoundation.org/civilinfrastructureplatform/cipcore\n        type: Documentation\n      - url: https://gitlab.com/cip-project/cip-core\n        type: Source Code\n    description: >-\n      CIP Core provides a curated set of Debian-derived user-space\n      packages aligned with the SLTS kernel to deliver a complete\n      reference platform for civil infrastructure devices.\n  - aid: civil-infrastructure-platform:cip-software-update\n    name: CIP Software Update\n    tags:\n      - OTA\n      - Software Update\n\
  \      - SWUpdate\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://wiki.linuxfoundation.org/civilinfrastructureplatform/softwareupdate\n    properties:\n      - url: https://wiki.linuxfoundation.org/civilinfrastructureplatform/softwareupdate\n        type: Documentation\n    description: >-\n      The CIP Software Update working group maintains tooling such as\n      SWUpdate and hawkBit-based servers used to deliver secure\n      over-the-air updates across long-lived industrial deployments.\n  - aid: civil-infrastructure-platform:cip-security\n    name: CIP Security\n    tags:\n      - IEC 62443\n      - Industrial Security\n      - Security\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://wiki.linuxfoundation.org/civilinfrastructureplatform/cipsecurity\n    properties:\n      - url: https://wiki.linuxfoundation.org/civilinfrastructureplatform/cipsecurity\n      \
  \  type: Documentation\n    description: >-\n      The CIP Security working group aligns the CIP base layer with\n      IEC 62443-4-1 and 62443-4-2 industrial cybersecurity requirements\n      and tracks CVE handling across the SLTS kernel and user-space.\n  - aid: civil-infrastructure-platform:cip-testing\n    name: CIP Testing\n    tags:\n      - CI\n      - LAVA\n      - Testing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://wiki.linuxfoundation.org/civilinfrastructureplatform/ciptesting\n    properties:\n      - url: https://wiki.linuxfoundation.org/civilinfrastructureplatform/ciptesting\n        type: Documentation\n    description: >-\n      The CIP Testing working group runs continuous-integration and\n      hardware-in-the-loop testing on member-supplied boards to validate\n      kernel and core packages against the SLTS branch.\ncommon:\n  - type: Website\n    url: https://www.cip-project.org/\n  - type: Wiki\n   \
  \ url: https://wiki.linuxfoundation.org/civilinfrastructureplatform\n  - type: GitLab\n    url: https://gitlab.com/cip-project\n  - type: GitHub\n    url: https://github.com/cip-project\n  - type: Mailing List\n    url: https://lists.cip-project.org/g/cip-dev\n  - type: Foundation\n    url: https://www.linuxfoundation.org/projects/civil-infrastructure-platform/\n  - type: JSON-LD\n    url: json-ld/civil-infrastructure-platform-context.jsonld\n  - type: Spectral\n    url: rules/civil-infrastructure-platform-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/civil-infrastructure-platform-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/civil-infrastructure-platform/refs/heads/main/apis.yml
tags:
- Embedded
- Industrial
- Infrastructure
- Linux
- Linux Foundation
- Long-Term Support
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/civil-infrastructure-platform/refs/heads/main/apis.yml
use_cases: []
---
