# Feature Brief: Our Stories

Last updated: May 2026  
Status: Concept — ready for discussion  
Authors: Mike + Claude  
Purpose: Define the Our Stories feature for design, development, and clinical review

---

## The Idea in One Paragraph

A section of the site where NZ families affected by youth self-harm can share their experience. Rather than asking parents to write something from scratch — which is a significant barrier for people who are exhausted and often still in the middle of it — Claude listens to what they want to say, asks gentle questions, reflects it back, and helps them shape it into a story. The story lives on the site, anonymised, for other families to read. The parent feels heard. Other parents feel less alone. And over time, the collection of stories becomes one of the most powerful things on the site.

---

## Why This Matters

### For the parent sharing
Being heard is itself meaningful. For many parents, this may be the first time they have told their story to anyone — shame and isolation prevent most from talking openly. Having something listen without judgment, ask questions that show it understood, and reflect the experience back coherently has genuine value. This is not therapy. It is closer to oral history — being witnessed.

### For parents reading
"You are not alone" stops being a tagline and becomes a living, growing body of evidence. Real stories from real NZ families, in their own words. That is more powerful than any statistic we can put on the site.

### For the project
- Builds the most emotionally resonant content on the site organically, without a content team writing it
- Demonstrates our founding principle in action — parents helping parents
- Creates a reason to return to the site and a reason to share it
- Generates aggregated data with real research and advocacy value (see below)

---

## How It Works — The User Journey

### 1. The invitation
A warm, low-pressure prompt on the site — not "submit your story" but something closer to:

> *"Every family's experience is different. If you'd like to share yours — so other parents know they're not alone — we'd love to hear it. There's no form to fill in. Just tell us what happened."*

### 2. The conversation
Claude opens a gentle, unhurried conversation. It:
- Listens to whatever the parent wants to share
- Asks simple, warm questions to draw out the story — "What was that like for you?" / "What do you wish you'd known?" / "What helped?"
- Reflects back what it's hearing to show it has understood
- Never pushes, never rushes, never redirects to clinical content
- Is explicit that this is not a support service — if the parent needs support right now, it offers 1737

This is not counselling. It is compassionate listening with a clear purpose — helping someone tell their story.

### 3. The shaping
When the parent feels they've said what they want to say, Claude offers:

> *"Would you like me to shape this into a short story we could share on the site? I'll use your words, tidy it up, and we can anonymise any names or details you want kept private."*

The parent can review, edit, approve or withdraw at any point.

### 4. Moderation
Before any story goes live, a human reviews it. This is non-negotiable. The moderation step checks:
- Safe messaging compliance — no method detail, no content that could be harmful to other readers
- Anonymisation is complete
- The parent's consent is clear and informed
- The story is appropriate for the site

### 5. Publication
The story goes live in the Our Stories section — attributed only as the parent chooses (e.g. "A mum from Auckland" or "Anonymous").

---

## The Participation Model — Things to Consider

The current design assumes a fully anonymous, single-session experience. That is the right default — lowest barrier, maximum accessibility. But there is a design tension worth resolving before build.

**The tension:** A fully anonymous process protects privacy and removes friction. A light relationship with the parent unlocks review, consent, follow-up, research value, and the possibility of deeper engagement over time. These are not mutually exclusive.

A progressive model may be the answer — the parent chooses how far in they want to go:

### Level 1 — Fully anonymous
Tell your story, Claude shapes it, human moderates it, it goes live. No account, no email, no follow-up. Maximum accessibility, minimum data. Right for parents who are not ready for anything more.

### Level 2 — Light touch
Email address only, offered at the end of the conversation — framed as "so we can send you the draft to review before anything goes live." The parent can edit, approve, or withdraw. An optional follow-up check-in a few days later. This feels like a reasonable ask and actually serves the parent. It also gives the project a consent trail and the beginning of a relationship.

### Level 3 — Research opt-in
Explicit, separate consent for anonymised themes from their story to contribute to aggregated research. This is the layer with value for grant applications, the clinical advisor partnership, and policy advocacy. Never assumed, never bundled with publication consent.

**The email address at Level 2 is the unlock.** It's not a significant ask in context — "leave your email so we can send you the draft" serves the parent directly. But it opens the door to the research layer, future community involvement, course participation, and peer support roles.

