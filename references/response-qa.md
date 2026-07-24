# Response Quality Gate

Run this review before returning a response package or an audit.

## Completeness

- Every editor and reviewer item has a stable ID.
- Every item has a reply, cross-reference, or explicit unresolved flag.
- No reviewer concern is silently omitted or materially changed in paraphrase.
- Major and blocking items are visibly surfaced.

## Traceability and factuality

- Every claimed change maps to a supplied section, page/line, figure, table, supplement, or a visible placeholder.
- No data, p-values, effect sizes, sample sizes, citations, approvals, repositories, or locations were invented.
- All editorial requirements supplied by the user are addressed before reviewer items.
- Claimed new experiments or analyses are supported by author-provided details.

## Tone and scientific posture

- The response is professional, concise, and non-accusatory.
- Disagreement is narrow, evidence-led, and acknowledges the underlying concern.
- Limitations are stated plainly when evidence is incomplete.
- No reply relies mainly on time, cost, or convenience.

## Readiness label

- `ready_to_submit`: every claim and location is supplied and traceable.
- `draft_with_placeholders`: strong draft, but visible placeholders remain.
- `needs_author_input`: factual details are needed before credible drafting.
- `blocked`: compliance, integrity, central-evidence, or appeal-like concerns prevent normal completion.

Never assign `ready_to_submit` unless all other conditions are met.
