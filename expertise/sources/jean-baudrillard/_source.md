# Sources: Jean Baudrillard

Raw material for the unit card `expertise/unit/jean-baudrillard.md`. All fetched 2026-10-12. Tools: `fetch.py` (stdlib page-to-text), `yt-dlp` + `vtt2txt.py` (YouTube captions with timestamps).

## 2001-the-spirit-of-terrorism-le-monde-bloul.txt
- Title: "The Spirit of Terrorism" (L'Esprit du terrorisme). Author: Jean Baudrillard. Published in Le Monde, 2 November 2001. English translation by Rachel Bloul, posted on 16beavergroup.org on 15 August 2004. The translator's own notes appear in parentheses and footnote markers; they are hers, not his. The authorised English translation is Chris Turner's (Verso, 2002), not used here.
- URL: https://16beavergroup.org/articles/?p=818
- Obtained: `fetch.py`, cut from the title line to the last sentence of the essay; the poster's preamble is dropped.
- Saved: the full newspaper essay (about 5,000 words in this translation).

## 2006-the-pyres-of-autumn-nlr.txt
- Title: "The Pyres of Autumn". Author: Jean Baudrillard. Published in New Left Review 37, January–February 2006 (on the November 2005 riots). Free on the NLR site.
- URL: https://newleftreview.org/issues/ii37/articles/jean-baudrillard-the-pyres-of-autumn
- Obtained: `fetch.py`, cut from the first paragraph to the last; subscription chrome dropped. Saved: full essay (about 950 words).

## 2004-egs-violence-of-the-image-captions.txt
- Title: "Violence of the Image". Lecture in English by Baudrillard at the European Graduate School, 2004 (video title "Jean Baudrillard. Violence of the Image. 2004", uploaded 20 October 2015 by European Graduate School Video Lectures). YouTube auto-captions with `[HH:MM:SS]` timestamps; errors possible.
- URL: https://www.youtube.com/watch?v=vB3baRqDbyY
- Obtained: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o base <url>` then `python3 -I vtt2txt.py base.en.vtt out.txt`. Saved: whole track (about 4,700 words).

## 2020-the-system-of-objects-verso-extract.txt
- Verso blog post reproducing an extract from *The System of Objects* (trans. James Benedict): "The Modern Object Liberated in Its Function", "The Model Interior", "Walls and Daylight" and following. Publisher-released extract, about 2,600 words. No page numbers on the page.
- URL: https://versobooks.com/blogs/4630-the-system-of-objects Obtained: `fetch.py`. Saved: whole page.

## 1994-simulacra-and-simulation-umich-page.txt
- University of Michigan Press book page: *Simulacra and Simulation*, trans. Sheila Faria Glaser, December 1994, series The Body, In Theory. URL: https://press.umich.edu/Books/S/Simulacra-and-Simulation Obtained: `fetch.py`.

## 2017-symbolic-exchange-and-death-sage-page.txt
- SAGE book page: *Symbolic Exchange and Death*, Theory, Culture & Society series; the page dates this edition December 2016, Sage UK (ISBN 9781473907584; the card first said 2017, corrected on review 2026-10-12). The page does not state the 1993 first English edition or the translator. URL: https://us.sagepub.com/en-us/nam/symbolic-exchange-and-death/book243850 (now 301 to https://www.sagepub.com/en-us/nam/symbolic-exchange-and-death/book243850, which the card links) Obtained: `fetch.py`.

## 2020-the-system-of-objects-verso-page.txt
- Verso product page: *The System of Objects*, Radical Thinkers edition (2020). URL: https://www.versobooks.com/products/1554-the-system-of-objects Obtained: `fetch.py`. Short page; the edition details (James Benedict, March 2020) are on the blog extract page above.

## undated-verso-author-page.txt
- Verso author page: dates (1929–2007), Paris-X Nanterre from 1966, retired 1987. URL: https://versobooks.com/authors/114-jean-baudrillard Obtained: `fetch.py`.

## undated-marine-dupuis-baudrillard-delere-press.txt
- Delere Press contributor page for Marine Dupuis Baudrillard, used only for the contact route (Cool Memories association, contact@coolmemories.fr). URL: https://www.delerepress.com/contributors/marinedupuisbaudrillard Obtained: `fetch.py`.

## Not saved
- "The Violence of the Global", CTheory, 20 May 2003: https://journals.uvic.ca/index.php/ctheory/article/view/14558. The journal page gave only a stub and the HTML galley did not load; Wayback copies were rate-limited (429). Link only.
- "Violence of the Virtual and Integral Reality", IJBS 2.2, 2005: https://baudrillardstudies.ubishops.ca/violence-of-the-virtual-and-integral-reality/. Server returned 503 all day. Link only.
- Interview with Truls Lie, Oslo, 2000 (https://www.youtube.com/watch?v=y0D-f6nsH58): auto-captions downloaded, too rough to quote; not saved.
- IMEC (Institut Mémoires de l'Édition Contemporaine) holds the Baudrillard papers (deposited 2017, per a Columbia Global Centers announcement found by search); the IMEC fonds page was not fetched.

## Checks
Each quote on the card, the file, and the line where it appears (line numbers include the three header lines).
- "A sort of eternal flame, like that under the Arc de Triomphe, burning in honour of the Unknown Immigrant." → `2006-the-pyres-of-autumn-nlr.txt`, line 5.
- "Terrorism is an act that reintroduces an irreducible singularity in a generalized exchange system." → `2001-the-spirit-of-terrorism-le-monde-bloul.txt`, line 33.
- "death is the key (to the game) not only the brutal irruption of death in direct, in real time, but also the irruption of a more-than-real death: symbolic and sacrificial death" → same file, line 49 (preceded by "Therefore, here,").
- "The image and more generally the sphere of information is violent because what happens there is a murder of the real, the vanishing point of reality." → `2004-egs-violence-of-the-image-captions.txt`, lines 130–133, timestamps 00:06:50–00:07:00 (caption lines joined).
- "Perhaps they prefer to see cars burning than to dream of one day driving them." → `2006-the-pyres-of-autumn-nlr.txt`, line 17.
- How they work: "when they speed up, one must slow down" → Spirit file, line 15. "I apologize for my English" → EGS captions, line 5 (00:00:10).
- Hooks: "ninety cars on average are torched every night in this gentle France of ours" → Pyres file, line 5. "events strike" → Spirit file, line 13. "have been liberalized", "spaces of refuge" → `2020-the-system-of-objects-verso-extract.txt`, line 27. "in their very double-ness" → Spirit file, line 23. "And power is complicit with its own destruction." → Spirit file, line 25. "The spectacle of terrorism imposes the terrorism of the spectacle." → Spirit file, line 97.
- Works: all three titles confirmed on the publisher pages fetched and saved above.
- Who line: dates and Nanterre from the Verso author page; Le Monde and NLR from the saved essays.
- Review 2026-10-12: all 15 quoted strings re-grepped verbatim; EGS timestamp 00:06:50–00:07:00 matches. Works re-fetched: University of Michigan Press (December 1994), Verso (James Benedict, March 2020), SAGE (December 2016, see above). Links: CTheory page loads but is still a stub (HTML galley only); IJBS still 503; all others 200.
- Not confirmed / caveats: the Spirit of Terrorism quotes are in Rachel Bloul's unofficial translation, not Chris Turner's Verso text; wording will differ from the book. The EGS lecture year (2004) is the EGS channel's listing. Nothing on the card is left unconfirmed.
