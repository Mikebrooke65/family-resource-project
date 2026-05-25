# AI in Mental Health & Education Platforms

Last updated: May 2026  
Status: First pass complete — landscape mapped, key risks and opportunities identified

---

## Why This Matters for Our Project

People access this resource at challenging moments — late at night, in shock, frightened. A well-designed AI assistant on the site could:

- Guide parents to the most relevant content for their situation
- Provide a warm, non-judgmental first point of contact
- Reduce the overwhelming feeling of "where do I start"
- Be available 24/7 when human support isn't

This is potentially a genuine differentiator — most existing resources are static. But it carries real risks and requires careful design.

---

## The Current Landscape (May 2026)

### Scale of AI in Mental Health
- One in three people have used an AI chatbot for emotional support (National Academy of Medicine, Jan 2026)
- The APA issued a formal health advisory (Nov 2025) warning that GenAI chatbots were not created to deliver mental health care and carry real risks for vulnerable users
- The FDA's Digital Health Advisory Committee has noted the bar for approval must be especially high for children and adolescents
- Purpose-built mental health AI (vs general chatbots) is showing early promise — a 2026 study of 305 adults using a purpose-built mental health chatbot showed reduced depression and anxiety symptoms over 10 weeks

### Key Risks Identified
1. Safeguard degradation — OpenAI acknowledged (Aug 2025) that safety guardrails can be less reliable in long interactions as safety training degrades over extended conversations
2. Scope creep — AI tools initially giving appropriate responses can drift into advice-giving or risk assessment in longer sessions
3. Privacy — Meta (Dec 2025) began using chatbot conversation data for ad targeting; our no-advertising commitment directly addresses this
4. Vulnerable populations — APA specifically notes significant harm to adolescents and other vulnerable populations from inappropriate AI mental health tools
5. False confidence — users may rely on AI when they need human or clinical support

### What IS Working
- AI as a guide and navigator (not therapist) — helping users find relevant information quickly
- AI reducing the barrier to starting a help-seeking journey
- Purpose-built tools with clinical oversight outperform general chatbots significantly
- 24/7 availability fills a genuine gap — crises don't happen 9-5
- Warm, conversational AI reduces the clinical/cold feeling of traditional resource sites
- Best practice: emotional validation with clear limits + actionable information + privacy protection (JMIR study, April 2026)

---

## What Good Looks Like — Design Principles for Our Site

Based on research, an AI assistant on our platform should:

### DO:
- Orient the parent — "Tell me what's happening and I'll point you to the most relevant resources"
- Validate the emotional experience — "This is one of the hardest things a parent can face"
- Provide clear next steps — GP, helplines, relevant content sections
- Know when to hand off — always surface 1737 and Yellow Brick Road when distress is indicated
- Be available 24/7
- Be transparent about what it is — "I'm an AI guide, not a counsellor"
- Protect privacy — no data used for any purpose other than helping this parent in this session

### NEVER:
- Conduct risk assessment
- Provide clinical advice or diagnosis
- Substitute for crisis services
- Engage in extended therapeutic dialogue
- Make the parent feel their child's safety is being managed by an AI

### The Hand-Off Rule
Any indication of immediate safety concern -> immediately surface 1737 (free, 24/7) and recommend calling. AI steps back completely.

---

## NZ Context — Headstrong and Aroha

The Headstrong/Aroha chatbot (University of Auckland) is the only NZ precedent for AI in mental health. Their design decisions are directly relevant to us:

- Uses predefined rules and scripts written by clinical experts — NOT generative AI
- Limited use of GenAI only to make conversations flow more naturally
- Clinically authored and controlled — keeps it safe
- Bicultural design (Kia Haumanu) — te reo Maori and tikanga embedded from the start
- Co-designed with the intended audience (rangatahi)
- Funded by Te Whatu Ora; clinically overseen

Key learning: The predefined-script approach, not generative AI, is the safe design model for a sensitive mental health context. This is what we should build.

Key contacts: Dr Sarah Hetrick and Karolina Stasiak (University of Auckland) — the people in NZ who have actually done this.

---

## AI for Course Delivery

### What's Possible
- Personalised learning paths — AI adapts course content based on where the parent is emotionally and practically
- Intelligent check-ins — "How did that conversation with your child go? Let's adjust what you're working on"
- On-demand Q&A — parent asks a question mid-course, AI answers from course content
- Progress tracking with adaptive pacing

### Phase Recommendation
- Phase 1: Static site with AI navigation assistant only
- Phase 2: AI-enhanced school resources (counsellor Q&A, adaptive parent guides)
- Phase 3: AI layer on courses — personalised pacing, Q&A, check-ins

---

## Technical Options

| Option | Pros | Cons | Fit |
|---|---|---|---|
| Claude API (Anthropic) | Strong safety training, good at sensitive topics, customisable | Requires development | Best fit — safest for sensitive context |
| OpenAI API | Widely used, good docs | Safeguard degradation in long sessions, privacy policy direction concerning | Possible but watch privacy policy |
| Purpose-built MH tools (e.g. Woebot) | Clinically validated | Expensive, limited customisation | Phase 3 option |
| Off-the-shelf chatbot builders | Easy to implement | Not designed for sensitive/crisis context | Not suitable |

Recommendation: Claude API for the navigation assistant — Anthropic's safety-first approach makes it the best fit for a sensitive mental health context, and aligns with our no-advertising, privacy-first values.

---

## Regulatory Considerations (NZ)

- No specific NZ AI regulation for health/mental health tools yet (as of May 2026)
- Privacy Act 2020 applies — must be transparent about data use, storage, purpose
- Health Information Privacy Code applies if health information is collected
- Practical requirement: Privacy policy must clearly state AI conversations are not stored, not shared, not used for any purpose other than helping the user in that session
- Attach clinical advisor before deploying any AI feature — they should sign off on scope and guardrails

---

## Key Principle (Confirmed by Research)

> AI on this platform should be a guide and connector, not a counsellor. It helps parents find what they need. It does not assess risk, provide therapy, or substitute for human support. It always knows when to hand off to a human or helpline.

This principle is well-supported by the research. The risk of going beyond it is well-documented and serious.

---

## Sources
- National Academy of Medicine, Health in the Headlines (January 2026)
- APA Health Advisory on GenAI Chatbots (November 2025)
- JMIR Mental Health — AI Chatbots for Mental Health Self-Management (April 2026)
- PIRG — The Risks of AI Companion Chatbots (January 2026)
- American Academy of Pediatrics — FDA Digital Health Advisory (2025)
- OpenAI safeguard statement (August 2025)
- NZ Doctor (2023) — Headstrong and Aroha chatbot
- JMIR (2022) — Aroha chatbot implementation study
