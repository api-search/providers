---
api_count: 3
apis:
- description: Provides access to Search Console data including search analytics, sitemaps, URL inspection, and index coverage reports.
  name: Google Search Console API
  slug: ''
- description: Provides tools for running validation tests against single URLs, including mobile-friendly testing and rich results validation for structured data.
  name: Google Search Console URL Testing Tools API
  slug: ''
- description: The Indexing API allows any site owner to directly notify Google when pages are added or removed, enabling faster crawling and indexing of content such as job postings and livestream videos.
  name: Google Indexing API
  slug: ''
capabilities:
- description: Unified SEO management workflow combining search analytics, sitemap management, URL inspection, and site management for SEO specialists and webmasters.
  name: Google Search Console SEO Management
  slug: seo-management
common:
- title: ''
  type: DeveloperPortal
  url: https://developers.google.com/
- title: ''
  type: StatusPage
  url: https://status.cloud.google.com/
- title: ''
  type: Blog
  url: https://developers.googleblog.com/
- title: ''
  type: PrivacyPolicy
  url: https://policies.google.com/privacy
- title: ''
  type: TermsOfService
  url: https://policies.google.com/terms
- title: OAuth 2.0 Scopes
  type: Authentication
  url: https://developers.google.com/identity/protocols/oauth2/scopes
- title: API Client Libraries
  type: SDK
  url: https://developers.google.com/api-client-library
- title: Google Search Central Blog
  type: Blog
  url: https://developers.google.com/search/updates
- title: Search Console Help
  type: Support
  url: https://support.google.com/webmasters/
- title: ''
  type: Console
  url: https://console.cloud.google.com/
- title: ''
  type: SpectralRules
  url: rules/google-search-console-spectral-rules.yml
- title: Search Console Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/search-console.yaml
- title: SEO Management Workflow
  type: NaftikoCapability
  url: capabilities/seo-management.yaml
created: '2024-01-01'
description: The Google Search Console API provides programmatic access to Search Console data, allowing you to monitor and maintain your site's presence in Google Search results.
features:
- description: Analyze search traffic data including impressions, clicks, CTR, and average position by query, page, country, device, and date.
  name: Search Analytics
- description: Submit, monitor, and manage XML sitemaps and sitemap indexes to optimize crawling and indexing.
  name: Sitemap Management
- description: Inspect individual URLs for indexing status, crawl details, mobile usability, and rich results eligibility.
  name: URL Inspection
- description: Monitor which pages are indexed, identify indexing errors, and track coverage status across your site.
  name: Index Coverage
- description: Test pages for mobile-friendliness and identify mobile usability issues.
  name: Mobile Usability Testing
- description: Validate structured data markup and check rich results eligibility for individual URLs.
  name: Rich Results Validation
- description: Manage site ownership verification and access permissions for Search Console properties.
  name: Site Verification
image: https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png
integrations:
- description: Combine Search Console data with Google Analytics for comprehensive website performance analysis.
  name: Google Analytics
- description: Connect search performance data with advertising campaigns to optimize paid and organic strategy together.
  name: Google Ads
- description: Deploy Search Console API integrations on Google Cloud Platform infrastructure.
  name: Google Cloud
- description: Export Search Console data to BigQuery for advanced analytics and cross-platform reporting.
  name: BigQuery
- description: Visualize Search Console metrics in dashboards for stakeholder reporting and trend analysis.
  name: Data Studio / Looker
jsonld:
- class_count: 0
  name: Google Search Console Context
  property_count: 0
  slug: google-search-console-context
