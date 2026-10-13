# Sources: David Gissen

Raw material for the unit card `expertise/unit/david-gissen.md`. All fetched 2026-10-12. `cfetch.py` is the scratchpad curl-based page saver.

## 2024-outline-for-a-disability-critique-of-property-eflux.txt
- "Outline for a Disability Critique of Property", David Gissen, e-flux Architecture (Positions), October 2024.
- URL: https://www.e-flux.com/architecture/positions/624965/outline-for-a-disability-critique-of-property
- How: `python3 -I cfetch.py <url> eflux-disability.txt`, chrome stripped. Saved in full with notes (about 4,200 words; an essay freely published online).

## 2014-the-mound-of-vendome-cca-talk.txt
- "David Gissen presents The Mound of Vendôme", talk at the Canadian Centre for Architecture, Montréal; CCAchannel YouTube upload 23 June 2014, 37 min.
- URL: https://www.youtube.com/watch?v=yqLsM_evOyk
- How: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o yt/yqLsM_evOyk <url>`, then `python3 -I vtt2txt.py`, entities unescaped. Auto-captions: "communi" = Communards, "Osman" = Haussmann, "plasome" = Place Vendôme.
- Saved: whole talk with `[HH:MM:SS]` stamps.

## 2023-architecture-off-centre-podcast.txt
- "On the Architecture of Disability / David Gissen", Architecture Off-Centre podcast, YouTube upload 24 Nov 2023, 49 min. Interview.
- URL: https://www.youtube.com/watch?v=vr1-PwpJNkg
- How: same yt-dlp + vtt2txt.py route. Auto-captions ("ACC" at 00:12:22 = access; "Hasam sarcus" = Hashim Sarkis, curator of the 2021 Venice Biennale).
- Saved: whole episode with stamps.

## 2009-cca-library-record-subnature.txt · 2014-cca-library-record-manhattan-atmospheres.txt
- Canadian Centre for Architecture library catalogue records for *Subnature: Architecture's Other Environments* (New York: Princeton Architectural Press, 2009, 224 pp, ISBN 9781568987774; contents list) and *Manhattan Atmospheres* (Minneapolis: University of Minnesota Press, 2014, viii+239 pp).
- URLs: https://www.cca.qc.ca/en/search/details/library/publication/314113421 · https://www.cca.qc.ca/en/search/details/library/publication/840465553
- How: cfetch.py, trimmed to the record. Used because the Princeton Architectural Press product page is a 404 and the UMN page for Manhattan Atmospheres could not be located by ISBN.

## 2023-umn-architecture-of-disability-page.txt
- University of Minnesota Press page for *The Architecture of Disability: Buildings, Cities, and Landscapes beyond Access* (published 24 Jan 2023, 224 pp, ISBN 9781517912505). URL: https://www.upress.umn.edu/9781517912505/the-architecture-of-disability/ cfetch.py, trimmed.

## 2026-yale-faculty-page.txt
- Yale School of Architecture faculty page: "Class of 1972 Professor of Architecture; Director of the PhD Program", with courses listed Fall 2025 to Spring 2027. URL: https://www.architecture.yale.edu/faculty/861-david-gissen cfetch.py, trimmed before the course table.

## Checks
- "Property is also a relationship formed between people and space that can incapacitate by design.": `2024-outline-for-a-disability-critique-of-property-eflux.txt` line 28.
- "Access simply affords one use of property, and the focus on disability independence often instantiates social relations endemic to property creation and development.": same file, line 36.
- "my ultimate argument I think in the book is that a disability critique of Architecture is not one that simply seeks to make the built environment more accessible": `2023-architecture-off-centre-podcast.txt` lines 344–348, [00:14:38]–[00:14:49].
- "a project that I hope poses questions about the types of historical landscapes, the type of nature or what some people call socio nature that become reconstructed and historicized in our cities today and why that happens": `2014-the-mound-of-vendome-cca-talk.txt` lines 13–19, [00:00:19]–[00:00:32].
- "this landscape was made to in a sense absorb the weight it was in a sense a cushion": same file, lines 432–434, [00:16:10]–[00:16:14].
- How they work: Samuel Garcia / National Archives: Mound file line 457 [00:17:00]. "a Greek archaeologist", seat "reconstructed it three different ways", Venice 2021: podcast lines 596–615 [00:25:24]–[00:26:21]. "I have a Prohibition against ramps in any project": podcast line 293 [00:12:16]. "disabled communalism" with Irene Cheng and Brett Snyder: e-flux file line 41. Curating: Yale page line 12.
- Hooks: contents list "Dankness -- Smoke -- …": `2009-cca-library-record-subnature.txt` line 18. "build out and across properties": e-flux line 44. "the plantation and the reservation": e-flux line 28. "nobody knows what it looks like": podcast line 616.
- Works: Subnature and Manhattan Atmospheres via CCA library records (fetched); Architecture of Disability via UMN page (fetched). Lead gave 2022 for The Architecture of Disability and 2014 for Manhattan Atmospheres; the records say January 2023 and 2014.

Review 2026-10-12: all five quotes and the method/hook fragments re-grepped and found verbatim at the stated stamps; CCA records, UMN page, e-flux essay and Yale page re-fetched; all five YouTube links resolve (titles match). The Parsons title in the Who line rests on the Parsons faculty page (https://www.newschool.edu/parsons/faculty/david-gissen/, HTTP 429) and the Places Journal author profile (https://placesjournal.org/?p=92440, 403) as shown in web search results; neither page was fetched.

Unconfirmed: nothing quoted on the card. Not reached: Parsons faculty page (bot check, HTTP 429), htcexperiments.org (now a private WordPress.com site), Places Journal pages and The Funambulist podcast page (Cloudflare challenge). The lead said "Places Journal, Log" essays; the only Places piece found with his byline is the multi-author "Field Notes on Repair: 2" (Nov 2024), linked on the card, not saved.
