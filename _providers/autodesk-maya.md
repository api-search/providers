---
api_count: 5
apis:
- description: 'Python API for scripting and extending Maya functionality, providing access to Maya''s scene graph and node architecture. Includes Python API 2.0 with a more Pythonic workflow and improved performance '
  name: Maya Python API
  slug: maya-python-api
- description: C++ API providing low-level access to Maya's core functionality for creating plugins, custom nodes, and high-performance tools. The API is organized into functional libraries including OpenMaya, OpenM
  name: Maya C++ API
  slug: maya-cpp-api
- description: Maya Embedded Language (MEL) scripting interface for automating tasks and customizing Maya workflows. MEL provides direct access to Maya commands and is the foundation of Maya's scripting capabilities
  name: Maya Commands (MEL)
  slug: maya-mel-commands
- description: Universal Scene Description (USD) integration for Maya, enabling exchange of 3D content between applications. Provides tools for importing, exporting, and working with USD stages and layers within May
  name: Maya USD API
  slug: maya-usd-api
- description: Bifrost is Maya's visual programming environment for creating simulation and procedural effects. It provides a node-based graph editor for building complex effects including fluids, particles, destruc
  name: Maya Bifrost API
  slug: maya-bifrost-api
common:
- title: ''
  type: Portal
  url: https://www.autodesk.com/developer-network/platform-technologies/maya
- title: ''
  type: Documentation
  url: https://help.autodesk.com/view/MAYADEV/2026/ENU/
- title: ''
  type: Support
  url: https://forums.autodesk.com/t5/maya-programming/bd-p/area-c-maya-programming
- title: ''
  type: Blog
  url: https://www.autodesk.com/blogs/maya/
- title: ''
  type: Tutorials
  url: https://tutorials.autodesk.io/
- title: ''
  type: ReleaseNotes
  url: https://help.autodesk.com/view/MAYAUL/2026/ENU/?guid=MAYA_RELEASENOTES_2026_RELEASE_NOTES_HTML
- title: ''
  type: TermsOfService
  url: https://www.autodesk.com/company/legal-notices-trademarks/terms-of-service-autodesk360-web-services
- title: ''
  type: GitHubOrganization
  url: https://github.com/autodesk-platform-services
created: '2025-01-01'
description: Autodesk Maya is a comprehensive 3D computer graphics application used for creating interactive 3D applications including video games, animated films, TV series, and visual effects. Maya provides multiple programming APIs including a Python API, C++ plugin API, MEL scripting language, USD integration, and Bifrost visual programming environment for extending and automating Maya workflows and creating custom tools and plugins.
features:
- description: Modern Pythonic API with improved performance and a cleaner interface for accessing Maya's node architecture and scene graph via maya.api.OpenMaya.
  name: Python API 2.0
- description: Low-level C++ API for high-performance plugin development with access to Maya's full internal architecture through OpenMaya functional libraries.
  name: C++ Plugin SDK
- description: Maya Embedded Language for command-line scripting, UI automation, and batch processing of Maya scenes and assets.
  name: MEL Scripting
- description: Universal Scene Description support for importing, exporting, and working with USD assets within Maya for cross-application 3D content pipelines.
  name: USD Integration
- description: Node-based visual programming environment for creating procedural effects, simulations, and custom workflows without traditional coding.
  name: Bifrost Visual Programming
- description: Create custom dependency graph nodes, deformers, and shape nodes that integrate natively into Maya's scene graph and evaluation system.
  name: Custom Node Development
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration with Arnold renderer via the MtoA (Maya to Arnold) plugin for photorealistic rendering of Maya scenes.
  name: Autodesk Arnold
- description: USD-based pipeline integration with Unreal Engine for game asset export and visualization workflows.
  name: Unreal Engine
- description: Integration with Autodesk ShotGrid for production tracking, asset management, and review workflows in film and TV production.
  name: ShotGrid (Flow Production Tracking)
- description: Interoperability with SideFX Houdini via USD and Alembic for visual effects simulation and procedural content pipelines.
  name: Houdini
