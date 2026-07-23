# Biology and Scientific Inquiry card blueprint

This file records retrieval decisions specific to this deck. Do not copy the
universal standard, playbook, subject brief, roadmap, or research literature
here; link to a justified exception when one is necessary.

## Learner model

- Level: foundational
- Confirmed mathematical/tool prerequisites: none
- Confirmed subject prerequisites: none
- Capabilities this deck should produce: biological orientation across scales;
  systems, structure-function, information, matter/energy, evolution, and
  evidence reasoning; qualitative model interpretation; bounded causal
  language; and readiness for explicit quantitative and chemical foundations.
- Important exclusions: specialist biology content, arithmetic and statistics,
  chemistry, independent laboratory or field technique, programming, clinical
  advice, and any claim that cards replace authentic investigation.

Unconfirmed subject knowledge is not mastered. A target level describes the
destination, not permission to assume its vocabulary.

## Curriculum and prerequisite graph

Define prerequisite decks and assumed tools in `deck.toml`; define chapter
edges and provided concepts in each chapter's TOML frontmatter. Inspect the
resolved, human-readable graph with `flashcards deck prerequisites .`. Do not
duplicate that graph here. Use this section only to explain important design
decisions, boundaries, or rejected edges that the metadata cannot express.

The resolved inbound closure is empty. Chapter 1 therefore uses scheduled
fronts to establish every technical word and visual convention it needs. The
later curriculum is ordered as a dependency progression: orientation; patterns
of life; structure-function; information; matter/energy; evolution;
interactions; questions; causal comparisons; synthesis. Planned filenames do
not grant knowledge until their chapter frontmatter declares an edge.

## Concept-dependency ledger

| Concept or representation | Front(s) requiring it | Confirmed inbound source or first explanation | First supported retrieval | Later application | Status |
|---|---|---|---|---|---|
| `biology` | C02, C05 | C01 front: the study of life | C02 | C05 | established |
| `organism` | C01, C08–C13 | C01 front: an individual living thing, with familiar examples | C01 | C08–C13 | established |
| `system`, `component`, `interaction` | C04–C07, C18–C19 | C03 front: a chosen set of parts and the ways they affect one another | C03 | C04–C07, C18–C19 | established |
| `system boundary` and dashed-outline grammar | C05–C07, C19 | C04 front defines the boundary; C06 front explains that dashed outlines show two candidate boundaries | C04 | C05–C07, C19 | established |
| `scale` | C08–C11 | C08 front: the size or level at which a question is asked | C08 | C09–C11 | established |
| `cell` | C08, C10 | C08 front: the smallest basic unit of life | C08 | C10 | established |
| `population` | C08–C13 | C08 front: organisms of the same kind in the same area | C09 | C10–C13 | established |
| `wilt` | C06, C19 | C06 front: lose firmness and droop | C06 | C19 | established |
| three-panel scale diagram | C10 | C10 front names each panel and states that icons are conceptual and not to scale | C10 | none in pilot | established |
| cross-scale statements | C11 | C08–C10 establish scales; C11 front supplies two pond notes each labelled with its named scale (organism, population) | C11 | later chapters | established |
| `variation` | C12–C13 | C12 front: differences among organisms in a population | C12 | C13 | established |
| `mechanism`, `mechanistic explanation` | C14–C15 | C14 front: a process that produces an outcome | C14 | C15 | established |
| observation, claim, evidence | C16–C17 | C16 front defines each and supplies a worked everyday biological example | C16 | C17 | established |
| `model`, limitation | C18–C19 | C18 front defines a model as a purposeful simplification and names omitted details as limitations | C18 | C19 | established |

Rejected pilot examples: membrane transport and photosynthesis require
chemistry; gene-expression diagrams require cell, chemistry, and genetics
instruction; natural-selection mechanisms require variation and inheritance
support beyond this chapter; feedback-control diagrams belong after interaction
grammar; statistical graphs require the quantitative and data decks; laboratory
controls belong in Chapter 9 and later research-practice work.

### Full-build dependency plan

Planning references use `2.01`, `3.01`, and so on for the intended scheduled
order within a chapter. They are reconciled to actual card blocks after
authoring. Every chapter explicitly depends on the chapter immediately before
it, so these establishment points—not filename order—authorize later use.

