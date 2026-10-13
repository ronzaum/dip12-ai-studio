# Sources: Giorgio Agamben

Raw material for the unit card `expertise/unit/giorgio-agamben.md`. All fetched 2026-10-12. Tools: `fetch.py` (stdlib page-to-text), `curl -sL`, `yt-dlp` + `vtt2txt.py` (YouTube captions with timestamps).

## 2021-green-pass-political-use-ill-will.txt
- Title: "What's Under Discussion is not the Vaccine, but the Political Use of the Green Pass". Author: Giorgio Agamben. First published in La Stampa, 30 July 2021; English translation by Ill Will, posted 14 August 2021 as the second of "Two Texts on the Green Pass".
- URL: https://illwill.com/green-pass
- Obtained: `fetch.py`, then cut to Agamben's text only (the first text on the page, by Il Rovescio, is not saved).
- Saved: the full essay (about 1,100 words).

## 2020-requiem-for-the-students-ill-will.txt
- Title: "Requiem for the Students". Author: Giorgio Agamben. Published on Quodlibet ("Una voce"), 23 May 2020; English translation by D. Alan Dean, Ill Will.
- URL: https://illwill.com/requiem-for-the-students Obtained: `fetch.py`. Saved: full essay.

## 2021-a-philosophy-of-contact-ill-will.txt
- Title: "A Philosophy of Contact". Author: Giorgio Agamben. Published on Quodlibet as "Filosofia del contatto", 5 January 2021; English translation by Richard Braude, Ill Will, 11 January 2021 (dates from the Aphelis index of his interventions and the Quodlibet "Una voce" list).
- URL: https://illwill.com/philosophy-of-contact Obtained: `fetch.py`. Saved: full essay.

## 2016-interview-gnoli-la-repubblica-jcrt.txt
- Title: "Philosophy as Interdisciplinary Intensity: An Interview with Giorgio Agamben". Interviewer: Antonio Gnoli. Published in La Repubblica, 15 May 2016; English translation by Ido Govrin, Journal for Cultural and Religious Theory (with permission of La Repubblica).
- URL: https://jcrt.org/religioustheory/posts/philosophy-as-interdisciplinary-intensity-an-interview-with-giorgio-agamben-antonio-gnolioido-govrin/
- Obtained: `fetch.py`, site menu removed. Saved: full interview with footnotes.

