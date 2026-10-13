# Sources: Thomas A. P. van Leeuwen

Raw material for the unit card `expertise/unit/thomas-van-leeuwen.md`. All fetched 2026-10-12. Tools: `fetch.py` and `vtt2txt.py` are the stdlib scripts in the session scratchpad (`$T` = `/private/tmp/claude-501/-Users-ronzaum-Library-Application-Support-Claude-scratch-workspaces-fdcfcf14-68ed-4dfe-a285-046e9856aef6-a9a0e178-9f4e-4d06-b589-9e4c95ea6c7a-scratch-2026-10-12-269ed3/e87a6f01-f0e9-41ab-b4ca-8ddfc3a3c50f/scratchpad/tools`); `yt-dlp` from the scratchpad venv.

## 1999-aa-lecture-springboard-in-the-pond.txt
- Title: Thomas van Leeuwen - The Springboard in the Pond. Author: Thomas A. P. van Leeuwen (lecture, introduced by Robert Bergerhoff Mulder; auto-caption spelling). Date: lecture 11 March 1999 (per the video description); uploaded 21 May 2015. Published: AA School of Architecture, YouTube.
- URL: https://www.youtube.com/watch?v=EutAuEStjKI
- How: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o "vl/aa-springboard" "https://www.youtube.com/watch?v=EutAuEStjKI"` then `python3 -I "$T/vtt2txt.py" vl/aa-springboard.en.vtt out.txt`
- Saved: the whole lecture (44 min, ~5,200 words), automatic captions with timestamps. Minutes 1–9 are a film clip he screens; his talk starts about 00:09:26.

## 2010-cabinet-hot-on-the-trail.txt
- Title: Hot on the Trail: The culinary genius of Alexis Soyer. Author: Thomas A. P. Van Leeuwen. Date: Spring 2010. Published: Cabinet magazine, issue 37 (online, free).
- URL: https://cabinetmagazine.org/issues/37/vanleeuwen.php
- How: `python3 -I "$T/fetch.py" "https://cabinetmagazine.org/issues/37/vanleeuwen.php" out.txt`
- Saved: the full essay with its footnotes (~4,100 words including notes), site navigation removed. A magazine essay freely published online.

## 2007-swiss-institute-conference.txt
- Title: Conference | Thomas A.P. van Leeuwen: An Intimate History of The Swimming Pool. Author: Swiss Institute (event page; includes a Rem Koolhaas blurb). Date: 2007. Published: swissinstitute.net.
- URL: https://swissinstitute.net/programs/conference-2
- How: `python3 -I "$T/fetch.py" "https://swissinstitute.net/programs/conference-2" out.txt`
- Saved: the event text only (~170 words). Used for the Who line (Leiden professorship), not for quotes.

## 2023-japsam-thinking-foot-launch.txt
- Title: November 15th launch of 'The Thinking Foot'. Author: Jap Sam Books (Ronja Driessen). Date: 7 November 2023. Published: japsambooks.nl news.
- URL: https://www.japsambooks.nl/blogs/news/november-15th-launch-of-the-thinking-foot
- How: `python3 -I "$T/fetch.py" "https://www.japsambooks.nl/blogs/news/november-15th-launch-of-the-thinking-foot" out.txt`
- Saved: the post (~180 words). Publisher record for *The Thinking Foot* (imprint, editor, designer).

## 2026-library-records.txt
- Title: Open Library search results for the books; Wikidata entity Q125297014; Library of Congress name authority. Published: openlibrary.org, wikidata.org, id.loc.gov.
- URL: https://openlibrary.org/search.json ; https://www.wikidata.org/wiki/Q125297014 ; https://id.loc.gov/authorities/names/label/Leeuwen,%20Thomas%20A.%20P.%20van
- How: `curl -sL "https://openlibrary.org/search.json?q=<query>&fields=key,title,author_name,first_publish_year,publisher,isbn&limit=2"`; `curl -sL "https://www.wikidata.org/wiki/Special:EntityData/Q125297014.json"`; `curl -sL -H "Accept: application/json" "https://id.loc.gov/authorities/names/label/Leeuwen,%20Thomas%20A.%20P.%20van"`; each printed with `python3 -I`.
- Saved: work keys, years, publishers, ISBNs; birth year; name variants.

## Checks
Each card quote, where it sits in the saved file (grep fragment in quotes).
- "there are several periods of water…": `1999-aa-lecture-springboard-in-the-pond.txt` lines 239–243, [00:13:46]–[00:13:55]. Grep "is to begin with the sacred period when".
- "water that had been submitted to the actions of man lost its original innocence": same file, lines 250–253, [00:14:20]–[00:14:30] (an "uh" line at 00:14:20 sits between; omitted). Grep "lost its original innocence".
- "the third period is the period of the vulgar…": same file, lines 269–274, [00:15:31]–[00:15:45]. Grep "In The Water Closet".
- "now the road is free for a new generation of social swimmers…": same file, lines 631–634, [00:34:37]–[00:34:46]. Grep "generation of social swimmers goldfish".
- "An abrupt contrast between formal interior and informal exterior…": `2010-cabinet-hot-on-the-trail.txt` line 17. Grep "the more contrast, the more fun".
- Hook fragments: "first they banned the springboard then" line 627 [00:34:29]; "No contrast could be more heartbreaking" Cabinet line 36; tetralogy at line 151 [00:09:32]; "Columns of fire" line 156 [00:09:46]; Bel Air visit line 407 [00:22:49].
- Works: Springboard, Skyward Trend, Magic Stove confirmed as Open Library records; Thinking Foot confirmed on the Jap Sam Books page. MIT Press product pages returned HTTP 403 (curl and WebFetch) and were not fetched.
- Review 2026-10-12: all 11 quoted strings re-grepped verbatim (timestamps stripped) and the cited timestamps match the file. Works re-checked: Springboard confirmed MIT Press 1998 on the Stroom and University of Patras library records; Skyward Trend confirmed MIT Press 1988 by the *Journal of American Studies* review record (ISBN 0-262-22034-5; Open Library's 0262220342 looks like a typo); the Jap Sam product page for *The Magic Stove* gives "second revised edition, Fall 2020, Les Éditions du Malentendu, first published 2017", so the card line was corrected; *The Thinking Foot* product page gives November 2023, ISBN 978-94-93329-01-0. Open Library refused connections all day and MIT Press still returns 403; second records linked on the card. Four further searches (English and Dutch, full name "Thomas Adriaan Peter van Leeuwen") found no birth date, death notice or university page; the Jap Sam author note gives career only. No published text by him with the three-periods-of-water argument was found free online (it is in the book); the caption quotes stay, labelled.
- NOT CONFIRMED: birth year 1941 rests on Wikidata alone (no date of death recorded there; no obituary found in searches in English and Dutch). Whether he is living is therefore not confirmed. *Columns of Fire* (named in the lead as 2012, 010 Publishers) was not found in Open Library, WorldCat (403), nai010 or any bookseller; the only trace is his own mention in the 1999 lecture. The lecture quotes are automatic captions, read for sense but not checked by ear.
- Peer review 2026-10-12 (second model, findings verified by hand): (1) Card mapped fire to the kitchen/stove; the lecture (00:09:46) names the fire volume *Columns of Fire*, so the Magic Stove mapping is dropped. (2) Pool hook: the source (00:34:01–00:34:33) has dig, fill, ladders, springboards, disinfectants, then shun; no fencing. (3) "No contrast could be more heartbreaking" (Cabinet line 36) sets Spitalfields against Pall Mall, not the Irish famine. (4) Berlage: "presently teaches" in the 2010 Cabinet note; card now dates it. (5) Caption gap before Position #2 noted. Not adopted: the second model's claim that the Cabinet note lists *Columns of Fire* "in preparation" (no such string in the file); the 1986 AHA Books first edition of *Skyward Trend* and the full Magic Stove subtitle/editors (TUM and Jap Sam pages sit behind bot checks, not verified).
