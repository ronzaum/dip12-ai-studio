# Sources: Paul B. Preciado

Raw material for the unit card `expertise/unit/paul-b-preciado.md`. All fetched 2026-10-12. Tools: `fetch.py` (stdlib page-to-text), `yt-dlp` + `vtt2txt.py` (YouTube subtitles with timestamps).

## 2020-learning-from-the-virus-artforum.txt
- Title: "Learning from the Virus". Author: Paul B. Preciado, translated from French by Molly Stevens.
- Date: May/June 2020. Published: Artforum 58, no. 9 (free on artforum.com).
- URL: https://www.artforum.com/features/learning-from-the-virus-247388/
- Obtained: `python3 -I fetch.py <url> out.txt`, then cut to the essay body (from "IF MICHEL FOUCAULT" to "Translated from French by Molly Stevens."), site navigation removed.
- Saved: the full essay (freely published online).

## 2020-pathologically-optimistic-gagosian.txt
- Title: "Pathologically Optimistic". Conversation between Paul B. Preciado, Alison M. Gingeras and Jamieson Webster.
- Date: 4 December 2020. Published: Gagosian Quarterly, Winter 2020 ("New Interiorities" supplement), free online.
- URL: https://gagosianquarterly.com/quarterly/2020/12/04/interview-pathologically-optimistic-paul-b-preciado/
- Obtained: `fetch.py`, cut from the editorial intro to the end of the author bio.
- Review 2026-10-12: the gagosianquarterly.com URL now redirects to gagosian.com/quarterly/2020/12/04/interview-pathologically-optimistic-paul-b-preciado/, which answers 403 to automated fetch; the page is still indexed by search.
- Saved: the full conversation.

## 2013-death-of-the-clinic-reina-sofia-captions.txt
- Title: "¿La muerte de la clínica?" (The death of the Clinic?). Lecture by Preciado (credited on the video as Beatriz Preciado), Museo Reina Sofía, Madrid, March 2013 (date from the video description). Spanish audio with English subtitles; the saved text is the English subtitle track with `[HH:MM:SS]` timestamps.
- URL: https://www.youtube.com/watch?v=mCK21tubTUk (uploaded by Pilar Narvaez, 2019)
- Obtained: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o base <url>` then `python3 -I vtt2txt.py base.en.vtt out.txt`.
- Saved: the whole subtitle track (about 14,700 words). Subtitle translation, not an authorised text: quote only lines that read cleanly.

## 2020-vice-interview-excerpt-zone.txt
- Title: "An Interview with Paul Preciado" (Vice, March 2020), excerpt reproduced on the Zone Books news page. Interviewer not named on the page.
- Date: 12 March 2020. URL: https://www.zonebooks.org/news-preciado-vice
- Obtained: `fetch.py`. Saved: the whole page (short excerpt on being renamed).

## 2020-an-apartment-on-uranus-fitzcarraldo-page.txt
- Fitzcarraldo Editions book page for *An Apartment on Uranus* (trans. Charlotte Mandell, foreword Virginie Despentes, published 15 January 2020), with the publisher's preview of the introduction and press quotes.
- URL: https://fitzcarraldoeditions.com/books/an-apartment-on-uranus/ Obtained: `fetch.py`. Saved: whole page.

## 2013-testo-junkie-feminist-press-page.txt
- Feminist Press book page for *Testo Junkie* (ISBN 9781558618374). URL: https://feministpress.org/products/9781558618374-testo-junkie Obtained: `fetch.py`. Saved: whole page (mostly menu; confirms title, author, publisher).

## 2014-pornotopia-zone-page.txt
- Zone Books book page for *Pornotopia: An Essay on Playboy's Architecture and Biopolitics* (October 2014, ISBN 9781935408499). URL: https://www.zonebooks.org/books/4-pornotopia-an-essay-on-playboy-s-architecture-and-biopolitics Obtained: `fetch.py`. Saved: whole page.

## 2021-can-the-monster-speak-fitzcarraldo-page.txt
- Fitzcarraldo Editions book page for *Can the Monster Speak?* (trans. Frank Wynne, published 2 June 2021), with preview of the opening. URL: https://fitzcarraldoeditions.com/books/can-the-monster-speak/ Obtained: `fetch.py`. Saved: whole page.

## undated-zone-books-about-page.txt
- Zone Books "About" page, used only for the contact route (general address info@zonebooks.org). URL: https://www.zonebooks.org/about Obtained: `fetch.py`.

## Not saved
- "Hacking the Binary", conversation, Digital Delights and Disturbances series: https://www.youtube.com/watch?v=4C8L8dQEB8E. Auto-captions downloaded but too rough to quote; link only.
- Artforum author page lists later essays ("The Impossible Dedication", "I Am Falling in Love"): https://www.artforum.com/author/paul-b-preciado/. Not fetched.

## Checks
Each quote on the card, the file, and the line where it appears (line numbers include the three header lines).
- "There are no politics that are not body politics." → `2020-learning-from-the-virus-artforum.txt`, line 13.
- "The new necropolitical frontier has shifted from the coast of Greece toward the door of your home. Lesbos now starts at your doorstep." → same file, line 57.
- "Our portable telecommunication machines are our new jailers and our own domestic interiors have become the soft and ultraconnected prisons of the future." → same file, line 95.
- "Torture and social blood rituals are forms of inscription of the law on this body without interiority." → `2020-pathologically-optimistic-gagosian.txt`, line 91.
- "The body as the last biopolitic capsule is a disciplinary capsule" → `2013-death-of-the-clinic-reina-sofia-captions.txt`, lines 442–443, timestamps 00:21:39 and 00:21:45.
- Hooks: "In Christianity, the body is thought of as the temple (in a strict architectural sense) of the soul." → Gagosian file, line 91. "disciplinary rituals of reproduction and heterosexual domesticity" → Gagosian file, line 77. "a parliament of (vulnerable) bodies living on planet Earth" and "a new understanding of community with all living creatures" → Artforum file, line 105. "The private residence has now become the center of the economy of tele-consumption and tele-production, but also the surveillance pod." → Artforum file, line 81. "The new frontier is your epidermis. The new Lampedusa is your skin." → Artforum file, line 55.
- Works: all four titles confirmed on publisher pages fetched and saved above.
- Who line: from the Gagosian bio (line 17 of that file) and the Artforum closing note (Libération columns 2013–18, line 107).
- Not confirmed / caveats: the Reina Sofía lecture date (March 2013) comes from the YouTube description, not from the saved subtitle text; the subtitles are a translation by the uploader, so the 00:21:39 quote is Preciado in translation. No agent or personal contact route found; publishers only.
