---
api_count: 14
api_specs:
- filename: abstract-api-email-reputation.yaml
  format: yaml
  label: Email Reputation API
  slug: email-reputation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-email-reputation.yaml
- filename: abstract-api-phone-intelligence.yaml
  format: yaml
  label: Phone Intelligence API
  slug: phone-intelligence
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-phone-intelligence.yaml
- filename: abstract-api-ip-geolocation.yaml
  format: yaml
  label: IP Geolocation API
  slug: ip-geolocation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-ip-geolocation.yaml
- filename: abstract-api-ip-intelligence.yaml
  format: yaml
  label: IP Intelligence API
  slug: ip-intelligence
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-ip-intelligence.yaml
- filename: abstract-api-company-enrichment.yaml
  format: yaml
  label: Company Enrichment API
  slug: company-enrichment
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-company-enrichment.yaml
- filename: abstract-api-exchange-rates.yaml
  format: yaml
  label: Exchange Rates API
  slug: exchange-rates
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-exchange-rates.yaml
- filename: abstract-api-public-holidays.yaml
  format: yaml
  label: Public Holidays API
  slug: public-holidays
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-public-holidays.yaml
- filename: abstract-api-timezones.yaml
  format: yaml
  label: Timezone API
  slug: timezones
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-timezones.yaml
- filename: abstract-api-vat-validation.yaml
  format: yaml
  label: VAT Validation API
  slug: vat-validation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-vat-validation.yaml
- filename: abstract-api-iban-validation.yaml
  format: yaml
  label: IBAN Validation API
  slug: iban-validation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-iban-validation.yaml
- filename: abstract-api-website-screenshot.yaml
  format: yaml
  label: Website Screenshot API
  slug: website-screenshot
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-website-screenshot.yaml
- filename: abstract-api-image-processing.yaml
  format: yaml
  label: Image Processing API
  slug: image-processing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-image-processing.yaml
- filename: abstract-api-web-scraping.yaml
  format: yaml
  label: Web Scraping API
  slug: web-scraping
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-web-scraping.yaml
- filename: abstract-api-avatars.yaml
  format: yaml
  label: Avatars API
  slug: avatars
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/openapi/abstract-api-avatars.yaml
apis:
- description: Validate email addresses for deliverability, detect disposable or risky domains, verify SMTP/MX records, and enrich email data with sender information, breach history, and risk scoring.
  name: Email Reputation API
  slug: email-reputation
- description: Identify carrier, line type, validity, location, and get deep insights including line status, VoIP detection, and risk scoring for any phone number globally.
  name: Phone Intelligence API
  slug: phone-intelligence
- description: Geolocate any IPv4 or IPv6 address to country, region, city, coordinates, timezone, currency, and flag data covering 4 billion+ IP addresses across 250,000+ cities worldwide.
  name: IP Geolocation API
  slug: ip-geolocation
- description: Detect VPNs, proxies, Tor exit nodes, abuse potential, hosting services, relays, and mobile IPs. Also provides ASN, company, location, timezone, flag, and currency data for any IP address.
  name: IP Intelligence API
  slug: ip-intelligence
- description: Retrieve comprehensive details about businesses using their domain or email address, including name, logo, headcount, location, industry, and more.
  name: Company Enrichment API
  slug: company-enrichment
- description: Look up the latest exchange rates for 80+ currencies, convert between currencies, and retrieve historical exchange rate data using ISO 4217 currency codes.
  name: Exchange Rates API
  slug: exchange-rates
- description: Get public, local, religious, and other holidays for any country. Supports year and country filtering with comprehensive holiday metadata.
  name: Public Holidays API
  slug: public-holidays
- description: Find, convert, and manage time and timezone data across the world. Supports lookup by location or coordinates and returns local time, timezone abbreviation, UTC offset, and DST information.
  name: Timezone API
  slug: timezones
