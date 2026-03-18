# LeadFlow — Full Project Context File
> This file contains everything needed to continue this project in a new conversation. Read it fully before responding.

---

## WHO THE CLIENT IS

- A **platform owner** who manages **68 HVAC service providers (SPs)**
- He is Taha's potential client — Taha is building and running this platform on his behalf
- The platform owner oversees the SP network — Taha charges the SPs directly on the owner's behalf
- The client spends significant money on operations and is looking for a modern lead gen + routing solution

---

## WHAT THE PLATFORM IS

**Name: LeadFlow**

A fully managed HVAC lead generation, routing, and re-engagement platform. It is not a dashboard product — it is a done-for-you service that Taha runs for the client's network of 68 HVAC service providers.

### Core Functions:
1. **Lead Generation** — Run ads (Google Search, Google LSA, Meta Feed) to drive HVAC customers to the platform
2. **Lead Routing** — Customer selects service type, enters location, gets matched to the nearest available SP automatically
3. **CRM Integration** — All 68 SPs share one CRM. Every routed lead is pushed into it instantly
4. **Revive Campaign** — Three-part re-engagement system (see below)
5. **Analytics & Reporting** — Network-wide performance reporting delivered to platform owner

---

## HOW THE ROUTING SYSTEM WORKS

1. Customer sees a Google or Meta ad
2. Customer lands on the LeadFlow platform
3. Customer selects service type (AC Repair, Furnace Repair, Full Installation, Maintenance Plan)
4. Customer enters their location (postal code or city)
5. LeadFlow calculates distance between customer and all 68 SPs
6. Nearest available SP is selected and lead is routed to them
7. If nearest SP is unavailable, next closest is automatically selected
8. Lead is instantly pushed into the shared CRM
9. SP receives lead inside CRM and follows up

---

## THE AD SYSTEM

Three ad channels:

| Channel | Type | Purpose |
|---|---|---|
| Google Search Ads | Bottom-of-funnel | High-intent customers searching "HVAC repair near me" right now |
| Google Local Services Ads (LSA) | Bottom-of-funnel | Google-verified Pro badge, appears above regular results, pay-per-lead |
| Meta Feed Ads | Top-of-funnel | Awareness stage, targets homeowners by location/demographic on FB/IG |

**Funnel:** Awareness (Meta) → Interest → Intent (Google Search) → Conversion (Google LSA) → Lead Routed to SP

---

## THE REVIVE CAMPAIGN

Three-part automated re-engagement system:

1. **Cold Lead Re-engagement** — Leads that came in but never converted are flagged after X days and re-entered into a follow-up sequence via CRM
2. **Past Customer Follow-Up** — Previous customers are automatically contacted for repeat business (annual maintenance reminders, seasonal checkups)
3. **Seasonal Promotions** — SP network's customer base receives automated outreach tied to HVAC seasons ("Get your AC checked before summer", "Furnace tune-up before winter")

Visual concept: Circular lifecycle — **Lead → Convert → Retain → Revive → Lead**

---

## THE TWO PRICING/PARTNERSHIP MODELS

> **Important: Never mention specific prices in the proposal site. Only explain how each model works.**

### Option A — Fully Managed (Taha covers ad spend)
- Taha runs everything: ads, routing, CRM, revive campaigns
- Ad spend is handled end-to-end on client's behalf
- SPs just receive leads and close jobs — zero ad management needed
- Monthly performance report delivered to platform owner

### Option B — Platform + Strategy (Client covers ad spend)
- Taha builds and manages the routing platform, CRM integration, and revive campaigns
- Client/SP network funds the ad spend directly
- Taha handles all campaign strategy, optimization, and reporting
- Full budget control stays with the client

---

## PRICING CONTEXT (For Taha's Reference — Do NOT Include in Proposal Site)

| Item | Amount |
|---|---|
| Platform fee per SP | $75/month (Fully Managed) / $15/month (Platform + Strategy) |
| Per lead fee | $20/converted lead |
| Premium placement upsell | +$150/month per SP |
| Ad management fee | 15–20% of ad spend |
| Taha's hard costs (total platform) | ~$20–$29/month |

