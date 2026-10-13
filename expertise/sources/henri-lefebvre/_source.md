# Sources: Henri Lefebvre

Raw material for the unit card `expertise/unit/henri-lefebvre.md`. All fetched 2026-10-12.

## 2004-rhythmanalysis-excerpts-pp5-8-15-18-27.txt
- Title: *Rhythmanalysis: Space, Time and Everyday Life*, chapters "The Critique of the Thing" and "Seen from the Window"
- Author: Henri Lefebvre, trans. Stuart Elden and Gerald Moore
- Date: French original 1992 (posthumous); English edition 2004, Continuum (now Bloomsbury)
- Where published: course PDF of excerpts, Princeton University, ENG 266 (Spring 2025), hosted on commons.princeton.edu
- URL: https://commons.princeton.edu/eng266-s25/wp-content/uploads/sites/433/2025/01/Lefebvre-Rhythmanalysis-excerpts.pdf
- How obtained: `curl -sL -o princeton-rhythm.pdf <url>`; `python3 -I pdftxt.py princeton-rhythm.pdf out.txt` (stdlib extraction of the PDF text operators); `python3 -I cleanrhythm.py` to join the one-line-per-operator output into paragraphs, restore characters the PDF font encoding dropped or substituted (fi/fl ligatures, ê, ô, é, ç, en dashes, curly quotes), de-hyphenate line-end breaks, and add `[p. N]` markers taken from the running heads
- What is saved: pp. 5, 6, 7, 8, 15, 16, 17, 18 and 27 (about 3,000 words). The PDF's pp. 9–10 and 28–30 were extracted but not saved, to stay under the length cap. Page numbers: the first block of the PDF has no running head; it is the chapter opening (p. 5 in the Continuum edition, which the next running head "6 Rhythmanalysis" confirms). Likewise the block before "28 Rhythmanalysis" is p. 27.
- Caveat: the text is a reconstruction from a PDF; four hyphenation and three accent repairs were made by hand (well-used, medium- and, One-two-three; fêtes, Hôtel de Ville, Métiers, façades). Quotes on the card were chosen to avoid those spots except "fêtes".

## 1968-the-right-to-the-city-chapter-excerpt.txt
- Title: "The Right to the City" (*Le Droit à la ville*, 1968), chapter "The Right to the City"
- Author: Henri Lefebvre, trans. Eleonore Kofman and Elizabeth Lebas, in *Writings on Cities* (Blackwell, 1996, pp. 61–181 for the whole text)
- Where published: The Anarchist Library (unofficial online copy of the Blackwell translation)
- URL: https://theanarchistlibrary.org/library/henri-lefebvre-right-to-the-city
- How obtained: `python3 -I fetch.py <url> out.txt`, then the chapter's first ~1,600 words and the "cry and a demand" paragraphs (~250 words) copied out; the rest of the book is not saved
- What is saved: two excerpts of the chapter "The Right to the City", marked `[...]` between them. The online text has no page numbers.

## 2019-michon-rhuthmos-lefebvre-rhythmanalysis-part-1.txt
- Title: "1. Henri Lefebvre's Rhythmanalysis of Everyday Life and Space – Part 1"
- Author: Pascal Michon (secondary source)
- Date: 14 December 2019
- Where published: *Rhuthmos* (rhuthmos.eu)
- URL: https://www.rhuthmos.eu/spip.php?article2479
- How obtained: fetch.py
- What is saved: the whole essay (~4,200 words, freely published). It quotes Lefebvre from *Critique of Everyday Life* vol. 2 (1961, trans. Moore 1991, pp. 231–232) and vol. 3 (1981, trans. Elliott 2005, pp. 11–12, 129–130) and *The Production of Space* (trans. Nicholson-Smith 1991, p. 31), with page numbers. Not used for card quotes; used for dates and for the collaboration with Catherine Régulier.

## 1991-the-production-of-space-wiley-page.txt
- Wiley-Blackwell product page: *The Production of Space*, trans. Donald Nicholson-Smith, Blackwell, August 1991, ISBN 978-0-631-18177-4
- URL: https://www.wiley.com/en-gb/The+Production+of+Space-p-9780631181774
- How obtained: fetch.py

## 2014-critique-of-everyday-life-verso-page.txt
- Verso product page: *Critique of Everyday Life: The One-Volume Edition*
- URL: https://www.versobooks.com/products/42-critique-of-everyday-life
- How obtained: fetch.py

