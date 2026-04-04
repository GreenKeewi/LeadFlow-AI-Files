---
title: Hotkey / LeadFlow — Customer Website Agent Context
tags:
  - leadflow
  - hotkey
  - website
  - agent-context
---

# Website Agent Context: Hotkey × LeadFlow Customer Site

> **Purpose:** This file gives a coding agent everything it needs to build a public-facing marketing website for Hotkey's LeadFlow service. The audience is HVAC business owners who are potential clients. Read this fully before writing a single line of code.

---

## 1. WHO THIS WEBSITE IS FOR

**Target audience:** HVAC business owners and operators — people who run heating, cooling, and ventilation companies. They are not technical. They care about booked jobs, cash flow, and growing their business without adding headcount.

**Their current reality:**
- Most rely entirely on word-of-mouth referrals, which are unpredictable and seasonal
- They've either never run ads, or tried ads and got burned (someone set it up and walked away)
- They have a list of old customers they've never followed up with — a goldmine sitting untouched
- When it's slow season, revenue dries up and they have no system to fix it
- They can't afford — or don't want to manage — a full marketing team

**What they want to hear:**
- More booked jobs, consistently
- A system that runs without them having to manage it
- Proof that it works and pays for itself
- No long-term lock-in risk

---

## 2. WHO HOTKEY IS

**Hotkey** is a done-for-you digital marketing and lead generation agency that specializes in local service businesses, with a core focus on HVAC. The flagship product is **LeadFlow**.

Hotkey handles everything: the ads, the lead routing, the follow-up campaigns, and the reporting. The client just receives leads and closes jobs.

**Positioning:** Not a generic marketing agency. Not a software tool. A full-stack revenue system built specifically for HVAC operators — delivered and managed end-to-end by Hotkey.

---

## 3. WHAT LEADFLOW IS

**LeadFlow** is Hotkey's managed HVAC lead generation, routing, and re-engagement system. It is a *service*, not a software product — clients don't log in and manage it themselves.

### What's included:

#### Paid Ads (Google + Meta)
- Google Search Ads: capture homeowners actively searching "HVAC repair near me" right now
- Google Local Services Ads (LSA): Google-verified Pro badge, appears above regular results, pay per lead
- Meta Feed Ads (Facebook/Instagram): awareness-stage targeting by location and homeowner demographics
- All campaigns are actively managed week-to-week — not set-and-forget
- Ad creative is built and refreshed every month (seasonal, offer-based, testimonial formats)

#### Lead Routing
- When a homeowner responds to an ad, they are matched to the nearest available HVAC provider automatically
- No manual dispatching needed
- If the primary provider is unavailable, the system falls back to the next closest one instantly
- Every lead is pushed into a shared CRM in real time

#### Revive Campaigns (The "Goldmine" Feature)
Three automated re-engagement flows that generate revenue from existing relationships:

1. **Cold Lead Re-engagement** — Leads that came in but never converted are followed up automatically after a set number of days via SMS and email
2. **Past Customer Follow-Up** — Previous customers are contacted automatically for repeat business: annual maintenance reminders, seasonal checkups
3. **Seasonal Promotions** — The full customer base receives automated outreach timed to HVAC seasons (e.g., "Get your AC checked before summer hits", "Furnace tune-up before first frost")

One reactivation campaign can book 10–20 jobs from people who already trust the business — with zero ad spend.

#### Reputation Management
- After every completed job, automated review request prompts are sent to the customer
- More Google reviews = lower ad costs, more organic calls, stronger social proof

#### Monthly Reporting
- Concise monthly report delivered to the client: leads generated, conversion rate, campaign performance by channel, re-engagement results

---

## 4. THE PERFORMANCE MODEL (HOW PRICING WORKS — HIGH LEVEL)

> **Do NOT mention specific dollar amounts on the site.** Explain the model structure only.

The pricing model is designed so Hotkey only wins when the client wins:

- There is a **monthly management fee** that covers all ad management, platform operation, and reporting
- On top of that, there is a **per-converted-lead fee** — paid only when a lead results in a booked job
- Clients do **not** pay per click or per form fill — only per job that made them money
- No long-term contract to start — clients can test for a month and decide

**Comparison frame to include:** Agencies like WebFX charge $1,000–$12,000+/month in retainers alone, plus 10–20% of ad spend on top. Hotkey's model is designed to be accessible while being tied directly to results.

---

## 5. THE FULL CUSTOMER JOURNEY (How It Works)

Explain this as a simple step-by-step flow on the site:

1. **A homeowner sees your ad** — on Google or Facebook/Instagram, targeted to your service area
2. **They click and submit their info** — a clean landing page captures name, service needed, and location
3. **LeadFlow routes the lead to you** — instantly matched based on your location and availability, pushed directly into your CRM
4. **You receive the lead and close the job** — no chasing, no manual dispatching
5. **Old leads and past customers get re-engaged automatically** — the Revive system keeps generating callbacks without any extra ad spend
6. **You get a monthly report** — showing exactly what's working and what it's generating

---

## 6. SERVICES SUMMARY (For a "What We Do" Section)

List these as the core service pillars:

1. **Fully Managed Paid Ads** — Google Search, Google LSA, Meta Feed. We handle targeting, creative, bidding, and optimization. You focus on the jobs.
2. **Intelligent Lead Routing** — Every lead is matched to the right provider automatically. No lost leads, no manual work.
3. **Revive Campaigns** — Automated re-engagement for cold leads, past customers, and seasonal windows. Jobs from people who already know you.
4. **Reputation Management** — Automated review requests after every job. More reviews, lower ad costs, more calls.
5. **Monthly Performance Reports** — Clear, concise. No guessing about what's working.

