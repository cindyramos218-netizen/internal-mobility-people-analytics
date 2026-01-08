# Analysis

This folder contains the core analytical work used to develop and validate
rule-based internal mobility personas.

The analysis focuses on producing **decision-ready insights** rather than
individual-level prediction.

---

## Contents

### internal_mobility_analysis.ipynb
Primary analysis notebook that includes:
- Data exploration and cleaning
- Feature normalization (tenure, training exposure, education)
- Construction of rule-based mobility personas
- Validation checks (coverage, overlap, stability)
- Alternative persona cuts for robustness
- Aggregations used to inform Tableau dashboards and executive insights

This notebook is structured to mirror real-world people analytics workflows,
with an emphasis on transparency, auditability, and business relevance.

---

## Analytical Principles

- Personas are **descriptive**, not predictive
- Rules are explicitly defined and reproducible
- Insights are evaluated at the **program and population level**
- Findings are validated across Python, SQL, and Tableau

---

## Notes

- Sensitive or identifying employee data has been removed or anonymized
- This analysis intentionally avoids black-box modeling
- Outputs are designed to support HR strategy, not automated decision-making

