---
api_count: 2
apis:
- description: The Army National Guard Recruiting API provides access to job listings, Military Occupational Specialties (MOS), unit locations, and recruiter contact information for prospective members interested in
  name: Army National Guard Recruiting API
  slug: recruiting-api
- description: 'The Freedom of Information Act (FOIA) portal for the Army National Guard and National Guard Bureau provides a mechanism for submitting FOIA requests, tracking request status, and accessing previously '
  name: Army National Guard FOIA Portal
  slug: foia-api
common:
- title: Army National Guard Website
  type: Portal
  url: https://www.nationalguard.mil/
- title: Resources
  type: Documentation
  url: https://www.nationalguard.mil/Resources/
- title: Army Guard GitHub Organization
  type: GitHubOrganization
  url: https://github.com/armyguard
- title: Web Policy and Terms
  type: TermsOfService
  url: https://www.nationalguard.mil/About/Web-Policy/
- title: Privacy Policy
  type: PrivacyPolicy
  url: https://www.nationalguard.mil/About/Web-Policy/
created: '2024-12-03'
description: The Army National Guard is a reserve component of the United States Army that serves both the nation and individual states in times of need. Operating under the dual authority of the federal government and the fifty state governors, the Army National Guard provides trained and ready soldiers for overseas military operations, domestic disaster relief, homeland security, and civil support missions. Its primary data and digital services are focused on recruiting, career management, benefits administration, and public outreach. The National Guard Bureau (NGB) coordinates federal operations and maintains administrative systems under Title 10 and Title 32 of the United States Code.
features:
- description: GoArmyGuard.com and the main recruiting portal allow prospective soldiers to search job listings by MOS, state, and skill, and connect with local recruiters.
  name: Recruiting Portal
- description: Online submission and tracking system for Freedom of Information Act requests to the National Guard Bureau and Army National Guard.
  name: FOIA Request System
- description: Current soldiers access pay, benefits, training records, and deployment orders through the Army self-service portal integrated with the National Guard.
  name: Soldier Self-Service Portal
- description: Public-facing tool allowing citizens to find Army National Guard units and armory locations in their state or territory.
  name: Unit Locator
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Army National Guard job listings integrate with USAJobs.gov, the federal government's official employment site, for civil service and technician positions.
  name: USA Jobs
- description: Integration with the Army's official benefits counseling portal (myarmybenefits.us.army.mil) for National Guard member benefits information.
  name: MyArmyBenefits
- description: Training management system used by the National Guard to manage soldier training requirements and school seat reservations.
  name: Army Training Requirements and Resources System (ATRRS)
- description: Financial management integration for National Guard pay, travel reimbursement, and benefits payments processed through DFAS.
  name: Defense Finance and Accounting Service (DFAS)
