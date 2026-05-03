---
api_count: 1
apis:
- description: 'Wireshark is a free and open-source network protocol analyzer that captures and interactively browses network traffic. It supports hundreds of protocols, runs on multiple platforms, and provides deep '
  name: Wireshark
  slug: wireshark
common:
- title: ''
  type: Website
  url: https://www.wireshark.org
- title: ''
  type: Documentation
  url: https://www.wireshark.org/docs/
- title: ''
  type: Blog
  url: https://blog.wireshark.org
- title: ''
  type: FAQ
  url: https://www.wireshark.org/faq.html
- title: ''
  type: GitHub
  url: https://github.com/wireshark/wireshark
- title: ''
  type: GitLab
  url: https://gitlab.com/wireshark/wireshark
- title: ''
  type: Support
  url: https://ask.wireshark.org
- title: ''
  type: Downloads
  url: https://www.wireshark.org/download.html
- title: ''
  type: ReleaseNotes
  url: https://www.wireshark.org/docs/relnotes/
- title: ''
  type: Forum
  url: https://www.wireshark.org/lists/
created: '2025-01-08'
description: Wireshark is the world's foremost and widely-used free and open-source network protocol analyzer. It lets you capture and interactively browse the traffic running on a computer network. Wireshark provides a powerful dissector framework with a Lua scripting API, C/C++ plugin architecture, TShark command-line tools, and the libwireshark library for developers building network analysis tools.
features:
- description: Capture live network traffic from multiple interfaces simultaneously using libpcap/Npcap.
  name: Packet Capture
- description: Analyze hundreds of protocols with full decode of packet fields and values.
  name: Deep Packet Inspection
- description: Powerful filter language for drilling into captured traffic.
  name: Display Filters
- description: Extend Wireshark with custom dissectors, listeners, and menus using the Lua API.
  name: Lua Scripting
- description: Write C/C++ plugins to add support for new protocols.
  name: Dissector Plugins
- description: Command-line version of Wireshark for scripting and automation.
  name: TShark CLI
- description: Plugin API to add custom capture sources to Wireshark.
  name: Extcap Interface
- description: Library for reading and writing capture file formats including pcap and pcapng.
  name: Wiretap Library
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Command-line packet analyzer that uses the same dissection engine as Wireshark.
  name: TShark
- description: Minimal capture utility used by Wireshark and TShark.
  name: dumpcap
- description: Utility for editing and converting capture files.
  name: editcap
- description: Scripting language embedded in Wireshark for custom protocol dissectors.
  name: Lua
- description: Packet capture libraries used by Wireshark on Unix and Windows respectively.
  name: libpcap/Npcap
