---
api_count: 21
apis:
- description: The Binance Spot Trading REST API provides programmatic access to the Binance spot exchange, the world's largest cryptocurrency trading platform by volume. Developers can place and manage orders, quer
  name: Binance Spot Trading API
  slug: spot-trading-api
- description: The Binance Spot WebSocket API provides an alternative way to access spot trading functionality through persistent WebSocket connections. It is functionally equivalent to the REST API, accepting the s
  name: Binance Spot WebSocket API
  slug: spot-websocket-api
- description: 'Binance Spot WebSocket Streams deliver real-time market data updates via persistent WebSocket connections. Developers can subscribe to individual symbol ticker streams, aggregate trade streams, kline '
  name: Binance Spot WebSocket Streams
  slug: spot-websocket-streams
- description: The Binance USD-S Margined Futures API enables trading of USDT and BUSD margined perpetual and delivery futures contracts. Developers can place leveraged long and short positions, manage margin and le
  name: Binance USD-S Margined Futures API
  slug: usds-margined-futures-api
- description: 'The Binance COIN-M Futures API provides access to coin-margined perpetual and delivery futures contracts, where the margin and settlement currency is the base cryptocurrency rather than a stablecoin. '
  name: Binance COIN-M Futures API
  slug: coin-margined-futures-api
- description: The Binance European Options API provides access to European-style cryptocurrency options contracts. Developers can trade call and put options on assets like BTC and ETH, query options chains with var
  name: Binance European Options API
  slug: european-options-api
- description: The Binance Portfolio Margin API enables cross-margining across spot, futures, and options positions under a unified margin account. This risk-based margining system calculates margin requirements bas
  name: Binance Portfolio Margin API
  slug: portfolio-margin-api
- description: The Binance Margin Trading API allows developers to programmatically access cross-margin and isolated-margin trading functionality. Users can borrow assets, place leveraged trades, repay loans, and ma
  name: Binance Margin Trading API
  slug: margin-trading-api
- description: The Binance Wallet API provides endpoints for managing cryptocurrency deposits, withdrawals, and account balances. Developers can query deposit and withdrawal history, retrieve deposit addresses, init
  name: Binance Wallet API
  slug: wallet-api
- description: The Binance Sub-Account API enables institutional and enterprise users to manage multiple sub-accounts under a master account. Developers can create and manage sub-accounts, transfer assets between th
  name: Binance Sub-Account API
  slug: sub-account-api
- description: The Binance Simple Earn API provides programmatic access to flexible and locked savings and staking products. Developers can subscribe to and redeem earn products, query available products and their i
  name: Binance Simple Earn API
  slug: simple-earn-api
- description: The Binance Mining API provides access to Binance Pool mining services. Developers can retrieve mining algorithms, available coins for mining, detailed miner statistics, earnings and revenue data, and
  name: Binance Mining API
  slug: mining-api
- description: The Binance Copy Trading API allows developers to interact with the copy trading platform where users can automatically replicate the trades of experienced lead traders. The API provides endpoints for
  name: Binance Copy Trading API
  slug: copy-trading-api
- description: The Binance Convert API provides a simple interface for converting between cryptocurrencies and fiat currencies at quoted prices. Unlike order-book trading, the Convert API offers instant swaps with p
  name: Binance Convert API
  slug: convert-api
- description: The Binance Pay API enables merchants and businesses to accept cryptocurrency payments from Binance users. Developers can create payment orders, query payment status, process refunds, and manage merch
  name: Binance Pay API
  slug: pay-api
- description: The Binance Algo Trading API provides access to algorithmic order execution strategies such as TWAP (Time-Weighted Average Price) and volume participation algorithms. Developers can place large orders
  name: Binance Algo Trading API
  slug: algo-trading-api
- description: The Binance Auto-Invest API enables developers to create and manage recurring cryptocurrency purchase plans, also known as dollar-cost averaging (DCA) strategies. Users can set up automated investment
  name: Binance Auto-Invest API
  slug: auto-invest-api
- description: The Binance Crypto Loan API provides programmatic access to cryptocurrency-collateralized lending services. Developers can borrow assets by pledging cryptocurrency as collateral, repay outstanding loa
  name: Binance Crypto Loan API
  slug: crypto-loan-api
- description: The Binance Gift Card API allows developers to create, redeem, and verify cryptocurrency gift cards programmatically. Businesses can integrate gift card creation into rewards programs, promotional cam
  name: Binance Gift Card API
  slug: gift-card-api
