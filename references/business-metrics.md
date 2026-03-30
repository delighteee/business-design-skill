# Business Metrics

## When to Use
- Presenting design work to executives or non-design stakeholders
- Making a business case for a design investment
- Understanding what leadership actually cares about
- Connecting your design metric to the financial language of the business

---

## The Executive Mindset

Executives primarily care about five things:
1. Increasing revenues
2. Decreasing costs
3. Acquiring new customers
4. Extracting more value from existing customers
5. Shareholder value (for public companies)

When presenting design work, lead with design impact, then **immediately translate** into whichever of these five applies. Don't make executives do the translation — they won't.

First ask: "What is the main goal of this project, and how is it measured?" Then design your design metric to connect directly to that business metric.

---

## Unit Economics: The Foundation

Unit economics answers whether your business model is fundamentally viable at the level of a single customer. For designers, this matters because it clarifies whether design work should prioritize acquisition, activation, or retention.

**Customer Acquisition Cost (CAC)**
How much it costs to acquire one new paying customer.
> CAC = (Total marketing + sales spend) / New customers acquired
> Example: $10k ads + $10k sales / 100 customers = $200 CAC

**Lifetime Value (LTV)**
Total revenue expected from a customer across their relationship with you.
> LTV (SaaS) = (Average Revenue Per Account × Gross Margin) / Churn Rate
> Example: $30/month × 80% margin / 10% monthly churn = $240 LTV

**LTV:CAC Ratio**
The health check of unit economics.
> Healthy benchmark: 3:1 or above (for every $1 spent acquiring a customer, you get $3 back)
> Below 3:1: the business is likely overspending on acquisition relative to the value customers generate

**CAC Payback Period**
How long before you recover the cost of acquiring a customer.
> Payback = CAC / (Monthly revenue per customer × Gross margin)
> Healthy benchmark: under 12 months for SaaS; shorter for consumer products

**Design implication:** When LTV:CAC is below 3:1, the design priority is typically retention (increase LTV) or improving onboarding and conversion (reduce effective CAC). When payback is too long, growth is constrained because cash is tied up recovering acquisition costs.

---

## Revenue Metrics

**Return on Investment (ROI)**
Measures efficiency of any investment.
> ROI = (Value gained − Cost of investment) / Cost of investment
> Example: $100k redesign investment generates $150k additional revenue → ROI = 50%

**Monthly Recurring Revenue (MRR)**
For subscription businesses: total revenue from all active subscribers per month.
> Design impact: improving upgrade flows, reducing churn, and enabling upsells all directly lift MRR

**Annual Recurring Revenue (ARR)**
MRR × 12. Used for annual planning and company valuation.

**Average Revenue Per User (ARPU)**
Total revenue / active users. Shows the per-user monetization rate.
> Design impact: better premium feature design, smoother upgrade UX, and intelligent upsell placement all lift ARPU

**Average Revenue Per Account (ARPA)**
Same as ARPU but measured per account (often used in B2B where one account = multiple seats).

---

## Cost Metrics

**Fixed Costs** — Don't change with volume: rent, salaries, infrastructure, insurance, depreciation.

**Variable Costs** — Scale with output: transaction fees, raw materials, shipping, cloud compute per request, commissions.

**Design implication:** Products with near-zero marginal cost (software, digital content) are structurally powerful — adding one more user costs almost nothing. Every additional user improves unit economics. This is why investing in onboarding quality pays enormous dividends: the cost of serving an additional activated user is negligible.

---

## Customer Base Metrics

**Daily / Weekly / Monthly Active Users (DAU / WAU / MAU)**
Users who took at least one meaningful action in the time period.
> Design impact: engagement features, notifications, habit-building, and value delivery improvements all lift these numbers

**DAU/MAU Ratio — Stickiness**
What % of monthly users return every day? Higher = stickier product.
> Social apps target 50%+. Most SaaS products target 15–25%.

