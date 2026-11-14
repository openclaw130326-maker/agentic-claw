---
issue_id: ISSUE-0000
from_agent: <sender-agent-id>
severity: S3            # S1 down · S2 broken feature · S3 degraded · S4 question
target: <system | agent | skill | repo | service>
request: diagnose       # diagnose | repair | review
approval_needed_for: [] # optional, e.g. [restart, config]
deadline: null          # optional, ISO 8601 with +08:00
---

## Symptom
What is wrong, in one or two sentences.

## Expected
What should happen instead.

## Repro
Exact command or steps, and how often it fails (e.g. 5/5).

## Evidence
Paths and line ranges only, e.g. ~/.openclaw/logs/gateway.log:1200-1260.
No pasted secrets, tokens or customer data.

## Already tried
What the sender did, so Claw doesn't repeat it.