**The transition moment matters.** A parent who has just told a painful story may not be in the right headspace to immediately review a polished version of it. Consider building in a natural pause — "I've shaped this into something. Would you like me to send it to your email so you can read it when you're ready?" — rather than presenting it immediately in the same conversation.

### Questions for clinical review
- Is a follow-up check-in after story-sharing clinically advisable — or does it risk re-opening something the parent has processed and moved on from?
- What does genuinely informed consent look like for the research layer — what must it say, and what must it not assume?
- Should Level 1 (fully anonymous) always remain available, or are there clinical reasons to require at least a light touch relationship before publication?

---

## The Data Layer

Done carefully and ethically, the aggregated and anonymised themes from stories could tell us things no survey ever would:

- How parents first discovered their child was self-harming
- What their immediate fears were
- What the system did and didn't do for them
- What helped — and what made things worse
- What they wish they'd known

This is:
- **Publishable research** — in partnership with a clinical advisor like Professor Theresa Fleming
- **Evidence for grant applications** — lived experience data is gold for funders
- **Material for advocacy** — policy conversations about CAMHS, schools, GP training
- **Ongoing insight** for improving the site and its content

Consent for anonymised data use must be explicit and clearly separate from consent to publish the story.

---

## Guardrails — Non-Negotiable

This feature requires more careful design than any other part of the site. The following are non-negotiable:

### Claude's role is listener and story-shaper only
Claude does not:
- Assess risk
- Provide clinical advice or therapeutic intervention
- Interpret or diagnose
- Ask questions designed to elicit distress

Claude does:
- Listen warmly and without judgment
- Ask gentle, open questions to help the parent tell their story
- Reflect back what it has heard
- Help shape the story into something the parent is proud of

### Crisis handoff is always available
At any point in the conversation, if a parent expresses that they or their child are in crisis right now, Claude:
- Acknowledges what they've shared with warmth
- Does not continue the story conversation
- Offers 1737 (free call or text, 24/7) and Yellow Brick Road (0800 732 825)
- Does not attempt to manage the situation itself

### Safe messaging compliance
All published stories are reviewed against safe messaging guidelines before going live. No story is published that contains method detail, glorification, or content that could be harmful to vulnerable readers.

### Informed consent
The parent must explicitly consent to:
- Their story being published on the site (anonymised)
- Anonymised themes being used in aggregated research data
- These are separate consents — one does not imply the other

### Human moderation before publication
No story goes live without human review. This is not optional.

### No stories from young people
This feature is for parents and whānau only. If a young person attempts to use it, they are gently redirected to youth-appropriate support.

---

## Questions for Clinical Review

Before this feature is built, the following need clinical sign-off from Professor Theresa Fleming or equivalent:

1. Is the listening/story-shaping role clearly distinct enough from counselling to be safe?
2. What are the specific risk indicators Claude should watch for that trigger crisis handoff?
3. What safe messaging guidelines apply specifically to published personal narratives (vs general content)?
4. Should there be a follow-up touchpoint after someone shares — e.g. an email checking in?
5. What does informed consent look like in this context — legally and ethically?
6. Is a follow-up check-in after story-sharing clinically advisable — or does it risk re-opening something the parent has processed and moved on from?
7. Should Level 1 (fully anonymous) always remain available, or are there clinical reasons to require at least a light touch relationship before publication?

---

## Questions for Caroline

- Does this resonate with your experience — would you have wanted something like this?
- What would have made you feel safe enough to share?
- What would the prompt need to say to not feel like pressure?
- Any instinct on what the moderation process should look like practically?
- Does the progressive model (Level 1 / 2 / 3) feel right — or would the choice itself feel like pressure?

---

## Relationship to Other Site Features

| Feature | Relationship |
|---|---|
| AI guide/navigator | Separate function — the navigator helps parents find content; this helps parents tell their story |
| Crisis response protocol | Our Stories must plug into the same crisis handoff system |
| Content library | Published stories become content — the most human content on the site |
| Research and advocacy | Stories feed the data layer that supports grant applications and policy work |

---

## Next Steps

1. Share with Caroline for her input — especially the questions above
2. Include in clinical advisor brief for Professor Theresa Fleming
3. Define the crisis handoff protocol (required before any AI feature is built)
4. Prototype the Claude conversation flow — what does the opening prompt look like? What questions does it ask?
5. Define the moderation workflow — who reviews, what checklist do they use, what's the turnaround time?
6. Legal review — consent, data use, privacy
7. Decide on participation model (Level 1/2/3) — get clinical and legal input before build
