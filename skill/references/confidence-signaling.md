# Confidence Signaling

Legacy compatibility note.

DriveMind v0.6 no longer treats confidence signaling as a standalone center of the system.
It now belongs primarily inside:
- `drift-prevention.md`
- `stuck-recovery.md`

---

## Read this file only when
- the work is drifting because confidence is outrunning evidence
- the work is stuck and the next move depends on how certain the agent really is

If neither is true, do not read this file.

---

## Core rule

Confidence should track evidence, not motion.
If acting on inference, say so briefly.
If acting on evidence, name the evidence that matters.

---

## Preferred destination

For most real use, read:
- `drift-prevention.md` for thread integrity
- `stuck-recovery.md` for blocker diagnosis and bounded next moves
