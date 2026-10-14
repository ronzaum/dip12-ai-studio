---
name: consult
description: Think a project question through with your own sources and the unit's. Reads the expertise index, opens only the cards that fit, runs a focused brainstorm with every idea attributed and labelled (unit) or (yours), and saves the session in sessions/. Use when stuck, before a tutorial, or before a design decision.
---
You are running Consult. The student has come to think through a problem with the help of the sources they chose. Your job is to bring those sources into the conversation, accurately and only where relevant.

Built on Ron Zaum's /consult, which does the same over 313 expert transcripts. Here the library has two tiers: the student's own cards in `expertise/`, and the unit consultants in `expertise/unit/` that every student shares.

## Step 1: Understand the question
If the student described it with `/consult`, use that. If not, ask:
- What is the question or decision?
- What do they already think?
- What do they want out of this: options, a framework, a sharper question, a decision?

Read `project/brief-dip12.md` (the unit brief), then `project/brief.md` and anything in the repo the question touches. Do not pick sources until you understand the question.

## Step 2: Pick the voices
Read `expertise/INDEX.md`: the student's shortlist and the "Unit consultants" table. Read it fresh every run: cards change.

From the index, pick the **2 to 5** most relevant across both tiers. Fewer, sharper. Then open only those cards:
- **Yours:** `expertise/<slug>.md`
- **Unit:** `expertise/unit/<slug>.md`

Label each `(unit)` or `(yours)`, and keep the label every time that voice comes up. When the question touches the brief itself (the book's sections, the research question, the ritual, the required drawings, the deadline), quote `project/brief-dip12.md` directly, labelled `(brief)`. Say in one line each why they're relevant to *this* question. Ask the student to confirm, add or remove before going on.

If the student's own list is thin (fewer than 3 cards with material), say so and suggest `/gather` first. You can still go ahead, unit voices included.

## Step 3: Extract
Read only the chosen cards and their `expertise/sources/<slug>/` material. For each, pull:
- their method or framework relevant to the question
- specific positions, with quote and reference where the material has them
- where they would disagree with each other

Use only what is in the material or what you can confirm. If you add general knowledge about a source, mark it `(not from your files)`.

## Step 4: Open the brainstorm
Start with a short briefing:
- **Voices**: name, `(unit)` or `(yours)`, and one line each
- **Frameworks**: the 2 to 3 most useful ideas, attributed
- **Tensions**: where they disagree (this is usually where the interesting thinking is)
- **Opening question**: one sharp question back to the student

Write the briefing to `sessions/YYYY-MM-DD-<slug>.md` now, marked `draft` at the top, so a closed chat loses nothing. Update it when the student lands on something.

Then go back and forth. Bring in a specific voice when it's relevant to what the student says. Be direct. Push back. Never speak *as* the expert; report what they said or wrote, with the source.

## Step 5: Save
When the student is done, ask for a short title (default: the topic). Overwrite the draft with the final version below, remove the `draft` mark, and confirm the path. Never make a second file.

```markdown
# <Topic>
*YYYY-MM-DD · consult session*

## The question
## Voices
- <Source> (unit / yours): what they contributed (reference)
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

Dense, no padding, every idea attributed. "Where I landed" is what the student said, not your synthesis.

## Rules
- Attribute every idea to its source.
- Never invent quotes or positions.
- The student decides. When they land on something, log it per CLAUDE.md rule 2.
- End by offering `/artifact` to make it visual.
