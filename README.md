# TradePilot

**By Tinashe Chimanikire**

TradePilot is a subscription service for managing a master trading account and its followers through a Windows desktop app, distributed through Microsoft Store. It works with dedicated MT4 and MT5 terminals.

## Why the source code is private

TradePilot is developed and supported as a commercial subscription service. Its source code is maintained in a private repository. This public repository shows that the project exists and explains the product; it does not contain application source code, compiled trading tools, credentials or customer data.

## Microsoft Store

[TradePilot on Microsoft Store](https://apps.microsoft.com/detail/restricted/9NJ7TWJSJ56G)

TradePilot is currently available to its private testing group. Installation is free during private testing; public subscription pricing has not been announced. A Microsoft account authorised for the test group is required to access the private Store listing.

Version 1.0.12.0 is published and verified installed for private testing. Paid approves the follower in the backend, each broker month requires payment approval, and copying requires a fresh authenticated master connection with terminal and advisor trading permissions. The app does not enable those permissions.

Version 1.0.10.0 adds professional PDF payment reports with candlestick branding, complete account details, date filters and page numbers, improves CSV headings, and explains Prepare connection and Open connection on hover or keyboard focus.

Version 1.0.11.0 corrects the command data filename, requires matching desktop and companion versions, and refreshes trading-permission guidance automatically. Matching native connections and management-command acknowledgement passed. A fresh demo OPEN reached the follower but was rejected because no fresh broker quote was available while markets were closed. End-to-end execution remains unverified.

Version 1.0.12.0 was published and installed on 3 October 2026. It keeps one Connect account action and adds a scrollable activation checklist after registration, with MT4/MT5 toolbar and F7 steps for every TradePilot chart. Manual confirmations are separate from automatically verified connection, advisor permission, follower history and current-month payment. Future platforms require their own activation guide before availability. Store-signed 1.0.12 startup was verified.

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

Validation includes 70 automated checks and clean native compilation. Version 1.0.10 packaged startup/PDF export passed. Version 1.0.11 Store-signed startup passed; the earlier unsigned startup was blocked by Windows Application Control and no protection was bypassed. MT5 automatic chart attachment and owner-chart failover passed; MT4 new-chart tools were user-confirmed and chart-closure continuity passed. The corrected command channel was acknowledged; actual end-to-end copying remains unverified until a demo test can execute with fresh quotes.

## Next update: statements and administrative freezes

The next candidate adds downloadable/email PDF statements with one consistent branded layout. Entered trades are available on request. Broker-month-end statements contain two PDFs: outstanding subscription amount and closed trades for that month. Verified terminal history is required; offline periods wait for a fresh complete connection.

Freeze and Unfreeze require a reason and record the date, account number and a unique freeze reference in statements and payment logs. Every inactive account, including frozen accounts, is red. Freezing blocks new copied entries while existing positions remain managed; unfreezing does not replay skipped signals.

The integrated admin guide explains these controls. The candidate passed 70 isolated checks and zero-error/warning MT4/MT5 compilation. Native statement-export verification and Store-signed candidate startup remain pending. These features are not yet available in the installed Store version.

The 1.0.14 candidate also adds account Country, audited edits, read-only account analytics and assets with tiers, analytics PDFs, Paid/Frozen/Due search, Active/Frozen/Due counts, automatic supported email-provider settings and purpose help on buttons. The admin guide explains these features.
