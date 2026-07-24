---
name: review-response
description: Draft, audit, or revise rigorous point-by-point responses to journal editor and peer-review comments, revision cover letters, and manuscript-change trackers. Use for reviewer comments, editor decision letters, rebuttal letters, response-to-reviewers drafts, revision correspondence, and Chinese requests such as "审稿意见回复", "逐点回复", "返修", "修回信", or "rebuttal".
---

# Review Response

## Purpose

Turn supplied editor instructions, reviewer comments, manuscript facts, and author notes into a professional, traceable response package. This skill is journal-agnostic: it does not assume a specific publisher's policies or templates.

The governing rule is evidence before prose. Never invent experiments, analyses, citations, line numbers, figures, tables, supplements, approvals, or manuscript changes. Mark absent facts as `AUTHOR_INPUT_NEEDED`.

## Workflow

### 1. Establish scope and readiness

Identify the requested mode:

- `draft`: create a new response package.
- `audit`: inspect an existing rebuttal for omissions, unsupported claims, tone, and traceability.
- `revise`: improve a prior draft using new author facts.
- `triage`: classify comments and produce a work plan without drafting final prose.
- `cover-letter`: draft only the editor-facing revision summary.
- `appeal-like`: flag for deliberate handling; do not treat it as an ordinary revision.

Extract or ask for the journal, decision type, editor instructions, reviewer boundaries, manuscript title/ID, and any submission deadline. If the source does not clearly separate reviewers or comments, preserve the ambiguity rather than guessing.

### 2. Parse before writing

Give editor instructions IDs such as `E.1`, then give reviewer comments stable IDs such as `R1.1`, `R1.2`, and `R2.1`. Preserve each comment's meaning. Build a compact tracker before drafting.

Load [references/comment-routing.md](references/comment-routing.md) when classifying comments or selecting a response strategy.

### 3. Draft evidence-linked replies

For each item:

1. Acknowledge the substantive concern.
2. State the action taken, supplied evidence, or a careful limitation.
3. Map claimed changes to a supplied manuscript location; use a visible placeholder when unavailable.
4. When disagreeing or declining a request, explain the scientific or scope-based reason narrowly and respectfully.

Use this default structure:

```text
Comment R1.2
[Preserved reviewer comment]

Response
Thank you for raising this important point. [Evidence-based answer.] We have
[specific supplied action] in [section/figure/location or PLACEHOLDER].
[If needed: We also clarify this limitation in PLACEHOLDER.]
```

Do not claim that an experiment, analysis, textual change, or literature search was completed unless the user provided it. Do not use time, cost, or convenience as the main reason to decline an experiment.

### 4. Package the result

Unless the user requests another format, return:

```text
Response strategy summary
- Decision type:
- Overall posture:
- Major risks:

Comment-response tracker
| ID | Concern | Type | Severity | Proposed action | Missing input |
|---|---|---|---|---|---|

Draft point-by-point response

Manuscript change checklist

Missing information / risk flags

Package readiness: ready_to_submit | draft_with_placeholders |
needs_author_input | blocked
```

For a cover letter, keep the focus on manuscript identity, appreciation, the main completed revisions, and the attached point-by-point response. Do not use it to duplicate every reply.

### 5. Perform a final quality gate

Load [references/response-qa.md](references/response-qa.md) before returning a final package or audit. Never label a package `ready_to_submit` while visible placeholders, unverified factual claims, or unresolved major concerns remain.

## Tone

Be concise, calm, and editor-readable. Thank reviewers for useful points without padding every response. A disagreement should first recognize the concern, then state the evidence or study-scope rationale. Avoid accusations, defensive language, and excessive apology.

## Language

Mirror the user's requested language. When author notes are Chinese but the submission response must be English, use the Chinese notes only as factual input and produce formal academic English. Flag any ambiguous translation that could change a scientific claim.

## Boundaries

- Use current journal instructions and the editor letter as the controlling source when they are supplied.
- For journal policy details that may change, verify the relevant official journal page before advising on submission requirements.
- For statistical, ethics, data-integrity, or compliance concerns, request exact facts rather than drafting around the gap.
- Do not write an appeal as a default response to an adverse decision; identify it as `appeal-like` and explain what evidence is needed.
