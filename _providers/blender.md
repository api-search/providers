---
api_count: 2
apis:
- description: The Blender Python API (bpy) provides Python access to Blender's internal data, operators, and UI components. It enables developers to automate tasks, create addons, build custom tools, manipulate sce
  name: Blender Python API
  slug: blender-python-api
- description: The Blender Extensions Platform (extensions.blender.org) provides a curated repository of addons, themes, and node presets for Blender. The platform supports structured addon packaging, versioning, an
  name: Blender Extensions Platform
  slug: blender-extensions
capabilities:
- description: ''
  name: Blender Python Api
  slug: blender-python-api
common:
- title: ''
  type: Website
  url: https://www.blender.org/
- title: ''
  type: Documentation
  url: https://docs.blender.org/
- title: ''
  type: GettingStarted
  url: https://docs.blender.org/api/current/info_quickstart.html
- title: ''
  type: Community
  url: https://www.blender.org/community/
- title: ''
  type: Support
  url: https://www.blender.org/support/
- title: ''
  type: GitHubOrganization
  url: https://github.com/blender
- title: ''
  type: GitHub
  url: https://github.com/blender/blender
- title: ''
  type: Blog
  url: https://www.blender.org/news/
- title: ''
  type: Training
  url: https://www.blender.org/training/
- title: ''
  type: FAQ
  url: https://www.blender.org/support/faq/
- title: ''
  type: ReleaseNotes
  url: https://developer.blender.org/docs/release_notes/
- title: GPL-2.0-or-later
  type: License
  url: https://www.blender.org/about/license/
- title: ''
  type: PackageRegistry
  url: https://extensions.blender.org
- title: ''
  type: SpectralRules
  url: rules/blender-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/blender-python-api.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/blender-vocabulary.yaml
created: '2024-01-01'
description: Blender is the free and open source 3D creation suite supporting the entirety of the 3D pipeline including modeling, rigging, animation, simulation, rendering, compositing, motion tracking, video editing, and game creation. Blender's Python API provides extensive scripting capabilities for automation, tool development, and addon creation, enabling developers to extend Blender with custom functionality. The project is governed by the Blender Foundation and maintained at blender.org.
features:
- description: The bpy module provides access to Blender's internal data model, allowing Python scripts to create, read, update, and delete scene objects, materials, animations, constraints, and render settings.
  name: Python Scripting (bpy)
- description: Blender's operator system allows Python developers to create custom operators (commands) accessible from menus, panels, keyboard shortcuts, and scripts.
  name: Operator Framework
- description: Blender addons are Python packages extending functionality across modeling, rigging, animation, rendering, import/export, and UI. Distributed via the Extensions Platform or bundled directly.
  name: Addon Development
- description: Geometry Nodes and Shader Nodes provide visual programming for procedural modeling and materials, scriptable via the Python API.
  name: Node Groups and Geometry Nodes
- description: Python API integrates with Blender's Cycles and EEVEE render engines for batch rendering, render farm integration, and custom render pipeline control.
  name: Render Pipeline Integration
- description: Blender can be invoked headlessly via CLI for batch rendering, script execution, and pipeline automation without a GUI.
  name: Command-Line Interface
- description: Blender 3.x+ includes an asset library system with Python API support for managing and accessing reusable 3D assets across projects.
  name: Asset Library System
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Blender's built-in path-tracing render engine with Python API access for controlling render settings, passes, and denoising.
  name: Cycles X Render Engine
- description: Blender supports import and export of Pixar USD scenes, enabling pipeline integration with VFX and game development workflows.
  name: USD (Universal Scene Description)
- description: Blender has built-in glTF 2.0 import/export support with Python API access, enabling web, AR/VR, and game engine pipelines.
  name: glTF 2.0
- description: Blender supports OpenVDB for volumetric simulation and rendering, with Python API access to volume data and simulation parameters.
  name: OpenVDB
- description: Blender integrates with OpenColorIO for ACES and professional color pipeline support in VFX productions.
  name: ACES Color Management
jsonld:
- class_count: 11
  name: Blender Context
  property_count: 0
  slug: blender-context
