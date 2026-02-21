# Contributing Guidelines

Thank you for contributing to the Luganda Tech Localization project.

This document explains how to propose new terminology, modify existing entries, and maintain consistency using the **one-term-per-file glossary structure**.

---

## 1. Before You Contribute

Please read:

* `README.md`
* `GOVERNANCE.md`
* `docs/STYLE_GUIDE.md`
* `docs/TERMINOLOGY_POLICY.md`

Understanding existing rules prevents duplication and inconsistency.

---

## 2. Glossary Structure (Important)

Each glossary term is stored as a separate Markdown file inside:

```
docs/glossary/
```

Example:

```
docs/glossary/continue.md
docs/glossary/disk.md
docs/glossary/partition.md
```

Each term must follow the standard template format.

---

## 3. Creating a New Glossary Entry

### Step 1: Open an Issue First

Before adding a new term:

1. Open a GitHub issue.
2. Use the title format:

```
Terminology Proposal: [English Term]
```

3. Include:

   * English term
   * Proposed Luganda translation
   * Context (where used)
   * Example sentence
   * Reasoning
   * Alternative options (if any)

Discussion should occur before the term is marked as approved.

---

### Step 2: Use the Template

Copy the file:

```
docs/glossary/_template.md
```

Rename it to:

```
docs/glossary/[term].md
```

Example:

```
docs/glossary/continue.md
```

---

### Step 3: Fill in the Required Front Matter

Each glossary file must begin with structured metadata:

```yaml
---
title: "Continue"
slug: "continue"
english: "Continue"
luganda: "Weyongerayo"
status: "proposed" # proposed | under_discussion | approved | deprecated
domains: ["installer", "ui"]
tags: ["navigation", "workflow"]
last_reviewed: "YYYY-MM-DD"
---
```

Metadata ensures:

* Future website integration
* Filtering by domain
* Easy search and indexing
* Structured documentation

---

### Step 4: Complete the Sections

Each term file must include:

* Meaning
* Notes
* Examples
* Alternatives (if relevant)
* Related terms (optional)

Keep explanations concise and context-focused.

---

## 4. Updating an Existing Term

If a term already exists:

* Do not overwrite it directly.
* Open an issue explaining:

  * What needs to change
  * Why
  * Proposed revision

After discussion and agreement:

* Update the file
* Change `status` if needed
* Update `last_reviewed`
* Document major changes in `docs/DECISIONS/`

---

## 5. Status Definitions

* **proposed** – Suggested but not yet reviewed.
* **under_discussion** – Being debated.
* **approved** – Official standard term.
* **deprecated** – No longer recommended.

Only approved terms should be used as official references.

---

## 6. Pull Request Guidelines

When submitting a pull request:

* Keep changes focused.
* Reference the related issue.
* Follow the glossary template strictly.
* Do not introduce undocumented terminology.

Pull requests that bypass the discussion process may be requested to open an issue first.

---

## 7. Respectful Communication

All discussions must remain:

* Respectful
* Linguistically justified
* Focused on clarity and usability
* Free from personal attacks

This is a collaborative, community-driven project.

---

## 8. Long-Term Contribution

As the project grows:

* Active contributors may become Reviewers.
* Review responsibilities are based on consistency and collaborative behavior.
* Governance changes follow `GOVERNANCE.md`.

---

Thank you for helping build a structured, scalable, and sustainable Luganda technical terminology standard.
