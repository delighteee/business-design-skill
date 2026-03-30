# Business Models

## When to Use
- Designing a new product or service — understand how it will make money before building it
- Evaluating whether a design decision aligns with how the business captures value
- Mapping the full stakeholder system around a product
- Identifying mismatches between what users need and what the business model rewards

---

## Why Business Models Matter for Designers

A product's UX is not just how someone uses it — it's also how they pay for it, upgrade it, share it, and stop using it. Business model innovation has been shown to have a larger impact on business success than product innovation alone.

Designers who understand business models can:
- Design payment and upgrade flows that align with how the business captures value
- Understand who the real "customer" is (often different from the user)
- Spot model mismatches before they become expensive failures
- Propose business model innovations as part of the design scope

---

## The Ecosystem Map

The Ecosystem Map visualizes the full business model — making abstract "how we make money" questions concrete and actionable.

**Four building blocks:**
- **Actors** — everyone involved in creating, delivering, and capturing value: your company, customers, partners, suppliers, distributors, third parties
- **Flow of Information** — what data moves between actors, how, and in what form
- **Flow of Goods** — how the product or service travels from creator to customer
- **Flow of Money** — who pays whom, how much, when, and in what form

**Three parts of every business model:**

| Part | Definition | Map Location |
|------|-----------|-------------|
| **Value Creation** | How the company produces what it offers | Left side (suppliers, operations) |
| **Value Delivery** | How the product reaches customers | Lower section (channels, distribution) |
| **Value Capture** | How the business gets paid | Upper right (customers, revenue flows) |

**How to build one:**
1. Place your company at the center
2. Add all actors around it
3. Draw arrows for each flow — use different colors for money, goods, and information
4. Label each arrow: what flows, in what quantity, under what conditions
5. Ask: who holds the most power? Where does value leak? Where could a new actor disrupt or be eliminated?

---

## Key Business Model Patterns

Research from the University of St. Gallen identified that 90% of business model innovation results from recombining existing patterns. The most important ones for product designers:

**Subscription** — Recurring payment for continued access. Creates predictable revenue and aligns the business toward retention. Design must ensure continuous perceived value. Examples: Netflix, Spotify, Adobe Creative Cloud, Figma.

**Freemium** — Free core product; pay for advanced features or scale. The free tier must be genuinely valuable (not crippled) and upgrade moments must feel earned, not forced. Examples: Slack, Dropbox, Zoom, Notion.
- Dropbox converts 15% of free users; Slack converts 12%; the critical success factor is that users hit limits *naturally* through real usage, not artificial restrictions.

**Marketplace / Two-Sided Platform** — Connect producers and consumers; capture a transaction fee or commission. Design must simultaneously serve two user types with conflicting needs. Examples: Airbnb, Uber, Etsy, eBay, App Store.

**Usage-Based / Consumption** — You pay for what you use (API calls, data processed, compute hours). Growing rapidly because it aligns cost with actual value received. Creates new UX challenges around billing transparency and spending control. Examples: AWS, Twilio, OpenAI API, Snowflake.

**Advertising** — Users are the product; advertisers pay. Design optimizes for engagement and time-on-platform. Creates inherent tension between user wellbeing and business model incentives. Examples: Facebook, Google, YouTube, TikTok.

**Razor & Blades** — Sell the primary product cheap (or subsidized); profit on consumables or add-ons. Design creates dependency on the consumable. Examples: Printers + ink, gaming consoles + games, Nespresso machines + pods.

**Direct / DTC** — Sell directly to the end consumer, bypassing intermediaries. Design drives every stage of the conversion funnel. Examples: Warby Parker, Casper, DTC brands on Shopify.

**Platform / Ecosystem** — Create infrastructure that third parties build on, capturing value through transactions, licensing, or the data generated. Design must prioritize extensibility, APIs, and third-party experience. Examples: Salesforce AppExchange, iOS App Store, Shopify.

---

## Deep Dives: How Iconic Products Evolved Their Models

