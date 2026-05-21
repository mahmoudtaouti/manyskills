# 🧪 Automated Testing Node

*This node is part of the [🧠 ManySkills Network](../manyskills.md). Reference this node when writing or running automated tests.*

---

## 🎯 Scope of Competency
This node guides the AI agent on how to run tests, inspect results, and write robust unit and integration tests.

---

## 🚦 Testing Directives

### 1. Test-Driven Development (TDD) Preference
Whenever possible, follow the TDD workflow:
1. Write a failing test matching the new feature requirement.
2. Implement the minimum code necessary to make the test pass.
3. Refactor the code while keeping tests green.

### 2. Coverage Targets
Aim to maintain or exceed **80% code coverage** for newly introduced logical blocks. Focus test cases on:
- Happy paths.
- Boundary values (e.g., empty arrays, null values, extreme numbers).
- Error boundaries (e.g., database connection timeouts, invalid inputs).

---

## 🛠️ Executing Tests

Depending on the codebase environment, run the appropriate command:

### Node.js / TypeScript Projects
- **Run all tests:** `npm test`
- **Run single test file:** `npm test -- path/to/file.test.ts`
- **Run tests in watch mode:** `npm run test:watch`

### Python Projects
- **Run all tests:** `pytest`
- **Run with coverage report:** `pytest --cov=src`

---

## 🔍 Diagnosing Test Failures

If a test fails, do not guess the solution. Follow this checklist:
1. **Isolate the failure:** Run only the failing test file to speed up your debug cycles.
2. **Review inputs/outputs:** Check the difference between `Expected` and `Actual` values in the runner console output.
3. **Trace dependencies:** Verify mock objects and network calls are correctly configured and isolated.
4. **Fix and Re-run:** Correct the implementation and execute the tests again until green.

---

## 🔗 Connected Nodes
* **Back to Center:** [🧠 manyskills.md](../manyskills.md)
* **Previous Step (Workflow):** [🔧 Git Operations Node](git_node.md)
