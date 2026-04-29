---
api_count: 1
apis:
- description: API-Football provides comprehensive football data including leagues, fixtures, standings, events, line-ups, players, pre-match odds, live odds, and historical statistics for 1,200+ leagues and cups wo
  name: API-Football
  slug: api-football
common:
- title: ''
  type: Website
  url: https://www.api-football.com/
- title: ''
  type: Documentation
  url: https://www.api-football.com/documentation-v3
- title: ''
  type: Pricing
  url: https://www.api-football.com/pricing
- title: ''
  type: SignUp
  url: https://dashboard.api-football.com/register
- title: ''
  type: Login
  url: https://dashboard.api-football.com/login
- title: ''
  type: Support
  url: https://www.api-football.com/contact
created: '2025-03-01'
description: API-Football is a RESTful API providing comprehensive football (soccer) data covering 1,200+ leagues and cups worldwide. Operated by API-Sports, the platform delivers live scores, fixtures, standings, events, line-ups, player statistics, pre-match odds, and historical data. The API supports 9+ sports total including soccer, Formula 1, basketball, baseball, hockey, rugby, volleyball, and handball. Data is returned in JSON format and updates every 15 seconds during live matches.
features:
- description: Comprehensive coverage of over 1,200 football leagues and cups worldwide including major leagues, cups, and international competitions.
  name: 1200+ Leagues and Cups
- description: Real-time match data updated every 15 seconds during live matches, including scores, events, and match statistics.
  name: Live Scores
- description: Complete fixture schedules and match results including past, present, and upcoming matches with full event details.
  name: Fixtures and Results
- description: League standings and tables for all supported competitions with points, wins, draws, losses, and goal difference.
  name: Standings
- description: Individual player statistics including goals, assists, cards, appearances, and detailed performance metrics.
  name: Player Statistics
- description: Pre-match betting odds and live odds from major bookmakers available in all pricing tiers.
  name: Pre-Match and Live Odds
- description: Multiple years of historical match data available for statistical analysis, fantasy football, and predictive modeling.
  name: Historical Data
- description: Beyond football/soccer, API-Sports covers Formula 1, basketball, baseball, hockey, rugby, volleyball, and handball.
  name: Multi-Sport Coverage
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: API-Football is available on the RapidAPI hub enabling discovery and access through the RapidAPI marketplace.
  name: RapidAPI
- description: Subscriptions managed via Stripe or PayPal with no auto-renewal and prepaid plan options.
  name: Stripe and PayPal
