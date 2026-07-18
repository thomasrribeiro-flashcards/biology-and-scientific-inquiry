# Full-deck cold-start audit

cold_start_status: pass
unresolved_dependencies: 0

Audit date: 2026-07-18
Scope: `flashcards/01_living_systems_and_scale.md` through
`flashcards/10_evidence_models_and_synthesis.md`
Learner contract: cold-start adult; no confirmed biology, mathematics,
chemistry, statistics, laboratory, field, or programming knowledge.

## Method and resolved closure

`flashcards deck prerequisites .` reports no deck prerequisites and no assumed
tools. Each chapter has one explicit edge to the immediately preceding chapter;
the resolved local closure grows from none for Chapter 1 to Chapters 1–9 for
Chapter 10. File order was not treated as an edge.

All 146 fronts were extracted without `A:` or `S:` content. For each front, the
required technical terms, visual grammar, examples, and procedures were mapped
below before the answer-follow-on scan. Scheduled fronts alone count as
establishment. Everyday objects and verbs are accepted; a technical biological
meaning is accepted only from an explicit inbound provider or an earlier
scheduled front.

## Front-by-front dependency map

Each row represents one scheduled front. `own` means the front itself supplies
the minimal bridge before asking for a supported decision.

### Chapter 1 — living systems and scale

The pilot chapter and its stable IDs are unchanged. These rows were re-extracted
and agree with `.flashcards/audits/pilot-cold-start.md`.

| Front | Required dependency source | Status |
|---|---|---|
| 1.01 | biology and organism: own definitions and familiar examples | pass |
| 1.02 | biology: 1.01 | pass |
| 1.03 | system, component, interaction: own definitions | pass |
| 1.04 | system boundary: own definition; system: 1.03 | pass |
| 1.05 | system/component/interaction/boundary: 1.03–1.04 | pass |
| 1.06 | dashed boundary, arrows, wilt: own visual/word bridge; system terms: 1.03–1.05 | pass |
| 1.07 | boundary revision: 1.03–1.06; no answer-only procedure required | pass |
| 1.08 | scale, cell, organism, population: own definitions | pass |
| 1.09 | organism/population scale: 1.08 | pass |
| 1.10 | panel grammar and not-to-scale warning: own; biological scales: 1.08–1.09 | pass |
| 1.11 | cell/organism and cross-scale relation: 1.08–1.10 | pass |
| 1.12 | variation: own definition; organism/population: 1.08 | pass |
| 1.13 | organism and variation: 1.01, 1.12 | pass |
| 1.14 | mechanism: own definition | pass |
| 1.15 | mechanistic explanation: 1.14 | pass |
| 1.16 | observation, claim, evidence: own definitions | pass |
| 1.17 | evidence and bounded claim: 1.16 | pass |
| 1.18 | model and limitation: own definitions; boundary diagram: 1.06 | pass |
| 1.19 | model purpose/limits: 1.18; system terms and wilt: 1.03–1.06 | pass |

### Chapter 2 — patterns of life

Inbound: all Chapter 1 providers.

| Front | Required dependency source | Status |
|---|---|---|
| 2.01 | life-process cluster and reproduction: own bridge; system/interaction: Chapter 1 | pass |
| 2.02 | cluster criterion: 2.01; organism: Chapter 1 | pass |
| 2.03 | biological organization: own definition; interaction: Chapter 1 | pass |
| 2.04 | organization and multiple criteria: 2.01, 2.03 | pass |
| 2.05 | regulation and workable range: own definition; plant response described on front | pass |
| 2.06 | regulation pattern: 2.05 | pass |
| 2.07 | lineage, reproduction, offspring: own definition/bridge | pass |
| 2.08 | organism versus lineage: Chapter 1 and 2.07 | pass |
| 2.09 | boundary case and classification criteria: own definition; boundary: Chapter 1 | pass |
| 2.10 | matrix symbols: own legend/alt; criteria: 2.01–2.09 | pass |
| 2.11 | growth/reproduction checklist limits: 2.01, 2.07 | pass |
| 2.12 | sequence, disturbance, workable range: own visual bridge and 2.05 | pass |
| 2.13 | classification method: criteria established 2.01–2.09; cell: Chapter 1 | pass |
| 2.14 | dormant defined on front; timespan/capacity inference: 2.01–2.11 | pass |

