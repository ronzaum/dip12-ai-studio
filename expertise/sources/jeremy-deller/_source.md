# Sources: Jeremy Deller

Raw material for the unit card `expertise/unit/jeremy-deller.md`. All fetched 2026-10-12. `fetch.py` = stdlib HTML-to-text script; `yt-dlp` captions converted with `vtt2txt.py` (timestamps are the caption file's).

## 2002-english-civil-war-part-ii-foreword-artangel.txt
- The Battle of Orgreave, Artangel project page: project text, Deller's foreword to *The English Civil War: Part II* (Artangel, 2002; "edited version"), an excerpt of his interview with David Douglass (NUM), and Artangel's "Making The Battle of Orgreave" note.
- Author: Jeremy Deller (foreword, interview questions); Artangel (page text). Date: foreword 2002; page undated.
- URL: https://www.artangel.org.uk/project/the-battle-of-orgreave/
- How: `python3 -I fetch.py <url> out.txt`; saved from "In 1984 the National Union..." to just before the donation block.

## 2011-photoworks-interview-david-alan-mellor.txt
- "Ideas Series: Jeremy Deller interviewed by David Alan Mellor", Photoworks, Issue 17, 2011. Full interview as published online.
- URL: https://photoworks.org.uk/jeremy-deller-interviewed-by-david-alan-mellor/
- How: fetch.py; navigation and footer stripped.

## 2012-artforum-jeremy-deller-talks-about-sacrilege.txt
- "Jeremy Deller talks about Sacrilege", as told to Sherman Sam, Artforum, 20 April 2012. The six paragraphs of the column, in order.
- URL: https://www.artforum.com/columns/jeremy-deller-talks-about-sacrilege-199932/
- How: fetch.py; page chrome stripped, column paragraphs kept.

## 2023-louisiana-channel-what-is-british-identity-captions.txt
- "What Is British Identity? | Artist Jeremy Deller", Louisiana Channel, YouTube, published 14 July 2023. Auto-generated English captions, whole video (17 min).
- URL: https://www.youtube.com/watch?v=iJNIjTiSNGw
- How: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt` then `vtt2txt.py`.

## 2024-louisiana-channel-can-art-change-the-world-captions.txt
- "Jeremy Deller: Can Art Change the World?", Louisiana Channel, YouTube, published 26 April 2024. English captions, whole video (3 min 20 s).
- URL: https://www.youtube.com/watch?v=osvGqKDgeUQ
- How: yt-dlp as above, then vtt2txt.py.

## 2023-art-is-magic-cheerio-publisher-page.txt
- Publisher page for *Art is Magic* (Cheerio, hardback 4 May 2023) with the author note.
- URL: https://www.cheeriopublishing.com/art-is-magic-jeremy-deller (the earlier URL /art-is-magic now redirects here)
- How: fetch.py.

## 2012-joy-in-people-openlibrary-record.txt and 2002-english-civil-war-part-ii-openlibrary-record.txt
- Open Library edition records: *Joy in People* (Hayward Publishing, 2012, ISBN 9781853322945) and *Jeremy Deller: The English Civil War - Part II* (Artangel, 2002, ISBN 9781902201139).
- URLs: https://openlibrary.org/books/OL28774578M ; https://openlibrary.org/books/OL8764594M
- How: `curl -sL https://openlibrary.org/books/<id>.json`, fields copied.

## 2026-the-modern-institute-artist-page.txt and 2026-galerie-art-concept-contact.txt
- Gallery pages used for the contact route. Modern Institute page saved whole (exhibition list); Art : Concept reduced to the address and contact emails.
- URLs: https://www.themoderninstitute.com/artists/jeremy-deller/ ; https://www.galerieartconcept.com/en/jeremy-deller-2/ (the earlier URL /en/artists/jeremy-deller/ redirects here)
- How: fetch.py.

## Checks
Each quote on the card, where it sits (file: line; caption quotes span the lines given).
- "I wanted the re-enactment of The Battle of Orgreave to become part of the lineage of decisive battles in English History." — 2002-english-civil-war-part-ii-foreword-artangel.txt: line 21.
- "Also as an artist I was interested in how far an idea could be taken ... 'a recreation of something that was essentially chaos'." — same file: line 23.
- "I was not interested in a nostalgic interpretation" (not quoted on card; context) — same file: line 24.
- "I saw the project as a kind trojan horse – an opportunity to get a political film and performance and book made under the guise of contemporary art." — 2011-photoworks-interview-david-alan-mellor.txt: line 25. ("kind trojan horse" is as published.)
- "The performance was the artwork and the film was a piece of documentation. The book was an attempt to gather a lot of the research together and make a decent history book out of an art project." — same file: line 19.
- "I had done my homework, basically." — same file: line 13.
- "I've always thought that a good deal of public or community art is pompous and has too many lofty aims. I just wanted to make something that could be enjoyed and also be a bit silly." — 2012-artforum-jeremy-deller-talks-about-sacrilege.txt: line 15.
- "The title is a way is to ward off any criticism—some will think that it is just that, a sacrilege, so why not call it that?" — same file: line 17 (the doubled "is a way is" is as published).
- "I think art can offer personal salvation - in the way that religion did once." — 2024-louisiana-channel-can-art-change-the-world-captions.txt: lines 5–7, [00:00:00]–[00:00:05]. The caption file breaks the sentence with a dash on each side of the break; the card joins the lines and keeps one dash (an earlier draft used an ellipsis; corrected 2026-10-12).
- "I suppose I work with groups of people and communities I do it because you can't get things done if you don't work with people" — 2023-louisiana-channel-what-is-british-identity-captions.txt: lines 86–89, [00:03:23]–[00:03:30].
- "the most contemporary building in Britain because there's always speculation there's always something happening there" — same file: lines 249–252, [00:10:49]–[00:10:54] (auto-captions; these lines read cleanly).
- "a civil war between the North and the South of the country", "veterans of a recent confrontation", "refused to meet us on any level" — foreword file lines 14 and 22; Photoworks file line 29.
- "the decoy of a film would be necessary", "a certain degree of credibility" — foreword file, "Making The Battle of Orgreave" block at the end (Michael Morris, June 2002; appended 2026-10-12, it had been named in this list but not saved).
- Works: Cheerio page fetched (publisher). Hayward and Artangel books confirmed by Open Library records (publisher pages: Hayward/Southbank shop returned 404; Artangel has no book page). Artangel's own project page states the 2002 book was "published by Artangel".
- Not confirmed / not saved: www.jeremydeller.org returned HTTP 503 on every attempt (direct and via Wayback, which rate-limited); listed as a link only. Southbank Centre magazine interview "Jeremy Deller on Joy in People" returned 403; not used.
