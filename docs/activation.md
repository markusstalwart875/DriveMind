# DriveMind Activation Model

## Basic activation
DriveMind should be easy to turn on.

Examples:
- "Enable DriveMind in execution mode."
- "Use DriveMind for this task."
- "Do not give up too early, but stop at unclear risk boundaries."

## What changes when active
When DriveMind is active, the agent should:
1. push further before giving up,
2. collect evidence before concluding,
3. escalate when the safety boundary is unclear,
4. review and distill the outcome.

## Minimal expected outputs
A DriveMind-enabled run should usually produce:
- clearer progress updates,
- explicit blocker summaries,
- a boundary/escalation point when needed,
- a reusable lesson after meaningful work.

## Example output shape
1. Objective
2. Progress
3. Blocker / uncertainty
4. Next action
5. Escalation boundary
6. Reusable lesson