layout: provider
modified: '2026-04-19'
name: Autodesk Maya
skills: []
slug: autodesk-maya
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: autodesk-maya\nname: Autodesk Maya\ndescription: >-\n  Autodesk Maya is a comprehensive 3D computer graphics application used for\n  creating interactive 3D applications including video games, animated films,\n  TV series, and visual effects. Maya provides multiple programming APIs\n  including a Python API, C++ plugin API, MEL scripting language, USD\n  integration, and Bifrost visual programming environment for extending and\n  automating Maya workflows and creating custom tools and plugins.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - 3D Graphics\n  - Animation\n  - Game Development\n  - Modeling\n  - Rendering\n  - Visual Effects\n  - VFX\n  - CAD\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/autodesk-maya/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: autodesk-maya:maya-python-api\n    name: Maya Python API\n    description:\
  \ >-\n      Python API for scripting and extending Maya functionality, providing access\n      to Maya's scene graph and node architecture. Includes Python API 2.0 with a\n      more Pythonic workflow and improved performance via maya.api.OpenMaya, as\n      well as Python API 1.0 via maya.OpenMaya and the maya.cmds wrapper for MEL\n      commands.\n    humanURL: https://help.autodesk.com/view/MAYAUL/2026/ENU/\n    baseURL: https://localhost\n    tags:\n      - Automation\n      - Python\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=Maya_SDK_MERGED_Maya_Python_API_Maya_Python_API_2_0_html\n      - type: APIReference\n        url: https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=Maya_SDK_py_ref_index_html\n      - type: GettingStarted\n        url: https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=Maya_SDK_MERGED_Maya_Python_API_Python_API_2_0_Quick_Start_html\n\n  - aid: autodesk-maya:maya-cpp-api\n\
  \    name: Maya C++ API\n    description: >-\n      C++ API providing low-level access to Maya's core functionality for\n      creating plugins, custom nodes, and high-performance tools. The API is\n      organized into functional libraries including OpenMaya, OpenMayaUI,\n      OpenMayaAnim, OpenMayaFX, and OpenMayaRender.\n    humanURL: https://help.autodesk.com/view/MAYAUL/2026/ENU/\n    baseURL: https://localhost\n    tags:\n      - C++\n      - Native\n      - Performance\n      - Plugins\n    properties:\n      - type: Documentation\n        url: https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=Maya_SDK_MERGED_cpp_ref_index_html\n      - type: APIReference\n        url: https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=Maya_SDK_cpp_ref_index_html\n      - type: GettingStarted\n        url: https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=Maya_SDK_MERGED_Maya_SDK_Maya_SDK_html\n\n  - aid: autodesk-maya:maya-mel-commands\n    name: Maya Commands (MEL)\n    description: >-\n\
  \      Maya Embedded Language (MEL) scripting interface for automating tasks and\n      customizing Maya workflows. MEL provides direct access to Maya commands\n      and is the foundation of Maya's scripting capabilities.\n    humanURL: https://help.autodesk.com/view/MAYAUL/2026/ENU/\n    baseURL: https://localhost\n    tags:\n      - Automation\n      - Commands\n      - MEL\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=__CommandsPython_index_html\n      - type: APIReference\n        url: https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=__Commands_index_html\n\n  - aid: autodesk-maya:maya-usd-api\n    name: Maya USD API\n    description: >-\n      Universal Scene Description (USD) integration for Maya, enabling exchange\n      of 3D content between applications. Provides tools for importing, exporting,\n      and working with USD stages and layers within Maya.\n    humanURL: https://help.autodesk.com/view/MAYAUL/2026/ENU/\n\
  \    baseURL: https://localhost\n    tags:\n      - Interchange\n      - Pipeline\n      - Scene Description\n      - USD\n    properties:\n      - type: Documentation\n        url: https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=GUID-C7DB6AF9-653E-4B49-93D6-F9C2D0865B85\n      - type: GitHubRepository\n        url: https://github.com/Autodesk/maya-usd\n\n  - aid: autodesk-maya:maya-bifrost-api\n    name: Maya Bifrost API\n    description: >-\n      Bifrost is Maya's visual programming environment for creating simulation\n      and procedural effects. It provides a node-based graph editor for building\n      complex effects including fluids, particles, destruction, and procedural\n      geometry, with SDK support for custom node development.\n    humanURL: https://help.autodesk.com/view/MAYAUL/2026/ENU/?guid=GUID-1223AA4F-1CD7-473C-87EA-C16C6B28F7FD\n    baseURL: https://localhost\n    tags:\n      - Bifrost\n      - Particles\n      - Procedural Effects\n      - Simulation\n    \
  \  - Visual Programming\n    properties:\n      - type: Documentation\n        url: https://help.autodesk.com/view/MAYAUL/2026/ENU/?guid=Bifrost_MayaPlugin_bifrost_for_maya_html\n      - type: GitHubRepository\n        url: https://github.com/Autodesk/bifrost-usd\n\ncommon:\n  - type: Portal\n    url: https://www.autodesk.com/developer-network/platform-technologies/maya\n  - type: Documentation\n    url: https://help.autodesk.com/view/MAYADEV/2026/ENU/\n  - type: Support\n    url: https://forums.autodesk.com/t5/maya-programming/bd-p/area-c-maya-programming\n  - type: Blog\n    url: https://www.autodesk.com/blogs/maya/\n  - type: Tutorials\n    url: https://tutorials.autodesk.io/\n  - type: ReleaseNotes\n    url: https://help.autodesk.com/view/MAYAUL/2026/ENU/?guid=MAYA_RELEASENOTES_2026_RELEASE_NOTES_HTML\n  - type: TermsOfService\n    url: https://www.autodesk.com/company/legal-notices-trademarks/terms-of-service-autodesk360-web-services\n  - type: GitHubOrganization\n    url: https://github.com/autodesk-platform-services\n\
  \  - type: Features\n    data:\n      - name: Python API 2.0\n        description: >-\n          Modern Pythonic API with improved performance and a cleaner interface for\n          accessing Maya's node architecture and scene graph via maya.api.OpenMaya.\n      - name: C++ Plugin SDK\n        description: >-\n          Low-level C++ API for high-performance plugin development with access to\n          Maya's full internal architecture through OpenMaya functional libraries.\n      - name: MEL Scripting\n        description: >-\n          Maya Embedded Language for command-line scripting, UI automation, and\n          batch processing of Maya scenes and assets.\n      - name: USD Integration\n        description: >-\n          Universal Scene Description support for importing, exporting, and working\n          with USD assets within Maya for cross-application 3D content pipelines.\n      - name: Bifrost Visual Programming\n        description: >-\n          Node-based visual programming\
  \ environment for creating procedural effects,\n          simulations, and custom workflows without traditional coding.\n      - name: Custom Node Development\n        description: >-\n          Create custom dependency graph nodes, deformers, and shape nodes that\n          integrate natively into Maya's scene graph and evaluation system.\n  - type: UseCases\n    data:\n      - name: VFX Pipeline Integration\n        description: >-\n          Integrating Maya into visual effects production pipelines with custom\n          tools, asset management systems, and render farm automation.\n      - name: Game Asset Automation\n        description: >-\n          Automating game asset creation, optimization, and export workflows for\n          game engines like Unreal Engine and Unity through Maya scripting.\n      - name: Animation Workflow Tools\n        description: >-\n          Building custom rigging systems, animation controls, and workflow tools\n          to accelerate character animation\
  \ production for film and TV.\n      - name: Procedural Content Generation\n        description: >-\n          Using Bifrost and Python APIs to generate procedural geometry, textures,\n          and scene content for games, visualization, and architectural projects.\n      - name: DCC Pipeline Development\n        description: >-\n          Developing studio pipeline tools that automate scene assembly, asset\n          tracking, and data interchange between Maya and other DCC applications.\n  - type: Integrations\n    data:\n      - name: Autodesk Arnold\n        description: >-\n          Integration with Arnold renderer via the MtoA (Maya to Arnold) plugin\n          for photorealistic rendering of Maya scenes.\n      - name: Unreal Engine\n        description: >-\n          USD-based pipeline integration with Unreal Engine for game asset export\n          and visualization workflows.\n      - name: ShotGrid (Flow Production Tracking)\n        description: >-\n          Integration with\
  \ Autodesk ShotGrid for production tracking, asset\n          management, and review workflows in film and TV production.\n      - name: Houdini\n        description: >-\n          Interoperability with SideFX Houdini via USD and Alembic for visual\n          effects simulation and procedural content pipelines.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/autodesk-maya/refs/heads/main/apis.yml
tags:
- 3D Graphics
- Animation
- Game Development
- Modeling
- Rendering
- Visual Effects
- VFX
- CAD
url: https://raw.githubusercontent.com/api-evangelist/autodesk-maya/refs/heads/main/apis.yml
use_cases:
- description: Integrating Maya into visual effects production pipelines with custom tools, asset management systems, and render farm automation.
  name: VFX Pipeline Integration
- description: Automating game asset creation, optimization, and export workflows for game engines like Unreal Engine and Unity through Maya scripting.
  name: Game Asset Automation
- description: Building custom rigging systems, animation controls, and workflow tools to accelerate character animation production for film and TV.
  name: Animation Workflow Tools
- description: Using Bifrost and Python APIs to generate procedural geometry, textures, and scene content for games, visualization, and architectural projects.
  name: Procedural Content Generation
- description: Developing studio pipeline tools that automate scene assembly, asset tracking, and data interchange between Maya and other DCC applications.
  name: DCC Pipeline Development
---
