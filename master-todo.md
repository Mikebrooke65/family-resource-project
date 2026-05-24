# Project Steering File
## Shared context for both Claude sessions — load this at the start of every conversation

**Last updated:** May 2026  
**Project working title:** TBD (see `admin/decisions-log.md`)  
**Active contributors:** [Name 1] + Caroline  

---

## What This Project Is

A New Zealand-focused digital resource and education platform for **parents of young people who self-harm**.

The founding insight: there is no dedicated, parent-centred hub for self-harm in New Zealand. Everything that exists is scattered, generic, or aimed at clinicians. We are building the resource we wish had existed when we needed it.

This project is founded on lived family experience combined with commercial and research skills.

---

## The Problem We're Solving

- NZ ranks **last among OECD countries** for child and youth mental health (UNICEF 2025)
- ~49% of NZ adolescents have a lifetime history of self-harm
- Parents who discover their child is self-harming have **nowhere specific to turn**
- Shame, stigma, and silence compound the crisis — parents feel alone and at fault
- Existing resources are scattered, generic, or clinician-facing

**The reframe that makes this different:** normalising the conversation for parents so they don't feel alone or ashamed.

---

## Phased Model

| Phase | Focus | Revenue |
|-------|-------|---------|
| 1 | Free resource — content, credibility, audience | Grants |
| 2 | Schools as paying customers — counsellor toolkit, parent workshops | School licensing |
| 3 | Courses and community for parents — online programmes, membership | Paid courses, membership |

---

## Key Decisions Made

See `admin/decisions-log.md` for full history.

- **Collaboration model:** Shared GitHub repo as single source of truth; both partners use their own Claude accounts referencing this repo
- **Revenue model:** Mixed — grants + school licensing + paid courses (no advertising)
- **Primary audience:** Parents/whānau (not young people directly)
- **Primary NZ referral partner:** Yellow Brick Road (0800 732 825)

---

## Key Decisions Pending

- Working name / brand
- Clinical advisor (critical — recruit early)
- Technology stack for the site
- Legal/entity structure
- Whether to use AI on the site itself (strong interest — see todo list)

---

## How to Use This File

**At the start of every Claude session:**
> "I'm working on a project — here is the steering file: [paste STEERING.md]. I also want to share today's working file: [paste relevant doc from /docs or /todo]."

**At the end of every session:**
- Paste any updates back into the relevant file and commit to the repo
- If a key decision was made, add it to `admin/decisions-log.md`
- Update the `Last updated` date at the top of this file if you changed anything here

---

## Critical Constraints (Non-Negotiable)

1. **Clinical credibility** — attach a clinical advisor before publishing anything
2. **Safeguarding** — define crisis response protocol before launch
3. **Contagion-safe content** — all content must follow evidence-based safe messaging guidelines
4. **No advertising** — trust is the product; ads undermine it