layout: provider
modified: '2026-04-18'
name: Google Search Console
rules:
- name: Google Search Console API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: google-search-console-spectral-rules
skills: []
slug: google-search-console
solutions: []
source_yaml: "aid: google-search-console\nname: Google Search Console\ndescription: The Google Search Console API provides programmatic access to Search Console data, allowing you to monitor and maintain your site's presence in Google Search results.\nimage: https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png\nurl: https://search.google.com/search-console/about\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Analytics\n  - Google\n  - Search\n  - SEO\n  - Webmaster Tools\napis:\n  - name: Google Search Console API\n    description: Provides access to Search Console data including search analytics, sitemaps, URL inspection, and index coverage reports.\n    image: https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png\n    humanURL: https://developers.google.com/webmaster-tools\n    baseURL: https://searchconsole.googleapis.com\n    tags:\n      - Indexing\n      - Search Analytics\n\
  \      - SEO\n      - Sitemaps\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/webmaster-tools/v1/api_reference_index\n      - type: OpenAPI\n        url: openapi/google-search-console-api-openapi.yml\n      - type: Documentation\n        url: https://searchconsole.googleapis.com/$discovery/rest?version=v1\n        title: Discovery Document\n      - type: Authentication\n        url: https://developers.google.com/webmaster-tools/v1/how-tos/authorizing\n      - type: GettingStarted\n        url: https://developers.google.com/webmaster-tools/v1/quickstart\n      - type: Console\n        url: https://console.cloud.google.com/apis/library/searchconsole.googleapis.com\n      - type: Pricing\n        url: https://developers.google.com/webmaster-tools/v1/limits\n      - type: TermsOfService\n        url: https://developers.google.com/terms\n      - type: CodeExamples\n        url: https://developers.google.com/webmaster-tools/v1/samples\n      - type:\
  \ ChangeLog\n        url: https://developers.google.com/webmaster-tools/v1/release-notes\n      - type: Support\n        url: https://support.google.com/webmasters/\n      - type: Documentation\n        url: https://developers.google.com/webmaster-tools/about\n        title: Overview\n      - type: Documentation\n        url: https://developers.google.com/webmaster-tools/v1/prereqs\n        title: Prerequisites\n      - type: Quickstart\n        url: https://developers.google.com/webmaster-tools/v1/quickstart/quickstart-python\n        title: Python Quickstart\n      - type: SDK\n        url: https://developers.google.com/webmaster-tools/v1/libraries\n        title: Client Libraries\n      - type: Documentation\n        url: https://developers.google.com/webmaster-tools/v1/how-tos/search_analytics\n        title: Search Analytics Guide\n      - type: APIReference\n        url: https://developers.google.com/webmaster-tools/v1/searchanalytics/query\n        title: Search Analytics Query\n\
  \      - type: APIReference\n        url: https://developers.google.com/webmaster-tools/v1/sitemaps\n        title: Sitemaps Reference\n      - type: APIReference\n        url: https://developers.google.com/webmaster-tools/v1/sitemaps/get\n        title: Sitemaps Get\n      - type: APIReference\n        url: https://developers.google.com/webmaster-tools/v1/sitemaps/submit\n        title: Sitemaps Submit\n      - type: APIReference\n        url: https://developers.google.com/webmaster-tools/v1/sites/get\n        title: Sites Get\n      - type: APIReference\n        url: https://developers.google.com/webmaster-tools/v1/urlInspection.index/inspect\n        title: URL Inspection\n      - type: APIReference\n        url: https://developers.google.com/webmaster-tools/v1/urlInspection.index/UrlInspectionResult\n        title: URL Inspection Result\n      - type: JSONSchema\n        url: json-schema/google-search-console-query-schema.json\n      - type: JSONLD\n        url: json-ld/google-search-console-context.jsonld\n\
  \  - name: Google Search Console URL Testing Tools API\n    description: Provides tools for running validation tests against single URLs, including mobile-friendly testing and rich results validation for structured data.\n    image: https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png\n    humanURL: https://developers.google.com/webmaster-tools/search-console-api\n    baseURL: https://searchconsole.googleapis.com\n    tags:\n      - Mobile Friendly\n      - Rich Results\n      - Structured Data\n      - Testing\n      - Validation\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/webmaster-tools/search-console-api/v1/\n      - type: Documentation\n        url: https://developers.google.com/webmaster-tools/search-console-api/about\n        title: About\n      - type: Documentation\n        url: https://search.google.com/test/rich-results\n        title: Rich Results Test\n  - name: Google Indexing API\n    description:\
  \ The Indexing API allows any site owner to directly notify Google when pages are added or removed, enabling faster crawling and indexing of content such as job postings and livestream videos.\n    image: https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png\n    humanURL: https://developers.google.com/search/apis/indexing-api/v3/quickstart\n    baseURL: https://indexing.googleapis.com\n    tags:\n      - Crawling\n      - Indexing\n      - SEO\n      - URL Submission\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/search/apis/indexing-api/v3/reference/indexing/rest\n      - type: GettingStarted\n        url: https://developers.google.com/search/apis/indexing-api/v3/quickstart\n      - type: Tutorials\n        url: https://developers.google.com/search/apis/indexing-api/v3/using-api\n        title: How-To Guide\n      - type: Documentation\n        url: https://developers.google.com/search/apis/indexing-api/v3/prereqs\n\
  \        title: Prerequisites\n      - type: Pricing\n        url: https://developers.google.com/search/apis/indexing-api/v3/quota-pricing\n        title: Quota and Pricing\n      - type: SDK\n        url: https://developers.google.com/search/apis/indexing-api/v3/libraries\n        title: Client Libraries\n      - type: APIReference\n        url: https://developers.google.com/search/apis/indexing-api/v3/reference/indexing/rpc\n        title: RPC Reference\n      - type: APIReference\n        url: https://developers.google.com/search/apis/indexing-api/v3/reference/indexing/rest/v3/urlNotifications/publish\n        title: Publish Method\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: DeveloperPortal\n    url: https://developers.google.com/\n  - type: StatusPage\n    url: https://status.cloud.google.com/\n  - type: Blog\n    url: https://developers.googleblog.com/\n  - type: PrivacyPolicy\n    url: https://policies.google.com/privacy\n  - type: TermsOfService\n\
  \    url: https://policies.google.com/terms\n  - type: Authentication\n    url: https://developers.google.com/identity/protocols/oauth2/scopes\n    title: OAuth 2.0 Scopes\n  - type: SDK\n    url: https://developers.google.com/api-client-library\n    title: API Client Libraries\n  - type: Blog\n    url: https://developers.google.com/search/updates\n    title: Google Search Central Blog\n  - type: Support\n    url: https://support.google.com/webmasters/\n    title: Search Console Help\n  - type: Console\n    url: https://console.cloud.google.com/\n  - type: SpectralRules\n    url: rules/google-search-console-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/shared/search-console.yaml\n    title: Search Console Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/seo-management.yaml\n    title: SEO Management Workflow\n  - type: Features\n    url: https://search.google.com/search-console/about\n    data:\n      - name: Search Analytics\n        description:\
  \ Analyze search traffic data including impressions, clicks, CTR, and average position by query, page, country, device, and date.\n      - name: Sitemap Management\n        description: Submit, monitor, and manage XML sitemaps and sitemap indexes to optimize crawling and indexing.\n      - name: URL Inspection\n        description: Inspect individual URLs for indexing status, crawl details, mobile usability, and rich results eligibility.\n      - name: Index Coverage\n        description: Monitor which pages are indexed, identify indexing errors, and track coverage status across your site.\n      - name: Mobile Usability Testing\n        description: Test pages for mobile-friendliness and identify mobile usability issues.\n      - name: Rich Results Validation\n        description: Validate structured data markup and check rich results eligibility for individual URLs.\n      - name: Site Verification\n        description: Manage site ownership verification and access permissions for Search\
  \ Console properties.\n  - type: UseCases\n    url: https://developers.google.com/webmaster-tools\n    data:\n      - name: SEO Performance Monitoring\n        description: Track organic search performance metrics to identify trends, measure optimization impact, and report on search visibility.\n      - name: Technical SEO Auditing\n        description: Identify and resolve indexing issues, crawl errors, and mobile usability problems affecting search performance.\n      - name: Content Optimization\n        description: Analyze which queries drive traffic to specific pages and optimize content to improve rankings and click-through rates.\n      - name: Automated Sitemap Submission\n        description: Programmatically submit sitemaps when content is published or updated to accelerate indexing.\n      - name: Multi-Site Management\n        description: Monitor and manage search performance across multiple websites from a single integration.\n  - type: Integrations\n    url: https://developers.google.com/webmaster-tools\n\
  \    data:\n      - name: Google Analytics\n        description: Combine Search Console data with Google Analytics for comprehensive website performance analysis.\n      - name: Google Ads\n        description: Connect search performance data with advertising campaigns to optimize paid and organic strategy together.\n      - name: Google Cloud\n        description: Deploy Search Console API integrations on Google Cloud Platform infrastructure.\n      - name: BigQuery\n        description: Export Search Console data to BigQuery for advanced analytics and cross-platform reporting.\n      - name: Data Studio / Looker\n        description: Visualize Search Console metrics in dashboards for stakeholder reporting and trend analysis.\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-search-console/refs/heads/main/apis.yml
tags:
- Analytics
- Google
- Search
- SEO
- Webmaster Tools
url: https://search.google.com/search-console/about
use_cases:
- description: Track organic search performance metrics to identify trends, measure optimization impact, and report on search visibility.
  name: SEO Performance Monitoring
- description: Identify and resolve indexing issues, crawl errors, and mobile usability problems affecting search performance.
  name: Technical SEO Auditing
- description: Analyze which queries drive traffic to specific pages and optimize content to improve rankings and click-through rates.
  name: Content Optimization
- description: Programmatically submit sitemaps when content is published or updated to accelerate indexing.
  name: Automated Sitemap Submission
- description: Monitor and manage search performance across multiple websites from a single integration.
  name: Multi-Site Management
---
