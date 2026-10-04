# TradePilot

**By Tinashe Chimanikire**

TradePilot is a Windows desktop app for managing one lead trading account and its followers through MT4/MT5. It brings together position sizing, basket management, Point Measurer, pending-order tools, payment approval, account analytics and PDF reports.

TradePilot is a commercial subscription service available through [Microsoft Store](https://apps.microsoft.com/detail/restricted/9NJ7TWJSJ56G). Its source code is private to protect the subscription product; this public repository explains the product and release status. Installation remains free during private testing.

## Release status

Version **1.0.20.0** is published for private testers and installed Status OK was verified on 4 October 2026.

Version **1.0.21.0** was submitted for certification on 4 October 2026 as Submission 18. It adds Send Mail with multiple follower selection, editable recipients and messages, broadcast selection and a saved editable signature. Sender setup and reminders are inside Send Mail. Review terminal setup is a separate action after Edit account. Lead account and Follower account replace older role names; PDFs use Lead Account Information. MT4 preparation attaches tools to all eligible saved charts, preserving other advisors. Pending Order starts OFF and ON requires a manual click. Admin guide updated. 100 regression checks and isolated UI/outbox checks passed without sending real emails; both companions compile with zero errors and warnings. Store-signed startup and final native default-OFF refresh remain pending. No end-to-end trade execution success is claimed.

## How it works

Each account uses a dedicated terminal. Add account guides installation and verifies an actual registered-account reply. Broker passwords stay in the terminal. Trading permission remains under the user’s control; Paid records approval without charging money. Future prepaid months capture their starting balance when their broker month begins.

Analytics includes read-only broker information, assigned tiers, recorded results, historical timing observations, account/payment audits and statements. Documents share one branded PDF layout and support View, Download and Email. Historical results are not predictions or promised returns.

Only MT4 and MT5 hedging connectors are currently supported. Additional trading/crypto connectors require implementation and verification before release. Full demo open/copy/close and scheduled execution still require testing. PDF email receipt was user-confirmed; unattended delivery still requires testing. Certification monitoring is paused.

Support: chimanikire.tc@gmail.com
