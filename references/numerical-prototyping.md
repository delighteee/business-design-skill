# Numerical Prototyping (Discovery Driven Planning)

## When to Use
- Evaluating the financial viability of a new idea before building it
- Surfacing hidden assumptions in a business case
- Making a go/no-go recommendation based on evidence, not gut feel
- Estimating the ROI of a design initiative
- Identifying which assumptions need testing most urgently

---

## The Core Idea

Just as designers create visual prototypes to test desirability and usability, we create **financial prototypes** to test viability. The goal is not to predict the future accurately — it's to surface the assumptions the business is betting on so the riskiest ones can be tested first.

Euro Disney lost more than $1M every single day after its 1992 Paris opening. Disney assumed European visitors would behave like American ones — spending patterns, dining habits, alcohol preferences, and visit duration all differed dramatically. A financial prototype would have surfaced each of those assumptions explicitly, and a small, cheap test could have falsified them before hundreds of millions were committed.

**Discovery Driven Planning (DDP)** is the framework. It reverses the typical business case: instead of forecasting forward from current conditions, it works backwards from a desired outcome.

---

## The DDP Process

### Step 1: Start with the End Goal

State a specific, measurable end result you want to achieve.
> "We want to make $100k in yearly profit."

### Step 2: Work Backwards to What Must Be True

Use simple math to calculate what must happen at every level to reach the goal.

> $100k profit at 20% profit margin → needs $500k in revenue → can spend $400k on costs
> $500k revenue / 12 months = $41,666/month
> $41,666/month / 30 days = $1,388/day
> $1,388 / $15 average transaction = 92 customers per day
> 92 customers / 8 operating hours = 11.5 transactions per hour

Keep going until you reach the most granular operational unit — the number of items sold per hour, the number of API calls per user per session, the number of seats per enterprise contract.

### Step 3: Document Every Assumption

Every number you just calculated is an assumption. List them explicitly with a confidence level:

| Assumption | Value | Confidence |
|-----------|-------|-----------|
| Profit margin | 20% | Medium |
| Average transaction value | $15 | Low |
| Customers per day | 92 | Low |
| Operating hours per day | 8 | High |
| Throughput per hour | 11.5 | Medium |

### Step 4: Rank by Risk

The assumptions that are both **low confidence** and **high impact on the outcome** are the ones that could kill the business if wrong. Start there.

### Step 5: Design a Testing Plan

Create the smallest, cheapest test for each high-risk assumption.

> Assumption: "92 customers per day will visit." → Test: run a pop-up for one weekend and count actual foot traffic.
> Assumption: "$15 average transaction." → Test: show a menu to 20 target customers and ask what they'd order.

If an assumption fails, tweak the model until you find a configuration that works — or conclude that no viable configuration exists.

---

## Applying DDP to Design Projects

The same logic applies to design initiatives inside an existing product. Work out the math explicitly.

**Example: Onboarding redesign**
- Current onboarding completion: 40%
- Target: 55%
- Monthly new signups: 10,000
- Improvement: 1,500 more activated users per month
- Average 3-month LTV: $30 per activated user
- Monthly revenue impact: $45,000

This "numerical prototype" makes the design proposal concrete, falsifiable, and persuasive to executives. It also identifies the key assumption: that activated users have a $30 average LTV. If that assumption is wrong (actual LTV is $10), the case is much weaker.

**The Profit Tree approach:** Map how a design change connects to the P&L:
- Every design change either increases revenue or decreases costs
- Revenue increases come through: conversion, activation, retention, upsell, new customers, pricing
- Cost decreases come through: support ticket deflection, automation, self-service, operational efficiency

Build the tree before proposing the design, not after.

---

## Market Sizing as a Numerical Prototype

Before investing in a product or feature, estimate whether the opportunity is worth pursuing. Use top-down or bottom-up approaches:

**Top-down:**
- Start with total market size (from industry reports)
- Apply realistic market share assumptions for your position
- Work down to your addressable opportunity

**Bottom-up:**
- Unit of value × number of potential buyers × your conversion assumptions
- Example: If 10,000 potential enterprise customers exist, and your close rate is 3%, and average contract value is $50k, your annual opportunity is $15M

A numerical prototype of the market catches overconfident assumptions before they become expensive roadmaps.

---

## Common Mistakes to Avoid

**Using DDP to prove, not explore.** The most dangerous use of this tool is retrofitting numbers to justify a decision already made. Use it to stress-test, not validate.

**Using optimistic assumptions on every variable.** If every single assumption needs to be in the top quartile for the business to work, the model is fragile. A realistic model has a mix of confident, moderate, and uncertain assumptions — and the uncertain ones drive the testing plan.

**Stopping at the numbers.** The output of DDP is not a spreadsheet — it's a testing plan. The value is in identifying which assumptions to test, not in the projected outcome.

**Ignoring unit economics.** A product that makes money on each transaction but requires enormous volume to cover fixed costs is a fundamentally different business from one with high margins from day one. The DDP model should make this distinction visible.

---

## Design ROI: Making the Numbers Real

For internal design initiatives, you rarely need full DDP. But you do need some math. Documented cases where design ROI was calculated:

- A form optimization at a major e-commerce company: $300M in additional annual revenue from a single UX change
- A UX overhaul of a financial services platform: 30% reduction in support call volume, directly reducing operational costs
- A ticketing platform redesign: conversion rate moved from 3% to 12% — a 4× improvement
- General Electric's UX investment: 100% productivity increase + $30M first-year savings

The pattern: identify the metric the design change affects, measure before and after, connect to financial outcomes.

Even a conservative estimate based on observed metric changes is more persuasive than a qualitative impact claim. "This could improve conversion" loses to "If this improves conversion by 5%, that's worth $X per month at our current traffic."