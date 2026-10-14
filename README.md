**DIPLOMA 12 · AI SESSIONS** &nbsp;&nbsp;&nbsp; Questions: ronzaum@gmail.com

# YOUR AI WORKING ENVIRONMENT

**AI makes options cheap. Taste decides which one is right. This repo is where your project lives from now on: your brief, your sources, your experts, your decisions. Claude reads it before it answers. The more you put in, the better it knows your project.**

---

## TOOLKIT · HOW IT FITS

| | |
|---|---|
| **Claude** | The agent. Reads the files in this folder, writes new ones, runs tasks. |
| **Git + GitHub** | The memory. Every change is a commit you can go back to, saved online so nothing lives on one laptop. |
| **Familiar** | The record. Turns what you do on screen into text Claude can search. On your laptop only. |

```
  you ──► Claude ──reads/writes──► this repo ──commit──► GitHub
             ▲
             └── Familiar (what you did on screen)
             └── Connectors (Drive, Gmail, Notion, Calendar…)
```

---

## SET UP · SESSION 1

**01 · GET YOUR OWN COPY**
1. On this page, click **Use this template** → **Create a new repository**.
2. Name it `dip12-<your-name>`. Set it to **Private**. Create.
3. Open Terminal and paste (swap in your username and name):
   `git clone https://github.com/<username>/dip12-<your-name> ~/Documents/dip12-<your-name>`

**02 · OPEN IT IN CLAUDE**
1. Open the Claude desktop app → **Code** tab.
2. Choose the folder `~/Documents/dip12-<your-name>`.
3. Type: `Read CLAUDE.md and README.md and tell me what this repo is for.`

**03 · WRITE YOUR FIRST MARKDOWN**
1. Open `project/brief.md`. Fill it in yourself: your project in your words.
2. This is the file Claude will lean on most. Keep it short and true.

**04 · CONNECT YOUR APPS**
1. In the Claude app, open **Settings → Connectors**.
2. Connect what you use: Google Drive, Gmail, Calendar, Notion, Dropbox, OneDrive.
3. Test it: `What connectors do you have? Find my latest file about <your site>.`

**05 · SWITCH ON FAMILIAR**
1. Check Familiar is running in the menu bar.
2. Test it: `/familiar what did I work on today?`

**06 · SAVE**
1. Type `/commit`. Your work is now on GitHub.
2. Do this at the end of every working session.

---

## THE WORK · DEVELOPING EXPERTISE

Choose **3 texts, 3 institutions, 3 experts** that can guide your project. Then go one step further: **contact one expert, contact one institution, order one book.**

| Step | Skill | What happens |
|---|---|---|
| 01 | `/explore` | Talk your project through. Claude only asks questions. Nothing is made yet. |
| 02 | `/gather` | Claude tells you where to find each source and files it in `expertise/`. You check it exists. |
| 03 | `/consult` | Ask a real project question. Claude answers through your sources and the unit's, quoting them, and saves the session. |
| 04 | `/artifact` | Turn the result into a visual page in `outputs/`, styled by `TASTE.md`. |
| 05 | `/commit` | Save. |

---

## HOW IT WORKS

**Markdown (.md).** Plain text with a few symbols: `#` for a heading, `-` for a list, `**bold**`. Humans and AI read it equally well. Every file in this repo is markdown.

**README.md vs CLAUDE.md.** `README.md` is for people: what this is, how to start. `CLAUDE.md` is for Claude: it is read automatically at the start of every conversation in this folder. Put standing instructions there.

**Context.** A chat forgets when it ends. A repo does not. Anything worth keeping goes into a file. Start a fresh chat when a thread gets long; the repo carries the memory.

**Skills.** A skill is a markdown file of instructions you can run with `/name`. Same task, same quality, every time. They live in `.claude/skills/`. Open any of them: they are just text. Edit them, copy them, write your own. Your skills are personal: they encode how *you* work. See `SKILLS.md`.

**Many chats at once.** Open a second chat in the same folder and give it a different job: one gathers, one reviews. They share the repo, not the conversation.

**Shorter replies.** Claude answers in normal sentences. To save tokens, type `/caveman lite` for terse replies; say `normal mode` to switch back.

---

## RULES

- **Gather · Decide · Account.** AI compiles. You decide. Every output records which was which (`DECISIONS.md`).
- **Credit AI.** When AI shaped something you present, say how.
- **Verify.** Every source must exist and say what you claim it says. AI invents references.
- **Keep it private.** Your copy stays private. No full copyrighted books, no passwords, nothing confidential.
- **Your taste is the point.** Out-of-the-box output is the floor, not the work.

---

## FOLDERS

Start with `project/brief-dip12.md` (the unit brief: Book of Rituals) and `project/brief.md` (your project). The full map of what goes where is the table "Where things go" in `CLAUDE.md`.
