# [Your Brand] — Strategy & Delivery Playbook

A working document. Read this once, then we keep refining as you sign your first 3–5 clients. The landing page lives next to this file.

---

## 1. The wedge, in one sentence

> A custom website you can change by talking to AI on your own laptop — and you own all of it, forever.

Every other "AI website" product (Wix AI, Framer AI, Lovable, Bolt, v0) traps the customer inside a proprietary platform. You're selling the *opposite*: a real codebase in a real GitHub repo, hosted on Vercel, on a domain in their name. The AI is a tool they install on their own computer. There is nothing for any platform to hold hostage.

This is the **only** message the landing page needs to drive home. Everything else is supporting evidence.

## 2. Who this is for (and who it isn't)

**Target persona — "Mara, the coach who's outgrown Squarespace":**
- Age 32–55. Solopreneur, coach, consultant, course creator, therapist, advisor.
- Already has paying clients. Likely $50k–$250k/yr in revenue. Has a real business.
- Currently on Squarespace, Wix, Showit, or a freelancer-built WordPress site they're afraid of.
- Embarrassed by how their site looks vs. how their work actually is.
- Has tried to redesign once or twice and gave up or got quoted $3k+.
- Tech comfort: comfortable with Notion, Instagram, Calendly, Stripe. Not with HTML.
- The thing they value above all else: **time + control.**

**Not for (yet):**
- Anyone who needs e-commerce with >10 SKUs (different beast, can do later)
- Anyone with a marketing team or in-house designer (different sale)
- B2B SaaS / startups (different buyer, different price)
- Local service businesses (plumbers, salons) — possible v2 audience but their buying motion is different (Google, reviews) and they're harder to reach. Solopreneurs/coaches buy from peers on social. Start there.

## 3. Pricing recommendation + rationale

**v1 pricing (use this for the first 10 clients):**

| Item | Price | Notes |
|------|-------|-------|
| Custom site + AI setup | **$2,497 one-time** | The whole offer. 10-day build. |
| Hands-free retainer | **$149/mo** | Optional. 6 edits/mo. Cancel anytime. First 2 months free. |
| Hourly rescue rate | **$120/hr** | For non-retainer clients who get stuck. |
| Domain | **Pass-through (~$15/yr)** | Paid to registrar directly. |
| Hosting | **Free in 90% of cases** | Vercel free tier. Pass-through if they outgrow it. |

### Why $2,497 specifically

- Above the psychological barrier where buyers expect "real" professional quality ($1,500+).
- Below the barrier where buyers need to justify it to a partner or pause to think ($3,000+).
- Lets you build it in ~15–20 hours of focused work → effective rate of $125–$165/hr, healthy for solo work.
- Sounds smarter than $2,500. Anchors with the 7. (Pricing-psych cliché but real.)

### What the retainer is for (be honest about this)

The retainer is **not** the core economic engine — the one-time fee is. The retainer exists to:
1. Catch the ~30% of clients who get scared of the AI handoff.
2. Generate a smooth secondary income that compounds.
3. Give you a reason to check in on clients quarterly (referral generation).

Don't expect every client to take it. Expect ~30% in month 1, ~15% stable after 6 months. That's fine.

### Pricing experiments to run after client 5

1. **Tier up:** Add a $4,497 "Premium" tier with custom illustrations, longer copy, multi-language, etc.
2. **Tier down:** A $997 "Quick start" with a smaller scope (3 pages, less design) — risky, can attract worse fits.
3. **Move retainer up:** Test $199/mo or $249/mo. Coaches and consultants are not price-sensitive on monthly retainers if the value is clear.

## 4. The 10-day delivery playbook

This is the actual operating procedure. Print it. Stick to it.

### Day 0 — Inquiry → discovery call

- They submit the form / email you.
- You send a Calendly link within 4 business hours.
- 30-minute Zoom. Goals: confirm fit, confirm trust, confirm scope.
- End with: "Here's the proposal. Pay 50% to lock the build slot, 50% on launch."

### Day 1 — Kickoff

- Receive 50% deposit.
- Send intake form (see §6).
- Schedule the screenshare for Day 8.
- Tell them: "You'll see the design on Day 4."

### Days 2–4 — Design

- Build the mockup. Either in Figma or directly as a real, clickable HTML prototype (faster — recommended).
- Send a Loom video walking through it. Loom + written notes always converts better than just a link.
- One round of revisions included. Anything beyond → "we'll handle it post-launch via your AI editor."

### Days 5–7 — Build