**Activation Rate**
The % of new users who reach the "aha moment" — the point where they've experienced the core value.
> This is one of the highest-leverage design metrics. Users who activate have dramatically higher retention and LTV.

**Customer Churn Rate**
Rate at which customers stop paying.
> Churn = Customers lost / Customers at start of period
> Healthy SaaS benchmark: 0.5–1% monthly (5–7% annually)
> High churn is often a design problem: poor onboarding, confusing UX, lack of perceived ongoing value

**Net Revenue Retention (NRR)**
How much recurring revenue you retain from existing customers, including expansion (upsells) and contraction (downgrades, churns).
> NRR = (Starting MRR + Expansion − Contraction − Churn) / Starting MRR
> Above 100% = existing customers are growing your revenue even without new acquisition
> Best-in-class SaaS companies achieve 120–130% NRR

**Viral Coefficient**
How many new users each existing user generates through referrals or organic sharing.
> Viral coefficient > 1.0 = explosive growth (each user brings more than one new user on average)
> Design impact: invitation mechanics, share flows, referral programs, in-product social features

---

## SaaS-Specific: The Rule of 40

A benchmark used by investors and executives to assess whether a SaaS company is creating value sustainably.

> **Rule of 40 score = Growth Rate (%) + Free Cash Flow Margin (%)**
> Healthy score: ≥ 40

Examples:
- 30% growth + 15% FCF margin = 45 score ✓
- 8% growth + 10% FCF margin = 18 score ✗
- 50% growth + −10% FCF margin = 40 score (borderline ✓)

**Why it matters for designers:** Companies above 40 have runway to invest in new features and experiences. Companies below 40 are under pressure to prioritize efficiency — retention, self-service, support cost reduction — over growth features.

As of 2025, the median Rule of 40 score across tracked SaaS companies is only 12%. Companies that achieve it command a 129% valuation premium over those that don't.

---

## Cohort Analysis: Understanding Users Over Time

Cohort analysis breaks users into groups by when they joined (or by behavior) and tracks how those groups behave over time. It reveals whether product changes are actually working — in a way that aggregate averages hide.

**What it reveals:**
- Is the most recent cohort retained better than the one from 3 months ago? (Did the design change help?)
- Do users who complete a specific onboarding step retain better than those who don't? (Is that step worth optimizing?)
- Which acquisition channel produces users with the best long-term behavior?

**Example:** A fintech app redesigns onboarding in March.
- January cohort (pre-redesign): 30% Day-30 retention
- April cohort (post-redesign): 42% Day-30 retention
The cohort comparison makes the improvement visible in a way that aggregate retention numbers cannot.

**Design application:**
- Test design changes by comparing cohort curves before and after
- Find the "activation event" — the action that predicts high retention — and optimize onboarding to reach it faster
- Identify which user segments retain well vs. poorly and focus design effort accordingly

---

## The Design Decision → Business Outcome Table

| Design Action | Business Impact |
|--------------|-----------------|
| Better onboarding → more users activate | ↑ Activation rate, ↓ effective CAC |
| Smoother upgrade flow → more users go paid | ↑ MRR, ↑ ARPU |
| Self-service UX → fewer support tickets | ↓ Variable costs, ↑ margins |
| Habit-building design → higher retention | ↓ Churn, ↑ LTV, ↑ NRR |
| Features users actually use → higher engagement | ↑ DAU/MAU, ↑ NPS, ↑ stickiness |
| Frictionless referral flows | ↑ Viral coefficient, ↓ effective CAC |
| Expansion feature design (upsell, cross-sell) | ↑ NRR, ↑ ARPA |
| Frictionless checkout → fewer abandoned purchases | ↑ Conversion, ↑ Revenue |

Make these connections explicit in every design presentation. The designer who can say "this onboarding change is worth $450k/month in recovered activation revenue" earns a seat at the strategy table.