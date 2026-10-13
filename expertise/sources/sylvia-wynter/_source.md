# Sources: Sylvia Wynter

Raw material behind `expertise/unit/sylvia-wynter.md`. Fetched 2026-10-12.

## 2012-ioj-induction-audio-response.txt
- Title: Prof. Emerita Sylvia Wynter - IOJ Induction of Fellows Audio Response
- Author: Sylvia Wynter (her recorded reply)
- Date: uploaded 21 Nov 2012 (instituteofjamaica, YouTube), 12:54
- URL: https://www.youtube.com/watch?v=zPrm0XwKOIg
- How obtained: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o yt-zPrm0XwKOIg <url>` then `python3 -I vtt2txt.py yt-zPrm0XwKOIg.en.vtt out.txt`
- Saved: whole talk, auto-captions with timestamps. Names are mis-heard (Elsa Goveia appears as "elsa gabar", Césaire as "cesare", Pagels as "pogba"). Only clean lines are quoted.

## 1994-no-humans-involved-excerpt.txt
- Title: "No Humans Involved": An Open Letter to my Colleagues
- Author: Sylvia Wynter; first published Forum N.H.I.: Knowledge for the 21st Century 1.1, 1994
- Where: libcom.org article page (excerpt as printed on the page; full letter is a scanned PDF attachment, https://files.libcom.org/files/Wynter5.pdf, not saved: no text layer)
- URL: https://libcom.org/article/no-humans-involved-open-letter-my-colleagues
- How obtained: `python3 -I fetch.py <url> out.txt`
- Saved: the page text (two paragraphs of the letter).

## 2015-on-being-human-as-praxis-duke-page.txt
- Title: Sylvia Wynter: On Being Human as Praxis, ed. Katherine McKittrick, Duke University Press, January 2015
- URL: https://www.dukeupress.edu/sylvia-wynter
- How obtained: `python3 -I fetch.py <url> out.txt`
- Saved: publisher page (description, contributors, contents).

## 1962-hills-of-hebron-library-records.txt
- Title: The Hills of Hebron
- Records: Duke University Library Exhibits item (dust jacket, 1st edition 1962, Sylvia Wynter Papers, Rubenstein Library); Open Library search record (Simon and Schuster 1962; J. Cape; Longman 1984; Ian Randle 2010)
- URLs: https://exhibits.library.duke.edu/items/show/14231 ; https://openlibrary.org/search.json?q=hills+of+hebron+wynter
- How obtained: fetch.py ; curl
- Saved: both records.

## 2020-we-must-learn-to-sit-down-together-records.txt
- Title: We Must Learn to Sit Down Together and Talk About a Little Culture: Decolonising Essays 1967-1984, ed. Demetrius L. Eudell, Peepal Tree Press
- Records: Open Library search record (2020, ISBN 9781845231088); Café OTO shop listing (Peepal Tree Press, 2022, 650pp, with the publisher's description)
- URLs: https://openlibrary.org/search.json?q=we+must+learn+to+sit+down+together+wynter ; https://www.cafeoto.co.uk/shop/sylvia-wynter-we-must-learn-to-sit-down-together-a/
- How obtained: curl ; fetch.py. The Peepal Tree page itself (https://www.peepaltreepress.com) returned 403 / Cloudflare.
- Saved: both records.

## 2026-stanford-profile.txt
- Title: Sylvia Wynter's Profile, Stanford Profiles
- URL: https://profiles.stanford.edu/sylvia-wynter
- How obtained: fetch.py. Saved: title and appointment lines.

## 2026-kcl-profile.txt
- Title: The Honourable Sylvia Wynter, King's College London alumni profile (undated)
- URL: https://www.kcl.ac.uk/people/sylvia-wynter
- How obtained: fetch.py. Saved: biography.

## 2026-wikipedia-status-check.txt
- Title: Sylvia Wynter, Wikipedia (infobox only; used to check living status and birth date, not quoted)
- URL: https://en.wikipedia.org/wiki/Sylvia_Wynter
- How obtained: fetch.py, first 3,000 characters.

## Not saved, link only
- The Re-Enchantment of Humanism (interview with David Scott, Small Axe 8, 2000): https://libcom.org/article/re-enchantment-humanism-interview-sylvia-wynter (scanned PDF).
- Unsettling the Coloniality of Being/Power/Truth/Freedom (CR: The New Centennial Review 3.3, 2003): https://muse.jhu.edu/article/51630 (paywalled).
- Sylvia Wynter: An Oral History, Stanford Digital Repository: https://purl.stanford.edu/vt433pj3894 (audio).
- Al Jazeera English, "Sylvia Wynter: Beyond man" (DigiDocs, 2025, 8 min): https://www.youtube.com/watch?v=WufVxu6EYao (a film about her; narration, not her voice; captions fetched but not saved).

## Checks
Quotes on the card, with file and line:
1. "to attempt to re-imagine ourselves no longer as inferiorized native subjects" — `2012-ioj-induction-audio-response.txt`, lines [00:02:03] "more real in effect to attempt to / re-imagine", [00:02:07] "ourselves no longer as inferiorized / native", [00:02:10] "subjects".
2. "that the fact of blackness was not a fact of inferiority" — same file, [00:03:34] "that the fact of blackness", [00:03:37] "was not a fact of inferiority".
3. "how can we be enabled to move outside the limits of the truth of solidarity" — same file, [00:09:17] "how can we be enabled to move outside", [00:09:21] "the limits of the truth of solidarity".
4. "it will now be the study of the word that is the study of each culture's uniquely human code of symbolic life and death that will now determine the study of nature" — same file, [00:10:53] to [00:11:03].
5. "The poor and the oppressed . . . have therefore come to lose all attractions for the intellectuals." — `1994-no-humans-involved-excerpt.txt`, second paragraph of the excerpt.
Card phrases in How they work / Hooks: "my still ongoing introduction to a collection of my essays" [00:00:55]; "code of symbolic life and death" [00:10:58]; "towards the very local cultural afro-west indian afro-jamaican attributes which had been despised and devalued" [00:02:35]–[00:02:39]; "no function" (excerpt, first paragraph).

Review 2026-10-12 (evening):
- Publication year of *We Must Learn to Sit Down Together...* settled as 2022: Café OTO listing (Peepal Tree Press, 2022, 650pp, re-fetched); ecampus.com ISBN 9781845231088 listing (copyright 2022-07-01, Peepal Tree Press Ltd.); Bocas Lit Fest Book Bulletin, May 2022, lists it under New Releases (https://library.bocaslitfest.com/?p=1829). Open Library's 2020 is treated as a pre-publication date. The publisher's own page still returns 403 (Cloudflare). Whether the volume contains the 1970 "Jonkonnu in Jamaica" essay is not confirmed and is not claimed on the card.
- *The Hills of Hebron*, Simon and Schuster, New York, 1962: Duke exhibit (first-edition dust jacket, 1962) plus the saved Open Library record; a web search also surfaced the Wake County (NC) library catalogue record (New York: Simon and Schuster, 1962, 315 pp, LCCN 62014285; https://catalog.wake.gov/Record/169510, which refuses non-browser fetches). Library of Congress and Open Library were both unreachable (503 / connection refused) at the recheck.
- libcom.org returned HTTP 503 site-wide at the recheck; the excerpt file was saved earlier the same day.
- Quotes 1–4 come from YouTube auto-captions, not a published transcript; the card says so. They read cleanly but have no punctuation; wording should be checked against the audio before print.
- Living status: Wikipedia (age 98) and the absence of any death report as of 2026-10-12; Duke's "Archive as Ceremony" symposium page (3 March 2026) and a Stanford event page (May 2026) do not say either way. No direct confirmation.
- Card phrase "Her papers (1950s–2018)" cut to "Her papers are at Duke's Rubenstein Library": the date range was not in any saved record.
- Peer review 2026-10-12 (second model, findings verified by hand): (1) The libcom excerpt hides two attributions: its "[T]he emergence" stands for "Bauman points out that the emergence" and its ". . ." for "Bauman notes" (checked against the New Frame edition of the essay, https://www.newframe.com/long-read-knowledge-must-mutate-be-fully-human/, fetched 2026-10-12; that edition also reads "attractiveness" where libcom has "attractions"). Position #5 and the Power hook now say she is relaying Bauman. (2) Positions #1–2 and the Ritual hook sit inside her summary of Elsa Goveia's proposal (00:01:08–00:05:10); labelled. (3) Position #4 is her rendering of Césaire's proposal (00:10:35–00:11:03); labelled, with "1946" marked as her dating. (4) "Works alone" cut: the KCL profile (line 19) says she often collaborated with Jan Carew. (5) Contact route no longer points to the Duke archive for a living person.

## 1994-no-humans-involved-newframe-bauman-attributions.txt
- Title: "No Humans Involved" (1994), New Frame republication. Author: Sylvia Wynter. Fetched 2026-10-12 with curl. Two short excerpts (about 420 characters each) around "Bauman points out" and "Bauman notes", saved so the card's attribution note is checkable here.
- URL: https://www.newframe.com/long-read-knowledge-must-mutate-be-fully-human/
