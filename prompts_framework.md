# Structured Prompt Framework — AI Website Copy Generator
# Reusable for any local business. Replace [bracketed variables] for each new client.

---

## PROMPT 1: Homepage Copy

```
You are a professional website copywriter specialising in local businesses in India.
Generate homepage copy for the following business:

BUSINESS DETAILS:
- Name: [BrightPath Academy]
- Type: [Competitive Exam Coaching Institute]
- Location: [Ameerpet, Hyderabad]
- Target audience: [Students aged 16–24 preparing for JEE, NEET, CA exams; also their parents]
- Tone: [Professional and confident — not salesy. Warm but authoritative.]
- Key USPs: [Batch size capped at 30, IIT/AIIMS/CA alumni faculty, 12 years in Hyderabad, 94% selection rate, 3,200+ students placed]
- Social proof available: [Google rating 4.8★, testimonials from IIT/AIIMS selections]

GENERATE IN THIS EXACT STRUCTURE:

1. HEADLINE (max 8 words)
   - Must communicate the core transformation or outcome
   - No generic phrases: "unlock your potential", "world-class", "best in city"
   - Use a verb if possible

2. SUB-HEADLINE (1 sentence, max 20 words)
   - Who it's for + the specific benefit
   - Include a credibility signal (years active, number of students, or location)

3. INTRO PARAGRAPH (60–80 words)
   - Conversational tone, not corporate
   - Address the audience's real fear or desire
   - End with a bridge to the CTA

4. VALUE PROPOSITIONS (4 items)
   - Format: [Feature]: [Benefit to student]
   - Each benefit must begin with "so that" or "which means"
   - Make each one specific — no vague claims

5. STUDENT TESTIMONIALS (2 items)
   - Must feel real: include a specific result (rank, college, year)
   - Attribution: First name, last initial, institution, year
   - Keep each under 50 words

RULES:
- No exclamation marks
- No ALL CAPS
- No generic education buzzwords
- Write in Indian English
- Every claim must be specific and verifiable
```

---

## PROMPT 2: Service Page Description (Run Once Per Course)

```
Write a services page block for ONE course offered by [BrightPath Academy, Hyderabad].

COURSE DETAILS:
- Course name: [JEE Mains + Advanced]
- Duration: [1-year and 2-year options available]
- What's included: [Physics, Chemistry, Maths full syllabus; weekly mock tests; doubt sessions; crash course 30 days before exam; performance analytics]
- Unique differentiator: [Teaching is exam-pattern focused, not textbook-chapter focused; IIT faculty only; personal doubt schedule]
- Student outcome to highlight: [AIR rankings, IIT/NIT selections]
- Batch timings: [Morning 7am, Afternoon 2pm, Weekend-only]
- One specific result stat: [Produced 3 students in top 500 AIR in 2024]

OUTPUT FORMAT — produce exactly this structure:

BADGE LABEL: [Short, exam name only — 2–4 words]

HEADLINE: [Benefit-led, not feature-led. What the student achieves, not what the course contains. Max 10 words.]

BODY COPY: [60 words. Open with the student's real fear or desire. Show you understand the problem before presenting the solution. End with a reason to trust this course specifically.]

INCLUSIONS LIST: [5 bullet points. Start each with a noun. Be specific — no "comprehensive coverage" or "expert guidance". Name what's included and why it matters.]

PROOF STAT: [One sentence. One number. Specific to this course. Avoid percentages if a raw number is more impressive.]

BATCH INFO LINE: [One line. Times + format. Factual, no fluff.]

---

REPEAT THIS PROMPT for each additional course, changing only the COURSE DETAILS section above:
- Course 2: NEET UG
- Course 3: CA Foundation & Intermediate  
- Course 4: UPSC CSE Foundation
```

---

## PROMPT 3: CTA Sections (4 Variants)

