# Sources: Ian Cheng

Raw material for the unit card `expertise/unit/ian-cheng.md`. All fetched 2026-10-12. Tools: `fetch.py` (stdlib page-to-text), `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt`, `vtt2txt.py`. Auto-captions carry transcription errors; only clean lines are quoted.

## Files

### 2019-worlding-raga-2-what-is-a-world.txt
- Title: "Worlding Raga: 2 – What is a World?" Author: Ian Cheng. Date: 5 March 2019. Published: Ribbonfarm (series Worlding Raga, hosted by Venkatesh Rao).
- URL: https://www.ribbonfarm.com/2019/03/05/worlding-raga-2-what-is-a-world/
- How: `python3 -I fetch.py <url> out.txt`; nav and reader comments removed. Non-breaking spaces normalised to spaces.
- Saved: the full essay (c. 1,100 words; freely published online).

### 2019-worlding-raga-6-world-to-live.txt
- Title: "Worlding Raga 6: World To Live". Author: Ian Cheng. Date: 18 June 2019. Published: Ribbonfarm.
- URL: https://www.ribbonfarm.com/2019/06/18/worlding-raga-6-world-to-live
- How: `fetch.py`; nav and comments removed. Saved: the full piece (a short speculative fiction, c. 3,100 words).

### 2017-louisiana-channel-portal-to-infinity.txt
- Title: "Ian Cheng Interview: A Portal to Infinity". Interview by Kasper Bech Dyg, Louisiana Channel; uploaded 19 October 2017. 17 min.
- URL: https://www.youtube.com/watch?v=TO6Luilc4Bo
- How: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o louisiana <url>` then `python3 -I vtt2txt.py louisiana.en.vtt out.txt`. Saved: whole transcript with [HH:MM:SS] stamps (auto-captions).

### 2018-serpentine-bob-emissaries.txt
- Title: "Ian Cheng: BOB, Emissaries | Serpentine". Serpentine Galleries; uploaded 12 April 2018. 5 min.
- URL: https://www.youtube.com/watch?v=XFmMrcW2ZsM
- How: `yt-dlp` + `vtt2txt.py` as above. Saved: whole transcript (auto-captions).

### 2022-the-stoa-art-of-worlding.txt
- Title: "The Art of Worlding: Creating the World You Wish to Inhabit w/ Ian Cheng". The Stoa; uploaded 30 November 2022. 60 min talk and Q&A.
- URL: https://www.youtube.com/watch?v=Tmve0PidacQ
- How: `yt-dlp` + `vtt2txt.py`. Saved: whole transcript (auto-captions). Not quoted on the card; kept for the four masks (Director, Cartoonist, Hacker, Emissary) and the infinite-game discussion from 00:13:00.

### 2023-de-balie-life-after-bob.txt
- Title: "Life after BOB: The Chalice Study with Ian Cheng". De Balie, Amsterdam; uploaded 16 March 2023. 50 min screening talk and Q&A.
- URL: https://www.youtube.com/watch?v=JfhdgNazHRo
- How: `yt-dlp` + `vtt2txt.py`. Saved: whole transcript (auto-captions). Not quoted on the card.

### ref-publisher-and-gallery-pages.txt
- Extracts from the publisher and gallery pages behind Works and Contact route: Artbook/D.A.P. (Koenig Books, *Emissaries Guide to Worlding*, 2018, ISBN 9783960982760), Spector Books (*Live Simulations*, 2015, ISBN 9783959050159), Pilar Corrias and Gladstone artist pages, Backstory bookshop (*WORLDING*, 2026). How: `fetch.py`.

## Checks
Each quote on the card, with the file and line (and caption timestamp where there is one):
- "A World is a reality you can believe in: one that promises to bring about habitable structure from the potential of chaos, and aim toward a future transformative enough to metabolize the pain and pleasure of its dysfunction." → `ian-cheng/2019-worlding-raga-2-what-is-a-world.txt` line 13 
- "Worlding is the art of devising a World: by choosing its dysfunctional present, maintaining its habitable past, aiming at its transformative future, and ultimately, letting it outlive your authorial control." → `ian-cheng/2019-worlding-raga-2-what-is-a-world.txt` line 25 
- "an individual sees or has a perspective" → `ian-cheng/2017-louisiana-channel-portal-to-infinity.txt` line 390 [00:15:45]
- "beliefs steadfast and change the group" → `ian-cheng/2017-louisiana-channel-portal-to-infinity.txt` line 394 [00:15:54]
- "we don't expect of nature complete" → `ian-cheng/2017-louisiana-channel-portal-to-infinity.txt` line 319 [00:12:36]
- "control we don't expect of nature total" → `ian-cheng/2017-louisiana-channel-portal-to-infinity.txt` line 320 [00:12:39]
- "make art with a nervous system and by" → `ian-cheng/2018-serpentine-bob-emissaries.txt` line 73 [00:02:55]
- "on its own and can react to you or me as" → `ian-cheng/2018-serpentine-bob-emissaries.txt` line 75 [00:03:01]

Fragments quoted in How they work and Hooks:
- "supported in a way almost invisible" → `ian-cheng/2017-louisiana-channel-portal-to-infinity.txt` line 354 [00:14:08]
- "losing control" → `ian-cheng/2017-louisiana-channel-portal-to-infinity.txt` line 184 [00:07:01]
- "she actually stops hearing the voices" → `ian-cheng/2017-louisiana-channel-portal-to-infinity.txt` line 152 [00:05:47]
- "environment has a set of narrative goals" → `ian-cheng/2018-serpentine-bob-emissaries.txt` line 50 [00:02:00]
- "landscape but many thousands of years" → `ian-cheng/2017-louisiana-channel-portal-to-infinity.txt` line 8 [00:00:15]
- "so that you never had a beginning an end" → `ian-cheng/2017-louisiana-channel-portal-to-infinity.txt` line 11 [00:00:22]
- "human things or such deterministic" → `ian-cheng/2017-louisiana-channel-portal-to-infinity.txt` line 332 [00:13:07]
- "almost like utility like water or gas" → `ian-cheng/2017-louisiana-channel-portal-to-infinity.txt` line 226 [00:08:51]
- "A World has laws. A World has values." → `ian-cheng/2019-worlding-raga-2-what-is-a-world.txt` line 9 
- "gives its members permission to act differently than outside of it" → `ian-cheng/2019-worlding-raga-2-what-is-a-world.txt` line 9 
- "embracing certain kinds of change is" → `ian-cheng/2017-louisiana-channel-portal-to-infinity.txt` line 397 [00:16:03]

Works: Artbook/D.A.P. page and Spector Books page fetched (extracts in `ref-publisher-and-gallery-pages.txt`). Gladstone's own publication page for the 2018 book returned 404; the Serpentine shop listing also 404.

Not confirmed, and so not on the card as a Work:
- *Life After BOB: The Chalice Study* as a 2022 book (Serpentine/Koenig): no publisher or library record found. Pilar Corrias lists it as a 48-minute real-time animation (2021).
- *WORLDING: A Guide for Creators in Changing Times* (2026, ISBN 9781068765728): bookseller page fetched, no publisher named.
- iancheng.com: a JavaScript app; `fetch.py` and `curl` return no text. Linked, not saved.
- The Serpentine 2018 conversation with Richard Evans (https://www.youtube.com/watch?v=UZRfofoXXI4) was fetched but is mostly Evans speaking; not saved.