### Chapter 3 — structure, function, and constraint

Inbound: Chapters 1–2.

| Front | Required dependency source | Status |
|---|---|---|
| 3.01 | structure and function: own definitions; system: Chapter 1 | pass |
| 3.02 | arrangement comparison: 3.01; root example fully described | pass |
| 3.03 | material properties and constraint: own bridge | pass |
| 3.04 | flexibility/brittleness: defined by ordinary contrast on front; constraint: 3.03 | pass |
| 3.05 | arrangement/material distinction: 3.01–3.03 | pass |
| 3.06 | tradeoff and conditional performance: own definition | pass |
| 3.07 | paired-shape grammar and light interception: own front/alt; structure: 3.01 | pass |
| 3.08 | exposed area versus layering: 3.06–3.07 | pass |
| 3.09 | current function/historical origin: own definitions | pass |
| 3.10 | mechanism and current performance: Chapter 1, 3.01, 3.09 | pass |
| 3.11 | open/pinched tube and attempted-flow arrows: own visual bridge; constraint: 3.03 | pass |
| 3.12 | hooks/fur problem: arrangement/material: 3.01–3.05; sufficient givens on front | pass |
| 3.13 | condition-dependent function: 3.06 | pass |
| 3.14 | function versus intention/origin: 3.09–3.10 | pass |

### Chapter 4 — information and response

Inbound: Chapters 1–3.

| Front | Required dependency source | Status |
|---|---|---|
| 4.01 | operational biological information: own definition; system/state: earlier chapters | pass |
| 4.02 | detection/use criterion: 4.01; plant growth example described | pass |
| 4.03 | cue, detector, response, path grammar: own definitions | pass |
| 4.04 | cue versus response: 4.03 | pass |
| 4.05 | arrow grammar, relay, break X: own front/alt; path terms: 4.03 | pass |
| 4.06 | detection versus later failure: 4.03–4.05 | pass |
| 4.07 | transmission: own definition; detection: 4.03 | pass |
| 4.08 | stored information: own definition | pass |
| 4.09 | three-role visual grammar: own front/alt; storage/transmission/detection: 4.03, 4.07–4.08 | pass |
| 4.10 | context-dependent response: response/state: 4.03 and earlier regulation | pass |
| 4.11 | operational information versus consciousness: 4.01 | pass |
| 4.12 | path-location problem: 4.03–4.07; sufficient observations on front | pass |
| 4.13 | detector measurement comparison: 4.03–4.07; observation: Chapter 1 | pass |
| 4.14 | diagram purpose/limits: model from Chapter 1; path grammar 4.03–4.07 | pass |

### Chapter 5 — matter and energy

Inbound: Chapters 1–4.

| Front | Required dependency source | Status |
|---|---|---|
| 5.01 | matter and energy: own bounded definitions | pass |
| 5.02 | matter source in growth: 5.01; organism: Chapter 1 | pass |
| 5.03 | open system: own definition; boundary/input/output ordinary bridge | pass |
| 5.04 | input/output crossing: 5.03 | pass |
| 5.05 | transfer/transformation: own definitions; energy: 5.01 | pass |
| 5.06 | storage: own definition; input: 5.03–5.04 | pass |
| 5.07 | qualitative arrow thickness and budget: own visual bridge; storage/input/output: 5.03–5.06 | pass |
| 5.08 | stopped input prediction: 5.07 | pass |
| 5.09 | loop and one-way visual grammar: own front/alt; matter/energy: 5.01 | pass |
| 5.10 | matter cycle versus energy path: 5.05, 5.09 | pass |
| 5.11 | waste as output, not destruction: 5.01, 5.03–5.04 | pass |
| 5.12 | energy creation misconception: 5.01, 5.05 | pass |
| 5.13 | pond boundary-repair problem: boundary/model earlier; energy transfers 5.01–5.05 | pass |
| 5.14 | budget model purpose/limits: model Chapter 1; tracking 5.03–5.07 | pass |

### Chapter 6 — variation, inheritance, and evolution

Inbound: Chapters 1–5.

