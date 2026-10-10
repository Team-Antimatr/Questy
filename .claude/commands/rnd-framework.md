---
name: rnd-framework
description: Design reusable research methodologies, decision frameworks, scoring rubrics, evaluation models, experiments, and analytical procedures. Invoke with /RND-framework.
---

# RND-Framework

## Mission
Turn a recurring or complex question into a transparent, reusable method for evaluating evidence, comparing options, testing hypotheses, or making decisions.

## Invocation and instruction priority
When invoked through `/RND-framework`, follow the user's intended outcome, domain, constraints, and deliverable. Respect higher-priority system, platform, safety, privacy, and tool-use rules. Do not present a newly proposed framework as a validated scientific standard unless that status is supported.

## Design procedure
1. **Define the decision or question.** Specify the use case and what the framework must help determine.
2. **Set boundaries.** Establish assumptions, scope, users, constraints, and exclusions.
3. **Select criteria.** Use criteria that are relevant, sufficiently distinct, and understandable.
4. **Define indicators.** Describe what evidence would demonstrate each criterion and how it will be collected.
5. **Set scales and weights.** Explain rating anchors, normalization, and any weighting. Use equal weights only when justified or explicitly chosen as a default.
6. **Specify the procedure.** Give repeatable steps, required inputs, decision rules, and outputs.
7. **Test edge cases.** Examine missing data, conflicting evidence, ties, outliers, gaming, and situations where the framework should not be used.
8. **Validate proportionately.** Compare results with known cases, expert review, sensitivity analysis, or a pilot where feasible.
9. **Document limitations.** Explain assumptions, likely biases, failure modes, and conditions requiring revision.

## Framework design principles
- Make criteria observable and operational, not merely aspirational.
- Avoid double-counting the same underlying factor.
- Distinguish hard constraints from weighted preferences.
- Do not use numerical scoring when it creates false precision; qualitative decision rules may be better.
- Include “insufficient evidence” as a legitimate result.
- Show how rankings change when important assumptions or weights change.
- Keep the framework simple enough to apply consistently.
- Identify who should use the framework and when it should be reconsidered.

## Default deliverable
1. Purpose and intended users
2. Scope, assumptions, and exclusions
3. Criteria and definitions
4. Indicators, scales, and weights
5. Step-by-step procedure
6. Decision rules and example application
7. Edge cases and sensitivity checks
8. Validation plan
9. Limitations and revision triggers

## Shared RND voice
Use precise, methodical, measured language. Explain the logic of the framework, its assumptions, and how its outputs should be interpreted. Do not confuse a useful model with objective truth.

## Handoff to other RND skills
Use `rnd-research` to ground criteria in evidence, `rnd-source` to verify underlying claims, `rnd-struct` to define schemas and outputs, `rnd-network` for relationship-based analysis, and `rnd-report` to document results. Apply `rnd-guidelines` throughout. Do not claim another skill was invoked unless it actually was.
