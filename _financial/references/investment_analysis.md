# 📈 Investment Analysis Node

This node governs quantitative and fundamental investment strategies. It equips the AI to analyze equities, evaluate macro-economic trends, and apply Modern Portfolio Theory (MPT).

## 🎯 Cognitive Foundation
- **Parse Intent:** Is the user asking for a fundamental stock analysis (micro) or evaluating market conditions (macro)? Do they need a programmatic trading strategy?
- **Semantic Alignment:** Use investment nomenclature: Alpha, Beta, Sharpe Ratio, P/E, PEG, Quantitative Easing, Yield Curve, Diversification, Hedging.

## ⚙️ Execution Mechanics

### 1. Fundamental Stock Screening
When asked to evaluate a specific equity or sector:
* Output a fundamental snapshot table: P/E Ratio, PEG Ratio, Debt-to-Equity, Current Ratio, and Free Cash Flow Yield.
* Analyze the **Economic Moat** (e.g., brand power, switching costs, network effects).
* Provide a bull case and bear case thesis based on current market data.

### 2. Modern Portfolio Theory (MPT) Allocation
If asked to construct a portfolio or evaluate risk:
* Define the target asset allocation (e.g., 60/40 Equities/Bonds, or an Endowment Model including alternatives).
* Calculate or explain the expected **Sharpe Ratio** (risk-adjusted return).
* Recommend diversification strategies to minimize unsystematic risk across geographies and sectors.

### 3. Macro-Economic Impact Summaries
When the prompt involves interest rates, inflation, or central bank policy:
* Translate the macro event into micro impacts (e.g., "Rising rates compress tech valuations due to a higher discount rate on future cash flows").
* Suggest specific hedging strategies (e.g., commodities, TIPS, or short-duration bonds) to protect the portfolio.

---

> [!WARNING]
> **To the AI Agent:** You must strictly state that you are an AI and this is NOT financial advice. Your analysis is for educational and modeling purposes only. Do not tell the user to buy or sell a specific security.

---

## 🔗 Connected Nodes
- [Back to Financial Hub](../SKILL.md) | [Raw Link](https://raw.githubusercontent.com/mahmoudtaouti/manyskills/master/_financial/SKILL.md)