**Airbnb — From Room Rental to Hospitality Ecosystem**
- 2008: Simple peer-to-peer room rental, commission-based
- 2017: Added Experiences (local tours and activities) — new revenue stream, same trust infrastructure
- 2018: Airbnb Plus (curated premium homes) — premium tier targeting higher-spending travelers
- 2024: Airbnb Services — book private chefs, massages, and hairstylists even without a stay
The model expanded by leveraging the existing trust infrastructure (reviews, payments, identity) into adjacent hospitality services. Each expansion was a business model innovation, not just a feature addition.

**Spotify — Freemium with Personalization**
Started as subscription-only, switched to freemium in 2012. The breakthrough: offer the full music library on free (genuine value) while limiting convenience (ads, shuffle-only mobile, no offline). By month 3, free users have ~7 playlists — switching costs make them 4× more likely to convert. Final conversion rate: 46% (industry average: 2–5%). The data network effect compounds this: more listeners = better recommendations = more listening = more conversion.

**Amazon Prime — Bundle as Lock-In**
Prime began as a $79/year shipping subscription in 2005. The insight: subsidize shipping losses to increase purchase frequency and basket size. Expanded to Prime Video, Prime Music, Prime Day — each new benefit increases the bundle's value, making cancellation feel like real loss. Now 250M+ members globally, $44B in subscription revenue, plus a new advertising layer added in 2024. The business model innovation was recognizing that lock-in through value bundling is more durable than lock-in through switching costs.

---

## Freemium Design: What Works and What Doesn't

**What works:**
- **Horizontal feature slicing**: Give complete access to core functions; reserve premium features for specific scaling scenarios (not limiting fundamental capabilities)
- Slack doesn't limit message *creation* (core value). It limits message *history* (scaling pain point). Users hit the limit through natural, engaged use.
- Dropbox doesn't limit file types or features. It limits *storage*. Users hit this limit as they generate real value with the product.

**What doesn't work:**
- Limiting the core value so severely that users can't experience what they're supposed to be paying for
- Upgrade prompts that feel manipulative rather than helpful
- Premium features that solve hypothetical future problems rather than real current ones

**The upgrade moment:** The best freemium products create natural, organic moments where users discover they need premium — through genuine use, not engineered frustration. Design for discovery, not friction.

---

## Usage-Based Pricing: UX Challenges

Usage-based pricing is growing because it aligns cost with value received. But it creates unique design problems:

**Bill shock:** Users face unexpected charges when usage spikes. This is primarily a design failure.

**Design solutions:**
- Real-time usage dashboard visible at all times (not buried in account settings)
- Projected monthly bill, updated continuously
- Multi-tiered alerts: 50% (informational), 80% (warning), 95% (urgent with action options)
- User-controlled spending caps with hard stops
- Clear mapping: "This action costs X credits" shown at the point of action

**Principle:** With usage-based pricing, trust is a product feature. Users tolerate higher costs if they understand them in real time.

---

## Business Model Mismatches: How Products Fail

34% of startups fail because they never achieve product-market fit — and business model mismatch is a primary driver. Signs of a mismatch:

**Product-Market Mismatch:** Built for professionals; marketed to non-professionals. Or vice versa. The UX complexity or simplicity creates rejection.

**Pricing-Reality Mismatch:** Premium pricing in a market where the ceiling doesn't support it. The business model requires revenue the market won't generate. (Mobile ESPN: $150M invested, reached only 6% of its sales target because $40/month was untenable for a single-purpose sports service.)

**Value Prop Mismatch:** The business captures value in a way that's misaligned with what users actually value. (Facebook Home: redesigned Android to prioritize Facebook's feed. Users felt they lost their phone.)

**Market Evolution Mismatch:** Business model designed for 2018 market reality; by 2024, a competitor's free tier makes your paid tier look unreasonable.

**Design-driven detection questions:**
- Would 8+ out of 10 target customers pay for exactly this feature set at this price?
- Does every premium feature solve a real, articulated current problem?
- Is the free experience good enough to build genuine habit?
- Could a competitor solve the core job more simply at lower cost?