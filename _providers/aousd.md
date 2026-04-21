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
