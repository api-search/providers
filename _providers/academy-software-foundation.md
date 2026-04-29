---
api_count: 11
api_specs:
- filename: academy-software-foundation-opencue.yaml
  format: yaml
  label: OpenCue
  slug: opencue
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/academy-software-foundation/refs/heads/main/openapi/academy-software-foundation-opencue.yaml
apis:
- description: OpenEXR is an open standard high-dynamic-range (HDR) image file format specification and reference implementation developed by Industrial Light and Magic. It is the industry standard for visual effect
  name: OpenEXR
  slug: openexr
- description: OpenVDB is an Academy Award-winning open source C++ library for efficient storage and manipulation of sparse volumetric data discretized on three-dimensional grids. It is the industry standard for vol
  name: OpenVDB
  slug: openvdb
- description: OpenColorIO (OCIO) is a complete color management solution geared towards motion picture production, enabling color transforms and image display to be handled in a consistent manner across many applic
  name: OpenColorIO
  slug: opencolorio
- description: OpenTimelineIO (OTIO) is an open source API and interchange format for editorial timeline information. It is designed to be more expressive than existing formats while still being easy to read and wri
  name: OpenTimelineIO
  slug: opentimelineio
- description: 'Open Shading Language (OSL) is a small but rich language for programmable shading in advanced renderers and other applications. It is ideal for describing materials, lights, displacement, and pattern '
  name: Open Shading Language
  slug: openshadinglanguage
- description: MaterialX is an open standard for the exchange of rich material and look-development content between applications and renderers. It provides a language for defining surface and volume shading patterns
  name: MaterialX
  slug: materialx
- description: OpenCue is an open source render management system for visual effects and animation productions. It enables studios to deploy and manage a render farm, schedule jobs, and track progress across large n
  name: OpenCue
  slug: opencue
- description: OpenImageIO (OIIO) is a library for reading, writing, and processing images in a wide variety of file formats. It is used in visual effects and animation production pipelines for texture baking, image
  name: OpenImageIO
  slug: openimagedio
- description: OpenFX is an open standard API for visual effects plug-ins used in compositing and image processing applications. It defines how host applications and image processing plug-ins communicate, enabling i
  name: OpenFX
  slug: openfx
- description: OpenAPV is an open, royalty-free video codec specification designed for professional video production and post-production workflows. It is optimized for high-quality intermediate video formats used in
  name: OpenAPV
  slug: openapv
- description: OpenPBR is an open specification and reference implementation for a physically-based shading model. It defines a standard material definition language that can be used across different renderers to ac
  name: OpenPBR
  slug: openpbr
capabilities:
- description: 'Render farm management workflow using OpenCue for monitoring and managing render jobs, layers, frames, and hosts in a VFX production pipeline. Used by render wranglers and pipeline TDs to monitor and '
  name: Academy Software Foundation Render Farm Management
  slug: render-farm-management
common:
- title: ''
  type: Website
  url: https://www.aswf.io/
- title: ''
  type: Documentation
  url: https://www.aswf.io/projects/
- title: ''
  type: GitHubOrganization
  url: https://github.com/AcademySoftwareFoundation
- title: ''
  type: Blog
  url: https://www.aswf.io/news/
- title: ''
  type: GettingStarted
  url: https://www.aswf.io/get-involved/
- title: ''
  type: TermsOfService
  url: https://www.aswf.io/terms/
- title: ''
  type: PrivacyPolicy
  url: https://www.aswf.io/privacy/
- title: ''
  type: SpectralRules
  url: rules/academy-software-foundation-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/render-farm-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/academy-software-foundation-vocabulary.yaml
created: '2026-03-16'
description: The Academy Software Foundation (ASWF) is a Linux Foundation project that supports open source software development for the motion picture, visual effects, and animation industries. ASWF hosts a portfolio of production-proven open source projects including OpenEXR, OpenVDB, OpenColorIO, OpenTimelineIO, OpenShadingLanguage, MaterialX, and more. These projects form the backbone of modern film and media production pipelines worldwide.
features:
- description: All ASWF projects are governed by open, transparent processes under the Linux Foundation umbrella
  name: Open Source Governance
- description: Projects like OpenEXR, OpenVDB, and OpenColorIO are used in major film studios worldwide
  name: Production-Proven Projects
- description: ASWF provides a neutral forum where studios, vendors, and developers collaborate on shared technology challenges
  name: Vendor-Neutral Collaboration
- description: ASWF provides shared containerized build and test infrastructure via aswf-docker for consistent CI/CD across all projects
  name: CI/CD Infrastructure
- description: Dedicated working groups address cross-project topics such as CI, color interop, and language interoperability
  name: Working Groups
