<div align="center">

# 📊 Market Analysis & GTM Strategy: "Interactive Clothes"
### A Data-Driven Product Launch Case Study (CES 2026)

**Lin Xiaoya (林小雅)** | Market Data Analyst & Frontend Developper Intern @ Shenzhen InnoX Academy

[![Portfolio](https://img.shields.io/badge/Portfolio-Lin_Xiaoya-blue?style=for-the-badge&logo=github)](https://linxiaoya0228.github.io/)
[![Role](https://img.shields.io/badge/Role-Market_Analyst_%26_Frontend_Dev-orange?style=for-the-badge)]()
[![Tools](https://img.shields.io/badge/Stack-Python_%7C_Tableau_%7C_HTML5-yellow?style=for-the-badge)]()

*This repository documents the technical implementation and market analysis I conducted during my internship (Dec 2025 – Jan 2026), contributing to a Red Dot Nominee product launch.*

[Project Overview](#-executive-summary) • [Data Analysis](#-key-contributions-data-analysis) • [Technical Implementation](#-technical-implementation)

</div>

---

## 📖 Executive Summary

**The Context:**
During my internship at **Shenzhen InnoX Academy**, I was tasked with supporting the global launch of a haptic wearable device ("PatPat") targeting the US market via **CES 2026**.

**The Problem:**
The product initially lacked a defined market fit, oscillating between "hardcore fitness" and "VR gaming"—highly saturated markets with prohibitive Customer Acquisition Costs (CAC).

**My Solution (The Pivot):**
Using **Python web scraping** and **sentiment analysis** on competitor reviews (Reddit/Amazon), I identified unserved personas in the "Somatic Wellness" sector. I then translated these insights into a **Go-To-Market (GTM) strategy** and engineered the **customer-facing digital infrastructure** (Landing Page & Design System).

---

## 🚀 Key Contributions: Data Analysis

### 1. Market Sentiment & Pain Point Analysis
I scraped unstructured data from competitor reviews to identify why users were churning. The analysis revealed that "Subscription Fatigue" and "Morning Stiffness" were significantly higher pain points than "Fitness Features."

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'pie1': '#F97316', 'pie2': '#333333', 'pie3': '#555555', 'pie4': '#777777' }}}%%
pie title Market Sentiment Analysis (Negative Reviews)
    "Subscription Fatigue" : 42
    "Morning Stiffness / Pain" : 35
    "Setup Difficulty" : 15
    "Battery Life" : 8

```

### 2. Strategic Pivot: Target Audience
Based on the data above, I proposed shifting the product positioning from "Athletic Performance" to "Somatic Wellness," targeting aging demographics and casual rhythm gamers.

```mermaid
gantt
    title Strategic Pivot: Target Audience Shift
    dateFormat  X
    axisFormat %s
    
    section Original Strategy
    Hardcore Gamers (VR)      :crit, active, 0, 10
    Fitness Athletes          :crit, active, 0, 10
    
    section My Data-Driven Strategy
    Somatic Wellness (Aging)  :done, 10, 20
    Tech-Forward Parents      :done, 10, 20
    Casual Rhythm Gamers      :done, 10, 20
```

## 💻 Technical Implementation
Beyond analysis, I served as the primary **Frontend Developer** for the campaign's digital touchpoints. I utilized a **Hybrid Architecture** (Custom Code injected into CMS) to balance rapid deployment with high-fidelity design.



### 🌌 1. Interactive "Design System" Orbit
* **Objective:** Visualize the R&D philosophy (Shape Change, Human Sensory, Fabric Tech).
* **Tech Stack:** Vanilla JavaScript (Canvas-less physics).
* **Implementation:** Built a custom orbital physics engine that maps 30+ icons to specific gravitational paths based on their category tags, allowing for dynamic filtering without page reloads.


### 🎨 2. The High-Conversion Landing Page
* **Objective**: Capture leads during CES 2026.
* **Tech Stack**: HTML5, Tailwind CSS (CDN), Forminator API.
* **Key Feature**: "Dual-Screen" Mobile UI Showcase. I engineered a responsive CSS grid that visualizes the app interface inside realistic phone bezels, solving the challenge of displaying vertical screenshots on desktop displays.

**Code Highlight: Custom Phone Bezel CSS**
```css
/* Creating realistic device frames using pure CSS */
.phone-screen {
    height: 420px !important;
    border: 10px solid #1a1a1a; /* Simulated Bezel */
    border-radius: 24px;
    background: #000;
    box-shadow: 0 30px 60px -15px rgba(0, 0, 0, 0.9); /* Depth */
    transition: all 0.4s ease;
}
```

### 🧪 3. 3D Texture Visualization (HufuLab)
* **Integration:** Integrated **Spline 3D** and **Wistia** to render high-fidelity fabric physics directly in the browser, ensuring low latency for mobile users.

---

## 🗓️ Commercial Roadmap Design
Formulated an **"Export-to-Domestic"** strategy, leveraging US brand equity (Kickstarter) to drive premium positioning for the Chinese market (618 Festival). 

> *See detailed timeline in [Launch_Timeline.md](./Launch_Timeline.md)*

```mermaid
gantt
    title Interactive Clothes Global Commercialization Plan (2025-2026)
    dateFormat  YYYY-MM-DD
    axisFormat  %m/%d

    section P1: Validation & CES
    _ :p1pad, 2025-12-08, 1d
    Nursing Home Test                 :done, des1, 2025-12-23, 2d
    CES Landing Page Live             :done, des2, 2025-12-31, 1d
    Award Applications (Red Dot)      :milestone, 2026-01-01, 6d
    CES 2026 Expo                     :active, des3, 2026-01-02, 8d
    Red Dot Deadline                  :crit, milestone, 2026-01-16, 1d

    section P2: Production & Prep
    PVT Trial Start                   :des5, 2026-02-01, 1d
    KOL/YouTuber Samples              :des6, 2026-02-01, 20d
    Email Marketing (EDM)             :des7, 2026-02-20, 7d
    Red Dot Sample Shipment           :des8, 2026-02-09, 19d
    KS Review Submission              :crit, des9, 2026-02-15, 6d
    A' Design Award Deadline          :milestone, 2026-02-28, 1d

    section P3: Kickstarter
    Email Countdown                   :des10, 2026-03-01, 9d
    Kickstarter Launch                :crit, milestone, 2026-03-10, 1d
    External Traffic                  :des11, 2026-03-15, 15d
    IDEA Deadline                     :milestone, 2026-03-11, 1d
    Core77 Deadline                   :milestone, 2026-03-27, 1d

    section P4: Wrap‑up & CN Entry
    G‑Mark Opens                      :milestone, 2026-04-01, 1d
    KS Ends                           :crit, milestone, 2026-04-10, 1d
    MP Prep Start                     :des12, 2026-04-15, 1d
    CN Seeding (Export→Domestic)      :des13, 2026-04-15, 15d
    FastCo Deadline                   :milestone, 2026-04-25, 1d

    section P5: 618 Campaign
    Tmall/JD Setup                    :des14, 2026-05-10, 1d
    iF Award Opens                    :milestone, 2026-05-15, 1d
    618 Pre‑Sale                      :crit, des15, 2026-05-26, 1d
    KS First Shipping                 :des16, 2026-06-10, 1d
    618 Peak                          :des17, 2026-06-15, 6d

    section P6: Fulfillment
    CN 618 Shipping Start             :des18, 2026-07-01, 1d
    User Community                    :des19, 2026-07-15, 1d
    CES 2027 Opens                    :milestone, 2026-09-01, 1d

```
## 🏆 Results & Impact

* **500+ Pre-launch Leads** captured via the landing page within the first 48 hours of CES.
* **Red Dot Award Nominee:** The narrative pivot contributed to the design award submission.
* **Strategic Clarity:** Replaced manual data compilation with automated dashboards, streamlining executive decision-making for the 2026 roadmap

---

<div align="center">

**[⬅ Back to Lin Xiaoya's Portfolio](https://linxiaoya0228.github.io/)** 
*This project is part of my professional experience portfolio. All proprietary data has been sanitized.*

</div>
