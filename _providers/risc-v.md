---
api_count: 5
apis:
- description: The canonical RISC-V Instruction Set Architecture specifications including the Unprivileged ISA (RV32I/RV64I base integer instructions) and Privileged Architecture specification. Freely available as r
  name: RISC-V ISA Specifications
  slug: isa-specifications
- description: Documentation of the RISC-V C API including calling conventions, ABI specifications, compiler intrinsics, and architectural extension interfaces for C/C++ development targeting RISC-V processors.
  name: RISC-V C API Documentation
  slug: c-api-documentation
- description: 'Supporting technical standards that do not add new instructions or modify the RISC-V ISA but help develop the ecosystem, including platform specifications, debug specifications, trace specifications, '
  name: RISC-V Non-ISA Specifications
  slug: non-isa-specifications
- description: Spike is the official RISC-V ISA Simulator and the golden reference implementation for RISC-V. It simulates the execution of RISC-V programs and is used for architecture validation and software develo
  name: RISC-V Spike ISA Simulator
  slug: spike-simulator
- description: OpenSBI is the official open-source implementation of the RISC-V Supervisor Binary Interface (SBI) specification. It provides a firmware execution environment for M-mode privileged operations and serv
  name: RISC-V OpenSBI
  slug: opensbi
common:
- title: ''
  type: Website
  url: https://riscv.org/
- title: ''
  type: Documentation
  url: https://riscv.org/technical/specifications/
- title: ''
  type: GithubOrg
  url: https://github.com/riscv
- title: ''
  type: GithubOrg
  url: https://github.com/riscv-non-isa
- title: ''
  type: GithubOrg
  url: https://github.com/riscv-software-src
- title: ''
  type: Wiki
  url: https://wiki.riscv.org/
- title: ''
  type: MemberPortal
  url: https://members.riscv.org/
- title: ''
  type: PrivacyPolicy
  url: https://riscv.org/privacy-policy/
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/risc-v/refs/heads/main/json-schema/risc-v-specification-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/risc-v/refs/heads/main/json-ld/risc-v-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/risc-v/refs/heads/main/vocabulary/risc-v-vocabulary.yml
created: '2026-03-16'
description: RISC-V International advances the RISC-V open standard instruction set architecture (ISA), promoting open hardware development and reducing dependency on proprietary processor designs. The organization maintains the canonical RISC-V ISA specifications, profiles, non-ISA specifications, extensions, and a rich ecosystem of open-source tools including simulators, compilers, debuggers, and verification frameworks.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 32
  name: Risc V Context
  property_count: 0
  slug: risc-v-context
