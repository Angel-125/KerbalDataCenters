# DEVELOPER_PROFILE.md

# Developer Profile

This document describes the project owner, preferred development style, coding conventions, and collaboration expectations.

AI assistants should read this document before proposing architecture changes or generating significant amounts of code.

---

# Development Philosophy

The developer values understanding over blindly generating code.

When proposing solutions:

- Explain why the solution works.
- Explain tradeoffs.
- Avoid treating implementation details as magic.
- Prefer teaching over simply providing answers.

The developer learns by understanding systems and mechanics.

---

# Project Approach

The developer prefers:

1. Design first.
2. Architecture second.
3. Implementation third.

Do not immediately generate large amounts of code when requirements are unclear.

Instead:

- Clarify assumptions.
- Discuss architecture.
- Identify tradeoffs.
- Then implement.

---

# Communication Style

Preferred:

- Concise explanations.
- Structured information.
- Bullet points.
- Incremental learning.

Avoid:

- Massive walls of text.
- Excessive jargon.
- Overly abstract explanations.

When possible, break information into manageable chunks.

---

# Coding Style

## Naming

Use meaningful names.

Good:

```csharp
dataProcessingRate
currentReliability
orbitalDataCenter
```

Avoid:

```csharp
x
tmp
foo
bar
```

unless required by convention.

## Maintainability

Prefer:

- Readable code
- Clear intent
- Self-documenting design

Over:

- Clever tricks
- Dense code
- Premature optimization

## Documentation

Public APIs should be documented.

Complex systems should include comments describing intent and design rationale.

Comments should explain WHY rather than restating WHAT the code does.

## Architecture

Favor:

- Modular systems
- Extensible designs
- Configuration-driven behavior
- Separation of concerns

Avoid:

- Monolithic classes
- Tight coupling
- Hard-coded assumptions

---

# Modding Preferences

The developer creates mods because they enjoy:

- Systems design
- Worldbuilding
- Gameplay loops
- Engineering-inspired mechanics

The developer does not enjoy repetitive boilerplate implementation.

AI-generated code is acceptable when it reduces repetitive work.

---

# Kerbal Space Program Preferences

When working on KSP projects:

- Preserve save-game compatibility whenever practical.
- Favor gameplay over strict realism.
- Create meaningful reasons to build infrastructure.
- Encourage player creativity.
- Reward engineering solutions.

---

# AI Expectations

Before implementing changes:

1. Read project documentation.
2. Summarize understanding.
3. Identify assumptions.
4. Propose approach.
5. Implement.

Large changes should be broken into smaller reviewable steps.

The developer prefers collaboration rather than autonomous rewrites.
