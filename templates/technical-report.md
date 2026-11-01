# Template Security Assessment Report

**Status:** Template. No assessment or findings are asserted.

**Author:** [Name] · **Environment:** [Lab or authorized scope] · **Report version:** [Version]

**Testing dates:** [Actual dates and timezone] · **Report date:** [Date]

## Executive summary

[Write for a manager. Explain the assessed function, the most important supported risks, likely operational consequences, recommended priorities, and major coverage limits. Avoid a tool inventory or unexplained jargon. If no significant finding was confirmed, report that accurately without equating it with proof of security.]

## Technical summary

[Write for the engineer or security analyst. Summarize architecture, tested trust boundaries, validated weaknesses, affected configurations, and the main repair and verification approach. Separate confirmed findings from suspected issues.]

## Scope and authorization

- Objective: [Specific assessment question]
- In scope: [Exact lab assets, application functions, identities, and boundaries]
- Out of scope: [Explicit exclusions]
- Authorization: [Lab ownership or documented permission; publish only a sanitized description]
- Constraints: [Time, access, unavailable logs, rate limits, test restrictions]
- Dates and point-in-time limits: [Relevant dates and change conditions]

## Environment and methodology

[Describe topology, data flow, versions, identities, initial access level, and how the lab was isolated. Explain which test methodology or requirements informed the assessment and cite the exact edition or version.]

| Test objective | Method and reason | Evidence ID | Result | Coverage limitation |
| --- | --- | --- | --- | --- |
| [Testable question] | [What and why] | [ID] | [Confirmed / not observed / inconclusive / not tested] | [Limits] |

## Findings summary

| ID | Finding | Affected component | Severity and basis | Remediation priority | Retest status |
| --- | --- | --- | --- | --- | --- |
| [F-001] | [Specific condition] | [Asset/function] | [Reasoned assessment] | [Priority] | [Not tested / failed / passed with limits] |

If no finding was confirmed, remove the example row and state that clearly.

## Detailed findings

Repeat the [finding template](finding.md) for each supported finding. In a completed report stored elsewhere, adjust this relative link or embed the template content.

Each finding must connect **observation → cause → consequence → repair → retest**. Keep observed facts separate from possible downstream effects.

## Defensive visibility

[Which actions appeared in application, host, identity, or network logs? What could a defender detect, using which fields and context? Explain blind spots, false positives, and whether a suggested detection was actually tested.]

## Remediation plan

| Finding | Recommended action | Dependency or operational impact | Proposed owner role | Verification criterion |
| --- | --- | --- | --- | --- |
| [ID] | [Specific fix] | [Constraint] | [Role, not an invented assignment] | [Observable pass condition] |

## Retest results

[Record date, fixed build/configuration, same test conditions, new evidence IDs, residual issues, and what could not be retested. A patch installation screenshot alone is not a functional retest.]

## Limitations and unresolved questions

[Document incomplete access, missing telemetry, untested paths, uncertain severity inputs, and alternative explanations. Explain how they constrain conclusions.]

## Evidence handling

[Reference the evidence register. State how originals and sanitized public derivatives were separated, how integrity was checked, and what timestamps mean. Do not publish private evidence paths or confidential records.]

## Sources and assistance

[Use primary documentation where possible. Identify provided lab steps, walkthroughs, human help, code reuse, and AI assistance. Explain which conclusions and results you personally verified.]

## Lessons and next assessment

[What did evidence change in your understanding? What would you test next, and why?]