layout: provider
modified: '2026-05-02'
name: RISC-V International
skills: []
slug: risc-v
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: risc-v\nname: RISC-V International\ndescription: >-\n  RISC-V International advances the RISC-V open standard instruction set\n  architecture (ISA), promoting open hardware development and reducing\n  dependency on proprietary processor designs. The organization maintains the\n  canonical RISC-V ISA specifications, profiles, non-ISA specifications,\n  extensions, and a rich ecosystem of open-source tools including simulators,\n  compilers, debuggers, and verification frameworks.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - C API\n  - Compiler\n  - Hardware\n  - Instruction Set Architecture\n  - Linux Foundation\n  - Open Hardware\n  - Open Source\n  - Processor\n  - RISC-V\n  - Simulator\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/risc-v/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ risc-v:isa-specifications\n    name: RISC-V ISA Specifications\n    description: >-\n      The canonical RISC-V Instruction Set Architecture specifications\n      including the Unprivileged ISA (RV32I/RV64I base integer instructions)\n      and Privileged Architecture specification. Freely available as ratified\n      standards with a machine-readable database in the riscv-unified-db repo.\n    humanURL: https://riscv.org/technical/specifications/\n    tags:\n      - Instruction Set Architecture\n      - Privileged Architecture\n      - RISC-V\n      - Specifications\n    properties:\n      - type: Documentation\n        url: https://riscv.org/technical/specifications/\n      - type: GithubRepository\n        url: https://github.com/riscv/riscv-isa-manual\n      - type: GithubRepository\n        url: https://github.com/riscv/riscv-unified-db\n  - aid: risc-v:c-api-documentation\n    name: RISC-V C API Documentation\n    description: >-\n      Documentation of the RISC-V C API including\
  \ calling conventions,\n      ABI specifications, compiler intrinsics, and architectural extension\n      interfaces for C/C++ development targeting RISC-V processors.\n    humanURL: https://github.com/riscv-non-isa/riscv-c-api-doc\n    tags:\n      - ABI\n      - C API\n      - Compiler\n      - RISC-V\n    properties:\n      - type: GithubRepository\n        url: https://github.com/riscv-non-isa/riscv-c-api-doc\n  - aid: risc-v:non-isa-specifications\n    name: RISC-V Non-ISA Specifications\n    description: >-\n      Supporting technical standards that do not add new instructions or\n      modify the RISC-V ISA but help develop the ecosystem, including\n      platform specifications, debug specifications, trace specifications,\n      and interface standards.\n    humanURL: https://github.com/riscv-non-isa\n    tags:\n      - Debug\n      - Non-ISA\n      - Platform\n      - RISC-V\n      - Trace\n    properties:\n      - type: GithubOrg\n        url: https://github.com/riscv-non-isa\n\
  \  - aid: risc-v:spike-simulator\n    name: RISC-V Spike ISA Simulator\n    description: >-\n      Spike is the official RISC-V ISA Simulator and the golden reference\n      implementation for RISC-V. It simulates the execution of RISC-V\n      programs and is used for architecture validation and software development.\n    humanURL: https://github.com/riscv-software-src/riscv-isa-sim\n    tags:\n      - Reference Implementation\n      - RISC-V\n      - Simulator\n      - Testing\n    properties:\n      - type: GithubRepository\n        url: https://github.com/riscv-software-src/riscv-isa-sim\n  - aid: risc-v:opensbi\n    name: RISC-V OpenSBI\n    description: >-\n      OpenSBI is the official open-source implementation of the RISC-V\n      Supervisor Binary Interface (SBI) specification. It provides a\n      firmware execution environment for M-mode privileged operations\n      and serves as the primary boot firmware for RISC-V Linux systems.\n    humanURL: https://github.com/riscv-software-src/opensbi\n\
  \    tags:\n      - Firmware\n      - Linux\n      - RISC-V\n      - SBI\n    properties:\n      - type: GithubRepository\n        url: https://github.com/riscv-software-src/opensbi\ncommon:\n  - type: Website\n    url: https://riscv.org/\n  - type: Documentation\n    url: https://riscv.org/technical/specifications/\n  - type: GithubOrg\n    url: https://github.com/riscv\n  - type: GithubOrg\n    url: https://github.com/riscv-non-isa\n  - type: GithubOrg\n    url: https://github.com/riscv-software-src\n  - type: Wiki\n    url: https://wiki.riscv.org/\n  - type: MemberPortal\n    url: https://members.riscv.org/\n  - type: PrivacyPolicy\n    url: https://riscv.org/privacy-policy/\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/risc-v/refs/heads/main/json-schema/risc-v-specification-schema.json\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/risc-v/refs/heads/main/json-ld/risc-v-context.jsonld\n  - type: Vocabulary\n   \
  \ url: https://raw.githubusercontent.com/api-evangelist/risc-v/refs/heads/main/vocabulary/risc-v-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/risc-v/refs/heads/main/apis.yml
tags:
- C API
- Compiler
- Hardware
- Instruction Set Architecture
- Linux Foundation
- Open Hardware
- Open Source
- Processor
- RISC-V
- Simulator
url: https://raw.githubusercontent.com/api-evangelist/risc-v/refs/heads/main/apis.yml
use_cases: []
---