### Ad Spend Per SP (If Taha Covers It):
| Platform | Monthly |
|---|---|
| Google Search Ads | $800–$1,200 |
| Meta Feed Ads | $300–$500 |
| **Total per SP** | **$1,100–$1,700/month** |
| **Total per SP annually** | **$13,200–$20,400** |

### Taha's Infrastructure Costs:
| Item | Monthly | Annual |
|---|---|---|
| Vercel Hosting | $0 | $0 |
| MongoDB Atlas | $0–$9 | $0–$108 |
| Domain (Namecheap) | ~$1.25 | $10–$15 |
| Claude Pro | $20 | $240 |
| **Total** | **$20–$29** | **$250–$363** |

---

## WHAT THE SP DASHBOARD INCLUDES

- Analytics & reports only (network-wide, not per SP login)
- Lead volume by SP, region, service type
- Campaign performance (impressions, clicks, CPL, conversion rate) by channel
- Revive campaign open rates and re-conversion metrics

---

## THE PROPOSAL SITE

### What It Is:
A single-page **sales proposal website** — not a product dashboard. It is designed to convince the platform owner to say yes. It should feel like a premium agency proposal.

### Design Direction:
- **Colors:** White background, emerald green (#059669) accent, dark charcoal (#111827) text
- **Fonts:** Playfair Display (headings) + DM Sans (body) via Google Fonts
- **Style:** Light, airy, generous whitespace, subtle card shadows, thin emerald dividers
- **Logo:** Clean "LeadFlow" wordmark — emerald, modern, minimal, no icon
- **Animations:** Scroll-triggered fade-ins via Intersection Observer API
- **Responsive:** Yes, mobile-friendly

### Tone:
- Second person — "your network", "your 68 providers", "your leads"
- Speak to platform owner as a business operator
- Frame everything as outcomes and value, not features
- No jargon

### Sections (in order):
1. **Hero** — Headline, subheadline, CTA scrolling down
2. **The Problem** — 3 pain point cards (no routing system, leads go cold, no visibility)
3. **What We're Building** — Animated full system flow diagram (ad → platform → routing → CRM → revive)
4. **The Ad System** — 3 channel cards + awareness-to-conversion funnel diagram
5. **The Routing System** — SVG decision tree / flow diagram
6. **The Revive Campaign** — Circular lifecycle SVG diagram + 3 explanations
7. **Two Partnership Models** — Side-by-side cards, no pricing
8. **What You Get** — Emerald checklist summary
9. **Next Steps** — Closing CTA, "Book a Call" + "Ask a Question" buttons
10. **Footer** — LeadFlow wordmark + tagline

### Technical Requirements:
- Single HTML file, all CSS and JS embedded
- Google Fonts via CDN
- All diagrams built in inline SVG
- Intersection Observer for scroll animations
- Smooth scroll
- No Chart.js (this is a proposal, not a dashboard)
- Mobile responsive

---

## TECH STACK (For Building the Actual Platform)

- **Frontend:** Next.js (React)
- **Hosting:** Vercel (free tier)
- **Database:** MongoDB Atlas (free tier to start)
- **CRM:** Shared across all 68 SPs (specific CRM TBD)
- **Ads:** Google Search, Google LSA, Meta Feed

---

## WHAT HAS BEEN COMPLETED SO FAR

- [x] Business model defined
- [x] Pricing structure discussed
- [x] Full cost breakdown created (saved as `hvac_platform_cost_breakdown.html`)
- [x] Platform named: **LeadFlow**
- [x] Proposal site prompt written (corrected version — sales proposal framing)
- [ ] Proposal site not yet built
- [ ] Actual platform not yet built
- [ ] Client not yet signed

---

## IMMEDIATE NEXT STEP

Build the proposal site using the prompt in the section above. It should be a single HTML file, beautiful, light + emerald design, with all SVG diagrams and scroll animations. Once the client approves the proposal, begin building the actual Next.js platform.