- description: ASWF projects define and maintain industry standards used across the global VFX and animation pipeline
  name: Standards Development
image: /assets/icons/academy-software-foundation.png
integrations:
- description: Integrates with OpenColorIO, OpenEXR, and other ASWF standards via native plug-ins
  name: Autodesk Maya
- description: Uses OpenColorIO, OpenEXR, and OpenFX plug-ins extensively in compositing workflows
  name: The Foundry Nuke
- description: Deep integration with OpenVDB, OpenColorIO, and OpenEXR for VFX and simulation workflows
  name: SideFX Houdini
- description: Uses OpenEXR, OpenColorIO, OpenShadingLanguage, and OpenVDB for rendering and compositing
  name: Blender
- description: Works alongside ASWF standards as part of the broader VFX open source ecosystem
  name: Pixar USD
- description: Uses MaterialX and OpenColorIO for material interchange and color management
  name: NVIDIA Omniverse
jsonld:
- class_count: 5
  name: Academy Software Foundation Opencue Context
  property_count: 22
  slug: academy-software-foundation-opencue-context
layout: provider
modified: '2026-04-19'
name: Academy Software Foundation
rules:
- name: Academy Software Foundation API Rules
  rule_count: 21
  severity_counts:
    error: 14
    hint: 0
    info: 2
    warn: 5
  slug: academy-software-foundation-spectral-rules
