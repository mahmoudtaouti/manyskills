# 📝 Data Storytelling & Summarization Node

This node acts as an automated translator between complex visual data (dashboards) and executive stakeholders. It removes the friction of interpreting charts by automatically generating written business narratives.

## 🎯 Cognitive Foundation
- **Parse Intent:** The user doesn't want more charts; they want to know *what the charts mean*.
- **Semantic Alignment:** Use executive reporting nomenclature: MoM (Month over Month), YoY, Headwinds, Tailwinds, Driven By, Offset By, Root-Cause.

## ⚙️ Execution Mechanics

### 1. The Executive Summary Framework
When asked to summarize a dataset or dashboard:
* Do not list raw data points row by row.
* **The Lead:** Start with the single most important macroeconomic shift in the data (e.g., "Overall Q3 revenue grew 14% to $2.1M").
* **The Drivers (Tailwinds):** Identify the specific segments that caused the growth.
* **The Drags (Headwinds):** Identify the segments that underperformed, calculating their drag on the overall metric.
* *Example:* "Revenue increased by 14% this quarter, primarily driven by enterprise software sales in Europe (+22%), despite a 4% dip in domestic retail sales."

### 2. Root-Cause Narratives
If a user asks *why* an anomaly occurred:
* Analyze the disparate data points. 
* Link the primary metric drop to secondary operational metrics.
* *Example:* "The 8% drop in MRR correlates directly with a 30% spike in average support ticket resolution times during the second week of the month, indicating churn was driven by delayed customer service."

### 3. Automated Dashboard Creation Prompts
If the user wants to generate visual charts instantly:
* Output the exact prompt or code needed to generate a dashboard structure (e.g., Python `matplotlib` code, or the specific query structure for a BI tool).
* Always pair a generated chart with a 2-sentence written summary below it.

---

> [!NOTE]
> **To the AI Agent:** Executives skim. Use bullet points and bold text for key figures. Never present a problem (anomaly) in your narrative without immediately presenting the correlated data explaining *why* it happened.

---

## 🔗 Connected Nodes
- [Back to BI Hub](../SKILL.md) | [Raw Link](https://raw.githubusercontent.com/mahmoudtaouti/manyskills/master/_business_intelligence/SKILL.md)
