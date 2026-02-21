# Style Guide

This document defines the linguistic and stylistic standards for Luganda localization across open-source software projects.

The goal is to ensure clarity, consistency, and usability across different platforms (e.g., GNOME, Fedora, KDE, Debian, and others).

---

## 1. General Tone and Register

* Use clear, neutral, and modern Luganda.
* Avoid overly academic or archaic expressions.
* Prefer natural spoken Luganda that remains grammatically correct.
* Keep sentences concise and direct.

Software interfaces must be easy to understand under time pressure.

---

## 2. Sentence Length

* Keep UI text short.
* Avoid long, complex grammatical structures.
* Prefer direct instructions over descriptive phrases.

✅ Good:

* Nyiga Next.
* Weyongerayo.
* Sazaamu data yonna.

❌ Avoid:

* Long explanatory constructions when a short command works.

---

## 3. Imperative Form (Commands)

Commands must use correct Luganda imperative forms.

Examples:

* Open → Ggulawo
* Close → Ggalawo
* Continue (process) → Weyongerayo
* Go back → Ddayo
* Select → Londawo
* Search → Noonya
* Save → Tereka
* Delete → Sazaamu
* Remove → Gyawo

Use strong verbs for dangerous actions.

---

## 4. Continue vs Add

Distinguish between progression and quantity increase.

* Continue (workflow progression) → Weyongerayo
* Add more (increase quantity) → Weyongere

This distinction must be applied consistently.

---

## 5. Dangerous or Irreversible Actions

For destructive operations (e.g., formatting, deleting partitions):

* Use clear and strong verbs.
* Avoid soft or ambiguous words.
* Ensure tone communicates seriousness.

Example:

* This action cannot be undone.
  → Kino tekisobola kuddamu.

---

## 6. Loanwords and Technical Terms

Adopt a hybrid approach:

* Use Luganda grammar and verbs.
* Retain recognizable technical loanwords where clarity is improved.

Examples:

* Disk → Disiki
* Partition → Patisoni
* File → Fayiro
* Folder → Folda
* USB → USB
* Storage → Storage (context-dependent)

Avoid quotation marks around technical terms unless required by the interface.

---

## 7. Consistency of Terminology

Each technical concept must have:

* One primary approved term.
* Standardized spelling.
* Documented usage context.

Do not alternate between multiple Luganda equivalents unless explicitly documented in the glossary.

---

## 8. Questions and Confirmation Dialogues

Use clear question forms.

Examples:

* Okakasa nti oyagala okweyongerayo?
* Okakasa nti oyagala kusazaamu data?

Avoid translating English structure literally if it sounds unnatural in Luganda.

---

## 9. Capitalization

* Follow sentence-style capitalization unless software requires title case.
* Proper nouns remain capitalized.
* Button labels should match platform conventions.

---

## 10. Punctuation

* Use standard Luganda sentence punctuation.
* Avoid unnecessary quotation marks.
* Use question marks only for genuine questions.

---

## 11. Clarity Over Literal Translation

Do not translate word-for-word if it results in unnatural Luganda.

Always prioritize:

1. Meaning
2. Context
3. User understanding
4. Consistency

---

## 12. Cross-Project Compatibility

This style guide applies across multiple open-source ecosystems.

Platform-specific variations may be documented in the `project-notes/` directory.

---

This document may evolve as the community grows and terminology matures.
