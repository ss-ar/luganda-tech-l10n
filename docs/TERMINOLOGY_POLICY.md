# Terminology Policy

This document defines the principles used to determine how technical terms are translated into Luganda within this project.

The objective is to balance clarity, linguistic integrity, usability, and long-term consistency across open-source ecosystems.

---

## 1. Core Philosophy

Terminology decisions must prioritize:

1. User comprehension
2. Consistency across projects
3. Linguistic correctness
4. Technical precision

Literal translation is not required if it reduces clarity.

---

## 2. Hybrid Translation Model

This project adopts a hybrid approach:

* Luganda grammar and sentence structure are used consistently.
* Technical nouns may remain in adapted or recognizable loanword form when clarity is improved.

This avoids:

* Overly literal translations that sound unnatural
* Excessive borrowing that erodes Luganda structure

---

## 3. When to Use Loanwords

Loanwords are acceptable when:

* The term is globally standardized (e.g., USB, Wi-Fi, Linux).
* The Luganda equivalent is ambiguous or overly long.
* The translated form would reduce clarity in a technical context.
* The user community already recognizes the English-derived term.

Examples:

* Disk → Disiki
* Partition → Patisoni
* File → Fayiro
* USB → USB

Loanwords should follow consistent spelling once adopted.

---

## 4. When to Prefer Native Luganda Terms

Native Luganda terms should be preferred when:

* The concept has a clear and widely understood Luganda equivalent.
* The term refers to general actions (e.g., Save, Search, Open).
* The translation improves accessibility for non-technical users.

Examples:

* Save → Tereka
* Search → Noonya
* Open → Ggulawo
* Close → Ggalawo

---

## 5. Avoiding Over-Translation

Avoid creating complex or artificial phrases when:

* The translation becomes significantly longer than the original.
* The meaning becomes indirect or abstract.
* The resulting phrase resembles a description rather than a term.

Clarity must not be sacrificed for linguistic purity.

---

## 6. One Concept, One Term

Each technical concept must have:

* One primary approved Luganda equivalent.
* A standardized spelling.
* Documented usage context.

If alternatives exist, one must be selected as primary, and others documented as deprecated or contextual.

---

## 7. Context Sensitivity

Some terms may require different translations depending on context.

Example:

* “Continue” (workflow progression) → Weyongerayo
* “Add more” (quantity increase) → Weyongere

Context-based decisions must be documented.

---

## 8. Irreversible and High-Risk Actions

For destructive operations (formatting disks, deleting partitions, wiping data):

* Use strong verbs.
* Avoid ambiguous wording.
* Ensure the seriousness of the action is clear.

All such terminology must be reviewed carefully before approval.

---

## 9. Terminology Documentation Process

Every significant terminology decision must:

1. Be proposed through an issue.
2. Include contextual examples.
3. Be discussed openly.
4. Be documented in:

   * `docs/GLOSSARY.md`
   * `docs/DECISIONS/` (if significant)

This ensures transparency and prevents future inconsistency.

---

## 10. Long-Term Standardization

This project aims to establish a consistent Luganda technical terminology standard that can be adopted across:

* Linux distributions
* Desktop environments
* Open-source applications
* Educational technology initiatives

Terminology choices should therefore consider long-term ecosystem impact.

---

This policy may evolve as usage patterns and community consensus develop.
