---
name: _human_resource
description: Provides advanced Human Resources and Talent Management workflows, including inclusive Job Description writing, structured Interview designing, objective Candidate Resume evaluation, 90-day Onboarding planning, and fair Performance Review generation.
---
# 👥 Human Resources & Talent Management Hub

Welcome to the **Human Resources and Talent Management Hub**. This skill activates a senior HR Business Partner, Talent Acquisition Director, and Organizational Psychologist persona, equipping you with professional frameworks to recruit, onboard, assess, and develop world-class teams.

To maintain high cognitive efficiency and avoid instruction bloat, this skill is structured as a modular network. Use the map below to route yourself to the exact HR node needed.

---

## 🗺️ HR Node Navigation

```mermaid
graph TD
    %% Base Styles
    classDef root fill:#4F46E5,stroke:#312E81,stroke-width:3px,color:#FFF;
    classDef sub fill:#1E293B,stroke:#475569,stroke-width:1.5px,color:#E2E8F0;
    classDef active fill:#0D9488,stroke:#115E59,stroke-width:2px,color:#FFF;

    Hub["👥 HR Hub<br/>(SKILL.md)"]:::root
    
    %% Paths
    JD["📝 Job Descriptions<br/>(references/jd_writer.md)"]:::sub
    Interview["❓ Structured Interviews<br/>(references/interview_builder.md)"]:::sub
    Eval["🔍 Candidate Evaluation<br/>(references/candidate_evaluator.md)"]:::sub
    Onboard["🚀 90-Day Onboarding<br/>(references/onboarding_plan.md)"]:::sub
    Review["📈 Performance Reviews<br/>(references/performance_writer.md)"]:::sub

    %% Connections
    Hub --> JD
    Hub --> Interview
    Hub --> Eval
    Hub --> Onboard
    Hub --> Review
```

---

## 🚦 Navigation Protocol for AI Agents

When the user requests a Human Resources task, execute the following traversal protocol:
1. **Analyze Input:** Identify the specific type of HR or recruiting request.
2. **Retrieve Sub-Node:** Open the corresponding markdown file in the `references/` directory.
3. **Execute Framework:** Strictly follow the persona, inputs, rules, and formats specified in that sub-node. Do not compromise or skip sections.
4. **Adhere to Cognitive Foundation:** Always use the [Universal Fallback Node (generic.md)](../generic/generic.md) for information density, active voice, and visually clean structures.

---

## 📂 Active HR Sub-Nodes

### 📝 1. [Job Description Writer](references/jd_writer.md)
* **Best for:** Crafting compelling, search-optimized, and bias-free job descriptions.
* **Outputs:** Inclusive openings, first 6 months impact statements, outcomes-oriented responsibilities, credential-free requirements, and transparent compensation packages.

### ❓ 2. [Interview Question Builder](references/interview_builder.md)
* **Best for:** Designing highly predictive structured interview guides to reduce bias and objectively measure talent.
* **Outputs:** Chronological round matrices, Phone screening green/red flags, STAR-method behavioral question guides, role-specific technical assessments, scoring scorecards, and debrief templates.

### 🔍 3. [Candidate Evaluator](references/candidate_evaluator.md)
* **Best for:** Analyzing resumes objectively against a job description, discovering hidden strengths, and catching innocuous red flags.
* **Outputs:** Weighted Fit Scores (0-100), detailed strength/gap breakdowns, warning flag mitigations, targeted interview questions, comparison frameworks, and final advance/hold/pass recommendations.

### 🚀 4. [90-Day Onboarding Specialist](references/onboarding_plan.md)
* **Best for:** Planning comprehensive ramp-up curriculums that get hires to full productivity in half the usual time while maximizing long-term retention.
* **Outputs:** Pre-start administrative and social buddy setups, Week 1 day-by-day orientation schedules, month-by-month objectives, success metrics, and early failure warning signals.

### 📈 5. [Performance Review Writer](references/performance_writer.md)
* **Best for:** Designing fair, specific, legally sound, and development-oriented performance assessments.
* **Outputs:** Overall performance rating justifications, achievement outcome tables, core competency strength spotlights, constructive development plans with targets, and growth roadmap timelines.

---

## 🔗 Connected Nodes
* **Back to Central Index:** [🧠 manyskills.md](../manyskills.md)
* **Base Reasoning Rules:** [⚙️ generic.md](../generic/generic.md)
