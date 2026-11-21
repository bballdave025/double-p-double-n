# Context Documents

This directory contains **continuation-ready context documents** (Lab
Notebook / LN files) for the **Paper–Pencil Neural Networks (PPNN)** project.

These are **not** polished documentation. They are:

- structured snapshots of project state,
- continuation-ready checkpoints,
- architecture and design records,
- "lab notebook" entries for engineering progress.

---

# Purpose

Each document is designed to answer:

> **If I had to resume this work in a fresh environment, what would I
> need to know?**

They preserve:

- current architecture and physical laminated components
- terminology and mathematical notation
- naming decisions
- design constraints and canonical visual symbols
- implementation status
- next-step execution plans
- important non-obvious insights
- active questions

Think of these as **checkpoint files for thinking**, not summaries.

---

# Documentation Hierarchy

```text
README.md
    ↓
Project Charter (if present)
    ↓
Lab Notebook / Context Documents
    ↓
Experiment Notes
```

Each layer answers a different question. This hierarchy describes the
documentation's roles; it does not assert that all listed files already exist.

---

# Context Document Header Template

Use **double-brace placeholders** (`{{...}}`) rather than angle brackets.

```text
*BEGIN: Context Document Header*

# CONTEXT DOCUMENT — Continuation

## Project

**Name:**
Paper–Pencil Neural Networks (PPNN)

**Description:**
A physical, hand-computable neural-network learning system using laminated,
reusable diagrams and writable spaces for inputs, weights, biases, neuron
calculations, predictions, residuals, losses, and costs.

---

## Continuation Metadata

**Prepared at:**
{{ssssssssss_YYYY-mm-ddTHH:MM:SS±ZZZZ}}

Generated via:

date +'%s_%Y-%m-%dT%H:%M:%S%z'

(Use the author's current local time zone; record the numeric UTC offset.
Do not assume Boston or any other fixed location.)

**Continued from chat:**
{{Exact chat title}}

**Also involving:**
- {{Related topic}}
- {{Related topic}}
- *(or: no other subjects specified)*

---

## Author / Source

**User (GitHub):**
@bballdave025

**User (ChatGPT):**
{{optional}}

---

## Intent for This Context

{{1–2 sentences describing what this continuation should enable}}

---

## Usage Instructions

- Treat this document as **authoritative project state**.
- Continue with **minimal re-derivation**.
- Reinterpret only when explicitly requested.
- Distinguish verified original artifacts from proposed diagrams or
  unconfirmed interpretations.

*ENDOF: Context Document Header*
```

---

# Pre-Context-Document Prompt (PCDP)

Before pasting a context document into a fresh chat, you may send a
short PCDP to establish context and immediate goals.

```text
## Current Work

Project:
Paper–Pencil Neural Networks (PPNN)

Starting with:
- {{Step}}
- {{Step}}
- {{Step}}

---

## Upcoming Context Document

The next message will be a CONTEXT DOCUMENT for:

Paper–Pencil Neural Networks (PPNN)

This continues discussion begun in:

"{{Previous chat title}}"

---

## Timing

Preparation:
{{YYYY-MM-DDTHH:MM:SS±ZZ:ZZ}}

(Optional) New chat:
{{YYYY-MM-DDTHH:MM:SS±ZZ:ZZ}}

---

## Instructions for Next Message

Instructions
- Do not summarize.
- Do not reformat.
- Do not analyze.
- Do not critique.
- Do not extract bullet points.
- Do not optimize language.
- Treat the context document as authoritative state.
- Your response should only:
  1. Confirm receipt.
  2. Confirm readiness to continue.

---

## Immediate Focus

Help me:

{{Concrete, task-oriented, ADHD-friendly next task}}

*End of PCDP*
```

---

## Practical Note

In normal use, the **Instructions for Next Message** section is often
**omitted for the chat creating the context document**. Including it
sometimes causes the model to interpret the transferred context as
operational instructions rather than information to pass on. Giving
those directions to the **new** chat can reduce confusion and help
preserve cognitive momentum.

Typical workflow:

```text
PCDP (optional)
      ↓
Context Document (authoritative)
      ↓
Continue work
      ↓
Update / create new LN document before stopping
```

---

# Naming Convention

```text
LN_ppnn_YYYY-MM-DD_{{optional-tag}}_-_{{short-slug}}.md
```

Examples (illustrative filenames, not claims that these files exist):

```text
LN_ppnn_2026-11-20_ctx01_-_visual-symbols-and-laminated-parts.md
LN_ppnn_2026-11-20_parked_-_xor-network-layout.md
```

`LN` = Lab Notebook, the author's longstanding term for these files.

The optional tag is usually omitted unless it adds useful context.
Examples:

- ctx01
- parked
- submitted-addenda
- pr-for-review

When in doubt, omit the optional tag.

Choose the slug to describe the primary engineering topic rather than
a minor implementation detail.

---

# What Belongs in a Context Document?

A context document should capture the project's **current engineering
state**, not merely what changed.

Typical sections include:

- Current architecture and network-part variants
- Original notebooks, photographs, and laminated artifacts (with provenance)
- Canonical visual vocabulary and SVG status
- Mathematical notation, including layer indices and conventions
- Major modules and responsibilities
- Recent implementation work
- Current design rationale
- Constraints and assumptions
- Confirmed decisions versus tentative ideas
- Active questions
- Immediate next steps

When useful, include small code snippets, directory layouts, Drive links,
GitHub paths, or command examples that reduce future re-derivation.
Do not treat an unverified file match or proposed diagram as confirmed.

---

# Scope

These documents are intended to bridge work across:

- multiple ChatGPT conversations,
- multiple development sessions,
- different machines,
- and interruptions lasting days or months.

They are written primarily for the future maintainer of the project,
which is usually the author.

---

# Retrieval Tip

1. Sort by filename.
2. Open the newest relevant `LN_*` document.
3. Resume from **Immediate Next Steps** (or equivalent).

---

*End of README*
