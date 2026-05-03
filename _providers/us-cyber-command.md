---
api_count: 2
apis:
- description: The U.S. Cyber Command Cyber National Mission Force (CNMF) shares unclassified malware samples on VirusTotal via the CYBERCOM_Malware_Alert account. This public threat intelligence sharing program pos
  name: CNMF Malware Sharing via VirusTotal
  slug: cnmf-virustotal-malware-sharing
- description: Public news releases, advisories, and operational announcements from U.S. Cyber Command. Includes joint cybersecurity advisories, malware disclosure announcements, defensive cyber operations public st
  name: USCYBERCOM News and Advisories
  slug: uscybercom-news-media
common:
- title: ''
  type: Website
  url: https://www.cybercom.mil/
- title: News and Advisories
  type: Documentation
  url: https://www.cybercom.mil/Media/News/
- title: Contact USCYBERCOM
  type: Contact
  url: https://www.cybercom.mil/About/Contact/
- title: US Cyber Command Vocabulary
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/us-cyber-command/refs/heads/main/vocabulary/us-cyber-command-vocabulary.yml
- title: US Cyber Command JSON-LD Context
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/us-cyber-command/refs/heads/main/json-ld/us-cyber-command-context.jsonld
created: '2024-12-25'
description: US Cyber Command (USCYBERCOM) is a Unified Combatant Command of the United States Armed Forces responsible for directing, synchronizing, and coordinating cyberspace operations. It defends Department of Defense information networks and prepares to conduct full spectrum military cyberspace operations to ensure freedom of action in cyberspace and deny the same to adversaries. USCYBERCOM's Cyber National Mission Force (CNMF) publicly shares unclassified malware samples attributed to state-sponsored threat actors via VirusTotal, contributing to the global cybersecurity community's threat intelligence capabilities. USCYBERCOM also collaborates with CISA, NSA, and allied nations on joint cybersecurity advisories and threat disclosures.
features:
- description: The Cyber National Mission Force (CNMF) shares unclassified malware samples on VirusTotal (CYBERCOM_Malware_Alert) attributed to state-sponsored threat actors from Russia, Iran, North Korea, and other adversaries.
  name: CNMF Malware Sharing Program
- description: USCYBERCOM publishes joint cybersecurity advisories with CISA, NSA, FBI, and allied nation cybersecurity agencies on active threats and recommended mitigations.
  name: Joint Cybersecurity Advisories
- description: USCYBERCOM conducts defensive cyber operations to detect and respond to malicious cyber activity targeting U.S. and partner networks, sharing findings through public disclosures.
  name: Defensive Cyber Operations
- description: Published guidance identifying high-priority cybersecurity challenge problems for industry, academia, and government collaboration to advance national cyber defense capabilities.
  name: Cyber Command Challenge Problems
- description: At partner nation invitation, USCYBERCOM deploys hunt forward teams to identify malicious cyber activity on allied networks, with findings sometimes shared publicly via VirusTotal.
  name: Hunt Forward Operations
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: CNMF publishes malware samples to VirusTotal via the CYBERCOM_Malware_Alert account for public analysis and sharing.
  name: VirusTotal
- description: USCYBERCOM collaborates with CISA on joint cybersecurity advisories, malware disclosures, and critical infrastructure defense.
  name: CISA (Cybersecurity and Infrastructure Security Agency)
- description: USCYBERCOM and NSA coordinate on threat intelligence sharing and jointly author cybersecurity advisories on nation-state threats.
  name: NSA Cybersecurity Directorate
- description: USCYBERCOM partners with UK NCSC, Canadian CCCS, Australian ACSC, and New Zealand NCSC for joint threat intelligence and advisory publications.
  name: Five Eyes Alliance
jsonld:
- class_count: 6
  name: Us Cyber Command Context
  property_count: 29
  slug: us-cyber-command-context
