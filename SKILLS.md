# SKILLS.md

A skill is a markdown file of instructions you run with `/name`. It makes a task repeatable: same method, same quality, every time. Skills live in `.claude/skills/<name>/SKILL.md`. Open them. They are plain text. Change them until they work the way you do.

**Why skills are personal.** A prompt is used once. A skill is your way of working, written down. Two students with the same tools and different skills will produce different work. Over the year, your skills become part of your practice.

---

## IN THIS REPO

| Skill | What it does | Origin |
|---|---|---|
| `/explore` | Asks questions until the task is clear. Makes nothing. | Ron's, adapted |
| `/create-plan` | Turns the exploration into a step-by-step plan in `plans/todo/`. | Ron's, adapted |
| `/execute` | Carries out a plan step by step and tracks progress. | Ron's, adapted |
| `/review` | Retraces every part of a piece of work, then judges it. | Ron's (`review-no-code`), adapted |
| `/explain` | Re-explains the last answer in plain English, decision first. | Ron's, adapted |
| `/commit` | Saves everything to GitHub in one step. | Ron's, adapted |
| `/consult` | Brainstorms a question through your own sources and the unit consultants, each voice labelled `(unit)` or `(yours)`. | Ron's, rebuilt for your library |
| `/save` | Saves a consult session as a standalone file. | Ron's, adapted |
| `/gather` | Finds, checks and files sources for your 3/3/3, design and practice. `/gather promote <name>` makes a unit consultant yours. | New for this course |
| `/artifact` | Turns work into a one-page visual in `outputs/`, styled by `TASTE.md`. | New for this course |
| `/decide` | Logs what AI gave vs what you chose, and why. | New for this course |
| `/familiar` | Searches your Familiar screen history. | From Familiar (third party) |
| `/superpower` | Three ways to make what you're building better without making it bigger. | Ron's (`superman`), adapted |
| `/caveman` | Shorter replies, fewer tokens. On by default in lite. Say `normal mode` to switch off. | Third party (Julius Brussee, MIT) |

**The loop:** `/explore` → `/gather` → `/consult` → `/artifact` → `/decide` → `/commit`
**For bigger tasks:** `/explore` → `/create-plan` → `/execute` → `/review`

---

## RON'S SKILLS · FOR REFERENCE

What a working set looks like after a year. Most are tied to Ron's company and clients, so they are not in this repo. They show the range: thinking, building, reviewing, communicating, automating.

**Thinking and planning**
- `explore`, `create-plan`, `execute`: the build loop above
- `consult`: brainstorm through 313 expert interview transcripts
- `save`, `log-scenario`: keep sessions and past situations as reusable precedent
- `superman`: three ideas to make something better without making it bigger
- `explain`, `learning-opportunity`: switch the AI from doing to teaching
- `adi`: read a conversation through one mentor's lens

**Reviewing**
- `review`, `review-no-code`, `peer-review`: judge work, then judge another model's judgement of it
- `check-sweep`: review a full drawing set against a method, with no false positives

**Meetings and records**
- `call-analysis`: turn a call transcript, notes and screen captures into tasks and a timeline ([public](https://github.com/ronzaum/skills))
- `live-board`: draw an evolving Excalidraw board live from a call
- `familiar`: search screen history

**Making things**
- `new-deck`, `new-report`, `new-asset`, `pre-sales-report`: start a deck, report or graphic from a house template
- `blog-post`: publish a post to a website

**Running the work**
- `daily-update`, `deployment-tasks`, `crm`, `client-mail`, `notify-ron`, `demo-prep`, `create-client-environment`: automations around clients and the team
- `commit`, `document`, `create-issue`: keep code and records tidy

**Personal**
- `image-input`, `merge-output`: transcribe and translate handwritten family diaries, comparing several AI models

---

## CLAUDE'S BUILT-IN SKILLS · WORTH KNOWING

These come with Claude (Anthropic). Use them by asking in plain words.

| Skill | Use it for |
|---|---|
| `deep-research` | Thorough research across many sources, written up as a report. |
| `import-memory` | Bring what ChatGPT or another assistant knows about you into Claude. |
| `pdf`, `docx`, `pptx`, `xlsx` | Read and make PDF, Word, PowerPoint and Excel files. |

---

## WRITE YOUR OWN

1. Notice a task you repeat (e.g. "turn my week's photos into a progress page").
2. `/explore` it: what goes in, what comes out, where it goes wrong by hand.
3. `/create-plan` the skill. Save it as `.claude/skills/<name>/SKILL.md` and add a row to the table above.
4. Run it three times. Fix what went wrong each time.
5. Share it with someone in the unit. Their version will be different. That's the point.
