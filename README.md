# Awesome-Subscription-Invoicing-Churn-Recovery-Agents

# Top Subscription Invoicing & Churn Recovery Agents Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Dunning Automation, Involuntary Churn Reduction & Failed Payment Recovery*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Subscription Invoicing & Churn Recovery Agents**. These tools automatically recover failed payments, retry soft card declines, orchestrate dunning communications, and prevent involuntary churn — turning what used to be manual collections work into an automated revenue recovery pipeline.

**Examples** include Churnkey, ProfitWell Retain (Paddle), Baremetrics Recover, Gravy Solutions, Flexpay, Stripe Billing, Chargebee, Recurly, Maxio, and Paddle (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom dunning logic, and transparent recovery analytics — ideal for SaaS teams prioritizing data sovereignty, developers building billing infrastructure, and organizations avoiding revenue-share pricing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Churnkey](https://churnkey.co/)**  
  Churn recovery platform combining **involuntary churn prevention (failed payment recovery)** with cancel flow optimization. Recovers 15-20% of failed payments through intelligent retry schedules, pre-dunning card update prompts, and personalized email/SMS campaigns. Also reduces voluntary churn through dynamic cancel flows with targeted offers. Used by 500+ subscription businesses including Netflix, Adobe, and Spotify .

- **[ProfitWell Retain (Paddle)](https://www.paddle.com/)**  
  Automated churn recovery tool from ProfitWell (now Paddle). Recovers failed payments using machine learning to determine the optimal time, frequency, and content for each recovery email. Claims 15-20% recovery rate with up to 71% of cancellations prevented. Free for most subscription businesses .

- **[Baremetrics Recover](https://baremetrics.com/features/recover)**  
  Failed payment recovery tool that automatically retries failed charges, sends smart dunning emails, and provides a self-service card update portal for customers. Integrates with Stripe, Braintree, Recurly, and Chargebee. Claims 10-15% recovery rate. Starts at $99/month .

- **[Gravy Solutions](https://gravy.com/)**  
  Human-assisted failed payment recovery service. Combines automated retries with a team of "Gravy Retainers" who personally contact customers to update payment information. Claims 80% recovery rate on failed payments. Usage-based pricing plus base platform fee .

- **[Flexpay](https://flexpay.io/)**  
  Payment recovery platform focused on high-ticket subscription businesses. Uses AI-driven retry timing and multi-channel outreach including phone calls, emails, and SMS. Claims 40-60% recovery rates for high-value transactions .

- **[Stripe Billing](https://stripe.com/billing)**  
  Native subscription billing with built-in Smart Retries that use machine learning to choose optimal retry timing. Supports dunning emails, hosted invoices, and customer portal for payment updates. Available on all Stripe accounts; advanced recovery features on Billing plans starting at 0.5% of billing volume .

- **[Chargebee](https://www.chargebee.com/)**  
  Subscription billing platform with dunning management, smart retries, and recovery workflows. Includes pre-dunning, card expiry alerts, and customizable recovery campaigns. Pricing scales with revenue .

- **[Recurly](https://recurly.com/)**  
  Subscription billing and revenue recovery platform with machine learning-based dunning optimization. Features Account Updater, smart retries, and pre-dunning communications. Enterprise-focused pricing .

- **[Maxio](https://www.maxio.com/)**  
  Billing and subscription management platform for SaaS companies with revenue recovery and dunning automation. Targets mid-market and enterprise SaaS .

- **[Paddle](https://www.paddle.com/)**  
  Merchant of record platform with built-in subscription billing, dunning management, and revenue recovery. Handles tax compliance and payment processing globally. Charges 5% + $0.50 per transaction .

## Open-Source GitHub Projects

- **[Churnkey Alternatives & Open-Source Dunning](https://github.com/topics/dunning)**  
  GitHub topic aggregating open-source dunning, payment recovery, and subscription billing projects. Includes libraries for Stripe webhook handling, retry logic, and customer recovery workflows.

- **[Kill Bill](https://github.com/killbill/killbill)**  
  **The most mature open-source subscription billing and payments platform.** Handles invoicing, payment retries, dunning, and revenue recovery. Features plugin architecture for payment gateways (Stripe, PayPal, Adyen, Braintree), entitlement management, analytics, and a full REST API. Apache 2.0 licensed. Used by enterprise SaaS, telecom, and media companies. Self-hosted with Java and MySQL/PostgreSQL .

- **[Lago](https://github.com/getlago/lago)**  
  Open-source usage-based billing and subscription management platform positioned as an alternative to Stripe Billing and Chargebee. Send usage events via API; Lago meters them, applies plans and taxes, and issues PDF invoices. Supports subscriptions, credits, hybrid pricing, and payment provider integrations (Stripe, Adyen, GoCardless). Features **retry logic for failed payments**, dunning workflows, and revenue analytics. AGPL-3.0 licensed .

- **[BillaBear](https://github.com/billabear/billabear)**  
  Open-source subscription management and billing system with Stripe integration, tax management (EU VAT, VAT Sense), workflows for async tasks, and multi-currency support. Includes **subscription reports (LTV, churn), dunning, vouchers, credit notes, and customer-facing frontend via Stripe.js**. Docker deployment with Symfony/PHP stack .

- **[Meteroid](https://github.com/meteroid-oss/meteroid)**  
  Open-source billing and subscription management platform built in Rust for high-performance usage event processing. Supports subscription billing, usage-based pricing, hybrid models, invoicing with tax compliance, coupons, trials, and revenue analytics. API-first architecture with **retry and recovery logic** for failed payments .

- **[Autumn](https://github.com/useautumn/autumn)**  
  Open-source pricing and billing layer between Stripe and applications. Supports subscriptions, credit systems, usage-based models, and custom plans. Provides three core functions (`/attach`, `/check`, `/track`) for embedding billing logic with minimal code. Includes **recovery workflows for failed payments** through Stripe integration .

- **[Open Payment Host](https://github.com/abishekmuthian/open-payment-host)**  
  Self-hosted payment and subscription host supporting Stripe, Square, PayPal, and Razorpay with webhook integration. Features subscription management, payment processing, and **failed payment retry logic**. Go-based with Docker support .

- **[JustSubs](https://github.com/ridho/justsubs)**  
  Self-hosted Laravel subscription and billing infrastructure with polymorphic subscribers, built-in dashboard, and agnostic payment drivers. Includes **renewal and dunning workflows** for subscription lifecycle management. MIT licensed .

- **[Laravel Cashier](https://github.com/laravel/cashier-stripe)**  
  Official Laravel package for Stripe subscription billing. Handles subscriptions, one-time charges, invoices, and **failed payment recovery** through Stripe's Smart Retries. Includes webhook handling, customer portal, and dunning email integration. MIT licensed. Also available for Paddle (`laravel/cashier-paddle`) .

- **[Django Stripe Subscriptions](https://github.com/oscartbeaumont/django-stripe-subscriptions)**  
  Django app for Stripe subscription billing with **payment retry and recovery workflows**. Handles subscription creation, plan changes, cancellation, and webhook processing. MIT licensed.

- **[Stripe Smart Retries (Open-Source Reimplementations)](https://github.com/topics/stripe-smart-retries)**  
  Community implementations of intelligent retry logic for failed Stripe payments. Includes ML-based retry timing, exponential backoff strategies, and dunning email sequences.

- **[subscription-recovery](https://github.com/topics/subscription-recovery)**  
  GitHub topic aggregating open-source subscription recovery tools, dunning libraries, and failed payment retry implementations.

### Additional Strong Open-Source Options

- **[Stripe CLI](https://github.com/stripe/stripe-cli)** — Command-line tool for testing Stripe webhooks and subscription events. Invaluable for developing and debugging recovery workflows locally .
- **[Stripe Node.js SDK](https://github.com/stripe/stripe-node)** — Official Node.js library for Stripe API including subscription, invoice, and payment intent management .
- **[Stripe Python SDK](https://github.com/stripe/stripe-python)** — Official Python library for Stripe API .
- **[Stripe Ruby SDK](https://github.com/stripe/stripe-ruby)** — Official Ruby library for Stripe API .
- **Webhook Testing Tools** — Stripe CLI, ngrok, and webhook.site for developing and testing dunning webhook handlers.
- **Email Delivery** — Listmonk, Postal, and Mautic for self-hosted dunning email campaigns.

**Frameworks for building custom systems**: Combine **Kill Bill** for full subscription billing with dunning and retries, **Lago** for usage-based billing with recovery workflows, **BillaBear** for Stripe-native subscription management with dunning, **Laravel Cashier** or **Django Stripe Subscriptions** for framework-native billing integration, and **Open Payment Host** for multi-gateway payment processing to build a complete self-hosted churn recovery stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Subscription invoicing and churn recovery tools must comply with payment card industry standards (PCI-DSS), data protection regulations (GDPR, CCPA), and consumer protection laws regarding recurring billing and cancellation.
- Self-hosted open-source solutions require proper security hardening, payment gateway integration testing, and ongoing compliance monitoring.

---

**Made for SaaS operators, billing engineers, revenue operations teams, and developers building subscription recovery platforms.**  
Let's make subscription invoicing and churn recovery more open, data-sovereign, and revenue-friendly.
