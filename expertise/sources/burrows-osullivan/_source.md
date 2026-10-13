# Sources: David Burrows & Simon O'Sullivan

Raw material for the unit card `expertise/unit/burrows-osullivan.md`. All fetched 2026-10-12. Tools: `fetch.py` and `vtt2txt.py` are the stdlib scripts in the session scratchpad (`$T` = `/private/tmp/claude-501/-Users-ronzaum-Library-Application-Support-Claude-scratch-workspaces-fdcfcf14-68ed-4dfe-a285-046e9856aef6-a9a0e178-9f4e-4d06-b589-9e4c95ea6c7a-scratch-2026-10-12-269ed3/e87a6f01-f0e9-41ab-b4ca-8ddfc3a3c50f/scratchpad/tools`); `yt-dlp` from the scratchpad venv; `pdf2txt.swift` is a 10-line macOS PDFKit text extractor written for this job (`swift "$T/pdf2txt.swift" in.pdf out.txt`).

## 2019-fictioning-introduction-excerpt.txt
- Title: Fictioning: The Myth-Functions of Contemporary Art and Philosophy, Introduction. Authors: David Burrows and Simon O'Sullivan. Date: 2019. Published: Edinburgh University Press (free sample PDF on the publisher's site).
- URL: https://edinburghuniversitypress.com/media/resources/Fictioning_-_introduction.pdf
- How: `curl -sL -A "<browser UA>" -o fictioning-intro.pdf "<url>"` then `swift "$T/pdf2txt.swift" fictioning-intro.pdf out.txt`
- Saved: contents page and book pp. 1–6 of the introduction (~2,900 words of a 10-page chapter; kept under the 3,000-word limit). Page markers are book page numbers. Pages 7–10 were read but not saved.

## 2016-myth-science-and-the-fictioning-of-reality.txt
- Title: Myth-Science and the Fictioning of Reality. Author: Simon O'Sullivan. Date: 2016. Published: Paragrana 25 (2016) 2, pp. 80–93, De Gruyter; published version deposited on Goldsmiths Research Online (eprint 19700).
- URL: https://research.gold.ac.uk/id/eprint/19700/1/Mythopoesis_Fictioning_publised_version.pdf
- How: `curl -sL -A "<browser UA>" -o paragrana.pdf "<url>"` then `swift "$T/pdf2txt.swift" paragrana.pdf out.txt`
- Saved: the full article (~6,000 words with references), page markers as journal page numbers. An essay freely published in an institutional repository.

## 2025-osullivan-writing-performance-and-myth-work-lecture.txt
- Title: Identity Crisis Network: Simon O'Sullivan ("Writing, Performance and Myth-Work"). Author: Simon O'Sullivan (lecture, then discussion). Date: uploaded 28 July 2025. Published: Culture.pl, YouTube.
- URL: https://www.youtube.com/watch?v=0Z0XMKBOzm0
- How: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o "bo/so-culturepl" "<url>"` then `python3 -I "$T/vtt2txt.py" bo/so-culturepl.en.vtt out.txt`
- Saved: the whole recording (94 min, ~16,000 words), automatic captions with timestamps. The lecture ends about 00:30:05; the rest is discussion.

## 2013-plastique-fantastique-all-the-fantasies-imt.txt
- Title: 'All The Fantasies Of The People!' | Plastique Fantastique. Authors: Plastique Fantastique (Burrows, O'Sullivan and collaborators). Date: performed 27 June 2013; uploaded 11 August 2013. Published: IMT Gallery, YouTube.
- URL: https://www.youtube.com/watch?v=iO_NwV5ubXU
- How: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o "bo/pf-imt" "<url>"` then `python3 -I "$T/vtt2txt.py" bo/pf-imt.en.vtt out.txt`
- Saved: the whole recording (29 min, ~1,300 words of captions; mostly music tags). The spoken performance text from 00:10:59 is garbled in places. No card quote is taken from it.

## 2026-publisher-pages.txt
- Title: publisher pages for the three Works. Published: edinburghuniversitypress.com, gold.ac.uk/goldsmiths-press, triarchypress.net.
- URL: https://edinburghuniversitypress.com/book-fictioning.html ; https://www.gold.ac.uk/goldsmiths-press/publications/from-magic-and-myth-work-to-care-and-repair/ ; https://www.triarchypress.net/ancient.html
- How: EUP: `curl -sL -c cj -b cj -A "<browser UA>" -o eup.html "<url>"` (HTTP 200; title and meta description extracted with `python3 -I`). Goldsmiths Press and Triarchy: `python3 -I "$T/fetch.py" "<url>" out.txt`.
- Saved: title and description (EUP); page count, date, ISBN, blurb (Goldsmiths Press); blurb (Triarchy).

## Checks
Each card quote, where it sits in the saved file (grep fragment in quotes).
- "A fictioning practice then, involves performing, diagramming or assembling…": `2019-fictioning-introduction-excerpt.txt` line 248 (under marker BOOK PAGE 6). Grep "performing, diagramming or assembling".
- "Mythopoesis is proposed as productive of worlds…": same file, line 62 (BOOK PAGE 1). Grep "Mythopoesis is proposed as productive of worlds".
- "Performance can involve what we might call this magical function…": `2016-myth-science-and-the-fictioning-of-reality.txt` line 157 (JOURNAL PAGE 83; the word "Colla-" following is the next sentence's hyphenation). Grep "the summoning forth of something hitherto".
- "time itself becomes a material insofar as the accretion happens through time…": same file, line 188 (JOURNAL PAGE 84). Grep "time itself becomes a material".
- "there was a kind of activation of that scene across space and across time": `2025-osullivan-writing-performance-and-myth-work-lecture.txt` lines 833–834, [00:40:17]–[00:40:20]. Grep "and there was a kind of activation of".
- Hook and method fragments: "five-year project" line 358 [00:16:37]; "as itself a kind of device" line 468 [00:22:07]; "pilgrimage into the marshes to a sacred" line 826 [00:40:00]; "practice activates the landscape" line 840 [00:40:36]; costumes/objects/devices lines 450–454 [00:21:10]–[00:21:23]; "without a set beginning or ending" intro lines 247–248 (p. 6); "future human and non-human modes of existence" lines 69–70 (p. 1); "critical power when it is set against" line 85 (p. 2); "the words ‘I do’" line 219 (p. 5).
- Works: Fictioning confirmed on the EUP page (HTTP 200) and the PDF imprint page; From Magic and Myth-Work and The Ancient Device confirmed on the publisher pages. All in `2026-publisher-pages.txt`.
- Who line: Burrows "Slade School of Fine Art, UCL" and O'Sullivan "Goldsmiths" from the PDF's last page (saved); O'Sullivan's title "Professor" from his Goldsmiths staff page (read via WebFetch, not saved raw). Burrows' current title at the Slade is not stated on the card because his UCL page refused the fetch.
- Caveats: lecture quotes are automatic captions, read for sense, not checked by ear. The 2013 performance captions are too garbled to quote.
- Review 2026-10-12: the card's How they work said "costumes, objects and electronic devices"; the lecture at [00:21:10]–[00:21:23] lists "audiovisisual work, props, objects, various electronic devices, samplers, drum machines, mics" and no costumes anywhere in the saved files, so the card now says "props". EUP page re-fetched: Fictioning published February 2019 (hardback and paperback). simonosullivan.net, plastiquefantastique.org and the two UCL pages still refuse non-browser fetches (403).