| Chapter | New concept or representation | First explanation or analyzed example | First supported retrieval | Later application | Status before authoring |
|---|---|---|---|---|---|
| 2 | life-process criteria; organized system; regulation; lineage; boundary case; criteria-by-case matrix; state-change sequence | 2.01, 2.03, 2.05, 2.07, 2.09, 2.10, 2.12 fronts | 2.02, 2.04, 2.06, 2.08, 2.10, 2.11, 2.12 | 2.13–2.14 and Chapters 3–10 | planned |
| 3 | structure; function; arrangement; material; constraint; tradeoff; current role versus historical origin; paired-shape and before/after grammars | 3.01, 3.03, 3.05, 3.07, 3.09 fronts | 3.02, 3.04, 3.06, 3.08, 3.10 | 3.11–3.14 and Chapter 10 | planned |
| 4 | biological information as a difference that can affect a response; stored/transmitted/detected information; cue; detector; response; interruption; path and comparison grammars | 4.01, 4.03, 4.05, 4.07 fronts | 4.02, 4.04, 4.06, 4.08 | 4.09–4.14 and Chapters 7–10 | planned |
| 5 | matter; energy; input; output; transfer; transformation; storage; open system; cycle-versus-flow and qualitative-budget grammars | 5.01, 5.03, 5.05, 5.07 fronts | 5.02, 5.04, 5.06, 5.08 | 5.09–5.14 and Chapters 7 and 10 | planned |
| 6 | inherited difference; generation; reproductive outcome; evolution as population change; natural selection as a bounded mechanism; non-goal-directed explanation; snapshot and causal-chain grammars | 6.01, 6.03, 6.05, 6.07 fronts | 6.02, 6.04, 6.06, 6.08 | 6.09–6.14 and Chapter 10 | planned |
| 7 | direct and indirect effect; reinforcing and counteracting feedback; subsystem; emergence; loop and individual-to-group grammars | 7.01, 7.03, 7.05, 7.07 fronts | 7.02, 7.04, 7.06, 7.08 | 7.09–7.14 and Chapter 10 | planned |
| 8 | bounded question; descriptive and explanatory question; hypothesis; prediction; result against an explanation; iterative inquiry-map and competing-prediction grammars | 8.01, 8.03, 8.05, 8.07 fronts | 8.02, 8.04, 8.06, 8.08 | 8.09–8.14 and Chapters 9–10 | planned |
| 9 | comparison group; changed factor; control; repeated observation; confounding difference; observational association; intervention evidence; setup and comparison grammars | 9.01, 9.03, 9.05, 9.07 fronts | 9.02, 9.04, 9.06, 9.08 | 9.09–9.14 and Chapter 10 | planned |
| 10 | converging and conflicting evidence; uncertainty; claim revision; model comparison by purpose and limits; cross-scale synthesis; evidence-revision, multiscale, and uncertainty grammars | 10.01, 10.03, 10.05, 10.07, 10.09 fronts | 10.02, 10.04, 10.06, 10.08, 10.10 | 10.11–10.15 capstone applications | planned |

Rejected cross-boundary scaffolds: Chapter 2 does not use viruses as a visual
identification task; Chapter 3 avoids molecules; Chapter 4 avoids DNA, nerves,
and receptors as assumed anatomy; Chapter 5 avoids chemical equations and
calculation; Chapter 6 avoids genes, alleles, and frequency arithmetic; Chapter
7 avoids differential equations; Chapters 8–10 avoid inferential statistics.
Each rejected example would test later-deck knowledge instead of the intended
foundational decision.

## Retrieval portfolio

The portfolio repeatedly uses bounded explanation, representation translation,
misconception diagnosis, qualitative prediction, and method choice. Likely
interference pairs are: component/system; organism/population; observation/claim;
evidence/claim; hypothesis/prediction; function/origin; need/mechanism;
association/causation; matter/energy; model/reality; and uncertainty/ignorance.
Each contrast is scheduled only after both neighbors have been established.

## Chapter design ledger

