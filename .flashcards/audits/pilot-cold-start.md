# Chapter 1 pilot cold-start audit

cold_start_status: pass
unresolved_dependencies: 0

Audit date: 2026-07-22
Chapter: `flashcards/01_living_systems_and_scale.md`
Learner contract: cold-start adult; no confirmed biology, mathematics,
chemistry, laboratory, field, or programming knowledge.

## Resolved inbound knowledge

`flashcards deck prerequisites . --chapter 1` reports an explicit Chapter 1
edge with no local prerequisite closure, no external deck closure, and no
assumed tools. Everyday English is allowed; every biology-specific term or
representation required by a front must therefore be established on that front
or an earlier scheduled front.

## Audit method

The chapter was extracted as fronts only in scheduled order. Dependencies for
each front—including alt text, panel labels, dashed outlines, arrows, examples,
and problem wording—were recorded before answers were inspected. Answers were
then scanned for terms that a later front might assume. Headings, prose outside
blocks, and figures outside scheduled fronts were not counted as instruction.

## Front-by-front dependency ledger

| Front | Retrieval target | Dependencies required to parse and attempt | Confirmed source or establishment | Finding |
|---|---|---|---|---|
| C01 | Meaning of `organism` | `biology`, life, organism; familiar examples | The front defines biology as study of life and organism as one individual living thing; examples require no specialist knowledge | pass |
| C02 | Scope of biology | `biology` | Established on C01 front | pass |
| C03 | Recognize an interaction | system, component, interaction; soil and plant | All three system terms are defined on the front; soil and plant are familiar examples | pass |
| C04 | Interpret a system boundary | system; inside/outside | System established C03; boundary and its inside/outside role are defined on the front | pass |
| C05 | Components of a useful system description | system, components, interactions, boundary; question dependence | Established C03–C04 | pass |
| C06 | Choose a boundary from a diagram | candidate boundary; dashed-outline and arrow grammar; components; wilt | System vocabulary established C03–C05; front explains dashed outlines and arrows; alt text names setup without giving the choice; front defines wilt as losing firmness and drooping | pass |
| C07 | Revise a mismatched boundary | system, boundary, component, interaction | Established C03–C06; no answer-only method is required to attempt the problem | pass |
| C08 | Select organism scale | scale, cell, organism, population | Front defines scale and all three biological levels before asking for a supported choice | pass |
| C09 | Discriminate organism and population scales | organism scale, population scale | Established C08 | pass |
| C10 | Translate a question to a pictured scale | panel grammar; cell/organism/population; conceptual icons; non-scale drawing | Scale terms established C08–C09; front and alt text identify panels and warn that icon sizes are not comparable | pass |
| C11 | Relate an organism-scale and a population-scale statement about one pond | organism scale, population scale; everyday duck/pond/spread language | Both scale terms established C08–C10; the front labels its two notes explicitly as organism-scale and population-scale, so no unstated mechanism is required | pass |
| C12 | Use variation to limit representation | variation, population, organism | Population established C08; variation is defined on the front before the inference | pass |
| C13 | Diagnose overgeneralization | organism; variation; brief observation | Organism established C01/C08; variation established C12; the front uses everyday “watches” and “concludes” rather than assuming evidence vocabulary | pass |
| C14 | Turn need language into a mechanism question | mechanism; plant stem; process/outcome | Mechanism is defined on the front; plant stem and bending use familiar language | pass |
| C15 | Distinguish mechanism from need | mechanistic explanation; two numbered alternatives; unequal lengthening | Mechanism established C14; the alternatives contain all process information needed for the contrast | pass |
| C16 | Identify an observation | observation, claim, evidence; drooping and dry soil | All three inquiry terms are defined on the front; the biological event is described in everyday language | pass |
| C17 | Bound support for a causal claim | evidence, claim, observation, cause | Evidence/claim/observation established C16; cause is used in its ordinary sense | pass |
| C18 | Judge an omitted detail in a model | model, simplification, limitation; boundary diagram | Model and limitation are defined on the front; boundary diagram established C06 | pass |
| C19 | Choose a purpose-fit model | model, system components/interactions, wilt | Models established C18; system vocabulary C03–C07; wilt C06; all model differences are stated in the cue | pass |

## Answer follow-on scan

- C07 introduces IPEE solution headings only on the back; no later front requires
  that procedure.
- C11's answer only states that a group is made up of individuals; it introduces
  no term that a later front assumes.
- No answer introduces a symbol, unit, axis, visual convention, method, or
  biological term that a later front silently assumes.

## Figure inspection

- `study_boundary.svg` has a responsive `viewBox`, one meaningful title and
  description, legible labels at a 900-pixel phone-width preview, and redundant
  cues: panel names plus dashed boundary shape, not color alone. The front
  explains the dashed outline and arrows without revealing the useful choice.
- `question_sets_scale.svg` has a responsive `viewBox`, one meaningful title and
  description, legible labels at the same preview width, and an explicit warning
  that the conceptual icon sizes are not comparable. Its alt text provides the
  complete setup without naming the requested scale.
- TikZ emits arrowheads as paths rather than SVG markers, so the hand-authored
  `markerUnits` rule is not applicable. Both SVGs were produced by
  `flashcards deck render-figures .` from the adjacent editable sources and pass
  the stale-output check.

## Repairs made during the simulation

1. Removed `evidence-based` from C01 because evidence is not taught until C16.
2. Replaced a bacterium example and avoidable `oak`, `seedling`, `shoot`, and
   `root` wording with familiar language that tests the same target.
3. Replaced `relative scale` with the explicit statement that drawn sizes are
   not meant to be compared.
4. Defined `wilt` on C06 before it reappears on C19.
5. Simplified the cell icon so it cannot be mistaken for several cells.
6. Rebuilt C11's cross-scale example around one duck pond (a single duck's
   paddling versus the flock's north/south distribution) instead of a
   cell-to-organism "growth" contrast. The earlier version implied a growth
   mechanism (cells dividing or lengthening) that this chapter never introduces
   and that the biology domain guide warns against asserting prematurely; the
   pond example makes the same organism-versus-population point using only scale
   terms already established on C08–C10.

## Gate decision

Every front can be parsed and plausibly attempted from its own bridge or
earlier scheduled cards. No dependency comes from a later chapter, an
undeclared deck, unscheduled prose, or an answer revealed only after an
uninformed failure. Chapter 1 passes the novice cold-start dependency gate and
the deck must now stop for explicit human pilot approval before Chapters 2–10
are authored.