layout: provider
modified: '2026-05-03'
name: Wireshark
skills: []
slug: wireshark
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wireshark\nname: Wireshark\ndescription: >-\n  Wireshark is the world's foremost and widely-used free and open-source network\n  protocol analyzer. It lets you capture and interactively browse the traffic\n  running on a computer network. Wireshark provides a powerful dissector\n  framework with a Lua scripting API, C/C++ plugin architecture, TShark\n  command-line tools, and the libwireshark library for developers building\n  network analysis tools.\ntype: Index\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/wireshark/refs/heads/main/apis.yml\ntags:\n  - Debugging\n  - Network Analysis\n  - Open Source\n  - Packet Capture\n  - Protocol Analysis\n  - Security\ncreated: '2025-01-08'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\naccess: 3rd-Party\nposition: Consumer\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\napis:\n  - aid: wireshark:wireshark\n    name: Wireshark\n    description: >-\n      Wireshark is a free\
  \ and open-source network protocol analyzer that\n      captures and interactively browses network traffic. It supports hundreds\n      of protocols, runs on multiple platforms, and provides deep inspection of\n      packets. Developers can extend Wireshark through its Lua scripting API,\n      C/C++ dissector plugins, Extcap plugin interface, and the Wiretap library\n      for custom capture file formats.\n    humanURL: https://www.wireshark.org\n    tags:\n      - Debugging\n      - Extcap\n      - Lua Scripting\n      - Network Analysis\n      - Open Source\n      - Packet Capture\n      - Protocol Analysis\n      - Plugins\n    properties:\n      - type: Documentation\n        url: https://www.wireshark.org/docs/\n      - type: APIReference\n        url: https://www.wireshark.org/docs/wsdg_html_chunked/\n      - type: GettingStarted\n        url: https://www.wireshark.org/docs/wsug_html_chunked/\n      - type: SDK\n        url: https://www.wireshark.org/docs/wsdg_html_chunked/ChapterDissection.html\n\
  \        title: Dissector Plugin API (C/C++)\n      - type: SDK\n        url: https://www.wireshark.org/docs/wsdg_html_chunked/wsluarm.html\n        title: Lua API Reference\n      - type: Downloads\n        url: https://www.wireshark.org/download.html\ncommon:\n  - type: Website\n    url: https://www.wireshark.org\n  - type: Documentation\n    url: https://www.wireshark.org/docs/\n  - type: Blog\n    url: https://blog.wireshark.org\n  - type: FAQ\n    url: https://www.wireshark.org/faq.html\n  - type: GitHub\n    url: https://github.com/wireshark/wireshark\n  - type: GitLab\n    url: https://gitlab.com/wireshark/wireshark\n  - type: Support\n    url: https://ask.wireshark.org\n  - type: Downloads\n    url: https://www.wireshark.org/download.html\n  - type: ReleaseNotes\n    url: https://www.wireshark.org/docs/relnotes/\n  - type: Forum\n    url: https://www.wireshark.org/lists/\n  - type: Features\n    data:\n      - name: Packet Capture\n        description: Capture live network traffic\
  \ from multiple interfaces simultaneously using libpcap/Npcap.\n      - name: Deep Packet Inspection\n        description: Analyze hundreds of protocols with full decode of packet fields and values.\n      - name: Display Filters\n        description: Powerful filter language for drilling into captured traffic.\n      - name: Lua Scripting\n        description: Extend Wireshark with custom dissectors, listeners, and menus using the Lua API.\n      - name: Dissector Plugins\n        description: Write C/C++ plugins to add support for new protocols.\n      - name: TShark CLI\n        description: Command-line version of Wireshark for scripting and automation.\n      - name: Extcap Interface\n        description: Plugin API to add custom capture sources to Wireshark.\n      - name: Wiretap Library\n        description: Library for reading and writing capture file formats including pcap and pcapng.\n  - type: UseCases\n    data:\n      - name: Network Troubleshooting\n        description:\
  \ Diagnose latency, packet loss, and protocol errors in live or captured traffic.\n      - name: API Traffic Debugging\n        description: Inspect raw HTTP, gRPC, and WebSocket API requests and responses at the packet level.\n      - name: Protocol Development\n        description: Develop and test new network protocols using Wireshark dissectors.\n      - name: Security Analysis\n        description: Analyze network traffic for intrusion indicators and malicious patterns.\n      - name: Education\n        description: Learn networking concepts by capturing and examining real protocol exchanges.\n  - type: Integrations\n    data:\n      - name: TShark\n        description: Command-line packet analyzer that uses the same dissection engine as Wireshark.\n      - name: dumpcap\n        description: Minimal capture utility used by Wireshark and TShark.\n      - name: editcap\n        description: Utility for editing and converting capture files.\n      - name: Lua\n        description: Scripting\
  \ language embedded in Wireshark for custom protocol dissectors.\n      - name: libpcap/Npcap\n        description: Packet capture libraries used by Wireshark on Unix and Windows respectively.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wireshark/refs/heads/main/apis.yml
tags:
- Debugging
- Network Analysis
- Open Source
- Packet Capture
- Protocol Analysis
- Security
url: https://raw.githubusercontent.com/api-evangelist/wireshark/refs/heads/main/apis.yml
use_cases:
- description: Diagnose latency, packet loss, and protocol errors in live or captured traffic.
  name: Network Troubleshooting
- description: Inspect raw HTTP, gRPC, and WebSocket API requests and responses at the packet level.
  name: API Traffic Debugging
- description: Develop and test new network protocols using Wireshark dissectors.
  name: Protocol Development
- description: Analyze network traffic for intrusion indicators and malicious patterns.
  name: Security Analysis
- description: Learn networking concepts by capturing and examining real protocol exchanges.
  name: Education
---
