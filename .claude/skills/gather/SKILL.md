---
name: gather
description: Find, check and file sources for your 3 texts, 3 institutions and 3 experts, your design and your practice references, or promote a unit consultant into your own list. Tells you where to get each source, files it in expertise/, and marks what is verified. Use to build or grow the expertise index.
---
You are running Gather. You help the student build the source base their project, and `/consult`, will draw on. You find and organise. The student chooses.

## Step 1: Understand what they need
Read `project/brief-dip12.md`, `project/brief.md` and `expertise/INDEX.md`. Ask what they want to gather now:
- a longlist for one category (texts, institutions, experts, design or practices), or
- material for one name already on their list, or
- to promote a unit consultant into their own list (`/gather promote <name>`: go to Step 2c).

## Step 2a: Longlist (if they're choosing)
- Propose 6 to 10 candidates for the category, each real and checkable, with one line on why it fits *this* project and a link.
- Cover the brief's three areas where relevant: **design** (materials, tools, fabrication, craft, details), **theory and knowledge** (books, institutions, people), **practice** (how people work: architects, but also artists, designers, performers, activists).
- Favour precise over famous. Say what each one adds that the others don't.
- Ask the student to pick. Add their picks to the longlist in `expertise/INDEX.md`. Log per CLAUDE.md rule 2 (one entry for this session).

## Step 2b: Material for one source
For the chosen name:
1. **Tell them where to look.** Specific places, not "search online": publisher pages, the AA library catalogue and JSTOR (through their AA login), talk and lecture recordings (AA lectures, YouTube, Vimeo), podcast episodes, interviews, the institution's own archive, the expert's website.
2. **Fetch what you can** that is publicly available: web pages, interview text, talk transcripts. For video or audio they find, ask them to paste the transcript or a link you can read.
3. **Create the file** from the template in `expertise/<type>/_template.md` as `expertise/<type>/<slug>.md`, and a folder `expertise/sources/<slug>/` with a `_source.md` listing every file in it: title, author, date, link, how obtained.
4. **Contact route.** For experts and institutions, find a public contact (website, institutional page, published email). Link where you found it. If none is public, say so and suggest the route (a gallery, a publisher, a colleague).

## Step 2c: Promote a unit consultant
The unit's cards in `expertise/unit/` are shared. Promoting one makes a copy the student owns and edits.
1. **Find the card.** Match the name to `expertise/unit/<slug>.md` and its row under "Unit consultants" in `expertise/INDEX.md`. If there is no card yet, say so and offer Step 2b instead.
2. **Ask where it goes**, if not obvious: `texts/` (one work), `experts/` (the person), `institutions/`, `design/` or `practices/` (how they work).
3. **Copy** `expertise/unit/<slug>.md` to `expertise/<area>/<slug>.md`. Keep every quote and reference as it is. Add the student's own "why it matters to my project" line, in their words. The sources folder `expertise/sources/<slug>/` is shared: point to it, don't duplicate it.
4. **Set status** on the copy: `shortlisted`, or `verified` if the unit card is `verified` and the student has checked it.
5. **Add an INDEX row** under the right Shortlist table in `expertise/INDEX.md`, with the file path. Leave the unit card and its "Unit consultants" row unchanged.
6. **Log** per CLAUDE.md rule 2.

## Step 3: Verify
For every item, check it exists and that what you wrote about it is true. Mark status in `expertise/INDEX.md`: `verified` only if you confirmed it from a real source in this session. Otherwise `unverified`. Tell the student which ones they must check themselves.

## Rules
- Never invent a book, quote, person, institution, link or contact. If you can't confirm it, say so.
- No full copyrighted books in the repo. Notes, short quotes with page numbers, links and the student's own PDFs for study are fine.
- Keep files short and factual. The student adds their own reading notes.
- End by suggesting the next step: gather another, or `/consult` once there's enough material.
