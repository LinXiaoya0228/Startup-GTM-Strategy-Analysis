
<div align="center">

# 🚀 GTM Strategy & Persona Modeling: "Interactive Clothes"
### From Unstructured Data to Commercial Roadmap

[![Status](https://img.shields.io/badge/Status-Completed-success)]()
[![Event](https://img.shields.io/badge/Launch-CES_2026-blue)]()
[![Tool](https://img.shields.io/badge/Tools-Python_%7C_Tableau_%7C_HTML5-yellow)]()

*A comprehensive market analysis, commercial roadmap, and landing page implementation for a haptic wearable startup targeting the Health-Tech sector.*

</div>

---

## 📖 Executive Summary
**The Challenge:** A Shenzhen-based hardware startup developed a "haptic vest" with 12 vibration nodes but lacked a clear market fit. They initially targeted "general fitness," a saturated market with high customer acquisition costs.

**My Role:** As a Market Data Analyst & Frontend Contributor, I pivoted the strategy from "Fitness" to **"Somatic Health & Neuro-Rehab"**, identifying three unserved personas. I then engineered the **CES 2026 Landing Page** and a 6-month commercial roadmap spanning **CES (USA)** to **618 (China)**.

---

## 🌐 Digital Execution: CES Landing Page
To capture leads at CES 2026, I co-developed a high-conversion Landing Page. I implemented a responsive design using **HTML5 & Tailwind CSS**, featuring custom-coded visual interactions to demonstrate the app interface.

### 🎥 Live Demo (Preview)
> *The GIFs below demonstrate the responsive scrolling interactions and the "Zero-Distraction" video player implementation.*

<table width="100%">
  <tr>
    <td width="45%" align="center">
      <img src="CES_Landing_Page/HUFUWeb1.gif" width="100%" alt="Landing Page Scroll Part 1"/>
    </td>
    <td width="10%">
        </td>
    <td width="45%" align="center">
      <img src="CES_Landing_Page/HUFUWeb2.gif" width="100%" alt="Landing Page Scroll Part 2"/>
    </td>
  </tr>
</table>

<div align="center">

### 📺 [Click Here to Watch the Full 1-Minute Walkthrough on YouTube](https://youtu.be/UrTLQHxSCOg)

</div>

### 💻 Key Technical Contributions
* **Survey Integration:** Engineered a custom **Forminator** questionnaire using CSS Grid/Flexbox hacks to force a 2-column layout on desktop while maintaining a mobile-friendly single column.
* **Responsive Design:** Implemented "Mobile-First" media queries to ensure the 12-point haptic feedback visualization renders perfectly on all devices.
* **Conversion Optimization:** Replaced standard forms with a gamified flow to capture buyer intent (Price sensitivity & Feature preference).

---

## 📊 Market Analysis: The Pivot
> *See full analysis in [Market_Analysis_and_Personas.md](./Market_Analysis_and_Personas.md)*

By analyzing "frequency keywords" in negative reviews of competitors, I discovered that **"Morning Stiffness"** and **"Subscription Fatigue"** were the two biggest pain points.

| Competitor Weakness | Our Strategic Pivot |
| :--- | :--- |
| **"Hardware as a Service"** (Monthly Fees) | **"One Price, Lifetime Access"** (No Subscription) |
| **"Athletic/Aggressive"** Branding | **"Gentle/Somatic"** Branding for Aging Parents |
| **"Setup Friction"** (Tripods/Mounts) | **"Wear & Play"** (Zero Setup Friction) |

---

## 🗓️ Commercial Roadmap (Gantt Chart)
> *See detailed timeline in [Launch_Timeline.md](./Launch_Timeline.md)*

I designed a "Export-to-Domestic" strategy: Building brand equity in the US (CES + Kickstarter) to drive premium sales in China.

```mermaid
gantt
    title Interactive Clothing GTM Execution Plan
    dateFormat  YYYY-MM-DD
    axisFormat  %m-%d
    todayMarker off

    section 🇺🇸 CES & Validation
    CES Landing Page Dev       :done,    2025-12-20, 2025-12-28
    Red Dot Submission (Urgent):crit,    2026-01-01, 2026-01-16
    CES 2026 Exhibition        :active,  2026-01-06, 2026-01-09

    section 🚀 Kickstarter
    KOL/Media Sample Sending   :         2026-02-01, 2026-02-20
    Platform Approval          :         2026-02-15, 2026-02-28
    KS Campaign Launch (Mar 10):crit,    2026-03-10, 2026-04-10

    section 🇨🇳 China Expansion
    618 Pre-Sale Prep          :         2026-04-15, 2026-05-20
    Tmall/JD Flagship Launch   :         2026-05-26, 2026-06-20
```
---

## 🛠️ Tools & Technologies
* **Web Development**: HTML5, CSS3 (Grid/Flexbox), Tailwind CSS, WordPress
* **Data Analysis**: Python (Scrapy), Tableau, Excel
* **Strategy**: SWOT Analysis, Persona Modeling
