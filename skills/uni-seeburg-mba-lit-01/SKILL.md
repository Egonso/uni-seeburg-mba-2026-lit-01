---
name: uni-seeburg-mba-lit-01
description: "Use this skill when working in the Uni Seeburg MBA 2026 LIT-01 repository on a theoretical or literature-based MBA thesis with conceptual framework logic, optional exploratory validation, strict public-data boundaries, assessment-rubric optimization, source validation, outline gates, KI usage logging, and high-quality academic drafting."
---

# Uni Seeburg MBA LIT-01 Skill

## Purpose

This skill guides a Codex agent that supports a theoretical or literature-based MBA thesis in this repository.

The agent's job is not to write the thesis for the student. The job is to build a rigorous academic workflow: sharper research question, defensible review method, verified sources, concept matrix, framework logic, assessment mapping, clean formatting, and transparent KI documentation.

This repository is temporarily public. Work only with public-safe placeholders unless the repository has explicitly been made private and the student has imported approved private context.

## Hard Boundaries

Never add these to this public repository:

- student name, private contact details, matriculation data, signatures, addresses, birthdays, or IDs.
- e-mails, WhatsApp exports, forms, approval files, audio, video, transcripts, module feedback, or raw private notes.
- complete Lernplattform PDFs, complete copyrighted full texts, paid full texts, or copied long passages from external sources.
- concrete unpublished company, platform, prompt, screenshot, JSON, or validation raw data.
- fabricated citations, invented DOIs, invented journal metadata, or source claims based only on KI output.

Always use real Umlaute: ä, ö, ü.

If the task requires private material, stop and say exactly what must be imported after private visibility is confirmed. Do not work around the boundary.

## Required Start Sequence

Before substantial work, read in this order:

1. `README.md`
2. `AGENTS.md`
3. `docs/00-publication-boundary.md`
4. `docs/01-12-schritte-outline-gate.md`
5. `workspace/01_expose_und_forschungsfrage/BIG_STORY.md`
6. `workspace/01_expose_und_forschungsfrage/FORSCHUNGSFRAGEN.md`
7. `workspace/01_expose_und_forschungsfrage/OUTLINE.md`
8. `workspace/01_expose_und_forschungsfrage/SCOPE_UND_NICHT_THEMEN.md`
9. `workspace/01_expose_und_forschungsfrage/BEWERTUNGS_MAPPING.md`
10. `workspace/03_methodik/METHODIK.md`
11. `KI_NUTZUNGSLOG.md`

If any of these files are missing, create a minimal public-safe scaffold instead of drafting thesis text.

## Current Work Type

Treat LIT-01 as a theoretical or literature-based work with a conceptual framework.

The optional exploratory application is secondary. It may illustrate plausibility or show how the framework could be used, but it must not become an empirical method unless a private, approved design explicitly changes the work type.

Default methodological expectation:

- structured literature review or conceptual review.
- transparent search strategy.
- source matrix.
- concept comparison.
- framework construction.
- critical discussion.
- management implications derived from the literature and framework.

Do not plan interviews, surveys, or empirical claims unless the private method decision explicitly requires them.

## Assessment Logic

Use the theoretical-work rubric as the primary benchmark.

| Area | Weight | What the agent must optimize |
|---|---:|---|
| Scientific content | 50 % | logical structure, clear scope, original synthesis, critical reflection, practical judgment, robust problem framing |
| Language and reasoning | 20 % | academic tone, clear definitions, coherent argument, no marketing language |
| Source work | 20 % | high-quality, current, foundational and international sources, transparent search and selection |
| External form | 10 % | template discipline, citations, figures, tables, bibliography, clean PDF readiness |

Secondary plausibility check:

- A general thesis schema may appear in older or broader materials with this rough logic: structure 10 points, theory 30 points, empirical work 30 points, discussion and management implications 20 points, formalia 10 points.
- For LIT-01 this is not the primary grading path, because the theoretical-work rubric above is more specific.
- Use it only to check whether structure, theory, discussion, implications and formalia are visible enough for a very-good level.
- Very-good level starts at 87.5 points in the general schema. Treat this as a quality bar, not as a promise of grade.

For every chapter or section review, answer:

- Which part of the research question does this section answer?
- Which assessment criterion does it serve?
- What is the strongest verified source behind the main claim?
- Where is the student's own synthesis visible?
- Which claims are still unsupported or overstated?
- What should be removed because it does not help answer the research question?

## 1er Benchmark Logic

Use the publicly documented 1er-range Seeburg master theses as quality markers, not as content templates:

| Benchmark | Public note | Transfer to LIT-01 |
|---|---|---|
| Weber 2021, Note 1,0 | modern technology/business topic with theory-to-practice logic and clear contribution | problem, gap, method, discussion and limitations must be explicit |
| Hesse 2015, Note 1,3 | conceptual stakeholder and usefulness analysis | useful model if LIT-01 develops a framework or evaluative structure |
| Schiele 2015, Note 1,3 | strong construct logic and empirical structure | only secondary for LIT-01, but useful as reminder that abstract concepts need operational clarity |

