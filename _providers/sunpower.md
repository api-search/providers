---
api_count: 3
apis:
- description: pvfactors is an open-source Python library for modeling diffuse shading and bifacial photovoltaic (PV) irradiance. It implements 2D geometry and view-factor mathematics to account for reflections betw
  name: pvfactors
  slug: pvfactors
- description: PVMismatch is an open-source Python library for calculating mismatch losses in photovoltaic systems. It models I-V and P-V curves for PV cells, modules, and strings to quantify power loss from cell-to
  name: PVMismatch
  slug: pvmismatch
- description: SolarUtils is an open-source Python package providing solar position algorithms and utility functions for solar energy calculations, including sun position (azimuth, elevation, zenith), sunrise/sunset
  name: SolarUtils
  slug: solar-utils
common:
- title: ''
  type: Website
  url: https://www.sunpower.com
- title: ''
  type: GitHub Organization
  url: https://github.com/SunPower
created: '2026-05-02'
description: 'SunPower is a residential solar energy company (Nasdaq: SPWR) that designs, installs, and finances solar systems and battery storage for homeowners. The original SunPower Corporation filed for Chapter 11 bankruptcy in August 2024; its assets were acquired by Complete Solaria in September 2024, which rebranded as SunPower Inc. in April 2025. SunPower maintains the GitHub org github.com/SunPower, hosting open-source solar modeling tools including pvfactors (view-factor model for bifacial PV modeling), PVMismatch (mismatch loss calculations), and SolarUtils. These Python libraries are used by solar energy professionals and researchers for photovoltaic system modeling and simulation.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-05-02'
name: SunPower
skills: []
slug: sunpower
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sunpower\nname: SunPower\ndescription: >-\n  SunPower is a residential solar energy company (Nasdaq: SPWR) that designs,\n  installs, and finances solar systems and battery storage for homeowners. The\n  original SunPower Corporation filed for Chapter 11 bankruptcy in August 2024;\n  its assets were acquired by Complete Solaria in September 2024, which\n  rebranded as SunPower Inc. in April 2025. SunPower maintains the GitHub org\n  github.com/SunPower, hosting open-source solar modeling tools including\n  pvfactors (view-factor model for bifacial PV modeling), PVMismatch\n  (mismatch loss calculations), and SolarUtils. These Python libraries are\n  used by solar energy professionals and researchers for photovoltaic system\n  modeling and simulation.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Solar Energy\n  - Renewable Energy\n  - Photovoltaics\n  - Open Source\n  - Python\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sunpower/refs/heads/main/apis.yml\n\
  created: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: sunpower:pvfactors\n    name: pvfactors\n    description: >-\n      pvfactors is an open-source Python library for modeling diffuse shading\n      and bifacial photovoltaic (PV) irradiance. It implements 2D geometry\n      and view-factor mathematics to account for reflections between array\n      surfaces including front and back sides of bifacial modules, ground,\n      and sky. Used by PV professionals for simulation of complex shading\n      scenarios, time-series irradiance calculations, and energy yield\n      assessment. Maintained under the SunPower GitHub organization.\n    humanURL: https://github.com/SunPower/pvfactors\n    tags:\n      - Solar Energy\n      - Photovoltaics\n      - Irradiance Modeling\n      - Bifacial PV\n      - Python\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://sunpower.github.io/pvfactors/\n      - type: GitHub\n    \
  \    url: https://github.com/SunPower/pvfactors\n      - type: PyPI\n        url: https://pypi.org/project/pvfactors/\n  - aid: sunpower:pvmismatch\n    name: PVMismatch\n    description: >-\n      PVMismatch is an open-source Python library for calculating mismatch\n      losses in photovoltaic systems. It models I-V and P-V curves for PV\n      cells, modules, and strings to quantify power loss from cell-to-cell\n      or module-to-module variation in electrical characteristics.\n    humanURL: https://github.com/SunPower/PVMismatch\n    tags:\n      - Solar Energy\n      - Photovoltaics\n      - Mismatch Loss\n      - Python\n      - Open Source\n    properties:\n      - type: GitHub\n        url: https://github.com/SunPower/PVMismatch\n  - aid: sunpower:solar-utils\n    name: SolarUtils\n    description: >-\n      SolarUtils is an open-source Python package providing solar position\n      algorithms and utility functions for solar energy calculations, including\n      sun position (azimuth,\
  \ elevation, zenith), sunrise/sunset times, and\n      solar irradiance decomposition models.\n    humanURL: https://github.com/SunPower/SolarUtils\n    tags:\n      - Solar Energy\n      - Solar Position\n      - Irradiance\n      - Python\n      - Open Source\n    properties:\n      - type: GitHub\n        url: https://github.com/SunPower/SolarUtils\ncommon:\n  - type: Website\n    url: https://www.sunpower.com\n  - type: GitHub Organization\n    url: https://github.com/SunPower\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sunpower/refs/heads/main/apis.yml
tags:
- Solar Energy
- Renewable Energy
- Photovoltaics
- Open Source
- Python
url: https://raw.githubusercontent.com/api-evangelist/sunpower/refs/heads/main/apis.yml
use_cases: []
---
