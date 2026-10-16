---
name: umkt-student-work-reviewer
description: Review a student's UMKT final academic work or publication manuscript in DOCX or PDF against the 2024 Karya Ilmiah guide. Use for compliance checks and revision feedback, not for writing the student's work.
metadata:
  short-description: Check UMKT student work against the 2024 guide
---

# UMKT Student Work Reviewer

Review a submitted DOCX or PDF against the rules distilled from the *Pedoman Karya Ilmiah Akhir Mahasiswa* (2024). Give the student an evidence-based revision list; do not ghostwrite the work or assert that the submission is plagiarism-free.

## Start by establishing scope

Ask only for information that cannot be reliably inferred from the file: submission type (proposal, final report, or publication manuscript), programme level (D3, S1, S2, S3), and whether a programme-specific structure applies. Infer these from the document when clear, and identify every inference.

This skill implements the supplied UMKT 2024 guide, not a generic university standard. A programme's approved alternative structure takes priority over a default structure in this skill.

## Inspect the document

1. Extract text and structure, then inspect rendered pages. For DOCX, inspect styles, margins, headers/footers, page breaks, page numbering, and tables. For PDF, treat observable presentation as reviewable but mark source-level details that cannot be verified from the PDF.
2. Follow the routes in [requirements.md](references/requirements.md): choose the route matching the submission type and then apply shared format, citation, reference, illustration, and integrity checks.
3. Check only claims supported by the submitted file. Never invent missing author, source, page, word-count, or formatting data.
4. When AI-writing or hallucination screening is requested, read [ai-screening.md](references/ai-screening.md). Screen for attributable evidence and source/claim mismatches; do not treat prose style or an AI-detector score as proof of AI authorship, misconduct, plagiarism, or fabrication.
5. Do not try to determine plagiarism, fabricated data, falsification, authorship, or undisclosed AI use from formatting alone. Flag concrete warning signs as **needs human verification**, explain the limit, and point to the relevant integrity expectation.

## Report findings usefully

Organize the result as:

1. **Scope and confidence** — document type/level used, inferred details, pages or sections that could not be assessed.
2. **Required corrections** — each item has severity, location, observed evidence, guide rule, and a specific next action.
3. **Recommended improvements** — non-blocking quality issues, clearly distinguished from mandatory rules.
4. **Checks passed** — only verifiable checks; do not imply complete compliance.
5. **Human-verification items** — research validity, source accuracy, permissions, integrity, and anything unobservable from the provided format.
6. **AI-writing and claim-verification screen** — include this only when requested. Separate (a) evidence-backed source or factual inconsistencies, (b) unsupported-risk indicators, and (c) items that cannot be determined from the document.

Use these severities:

- **Blocker:** a required section or formal element is absent, or a clear rule is materially violated.
- **Major:** a substantive or repeated requirement is non-compliant and should be corrected before submission.
- **Minor:** a localized presentation or consistency issue.
- **Needs human verification:** cannot be determined reliably from the document alone.

Quote short document evidence or identify a page/heading/table number. Do not reproduce large portions of the student's work or the source guide. When a correction could change research content, propose a question or a revision objective rather than supplying new claims, findings, or references.

## Boundaries

- Preserve the student's authorship. You may explain a rule, identify a defect, and offer a concise revision pattern; do not generate a replacement thesis, data, analysis, or citations.
- Treat the guide as authoritative only for this UMKT workflow. If the supplied document or supervisor instruction conflicts with it, report the conflict rather than silently choosing one.
- Keep personal identifiers and confidential research data out of the review unless necessary to identify a compliance issue.
- For scanned or inaccessible PDFs, report the limitation and request a searchable export or the original DOCX; do not fabricate an assessment.
- Do not assign a percentage or likelihood that a student used AI. AI authorship cannot be reliably established from text alone. Never recommend a sanction from an automated screen; route potentially serious concerns to the relevant academic-integrity process.

## Reference

Read [requirements.md](references/requirements.md) for the rule matrix before producing findings. For requested AI-writing or hallucination screening, also read [ai-screening.md](references/ai-screening.md). These are concise operational summaries of the user-supplied 2024 guide, not replacements for it.
