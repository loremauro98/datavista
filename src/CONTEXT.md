# Context: src

> Room Contract for `/src`. Governs what is allowed and expected in this folder.
> Consult `../AGENTS.md` for project-wide routing and rules.

## 1. Role & Purpose
Pure, stateless computational engines and core business/algorithmic logic.

---

## 2. Allowed Inputs
Configuration objects, raw data structures, or explicit mathematical specifications.

---

## 3. Core Process & Execution
Pure functions, typed classes, vectorized math. Zero global state. Must never import from ops.

---

## 4. Expected Outputs
Deterministic return values, transformed tensors/dataframes, fitted model objects.

---

## 5. Local Invariants & NEVER Rules
- **Strictly stateless and pure functions where possible.**
- **Must never import from /ops (strict one-way dependency: ops -> src).**
- **Must be accompanied by headless unit tests.**

---

## 6. General Guidelines
All changes in this workspace must follow the 9-step engineering pipeline defined in [../CODE_PIPELINE.md](../CODE_PIPELINE.md).
Tests governing logic here belong in `tests/`.