- description: The Binance NFT API provides endpoints for interacting with the Binance NFT marketplace programmatically. Developers can query NFT transaction history, deposit and withdrawal records, and asset inform
  name: Binance NFT API
  slug: nft-api
- description: The Binance Fiat API provides access to fiat currency deposit and withdrawal operations on the Binance platform. Developers can query fiat deposit and withdrawal order history, check available fiat pa
  name: Binance Fiat API
  slug: fiat-api
asyncapis:
- description: 'Binance Pay sends webhook notifications to merchants for real-time payment status updates. When a customer completes a payment or a refund is processed, Binance Pay sends an HTTPS POST request to the '
  name: Binance Pay Webhooks
  slug: binance-pay-webhooks-asyncapi
- description: The Binance Spot WebSocket API provides an alternative way to access spot trading functionality through persistent WebSocket connections. It is functionally equivalent to the REST API, accepting the s
  name: Binance Spot WebSocket API
  slug: binance-spot-websocket-api-asyncapi
- description: 'Binance Spot WebSocket Streams deliver real-time market data updates via persistent WebSocket connections. Developers can subscribe to individual symbol ticker streams, aggregate trade streams, kline '
  name: Binance Spot WebSocket Streams
  slug: binance-spot-websocket-streams-asyncapi
capabilities:
- description: ''
  name: Spot Trading
  slug: spot-trading
common:
- title: ''
  type: Portal
  url: https://developers.binance.com/
- title: ''
  type: Documentation
  url: https://developers.binance.com/docs/binance-spot-api-docs/
- title: ''
  type: GettingStarted
  url: https://developers.binance.com/docs/binance-spot-api-docs/rest-api
- title: ''
  type: GitHubOrganization
  url: https://github.com/binance
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/binance/refs/heads/main/rules/binance-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/binance/refs/heads/main/vocabulary/binance-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/binance/refs/heads/main/capabilities/spot-trading.yaml
created: '2025-01-01'
description: Binance is the world's largest cryptocurrency exchange by trading volume, providing APIs for spot trading, futures, margin, wallet management, and market data across 19+ specialized REST APIs and WebSocket streams.
features:
- description: Buy and sell 500+ cryptocurrency pairs with limit, market, and stop-loss orders.
  name: Spot Trading
- description: Trade perpetual and delivery futures contracts settled in USDT.
  name: USD-M Futures
- description: Trade perpetual and delivery futures contracts settled in cryptocurrency.
  name: Coin-M Futures
- description: Trade on margin with up to 10x leverage using borrowed assets.
  name: Margin Trading
- description: Place algorithmic orders using TWAP, VP, and other execution strategies.
  name: Algo Trading
- description: Real-time market data streams for price, depth, and trade updates.
  name: WebSocket Streams
- description: Manage deposits, withdrawals, and asset transfers between wallets.
  name: Wallet Management
- description: Earn interest on idle cryptocurrency assets through flexible and locked products.
  name: Simple Earn
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Connect Binance to TradingView for charting and automated alert-based trading.
  name: TradingView
- description: Use MetaTrader bridge adapters to trade Binance from MT4/MT5.
  name: MetaTrader
- description: Receive Binance trade notifications and alerts via Telegram bot.
  name: Telegram
- description: Run serverless trading bots triggered by events on AWS Lambda.
  name: AWS Lambda
- description: Access Binance through the CCXT unified cryptocurrency exchange library.
  name: Python CCXT
jsonld:
- class_count: 0
  name: Binance Context
  property_count: 8
  slug: binance-context
layout: provider
modified: '2026-04-21'
name: Binance
rules:
- name: Binance API Rules
  rule_count: 24
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 15
  slug: binance-spectral-rules
skills: []
slug: binance
solutions: []
tags:
- Cryptocurrency
- Exchange
- Trading
- Blockchain
- Finance
- DeFi
- Market Data
url: https://raw.githubusercontent.com/api-evangelist/binance/refs/heads/main/apis.yml
use_cases:
- description: Build automated trading bots using Binance REST and WebSocket APIs.
  name: Algorithmic Trading
- description: Track and rebalance cryptocurrency portfolios programmatically.
  name: Portfolio Management
- description: Aggregate real-time price and order book data for analysis or display.
  name: Market Data Aggregation
- description: Bridge centralized Binance liquidity into DeFi protocols.
  name: DeFi Integration
- description: Exploit price differences across Binance spot, futures, and margin markets.
  name: Arbitrage Trading
---
