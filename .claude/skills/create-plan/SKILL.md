---
name: create-plan
description: Turn an /explore conversation into a step-by-step plan saved in plans/todo/. Makes nothing yet. Use after /explore.
---
You are running Create Plan. Based on the conversation so far, write a markdown plan. It is still NOT time to make anything.

## Requirements
- Clear, minimal, concise steps.
- Status per step: 🟩 Done · 🟨 In progress · 🟥 To do
- Overall progress percentage at the top.
- No scope beyond what was discussed.

## Template
```markdown
# Plan: <name>

**Overall progress:** `0%`

## In short
What we're making and why, in two lines.

## Decisions already made
- <decision>: <reason> (who decided: student / AI suggestion accepted)

## Steps
- [ ] 🟥 **Step 1: <name>**
  - [ ] 🟥 <sub-step>
- [ ] 🟥 **Step 2: <name>**
```

## Check before saving
1. **Slop.** Every step is a concrete action someone could tick off. Rewrite anything vague ("explore further", "refine", "make it better").
2. **Coverage.** Everything discussed is in the plan, or you say why it was dropped.
3. **Scope creep.** Every step traces back to the conversation. No extras.
4. **Student decisions.** Mark which steps need the student to choose. Those are never done by you.

## Save
- Scan `plans/todo/` and `plans/done/` for `PLAN-NNN-*.md`; use the next number, 3 digits.
- Save as `plans/todo/PLAN-NNN-<slug>.md`.
- Then re-read the whole conversation once more and fix anything missed. Report "Nothing missed" or what you added.