- Use Claude Code on your end to build the production site.
- Set up the repo under **their** GitHub account from day one (they can invite you as collaborator).
- Stage it on a Vercel preview URL so you can show progress mid-week.

### Day 8 — Setup screenshare (the magic moment)

This is the single most important hour of the whole engagement. Practice it.

Order of operations:
1. They share screen. You guide.
2. Install Claude Code (or Codex) on their machine. **You verify it works.**
3. Clone the repo locally.
4. Walk them through the project structure (very briefly — they don't need to understand it).
5. Open Claude Code in the project folder.
6. Make one tiny edit together ("change this word"). Watch it deploy. Cheer.
7. Connect the custom domain in Vercel (transfer to their account if it isn't already).

If anything breaks, **do not improvise on the call.** Reschedule and fix it offline. The setup call has to feel like magic, not a debugging session.

### Day 9 — Training session

A 60-minute screenshare focused on three real edits *they* care about. Don't pick fake examples. Ask them on Day 8: "What are the three things you'd most likely want to change next month?" — and use those.

End with a 1-page PDF of "How to talk to your site" cheatsheet (good and bad prompt examples). Optional but high-leverage.

### Day 10 — Launch

- Final 50% invoice clears.
- Site goes live on the real domain.
- You send a launch email template they can forward to their list.
- 30-day support window starts.

### Day 30 — Check-in

- Email: "How's it going? Any edits you've been afraid to try?"
- This is when ~50% of retainer signups actually happen — not at launch.
- Ask for the testimonial here, not at launch. They've now had time to use it.

### Day 90 — Quarterly check (retainer clients only)

- 15-minute Loom: site performance review, SEO check, 1–2 suggestions.
- This is the relationship muscle that drives referrals.

## 5. Scope guardrails (what's in and what isn't)

**In:**
- Up to 6 pages (Home, About, Services, Contact, +2 of their choice)
- Contact form (Formspree or similar, free tier)
- Embedded Calendly / Stripe payment links
- A blog scaffold (they can add posts via AI)
- Basic SEO (meta tags, OG images, sitemap)
- Mobile-responsive (non-negotiable)

**Not in (charge separately or push to v2):**
- E-commerce with inventory / cart logic
- User accounts / auth
- Custom backend / database
- Email automation / CRM integration
- Multi-language sites
- Animations beyond what a tasteful theme provides

**Politely declined:**
- "Can you copy this site I saw?" → No. (Legal + creative reasons.)
- "Can we ship in 3 days?" → Possible at +50% rush fee.
- "I want to keep editing during the build" → No, scope creep killer. We design first.

## 6. Intake questionnaire (use as-is)

Send this after deposit. 10–15 minutes for them to fill out.

```
About you & your work
1. In one sentence, what do you do?
2. Who's your ideal client? (Be specific — "women founders 30–45 in their first year" beats "entrepreneurs.")
3. What do you want someone to feel in the first 3 seconds on your homepage?
4. What's the single most important action you want a visitor to take?
   (book a call, sign up for newsletter, buy a product, etc.)

About your current site
5. URL of your current site (if any):
6. What works about it? What's broken?
7. Show us 2–3 sites you love. What do you love about each?
8. Anything to avoid? (colors, fonts, vibes you hate)

About content
9. Send your logo (or tell us you don't have one — we'll handle it).
10. Send any brand colors or fonts you already use.
11. Photos: send what you have. Up to 20 images.
12. Copy: send what you have. We'll write what's missing.

About scope
13. List every page you want.
14. Anything you need to embed? (Calendly, Stripe, ConvertKit, etc.)
15. Domain: do you already own one? If yes, where is it registered?

About launch
16. When do you want this live? Hard deadlines?
17. Anyone else needs to weigh in? (partner, business coach, etc.)
```

## 7. Risks & mitigations

| Risk | Likelihood | Mitigation |
|------|------------|------------|
| Client's machine can't run Claude Code (M1 Mac, Linux, weird Windows config) | Medium | Pre-check on the discovery call. Have a fallback: a hosted version (Cursor cloud, or you run a Codex sandbox they SSH into). |
| Client gets scared and stops editing | High (~30%) | This is exactly what the retainer is for. Pitch it warmly at Day 30. |
| Client breaks their own site with a bad prompt | Medium | (a) Git history = undo button. (b) Vercel auto-rolls back failed builds. (c) Teach them the phrase "undo your last change" in training. |
| Client wants you to be their AI tech support forever, for free | Medium | 30-day window is firm. After that, retainer or hourly rate. Be kind but clear. |
| AI tooling changes (Claude Code rebrands, new pricing, etc.) | Certain over 12 months | Stay flexible. Your moat isn't the tool — it's the setup + design + handoff. Tools will swap. |
| Client wants out / asks for a refund | Low if intake is good | Refund 50% of deposit if you haven't started design. After design starts: no refund, but the site is theirs to keep. Document this in the proposal. |
| Legal: what if their site infringes something? | Low | Add a "you're responsible for the content you give us" line to the proposal. Don't write controversial copy for them. |

## 8. Naming brainstorm seeds

You parked the name for now. When you're ready, here are starting directions. Pick a lane first — the right name depends on the angle.

**"Talk to your site" angle (verb-forward):**
- Sayso · Tellsite · Voicewright · Wordhouse · Aloud · Speakeasy (taken) · Convey

**"You own it" angle (sovereignty):**
- Hold · Mainstay · Keep · Tenure · Stake · Anchor · Homestead

**"Craft + AI" angle (warmth):**
- Quill · Loom · Studio Loop · Brio · Mantle · Atelier · Hearth · Indigo

**"Solopreneur energy" angle (modern + clean):**
- Self / Selfsite · Solo · Marka · Cadence · Plain · Mark · Letter · Page

**Process for narrowing:**
1. Shortlist 5 you don't hate.
2. Check .com availability. (.com only, no .ai/.io fluff for a solopreneur-facing brand.)
3. Say each one out loud 3 times. The one that doesn't make you wince — that's it.

## 9. First 10 customers: where they come from

Solopreneurs and coaches do not Google for "website builder." They buy from peers. Acquisition for v1:

1. **Your own network — first 3 clients (free / discount).** Family, ex-coworkers, friends-of-friends running coaching businesses. Offer them a $500 discount in exchange for a testimonial + permission to use their site in your portfolio. **You need 3 case studies before paid acquisition makes sense.**
2. **LinkedIn DM outreach to coaches.** Highly targeted. Write a 4-line message offering a free site audit. Convert audits to builds.
3. **Twitter / X build-in-public.** Post screenshots of every site you ship + Loom snippets of clients editing via Claude. This audience is unusually responsive to AI tooling stories.
4. **Niche Slack/Discord communities for coaches and consultants.** Be a member, not an advertiser. Answer questions. Drop your site in a profile.
5. **Referral loop from existing clients.** 20% of every new build's setup fee to the referrer. This is the long-term engine — design it now even if it takes 6 months to fire.

**Channels to avoid for v1:** Facebook ads, Google ads, SEO. All slow or expensive when you don't have social proof yet.

## 10. Open strategic questions to resolve before/during your first sale

These are the decisions I deferred to keep momentum. Each is small but real.

1. **Whose Vercel account hosts the site — yours or theirs?**
   - *Recommended: theirs.* Reinforces ownership. You get added as a collaborator for support. Bonus: their hosting bill is never your problem.
2. **What happens to their AI setup when you stop supporting them?**
   - Document a "self-serve handoff guide" they get on Day 10. Worst case, they can keep editing forever with no help from you.
3. **Are you offering refunds? Under what conditions?**
   - *Recommended:* 50% deposit refundable until design starts. After that, no cash refund — but they own the site and code regardless.
4. **Contract / proposal template — do you have one?**
   - Not yet. Use something like SignWell or Bonsai. I can draft the contract language for you next.
5. **Do you need an LLC / business entity?**
   - Probably yes before client #3 to keep liability clean. Boring but real.
6. **What does the demo look like on the landing page?**
   - The static chat mockup in the hero is good for v1. For v2, record a 60-second Loom of you making a real edit on a real site. Loom > static. Always.
7. **Naming + domain.**
   - Already covered above. Highest priority once you're sold on the offer.
8. **Will you let clients use Codex / Cursor / OpenAI Codex instead of Claude?**
   - *Recommended for v1: pick one.* Multi-tool support is a support nightmare. Lead with Claude Code. Offer the other only by request.

---

## What to do this week (concrete checklist)

If you do these 5 things by Sunday, you're ready to sell:

- [ ] Pick a working name + secure the .com (even if not final)
- [ ] Find/replace `[Your Brand]` and `yourbrand` in the landing page → real name
- [ ] Deploy the landing page to Vercel under your real domain
- [ ] Write down 10 people in your network who'd be plausible "free/discounted first 3 clients" and DM the top 3
- [ ] Set up a Calendly link for the discovery call and replace `hello@yourbrand.com` everywhere on the page

Then we revisit and refine based on what comes back. Onward.
