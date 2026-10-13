# Sources: Hildegard von Bingen

Raw material for the unit card `expertise/unit/hildegard-von-bingen.md`. Her own words are quoted from a public-domain 1917 English translation and, for one short line, from the copyrighted 1994 Baird–Ehrman translation of a letter.

## 1917-singer-scientific-views-and-visions-of-hildegard.txt
- **Title:** The Scientific Views and Visions of Saint Hildegard (1098-1180), in *Studies in the History and Method of Science*, vol. 1, pp. 1–55
- **Author:** Charles Singer (translating Hildegard from Migne, *Patrologia Latina* vol. 197)
- **Date:** 1917, Oxford, Clarendon Press
- **Where published:** Project Gutenberg #46572 (public domain)
- **URL:** https://www.gutenberg.org/ebooks/46572 (text: https://www.gutenberg.org/cache/epub/46572/pg46572.txt)
- **How obtained:** `curl -sL -o singer1917.txt "https://www.gutenberg.org/cache/epub/46572/pg46572.txt"`, then cut to the Hildegard essay (Gutenberg lines 573–2562) plus its footnotes [1]–[120]
- **What is saved:** the whole essay and its footnotes (public domain, saved in full). Singer's footnotes give the Migne column for each passage he translates.

## 1147-letter-to-bernard-of-clairvaux-epistolae.txt
- **Title:** A letter from Hildegard of Bingen (1146-47) to Bernard of Clairvaux (Epistolarium ep. 1)
- **Author:** Hildegard; Latin ed. Van Acker (CCCM 91, 1991); English trans. Joseph L. Baird and Radd K. Ehrman, *The Letters of Hildegard of Bingen* vol. I (Oxford UP, 1994), pp. 27–28
- **Date:** 1146–47
- **Where published:** Epistolae: Medieval Women's Latin Letters, Columbia University
- **URL:** https://epistolae.ctl.columbia.edu/letter/1188.html
- **How obtained:** `python3 -I fetch.py "https://epistolae.ctl.columbia.edu/letter/1188.html" out.txt`
- **What is saved:** the page as published: the English translation (about 700 words) and the Latin original. The translation is copyrighted: short quotes only, with page.

## 1996-halsall-fordham-life-and-works.txt
- **Title:** The Life and Works of Hildegard von Bingen (1098-1179)
- **Author:** Kristina Lerman (page credit: created 15 February 1995, last modified 24 May 1995). Paul Halsall edits the Internet Medieval Sourcebook that hosts it (site note May 2023; site revision 2026). The card cites it as (Lerman); the file name keeps "halsall" for the site.
- **Date:** 1995 (site revised 2026)
- **Where published:** Fordham University, Internet Medieval Sourcebook
- **URL:** https://sourcebooks.fordham.edu/med/hildegarde.asp (the earlier URL https://sourcebooks.web.fordham.edu/halsall/med/hildegarde.asp redirects here)
- **How obtained:** `python3 -I fetch.py "https://sourcebooks.web.fordham.edu/halsall/med/hildegarde.asp" out.txt`
- **What is saved:** the biography and bibliography (about 2,800 words). Context only; not Hildegard's words.

## Pages fetched for the Works and Contact lines (not saved as text)
- Open Library, *Scivias*, trans. Hart and Bishop, Paulist Press, August 1990: https://openlibrary.org/books/OL7975073M
- Open Library, *The Letters of Hildegard of Bingen* vol. I, Oxford University Press, 25 August 1994: https://openlibrary.org/books/OL7387464M
- Penn Libraries record, *Ordo virtutum*, ed. Audrey Ekdahl Davidson, 1985 (call number M2002.H62 O7 1985): https://find.library.upenn.edu/catalog/99975473503681
- Open Library, *Hildegard von Bingen's Physica*, trans. Throop, Healing Arts Press, 1 September 1998: https://openlibrary.org/books/OL8233138M
- IMSLP, *Ordo virtutum* (Davidson edition, Kalamazoo: Medieval Institute Publications, 1985): https://imslp.org/wiki/Ordo_virtutum_(Hildegard)
- Abtei St. Hildegard, Impressum (addresses and emails): https://abtei-st-hildegard.de/impressum/
- Publisher pages for Paulist Press, Oxford University Press and Healing Arts Press returned HTTP 403 to the fetch tool; library records are linked instead.

## Checks
Every quote on the card, where it sits:
- "I beheld neither in sleep, nor in dream, nor in madness, nor with my carnal eyes, nor with the ears of the flesh, nor in hidden places; but wakeful, alert, with the eyes of the spirit" → `1917-singer-...txt`, lines 1857–1860 (section X; Singer's note [117]: Migne col. 384, the *Scivias* prefatory declaration)
- "I saw a great star most splendid and beautiful, and with it an exceeding multitude of falling sparks which with the star followed southward." → same file, lines 1883–1885 (note [118]: *Scivias* lib. iii, vis. 1; Migne col. 565)
- "I saw in the bosom of the form the appearance of a disk of like sort to that which twenty-eight years before I had seen in the third vision, set forth in my book of *Scivias*" → same file, lines 1126–1129 (note [74]: Migne col. 751, *Liber Divinorum Operum*; the saved text marks the italic title as `_Scivias_`)
- "I saw that the upper fiery firmament was stirred, so that as it were ashes were cast therefrom to earth, and they produced rashes and ulcers in men and animals and fruits." → same file, lines 1223–1225 (note [78]: Migne col. 807, *Liber Divinorum Operum*)
- "a vision seen not with my fleshly eyes but only in my spirit" → `1147-letter-to-bernard-of-clairvaux-epistolae.txt`, line 21 (Baird–Ehrman, *Letters* I, pp. 27–28)

Supporting references: Epistolae line 22 ("untaught and untrained"), line 24 ("whether I should speak these things openly or keep my silence"); Singer line 1235 ("resisted these ashes and vapours"), line 1810 ("Arise! for it is dawn"), line 83 (Rupertsberg); Lerman (Halsall file) line 87 (Volmar); Singer note [32] (line 2137: visions "dictated by Hildegard and were latinized by a secretary", cited from section V, line 529); lines 120–146 (Bernard, Pope Eugenius, move from Disibodenberg to Bingen c. 1150), lines 149–151 (*Ordo Virtutum* performed in her own convent).

Not confirmed / caveats:
- The attribution of Migne columns to works (col. 384 = *Scivias* preface; cols. 751 and 807 = *Liber Divinorum Operum*) follows Singer's footnotes and the standard layout of PL 197; the Latin was not checked against a modern edition.
- Singer's translations are 1917 English and differ in wording from Hart–Bishop (1990). Page numbers in Hart–Bishop are not given because that book was not fetched.
- Review 2026-10-12 (evening): openlibrary.org refused connections, so the three Open Library links could not be reopened; the editions were confirmed instead by library and publisher records found by web search (Paulist Press 1990; Oxford University Press 1994, ISBN 0-19-508937-5; Healing Arts Press, 1 September 1998, ISBN 9780892816613). The Penn record for *Ordo virtutum* reopened and gives 1985 in brackets (not printed on the title page).
- No public-domain English translation of the full *Scivias* was found; the only complete free English text on archive.org is an AI translation (2025) and was not used.
