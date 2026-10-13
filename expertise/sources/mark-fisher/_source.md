# Sources: Mark Fisher

Raw material for the unit card `expertise/unit/mark-fisher.md`. All fetched 2026-10-12. Tools: `fetch.py` and `vtt2txt.py` are the stdlib scripts in the session scratchpad (`$T` = `/private/tmp/claude-501/-Users-ronzaum-Library-Application-Support-Claude-scratch-workspaces-fdcfcf14-68ed-4dfe-a285-046e9856aef6-a9a0e178-9f4e-4d06-b589-9e4c95ea6c7a-scratch-2026-10-12-269ed3/e87a6f01-f0e9-41ab-b4ca-8ddfc3a3c50f/scratchpad/tools`); `yt-dlp` from the scratchpad venv.

## 2014-slow-cancellation-of-the-future-zagreb-lecture.txt
- Title: Mark Fisher: The Slow Cancellation Of The Future. Author: Mark Fisher (talk). Date: 21 May 2014 (uploaded 22 May 2014). Published: MaMa Zagreb, YouTube.
- URL: https://www.youtube.com/watch?v=aCgkLICTskQ
- How: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o "fisher/mama-zagreb" "https://www.youtube.com/watch?v=aCgkLICTskQ"` then `python3 -I "$T/vtt2txt.py" fisher/mama-zagreb.en.vtt out.txt`
- Saved: the whole talk (46 min, ~8,100 words), automatic captions with timestamps. Names mis-heard; see note at top of file.

## 2014-good-for-nothing.txt
- Title: Good For Nothing. Author: Mark Fisher. Date: 19 March 2014. Published: The Occupied Times (online).
- URL: https://theoccupiedtimes.org/?p=12841
- How: `python3 -I "$T/fetch.py" "https://theoccupiedtimes.org/?p=12841" out.txt`
- Saved: the full essay (~1,400 words), site navigation removed.

## 2015-abandon-hope-summer-is-coming.txt
- Title: Abandon hope (summer is coming). Author: Mark Fisher. Date: 11 May 2015. Published: k-punk blog (k-punk.org).
- URL: http://k-punk.org/abandon-hope-summer-is-coming/
- How: `python3 -I "$T/fetch.py" "http://k-punk.org/abandon-hope-summer-is-coming/" out.txt`
- Saved: the full post (~5,100 words; a blog post freely published by the author).

## 2013-exiting-the-vampire-castle-opening.txt
- Title: Exiting the Vampire Castle. Author: Mark Fisher. Date: 24 November 2013 (openDemocracy repost; first published in The North Star, 2013). Published: openDemocracy.
- URL: https://www.opendemocracy.net/en/opendemocracyuk/exiting-vampire-castle/
- How: `python3 -I "$T/fetch.py" "https://www.opendemocracy.net/en/opendemocracyuk/exiting-vampire-castle/" out.txt`
- Saved: standfirst and opening section only (~1,000 words). The page served the rest as unrelated site content; the body of the essay was not retrievable. No card quote is taken from this file.

## 2026-library-records.txt
- Title: Open Library search results for the four books; Wikipedia first line for dates. Published: openlibrary.org (Internet Archive), en.wikipedia.org.
- URL: https://openlibrary.org/search.json ; https://en.wikipedia.org/wiki/Mark_Fisher
- How: `curl -sL "https://openlibrary.org/search.json?q=<query>&fields=key,title,author_name,first_publish_year,publisher,isbn&limit=2"` printed with `python3 -I`; `python3 -I "$T/fetch.py" "https://en.wikipedia.org/wiki/Mark_Fisher" out.txt` (only the dates line kept).
- Saved: work keys, titles, years, publishers, ISBNs; dates of birth and death.

## Checks
Each card quote, where it sits in the saved file (grep fragment in quotes).
- "there are non- times as well as non-places": `2014-slow-cancellation-of-the-future-zagreb-lecture.txt` lines 237–239, [00:10:40]–[00:10:43]. Grep "there there are non- times as".
- "one can't by force of will alone create a sense of the future": same file, lines 1047–1048, [00:45:21]–[00:45:24]. Grep "will alone create a sense of the future".
- "many forms of depression are best understood…": `2014-good-for-nothing.txt` line 9. Grep "impersonal and political rather than individual".
- "England is a country in which every last space…": `2015-abandon-hope-summer-is-coming.txt` line 15. Grep "every last space where conviviality".
- "Real wealth is the collective capacity to produce, care and enjoy.": same file, line 65. Grep "Real wealth is the collective capacity".
- Hook fragments: "camp out for three days to glimpse the Royal Couple" line 55 (abandon hope); "their fault and their fault alone" line 19 (good for nothing); "that time free of urgencies" line 900 [00:39:27], "which is now kind of radically fugitive" line 917 [00:40:09] (lecture).
- Works: all four confirmed as Open Library records (`2026-library-records.txt`). Publisher pages at repeaterbooks.com and collectiveinkbooks.com returned HTTP 403 on 2026-10-12 (both curl and WebFetch); not fetched.
- Dates 1968–2017: Wikipedia first line (`2026-library-records.txt`).
- Review 2026-10-12 (evening): openlibrary.org refused connections (WebFetch and curl); the morning's API records stand. *The Weird and the Eerie* cross-checked against the CCA library record https://www.cca.qc.ca/en/search/details/library/publication/990609021 (London: Repeater Books, 2016). Card links re-checked: k-punk.abstractdynamics.org, k-punk.org, theoccupiedtimes.org, opendemocracy.net and the YouTube video all resolve; repeaterbooks.com and collectiveinkbooks.com still 403.
- Not confirmed / caveats: the lecture quotes are automatic captions; both read cleanly against the audio sense but were not checked by ear. "Exiting the Vampire Castle" is saved only in part. The k-punk index page (k-punk.abstractdynamics.org) was fetched but not saved; the On Vanishing Land note in "How they work" rests on it.