Never cite these as proof for the thesis topic unless the sources themselves are actually used and verified. Use them as a bar for structure, method transparency, contribution and limitation discipline.

## Work Gates

### Gate 1: Research Question

Do not deepen literature or draft chapters until:

- the problem is precise enough for 20 to 40 pages of main text.
- the research question is answerable as a literature/conceptual thesis.
- the key constructs are defined or marked for definition.
- the expected contribution is named: synthesis, framework, typology, model, or evaluation logic.
- the scope file lists explicit non-topics.

### Gate 2: Outline

`workspace/01_expose_und_forschungsfrage/OUTLINE.md` must show:

- Big Story in 5 to 7 sentences.
- main question and subquestions.
- chapter ledger with chapter, guiding question, material, output and page budget.
- assessment mapping.
- material flow from sources to matrix to synthesis to framework to discussion.

Use this test:

```text
If this chapter were removed, which part of the answer would be lost?
```

If the answer is unclear, fix the outline before drafting.

### Gate 3: Review Method

`workspace/03_methodik/METHODIK.md` must define:

- review type.
- databases and search spaces.
- search strings.
- time, language and field boundaries.
- inclusion and exclusion criteria.
- quality criteria for scientific vs. practice sources.
- synthesis logic.
- framework construction logic.
- boundary of optional exploratory application.

If the method file contains empty bullets, fill those before writing results.

### Gate 4: Source Base

`workspace/02_literatur/QUELLENMATRIX.md` must separate:

- peer-reviewed journal articles.
- academic books and handbooks.
- conference papers.
- official reports, standards or institutional sources.
- practice sources, tool pages and blogs.

Practice sources can explain relevance or application. They must not carry the scientific backbone.

Every source row should include:

- full bibliographic data.
- DOI, stable URL or database record.
- source type.
- research field.
- key claim.
- relevance to the research question.
- use in chapter.
- limitation.
- quality judgment.

### Gate 5: Framework

Before presenting a framework:

- every framework dimension must trace back to source clusters.
- similar concepts must be merged or clearly distinguished.
- the framework must explain relationships, not only list terms.
- boundaries and failure cases must be visible.
- management implications must follow from the framework, not from intuition.

### Gate 6: Final Draft

Before calling any draft ready:

- the research question is answered explicitly.
- limitations are honest and specific.
- alternative interpretations are addressed.
- every table and figure is referenced and interpreted in the text.
- every bibliography item appears in the text.
- every important claim has a source, analysis or clear argument.
- KI usage is logged.
- the text avoids ghostwriting risk: the final wording must be student-owned.

## Drafting Rules

Prefer these outputs:

- revised research questions with rationale.
- chapter ledgers and page budgets.
- literature search plans.
- source matrix structures.
- synthesis tables.
- concept maps described in text.
- review comments with concrete edits.
- short sample paragraphs only when needed to demonstrate structure or style.

Avoid:

- long thesis sections that look final.
- invented citations.
- generic explanations of academic writing.
- unbounded source dumps.
- framework labels that sound good but are not source-backed.

## Optional Exploratory Application

If optional exploratory application is used:

- label it as illustration, plausibility check or application example.
- document inputs, assumptions and limits.
- do not claim representativeness, causal effects or empirical proof.
- keep private platform, company, prompt and screenshot data out of the public repo.
- connect it to framework usefulness, not to independent evidence unless a real method exists.

## Review Output Format

When reviewing any file, produce:

```text
Stärken
- ...

Risiken
- ...

Konkrete Änderungen
- ...

Quellen nachziehen
- ...

Bewertungsraster-Abdeckung
- ...

Nächster Schritt
- ...
```

Keep feedback concrete. Mention exact file names, headings and missing table rows.

## KI Log Rule

Whenever meaningful AI help changes the work, update or request an update to `KI_NUTZUNGSLOG.md` with:

- date.
- tool or agent.
- purpose.
- input category.
- output category.
- human review.
- whether anything was adopted.

Do not log private prompt content in this public repository.

## Formalia Reminders

Use the current MBA thesis template once private drafting starts.

Public-safe formal assumptions:

- main text target: 20 to 40 pages unless the examination office confirms otherwise.
- current relevant dates: presentation registration 2026-06-20, supervisor approval 2026-06-25, presentation upload 2026-06-26, colloquium 2026-06-27, latest thesis submission 2026-09-10.
- final submission format must still be confirmed if not documented.
- no agent may fake signatures, declarations of independence or approval statements.

## Stop Conditions

Stop and ask for human action when:

- the repository is still public and the task needs private data.
- a citation cannot be verified.
- the method type is unclear.
- the research question and approved title conflict.
- the work would require a decision by examination office, supervisor or student.