skills: []
slug: academy-software-foundation
solutions: []
source_filename: apis.yml
source_yaml: "aid: academy-software-foundation\nname: Academy Software Foundation\ndescription: >-\n  The Academy Software Foundation (ASWF) is a Linux Foundation project that\n  supports open source software development for the motion picture, visual\n  effects, and animation industries. ASWF hosts a portfolio of production-proven\n  open source projects including OpenEXR, OpenVDB, OpenColorIO, OpenTimelineIO,\n  OpenShadingLanguage, MaterialX, and more. These projects form the backbone of\n  modern film and media production pipelines worldwide.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Animation\n- Color Management\n- Film\n- Linux Foundation\n- Open Source\n- Rendering\n- Standards\n- Visual Effects\n- VFX\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/academy-software-foundation/refs/heads/main/apis.yml\nspecificationVersion:\
  \ '0.19'\napis:\n- aid: academy-software-foundation:openexr\n  name: OpenEXR\n  description: >-\n    OpenEXR is an open standard high-dynamic-range (HDR) image file format\n    specification and reference implementation developed by Industrial Light\n    and Magic. It is the industry standard for visual effects and animation\n    and provides a C++ library for reading and writing EXR image files.\n  humanURL: https://openexr.com/\n  tags:\n  - Image Format\n  - HDR\n  - Standards\n  - C++\n  properties:\n  - type: Documentation\n    url: https://openexr.com/\n  - type: GitHubRepository\n    url: https://github.com/AcademySoftwareFoundation/openexr\n\n- aid: academy-software-foundation:openvdb\n  name: OpenVDB\n  description: >-\n    OpenVDB is an Academy Award-winning open source C++ library for efficient\n    storage and manipulation of sparse volumetric data discretized on\n    three-dimensional grids. It is the industry standard for volumetric\n    effects in film and visual effects\
  \ production.\n  humanURL: https://www.openvdb.org/\n  tags:\n  - Volumetric Data\n  - C++\n  - Rendering\n  - Standards\n  properties:\n  - type: Documentation\n    url: https://www.openvdb.org/documentation/\n  - type: GitHubRepository\n    url: https://github.com/AcademySoftwareFoundation/openvdb\n\n- aid: academy-software-foundation:opencolorio\n  name: OpenColorIO\n  description: >-\n    OpenColorIO (OCIO) is a complete color management solution geared towards\n    motion picture production, enabling color transforms and image display to\n    be handled in a consistent manner across many applications. It is used by\n    major VFX studios and DCC tools including Maya, Nuke, and Houdini.\n  humanURL: https://opencolorio.org/\n  tags:\n  - Color Management\n  - Standards\n  - C++\n  properties:\n  - type: Documentation\n    url: https://opencolorio.readthedocs.io/\n  - type: GitHubRepository\n    url: https://github.com/AcademySoftwareFoundation/OpenColorIO\n\n- aid: academy-software-foundation:opentimelineio\n\
  \  name: OpenTimelineIO\n  description: >-\n    OpenTimelineIO (OTIO) is an open source API and interchange format for\n    editorial timeline information. It is designed to be more expressive than\n    existing formats while still being easy to read and write, enabling better\n    interoperability between editing tools.\n  humanURL: https://opentimeline.io/\n  tags:\n  - Editorial\n  - Timeline\n  - Standards\n  - Python\n  properties:\n  - type: Documentation\n    url: https://opentimelineio.readthedocs.io/\n  - type: GitHubRepository\n    url: https://github.com/AcademySoftwareFoundation/OpenTimelineIO\n\n- aid: academy-software-foundation:openshadinglanguage\n  name: Open Shading Language\n  description: >-\n    Open Shading Language (OSL) is a small but rich language for\n    programmable shading in advanced renderers and other applications. It is\n    ideal for describing materials, lights, displacement, and pattern\n    generation and is supported by many production renderers.\n\
  \  humanURL: https://github.com/AcademySoftwareFoundation/OpenShadingLanguage\n  tags:\n  - Shading\n  - Rendering\n  - Standards\n  - C++\n  properties:\n  - type: Documentation\n    url: https://github.com/AcademySoftwareFoundation/OpenShadingLanguage/blob/main/src/doc/osl-languagespec.pdf\n  - type: GitHubRepository\n    url: https://github.com/AcademySoftwareFoundation/OpenShadingLanguage\n\n- aid: academy-software-foundation:materialx\n  name: MaterialX\n  description: >-\n    MaterialX is an open standard for the exchange of rich material and\n    look-development content between applications and renderers. It provides\n    a language for defining surface and volume shading patterns that can be\n    used across different rendering systems and DCC applications.\n  humanURL: https://www.materialx.org/\n  tags:\n  - Materials\n  - Shading\n  - Standards\n  - XML\n  properties:\n  - type: Documentation\n    url: https://materialx.org/docs/\n  - type: GitHubRepository\n    url: https://github.com/AcademySoftwareFoundation/MaterialX\n\
  \n- aid: academy-software-foundation:opencue\n  name: OpenCue\n  description: >-\n    OpenCue is an open source render management system for visual effects and\n    animation productions. It enables studios to deploy and manage a render\n    farm, schedule jobs, and track progress across large numbers of render\n    nodes. It was originally developed by Sony Pictures Imageworks.\n  humanURL: https://www.opencue.io/\n  tags:\n  - Render Management\n  - VFX\n  - Python\n  properties:\n  - type: Documentation\n    url: https://www.opencue.io/docs/\n  - type: GitHubRepository\n    url: https://github.com/AcademySoftwareFoundation/OpenCue\n\n  - url: openapi/academy-software-foundation-opencue.yaml\n    type: OpenAPI\n  - url: json-schema/opencue-job-schema.json\n    type: JSONSchema\n  - url: examples/opencue-job-example.json\n    type: Example\n- aid: academy-software-foundation:openimagedio\n  name: OpenImageIO\n  description: >-\n    OpenImageIO (OIIO) is a library for reading, writing,\
  \ and processing\n    images in a wide variety of file formats. It is used in visual effects\n    and animation production pipelines for texture baking, image compositing,\n    and format conversion.\n  humanURL: https://sites.google.com/site/openimageio/home\n  tags:\n  - Image Processing\n  - C++\n  - VFX\n  properties:\n  - type: Documentation\n    url: https://openimageio.readthedocs.io/\n  - type: GitHubRepository\n    url: https://github.com/AcademySoftwareFoundation/OpenImageIO\n\n- aid: academy-software-foundation:openfx\n  name: OpenFX\n  description: >-\n    OpenFX is an open standard API for visual effects plug-ins used in\n    compositing and image processing applications. It defines how host\n    applications and image processing plug-ins communicate, enabling\n    interoperability across compositing tools.\n  humanURL: https://openfx.io/\n  tags:\n  - Visual Effects\n  - Plugin API\n  - Standards\n  - C++\n  properties:\n  - type: Documentation\n    url: https://openfx.io/\n\
  \  - type: GitHubRepository\n    url: https://github.com/AcademySoftwareFoundation/openfx\n\n- aid: academy-software-foundation:openapv\n  name: OpenAPV\n  description: >-\n    OpenAPV is an open, royalty-free video codec specification designed for\n    professional video production and post-production workflows. It is\n    optimized for high-quality intermediate video formats used in camera\n    and on-set production pipelines.\n  humanURL: https://github.com/AcademySoftwareFoundation/openapv\n  tags:\n  - Video Codec\n  - Standards\n  - C\n  properties:\n  - type: GitHubRepository\n    url: https://github.com/AcademySoftwareFoundation/openapv\n\n- aid: academy-software-foundation:openpbr\n  name: OpenPBR\n  description: >-\n    OpenPBR is an open specification and reference implementation for a\n    physically-based shading model. It defines a standard material\n    definition language that can be used across different renderers to\n    achieve consistent appearance.\n  humanURL: https://academysoftwarefoundation.github.io/OpenPBR/\n\
  \  tags:\n  - Rendering\n  - Materials\n  - Standards\n  properties:\n  - type: Documentation\n    url: https://academysoftwarefoundation.github.io/OpenPBR/\n  - type: GitHubRepository\n    url: https://github.com/AcademySoftwareFoundation/OpenPBR\n\ncommon:\n- type: Website\n  url: https://www.aswf.io/\n- type: Documentation\n  url: https://www.aswf.io/projects/\n- type: GitHubOrganization\n  url: https://github.com/AcademySoftwareFoundation\n- type: Blog\n  url: https://www.aswf.io/news/\n- type: GettingStarted\n  url: https://www.aswf.io/get-involved/\n- type: TermsOfService\n  url: https://www.aswf.io/terms/\n- type: PrivacyPolicy\n  url: https://www.aswf.io/privacy/\n- type: Features\n  data:\n  - name: Open Source Governance\n    description: All ASWF projects are governed by open, transparent processes under the Linux Foundation umbrella\n  - name: Production-Proven Projects\n    description: Projects like OpenEXR, OpenVDB, and OpenColorIO are used in major film studios worldwide\n\
  \  - name: Vendor-Neutral Collaboration\n    description: ASWF provides a neutral forum where studios, vendors, and developers collaborate on shared technology challenges\n  - name: CI/CD Infrastructure\n    description: ASWF provides shared containerized build and test infrastructure via aswf-docker for consistent CI/CD across all projects\n  - name: Working Groups\n    description: Dedicated working groups address cross-project topics such as CI, color interop, and language interoperability\n  - name: Standards Development\n    description: ASWF projects define and maintain industry standards used across the global VFX and animation pipeline\n- type: UseCases\n  data:\n  - name: VFX Production Pipeline\n    description: OpenEXR, OpenVDB, OpenColorIO, and OSL form the core of visual effects production pipelines at major studios\n  - name: Render Farm Management\n    description: OpenCue enables studios to build and operate large-scale distributed render farms for animation and VFX\n \
  \ - name: Color Pipeline Standardization\n    description: OpenColorIO provides consistent color transforms across all DCC tools in a studio pipeline\n  - name: Editorial Interchange\n    description: OpenTimelineIO enables timeline data exchange between editing applications like Avid, Premiere, and DaVinci Resolve\n  - name: Material Interchange\n    description: MaterialX and OpenPBR enable look development assets to be transferred between different render engines\n  - name: Image Format Standardization\n    description: OpenEXR provides a universal HDR image format for compositing, rendering output, and archiving\n- type: Integrations\n  data:\n  - name: Autodesk Maya\n    description: Integrates with OpenColorIO, OpenEXR, and other ASWF standards via native plug-ins\n  - name: The Foundry Nuke\n    description: Uses OpenColorIO, OpenEXR, and OpenFX plug-ins extensively in compositing workflows\n  - name: SideFX Houdini\n    description: Deep integration with OpenVDB, OpenColorIO, and\
  \ OpenEXR for VFX and simulation workflows\n  - name: Blender\n    description: Uses OpenEXR, OpenColorIO, OpenShadingLanguage, and OpenVDB for rendering and compositing\n  - name: Pixar USD\n    description: Works alongside ASWF standards as part of the broader VFX open source ecosystem\n  - name: NVIDIA Omniverse\n    description: Uses MaterialX and OpenColorIO for material interchange and color management\n\n- url: rules/academy-software-foundation-spectral-rules.yml\n  type: SpectralRules\n- url: capabilities/render-farm-management.yaml\n  type: NaftikoCapability\n- url: vocabulary/academy-software-foundation-vocabulary.yaml\n  type: Vocabulary\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/academy-software-foundation/refs/heads/main/apis.yml
tags:
- Animation
- Color Management
- Film
- Linux Foundation
- Open Source
- Rendering
- Standards
- Visual Effects
- VFX
url: https://raw.githubusercontent.com/api-evangelist/academy-software-foundation/refs/heads/main/apis.yml
use_cases:
- description: OpenEXR, OpenVDB, OpenColorIO, and OSL form the core of visual effects production pipelines at major studios
  name: VFX Production Pipeline
- description: OpenCue enables studios to build and operate large-scale distributed render farms for animation and VFX
  name: Render Farm Management
- description: OpenColorIO provides consistent color transforms across all DCC tools in a studio pipeline
  name: Color Pipeline Standardization
- description: OpenTimelineIO enables timeline data exchange between editing applications like Avid, Premiere, and DaVinci Resolve
  name: Editorial Interchange
- description: MaterialX and OpenPBR enable look development assets to be transferred between different render engines
  name: Material Interchange
- description: OpenEXR provides a universal HDR image format for compositing, rendering output, and archiving
  name: Image Format Standardization
---
