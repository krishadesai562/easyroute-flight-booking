# ✈️ EasyRoute — Flight Booking Interface

> A flight-booking interface designed for clarity and trust. Built from 46 user surveys and competitor analysis of three major airlines, with two iterative design cycles in Figma. **COSC 3P94: Introduction to Human-Computer Interaction** at Brock University (Winter 2026).

![Course](https://img.shields.io/badge/course-COSC%203P94-blue)
![Type](https://img.shields.io/badge/type-UX%20Research%20%26%20Design-purple)
![Tool](https://img.shields.io/badge/Figma-prototype-F24E1E?logo=figma&logoColor=white)
![Surveys](https://img.shields.io/badge/surveys-46%20respondents-success)
![Status](https://img.shields.io/badge/status-final-brightgreen)

---

## 🎨 Try the Live Prototype

<p align="center">
  <a href="https://www.figma.com/proto/RL6LSJnW9JMXOp9ZpHH21D/3P94---Airlines-Website?node-id=95-23&t=ugWmAqWVDBS0r7I9-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1">
    <img src="https://img.shields.io/badge/▶_Launch_Interactive_Prototype-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Launch Prototype" />
  </a>
  &nbsp;&nbsp;
  <a href="https://www.figma.com/design/RL6LSJnW9JMXOp9ZpHH21D/3P94---Airlines-Website?node-id=0-1&t=iatJvjcPiDqNGDvK-1">
    <img src="https://img.shields.io/badge/🎨_View_Figma_Design_File-2F2F2F?style=for-the-badge&logo=figma&logoColor=white" alt="Figma Design File" />
  </a>
</p>

Click through a full booking — from homepage search to seat map to payment confirmation. The prototype is fully interactive in Figma.

---

## 📖 Overview

EasyRoute is a redesigned flight-booking experience that prioritizes **clarity, transparency, and reduced cognitive load** over the upselling-heavy patterns used by most airlines today. Our team of five designed it across two iterative cycles, grounded in real user research:

- 🔬 **46-respondent user survey** capturing booking habits, frustrations, and goals
- 🏢 **Competitor analysis** of Air Canada, Saudia Airlines, and Emirates
- 👥 **Two personas** built from survey patterns, with primary and secondary user goals
- 📐 **HTA (Hierarchical Task Analysis)** of the booking flow for each competitor
- ✏️ **Storyboards** for the homepage and results page
- 🎨 **High-fidelity Figma prototype** with a complete clickable booking flow

---

## 🎯 The Problem We Solved

Most airline booking sites force users to wade through fare tiers, upsell banners, hidden baggage fees, and confusing refund policies. Our research showed that **price-sensitive independent travelers** abandon bookings when overwhelmed, and **family planners** struggle with multi-passenger coordination on form-heavy interfaces.

EasyRoute's design philosophy:

| ❌ Common patterns | ✅ Our approach |
|---|---|
| Dense fare grids with 6+ tiers | Progressive disclosure — see basics first, details on demand |
| Persistent upsell banners | Minimal promotional content — focus stays on the task |
| Hidden total cost until checkout | Persistent price summary panel throughout flow |
| Generic seat maps | Real airplane layout with clear legend |
| Confusing back navigation | Always-visible progress bar with clickable steps |

---

## 👥 Our Users

### 🎓 Primary: Aisha Patel — the Budget-Conscious Student

> *"I just want to see the final price without digging through fare tiers."*

- **22, business student, books independently**
- **Goals:** Save money, book quickly under time pressure, understand total cost upfront
- **Frustrations:** Hidden fees, aggressive upselling, too many fare tiers, confusing refunds

**Why she's primary:** She's the most sensitive to complexity and price confusion. Design for Aisha and the interface stays simple for everyone else.

### 👨‍👩‍👧‍👦 Secondary: Michael Thompson — the Organized Family Planner

> *"I don't mind paying a bit more — I just need to sit with my kids and know what's included."*

- **39, marketing manager, books for family of 4**
- **Goals:** Coordinate seats, clear baggage rules, stress-free pre-planning, full booking review
- **Frustrations:** Re-entering passenger details, complex seat maps, hard-to-find support

**Why he's secondary:** His needs are supported through progressive disclosure — multi-passenger forms and seat coordination — without overwhelming Aisha's simpler flow.

---

## 🛫 The Booking Flow

```
   ┌─────────┐   ┌──────────────┐   ┌──────────────┐   ┌────────┐   ┌────────┐   ┌─────────┐
   │  1.     │   │  2.          │   │  3.          │   │  4.    │   │  5.    │   │  6.     │
   │ Search  │ → │ Select       │ → │ Passenger    │ → │ Seats  │ → │ Extras │ → │ Payment │
   │         │   │ Flight       │   │ Info         │   │        │   │        │   │         │
   └─────────┘   └──────────────┘   └──────────────┘   └────────┘   └────────┘   └─────────┘
   trip type     compare by         grouped fields,   real layout  baggage,    review +
   route, dates  price, duration,   inline            with skip    meals,      confirmation
   passengers    stops              validation        option       assistance  screen
```

**What makes our flow different:**
- The progress bar is always visible — users never feel trapped in a funnel
- The price summary panel stays on the right throughout the flow
- Optional steps (seats, extras) can be skipped without losing context
- Every step is **clickable from the progress bar** — easy back-navigation

---

## 🔄 Two Design Iterations

### Stage 2 — Initial Prototype

Our first Figma prototype focused on six design principles:

1. **Combined search + find-booking** on the homepage — our key innovation
2. **Visible progress indicator** at every step
3. **Persistent price summary** for transparency
4. **Progressive disclosure** for fare details and optional services
5. **Real airplane seat layout** with a legend for availability and seat type
6. **Minimal promotional content** to lower cognitive load

### Stage 3 — Peer Feedback

Other student teams reviewed our prototype and surfaced four themes:

| Feedback theme | What they said |
|---|---|
| **Visual design** | Interface felt grey and text-heavy; low contrast |
| **Navigation** | No back button; progress-bar steps weren't clickable |
| **Missing features** | No booking confirmation screen, no loyalty preview, limited help |
| **Responsiveness** | Layout didn't adapt to smaller screens |

### Stage 4 — Final Product

We addressed every theme:

| Feedback | What we changed |
|---|---|
| Flat colors, weak hierarchy | New palette with stronger contrast and clearer typographic hierarchy |
| No back button | Persistent back button + every progress step now clickable |
| No confirmation screen | Dedicated confirmation page with booking reference and itinerary |
| Trip-type toggle didn't update form | Return-date field hides dynamically for one-way trips |
| Broke on small screens | Rebuilt with responsive breakpoints for mobile and tablet |
| Missing help and loyalty | Help Centre link in footer + simple rewards preview on homepage |

---

## 📊 Research Snapshot

| Metric | Value |
|---|---|
| **Survey respondents** | 46 |
| **Airlines analyzed** | 3 (Air Canada, Saudia, Emirates) |
| **Personas developed** | 2 (primary + secondary) |
| **Iteration cycles** | 2 (Stage 2 → Stage 4) |
| **Final user-flow stages** | 6 |
| **Top reason for flying (from survey)** | Leisure/Vacation (49%) |
| **Booking preference (from survey)** | Slight majority use third-party sites — opportunity for airlines to win back |

---

## 📁 Repository Contents

```
easyroute-flight-booking/
├── Airline Website Stage 1 Report.pdf      # Full user research + competitor analysis
├── Group6_Stage4_Presentation.pptx         # Final presentation deck
├── figma and credits link.docx             # Links to live Figma prototype
└── README.md                               # You are here
```

The actual high-fidelity design lives in Figma — see the prototype link at the top.

---

## 👥 Team & My Contribution

**Group 6** — COSC 3P94 (Winter 2026)
Instructor: Aws Al Jumaily

| Team member |
|---|
| **Krisha Desai** |
| Dimple Mistry |
| Brian Eyong Enoh |
| Sarisha Kadakia |
| Tanisha Bhayani |

### My Role

- 🎨 **Co-designed the Stage 2 Figma prototype**, focusing on the booking flow architecture and visual hierarchy
- 👥 **Contributed to persona development** — built out Aisha and Michael from survey data and competitor critiques
- 🔄 **Helped lead the Stage 4 iteration** based on peer feedback, particularly around responsiveness and the confirmation screen
- 📊 **Participated in the 46-respondent survey design** and data analysis
- 📝 **Co-authored the Stage 1 research report** including competitor analysis and user-goal synthesis

---

## 🎓 What I Learned

This project pulled me deep into **design thinking** — not just making screens that look good, but designing decisions that make users *feel* something. The biggest takeaways:

- **Research before pixels.** The 46-survey + competitor analysis radically changed what we built. Without that grounding, we would've designed for ourselves, not for Aisha and Michael.
- **Personas aren't decoration.** Every time we got stuck on a design decision, going back to "what would Aisha do here?" gave us a clear answer.
- **Peer feedback is gold.** Half the things we missed in Stage 2 were obvious to fresh eyes. The Stage 4 product is meaningfully better because we listened.
- **Progressive disclosure beats minimalism.** You don't have to hide complexity; you just have to reveal it only when the user wants it.
- **Collaboration on Figma is its own skill.** Five designers working on one file taught me a lot about component reuse, naming, and version hygiene.

This was also the project where I realized I genuinely enjoy **design + project coordination** as much as I enjoy writing code.

---

## 👤 About

I'm Krisha Desai, a Computer Science student at Brock University focused on application development, design, and project management.

🔗 [LinkedIn](https://www.linkedin.com/in/krisha-desai-850015194) · 📧 krishudesai562@gmail.com · 💻 [GitHub](https://github.com/krishadesai562)