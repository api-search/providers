---
api_count: 3
apis:
- description: The libiio library provides a cross-platform C API for interfacing with Linux Industrial I/O (IIO) devices including ADCs, DACs, and RF transceivers. It supports local and remote device access via a n
  name: Analog Devices libiio API
  slug: libiio-api
- description: PyADI-IIO provides Python interfaces for ADI hardware with IIO drivers, enabling Python developers to interact with ADI evaluation boards and production hardware. It abstracts libiio with device-speci
  name: Analog Devices PyADI-IIO Python API
  slug: pyadi-iio-api
- description: CodeFusion Studio is ADI's embedded software development environment built on Visual Studio Code for ADI microcontrollers and DSPs. It provides graphical system configuration, code generation, debuggi
  name: Analog Devices CodeFusion Studio
  slug: codefusion-studio
common:
- title: ''
  type: Portal
  url: https://www.analog.com
- title: ''
  type: DeveloperPortal
  url: https://developer.analog.com
- title: ''
  type: Documentation
  url: https://www.analog.com/en/software.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/analogdevicesinc
- title: ''
  type: Blog
  url: https://www.analog.com/en/resources/media-center/analog-dialogue.html
- title: ''
  type: Support
  url: https://ez.analog.com/
- title: ''
  type: JSONSchema
  url: json-schema/analog-devices-iio-device-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/analog-devices-iio-context-schema.json
- title: ''
  type: JSONLD
  url: json-ld/analog-devices-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/analog-devices-vocabulary.yaml
- title: ''
  type: SpectralRules
  url: rules/analog-devices-spectral-rules.yml
created: ''
description: Analog Devices (ADI) is a global semiconductor company designing high-performance analog, mixed-signal, and digital signal processing integrated circuits for industrial, communications, automotive, and consumer markets. ADI provides developer tools through its CodeFusion Studio embedded development environment and the ADI Developer Portal. ADI's APIs are primarily embedded software APIs for microcontrollers and DSPs via the libiio library for Linux Industrial I/O devices, pyadi-iio Python interfaces, and security APIs within the ADI Assure Trusted Edge Security Architecture. The company also maintains the no-OS driver library for bare-metal embedded systems.
features:
- description: libiio library for accessing Linux Industrial I/O devices over USB, network, and local interfaces.
  name: Linux IIO Interface
- description: PyADI-IIO provides Pythonic device-specific APIs for ADI transceivers, converters, and sensors.
  name: Python Hardware Interfaces
- description: ADI Assure security APIs for hardware root of trust, secure boot, and cryptographic operations.
  name: Embedded Security APIs
- description: Bare-metal C drivers for ADI ICs without requiring an operating system.
  name: No-OS Drivers
- description: VS Code-based IDE for ADI MCUs and DSPs with graphical configuration and code generation.
  name: CodeFusion Studio
- description: Active contributor to Linux kernel IIO subsystem, Zephyr RTOS, and other open source projects.
  name: Open Source Ecosystem
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: ADI actively contributes drivers to the Linux kernel IIO framework.
  name: Linux Kernel IIO Subsystem
- description: ADI maintains hardware support for ADI MCUs in the Zephyr real-time operating system.
  name: Zephyr RTOS
- description: Integration with GNU Radio for software-defined radio applications using ADI transceivers.
  name: GNU Radio
- description: MathWorks toolbox support for ADI hardware for signal processing prototyping.
  name: MATLAB/Simulink
- description: CodeFusion Studio is built as a VS Code extension for embedded development.
  name: Microsoft Visual Studio Code
jsonld:
- class_count: 5
  name: Analog Devices Context
  property_count: 6
  slug: analog-devices-context
layout: provider
modified: '2026-04-19'
name: Analog Devices
rules:
- name: Analog Devices API Rules
  rule_count: 4
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 0
  slug: analog-devices-spectral-rules
