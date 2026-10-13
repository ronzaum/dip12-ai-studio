# Sources: Dunne & Raby

Raw material for the unit card `expertise/unit/dunne-raby.md`. All fetched 2026-10-12. `fetch.py` = stdlib HTML-to-text script; captions via `yt-dlp` then `vtt2txt.py` (timestamps are the caption file's; auto-captions mis-hear names and some words).

## 2007-critical-design-faq.txt
- "Critical Design FAQ", Anthony Dunne & Fiona Raby. On their site; their texts list dates it 2007 and records reprints in *Design for Change* (Black Jack, 2011) and the *Bunny Smash* catalogue (MOT Tokyo, 2014). Full text.
- URL: http://dunneandraby.co.uk/content/bydandr/13/0
- How: fetch.py; site navigation stripped.

## 2018-a-larger-reality-anthony-dunne.txt
- "A Larger Reality", Anthony Dunne. First published in *Fitness for What Purpose*, ed. Mary V. Mullin and Christopher Frayling, Design Manchester / Eyewear Publishing, 2018, pp. 116–117; republished on Reading Design. Full essay (about 900 words).
- URL: https://www.readingdesign.org/a-larger-reality
- How: fetch.py.

## 2015-aa-school-lecture-captions.txt
- "Anthony Dunne, Fiona Raby - Lecture", AA School of Architecture YouTube channel, published 15 July 2015; introduced by Liam Young. Whole lecture and Q&A (73 min), auto-captions. The recording date is not stated on the page; the introduction places them at the RCA, so 2015 or earlier.
- URL: https://www.youtube.com/watch?v=UHHlSnmX4UA
- How: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt`, then vtt2txt.py.

## 2017-strelka-speculative-everything-book-presentation-captions.txt
- "Speculative Everything" book presentation, Strelka Institute, published 14 November 2017. Whole talk (70 min), auto-captions. Not quoted on the card; saved as free material.
- URL: https://www.youtube.com/watch?v=kmibm20UsoA
- How: as above.

## 2025-dunneandraby-biography.txt, 2024-dunneandraby-contact.txt, 2024-dunneandraby-texts-list.txt
- Biography (current posts, book list), contact page (studio email), and the full list of their texts and book editions by year, from their site.
- URLs: http://dunneandraby.co.uk/content/biography ; http://dunneandraby.co.uk/content/contact ; http://dunneandraby.co.uk/content/bydandr
- How: fetch.py.

## 2013-speculative-everything-openlibrary-record.txt, 2005-hertzian-tales-openlibrary-record.txt, 2001-design-noir-openlibrary-record.txt
- Open Library edition records: *Speculative Everything* (MIT Press, ISBN 9780262019842; record dated 2014 printing), *Hertzian Tales* (MIT Press, ISBN 9780262541992; 2008 printing of the 2005 edition), *Design Noir* (Birkhäuser 2001, ISBN 9783764365660; Bloomsbury 2021, ISBN 9781350070639).
- URLs: https://openlibrary.org/books/OL26019393M ; https://openlibrary.org/books/OL29547252M ; https://openlibrary.org/books/OL9090652M ; https://openlibrary.org/books/OL29432549M
- How: `curl -sL https://openlibrary.org/books/<id>.json`, fields copied.

## Checks
- "Critical Design uses speculative design proposals to challenge narrow assumptions ... a position rather than a method." — 2007-critical-design-faq.txt: line 8.
- "The viewer should experience a dilemma, is it serious or not? Real or not?" — same file: line 22.
- "Too weird and it will be dismissed as art, too normal and it will be effortlessly assimilated." — same file: line 47.
- "needs to be closer to the everyday, that's where its power to disturb comes from" — same file: line 47.
- "affirmative design" / "design that reinforces the status quo" — same file: line 9.
- "What if design education's focus on 'making stuff real' perpetuates everything that is wrong with current reality, ensuring that all possible futures are merely extrapolations of a dysfunctional present?" — 2018-a-larger-reality-anthony-dunne.txt: line 9.
- "there's another space of speculation that can be used not to imagine better products but to imagine better human relations or to critique a political situation" — 2015-aa-school-lecture-captions.txt: lines 1640–1644, [01:07:43]–[01:07:51].
- "nothing we've ever designed has been mass-produced but we like to sort of use the language of mass production or everyday consumerism" — same file: lines 305–308, [00:13:16]–[00:13:24].
- "almost as if you don't put something into production it's not real" — same file: lines 1653–1654, [01:08:08]–[01:08:11].
- "speculative economics or speculative ethics" — same file: lines 1729–1730, [01:11:45]–[01:11:46].
- Works: MIT Press (mitpress.mit.edu, direct.mit.edu) and Bloomsbury pages returned 403 (Cloudflare) by every route, so the links are Open Library records; publisher and year also confirmed by the studio's own texts list (2024-dunneandraby-texts-list.txt: 2013 MIT Press; 2005 MIT Press; 2001 August/Birkhäuser; 2021 Bloomsbury). The MIT Press pages exist but were not fetched. No open-access edition of *Speculative Everything* was found.
- *Not Here, Not Now* (MIT Press, 2025, ISBN 9780262049665): confirmed 2026-10-12 from their book page https://dunneandraby.co.uk/content/books/1081/0 (links the MIT Press record, which returns 403) and bookseller/library listings found by web search. The 2024 *Speculative Everything* paperback carries a new preface by the authors (ISBN 9780262548687); the texts list calls it a foreword.
- Open Library was unreachable (connection refused) during the 2026-10-12 review; the saved records above were fetched earlier the same day. The AA lecture's recording date. Which of the two speaks in each caption line (the file does not mark speakers; the AA quotes are in Anthony Dunne's answers by context but this is not certain).
