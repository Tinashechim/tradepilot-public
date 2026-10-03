# TradePilot

**By Tinashe Chimanikire**

TradePilot is a subscription service for managing a master trading account and its followers through a Windows desktop app, distributed through Microsoft Store. It works with dedicated MT4 and MT5 terminals.

## Why the source code is private

TradePilot is developed and supported as a commercial subscription service. Its source code is maintained in a private repository. This public repository shows that the project exists and explains the product; it does not contain application source code, compiled trading tools, credentials or customer data.

## Microsoft Store

[TradePilot on Microsoft Store](https://apps.microsoft.com/detail/restricted/9NJ7TWJSJ56G)

TradePilot is currently available to its private testing group. Installation is free during private testing; public subscription pricing has not been announced. A Microsoft account authorised for the test group is required to access the private Store listing.

Version 1.0.2.0 has passed Microsoft Store certification and is published to private testers. It adds field examples and hover help, chart discovery, historical commission estimates per symbol, and monthly targets from 1% to 100%. Installation remains free during private testing.

Version 1.0.4.0 has passed Microsoft Store certification and is published to the private testing group. It adds a step-by-step Admin guide inside the app, captures the current balance at activation as a fixed monthly target baseline, hides automatic setup inputs until manual information is needed, uses black payment text and increases chart-tool text by 20%. Refresh terminal companions through Connect account after installing the approved Store update.

The Platforms catalogue lists TradingView, cTrader, NinjaTrader, Interactive Brokers, TradeStation, Binance, Bybit, Gate, OKX and Coinbase as **Planned**. These connectors are not implemented or available for trading. MT4 and MT5 remain the working connections.

## Product features

- Manage an MT4 or MT5 master and multiple follower accounts.
- Size copied trades against each follower's balance.
- Track payment status and monthly targets at any whole percentage from 1% to 100%.
- Send optional reminders through the user's email provider.
- Connect accounts through the desktop app, with terminal detection, companion installation and saved connection settings in version 1.0.1.0.
- Use the TradePilot position sizer, basket manager and Point Measurer in MetaTrader.

MT5 followers require hedging accounts. Each simultaneous account needs its own terminal installation. Broker login and trading permissions stay in MetaTrader.

Monthly target settings do not promise returns. End-to-end broker copying is still being validated in demo testing.

From version 1.0.4.0, the monthly baseline is the follower's current balance when copying first becomes ready. It remains fixed for that broker month; earlier closed/floating profit and subsequent deposits are excluded from target progress. Closure attempts can be delayed by broker rejections or closed markets.

## Contact

Support and privacy enquiries: chimanikire.tc@gmail.com
Private Store version 1.0.5.0, approved and published, removes manual commission entry and uses consistent balance and stop-loss price-risk sizing in MT4, MT5 and the copier. Broker fees still affect actual results.

Version 1.0.6.0 passed certification and was published to private testers on 3 October 2026. It adds automatic chart tools on available existing/new charts while the desktop connection runs and improves Accounts text fitting, scrollbars and status readability. Existing advisors are preserved. Installation remains free for private testers. The Store update is verified installed; restart and demo execution checks remain part of private testing.