skills: []
slug: analog-devices
solutions: []
source_yaml: "aid: analog-devices\nurl: https://raw.githubusercontent.com/api-evangelist/analog-devices/refs/heads/main/apis.yml\nmodified: '2026-04-19'\nname: Analog Devices\ndescription: Analog Devices (ADI) is a global semiconductor company designing high-performance analog, mixed-signal, and digital signal processing integrated circuits for industrial, communications, \n  automotive, and consumer markets. ADI provides developer tools through its CodeFusion Studio embedded development environment and the ADI Developer Portal. ADI's APIs are primarily embedded software\n  APIs for microcontrollers and DSPs via the libiio library for Linux Industrial I/O devices, pyadi-iio Python interfaces, and security APIs within the ADI Assure Trusted Edge Security Architecture. \n  The company also maintains the no-OS driver library for bare-metal embedded systems.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Embedded Systems\n- Hardware\n- IoT\n- Semiconductor\n\
  - Signal Processing\napis:\n- aid: analog-devices:libiio-api\n  name: Analog Devices libiio API\n  description: The libiio library provides a cross-platform C API for interfacing with Linux Industrial I/O (IIO) devices including ADCs, DACs, and RF transceivers. It supports local and remote device\n    access via a network daemon, enabling developers to control ADI hardware from Linux and other host platforms.\n  tags:\n  - Embedded Systems\n  - Hardware Interface\n  - IIO\n  - Linux\n  - Signal Processing\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://github.com/analogdevicesinc/libiio\n  humanURL: https://analogdevicesinc.github.io/libiio/\n  properties:\n  - url: https://analogdevicesinc.github.io/libiio/\n    type: Documentation\n  - url: https://github.com/analogdevicesinc/libiio\n    type: GitHubRepository\n- aid: analog-devices:pyadi-iio-api\n  name: Analog Devices PyADI-IIO Python API\n  description: PyADI-IIO provides Python\
  \ interfaces for ADI hardware with IIO drivers, enabling Python developers to interact with ADI evaluation boards and production hardware. It abstracts libiio \n    with device-specific high-level interfaces for transceivers, converters, and sensors.\n  tags:\n  - ADC\n  - Embedded Systems\n  - Hardware\n  - Python\n  - RF\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://github.com/analogdevicesinc/pyadi-iio\n  humanURL: https://analogdevicesinc.github.io/pyadi-iio/\n  properties:\n  - url: https://analogdevicesinc.github.io/pyadi-iio/\n    type: Documentation\n  - url: https://github.com/analogdevicesinc/pyadi-iio\n    type: GitHubRepository\n  - url: https://pypi.org/project/pyadi-iio/\n    type: SDK\n- aid: analog-devices:codefusion-studio\n  name: Analog Devices CodeFusion Studio\n  description: CodeFusion Studio is ADI's embedded software development environment built on Visual Studio Code for ADI microcontrollers and DSPs. It\
  \ provides graphical system configuration, code \n    generation, debugging, and security APIs for the ADI Assure Trusted Edge Security Architecture. Initially supports MAX32690 and ADSP-SC5xx processor families.\n  tags:\n  - Embedded Development\n  - IDE\n  - Microcontrollers\n  - Security\n  - VSCode\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://developer.analog.com\n  humanURL: https://developer.analog.com/solutions/codefusionstudio\n  properties:\n  - url: https://developer.analog.com/solutions/codefusionstudio\n    type: Documentation\n  - url: https://developer.analog.com/docs/codefusion-studio/1.0.2/\n    type: APIReference\n  - url: https://github.com/analogdevicesinc/codefusion-studio\n    type: GitHubRepository\n  - url: https://marketplace.visualstudio.com/items?itemName=AnalogDevices.cfs-ide\n    type: SDK\ncommon:\n- type: Portal\n  url: https://www.analog.com\n- type: DeveloperPortal\n  url: https://developer.analog.com\n\
  - type: Documentation\n  url: https://www.analog.com/en/software.html\n- type: GitHubOrganization\n  url: https://github.com/analogdevicesinc\n- type: Blog\n  url: https://www.analog.com/en/resources/media-center/analog-dialogue.html\n- type: Support\n  url: https://ez.analog.com/\n- type: Features\n  data:\n  - name: Linux IIO Interface\n    description: libiio library for accessing Linux Industrial I/O devices over USB, network, and local interfaces.\n  - name: Python Hardware Interfaces\n    description: PyADI-IIO provides Pythonic device-specific APIs for ADI transceivers, converters, and sensors.\n  - name: Embedded Security APIs\n    description: ADI Assure security APIs for hardware root of trust, secure boot, and cryptographic operations.\n  - name: No-OS Drivers\n    description: Bare-metal C drivers for ADI ICs without requiring an operating system.\n  - name: CodeFusion Studio\n    description: VS Code-based IDE for ADI MCUs and DSPs with graphical configuration and code generation.\n\
  \  - name: Open Source Ecosystem\n    description: Active contributor to Linux kernel IIO subsystem, Zephyr RTOS, and other open source projects.\n- type: UseCases\n  data:\n  - name: Precision Measurement\n    description: High-accuracy data acquisition from ADI ADCs and sensors using libiio or PyADI-IIO.\n  - name: RF and Communications\n    description: Control of RF transceivers like ADRV9002 and AD9361 for SDR and communications applications.\n  - name: Industrial Automation\n    description: Integration of ADI industrial ICs into factory automation and process control systems.\n  - name: Secure IoT Devices\n    description: Building secure edge devices with hardware root of trust using ADI Assure security APIs.\n  - name: Motor Control\n    description: Developing motor drive applications using ADI ADSP processors and evaluation kits.\n- type: Integrations\n  data:\n  - name: Linux Kernel IIO Subsystem\n    description: ADI actively contributes drivers to the Linux kernel IIO framework.\n\
  \  - name: Zephyr RTOS\n    description: ADI maintains hardware support for ADI MCUs in the Zephyr real-time operating system.\n  - name: GNU Radio\n    description: Integration with GNU Radio for software-defined radio applications using ADI transceivers.\n  - name: MATLAB/Simulink\n    description: MathWorks toolbox support for ADI hardware for signal processing prototyping.\n  - name: Microsoft Visual Studio Code\n    description: CodeFusion Studio is built as a VS Code extension for embedded development.\n- type: JSONSchema\n  url: json-schema/analog-devices-iio-device-schema.json\n- type: JSONSchema\n  url: json-schema/analog-devices-iio-context-schema.json\n- type: JSONLD\n  url: json-ld/analog-devices-context.jsonld\n- type: Vocabulary\n  url: vocabulary/analog-devices-vocabulary.yaml\n- type: SpectralRules\n  url: rules/analog-devices-spectral-rules.yml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/analog-devices/refs/heads/main/apis.yml
tags:
- Embedded Systems
- Hardware
- IoT
- Semiconductor
- Signal Processing
url: https://raw.githubusercontent.com/api-evangelist/analog-devices/refs/heads/main/apis.yml
use_cases:
- description: High-accuracy data acquisition from ADI ADCs and sensors using libiio or PyADI-IIO.
  name: Precision Measurement
- description: Control of RF transceivers like ADRV9002 and AD9361 for SDR and communications applications.
  name: RF and Communications
- description: Integration of ADI industrial ICs into factory automation and process control systems.
  name: Industrial Automation
- description: Building secure edge devices with hardware root of trust using ADI Assure security APIs.
  name: Secure IoT Devices
- description: Developing motor drive applications using ADI ADSP processors and evaluation kits.
  name: Motor Control
---
