# 🧠 ManySkills: The Agentic Knowledge Network

ManySkills is a state-of-the-art **Decentralized Agentic Knowledge Network** designed to structure, route, and optimize interaction prompts for advanced AI agents (such as Claude, Gemini, and GPT models).

**The goal is simple:** You give a tiny 5-word prompt, and the AI handles the massive complexity, rules, and specifications by traversing this skill network.

---

## 🎯 The Main Philosophy: Hub-and-Spoke Cognition

When an AI agent enters this repository, it acts like a visitor traversing a structured wiki. Rather than you writing a massive system prompt:
1. The agent reads the single central root router (`manyskills.md`).
2. It parses your short intent and references the network map.
3. It opens and loads **only** the specific, highly vertical skill node relevant to the current task.
4. If no specialized skill node exists, it dynamically drops back to the **Universal Fallback Node** to execute your prompt based on professional heuristics.

---

## 🚀 How to Use It (Zero-Friction Prompting)

You never need to manually search folders, copy-paste markdown instructions, or explicitly decide which skill files to use.

### Method A: Web-Connected AI Interfaces (ChatGPT, Claude, Gemini Web UI)
If you are using a standard web interface with browsing enabled, you just give the AI the raw URL to the router and your simple prompt. The AI will do the rest.

**Copy and paste this into ChatGPT/Claude/Gemini:**
> *"Use the knowledge network at https://raw.githubusercontent.com/mahmoudtaouti/manyskills/master/manyskills.md to handle my request. 
> 
> My prompt: [Insert your simple 5-word prompt here, e.g., 'write a cold email for SaaS']"*

**What happens next?**
The AI will visit the router, realize it needs the Marketing/Sales hub, construct the raw URL for that sub-node, read the deep instructions there, and output an expert-level result without you needing to specify tone, length, or rules.

### Method B: Workspace-Aware AI Assistants (Cursor, Windsurf, Antigravity)
If you are working with an advanced coding assistant operating locally inside this workspace directory:

**Just ask naturally:**
> `"Write a 7-email nurture sequence for our developer productivity SaaS."`

The assistant will automatically scan the project files, read `manyskills.md`, self-route to the Email Builder node, and execute the sequence with zero manual input from you.

---

## 📂 Project Structure

```
F:\GitRepositories\manyskills/
├── manyskills.md               <-- 🧠 Central Router (AI Execution Engine)
├── README.md                   <-- 📖 This index
├── generic/
│   └── generic.md              <-- ⚙️ Universal Fallback for unmapped prompts
├── nodes/                      <-- 💻 Code, Testing, DevOps Nodes
├── _marketing/                 <-- 📣 Growth Marketing & Strategy Hub
├── _business/                  <-- 💼 Business & Operations Hub
└── ... (Multiple specific skill domains)
```

## 🛠️ Scaling & Creating Skills

Whenever you add a folder or create a new skill, simply use a standard `SKILL.md` template (see `_template/SKILL_TEMPLATE.md`). 

Maintain the rule of **Density Displacement**: Keep the parent `SKILL.md` strictly under 150 lines. If a prompt requires deep examples, push them into a `references/` directory.