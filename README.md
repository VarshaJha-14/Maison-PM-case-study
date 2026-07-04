# 🏛️ MAISON

### *Your Personal AI Fashion House*

Try the MVP Prototype: https://maison-ai-stylist.lovable.app

Demo for Stakeholders: https://www.loom.com/share/d5d59be0d6644fc7a8f950d8cee29671

### From Inspiration to Outfit

Transform a screenshot or a simple text prompt into a complete, budget-friendly outfit curated across multiple retailers using AI.

---

![Status](https://img.shields.io/badge/Status-Product%20Case%20Study-6C63FF) ![Stage](https://img.shields.io/badge/Stage-MVP%20Validated-success) ![Domain](https://img.shields.io/badge/Domain-AI%20Product%20Management-orange) ![Focus](https://img.shields.io/badge/Focus-Product%20Strategy-blue)

---

# 📖 Overview

MAISON is an AI-powered fashion decision platform designed to eliminate decision fatigue during online shopping.

Instead of forcing users to browse dozens of products across multiple shopping apps, MAISON allows them to upload an outfit inspiration (Pinterest, Instagram, celebrity looks) or simply describe what they need.

The platform generates **2–3 complete, budget-aware outfits** sourced across multiple retailers while explaining *why* each recommendation fits the user's occasion, style, and budget.

Unlike traditional e-commerce platforms that optimize for selling products, MAISON optimizes for helping users make confident fashion decisions.

---

# 🚨 Problem

Today's shopping journey is fragmented.

A typical user often goes through:

Pinterest → Instagram → Google Lens → Myntra → Amazon → H&M → Ajio → Flipkart

...just to recreate one outfit.

This creates:

- Information overload
- Decision fatigue
- Endless comparison
- Budget uncertainty
- Styling confusion

The real problem isn't finding products.

**It's making confident fashion decisions.**

---

# 💡 Solution

MAISON acts as an AI stylist that converts inspiration into complete outfits.

Users can:

✅ Upload an inspiration image
✅ Describe an outfit using natural language
✅ Set budget
✅ Select occasion
✅ Select size

MAISON then:

- Understands the user's intent
- Identifies garments
- Finds similar products
- Builds complete outfits
- Optimizes within budget
- Sources items from multiple retailers
- Explains every recommendation

---

# 🎯 Target Audience

MAISON is scoped around two distinct jobs-to-be-done, not two age brackets — each persona pulls the product in a different direction (image-led vs. text-led), which is a deliberate finding from the discovery phase, not an assumption.

**Primary Persona — Riya, "The Inspiration-Driven Shopper"**
- 24, Product Marketing Executive, Bangalore
- Discovers looks on Pinterest and Instagram
- Enjoys fashion, dislikes the manual work of assembling an outfit across five apps
- Core job: *"Recreate the look I discovered."*

**Secondary Persona — Neha, "The Busy Professional"**
- 29, Senior Consultant, Gurgaon
- Has little time to browse; needs occasion-appropriate outfits fast
- Values speed and trust over style experimentation
- Core job: *"Help me decide what to wear."*

---

# 🧠 Product Thinking

This project covers the complete product lifecycle rather than only UI design.

- Product Discovery
- Problem Validation
- JTBD
- User Personas
- Value Proposition
- Competitive Analysis
- Positioning
- MVP Definition
- RICE & MoSCoW Prioritization
- Product Requirements Document (PRD)
- Agile Backlog
- Responsible AI Design
- Metrics Framework
- Experiment Design
- Go-To-Market Strategy
- **MVP Validation & Post-Launch Learnings**

---

# 🤖 AI Capabilities

MAISON combines multiple AI capabilities:

- Computer Vision / Image Understanding
- Natural Language Processing
- Multi-Retailer Product Retrieval
- Outfit Recommendation Engine
- Budget Optimization
- Personalization Engine
- Responsible AI Framework

---

# 🏗️ MVP Features

### User Input
- Upload inspiration image (primary path)
- Text-based outfit prompt (secondary path)
- Budget input
- Occasion selection (including Job Interview, Wedding, Festival)
- Size preferences

### AI Engine
- Outfit understanding
- Style extraction
- Budget reasoning (hard budget ceiling, validated pre-display)
- Multi-retailer matching
- Outfit generation

### Recommendation
- 2–3 curated outfits, ranked by fit, style match, and price — never by which retailer pays us
- Total outfit price and per-item breakdown
- Buy links per retailer
- "Why this outfit" confidence explanation

### Feedback Loop
- Rate recommendation (1–5 Decision Confidence Score)
- Show alternatives
- Save outfits
- Improve personalization from rating history

---

# 📊 Success Metrics

**North Star Metric**
Decision Confidence Score (DCS) — always reported alongside Recommendation Acceptance Rate (buy-link click-through), since a confidence score that rises without a matching rise in click-through is a signal on its own, not just noise.

**Supporting Metrics**
- Outfit Completion Rate
- Recommendation Acceptance Rate
- Budget Adherence Accuracy
- Catalog Swap Rate
- Time to Complete an Outfit

---

# 🧪 Experimentation

Example experiment included:

### Image-First vs. Text-First Capture

**Hypothesis:** Leading with image upload increases activation for inspiration-driven shoppers, since Pinterest/Instagram-attributed traffic thinks visually.

**Measured through:**
- First-Time Activation Rate
- Drop-off Rate before submission
- Time to First Submission
- Budget-Field Completion Rate

---

# 🔍 Key Learnings from Validation

Recommendation quality alone wasn't the whole picture. Hands-on validation of the prototype surfaced a finding the original scope didn't fully account for, plus several confirmations of risks the discovery phase had only flagged on paper. Full detail in `07_MAISON_MVP_Validation_Report.pdf`.

**Headline finding — Multi-Retailer Checkout Friction:** An outfit that's stylistically optimal across three retailers can still lose to a "good enough" single-retailer outfit, because users weigh delivery count, return policies, and cognitive load alongside style fit — not instead of it. This wasn't in the original ranking logic and is now a planned V2 addition (see Roadmap).

**Other confirmed findings:**
- Budget flexibility is real: users spontaneously asked for near-budget, better-fit alternatives, echoing an early research insight that had been deliberately left unresolved.
- Low-resolution or cropped input images meaningfully degrade garment-detection accuracy — more than model capability alone explains.
- Social sharing before purchase is real, observed behavior (not just a funnel assumption) — users screenshot outfit cards to send to friends unprompted.
- The Decision Confidence Score can rise without matching purchase intent — confirming, in practice, exactly why it's never reported alone.

**Assumptions that changed:**

| Initial Assumption | What We Learned | Product Decision |
|---|---|---|
| Best outfit = highest style-and-budget fit score | Convenience (retailer count, delivery, returns) meaningfully changes what users choose | Add a Purchase Optimization Engine (V2) with a Convenience Score |
| Multi-retailer catalog access is reachable mainly via affiliate feeds, with scraping as a fallback | Scraping is unreliable at the granularity needed; affiliate feeds have real gaps (festive/ethnic wear especially) | Hybrid catalog architecture: affiliate feeds + prioritized direct partnerships for gap categories |
| A hard budget ceiling with no exceptions is the safest default | Users want to see near-budget, better-fit alternatives | Move "near-budget alternative" from an unscheduled idea to an explicit V1 backlog item |

Two decisions that were **not** revised, because they held up exactly as designed from day one: returning 2–3 ranked outfits rather than one, and keeping the AI as an assistant that explains and lets the user choose, rather than one that decides for them.

---

# 🚀 Go-To-Market Strategy

**Launch Channels**
- Pinterest
- Instagram Reels
- Campus Communities
- Fashion Creators
- Micro-Influencers

**Positioning**
> "Stop scrolling five apps for one outfit.
> Show us the look.
> We'll find it within your budget."

---

# 📁 Repository Structure

```
Maison-PM-case-study/
│
├── 01_MAISON_Product_Discovery_and_Strategy.pdf
├── 02_MAISON_PRD_and_Agile_Backlog.pdf
├── 03_MAISON_AI_Feature_and_Responsible_AI.pdf
├── 04_MAISON_Metrics_Experimentation_and_GTM.pdf
├── 05_MAISON_User flow_Diagram.png
├── 06_MAISON_Technical_Architecture_Document.pdf
├── 07_MAISON_MVP_Validation_Report.pdf
├── 08_MAISON_AI_Tool_Usage_Appendix.pdf
└── README.md
```

---

# 📚 Documentation

| # | Document | Description |
|---|---|---|
| 01 | Product Discovery & Strategy | Problem discovery, JTBD, personas, competitive landscape, positioning, desirability validation plan |
| 02 | PRD & Agile Backlog | Functional requirements, user stories, acceptance criteria, risks, sprint-ready backlog |
| 03 | AI Feature & Responsible AI | AI workflow, input/output design, failure cases, privacy and bias guardrails, transparency strategy |
| 04 | Metrics, Experimentation & GTM | North Star metric, KPIs, A/B test design, dashboard plan, pricing model, launch strategy |
| 05 | User Flow Diagram | MVP flowchart, primary path from input to purchase |
| 06 | Technical Architecture Document | System design and integration approach behind the AI and catalog-matching pipeline |
| 07 | MVP Validation Report | Post-prototype learnings, corrected roadmap, and assumptions that changed vs. held up |
| 08 | AI Tool Usage Appendix | How AI tools were used in producing this case study |

---

# 🛠️ Design Process

```
Problem Discovery
        ↓
User Research
        ↓
JTBD
        ↓
Personas
        ↓
Value Proposition
        ↓
Competitive Analysis
        ↓
Product Strategy
        ↓
MVP
        ↓
PRD
        ↓
AI Design
        ↓
Metrics
        ↓
Launch Strategy
        ↓
Validation & Roadmap Iteration
```

---

# 🔮 Roadmap

| Stage | Scope |
|---|---|
| **MVP** | AI outfit generation · Multi-retailer recommendations · Hard budget-ceiling enforcement · 1–5 confidence rating · Product substitution on stock/size unavailability · "Why this outfit" explanation |
| **V1** | Saves · Richer feedback signals · Near-budget, higher-fit alternative (opt-in) · "Share this outfit" export · Weather-aware recommendations · "Prefer fewer retailers" filter |
| **V2** | ⭐ Purchase Optimization Engine (Retailer Count, Shipping Cost, Delivery Time, Convenience Score) · Retailer preference / single-retailer mode · Delivery optimization |
| **V3** | Wardrobe AI / Closet Digitization · Virtual Try-On · Outfit Calendar · Packing Assistant · Multi-country Retail Expansion |

---

# 👩🏻‍💻 About This Project

This repository was created as an end-to-end Product Management case study demonstrating the complete lifecycle of building an AI-first consumer product — including what changed after putting the prototype in front of real users.

The project emphasizes:

- Customer-centric product thinking
- AI product strategy
- UX reasoning
- Product documentation
- Responsible AI
- Experimentation
- Data-driven decision making
- Honest post-validation iteration — documenting what worked, what didn't, and what the team got right on the first try

Rather than focusing only on implementation, the goal is to demonstrate how a product moves from **problem discovery to launch planning to validated iteration**.

---

### ⭐ If you enjoyed exploring this project, feel free to star the repository!

Designed & Documented by **Varsha Jha**
Aspiring Product Manager | Business Analyst | AI Product Enthusiast
