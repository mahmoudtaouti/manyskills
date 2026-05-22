# 💾 Text-to-Query (SQL/DAX) Node

This node governs the translation of plain-English business questions into precise, machine-executable code. It eliminates the need for manual SQL writing or dashboard building by bridging human intent directly to the database layer.

## 🎯 Cognitive Foundation
- **Parse Intent:** Determine what the user actually wants to measure. (e.g., "How are we doing?" usually implies a request for MoM Revenue Growth or Churn Rate).
- **Semantic Alignment:** Use database nomenclature: Schema, Joins, Primary Keys, DAX Measures, CTEs (Common Table Expressions), Aggregations.

## ⚙️ Execution Mechanics

### 1. Natural Language to SQL Generation
When a user asks a data question (e.g., *"Show me our monthly churn rate compared to last year"*), output the flawless SQL required to answer it:
* **Assumptions:** If the schema isn't provided, explicitly declare the assumed table structure (e.g., `Assume table 'subscriptions' with columns: user_id, start_date, end_date`).
* **Code Structure:** Use modern SQL practices. Prefer CTEs (`WITH` clauses) for readability over nested subqueries.
* **Safety:** Never output `DROP`, `DELETE`, or `UPDATE` statements unless explicitly commanded to do so in a DBA context. Always default to `SELECT`.

### 2. Power BI / DAX Translation
If the user implies they are working in Power BI, translate the request into DAX:
* Output the exact `CALCULATE`, `FILTER`, or `SUMX` formulas needed.
* Provide context on whether this should be created as a **Measure** or a **Calculated Column**.

### 3. Semantic Modeling & Documentation
If a data engineer asks for help setting up a BI environment:
* Generate descriptive metadata for their raw tables.
* Suggest logical relationships (e.g., "1-to-many relationship between `Users` and `Transactions` via `user_id`").
* Output markdown or JSON structures documenting the semantic layer.

---

> [!NOTE]
> **To the AI Agent:** You must retain conversational context. If the user asks a follow-up ("Filter that by product category"), modify the previous SQL/DAX code without asking them to repeat the base parameters.

---

## 🔗 Connected Nodes
- [Back to BI Hub](../SKILL.md) | [Raw Link](https://raw.githubusercontent.com/mahmoudtaouti/manyskills/master/_business_intelligence/SKILL.md)
