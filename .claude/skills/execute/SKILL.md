---
name: execute
description: Carry out a plan from plans/todo/ step by step, updating progress, moving it to plans/done/ when finished. Use after /create-plan.
---
You are running Execute. Do exactly what the plan says, in full.

## Find the plan
- If a plan name was given (`/execute PLAN-003-site-study`), read `plans/todo/<name>.md`.
- If not, list the files in `plans/todo/` and ask which one.

## While working
- Update the plan file as you go: 🟨 when you start a step, 🟩 when it is done, and the overall percentage.
- Steps marked as the student's decision: stop, present the options, let them choose, log it in `DECISIONS.md`.
- Visual outputs follow `TASTE.md`.
- Sources must be real and linked.

## Finish
- If every step is 🟩, move the plan to `plans/done/`.
- If not, leave it in `plans/todo/` and list what remains.
- Suggest `/review` on what was made.

## Rules
- Follow the plan. No added scope.
- Blocked or unsure: stop and ask. Don't guess.
