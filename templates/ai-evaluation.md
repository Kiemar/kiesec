# Template AI Council Evaluation

**Status:** Template. No model, agent, or benchmark result is claimed.

**Project purpose:** [Specific task the Council should improve]

**Evaluation dates:** [Dates] · **Model versions:** [Exact identifiers] · **Dataset version:** [Version]

## What I built

[Describe orchestration, inputs, agent roles, model calls, disagreement resolution, final output, and your original contribution. Distinguish multiple prompts to one model from genuinely different models. Link actual code or architecture only when it exists.]

## Evaluation question

[For example: Does a critic-and-revision workflow improve the correctness of short incident summaries compared with one model call using the same source evidence? Choose a narrow, measurable question.]

## Data and permissions

[Use synthetic, public, or explicitly approved data. Document dataset provenance, licensing, exclusions, redaction, and what is sent to external services. Keep real secrets and private employer information out of prompts and committed logs.]

## Baselines and experiment design

- Simple baseline: [One model call or deterministic workflow]
- Council configuration: [Roles, models, ordering, tools, termination rule]
- Shared conditions: [Same tasks, source evidence, budgets, and scoring rubric]
- Development set: [Tasks used to tune prompts]
- Held-out set: [Tasks not used to tune prompts]
- Repeats: [Number and rationale; account for nondeterministic outputs]
- Ground truth: [How it was established and reviewed]

## Measures

| Measure | Definition | How calculated | Limitation |
| --- | --- | --- | --- |
| Correctness | [Task-specific criterion] | [Scoring method] | [Limits] |
| Unsupported claims | [What counts] | [Count or rate with denominator] | [Limits] |
| Cost | [Currency and price date] | [Actual usage basis] | [Limits] |
| Latency | [Start/end definition] | [Median/range or raw timings] | [Limits] |
| Human review effort | [Observable effort] | [Method] | [Limits] |

## Results

[Report actual sample size, raw or aggregated results, failed cases, and uncertainty. Do not fill this section with planned improvements or hypothetical percentages.]

## Failure analysis

[Include at least one case where consensus was wrong or the Council added cost without improving the answer, if observed. Explain why multiple agents agreeing is not independent verification. Test whether untrusted source text can redirect the workflow and document the limits of any mitigations.]

## Reproduction

[Versions, sanitized configuration, prompt files, input examples, environment variables by name only, run instructions, evaluation code, and known sources of variation.]

## Conclusion

[State when the Council helped, when the simple baseline was preferable, and what remains unproven.]

## Sources and assistance

[Citations, code reuse, third-party frameworks, human review, and AI-generated code or text that you checked.]
