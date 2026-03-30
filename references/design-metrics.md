# Design Metrics

## When to Use
- Defining success for a product or feature before building it
- Moving design conversations from opinion to evidence
- Connecting design work to outcomes that matter to the team and business
- Building credibility with executives and stakeholders

---

## Design Metrics vs. Business Metrics

| | Design Metrics | Business Metrics |
|--|---------------|-----------------|
| **Measure** | Value created *for users* | Value captured *by the business* |
| **Question** | Is the product doing what users need? | Is the business doing what it needs? |
| **Examples** | % of users who complete a key action, task success rate, time-to-value | Revenue, churn, CAC, MRR |

Both matter. A great design metric *predicts* business metric improvements — but with a lag. When you improve user value, business value follows. This is why you need both.

---

## How to Find Your Design Metric (Two Steps)

**Step 1: What does success look like for our users?**
Identify the core value proposition. Why does this product exist in someone's life? What job does it do for them?

**Step 2: What is the ONE action a user must take to actually extract that value?**
Find the specific behavior that indicates genuine value — not just "logged in," but the thing that made them show up.

---

## The Metric Quality Ladder

Most teams start with mediocre metrics and don't realize it. Here's how to upgrade (Google Calendar example):

| Level | Metric | Why It Falls Short or Works |
|-------|--------|---------------------------|
| OK | "New events created per week" | Goes up just from adding users — doesn't show if the product works better |
| Good | "New events created per week per user" | Per-user is better, but averages hide whether most users do nothing |
| Great | "% of users who create at least one event per week" | Shows what share of the user base takes the key action |
| Excellent | "% of users who create 3+ events per week" | Threshold tied to real value; comparable week-over-week; per-user |

Pattern: move from totals → per-user → binary (did they or didn't they) → threshold (did they *enough* to get real value).

---

## The HEART Framework (Google)

For larger products with multiple features and user journeys, the HEART framework provides a structured lens:

- **Happiness** — User attitudes and satisfaction (NPS, CSAT, survey scores)
- **Engagement** — How actively users interact with the product (sessions per week, feature adoption rates)
- **Adoption** — New users or feature discovery (activation rate, time to first key action)
- **Retention** — Whether users return over time (Day 1/7/30 retention, churn rate)
- **Task Success** — Can users complete their goal efficiently and correctly? (task completion rate, error rate, time-on-task)

You don't need to track all five simultaneously. Pick the two or three most relevant to your current product goals, then expand. Use the **Goals-Signals-Metrics** structure for each: What is the goal? What observable signal indicates progress? What metric captures that signal?

---

## The North Star Metric

A North Star Metric (NSM) is a single number that captures the core value your product delivers to users. It should:
- Reflect genuine user value (not just business revenue)
- Be directly influenced by product team decisions
- Be understood and tracked across the whole organization

**Real examples:**
- **Airbnb:** Nights booked — aligns guest value (accommodation found) with host value (revenue earned) with platform health (transaction volume)
- **Spotify:** Time spent listening — captures the fundamental value of the product (music enjoyment) and drives decisions about recommendations, discovery, and playlist UX
- **Netflix:** Total hours streamed — directly measures entertainment consumption and drives content investment, recommendation algorithm, and UI decisions

**How to define yours:**
1. What is your product's core value proposition to users?
2. What behavior indicates a user is genuinely experiencing that value?
3. Can you express that as a single measurable number?
4. Does it move when you improve the product?

---

## Retention Curves: Reading the Health of a Product

A retention curve shows what % of users return to the product over time. The shape reveals the health of the product more honestly than almost any other single metric.

**Healthy curve:** Sharp initial drop, then flattens at a stable baseline.
- Day 0: 100%
- Day 7: ~40%
- Day 30: ~30% (stable)

The flattening is the signal. Users who found genuine value stayed. The baseline is your product-market fit indicator — the higher it is, the better.

**Broken patterns to watch for:**

*Continuous decline to zero:* No stabilization. The product doesn't deliver lasting value. Onboarding or core value proposition is broken.

*Flat-line at very low Day 1 retention (<10%):* Users aren't experiencing value in the first session. Activation is the problem.

*Gradual decline to a small baseline:* Product works for a narrow segment. Either narrow the target or expand the value.

*The smile curve (rare):* Retention initially drops, then recovers as the network grows. Indicates network effects — more users make the product more valuable, which pulls churned users back. LinkedIn shows this pattern.

**How to act:**
- Measure retention at Day 1, 7, 14, 30, 90 as a baseline set
- Segment by acquisition source — do paid-ad users have different curves than organic?
- Before/after cohort comparison tells you if a design change improved retention
- Identify the "aha moment" — the action that predicts which users stay. Design onboarding to get users there faster.

---

## Four Criteria for a Good Metric

A metric is only useful if it's:

1. **Understandable** — you can explain it in one sentence and discuss it in a meeting without confusion
2. **Comparable** — can be compared to last week, last quarter, another segment, or a competitor benchmark
3. **Actionable** — when it moves, you know what design change to make. Avoid vanity metrics
4. **Normalized** — expressed as a ratio or rate, not a raw count ("% of users" not "number of users")

---

## Vanity Metrics vs. Actionable Metrics

**Vanity metrics** feel good but don't drive decisions:
- Total app downloads
- Total page views
- Social media followers
- Time on site (without context)

**Actionable metrics** tell you what's working and what needs to change:
- Trial-to-paid conversion rate
- % of users who complete onboarding within 3 days
- Cart abandonment rate by step
- Feature adoption rate among target segment
- 30-day retention by cohort

The key test: when this metric changes, do you know *what to do differently*? If not, it's probably vanity.

---

## The Design Metrics Canvas

Once you have your main metric, build it out:

**Main metric** — the one number that defines design success for this product or feature

**Supporting metrics** — secondary signals that explain *why* the main metric moved
> If your main metric is "% of users who complete onboarding," supporting metrics might be step-by-step drop-off rates, time-to-completion, and error rates at each step

**Counter metrics** — measures of what could go wrong if you over-optimize the main metric
> If you gamify onboarding to boost completion, does session quality drop? Does early churn increase? Does support volume spike?

**Business metric link** — explicit connection from your design metric to what stakeholders care about
> "Higher onboarding completion → higher activation rate → higher 30-day retention → lower effective CAC → higher MRR"

---

## Measuring the ROI of Design Work

Design ROI is real and measurable. Real examples:
- A form redesign for a major e-commerce company increased revenue by $300M from a single change
- A UX overhaul reduced support call volume 30% at a financial services company — direct cost reduction
- Improving a ticketing platform's user flow moved conversion from 3% to 12% (4× improvement)
- General Electric's UX investment produced 100% productivity increase and $30M in first-year savings

**ROI calculation approach:**
1. Identify UX KPIs that influence business metrics (conversion rate, task success, error rates, NPS)
2. Track them before and after design changes (require a baseline before you ship)
3. Tie UX metric improvement to financial outcomes (revenue, cost, LTV)
4. ROI = (Financial Benefit − Design Cost) / Design Cost

**Practical tip:** Perfect attribution isn't required to be credible. Even a conservative, documented estimate based on observed metric changes is more persuasive than qualitative impact claims.

---

## Practical Rules

- Set the metric *before* you design — this prevents retrofitting data to tell a comfortable story
- Establish a baseline before you ship — you can't prove improvement without knowing where you started
- Disagree with bad metrics out loud — if a stakeholder proposes downloads as the success metric, say why it's a vanity metric and propose a better one
- Check metrics regularly but don't optimize too fast — give changes time to show real behavioral shifts (at least 2–4 weeks for most products)