```
Write 4 call-to-action (CTA) sections for [BrightPath Academy] website.

BUSINESS CONTEXT:
- Location: [Ameerpet, Hyderabad — well-known education hub, easy to find]
- Phone: [040-4567-8910]
- WhatsApp: [+91-98765-43210]
- Hours: [Mon–Sat, 8am–8pm]
- Key offering: [Free demo class for new students, no registration fee]
- Current urgency: [June batches filling up, only 6 seats left in JEE morning batch]

GENERATE ALL 4 CTAs IN THIS FORMAT:

CTA 1 — PRIMARY (appears above the fold or after hero section)
Purpose: Convert first-time visitors who are curious but not yet committed
Tone: Low pressure, generous offer
Must include: Free offer, specific action, no commitment required

CTA 2 — MID-PAGE (after services section)
Purpose: Capture visitors who are comparing institutes
Tone: Helpful, not pushy
Must include: A counsellor offer, 20-minute call, "no obligations"

CTA 3 — URGENCY (sidebar or mid-scroll banner)
Purpose: Push warm leads who are delaying a decision
Tone: Direct, factual, no fake urgency
Must include: Specific seat count, specific batch name, daily update note

CTA 4 — TRUST/FOOTER (bottom of every page)
Purpose: Final reassurance for hesitant visitors
Tone: Grounded, credibility-first, no pressure
Must include: Years active, Google rating, EMI availability

RULES FOR ALL CTAs:
- Headline: max 7 words
- Supporting copy: 2–3 sentences, under 40 words total
- Button labels: action verbs only. No "Click Here", no "Submit"
- Micro-detail line: one piece of factual info (address, phone, hours)
- No exclamation marks
- No fake urgency ("Act now before it's too late!")
```

---

## PROMPT 4: Tone Adapter (Reuse Copy for a Different Business Type)

```
Adapt the following website copy block for a different type of local business.

ORIGINAL COPY (written for a coaching institute):
[Paste any section from the generated copy above]

ORIGINAL TONE: Professional, structured, results-focused, slightly formal

NEW BUSINESS TYPE: [Choose one: Hair Salon / Cafe / Dental Clinic / Fitness Studio]
NEW LOCATION: [e.g., Banjara Hills, Hyderabad]
NEW TARGET AUDIENCE: [e.g., working professionals aged 25–40 looking for premium grooming]
NEW TONE: [Choose: Friendly + warm / Clinical + reassuring / Casual + playful / Energetic + motivating]

ADAPTATION RULES:
1. Keep identical structure (headline, body, bullet list, CTA, micro-detail)
2. Replace education jargon with the new industry's vocabulary:
   - "exam" → "appointment" / "session" / "treatment"
   - "results/ranks" → "transformation" / "relief" / "experience"
   - "faculty" → "stylist" / "doctor" / "trainer" / "barista"
3. Every feature must still be paired with a benefit ("so you..." / "which means...")
4. Keep sentences under 18 words for mobile readability
5. The audience's real fear/desire must still open the body copy

OUTPUT FORMAT:
Show ORIGINAL and ADAPTED versions side by side, with a 1-line note on what changed and why for each element.
```

---

## PROMPT 5: About Page (Bonus — Story-Driven)

```
Write an About page for [BrightPath Academy, Hyderabad].

FACTS TO INCLUDE:
- Founded: [2012]
- Founder background: [Former IIT Madras graduate who struggled to find quality coaching in Hyderabad]
- Mission: [Make IIT/AIIMS-quality teaching accessible in Hyderabad without relocating to Kota or Delhi]
- Milestones: [500 students by 2015, first AIIMS selection 2016, moved to larger Ameerpet campus 2019, crossed 3,000 students 2023]
- Team: [12 full-time faculty, all entrance exam qualifiers themselves]
- Current focus: [Keeping batch sizes small as the institute grows]

TONE: Personal, honest, slightly vulnerable — this is not a corporate "About Us". Write it as if the founder is speaking directly to a prospective student or parent.

STRUCTURE:
1. Opening hook: A specific moment or turning point (not "our journey began...")
2. The problem we saw: 2–3 sentences on what was missing in Hyderabad coaching
3. What we built: How BrightPath is different in practice, not in theory
4. Where we are now: 2–3 sentences, grounded in real numbers
5. Our promise: One short paragraph, written to the student directly

Word count: 200–250 words. No fluff. Every sentence must earn its place.
```

---

## Variable Reference Sheet

Use this table when setting up prompts for a new client:

| Variable | BrightPath (Example) | Your Client |
|----------|---------------------|-------------|
| Business Name | BrightPath Academy | ___ |
| Business Type | Coaching Institute | ___ |
| Location | Ameerpet, Hyderabad | ___ |
| Target Audience | Students 16–24, JEE/NEET/CA | ___ |
| Tone | Professional, warm | ___ |
| Years Active | 12 | ___ |
| Customers Served | 3,200+ | ___ |
| Key USP 1 | Batch size ≤ 30 | ___ |
| Key USP 2 | IIT/AIIMS faculty | ___ |
| Key USP 3 | 94% selection rate | ___ |
| Social Proof | 4.8★ Google, testimonials | ___ |
| Phone | 040-4567-8910 | ___ |
| Address | Ameerpet, Hyderabad | ___ |
| Urgency Signal | June batches filling | ___ |
| Free Offer | Free demo class | ___ |
