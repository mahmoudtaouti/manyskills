# 🧾 Accounting & Audit Node

This node governs financial statement generation, bookkeeping workflows, and compliance audits. It ensures data integrity and adherence to Generally Accepted Accounting Principles (GAAP) or International Financial Reporting Standards (IFRS).

## 🎯 Cognitive Foundation
- **Parse Intent:** Is the user trying to reconcile past transactions, generate financial statements, or prepare for an upcoming audit?
- **Semantic Alignment:** Use accounting nomenclature: Accrual vs. Cash, Depreciation, Amortization, Accounts Receivable (AR), Accounts Payable (AP), Retained Earnings, Variance, Double-Entry.

## ⚙️ Execution Mechanics

### 1. The 3-Statement Model Generation
When asked to analyze or generate financial statements from raw data:
* **Income Statement:** Calculate Revenue, COGS, Gross Profit, Operating Expenses (SG&A), and Net Income.
* **Balance Sheet:** Ensure Assets = Liabilities + Shareholders' Equity. Categorize into Current and Non-Current.
* **Cash Flow Statement:** Reconcile Net Income to actual cash by adjusting for non-cash expenses (Depreciation) and changes in Working Capital. Group by Operating, Investing, and Financing activities.
* Explicitly state if you are using Accrual or Cash basis accounting.

### 2. Variance Analysis & Budgeting
If the prompt involves comparing budgets to actual performance:
* Output a table calculating the exact percentage and dollar variance for each line item.
* Isolate the **Volume Variance** (selling more/fewer units) from the **Price Variance** (selling at a higher/lower cost).
* Provide a narrative explaining the operational causes of the largest variances.

### 3. Audit-Prep & Red Flag Detection
If asked to review ledgers or prepare for compliance:
* Scan for standard accounting red flags: irregular journal entries made on weekends, unexplained spikes in AP, or revenue recognized before obligations are fulfilled (Revenue Recognition Principle).
* Output a checklist of documentation the auditors will request (e.g., Bank Reconciliations, Fixed Asset Schedules, Debt Agreements).

---

> [!NOTE]
> **To the AI Agent:** Accounting is the language of business, and it must balance perfectly. Never output a Balance Sheet where Assets do not exactly equal Liabilities + Equity. If data is missing to achieve this balance, explicitly state what is missing.

---

## 🔗 Connected Nodes
- [Back to Financial Hub](../SKILL.md) | [Raw Link](https://raw.githubusercontent.com/mahmoudtaouti/manyskills/master/_financial/SKILL.md)
