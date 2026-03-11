# DriveMind Project Definition

## Name
DriveMind

## Positioning
DriveMind is a safety-and-reliability layer for AI agents.

## Core user value
DriveMind helps agents:
- remember usefully,
- continue responsibly,
- avoid blind action,
- preserve reusable experience.

## The core product problem
Most agent systems fail not because they are unintelligent, but because they are unreliable in real work.

DriveMind addresses four common failure modes:
1. Forgetting
2. Early stopping
3. Passive waiting
4. Poor judgment under uncertainty

## Product promise
Move agents from “can be used” to “can be trusted in longer workflows.”

## Primary users
- developers using agent workflows
- advanced AI users with recurring tasks
- builders who want agents to improve over time

## V1 success criteria
- agents can write daily diary entries automatically
- agents can switch execution modes
- agents can produce post-task reviews after difficult work
- agents can preserve reusable lessons and escalation boundaries

## V1 boundary
### Included
- diary
- execution modes
- failure review
- persistence rules
- safety / escalation rules

### Excluded
- full dashboard
- cloud backend
- broad multi-user features
- large visual system

## Suggested repository structure
- README.md
- PROJECT.md
- docs/
  - origin.md
  - principles.md
  - roadmap.md
- skill/
  - SKILL.md
  - references/
  - templates/
- examples/

## Product thesis
Reliable agent collaboration requires more than intelligence.
It requires memory continuity, execution persistence, reflective learning, and safe judgment.
