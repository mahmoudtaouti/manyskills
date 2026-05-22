# 🧠 Unstructured Data & RAG Node

This node governs the analysis of unstructured text (emails, PDFs, reviews) and the architecture of Retrieval-Augmented Generation (RAG) systems. It bridges the gap between raw quantitative data and qualitative human context.

## 🎯 Cognitive Foundation
- **Parse Intent:** The user wants to extract meaning from text/logs, not just numbers.
- **Semantic Alignment:** Use unstructured data nomenclature: Embeddings, Vector Database, Sentiment Analysis, RAG, NLP (Natural Language Processing), Data Labeling.

## ⚙️ Execution Mechanics

### 1. Customer Sentiment Analysis
When a user asks to gauge public perception based on reviews or social media:
* Output a categorization matrix: Positive, Neutral, Negative, and "Critical Escalation".
* Identify recurring keywords or themes driving the negative sentiment.
* Provide the Python script (using libraries like `TextBlob` or `VADER`) to run the sentiment analysis locally if requested.

### 2. Automated Data Labeling
If tasked with categorizing unstructured data (e.g., support emails):
* Define a strict taxonomy (e.g., "Billing Issue", "Bug Report", "Feature Request").
* Generate the prompt template that an LLM would use in a pipeline to auto-categorize incoming text against that taxonomy.

### 3. RAG Architecture Mapping
If the user asks a complex question requiring unstructured data (e.g., *"Why did shipping costs spike in Q3?"*):
* **Direct Execution:** If you possess the data in your context window, cross-reference the structured numbers with the unstructured logs/contracts and return a unified answer.
* **Architectural Guidance:** If you do not have the data, provide a blueprint on how the user can build a RAG system:
  1. Chunking the shipping logs and PDF contracts.
  2. Embedding them into a Vector DB (e.g., Pinecone or Weaviate).
  3. Querying the Vector DB simultaneously with the SQL database.

---

> [!NOTE]
> **To the AI Agent:** Unstructured data is messy. Your job is to enforce structure upon it. Always output your qualitative text analysis in highly structured tables or quantifiable percentages.

---

## 🔗 Connected Nodes
- [Back to BI Hub](../SKILL.md) | [Raw Link](https://raw.githubusercontent.com/mahmoudtaouti/manyskills/master/_business_intelligence/SKILL.md)
