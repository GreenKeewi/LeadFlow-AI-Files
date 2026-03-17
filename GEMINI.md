# LeadFlow — Project Context & Instructions

## Project Overview
**LeadFlow** is a "done-for-you" HVAC lead generation, routing, and re-engagement platform. It is designed for a platform owner who manages a network of 68 HVAC Service Providers (SPs). The project transitions from a strategic sales proposal to a fully managed technical platform.

### Core Architecture
1.  **Lead Generation:** Automated ads via Google Search, Google LSA, and Meta Feed.
2.  **Lead Routing:** A geographic matching system that connects customers to the nearest available SP based on location and service type.
3.  **CRM Integration:** A centralized CRM shared across all 68 providers for instant lead delivery.
4.  **Revive Campaign:** A three-part re-engagement system for cold leads, past customers, and seasonal promotions.
5.  **Analytics:** Network-wide performance reporting for the platform owner.

---

## Directory Overview
This directory contains the strategic foundation, research, and initial deliverables for the LeadFlow project.

### Key Files
-   **`leadflow_context.md`**: The primary source of truth for project requirements, business logic, technical stack, and current status. **Read this first for any LeadFlow-specific task.**
-   **`leadflow-proposal.html`**: A high-end, single-page sales proposal website designed to pitch the platform to the owner. It uses a modern Emerald/Charcoal aesthetic with custom SVG diagrams.
-   **`Agency_Strategy.md`**: The high-level business blueprint for the AI Ad Agency model used to build LeadFlow.
-   **`Video_Transcript_Analysis.md`**: Deep-dive research into the "190K AI Services" model, providing the "why" and "mindset" behind the strategy.
-   **`video-transcript-[1-7].md`**: Raw transcripts of research materials and case studies.

---

## Technical Stack (Planned)
-   **Frontend:** Next.js (React)
-   **Styling:** Vanilla CSS (for the proposal) / Tailwind (likely for the platform)
-   **Database:** MongoDB Atlas
-   **Hosting:** Vercel
-   **CRM:** Shared (TBD)

---

## Development Conventions
- **Source Control:** Commit and push changes after every modification to any of the files in the repository.
- **Proposal Design:** Follow the "Light + Emerald" theme (#059669) with Playfair Display headings and DM Sans body text.
-   **Communication Tone:** Use the second person ("your network", "your leads") when drafting content for the platform owner. Frame features as business outcomes.
-   **Diagrams:** Use inline SVGs for all technical and flow diagrams within the proposal and platform documentation.

---

## Usage
1.  **Proposing Changes:** Refer to `leadflow_context.md` to ensure any new feature or pricing discussion aligns with the defined "Option A/B" models.
2.  **Building the Platform:** Once the proposal is approved, use the logic defined in the "Routing System" and "Revive Campaign" sections of `leadflow_context.md` to build the Next.js application.
3.  **Content Creation:** Use the insights in `Video_Transcript_Analysis.md` to maintain the "contractor-friendly" rapport and focus on "Lead-to-Job" outcomes.
