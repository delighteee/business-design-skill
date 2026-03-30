# Competitor Analysis

## When to Use
- Starting a new product or feature — understand the landscape before designing
- Differentiating your product — find where competitors are weak or absent
- Anticipating how competitors will react to your design decisions
- Building a stakeholder presentation grounded in market reality

---

## Step 1: Identify Your Competitors

**Direct competitors** — offer the same product or service
**Indirect competitors** — offer a different product that solves the same underlying problem (use JTBD thinking: what else could a customer use to accomplish the same job?)
**Future competitors** — large platforms (tech companies, banks, telecom operators) that could enter your market

> Example: For a project management tool, direct competitors are Asana, Linear, ClickUp. Indirect competitors are email threads, spreadsheets, and shared docs. Future competitors are Microsoft, Notion, and any platform that wants to be "the work OS."

Aim for **4–10 competitors** — a mix of direct and indirect. Beyond 10, signal-to-noise degrades.

---

## Step 2: Gather Data Across Four Buckets

**Arena**
- What industry or sub-industry are they in?
- What is their size and market position?
- Are they growing, plateauing, or shrinking?
- Which customer clusters do they dominate?
- Who are the dominant players in their segment?

**Business**
- Founding year, revenue model (subscription, transaction, freemium, ads)
- Estimated revenue, funding rounds, revenue trend
- Market share, profitability, user/customer base size

**Product**
- Core competitive advantage
- Product portfolio and feature set
- What features do they conspicuously NOT offer? (These are your opportunities)
- Pricing model and price points

**Customer**
- Primary target group and user problem being solved
- Customer reviews across App Store, Google Play, Trustpilot, G2, Reddit
- What people love (understand what they'll defend) and what they complain about (your design opportunities)

---

## Step 3: Useful Sources

- Competitor's own website, pricing page, blog, and job postings (hiring tells you strategic direction)
- Meta Ad Library and Google Ads Transparency for messaging and positioning cues
- Wikipedia and Crunchbase for funding history and scale
- Google News for recent strategic moves
- Annual reports (public companies)
- G2, Trustpilot, App Store, Reddit — the richest source of authentic customer sentiment

**Mining reviews for insight:** Pattern recognition matters more than individual complaints. If 5 users mention a problem, it's noteworthy. If 50 mention it, it's a design opportunity. Look for emotional language: "confusing" and "unintuitive" = UX gaps; "slow" or "buggy" = performance gaps; "waste of time" = value proposition gaps. Extended complaint paragraphs indicate high-importance features that are failing.

---

## Step 4: Modern Analysis Frameworks

### Perceptual Mapping
Plot competitors on a 2×2 matrix comparing two dimensions that matter most to customers (e.g., price vs. simplicity, breadth vs. depth). This reveals market whitespace — segments with high demand and low competitive density. If the map is crowded in one quadrant, that's a red ocean. Empty quadrants are potential blue oceans.

### Competitive UX Teardown
Systematically deconstruct a competitor's product across layers:
- **User flows:** How do they onboard? What's the path to first value?
- **Feature set:** What jobs does each feature serve? What's missing?
- **Design patterns:** Navigation, feedback, error handling, empty states — are they better or worse than yours?
- **Engagement loops:** How do they bring users back? Notifications, streaks, social triggers?
- **Monetization:** Where and how do they ask for money? Does it feel earned or forced?

Document with screenshots. Finish with a quick SWOT of the competitor's *product* (not the company). This synthesis often surfaces more than a feature matrix alone.

### JTBD Competitor Mapping
Instead of mapping products against each other, map against the customer job:
1. Define the core job your customer is trying to accomplish
2. For each competitor (direct and indirect), score: how well does it accomplish each step of that job?
3. Identify which steps are poorly served across all competitors
4. That's your whitespace — design for the underserved job step

---

## What the Best Companies Did

**Figma** spent three years in stealth building on WebGL while every major competitor (Sketch, Adobe XD, InVision) was committed to desktop apps. Their analysis wasn't "let's make a better Sketch" — it was "what are Sketch users frustrated by?" The answer: version conflicts, file handoffs, the designer-developer gap. Every Figma feature (multiplayer cursors, live inspect, shared libraries) maps to a specific competitor frustration. Figma won by designing against the friction their competitors created, not by copying their features.

**Slack** ran six months of private beta with 15,000 users, deliberately studying IRC (a 1980s communication tool) alongside modern alternatives. They identified that users valued persistent searchable context over feature richness. Their breakthrough metric — a team that sends 2,000 messages has truly committed to the platform — came from competitor and behavioral research. Competitive analysis of HipChat and Yammer showed feature parity wasn't the problem; adoption and cultural integration were.

**Notion** positioned itself against Microsoft, Airtable, and ClickUp by refusing to dominate any single category. Their competitive strategy was flexibility itself. When Microsoft launched Loop as a direct competitor in 2021, Notion had already built community lock-in and a template ecosystem deep enough to blunt the threat.

---

## Step 5: Synthesize Into Decisions

Don't just compile data — extract strategic implications. Ask:
- What are all competitors doing that customers don't actually value? (Candidates for elimination)
- What are customers asking for that no competitor offers? (Your opportunity)
- What trade-offs have competitors made that leave a gap?
- If we entered this market tomorrow, what would we build that no one else has?

**Visualize:** Plot competitors on 2×2 matrices. Gaps in the map are where you should play.

**Key principle:** Use competitor analysis for insight, not imitation. The goal is understanding why competitors made the choices they did — and finding the places they were wrong.

---

## Competitive War-Gaming

Before major launches or strategy shifts, run a war game: a structured session where teams role-play as competitors responding to your planned moves.

Structure:
- **Home team** (5–8 cross-functional members): your company
- **Competitor teams** (2–3 teams): key rivals playing themselves
- **Scenario**: a specific event — your product launch, a pricing change, a market entry

This surfaces: hidden assumptions in your strategy, likely competitive responses you haven't designed for, and alignment opportunities across the team. Ideal participants: product leaders, designers, strategy and GTM leads.

---

## Connecting Competitive Analysis to Design

Competitor research should directly inform:
- Your **value proposition** — what you do that others don't
- **Feature prioritization** — don't invest in what competitors already do well
- **Pricing** — where does the market have room?
- **Blue Ocean Canvas** — what to eliminate, reduce, raise, or create (see business-strategy.md)
- **Stakeholder conversations** — show that design decisions are grounded in market reality, not opinion