# Sources: Pierre Huyghe

Raw material for the unit card `expertise/unit/pierre-huyghe.md`. All fetched 2026-10-12. Tools: `fetch.py`, `yt-dlp` (captions), `vtt2txt.py`.

## Files

### 2007-art21-romance-segment.txt
- Title: Pierre Huyghe in "Romance", Art in the Twenty-First Century, Season 4 (Art21, first broadcast 2007). YouTube upload by Art21, 5 April 2024. 16 min. Art21's own subtitles (not auto-captions), so the lines are clean; Huyghe's English is kept as spoken.
- URL: https://www.youtube.com/watch?v=syEhEFkOFR4
- How: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang "en,en-US" --sub-format vtt -o art21 <url>` then `vtt2txt.py art21.en-US.vtt`. Saved: whole transcript.

### 2017-elephant-indiscernible-unpredictable-irrational.txt
- Title: "Pierre Huyghe: Indiscernible, Unpredictable, Irrational". Author: Emily McDermott (interview at *After ALife Ahead*, Münster). Published: Elephant, issue 33, 2017; online.
- URL: https://elephant.art/pierre-huyghe-indiscernible-unpredictable-irrational/
- How: `fetch.py`; site nav, footer and injected spam lines removed. Saved: the full article (c. 1,400 words).

### 2017-the-art-section-interview-michael-amy.txt
- Title: "Pierre Huyghe with Michaël Amy". Interview recorded Brooklyn, 20 January 2017; published in The Art Section, November 2021 issue.
- URL: https://www.theartsection.com/pierre-huyghe
- How: `fetch.py`; page nav removed. Saved: the full interview as freely published online (c. 5,500 words).

### 2022-louisiana-channel-not-interested-in-binarity.txt
- Title: Artist Pierre Huyghe: "I'm not interested in binarity." Louisiana Channel; uploaded 29 September 2022. 19 min. Auto-captions, rough (e.g. "Joseph B" for Beuys, "un" for Untilled).
- URL: https://www.youtube.com/watch?v=WArGjRRF8Ec
- How: `yt-dlp` + `vtt2txt.py`. Saved: whole transcript. Used for the compost passage 00:05:22–00:07:38; only two short clean fragments are quoted.

### ref-publisher-and-gallery-pages.txt
- Extracts: Centre Pompidou online shop (2013 catalogue, EAN 9782844266217, 248 pp.), Hoepli bookseller listing of the Hirmer English edition (ISBN 9783777422497), Marsilio Arte (*Liminal*, 2024, ISBN 9791254632055), Serpentine shop (2019 book, publishers Serpentine / Koenig Books / Luma), Esther Schipper publication page (same book, ISBN 9783960987093, 2019), Marian Goodman and Esther Schipper artist pages. How: `fetch.py`.

## Checks
- "I always need to create a world." → `pierre-huyghe/2007-art21-romance-segment.txt` line 6 [00:00:10]
- "and my walk through this world" → `pierre-huyghe/2007-art21-romance-segment.txt` line 9 [00:00:23]
- "holes in the map." → `pierre-huyghe/2007-art21-romance-segment.txt` line 79 [00:05:18]
- "Blur certitude." → `pierre-huyghe/2007-art21-romance-segment.txt` line 83 [00:05:32]
- "Then people play this mythology in the form" → `pierre-huyghe/2007-art21-romance-segment.txt` line 215 [00:13:32]
- "and then you have an interpretation." → `pierre-huyghe/2007-art21-romance-segment.txt` line 218 [00:13:38]
- "I would lean toward a ‘garden approach’, meaning a place made by a particular—eventually irrational—mind, with indiscernible and unpredictable parts, and only then potentially share the space with people, but few and at their own risk" → `pierre-huyghe/2017-elephant-indiscernible-unpredictable-irrational.txt` line 19 
- "I define the condition under which the work will occur, and eventually there is the formation of something. There is a movement, there is a trajectory, rather than a formal intention." → `pierre-huyghe/2017-the-art-section-interview-michael-amy.txt` line 32 

Fragments quoted in How they work and Hooks:
- "I never had a place where things are made" → `pierre-huyghe/2017-the-art-section-interview-michael-amy.txt` line 34 (line 5, "an office where research and thinking take place…", is Michaël Amy's framing, not Huyghe, and is no longer quoted)
- "a table, a piece of paper, a pen" → `pierre-huyghe/2017-the-art-section-interview-michael-amy.txt` line 34 
- "conditional set up" → `pierre-huyghe/2017-the-art-section-interview-michael-amy.txt` line 32 
- "a tool to deregulate fixity of the self" → `pierre-huyghe/2017-elephant-indiscernible-unpredictable-irrational.txt` line 13 
- "studio employs only four people" → `pierre-huyghe/2017-elephant-indiscernible-unpredictable-irrational.txt` line 18 
- "is not the end of a process," → `pierre-huyghe/2007-art21-romance-segment.txt` line 232 [00:14:18]
- "to go somewhere else." → `pierre-huyghe/2007-art21-romance-segment.txt` line 234 [00:14:22]
- "the back of the park" → `pierre-huyghe/2022-louisiana-channel-not-interested-in-binarity.txt` line 112 [00:05:43]
- "if I throw element of History" → `pierre-huyghe/2022-louisiana-channel-not-interested-in-binarity.txt` line 117 [00:05:57]
- "It’s a score." → `pierre-huyghe/2007-art21-romance-segment.txt` line 199 [00:12:46]
- "come back and come back" → `pierre-huyghe/2007-art21-romance-segment.txt` line 208 [00:13:03]
- "to produce a time," → `pierre-huyghe/2007-art21-romance-segment.txt` line 210 [00:13:06]
- "the duration that will just come back in time." → `pierre-huyghe/2007-art21-romance-segment.txt` line 211 [00:13:09]
- "a cycle that includes change" → `pierre-huyghe/2017-the-art-section-interview-michael-amy.txt` line 90 
- "is no more important than the ants that no one sees" → `pierre-huyghe/2017-elephant-indiscernible-unpredictable-irrational.txt` line 10 
- "It is a place where an uncertain ecology might occur, [but] having a dramatic place wasn’t a goal. It is not about landscape." → `pierre-huyghe/2017-elephant-indiscernible-unpredictable-irrational.txt` line 7 
- "a way to broke the rule of power." → `pierre-huyghe/2007-art21-romance-segment.txt` line 136 [00:09:41]
- "an organization, as a distribution of goods or ideas among a spectrum of people" → `pierre-huyghe/2017-the-art-section-interview-michael-amy.txt` line 54 

Works: Centre Pompidou shop (publisher), Marsilio Arte (publisher) and Serpentine shop (publisher) pages fetched; extracts in `ref-publisher-and-gallery-pages.txt`.

Not confirmed:
- The Hirmer English edition (2014/15): hirmerverlag.de returned 404 and the Smithsonian library record 403; only the Hoepli bookseller listing was fetched. It is therefore given as a note under the Pompidou entry, not as a separate Work.
- The brief's "*Untilled* dOCUMENTA(13) notebook (Hatje Cantz)": no Huyghe volume found in the 100 Notes – 100 Thoughts series (documenta publications page is JavaScript-only; web searches found none). Not listed.
- Serpentine 2018 conversation with Hans Ulrich Obrist (https://www.youtube.com/watch?v=emYOOVRzG8E): both caption tracks are machine-garbled; linked only, not saved.
- Hauser & Wirth artist page: HTTP 429 on first fetch; Vercel bot check on the 2026-10-12 review. Named without link.
- Review 2026-10-12: the Marian Goodman and Esther Schipper links first given (`/artists/48-…`) opened other artists' pages (Amar Kanwar; Christopher Roth). Corrected to `/artists/pierre-huyghe/` and `/artists/41-pierre-huyghe/`; extracts in `ref-publisher-and-gallery-pages.txt` replaced. Marsilio link replaced by the page it redirects to.
