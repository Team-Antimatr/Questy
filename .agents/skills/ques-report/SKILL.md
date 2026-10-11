---
name: ques-report
description: Convert research and analysis into clear, traceable, decision-ready reports tailored to the intended audience. Invoke with /Ques-report.
---

# Ques-Report

## Mission
Communicate research findings so that a reader can understand the question, evaluate the evidence, see the implications, and decide what to do next.

## Invocation and instruction priority
When invoked through `/Ques-report`, follow the user's requested audience, length, format, and purpose. Respect higher-priority system, platform, safety, privacy, and tool-use rules. Do not invent missing findings to make a report feel complete.

## Reporting procedure
1. **Define the decision context.** Identify the intended reader, purpose, scope, and decision the report should support.
2. **Audit the inputs.** Separate sourced findings from assumptions, estimates, interpretation, and recommendations. Identify missing or contradictory evidence.
3. **Choose the report architecture.** Use only sections that serve the audience and decision.
4. **Lead with the result.** State the main finding and its practical significance before extended detail.
5. **Build a traceable argument.** Connect each important conclusion to evidence, reasoning summaries, and limitations.
6. **Include alternatives and counter-evidence.** Explain the strongest relevant objections or competing options.
7. **Make recommendations actionable.** Identify next steps, owners or roles where known, dependencies, risks, and measures of success.
8. **Quality-check.** Verify numbers, dates, terminology, citations, consistency, and whether the report answers the original question.

## Default report outline
Adapt as needed:
1. Title, date, and scope
2. Executive summary
3. Research question and method
4. Key findings
5. Evidence and analysis
6. Alternatives, risks, and counter-evidence
7. Conclusions and recommendations
8. Limitations and unanswered questions
9. Sources and appendices

## Quality rules
- Match depth to importance; do not inflate a short answer into a long report.
- Make the difference between evidence and interpretation visible.
- Include dates for time-sensitive findings.
- Explain technical terms for the intended audience.
- Use tables for comparisons and prose for reasoning and context.
- Use charts only when the data supports a meaningful visual comparison; label units, periods, and sources.
- Never conceal a material limitation or manufacture certainty.
- Make recommendations proportionate to the strength of the evidence.

## Shared Questy voice
Use professional, measured analytical narration. Progress from context to findings, implications, and next actions. Be direct without being abrupt and detailed without being repetitive. Prefer concrete claims and calibrated conclusions over rhetorical language.

## Handoff to other Questy skills
Use `Ques-source` to verify claims and citations, `Ques-struct` to organize complex findings, `Ques-framework` to clarify evaluation criteria, and `Ques-network` when relationships are central. Use `Ques-research` if important evidence is missing. Apply `Ques-guidelines` throughout. Do not claim another skill was invoked unless it actually was.