layout: provider
modified: '2026-05-03'
name: US Cyber Command
skills: []
slug: us-cyber-command
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-cyber-command\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-cyber-command/refs/heads/main/apis.yml\napis:\n  - aid: us-cyber-command:cnmf-virustotal-malware-sharing\n    name: CNMF Malware Sharing via VirusTotal\n    tags:\n      - Cybersecurity\n      - Malware\n      - Threat Intelligence\n      - VirusTotal\n      - Federal Government\n    humanURL: https://www.virustotal.com/gui/user/CYBERCOM_Malware_Alert/comments\n    properties:\n      - url: https://www.virustotal.com/gui/user/CYBERCOM_Malware_Alert/comments\n        type: Documentation\n        title: CYBERCOM VirusTotal Malware Alert Feed\n      - url: https://www.cybercom.mil/Media/News/News-Display/Article/1681533/new-cnmf-initiative-shares-malware-samples-with-cybersecurity-industry/\n        type: GettingStarted\n        title: CNMF Malware Sharing Initiative Announcement\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-cyber-command/refs/heads/main/json-schema/uscybercom-malware-sample-schema.json\n\
  \        type: JSONSchema\n        title: Malware Sample Schema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-cyber-command/refs/heads/main/json-schema/uscybercom-threat-actor-schema.json\n        type: JSONSchema\n        title: Threat Actor Schema\n    description: >-\n      The U.S. Cyber Command Cyber National Mission Force (CNMF) shares\n      unclassified malware samples on VirusTotal via the CYBERCOM_Malware_Alert\n      account. This public threat intelligence sharing program posts malware\n      samples attributed to state-sponsored threat actors from Russia, Iran,\n      North Korea, and other adversaries. The program launched in November 2018\n      to improve global cybersecurity by sharing samples with the security\n      community. Follow @CNMF_VirusAlert on Twitter/X for alerts on new uploads.\n  - aid: us-cyber-command:uscybercom-news-media\n    name: USCYBERCOM News and Advisories\n    tags:\n      - Cybersecurity\n      - Federal Government\n\
  \      - Military\n      - Advisories\n    humanURL: https://www.cybercom.mil/Media/News/\n    properties:\n      - url: https://www.cybercom.mil/Media/News/\n        type: Documentation\n        title: USCYBERCOM News and Press Releases\n      - url: https://www.cybercom.mil/Portals/56/Documents/Cyber%20Command%20Problem%20Set%203rd%20Edition.pdf\n        type: Documentation\n        title: Cyber Command Challenge Problems Guidance\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-cyber-command/refs/heads/main/json-schema/uscybercom-advisory-schema.json\n        type: JSONSchema\n        title: Cybersecurity Advisory Schema\n    description: >-\n      Public news releases, advisories, and operational announcements from\n      U.S. Cyber Command. Includes joint cybersecurity advisories, malware\n      disclosure announcements, defensive cyber operations public statements,\n      and the Cyber Command Challenge Problems guidance for industry collaboration.\n\
  name: US Cyber Command\ntags:\n  - Cybersecurity\n  - Federal Government\n  - Military\n  - Threat Intelligence\n  - Defense\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-25'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  US Cyber Command (USCYBERCOM) is a Unified Combatant Command of the United\n  States Armed Forces responsible for directing, synchronizing, and coordinating\n  cyberspace operations. It defends Department of Defense information networks\n  and prepares to conduct full spectrum military cyberspace operations to ensure\n  freedom of action in cyberspace and deny the same to adversaries. USCYBERCOM's\n  Cyber National Mission Force (CNMF) publicly shares unclassified malware samples\n  attributed to state-sponsored threat actors via VirusTotal, contributing to the\n  global cybersecurity community's threat intelligence capabilities. USCYBERCOM\n  also collaborates with\
  \ CISA, NSA, and allied nations on joint cybersecurity\n  advisories and threat disclosures.\ncommon:\n  - type: Website\n    url: https://www.cybercom.mil/\n  - type: Documentation\n    url: https://www.cybercom.mil/Media/News/\n    title: News and Advisories\n  - type: Contact\n    url: https://www.cybercom.mil/About/Contact/\n    title: Contact USCYBERCOM\n  - type: Features\n    data:\n      - name: CNMF Malware Sharing Program\n        description: >-\n          The Cyber National Mission Force (CNMF) shares unclassified malware\n          samples on VirusTotal (CYBERCOM_Malware_Alert) attributed to state-sponsored\n          threat actors from Russia, Iran, North Korea, and other adversaries.\n      - name: Joint Cybersecurity Advisories\n        description: >-\n          USCYBERCOM publishes joint cybersecurity advisories with CISA, NSA,\n          FBI, and allied nation cybersecurity agencies on active threats and\n          recommended mitigations.\n      - name: Defensive Cyber\
  \ Operations\n        description: >-\n          USCYBERCOM conducts defensive cyber operations to detect and respond\n          to malicious cyber activity targeting U.S. and partner networks,\n          sharing findings through public disclosures.\n      - name: Cyber Command Challenge Problems\n        description: >-\n          Published guidance identifying high-priority cybersecurity challenge\n          problems for industry, academia, and government collaboration to\n          advance national cyber defense capabilities.\n      - name: Hunt Forward Operations\n        description: >-\n          At partner nation invitation, USCYBERCOM deploys hunt forward teams\n          to identify malicious cyber activity on allied networks, with findings\n          sometimes shared publicly via VirusTotal.\n  - type: UseCases\n    data:\n      - name: Threat Intelligence Enrichment\n        description: >-\n          Security analysts and threat hunters use CNMF VirusTotal uploads to\n    \
  \      identify and analyze state-sponsored malware, updating detection rules\n          and IOC databases.\n      - name: Malware Analysis and Attribution\n        description: >-\n          Security researchers analyze USCYBERCOM-disclosed malware samples\n          to understand adversary TTPs, develop detection signatures, and\n          support attribution analysis.\n      - name: Cybersecurity Advisory Tracking\n        description: >-\n          Organizations and security teams track USCYBERCOM joint advisories\n          to understand active threats and implement recommended mitigations.\n      - name: Defensive Tool Development\n        description: >-\n          Security tool developers use CNMF malware samples to test and improve\n          detection capabilities, antivirus signatures, and threat hunting tools.\n      - name: Government Threat Awareness\n        description: >-\n          Government agencies and critical infrastructure operators monitor\n          USCYBERCOM\
  \ disclosures for nation-state threat indicators relevant\n          to their networks.\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/us-cyber-command/refs/heads/main/vocabulary/us-cyber-command-vocabulary.yml\n    title: US Cyber Command Vocabulary\n  - type: JSONLD\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/us-cyber-command/refs/heads/main/json-ld/us-cyber-command-context.jsonld\n    title: US Cyber Command JSON-LD Context\n  - type: Integrations\n    data:\n      - name: VirusTotal\n        description: >-\n          CNMF publishes malware samples to VirusTotal via the\n          CYBERCOM_Malware_Alert account for public analysis and sharing.\n      - name: CISA (Cybersecurity and Infrastructure Security Agency)\n        description: >-\n          USCYBERCOM collaborates with CISA on joint cybersecurity advisories,\n          malware disclosures, and critical infrastructure defense.\n      - name: NSA Cybersecurity\
  \ Directorate\n        description: >-\n          USCYBERCOM and NSA coordinate on threat intelligence sharing and\n          jointly author cybersecurity advisories on nation-state threats.\n      - name: Five Eyes Alliance\n        description: >-\n          USCYBERCOM partners with UK NCSC, Canadian CCCS, Australian ACSC, and\n          New Zealand NCSC for joint threat intelligence and advisory publications.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-cyber-command/refs/heads/main/apis.yml
tags:
- Cybersecurity
- Federal Government
- Military
- Threat Intelligence
- Defense
url: https://raw.githubusercontent.com/api-evangelist/us-cyber-command/refs/heads/main/apis.yml
use_cases:
- description: Security analysts and threat hunters use CNMF VirusTotal uploads to identify and analyze state-sponsored malware, updating detection rules and IOC databases.
  name: Threat Intelligence Enrichment
- description: Security researchers analyze USCYBERCOM-disclosed malware samples to understand adversary TTPs, develop detection signatures, and support attribution analysis.
  name: Malware Analysis and Attribution
- description: Organizations and security teams track USCYBERCOM joint advisories to understand active threats and implement recommended mitigations.
  name: Cybersecurity Advisory Tracking
- description: Security tool developers use CNMF malware samples to test and improve detection capabilities, antivirus signatures, and threat hunting tools.
  name: Defensive Tool Development
- description: Government agencies and critical infrastructure operators monitor USCYBERCOM disclosures for nation-state threat indicators relevant to their networks.
  name: Government Threat Awareness
---