layout: provider
modified: '2026-04-19'
name: Army National Guard
skills: []
slug: army-national-guard
solutions: []
source_filename: apis.yml
source_yaml: "aid: army-national-guard\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/army-national-guard/refs/heads/main/apis.yml\nname: Army National Guard\ntags:\n  - Federal Government\n  - Military\n  - Defense\n  - National Guard\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-04-19'\ndescription: >-\n  The Army National Guard is a reserve component of the United States Army that\n  serves both the nation and individual states in times of need. Operating under\n  the dual authority of the federal government and the fifty state governors, the\n  Army National Guard provides trained and ready soldiers for overseas military\n  operations, domestic disaster relief, homeland security, and civil support\n  missions. Its primary data and digital services are focused on recruiting,\n  career management, benefits administration, and public outreach. The National\n  Guard Bureau\
  \ (NGB) coordinates federal operations and maintains administrative\n  systems under Title 10 and Title 32 of the United States Code.\napis:\n  - aid: army-national-guard:recruiting-api\n    name: Army National Guard Recruiting API\n    description: >-\n      The Army National Guard Recruiting API provides access to job listings,\n      Military Occupational Specialties (MOS), unit locations, and recruiter\n      contact information for prospective members interested in joining the\n      National Guard. This supports the GoArmyGuard.com recruiting portal.\n    humanURL: https://www.nationalguard.mil/Portals/31/Documents/About/NGB_Fact_Sheet.pdf\n    baseURL: https://www.nationalguard.mil\n    tags:\n      - Recruiting\n      - Military\n      - Jobs\n      - National Guard\n    properties:\n      - type: Documentation\n        url: https://www.nationalguard.mil/Recruiting/\n  - aid: army-national-guard:foia-api\n    name: Army National Guard FOIA Portal\n    description: >-\n      The\
  \ Freedom of Information Act (FOIA) portal for the Army National Guard\n      and National Guard Bureau provides a mechanism for submitting FOIA\n      requests, tracking request status, and accessing previously released\n      records. Managed under the NGB FOIA Policy.\n    humanURL: https://www.nationalguard.mil/About/FOIA/\n    baseURL: https://www.nationalguard.mil\n    tags:\n      - FOIA\n      - Government\n      - Transparency\n      - Open Government\n    properties:\n      - type: Documentation\n        url: https://www.nationalguard.mil/About/FOIA/\ncommon:\n  - type: Portal\n    url: https://www.nationalguard.mil/\n    title: Army National Guard Website\n  - type: Documentation\n    url: https://www.nationalguard.mil/Resources/\n    title: Resources\n  - type: GitHubOrganization\n    url: https://github.com/armyguard\n    title: Army Guard GitHub Organization\n  - type: TermsOfService\n    url: https://www.nationalguard.mil/About/Web-Policy/\n    title: Web Policy and Terms\n\
  \  - type: PrivacyPolicy\n    url: https://www.nationalguard.mil/About/Web-Policy/\n    title: Privacy Policy\n  - type: Features\n    data:\n      - name: Recruiting Portal\n        description: >-\n          GoArmyGuard.com and the main recruiting portal allow prospective\n          soldiers to search job listings by MOS, state, and skill, and connect\n          with local recruiters.\n      - name: FOIA Request System\n        description: >-\n          Online submission and tracking system for Freedom of Information Act\n          requests to the National Guard Bureau and Army National Guard.\n      - name: Soldier Self-Service Portal\n        description: >-\n          Current soldiers access pay, benefits, training records, and\n          deployment orders through the Army self-service portal integrated\n          with the National Guard.\n      - name: Unit Locator\n        description: >-\n          Public-facing tool allowing citizens to find Army National Guard units\n      \
  \    and armory locations in their state or territory.\n  - type: UseCases\n    data:\n      - name: Recruit Prospective Soldiers\n        description: >-\n          Recruiters and prospective enlistees use the recruiting portal to\n          search available MOS positions, explore benefits, and initiate the\n          enlistment process.\n      - name: Submit FOIA Requests\n        description: >-\n          Journalists, researchers, and citizens submit Freedom of Information\n          Act requests for Army National Guard records and documents.\n      - name: Locate National Guard Units\n        description: >-\n          Citizens and emergency managers find local National Guard units and\n          armory locations for community engagement or emergency coordination.\n      - name: Access Soldier Benefits Information\n        description: >-\n          Soldiers and their families access information on benefits including\n          education assistance (Montgomery GI Bill), healthcare\
  \ (TRICARE), and\n          retirement benefits.\n  - type: Integrations\n    data:\n      - name: USA Jobs\n        description: >-\n          Army National Guard job listings integrate with USAJobs.gov, the\n          federal government's official employment site, for civil service and\n          technician positions.\n      - name: MyArmyBenefits\n        description: >-\n          Integration with the Army's official benefits counseling portal\n          (myarmybenefits.us.army.mil) for National Guard member benefits\n          information.\n      - name: Army Training Requirements and Resources System (ATRRS)\n        description: >-\n          Training management system used by the National Guard to manage\n          soldier training requirements and school seat reservations.\n      - name: Defense Finance and Accounting Service (DFAS)\n        description: >-\n          Financial management integration for National Guard pay, travel\n          reimbursement, and benefits payments\
  \ processed through DFAS.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/army-national-guard/refs/heads/main/apis.yml
tags:
- Federal Government
- Military
- Defense
- National Guard
url: https://raw.githubusercontent.com/api-evangelist/army-national-guard/refs/heads/main/apis.yml
use_cases:
- description: Recruiters and prospective enlistees use the recruiting portal to search available MOS positions, explore benefits, and initiate the enlistment process.
  name: Recruit Prospective Soldiers
- description: Journalists, researchers, and citizens submit Freedom of Information Act requests for Army National Guard records and documents.
  name: Submit FOIA Requests
- description: Citizens and emergency managers find local National Guard units and armory locations for community engagement or emergency coordination.
  name: Locate National Guard Units
- description: Soldiers and their families access information on benefits including education assistance (Montgomery GI Bill), healthcare (TRICARE), and retirement benefits.
  name: Access Soldier Benefits Information
---
