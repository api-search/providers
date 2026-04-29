---
api_count: 14
api_specs:
- filename: indeed-employer-api-openapi.yml
  format: yaml
  label: Indeed Job Sync API
  slug: job-sync
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/indeed/refs/heads/main/openapi/indeed-employer-api-openapi.yml
- filename: indeed-employer-api-openapi.yml
  format: yaml
  label: Indeed Employer API
  slug: employer
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/indeed/refs/heads/main/openapi/indeed-employer-api-openapi.yml
apis:
- description: Search for jobs by keyword, location, and other criteria. Returns job listings with details including title, company, location, and description. This API is deprecated and not available for new integr
  name: Indeed Job Search API
  slug: job-search
- description: Monetize your website by displaying Indeed job listings. Earn revenue through cost-per-click advertising.
  name: Indeed Publisher API
  slug: publisher
- description: Allow job seekers to apply to your jobs directly through Indeed with a streamlined application process. Supports screener questions, EEO compliance for US employers, and disposition data integration.
  name: Indeed Apply API
  slug: apply
- description: A GraphQL API that enables ATS partners to create, upsert, expire, and get status for job postings on Indeed. Supports qualifications, working hours, salary, benefits, and employer information.
  name: Indeed Job Sync API
  slug: job-sync
- description: A GraphQL API that enables ATS partners to send disposition data for Indeed Apply and non-Indeed Apply jobs to Indeed, tracking application status changes through various stages of the hiring process.
  name: Indeed Disposition Sync API
  slug: disposition-sync
- description: A GraphQL API used to get information about and manage an employer's sponsored job campaigns on Indeed, including campaign creation, budget management, and performance insights.
  name: Indeed Sponsored Jobs API
  slug: sponsored-jobs
- description: Allows partners to list and update job postings on Indeed, including adding metadata to ATS-sourced jobs for improved quality and sponsorship grouping, and subscribing to jobs lifecycle events via web
  name: Indeed Job Update API
  slug: job-update
- description: Stream real-time server-sent events (SSE) to enable front-end applications to update instantly, supporting event filtering, deduplication, and latency tracking.
  name: Indeed Real-time API
  slug: real-time
- description: A GraphQL API for scheduling, updating, retrieving information about, and canceling virtual interview events with job candidates. This API is deprecated.
  name: Indeed Interview API
  slug: interview
- description: A RESTful abstraction of Indeed's employer-facing partner APIs, providing unified access to employer management, candidate retrieval, and job posting operations.
  name: Indeed Employer API
  slug: employer
- description: A GraphQL API for creating and updating employer entities on Indeed and the Indeed PLUS platform.
  name: Indeed Employer Data API
  slug: employer-data
- description: Tracks candidate events such as job application page visits and completed applications from Indeed to your site. Provides data for reporting, analytics dashboards, and apply-based bidding algorithms.
  name: Indeed Conversion Tracking API
  slug: conversion-tracking
- description: Part of the Candidate Sync APIs, this API allows ATS partners to register employers for Candidate Sync integration.
  name: Indeed Employer Registration API
  slug: employer-registration
- description: Part of the Candidate Sync APIs, this API enables ATS partners to get candidate and application information from Indeed on behalf of employers.
  name: Indeed Retrieve Candidates API
  slug: retrieve-candidates
capabilities:
- description: Unified workflow for managing the hiring pipeline including employer setup, job posting, candidate retrieval, and disposition tracking. Used by ATS partners and hiring platform developers.
  name: Indeed Talent Acquisition
  slug: talent-acquisition
common:
- title: ''
  type: DeveloperPortal
  url: https://opensource.indeedeng.io/
- title: ''
  type: TermsOfService
  url: https://www.indeed.com/legal/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.indeed.com/legal/privacy
- title: ''
  type: StatusPage
  url: https://status.indeed.com
- title: ''
  type: Support
  url: https://support.indeed.com/hc/en-us
- title: ''
  type: Blog
  url: https://engineering.indeedblog.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/indeedeng
- title: ''
  type: X
  url: https://twitter.com/indeedeng
- title: ''
  type: RateLimits
  url: https://opensource.indeedeng.io/api-documentation/docs/rate-limits
- title: ''
  type: Authentication
  url: https://docs.indeed.com/authorization/
- title: ''
  type: GettingStarted
  url: https://docs.indeed.com/getstarted/
- title: ''
  type: ReleaseNotes
  url: https://docs.indeed.com/release-notes/
