---
name: commit
description: Save all changes to GitHub in one step. Use at the end of every working session.
---
You are running Commit: save and upload the student's work.

## Steps
1. Check what changed (`git status`).
2. Do NOT include passwords, `.env` files, or very large files (over 50 MB). Warn the student if you see any.
3. Stage everything else.
4. Write a one-line message under 72 characters saying what changed, in plain words ("Added three experts and first consult session").
5. Commit and push. If there is no upstream yet, set it and retry.
6. Confirm in one line. If nothing changed, say so.

## First time only
If the push fails because Git doesn't know who they are, explain in one sentence and help them set `git config user.name` and `user.email`. If GitHub asks them to sign in, tell them what to click.
