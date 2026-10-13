# Sources: Saidiya Hartman

Raw material for `expertise/unit/saidiya-hartman.md`. All fetched 2026-10-12.

## 2018-on-working-with-archives-creative-independent.txt
- Title: "Saidiya Hartman on working with archives". As told to Thora Siemsen. The Creative Independent; originally published 18 Apr 2018, page dated 3 Feb 2021. 2,816 words.
- URL: https://thecreativeindependent.com/people/saidiya-hartman-on-working-with-archives/
- How obtained: `python3 -I "$T/fetch.py" "<url>" tci.txt`
- Saved: the full interview (freely published).

## 2020-interview-with-saidiya-hartman-white-review.txt
- Title: "Interview with Saidiya Hartman". By Victoria Adukwei Bulley. The White Review, June 2020.
- URL: https://thewhitereview.org/feature/interview-with-saidiya-hartman
- How obtained: `python3 -I "$T/fetch.py" "<url>" whitereview.txt`
- Saved: the full interview with its introduction (~5,600 words, freely published). The interviewer's introduction quotes two short phrases from "Venus in Two Acts" ("impossible writing that attempts to say that which resists being said"; "with and against the archive"); the card uses only the second, attributed through this file.

## 2020-insurgent-histories-artforum-interview.txt
- Title: "Saidiya Hartman on insurgent histories and the abolitionist imaginary". Artforum, 14 Jul 2020 (first-person "as told to" format).
- URL: https://www.artforum.com/columns/saidiya-hartman-on-insurgent-histories-and-the-abolitionist-imaginary-248115/ (the original https://www.artforum.com/interviews/saidiya-hartman-83579 redirects here; link updated on review 2026-10-12)
- How obtained: `python3 -I "$T/fetch.py" "<url>" artforum.txt`; newsletter chrome trimmed.
- Saved: the full piece (~2,000 words).

## 2019-wayward-lives-politics-and-prose-talk.txt
- Title: "Saidiya Hartman, 'Wayward Lives, Beautiful Experiments'". Politics and Prose bookshop talk and Q&A, YouTube, uploaded 24 Nov 2019, 58 min. Auto-captions (errors: "RW knows WB Dubois" etc.).
- URL: https://www.youtube.com/watch?v=DAMeXgIi5DU
- How obtained: `"$V/yt-dlp" --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o DAMeXgIi5DU "<url>"` then `python3 -I "$T/vtt2txt.py" DAMeXgIi5DU.en.vtt DAMeXgIi5DU.txt`
- Saved: full caption transcript with [HH:MM:SS] timestamps.

## Pages fetched for Works and Contact (not saved as text)
- Wayward Lives, Norton: https://wwnorton.com/books/9780393357622 (fetch.py returned only the page title "Wayward Lives, Beautiful Experiments | Saidiya Hartman | W. W. Norton & Company"; WebFetch confirmed title, author, publisher, no date). Year and subtitle confirmed on the fetched Columbia CSSD page: "(W. W. Norton & Company, 2019)".
- Lose Your Mother, FSG: https://us.macmillan.com/books/9780374531157/loseyourmother/ (Imprint Farrar, Straus and Giroux, ISBN 9780374531157; "Published in January 2007 by Farrar, Straus and Giroux"; On Sale 01/22/2008 for the paperback).
- Scenes of Subjection, Norton: https://wwnorton.com/books/9781324021582 (fetch.py returned the title line listing Hartman, Keeanga-Yamahtta Taylor, Marisa J Fuentes, Sarah Haley, Cameron Rowland, Torkwase Dyson; no date shown). 1997 Oxford edition confirmed in the TCI and CSSD pages. Review 2026-10-12: the Norton UK record https://wwnorton.co.uk/books/9781324021582-scenes-of-subjection gives the date (4 November 2022, paperback, 560 pages, 25th anniversary edition, revised and updated, new preface; foreword Keeanga-Yamahtta Taylor, afterwords Marisa J. Fuentes and Sarah Haley, notes Cameron Rowland, artist Torkwase Dyson).
- "Venus in Two Acts": MoMA/Cassandra Press zine PDF downloaded with `curl -sL -o venus-moma.pdf "<url>"` (15.6 MB, image-based; no PDF text tool available, so not saved as text). Journal record: Small Axe 26, June 2008, pp. 1–14 (Project MUSE, paywalled; link only). Review 2026-10-12: Project MUSE listing confirmed by search as Small Axe, Number 26 (Volume 12, Number 2), June 2008, pp. 1–14, https://muse.jhu.edu/article/241115.
- Columbia CSSD page https://www.socialdifference.columbia.edu/faculty-/saidiya-hartman (fetched; title and book list).
- Columbia English page https://english.columbia.edu/content/saidiya-v-hartman: HTTP 403 with fetch.py and WebFetch. University Professor title is from the Columbia president's announcement found by search (not fetched). Review 2026-10-12: confirmed by fetching Columbia Magazine, Winter 2020–21, https://magazine.columbia.edu/article/saidiya-hartman-named-university-professor ("has been named a University Professor, which is the highest rank that Columbia bestows on its faculty"; announced by President Lee C. Bollinger). The English department page still returns 403 to automated fetch.
- us.macmillan.com pages (Lose Your Mother, author page) returned 403 to curl and WebFetch on the review re-check 2026-10-12 (bot block); the 2007 FSG year is also on the fetched CSSD page.

