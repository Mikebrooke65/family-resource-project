## Shared context for both Claude sessions — load this at the start of every conversation

**Last updated:** May 2026  
**Project working title:** TBD (name brainstorming pending)  
**Active contributors:** Mike + Caroline  

---

## What This Project Is

A New Zealand-focused digital resource and education platform for **parents of young people who self-harm**.

The founding insight — now confirmed by research: there is no dedicated, parent-centred resource for self-harm anywhere in New Zealand. Every existing NZ digital mental health tool is youth-facing. Not one is parent-facing. Not one is self-harm specific. We are building the resource we wish had existed when we needed it.

This project is founded on lived family experience combined with commercial and research skills.

---

## The Positioning Statement

> "When your child is self-harming, everything you find online is written for them. This is written for you."

This captures the entire gap, the entire audience, and the entire reason this needs to exist. Use it to guide every content and design decision.

---

## The Problem We're Solving

- NZ ranks **last among OECD countries** for child and youth mental health (UNICEF 2025)
- 25-50% of NZ secondary school students self-harm in any given year (Fleming et al. 2020)
- ~49% lifetime self-harm history among NZ adolescents
- Parents who discover their child is self-harming have **nowhere specific to turn**
- CAMHS only accepts moderate-severe cases — most self-harm presentations are turned away
- GPs and school counsellors are under-resourced and under-trained for this conversation
- Shame, stigma, and silence compound the crisis — parents feel alone and at fault
- Every NZ digital mental health tool is youth-facing — the parent gap is completely unoccupied

**The reframe that makes this different:** normalising the conversation for parents so they don't feel alone or ashamed.

---

## Phased Model

| Phase | Focus | Revenue |
|-------|-------|---------|
| 1 | Free resource — content, credibility, audience | Grants |
| 2 | Schools as paying customers — counsellor toolkit, parent workshops | School licensing |
| 3 | Courses and community for parents — online programmes, membership, one-on-one coaching | Paid courses, membership |

---

## Key Decisions Made

- **Collaboration model:** Shared GitHub repo as single source of truth; both partners use their own Claude Projects referencing this steering file
- **Revenue model:** Mixed — grants + school licensing + paid courses + one-on-one coaching (no advertising)
- **Primary audience:** Parents/whanau (not young people directly)
- **Primary NZ referral partner:** Yellow Brick Road (0800 732 825 | hello@yellowbrickroad.org.nz)
- **AI on site:** Yes — Claude API; guide and navigator only, never counsellor or risk assessor; always hands off to 1737 for crisis
- **Content approach:** Safe messaging guidelines must be followed; contagion-safe design required before any content goes live

---

## Key Decisions Pending

- Working name and brand (priority — domain registration follows immediately)
- Legal/entity structure (charitable trust likely best fit for grants)
- Clinical advisor (Professor Terry Fleming, University of Auckland, is priority contact)
- Technology stack for the site

---

## Key People and Organisations

### Primary Referral Partner
- **Yellow Brick Road** — 0800 732 825 | hello@yellowbrickroad.org.nz | yellowbrickroad.org.nz

### Priority Contacts to Make
- **Professor Terry Fleming** (University of Auckland) — clinical advisor target
- **Dr Tania Cargo** (University of Auckland) — Cure Kids whanau project; Headstrong; one contact, multiple doors
- **Cure Kids** — funding a parent self-harm resource; understand before going public
- **MHF resources team** — resource@mentalhealth.org.nz — obtain whanau self-harm resource

### Crisis References (Always Include in Content)
- **1737** — free call or text, 24/7
- **Youthline** — 0800 376 633, free text 234, 24/7
- **Yellow Brick Road** — 0800 732 825, Mon-Fri

---

## International Comparators

- **Youth Mental Health Foundation** (youthmentalhealthfoundation.org) — closest international model; same founding story, same audience, same phased approach
- **YoungMinds** (youngminds.org.uk) — best-in-class parent-facing resource
- **ReachOut Parents** (parents.au.reachout.com) — strong UX; one-on-one coaching model

---

## Key Principle (Working Assumption)