| Chapter | Retrieval targets | Basic-card roles | Cloze candidates | Problem progression | Representations and figure opportunities |
|---|---|---|---|---|---|
| 1. Living systems, boundaries, and scale | Organism and biology; system/component/interaction/boundary; question-dependent scale; cell/organism/population; cross-scale compatibility; variation; mechanism; observation/claim/evidence; model limits | Bridges, definitions, figure interpretation, contrasts, and diagnoses | None: all targets require meaning or reasoning before exact recall | Analyzed boundary choice (C06), independent boundary problem (C07), mixed model discrimination (C19) | **Include:** candidate-boundary diagram for relational choice; **include:** three-scale diagram for question-to-scale translation. **Omit:** photographs because morphology is not the target; quantitative graph because no axes or arithmetic are inbound. |
| 2. Patterns of life | Shared processes; organization; responsiveness; maintenance; reproduction and lineage; criteria and boundary cases | Define criteria, compare cases, diagnose checklist misuse | Possible compact terms only after meaning is established; no vocabulary-list clozes | Analyzed classification, faded boundary case, mixed living/nonliving cases | **Include:** criteria-by-case matrix because no single picture defines life; **include:** state-change sequence for maintenance. **Omit:** virus micrograph because visual morphology cannot settle the classification. |
| 3. Structure, function, and constraint | Arrangement and material; function; constraint; tradeoff; current role versus origin | Structure-to-function inference, function-to-structure prediction, misconception contrast | None planned: relations, not isolated terms, are the targets | Analyzed familiar structure, faded novel structure, independent comparison | **Include:** paired structures with redundant shape cues; **include:** before/after structural change. **Omit:** molecular structures until chemistry is inbound. |
| 4. Information and response | Stored versus transmitted versus detected information; cue, detector, response; context dependence | Trace paths, distinguish information senses, predict interruption | Possible `cue`/`response` only if uniquely cued after explanation | Analyzed path trace, completion of a missing link, novel qualitative path | **Include:** cue-to-response path; **include:** stored-versus-transmitted comparison. **Omit:** DNA and neural circuit diagrams because their mechanisms belong to later decks. |
| 5. Matter, energy, and change | Inputs, outputs, storage, transfer, transformation; matter versus energy; open systems | Track and classify arrows, predict consequences of blocked transfer | None planned: exact labels would encourage slogan recall | Analyzed input/output inventory, faded trace, independent matter/energy discrimination | **Include:** matter-cycle versus energy-transfer diagrams; **include:** qualitative system budget. **Omit:** chemical equations and numerical efficiency graphs because chemistry/math are not inbound. |
| 6. Variation, inheritance, and evolution | Individual variation; inherited differences; population change across generations; unequal reproductive outcomes; non-goal-directed change | Sequence reasoning, prediction, diagnose striving/need stories | Possible `population` or `generation` only after causal model is secure | Analyzed generation sequence, faded prediction, independent nonteleological explanation | **Include:** population snapshots across generations; **include:** variation-to-outcome causal chain. **Omit:** allele-frequency graphs and DNA mechanisms until quantitative/genetic prerequisites exist. |
| 7. Interactions, feedback, and emergence | Direct/indirect interaction; reinforcing/counteracting feedback; subsystem; emergent pattern | Trace effects, compare loops, predict perturbation, diagnose part-only explanation | None planned: arrows must be interpreted, not named from prose | Analyzed loop, completion trace, faded perturbation, mixed network choice | **Include:** two feedback loops with sign and text cues; **include:** individual-to-group emergence sequence. **Omit:** differential-equation plots because mathematics is not inbound. |
| 8. Questions, claims, and predictions | Observation, bounded question, hypothesis, prediction, disconfirming result; descriptive versus explanatory inquiry | Translate among forms, improve vague questions, distinguish hypothesis/prediction | Possible exact terms after worked translations | Analyzed translation, completion prediction, independent testability diagnosis | **Include:** non-linear inquiry map; **include:** competing-explanation prediction table. **Omit:** rigid “scientific method” staircase because it misrepresents practice. |
| 9. Comparisons, controls, and causes | Comparison group; changed factor; control; repeated observations; association versus causal claim; alternative explanations | Choose comparisons, identify confounds, bound conclusions | None planned: method decisions are the target | Analyzed comparison, completion control, faded design, independent causal critique | **Include:** experimental setup with answer labels reserved for back; **include:** observational-versus-intervention comparison. **Omit:** inferential-statistics plots because that deck is not inbound. |
| 10. Evidence, models, uncertainty, and synthesis | Convergence; conflict; uncertainty; model purpose/limits; cross-scale causal synthesis; science-society boundary | Weigh evidence, compare models, revise claims, communicate limits | Possible `converging evidence` only after several examples | Analyzed evidence bundle, faded model comparison, independent synthesis, mixed capstone | **Include:** evidence-to-model revision map; **include:** multi-scale capstone system; **include:** uncertainty communication comparison. **Omit:** numerical confidence intervals because statistics is not inbound. |

Card-form diversity is not a goal by itself. Zero clozes can be correct. A
visually rich chapter may require several figures because diagrams, graphs,
before/after states, and spatial constructions serve different retrieval roles.

## Initial-learning path

Chapter 1 alternates a scheduled teaching bridge with supported retrieval and
then a less-supported application. C01–C02 orient biology and organism; C03–C06
build system reasoning before the independent C07 problem; C08–C11 build scale
reasoning; C12–C13 establish variation before diagnosing overgeneralization;
C14–C15 establish mechanism before contrasting need language; C16–C17
establish evidence vocabulary before limiting a claim; and C18 establishes
models before the C19 discrimination. Headings and figures outside card blocks
are not counted as teaching.

