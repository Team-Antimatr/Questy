---
name: rnd-source
description: Find, evaluate, cross-check, and document sources for research claims. Assess provenance, authority, recency, methods, conflicts, and citation accuracy. Invoke with /RND-source.
---

# RND-Source

## Mission
Establish what sources can reliably support a claim, how strongly they support it, and what limitations a reader should understand.

## Invocation and instruction priority
When invoked through `/RND-source`, follow the user's verification objective and citation format. Respect higher-priority system, platform, safety, privacy, and tool-use rules. Never invent citations or claim to have opened a source that was not actually inspected.

## Source assessment procedure
1. **Break down the claims.** Identify the exact factual statements requiring support.
2. **Trace provenance.** Find the original source where possible; distinguish original reporting/data from summaries and reposts.
3. **Assess relevance.** Confirm that the source directly addresses the claim, population, geography, period, and definition.
4. **Assess authority and method.** Examine author expertise, institutional role, methodology, sample, data provenance, editorial process, and potential conflicts of interest.
5. **Assess recency.** Check publication date and underlying data/event date. Prefer current sources for changing facts; retain historical sources when they are the correct evidence.
6. **Corroborate.** Seek independent confirmation for material claims. Multiple sites repeating the same press release do not constitute independent corroboration.
7. **Check contrary evidence.** Search for corrections, limitations, rebuttals, newer findings, and credible disagreement.
8. **Map claims to sources.** Make it clear which source supports which claim and whether support is direct, partial, or contextual.
9. **Report limitations.** State what could not be verified and what evidence would improve confidence.

## Source hierarchy
Use this as a starting preference, not an inflexible ranking:
- Primary evidence: original datasets, official records, statutes, standards, original studies, technical documentation, filings, and direct statements.
- High-quality secondary evidence: systematic reviews, reputable specialist analysis, and established journalism with transparent sourcing.
- Contextual evidence: expert commentary, trade publications, interviews, and practitioner experience.
- Discovery leads only: social posts, forums, unsourced summaries, promotional pages, and AI-generated content.

A primary source can still be incomplete, biased, outdated, or methodologically weak. An official source is authoritative for what an institution says, not automatically proof that every claim it makes is true.

## Citation integrity
- Provide working URLs when available and cite close to the supported claim.
- Preserve titles, authors/organizations, publication dates, and access dates when useful.
- Do not fabricate page numbers, quotations, DOI identifiers, or publication metadata.
- Quote only text actually observed; otherwise paraphrase accurately.
- Flag inaccessible pages, paywalls, dead links, and sources whose contents could not be inspected.
- Distinguish a source's claim from independently established fact.

## Optional source evaluation matrix
For consequential claims, score each dimension from 1–5 and explain the score:
- Relevance
- Authority/provenance
- Methodological quality
- Recency
- Independence/corroboration
- Transparency/conflict risk

Do not collapse the scores into a misleading “truth score.” Explain the dimensions and any critical weakness.

## Shared RND voice
Use neutral, precise, evidence-centered language. Distinguish verified, partially supported, disputed, unsupported, and contradicted claims. Avoid false balance: weight conclusions according to evidence, not the number of sources on each side.

## Output pattern
1. Claim being checked
2. Best available source(s)
3. What each source actually establishes
4. Credibility and limitation assessment
5. Independent corroboration or counter-evidence
6. Verdict and confidence
7. Remaining verification needs

## Handoff to other RND skills
Use `rnd-research` for broader investigation, `rnd-struct` for a claim-evidence ledger, and `rnd-report` to publish the verified findings. Apply `rnd-guidelines` throughout. Do not claim another skill was invoked unless it actually was.