## 2011-egs-archaeology-of-commandment-captions.txt
- Title: "The Archaeology of Commandment". Lecture in English by Agamben at the European Graduate School, 2011 (video title: "Giorgio Agamben. The Archaeology of Commandment. 2011", uploaded 26 April 2012 by European Graduate School Video Lectures). YouTube auto-captions with `[HH:MM:SS]` timestamps; errors possible.
- URL: https://www.youtube.com/watch?v=T4MjMj4S4B8
- Obtained: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o base <url>` then `python3 -I vtt2txt.py base.en.vtt out.txt`. Saved: whole caption track (about 7,300 words).

## 2005-egs-what-is-a-dispositive-part1-captions.txt
- Title: "What is a Dispositive?", part 1 of 8. Lecture in English, EGS, 2005 (uploaded 9 July 2009). Auto-captions with timestamps; errors possible.
- URL: https://www.youtube.com/watch?v=ua7ElsQFZPo Obtained: as above. Saved: whole track for part 1 (about 950 words).

## 2007-profanations-zone-page.txt
- Zone Books book page for *Profanations* (trans. Jeff Fort, September 2007, ISBN 9781890951832). Publisher's description only; the essay "In Praise of Profanation" itself is not online in English and is not saved.
- URL: https://www.zonebooks.org/books/90-profanations Obtained: `fetch.py`.

## 1998-2013-stanford-titles-openlibrary-records.txt
- Open Library JSON records (library catalogue) for *Homo Sacer* (Stanford University Press, 1998, ISBN 9780804732185), *"What Is an Apparatus?" and Other Essays* (Stanford, 2009, ISBN 9780804762304) and *The Highest Poverty* (Stanford, 2013, ISBN 9780804784061).
- URLs: https://openlibrary.org/isbn/9780804732185.json ; https://openlibrary.org/isbn/9780804762304.json ; https://openlibrary.org/isbn/9780804784061.json
- Obtained: `curl -sL`. Why not sup.org: the Stanford University Press site answered 403/429 ("Vercel Security Checkpoint") on every try.
- Review 2026-10-12: openlibrary.org refused connections (ECONNREFUSED) for the whole session, so the three links could not be re-opened; years and publisher re-confirmed by web search (Library of Congress ISBN data, library catalogues).

## Not saved
- "The Invention of an Epidemic", 26 February 2020, English on the European Journal of Psychoanalysis site (https://www.journal-psychoanalysis.eu/articles/coronavirus-and-philosophers/): site returned 403; link only.
- "The Sacrifice in Liturgy", EGS, 2009 (https://www.youtube.com/watch?v=b8iwsgMw3BE): caption download failed (HTTP 429); link only. Worth retrying for the sacred/ritual hook.
- Quodlibet "Una voce" index of all Italian originals: https://www.quodlibet.it/una-voce-giorgio-agamben (fetched, Italian, not saved).
- Aphelis index of pandemic interventions and their translations: https://aphelis.net/agamben-coronavirus-pandemic-interventions/ (fetched for dates, not saved).

## Checks
Each quote on the card, the file, and the line where it appears (line numbers include the three header lines).
- "One might say that the vaccine has become a religious symbol that, as with any creed, now acts as a shibboleth [spartiacque] between friends and enemies, the saved and the damned." → `2021-green-pass-political-use-ill-will.txt`, line 9.
- "Just as it makes no sense to sacrifice freedom in the name of freedom, so it is not possible to renounce, in the name of bare life, what makes life worth living." → same file, line 19.
- "I’m convinced that these days the only way to access the present is through investigation of the past, the archeology." → `2016-interview-gnoli-la-repubblica-jcrt.txt`, line 51.
- "power is not defined only by its capacity to be obeyed first of all power is defined by its capacity to give orders" → `2011-egs-archaeology-of-commandment-captions.txt`, lines 194–197, timestamps 00:12:02–00:12:17 (caption lines joined; the word "that" precedes the quote at 00:12:02).
- "To be a student entailed first of all a form of life in which studying and listening to lectures were certainly decisive features" → `2020-requiem-for-the-students-ill-will.txt`, line 9.
- How they work: "terminology is the poetical element in philosophy" → `2005-egs-what-is-a-dispositive-part1-captions.txt`, lines 31–32 (00:01:42–00:01:46). Le Thor 1966/1968, Benjamin, Debord, Morante, Weil → 2016 interview file, lines 31–77.
- Hooks: "return to common usage", "to profane the unprofanable" → `2007-profanations-zone-page.txt`, line 43 (publisher's description, not Agamben's own sentence). "gathered together according to their place of origin" and "being a student [studentato, studenthood] as a form of life" → Requiem file, line 9 (note: the source has a non-breaking space before "nationes", so that word is kept outside the quote marks). "Students will no longer live in the cities where their universities are located." → Requiem file, line 11. "We would lose, purely and simply, our flesh." → `2021-a-philosophy-of-contact-ill-will.txt`, line 11. "its capacity to give orders" and "collapse when it's not more" → commandment captions, lines 197–198.
- Works: *Profanations* confirmed on the Zone page; the three Stanford titles confirmed on Open Library records (fetched). Publisher's own pages not fetched (blocked).
- Not confirmed / caveats: the two EGS lecture titles and years are the YouTube listings by the EGS channel. "A Philosophy of Contact" date is from the Aphelis index and the Quodlibet list, not shown on the Ill Will page. Nothing on the card is left unconfirmed.
