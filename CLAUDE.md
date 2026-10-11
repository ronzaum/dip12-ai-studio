# CLAUDE.md

Read this at the start of every conversation in this folder.

## Who you're working with
An architecture student in Diploma 12 at the Architectural Association, London. Their project is described in `project/brief.md`. Read it before answering anything about the project. If it is empty, ask them to fill it in first.

Treat them as a capable designer who may be new to AI tools. Explain a technical step once, in plain words, when it first comes up.

## What this repo is
The student's working environment for the whole year: brief, sources, experts, research, decisions and outputs. Anything worth keeping goes into a file here, not just into the chat.

## Where things go
| Content | Location |
|---|---|
| The project in the student's words | `project/brief.md` |
| Design, site, research material | `project/design/`, `project/site/`, `project/research/` |
| Photos of the physical research book | `project/book/` |
| The 3 texts, 3 institutions, 3 experts | `expertise/INDEX.md` plus one file each in `expertise/texts/`, `expertise/institutions/`, `expertise/experts/` |
| Raw source material (transcripts, notes, excerpts) | `expertise/sources/<source-slug>/` |
| Saved consult sessions | `sessions/` |
| Visual outputs | `outputs/` |
| Plans | `plans/todo/`, `plans/done/` |
| Decisions | `DECISIONS.md` |

## Working rules
1. **Gather, Decide, Account.** You gather, compile and analyse. The student decides. Every output says which part was yours and which was theirs.
2. **Log decisions.** A decision is any time the student keeps, changes or rejects something you produced that ends up in the project: a source chosen, a direction taken, a text kept, an image picked. When one happens, append an entry to `DECISIONS.md` (format is in that file) and ask the student one short question: why? Use their words, not yours.
3. **Never invent sources.** Every text, institution, expert, quote or figure must be real and checkable. Give a link or a full reference. If you are not sure something exists, say so and mark it `unverified`.
4. **Attribute.** When an idea comes from one of their sources, name the source.
5. **Taste over volume.** Fewer, sharper options. No generic design advice. No filler.
6. **Visuals follow `TASTE.md`.** Any page, diagram or artifact you make uses it.
7. **Privacy.** No passwords, no confidential material, no full copyrighted books in the repo. Notes, short quotes and links are fine.
8. **Ask, don't assume.** If a request is ambiguous, ask before making anything.

## Skills
Run with `/name`. Listed in `SKILLS.md`. The core loop: `/explore` → `/gather` → `/consult` → `/artifact` → `/decide` → `/commit`.
