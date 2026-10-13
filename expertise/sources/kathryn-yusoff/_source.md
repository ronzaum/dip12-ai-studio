# Sources: Kathryn Yusoff

Raw material for the unit card `expertise/unit/kathryn-yusoff.md`. All fetched 2026-10-12. `cfetch.py` is the scratchpad curl-based page saver.

## 2018-a-billion-black-anthropocenes-excerpt.txt
- *A Billion Black Anthropocenes or None*, Kathryn Yusoff, University of Minnesota Press, 2018 (Forerunners: Ideas First, 27). Open-access edition on Manifold, DOI https://doi.org/10.5749/9781452962054.
- URL: https://manifold.umn.edu/projects/a-billion-black-anthropocenes-or-none
- How: Manifold's reader is JavaScript, so the text came from its API: `curl -sL -A "Mozilla/5.0" https://manifold.umn.edu/api/v1/texts/6b94c453-792a-4a6e-8aea-5a2c8c8155bd/relationships/text_sections/<section-id>`, the `body` HTML stripped to text. Section ids: Preface `b17181bd-…`, "Geology, Race, and Matter" `6243cd2f-…`.
- Saved: Preface in full (about 1,150 words) and the first ~1,700 words of "Geology, Race, and Matter". Under 3,000 words of the book. The Manifold text has no page numbers; quote by section.

## 2017-epochal-aesthetics-eflux.txt
- "Epochal Aesthetics: Affectual Infrastructures of the Anthropocene", Kathryn Yusoff, e-flux Architecture (Accumulation), March 2017.
- URL: https://www.e-flux.com/architecture/accumulation/121847/epochal-aesthetics-affectual-infrastructures-of-the-anthropocene/
- How: `python3 -I cfetch.py <url> eflux-epochal.txt`, chrome stripped. Saved in full with notes.

## 2019-white-utopia-black-inferno-eflux.txt
- "White Utopia/Black Inferno: Life on a Geologic Spike", Kathryn Yusoff, e-flux journal #97, February 2019.
- URL: https://www.e-flux.com/journal/97/252226/white-utopia-black-inferno-life-on-a-geologic-spike/
- How: `python3 -I cfetch.py <url> eflux-white-utopia.txt`. Saved in full with notes. The epigraph "The white utopia was a black inferno" is Sylvia Wynter's, not hers.

## 2023-yale-broken-earth-built-earths-talk.txt
- "Broken Earth & Built Earths: Architectures at an Inhuman Impasse", Kathryn Yusoff, Yale School of Architecture lecture, 6 April 2023; YouTube upload 7 June 2023, 60 min.
- URL: https://www.youtube.com/watch?v=pE7N8Xf1eXk
- How: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o yt/yale-broken-earth <url>`, then `python3 -I vtt2txt.py`. Auto-captions; "geropower" at 00:10:16 is a mishearing of "geopower".
- Saved: whole talk with `[HH:MM:SS]` stamps.

## 2026-qmul-staff-page.txt · 2026-qmul-decentering-the-human-people-page.txt
- QMUL Geography staff profile (full) and her co-director entry on the Decentering the Human People page (entry only). URLs: https://www.qmul.ac.uk/geog/staff/academicstaff/profiles/yusoffk.html · https://www.qmul.ac.uk/decentering-human/people/
- How: cfetch.py. The older URL `/geog/staff/yusoffk.html` is a 404.

## 2018-umn-billion-black-anthropocenes-page.txt · 2024-duke-geologic-life-page.txt
- Publisher pages for the two Works (University of Minnesota Press, published 2 Nov 2018; Duke University Press, May 2024, 608 pages). cfetch.py, trimmed to book data and blurb.

## Checks
- "The proximity of black and brown bodies to harm in this intimacy with the inhuman is what I am calling Black Anthropocenes.": `2018-a-billion-black-anthropocenes-excerpt.txt` line 11 (Preface).
- "Geology is a mode of accumulation, on one hand, and of dispossession, on the other, depending on which side of the geologic color line you end up on.": same file, line 33 ("Geology, Race, and Matter").
- "We might imagine the term "architecture" to refer to the organization of the material structures of space and its temporal patterning; or, how the material mediation of space orders a specific temporal indexing.": `2017-epochal-aesthetics-eflux.txt` line 20 (the file has curly quotes around architecture).
- "It may be precisely because land and labor were regarded as private property that the earth became a source of possibility to release the literal stranglehold of that incarceration in a propertied relation.": `2019-white-utopia-black-inferno-eflux.txt` line 33.
- "what is the cost of architectural forms that continue to propagate the myth of architecture as isolated from the mine and the memory of life worlds and prior materialisms that were held in place?": `2023-yale-broken-earth-built-earths-talk.txt` lines 128–133, [00:05:13]–[00:05:27].
- How they work: "I engage historical, geophilosophical and black feminist methods": `2026-qmul-staff-page.txt` line 14. "kept me company at 2:00 A.M.": excerpt file line 9. Modules and field trip: staff page, Teaching section.
- Hooks: "great veneration" and "the plot accorded to slaves to grow their own food": 2019 essay line 33. "the death of 50 million indigenous people": line 24. "where does architecture begin and where does it end": Yale file line 117 [00:04:48]. "at its onset geology is always about race and earth": lines 478–480 [00:21:03]. "architecture is at an inhuman impasse": line 265 [00:11:30].
- Contact: email k.yusoff@qmul.ac.uk in `2026-qmul-decentering-the-human-people-page.txt`.
- Works: both publisher pages fetched and saved.

Review 2026-10-12: all five quotes and every hook phrase re-found verbatim at the stated line/timestamp ("and earth" closes at [00:21:05]). The card now labels the Yale talk as auto-captions. Works re-fetched: Duke (May 2024, 608 pp), Minnesota (2 Nov 2018); Manifold's project page gives the series number as Forerunners 27 (an Emory catalogue record says 53; the publisher's platform is followed). All card links resolve.

Unconfirmed: nothing on the card. Lead said "lectures on YouTube": Harvard GSD 2020 (QM8B-XZG8OQ) and ASU 2020 (6GNzDbrILmA) exist but were not saved; the Yale 2023 talk was chosen because the audience is architects.