## Checks
Each card quote, the file, and the line where it appears (line numbers include the 4 header lines).
- "I work a lot with scraps of the archive. I work a lot with unknown persons, nameless figures, ensembles, collectives, multitudes, the chorus." → `2018-on-working-with-archives-creative-independent.txt` line 125
- "the sense of temporal entanglement, where the past, the present and the future, are not discrete and cut off from one another, but rather that we live the simultaneity of that entanglement." → same file, line 131
- "there are these three spaces or architectures that are absolutely foundational to my work: the Atlantic, the hold, and the circle." → `2020-interview-with-saidiya-hartman-white-review.txt` line 155
- "The character of the archive in Ghana at the time was not textual but one of landscape, it was an archive of the unsaid" → same file, line 75
- "One of the things that was really important for me to convey was the sensorium of black urban space, and that is so much about sound, right?" → same file, line 205
- How they work: "I work intuitively and will follow a trail of documents or my instincts until the project emerges." → 2018 file line 95; "with and against the archive" → White Review file line 37 (interviewer's introduction, quoting "Venus in Two Acts"); 1882 photograph and "probably seven years" → 2018 file line 145; "61 images" → 2019 transcript line 763 [00:36:11]; "new captions" → line 770 [00:36:38]; "other ends" → line 798 [00:38:00]; "a laboratory in thought" → 2018 file line 139; Selina Thompson's salt. → White Review file line 33.
- Hooks: "refusals and ruptures with the order" → White Review line 229; "self-dissolution, escape" → line 245; "a space of sociality and radical thought" and Bakongo cosmogram → line 155; "it doesn’t matter if it’s 1919 or 2019" → line 221; "an archive of the unsaid" → line 75; "as an enclosure" → Artforum file line 110; "It requires abolition, the abolition of the carceral world, the abolition of capitalism." → Artforum file line 116; Du Bois and "the first study of the black slum" → 2018 file line 151.
- Review 2026-10-12: all 5 Positions, 4 How-they-work quotes and the Hook quotes re-checked verbatim; the 2019 talk timestamps (00:36:11, 00:38:00) match the transcript. The 2019 citation is now labelled auto-captions on the card. Resolved (card now `verified`): Norton edition year 2022 (Norton UK record); University Professor title (Columbia Magazine, fetched); Venus in Two Acts citation (Project MUSE listing); the English page is marked 403 with the date and the CSSD page is the fetched route.
- Original notes: (1) Columbia English department page (the main faculty page) could not be fetched (403); the CSSD page is the fetched contact route. (2) The Norton edition of Scenes of Subjection: title and contributors confirmed on the fetched Norton page, but its year (brief says 2022) is not shown there, so the card gives no year for that edition. (3) "Venus in Two Acts": not read here; the Small Axe citation (no. 26, June 2008, pp. 1–14) comes from search results, and the MoMA PDF was downloaded but not read. (4) "University Professor" title comes from a Columbia announcement found by search, not fetched.
