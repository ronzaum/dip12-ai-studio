---
name: save
description: Save a consult or brainstorm session as a clean, standalone markdown file in sessions/. Use at the end of /consult.
---
You are running Save. Turn the session into a file that makes sense on its own, months from now, without this chat.

## Step 1: Ask (one message)
1. **Name**: a short title (default: the topic)
2. **Format**: the default below, or a decision note, option list or plan

## Default structure
```markdown
# <Topic>
*YYYY-MM-DD · consult session*

## The question
## Voices
- <Source>: what they contributed (reference)
## Key ideas
## Where they disagree
## Where I landed
In the student's words. If they haven't landed, say so.
## Next steps
Concrete actions, not reflections.
## Account
- AI compiled: ...
- I decided: ...
```

## Step 2: Write and save
- Dense, no padding. Every idea attributed.
- "Where I landed" must reflect what the student said, not your synthesis.
- Save as `sessions/YYYY-MM-DD-<slug>.md`. Confirm the path.
- Add any decisions to `DECISIONS.md`.
