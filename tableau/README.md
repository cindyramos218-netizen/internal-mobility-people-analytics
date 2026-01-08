# Tableau Dashboard

This folder contains the interactive Tableau dashboard used to visualize
internal mobility patterns and mobility personas.

The dashboard is designed to support **exploratory analysis and executive
conversation**, not operational decision-making.

---

## Files

### internal_mobility_dashboard.twbx
Packaged Tableau workbook containing:
- Mobility by Persona (job change rate)
- Persona Size (population distribution)
- Job Change Rate by Training Exposure (overall)

The workbook is fully self-contained and can be opened in:
- Tableau Public (Desktop)
- Tableau Desktop (if licensed)

---

## Dashboard Purpose

The dashboard enables HR and People Analytics stakeholders to:
- Compare job-change rates across mobility personas
- Understand the relative size and stability of each persona
- Explore whether training exposure meaningfully differentiates mobility risk
- Ground workforce investment conversations in consistent, explainable signals

---

## How to Use

Recommended flow:
1. Start with **Mobility by Persona** to understand relative risk
2. Review **Persona Size** to assess population-level impact
3. Use **Training Exposure** to test common assumptions about development spend

Insights should be interpreted at the **group level only**.

---

## Design Notes

- Personas are rule-based and intentionally transparent
- Metrics are aggregated and anonymized
- Visuals emphasize comparison and clarity over complexity
- No predictive modeling is used in this dashboard

---

## Important Limitations

- The dashboard does not predict individual attrition
- Personas should not be used for performance evaluation or individual targeting
- Findings are directional and intended to inform strategy, not policy decisions

---

## Data Source

- Cleaned, analysis-ready dataset from the `data/` folder
- Dataset reflects anonymized HR records used for portfolio demonstration

