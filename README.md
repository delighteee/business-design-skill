# Business Design Skill for AI Tools

A custom skill file that teaches AI tools (Claude, ChatGPT) to think like a business designer — connecting design decisions to business outcomes, speaking the language of stakeholders, and applying the right strategic frameworks at the right time.

Built by a d.MBA alumnus and MBA student at Valar Institute, distilled from training across business and design connected disciplines.

---

## What is a Skill File?

A skill file is a structured context document you add to your AI tool to give it deep, domain-specific knowledge. Instead of re-explaining your context every session, the skill file is always present — making your AI a sharper thinking partner for the work you actually do.

This skill is optimised for **Claude** (via the Cowork desktop app or Projects) but the concepts and frameworks transfer to any AI tool that supports custom instructions or system prompts.

---

## What This Skill Covers

### What Business Design Is (and Isn't)
A clear definition of business design as the intersection of design methodology, design mindset, and business tools — applied to business challenges. Includes what separates it from management consulting, product management, service design, and business development.

### The Six Mindsets of a Business Designer
The thinking habits that distinguish strategic designers: starting with customers, thinking in extremes, prototyping to learn, combining qualitative and quantitative data, embracing small data sets, and thinking visually.

### The Business Design Process
A non-linear five-stage process: Empathize & Explore → Define → Ideate → Prototype → Test. Adapted for business challenges, not just UX problems.

### Framework Repository

| Domain | When to Use |
|--------|-------------|
| **Industry Analysis** | Entering a new market, finding where design has most leverage |
| **Competitor Research** | Understanding the competitive landscape, differentiating your product |
| **Business Strategy** | Defining what to do (and what not to do), positioning |
| **Business Models** | Understanding how value is created, delivered, and captured |
| **Numerical Prototyping** | Testing financial viability of ideas before building |
| **Design Metrics** | Measuring value created for users |
| **Business Metrics** | Speaking the language of executives — revenue, cost, customer metrics |
| **Economics Principles** | Applying supply/demand, scale, and opportunity cost to product decisions |
| **Pre-Project Framing** | Starting any project with the right business questions |

---

## File Structure

```
business-design-skill/
├── README.md
├── SKILL.md                          ← Main skill file
└── references/
    ├── industry-analysis.md
    ├── competitor-analysis.md
    ├── business-strategy.md
    ├── business-models.md
    ├── numerical-prototyping.md
    ├── design-metrics.md
    ├── business-metrics.md
    ├── economics-101.md
    └── pre-project-questions.md
```

---

## How to Use with Claude

### Option 1 — Claude Projects (Recommended)
1. Open [claude.ai](https://claude.ai) and create a new **Project**
2. In Project settings, paste the contents of `SKILL.md` into the **Custom Instructions** field
3. Upload the `references/` files as project knowledge
4. Start a conversation — Claude will apply the business design context automatically

### Option 2 — Cowork (Desktop App)
1. Place the entire `business-design-skill/` folder inside your Cowork skills directory
2. Claude will detect and load the skill automatically in supported sessions

### Option 3 — System Prompt (API or any AI tool)
1. Copy the contents of `SKILL.md`
2. Paste it as the system prompt in your API call, ChatGPT custom instructions, or any AI tool that supports custom context
3. Reference the framework files inline as needed

---

## Example Prompts to Try

Once the skill is loaded, try these to see it in action:

- *"I'm designing a new savings feature for our app. Help me frame the business case before I start."*
- *"What competitive forces should I consider before proposing this product change?"*
- *"Help me build a numerical prototype to test if this idea is financially viable."*
- *"What metrics should I track to demonstrate the business impact of this UX improvement?"*
- *"Walk me through the pre-project questions for this initiative."*

---

## Who This Is For

- Product and UX designers who want to operate more strategically
- Designers preparing for stakeholder or executive presentations
- Design leads building a business case for their team's work
- Anyone bridging the gap between design craft and business impact

---

## About the Author

Tolulope Oyewumi is a Senior Product Designer with experience across fintech and digital products. d.MBA alumnus. MBA student at Valar Institute. Passionate about the intersection of design thinking and business strategy — and building AI workflows that make that thinking accessible. Find me on [LinkedIn](https://www.linkedin.com/in/tolulopeoyewumi/)

---

## Contributing

Found a framework that should be in here? Have a reference file to add? PRs are welcome. Open an issue to discuss before making large changes.

---

## License

MIT — free to use, adapt, and share. Attribution appreciated but not required.
