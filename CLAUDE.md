# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**LeadFlow** is a done-for-you HVAC lead generation, routing, and re-engagement platform built for a platform owner managing 68 HVAC service providers (SPs). The project is currently in the **pre-development / sales phase** — the proposal site (`leadflow-proposal.html`) is the primary deliverable.

**Always read `leadflow_context.md` first** before working on any LeadFlow task — it is the source of truth for business logic, system design, and current status.

## Current State

- `leadflow-proposal.html` — Single-page sales proposal website (complete, single HTML file with embedded CSS/JS)
- `leadflow_context.md` — Full project context: business logic, pricing, routing system, revive campaign, proposal spec
- `GEMINI.md` — Development conventions and usage rules
- `Agency_Strategy.md` — Business blueprint
- `Video_Transcript_Analysis.md` + `video-transcript-[1-7].md` — Research materials

No Next.js platform has been built yet. That work begins after client approval.

## The Proposal Site (`leadflow-proposal.html`)

A single HTML file with all CSS and JS embedded. Key constraints:
- All diagrams must be **inline SVGs** (no Chart.js, no external diagram libraries)
- Scroll animations via **Intersection Observer API** only
- Google Fonts loaded via CDN (Playfair Display + DM Sans)
- Must remain **mobile responsive**
- **Never mention specific prices** in proposal content

### Design System
| Token | Value |
|---|---|
| Primary emerald | `#059669` |
| Light emerald | `#10b981` |
| Pale emerald | `#d1fae5` |
| Charcoal | `#111827` |
| Soft gray | `#6b7280` |

Headings: Playfair Display · Body: DM Sans

## Content & Tone Rules

- Use **second person** throughout: "your network", "your 68 providers", "your leads"
- Frame everything as **outcomes and business value**, not features
- No technical jargon — audience is a business operator, not a developer
- Option A vs Option B models must be explained by *how they work*, never by price

## Git Workflow

**After every change to any file, commit and push immediately.** Do not batch changes across multiple files before committing — each save should be followed by a commit and push.

## Platform Architecture (Planned — Not Yet Built)

When building the Next.js platform after proposal approval:

- **Frontend:** Next.js (React) hosted on Vercel
- **Database:** MongoDB Atlas
- **Routing logic:** Geographic distance matching across 68 SPs; fallback to next-closest if unavailable
- **CRM:** Shared single CRM for all 68 SPs; every routed lead pushed instantly
- **Revive campaign:** 3-part automation — cold lead re-engagement, past customer follow-up, seasonal promotions
- **Ad channels:** Google Search, Google LSA, Meta Feed (full funnel from awareness to conversion)