- description: Validate VAT numbers, look up current VAT rates by country, and calculate VAT-inclusive or VAT-exclusive prices to stay compliant for domestic and cross-border sales.
  name: VAT Validation API
  slug: vat-validation
- description: Determine the validity and details of International Bank Account Numbers (IBANs), including bank name, account type, and country code.
  name: IBAN Validation API
  slug: iban-validation
- description: Capture high-quality screenshots of any website with optional customizations including CSS injection, delay settings, and viewport configuration.
  name: Website Screenshot API
  slug: website-screenshot
- description: Compress, convert, and optimize images by URL or direct upload. Supports format conversion, quality adjustment, and size reduction.
  name: Image Processing API
  slug: image-processing
- description: Extract data from any website by providing the target URL. Handles JavaScript rendering and returns the full HTML content of any web page.
  name: Web Scraping API
  slug: web-scraping
- description: Create highly customizable avatar images using a person's name or initials. Supports color, font, and size customization for user profile images.
  name: Avatars API
  slug: avatars
capabilities:
- description: Unified data enrichment workflow combining IP geolocation, company enrichment, and timezone APIs. Used by product teams and data engineers to automatically enrich user profiles, personalize experience
  name: Abstract API Data Enrichment
  slug: data-enrichment
- description: Unified financial compliance workflow combining exchange rates, VAT validation, and IBAN validation APIs. Used by finance teams, e-commerce platforms, and fintech developers to automate VAT compliance
  name: Abstract API Financial Compliance
  slug: financial-compliance
- description: Unified fraud detection and risk assessment workflow combining email reputation, phone intelligence, and IP intelligence APIs. Used by security engineers, fraud analysts, and compliance teams to detec
  name: Abstract API Fraud Detection
  slug: fraud-detection
common:
- title: ''
  type: Website
  url: https://www.abstractapi.com/
- title: ''
  type: Portal
  url: https://app.abstractapi.com/
- title: ''
  type: SignUp
  url: https://app.abstractapi.com/users/signup
- title: ''
  type: Login
  url: https://app.abstractapi.com/users/login
- title: ''
  type: Pricing
  url: https://www.abstractapi.com/pricing
- title: ''
  type: Blog
  url: https://www.abstractapi.com/blog
- title: ''
  type: Documentation
  url: https://docs.abstractapi.com/
- title: ''
  type: GettingStarted
  url: https://docs.abstractapi.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/abstractapi
- title: ''
  type: TermsOfService
  url: https://www.abstractapi.com/legal/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.abstractapi.com/legal/privacy
- title: ''
  type: Authentication
  url: https://docs.abstractapi.com/
- title: ''
  type: SpectralRules
  url: rules/abstract-api-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/fraud-detection.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/data-enrichment.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/financial-compliance.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/abstract-api-vocabulary.yaml
created: '2025-02-24'
description: Abstract API is a platform that offers a wide range of API services for developers to easily integrate various functionalities into their applications. Services include IP geolocation, IP intelligence, email validation, phone validation, currency exchange, website screenshots, image processing, web scraping, company enrichment, public holidays, timezone lookup, VAT validation, IBAN validation, and user avatar generation. Abstract API provides a seamless way for developers to access powerful features without having to build them from scratch.
features:
- description: Each API uses a unique API key passed as a query parameter or Bearer token header
  name: API Key Authentication
- description: Each API offers a free tier with limited monthly requests and 1 request/second rate limit
  name: Free Tier
- description: All APIs follow a simple REST pattern with a single base URL and query parameters
  name: Simple REST API
- description: Data covers global locations with 80+ currencies, 250,000+ cities, and worldwide phone/IP coverage
  name: Global Coverage
- description: All API responses return structured JSON data with consistent error codes
  name: JSON Responses
- description: Each API is independently keyed and priced, allowing granular subscription management
  name: Modular Services
image: /assets/icons/abstract-api.png
integrations:
- description: Official JavaScript SDK for Exchange Rates, Email Validation, IP Geolocation, and Phone Validation
  name: JavaScript
