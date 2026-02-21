# Loanword and Terminology Adaptation Policy

This document defines how English and other foreign technical terms are handled in Luganda localization within this project.

The project adopts a **hybrid terminology model**, balancing linguistic integrity with technical clarity and usability.

---

## 1. Core Principle

The purpose of localization is **clarity and usability**, not linguistic purity.

Terminology decisions must prioritize:

1. User comprehension
2. Consistency
3. Technical accuracy
4. Natural Luganda structure

Loanwords are acceptable when they improve clarity and recognition.

---

## 2. Terminology Classification Model

All technical terms fall into one of four categories:

---

### Category 1: Global Technical Standards (Do Not Translate)

These are internationally standardized technical identifiers.

Examples:

* USB
* Wi-Fi
* Linux
* HTTP
* BIOS
* UEFI
* TCP/IP

**Rule:**

* Keep original spelling.
* Do not translate.
* Do not phoneticize.
* Do not add Luganda prefixes or suffixes.

These are protocol names, not vocabulary terms.

---

### Category 2: Adapted Technical Loanwords

These are technical nouns commonly used in computing and software interfaces.

Examples:

* Disk → Disiki
* Partition → Patisoni
* File → Fayiro
* Folder → Folda
* Server → Seva
* Driver → Diraiva

**Rule:**

* Adapt to Luganda phonetics.
* Choose one standardized spelling.
* Document it in the glossary.
* Do not alternate spellings.

Example:
If "Disiki" is approved, do not later use "Diski" or "Disk".

Consistency is mandatory.

---

### Category 3: Native Luganda Action Verbs (Translate Fully)

General interface actions must use proper Luganda verbs.

Examples:

* Open → Ggulawo
* Close → Ggalawo
* Save → Tereka
* Search → Noonya
* Delete → Sazaamu
* Remove → Gyawo
* Continue (workflow) → Weyongerayo

**Rule:**

* Do not replace common verbs with English loanwords.
* Maintain correct Luganda grammar and verb forms.
* Use strong verbs for irreversible actions.

---

### Category 4: Abstract or Complex Technical Concepts (Case-by-Case)

Some terms require discussion due to complexity or ambiguity.

Examples:

* Encryption
* Virtualization
* Containerization
* Repository
* Kernel
* Mount

**Rule:**

* Open a terminology discussion issue.
* Provide context and usage examples.
* Evaluate clarity, length, and usability.
* Document the final decision.

These terms must never be decided without review.

---

## 3. Spelling Standardization Rules

To avoid inconsistency:

1. Once a spelling is approved, it must not change without formal review.
2. Avoid mixing phonetic variants.
3. Avoid partial English spelling unless the term is Category 1.
4. Document spelling decisions in the glossary.

Approved spelling becomes binding for all future translations.

---

## 4. Context-Based Adaptation

Some English terms may require different Luganda translations depending on context.

Example:

* Continue (workflow progression) → Weyongerayo
* Add more (quantity increase) → Weyongere

Context must always guide the choice.

If a term changes meaning depending on environment, the distinction must be documented.

---

## 5. Avoiding Over-Translation

Avoid creating long descriptive phrases when:

* The loanword is already widely understood.
* The translation becomes unclear.
* The term becomes too long for UI display.

Clarity and brevity are essential in interface localization.

---

## 6. Long-Term Terminology Stability

All approved loanwords and translations should aim for long-term stability across:

* Linux distributions
* Desktop environments
* Open-source applications
* Educational deployments

Terminology decisions should consider ecosystem-wide impact, not project-specific convenience.

---

## 7. Documentation Requirement

All significant terminology decisions must:

* Be discussed publicly.
* Be recorded in `docs/DECISIONS/`.
* Be reflected in `docs/GLOSSARY/`.

No term becomes official without documentation.

---

This hybrid model ensures that Luganda technical localization remains modern, usable, consistent, and sustainable across open-source ecosystems.