> AI on this platform should be a **guide and connector**, not a counsellor. It helps parents find what they need. It does not assess risk, provide therapy, or substitute for human support. It always knows when to hand off to a human or helpline.

---

## Critical Constraints (Non-Negotiable)

1. **Clinical credibility** — attach a clinical advisor before publishing anything
2. **Safeguarding** — define crisis response protocol before launch
3. **Contagion-safe content** — all content must follow evidence-based safe messaging guidelines
4. **No advertising** — trust is the product; ads undermine it
5. **AI guardrails** — AI assistant must never conduct risk assessment, provide clinical advice, or substitute for crisis services

---

## How to Use This File

**Claude Project setup (one time):**
Paste the entire contents of this file into your Claude Project Instructions. Every conversation in the Project will then have full context automatically.

**Each working session:**
- Paste the raw GitHub URL of the file you want to work on — Claude will fetch it directly
- All URLs are listed below in the GitHub Raw File URLs section
- Tell Claude what you want to work on
- At the end of the session, copy Claude's output back into the relevant file and commit to GitHub

**Important:** Always paste URLs directly into the chat — do not ask Claude to construct URLs itself.

**Repo:** https://github.com/Mikebrooke65/family-resource-project

---

## Repository File Inventory (as at May 2026)

| File | Status | Notes |
|---|---|---|
| STEERING.md | Complete | Load every session |
| README.md | Complete | How the repo works |
| todo/master-todo.md | Complete | Prioritised task list |
| admin/decisions-log.md | Complete | Key decisions and rationale |
| admin/caroline-instructions.md | Complete | Setup guide for Caroline |
| research/nz-landscape.md | Comprehensive | Full audit — all organisations and digital tools |
| research/international.md | First pass complete | Key comparators mapped |
| research/ai-in-mh.md | First pass complete | Risks, opportunities, design principles |
| docs/business-case.md | Seeded | Needs expanding |
| docs/brand-brief.md | Complete | Name shortlist ready for Caroline |
| docs/parent-emotional-journey.md | Complete | Essential brand and content foundation |
| docs/site-architecture.md | Not started | — |
| content/drafts/ | Empty | — |

---

## GitHub Raw File URLs (for direct access in Claude sessions)

### Core Files
STEERING.md
https://raw.githubusercontent.com/Mikebrooke65/family-resource-project/refs/heads/main/STEERING.md

README.md
https://raw.githubusercontent.com/Mikebrooke65/family-resource-project/refs/heads/main/README.md

### Todo
todo/master-todo.md
https://raw.githubusercontent.com/Mikebrooke65/family-resource-project/refs/heads/main/todo/master-todo.md

### Research
research/nz-landscape.md
https://raw.githubusercontent.com/Mikebrooke65/family-resource-project/refs/heads/main/research/nz-landscape.md

research/international.md
https://raw.githubusercontent.com/Mikebrooke65/family-resource-project/refs/heads/main/research/international.md

research/ai-in-mh.md
https://raw.githubusercontent.com/Mikebrooke65/family-resource-project/refs/heads/main/research/ai-in-mh.md

### Docs
docs/business-case.md
https://raw.githubusercontent.com/Mikebrooke65/family-resource-project/refs/heads/main/docs/business-case.md

docs/brand-brief.md
https://raw.githubusercontent.com/Mikebrooke65/family-resource-project/refs/heads/main/docs/brand-brief.md

docs/parent-emotional-journey.md
https://raw.githubusercontent.com/Mikebrooke65/family-resource-project/refs/heads/main/docs/parent-emotional-journey.md

docs/site-architecture.md
https://raw.githubusercontent.com/Mikebrooke65/family-resource-project/refs/heads/main/docs/site-architecture.md

### Admin
admin/decisions-log.md
https://raw.githubusercontent.com/Mikebrooke65/family-resource-project/refs/heads/main/admin/decisions-log.md

admin/caroline-instructions.md
https://raw.githubusercontent.com/Mikebrooke65/family-resource-project/refs/heads/main/admin/caroline-instructions.md
> AI on this platform should be a **guide and connector**, not a counsellor. It helps parents find what they need. It does not assess risk, provide therapy, or substitute for human support. It always knows when to hand off to a human or helpline.
