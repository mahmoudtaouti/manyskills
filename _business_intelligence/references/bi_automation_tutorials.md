# ⚙️ BI Automation & Tutorials Node

This node is activated when the user asks the AI to execute a complex, persistent, or external data task that the AI cannot run locally within its chat interface (e.g., real-time continuous fraud detection, automated web scraping, or deploying a permanent agent).

Instead of saying "I can't do that," the AI pivots to becoming an architectural consultant, providing step-by-step tutorials on how the user can set up external systems to achieve the goal.

## 🎯 Cognitive Foundation
- **Parse Intent:** Recognize the limitations of the current chat session. Identify if the user needs a persistent script, an external agent framework, or an integration platform.
- **Semantic Alignment:** Use tooling nomenclature: CRON jobs, API Endpoints, Webhooks, Multi-Agent Frameworks (LangChain, AutoGen), Process Mining, ETL Pipelines.

## ⚙️ Execution Mechanics

### 1. The Tooling Agnostic Tutorial Framework
When providing a tutorial on how to build an automation:
* **The Stack:** Recommend 2-3 standard, widely used tools (e.g., "To achieve this, you will need an orchestration tool like Airflow, or a no-code tool like Make/Zapier").
* **Step-by-Step Architecture:** Break down the exact logic flow:
  1. **Trigger:** What initiates the action (e.g., Webhook from Stripe).
  2. **Processing:** The script or AI agent required to analyze the data (e.g., Python script analyzing transaction anomaly).
  3. **Action:** The final output (e.g., Slack alert or database update).
* **Code Snippets:** Provide the foundational code (Python/Node.js) required for the 'Processing' step.

### 2. Process Mining Guidance
If the user wants to find operational bottlenecks from logs:
* Explain how to extract the Event Logs (Case ID, Activity, Timestamp).
* Provide a tutorial on using libraries like `pm4py` to map the workflow paths and identify the slowest transitions.

### 3. Deploying Persistent AI Agents
If the user wants continuous tracking (e.g., Competitive Intelligence or Real-Time Fraud):
* Outline how to set up a headless LLM agent using a framework like LangChain.
* Provide the system prompt architecture the agent will need to evaluate the incoming data continuously.

---

> [!NOTE]
> **To the AI Agent:** Never hit a dead end. If you cannot scrape a live website or run a 24/7 background process, provide the exact blueprint for how the user can deploy an AWS Lambda function or a Python script to do it themselves.

---

## 🔗 Connected Nodes
- [Back to BI Hub](../SKILL.md) | [Raw Link](https://raw.githubusercontent.com/mahmoudtaouti/manyskills/master/_business_intelligence/SKILL.md)
