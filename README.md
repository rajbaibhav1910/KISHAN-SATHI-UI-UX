# Kisan Saathi (किसान साथी) 🌾
> **Empowering Farmers with Smart, Weather-Driven Agricultural Advisory & Decision Intelligence**

[![Figma Design](https://img.shields.io/badge/Design-Figma_Prototype-F24E1E?style=for-the-badge&logo=figma)](https://figma.com)
[![Domain-Agriculture](https://img.shields.io/badge/Domain-Agriculture-emerald?style=for-the-badge)](https://github.com/rajbaibhav1910)
[![Author-rajbaibhav1910](https://img.shields.io/badge/Profile-rajbaibhav1910-blue?style=for-the-badge&logo=github)](https://github.com/rajbaibhav1910)

**Kisan Saathi** is an end-to-end Human-Centered Design (HCD) solution crafted to bridge the volatile gap between unpredictable meteorological shifts and daily, hyper-local farming operations. By translating sterile, raw weather telemetry into highly contextualized, execution-ready agricultural insights, the platform enables small-to-medium-scale farmers to actively mitigate risks, reduce resource wastage, optimize input investments, and log their operational journey.

---

## 📖 Project Context & The Challenge

This repository serves as the central hub for the design framework, product architecture, interface layouts, and interactive prototype assets developed for the mobile application. Created under the technical parameters of the **"Design Challenge: From Problem to Prototype"** brief, this project represents a disciplined translation of empirical agricultural friction points into an elegant, low-cognitive-load mobile experience.

### 🔴 The Core Friction Points
*   **Data vs. Actionability:** Standard consumer weather applications deliver numerical probabilities (e.g., *"Precipitation: 65%, Wind: 22 km/h"*). For a farmer, this data lacks absolute context. They are left guessing: *Should I apply pesticides today, or will it wash away? Is it safe to irrigate tonight?*
*   **Delayed Alerts:** Critical anomalies—such as sudden frost, hail, or localized flash downpours—often reach the user after preventive windows have already closed.
*   **Fragmented Logging:** Farmers rely heavily on mental logs or physical notebooks to track historical crop outcomes relative to seasonal shifts, losing valuable pattern data year-over-year.

### 🟢 The Value Proposition
**Kisan Saathi** acts as a proactive digital partner. The platform continuously maps real-time weather forecasts directly against the user’s specific crop type, growth stage, and soil characteristics, delivering four categorical command directives: **Irrigate, Harvest, Fertilize, or Protect.**

---

## 🎨 Information Architecture & Screen Mapping

The system architecture utilizes a strictly bounded **8-page blueprint**, intentionally engineered to keep app depth shallow, ensuring high discoverability and seamless navigation under harsh, high-glare outdoor working conditions.

### Core Architecture Blueprint

| Screen Index | Screen State | Strategic UX Focus & Key Functional Components |
| :---: | :--- | :--- |
| **01** | **Onboarding & Profiling** | **Frictionless Entry:** Multi-lingual preference initialization, geo-location mapping, and adaptive crop profiling (specifying crop species, soil profile, and planting epoch). |
| **02** | **Home Dashboard** | **The Pulse Screen:** High-visibility real-time weather summary, immediate actionable agricultural directive, and high-priority system status tiles. |
| **03** | **Decision Detail** | **Contextual Deep-Dive:** Micro-copy breaking down the *Why* and *How* behind a directive (e.g., *"Delay fertilizer application: Heavy downpour projected within 4 hours will cause nutrient runoff"*). |
| **04** | **Severe Alert Detail** | **Emergency UI (High-Contrast):** Activated during high-threat hazards (hail, frost). Features flashing visual safety elements and immediate step-by-step crop preservation measures. |
| **05** | **Alerts Feed** | **Chronological Urgency Log:** A unified panel segmenting warnings into *Critical*, *High Alert*, and *General Advisory* tiers to prevent notification fatigue. |
| **06** | **7-Day Ag-Forecast** | **Predictive Planning:** A non-standard extended forecast that correlates traditional metrics (temperature/rain) directly with field-work safety indexes. |
| **07** | **My Farm Management** | **Digital Twin Hub:** An administrative dashboard allowing users to track multiple distinct land plots, alter crop variables, and evaluate individual plot health states. |
| **08** | **Track Record Logbook** | **Historical Analytics:** A simplified digital ledger tracking what weather event occurred, what action the farmer took, and the ultimate outcome on yield quality. |

---

## 📱 Interface Preview

The interface utilizes high-contrast typography, large tap targets ($>48\text{dp}$), and unmistakable iconography to remain usable even when the farmer's device screen is under direct sunlight.

<table align="center">
  <tr>
    <td align="center"><b>1. Onboarding & Setup</b><br><img src="Screenshot 2026-07-18 152637.png" width="200" alt="Onboarding"/></td>
    <td align="center"><b>2. Home Dashboard</b><br><img src="Screenshot 2026-07-18 152637.png" width="200" alt="Home Dashboard"/></td>
    <td align="center"><b>3. Decision Detail</b><br><img src="Screenshot 2026-07-18 152637.png" width="200" alt="Decision Detail"/></td>
    <td align="center"><b>4. Severe Alert Detail</b><br><img src="Screenshot 2026-07-18 152637.png" width="200" alt="Severe Alert"/></td>
  </tr>
  <tr>
    <td align="center"><b>5. Alerts Feed</b><br><img src="Screenshot 2026-07-18 152637.png" width="200" alt="Alerts List"/></td>
    <td align="center"><b>6. 7-Day Ag-Forecast</b><br><img src="Screenshot 2026-07-18 152637.png" width="200" alt="7-Day Forecast"/></td>
    <td align="center"><b>7. My Farm Hub</b><br><img src="Screenshot 2026-07-18 152637.png" width="200" alt="My Farm"/></td>
    <td align="center"><b>8. Track Record Log</b><br><img src="Screenshot 2026-07-18 152637.png" width="200" alt="Track Record"/></td>
  </tr>
</table>

*(Note: Verify your filenames mirror the `Screenshot 2026-07-18 152637.png` format in the root folder).*

---

## 🚀 The Human-Centered Design Framework

The development of Kisan Saathi rigorously applied the standard 5-stage HCD pipeline:

```text
┌───────────┐     ┌───────────┐     ┌───────────┐     ┌───────────┐     ┌──────────────────┐
│ DISCOVER  │ ──> │  DEFINE   │ ──> │  IDEATE   │ ──> │  DESIGN   │ ──> │ PROTOTYPE & TEST │
└───────────┘     └───────────┘     └───────────┘     └───────────┘     └──────────────────┘
 User Research     Pain Points       User Flows        UI Layouts        Interactive Link
 & Context Gathering Framed Targets   & Logic Trees     & UI Kits         & Validation
