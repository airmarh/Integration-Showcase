# Integration Experience

Third-party integrations I have designed and built across 6+ years in Nigerian financial services. Provider and product names are included only where the relationship is public knowledge; everything else is described by category out of respect for confidentiality obligations.

---

## Telecoms & USSD
**MTN, Airtel, Glo, 9Mobile**

Built the regulator-mandated USSD consent API consumed by all four major Nigerian mobile network operators, covering real-time customer consent and debit flows and periodic operator settlement. Also led the migration of airtime and data purchases across all bank channels from a legacy SMS aggregator to a new payments aggregator with no downtime to customers.

---

## International Money Transfer (IMTO)
**Western Union, MoneyGram + 5 additional licensed IMTOs**

Built inward remittance infrastructure enabling customers to receive funds from seven international money transfer operators directly into their accounts. Implemented SWIFT MT103 and MT202 message generation from scratch, and handled automatic foreign-currency account provisioning for customers receiving USD for the first time.

---

## Identity Verification & KYC
**Five verification providers**

Integrated five physical address verification providers for regulator-compliant KYC during account opening. Designed the multi-provider routing layer that distributes verification requests based on provider efficiency and volume, with full audit trails and per-provider SLA tracking.

---

## Payment Gateways & Merchant Payments
**Paystack**

Extended the customer-facing checkout flow and backend processing for a payment gateway product powered by Paystack.

**Push-based merchant payment authorization**

Co-architected and solely implemented a push notification–based system that lets customers approve merchant charges inside the banking app — no card details or OTPs shared with merchants. See the [case study](#) for the architecture and design decisions.

---

## Bill Payments & Betting
**Electricity billing aggregator + two major betting platforms**

Integrated electricity bill payments and betting wallet funding, all built on a verify → transact → transaction-status-query fallback pattern that guarantees correct transaction resolution even when provider webhooks are delayed or never arrive.

---

## Investment & Stock Trading
**Retail investment platform**

Collaborated on integrations enabling bank customers to access stock trading and investment products directly from the banking app.

---

## Messaging & Notifications
**Three messaging providers (SMS, email, push)**

Integrated multiple messaging providers for transactional SMS, email, and push notifications, with multi-provider routing for delivery resilience and failover.

---

## Risk & Regulatory Systems
**Four Nigerian commercial banks**

Designed and built IFRS 9 Expected Credit Loss (ECL) and internal credit rating systems for four commercial banks, covering data ingestion from core banking systems, model implementation, and regulatory reporting outputs. Separately, supported a tier-1 bank's migration to a new core banking platform, working on internal applications outsourced during the transition.

---

## Summary

| Category | Scope |
|---|---|
| Telecoms / USSD | 4 mobile network operators + 2 aggregators |
| International Money Transfer | 7 IMTOs incl. Western Union & MoneyGram; SWIFT MT103/MT202 |
| Identity Verification / KYC | 5 providers with intelligent routing |
| Payment Gateways | Paystack-powered gateway; push-based merchant authorization |
| Bill Payments & Betting | Electricity + 2 betting platforms |
| Investment & Trading | Retail stock trading platform |
| Messaging & Notifications | 3 providers (SMS, email, push) |
| Risk & Regulatory | IFRS 9 ECL + credit rating systems for 4 banks; core banking migration support |

---

*Specific employers, internal product names, and non-public vendor relationships are intentionally generalised. Details available in conversation where appropriate.*