| Front | Required dependency source | Status |
|---|---|---|
| 6.01 | variation: Chapter 1; inherited difference: own definition | pass |
| 6.02 | acquired versus inherited evidence: 6.01 | pass |
| 6.03 | generation and evolution: own definitions; population: Chapter 1 | pass |
| 6.04 | individual versus population/timespan: 6.03 | pass |
| 6.05 | reproductive outcome: own definition; lineage/reproduction: Chapter 2 | pass |
| 6.06 | unequal reproduction without survival difference: 6.05 | pass |
| 6.07 | natural selection and three required links: own definition plus 6.01, 6.05 | pass |
| 6.08 | shape symbols/snapshots/not-map caveat: own front/alt; generation/population 6.03 | pass |
| 6.09 | environment reversal prediction: 6.07–6.08 | pass |
| 6.10 | chain arrow grammar: own front/alt; all causal nodes 6.01–6.07 | pass |
| 6.11 | need-story diagnosis: mechanism Chapter 1; selection 6.07 | pass |
| 6.12 | environment dependence and tradeoff: 6.07; tradeoff Chapter 3 | pass |
| 6.13 | insect selection problem: inherited/selection 6.01–6.07; all givens supplied | pass |
| 6.14 | evolution versus selection mechanism: 6.03, 6.07 | pass |

### Chapter 7 — interactions, feedback, and emergence

Inbound: Chapters 1–6.

| Front | Required dependency source | Status |
|---|---|---|
| 7.01 | direct/indirect effect and path arrows: own definitions | pass |
| 7.02 | increase/decrease path tracing: 7.01; qualitative terms ordinary | pass |
| 7.03 | feedback and closed loop: own definition | pass |
| 7.04 | reinforcing feedback: own definition; plant loop fully described | pass |
| 7.05 | counteracting feedback: own definition; population/reproduction earlier | pass |
| 7.06 | increase/decrease labels and loop grammar: own front/alt; feedback 7.03–7.05 | pass |
| 7.07 | broken-return prediction: 7.03, 7.05–7.06 | pass |
| 7.08 | direction label versus value judgment: 7.04–7.05 | pass |
| 7.09 | subsystem: own definition; boundary/system Chapter 1 | pass |
| 7.10 | emergent pattern: own definition; scale/system Chapter 1 | pass |
| 7.11 | dot/arrow/local-rule grammar: own front/alt; emergence 7.10 | pass |
| 7.12 | reinforcing-loop perturbation problem: 7.03–7.06; complete loop supplied | pass |
| 7.13 | isolated part versus group pattern: 7.10–7.11 | pass |
| 7.14 | feedback-model purpose/limits: model Chapter 1; loop grammar 7.03 | pass |

### Chapter 8 — questions, hypotheses, and predictions

Inbound: Chapters 1–7.

| Front | Required dependency source | Status |
|---|---|---|
| 8.01 | bounded question and scope: own definition; system/outcome ordinary/inbound | pass |
| 8.02 | bounded-question construction: 8.01; stem/light example earlier | pass |
| 8.03 | descriptive/explanatory questions: own definitions | pass |
| 8.04 | observation-to-explanatory question: observation Chapter 1; 8.03 | pass |
| 8.05 | hypothesis: own definition; observation distinction Chapter 1 | pass |
| 8.06 | prediction: own definition; hypothesis 8.05 | pass |
| 8.07 | hypothesis versus prediction: 8.05–8.06 | pass |
| 8.08 | inquiry-map arrows and return paths: own visual bridge; node terms 8.01–8.07 | pass |
| 8.09 | descriptive entry point: 8.03, 8.08 | pass |
| 8.10 | result against hypothesis: own definition; prediction 8.06 | pass |
| 8.11 | competing-prediction table: own front/alt; hypothesis/prediction 8.05–8.06 | pass |
| 8.12 | observable specificity: prediction 8.06 | pass |
| 8.13 | discriminating-prediction problem: observation/hypothesis/prediction established; givens sufficient | pass |
| 8.14 | bounded support and alternatives: evidence/model limits Chapter 1; hypothesis 8.05 | pass |

### Chapter 9 — comparisons, controls, and causes

Inbound: Chapters 1–8.

