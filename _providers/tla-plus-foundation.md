---
api_count: 6
apis:
- description: TLC is the primary model checker for specifications written in TLA+. It can be run from the command line using tla2tools.jar or consumed as a Java dependency via Maven from central.sonatype.org. Requi
  name: TLC Model Checker
  slug: tlc-model-checker
- description: The TLA+ Proof Manager (TLAPS) is a proof system for TLA+ specifications, enabling formal mathematical proofs of system properties. It integrates with back-end provers and supports interactive proof d
  name: TLAPS Proof System
  slug: tlaps-proof-system
- description: The TLA+ Toolbox is a full-featured IDE for writing TLA+ specifications, running TLC model checks, and managing proofs with TLAPS. Available as a standalone Eclipse-based application.
  name: TLA+ Toolbox IDE
  slug: tla-toolbox-ide
- description: The official TLA+ extension for Visual Studio Code providing language support, syntax highlighting, TLC integration, and model checking from within the VS Code editor.
  name: TLA+ VS Code Extension
  slug: vscode-tlaplus
- description: A curated collection of TLA+ snippets, operators, and modules contributed by the TLA+ community, providing reusable formal specification components for common patterns in concurrent and distributed sy
  name: TLA+ Community Modules
  slug: community-modules
- description: A collection of TLA+ specifications of varying complexity covering distributed algorithms, consensus protocols, concurrent data structures, and system models. Includes reference implementations for le
  name: TLA+ Specification Examples
  slug: tlaplus-examples
common:
- title: ''
  type: Website
  url: https://foundation.tlapl.us/
- title: ''
  type: Documentation
  url: https://lamport.azurewebsites.net/tla/tla.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/tlaplus
- title: ''
  type: Support
  url: mailto:support@tlapl.us
created: '2026-03-16'
description: The TLA+ Foundation is an independent nonprofit hosted by the Linux Foundation, dedicated to fostering the adoption of the TLA+ specification language in industry, academia, and education. Created by Leslie Lamport, TLA+ is a high-level formal specification language based on set theory and temporal logic for modeling concurrent and distributed systems. Inaugural members include Amazon Web Services (AWS) and Oracle. The Foundation funds research and development, maintains the TLC model checker, TLAPS proof system, and TLA+ Toolbox IDE, and coordinates community resources including the VS Code extension, CommunityModules, and formal verification examples. The current stable release is v1.7.4 (The Xenophanes release).
features:
- description: Explicit-state model checker for TLA+ specifications supporting both exhaustive verification and simulation modes.
  name: TLC Model Checker
- description: Interactive proof manager for formally verifying TLA+ specifications against mathematical proofs.
  name: TLAPS Proof System
- description: Eclipse-based IDE for writing, model-checking, and managing TLA+ specifications with TLAPS integration.
  name: TLA+ Toolbox IDE
- description: Official Visual Studio Code extension providing TLA+ language support and TLC integration.
  name: VS Code Extension
- description: Reusable TLA+ operator and module library contributed and maintained by the community.
  name: Community Modules
- description: Foundation grants funding research and industry initiatives to advance TLA+ specification and tool adoption.
  name: Grant Program
- description: TLA+ tools available as Maven Java dependency from central.sonatype.org for programmatic integration.
  name: Maven Package Distribution
- description: Python interpreter for executing TLA+ specifications, enabling Python-based formal modeling workflows.
  name: PlusPy Python Interpreter
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Founding member; AWS uses TLA+ for distributed systems design including DynamoDB and S3 protocols.
  name: Amazon Web Services
- description: Founding member; uses TLA+ for database and distributed system specification.
  name: Oracle
- description: Early TLA+ adopter for Azure and distributed systems formal verification.
  name: Microsoft
- description: Official VS Code extension for TLA+ editing and model checking.
  name: Visual Studio Code
- description: TLA+ tools distributed as Java Maven dependency for programmatic integration.
  name: Maven Central
- description: Parent organization hosting the TLA+ Foundation as an independent nonprofit project.
  name: Linux Foundation
