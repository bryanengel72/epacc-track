# EPACC Track & Field Suite

Interactive compliance and operations tools for NCAA and NAIA Track & Field and Cross Country programs. Built by [E-Performance Compliance & Consulting Group (EPACC)](https://epacc.example).

**Live site:** `https://<your-github-username>.github.io/epacc-track-suite/`

---

## What's in the suite

Two self-contained, browser-based instruments that work together as a diagnostic → operations workflow.

### 1. NAIA Track & Field Eligibility & Compliance Readiness Assessment
**File:** `NAIA_Track_Compliance_Readiness_Assessment.html`

A 25-item diagnostic that scores a Track & Field / Cross Country program across six weighted compliance domains:

| Domain | Weight |
|---|---|
| NAIA Eligibility Certification | 22% |
| Progress Toward Degree (PTD) & Academic Standards | 20% |
| Audit Readiness, Records & Reporting | 18% |
| Transcript & Enrollment Verification | 14% |
| Recruiting Communication & Documentation | 14% |
| Rules Education & Student-Athlete Onboarding | 12% |

**Outputs:**
- Composite readiness percentage with live scoring
- Risk tier (Low / Moderate / Elevated / Critical)
- Domain-level performance bars
- Prioritized 30-day and 31–90-day action lists
- Tier-specific EPACC engagement recommendation
- Print-friendly report

### 2. Track & Field Operations Financial & Compliance Audit Tool
**File:** `Track_Operations_Financial_Compliance_Audit_Tool.html`

An interactive workspace for running financial and compliance audits across seven operational domains. Editable tables, live KPI recalculation, charted dashboard, and a generated audit report.

**Tabs:**
- Overview · framework summary
- Program Setup · institution, fiscal year, roster, division
- Budget Tracker · category-level budget vs. actual with variance analysis
- Travel & Meets · trip-by-trip cost analysis with per-athlete metrics
- Recruiting · prospect visit tracking with event-group tagging
- Equipment · lifecycle cost analyzer with procurement approval tracking
- Compliance · 12-point checkpoint review (severity-tagged)
- Dashboard · live charts and composite health score
- Audit Report · printable, distribution-ready summary

**Division coverage:** NCAA Division I, II, III; NAIA; NJCAA. The compliance layer adapts references based on division selection.

---

## How to use

### Locally
1. Clone or download this repository.
2. Open `index.html` in any modern browser.
3. Click into either tool from the landing page.

No build step, no dependencies to install. Everything runs client-side.

### Hosted on GitHub Pages
1. Push this repository to GitHub.
2. Enable GitHub Pages under **Settings → Pages**.
3. Set source to `Deploy from a branch` → `main` → `/ (root)`.
4. Your suite will be live at `https://<your-username>.github.io/<repo-name>/`.

---

## Technical notes

- **Pure HTML/CSS/JavaScript.** No frameworks, no build system, no server.
- **Chart.js loaded from CDN** (audit tool only) for dashboard visualizations.
- **Google Fonts (Inter + Playfair Display)** loaded from CDN for typography.
- **All data stays in your browser.** Nothing is transmitted, logged, or stored remotely.
- **Export Snapshot (JSON)** lets you save and version audit data manually.
- **Print-to-PDF** is supported via the browser's print dialog with print-optimized CSS.

---

## Browser support

Tested on current versions of Chrome, Edge, Firefox, and Safari (desktop and mobile). Recommended viewport: 1024px wide or larger for the audit tool dashboard.

---

## File structure

```
.
├── index.html                                              ← Landing page
├── NAIA_Track_Compliance_Readiness_Assessment.html         ← Diagnostic tool
├── Track_Operations_Financial_Compliance_Audit_Tool.html   ← Audit workspace
└── README.md                                               ← This file
```

---

## The framework behind the tools

The suite operationalizes EPACC's three-phase methodology:

**Diagnose** — Use the Readiness Assessment to establish a defensible compliance baseline.

**Engage** — The tier output names a fit-for-purpose EPACC engagement: Foundation (Critical), Pilot (Elevated), Hardening (Moderate), or Continuous Monitoring (Low).

**Operate** — Run the Operations Audit Tool on a monthly cadence to keep budget variance within tolerance, maintain compliance documentation at 100%, and produce the report that goes to the AD, Head Coach, Business Office, and Compliance Office.

---

## About EPACC

E-Performance Compliance & Consulting Group is the only athletic compliance consulting firm built on empirical doctoral research connecting governance systems to academic performance metrics (APR, GSR). Our theoretical foundation incorporates the Burke-Litwin Organizational Change Model, the ADKAR behavioral change framework, and Compliance Theory to help athletic departments navigate complex compliance landscapes while protecting academic performance outcomes.

**Services:** Institutional B2B consulting, professional certification & training, student-athlete education.

**Coverage:** NCAA Division I, II, III; NAIA; NJCAA.

---

## Disclaimer

This suite provides directional risk and operational insight. It does not constitute a formal eligibility determination, financial audit, or legal advice. Always corroborate findings with your institution's Compliance Office, Registrar, Business Office, and General Counsel.

---

## License

© EPACC — E-Performance Compliance & Consulting Group. All rights reserved.

The contents of this repository are proprietary. Permission to view and use the suite is granted for evaluation and licensed-engagement purposes. Redistribution, modification, or derivative works require written permission from EPACC.

---

## Contact

Engagement inquiries: `contact@epacc.example`
Web: `https://epacc.example`