layout: provider
modified: '2026-04-21'
name: Blender
rules:
- name: Blender API Rules
  rule_count: 5
  severity_counts:
    error: 0
    hint: 0
    info: 0
    warn: 5
  slug: blender-spectral-rules
skills: []
slug: blender
solutions: []
source_filename: apis.yml
source_yaml: "aid: blender\nname: Blender\ndescription: >-\n  Blender is the free and open source 3D creation suite supporting the entirety\n  of the 3D pipeline including modeling, rigging, animation, simulation, rendering,\n  compositing, motion tracking, video editing, and game creation. Blender's Python\n  API provides extensive scripting capabilities for automation, tool development, and\n  addon creation, enabling developers to extend Blender with custom functionality.\n  The project is governed by the Blender Foundation and maintained at blender.org.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - 3D\n  - Animation\n  - Game Development\n  - Modeling\n  - Open Source\n  - Python\n  - Rendering\n  - VFX\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/blender/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\napis:\n  - aid: blender:blender-python-api\n    name:\
  \ Blender Python API\n    description: >-\n      The Blender Python API (bpy) provides Python access to Blender's internal data,\n      operators, and UI components. It enables developers to automate tasks, create\n      addons, build custom tools, manipulate scene data, interact with the render\n      pipeline, and extend Blender's interface. The API is embedded within Blender\n      and does not expose HTTP endpoints; it is invoked via Blender's built-in Python\n      interpreter or through command-line batch rendering.\n    humanURL: https://docs.blender.org/api/current/\n    tags:\n      - Addons\n      - Automation\n      - Open Source\n      - Python\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://docs.blender.org/api/current/\n      - type: GitHub\n        url: https://github.com/blender/blender\n      - type: GettingStarted\n        url: https://docs.blender.org/api/current/info_quickstart.html\n      - type: Tutorials\n        url: https://docs.blender.org/api/current/info_tips_and_tricks.html\n\
  \      - type: JSONSchema\n        url: json-schema/blender-addon-manifest-schema.json\n      - type: JSONSchema\n        url: json-schema/blender-bpy-operator-schema.json\n      - type: JSONStructure\n        url: json-structure/blender-addon-manifest-structure.json\n      - type: JSONStructure\n        url: json-structure/blender-bpy-operator-structure.json\n      - type: JSONLD\n        url: json-ld/blender-context.jsonld\n      - type: Example\n        url: examples/blender-addon-manifest-example.json\n      - type: Example\n        url: examples/blender-bpy-operator-example.json\n  - aid: blender:blender-extensions\n    name: Blender Extensions Platform\n    description: >-\n      The Blender Extensions Platform (extensions.blender.org) provides a curated\n      repository of addons, themes, and node presets for Blender. The platform\n      supports structured addon packaging, versioning, and distribution. Developers\n      can publish addons with metadata via the extensions.blender.org\
  \ manifest format.\n    humanURL: https://extensions.blender.org\n    tags:\n      - Addons\n      - Extensions\n      - Marketplace\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://docs.blender.org/manual/en/latest/extensions/index.html\n      - type: Portal\n        url: https://extensions.blender.org\ncommon:\n  - type: Website\n    url: https://www.blender.org/\n  - type: Documentation\n    url: https://docs.blender.org/\n  - type: GettingStarted\n    url: https://docs.blender.org/api/current/info_quickstart.html\n  - type: Community\n    url: https://www.blender.org/community/\n  - type: Support\n    url: https://www.blender.org/support/\n  - type: GitHubOrganization\n    url: https://github.com/blender\n  - type: GitHub\n    url: https://github.com/blender/blender\n  - type: Blog\n    url: https://www.blender.org/news/\n  - type: Training\n    url: https://www.blender.org/training/\n  - type: FAQ\n    url: https://www.blender.org/support/faq/\n\
  \  - type: ReleaseNotes\n    url: https://developer.blender.org/docs/release_notes/\n  - type: License\n    url: https://www.blender.org/about/license/\n    title: GPL-2.0-or-later\n  - type: PackageRegistry\n    url: https://extensions.blender.org\n  - type: SpectralRules\n    url: rules/blender-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/blender-python-api.yaml\n  - type: Vocabulary\n    url: vocabulary/blender-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Python Scripting (bpy)\n        description: >-\n          The bpy module provides access to Blender's internal data model, allowing\n          Python scripts to create, read, update, and delete scene objects, materials,\n          animations, constraints, and render settings.\n      - name: Operator Framework\n        description: >-\n          Blender's operator system allows Python developers to create custom operators\n          (commands) accessible from menus, panels, keyboard shortcuts,\
  \ and scripts.\n      - name: Addon Development\n        description: >-\n          Blender addons are Python packages extending functionality across modeling,\n          rigging, animation, rendering, import/export, and UI. Distributed via the\n          Extensions Platform or bundled directly.\n      - name: Node Groups and Geometry Nodes\n        description: >-\n          Geometry Nodes and Shader Nodes provide visual programming for procedural\n          modeling and materials, scriptable via the Python API.\n      - name: Render Pipeline Integration\n        description: >-\n          Python API integrates with Blender's Cycles and EEVEE render engines for\n          batch rendering, render farm integration, and custom render pipeline control.\n      - name: Command-Line Interface\n        description: >-\n          Blender can be invoked headlessly via CLI for batch rendering, script\n          execution, and pipeline automation without a GUI.\n      - name: Asset Library System\n\
  \        description: >-\n          Blender 3.x+ includes an asset library system with Python API support for\n          managing and accessing reusable 3D assets across projects.\n  - type: UseCases\n    data:\n      - name: Pipeline Automation\n        description: >-\n          VFX and animation studios automate Blender production pipelines using\n          Python scripts for batch rendering, asset processing, and scene assembly.\n      - name: Addon Development\n        description: >-\n          Developers create custom tools and plugins extending Blender's functionality\n          for modeling, rigging, simulation, and export workflows.\n      - name: Headless Rendering\n        description: >-\n          Blender is used for headless server-side rendering via CLI and Python scripts\n          in cloud rendering pipelines and automated content generation workflows.\n      - name: Procedural Content Generation\n        description: >-\n          Python scripts and Geometry Nodes enable\
  \ procedural generation of 3D assets\n          for games, VFX, and architectural visualization.\n      - name: Education and Research\n        description: >-\n          Universities, research labs, and educators use Blender's Python API for\n          3D visualization, scientific rendering, and computer graphics research.\n  - type: Integrations\n    data:\n      - name: Cycles X Render Engine\n        description: >-\n          Blender's built-in path-tracing render engine with Python API access\n          for controlling render settings, passes, and denoising.\n      - name: USD (Universal Scene Description)\n        description: >-\n          Blender supports import and export of Pixar USD scenes, enabling\n          pipeline integration with VFX and game development workflows.\n      - name: glTF 2.0\n        description: >-\n          Blender has built-in glTF 2.0 import/export support with Python API\n          access, enabling web, AR/VR, and game engine pipelines.\n      - name:\
  \ OpenVDB\n        description: >-\n          Blender supports OpenVDB for volumetric simulation and rendering,\n          with Python API access to volume data and simulation parameters.\n      - name: ACES Color Management\n        description: >-\n          Blender integrates with OpenColorIO for ACES and professional color\n          pipeline support in VFX productions.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/blender/refs/heads/main/apis.yml
tags:
- 3D
- Animation
- Game Development
- Modeling
- Open Source
- Python
- Rendering
- VFX
url: https://raw.githubusercontent.com/api-evangelist/blender/refs/heads/main/apis.yml
use_cases:
- description: VFX and animation studios automate Blender production pipelines using Python scripts for batch rendering, asset processing, and scene assembly.
  name: Pipeline Automation
- description: Developers create custom tools and plugins extending Blender's functionality for modeling, rigging, simulation, and export workflows.
  name: Addon Development
- description: Blender is used for headless server-side rendering via CLI and Python scripts in cloud rendering pipelines and automated content generation workflows.
  name: Headless Rendering
- description: Python scripts and Geometry Nodes enable procedural generation of 3D assets for games, VFX, and architectural visualization.
  name: Procedural Content Generation
- description: Universities, research labs, and educators use Blender's Python API for 3D visualization, scientific rendering, and computer graphics research.
  name: Education and Research
---
