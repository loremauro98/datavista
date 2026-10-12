# Context: data

> Room Contract for `/data`. Governs what is allowed and expected in this folder.
> Consult `../AGENTS.md` for project-wide routing and rules.

## 1. Role & Purpose
Read-only empirical data, reference benchmarks, and stabilized outputs.

---

## 2. Allowed Inputs
External experimental data, raw logs, imported datasets.

---

## 3. Core Process & Execution
Storage and access only. Agents must never overwrite or delete raw data.

---

## 4. Expected Outputs
Versioned datasets and stable checkpoints.

---

## 5. Local Invariants & NEVER Rules
- **NEVER modify or mutate raw data — treat as strictly immutable.**
- **Intermediate caches go to current_output/ or temporary folders.**
- **Large data files must be ignored by version control.**

---

## 6. General Guidelines
All changes in this workspace must follow the 9-step engineering pipeline defined in [../CODE_PIPELINE.md](../CODE_PIPELINE.md).
Tests governing logic here belong in `tests/`.
