# Context: planning

> Room Contract for `/planning`. Governs what is allowed and expected in this folder.
> Consult `../AGENTS.md` for project-wide routing and rules.

## 1. Role & Purpose
Task tracking, architectural specifications, design documents, and decisions.

---

## 2. Allowed Inputs
User requirements, GitHub issues, experimental hypotheses.

---

## 3. Core Process & Execution
Design iterations, 80/20 planning phase, implementation specifications.

---

## 4. Expected Outputs
Task description files under planning/tasks/ (e.g. task_<name>.md).

---

## 5. Local Invariants & NEVER Rules
- **All active tasks must have a markdown log in planning/tasks/.**
- **Completed tasks are archived to planning/tasks/archive/ during /project-checkpoint.**
- **Never write ad-hoc task notes to the repository root.**

---

## 6. General Guidelines
All changes in this workspace must follow the 9-step engineering pipeline defined in [../CODE_PIPELINE.md](../CODE_PIPELINE.md).
Tests governing logic here belong in `tests/`.