layout: provider
modified: '2026-05-03'
name: TLA Plus Foundation
skills: []
slug: tla-plus-foundation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tla-plus-foundation\nname: TLA Plus Foundation\ndescription: >-\n  The TLA+ Foundation is an independent nonprofit hosted by the Linux Foundation,\n  dedicated to fostering the adoption of the TLA+ specification language in industry,\n  academia, and education. Created by Leslie Lamport, TLA+ is a high-level formal\n  specification language based on set theory and temporal logic for modeling concurrent\n  and distributed systems. Inaugural members include Amazon Web Services (AWS) and\n  Oracle. The Foundation funds research and development, maintains the TLC model\n  checker, TLAPS proof system, and TLA+ Toolbox IDE, and coordinates community\n  resources including the VS Code extension, CommunityModules, and formal verification\n  examples. The current stable release is v1.7.4 (The Xenophanes release).\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Formal Methods\n  -\
  \ Linux Foundation\n  - Specifications\n  - Verification\n  - Distributed Systems\n  - Concurrency\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tla-plus-foundation/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: tla-plus-foundation:tlc-model-checker\n    name: TLC Model Checker\n    description: >-\n      TLC is the primary model checker for specifications written in TLA+. It\n      can be run from the command line using tla2tools.jar or consumed as a Java\n      dependency via Maven from central.sonatype.org. Requires Java 11+. The\n      current stable release is v1.7.4 (The Xenophanes release) with pre-release\n      v1.8.0 (The Clarke release) available.\n    humanURL: https://github.com/tlaplus/tlaplus\n    tags:\n      - Model Checking\n      - Formal Verification\n      - Java\n    properties:\n      - type: Documentation\n        url: https://tla.msr-inria.inria.fr/tlatoolbox/doc/model/executing-tlc.html\n\
  \      - type: GitHubRepository\n        url: https://github.com/tlaplus/tlaplus\n\n  - aid: tla-plus-foundation:tlaps-proof-system\n    name: TLAPS Proof System\n    description: >-\n      The TLA+ Proof Manager (TLAPS) is a proof system for TLA+ specifications,\n      enabling formal mathematical proofs of system properties. It integrates\n      with back-end provers and supports interactive proof development.\n    humanURL: https://tla.msr-inria.inria.fr/tlaps/\n    tags:\n      - Proof System\n      - Formal Verification\n      - Mathematics\n    properties:\n      - type: Documentation\n        url: https://tla.msr-inria.inria.fr/tlaps/\n      - type: GitHubRepository\n        url: https://github.com/tlaplus/tlapm\n\n  - aid: tla-plus-foundation:tla-toolbox-ide\n    name: TLA+ Toolbox IDE\n    description: >-\n      The TLA+ Toolbox is a full-featured IDE for writing TLA+ specifications,\n      running TLC model checks, and managing proofs with TLAPS. Available as a\n      standalone\
  \ Eclipse-based application.\n    humanURL: https://github.com/tlaplus/tlaplus\n    tags:\n      - IDE\n      - Tooling\n      - Development\n    properties:\n      - type: Documentation\n        url: https://tla.msr-inria.inria.fr/tlatoolbox/doc/\n      - type: GitHubRepository\n        url: https://github.com/tlaplus/tlaplus\n\n  - aid: tla-plus-foundation:vscode-tlaplus\n    name: TLA+ VS Code Extension\n    description: >-\n      The official TLA+ extension for Visual Studio Code providing language\n      support, syntax highlighting, TLC integration, and model checking from\n      within the VS Code editor.\n    humanURL: https://marketplace.visualstudio.com/items?itemName=alygin.vscode-tlaplus\n    tags:\n      - IDE\n      - VS Code\n      - Tooling\n    properties:\n      - type: Documentation\n        url: https://github.com/tlaplus/vscode-tlaplus\n      - type: GitHubRepository\n        url: https://github.com/tlaplus/vscode-tlaplus\n\n  - aid: tla-plus-foundation:community-modules\n\
  \    name: TLA+ Community Modules\n    description: >-\n      A curated collection of TLA+ snippets, operators, and modules contributed\n      by the TLA+ community, providing reusable formal specification components\n      for common patterns in concurrent and distributed systems.\n    humanURL: https://github.com/tlaplus/CommunityModules\n    tags:\n      - Community\n      - Modules\n      - Specifications\n    properties:\n      - type: Documentation\n        url: https://github.com/tlaplus/CommunityModules\n      - type: GitHubRepository\n        url: https://github.com/tlaplus/CommunityModules\n\n  - aid: tla-plus-foundation:tlaplus-examples\n    name: TLA+ Specification Examples\n    description: >-\n      A collection of TLA+ specifications of varying complexity covering\n      distributed algorithms, consensus protocols, concurrent data structures,\n      and system models. Includes reference implementations for learning and validation.\n    humanURL: https://github.com/tlaplus/Examples\n\
  \    tags:\n      - Examples\n      - Specifications\n      - Learning\n    properties:\n      - type: Documentation\n        url: https://github.com/tlaplus/Examples\n      - type: GitHubRepository\n        url: https://github.com/tlaplus/Examples\n\ncommon:\n  - type: Website\n    url: https://foundation.tlapl.us/\n  - type: Documentation\n    url: https://lamport.azurewebsites.net/tla/tla.html\n  - type: GitHubOrganization\n    url: https://github.com/tlaplus\n  - type: Support\n    url: mailto:support@tlapl.us\n  - type: Features\n    data:\n      - name: TLC Model Checker\n        description: Explicit-state model checker for TLA+ specifications supporting both exhaustive verification and simulation modes.\n      - name: TLAPS Proof System\n        description: Interactive proof manager for formally verifying TLA+ specifications against mathematical proofs.\n      - name: TLA+ Toolbox IDE\n        description: Eclipse-based IDE for writing, model-checking, and managing TLA+ specifications\
  \ with TLAPS integration.\n      - name: VS Code Extension\n        description: Official Visual Studio Code extension providing TLA+ language support and TLC integration.\n      - name: Community Modules\n        description: Reusable TLA+ operator and module library contributed and maintained by the community.\n      - name: Grant Program\n        description: Foundation grants funding research and industry initiatives to advance TLA+ specification and tool adoption.\n      - name: Maven Package Distribution\n        description: TLA+ tools available as Maven Java dependency from central.sonatype.org for programmatic integration.\n      - name: PlusPy Python Interpreter\n        description: Python interpreter for executing TLA+ specifications, enabling Python-based formal modeling workflows.\n  - type: UseCases\n    data:\n      - name: Distributed Algorithm Verification\n        description: Model-check distributed consensus, replication, and coordination protocols against safety and\
  \ liveness properties.\n      - name: Concurrent System Specification\n        description: Formally specify concurrent data structures, lock-free algorithms, and parallel systems using TLA+.\n      - name: Protocol Design and Validation\n        description: Use TLA+ to design and validate network protocols, database transactions, and API contracts before implementation.\n      - name: Tooling Integration via Java API\n        description: Embed TLC model checking in CI/CD pipelines or custom tools using the tla2tools Maven dependency.\n      - name: Education and Training\n        description: Use the TLA+ Toolbox, VS Code extension, and Leslie Lamport's video course to learn formal methods.\n      - name: Safety and Liveness Proof\n        description: Use TLAPS to produce machine-checked proofs of safety and liveness properties for critical systems.\n  - type: Integrations\n    data:\n      - name: Amazon Web Services\n        description: Founding member; AWS uses TLA+ for distributed\
  \ systems design including DynamoDB and S3 protocols.\n      - name: Oracle\n        description: Founding member; uses TLA+ for database and distributed system specification.\n      - name: Microsoft\n        description: Early TLA+ adopter for Azure and distributed systems formal verification.\n      - name: Visual Studio Code\n        description: Official VS Code extension for TLA+ editing and model checking.\n      - name: Maven Central\n        description: TLA+ tools distributed as Java Maven dependency for programmatic integration.\n      - name: Linux Foundation\n        description: Parent organization hosting the TLA+ Foundation as an independent nonprofit project.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tla-plus-foundation/refs/heads/main/apis.yml
tags:
- Formal Methods
- Linux Foundation
- Specifications
- Verification
- Distributed Systems
- Concurrency
url: https://raw.githubusercontent.com/api-evangelist/tla-plus-foundation/refs/heads/main/apis.yml
use_cases:
- description: Model-check distributed consensus, replication, and coordination protocols against safety and liveness properties.
  name: Distributed Algorithm Verification
- description: Formally specify concurrent data structures, lock-free algorithms, and parallel systems using TLA+.
  name: Concurrent System Specification
- description: Use TLA+ to design and validate network protocols, database transactions, and API contracts before implementation.
  name: Protocol Design and Validation
- description: Embed TLC model checking in CI/CD pipelines or custom tools using the tla2tools Maven dependency.
  name: Tooling Integration via Java API
- description: Use the TLA+ Toolbox, VS Code extension, and Leslie Lamport's video course to learn formal methods.
  name: Education and Training
- description: Use TLAPS to produce machine-checked proofs of safety and liveness properties for critical systems.
  name: Safety and Liveness Proof
---
