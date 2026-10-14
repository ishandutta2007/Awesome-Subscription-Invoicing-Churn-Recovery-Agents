<div align="center">

![Awesome Subscription Invoicing & Churn Recovery Agents](assets/banner.svg)

# 🚀 Awesome Subscription Invoicing & Churn Recovery Agents

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Subscription-Invoicing-Churn-Recovery-Agents/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Subscription-Invoicing-Churn-Recovery-Agents?style=flat-square&logo=github&color=gold" alt="Repo Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Subscription-Invoicing-Churn-Recovery-Agents/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Subscription-Invoicing-Churn-Recovery-Agents?style=flat-square&logo=github&color=blue" alt="Repo Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Subscription-Invoicing-Churn-Recovery-Agents/pulls"><img src="https://img.shields.io/badge/PRs-Welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Subscription-Invoicing-Churn-Recovery-Agents/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

**A curated, production-grade directory of SaaS platforms, autonomous dunning agents, and open-source software dedicated to failed payment recovery, involuntary churn reduction, smart card retries, and recurring subscription billing.**

</div>

---

## 📑 Table of Contents

- [🎯 Executive Summary & Core Concepts](#-executive-summary--core-concepts)
- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [💼 SaaS & Hosted Recovery Platforms](#-saas--hosted-recovery-platforms)
- [🔓 Open-Source GitHub Projects & Dunning Engines](#-open-source-github-projects--dunning-engines)
- [⚙️ The Recovery Pipeline: How Dunning Agents Work](#️-the-recovery-pipeline-how-dunning-agents-work)
- [🤝 How to Contribute](#-how-to-contribute)
- [📈 Star History](#-star-history)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [⚖️ Disclaimer & Compliance](#️-disclaimer--compliance)

---

## 🎯 Executive Summary & Core Concepts

In subscription businesses, **20% to 40% of all customer churn is involuntary** — caused by soft bank declines, expired credit cards, transient processor outages, and insufficient funds rather than intentional cancellations. 

Modern **Subscription Invoicing & Churn Recovery Agents** solve this silent revenue leak through:
- ⚡ **Machine Learning Smart Retries**: Algorithmic scheduling of retry attempts tailored to issuer response codes and local pay cycles.
- 📬 **Orchestrated Pre-Dunning & Post-Dunning**: Triggering multi-channel card update reminders (email, in-app paywalls, SMS, WhatsApp) before and after payment failures.
- 🛡️ **Autonomous Cancel Flow Interception**: Deflecting voluntary churn via customized exit surveys, pause options, downsell offers, and instant retention incentives.
- 💳 **Self-Service Card Updater Portals**: Frictionless, tokenized payment modification links requiring no customer login credentials.

---

## 📊 Sector Overview & Market Dynamics

The global **subscription management, billing, and revenue recovery** software market is valued at approximately **$6.8 billion in 2026** and is projected to surpass **$14.2 billion by 2030**, growing at a compound annual growth rate (**CAGR**) of **16.5%**. Globally, over **$40 billion in salvageable ARR** is lost annually to passive billing failures across SaaS, digital media, and e-commerce ecosystems.

### 🌐 Market Fragmentation & Structural Dynamics

The market exhibits a **moderately fragmented, two-tier competitive structure**:

1. **Core Payment Rails & Billing Infrastructure (Concentrated / Oligopolistic)**:
   - Dominated by a handful of multibillion-dollar giants (such as **Stripe**, **Paddle**, and **Chargebee**).
   - High barrier to entry driven by PCI-DSS Level 1 compliance, banking integrations, global tax remittance, and multi-currency ledger management.
   - Tendency toward platform consolidation through M&A (e.g., Paddle acquiring ProfitWell for $200M; Battery Ventures consolidating SaaSOptics and Chargify into Maxio).

2. **Specialized Churn Recovery & Autonomous Dunning Agents (Highly Fragmented / Specialized)**:
   - Composed of focused point solutions and intelligent agents (e.g., **Churnkey**, **Flexpay**, **Gravy**, **Baremetrics Recover**).
   - Highly competitive and fragmented because specialized algorithmic retries, conversational SMS outreach, and dynamic cancel-flow personalization routinely outperform standard built-in billing gateway retry rules by **10% to 30%**.
   - Low switching costs and performance-based contingency pricing models allow specialized recovery agents to sit seamlessly on top of existing Stripe or Chargebee billing stacks.

---

## 💼 SaaS & Hosted Recovery Platforms

The following SaaS platforms provide hosted dunning automation, algorithmic payment retries, and voluntary/involuntary churn deflection.

> **Sorted by Company Scale (Valuation / Revenue) Descending**

| Platform | Company Scale (Valuation / Revenue) | Pricing | Free Tier / Trial Limit | Key Capabilities & Recovery Focus |
| :--- | :--- | :--- | :--- | :--- |
| **[Stripe Billing](https://stripe.com/billing)** | **$70 Billion Valuation**<br>*(~$14B+ Annual Gross Revenue)* | **0.5%** on recurring volume (Starter)<br>**0.8%** on recurring volume (Scale)<br>Invoicing: 0.4% per paid invoice after free allowance (max $2/inv) | **Free forever Developer Sandbox** (unlimited test transactions); first **25 automated invoices/month are 100% free**; $0 fixed monthly fee | Native Smart Retries trained on billions of global transactions, automated customer portal, invoice PDF delivery, webhook dunning webhooks, and automatic card account updater. |
| **[Chargebee](https://www.chargebee.com/)** | **$3.5 Billion Valuation**<br>*(~$100M+ ARR)* | **Launch**: $0/mo for first $250k cumulative volume (then 0.75% overage)<br>**Performance**: **$599/mo** (billed annually at $7,188/yr) for up to $100k/mo volume + 0.75% overage | **Free forever Launch Plan** up to **$250,000 in cumulative lifetime billing**; plus **14-day full-access free trial** on Performance plan | Configurable multi-stage dunning rules, automated pre-dunning card expiration alerts, white-labeled payment update pages, and multi-gateway fallbacks. |
| **[Paddle](https://www.paddle.com/)** | **$1.4 Billion Valuation**<br>*(~$100M+ ARR)* | **5% + $0.50** per successful checkout/transaction (all-in Merchant of Record fee); custom volume pricing over $250k/mo | **Free forever Sandbox Account** with unlimited simulated transactions; **$0 monthly platform subscription fee** (zero cost when not processing revenue) | Merchant of Record (MoR) architecture handling global sales tax, VAT, compliance, automated localized dunning emails, dynamic retry schedules, and churn analytics. |
| **[Recurly](https://recurly.com/)** | **~$800 Million Valuation**<br>*(Accel-KKR backed; ~$80M ARR)* | **Starter**: **$249/mo** + 0.9% of billing volume over $40,000/month<br>**Professional/Elite**: Custom quote with committed annual volume | **90-day free trial** on Starter plan with full sandbox access, simulated recovery tests, and no credit card required | Statistical machine learning models predicting optimal retry time per card brand, intelligent dunning intervals, and Account Updater gateway sync. |
| **[Maxio](https://www.maxio.com/)** | **~$450 Million Valuation**<br>*(Battery Ventures; ~$60M ARR)* | **Grow**: Starts at **$599/mo** (billed annually) for up to $100k/mo billing volume<br>**Scale**: Custom quote for multi-entity & complex usage | **Free forever Build Plan** (developer sandbox with unlimited API calls and mock billing engines); **14-day guided proof-of-concept trial** upon request | Enterprise B2B SaaS dunning, automated credit card re-attempts, self-service payment update pages, automated revenue recognition (ASC 606), and churn cohort analysis. |
| **[ProfitWell Retain](https://www.paddle.com/retain)** | **$200 Million Acquisition**<br>*(Paddle subsidiary; ~$25M ARR)* | **Pure Performance Contingency**: Charges **10% to 15%** of recovered delinquent revenue; 100% ROI guarantee (no recovery = $0 fee) | **Free forever Retain Audit & Benchmarking tier** (diagnoses card failure leakage at 0 cost); **60-day risk-free pilot** with ROI guarantee | Deep machine learning algorithms analyzing hundreds of customer attributes to calculate optimal retry cadence; white-label localized dunning emails and in-app paywalls. |
| **[Gravy Solutions](https://gravy.com/)** | **~$60 Million Valuation**<br>*(Private; ~$15M ARR)* | **Hybrid Retainer**: Starts at **$997/mo** base retainer + **15% to 20%** contingency fee on revenue recovered by human agents | **Free 30-day Failed Payment Diagnostic Audit** (analyzes past 90 days of churn and decline patterns across Stripe/PayPal with revenue forecast) | Human-assisted failed payment recovery combining software notifications with trained retention specialists ("Gravy Retainers") providing personalized phone, SMS, and email outreach. |
| **[Flexpay](https://flexpay.io/)** | **~$35 Million Valuation**<br>*(Series A; ~$6M ARR)* | **Performance-based**: Starts at **10% to 15%** of recovered revenue with a **$500/mo** minimum platform platform fee | **Free 30-day historical transaction decline audit** (analyzing up to 180 days of decline codes and salvageable MRR); **30-day pilot proof-of-concept** | Invisible Recovery™ platform leveraging machine learning to retry soft declines directly through the payments ecosystem without bothering the end consumer; high-ticket recovery focus. |
| **[Churnkey](https://churnkey.co/)** | **~$25 Million Valuation**<br>*(Bootstrapped / Seed; ~$4M ARR)* | **Launch**: **$199/mo** (covers up to $20k churned revenue/mo)<br>**Core**: **$499/mo** (covers up to $50k churned revenue/mo)<br>**Enterprise**: **$999/mo** | **14-day free trial** with full access to cancel flows, failed payment recovery, card update walls, and up to $5,000 in tracked MRR; no credit card required | Comprehensive churn prevention combining involuntary failed payment recovery (smart retries, pre-dunning, dynamic paywalls) with voluntary cancel-flow optimization and discount deflection. |
| **[Baremetrics Recover](https://baremetrics.com/features/recover)** | **$4 Million Acquisition**<br>*(Xenon Ventures; ~$2.5M ARR)* | **Standalone Recover Add-on**: **$129/mo** (or $108/mo when bundled with base analytics for under $10k MRR); includes 100% money-back ROI guarantee | **14-day unrestricted free trial** with complete access to automated dunning emails, credit card paywalls, customer card update portal, and in-app banners | Plug-and-play dunning email campaigns, automated in-app payment update forms, customizable grace periods, and transparent recovery analytics for Stripe, Recurly, and Braintree. |

---

## 🔓 Open-Source GitHub Projects & Dunning Engines

Explore battle-tested open-source billing engines, payment switches, dunning orchestrators, and cancel-survey frameworks.

> **Sorted by GitHub_Stars Descending**  
> *Click the social Stars_Badge next to each project to view its real-time stargazers!*

### 1. 🌟 [Hyperswitch](https://github.com/juspay/hyperswitch) [![GitHub_Stars](https://img.shields.io/github/stars/juspay/hyperswitch?style=social&color=white)](https://github.com/juspay/hyperswitch/stargazers)
- **Primary Language**: Rust 🦀
- **License**: Apache-2.0
- **Focus**: High-Performance Payment Switch, Smart Routing & Multi-Gateway Failover
- **Description**: A lightning-fast, modular open-source financial switch. Enables SaaS teams to route payments across 50+ gateways (Stripe, Adyen, Braintree, Checkout.com, Razorpay), automatically reroute soft declines to fallback processors, retry failed recurring payments, and maintain unified customer subscription vaults with zero vendor lock-in.

### 2. 📋 [Formbricks](https://github.com/formbricks/formbricks) [![GitHub_Stars](https://img.shields.io/github/stars/formbricks/formbricks?style=social&color=white)](https://github.com/formbricks/formbricks/stargazers)
- **Primary Language**: TypeScript / Next.js ⚛️
- **License**: AGPL-3.0
- **Focus**: Experience Management, In-App Exit Surveys & Cancel Flow Optimization
- **Description**: The open-source alternative to Churnkey and Qualtrics for voluntary churn deflection. Allows engineering and growth teams to embed customizable cancellation surveys directly into their React/Next.js apps, dynamically offer discounts or subscription pause options before user churn, and trigger retention webhook workflows.

### 3. ⚡ [Lago](https://github.com/getlago/lago) [![GitHub_Stars](https://img.shields.io/github/stars/getlago/lago?style=social&color=white)](https://github.com/getlago/lago/stargazers)
- **Primary Language**: Ruby / Go 💎
- **License**: AGPL-3.0
- **Focus**: Open-Source Metering, Usage-Based Billing & Dunning Workflows
- **Description**: A transparent, developer-first alternative to Stripe Billing and Chargebee. Ingests high-frequency consumption events, calculates complex tiered/hybrid billing models, generates localized PDF invoices, and executes automated payment retries with configurable dunning webhook notifications when card charges fail.

### 4. 🧾 [Invoice Ninja](https://github.com/invoiceninja/invoiceninja) [![GitHub_Stars](https://img.shields.io/github/stars/invoiceninja/invoiceninja?style=social&color=white)](https://github.com/invoiceninja/invoiceninja/stargazers)
- **Primary Language**: PHP (Laravel) / Flutter 📱
- **License**: Functional Source License / Fair Code
- **Focus**: Self-Hosted Invoicing, Recurring Subscriptions & Automated Reminders
- **Description**: One of the most mature self-hosted billing engines on GitHub. Supports recurring auto-billing, client-facing payment portals, automated multi-stage dunning reminders (First Notice, Overdue, Final Notice), multi-gateway integration (PayPal, Stripe, Mollie, Authorize.Net), and automated credit card charging.

### 5. 📑 [Crater](https://github.com/crater-invoice-inc/crater) [![GitHub_Stars](https://img.shields.io/github/stars/crater-invoice-inc/crater?style=social&color=white)](https://github.com/crater-invoice-inc/crater/stargazers)
- **Primary Language**: PHP (Laravel) / Vue.js 🚀
- **License**: MIT
- **Focus**: Clean Self-Hosted Invoicing & Automated Late Payment Reminders
- **Description**: A modern, mobile-friendly invoicing suite designed for freelancers, agencies, and small SaaS companies. Includes automated recurring invoices, detailed payment status tracking (Sent, Viewed, Partial, Paid, Overdue), payment gateway webhooks, and automated email payment reminders.

### 6. ⚔️ [Kill Bill](https://github.com/killbill/killbill) [![GitHub_Stars](https://img.shields.io/github/stars/killbill/killbill?style=social&color=white)](https://github.com/killbill/killbill/stargazers)
- **Primary Language**: Java ☕
- **License**: Apache-2.0
- **Focus**: Enterprise Open-Source Subscription Billing & Modular Overdue Engine
- **Description**: The enterprise gold standard for open-source recurring billing. Features an advanced **Overdue / Dunning State Machine** allowing operators to configure deterministic grace periods, automatic service downgrades, payment retry intervals, and custom plugin hooks for custom notification channels. Used by multinational telecom, streaming, and enterprise SaaS companies.

### 7. 📦 [Stripe Node.js SDK](https://github.com/stripe/stripe-node) [![GitHub_Stars](https://img.shields.io/github/stars/stripe/stripe-node?style=social&color=white)](https://github.com/stripe/stripe-node/stargazers)
- **Primary Language**: TypeScript / JavaScript 🌐
- **License**: MIT
- **Focus**: Official Stripe API Library for Subscription Lifecycle Orchestration
- **Description**: The foundational SDK used by tens of thousands of SaaS companies to orchestrate subscription billing, catch `invoice.payment_failed` and `customer.subscription.updated` events, create hosted Billing Customer Portal sessions, and automate custom in-house recovery sequences.

### 8. 🍂 [Autumn](https://github.com/useautumn/autumn) [![GitHub_Stars](https://img.shields.io/github/stars/useautumn/autumn?style=social&color=white)](https://github.com/useautumn/autumn/stargazers)
- **Primary Language**: TypeScript / Node.js 💻
- **License**: MIT
- **Focus**: Pricing-as-a-Service & Self-Healing Billing Abstraction Layer
- **Description**: Sits between your application code and payment gateway (Stripe). Exposes three streamlined primitives (`/attach`, `/check`, `/track`) to handle complex pricing tiers, credit systems, and entitlement verification, while automatically executing recovery workflows when recurring subscription invoices enter a past-due state.

### 9. 🐘 [Laravel Cashier](https://github.com/laravel/cashier-stripe) [![GitHub_Stars](https://img.shields.io/github/stars/laravel/cashier-stripe?style=social&color=white)](https://github.com/laravel/cashier-stripe/stargazers)
- **Primary Language**: PHP (Laravel) 🐘
- **License**: MIT
- **Focus**: Expressive Subscription Billing, Invoicing & Automated Dunning for Laravel
- **Description**: The official Laravel package for Stripe billing. Handles subscription management, coupon redemption, automated receipt generation, failed charge webhook handling, customer billing portal redirects, and customizable dunning email notifications out-of-the-box. Also available for Paddle (`laravel/cashier-paddle`).

### 10. 📊 [OpenMeter](https://github.com/openmeterio/openmeter) [![GitHub_Stars](https://img.shields.io/github/stars/openmeterio/openmeter?style=social&color=white)](https://github.com/openmeterio/openmeter/stargazers)
- **Primary Language**: Go 🐹
- **License**: Apache-2.0
- **Focus**: Real-Time Metering & Consumption Engine for AI, APIs & DevOps Billing
- **Description**: Cloud-native usage aggregation engine built on Apache Kafka and ClickHouse. Tracks real-time token/API consumption, enforces customer credit limits, and immediately alerts billing engines when accounts hit overdue balances or quota exhaustion to prevent unpaid usage leakage.

### 11. 💻 [Stripe CLI](https://github.com/stripe/stripe-cli) [![GitHub_Stars](https://img.shields.io/github/stars/stripe/stripe-cli?style=social&color=white)](https://github.com/stripe/stripe-cli/stargazers)
- **Primary Language**: Go 🐹
- **License**: Apache-2.0
- **Focus**: Local Webhook Testing, Dunning Simulation & Subscription Event Mocking
- **Description**: An indispensable development and debugging tool that streams Stripe events directly to local development machines. Essential for testing dunning handlers by triggering simulated `charge.failed`, `invoice.payment_action_required`, and card decline webhooks without needing public staging endpoints.

### 12. 🐍 [dj-stripe](https://github.com/dj-stripe/dj-stripe) [![GitHub_Stars](https://img.shields.io/github/stars/dj-stripe/dj-stripe?style=social&color=white)](https://github.com/dj-stripe/dj-stripe/stargazers)
- **Primary Language**: Python (Django) 🐍
- **License**: MIT
- **Focus**: Django Model Mirror for Stripe Subscriptions, Webhooks & Invoices
- **Description**: Automatically synchronizes all Stripe subscription objects, invoices, customer payment methods, and charges directly into local Django models. Makes building custom in-house dunning logic, grace period enforcement, and failed payment alerts effortless within Python web applications.

### 13. 🦀 [Meteroid](https://github.com/meteroid-oss/meteroid) [![GitHub_Stars](https://img.shields.io/github/stars/meteroid-oss/meteroid?style=social&color=white)](https://github.com/meteroid-oss/meteroid/stargazers)
- **Primary Language**: Rust 🦀
- **License**: AGPL-3.0
- **Focus**: High-Performance Pricing Infrastructure & Subscription Recovery
- **Description**: Built in Rust for sub-millisecond event processing and scalable subscription architectures. Features automated invoice generation, dynamic tax compliance, multi-currency pricing plans, and pluggable retry/recovery rules for soft credit card rejections.

### 14. 🎯 [Tier](https://github.com/tierrun/tier) [![GitHub_Stars](https://img.shields.io/github/stars/tierrun/tier?style=social&color=white)](https://github.com/tierrun/tier/stargazers)
- **Primary Language**: Go 🐹
- **License**: Apache-2.0
- **Focus**: Pricing-as-Code SDK & Automated Entitlement Enforcement
- **Description**: Manage SaaS subscription pricing models directly from a single `pricing.json` file. Unifies Stripe plan synchronization, feature gating, and payment status checks with clear error states when a customer’s payment method fails.

### 15. 🐻 [BillaBear](https://github.com/billabear/billabear) [![GitHub_Stars](https://img.shields.io/github/stars/billabear/billabear?style=social&color=white)](https://github.com/billabear/billabear/stargazers)
- **Primary Language**: PHP (Symfony) 🛠️
- **License**: Functional Source License (FSL)
- **Focus**: Self-Hosted Subscription Management & Dunning Email Workflows
- **Description**: Complete self-hosted billing engine with native Stripe support. Includes automated dunning sequences, customer churn reports (LTV, MRR, churn rate), multi-currency invoices, EU VAT / tax automation, and self-service payment update widgets.

### 16. 🌐 [Open Payment Host](https://github.com/abishekmuthian/open-payment-host) [![GitHub_Stars](https://img.shields.io/github/stars/abishekmuthian/open-payment-host?style=social&color=white)](https://github.com/abishekmuthian/open-payment-host/stargazers)
- **Primary Language**: Go 🐹
- **License**: AGPL-3.0
- **Focus**: Self-Hosted Multi-Gateway Payment Host & Retry Logic
- **Description**: Lightweight self-hosted payment hub supporting Stripe, Square, PayPal, and Razorpay with webhook processing and failed transaction retry logic. Designed for developers seeking zero-revenue-share payment processing.

---

## ⚙️ The Recovery Pipeline: How Dunning Agents Work

An effective churn recovery agent operates across five coordinated pipeline phases:

```
┌─────────────────┐     ┌──────────────────────┐     ┌───────────────────────┐
│ Payment Failure │ ──> │ Decline Analysis     │ ──> │ Algorithmic Retries   │
│ (Soft / Hard)   │     │ (Issuer Error Codes) │     │ (Smart ML Timing)     │
└─────────────────┘     └──────────────────────┘     └───────────────────────┘
                                                                 │
                                                                 ▼
┌─────────────────┐     ┌──────────────────────┐     ┌───────────────────────┐
│ Revenue Saved / │ <── │ Self-Service Portal  │ <── │ Multi-Channel Dunning │
│ Account Renewed │     │ (Zero-Login Paywall) │     │ (Email / SMS / App)   │
└─────────────────┘     └──────────────────────┘     └───────────────────────┘
```

1. **Decline Categorization**: Distinguishes between **Hard Declines** (stolen card, closed account — immediate outreach required) and **Soft Declines** (insufficient funds, temporary processing error — automated retries appropriate).
2. **Algorithmic Retries**: Avoids naive retries on consecutive days. Schedules retries based on paydays (1st and 15th of month), morning banking processing windows, and card network parameters.
3. **Pre-Dunning Alerts**: Proactively prompts users when their registered credit card is 30/15 days from expiration before a billing failure occurs.
4. **Frictionless Update Flow**: Sends authenticated, single-use tokenized URLs directing the customer to a mobile-responsive update form without requiring password recovery.
5. **Dynamic In-App Interception**: Temporarily degrades feature access via non-intrusive banners or modal paywalls while preserving user data.

---

## 🤝 How to Contribute

We actively welcome contributions from billing engineers, FinTech developers, and SaaS founders!

1. 🍴 **Fork the Repository**: Click Fork on the top right.
2. 🌿 **Create a Branch**: `git checkout -b feature/add-new-recovery-agent`
3. 📝 **Add Your Entry**: Ensure SaaS entries include verified starting tier pricing and specific free trial terms. Ensure open-source entries include the shields.io social Stars_Badge linked to the repo's stargazers page.
4. 📬 **Submit a PR**: Provide a factual, neutral description and relevant links.

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Subscription-Invoicing-Churn-Recovery-Agents&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Subscription-Invoicing-Churn-Recovery-Agents&type=date&legend=top-left)

---

## 💖 Support & Sponsorship

If this curated directory has helped you reduce involuntary churn, recover failed SaaS revenue, or build modern billing infrastructure:

- ⭐ **Star this repository** to help other developers discover it!
- 🍴 **Fork and share** it across your developer communities.
- ☕ **Sponsor the Maintainer**: Support ongoing curation, open-source tooling, and maintenance via the **[GitHub Sponsors Dashboard](https://github.com/sponsors/ishandutta2007)**.

<div align="center">
  <a href="https://github.com/sponsors/ishandutta2007">
    <img src="https://img.shields.io/badge/Sponsor%20on%20GitHub-%E2%9D%A4-ff69b4?style=for-the-badge&logo=githubsponsors" alt="Sponsor on GitHub" />
  </a>
</div>

---

## ⚖️ Disclaimer & Compliance

- This repository is an independently curated educational and technical index. Listing does not constitute an official endorsement.
- All subscription billing platforms and self-hosted recovery mechanisms must comply with **PCI-DSS Level 1 to 4**, **GDPR**, **CCPA**, and applicable national auto-renewal cancellation regulations (e.g., FTC "Click-to-Cancel" rulings and California SB-313).
- Always verify API rate limits, webhook delivery guarantees, and sandbox test harnesses prior to deploying automated dunning agents to live production accounts.

---

<div align="center">
  <sub>Curated with care for SaaS founders, RevOps engineers, and FinTech developers.</sub><br>
  <sub>Found an outdated link or new open-source dunning engine? Please <a href="https://github.com/ishandutta2007/Awesome-Subscription-Invoicing-Churn-Recovery-Agents/issues/new">open an issue</a> or submit a PR!</sub>
</div>
