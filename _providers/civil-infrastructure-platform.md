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
