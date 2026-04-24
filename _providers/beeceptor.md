---
api_count: 1
apis:
- description: Beeceptor's management API provides programmatic access to create and manage mock endpoints, rules, and traffic inspection on Scale and Enterprise plans. It enables teams to automate mock server provi
  name: Beeceptor API
  slug: beeceptor
common:
- title: ''
  type: Website
  url: https://beeceptor.com
- title: ''
  type: Portal
  url: https://app.beeceptor.com
- title: ''
  type: Pricing
  url: https://beeceptor.com/pricing/
- title: ''
  type: FAQ
  url: https://beeceptor.com/faq/
- title: ''
  type: Blog
  url: https://beeceptor.com/blog/
- title: ''
  type: StatusPage
  url: https://beeceptorstatus.statuspage.io
- title: ''
  type: PrivacyPolicy
  url: https://beeceptor.com/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://beeceptor.com/terms-of-service/
- title: ''
  type: GitHubOrganization
  url: https://github.com/beeceptor
- title: ''
  type: Plans
  url: ''
created: '2025-01-08'
description: Beeceptor is an API mocking, HTTP debugging, and proxy platform that lets developers create mock servers instantly without any coding. It supports REST, SOAP, GraphQL, and gRPC mocking, provides real-time HTTP traffic inspection, webhook testing, local tunneling, and AI-powered spec generation. Teams use Beeceptor to unblock frontend, backend, and QA workflows by simulating APIs before they are built or while avoiding dependencies on live services.
features:
- description: Capture and inspect HTTP headers, request/response bodies, and status codes in real time as traffic flows through your mock or proxy endpoints.
  name: HTTP Traffic Inspection
- description: Create mock servers for REST, SOAP, GraphQL, and gRPC APIs instantly with flexible request matching rules and dynamic response generation, no coding required.
  name: API Mocking
- description: Wrap any live API endpoint with a Beeceptor subdomain to intercept, inspect, and selectively override traffic using man-in-the-middle proxy functionality.
  name: Reverse Proxy and Interception
- description: Bind localhost services to persistent public HTTPS endpoints for webhook testing, live local debugging, and sharing local services with teammates.
  name: Local Tunneling
- description: Upload an OpenAPI YAML or JSON specification to instantly create a fully functional mock server with one click, no manual rule creation needed.
  name: OpenAPI Mock Generation
- description: Generate realistic mock servers from natural language prompts or live traffic, using AI to synthesize responses for REST, SOAP, GraphQL, and gRPC.
  name: AI-Powered Mock Creation
- description: Simulate network delays, timeouts, connection resets, and HTTP error codes to validate how applications handle failure scenarios.
  name: Fault and Latency Injection
- description: Record live API interactions and automatically generate mock rules from real traffic captures, enabling rapid mock creation from production behavior.
  name: Traffic Recording
- description: Monitor for drift between live API behavior and the OpenAPI contract to detect breaking changes and schema violations over time.
  name: API Contract Drift Detection
- description: Set maximum request limits per second, minute, or hour on endpoints to test application behavior under throttled or rate-limited conditions.
  name: Rate Limiting Simulation
- description: Scale and Enterprise plans unlock the Beeceptor management API for programmatic creation and management of endpoints and rules in CI/CD pipelines.
  name: Programmatic API Control
- description: Configure custom domain names for mock endpoints on Scale and Enterprise plans, enabling team-branded or environment-specific endpoint URLs.
  name: Custom Domains
- description: Mutual TLS support for secure proxy configurations requiring client certificate authentication in enterprise environments.
  name: mTLS Support
- description: Enterprise plan includes Single Sign-On (SSO) integration and full audit logging for compliance and access governance.
  name: SSO and Audit Logs
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Inspect and debug Shopify webhook payloads by tunneling webhook deliveries through Beeceptor for local development and testing.
  name: Shopify
- description: Test Stripe webhook events and payment API callbacks using Beeceptor local tunneling and traffic inspection.
  name: Stripe
- description: Debug email delivery webhook callbacks and event notifications from Sendgrid using Beeceptor HTTP inspection and mock responses.
  name: Sendgrid
- description: Integrate Beeceptor programmatic API (Scale plan and above) into CI/CD pipelines to automate mock provisioning and teardown during testing.
  name: CI/CD Pipelines
layout: provider
modified: '2026-04-19'
name: Beeceptor
skills: []
slug: beeceptor
solutions: []
tags:
- API Mocking
- Automation
- Debugging
- HTTP Proxy
- Integrations
- Mock Servers
- Platform
- Testing
- Webhooks
url: https://raw.githubusercontent.com/api-evangelist/beeceptor/refs/heads/main/apis.yml
use_cases:
- description: Build and test frontend applications against mock APIs without waiting for backend APIs to be ready, removing cross-team blocking dependencies.
  name: Frontend Development
- description: Mock downstream microservices and third-party APIs to test API behavior under various conditions including timeouts and error states.
  name: Backend Development
- description: Access mock servers to enable parallel mobile development without backend dependencies, accelerating the mobile app development cycle.
  name: Mobile Development
- description: Simulate edge cases, rate limits, latencies, and rarely reachable code paths to achieve comprehensive test coverage without live API dependencies.
  name: QA Engineering
- description: Inspect and debug HTTP payloads for webhook consumers and producers from platforms like Shopify, Stripe, and Sendgrid using local tunneling.
  name: Webhook Testing
- description: Mimic external service behavior for predictable load test outcomes and reduce costs associated with third-party API usage during performance testing.
  name: Load Testing
- description: Collaborate with teammates by sharing intercepted requests and mock servers via permanent links for distributed team workflows.
  name: API Contract Sharing
---
