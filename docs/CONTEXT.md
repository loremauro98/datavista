# Context: docs

> Room Contract for `/docs`. Governs what is allowed and expected in this folder.
> Consult `../AGENTS.md` for project-wide routing and rules.

## 1. Role & Purpose
Permanent architecture blueprints, scientific literature, guides, and CHANGELOG.

---

## 2. Allowed Inputs
Project milestones, finalized specifications, paper citations.

---

## 3. Core Process & Execution
Documentation synchronization, literature indexing, version history.

---

## 4. Expected Outputs
System manuals, architecture diagrams, CHANGELOG.md records.

---

## 5. Local Invariants & NEVER Rules
- **Keep structure synchronized via sync_tree / icm-maintenance.**
- **Maintain permanent audit log in docs/CHANGELOG.md.**

---

## 6. General Guidelines
All changes in this workspace must follow the 9-step engineering pipeline defined in [../CODE_PIPELINE.md](../CODE_PIPELINE.md).
Tests governing logic here belong in `tests/`.