layout: provider
modified: '2026-04-19'
name: API Football
skills: []
slug: api-football
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: api-football\nname: API Football\ndescription: >-\n  API-Football is a RESTful API providing comprehensive football (soccer) data\n  covering 1,200+ leagues and cups worldwide. Operated by API-Sports, the\n  platform delivers live scores, fixtures, standings, events, line-ups, player\n  statistics, pre-match odds, and historical data. The API supports 9+ sports\n  total including soccer, Formula 1, basketball, baseball, hockey, rugby,\n  volleyball, and handball. Data is returned in JSON format and updates every\n  15 seconds during live matches.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Sports\n  - Football\n  - Soccer\n  - Live Scores\n  - Statistics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/api-football/refs/heads/main/apis.yml\ncreated: '2025-03-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: api-football:api-football\n    name: API-Football\n    description:\
  \ >-\n      API-Football provides comprehensive football data including leagues,\n      fixtures, standings, events, line-ups, players, pre-match odds, live\n      odds, and historical statistics for 1,200+ leagues and cups worldwide.\n    humanURL: https://www.api-football.com/\n    tags:\n      - Sports\n      - Football\n      - Soccer\n      - Live Scores\n    properties:\n      - type: Documentation\n        url: https://www.api-football.com/documentation-v3\n      - type: GettingStarted\n        url: https://www.api-football.com/documentation-v3#section/Introduction\n      - type: Pricing\n        url: https://www.api-football.com/pricing\n      - type: Authentication\n        url: https://www.api-football.com/documentation-v3#section/Authentication\n      - type: RateLimits\n        url: https://www.api-football.com/documentation-v3#section/Rate-limit\ncommon:\n  - type: Website\n    url: https://www.api-football.com/\n  - type: Documentation\n    url: https://www.api-football.com/documentation-v3\n\
  \  - type: Pricing\n    url: https://www.api-football.com/pricing\n  - type: SignUp\n    url: https://dashboard.api-football.com/register\n  - type: Login\n    url: https://dashboard.api-football.com/login\n  - type: Support\n    url: https://www.api-football.com/contact\n  - type: Features\n    data:\n      - name: 1200+ Leagues and Cups\n        description: >-\n          Comprehensive coverage of over 1,200 football leagues and cups\n          worldwide including major leagues, cups, and international competitions.\n      - name: Live Scores\n        description: >-\n          Real-time match data updated every 15 seconds during live matches,\n          including scores, events, and match statistics.\n      - name: Fixtures and Results\n        description: >-\n          Complete fixture schedules and match results including past, present,\n          and upcoming matches with full event details.\n      - name: Standings\n        description: >-\n          League standings and tables\
  \ for all supported competitions with\n          points, wins, draws, losses, and goal difference.\n      - name: Player Statistics\n        description: >-\n          Individual player statistics including goals, assists, cards,\n          appearances, and detailed performance metrics.\n      - name: Pre-Match and Live Odds\n        description: >-\n          Pre-match betting odds and live odds from major bookmakers\n          available in all pricing tiers.\n      - name: Historical Data\n        description: >-\n          Multiple years of historical match data available for statistical\n          analysis, fantasy football, and predictive modeling.\n      - name: Multi-Sport Coverage\n        description: >-\n          Beyond football/soccer, API-Sports covers Formula 1, basketball,\n          baseball, hockey, rugby, volleyball, and handball.\n  - type: UseCases\n    data:\n      - name: Sports Applications\n        description: >-\n          Build mobile and web apps displaying\
  \ live scores, fixtures,\n          standings, and player statistics for football fans.\n      - name: Fantasy Football Platforms\n        description: >-\n          Power fantasy football platforms with player statistics, injury\n          updates, match results, and historical performance data.\n      - name: Sports Betting\n        description: >-\n          Integrate pre-match odds, live odds, and real-time match events\n          into sports betting and prediction platforms.\n      - name: Sports Analytics\n        description: >-\n          Analyze historical match data, player performance, and team\n          statistics for sports analytics and scouting platforms.\n      - name: Widgets and Embeds\n        description: >-\n          Embed live score widgets and statistics panels into websites\n          using API-Football's data and widget integrations.\n  - type: Integrations\n    data:\n      - name: RapidAPI\n        description: >-\n          API-Football is available on the\
  \ RapidAPI hub enabling discovery\n          and access through the RapidAPI marketplace.\n      - name: Stripe and PayPal\n        description: >-\n          Subscriptions managed via Stripe or PayPal with no auto-renewal\n          and prepaid plan options.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/api-football/refs/heads/main/apis.yml
tags:
- Sports
- Football
- Soccer
- Live Scores
- Statistics
url: https://raw.githubusercontent.com/api-evangelist/api-football/refs/heads/main/apis.yml
use_cases:
- description: Build mobile and web apps displaying live scores, fixtures, standings, and player statistics for football fans.
  name: Sports Applications
- description: Power fantasy football platforms with player statistics, injury updates, match results, and historical performance data.
  name: Fantasy Football Platforms
- description: Integrate pre-match odds, live odds, and real-time match events into sports betting and prediction platforms.
  name: Sports Betting
- description: Analyze historical match data, player performance, and team statistics for sports analytics and scouting platforms.
  name: Sports Analytics
- description: Embed live score widgets and statistics panels into websites using API-Football's data and widget integrations.
  name: Widgets and Embeds
---
