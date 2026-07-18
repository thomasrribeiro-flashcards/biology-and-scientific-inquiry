# Full-build and whole-deck audit record

## Contract and baseline

- Date: 2026-07-18
- Model: Codex (GPT-5)
- Requested mode: build, followed by an editing whole-deck audit
- Learner: cold-start adult with no confirmed biology, mathematics, chemistry,
  statistics, laboratory, field, or programming prerequisites
- Scope: preserve approved Chapter 1; author Chapters 2–10; add earned figures;
  reconcile design and dependency ledgers; complete a full cold-start scan
- Baseline commit: `1f4598c9097c594c9b26c10f8272a13130c1b586`
- Baseline working tree: clean
- Standards: staged `CARD_STANDARD.md`, `AUTHORING_PLAYBOOK.md`, biology domain
  guide, cold-start workflow, and audit workflow listed by the isolated CLI

## Authoritative sources added or rechecked

The deck source register records authority, role, rights/terms, and access date.
This build added or rechecked the National Research Council life-science core
ideas, NASA Astrobiology's current life-definition boundary discussion, Fudge
and Turko on discriminating predictions, and Hartman et al. on experimental
controls. Existing Vision and Change, BioCore, BioSkills, National Academies
systems/evolution, and OpenStax rights records were preserved.

## Inventory before and after

| Item | Before | After |
|---|---:|---:|
| Chapter files | 1 | 10 |
| Basic cards | 18 | 135 |
| Cloze cards | 0 | 0 |
| Problem cards | 1 | 11 |
| Total scheduled cards | 19 | 146 |
| Editable TikZ sources | 2 | 21 |
| Compiled SVG figures | 2 | 21 |

Chapter-level actuals and planned-versus-actual reconciliation are recorded in
`CARD_README.md`. Zero clozes is an intentional target-driven result, not an
omission: the portfolio emphasizes explanations, distinctions, predictions,
figure interpretation, and method choices.

## Findings and repairs

### Critical

None. The parser dropped no cards; no false claim, broken identity, missing
asset, or invalid prerequisite edge was found.

### Major — repaired

1. **U7/D7, Chapters 2–3:** future `lineage`, inheritance, information, and
   generation language appeared before its scheduled establishment. The Chapter
   2 boundary case was replaced with a dormant-seed timespan case, and Chapter 3
   origin language was made history-neutral.
2. **U7, Chapter 8:** `comparison` appeared in a technical definition before
   Chapter 9. The bounded-question bridge now uses system, outcome, conditions,
   and scope only.
3. **U7, Chapter 9:** `focal changed factor` was used before definition. Front
   9.01 now defines it before the comparison-group decision.
4. **U8/V2, Chapters 4, 7, and 10:** printed figure labels or alt text revealed
   the requested panel/category/selection conditions. Prompts now require a
   relationship or prior-knowledge inference, while setup descriptions remain
   accessible.

### Minor — repaired

1. **V3, Chapter 5:** the first phone-width render of the matter-cycle/energy-path
   figure cropped an edge node and overlapped labels. The layout was rebuilt
   within a fixed panel.
2. **V3, Chapter 10:** a capstone label hyphenated awkwardly at 390 pixels. It
   was shortened to `more evidence needed` and re-rendered.

No unresolved findings remain. No study telemetry was available, so the audit
used the learner contract, standards, source verification, parser output, and
semantic cold-start simulation rather than performance data.

## Identity decisions

- Chapter 1 and all 19 existing stable IDs are byte-for-byte unchanged.
- Chapters 2–10 contain 127 new retrieval targets, each with a new unique stable
  ID.
- Wording and figure repairs made during the cold-start scan retained their new
  IDs because each retrieval target and grading decision remained the same.
- No card was split, retired, aliased, or assigned another card's history.

## Figure audit

All 21 TikZ sources load `figures/tikz-style.tex` from the repository root and
have adjacent same-named SVG outputs. Every SVG has a responsive `viewBox`,
role/ARIA wiring, and meaningful title and description. Every figure was
rendered to a 390-pixel-wide preview and inspected for label legibility, crop,
whitespace, arrow proportion, answer leak, contrast, and redundant non-color
cues. TikZ compiles arrows to paths, so SVG marker-unit requirements do not
apply.

## Cold-start result

`.flashcards/audits/full-cold-start.md` maps every scheduled front to declared
inbound knowledge, an own-front teaching bridge, or an earlier scheduled
establishment. The answer-follow-on scan found no answer-only dependency later
assumed without re-establishment.

## Validation

Commands and final results:

- `flashcards deck render-figures . --check` — 21 figures checked; no stale or
  missing output
- `flashcards deck stabilize . --check` — 0 missing stable IDs across 146
  scheduled cards
- `flashcards deck validate .` — 10 files; 146 cards; 0 parser warnings, KaTeX
  errors, image errors, identity errors, cloze lints, or frontmatter lints;
  prerequisite graph valid with 10 local chapters and 0 external decks
- `git diff --check` — pass
- Application tests — not run because parser and identity behavior were not
  changed

## Intentional omissions and handoff state

Later-deck chemistry, molecular mechanisms, equations, statistical inference,
allele-frequency calculations, detailed anatomy, and quantitative dynamics
remain intentionally omitted. Their absence protects the declared cold-start
boundary rather than narrowing an approved chapter outcome.

All work is local and uncommitted. No commit, push, remote creation, deployment,
or staged-context modification was performed.
