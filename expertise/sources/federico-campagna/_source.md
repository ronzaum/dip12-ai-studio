# Sources: Federico Campagna

Raw material for the unit card `expertise/unit/federico-campagna.md`. All fetched 2026-10-12.

## 2022-metaphysics-and-architecture-aa-talk.txt
- Title: Metaphysics and architecture: Federico Campagna
- Author: Federico Campagna (introduced by Brendan Carlin, AA Diploma 19)
- Date: YouTube upload 2022-11-01; session 5 of the seminar series *The Ambivalence of Design* (AA Diploma 19 with Yonsei University, funded by the British Council)
- Where published: YouTube, AA School of Architecture channel
- URL: https://www.youtube.com/watch?v=g4XwDgFOMrE
- How obtained: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o g4XwDgFOMrE <url>` then `python3 -I vtt2txt.py g4XwDgFOMrE.en.vtt out.txt`
- What is saved: the whole talk and Q&A as auto-captions with `[HH:MM:SS]` timestamps (85 min, ~14,900 words). Auto-captions: no punctuation, some mis-hearings (e.g. "Rick vert" for Rykwert, "shine tour" for Scheintür).

## 2022-technic-and-magic-bergen-kunsthall.txt
- Title: Plattform: Federico Campagna: Technic and Magic
- Author: Federico Campagna
- Date: YouTube upload 2022-08-20
- Where published: YouTube, Bergen Kunsthall channel (public programme for an exhibition)
- URL: https://www.youtube.com/watch?v=-o0aqT4m8ek
- How obtained: same yt-dlp command with `-o -o0aqT4m8ek`, then vtt2txt.py
- What is saved: whole talk, auto-captions with timestamps (40 min, ~6,600 words).

## 2021-cultural-apocalypse-flash-art-eflux-announcement.txt
- Title: "Cultural Apocalypse": Summer 2021 (announcement for Flash Art Italia no. 335)
- Author: Flash Art / e-flux; quotes Campagna in conversation with Andrea Bellini
- Date: 14 June 2021
- Where published: e-flux announcements
- URL: https://www.e-flux.com/announcements/399380/cultural-apocalypse-summer-2021
- How obtained: `python3 -I fetch.py <url> out.txt`
- What is saved: the announcement text (~640 words). The full conversation is in the magazine and is not saved.

## 2026-sas-expert-profile.txt
- Title: Expert profile: Dr Federico Campagna
- Author: School of Advanced Study, University of London
- Date: undated page, fetched 2026-10-12
- URL: https://research.london.ac.uk/search/fellow/2020/dr-federico-campagna
- How obtained: fetch.py
- What is saved: the profile (affiliations, email, book list).

## 2018-technic-and-magic-bl-record.txt
- Title: British Library Electronic Legal Deposit catalogue record, *Technic and Magic: The Reconstruction of Reality* (London: Bloomsbury Academic, 2018)
- URL: https://eld.bl.uk/catalog/018826266
- How obtained: fetch.py
- What is saved: the record (title, author, contents, publisher, date).

## 2021-prophetic-culture-bl-record.txt
- Title: British Library Electronic Legal Deposit catalogue record, *Prophetic Culture: Recreation for Adolescents* (London: Bloomsbury Academic, 2021)
- URL: https://eld.bl.uk/catalog/020203390
- How obtained: fetch.py
- What is saved: the record (title, author, contents, publisher, date).

## Not saved
- Bloomsbury product pages for both books: HTTP 403 (Cloudflare) on 2026-10-12. Library records used instead.
- *The Last Night* (Zero Books, 2013): Zero / John Hunt Publishing pages returned 403; Open Library refused the connection. Named in the SAS profile and the AA introduction only. Left out of Works. Review 2026-10-12: Zer0 page at collectiveinkbooks.com/zer0-books/our-books/last-night still 403; web search shows it as Zer0 Books, 25 October 2013, ISBN 978-1-78279-195-9.
- *Otherworlds: Mediterranean Lessons on Escaping History* (Bloomsbury, 2025): not named in the SAS profile (which only says his next book will be on the Mediterranean) nor in the 2022 AA introduction. Confirmed by web search on 2026-10-12 (Wikipedia bibliography, retailer listing dated June 2025); bloomsbury.com cannot be fetched.
- Warburg Institute people page (403) and AA School people page (429). Contact route uses the SAS profile.
- *Purple* #42 interview: paywalled after the first answer. Link only.

## Checks
Every quote on the card, with file and line (timestamp). Checked by grep on 2026-10-12.
- "the world is in fact only an hypothesis it's an attempt to tell ourselves a narrative story about how reality is structured" — `2022-metaphysics-and-architecture-aa-talk.txt`, lines [00:25:38]–[00:25:45] (four caption lines joined).
- "a ritual is not a homage to a certain sacred event the ritual is a reproduction of a sacred event" — same file, [00:39:17]–[00:39:25].
- "every time you create a building that has even supposedly only a function there is always implied within that your idea of that function what kind of entities populate reality is implied" — same file, [00:29:35]–[00:29:46].
- "politics we have to modify the metaphysical architecture that sustains it so at the basis of radical political interventions it's necessary to have radical metaphysical interventions" — same file, [00:34:47]–[00:34:57].
- "indeed there is a limit to reality which is defined by the limit of our language" — `2022-technic-and-magic-bergen-kunsthall.txt`, [00:25:31]–[00:25:34].
- How they work: "ask yourself what are the implicit things there are included" — AA talk, [00:30:59]–[00:31:02]; "ancient or archaic or traditional architects" — AA talk, [00:38:06] (card corrected from 00:38:03 on review, 2026-10-12).
- Hooks: "the sacrifice is a reproduction of the activity through which the gods keep the world spinning" — AA talk, [00:39:27]–[00:39:33]; "a reproduction of a sacred event" — [00:39:23]; "time frame of things" — [00:30:38] (card corrected from 00:30:36 on review, 2026-10-12); "a door that allows the spirits to pass in and out of the building" — [00:44:25]–[00:44:29]; "ways of passage for immaterial" — [00:44:46]; "politics is the art of the possible" — [00:34:05]–[00:34:08].
- Works: both Bloomsbury titles confirmed on fetched British Library records. Nothing on the card is unconfirmed; *The Last Night* and *Otherworlds* are named but deliberately not listed as Works because no publisher or library page was fetched.
