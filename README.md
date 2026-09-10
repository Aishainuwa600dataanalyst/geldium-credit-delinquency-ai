# 💳 Geldium Credit Delinquency Analysis

[![Forage](https://img.shields.io/badge/Tata%20iQ-Geldium%20Finance-blue?logo=tata&logoColor=white)](https://www.theforage.com/) [![Certified](https://img.shields.io/badge/Status-Certified-brightgreen)]() [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

End-to-end credit risk analysis for a consumer-credit lender: data cleaning, exploratory analysis, business recommendations, and an AI-powered collections strategy.

**Author:** Aisha O. Inuwa  
**Program:** Tata iQ — AI Transformation Consultant Simulation (Forage)

---

## 📂 Documents

> Click any link to view instantly in your browser — no download needed.

| Document | What's Inside |
|:---------|:-------------|
| 📊 [Raw Dataset](Delinquency_prediction_dataset_(1).pdf) | Original 500-customer, 19-variable simulated dataset |
| 🧹 [Cleaned Dataset](Delinquency_prediction_dataset_CLEANED_BY_AISHA_O_INUWA.pdf) | Cleaned version with a documented cleaning log on the second sheet |
| 🔍 [EDA Summary Report](EDA_SummaryReport_Completed_BY_AISHA_O_INUWA.pdf) | Missing-value treatment, risk indicators, anomaly flags |
| 📝 [Business Summary Report](Geldium_Business_Summary_Report_Completed_by_Aisha_O_Inuwa.pdf) | Top 3 risk factors, SMART intervention framework, ethical considerations |
| 🤖 [AI Collections Strategy Deck](Geldium_AI_Collections_Strategy_Aisha_O_Inuwa.pdf) | Risk-tiered workflow, agentic AI split, guardrails, 90-day pilot roadmap |

---

## 🔍 Key Findings

- **Payment history is the strongest warning signal** — repeated Late/Missed payments across Month_1–Month_6 indicate repayment difficulty
- **High credit utilization** reduces financial flexibility and compounds risk
- **Repayment pressure** from high loan balance relative to income amplifies delinquency likelihood
- **Class imbalance** — only 16% of customers are delinquent; accuracy alone is misleading
- **Data quality issues** — inconsistent Employment_Status labels and Credit_Utilization values above 100% were corrected during cleaning

---

## 🤖 AI Collections Strategy Highlights

- **Risk-tiered workflow**: Low → standard statement · Medium → automated reminders · High → human outreach
- **Agentic AI**: Routine actions (scoring, reminders, logging) run autonomously; irreversible actions (hardship plans, bureau reporting) require human sign-off
- **Guardrails**: Fairness monitoring across groups, explainable reason codes per flag, regulatory alignment (ECOA, FDCPA), quarterly revalidation
- **90-day pilot**: Data prep → live scoring → review and scale/adjust/stop decision

---

## 🛡️ Responsible AI Considerations

- Biased or inconsistent data categories must be standardised before modelling
- False-positive and false-negative rates should be monitored across customer groups
- Predictions should support — not replace — human decision-making
- Model limitations, data lineage, and fairness metrics should be documented and version-controlled

---

## ⚠️ Note on the Dataset

This is a simulated Forage dataset. The delinquency target appears statistically independent of all features, so any predictive model would perform near random. The deliverables above reflect the simulation tasks as completed; the analytical methodology and reasoning are transferable to real credit-risk portfolios.

---

## 📜 License

[MIT](LICENSE) · The dataset is simulated and contains no real customer data.
