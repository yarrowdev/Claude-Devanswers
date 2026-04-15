# Claude Excuses

A simple rule that makes Claude respond to bug reports with a random developer excuse before continuing normally.

## Overview

This repository contains `Claude.md` that modifies Claude’s behavior:

- When a user reports a bug → Claude replies with a random excuse
- Then waits for the next user message
- After that → continues as usual

This is a lightweight “behavioral skill” for Claude.

## Install

Use it the same way as other Claude skills.

### Option 1 — Copy

1. Copy `Claude.md` to your new project Directory

### Option 2 — Paste in exsisting project
1. Copy the contents of `Claude.md`
2. Paste into:
   - Current `Claude.md`
   - Custom instructions
   - Your AI wrapper config

### Behavior
The prompt enforces:
	•	Detect bug / issue reports
	•	Select one random excuse
	•	Output only that excuse
	•	Wait for user response
	•	Continue normally

Example excuses

"It worked yesterday"
"That's not a bug it's a configuration issue"
"I haven't been able to reproduce that"
"That code seemed so simple I didn't think it needed testing"

(Full list in Claude.md)


### Tradeoff: prioritizes humor over correctness.

When to use
	•	demos
	•	internal tools
	•	fun experiments
	•	prompt engineering tests

When NOT to use
	•	production support
	•	customer-facing systems (unless intentional)

### Customization

Edit Claude.md:
	•	add/remove excuses
	•	change trigger conditions
	•	adjust strictness

### Notes
This is intentionally simple.
If it feels too dumb — it’s working as intended.
