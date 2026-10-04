# TradePilot

**By Tinashe Chimanikire**

TradePilot is a Windows desktop subscription service for administering a master trading account and its followers, distributed through [Microsoft Store](https://apps.microsoft.com/detail/restricted/9NJ7TWJSJ56G). Its source remains private because TradePilot is a commercial subscription product. This public repository documents the project and contains no application source, compiled companions, credentials or customer data.

## Private testing

Version 1.0.18.0 is published for private testing and its Store installation was verified with Windows reporting Status OK. Availability is limited to authorised private testers, with free installation during testing. Public subscription pricing has not been announced. Certification monitoring is paused.

MT4 and MT5 use dedicated local terminals. Each simultaneous account needs its own installation; MT5 followers require hedging accounts. Logins and trading permissions remain under the user's control in the terminal. Paid followers require current broker-month approval and verified master readiness before copying. Existing positions are not replayed on first connection. End-to-end trade execution remains under validation.

## Administration and reporting

- Account registration, country, audited edits, payment references and dated freeze reasons.
- Paid renews approval and resets the target baseline to that account's verified current broker balance; historical records remain searchable.
- Whole-percentage follower tiers from 1% to 100%, representing stop thresholds rather than promised returns.
- PDF statements, payment records, account analytics and dated connection audits, with View, Download and Email actions.
- Configurable payment notices, selectable due-account reports and editable reminders through the user's email service.
- Position Sizer, Basket Manager and Point Measurer chart tools, plus an integrated administrator guide and purpose help.

Broker records drive read-only assets and performance reports. Unsupported risk/return metrics are marked unavailable rather than estimated. Historical results do not predict future performance.

## Version 1.0.18

Version 1.0.18 adds sequential connection preparation, verified terminal reply checks in Activity, clickable email delivery details, searchable Master/Slave Analytics tabs, statements within Analytics, and account totals excluding the master. Reports use consistent contained sections and account-holder headings.

Pending orders below Point Measurer use the four standard MT4 types, with volume, entry, optional SL/TP, broker-time scheduled placement and separate expiry. Toggling Point Measurer moves the panel while retaining inputs. A local schedule requires its chart/terminal to remain running, connected and trading-enabled; closing, restart or lost permission cancels it. Missed schedules are not replayed. Broker pending orders execute on their price condition. Unfilled pending orders are not copied; normal copying follows master execution.

Analytics includes authenticated fresh pending-order details and historical best entry days/hours, wins/losses and a timing map. Timing groups need at least three completed trades; sample counts and imported costs are disclosed. These are historical observations, not predictions of favourable future trading times.

The candidate passed 95 isolated regression checks and desktop layout checks. Both companions compile with zero errors and warnings; synthetic PDFs were rendered and reviewed. New native scheduled placement, broker acceptance, final chart layout, authenticated reply checks, Store-signed candidate startup and end-to-end copying remain to be tested. Publication and Store installation were verified on 4 October 2026; native validation is pending.

## Planned platforms

TradingView, cTrader, NinjaTrader, Interactive Brokers, TradeStation, Binance, Bybit, Gate, OKX and Coinbase are planned catalogue entries. Their trading connectors are not implemented.

Support: chimanikire.tc@gmail.com
