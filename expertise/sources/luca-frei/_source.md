# Sources: Luca Frei

Raw material for the unit card `expertise/unit/luca-frei.md`. All fetched 2026-10-12. Tools: `fetch.py`, `yt-dlp` (captions), `vtt2txt.py`. Primary material in his own words is thin: one published Q&A, his site texts, and a 2008 video of him reading from his Beaubourg interpretation. The Artforum column and the two institutional texts are other people's words about him and are marked as such.

## Files

### 2024-daily-lazy-guiding-fabric-qa.txt
- Title: "Luca Frei at Galerie Barbara Wien / Berlin" (conversation on *Guiding Fabric*, 24 February – 13 April 2024). Questions by Barbara Buchmaier; answers by Luca Frei. Published: Daily Lazy, March 2024.
- URL: https://daily-lazy.com/2024/03/luca-frei-at-galerie-barbara-wien-berlin.html
- How: `fetch.py`; nav and image captions removed. Saved: the full Q&A and the short bio.

### 2026-lucaleefrei-com-site-texts.txt
- Title: texts from his site: About (with a passage by Gertrud Sandqvist), Introduction to the Hermann Scherchen works (first person), Soft Logic 2025–26 (catalogue text), Folds–Spreads 2025, Kunsthaus Glarus 2013, From Day to Day 2020, Contact. Author: Luca Lee Frei, except where credited.
- URL: https://www.lucaleefrei.com/ (pages /about-and-contact, /introduction-scherchen-works, /soft-logic-2025-2026, /folds-spreads, /kunsthaus-glarus, /from-day-to-day, /contact)
- How: `fetch.py` per page; slideshow labels removed. Saved: full page texts (short). The site is also reachable as lucafrei.info; lucafrei.net (in the brief) does not resolve.

### 2008-youtube-reading-beaubourg-part-2.txt
- Title: "Luca Frei - Part 2 of 3". Frei reading from his English interpretation of Albert Meister's *La soi-disant utopie du Centre Beaubourg*. YouTube, channel sofiahernandezchc, uploaded 20 September 2008. 9 min. Auto-captions, rough. Parts 1 and 3 are no longer available.
- URL: https://www.youtube.com/watch?v=v6zK2gr8NPo
- How: `yt-dlp` + `vtt2txt.py`. Saved: whole transcript. These are Meister's words in Frei's translation, not Frei's own positions; referenced in Hooks only.

### 2007-artforum-schambelan-so-called-utopia.txt
- Title: "The So-Called Utopia of the Centre Beaubourg". Author: Elizabeth Schambelan (critic's column on Frei's book, with short quotations from Frei). Published: Artforum, October 2007, Vol. 46, No. 2; online.
- URL: https://www.artforum.com/columns/the-so-called-utopia-of-the-centre-beaubourg-180868/
- How: `fetch.py`; nav removed. Saved: the full column (c. 2,300 words, freely online).

### 2020-malmo-konsthall-from-day-to-day.txt
- Title: "Luca Frei – From day to day", exhibition text, Malmö Konsthall, 6 June – 30 August 2020 (institutional text, not Frei's words).
- URL: https://malmokonsthall.se/en/utstallningar/luca-frei/
- How: `fetch.py`. Saved: full text.

### 2015-eflux-barbara-wien-scherchen-ii.txt
- Title: "Luca Frei: Hermann Scherchen: alles hörbar machen II", e-flux announcement for Galerie Barbara Wien, 1 December 2015 – 30 January 2016. Text by Gauthier Lesturgie (not Frei's words).
- URL: https://www.e-flux.com/announcements/185407/luca-frei-hermann-scherchen-alles-hrbar-machen-ii/
- How: `fetch.py`. Saved: full text.

### ref-publisher-and-gallery-pages.txt
- Extracts: Book Works product page (2007, ISBN 978 1 870699 99 0, Book Works and Casco, 208 pp.), Spector Books page (2014, ISBN 9783944669434), Book Works site search for "Luca Frei", Galerie Barbara Wien artist page. How: `fetch.py`.

## Checks
- "familiar yet strange, recognisable yet" → `luca-frei/2024-daily-lazy-guiding-fabric-qa.txt` line 28 
- "diffuse – alluding to a sense of place without necessarily representing" → `luca-frei/2024-daily-lazy-guiding-fabric-qa.txt` line 29 
- "about taking a widely available" → `luca-frei/2024-daily-lazy-guiding-fabric-qa.txt` line 79 
- "stitch, and texture becomes a language that speaks directly to the viewer." → `luca-frei/2024-daily-lazy-guiding-fabric-qa.txt` line 81 
- "textiles is their double character – both decorative and functional." → `luca-frei/2024-daily-lazy-guiding-fabric-qa.txt` line 59 
- "He was also my maternal grandfather. His latest venture and the focus of my research was the establishment of the Hermann Scherchen Experimental Electroacoustic Studio in Gravesano in 1954" → `luca-frei/2026-lucaleefrei-com-site-texts.txt` line 13 
- "“very committed ideas,” so as to “challenge more dogmatic ways of writing, and of course reading.”" → `luca-frei/2007-artforum-schambelan-so-called-utopia.txt` line 12 

Fragments quoted in How they work and Hooks:
- "at home or while travelling, on a table or directly on the floor" → `luca-frei/2026-lucaleefrei-com-site-texts.txt` line 58 
- "a radical libertarian space submerged beneath the newly erected center-piece of French Culture" → `luca-frei/ref-publisher-and-gallery-pages.txt` line 9 
- "Scores is a work that expands with time." → `luca-frei/2026-lucaleefrei-com-site-texts.txt` line 42 
- "turn an hourglass" → `luca-frei/2020-malmo-konsthall-from-day-to-day.txt` line 14 
- "the fragility of time" → `luca-frei/2026-lucaleefrei-com-site-texts.txt` line 101 
- "stop all" → `luca-frei/2008-youtube-reading-beaubourg-part-2.txt` lines 30–32 [00:01:22]–[00:01:28]
- "re-direct Klas Anshelm's geometric architecture" → `luca-frei/2026-lucaleefrei-com-site-texts.txt` line 124 
- "never takes its eye of the main target: state sponsored culture" → `luca-frei/ref-publisher-and-gallery-pages.txt` line 9 
- "internalized respect for Authority" → `luca-frei/2007-artforum-schambelan-so-called-utopia.txt` line 9 

Notes on the quotes: the Daily Lazy page uses a curly apostrophe in "It‘s"; the card keeps it as saved. The Artforum quotation is Frei's words as reported by the columnist, and the card says so.

Works: Book Works and Spector Books publisher pages fetched; extracts in `ref-publisher-and-gallery-pages.txt`.

Not confirmed:
- The brief's "*Luca Frei* monographs (e.g. Mousse Publishing)": no Mousse title found; the only monograph found is the Spector Books one (2014).
- "His books with Book Works": the Book Works site search returns only the Beaubourg title (plus a 2011 archive item for the *Make the Living Look Dead* commission).
- Interviews in Kunstkritikk or Mousse: none found.
- Signal (Malmö) talk page, 3 February 2016: fetched but JavaScript-only; not saved. Kunstakademiet (Copenhagen) lecture page: 404.
