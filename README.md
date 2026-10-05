# TradePilot

**By Tinashe Chimanikire**

TradePilot is a Windows desktop app for managing one lead trading account and its followers through MT4/MT5. It brings together position sizing, basket management, Point Measurer, pending-order tools, payment approval, account analytics and PDF reports.

TradePilot is a commercial subscription service available through [Microsoft Store](https://apps.microsoft.com/detail/restricted/9NJ7TWJSJ56G). Its source code is private to protect the subscription product; this public repository explains the product and release status. Installation remains free during private testing.

## Release status

Version **1.0.23.0** is published for private testers and installed Status OK was verified on 5 October 2026.

Version **1.0.24.0**, submitted on 5 October 2026 as Submission 21, adds automatic authenticated lead-to-follower symbol/timeframe chart opening; optional Admin company details and a centred company logo on PDFs with TradePilot at the bottom centre; mandatory country and phone-code selectors; a confirmed follower-to-lead replacement; planned stop-loss Spread ON/OFF controls; and exact trade-attempt error PDFs linked from Activity. The Admin guide is updated. All 108 regression checks pass and both native companions compile with zero errors and warnings. Native chart mirroring/spread-control checks, Store-signed 1.0.24 startup and end-to-end demo execution remain pending. Broker-server automated-trading restrictions cannot be overridden by the app. No actual account roles, payments or trading permissions were changed during development.

## How it works

Each account uses a dedicated terminal. Add account guides installation and verifies an actual registered-account reply. Broker passwords stay in the terminal. Trading permission remains under the user’s control; Paid records approval without charging money. Future prepaid months capture their starting balance when their broker month begins.

Analytics includes read-only broker information, assigned tiers, recorded results, historical timing observations, account/payment audits and statements. Documents share one branded PDF layout and support View, Download and Email. Historical results are not predictions or promised returns.

Only MT4 and MT5 hedging connectors are currently supported. Additional trading/crypto connectors require implementation and verification before release. Full demo open/copy/close and scheduled execution still require testing. PDF email receipt was user-confirmed; unattended delivery still requires testing. Certification monitoring is paused.

Support: chimanikire.tc@gmail.com