---

## 7. OBJECTION HANDLING (Inform the Copy)

Use these to shape how the site addresses hesitation:

- **"We already get referrals"** → Referrals are unpredictable. LeadFlow adds a consistent layer that doesn't fluctuate with the seasons.
- **"We tried ads before and it didn't work"** → Most ad agencies set things up and walk away. LeadFlow is actively managed week-to-week.
- **"I don't have time for this"** → You don't need to. We handle everything — you just receive the leads and close the jobs.
- **"Is there a long-term contract?"** → No. Start with a month, see the results, then decide.

---

## 8. SOCIAL PROOF / TRUST SIGNALS

Include placeholders for:
- Client testimonials (slots to be filled with real quotes)
- "X jobs booked" or "X leads generated" stat blocks (placeholder until real numbers are available)
- Google review count badge (placeholder)
- Google Partner / Meta Partner badges (if applicable)

---

## 9. DESIGN SYSTEM

### Colors
| Token | Value |
|---|---|
| Primary emerald | `#059669` |
| Light emerald | `#10b981` |
| Pale emerald (background tint) | `#d1fae5` |
| Charcoal (primary text) | `#111827` |
| Soft gray (secondary text) | `#6b7280` |
| White (page background) | `#ffffff` |

### Typography
- **Headings:** Playfair Display (Google Fonts CDN)
- **Body / UI:** DM Sans (Google Fonts CDN)

### Style Direction
- Light, airy, generous whitespace
- Subtle card shadows (not heavy drop shadows)
- Thin emerald dividers between sections
- Clean "LeadFlow" and "Hotkey" wordmarks — no icons, modern, minimal
- Scroll-triggered fade-in animations via Intersection Observer API only
- Mobile responsive — must look excellent on phones

---

## 10. SITE STRUCTURE (Recommended Sections in Order)

1. **Nav** — Logo (Hotkey or LeadFlow wordmark), nav links, CTA button ("Book a Call" or "Get Started")

2. **Hero** — Bold headline targeting the HVAC owner's core pain. Subheadline positioning LeadFlow as the solution. Two CTAs: primary ("Book a Free Strategy Call") and secondary ("See How It Works")

3. **The Problem** — 3 pain point cards: (a) Leads dry up in slow season, (b) Old leads and customers go cold, (c) No visibility into what's actually working

4. **How It Works** — Step-by-step numbered flow (see Section 5 above) with a simple visual or SVG diagram

5. **Services** — 5 service cards (see Section 6 above), icon + title + 2-line description each

6. **The Revive Campaign** — Dedicated section for this feature. It's the most compelling differentiator. Show the lifecycle: Lead → Convert → Retain → Revive → Lead (circular flow diagram in SVG)

7. **Pricing Model** — Explain the structure without numbers: management fee + per-converted-job component. Emphasize: "You only pay for results." Include a comparison note about what traditional agencies charge.

8. **Why Hotkey** — Short trust-building section: specialized in HVAC, actively managed (not set-and-forget), performance-tied pricing, no long-term contracts

9. **Testimonials / Social Proof** — Placeholder cards for client quotes and stats

10. **CTA Section** — "Ready to stop relying on referrals?" with a strong button and a short reassurance line ("No contract. No guesswork. Just leads.")

11. **Footer** — Hotkey wordmark, LeadFlow tagline, contact link or email

---

## 11. TONE & COPY RULES

- **Second person throughout:** "your leads", "your customers", "your slow season"
- **Outcome-first language:** Don't describe features — describe what they produce for the business
- **No jargon:** Never say "AI", "automation", "CRM", "funnel", "LLM", or "algorithm" — say "booked jobs", "follow-up", "your customer list", "the system"
- **Direct and confident:** This is not a pitch deck — it's a sales page. Be assertive.
- **Conversational, not corporate:** Write like a smart person talking to a contractor, not a startup pitching investors

### Example headline directions:
- "Stop Relying on Referrals."
- "More HVAC Jobs. No Extra Work."
- "Your Leads Shouldn't Go Cold."
- "We Run Your Marketing. You Run Your Jobs."

---

## 12. TECHNICAL REQUIREMENTS

- **Single HTML file** with all CSS and JavaScript embedded (no build step required)
- Google Fonts loaded via CDN link in `<head>`
- All diagrams built as **inline SVGs** — no Chart.js, no external diagram libraries
- Scroll animations via **Intersection Observer API** only — no GSAP or heavy animation libraries
- Smooth scroll behavior
- Fully **mobile responsive** (CSS Grid or Flexbox layouts)
- No backend required — this is a static marketing page
- CTA buttons can link to a Calendly URL or mailto: (placeholder)

---

## 13. WHAT NOT TO DO

- Do not mention specific prices or dollar amounts anywhere on the site
- Do not use technical language (AI, automation, algorithms, APIs, CRM)
- Do not design for developers — design for HVAC business owners
- Do not make it look like a SaaS product dashboard — it's a service, not software
- Do not use Chart.js or any JavaScript charting library
- Do not add features beyond what's described here — no blog, no case study pages, no login
- Do not use stock photo carousels or heavy image backgrounds that slow load time

---

## 14. GOAL OF THE SITE

A homeowner who lands on this page should feel:
> "This is exactly what I've been missing. They get my industry, they handle everything, and I only pay when it works. I want to talk to them."

The site's one job is to get an HVAC owner to book a call.