- description: Official Python SDK for Exchange Rates, Email Validation, IP Geolocation, and Phone Validation
  name: Python
- description: Official PHP SDK for Exchange Rates, Email Validation, IP Geolocation, and Phone Validation
  name: PHP
jsonld:
- class_count: 1
  name: Abstract Api Company Enrichment Context
  property_count: 11
  slug: abstract-api-company-enrichment-context
- class_count: 7
  name: Abstract Api Email Reputation Context
  property_count: 42
  slug: abstract-api-email-reputation-context
- class_count: 3
  name: Abstract Api Exchange Rates Context
  property_count: 8
  slug: abstract-api-exchange-rates-context
- class_count: 1
  name: Abstract Api Iban Validation Context
  property_count: 12
  slug: abstract-api-iban-validation-context
- class_count: 1
  name: Abstract Api Image Processing Context
  property_count: 5
  slug: abstract-api-image-processing-context
- class_count: 5
  name: Abstract Api Ip Geolocation Context
  property_count: 32
  slug: abstract-api-ip-geolocation-context
- class_count: 8
  name: Abstract Api Ip Intelligence Context
  property_count: 35
  slug: abstract-api-ip-intelligence-context
- class_count: 2
  name: Abstract Api Phone Intelligence Context
  property_count: 11
  slug: abstract-api-phone-intelligence-context
- class_count: 1
  name: Abstract Api Public Holidays Context
  property_count: 12
  slug: abstract-api-public-holidays-context
- class_count: 1
  name: Abstract Api Timezones Convert Context
  property_count: 10
  slug: abstract-api-timezones-convert-context
- class_count: 1
  name: Abstract Api Timezones Current Context
  property_count: 9
  slug: abstract-api-timezones-current-context
- class_count: 3
  name: Abstract Api Vat Validation Context
  property_count: 18
  slug: abstract-api-vat-validation-context
- class_count: 1
  name: Abstract Api Web Scraping Context
  property_count: 3
  slug: abstract-api-web-scraping-context
layout: provider
modified: '2026-04-19'
name: Abstract API
rules:
- name: Abstract API API Rules
  rule_count: 34
  severity_counts:
    error: 17
    hint: 0
    info: 6
    warn: 11
  slug: abstract-api-spectral-rules
