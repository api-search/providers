---
api_count: 2
apis:
- description: Manage your DoubleClick Campaign Manager ad campaigns and reports programmatically. Create, retrieve, update, and delete campaigns, creatives, placements, and generate comprehensive reporting data.
  name: Campaign Manager 360 API
  slug: ''
- description: Data Transfer v2.0 provides raw, event-level reporting data from Campaign Manager 360 beyond what is available through standard reporting. Data is delivered to Google Cloud Storage as CSV files for ad
  name: Campaign Manager 360 Data Transfer v2.0
  slug: ''
capabilities:
- description: Unified workflow for managing digital advertising campaigns, ads, placements, and performance reports. Used by ad operations specialists and digital marketers.
  name: Google Campaign Manager Campaign Management
  slug: campaign-management
common:
- title: ''
  type: Portal
  url: https://developers.google.com/
- title: ''
  type: Authentication
  url: https://developers.google.com/identity/protocols/oauth2
- title: ''
  type: Blog
  url: https://blog.google/products/marketingplatform/
- title: ''
  type: StatusPage
  url: https://status.cloud.google.com/
- title: ''
  type: PrivacyPolicy
  url: https://policies.google.com/privacy
- title: ''
  type: TermsOfService
  url: https://policies.google.com/terms
- title: ''
  type: GitHubRepository
  url: https://github.com/googleads/googleads-dfa-reporting-samples
- title: ''
  type: JSONLD
  url: json-ld/google-campaign-manager-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/google-campaign-manager-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/google-campaign-manager-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/campaign-management.yaml
created: '2024'
description: The Campaign Manager 360 API allows developers to programmatically manage campaigns, creatives, reports, and other advertising operations in Google's Campaign Manager 360 platform.
features:
- description: Create, update, and manage advertising campaigns from inception through completion with full programmatic control.
  name: Campaign Lifecycle Management
- description: Automate the placement and scheduling of ads across publisher sites with targeting and delivery rules.
  name: Ad Trafficking
- description: Generate standard, reach, path-to-conversion, cross-dimension, floodlight, and cross-media reach reports.
  name: Multi-Format Reporting
- description: Automatically generate ad tags for publishers to install on their pages.
  name: Placement Tag Generation
- description: Configure geo-targeting, technology targeting, day-part targeting, and audience segment rules.
  name: Audience Targeting
- description: Track and attribute conversions using Floodlight tags for cross-channel measurement.
  name: Floodlight Conversion Tracking
image: https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png
integrations:
- description: Combine Campaign Manager 360 data with Google Analytics for unified web analytics and attribution.
  name: Google Analytics
- description: Coordinate campaign management between Campaign Manager 360 and Google Ads platforms.
  name: Google Ads
- description: Integrate with DV360 for programmatic buying and campaign execution.
  name: Display & Video 360
- description: Export raw event-level data via Data Transfer for advanced analysis in BigQuery or other tools.
  name: Google Cloud Storage
- description: Automate Campaign Manager operations using Google Apps Script advanced service.
  name: Google Apps Script
jsonld:
- class_count: 0
  name: Google Campaign Manager Context
  property_count: 0
  slug: google-campaign-manager-context
