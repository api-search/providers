---
api_count: 2
apis:
- description: The OpenUSD C++ API is the primary interface for working with Universal Scene Description data. Provides access to USD core (scene composition and asset management), UsdImaging and Hydra (rendering in
  name: OpenUSD C++ API
  slug: ''
- description: OpenUSD provides comprehensive Python bindings for all major C++ modules, enabling scripting and pipeline integration in Python-based DCC workflows. Python bindings cover the full USD API including px
  name: OpenUSD Python Bindings
  slug: ''
common:
- title: ''
  type: Portal
  url: https://aousd.org
- title: ''
  type: Documentation
  url: https://openusd.org/release/index.html
- title: ''
  type: GettingStarted
  url: https://openusd.org/release/tut_usd_tutorials.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/PixarAnimationStudios
- title: ''
  type: GitHubRepository
  url: https://github.com/PixarAnimationStudios/OpenUSD
- title: USD Layer Schema
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/aousd/refs/heads/main/json-schema/aousd-usd-layer-schema.json
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/aousd/refs/heads/main/vocabulary/aousd-vocabulary.yaml
created: '2026-03-16'
description: The Alliance for OpenUSD (AOUSD) is a Linux Foundation project dedicated to promoting interoperability of 3D content through Universal Scene Description (OpenUSD). Founded by Pixar, Adobe, Apple, Autodesk, and NVIDIA, AOUSD standardizes 3D content ecosystems for film, gaming, architecture, industrial design, and the metaverse. OpenUSD provides a high-performance extensible software platform for collaboratively constructing animated 3D scenes with schemas for geometry, shading, lighting, physics, and volume rendering.
features:
- description: USD's composition arcs (references, payloads, variants, instancing, and specializes) enable non-destructive scene assembly from multiple asset layers with override workflows.
  name: Scene Composition
- description: OpenUSD's schema system allows studios and tool vendors to extend the core specification with domain-specific schemas for physics, simulation, characters, and environments.
  name: Schema-Driven Extensibility
- description: The Hydra rendering delegate architecture enables pluggable render backends including Storm (OpenGL), Arnold, RenderMan, and others.
  name: Hydra Rendering Architecture
- description: OpenUSD supports human-readable ASCII (.usda), binary (.usdb), and packaged archive (.usdz) file formats for different use cases.
  name: Multiple File Formats
- description: The ArResolver system enables customizable asset path resolution for integrating USD with studio asset management systems.
  name: Asset Resolution
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Import and export USD files via Autodesk's official USD plugins for Maya and 3ds Max, enabling OpenUSD-based pipelines.
  name: Autodesk Maya / 3ds Max
- description: Native USD integration in Houdini via LOPs (Layout Object Primitives) for creating and editing USD scenes and assets.
  name: SideFX Houdini
- description: Apple's spatial computing tools use .usdz as the primary format for augmented reality and visionOS content.
  name: Apple Reality Composer Pro
- description: NVIDIA Omniverse is built on OpenUSD, using it as the foundation for collaborative 3D design and industrial digital twin workflows.
  name: NVIDIA Omniverse
- description: RenderMan natively reads USD scenes, making it the primary production renderer for USD-based feature film pipelines.
  name: Pixar RenderMan
jsonld:
- class_count: 5
  name: Aousd Context
  property_count: 18
  slug: aousd-context
layout: provider
modified: '2026-04-19'
name: Alliance for OpenUSD
skills: []
slug: aousd
solutions: []
source_filename: apis.yml
source_yaml: "name: Alliance for OpenUSD\ndescription: >-\n  The Alliance for OpenUSD (AOUSD) is a Linux Foundation project dedicated to\n  promoting interoperability of 3D content through Universal Scene Description\n  (OpenUSD). Founded by Pixar, Adobe, Apple, Autodesk, and NVIDIA, AOUSD\n  standardizes 3D content ecosystems for film, gaming, architecture, industrial\n  design, and the metaverse. OpenUSD provides a high-performance extensible\n  software platform for collaboratively constructing animated 3D scenes with\n  schemas for geometry, shading, lighting, physics, and volume rendering.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - 3D\n  - Interoperability\n  - Linux Foundation\n  - Metaverse\n  - OpenUSD\n  - Specification\n  - Standards\n  - USD\n  - Visual Effects\ncreated: \"2026-03-16\"\nmodified: \"2026-04-19\"\nurl: https://raw.githubusercontent.com/api-evangelist/aousd/refs/heads/main/apis.yml\nspecificationVersion: '0.16'\n\
  apis:\n  - name: OpenUSD C++ API\n    description: >-\n      The OpenUSD C++ API is the primary interface for working with Universal\n      Scene Description data. Provides access to USD core (scene composition\n      and asset management), UsdImaging and Hydra (rendering infrastructure),\n      schema APIs for geometry (UsdGeom), shading (UsdShade), lighting\n      (UsdLux), physics (UsdPhysics), volume (UsdVol), and the Shader Discovery\n      and Registry (SDR). Available as an open-source library under the Apache\n      2.0 license.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://openusd.org/release/api/index.html\n    baseURL: https://openusd.org\n    tags:\n      - 3D\n      - C++\n      - File Format\n      - Library\n      - OpenUSD\n      - Rendering\n      - Scene Description\n    properties:\n      - type: Documentation\n        url: https://openusd.org/release/api/index.html\n      - type: APIReference\n        url:\
  \ https://openusd.org/release/api/index.html\n      - type: GettingStarted\n        url: https://openusd.org/release/tut_usd_tutorials.html\n      - type: GitHubRepository\n        url: https://github.com/PixarAnimationStudios/OpenUSD\n      - type: Glossary\n        url: https://openusd.org/release/glossary.html\n    contact:\n      - FN: AOUSD Community\n        url: https://aousd.org/\n\n  - name: OpenUSD Python Bindings\n    description: >-\n      OpenUSD provides comprehensive Python bindings for all major C++ modules,\n      enabling scripting and pipeline integration in Python-based DCC workflows.\n      Python bindings cover the full USD API including pxr.Usd, pxr.UsdGeom,\n      pxr.UsdShade, pxr.UsdLux, pxr.UsdPhysics, pxr.Sdf, and Hydra. Used\n      extensively in production pipelines at Pixar, ILM, and other studios.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://openusd.org/release/api/index.html\n    baseURL:\
  \ https://pypi.org/project/usd-core/\n    tags:\n      - 3D\n      - OpenUSD\n      - Python\n      - Scene Description\n    properties:\n      - type: Documentation\n        url: https://openusd.org/release/api/index.html\n      - type: SDK\n        url: https://pypi.org/project/usd-core/\n      - type: GitHubRepository\n        url: https://github.com/PixarAnimationStudios/OpenUSD\n    contact:\n      - FN: Pixar Animation Studios\n        url: https://github.com/PixarAnimationStudios/OpenUSD\n\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n    X: apievangelist\n    url: https://apievangelist.com\ncommon:\n  - type: Portal\n    url: https://aousd.org\n  - type: Documentation\n    url: https://openusd.org/release/index.html\n  - type: GettingStarted\n    url: https://openusd.org/release/tut_usd_tutorials.html\n  - type: GitHubOrganization\n    url: https://github.com/PixarAnimationStudios\n  - type: GitHubRepository\n    url: https://github.com/PixarAnimationStudios/OpenUSD\n\
  \  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/aousd/refs/heads/main/json-schema/aousd-usd-layer-schema.json\n    title: USD Layer Schema\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/aousd/refs/heads/main/vocabulary/aousd-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Scene Composition\n        description: >-\n          USD's composition arcs (references, payloads, variants, instancing,\n          and specializes) enable non-destructive scene assembly from multiple\n          asset layers with override workflows.\n      - name: Schema-Driven Extensibility\n        description: >-\n          OpenUSD's schema system allows studios and tool vendors to extend\n          the core specification with domain-specific schemas for physics,\n          simulation, characters, and environments.\n      - name: Hydra Rendering Architecture\n        description: >-\n          The Hydra rendering delegate architecture\
  \ enables pluggable render\n          backends including Storm (OpenGL), Arnold, RenderMan, and others.\n      - name: Multiple File Formats\n        description: >-\n          OpenUSD supports human-readable ASCII (.usda), binary (.usdb),\n          and packaged archive (.usdz) file formats for different use cases.\n      - name: Asset Resolution\n        description: >-\n          The ArResolver system enables customizable asset path resolution\n          for integrating USD with studio asset management systems.\n  - type: UseCases\n    data:\n      - name: Film and Visual Effects Production\n        description: >-\n          Exchange complex animated scenes between DCC tools (Maya, Houdini,\n          Blender, Katana) and render farms using OpenUSD as the common format.\n      - name: Game Development\n        description: >-\n          Use OpenUSD as an interchange format between game engines like Unreal\n          Engine and Unity and DCC content creation tools.\n      - name: Architecture\
  \ and Design Visualization\n        description: >-\n          Share 3D building models, materials, and lighting between\n          architectural design tools and real-time visualization platforms.\n      - name: Metaverse and XR\n        description: >-\n          Enable interoperability of 3D assets and scenes across XR platforms,\n          spatial computing devices, and virtual world applications.\n      - name: Industrial Digital Twins\n        description: >-\n          Represent complex mechanical assemblies and simulation environments\n          for industrial digital twin applications using USD schemas.\n  - type: Integrations\n    data:\n      - name: Autodesk Maya / 3ds Max\n        description: >-\n          Import and export USD files via Autodesk's official USD plugins for\n          Maya and 3ds Max, enabling OpenUSD-based pipelines.\n      - name: SideFX Houdini\n        description: >-\n          Native USD integration in Houdini via LOPs (Layout Object Primitives)\n \
  \         for creating and editing USD scenes and assets.\n      - name: Apple Reality Composer Pro\n        description: >-\n          Apple's spatial computing tools use .usdz as the primary format for\n          augmented reality and visionOS content.\n      - name: NVIDIA Omniverse\n        description: >-\n          NVIDIA Omniverse is built on OpenUSD, using it as the foundation for\n          collaborative 3D design and industrial digital twin workflows.\n      - name: Pixar RenderMan\n        description: >-\n          RenderMan natively reads USD scenes, making it the primary production\n          renderer for USD-based feature film pipelines.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aousd/refs/heads/main/apis.yml
tags:
- 3D
- Interoperability
- Linux Foundation
- Metaverse
- OpenUSD
- Specification
- Standards
- USD
- Visual Effects
url: https://raw.githubusercontent.com/api-evangelist/aousd/refs/heads/main/apis.yml
use_cases:
- description: Exchange complex animated scenes between DCC tools (Maya, Houdini, Blender, Katana) and render farms using OpenUSD as the common format.
  name: Film and Visual Effects Production
- description: Use OpenUSD as an interchange format between game engines like Unreal Engine and Unity and DCC content creation tools.
  name: Game Development
- description: Share 3D building models, materials, and lighting between architectural design tools and real-time visualization platforms.
  name: Architecture and Design Visualization
- description: Enable interoperability of 3D assets and scenes across XR platforms, spatial computing devices, and virtual world applications.
  name: Metaverse and XR
- description: Represent complex mechanical assemblies and simulation environments for industrial digital twin applications using USD schemas.
  name: Industrial Digital Twins
---
