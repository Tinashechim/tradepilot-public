# TradePilot

**By Tinashe Chimanikire**

TradePilot is a Windows desktop app for managing one lead trading account and its followers through MT4/MT5. It brings together position sizing, basket management, Point Measurer, pending-order tools, payment approval, account analytics and PDF reports.

TradePilot is a commercial subscription service available through [Microsoft Store](https://apps.microsoft.com/detail/restricted/9NJ7TWJSJ56G). Its source code is private to protect the subscription product; this public repository explains the product and release status. Installation remains free during private testing.

## Release status

Version **1.0.21.0** is published for private testers and installed Status OK was verified on 4 October 2026.

Version **1.0.22.0**, submitted for certification on 4 October 2026 as Submission 19, adds Current period / Date range selection before Analytics and inclusive broker exit-date filtering, with the selected range on screen and PDF reports. Current balances remain clearly labelled snapshots. Generated PDFs retain TradePilot branding without the personal author line. Total accounts, Paid and native messages use Lead account / Follower account labels. Every ordinary app closure warns about stopped copying and email delivery. Windows session handling provides an ordinary shutdown warning; forced shutdown, killed processes and power loss may bypass it. It never initiates shutdown or closes broker trades. The Admin guide is updated. 103 regression checks and isolated UI, range-PDF and native Windows-message checks passed without shutting down the computer or executing trades. Both companions compile with zero errors and warnings. Store-signed 1.0.22 startup and final native display refresh remain pending.

## How it works

Each account uses a dedicated terminal. Add account guides installation and verifies an actual registered-account reply. Broker passwords stay in the terminal. Trading permission remains under the user’s control; Paid records approval without charging money. Future prepaid months capture their starting balance when their broker month begins.

Analytics includes read-only broker information, assigned tiers, recorded results, historical timing observations, account/payment audits and statements. Documents share one branded PDF layout and support View, Download and Email. Historical results are not predictions or promised returns.

Only MT4 and MT5 hedging connectors are currently supported. Additional trading/crypto connectors require implementation and verification before release. Full demo open/copy/close and scheduled execution still require testing. PDF email receipt was user-confirmed; unattended delivery still requires testing. Certification monitoring is paused.

Support: chimanikire.tc@gmail.com
