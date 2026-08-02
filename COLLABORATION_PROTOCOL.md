# Collaboration Protocol

## Purpose

This repository is the authoritative source of truth for the project.

All contributors must use repository documentation as the primary reference before proposing, discussing, implementing, or modifying any component.

No work begins from assumptions.

All work begins from documented state.

---

# Source of Truth Rule

Before making recommendations, changes, designs, specifications, implementations, or reviews:

Contributors must review:

- README.md
- PROJECT_STRUCTURE.md
- FOUNDERS_NOTES.md
- OPEN_QUESTIONS.md
- Relevant specification files
- Relevant research files

Repository documentation supersedes memory, assumptions, previous conversations, and undocumented interpretations.

---

# Documentation First

No structural modification may be proposed without first identifying:

1. Existing structure affected
2. Existing files affected
3. Existing invariants affected
4. Existing assumptions affected

Changes must reference current repository state.

Undocumented changes are invalid.

---

# Directional Stability

The project shall not change direction based on preference alone.

New directions require documented justification.

Acceptable reasons include:

- Contradictory evidence
- Proven architectural failure
- Formal threat discovery
- Measurable improvement
- Removal of unnecessary complexity
- Demonstrated inconsistency with project goals

Preference is not sufficient justification.

Novelty is not sufficient justification.

---

# Preservation Before Expansion

Before introducing new systems, contributors must determine whether:

- Existing components solve the problem
- Existing components can be extended
- Existing components can be simplified

Expansion is the final option.

Not the first.

---

# Continuity Requirement

Every proposed change must answer:

1. What problem is being solved?
2. What existing component is affected?
3. Why is the current design insufficient?
4. What evidence supports the change?
5. What new risks are introduced?
6. How is continuity preserved?

If these questions cannot be answered, the change remains a proposal.

---

# Repository Hierarchy

Authority flows from documentation.

The hierarchy is:

1. Specifications
2. Architecture documents
3. Research documents
4. Planning documents
5. Discussion

When conflicts occur, higher layers take precedence.

---

# Proposal Format

All significant changes should include:

## Summary

Brief description.

## Motivation

Reason for change.

## Evidence

Supporting observations, testing, analysis, or research.

## Impact

Affected files, systems, or invariants.

## Risks

Potential negative outcomes.

## Decision

Accept, reject, defer, or research further.

---

# Assumption Control

Assumptions must be identified explicitly.

Assumptions should never be treated as facts.

Unknowns should remain documented as unknowns until verified.

---

# Open Questions

Questions without evidence belong in:

OPEN_QUESTIONS.md

They do not become architecture until supported.

---

# Collaboration Standard

Contributors are expected to:

- Read before proposing
- Understand before modifying
- Preserve before replacing
- Document before implementing
- Verify before concluding

---

# Structural Change Rule

No contributor may alter repository structure without:

1. Reviewing existing structure
2. Explaining why change is required
3. Identifying affected components
4. Preserving continuity of documentation

Structure exists to preserve understanding.

Changes to structure require justification.

---

# Principle of Continuity

The objective is not to continuously create.

The objective is to continuously understand.

A smaller architecture that remains coherent is preferred over a larger architecture that loses continuity.

All contributions should strengthen clarity, traceability, and survivability of the project.