- title: ''
  type: Sandbox
  url: https://docs.indeed.com/getstarted/simulated-graphql-environment
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/indeed-com/
- title: Employer API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/employer-api.yaml
- title: Talent Acquisition Workflow
  type: NaftikoCapability
  url: capabilities/talent-acquisition.yaml
created: '2025-01-01'
description: Indeed is the world's largest job site, connecting millions of job seekers with employers across industries and locations worldwide. Indeed offers a suite of APIs for applicant tracking systems, job boards, and hiring platforms to integrate with its employment ecosystem.
features:
- description: Search millions of job listings by keyword, location, salary, and other criteria across industries worldwide.
  name: Job Search and Discovery
- description: Post and syndicate job listings from ATS platforms to Indeed's marketplace with automated synchronization.
  name: Job Posting and Syndication
- description: Retrieve and manage candidate applications, track disposition status, and sync hiring data with ATS systems.
  name: Candidate Management
- description: Create and manage pay-per-click sponsored job campaigns with budget controls and performance analytics.
  name: Sponsored Job Campaigns
- description: Enable one-click job applications directly through Indeed with screener questions and EEO compliance.
  name: Indeed Apply Integration
- description: Track candidate events from Indeed to employer sites for analytics, reporting, and bidding optimization.
  name: Conversion Tracking
- description: Stream server-sent events for instant application updates and job lifecycle notifications.
  name: Real-Time Event Streaming
image: https://www.indeed.com/images/indeed-logo.png
integrations:
- description: Native ATS integration for job posting synchronization and candidate data exchange with Greenhouse.
  name: Greenhouse
- description: Pre-built integration for posting jobs and retrieving candidate applications through Lever ATS.
  name: Lever
- description: Enterprise integration for syncing job postings and candidate data with Workday Recruiting.
  name: Workday
- description: Integration for job distribution and candidate management through iCIMS talent acquisition platform.
  name: iCIMS
- description: Connector for job posting and candidate synchronization with SAP SuccessFactors Recruiting.
  name: SAP SuccessFactors
- description: Integration for distributing jobs and managing candidates through Oracle Taleo ATS.
  name: Oracle Taleo
jsonld:
- class_count: 0
  name: Indeed Context
  property_count: 14
  slug: indeed-context
- class_count: 0
  name: Indeed Employer Context
  property_count: 0
  slug: indeed-employer-context