layout: provider
modified: '2026-04-18'
name: Google Campaign Manager
rules:
- name: Google Campaign Manager API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: google-campaign-manager-spectral-rules
skills: []
slug: google-campaign-manager
solutions: []
source_yaml: "aid: google-campaign-manager\nname: Google Campaign Manager\ndescription: >-\n  The Campaign Manager 360 API allows developers to programmatically manage\n  campaigns, creatives, reports, and other advertising operations in Google's\n  Campaign Manager 360 platform.\nimage: https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png\nurl: https://developers.google.com/doubleclick-advertisers\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Advertising\n  - Analytics\n  - Campaign Management\n  - Digital Marketing\n  - Reporting\napis:\n  - name: Campaign Manager 360 API\n    description: >-\n      Manage your DoubleClick Campaign Manager ad campaigns and reports\n      programmatically. Create, retrieve, update, and delete campaigns,\n      creatives, placements, and generate comprehensive reporting data.\n    image: https://www.gstatic.com/images/branding/product/2x/googleg_48dp.png\n    humanURL: https://developers.google.com/doubleclick-advertisers\n\
  \    baseURL: https://dfareporting.googleapis.com\n    tags:\n      - Advertising\n      - Analytics\n      - Campaign Management\n      - Conversions\n      - Creatives\n      - Digital Marketing\n      - Floodlight\n      - Placements\n      - Reporting\n      - Trafficking\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/doubleclick-advertisers/v4\n      - type: Documentation\n        url: https://developers.google.com/doubleclick-advertisers/rest\n      - type: OpenAPI\n        url: openapi/google-campaign-manager-openapi.yml\n      - type: OpenAPI\n        url: https://dfareporting.googleapis.com/$discovery/rest?version=v4\n      - type: OpenAPI\n        url: https://dfareporting.googleapis.com/$discovery/rest?version=v5\n      - type: Authentication\n        url: https://developers.google.com/doubleclick-advertisers/guides/authorizing\n      - type: Pricing\n        url: https://marketingplatform.google.com/about/campaign-manager-360/pricing/\n\
  \      - type: Quickstart\n        url: https://developers.google.com/doubleclick-advertisers/getting_started\n      - type: Support\n        url: https://support.google.com/campaignmanager\n      - type: Console\n        url: https://console.cloud.google.com/apis/library/dfareporting.googleapis.com\n      - type: TermsOfService\n        url: https://developers.google.com/terms\n      - type: RateLimits\n        url: https://developers.google.com/doubleclick-advertisers/quotas\n      - type: ReleaseNotes\n        url: https://developers.google.com/doubleclick-advertisers/rel_notes\n      - type: SDK\n        url: https://developers.google.com/doubleclick-advertisers/libraries\n        title: Client Libraries\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-campaign-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-ad-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-placement-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/google-campaign-manager-report-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-report-criteria-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-report-reach-criteria-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-report-path-to-conversion-criteria-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-report-cross-dimension-reach-criteria-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-report-floodlight-criteria-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-report-cross-media-reach-criteria-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-report-schedule-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-report-delivery-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/google-campaign-manager-recipient-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-file-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-size-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-date-range-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-sorted-dimension-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-activities-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-custom-rich-media-events-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-dimension-value-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-last-modified-info-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-audience-segment-group-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/google-campaign-manager-audience-segment-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-event-tag-override-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-click-through-url-suffix-properties-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-default-click-through-event-tag-properties-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-click-through-url-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-creative-optimization-configuration-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-optimization-activity-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-ad-blocking-configuration-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-measurement-partner-link-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/google-campaign-manager-measurement-partner-wrapping-data-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-conversion-domain-override-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-placement-assignment-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-creative-rotation-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-creative-assignment-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-delivery-schedule-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-frequency-cap-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-geo-targeting-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-country-schema.json\n      - type: JSONSchema\n      \
  \  url: json-schema/google-campaign-manager-region-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-city-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-metro-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-postal-code-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-technology-targeting-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-browser-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-platform-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-operating-system-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-operating-system-version-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-mobile-carrier-schema.json\n      - type: JSONSchema\n\
  \        url: json-schema/google-campaign-manager-connection-type-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-day-part-targeting-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-pricing-schedule-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-pricing-schedule-pricing-period-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-video-settings-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-lookback-configuration-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-tag-setting-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-placement-tag-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-campaigns-list-response-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-ads-list-response-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/google-campaign-manager-placements-list-response-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-placements-generate-tags-response-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-reports-list-response-schema.json\n      - type: JSONSchema\n        url: json-schema/google-campaign-manager-error-schema.json\n      - type: JSONLD\n        url: json-ld/google-campaign-manager-context.jsonld\n    contact:\n      - type: Support\n        url: https://support.google.com/campaignmanager/contact/cm360_api_support\n  - name: Campaign Manager 360 Data Transfer v2.0\n    description: >-\n      Data Transfer v2.0 provides raw, event-level reporting data from Campaign\n      Manager 360 beyond what is available through standard reporting. Data is\n      delivered to Google Cloud Storage as CSV files for advanced analysis and\n      data warehousing use cases.\n    image:\
  \ https://www.gstatic.com/images/branding/product/2x/googleg_48dp.png\n    humanURL: https://developers.google.com/doubleclick-advertisers/dtv2/overview\n    tags:\n      - Analytics\n      - Cloud Storage\n      - CSV\n      - Data Transfer\n      - Raw Data\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/doubleclick-advertisers/dtv2/overview\n      - type: Quickstart\n        url: https://developers.google.com/doubleclick-advertisers/dtv2/getting-started\n      - type: FAQ\n        url: https://developers.google.com/doubleclick-advertisers/dtv2/reference/faq\n      - type: ReleaseNotes\n        url: https://developers.google.com/doubleclick-advertisers/dtv2/reference/release-notes\n      - type: Support\n        url: https://developers.google.com/doubleclick-advertisers/dtv2/get-support\ncommon:\n  - type: Portal\n    url: https://developers.google.com/\n  - type: Authentication\n    url: https://developers.google.com/identity/protocols/oauth2\n\
  \  - type: Blog\n    url: https://blog.google/products/marketingplatform/\n  - type: StatusPage\n    url: https://status.cloud.google.com/\n  - type: PrivacyPolicy\n    url: https://policies.google.com/privacy\n  - type: TermsOfService\n    url: https://policies.google.com/terms\n  - type: GitHubRepository\n    url: https://github.com/googleads/googleads-dfa-reporting-samples\n  - type: JSONLD\n    url: json-ld/google-campaign-manager-context.jsonld\n  - type: SpectralRules\n    url: rules/google-campaign-manager-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/google-campaign-manager-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/campaign-management.yaml\n  - type: Features\n    data:\n      - name: Campaign Lifecycle Management\n        description: Create, update, and manage advertising campaigns from inception through completion with full programmatic control.\n      - name: Ad Trafficking\n        description: Automate the placement and scheduling\
  \ of ads across publisher sites with targeting and delivery rules.\n      - name: Multi-Format Reporting\n        description: Generate standard, reach, path-to-conversion, cross-dimension, floodlight, and cross-media reach reports.\n      - name: Placement Tag Generation\n        description: Automatically generate ad tags for publishers to install on their pages.\n      - name: Audience Targeting\n        description: Configure geo-targeting, technology targeting, day-part targeting, and audience segment rules.\n      - name: Floodlight Conversion Tracking\n        description: Track and attribute conversions using Floodlight tags for cross-channel measurement.\n  - type: UseCases\n    data:\n      - name: Programmatic Campaign Setup\n        description: Automate the creation and configuration of advertising campaigns, ads, and placements across publisher inventory.\n      - name: Performance Reporting\n        description: Generate and schedule reports to analyze campaign performance,\
  \ reach, and conversion data.\n      - name: Cross-Channel Attribution\n        description: Use path-to-conversion and cross-media reach reports to understand multi-channel advertising impact.\n      - name: Ad Operations Automation\n        description: Streamline trafficking workflows including placement creation, tag generation, and creative assignment.\n  - type: Integrations\n    data:\n      - name: Google Analytics\n        description: Combine Campaign Manager 360 data with Google Analytics for unified web analytics and attribution.\n      - name: Google Ads\n        description: Coordinate campaign management between Campaign Manager 360 and Google Ads platforms.\n      - name: Display & Video 360\n        description: Integrate with DV360 for programmatic buying and campaign execution.\n      - name: Google Cloud Storage\n        description: Export raw event-level data via Data Transfer for advanced analysis in BigQuery or other tools.\n      - name: Google Apps Script\n  \
  \      description: Automate Campaign Manager operations using Google Apps Script advanced service.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-campaign-manager/refs/heads/main/apis.yml
tags:
- Advertising
- Analytics
- Campaign Management
- Digital Marketing
- Reporting
url: https://developers.google.com/doubleclick-advertisers
use_cases:
- description: Automate the creation and configuration of advertising campaigns, ads, and placements across publisher inventory.
  name: Programmatic Campaign Setup
- description: Generate and schedule reports to analyze campaign performance, reach, and conversion data.
  name: Performance Reporting
- description: Use path-to-conversion and cross-media reach reports to understand multi-channel advertising impact.
  name: Cross-Channel Attribution
- description: Streamline trafficking workflows including placement creation, tag generation, and creative assignment.
  name: Ad Operations Automation
---
