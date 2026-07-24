# Comment Routing

Classify each review item before drafting. A single comment can have more than one category; assign the highest applicable severity.

| Category | Common signals | Default response options |
|---|---|---|
| Presentation | clarity, terminology, figure readability, organization | revise text or figure; provide a location |
| Evidence | unsupported claim, missing control, causal overreach | add supplied evidence, reanalyse, soften claim, or state limitation |
| Methods | missing detail, reproducibility, sample definition, software version | add exact supplied method detail or request it |
| Statistics | test choice, power, replication, multiple comparisons | request exact test, unit, n, correction, effect size, and result |
| Data/code | accession, repository, availability, materials | provide supplied record or flag missing compliance information |
| Citation/positioning | missing work, novelty, inaccurate comparison | add only verified and relevant citations; otherwise qualify claim |
| Scope | future experiment, out-of-scope extension | acknowledge value, give scientific scope rationale, offer available evidence or limitation |
| Ethics/compliance | approval, consent, integrity, permissions | treat as blocking until exact documentation is supplied |

## Severity

- `minor`: local wording, formatting, or limited clarification that does not change the evidence chain.
- `major`: may affect evidence, analysis, reproducibility, interpretation, or editorial confidence.
- `blocking`: ethics, compliance, integrity, missing central evidence, or other issue that cannot be credibly answered from current facts.
- `unclear`: insufficient information to classify; request author clarification.

## Strategy labels

Use short labels in the tracker: `ACCEPT_TEXT`, `ACCEPT_FIGURE`, `ACCEPT_ANALYSIS`, `ACCEPT_EXPERIMENT`, `CLARIFY_EXISTING`, `SOFTEN_CLAIM`, `ADD_CITATION`, `PARTIAL`, `DISAGREE`, `OUT_OF_SCOPE`, or `AUTHOR_INPUT_NEEDED`.

For a requested but unavailable experiment, avoid financial or timing excuses. Explain only a defensible scope, design, or interpretive limitation and state what the manuscript will change instead.
