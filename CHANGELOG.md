# Changelog

All notable changes to DriveMind should be recorded here.

## `v0.6.0` - 2026-03-22

### Changed
- fully re-centered DriveMind from a “calm reliability layer” into an **execution-integrity + experience-compounding layer** for long-horizon human-AI work
- reframed the product around five failure modes of degraded work: goal drift, boundary drift, continuity decay, stuck degeneration, and closure failure
- rewrote `skill/SKILL.md` so the skill now activates around degradation risk rather than general collaboration doctrine
- replaced the old main-path framing with a new active path: detect degradation risk → stabilize the thread → preserve boundary integrity → recover from stuckness → preserve continuity → close with compounding residue
- established a new v0.6 product thesis in `docs/drivemind-v0.6-product-thesis.md`

### Added
- new core references:
  - `skill/references/drift-prevention.md`
  - `skill/references/boundary-preservation.md`
  - `skill/references/continuity-preservation.md`
  - `skill/references/stuck-recovery.md`
  - `skill/references/closure-compounding.md`

### Refactored
- downgraded older reference files into compatibility / redirect layers so the new v0.6 structure becomes the real spine of the skill
- clarified that old units such as persistence, escalation, decision gates, session handoff, task typing, and review style now belong under the stronger anti-degradation structure rather than acting as separate doctrine centers

### Notes

`v0.6.0` is a real product-center reset.

It does not merely polish the previous doctrine.
It changes the standard by which DriveMind should be judged:

# not “does it sound mature?”
# but “does it reduce degradation in meaningful long-horizon work and leave behind stronger future defaults?”

Primary reading for this release:
- `docs/drivemind-v0.6-product-thesis.md`
- `skill/SKILL.md`
- `skill/references/drift-prevention.md`
- `skill/references/boundary-preservation.md`
- `skill/references/continuity-preservation.md`
- `skill/references/stuck-recovery.md`
- `skill/references/closure-compounding.md`

## `v0.5.0` - 2026-03-20

### Added
- `PLAN.md` to define the next DriveMind upgrade around collaboration doctrine rather than rigid procedure
- `docs/github-release-v0.5.0.md` for the new release line

### Changed
- upgraded product definition from a reliability-focused framing toward an explicit collaboration doctrine and reliability layer
- re-centered the product around clear goals, clear boundaries, and enough freedom to act
- updated README, README.zh-CN, PROJECT, principles, activation, interaction model, roadmap, brand-kit, GitHub presence, FAQ, promo materials, and skill guidance to reflect the new doctrine
- clarified collaboration guidance with `steady, not silent` and `concise, not absent`
- made explicit that DriveMind should not become an operations manual

## `v0.4.0` - 2026-03-17

### Added
- `session-handoff.md` for cross-session continuity: passive by default, triggered by user signals, one-line prompt in Execution/Intensive mode at natural stopping points
- `confidence-signaling.md` for structured uncertainty communication: three levels (evidence-based, inference, hypothesis) with verification paths and anti-pattern guidance
- zero-config auto-detect install: `bootstrap.sh` and `bootstrap.ps1` now detect installed AI tools and install to all targets automatically — no flags required
- `irm ... | iex` support for Windows PowerShell one-liner install

### Changed
- translated `decision-gates.md`, `stuck-resolution.md`, and `task-typing.md` from Chinese to English for language consistency across all skill references
- updated `SKILL.md` description to include session continuity triggers
- updated `SKILL.md` to reference `session-handoff.md` and `confidence-signaling.md`
- removed internal development note from `SKILL.md`
- updated `docs/roadmap.md` to reflect accurate v0.4 direction
- simplified README install section: zero-param command is now the primary path, advanced options folded into a collapsible block

## `v0.3.0` - 2026-03-12

### Added
- `task-typing.md` for lightweight internal task classification
- `decision-gates.md` for boundary, pressure, release/production, external representation, and data/deletion decisions
- `stuck-resolution.md` for blocker diagnosis and momentum recovery
- a compression rule to keep short answers natural and avoid visible framework over-expansion
- release notes for the formal v0.3.0 iteration

### Changed
- upgraded DriveMind from a validated reliability layer toward a sharper decision layer
- strengthened persistence behavior so stuck work is resolved by blocker diagnosis rather than brute repetition
- strengthened safety-boundary behavior so urgency does not weaken authorization or release discipline
- improved output guidance so judgment, boundary, and stuck tasks can stay concise while still preserving clarity and next-step value
- updated mode guidance so higher intensity never weakens authority boundaries
- refined escalation guidance with clearer high-pressure and missing-authority handling

## `v0.2.0` - 2026-03-11

### Added
- `review-style-guide.md` for structured-but-natural retrospectives
- release notes for the validated v0.2.0 iteration

### Changed
- expanded natural-language trigger coverage for calm persistence and boundary-aware instructions
- renamed the strongest mode from `Focused` to `Intensive`
- improved non-trivial output guidance so implicit activation expands beyond one-line acknowledgements
- changed review guidance from rigid template enforcement to structured-and-adaptive retrospectives
- preserved a stable six-part review spine while reducing mechanical phrasing

## `v0.1.0` - 2026-03-11

### Added
- the first reusable DriveMind skill package
- one-click bootstrap installers for Codex and Claude Code
- portable local install scripts for personal, project, and custom targets
- source-available licensing under BUSL-1.1
- logo source assets and rendering script
- bilingual public README entry points in English and Chinese
- governance docs: contributing, changelog, conduct, security, and trademark policy
- a minimal GitHub Actions validation workflow
- issue contact guidance with public issues and maintainer email
- GitHub About, topic, and social preview copy for repository presentation.

### Changed
- unified product language around calm reliability, safety boundaries, and human collaboration
- consolidated repeated brand copy into a single brand kit
- cleaned redundant logo exports and kept source assets only
- aligned roadmap language under the `v0.x` version line
- added README badges for version, license, and install targets.