The approved full build repeats the same bridge-supported-retrieval-application
pattern within every chapter. A front may use only declared inbound concepts or
an explanation already placed on a scheduled front. The full front-by-front
simulation is recorded in `.flashcards/audits/full-cold-start.md`.

## Figure policy

Add a figure only when inspecting, predicting, labeling, comparing, tracing, or
translating it is part of learning. Author new technical figures in TikZ by
default, compile them to responsive SVG before handoff, and commit source and
output together under repository-root `figures/NN_chapter/`; keep the shared
style at `figures/tikz-style.tex` and never create `flashcards/figures/`. Since
rendering runs from the repository root, load it with
`\\input{figures/tikz-style.tex}` rather than a source-relative path. Put
setup figures on the front and answer-revealing
annotations on the back. Record why an authentic target requires another medium.

Do not treat one figure per chapter as a target or cap. Inventory every
plausible spatial, temporal, structural, graphical, relational, experimental,
and before/after representation, then include or explicitly omit it according
to its retrieval value.

## Sources and accuracy

Authoritative sources, rights, access dates, simplifications, and boundary
conditions are recorded in `README.md`. All diagrams are original and
conceptual; those using organism symbols explicitly avoid scale claims.

## Inventory reconciliation

| Chapter | Planned cards/problems/figures | Actual | Reconciliation |
|---|---|---|---|
| 1 | 18 basic, 0 cloze, 1 problem; 2 TikZ/SVG figures | 18 basic, 0 cloze, 1 problem; 2 editable TikZ sources and 2 compiled SVGs | Matches the plan. Both figures serve distinct retrieval roles; no card or figure was added for type balance. |
| 2 | Definitions, contrasts, one classification problem; criteria matrix and regulation sequence | 13 basic, 0 cloze, 1 problem; 2 TikZ/SVG figures | Matches all planned roles. The virus micrograph remains omitted because morphology cannot settle the criterion question. |
| 3 | Structure-to-function inference, prediction, origin contrast, one transfer problem; paired and before/after figures | 13 basic, 0 cloze, 1 problem; 2 TikZ/SVG figures | Matches. Molecular structures remain omitted because chemistry is not inbound. |
| 4 | Information-role contrasts, path tracing, interruption prediction, one transfer problem; path and role figures | 13 basic, 0 cloze, 1 problem; 2 TikZ/SVG figures | Matches. DNA and neural mechanisms remain intentionally omitted. |
| 5 | Qualitative input/output tracking, transfer/transformation contrasts, one boundary-repair problem; budget and cycle/path figures | 13 basic, 0 cloze, 1 problem; 2 TikZ/SVG figures | Matches. Equations and efficiency graphs remain omitted because math and chemistry are not inbound. |
| 6 | Inheritance/evolution mechanism, prediction, misconception diagnosis, one selection problem; snapshots and causal chain | 13 basic, 0 cloze, 1 problem; 2 TikZ/SVG figures | Matches. Alleles, DNA, and frequency arithmetic remain reserved for later decks. |
| 7 | Direct/indirect effects, two feedback classes, emergence, one perturbation problem; loop and group-pattern figures | 13 basic, 0 cloze, 1 problem; 2 TikZ/SVG figures | Matches. Quantitative dynamics remain omitted. |
| 8 | Question/hypothesis/prediction translation, disconfirmation, one discriminating-prediction problem; iterative map and prediction table | 13 basic, 0 cloze, 1 problem; 2 TikZ/SVG figures | Matches. A rigid method staircase remains intentionally omitted. |
| 9 | Comparison/control decisions, confound repair, causal bounds, one redesign problem; matched setup and association/intervention figures | 13 basic, 0 cloze, 1 problem; 2 TikZ/SVG figures | Matches. Statistical inference remains outside scope. |
| 10 | Evidence weighting, model comparison, uncertainty, cross-scale synthesis, evidence-bundle and capstone problems; revision, uncertainty, and multiscale figures | 13 basic, 0 cloze, 2 problems; 3 TikZ/SVG figures | Matches all three distinct visual roles. Confidence intervals remain omitted because statistics is not inbound. |

Actual total: 135 basic cards, 0 clozes, 11 problems, 21 editable TikZ
sources, and 21 compiled accessible SVGs. Zero clozes is intentional: every
target requires explanation, discrimination, prediction, interpretation, or
method choice rather than isolated exact insertion.

## Validation gate

Before handoff:

1. Run `flashcards deck stabilize . --check`.
2. Run `flashcards deck validate .`.
3. Inspect every changed figure at phone width.
4. Reconcile planned versus actual card types, problems, and figures by chapter.
5. Run `git diff --check` and review the complete diff.
6. Summarize additions, changes, omissions, and any unresolved uncertainty.
