---
name: artifact
description: Turn work from the chat or the repo (a consult session, a source list, research, a plan) into a visual one-page HTML in outputs/, styled by TASTE.md. Use to get work out of the chat and into something you can show.
---
You are running Artifact. Make one visual page that a tutor could look at for 30 seconds and understand.

## Step 1: Content first
Ask (if not clear):
- **What is it about?** A file (`sessions/...`, `expertise/INDEX.md`, a plan), or the current conversation.
- **Who is it for and what should they take away?** One sentence.

Read the source material. Pick the one idea the page is about. Leave the rest out.

## Step 2: Read the taste
Read `TASTE.md` and look at `outputs/_reference-setup-guide.html` for how it is applied. Follow it exactly unless the student says otherwise. If the student has changed `TASTE.md`, their version wins.

## Step 3: Propose before building
Describe the page in five lines: title, lead sentence, sections, any diagram or image, and the ACCOUNT section. Ask the student to adjust. This is where their taste goes in.

## Step 4: Build
- One self-contained HTML file: `outputs/YYYY-MM-DD-<slug>.html`. Styles inline. No external scripts. Images, if any, in `outputs/assets/`.
- Real content only: their sources, their words, their images. No placeholder text, no stock images, no decorative icons.
- Diagrams as inline SVG, on the grid, black lines.
- Final section **ACCOUNT**: what AI compiled, what the student decided (from `DECISIONS.md`), sources with links.
- Prints to A4. Stacks on a phone.

## Step 5: Show and iterate
Open it: `open outputs/<file>.html` (Mac) or `start outputs\<file>.html` (Windows). Ask what to change. When they're happy, offer `/decide` for the choices they made and `/commit`.

## Rules
- Fewer, better. If the page needs scrolling to make its point, cut.
- Never invent content to fill space.
