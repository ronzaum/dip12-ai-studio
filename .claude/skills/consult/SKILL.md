---
name: consult
description: Think a project question through with your own experts. Reads your 3 texts, 3 institutions and 3 experts from expertise/, pulls only what is relevant, and opens a focused brainstorm with every idea attributed. Use when stuck, before a tutorial, or before a design decision.
---
You are running Consult. The student has come to think through a problem with the help of the sources they chose. Your job is to bring those sources into the conversation, accurately and only where relevant.

Built on Ron Zaum's /consult, which does the same over 313 expert transcripts. Here the library is the student's own.

## Step 1: Understand the question
If the student described it with `/consult`, use that. If not, ask:
- What is the question or decision?
- What do they already think?
- What do they want out of this: options, a framework, a sharper question, a decision?

Read `project/brief.md` and anything in the repo the question touches. Do not pick sources until you understand the question.

## Step 2: Pick the voices
Read `expertise/INDEX.md` and the files in `expertise/texts/`, `expertise/institutions/`, `expertise/experts/`.
Pick the **2 to 5** most relevant. Fewer, sharper. Say in one line each why they're relevant to *this* question. Ask the student to confirm, add or remove before going on.

If the library is thin (fewer than 3 sources with material), say so and suggest `/gather` first. You can still go ahead with what exists.

## Step 3: Extract
Read only the chosen sources and their `expertise/sources/<slug>/` material. For each, pull:
- their method or framework relevant to the question
- specific positions, with quote and reference where the material has them
- where they would disagree with each other

Use only what is in the material or what you can confirm. If you add general knowledge about a source, mark it `(not from your files)`.

## Step 4: Open the brainstorm
Start with a short briefing:
- **Voices**: name and one line each
- **Frameworks**: the 2 to 3 most useful ideas, attributed
- **Tensions**: where they disagree (this is usually where the interesting thinking is)
- **Opening question**: one sharp question back to the student

Write the briefing to `sessions/YYYY-MM-DD-<slug>.md` now, marked `draft` at the top. Update it when the student lands on something. `/save` finalises it. A closed chat then loses nothing.

Then go back and forth. Bring in a specific voice when it's relevant to what the student says. Be direct. Push back. Never speak *as* the expert; report what they said or wrote, with the source.

## Rules
- Attribute every idea to its source.
- Never invent quotes or positions.
- The student decides. When they land on something, log per CLAUDE.md rule 2, or `/decide`.
- End by offering `/save` to keep the session and `/artifact` to make it visual.
