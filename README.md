# TradePilot

**By Tinashe Chimanikire**

TradePilot is a Windows desktop app for managing one master trading account and its followers through MT4/MT5. It brings together position sizing, basket management, Point Measurer, pending-order tools, payment approval, account analytics and PDF reports.

TradePilot is a commercial subscription service available through [Microsoft Store](https://apps.microsoft.com/detail/restricted/9NJ7TWJSJ56G). Its source code is private to protect the subscription product; this public repository explains the product and release status. Installation remains free during private testing.

## Release status

Version **1.0.18.0** is published for private testers and its Store installation was verified. Both native connections returned verified replies with trading off; restarts, automatic chart attachment and connection continuity after original-chart closure were checked. These checks do not establish end-to-end trading or copying success.

Version **1.0.19.0** was submitted for Microsoft certification on 4 October 2026 as Submission 16. Partner Center shows In certification; publication and installation remain pending. It adds one seven-step Add account flow with Next/Back and a separate trading-permission page; independent Pending Order ON/OFF and broker date/time selectors; stable Analytics and registered-account overview; advance paid periods with PDF receipts; shared Admin email/master phone report contacts; combined Activity; exact Paid/Frozen/Due search; and a fixed white name/version footer. 98 regression checks and isolated UI checks pass; MT4/MT5 companions compile without errors or warnings. Final Store-signed startup, native calendar/permission transfer, scheduled placement and demo execution remain pending.

## How it works

Each account uses a dedicated terminal. Add account guides installation and verifies an actual registered-account reply. Broker passwords stay in the terminal. Trading permission remains under the user’s control; Paid records approval without charging money. Future prepaid months capture their starting balance when their broker month begins.

Analytics includes read-only broker information, assigned tiers, recorded results, historical timing observations, account/payment audits and statements. Documents share one branded PDF layout and support View, Download and Email. Historical results are not predictions or promised returns.

Only MT4 and MT5 hedging connectors are currently supported. Additional trading/crypto connectors require implementation and verification before release. Full demo open/copy/close, scheduled execution and SMTP delivery still require testing. Certification monitoring is paused.

Support: chimanikire.tc@gmail.com
