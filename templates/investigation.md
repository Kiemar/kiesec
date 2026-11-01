# Template Incident Reconstruction

**Status:** Template. No real incident or actor attribution is asserted.

**Case context:** [Synthetic lab / public dataset / authorized incident]

**Question:** [What happened, to which assets, during what period?]

**Analyst:** [Name] · **Analysis dates:** [Dates] · **Timezone convention:** [For example UTC]

## Executive summary

[Explain the supported sequence, affected scope, confidence, recommended containment or recovery actions, and major unknowns. Do not claim an actor identity from an IP address, tool name, language, or infrastructure overlap alone.]

## Evidence sources and integrity

[Record source systems, collection method, time range, clock offsets, retention gaps, and whether you have original evidence or a public dataset. Use the evidence-register CSV to track item IDs, hashes, and sanitized derivatives. A hash supports integrity comparison; it does not by itself prove provenance or legal admissibility.]

## Timeline

| Normalized timestamp | Original timestamp and timezone | Source and evidence ID | Observed event | Interpretation | Confidence and basis |
| --- | --- | --- | --- | --- | --- |
| [ISO 8601] | [As recorded] | [Log/artifact plus ID] | [Fact] | [Inference, if any] | [High/medium/low and why] |

Preserve the original timestamp when converting timezones. State uncertainty if clocks or timestamp semantics differ.

## Hypotheses and competing explanations

| Hypothesis | Supporting evidence | Contradicting or missing evidence | Competing explanation | Next discriminating check |
| --- | --- | --- | --- | --- |
| [Claim being tested] | [IDs] | [IDs or gaps] | [Plausible alternative] | [Check that could change the conclusion] |

## Intrusion reconstruction

[Explain initial access if known, execution, identity use, affected hosts, lateral activity, and any observed collection or transfer. Leave stages marked unknown when evidence does not establish them. Map behavior to a cited ATT&CK version or accessed date when useful; the mapping does not prove attribution.]

## Indicators and detection

| Indicator or behavior | Source | Validity period | Context | False-positive or attribution limits | Tested detection |
| --- | --- | --- | --- | --- | --- |
| [Sanitized value] | [ID] | [Dates] | [Why relevant] | [Limits] | [Result or not tested] |

## Containment and recovery recommendations

[Separate actions performed in the lab from recommendations. Include operational dependencies and evidence-preservation considerations.]

## What remains unknown

[Explain missing data, uncertain boundaries, identity uncertainty, and what evidence would be necessary to improve confidence. Reconstruct activity without implying you identified the human responsible.]

## Sources and assistance

[Dataset provenance, primary references, tools and versions, collaborators, walkthroughs, and AI assistance.]
