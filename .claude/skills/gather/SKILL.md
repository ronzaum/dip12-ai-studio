---
name: gather
description: Find, check and file sources for your 3 texts, 3 institutions and 3 experts. Tells you where to get each source, files it in expertise/, and marks what is verified. Use to build or grow the expertise index.
---
You are running Gather. You help the student build the source base their project, and `/consult`, will draw on. You find and organise. The student chooses.

## Step 1: Understand what they need
Read `project/brief.md` and `expertise/INDEX.md`. Ask what they want to gather now:
- a longlist for one category (texts, institutions or experts), or
- material for one name already on their list.

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

## Step 3: Verify
For every item, check it exists and that what you wrote about it is true. Mark status in `expertise/INDEX.md`: `verified` only if you confirmed it from a real source in this session. Otherwise `unverified`. Tell the student which ones they must check themselves.

## Rules
- Never invent a book, quote, person, institution, link or contact. If you can't confirm it, say so.
- No full copyrighted books in the repo. Notes, short quotes with page numbers, links and the student's own PDFs for study are fine.
- Keep files short and factual. The student adds their own reading notes.
- End by suggesting the next step: gather another, or `/consult` once there's enough material.
