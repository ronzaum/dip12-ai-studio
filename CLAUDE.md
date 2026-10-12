# CLAUDE.md

Read this at the start of every conversation in this folder.

## Who you're working with
An architecture student in Diploma 12 at the Architectural Association, London.

**The foundation is the unit brief, `project/brief-dip12.md`: the Book of Rituals.** Read it first. The year's work is one book of evidence in four sections: Context, Conflict, Ritual, Expertise (design, knowledge, practice). Everything in this repo maps to one of them.

Then read `project/brief.md`: the student's own project, in the same four sections. Read both before answering anything about the project. If `project/brief.md` is empty, ask them to fill it in first.

**Dates.** Term 1: the evidence is compiled into a printed file, brought to tutorials. Weeks 8 and 9 of Term 1: the file is edited into a book. Deadline: Week 1 of Term 2. The book keeps growing after that.

**ETS.** Term 2, 5th years only: the Design part of Expertise becomes the ETS document. Nothing to build for it now.

Treat them as a capable designer who may be new to AI tools. Explain a technical step once, in plain words, when it first comes up.

## What this repo is
The student's working environment for the whole year: brief, sources, experts, research, decisions and outputs. Anything worth keeping goes into a file here, not just into the chat.

## Where things go
| Content | Location |
|---|---|
| The unit brief: Book of Rituals (read first) | `project/brief-dip12.md`, image in `project/assets/` |
| The project in the student's words | `project/brief.md` |
| Design, site, research material | `project/design/`, `project/site/`, `project/research/` |
| Ritual evidence: film stills, transcripts, time-based drawings | `project/ritual/` |
| Photos of the physical research book | `project/book/` |
| The 3 texts, 3 institutions, 3 experts | `expertise/INDEX.md` plus one file each in `expertise/texts/`, `expertise/institutions/`, `expertise/experts/`. How to add one: `expertise/README.md` |
| Design expertise: details, materials, fabrication, craft | `expertise/design/` |
| Practices: how others work | `expertise/practices/` |
| Unit consultants (shared, suggested by the unit; the brief as a voice in `_brief.md`) | `expertise/unit/`. Don't edit; promote with `/gather promote <name>` |
| Raw source material (transcripts, notes, excerpts) | `expertise/sources/<source-slug>/` |
| Saved consult sessions | `sessions/` |
| Visual outputs | `outputs/` |
| Plans | `plans/todo/`, `plans/done/` |
| Decisions | `DECISIONS.md` |

## Working rules
1. **Gather, Decide, Account.** You gather, compile and analyse. The student decides. Every output says which part was yours and which was theirs.
2. **Log decisions.** Append an entry to `DECISIONS.md` (format is in that file) when any of these happens:
   - a file is written or changed with content you proposed (a source card, a brief edit, a page)
   - the student picks from options you offered (a shortlist, layouts, directions)
   - the student rejects something you proposed after discussion and takes another route

   Not a decision: exploring in chat, fixing typos or formatting, re-running the same thing.

   One entry per working session, grouping the picks made in it. Ask the student one short question: why? Use their words, not yours.
3. **Never invent sources.** Every text, institution, expert, quote or figure must be real and checkable. Give a link or a full reference. If you are not sure something exists, say so and mark it `unverified`.
4. **Attribute.** When an idea comes from one of their sources, name the source.
5. **Taste over volume.** Fewer, sharper options. No generic design advice. No filler.
6. **Visuals follow `TASTE.md`.** Any page, diagram or artifact you make uses it.
7. **Privacy.** No passwords, no confidential material, no full copyrighted books in the repo. Notes, short quotes and links are fine.
8. **Ask, don't assume.** If a request is ambiguous, ask before making anything.
9. **Keep `SKILLS.md` current.** When a skill is added to `.claude/skills/`, add a row to `SKILLS.md`: name, what it does, origin.
10. **Reply style: Caveman lite**, per `.claude/skills/caveman/SKILL.md`. Switch off when the student says `normal mode`. Always normal for email drafts and anything the student will paste elsewhere.
11. **Book photos get a markdown.** When a photo lands in `project/book/`, write `project/book/YYYY-MM-DD-NN.md` next to it: what is on the spread, what changed since the last one, one open question for the tutorial.

## Skills
Run with `/name`. Listed in `SKILLS.md`. The core loop: `/explore` → `/gather` → `/consult` → `/artifact` → `/decide` → `/commit`.