layout: provider
modified: '2026-04-18'
name: Indeed
rules:
- name: Indeed API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: indeed-spectral-rules
skills: []
slug: indeed
solutions: []
source_filename: apis.yml
source_yaml: "aid: indeed\nname: Indeed\ndescription: Indeed is the world's largest job site, connecting millions of job seekers with employers across industries and locations worldwide. Indeed offers a suite of APIs for applicant tracking systems, job boards, and hiring platforms to integrate with its employment ecosystem.\nimage: https://www.indeed.com/images/indeed-logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/indeed/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\naccess: 3rd-Party\ntags:\n  - Careers\n  - Employment\n  - Hiring\n  - Job Search\n  - Jobs\n  - Recruiting\napis:\n  - aid: indeed:job-search\n    name: Indeed Job Search API\n    description: Search for jobs by keyword, location, and other criteria. Returns job listings with details including title, company, location, and description. This API is deprecated and not available for new integrations.\n    image: https://www.indeed.com/images/indeed-logo.png\n\
  \    humanURL: https://developer.indeed.com/docs/publisher-jobs/job-search\n    baseURL: https://api.indeed.com\n    tags:\n      - Deprecated\n      - Jobs\n      - Listings\n      - Search\n    properties:\n      - type: Documentation\n        url: https://opensource.indeedeng.io/api-documentation/docs/job-search/\n    contact:\n      - FN: Indeed API Support\n        email: opensource@indeed.com\n        url: https://opensource.indeedeng.io/\n  - aid: indeed:publisher\n    name: Indeed Publisher API\n    description: Monetize your website by displaying Indeed job listings. Earn revenue through cost-per-click advertising.\n    image: https://www.indeed.com/images/indeed-logo.png\n    humanURL: https://www.indeed.com/publisher\n    baseURL: https://api.indeed.com/ads\n    tags:\n      - Advertising\n      - Monetization\n      - Publisher\n    properties:\n      - type: Documentation\n        url: https://www.indeed.com/publisher/docs\n      - type: SignUp\n        url: https://www.indeed.com/publisher/signup\n\
  \  - aid: indeed:apply\n    name: Indeed Apply API\n    description: Allow job seekers to apply to your jobs directly through Indeed with a streamlined application process. Supports screener questions, EEO compliance for US employers, and disposition data integration.\n    image: https://www.indeed.com/images/indeed-logo.png\n    humanURL: https://docs.indeed.com/indeed-apply\n    baseURL: https://api.indeed.com/apply\n    tags:\n      - Applications\n      - Apply\n      - Hiring\n    properties:\n      - type: Documentation\n        url: https://docs.indeed.com/indeed-apply\n      - type: GettingStarted\n        url: https://docs.indeed.com/indeed-apply/add-indeed-apply\n  - aid: indeed:job-sync\n    name: Indeed Job Sync API\n    description: A GraphQL API that enables ATS partners to create, upsert, expire, and get status for job postings on Indeed. Supports qualifications, working hours, salary, benefits, and employer information.\n    image: https://www.indeed.com/images/indeed-logo.png\n\
  \    humanURL: https://docs.indeed.com/job-sync-api/\n    baseURL: https://apis.indeed.com/graphql\n    tags:\n      - ATS\n      - GraphQL\n      - Jobs\n      - Postings\n    properties:\n      - type: Documentation\n        url: https://docs.indeed.com/job-sync-api/\n      - type: GettingStarted\n        url: https://docs.indeed.com/job-sync-api/job-sync-api-guide\n      - type: FAQ\n        url: https://docs.indeed.com/job-sync-api/reference/faq\n      - type: Sandbox\n        url: https://docs.indeed.com/getstarted/simulated-graphql-environment\n      - type: OpenAPI\n        url: openapi/indeed-employer-api-openapi.yml\n      - type: JSONLD\n        url: json-ld/indeed-context.jsonld\n  - aid: indeed:disposition-sync\n    name: Indeed Disposition Sync API\n    description: A GraphQL API that enables ATS partners to send disposition data for Indeed Apply and non-Indeed Apply jobs to Indeed, tracking application status changes through various stages of the hiring process.\n    image:\
  \ https://www.indeed.com/images/indeed-logo.png\n    humanURL: https://docs.indeed.com/disposition-sync-api/\n    baseURL: https://apis.indeed.com/graphql\n    tags:\n      - Applications\n      - ATS\n      - Disposition\n      - GraphQL\n      - Tracking\n    properties:\n      - type: Documentation\n        url: https://docs.indeed.com/disposition-sync-api/\n      - type: GettingStarted\n        url: https://docs.indeed.com/disposition-sync-api/disposition-sync-api-guide\n  - aid: indeed:sponsored-jobs\n    name: Indeed Sponsored Jobs API\n    description: A GraphQL API used to get information about and manage an employer's sponsored job campaigns on Indeed, including campaign creation, budget management, and performance insights.\n    image: https://www.indeed.com/images/indeed-logo.png\n    humanURL: https://docs.indeed.com/sponsored-jobs-api/\n    baseURL: https://apis.indeed.com/graphql\n    tags:\n      - Advertising\n      - Campaigns\n      - GraphQL\n      - Sponsored\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.indeed.com/sponsored-jobs-api/\n      - type: GettingStarted\n        url: https://docs.indeed.com/sponsored-jobs-api/sponsored-jobs-api-1-guides/get-started\n      - type: APIReference\n        url: https://docs.indeed.com/api/sponsored-jobs-api/sponsored-jobs-api-reference\n  - aid: indeed:job-update\n    name: Indeed Job Update API\n    description: Allows partners to list and update job postings on Indeed, including adding metadata to ATS-sourced jobs for improved quality and sponsorship grouping, and subscribing to jobs lifecycle events via webhooks.\n    image: https://www.indeed.com/images/indeed-logo.png\n    humanURL: https://docs.indeed.com/job-update-api/\n    baseURL: https://apis.indeed.com/graphql\n    tags:\n      - GraphQL\n      - Jobs\n      - Updates\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://docs.indeed.com/job-update-api/\n  - aid: indeed:real-time\n    name: Indeed Real-time\
  \ API\n    description: Stream real-time server-sent events (SSE) to enable front-end applications to update instantly, supporting event filtering, deduplication, and latency tracking.\n    image: https://www.indeed.com/images/indeed-logo.png\n    humanURL: https://docs.indeed.com/real-time-api/get-started\n    baseURL: https://apis.indeed.com\n    tags:\n      - Events\n      - Real-Time\n      - SSE\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://docs.indeed.com/api/real-time-api/indeed-real-time-api\n      - type: GettingStarted\n        url: https://docs.indeed.com/real-time-api/get-started\n  - aid: indeed:interview\n    name: Indeed Interview API\n    description: A GraphQL API for scheduling, updating, retrieving information about, and canceling virtual interview events with job candidates. This API is deprecated.\n    image: https://www.indeed.com/images/indeed-logo.png\n    humanURL: https://docs.indeed.com/indeed-interview-api\n    baseURL:\
  \ https://apis.indeed.com/graphql\n    tags:\n      - Deprecated\n      - GraphQL\n      - Interviews\n      - Scheduling\n      - Virtual\n    properties:\n      - type: Documentation\n        url: https://docs.indeed.com/indeed-interview-api\n      - type: GettingStarted\n        url: https://docs.indeed.com/indeed-interview-api/indeed-interview-api-guide\n      - type: APIReference\n        url: https://docs.indeed.com/dev/reference/indeed-interview-api\n  - aid: indeed:employer\n    name: Indeed Employer API\n    description: A RESTful abstraction of Indeed's employer-facing partner APIs, providing unified access to employer management, candidate retrieval, and job posting operations.\n    image: https://www.indeed.com/images/indeed-logo.png\n    humanURL: https://docs.indeed.com/employers/operations/create-employer\n    baseURL: https://apis.indeed.com\n    tags:\n      - ATS\n      - Candidates\n      - Employers\n      - Jobs\n    properties:\n      - type: Documentation\n     \
  \   url: https://docs.indeed.com/employers/operations/create-employer\n      - type: OpenAPI\n        url: openapi/indeed-employer-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/indeed-candidate-schema.json\n      - type: JSONLD\n        url: json-ld/indeed-context.jsonld\n  - aid: indeed:employer-data\n    name: Indeed Employer Data API\n    description: A GraphQL API for creating and updating employer entities on Indeed and the Indeed PLUS platform.\n    image: https://www.indeed.com/images/indeed-logo.png\n    humanURL: https://docs.indeed.com/employers/operations/create-employer\n    baseURL: https://apis.indeed.com/graphql\n    tags:\n      - ATS\n      - Employers\n      - GraphQL\n    properties:\n      - type: Documentation\n        url: https://docs.indeed.com/employers/operations/create-employer\n      - type: APIReference\n        url: https://docs.indeed.com/api/employers-api/create-using-post\n      - type: Sandbox\n        url: https://docs.indeed.com/getstarted/simulated-graphql-environment\n\
  \  - aid: indeed:conversion-tracking\n    name: Indeed Conversion Tracking API\n    description: Tracks candidate events such as job application page visits and completed applications from Indeed to your site. Provides data for reporting, analytics dashboards, and apply-based bidding algorithms.\n    image: https://www.indeed.com/images/indeed-logo.png\n    humanURL: https://docs.indeed.com/conversion-tracking-api/conversion-tracking-getting-started\n    baseURL: https://apis.indeed.com\n    tags:\n      - Analytics\n      - Conversion\n      - Reporting\n      - Tracking\n    properties:\n      - type: Documentation\n        url: https://docs.indeed.com/conversion-tracking-api/conversion-tracking-getting-started\n      - type: APIReference\n        url: https://docs.indeed.com/api/conversion-tracking-api/conversion-tracking-api\n  - aid: indeed:employer-registration\n    name: Indeed Employer Registration API\n    description: Part of the Candidate Sync APIs, this API allows ATS partners\
  \ to register employers for Candidate Sync integration.\n    image: https://www.indeed.com/images/indeed-logo.png\n    humanURL: https://docs.indeed.com/candidate-sync-apis/employer-registration-api/\n    baseURL: https://apis.indeed.com/graphql\n    tags:\n      - ATS\n      - Candidate Sync\n      - Employers\n      - Registration\n    properties:\n      - type: Documentation\n        url: https://docs.indeed.com/candidate-sync-apis/employer-registration-api/\n  - aid: indeed:retrieve-candidates\n    name: Indeed Retrieve Candidates API\n    description: Part of the Candidate Sync APIs, this API enables ATS partners to get candidate and application information from Indeed on behalf of employers.\n    image: https://www.indeed.com/images/indeed-logo.png\n    humanURL: https://docs.indeed.com/candidate-sync-apis/retrieve-candidates-api/\n    baseURL: https://apis.indeed.com/graphql\n    tags:\n      - Applications\n      - ATS\n      - Candidate Sync\n      - Candidates\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.indeed.com/candidate-sync-apis/retrieve-candidates-api/\n      - type: JSONSchema\n        url: json-schema/indeed-candidate-schema.json\n      - type: JSONLD\n        url: json-ld/indeed-context.jsonld\ncommon:\n  - type: DeveloperPortal\n    url: https://opensource.indeedeng.io/\n  - type: TermsOfService\n    url: https://www.indeed.com/legal/terms-of-service\n  - type: PrivacyPolicy\n    url: https://www.indeed.com/legal/privacy\n  - type: StatusPage\n    url: https://status.indeed.com\n  - type: Support\n    url: https://support.indeed.com/hc/en-us\n  - type: Blog\n    url: https://engineering.indeedblog.com/\n  - type: GitHubOrganization\n    url: https://github.com/indeedeng\n  - type: X\n    url: https://twitter.com/indeedeng\n  - type: RateLimits\n    url: https://opensource.indeedeng.io/api-documentation/docs/rate-limits\n  - type: Authentication\n    url: https://docs.indeed.com/authorization/\n  - type: GettingStarted\n\
  \    url: https://docs.indeed.com/getstarted/\n  - type: ReleaseNotes\n    url: https://docs.indeed.com/release-notes/\n  - type: Sandbox\n    url: https://docs.indeed.com/getstarted/simulated-graphql-environment\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/indeed-com/\n  - type: NaftikoCapability\n    url: capabilities/shared/employer-api.yaml\n    title: Employer API Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/talent-acquisition.yaml\n    title: Talent Acquisition Workflow\n  - type: Features\n    data:\n      - name: Job Search and Discovery\n        description: Search millions of job listings by keyword, location, salary, and other criteria across industries worldwide.\n      - name: Job Posting and Syndication\n        description: Post and syndicate job listings from ATS platforms to Indeed's marketplace with automated synchronization.\n      - name: Candidate Management\n        description: Retrieve and manage candidate applications,\
  \ track disposition status, and sync hiring data with ATS systems.\n      - name: Sponsored Job Campaigns\n        description: Create and manage pay-per-click sponsored job campaigns with budget controls and performance analytics.\n      - name: Indeed Apply Integration\n        description: Enable one-click job applications directly through Indeed with screener questions and EEO compliance.\n      - name: Conversion Tracking\n        description: Track candidate events from Indeed to employer sites for analytics, reporting, and bidding optimization.\n      - name: Real-Time Event Streaming\n        description: Stream server-sent events for instant application updates and job lifecycle notifications.\n  - type: UseCases\n    data:\n      - name: ATS Job Distribution\n        description: Automatically distribute job postings from applicant tracking systems to Indeed's marketplace with real-time synchronization.\n      - name: Candidate Pipeline Management\n        description: Retrieve\
  \ and manage candidates through the hiring pipeline with disposition tracking and status updates.\n      - name: Recruitment Marketing Analytics\n        description: Track campaign performance, application conversions, and ROI across sponsored and organic job listings.\n      - name: Employer Branding\n        description: Create and manage employer profiles on Indeed to attract candidates with company information and branding.\n      - name: High-Volume Hiring\n        description: Scale recruitment operations with automated job posting, candidate retrieval, and application processing.\n  - type: Integrations\n    data:\n      - name: Greenhouse\n        description: Native ATS integration for job posting synchronization and candidate data exchange with Greenhouse.\n      - name: Lever\n        description: Pre-built integration for posting jobs and retrieving candidate applications through Lever ATS.\n      - name: Workday\n        description: Enterprise integration for syncing job\
  \ postings and candidate data with Workday Recruiting.\n      - name: iCIMS\n        description: Integration for job distribution and candidate management through iCIMS talent acquisition platform.\n      - name: SAP SuccessFactors\n        description: Connector for job posting and candidate synchronization with SAP SuccessFactors Recruiting.\n      - name: Oracle Taleo\n        description: Integration for distributing jobs and managing candidates through Oracle Taleo ATS.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/indeed/refs/heads/main/apis.yml
tags:
- Careers
- Employment
- Hiring
- Job Search
- Jobs
- Recruiting
url: https://raw.githubusercontent.com/api-evangelist/indeed/refs/heads/main/apis.yml
use_cases:
- description: Automatically distribute job postings from applicant tracking systems to Indeed's marketplace with real-time synchronization.
  name: ATS Job Distribution
- description: Retrieve and manage candidates through the hiring pipeline with disposition tracking and status updates.
  name: Candidate Pipeline Management
- description: Track campaign performance, application conversions, and ROI across sponsored and organic job listings.
  name: Recruitment Marketing Analytics
- description: Create and manage employer profiles on Indeed to attract candidates with company information and branding.
  name: Employer Branding
- description: Scale recruitment operations with automated job posting, candidate retrieval, and application processing.
  name: High-Volume Hiring
---