skills: []
slug: abstract-api
solutions: []
source_filename: apis.yml
source_yaml: "aid: abstract-api\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/apis.yml\nname: Abstract API\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Avatars\n- Company Enrichment\n- Contacts\n- Currencies\n- Email Validation\n- Exchange Rates\n- IBAN Validation\n- Image Processing\n- IP Geolocation\n- IP Intelligence\n- Phone Validation\n- Public Holidays\n- Screenshots\n- Timezones\n- VAT Validation\n- Web Scraping\ndescription: >-\n  Abstract API is a platform that offers a wide range of API services for\n  developers to easily integrate various functionalities into their applications.\n  Services include IP geolocation, IP intelligence, email validation, phone\n  validation, currency exchange, website screenshots, image processing, web\n  scraping, company enrichment, public holidays, timezone lookup, VAT\n  validation, IBAN validation, and user avatar generation. Abstract API provides\n\
  \  a seamless way for developers to access powerful features without having to\n  build them from scratch.\ncreated: '2025-02-24'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: abstract-api:email-reputation\n  name: Email Reputation API\n  tags:\n  - Email Validation\n  - Email Reputation\n  - Fraud Detection\n  humanURL: https://www.abstractapi.com/api/email-verification-validation-api\n  baseURL: https://emailreputation.abstractapi.com/v1/\n  properties:\n  - url: https://docs.abstractapi.com/api/email-reputation.md\n    type: Documentation\n  - url: openapi/abstract-api-email-reputation.yaml\n    type: OpenAPI\n  - url: json-schema/email-reputation-breach-info-schema.json\n    type: JSONSchema\n  - url: examples/email-reputation-breach-info-example.json\n    type: Example\n  description: >-\n    Validate email addresses for deliverability, detect disposable or risky\n    domains, verify SMTP/MX records, and enrich email data with sender\n    information, breach\
  \ history, and risk scoring.\n\n- aid: abstract-api:phone-intelligence\n  name: Phone Intelligence API\n  tags:\n  - Phone Validation\n  - Phone Intelligence\n  - Fraud Detection\n  humanURL: https://www.abstractapi.com/api/phone-validation-api\n  baseURL: https://phoneintelligence.abstractapi.com/v1/\n  properties:\n  - url: https://docs.abstractapi.com/api/phone-intelligence.md\n    type: Documentation\n  - url: openapi/abstract-api-phone-intelligence.yaml\n    type: OpenAPI\n  - url: json-schema/phone-intelligence-phone-country-schema.json\n    type: JSONSchema\n  - url: examples/phone-intelligence-phone-country-example.json\n    type: Example\n  description: >-\n    Identify carrier, line type, validity, location, and get deep insights\n    including line status, VoIP detection, and risk scoring for any phone\n    number globally.\n\n- aid: abstract-api:ip-geolocation\n  name: IP Geolocation API\n  tags:\n  - IP Geolocation\n  - IP Addresses\n  - Geolocation\n  humanURL: https://www.abstractapi.com/api/ip-geolocation-api\n\
  \  baseURL: https://ipgeolocation.abstractapi.com/v1/\n  properties:\n  - url: https://www.abstractapi.com/api/ip-geolocation-api\n    type: Documentation\n  - url: openapi/abstract-api-ip-geolocation.yaml\n    type: OpenAPI\n  - url: json-schema/ip-geolocation-currency-info-schema.json\n    type: JSONSchema\n  - url: examples/ip-geolocation-currency-info-example.json\n    type: Example\n  description: >-\n    Geolocate any IPv4 or IPv6 address to country, region, city, coordinates,\n    timezone, currency, and flag data covering 4 billion+ IP addresses across\n    250,000+ cities worldwide.\n\n- aid: abstract-api:ip-intelligence\n  name: IP Intelligence API\n  tags:\n  - IP Intelligence\n  - IP Addresses\n  - Security\n  - Fraud Detection\n  humanURL: https://www.abstractapi.com/api/ip-intelligence\n  baseURL: https://ip-intelligence.abstractapi.com/v1/\n  properties:\n  - url: https://docs.abstractapi.com/api/ip-intelligence.md\n    type: Documentation\n  - url: openapi/abstract-api-ip-intelligence.yaml\n\
  \    type: OpenAPI\n  - url: json-schema/ip-intelligence-asn-info-schema.json\n    type: JSONSchema\n  - url: examples/ip-intelligence-asn-info-example.json\n    type: Example\n  description: >-\n    Detect VPNs, proxies, Tor exit nodes, abuse potential, hosting services,\n    relays, and mobile IPs. Also provides ASN, company, location, timezone,\n    flag, and currency data for any IP address.\n\n- aid: abstract-api:company-enrichment\n  name: Company Enrichment API\n  tags:\n  - Company Enrichment\n  - Business Data\n  - Data Enrichment\n  humanURL: https://www.abstractapi.com/api/company-enrichment\n  baseURL: https://companyenrichment.abstractapi.com/v1/\n  properties:\n  - url: https://docs.abstractapi.com/api/company-enrichment.md\n    type: Documentation\n  - url: openapi/abstract-api-company-enrichment.yaml\n    type: OpenAPI\n  - url: json-schema/company-enrichment-company-enrichment-response-schema.json\n    type: JSONSchema\n  - url: examples/company-enrichment-company-enrichment-response-example.json\n\
  \    type: Example\n  description: >-\n    Retrieve comprehensive details about businesses using their domain or\n    email address, including name, logo, headcount, location, industry, and\n    more.\n\n- aid: abstract-api:exchange-rates\n  name: Exchange Rates API\n  tags:\n  - Currencies\n  - Exchange Rates\n  - Finance\n  humanURL: https://www.abstractapi.com/api/exchange-rate-api\n  baseURL: https://exchange-rates.abstractapi.com/v1/\n  properties:\n  - url: https://docs.abstractapi.com/api/exchange-rates.md\n    type: Documentation\n  - url: openapi/abstract-api-exchange-rates.yaml\n    type: OpenAPI\n  - url: json-schema/exchange-rates-convert-response-schema.json\n    type: JSONSchema\n  - url: examples/exchange-rates-convert-response-example.json\n    type: Example\n  description: >-\n    Look up the latest exchange rates for 80+ currencies, convert between\n    currencies, and retrieve historical exchange rate data using ISO 4217\n    currency codes.\n\n- aid: abstract-api:public-holidays\n\
  \  name: Public Holidays API\n  tags:\n  - Public Holidays\n  - Calendar\n  - Global Data\n  humanURL: https://www.abstractapi.com/api/holidays-api\n  baseURL: https://holidays.abstractapi.com/v1/\n  properties:\n  - url: https://docs.abstractapi.com/api/holidays.md\n    type: Documentation\n  - url: openapi/abstract-api-public-holidays.yaml\n    type: OpenAPI\n  - url: json-schema/public-holidays-holiday-schema.json\n    type: JSONSchema\n  - url: examples/public-holidays-holiday-example.json\n    type: Example\n  description: >-\n    Get public, local, religious, and other holidays for any country. Supports\n    year and country filtering with comprehensive holiday metadata.\n\n- aid: abstract-api:timezones\n  name: Timezone API\n  tags:\n  - Timezones\n  - Time\n  - Date\n  - Calendar\n  humanURL: https://www.abstractapi.com/api/time-date-timezone-api\n  baseURL: https://timezone.abstractapi.com/v1/\n  properties:\n  - url: https://docs.abstractapi.com/api/timezones.md\n    type: Documentation\n\
  \  - url: openapi/abstract-api-timezones.yaml\n    type: OpenAPI\n  - url: json-schema/timezones-convert-time-response-schema.json\n    type: JSONSchema\n  - url: examples/timezones-convert-time-response-example.json\n    type: Example\n  description: >-\n    Find, convert, and manage time and timezone data across the world.\n    Supports lookup by location or coordinates and returns local time,\n    timezone abbreviation, UTC offset, and DST information.\n\n- aid: abstract-api:vat-validation\n  name: VAT Validation API\n  tags:\n  - VAT Validation\n  - Finance\n  - Compliance\n  - Tax\n  humanURL: https://www.abstractapi.com/api/vat-validation-rates-api\n  baseURL: https://vat.abstractapi.com/v1/\n  properties:\n  - url: https://docs.abstractapi.com/api/vat-validation.md\n    type: Documentation\n  - url: openapi/abstract-api-vat-validation.yaml\n    type: OpenAPI\n  - url: json-schema/vat-validation-vat-calculate-response-schema.json\n    type: JSONSchema\n  - url: examples/vat-validation-vat-calculate-response-example.json\n\
  \    type: Example\n  description: >-\n    Validate VAT numbers, look up current VAT rates by country, and calculate\n    VAT-inclusive or VAT-exclusive prices to stay compliant for domestic and\n    cross-border sales.\n\n- aid: abstract-api:iban-validation\n  name: IBAN Validation API\n  tags:\n  - IBAN Validation\n  - Finance\n  - Banking\n  humanURL: https://www.abstractapi.com/api/iban-validation\n  baseURL: https://ibanvalidation.abstractapi.com/v1/\n  properties:\n  - url: https://docs.abstractapi.com/api/iban-validation.md\n    type: Documentation\n  - url: openapi/abstract-api-iban-validation.yaml\n    type: OpenAPI\n  - url: json-schema/iban-validation-iban-validation-response-schema.json\n    type: JSONSchema\n  - url: examples/iban-validation-iban-validation-response-example.json\n    type: Example\n  description: >-\n    Determine the validity and details of International Bank Account Numbers\n    (IBANs), including bank name, account type, and country code.\n\n- aid: abstract-api:website-screenshot\n\
  \  name: Website Screenshot API\n  tags:\n  - Screenshots\n  - Web Capture\n  - Images\n  humanURL: https://www.abstractapi.com/api/website-screenshot-api\n  baseURL: https://screenshot.abstractapi.com/v1/\n  properties:\n  - url: https://docs.abstractapi.com/api/screenshot.md\n    type: Documentation\n  - url: openapi/abstract-api-website-screenshot.yaml\n    type: OpenAPI\n  description: >-\n    Capture high-quality screenshots of any website with optional\n    customizations including CSS injection, delay settings, and viewport\n    configuration.\n\n- aid: abstract-api:image-processing\n  name: Image Processing API\n  tags:\n  - Image Processing\n  - Images\n  - Optimization\n  humanURL: https://www.abstractapi.com/api/image-processing-optimization-api\n  baseURL: https://images.abstractapi.com/v1/\n  properties:\n  - url: https://docs.abstractapi.com/api/images.md\n    type: Documentation\n  - url: openapi/abstract-api-image-processing.yaml\n    type: OpenAPI\n  - url: json-schema/image-processing-image-processing-response-schema.json\n\
  \    type: JSONSchema\n  - url: examples/image-processing-image-processing-response-example.json\n    type: Example\n  description: >-\n    Compress, convert, and optimize images by URL or direct upload. Supports\n    format conversion, quality adjustment, and size reduction.\n\n- aid: abstract-api:web-scraping\n  name: Web Scraping API\n  tags:\n  - Web Scraping\n  - Data Extraction\n  - HTML\n  humanURL: https://www.abstractapi.com/api/web-scraping-api\n  baseURL: https://scrape.abstractapi.com/v1/\n  properties:\n  - url: https://docs.abstractapi.com/api/scrape.md\n    type: Documentation\n  - url: openapi/abstract-api-web-scraping.yaml\n    type: OpenAPI\n  - url: json-schema/web-scraping-web-scraping-response-schema.json\n    type: JSONSchema\n  - url: examples/web-scraping-web-scraping-response-example.json\n    type: Example\n  description: >-\n    Extract data from any website by providing the target URL. Handles\n    JavaScript rendering and returns the full HTML content of any\
  \ web page.\n\n- aid: abstract-api:avatars\n  name: Avatars API\n  tags:\n  - Avatars\n  - Images\n  - User Interface\n  humanURL: https://www.abstractapi.com/api/user-avatar-api\n  baseURL: https://avatars.abstractapi.com/v1/\n  properties:\n  - url: https://docs.abstractapi.com/api/avatars.md\n    type: Documentation\n  - url: openapi/abstract-api-avatars.yaml\n    type: OpenAPI\n  description: >-\n    Create highly customizable avatar images using a person's name or\n    initials. Supports color, font, and size customization for user profile\n    images.\n\ncommon:\n- type: Website\n  url: https://www.abstractapi.com/\n- type: Portal\n  url: https://app.abstractapi.com/\n- type: SignUp\n  url: https://app.abstractapi.com/users/signup\n- type: Login\n  url: https://app.abstractapi.com/users/login\n- type: Pricing\n  url: https://www.abstractapi.com/pricing\n- type: Blog\n  url: https://www.abstractapi.com/blog\n- type: Documentation\n  url: https://docs.abstractapi.com/\n- type: GettingStarted\n\
  \  url: https://docs.abstractapi.com/\n- type: GitHubOrganization\n  url: https://github.com/abstractapi\n- type: TermsOfService\n  url: https://www.abstractapi.com/legal/terms\n- type: PrivacyPolicy\n  url: https://www.abstractapi.com/legal/privacy\n- type: Authentication\n  url: https://docs.abstractapi.com/\n  data:\n  - type: apiKey\n    in: query\n    name: api_key\n    description: Unique API key per service, passed as a query parameter or Bearer token\n- type: Features\n  data:\n  - name: API Key Authentication\n    description: Each API uses a unique API key passed as a query parameter or Bearer token header\n  - name: Free Tier\n    description: Each API offers a free tier with limited monthly requests and 1 request/second rate limit\n  - name: Simple REST API\n    description: All APIs follow a simple REST pattern with a single base URL and query parameters\n  - name: Global Coverage\n    description: Data covers global locations with 80+ currencies, 250,000+ cities, and worldwide\
  \ phone/IP coverage\n  - name: JSON Responses\n    description: All API responses return structured JSON data with consistent error codes\n  - name: Modular Services\n    description: Each API is independently keyed and priced, allowing granular subscription management\n- type: UseCases\n  data:\n  - name: Email List Cleaning\n    description: Validate and filter email lists to improve deliverability and reduce bounce rates\n  - name: Fraud Detection\n    description: Use IP intelligence, email reputation, and phone intelligence to detect and block fraudulent users\n  - name: User Onboarding Enrichment\n    description: Automatically enrich user profiles with geolocation, company, and contact data at signup\n  - name: Currency Conversion\n    description: Display localized pricing or perform currency conversions in e-commerce and fintech apps\n  - name: Compliance Automation\n    description: Validate VAT numbers and IBAN codes to automate financial compliance workflows\n  - name: Content\
  \ Extraction\n    description: Use web scraping API to extract structured data from any website for data pipelines\n  - name: Dynamic User Avatars\n    description: Generate placeholder avatars for users without profile photos using the Avatars API\n- type: Integrations\n  data:\n  - name: JavaScript\n    description: Official JavaScript SDK for Exchange Rates, Email Validation, IP Geolocation, and Phone Validation\n  - name: Python\n    description: Official Python SDK for Exchange Rates, Email Validation, IP Geolocation, and Phone Validation\n  - name: PHP\n    description: Official PHP SDK for Exchange Rates, Email Validation, IP Geolocation, and Phone Validation\n\n- url: rules/abstract-api-spectral-rules.yml\n  type: SpectralRules\n- url: capabilities/fraud-detection.yaml\n  type: NaftikoCapability\n- url: capabilities/data-enrichment.yaml\n  type: NaftikoCapability\n- url: capabilities/financial-compliance.yaml\n  type: NaftikoCapability\n- url: vocabulary/abstract-api-vocabulary.yaml\n\
  \  type: Vocabulary\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/apis.yml
tags:
- Avatars
- Company Enrichment
- Contacts
- Currencies
- Email Validation
- Exchange Rates
- IBAN Validation
- Image Processing
- IP Geolocation
- IP Intelligence
- Phone Validation
- Public Holidays
- Screenshots
- Timezones
- VAT Validation
- Web Scraping
url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/apis.yml
use_cases:
- description: Validate and filter email lists to improve deliverability and reduce bounce rates
  name: Email List Cleaning
- description: Use IP intelligence, email reputation, and phone intelligence to detect and block fraudulent users
  name: Fraud Detection
- description: Automatically enrich user profiles with geolocation, company, and contact data at signup
  name: User Onboarding Enrichment
- description: Display localized pricing or perform currency conversions in e-commerce and fintech apps
  name: Currency Conversion
- description: Validate VAT numbers and IBAN codes to automate financial compliance workflows
  name: Compliance Automation
- description: Use web scraping API to extract structured data from any website for data pipelines
  name: Content Extraction
- description: Generate placeholder avatars for users without profile photos using the Avatars API
  name: Dynamic User Avatars
---
