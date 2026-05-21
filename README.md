# FUTURE_PE_01 — AI Website Copy Generator
## BrightPath Academy, Hyderabad | Future Interns · Prompt Engineering Track

## Project Overview

A structured prompt engineering system that generates conversion-focused website copy for local businesses.
This project demonstrates how AI tools (Claude, ChatGPT) can produce professional, client-ready website copy that web agencies typically charge ₹15,000–₹50,000 for.

**Business Chosen:** BrightPath Academy  
**Type:** Competitive Exam Coaching Institute  
**Location:** Ameerpet, Hyderabad, Telangana  
**Courses Offered:** JEE, NEET, CA Foundation/Intermediate, UPSC Foundation  
**Tool Used:** Claude (claude.ai) — claude-sonnet-4  

---

## What This Repository Contains

```
/
├── README.md                  ← This file
├── prompts/
│   ├── 01_homepage_prompt.md  ← Structured prompt for homepage copy
│   ├── 02_services_prompt.md  ← Prompt for service descriptions (reusable per course)
│   ├── 03_cta_prompt.md       ← Prompt for Call-to-Action sections
│   └── 04_tone_adapter.md     ← Prompt to adapt copy for different business types
└── outputs/
    ├── homepage_copy.md       ← Generated homepage copy
    ├── services_copy.md       ← Generated services page copy
    └── cta_sections.md        ← Generated CTA sections
```

---

## Business Chosen: BrightPath Academy

**Why this business?**  
Coaching institutes in Hyderabad are abundant, but most have weak or generic website copy. Students and parents make high-stakes decisions based on websites, yet most institute sites read like 2010-era brochures. This creates a clear gap that AI-assisted copywriting can fill.

**Key Details Used in Prompts:**
- Founded in 2012 (12+ years of credibility)
- Located in Ameerpet — Hyderabad's most recognized education hub
- Batch size capped at 30 students (genuine differentiator)
- Faculty from IIT, AIIMS, and ICAI backgrounds
- 94% selection rate — a specific, verifiable claim
- 3,200+ students placed

---

## Prompt Logic

### Core Principles Behind Every Prompt

1. **Specificity over generality** — Every prompt demands specific numbers, named outcomes, and verifiable claims. Generic phrases like "world-class" or "best-in-class" are explicitly banned.

2. **Benefit-led, not feature-led** — Prompts instruct the AI to always pair a feature with a customer benefit. Not "small batches" — but "small batches, so your doubts never go unanswered."

3. **Audience-aware tone** — Each prompt includes the target audience (students aged 16–24, parents) and specifies an emotional state (anxiety about exams, desire for credibility).

4. **Conversion architecture** — The four sections (Homepage → Services → CTA → Trust) follow a proven copywriting funnel: Attract → Educate → Convert → Reassure.

5. **Reusability** — Variable placeholders `[in brackets]` make every prompt reusable. Swap the business name, location, and USPs to generate copy for a new client in minutes.

---

## How to Reproduce This

### Step 1 — Choose a Business
Pick any local business. Gather:
- Business name, location, type
- Target audience (who they serve)
- 3–5 unique selling points (specific, not generic)
- Social proof (years active, number of customers, ratings)

### Step 2 — Fill the Prompts
Open any of the prompt files in `/prompts/`. Replace all `[bracketed variables]` with your client's information.

### Step 3 — Run Through Claude or ChatGPT
Paste each prompt into claude.ai or chat.openai.com. Generate one section at a time.

### Step 4 — Review and Refine
Ask follow-up questions like:
- "Make the headline 30% punchier"
- "Add more urgency to CTA 3"
- "Rewrite the intro for parents, not students"

### Step 5 — Deliver to Client
Export to Google Docs or Notion. Copy is paste-ready for Framer, Webflow, WordPress, or Wix.

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Claude (claude.ai) | Primary copy generation |
| ChatGPT | Variation testing and headline alternatives |
| Framer AI | Visual website layout (optional) |
| Notion | Client deliverable formatting |

---

## Results: What This System Produced

- Full homepage copy (headline, sub-headline, intro, 4 value props, 2 testimonials)
- 4 complete service descriptions (JEE, NEET, CA, UPSC)
- 4 conversion-optimized CTA sections
- Tone adaptation guide for other business types

**Total time:** ~90 minutes (research + prompt design + generation + review)  
**Equivalent agency cost:** ₹15,000–₹40,000

---

## How to Turn This Into a Paid Project

1. Visit the actual BrightPath Academy (or any coaching centre near you)
2. Show them their current website vs. this copy — side by side
3. Explain what each section improves: clarity, trust signals, conversion path
4. Offer: copy writing + paste into their existing website builder
5. Price suggestion: ₹8,000–₹20,000 for a complete website copy package

Many coaches, clinics, and cafes in Hyderabad have outdated or absent websites. This is a repeatable, scalable service.

---

## GitHub Repository Setup

**Repository name:** `FUTURE_PE_01`  
**Track code:** PE (Prompt Engineering)  
**Visibility:** Public (required for evaluation)

### Steps to publish:
1. Go to [github.com/new](https://github.com/new)
2. Name the repository exactly: `FUTURE_PE_01`
3. Set visibility to **Public**
4. Upload these files:
   - `README.md`
   - `prompts_framework.md`
   - `website_copy_brightpath.md`
5. Submit the repository link for evaluation

> Submissions not following the `FUTURE_PE_TaskNumber` format may not be considered for evaluation.

---

## Connect

Built as part of the Future Interns AI Prompt Engineering Programme.  
Share your version on LinkedIn and tag [@FutureInterns](https://www.linkedin.com/company/future-interns).
