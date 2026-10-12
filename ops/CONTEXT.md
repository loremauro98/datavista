# Context: ops

> Room Contract for `/ops`. Governs what is allowed and expected in this folder.
> Consult `../AGENTS.md` for project-wide routing and rules.

## 1. Role & Purpose
Pipeline orchestration, workflow runners, evaluation scripts, and reports.

---

## 2. Allowed Inputs
Stable outputs from /data, configuration specs, engines from /src.

---

## 3. Core Process & Execution
Batch iteration, multiprocessing orchestration, metric aggregation, report generation.

---

## 4. Expected Outputs
Run artifacts, benchmark metrics, processed datasets into /data, presentation decks.

---

## 5. Local Invariants & NEVER Rules
- **One-way dependency on /src.**
- **Must not re-implement core math — call /src engines instead.**
- **Expose all hyperparameters, seeds, and cutoff thresholds in signatures or configs.**

---

## 6. General Guidelines
All changes in this workspace must follow the 9-step engineering pipeline defined in [../CODE_PIPELINE.md](../CODE_PIPELINE.md).
Tests governing logic here belong in `tests/`.
