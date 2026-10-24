# 🚂 RAILGUARD AI
### *Calm Decisions When Every Minute Matters*
**The Intelligent Family Journey Rescue Engine for Indian Railways**

---

<div align="center">

![Indian Railways Animated Train](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&pause=1000&color=2563EB&center=true&vCenter=true&width=750&lines=Welcome+to+RailGuard+AI;Turning+Railway+Delays+into+Calm+Decisions;Live+NTES+Disruption+Detection+%2B+Smart+Re-routing;Automated+TDR+Refunds+%26+Offline+SMS+Mode;Built+for+24+Million+Daily+Indian+Railways+Passengers)

[![IMPACTX 2026](https://img.shields.io/badge/IMPACTX-2026_Hackathon_Project-FF9933?style=for-the-badge&logo=target&logoColor=white)](#)
[![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](#)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](#)
[![Vite](https://img.shields.io/badge/Vite_8-646CFF?style=for-the-badge&logo=vite&logoColor=white)](#)
[![Indian Railways](https://img.shields.io/badge/Indian_Railways-NTES_%7C_IRCTC_Compliant-000080?style=for-the-badge&logo=train&logoColor=white)](#)
[![WCAG AAA](https://img.shields.io/badge/Accessibility-WCAG_AAA-138808?style=for-the-badge&logo=w3c&logoColor=white)](#)



</div>

---

## 🌟 The Reality: 24 Million Passengers & 0 Seconds to Lose

Every single day, over **24 million passengers** travel across India's 7,300+ railway stations. But when an unexpected signal failure, freight backlog, or weather disruption delays a trunk line train like the **Kerala Superfast Express** by 90 minutes at **Nagpur Junction**:

* 🚨 **Connecting Trains Are Missed:** The family's onward connection (Telangana Express) departs without them.
* 😰 **Panic in the Dark:** Families traveling with elderly grandparents and heavy luggage are stranded at midnight on packed platforms.
* 💸 **Financial Uncertainty:** Passengers don't know IRCTC's strict **TDR (Ticket Deposit Receipt)** filing deadlines, forfeiting thousands of rupees in refunds.
* 📶 **Connectivity Blackouts:** Mobile network signals fade inside metal coaches and crowded junctions, rendering heavy apps useless.

> **RailGuard AI replaces platform panic with calm, intelligent clarity.** It continuously monitors your journey, predicts cascade connection failures hours in advance, ranks multi-modal rescue options, tracks every rupee of refunds, and works seamlessly even when the internet dies.

---

## 🚀 Key Innovations & Architectural Pillars

```mermaid
graph TD
    A[📡 Live NTES / IRCTC Disruption Feed] --> B{⚡ RailGuard AI Detection Engine}
    B -->|Buffer < 25 mins| C[🚨 High-Risk Missed Connection Trigger]
    C --> D[🧠 Feasibility Engine]
    C --> E[🛡️ Family Safety Engine]
    C --> F[💰 Financial Recovery Ledger]
    D & E & F --> G[🏆 Ranked Rescue Decision Matrix]
    G --> H1[Plan A: Same-Platform Vande Bharat]
    G --> H2[Plan B: Multi-Modal AC Express Bus]
    G --> H3[Plan C: Over-Night Retiring Room Rest]
    G --> I[📲 Offline Emergency SMS & GRP Dispatch]


1. Real-Time NTES Disruption & Buffer Engine
Live tracking of scheduled vs. expected arrival times at interchange junctions.
Dynamic Buffer Gauge: Computes safety margins between incoming train and onward connection.
Automated alert triggers the moment connection probability drops below safe threshold (≤ 25 mins).

2. 🧠 Intelligent Multi-Modal Route Ranking
Evaluates alternate train itineraries, special Rajdhani/Vande Bharat routes, and highway express buses.
Multi-dimensional ranking based on:
Family Safety Score (lighting, platform change distance, midnight wait times)
Total Journey Duration
Seat Availability & Confirmation Probability
Elderly / Wheelchair Accessibility

3. 💸 Financial Ledger & Automated TDR Claim Engine
Real-time calculation of ticket cancellation refunds under Indian Railway Passenger Tariff Rules.
Automatic qualification check: When a train is delayed >3 hours, 100% full refund is eligible without cancellation deduction.

Generates exact step-by-step TDR filing instructions with countdown timers to avoid deadline forfeiture.

4. 📶 Zero-Data Offline Mode & Emergency SMS
If data connection drops, RailGuard AI switches instantly to Zero-Bandwidth Mode.
Generates pre-formatted offline SMS payloads for Indian Railways SMS service (139) and emergency contacts.
Quick-dial integration for RPF (182 / 139), GRP helpline, and station medical booths.

5. 🎨 Cinematic Animated Railway Station Experience
Photorealistic Nagpur Junction Atmosphere: Handcrafted, high-fidelity SVG canvas featuring:
Moving billowy cumulus clouds drifting across dawn/dusk skies.
Ticking station master clock and glowing signals that switch from Amber to Red on delay.
True 3D Optical Parallax: Foreground Vande Bharat Express and background WAP-7 Kerala Express pass each other with physical optical occlusion and ambient depth shadows.
Interactive Disruption Simulator: Hackathon judges can slide the delay dial from +0m to +180m to watch the AI recalculate alternative routes in real time!
Station View Mode: One-click toggle in the header to hide cards and inspect the living railway environment.



🛠️ Tech Stack & Engineering Excellence

Domain	Technologies & Libraries
Frontend Framework	React 19 with TypeScript (Strict Type Safety)
Build & Tooling	Vite 8 (Lightning-fast HMR, sub-100ms builds)
Visual Art & Design	Pure Scalable Vector Graphics (SVG), Vanilla CSS Keyframe Animations
UI Design System	Tailored Indian Railways Indigo, Saffron (#F97316), Emerald (#10B981) & Light/Dark Theme Tokens
Icons & Typography	Lucide React, Google Fonts (Outfit, Inter, Manrope)
Accessibility	WCAG AAA Compliant, High-Contrast Mode, Screen-Reader Live Regions



📂 Repository Architecture
text
IRCTC/
├── public/                     # Static assets & web manifest
├── src/
│   ├── components/
│   │   ├── background/         # MidnightRailwayBg.tsx (Cinematic SVG station & dual train loops)
│   │   ├── loading/            # WebsiteLoadingScreen.tsx (3D perspective WAP-7 opening sequence)
│   │   ├── layout/             # Header.tsx (Station View, Intro Replay, Theme switcher)
│   │   ├── cards/              # DelayAlertCard, RouteComparisonCard, TdrRefundCard
│   │   ├── simulator/          # DisruptionSimulator.tsx (Interactive judge scrubber)
│   │   └── accessibility/      # ScreenReaderView.tsx, OfflineBanner.tsx
│   ├── engine/                 # Core domain logic
│   │   ├── feasibilityEngine.ts # Journey route scoring & timing feasibility
│   │   ├── safetyEngine.ts     # Family, female passenger & senior safety metrics
│   │   ├── rankingEngine.ts    # Pareto-optimal sorting across time, cost & safety
│   │   └── financialLedger.ts  # IRCTC TDR refund calculation matrix
│   ├── types/                  # TypeScript interfaces (Disruption, Train, Route, Ledger)
│   ├── App.tsx                 # Master state & route coordinator
│   ├── index.css               # Kinetic train keyframes & custom glassmorphism
│   └── main.tsx                # App entrypoint
├── package.json
└── vite.config.ts


⚡ Quick Start Guide
Prerequisites
Node.js (v18.0.0 or higher recommended)
npm or pnpm / yarn


Installation

# 1. Clone the repository
git clone https://github.com/<your-username>/railguard-ai.git

# 2. Navigate to project root
cd railguard-ai

# 3. Install dependencies
npm install

# 4. Start local development server
npm run dev

Visit http://localhost:5173/ in your browser.
or
Visit https://railguard-ai-navy.vercel.app


🎮 How to Test / Hackathon Demo Flow
Watch the Cinematic 3D Loading Sequence:
Witness the WAP-7 locomotive approach with glowing volumetric headlights and NTES telemetry status sync.
Click "Skip Intro" or "Board Train" to enter.
Explore Nagpur Junction Background:
Click the Station View (Eye Icon) in the header to admire the moving clouds, tracks, station board, and realistic train passing animations.
Simulate a Delay with the Disruption Simulator:
Switch the delay from +15m (Minor) to +90m (Severe).
Watch the platform signal turn red, the buffer gauge drop to 0m Missed Connection, and the rescue plans dynamically re-order.
Inspect Route Comparisons & TDR Claims:
Review Plan A (Vande Bharat), Plan B (Bus), and Plan C.
Check the Financial Ledger to see exact refund amounts and one-click filing guidance.
Test Zero-Data Emergency Mode:
Toggle the Offline Mode to see how RailGuard AI generates SMS codes for 139 without any active internet connection.



🏆 IMPACTX 2026 Hackathon Submission
Track: AI for Public Good & Resilient Infrastructure
Focus: Indian Railways Passenger Journey Continuity
Status: Working Prototype with Zero Mock API Failures
Made with ❤️ for the Indian Railways Passenger Community
RAILGUARD AI — Because your family's safety & peace of mind should never be delayed.


```
