# 🔧 Git Operations Node

*This node is part of the [🧠 ManySkills Network](../manyskills.md). Reference this node when performing version control operations.*

---

## 🎯 Scope of Competency
This node outlines the exact branch and commit workflows for this repository. It ensures clean, predictable history and prepares code for seamless peer reviews.

---

## 🚦 Git Directives

### 1. Branch Naming Convention
Every branch created must start with a classification prefix followed by a hyphenated description:
- `feat/` for new features (e.g., `feat/auth-jwt-rotation`)
- `fix/` for bug fixes (e.g., `fix/header-alignment`)
- `docs/` for documentation-only changes (e.g., `docs/api-guide`)
- `refactor/` for code restructuring (e.g., `refactor/database-queries`)

### 2. The Semantic Commit Protocol
All commit messages must strictly adhere to the Conventional Commits specification:
```
<type>(<scope>): <short descriptive summary>

[Optional longer body explaining 'why', not 'what']
```

#### Allowed Types:
- `feat`: A new user-facing feature.
- `fix`: A bug fix.
- `docs`: Documentation updates.
- `style`: Changes that do not affect code logic (formatting, spacing, etc.).
- `refactor`: Code changes that neither fix a bug nor add a feature.
- `test`: Adding or correcting tests.
- `chore`: Build steps, dependency updates, or tool configurations.

---

## 🛠️ Step-by-Step Feature Workflow

When a user requests a code change, follow this sequence:

1. **Verify your working tree:**
   Ensure your workspace is clean:
   ```bash
   git status
   ```
2. **Fetch and rebase on main:**
   ```bash
   git checkout main
   git pull origin main
   ```
3. **Spin up a new branch:**
   ```bash
   git checkout -b feat/<short-description>
   ```
4. **Develop and commit:**
   Keep changes atomic. Commit frequently with clean messages:
   ```bash
   git add -A
   git commit -m "feat(api): connect dashboard charts to backend"
   ```
5. **Verify and push:**
   Run tests first (traverse to the [Test Node](test_node.md) if needed), then push:
   ```bash
   git push -u origin <your-branch-name>
   ```

---

## 🔗 Connected Nodes
* **Back to Center:** [🧠 manyskills.md](../manyskills.md)
* **Next Step (Verification):** [🧪 Automated Testing Node](test_node.md)
