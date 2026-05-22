# 🔍 Discovery & Demos Node

This node equips the AI to script and structure the most important phase of a sales cycle: The Discovery Call and the subsequent Product Demo. It strictly enforces the SPIN selling methodology to uncover deep pain before offering a solution.

## 🎯 Cognitive Foundation
- **Parse Intent:** Is the user preparing for a first-contact discovery call, or are they structuring a product demonstration?
- **Semantic Alignment:** Use discovery nomenclature: Qualification, BANT, SPIN, Champion, Decision Maker, Value Proposition, "Show, Don't Tell".

## ⚙️ Execution Mechanics

### 1. SPIN Discovery Scripting
When asked to prepare for a call, generate a script utilizing the SPIN framework. Do not output generic "how is your day" scripts.
* **Situation:** 2-3 questions establishing the current operational state (e.g., "What CRM are you currently using?").
* **Problem:** 2-3 questions probing for friction (e.g., "Where are deals getting stuck in that CRM?").
* **Implication:** 2-3 questions magnifying the pain (e.g., "How much revenue is lost per quarter because of those stuck deals?").
* **Need-Payoff:** 1-2 questions getting the prospect to state the value of a solution (e.g., "If you could automate that follow-up, how would that impact your quota attainment?").

### 2. Value-Driven Demo Flow
When structuring a demo, enforce the "Sell the Hole, Not the Drill" methodology:
* **The Recap:** Start the demo by repeating the Implication pain uncovered in discovery. Get a "Yes, that's correct."
* **The Harbor Tour (Avoid):** Explicitly warn against showing every feature.
* **The 3 Pillars:** Focus the demo on exactly 3 features that solve the specific pain.
* **Tie-Downs:** After each feature, generate a tie-down question (e.g., "Can you see how this eliminates the manual entry issue we discussed?").

---

> [!NOTE]
> **To the AI Agent:** Discovery is not an interrogation; it is a diagnosis. Generate questions that make the prospect realize the severity of their own problem before a product is ever mentioned.

---

## 🔗 Connected Nodes
- [Back to Sales Hub](../SKILL.md) | [Raw Link](https://raw.githubusercontent.com/mahmoudtaouti/manyskills/master/_sales/SKILL.md)
