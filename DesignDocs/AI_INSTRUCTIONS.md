# AI\_INSTRUCTIONS.md

# AI Instructions for Kerbal Data Centers

Read these files in order before making significant changes:

1. DEVELOPER\_PROFILE.md
2. KDC\_CONTEXT.md
3. KDC\_GLOSSARY.md
4. KDC\_LORE.md
5. KDC\_ARCHITECTURE.md
6. KDC\_BALANCING.md
7. KDC\_ROADMAP.md

\---

# Primary Objective

Help develop Kerbal Data Centers while preserving the project's design philosophy, gameplay goals, and architectural integrity.

\---

# Required Workflow

Before implementing a feature:

1. Read the relevant project documentation.
2. Summarize your understanding.
3. Identify assumptions and risks.
4. Propose an implementation approach.
5. Make incremental changes.
6. Explain what changed and why.

\---

# Architectural Rules

* Favor modular PartModules.
* Prefer extensible designs.
* Preserve save-game compatibility whenever practical.
* Avoid unnecessary complexity.
* Use meaningful names.
* Avoid hard-coded values when configuration is appropriate.

\---

# Change Management

Do NOT:

* Rename public APIs without approval.
* Remove existing functionality without approval.
* Rewrite major systems when a targeted change will suffice.
* Change resource definitions without approval.

Prefer small, reviewable changes over large rewrites.

\---

# Communication

When requirements are unclear:

* Ask questions.
* Identify assumptions.
* Present alternatives and tradeoffs.

Do not assume that the first possible solution is the correct solution.

\---

# KDC Design Principles

* Encourage orbital infrastructure.
* Reward long-duration missions.
* Create meaningful gameplay loops.
* Balance realism with fun.
* Keep systems understandable by players.

When conflicts arise, gameplay takes priority over strict realism.

\---

# Success Criteria

A successful contribution:

* Preserves project goals.
* Is maintainable.
* Is understandable.
* Is documented.
* Minimizes future technical debt.