## Not saved
- *Rhythmanalysis* publisher page (Bloomsbury): HTTP 403 (Cloudflare). Open Library's search API returned the record (work OL13607891W: *Rhythmanalysis: Space, Time and Everyday Life*, Continuum, 2004, ISBN 9780826472991) when queried, but the site refused connections before the page or JSON could be saved. The card links the Open Library work page; the fetched evidence for the edition is the citation line in the Princeton PDF ("Lefebvre, Henri. 2004. Rhythmanalysis: Space, Time and Everyday Life.") and Michon's essay. Review 2026-10-12: Blackwell's, the OSA Archivum catalogue and Monoskop all returned 403 to direct fetches, but web search results from those pages agree: Continuum 2004, trans. Elden and Moore, ISBN 9780826472991, reprinted 2004–2007; the Blackwell's listing is now linked on the card as the second record.
- *Writings on Cities* (Blackwell, 1996): no publisher or library page fetched on the first pass (Open Library refused; Monoskop's book page was fetched but is not a library record, and its hosted PDF of the whole book was not kept). Review 2026-10-12: Wiley product page fetched (https://www.wiley.com/en-gb/Writings+on+Cities-p-9780631191889: Wiley-Blackwell, November 1995, ISBN 978-0-631-19188-9, eds Kofman and Lebas) and the CCA library record (https://cca.qc.ca/en/search/details/library/publication/32349316: Blackwell Publishers, Cambridge, Mass., 1996, vi + 250 pp., ISBN 0631191879 / pbk 0631191887). Card keeps 1996 (copyright page) and links both.
- YouTube "Leszek Kolakowski and Henri Lefebvre (TV, 1971) eng sub": subtitle download failed three times with HTTP 429.
- *The Production of Space* full text on archive.org: lending-only, no text file.

## Checks
Every quote on the card, with file and location. Checked by grep on 2026-10-12.
- "When it concerns the everyday, rites, ceremonies, fêtes, rules and laws, there is always something new and unforeseen that introduces itself into the repetitive: difference." — `2004-rhythmanalysis-excerpts-pp5-8-15-18-27.txt`, block `[p. 6]`.
- "The cyclical originates in the cosmic, in nature: days, nights, seasons, the waves and tides of the sea, monthly cycles, etc. The linear would come rather from social practice, therefore from human activity" — block `[p. 8]`.
- "Everywhere where there is interaction between a place, a time and an expenditure of energy, there is rhythm." — block `[p. 15]`.
- "to grasp a rhythm it is necessary to have been grasped by it; one must let oneself go, give oneself over, abandon oneself to its duration." — block `[p. 27]`.
- "the right to the city is like a cry and a demand" — `1968-the-right-to-the-city-chapter-excerpt.txt`, second excerpt, first line (line break after "cry and" in the saved text).
- How they work: "we follow the second, more philosophical method, with its attendant risks" — block `[p. 5]`.
- Hooks: "Calendars, fêtes, ceremonies and celebrations" — block `[p. 18]`; "was also the society of the fête, of festivities. But that aspect, the best, has been lost" — Right to the City excerpt, first part (line break after "aspect,"); "something new and unforeseen" — `[p. 6]`; "days, nights, seasons" and "the monotony of actions and of movements, imposed structures" — `[p. 8]`; "a place, a time and an expenditure of energy" — `[p. 15]`; "places of simultaneity and encounters, places where exchange would not go through exchange value, commerce and profit" — Right to the City excerpt, first part (line breaks after "places," and "would").
- First pass left the card `unverified`: (1) no publisher or library page fetched for *Rhythmanalysis* (Open Library link given, record seen via API only) or for *Writings on Cities*; (2) the *Rhythmanalysis* text is a cleaned PDF extraction, not a publisher HTML page, so accents and ligatures were restored by hand.
- Review 2026-10-12 (card set to `verified`): all 13 quoted strings re-grepped verbatim in the files, page markers as cited. Page numbers checked a second way: a fresh raw extraction of the Princeton PDF shows the same running heads (6, 8, 15, 18, and the chapter-3 opening page for the p. 27 passage, which the Continuum contents list puts at p. 27); e-flux journal 54 cites the "new and unforeseen" sentence to p. 6 and Gordon Walker cites the "expenditure of energy" sentence to p. 15 of the 2004 edition. The only hand-restored character inside a card quote is the ê of "fêtes" (the raw PDF text drops it; e-flux quotes the sentence with "fêtes"). Google Books could not be used (API quota). Works: Wiley and Verso pages re-fetched (Production of Space, August 1991; Critique one-volume edition, May 2014); Rhythmanalysis and Writings on Cities as above. Links: Princeton PDF server's TLS certificate had expired on 2026-10-12 (fetchable with `curl -k`); Open Library refused connections all day; the rest returned 200.
