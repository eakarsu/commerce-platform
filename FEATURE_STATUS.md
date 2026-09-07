# Feature status — E-commerce, marketplaces & subscriptions

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 308 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 7 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 1 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 1 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 3 | 0 | Native records/view |
| Reports & analytics | report | 8 | 0 | Native records/view |
| Activity & audit trail | audit | 4 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Fulfillment agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SKU cost registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inbound shipment ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Receiving reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inventory adjustment tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Warehouse loss detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Damage event evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Disposal authorization control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Removal order matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reimbursement eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Replacement cost calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider claim generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Denial appeal workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash reimbursement matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider SKU analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Marketplace account and policy library | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| SKU and listing registry | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Order and settlement ingestion | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Fulfillment inventory ledger | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Inbound shortage detection | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Lost and damaged inventory recovery | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Return and refund reconciliation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Fulfillment fee recalculation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Storage and aged-inventory fee audit | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Commission and referral fee audit | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Duplicate deduction detection | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Reimbursement eligibility engine | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Claim package and submission | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Settlement credit reconciliation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| SKU and marketplace leakage analytics | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Product catalog versioning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer contract ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Entitlement registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subscription lifecycle control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Usage-event ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Minimum commitment validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proration recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Discount expiration monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Renewal uplift enforcement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overage billing calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax and currency validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing invoice detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit and refund audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Corrected billing workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| MRR ARR and leakage analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material passport ledger | records | 1 | 0 | Native records/view |
| Upcycle idea | records | 1 | 0 | Native records/view |
| Material valuation | records | 1 | 0 | Native records/view |
| Listing optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carbon impact | records | 1 | 0 | Native records/view |
| Buyer match | records | 1 | 0 | Native records/view |
| Repair or resell | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pricing strategy | records | 1 | 0 | Native records/view |
| Trend forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sustainability verify | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seller coach | records | 1 | 0 | Native records/view |
| Products | records | 7 | 0 | Native records/view |
| Ad Campaigns | records | 2 | 0 | Native records/view |
| Inventory | records | 5 | 0 | Native records/view |
| Orders | records | 8 | 0 | Native records/view |
| Reviews | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Content | records | 1 | 0 | Native records/view |
| Fraud Detector | records | 1 | 0 | Native records/view |
| Cart Recovery | records | 1 | 0 | Native records/view |
| Trends | records | 1 | 0 | Native records/view |
| Competitors | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| A/B Tests | records | 1 | 0 | Native records/view |
| Forecasts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Segments | records | 1 | 0 | Native records/view |
| Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Growth os | records | 1 | 0 | Native records/view |
| Validation | records | 1 | 0 | Native records/view |
| Suppliers | records | 2 | 0 | Native records/view |
| Creative | records | 1 | 0 | Native records/view |
| Testing | records | 1 | 0 | Native records/view |
| Connectors | integration | 1 | 0 | Provider request records only |
| Dropship operations | records | 1 | 0 | Native records/view |
| Inventory alerts | records | 1 | 0 | Native records/view |
| Payment methods | records | 2 | 0 | Native records/view |
| Checkout | records | 2 | 0 | Native records/view |
| Success | records | 1 | 0 | Native records/view |
| Coupons | records | 2 | 0 | Native records/view |
| Users | records | 2 | 0 | Native records/view |
| Inventory reorder | records | 1 | 0 | Native records/view |
| Price elasticity | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Photo critique | records | 1 | 0 | Native records/view |
| Concierge | records | 1 | 0 | Native records/view |
| Fraud clusters | records | 1 | 0 | Native records/view |
| Visual search | records | 1 | 0 | Native records/view |
| Marketplace sync | records | 1 | 0 | Native records/view |
| Affiliate referrals | records | 1 | 0 | Native records/view |
| Store views | records | 1 | 0 | Native records/view |
| Return risk exchange optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Marketplace Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seller Match | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pricing Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fraud Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demand Signals | records | 2 | 0 | Native records/view |
| Price Suggestions | records | 2 | 0 | Native records/view |
| Price History | records | 1 | 0 | Native records/view |
| Market Trends | records | 2 | 0 | Native records/view |
| AI Insights | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Competitor Tracker | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Demand Forecaster | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Bundle Recommender | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Discount Optimizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Price Tracker | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Pricing Simulation | records | 1 | 0 | Native records/view |
| AI Usage Stats | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bulk Price Update | records | 1 | 0 | Native records/view |
| Password Resets | records | 2 | 0 | Native records/view |
| Password Changes | records | 2 | 0 | Native records/view |
| Session Logs | records | 2 | 0 | Native records/view |
| Pagination Configs | records | 2 | 0 | Native records/view |
| PDF Exports | records | 2 | 0 | Native records/view |
| Confirmation Dialogs | records | 2 | 0 | Native records/view |
| Error Logs | records | 3 | 0 | Native records/view |
| Loading Configs | records | 2 | 0 | Native records/view |
| RBAC Policies | records | 2 | 0 | Native records/view |
| Rate Limit Logs | records | 2 | 0 | Native records/view |
| Security Headers | records | 2 | 0 | Native records/view |
| Email Verifications | records | 2 | 0 | Native records/view |
| Password Validations | records | 2 | 0 | Native records/view |
| agentic pricing optimization | records | 1 | 0 | Native records/view |
| demand forecasting ensemble | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| price elasticity modeling | records | 1 | 0 | Native records/view |
| competitive intelligence | records | 1 | 0 | Native records/view |
| discount optimization | records | 1 | 0 | Native records/view |
| stronger price elasticity models per | records | 1 | 0 | Native records/view |
| auto | records | 1 | 0 | Native records/view |
| dedicated routes directory all inline | records | 1 | 0 | Native records/view |
| webhooks for price | integration | 1 | 0 | Provider request records only |
| limited integrations no shopify amazon ebay adapte | integration | 1 | 0 | Provider request records only |
| notifications module | records | 1 | 0 | Native records/view |
| Box Curator | records | 1 | 0 | Native records/view |
| Product Discovery | records | 1 | 0 | Native records/view |
| Price Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Theme Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Description Writer | records | 1 | 0 | Native records/view |
| Feedback Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Personalized Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Marketing Copy | records | 1 | 0 | Native records/view |
| Quality Scorer | records | 1 | 0 | Native records/view |
| Trend Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer Segmentation | records | 1 | 0 | Native records/view |
| Customer LTV Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unboxing Arrangement | records | 1 | 0 | Native records/view |
| Competitor Price Monitor | records | 1 | 0 | Native records/view |
| Preference Bandit | records | 1 | 0 | Native records/view |
| Subscription boxes | records | 1 | 0 | Native records/view |
| Feedback | records | 1 | 0 | Native records/view |
| Quiz | records | 1 | 0 | Native records/view |
| Churn | records | 1 | 0 | Native records/view |
| seasonal demand forecasting for inventory spikes around holidays | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| unboxing experience optimization with ai suggested product arrangement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| competitor price monitoring with repricing recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| customer lifetime value prediction to guide acquisition spend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multi armed bandit preference learning loop for product discovery | records | 1 | 0 | Native records/view |
| logistics integrated address validation and label generation | records | 1 | 0 | Native records/view |
| ai endpoints cover the curation workflow well | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| vision based product image quality scoring | records | 1 | 0 | Native records/view |
| conversational box customization chatbot | records | 1 | 0 | Native records/view |
| marketing email sequences for onboarding retention | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| integrations with logistics fulfillment platforms shippo shipstation | integration | 1 | 0 | Provider request records only |
| referral affiliate tracking | records | 1 | 0 | Native records/view |
| pause skip subscription functionality | records | 1 | 0 | Native records/view |
| gift subscription workflow | records | 1 | 0 | Native records/view |
| webhooks or notifications | integration | 1 | 0 | Provider request records only |
| payment processor integration | integration | 1 | 0 | Provider request records only |
| 3D Model Generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Store Layouts | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AR Try-On | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Descriptions | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Style Recommendations | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Store Themes | records | 1 | 0 | Native records/view |
| Promotions | records | 2 | 0 | Native records/view |
| Conversion Tracking | records | 1 | 0 | Native records/view |
| Room Layout Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product Description Enhancer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lighting Mood Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Visitor Behavior Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Showroom Comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Merchandising Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seasonal Layout Recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer Journey Heatmap | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Competitor Showroom Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Results History | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| personalized product recommendations from browsing behavior | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| visual merchandising optimizer using conversion data | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| customer journey heatmap visualizing dwell time | records | 1 | 0 | Native records/view |
| competitor showroom analysis adapting layouts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| seasonal layout promotion recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| 3d model auto generation from product photos | records | 1 | 0 | Native records/view |
| ai driven personalized product recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai visual merchandising optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai generated 3d model auto rigging from photos | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| native webar webxr platform integration | integration | 1 | 0 | Provider request records only |
| customer path heatmap visualization | records | 1 | 0 | Native records/view |
| pos inventory sync | records | 1 | 0 | Native records/view |
| webhooks | integration | 1 | 0 | Provider request records only |
| notifications subsystem | records | 1 | 0 | Native records/view |
| Sales Channels | records | 1 | 0 | Native records/view |
| Pricing Rules | records | 1 | 0 | Native records/view |
| Returns | records | 2 | 0 | Native records/view |
| Shipments | records | 1 | 0 | Native records/view |
| Ebay work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demand seasonality | records | 1 | 0 | Native records/view |
| Seller reputation forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Counterfeit detect | records | 1 | 0 | Native records/view |
| Dynamic shipping | records | 1 | 0 | Native records/view |
| Repeat purchase | records | 1 | 0 | Native records/view |
| Auto source | records | 1 | 0 | Native records/view |
| Auction ending | records | 1 | 0 | Native records/view |
| Payment fraud | records | 1 | 0 | Native records/view |
| Cart | records | 1 | 0 | Native records/view |
| Watchlist | records | 1 | 0 | Native records/view |
| Sell | records | 1 | 0 | Native records/view |
| Dashboard | records | 1 | 0 | Native records/view |
| Onboarding | records | 1 | 0 | Native records/view |
| My listings | records | 1 | 0 | Native records/view |
| Admin | records | 1 | 0 | Native records/view |
| Disputes | records | 1 | 0 | Native records/view |
| Security | records | 1 | 0 | Native records/view |
| Saved searches | records | 1 | 0 | Native records/view |
| Addresses | records | 1 | 0 | Native records/view |
| Collections | records | 2 | 0 | Native records/view |
| Rewards | records | 1 | 0 | Native records/view |
| Payment plans | records | 1 | 0 | Native records/view |
| Price alerts | records | 1 | 0 | Native records/view |
| My offers | records | 1 | 0 | Native records/view |
| Bulk upload | records | 1 | 0 | Native records/view |
| Scheduled listings | records | 1 | 0 | Native records/view |
| Listing templates | records | 1 | 0 | Native records/view |
| Vacation mode | records | 1 | 0 | Native records/view |
| Compare | records | 1 | 0 | Native records/view |
| Gift cards | records | 1 | 0 | Native records/view |
| Earnings | records | 1 | 0 | Native records/view |
| Roi | records | 1 | 0 | Native records/view |
| Fee optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bundle discounts | records | 1 | 0 | Native records/view |
| My feed | records | 1 | 0 | Native records/view |
| Bid retractions | records | 1 | 0 | Native records/view |
| My coupons | records | 1 | 0 | Native records/view |
| Best match | records | 1 | 0 | Native records/view |
| Experiments | records | 1 | 0 | Native records/view |
| Low stock | records | 1 | 0 | Native records/view |
| Image search | records | 1 | 0 | Native records/view |
| Wallet | records | 1 | 0 | Native records/view |
| Referrals | records | 1 | 0 | Native records/view |
| Flash sales | records | 1 | 0 | Native records/view |
| Group buys | records | 1 | 0 | Native records/view |
| For you | records | 1 | 0 | Native records/view |
| Inventory forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Feed | records | 1 | 0 | Native records/view |
| Deals | records | 1 | 0 | Native records/view |
| Daily deals | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Live | records | 1 | 0 | Native records/view |
| Ebay live | records | 1 | 0 | Native records/view |
| Team | records | 1 | 0 | Native records/view |
| Team access | records | 1 | 0 | Native records/view |
| Vault | records | 1 | 0 | Native records/view |
| Categories | records | 1 | 0 | Native records/view |
| Resolution | records | 1 | 0 | Native records/view |
| Membership | records | 1 | 0 | Native records/view |
| Gsp | records | 1 | 0 | Native records/view |
| Global shipping | records | 1 | 0 | Native records/view |
| Seller performance | records | 1 | 0 | Native records/view |
| Proxy bidding | records | 1 | 0 | Native records/view |
| My bids | records | 1 | 0 | Native records/view |
| Local pickup | records | 1 | 0 | Native records/view |
| Policies | records | 1 | 0 | Native records/view |
| Careers | records | 1 | 0 | Native records/view |
| Government | records | 1 | 0 | Native records/view |
| Stores | records | 1 | 0 | Native records/view |
| Apps | records | 1 | 0 | Native records/view |
| Sitemap | records | 1 | 0 | Native records/view |
| Promoted listings | records | 1 | 0 | Native records/view |
| Second chance offers | records | 1 | 0 | Native records/view |
| Authenticity guarantee | records | 1 | 0 | Native records/view |
| Motors | records | 1 | 0 | Native records/view |
| Charity | records | 1 | 0 | Native records/view |
| Import duties | records | 1 | 0 | Native records/view |
| Selling limits | records | 1 | 0 | Native records/view |
| Volume pricing | records | 1 | 0 | Native records/view |
| Features | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demand reputation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Security audit | records | 1 | 0 | Native records/view |
| Token blacklist | records | 1 | 0 | Native records/view |
| Validation rules | records | 1 | 0 | Native records/view |
| Discounts | records | 1 | 0 | Native records/view |
| CSV Export | records | 3 | 0 | Native records/view |
| Margin Guard | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 308 feature pages were visited in the browser; 306 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 112 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

112 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