| Front | Required dependency source | Status |
|---|---|---|
| 9.01 | focal changed factor and comparison group: own definitions | pass |
| 9.02 | changed factor versus outcome: own outcome bridge; factor 9.01 | pass |
| 9.03 | control: own definition; comparison 9.01 | pass |
| 9.04 | matched-group visual and added-material setup: own front/alt; control 9.03 | pass |
| 9.05 | confounding difference: own definition; group setup 9.04 | pass |
| 9.06 | confound repair: 9.04–9.05 | pass |
| 9.07 | repeated observations and variation: own bridge; variation Chapter 1 | pass |
| 9.08 | association and causal alternatives: own definition; claim/evidence Chapter 1 | pass |
| 9.09 | intervention evidence: own definition; comparison 9.01 | pass |
| 9.10 | two-headed association and one-way intervention grammar: own front/alt; 9.08–9.09 | pass |
| 9.11 | bounded causal claim: intervention 9.09; conditions 8.01 | pass |
| 9.12 | redesign problem: control/confound 9.03–9.06; all conditions stated | pass |
| 9.13 | container-condition control issue: 9.03, 9.05 | pass |
| 9.14 | observational causal uncertainty: 9.08–9.09 | pass |

### Chapter 10 — evidence, models, uncertainty, and synthesis

Inbound: Chapters 1–9.

| Front | Required dependency source | Status |
|---|---|---|
| 10.01 | converging evidence: own definition; evidence/claim Chapter 1 | pass |
| 10.02 | method independence and scope: 10.01; conditions Chapter 8 | pass |
| 10.03 | conflicting evidence: own definition; hypotheses/evidence earlier | pass |
| 10.04 | uncertainty: own definition and contrast | pass |
| 10.05 | convergence/conflict/revision-map grammar: own front/alt; 10.01–10.04 | pass |
| 10.06 | scope repair: conditions/causal bounds Chapters 8–9 | pass |
| 10.07 | model purpose, assumptions, limitations: model Chapter 1; own purpose bridge | pass |
| 10.08 | two-report visual grammar: own front/alt; uncertainty 10.04 and causal bounds Chapter 9 | pass |
| 10.09 | cross-scale explanation: own definition; scale/mechanism Chapter 1 | pass |
| 10.10 | multiscale visual and dashed “more evidence” cue: own front/alt; inheritance/selection Chapter 6 | pass |
| 10.11 | question-relevant boundary: system/boundary Chapter 1 | pass |
| 10.12 | evidence versus value judgment: own bridge; evidence/uncertainty earlier | pass |
| 10.13 | evidence-bundle problem: intervention/association Chapter 9; convergence/conflict 10.01–10.04 | pass |
| 10.14 | model choice by relevant relationship: model purpose 10.07; matter input Chapter 5 | pass |
| 10.15 | cross-scale capstone problem: system/matter/variation/inheritance all established; unsupported steps explicitly named | pass |

## Answer-follow-on scan

Answers were inspected after the dependency tables above were recorded.

- IPEE headings appear only in solutions and are never required by a later
  front without the problem itself supplying a plan cue.
- New corrective phrases such as `conditional`, `historical mechanism`, and
  `method limitation` are either ordinary language, restatements of established
  concepts, or re-established on a later front before retrieval.
- No answer introduces a symbol, unit, axis, statistical method, chemical term,
  molecular actor, anatomical structure, or figure convention silently assumed
  later.
- Figure alt text and embedded SVG descriptions were included in the front
  scan. Setup descriptions are complete; requested inferences are not directly
  named after the repairs below.

## Repairs from the full scan

1. Chapter 2 front 2.01 removed `lineage` before its definition; front 2.14
   replaced a future inheritance/information example with a defined dormant-seed
   timespan case.
2. Chapter 3 front 3.09 removed `generations` before Chapter 6 establishes the
   term; related feedback now says “earlier process.”
3. Chapter 4 front 4.09 now asks for the visible distinction between
   transmission and storage instead of asking for a panel label printed on the
   figure.
4. Chapter 7 figure labels and alt text no longer name the feedback categories
   being inferred; they provide only increase/decrease link data.
5. Chapter 8 front 8.01 no longer depends on the Chapter 9 technical comparison
   concept.
6. Chapter 9 front 9.01 now defines `focal changed factor` before using it.
7. Chapter 10 front 10.10 and its figure no longer print the evolutionary
   conditions being retrieved; the front asks the learner to supply them from
   Chapter 6.

## Gate decision

Every front can be parsed and plausibly attempted from its own scheduled bridge
or its explicit local prerequisite closure. No front depends on a later chapter,
an undeclared deck or tool, unscheduled prose, or an answer revealed only after
an uninformed failure. The full deck passes the cold-start dependency gate.
