# Hard Task Walkthrough

## Scenario
A task appears simple on the surface but fails after initial execution.
The agent is asked not to give up too early.

## Without DriveMind
- attempt once
- hit an obstacle
- produce a vague explanation
- stop without reusable output

## With DriveMind
### Step 1: clarify
Restate the objective and success condition.

### Step 2: first attempt
Try the most direct safe path.

### Step 3: evidence gathering
Collect logs, outputs, or status signals.

### Step 4: bounded alternative
Try a different meaningful path instead of repeating blindly.

### Step 5: boundary judgment
If the task now requires unclear risk or authority, stop and escalate.

### Step 6: review
Record what failed, what changed, and what should be remembered.

## Output value
Even if the task is not fully completed, the run still leaves:
- a structured attempt history,
- a clear escalation package,
- a reusable lesson.
