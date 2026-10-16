# UMKT Student Work Reviewer

An agent-agnostic skill for reviewing student academic work in DOCX or PDF against the 2024 *Pedoman Karya Ilmiah Akhir Mahasiswa* from Universitas Muhammadiyah Kalimantan Timur (UMKT).

It helps an AI agent identify document-structure, layout, citation, references, table/figure, language, and academic-integrity review items. On request, it also performs evidence-based AI-writing and hallucination-risk screening: citation metadata, claim-to-source support, internal consistency, and research traceability. It does **not** write the student's thesis, certify originality, determine plagiarism, or prove AI authorship.

## Install

Copy the `umkt-student-work-reviewer` folder into the skills directory used by your agent platform. A compatible skill loader should load `SKILL.md` when the task is to review a UMKT student proposal, final report, thesis, dissertation, or publication manuscript.

The skill itself requires no vendor-specific API, runtime, or model. The host agent needs a way to read DOCX and PDF files and, ideally, render them for visual-format inspection.

## Use

Give the agent the student document and ask for a review. State the submission type and programme level when known.

Example:

```text
Use the UMKT Student Work Reviewer skill to review this DOCX as an S1 skripsi.
List blockers, major issues, minor issues, and items that need human verification.
Do not rewrite the student's research content.
```

For the optional screen:

```text
Also screen for unverifiable citations, citations that do not support their claims,
and internal factual inconsistencies. Do not estimate whether AI wrote the document;
report only evidence-backed findings and items needing human verification.
```

The review should report its assumptions, cite document locations, distinguish rules from recommendations, and explain what it cannot verify from the file.

## Updating the guide

The rules are a concise operational summary in `references/requirements.md`. When UMKT publishes a revised guide, update that summary from the new authoritative document, keep the change scoped to the altered rules, and state the guide edition used in any review.

## Source and scope

This repository does not include the supplied source PDF. It summarizes rules from the 2024 UMKT guide for operational checking and is not an official UMKT publication. Programme-specific approved rules and supervisor instructions may take precedence; the skill directs the reviewer to report conflicts rather than silently override them.
